<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luis Lawn Care</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background: #228B22; color: white; text-align: center; padding: 1.5em; }
        nav { text-align: center; padding: 1em; background: #2E8B57; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        section { padding: 20px; text-align: center; }
        .about, .services, .contact { margin: 20px 0; background: white; padding: 20px; border-radius: 10px; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1); }
        footer { background: #333; color: white; text-align: center; padding: 1em; }
        img { width: 100%; max-height: 400px; object-fit: cover; border-radius: 10px; margin-bottom: 15px; }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Luis Lawn Care</h1>
        <p>Your trusted lawn care and landscaping experts</p>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section class="about">
        <img src="https://source.unsplash.com/800x400/?lawn,garden" alt="Beautiful Lawn">
        <h2>About Us</h2>
        <p>At Luis Lawn Care, we are dedicated to providing top-notch lawn maintenance and landscaping services. Our goal is to enhance your outdoor space with expert care and precision.</p>
    </section>
    <footer>
        <p>&copy; 2025 Luis Lawn Care. All rights reserved.</p>
    </footer>
</body>
</html>

<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Luis Lawn Care</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background: #228B22; color: white; text-align: center; padding: 1.5em; }
        nav { text-align: center; padding: 1em; background: #2E8B57; }
        nav a { color: white; text-decoration: none; margin: 0 15px; font-weight: bold; }
        section { padding: 20px; text-align: center; }
        .contact-form { margin: 20px auto; background: white; padding: 20px; border-radius: 10px; box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1); max-width: 500px; }
        footer { background: #333; color: white; text-align: center; padding: 1em; }
        input, textarea { width: 100%; padding: 10px; margin: 10px 0; border-radius: 5px; border: 1px solid #ccc; }
        button { background: #228B22; color: white; padding: 10px; border: none; border-radius: 5px; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section class="contact-form">
        <h2>Have Questions? Set Up a Meeting!</h2>
        <p>Fill out the form below and we'll get back to you as soon as possible.</p>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Luis Lawn Care. All rights reserved.</p>
    </footer>
</body>
</html>
