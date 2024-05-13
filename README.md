<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website Title</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
    <style>
        /* Simple CSS for basic styling, customize as needed */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9; /* Light grey background */
            color: #333; /* Dark text color */
        }
        header {
            background-color: #66c3ff; /* Light blue header */
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        main {
            padding: 20px;
            text-align: center; /* Center main content */
        }
        section {
            margin-bottom: 30px;
            background-color: #fff; /* White background for sections */
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center; /* Center text content within sections */
        }
        footer {
            background-color: #66c3ff; /* Light blue footer */
            color: #fff;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Button styles */
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #66c3ff; /* Light blue button */
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: #3f8fdd; /* Darker blue on hover */
        }
        /* CSS for Gallery Images */
        .gallery-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .gallery-item img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .gallery-item img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Your Website</h1>
    <nav>
        <ul>
            <li><a href="#home" onclick="scrollToSection('home')">Home</a></li>
            <li><a href="#gallery" onclick="scrollToSection('gallery')">Gallery</a></li>
            <li><a href="#faq" onclick="scrollToSection('faq')">FAQ</a></li>
            <li><a href="#services" onclick="scrollToSection('services')">Services</a></li> <!-- New button -->
            <li><a href="#about" onclick="scrollToSection('about')">About Us</a></li> <!-- New button -->
            <li><a href="#contact" onclick="scrollToSection('contact')">Contact</a></li> <!-- New button -->
        </ul>
    </nav>
</header>

<main>
    <section id="home">
        <h2>Home</h2>
        <p>This is your homepage content.</p>
        <a href="#gallery" class="button">Explore Gallery</a> <!-- New button -->
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <div class="gallery-container">
            <div class="gallery-item"><img src="https://img.hotimg.com/received_3724761744470788.png"t="received_3724761744470788.png" border="0" />Leche Flan is a popular Filipino dessert that's similar to crème caramel or caramel custard.</p>
            </div>
            <div class="gallery-item"><img src="https://img.hotimg.com/received_717282333724437.png" alt="Image 2">
            <p>"Knickerbocker" refers to a popular fruit cocktail dessert known as "Knickerbocker Glory. </p></div>
            <div class="gallery-item"><img src="https://img.hotimg.com/received_1191023415599401.png" alt="Image 3"
            <p>The curacha is also known as the spanner crab or red frog crab. It's distinct for its large size and unique appearance, with broad claws and a reddish coloration</p></div>
            <!-- Add more gallery items as needed -->
        </div>
        <a href="#home" class="button">Back to Home</a> <!-- New button -->
    </section>

    <section id="faq">
        <h2>FAQ</h2>
        <p>Find answers to frequently asked questions.</p>
        <a href="#contact" class="button">Contact Us</a> <!-- New button -->
    </section>

    <section id="services">
        <h2>Services</h2>
        <p>Discover our catering and delivery services.</p>
        <a href="#contact" class="button">Contact Us</a> <!-- New button -->
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Learn m
