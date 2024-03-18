<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Me</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>Welcome to my portfolio website! I am passionate about web development and love creating innovative solutions.</p>
            <p>For me, web development is more than just a career—it's a canvas for innovation and expression.</P>
            <p>I thrive on the thrill of turning ideas into interactive experiences, utilizing the latest technologies to build websites that captivate and inspire.</p>
        </section>

        <section>
            <h2>Latest Projects</h2>
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
About Me Page (about.html)
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
</head>
<body>
    <header>
        <h1>About Me</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Me</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>My Background</h2>
            <p>I am a web developer with a passion for creating engaging and user-friendly websites.</p>
            <p><em>Skills:</em> HTML, CSS, JavaScript, React</p>
        </section>

        <section>
            <h2>My Interests</h2>
            <ul>
                <li>Web Development</li>
                <li>I am more interested in web development than any other stuffs</li>
                <li>Photography</li>
                <li>I like to click sunset photos</li>
                </li>Photography supports me to stay calm and cool my mind</li>
                <li>Traveling</li>
                <li>curiosity of peoples lifestyle, cultures and religions from the evry coorner the earth</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
Contact Page (contact.html)
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Me</title>
</head>
<body>
    <header>
        <h1>Contact Me</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About Me</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Send me a Message</h2>
            <form action="submit.php" method="post">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name"><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="message">Message:</label><br>
                <textarea id="message" name="message"></textarea><br>
                <input type="submit" value="Submit">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>
