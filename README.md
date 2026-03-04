<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Business</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            font-size: 2em;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 50px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .hero {
            background: #e0f0ff;
            padding: 100px 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 30px;
        }

        .hero h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2em;
            color: #555;
        }

        .services {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .service-card {
            background: #fff;
            padding: 20px;
            flex: 1 1 250px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            text-align: center;
        }

        .service-card h3 {
            margin-bottom: 15px;
            color: #007bff;
        }

        footer {
            background: #222;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }

        footer a {
            color: #007bff;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Rama Palce</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h2>Rama Palace</h2>
        <p>currently avaible for TO-LET....contact here</p>
    </section>

    <section class="services" id="services">
        <div class="service-card">
            <h3>Contact us</h3>
            <p>Email and phone number avaible </p>
        </div>
        <div class="service-card">
            <h3>Photos</h3>
            <p>Look for the space for establishment of your business.</p>
        </div>
        <div class="service-card">
            <h3>Owner</h3>
            <p>about owner</p>
        </div>
    </section>

    <section id="contact">
        <h2 style="text-align:center; margin-bottom:20px;">Contact Us</h2>
        <p style="text-align:center;">Email: <a href="Ramapalace01@gmail.com"> "Ramapalace01@gmail.com"</a> | Phone: +91 9411424581</p>
    </section>

    <footer>
        &copy; 2026 Rama Palce. All Rights Reserved.
    </footer>

</body>
</html>
