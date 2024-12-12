<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Potato Paradise</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        header {
            background-color: #ffcc33;
            padding: 20px;
            text-align: center;
            color: #333;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
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

        .hero {
            text-align: center;
            padding: 50px 20px;
            background: url('https://via.placeholder.com/1500x500') no-repeat center center/cover;
            color: white;
        }

        .hero h2 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 1.5em;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
            text-align: center;
        }

        .product img {
            max-width: 100%;
            border-radius: 5px;
        }

        .product h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .product p {
            color: #666;
        }

        .product button {
            background-color: #ffcc33;
            border: none;
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            border-radius: 5px;
        }

        .product button:hover {
            background-color: #e6b800;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Potato Paradise</h1>
        <p>Your one-stop shop for all things potato!</p>
    </header>
    <nav>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h2>Fresh Potatoes Delivered to Your Doorstep</h2>
        <p>Experience the finest selection of farm-fresh potatoes.</p>
    </div>
    <section id="products" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Single Potato">
            <h3>Single Potato</h3>
            <p>Fresh and handpicked. £0.50 each.</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Sweet Potato">
            <h3>Sweet Potato</h3>
            <p>Perfect for a healthier choice. £1.00 each.</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Potato Bundle">
            <h3>Potato Bundle</h3>
            <p>Includes 5 golden, 5 russet, and 5 red potatoes. £6.00 per bundle.</p>
            <button>Add to Cart</button>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Potato Paradise. All rights reserved. Serving the UK only.</p>
    </footer>
</body>
</html>

