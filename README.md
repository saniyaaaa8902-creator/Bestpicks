<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Best Picks</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f5f5;
        }
        header {
            background: #111;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background: #222;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            padding: 80px 20px;
            text-align: center;
            background: linear-gradient(135deg, #ff7e5f, #feb47b);
            color: #fff;
        }
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 40px 20px;
        }
        .card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Best Picks</h1>
        <p>Your personal collection of top choices</p>
    </header>

    <nav>
        <a href="#products">Products</a>
        <a href="#reviews">Reviews</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <h2>Welcome to Best Picks</h2>
        <p>Discover the best products, ideas, and recommendations picked just for you.</p>
    </section>

    <div class="container">
        <div class="card" id="products">
            <h3>Top Products</h3>
            <p>Add your best picks here. You can include images, descriptions, or affiliate links.</p>
        </div>

        <div class="card" id="reviews">
            <h3>Reviews</h3>
            <p>Write your honest reviews and opinions about products you like.</p>
        </div>

        <div class="card" id="contact">
            <h3>Contact</h3>
            <p>Email: yourname@example.com</p>
        </div>
    </div>

    <footer>
        <p>© 2025 Best Picks by You</p>
    </footer>
</body>
</html>
