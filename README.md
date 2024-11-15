<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scootico - Your Green Companion On The Go</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            color: #333;
            line-height: 1.6;
            background-color: #f4f4f9;
        }

        header, section {
            padding: 20px;
        }

        h1, h2 {
            color: #3a9d23;
        }

        /* Header Styles */
        header {
            background-color: #f9f9f9;
            color: #000000;
            text-align: center;
            padding: 40px 0;
        }

        header h1 {
            font-size: 2.5em;
        }

        header p {
            font-size: 1.2em;
            font-weight: 300;
        }

        /* Navigation Styles */
        nav {
            display: flex;
            justify-content: center;
            gap: 15px;
            padding: 10px;
            background: #333;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            background: #3a9d23;
            border-radius: 5px;
        }

        /* Sections */
        section {
            max-width: 800px;
            margin: auto;
        }

        .section-title {
            margin: 20px 0;
        }

        .features, .specs, .connectivity {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }

        .feature-item, .spec-item, .connect-item {
            flex: 1 1 200px;
            background-color: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        /* Call to Action */
        .cta {
            text-align: center;
        }

        .cta button {
            padding: 10px 20px;
            background: #3a9d23;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Scootico</h1>
        <p>Your Green Companion On The Go</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#about">Introduction</a>
        <a href="#features">Features</a>
        <a href="#specs">Specifications</a>
        <a href="#connectivity">Connectivity</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Introduction Section -->
    <section id="about">
        <h2 class="section-title">Introduction</h2>
        <p>Meet Scootico, the eco-friendly electric scooter designed for modern urban commuters. 
           With zero emissions and sleek design, Scootico is your sustainable companion on the go. 
           Ride smoothly and comfortably while helping reduce your carbon footprint.</p>
    </section>

    <!-- Features Section -->
    <section id="features">
        <h2 class="section-title">Key Features</h2>
        <div class="features">
            <div class="feature-item">
                <h3>Eco-Friendly</h3>
                <p>Zero emissions and a powerful electric motor for a sustainable ride.</p>
            </div>
            <div class="feature-item">
                <h3>Long Battery Life</h3>
                <p>Go up to 40 kilometres on a single charge, perfect for local commutes.</p>
            </div>
            <div class="feature-item">
                <h3>Smart Braking</h3>
                <p>Equipped with regenerative braking technology for safe and efficient stops.</p>
            </div>
        </div>
    </section>

    <!-- Specifications Section -->
    <section id="specs">
        <h2 class="section-title">Specifications</h2>
        <div class="specs">
            <div class="spec-item">
                <h3>Top Speed</h3>
                <p>15 mph (25 km/h)</p>
            </div>
            <div class="spec-item">
                <h3>Battery Capacity</h3>
                <p>660 Whr</p>
            </div>
            <div class="spec-item">
                <h3>Weight Capacity</h3>
                <p>Up to 150 kg</p>
            </div>
            <div class="spec-item">
                <h3>Charging Time</h3>
                <p>4-5 hours</p>
            </div>
        </div>
    </section>

    <!-- Connectivity Section -->
    <section id="connectivity">
        <h2 class="section-title">Connectivity</h2>
        <div class="connectivity">
            <div class="connect-item">
                <h3>Smart App</h3>
                <p>Connect to our app for real-time ride stats, battery tracking, and route planning.</p>
            </div>
            <div class="connect-item">
                <h3>Bluetooth Enabled</h3>
                <p>Control your scooter remotely, lock/unlock, and monitor from your phone.</p>
            </div>
            <div class="connect-item">
                <h3>GPS Tracking</h3>
                <p>Stay connected with built-in GPS for easy tracking and enhanced security.</p>
            </div>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section class="cta">
        <h2>Ready to Ride?</h2>
        <p>Join the green revolution and make Scootico your daily ride. Eco-friendly, efficient, and connected – 
           Scootico has everything you need for a smarter, greener commute.</p>
        <a href="mailto:sreejithsivan2003191@gmail.com?subject=Order%20Inquiry%20for%20Scootico&body=Hello%20Sreejith%2C%0A%0AI%20am%20interested%20in%20ordering%20the%20Scootico%20electric%20scooter.%20Please%20provide%20more%20details%20about%20the%20ordering%20process.%0A%0AThank%20you.%0A%0ARegards%2C%0A[Your%20Name]"
           style="text-decoration: none;">
           <button>Order Now</button>
        </a> 
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2 class="section-title">Contact</h2>
        <p>Contact: <strong>Sreejith S</strong></p>
        <p>Email: sreejithsivan2003191@gmail.com</p>
        <p>Feel free to reach out for more information or assistance with your order.</p>
        
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Scootico. All Rights Reserved.</p>
    </footer>

</body>
</html>
