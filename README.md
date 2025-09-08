<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tycoon Olam - Real Estate Investment</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            color: #333;
        }
        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }
        .hero {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://drive.google.com/uc?export=download&id=1yacyLsR08eKzQ0wLNCAzKlbPae7W-dDi');
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
        }
        .section {
            padding: 5rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            border: 1px solid #d1d5db;
            border-radius: 0.375rem;
            padding: 0.75rem;
            width: 100%;
            margin-bottom: 1rem;
            font-family: 'Roboto', sans-serif;
        }
        .contact-form button {
            background-color: #1f2937;
            color: white;
            padding: 0.75rem 2rem;
            border-radius: 0.375rem;
            font-family: 'Playfair Display', serif;
            transition: background-color 0.3s;
        }
        .contact-form button:hover {
            background-color: #374151;
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h1 class="text-5xl md:text-6xl font-bold mb-4">Tycoon Olam</h1>
            <p class="text-xl md:text-2xl mb-6">Building Wealth Through Strategic Real Estate Investments</p>
            <a href="#contact" class="bg-white text-gray-800 py-3 px-6 rounded-md font-semibold hover:bg-gray-100 transition">Get Started</a>
        </div>
    </section>

    <!-- About Section -->
    <section class="section bg-gray-100">
        <h2 class="text-4xl font-bold text-center mb-6">About Tycoon Olam</h2>
        <p class="text-lg text-center max-w-3xl mx-auto">
            At Tycoon Olam, we are premier real estate investors with a proven track record. Our partners collectively own thousands of residential and commercial units, showcasing our expertise in high-potential markets. Specializing in strategic acquisitions and portfolio growth, we deliver exceptional value, leveraging data-driven insights and economic trends to maximize returns.
        </p>
    </section>

    <!-- Services Section -->
    <section class="section">
        <h2 class="text-4xl font-bold text-center mb-6">Our Services</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="text-center">
                <h3 class="text-2xl font-semibold mb-4">Market Analysis</h3>
                <p>Leveraging data-driven insights to identify properties in expansion-stage markets with strong job growth and economic stability.</p>
            </div>
            <div class="text-center">
                <h3 class="text-2xl font-semibold mb-4">Property Acquisition</h3>
                <p>Securing high-value assets with favorable Debt Coverage Ratios, ensuring robust returns and minimized risk.</p>
            </div>
            <div class="text-center">
                <h3 class="text-2xl font-semibold mb-4">Portfolio Management</h3>
                <p>Optimizing investments through proactive management, ensuring properties benefit from insurance proceeds and local incentives.</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section bg-gray-100" id="contact">
        <h2 class="text-4xl font-bold text-center mb-6">Contact Us</h2>
        <form class="contact-form max-w-lg mx-auto" action="https://formspree.io/f/xqkwzbky" method="POST">
            <input type="text" name="name" placeholder="Name" required>
            <input type="email" name="email" placeholder="Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <input type="hidden" name="_subject" value="New Contact Form Submission from Tycoon Olam">
            <input type="hidden" name="_cc" value="yissy@tycoonolam.com">
            <input type="hidden" name="_next" value="https://tycoonolam.com/thanks">
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white text-center py-4">
        <p>&copy; 2025 Tycoon Olam. All Rights Reserved.</p>
    </footer>
</body>
</html>
