# WELLCOME TO EVERGREEN HERBS
# GROWING THE FUTURE













<div class="hero-container">
     <img width="1264" height="842" alt="image" src="https://github.com/user-attachments/assets/b481738a-af5b-4736-a6c5-396c5df34d23" /> 
  <div class="header-overlay">
    <h1>PACKING <span>& GRADING</span></h1>
    <div class="divider-curve"></div>
    <p class="tagline">Ensuring Quality & Freshness</p>
  </div>
</div
  

  <section id="home" className="text-center py-20 px-6 bg-gradient-to-r from-green-100 to-green-50">
    <motion.h1 
      initial={{ opacity: 0, y: -20 }}
      animate={{ opacity: 1, y: 0 }}
      className="text-4xl md:text-5xl font-bold mb-4">
      Fresh Herbs, Naturally Grown
    </motion.h1>
    <p className="mb-6 text-lg">Premium organic herbs delivered straight to your destination.</p>
    <Button className="rounded-2xl px-6 py-2">Shop Now</Button
                                                        
  <section id="products" className="p-10">
    <h1 className="text-3xl font-semibold text-center mb-10">Our Products</h1>
    <div className="grid md:grid-cols-3 gap-6">
      {["Chives", "Mint", "Rosemary", "Thyme", "Coriander", "Oregano"]
      <Card key={index} className="rounded-2xl shadow-md hover:shadow-xl transition">
          <CardContent className="p-6 text-center">
            <div className="text-3x2 mb-2">🌱</div>
            <h3 className="text-xl font-medium">{item}</h3>
            <p className="text-sm mt-2">Fresh and organic.</p>
            <Button className="mt-4">Buy</Button>
          </CardContent>
        </Card>
      ))}
    </div>
    
  <section id="about" className="bg-white p-10 text-center">
    <h2 className="text-3xl font-semibold mb-4">About Us</h2>
    <p className="max-w-2xl mx-auto">
     Evergreen Herbs Co. is dedicated to providing high-quality organic herbs grown sustainably. 
      We work with local farmers to ensure freshness and quality in every product.
    </p>
  </section>

  <section id="contact" className="p-10 text-center">
    <h2 className="text-3xl font-semibold mb-4">Contact Us</h2>
    <p>Email: evergreenherbs@gmail.com</p>
    <p>Phone: +254 796 13367</p>
    <Button className="mt-4">Send Message</Button>
  </section>

  <footer className="text-center p-6 bg-gray-900 text-white mt-10">
    <p>© 2026 Evergreen Herbs Grading Co. All rights reserved.</p>
  </footer>
</div>
