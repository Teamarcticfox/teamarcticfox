<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation Bar -->
    <header>
        <div class="logo">MyBrand</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to Your Future Website</h1>
            <p>We build clean, fast, and modern digital experiences that help your business grow.</p>
            <a href="#contact" class="btn">Get Started</a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="card-container">
            <div class="card">
                <h3>Web Design</h3>
                <p>Beautiful, user-friendly layouts tailored to your unique business brand.</p>
            </div>
            <div class="card">
                <h3>Development</h3>
                <p>Fast, secure, and responsive clean code optimized for all screen sizes.</p>
            </div>
            <div class="card">
                <h3>SEO Optimization</h3>
                <p>Strategies designed to boost your search rankings and drive traffic.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>We are a team of passionate creators dedicated to turning ideas into functional digital realities. Our process focuses on simplicity, speed, and exceptional user experience.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form action="#" method="POST">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 MyBrand. All rights reserved.</p>
    </footer>

</body>
</html>

