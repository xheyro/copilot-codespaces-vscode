<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eyro Apparel</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>Eyro Apparel</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to Eyro Apparel</h2>
            <p>Your destination for affordable, stylish fashion.</p>
            <a href="#shop" class="cta-button">Shop Now</a>
        </div>
    </section>

    <!-- Product Section -->
    <section id="shop" class="product-section">
        <h2>Our Collections</h2>
        <div class="product-container">
            <div class="product">
                <img src="https://via.placeholder.com/250" alt="Top">
                <h3>Trendy Tops</h3>
                <p>Comfortable, stylish tops for every occasion.</p>
                <a href="#" class="cta-button">Shop Now</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250" alt="Bottoms">
                <h3>Stylish Bottoms</h3>
                <p>Perfect fits and fashionable designs for every day.</p>
                <a href="#" class="cta-button">Shop Now</a>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250" alt="Accessories">
                <h3>Accessories</h3>
                <p>Add the finishing touch to any outfit with our accessories.</p>
                <a href="#" class="cta-button">Shop Now</a>
            </div>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about-us">
        <h2>About Eyro Apparel</h2>
        <p>At Eyro Apparel, we believe fashion should be affordable for everyone. Our mission is to bring you the latest trends, high-quality designs, and comfortable apparel at prices that won't break the bank.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or need assistance, feel free to reach out.</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Eyro Apparel. All Rights Reserved.</p>
    </footer>

</body>
</html>
