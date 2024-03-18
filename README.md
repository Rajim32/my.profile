<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Hello, I'm John Doe, a web developer passionate about creating beautiful and functional websites.</p>
        </section>

        <section>
            <h2>Projects</h2>
            <figure>
                <img src="project1.jpg" alt="Project 1">
                <figcaption>Project 1: Description</figcaption>
            </figure>
            <figure>
                <img src="project2.jpg" alt="Project 2">
                <figcaption>Project 2: Description</figcaption>
            </figure>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
About.html
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Me</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>My Bio</h2>
            <p>I am a web developer with 5 years of experience in frontend and backend development.</p>
            <p><em>I love creating innovative solutions</em> to complex problems and <strong>bringing ideas to life through code</strong>.</p>
        </section>

        <section>
            <h2>Skills</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Python</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
Contact.html
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Me</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Me</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Get in Touch</h2>
            <form action="submit.php" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea><br>

                <input type="submit" value="Send Message">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
styles.css
css
Copy code
/* Add your CSS styles here */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header, footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 10px;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

footer {
    position: fixed;
    width: 100%;
    bottom: 0;


