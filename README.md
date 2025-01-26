# transcend-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transcend Health | Primary Care Redefined</title>
    <style>
        /* Medical Blue Theme */
        :root {
            --primary-blue: #005eb8;
            --light-gray: #f5f7fa;
        }

        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
        }

        /* Logo Styling */
        .logo {
            font-family: 'Segoe UI', sans-serif;
            font-size: 32px;
            color: var(--primary-blue);
            font-weight: 600;
            text-decoration: none;
        }

        /* Navigation */
        nav {
            display: flex;
            align-items: center;
            padding: 1rem 5%;
            background: white;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        nav a {
            margin-left: 2rem;
            color: #333;
            text-decoration: none;
        }
        .portal-btn {
            margin-left: auto;
            background: var(--primary-blue);
            color: white;
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(0,94,184,0.9), rgba(0,94,184,0.9)), 
                        url('clinic-hero-placeholder.jpg');
            background-size: cover;
            color: white;
            padding: 6rem 2rem;
            text-align: center;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero button {
            background: #fff;
            color: var(--primary-blue);
            padding: 1rem 2rem;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            margin-top: 1rem;
        }

        /* Services Grid */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 2rem;
            padding: 4rem 5%;
            background: var(--light-gray);
        }
        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .service-card img {
            height: 80px;
            margin-bottom: 1rem;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <a href="#" class="logo">TRANSCEND HEALTH</a>
        <a href="#services">Services</a>
        <a href="#providers">Providers</a>
        <a href="#contact">Contact</a>
        <button class="portal-btn">Patient Portal</button>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Exceptional Care for Life's Journey</h1>
        <p>Same-Day Appointments Available</p>
        <button>Schedule Online</button>
    </section>

    <!-- Services Grid -->
    <section id="services" class="services-grid">
        <div class="service-card">
            <img src="icon-primary-care.png" alt="Primary Care Icon">
            <h3>Primary Care</h3>
            <p>Comprehensive health management for all ages</p>
        </div>
        <div class="service-card">
            <img src="icon-pediatrics.png" alt="Pediatrics Icon">
            <h3>Pediatrics</h3>
            <p>Specialized care for infants through adolescents</p>
        </div>
        <div class="service-card">
            <img src="icon-preventive.png" alt="Preventive Care Icon">
            <h3>Preventive Care</h3>
            <p>Vaccinations, screenings, and wellness plans</p>
        </div>
    </section>

    <!-- Add Providers, Contact, and Footer sections -->
</body>
</html>
