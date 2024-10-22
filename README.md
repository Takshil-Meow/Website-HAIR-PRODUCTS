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
                    <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcQB0oJz5jJiPJQzYncs8EJWDC6n8KYgbJsqrh1VROo0VN7aOGeispfF7QjyDOUYD1lNGhTzlYnx0vUIAu9IYQZN8HIiC8ECMp7jL5LianEzqKdcJd9eSZdYHw" alt="Tea Tree Hair Oil">
                    <h3>Tea Tree Hair Oil</h3>
                    <p>Controls dandruff and itchiness.</p>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="product-card">
    <img src="https://via.placeholder.com/300x200?text=Shampoo+1" alt="Shampoo 1">
    <h3>Shampoo 1</h3>
    <p>Perfect for all hair types.</p>
    <button>Buy Now</button>
</div>
<div class="product-card">
    <img src="https://via.placeholder.com/300x200?text=Shampoo+2" alt="Shampoo 2">
    <h3>Shampoo 2</h3>
    <p>Deep cleansing formula.</p>
    <button>Buy Now</button>
</div>
<div class="product-card">
    <img src="https://via.placeholder.com/300x200?text=Shampoo+3" alt="Shampoo 3">
    <h3>Shampoo 3</h3>
    <p>Moisturizing and nourishing.</p>
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
