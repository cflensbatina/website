<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1>UX Designer for Luxury Brands</h1>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <div class="container">
            <h1>About Me</h1>
            <p>I am a UX designer specializing in creating exceptional user experiences for luxury brands in the digital space.</p>
        </div>
    </section>
    <section id="portfolio">
        <div class="container">
            <h1>Portfolio</h1>
            <div class="portfolio-item">
                <img src="portfolio-item1.jpg" alt="Portfolio Item 1">
                <h2>App Design for Luxury Fashion</h2>
                <p>View Project</p>
            </div>
            <div class="portfolio-item">
                <img src="portfolio-item2.jpg" alt="Portfolio Item 2">
                <h2>Website Redesign for High-End Jewelry Brand</h2>
                <p>View Project</p>
            </div>
            <!-- Add more portfolio items as needed -->
        </div>
    </section>
    <section id="services">
        <div class="container">
            <h1>Services</h1>
            <ul>
                <li>User Experience Design</li>
                <li>UI Design</li>
                <li>Prototyping</li>
                <li>User Testing</li>
                <li>Design Consultation</li>
            </ul>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h1>Contact Me</h1>
            <form action="contact.php" method="POST">
                <input type="text" name="name" placeholder="Your Name">
                <input type="email" name="email" placeholder="Your Email">
                <textarea name="message" placeholder="Your Message"></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2024 UX Designer for Luxury Brands. All rights reserved.</p>
        </div>
    </footer>
</body>
