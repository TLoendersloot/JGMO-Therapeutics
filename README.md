<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haensgrada - JGMO Therapeutics</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Haensgrada - JGMO Therapeutics</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#over">Over het medicijn</a></li>
                <li><a href="#faq">Veelgestelde vragen</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#nieuws">Nieuws & updates</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <h2>Welkom bij Haensgrada</h2>
        <p>Informatie over Haensgrada, een innovatief geneesmiddel van JGMO Therapeutics.</p>
    </section>
    
    <footer>
        <p>&copy; 2025 JGMO Therapeutics - Alle rechten voorbehouden.</p>
    </footer>

    <script src="scripts/script.js"></script>
</body>
</html>

/* Global Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

/* Header Styles */
header {
    background: #004080;
    color: white;
    padding: 15px;
    text-align: center;
}

/* Navigation Styles */
nav ul {
    list-style: none;
    padding: 0;
    text-align: center;
    margin-top: 15px;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-size: 18px;
}

/* Section Styles */
section {
    padding: 40px 20px;
    margin: 20px 0;
    text-align: center;
    background-color: white;
    border-radius: 10px;
    box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
}

/* Footer Styles */
footer {
    background: #004080;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

/* Mobile Styles */
@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin: 10px 0;
    }

    section {
        padding: 20px;
    }
}
git add .
git commit -m "Refined website layout and design"
git push origin main

