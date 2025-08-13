<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User-Portfolio website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: blue; /* Primary background */
            color: white; /* Tertiary color */
        }

        header {
            background-color: black; /* Secondary color */
            padding: 1rem;
            text-align: center;
        }

        header h1 {
            margin: 0;
            color: white;
        }

        header nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 2rem;
            max-width: 900px;
            margin: auto;
            background-color: black; /* Secondary color */
            margin-bottom: 1rem;
            border-radius: 8px;
            color: white;
        }

        button {
            background: white; /* Tertiary color */
            color: black; /* Secondary color */
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background: #ddd;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 8px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            color: black;
        }

        form button {
            width: 100%;
        }

        footer {
            text-align: center;
            background: black; /* Secondary */
            color: white; /* Tertiary */
            padding: 1rem;
            margin-top: 1rem;
        }
    </style>
</head>
<body>
    <!-- HEADER -->
    <header>
        <h1>My Portfolio Website</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- HOME SECTION -->
    <section id="home">
        <h2>Welcome!</h2>
        <p>This website is created to present my works and skills.</p>
        <button id="learnBtn">Click Me</button>
    </section>

    <!-- ABOUT SECTION -->
    <section id="about">
        <h2>About</h2>
        <p>I'm a website developer, coder, and graphic designer. I focus on making simple, clean, and responsive designs that work on all devices.</p>
    </section>

    <!-- CONTACT SECTION -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:wasiubello208@mail.com" style="color:white;">wasiubello208@mail.com</a></p>
        <p>Phone: <a href="tel:07044024028" style="color:white;">07044024028</a></p>
        <form id="contactForm">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="email" id="email" placeholder="Your Email" required>
            <textarea id="message" placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
        <p id="formStatus"></p>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2025 My User-Friendly Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
