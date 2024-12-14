<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthcare Services</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background-color: #f4f4f4;
            line-height: 1.6;
            color: #333;
        }

        /* Navigation Bar */
        .navbar {
            background-color: #004f9f;
            color: white;
            padding: 20px 40px;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .navbar ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        .navbar ul li {
            margin: 0 20px;
        }
        .navbar ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        .navbar ul li a:hover {
            color: #ff6a00;
        }

        /* Hero Section */
        .hero {
            background: url("C:/Users/Nikol/Downloads/hospital_bed_vn_background_by_drechenaux_dg83a9z-pre.jpg") no-repeat center center/cover;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: black;
            padding: 0 20px;
        }
        .hero h1 {
            font-size: 4rem;
            font-weight: 600;
            margin: 0;
        }
        .hero p {
            font-size: 1.5rem;
            margin-top: 10px;
            max-width: 600px;
            line-height: 1.5;
        }
        .btn-primary {
            background-color: #49649a;
            padding: 12px 25px;
            color: white;
            font-size: 16px;
            font-weight: 600;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #49649a;
        }

        /* Main Content Sections */
        .section {
            padding: 80px 20px;
            text-align: center;
        }
        .section h2 {
            font-size: 2.5rem;
            font-weight: 600;
            margin-bottom: 30px;
        }
        .section img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }

        /* Grid Layout for Services */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 30px;
        }
        .service-card {
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        /* Service Card Link Styling */
        .service-card a {
            display: block;
            text-decoration: none;
            background-color: #49649a;
            padding: 15px;
            color: white;
            font-size: 1.4rem;
            font-weight: 600;
            text-align: center;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .service-card a:hover {
            background-color: #49649a;
        }

        /* Footer */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }
        footer p {
            font-size: 1rem;
            margin-bottom: 20px;
        }
        footer .social-icons a {
            margin: 0 10px;
            font-size: 1.5rem;
            color: white;
            text-decoration: none;
        }
        footer .social-icons a:hover {
            color: #49649a;
        }

        /* Responsiveness */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 3rem;
            }
            .hero p {
                font-size: 1.2rem;
                max-width: 90%;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
    <div class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#aboutus">About Us</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </div>

    <!-- Hero Section -->
    <div class="hero" id="home">
        <h1>Healthify</h1>
        <h3>The World's go to info desk</h3>
        <a href="#services" class="btn-primary">Explore Our Services</a>
    </div>

    <!-- Services Section -->
    <div class="section" id="services">
        <h2>Our Info Services</h2>
        <p>We offer a wide range of Info services designed to meet your health needs with the highest quality care.</p>
        <div class="services-grid">
            <div class="service-card">
                <a href="BMI calc.html">
                    <h3>BMI</h3>
                    <h3>Calculator</h3>
                </a>
            </div>
            <div class="service-card">
                <a href="HospitalFinder.html">
                    <h3>Nearby Hospitals</h3>
                </a>
            </div>
            <div class="service-card">
                <a href="HospitalFunding.html">
                    <h3>Hospital Fundraising</h3>
                </a>
            </div>
            <div class="service-card">
                <a href="Treatment Type.html">
                    <h3>Treatment</h3>
                    <h3>Info & Referances</h3>
                </a>
            </div>
        </div>
    </div>

    <!-- Doctors Section -->
    <div class="section" id="aboutus">
        <h2>About Us</h2>
        <p>Our info desk team consists of highly trained professionals dedicated to providing exceptional care.</p>
        <div class="services-grid">
            <div class="service-card">
                <h3>Dr. Nikolay Zhibarev</h3>
                <p>Info specialist with over 16 years processing info</p>
            </div>
            <div class="service-card">
                <h3>Dr. Maarten Van Roon</h3>
                <p> Info specialist with over 16 years processing info></p>
            </div>
        </div>
    </div>

    <!-- Contact Section -->
    <div class="section" id="contact">
        <h2>Contact Us</h2>
        <p>Have any questions or need assistance? Reach out to us!</p>
        <p>Email: contact@healthcare.com | Phone: (123) 456-7890</p>
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Healthcare Services | All Rights Reserved</p>
        <div class="social-media">
            <a href="#" class="fab fa-facebook-f">F</a>
            <a href="#" class="fab fa-twitter">T</a>
            <a href="#" class="fab fa-instagram">I</a>
        </div>
    </footer>

</body>
</html>
