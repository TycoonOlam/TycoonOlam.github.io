[<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tycoon Olam Real Estate</title>
  <style>
    body {
      margin: 0;
      font-family: "Helvetica Neue", Arial, sans-serif;
      color: #333;
      background-color: #f9f9f9;
    }
    .hero {
      background: url("image/design-house-modern-villa-with-open-plan-living-private-bedroom-wing-large-terrace-with-privacy.jpg") no-repeat center center;
      background-size: cover;
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-shadow: 0 2px 6px rgba(0,0,0,0.6);
    }
    .hero h1 {
      font-size: 3rem;
      margin: 0;
    }
    .content {
      max-width: 600px;
      margin: 2rem auto;
      padding: 0 1rem;
      text-align: center;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      margin-top: 2rem;
    }
    input, textarea, button {
      padding: 0.75rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      background: #002b5c;
      color: white;
      border: none;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #004080;
    }
  </style>
</head>
<body>
  <!-- Hero Section -->
  <div class="hero">
    <h1>Building a Better World in Real Estate</h1>
  </div>

  <!-- About + Contact -->
  <div class="content">
    <p>
      Together with our partners, we manage thousands of units across the country.  
      Interested in working with us? Get in touch below.
    </p>

    <!-- Contact Form -->
    <form action="https://formspree.io/f/xkgvklqo" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="_replyto" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <!-- Hidden field to send directly to your email -->
      <input type="hidden" name="_to" value="yissy@tycoonolam.com">
      <button type="submit">Send Message</button>
    </form>
  </div>
</body>
</html>
](https://github.com/mmistakes/minimal-mistakes.git)
