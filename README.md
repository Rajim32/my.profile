<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/portfolio">Portfolio</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p><em>Welcome to my website!</em> I am passionate about [insert your interests or purpose here]. This website serves as a platform to showcase my work and share my experiences.</p>
        </section>

        <section>
            <h2>My Portfolio</h2>
            <figure>
                <img src="image1.jpg" alt="Description of Image 1">
                <figcaption>Description of Image 1</figcaption>
            </figure>
            <figure>
                <img src="image2.jpg" alt="Description of Image 2">
                <figcaption>Description of Image 2</figcaption>
            </figure>
            <!-- Add more images as needed -->
        </section>

        <section>
            <h2>Contact Me</h2>
            <form action="/submit_message" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br>

                <input type="submit" value="Submit">
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Your Website. All rights reserved.</p>
    </footer>
</body>
</html>


