
-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Hassan's Clothing Store">
    <title>Hassan's Clothing</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        section {
            margin-bottom: 40px;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product-item {
            background-color: white;
            padding: 20px;
            border: 1px solid #ddd;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product-item img {
            max-width: 100%;
            height: auto;
        }
        .product-item h3 {
            font-size: 1.5em;
            margin: 15px 0 10px;
        }
        .product-item p {
            color: #666;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Hassan's Clothing Store</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#collections">Collections</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="collections">
            <h2>Our Latest Collections</h2>
            <div class="product-grid">
                <div class="product-item">
                    <img src="https://via.placeholder.com/250" alt="Product 1">
                    <h3>Stylish Jacket</h3>
                    <p>Perfect for the modern trendsetter. $120</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/250" alt="Product 2">
                    <h3>Casual Hoodie</h3>
                    <p>Stay cozy in this classic hoodie. $80</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/250" alt="Product 3">
                    <h3>Elegant Dress</h3>
                    <p>Perfect for any occasion. $150</p>
                </div>
                <div class="product-item">
                    <img src="https://via.placeholder.com/250" alt="Product 4">
                    <h3>Denim Jeans</h3>
                    <p>Classic fit with a modern twist. $95</p>
                </div>
            </div>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Welcome to Hassan's Clothing Store! We are dedicated to providing high-quality, stylish, and affordable clothing for every occasion. Whether you're looking for casual wear, formal attire, or the latest trends, we've got something for everyone. Our collections are carefully curated to ensure that you find the perfect outfit to express your unique style.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Want to get in touch? Drop us an email at <strong>info@hassansclothing.com</strong> or follow us on social media for the latest updates and promotions.</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Hassan's Clothing Store. All Rights Reserved.</p>
    </footer>

</body>
</html>
