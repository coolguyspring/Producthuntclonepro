<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Hunt Clone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #ff4500;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .product {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid #ddd;
        }
        .product:last-child {
            border-bottom: none;
        }
        .product img {
            max-width: 50px;
            margin-right: 20px;
        }
        .product-info {
            flex: 1;
        }
        .product-title {
            font-size: 18px;
            margin: 0;
        }
        .product-description {
            margin: 5px 0;
            color: #666;
        }
        .upvote {
            display: flex;
            align-items: center;
            color: #ff4500;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Product Hunt Clone</h1>
    </header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/50" alt="Product Image">
            <div class="product-info">
                <h2 class="product-title">Product Name</h2>
                <p class="product-description">I can explain the description about any product.</p>
            </div>
            <div class="upvote">
                <span>⬆️</span>
                <span>100</span>
            </div>
        </div>
        <!-- Add more products here -->
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Hunt Features</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .feature {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .feature img {
            width: 50px;
            height: 50px;
            border-radius: 10px;
            margin-right: 20px;
        }
        .feature-info {
            flex-grow: 1;
        }
        .feature-info h2 {
            margin: 0;
            font-size: 18px;
        }
        .feature-info p {
            margin: 5px 0;
            color: #666;
        }
        .upvote-button {
            background-color: #ff4500;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        .upvote-button.upvoted {
            background-color: #ccc;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="feature">
            <img src="https://via.placeholder.com/50" alt="Feature Image">
            <div class="feature-info">
                <h2>Feature Name</h2>
                <p>Feature description goes here.</p>
            </div>
            <button class="upvote-button" onclick="upvote(this)">Upvote</button>
        </div>
        <!-- Repeat the above block for more features -->
    </div>

    <script>
        function upvote(button) {
            button.classList.toggle('upvoted');
            button.textContent = button.classList.contains('upvoted') ? 'Upvoted' : 'Upvote';
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Hunt Features</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .feature {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 10px;
            transition: box-shadow 0.3s ease;
        }
        .feature:hover {
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        .feature img {
            width: 50px;
            height: 50px;
            border-radius: 10px;
            margin-right: 20px;
        }
        .feature-info {
            flex-grow: 1;
        }
        .feature-info h2 {
            margin: 0;
            font-size: 18px;
        }
        .feature-info p {
            margin: 5px 0;
            color: #666;
        }
        .upvote-button {
            background-color: #ff4500;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .upvote-button.upvoted {
            background-color: #ccc;
        }
        .upvote-button:hover {
            background-color: #ff5733;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="feature">
            <img src="https://via.placeholder.com/50" alt="Feature Image">
            <div class="feature-info">
                <h2>Feature Name</h2>
                <p>Feature description goes here.</p>
            </div>
            <button class="upvote-button" onclick="upvote(this)">Upvote</button>
        </div>
        <!-- Repeat the above block for more features -->
    </div>

    <script>
        function upvote(button) {
            button.classList.toggle('upvoted');
            button.textContent = button.classList.contains('upvoted') ? 'Upvoted' : 'Upvote';
        }
    </script>
</body>
</html>
