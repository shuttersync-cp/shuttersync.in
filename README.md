<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShutterSync.in | Photography</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #111;
            color: #fff;
        }

        header {
            background: #000;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 32px;
            letter-spacing: 2px;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            color: #f39c12;
        }

        .hero {
            height: 80vh;
            background: url('https://images.unsplash.com/photo-1516035069371-29a1b244cc32') no-repeat center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        .hero h2 {
            font-size: 40px;
            background: rgba(0,0,0,0.6);
            padding: 20px;
        }

        .section {
            padding: 50px 20px;
            text-align: center;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .card {
            background: #222;
            margin: 15px;
            padding: 20px;
            width: 250px;
            border-radius: 10px;
        }

        .card h3 {
            color: #f39c12;
        }

        footer {
            background: #000;
            padding: 20px;
            text-align: center;
        }

        .contact {
            font-size: 18px;
            line-height: 1.8;
        }

        @media (max-width: 600px) {
            .hero h2 {
                font-size: 24px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>ShutterSync.in</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero" id="home">
    <h2>Capturing Moments, Creating Memories</h2>
</section>

<section class="section" id="services">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">
            <h3>Wedding Photography</h3>
            <p>Beautifully capturing your special day.</p>
        </div>
        <div class="card">
            <h3>Portrait Shoots</h3>
            <p>Professional and creative portraits.</p>
        </div>
        <div class="card">
            <h3>Event Coverage</h3>
            <p>From small events to grand celebrations.</p>
        </div>
    </div>
</section>

<section class="section" id="contact">
    <h2>Contact Us</h2>
    <div class="contact">
        <p><strong>Brand:</strong> ShutterSync.in</p>
        <p><strong>Phone:</strong> 7356574403,7012919818</p>
        <p><strong>Email:</strong> shuttersync.in@gmail.com</p>
    </div>
</section>

<footer>
    <p>© 2026 ShutterSync.in | All Rights Reserved</p>
</footer>

</body>
</html>
