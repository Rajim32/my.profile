<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emily's Portfolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Assuming you have a separate CSS file -->
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="portfolio.html">Portfolio</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>Welcome to Emily's Portfolio</h1>
        <p>Explore my creative journey through visual storytelling.</p>
    </main>

    <footer>
        <p>&copy; 2024 Emily's Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
about.html (About Me Page)
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Emily</title>
    <link rel="stylesheet" href="styles.css"> <!-- Assuming you have a separate CSS file -->
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="portfolio.html">Portfolio</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>About Me</h1>
        <section>
            <h2>My Story</h2>
            <p>I am a passionate graphic designer with a love for creating visually stunning designs that captivate and inspire. With a background in both art and technology, I blend creativity with technical expertise to deliver unique and impactful designs.</p>
        </section>
        <section>
            <h2>My Skills</h2>
            <ul>
                <li><strong>Graphic Design:</strong> Adobe Photoshop, Illustrator</li>
                <li><strong>Web Design:</strong> HTML, CSS, JavaScript</li>
                <li><strong>UI/UX Design:</strong> Wireframing, Prototyping</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Emily's Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
portfolio.html (Portfolio Page)
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emily's Portfolio</title>
    <link rel="stylesheet" href="styles.css"> <!-- Assuming you have a separate CSS file -->
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="portfolio.html">Portfolio</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>Portfolio</h1>
        <section>
            <h2>Featured Projects</h2>
            <article>
                <h3>Project 1: Logo Design</h3>
                <figure>
                    <img src="logo1.jpg" alt="Logo 1">
                    <figcaption>Logo design for a local restaurant.</figcaption>
                </figure>
            </article>
            <article>
                <h3>Project 2: Website Redesign</h3>
                <figure>
                    <img src="website1.jpg" alt="Website 1">
                    <figcaption>Redesign of an e-commerce website.</figcaption>
                </figure>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Emily's Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
contact.html (Contact Page)
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Emily</title>
    <link rel="stylesheet" href="styles.css"> <!-- Assuming you have a separate CSS file -->
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="portfolio.html">Portfolio</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>Contact Me</h1>
        <section>
            <h2>Send Me a Message</h2>
            <form action="submit.php" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                <input type="submit" value="Send Message">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Emily's Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>


