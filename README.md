<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Military ERP System</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #0a0a23;
            color: white;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        header {
            background: #1e1e2e;
            padding: 20px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #00c3ff;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: url('E:\military-erp\hero-image.jpg') no-repeat center center/cover;
            padding: 100px 0;
        }
        .hero h1 {
            font-size: 2.5em;
        }
        .btn {
            background: #00c3ff;
            color: #0a0a23;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 40px 0;
        }
        .feature-box {
            width: 45%;
            padding: 20px;
            background: #1e1e2e;
            margin: 10px;
            border-radius: 8px;
        }
        .feature-box img {
            width: 100%;
            border-radius: 8px;
        }
        .map-section {
            background: #141414;
            padding: 50px 0;
        }
        footer {
            background: #1e1e2e;
            color: white;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <ul>
                    <li><a href="#">Dashboard</a></li>
                    <li><a href="#">Operations</a></li>
                    <li><a href="#">Logistics</a></li>
                    <li><a href="#">Communications</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <section class="hero">
        <div class="container">
            <h1>Military ERP System</h1>
            <p>Advanced solutions for military operations, logistics, and communication.</p>
            <button class="btn">Get Started</button>
        </div>
    </section>
    
    <section class="features">
        <div class="feature-box">
            <img src="secure-data.jpg" alt="Secure Data">
            <h2>Secure Data Management</h2>
            <p>Ensure top-tier security and encryption for mission-critical data.</p>
        </div>
        <div class="feature-box">
            <img src="operations.jpg" alt="Operations">
            <h2>Operational Efficiency</h2>
            <p>Streamline military operations with intelligent resource planning.</p>
        </div>
        <div class="feature-box">
            <img src="communications.jpg" alt="Communications">
            <h2>Real-Time Communications</h2>
            <p>Facilitate secure and instant communication across all units.</p>
        </div>
        <div class="feature-box">
            <img src="logistics.jpg" alt="Logistics">
            <h2>Logistics & Supply Chain</h2>
            <p>Track and manage military supplies with real-time insights.</p>
        </div>
    </section>
    
    <section class="map-section">
        <div class="container">
            <h2>Global Military Operations</h2>
            <p>160+ bases worldwide, 94 active deployments.</p>
            <img src="world-map.png" alt="Military Bases Map">
        </div>
    </section>
    
    <footer>
        <p>&copy; 2025 Military ERP System. All Rights Reserved.</p>
    </footer>
</body>
</html>
