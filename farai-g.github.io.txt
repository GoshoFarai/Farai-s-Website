<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Farai Gosho's personal webpage showcasing journalism work, writing samples, and projects.">
    <title>Farai Gosho - Personal Webpage</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* General Styles */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #202123;
            color: #ECECEC;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            scroll-behavior: smooth;
        }
        h1, h2, h3 {
            color: #00A67E;
        }
        a {
            color: #00A67E;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #007C5E;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }

        /* Navbar */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: #2A2B30;
            padding: 10px 0;
            text-align: center;
            z-index: 1000;
        }
        nav a {
            margin: 0 15px;
            font-weight: 600;
            color: #ECECEC;
        }
        nav a:hover {
            color: #00A67E;
        }

        /* Header Section */
        header {
            text-align: center;
            padding: 100px 0 50px;
            background-color: #2A2B30;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }

        /* About Me Section */
        .about {
            text-align: center;
        }
        .about img {
            border-radius: 50%;
            max-width: 150px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Portfolio Section */
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .portfolio-item {
            background-color: #2A2B30;
            padding: 20px;
            margin-bottom: 20px;
            width: 48%;
            box-sizing: border-box;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .portfolio-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
        }
        .portfolio-item h3 {
            margin-top: 0;
        }

        /* Blog Section */
        .blog-post {
            margin-bottom: 20px;
        }
        .blog-post h3 {
            margin-top: 0;
        }

        /* Contact Section */
        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            max-width: 500px;
            padding: 10px;
            margin-bottom: 10px;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: #ECECEC;
        }
        .contact-form input[type="submit"] {
            background-color: #00A67E;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .contact-form input[type="submit"]:hover {
            background-color: #007C5E;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #2A2B30;
        }

        /* Smooth scrolling for internal links */
        html {
            scroll-behavior: smooth;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .portfolio-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Header Section -->
    <header>
        <h1>Farai Gosho</h1>
        <p>Journalist | Content Writer | Project Enthusiast</p>
    </header>

    <div class="container">
        
        <!-- About Me Section -->
        <section id="about" class="about section">
            <img src="profile.jpg" alt="Farai Gosho">
            <h2>About Me</h2>
            <p>Hello! I'm Farai Gosho, a journalist and content writer with a passion for politics, climate change, and the entertainment industry. With experience writing for various platforms and managing projects, I combine storytelling and research to bring impactful narratives to life.</p>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio" class="portfolio section">
            <h2>Portfolio</h2>
            
            <div class="portfolio-item">
                <h3>Writing Samples</h3>
                <p>Check out my collection of writing samples, featuring a blend of journalism, content writing, and in-depth articles.</p>
                <a href="https://example.com/writing-samples" target="_blank">View Writing Samples</a>
            </div>

            <div class="portfolio-item">
                <h3>Projects</h3>
                <p>Explore the projects I've been involved in, including collaborations with artists, climate change awareness initiatives, and more.</p>
                <a href="https://example.com/projects" target="_blank">View Projects</a>
            </div>

            <div class="portfolio-item">
                <h3>Journalism Work</h3>
                <p>My journalism portfolio includes pieces written for Politico Pulse Blogspot and 3mob.com, covering topics from politics to local entertainment.</p>
                <a href="https://example.com/journalism" target="_blank">View Journalism Work</a>
            </div>
        </section>

        <!-- Blog Section -->
        <section id="blog" class="blog section">
            <h2>Blog</h2>

            <div class="blog-post">
                <h3>Latest Post: The Future of AI in Journalism</h3>
                <p>In this article, I explore how artificial intelligence is transforming the journalism landscape, from automated reporting to AI-powered research tools.</p>
                <a href="https://example.com/blog-post-1" target="_blank">Read More</a>
            </div>

            <div class="blog-post">
                <h3>Impact of Climate Change on Local Communities</h3>
                <p>This piece delves into how climate change is affecting small communities in Southern Africa, with a focus on sustainable solutions.</p>
                <a href="https://example.com/blog-post-2" target="_blank">Read More</a>
            </div>

        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact section">
            <h2>Contact Me</h2>
            <form class="contact-form" action="mailto:youremail@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="6" required></textarea>
                <input type="submit" value="Send Message">
            </form>
        </section>

    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Farai Gosho. All Rights Reserved.</p>
    </footer>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Farai Gosho's personal webpage showcasing journalism work, writing samples, and projects.">
    <title>Farai Gosho - Personal Webpage</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* General Styles */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #202123;
            color: #ECECEC;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            scroll-behavior: smooth;
        }
        h1, h2, h3 {
            color: #00A67E;
        }
        a {
            color: #00A67E;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #007C5E;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }

        /* Navbar */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: #2A2B30;
            padding: 10px 0;
            text-align: center;
            z-index: 1000;
        }
        nav a {
            margin: 0 15px;
            font-weight: 600;
            color: #ECECEC;
        }
        nav a:hover {
            color: #00A67E;
        }

        /* Header Section */
        header {
            text-align: center;
            padding: 100px 0 50px;
            background-color: #2A2B30;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }

        /* About Me Section */
        .about {
            text-align: center;
        }
        .about img {
            border-radius: 50%;
            max-width: 150px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Portfolio Section */
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .portfolio-item {
            background-color: #2A2B30;
            padding: 20px;
            margin-bottom: 20px;
            width: 48%;
            box-sizing: border-box;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .portfolio-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
        }
        .portfolio-item h3 {
            margin-top: 0;
        }

        /* Blog Section */
        .blog-post {
            margin-bottom: 20px;
        }
        .blog-post h3 {
            margin-top: 0;
        }

        /* Contact Section */
        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            max-width: 500px;
            padding: 10px;
            margin-bottom: 10px;
            border: none;
            border-radius: 5px;
            background-color: #333;
            color: #ECECEC;
        }
        .contact-form input[type="submit"] {
            background-color: #00A67E;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .contact-form input[type="submit"]:hover {
            background-color: #007C5E;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #2A2B30;
        }

        /* Smooth scrolling for internal links */
        html {
            scroll-behavior: smooth;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .portfolio-item {
                width: 100%;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Header Section -->
    <header>
        <h1>Farai Gosho</h1>
        <p>Journalist | Content Writer | Project Enthusiast</p>
    </header>

    <div class="container">
        
        <!-- About Me Section -->
        <section id="about" class="about section">
            <img src="profile.jpg" alt="Farai Gosho">
            <h2>About Me</h2>
            <p>Hello! I'm Farai Gosho, a journalist and content writer with a passion for politics, climate change, and the entertainment industry. With experience writing for various platforms and managing projects, I combine storytelling and research to bring impactful narratives to life.</p>
        </section>

        <!-- Portfolio Section -->
        <section id="portfolio" class="portfolio section">
            <h2>Portfolio</h2>
            
            <div class="portfolio-item">
                <h3>Writing Samples</h3>
                <p>Check out my collection of writing samples, featuring a blend of journalism, content writing, and in-depth articles.</p>
                <a href="https://example.com/writing-samples" target="_blank">View Writing Samples</a>
            </div>

            <div class="portfolio-item">
                <h3>Projects</h3>
                <p>Explore the projects I've been involved in, including collaborations with artists, climate change awareness initiatives, and more.</p>
                <a href="https://example.com/projects" target="_blank">View Projects</a>
            </div>

            <div class="portfolio-item">
                <h3>Journalism Work</h3>
                <p>My journalism portfolio includes pieces written for Politico Pulse Blogspot and 3mob.com, covering topics from politics to local entertainment.</p>
                <a href="https://example.com/journalism" target="_blank">View Journalism Work</a>
            </div>
        </section>

        <!-- Blog Section -->
        <section id="blog" class="blog section">
            <h2>Blog</h2>

            <div class="blog-post">
                <h3>Latest Post: The Future of AI in Journalism</h3>
                <p>In this article, I explore how artificial intelligence is transforming the journalism landscape, from automated reporting to AI-powered research tools.</p>
                <a href="https://example.com/blog-post-1" target="_blank">Read More</a>
            </div>

            <div class="blog-post">
                <h3>Impact of Climate Change on Local Communities</h3>
                <p>This piece delves into how climate change is affecting small communities in Southern Africa, with a focus on sustainable solutions.</p>
                <a href="https://example.com/blog-post-2" target="_blank">Read More</a>
            </div>

        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact section">
            <h2>Contact Me</h2>
            <form class="contact-form" action="mailto:youremail@example.com" method="post" enctype="text/plain">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="6" required></textarea>
                <input type="submit" value="Send Message">
            </form>
        </section>

    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Farai Gosho. All Rights Reserved.</p>
    </footer>

</body>
</html>
