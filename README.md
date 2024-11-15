<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manish Pandey</title>
    <style>
        /* CSS Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        #hero {
            padding: 50px;
            text-align: center;
            background: #333;
            color: #fff;
        }
        #hero h2 {
            margin-top: 0;
        }
        #skills {
            padding: 20px;
            text-align: center;
        }
        .skills-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        .skill {
            padding: 10px 15px;
            background: #333;
            color: #fff;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .social-icons img {
            width: 30px;
            margin: 0 5px;
        }
        .social-icons a {
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Manish Pandey</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
            <a href="portfolio.html">Portfolio</a>
            <a href="services.html">Services</a>
            <a href="blog.html">Blog</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <section id="hero">
            <h2>Welcome to My Personal Space</h2>
            <p>I'm Manish, a developer and tech enthusiast focused on crafting innovative solutions.</p>
            <button onclick="navigateToAbout()">Learn More</button>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills-container">
                <div class="skill">HTML</div>
                <div class="skill">CSS</div>
                <div class="skill">JavaScript</div>
                <div class="skill">Python</div>
            </div>
        </section>
    </main>

    <footer>
        <section class="connect" id="connect">
            <h2>Connect with Me</h2>
            <div class="social-icons">
                <a href="https://linkedin.com/in/hmpmanish" target="_blank">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/linkedin.png" alt="LinkedIn">
                </a>
                <a href="https://instagram.com/hmpmanish" target="_blank">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/instagram-new.png" alt="Instagram">
                </a>
                <a href="https://twitter.com/hmpmanish" target="_blank">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/twitter.png" alt="Twitter">
                </a>
                <a href="https://github.com/hmpmanish" target="_blank">
                    <img src="https://img.icons8.com/ios-filled/50/ffffff/github.png" alt="GitHub">
                </a>
            </div>
            <p>&copy; 2024 Hmpmanish. All rights reserved.</p>
        </section>
    </footer>

    <script>
        // JavaScript function to navigate to About page
        function navigateToAbout() {
            window.location.href = 'about.html';
        }
    </script>
</body>
</html>
