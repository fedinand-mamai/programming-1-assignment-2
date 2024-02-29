//html 
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travelsafi Adventures</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Travelsafi Adventures</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="destinations.html">Destinations</a></li>
                <li><a href="packages.html">Packages</a></li>
                <li><a href="testimonials.html">Testimonials</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="hero">
            <h2>Travel in Style with Travelsafi adventures</h2>
            <p>Grab your chance and travel across the global village,fun guaranteed.</p>
            <a href="packages.html" class="cta-button">Explore Packages</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Travelsafi Adventures. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

//css
/* styles.css */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #0077b6;
    color: white;
    padding: 20px;
}

header h1 {
    margin: 0;
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
    color: white;
    text-decoration: underline;
    font-weight: bold;
}

main {
    padding: 20px;
}

footer {
    background-color: #f3a712;
    color: white;
    text-align: center;
    padding: 10px;
}


// script.js
document.addEventListener('DOMContentLoaded', function() {
    console.log('DOM loaded.');
});
