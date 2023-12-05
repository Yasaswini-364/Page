DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Page</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
        }
        .product-container {
            display: flex;
            justify-content: space-around;
            margin: 20px;
        }
        .product-info {
            text-align: center;
        }
        .add-to-cart {
            cursor: pointer;
            background-color: #4caf50;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<div class="product-container">
    <div class="product-info">
        <img src="product_image.jpg" alt="Product Image" width="200">
        <h2>Product Name</h2>
        <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <p>Price: $19.99</p>
        <button class="add-to-cart" onclick="addToCart()">Add to Cart</button>
    </div>
</div>

<script>
    // JavaScript for shopping cart functionality
    let cartItems = 0;

    function addToCart() {
        cartItems++;
        alert("Product added to cart. Total items in cart: " + cartItems);
    }
</script>
