<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BHARGAV ART STORES</title>
    <style>
        body, header, nav, footer {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        header, nav, footer {
            background-color: #add8e6;
            color: #fff;
            text-align: center;
        }

        header, nav {
 background-color: #c46210;
            color: #fff;
            padding: 1em;
            text-align: center;
            
        }

        nav a {
            padding: 0.5em 1em;
            text-decoration: none;
            color: #fff;
        }

        .cart-symbol::before {
            content: "\1F6D2"; /* Unicode for cart symbol */
            font-size: 1.5em;
            margin-right: 5px;
        }

        .refresh-symbol::before {
            content: "\21BB"; /* Unicode for refresh symbol */
            font-size: 1.5em;
            margin-right: 5px;
        }

        main {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .product-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            margin: 16px;
            padding: 16px;
            width: 200px;
            text-align: center;
            background-color: #fff;
        }

        .product-card img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }

        footer {
            padding: 1em;
        }
    </style>
</head>
<body>
    <header>
        <h1>BHARGAV ART STORE</h1>
    </header>
    <nav>
        <a href="#"><span class="cart-symbol"></span> Cart</a>
        <a href="#"><span class="refresh-symbol"></span> Refresh</a>
        <a href="#">Categories</a>
        <a href="#">Deals</a>
        <a href="#">Contact</a>
    </nav>
    <main>
        <div class="product-card">
            <img src="C:\Users\bharg\OneDrive\Desktop\art2.jpg" alt="Product 1">
            <h2>Product 1</h2>
            <p>Acrylic Painting</p>
            <p>1299 Rs</p>
            <button>Add to Cart</button>
        </div>
        <div class="product-card">
            <img src="C:\Users\bharg\OneDrive\Desktop\art1_20220707142040753_save.jpg" alt="Product 2">
            <h2>Product 2</h2>
            <p>Colour Pencil</p>
            <p>799 Rs</p>
            <button>Add to Cart</button>
        </div>
<div class="product-card">
            <img src="C:\Users\bharg\OneDrive\Desktop\art4.jpg">
            <h2>Product 3</h2>
            <p>Pencil Art </p>
            <p>699 Rs</p>
            <button>Add to Cart</button>
        </div>

    </main>
    <footer>
        <p>&copy; 2024 Bhargav ART STORE. All rights reserved.</p>
    </footer>
</body>
</html>
