<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KeshRatan - Hair Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="home">
            <h1>Welcome to KeshRatan</h1>
            <p>Your destination for natural hair care products.</p>
            <button onclick="document.getElementById('products').scrollIntoView();">Explore Our Products</button>
        </section>
        <section id="products">
            <h2>Our Products</h2>
            <div class="product-grid">
                <div class="product-card">
                    <img src="https://www.pepperhub.in/wp-content/uploads/2023/01/Coconut-oil-.5L.webp">
                    <h3>Coconut Hair Oil</h3>
                    <p>Nourishes and moisturizes dry hair.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-card">
                    <img src="https://latourangelle.com/cdn/shop/articles/32_1200x1200.jpg?v=1647297916">
                    <h3>Argan Hair Oil</h3>
                    <p>Hydrates and protects damaged hair.</p>
                    <button>Buy Now</button>
                </div>
                <div class="product-card">
                    <img src="https://passionindulge.com/cdn/shop/files/Tea_Tree_ESSENTIAL_OIL_95146d40-8bef-4ebd-944b-295c32ef9344.jpg?v=1721891953&width=1946">
                    <h3>Tea Tree Hair Oil</h3>
                    <p>Controls dandruff and itchiness.</p>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="product-card">
    <img src="https://cdn.shopify.com/s/files/1/0556/0385/5430/files/Shampoo-Coconut_Water___Aloevera-A__content_01.jpg">
    <h3>Aloe-vera</h3>
    <p>Perfect for all hair types.</p>
    <button>Buy Now</button>
</div>
<div class="product-card">
    <img src="https://images.jdmagicbox.com/quickquotes/images_main/indrani-aritha-amla-shikakai-shampoo-2022839706-9w5wrwme.jpg">
    <h3>Aritha Sampoo</h3>
    <p>Deep cleansing formula.</p>
    <p>Hair Growth increase.</p>
    <button>Buy Now</button>
</div>
<div class="product-card">
    <img src="https://vijohnkart.com/cdn/shop/files/8900021669816_4_800x.jpg?v=1712927505">
    <h3>Onion Shampoo</h3>
    <p>Moisturizing and nourishing.</p>
    <p>Dandruff Free Hair.</p>
    <button>Buy Now</button>
</div>
        </section>
        <section id="about">
            <h2>About Us</h2>
            <p>Keshratan is dedicated to providing natural hair care products that nourish and protect your hair. Our products are made with high-quality ingredients and are free from harsh chemicals.</p>
        </section>
        <section id="contact">
            <h2>Contact Us:9377677836</h2>
            <p>Get in touch with us to learn more about our products or to place an order.</p>
            <form>
                <input type="text" placeholder="Name" required>
                <input type="email" placeholder="Email" required>
                <textarea placeholder="Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Keshratan. All rights reserved.</p>
    </footer>
</body>
</html>
