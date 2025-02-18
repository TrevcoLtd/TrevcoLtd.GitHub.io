<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trevco Engineering</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 0.5rem 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .container {
            padding: 2rem;
            text-align: center;
        }
        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .service {
            background: white;
            padding: 1rem;
            margin: 1rem;
            width: 250px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Trevco Engineering</h1>
        <p>Structural | Geotechnical | Civil | Transport Engineering</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="about">
        <h2>About Us</h2>
        <p>Trevco Engineering provides expert solutions in structural, geotechnical, civil, and transport engineering.</p>
    </div>
    <div class="container" id="services">
        <h2>Our Services</h2>
        <div class="services">
            <div class="service">
                <h3>Structural Engineering</h3>
                <p>We provide innovative structural solutions for various building projects.</p>
            </div>
            <div class="service">
                <h3>Geotechnical Engineering</h3>
                <p>Expert analysis and recommendations for soil and foundation conditions.</p>
            </div>
            <div class="service">
                <h3>Civil Engineering</h3>
                <p>Infrastructure and land development solutions to meet modern needs.</p>
            </div>
            <div class="service">
                <h3>Transport Engineering</h3>
                <p>Specialized transport assessments and traffic impact analysis.</p>
            </div>
        </div>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@trevcoengineering.com</p>
        <p>Phone: +64 123 456 789</p>
    </div>
    <footer>
        <p>&copy; 2025 Trevco Engineering. All rights reserved.</p>
    </footer>
</body>
</html>
