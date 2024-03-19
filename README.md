<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My hobby</title>
</head>
<body>
    <header>
        <h1></h1>
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
            <p><em>Welcome to my website,</em> this website is all about my hobbies on movies. This website serves as a platform to showcase my work and share my experiences.</p>
            <p>In hollywood movie industry i like the direction of christopher nolan. </p>
            <p><em>Recently his movie openheimer got <strong>7 oscars.</strong></em></p>
        </section>

        <section>
            <h2>My thoughts on movies:</h2>
            <p>As I have already mentioned, I am fascinated by the works of Christopher Nolan. His movies not only entertain but also challenge the audience with their intricate narratives and thought-provoking themes.</p>
            <p>Nolan's films often delve into complex concepts such as time, identity, and morality, making them a captivating experience for any movie enthusiast.</p>
            <p>The impeccable craftsmanship, mesmerizing visuals, and haunting soundtracks in his movies, like <strong>tenet</strong> and <strong>The dark knight</strong> leave a lasting impression on the viewers.</p>
            <figure>
                <img src="https://tse3.mm.bing.net/th?id=OIP.B2U3K0cTsn1kxzuCq9wQxQHaHa&pid=Api&P=0&h=220" alt="Description of Image 1">
                <figcaption>Movie:Tenet</figcaption>
            </figure>
            <figure>
                <img src="https://tse3.mm.bing.net/th?id=OIP.zU8P45LlyXn-F874TJtR-QHaFj&pid=Api&P=0&h=220" alt="Description of Image 2">
                <figcaption>Movie:The dark Knight</figcaption>
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


