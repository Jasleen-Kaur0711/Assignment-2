<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Café Delight</title>
    <style>
        /* Reset some basic styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body and font styles */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
        }

        /* Header */
        header {
            background: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
        }

        /* Navigation */
        nav {
            text-align: center;
            margin-top: 10px;
        }

        nav a {
            text-decoration: none;
            color: #fff;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            color: #ff6347;
        }

        /* About Us Section */
        #about {
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            text-align: center;
        }

        /* Menu Section */
        #menu {
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            text-align: center;
        }

        .menu-item {
            display: inline-block;
            width: 30%;
            margin: 10px;
            background-color: #f9f9f9;
            padding: 15px;
            border-radius: 8px;
        }

        .menu-item h3 {
            color: #333;
        }

        .menu-item p {
            margin: 5px 0;
        }

        /* Contact Section */
        #contact {
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            text-align: center;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Café Delight</h1>
        <nav>
            <a href="#about">About Us</a>
            <a href="#menu">Menu</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- About Us Section -->
    <section id="about">
        <h2>Welcome to Café Delight</h2>
        <p>We serve the finest coffee, pastries, and snacks in town. Come for the taste, stay for the ambiance!</p>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <h3>Coffee</h3>
            <p>Espresso, Latte, Cappuccino, Americano</p>
            <p>Price: $3 - $5</p>
        </div>
        <div class="menu-item">
            <h3>Pastries</h3>
            <p>Croissants, Muffins, Donuts, Bagels</p>
            <p>Price: $2 - $4</p>
        </div>
        <div class="menu-item">
            <h3>Snacks</h3>
            <p>Sandwiches, Salads, Chips</p>
            <p>Price: $4 - $7</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@cafedelight.com</p>
        <p>Phone: +1 (555) 123-4567</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Café Delight. All rights reserved.</p>
    </footer>

</body>
</html>

