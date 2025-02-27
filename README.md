# Vidhi-shop- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Product Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product {
            display: flex;
            margin-bottom: 20px;
        }
        .product img {
            max-width: 200px;
            margin-right: 20px;
        }
        .product-info {
            flex: 1;
        }
        .product-info h2 {
            margin-top: 0;
        }
        .product-info p {
            margin: 10px 0;
        }
        .product-info .price {
            font-size: 1.5em;
            color: #e67e22;
        }
        .product-info button {
            background-color: #e67e22;
            color: #fff;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 1em;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>My E-Commerce Store</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">About Us</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <div class="product-info">
                <h2>Product Name</h2>
                <p>Product description goes here. This is a brief description of the product.</p>
                <p class="price">$19.99</p>
                <button>Add to Cart</button>
            </div>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <div class="product-info">
                <h2>Product Name</h2>
                <p>Product description goes here. This is a brief description of the product.</p>
                <p class="price">$29.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 My E-Commerce Store. All rights reserved.</p>
    </footer>

</body>
</html>
