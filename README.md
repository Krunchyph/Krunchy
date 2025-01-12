<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krunchy - Coco Krunch with Liquid Chocolate</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        header {
            background-color: #ff9900;
            padding: 10px 20px;
            color: white;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 10px;
            padding: 15px;
            background: white;
            margin-bottom: 20px;
        }
        .product img {
            max-width: 100%;
            border-radius: 10px;
        }
        .product h2 {
            color: #333;
        }
        .product p {
            color: #555;
        }
        .product select, .product input {
            margin: 10px 0;
            padding: 5px;
            width: 100%;
        }
        .btn {
            background-color: #ff9900;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
        }
        .btn:hover {
            background-color: #cc7a00;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #222;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Krunchy!</h1>
        <p>Delicious Coco Krunch with Liquid Chocolate</p>
    </header>

    <div class="container">
        <!-- Product Section -->
        <div class="product">
            <img src="example.jpg" alt="Krunchy Coco Krunch">
            <h2>Krunchy Jar</h2>
            <p>Our signature coco krunch with rich liquid chocolate filling. A perfect treat for any occasion!</p>

            <label for="size">Choose Size:</label>
            <select id="size">
                <option value="small">Small - €5</option>
                <option value="medium">Medium - €10</option>
                <option value="large">Large - €15</option>
            </select>

            <label for="flavor">Choose Flavor:</label>
            <select id="flavor">
                <option value="milk">Milk Chocolate</option>
                <option value="dark">Dark Chocolate</option>
                <option value="white">White Chocolate</option>
            </select>

            <button class="btn">Add to Cart</button>
        </div>

        <!-- Summary Section -->
        <div class="summary">
            <h2>About Krunchy</h2>
            <p>Krunchy combines the satisfying crunch of coco krunch with a luscious liquid chocolate filling, bringing joy in every bite. Available in multiple sizes and flavors to suit every taste!</p>
        </div>

        <!-- Payment and Shipping Section -->
        <div class="shipping">
            <h2>Payment & Shipping</h2>
            <p>Payment Methods: Credit/Debit Card, PayPal, Bank Transfer</p>
            <p>Modes of Shipment: Standard Delivery (3-5 days), Express Delivery (1-2 days)</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Krunchy. All rights reserved.</p>
    </footer>
</body>
</html>
