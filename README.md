<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Salon Élégance</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fdfdfd;
      color: #333;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background-color: #575757;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      margin: 10px;
    }
    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .services {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }
    @media (max-width: 768px) {
      .services {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Salon Élégance</h1>
    <p>Votre beauté, notre passion</p>
  </header>
  <nav>
    <a href="#about">À propos</a>
    <a href="#services">Services</a>
    <a href="#gallery">Galerie</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="about">
    <h2>À propos</h2>
    <p>Bienvenue au Salon Élégance, où chaque coiffure est une œuvre d'art. Notre équipe de professionnels vous accueille dans un cadre chaleureux pour révéler votre beauté naturelle.</p>
  </section>
  <section id="services">
    <h2>Nos Services</h2>
    <div class="services">
      <div><strong>Coupe & Brushing</strong><br/>Pour femme, homme et enfant</div>
      <div><strong>Coloration & Mèches</strong><br/>Des nuances éclatantes et sur-mesure</div>
      <div><strong>Lissage</strong><br/>Brillance et douceur longue durée</div>
      <div><strong>Soins capillaires</strong><br/>Des traitements profonds pour cheveux abîmés</div>
    </div>
  </section>
  <section id="gallery">
    <h2>Galerie</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/300x200?text=Coiffure+1" alt="Coiffure 1">
      <img src="https://via.placeholder.com/300x200?text=Coiffure+2" alt="Coiffure 2">
      <img src="https://via.placeholder.com/300x200?text=Coiffure+3" alt="Coiffure 3">
    </div>
  </section>
  <section id="contact">
    <h2>Contact</h2>
    <p>Adresse : 123 Rue de la Beauté, Paris<br/>
    Téléphone : 01 23 45 67 89<br/>
    Email : contact@salon-elegance.fr</p>
  </section>
  <footer>
    <p>&copy; 2025 Salon Élégance. Tous droits réservés.</p>
  </footer>
</body>
</html># TIAMA-ADAM-S-COIFFURE-
