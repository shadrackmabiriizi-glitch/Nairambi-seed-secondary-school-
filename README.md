
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHAD SPORTS UGANDA</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: white;
        }

        header {
            background-color: #000;
            text-align: center;
            padding: 30px 20px;
        }

        header img {
            width: 120px;
            margin-bottom: 15px;
        }

        header h1 {
            margin: 10px 0 5px;
            font-size: 28px;
            color: #ffffff;
        }

        header p {
            color: #ccc;
        }

        nav {
            background: #111;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: orange;
        }

        section {
            padding: 40px 20px;
        }

        .container {
            width: 90%;
            margin: auto;
            max-width: 1000px;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .services {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .service-box {
            background: #111;
            padding: 20px;
            flex: 1;
            min-width: 250px;
            border-radius: 8px;
        }

        .service-box h3 {
            color: orange;
        }

        footer {
            background: #111;
            text-align: center;
            padding: 15px;
            color: #aaa;
        }

        .btn {
            display: block;
            width: fit-content;
            margin: 20px auto;
            background: orange;
            color: black;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background: #ff8800;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="SHAD SPORTS UGANDA Logo">
    <h1>SHAD SPORTS UGANDA</h1>
    <p>Professional Licensing for Football Players & Clubs</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <div class="container">
        <h2>About Us</h2>
        <p>
            SHAD SPORTS UGANDA is a professional sports company focused on helping
            football players and clubs obtain official licenses. We ensure compliance
            with football regulations and support talent growth in Uganda.
        </p>
    </div>
</section>

<section id="services">
    <div class="container">
        <h2>Our Services</h2>

        <div class="services">
            <div class="service-box">
                <h3>Player Licensing</h3>
                <p>We help players get official licenses to participate in competitions.</p>
            </div>

            <div class="service-box">
                <h3>Club Registration</h3>
                <p>We assist clubs in legal registration and certification.</p>
            </div>

            <div class="service-box">
                <h3>Document Processing</h3>
                <p>We handle all required paperwork quickly and professionally.</p>
            </div>

            <div class="service-box">
                <h3>Consultation</h3>
                <p>Expert advice on football rules, transfers, and player eligibility.</p>
            </div>
        </div>

        <a href="#contact" class="btn">Get Started</a>
    </div>
</section>

<section id="contact">
    <div class="container">
        <h2>Contact Us</h2>
        <p>Email: shadsportsuganda@gmail.com</p>
        <p>Phone: +256 700 000000</p>
        <p>Location: Kampala, Uganda</p>
    </div>
</section>

<footer>
    <p>&copy; 2026 SHAD SPORTS UGANDA. All Rights Reserved.</p>
</footer>

</body>
</html>

