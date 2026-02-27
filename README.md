# car-rental-business-websit
A responsive and modern car rental business website built using HTML, CSS, and Bootstrap 5 for Sri Guru Car Rentals, Hospet.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sri Guru Car Rentals | Reliable & Affordable Travel in Hospet</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>
  <style>
    :root {
      --primary: #1e40af;      /* Professional blue */
      --secondary: #3b82f6;
      --dark: #111827;
      --light: #f8fafc;
    }
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; color: var(--dark); background: var(--light); }
    .navbar { background: white !important; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
    .navbar-brand { font-weight: bold; color: var(--primary) !important; font-size: 1.6rem; }
    .hero { background: linear-gradient(rgba(30,64,175,0.7), rgba(30,64,175,0.7)), url('https://images.unsplash.com/photo-1502877338535-766e1452684a?auto=format&fit=crop&q=80') center/cover no-repeat; color: white; padding: 150px 0 100px; text-align: center; }
    .hero h1 { font-size: 3.5rem; font-weight: 700; margin-bottom: 20px; }
    .hero p { font-size: 1.4rem; margin-bottom: 30px; }
    .btn-primary { background: var(--primary); border: none; padding: 14px 32px; font-size: 1.2rem; }
    .section-title { text-align: center; margin-bottom: 50px; font-weight: 700; color: var(--primary); }
    .feature-card { transition: all 0.3s; border: none; box-shadow: 0 5px 20px rgba(0,0,0,0.08); }
    .feature-card:hover { transform: translateY(-10px); box-shadow: 0 15px 30px rgba(0,0,0,0.12); }
    .feature-icon { font-size: 3rem; color: var(--secondary); margin-bottom: 20px; }
    .car-card img { height: 220px; object-fit: cover; border-radius: 10px 10px 0 0; width: 100%; }
    .contact { background: var(--dark); color: white; padding: 80px 0; }
    .contact h2 { color: white; }
    .contact .phone { font-size: 2.5rem; font-weight: bold; color: #60a5fa; }
    footer { background: var(--primary); color: white; padding: 30px 0; text-align: center; }
    @media (max-width: 768px) {
      .hero h1 { font-size: 2.8rem; }
      .hero { padding: 120px 0 80px; }
    }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Sri Guru Car Rentals</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#services">Services</a></li>
        <li class="nav-item"><a class="nav-link" href="#fleet">Fleet</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- Hero Section -->
<section id="home" class="hero">
  <div class="container">
    <h1>Reliable Car Rentals in Hospet</h1>
    <p>Comfortable, Safe & Affordable Journeys – Local, Outstation, Airport Transfers & More</p>
    <a href="tel:+918722551326" class="btn btn-primary btn-lg">Book Now: +91 8722551326</a>
  </div>
</section>

<!-- Services / Features -->
<section id="services" class="py-5">
  <div class="container">
    <h2 class="section-title">Why Choose Sri Guru?</h2>
    <div class="row g-4">
      <div class="col-md-3">
        <div class="card feature-card text-center p-4">
          <i class="fa-solid fa-car-side feature-icon"></i>
          <h4>Well-Maintained Fleet</h4>
          <p>Regular servicing, AC, clean & comfortable vehicles</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card feature-card text-center p-4">
          <i class="fa-solid fa-user-shield feature-icon"></i>
          <h4>Experienced Drivers</h4>
          <p>Verified, polite & safe drivers with 10+ years experience</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card feature-card text-center p-4">
          <i class="fa-solid fa-indian-rupee-sign feature-icon"></i>
          <h4>Best Prices</h4>
          <p>No hidden charges – Transparent & affordable rates</p>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card feature-card text-center p-4">
          <i class="fa-solid fa-headset feature-icon"></i>
          <h4>24×7 Support</h4>
          <p>Instant booking & roadside assistance anytime</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Fleet Showcase - All Bolero Images -->
<section id="fleet" class="py-5 bg-light">
  <div class="container">
    <h2 class="section-title">Our Vehicles</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card car-card">
          <img src="https://static-cdn.team-bhp.com/prod/new-car-cms/Mahindra_Bolero_exterior_4_81b34ba2e3.jpg" alt="Mahindra Bolero White Side View">
          <div class="card-body text-center">
            <h5>Mahindra Bolero</h5>
            <p>Ideal for city & short trips – Starts @ ₹1400/day</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card car-card">
          <img src="https://media.spinny.com/sp-file-system/public/2024-09-12/107603832bd141f99aba6974ad13e5e6/file.JPG" alt="Mahindra Bolero White Professional Side">
          <div class="card-body text-center">
            <h5>Mahindra Bolero</h5>
            <p>Comfort for family & long tours – Starts @ ₹2500/day</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card car-card">
          <img src="https://cdn-s3.autocarindia.com/Mahindra/bolero-neoplus/OP708414.jpg" alt="Mahindra Bolero White Front Three-Quarter">
          <div class="card-body text-center">
            <h5>Mahindra Bolero</h5>
            <p>Premium comfort for groups & weddings</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Contact / Booking -->
<section id="contact" class="contact">
  <div class="container text-center">
    <h2>Ready to Travel?</h2>
    <p class="lead mb-4">Call us now or email for instant booking & quotes</p>
    <div class="phone mb-3"><i class="fa-solid fa-phone-volume me-2"></i> +91 8722551326</div>
    <div class="mb-4"><i class="fa-solid fa-envelope me-2"></i> viru08394@gmail.com</div>
    <p>Hospet (Hosapete), Vijayanagara District, Karnataka – 583201</p>
  </div>
</section>

<!-- Footer -->
<footer>
  <div class="container">
    <p>© 2026 Sri Guru Car Rentals. All Rights Reserved. | <a href="tel:+919731115426" style="color:white;">Book Now</a></p>
  </div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
