# BLUESTAR
import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { motion } from "framer-motion";

export default function CompanyWebsite() { return ( <div className="min-h-screen bg-gray-50 text-gray-800"> {/* Header */} <header className="flex items-center justify-between p-6 shadow-md bg-white"> <div className="text-2xl font-bold">🌿 GreenLeaf Co.</div> <nav className="space-x-6"> <a href="#home" className="hover:text-green-600">Home</a> <a href="#products" className="hover:text-green-600">Products</a> <a href="#about" className="hover:text-green-600">About</a> <a href="#contact" className="hover:text-green-600">Contact</a> </nav> </header>

{/* Hero Section */}
  <section id="home" className="text-center py-20 px-6 bg-gradient-to-r from-green-100 to-green-50">
    <motion.h1 
      initial={{ opacity: 0, y: -20 }}
      animate={{ opacity: 1, y: 0 }}
      className="text-4xl md:text-5xl font-bold mb-4">
      Fresh Herbs, Naturally Grown
    </motion.h1>
    <p className="mb-6 text-lg">Premium organic herbs delivered straight to your kitchen.</p>
    <Button className="rounded-2xl px-6 py-2">Shop Now</Button>
  </section>

  {/* Products Section */}
  <section id="products" className="p-10">
    <h2 className="text-3xl font-semibold text-center mb-10">Our Products</h2>
    <div className="grid md:grid-cols-3 gap-6">
      {["Chives", "Mint", "Rosemary", "Thyme", "Coriander", "Oregano"].map((item, index) => (
        <Card key={index} className="rounded-2xl shadow-md hover:shadow-xl transition">
          <CardContent className="p-6 text-center">
            <div className="text-2xl mb-2">🌱</div>
            <h3 className="text-xl font-medium">{item}</h3>
            <p className="text-sm mt-2">Fresh and organic {item.toLowerCase()}.</p>
            <Button className="mt-4">Buy</Button>
          </CardContent>
        </Card>
      ))}
    </div>
  </section>

  {/* About Section */}
  <section id="about" className="bg-white p-10 text-center">
    <h2 className="text-3xl font-semibold mb-4">About Us</h2>
    <p className="max-w-2xl mx-auto">
      GreenLeaf Co. is dedicated to providing high-quality organic herbs grown sustainably. 
      We work with local farmers to ensure freshness and quality in every product.
    </p>
  </section>

  {/* Contact Section */}
  <section id="contact" className="p-10 text-center">
    <h2 className="text-3xl font-semibold mb-4">Contact Us</h2>
    <p>Email: info@greenleafco.com</p>
    <p>Phone: +254 700 000000</p>
    <Button className="mt-4">Send Message</Button>
  </section>

  {/* Footer */}
  <footer className="text-center p-6 bg-gray-900 text-white mt-10">
    <p>© 2026 GreenLeaf Co. All rights reserved.</p>
  </footer>
</div>

); }
