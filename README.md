# Sharpkey-media
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sharpkey Media | Creative Services & Production</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-color: #0b0f19;
            --card-bg: #111827;
            --accent-color: #6366f1;
            --accent-hover: #4f46e5;
            --text-main: #f3f4f6;
            --text-muted: #9ca3af;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Inter', sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
        }

        /* Header & Navigation */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1.5rem 5%;
            background-color: rgba(11, 15, 25, 0.9);
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 1px solid #1f2937;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: 800;
            color: var(--text-main);
            letter-spacing: -0.5px;
        }

        .logo span {
            color: var(--accent-color);
        }

        nav a {
            color: var(--text-muted);
            text-decoration: none;
            margin-left: 2rem;
            font-weight: 600;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--text-main);
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 8rem 5% 5rem 5%;
            max-width: 900px;
            margin: 0 auto;
        }

        .hero h1 {
            font-size: 3.5rem;
            font-weight: 800;
            margin-bottom: 1.5rem;
            letter-spacing: -1px;
        }

        .hero h1 span {
            color: var(--accent-color);
        }

        .hero p {
            font-size: 1.2rem;
            color: var(--text-muted);
            margin-bottom: 2.5rem;
        }

        .btn {
            background-color: var(--accent-color);
            color: white;
            padding: 0.8rem 2rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            transition: background-color 0.3s;
            display: inline-block;
        }

        .btn:hover {
            background-color: var(--accent-hover);
        }

        /* Services Section */
        .section {
            padding: 5rem 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 2.2rem;
            margin-bottom: 3rem;
            font-weight: 800;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background-color: var(--card-bg);
            padding: 2.5rem;
            border-radius: 10px;
            border: 1px solid #1f2937;
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
        }

        .service-card p {
            color: var(--text-muted);
        }

        /* Contact Section */
        .contact {
            background-color: var(--card-bg);
            padding: 4rem;
            border-radius: 10px;
            max-width: 700px;
            margin: 0 auto 5rem auto;
            border: 1px solid #1f2937;
        }

        .contact form {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            text-align: left;
        }

        .form-group label {
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: var(--text-muted);
        }

        .form-group input, .form-group textarea {
            padding: 0.8rem;
            border-radius: 5px;
            border: 1px solid #374151;
            background-color: var(--bg-color);
            color: var(--text-main);
            font-size: 1rem;
        }

        .form-group input:focus, .form-group textarea:focus {
            outline: none;
            border-color: var(--accent-color);
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            border-top: 1px solid #1f2937;
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        @media(max-width: 768px) {
            .hero h1 { font-size: 2.5rem; }
            nav { display: none; } /* Simplified mobile for basic template */
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <div class="logo">Sharpkey<span>Media</span></div>
        <nav>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Elevate Your Brand with <span>Sharpkey Media</span></h1>
        <p>We deliver top-tier digital media services, video production, and creative solutions tailored to scale your business.</p>
        <a href="#contact" class="btn">Get Started</a>
    </section>

    <!-- Services Section -->
    <section id="services" class="section">
        <h2 class="section-title">Our Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Video Production</h3>
                <p>High-quality promotional videos, commercials, and social media content designed to capture attention and drive engagement.</p>
            </div>
            <div class="service-card">
                <h3>Brand Strategy</h3>
                <p>Comprehensive identity building, visual guidelines, and strategic positioning to make your brand unforgettable.</p>
            </div>
            <div class="service-card">
                <h3>Digital Marketing</h3>
                <p>Data-driven campaigns across platforms to increase your reach, generate leads, and maximize your ROI.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2 class="section-title">Let's Work Together</h2>
        <div class="contact">
            <form>
                <div class="form-group">
                    <label for="name">Your Name</label>
                    <input type="text" id="name" placeholder="John Doe" required>
                </div>
                <div class="form-group">
                    <label for="email">Your Email</label>
                    <input type="email" id="email" placeholder="john@example.com" required>
                </div>
                <div class="form-group">
                    <label for="message">Project Details</label>
                    <textarea id="message" rows="5" placeholder="Tell us about your project..." required></textarea>
                </div>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Sharpkey Media. All rights reserved.</p>
    </footer>

</body>
</html>
