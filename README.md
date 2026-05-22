<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Ingénieur Informatique</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Barre de navigation -->
  <header>
    <nav class="navbar">
      <h1 class="logo">MonPortfolio</h1>
      <ul class="nav-links">
        <li><a href="#accueil">Accueil</a></li>
        <li><a href="#apropos">À propos</a></li>
        <li><a href="#competences">Compétences</a></li>
        <li><a href="#projets">Projets</a></li>
        <li><a href="#experience">Expérience</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Section Héro -->
  <section id="accueil" class="hero">
    <div class="hero-content">
      <h2>Bonjour, je suis <span>[Ton Nom]</span></h2>
      <p>Ingénieur en Informatique | Spécialiste en Développement Full-Stack</p>
      <p>"Je conçois et développe des solutions logicielles robustes et scalables."</p>
      <div class="cta">
        <a href="#projets" class="btn">Voir mes projets</a>
        <a href="cv.pdf" class="btn">Télécharger mon CV</a>
      </div>
    </div>
  </section>

  <!-- À propos -->
  <section id="apropos" class="section">
    <h2>À propos</h2>
    <p>Passionné par l’innovation technologique et la résolution de problèmes complexes, 
       je suis ingénieur en informatique diplômé de [Université]. 
       Curieux et rigoureux, j’aime transformer des besoins métiers en lignes de code performantes.</p>
  </section>

  <!-- Compétences -->
  <section id="competences" class="section">
    <h2>Compétences Techniques</h2>
    <div class="skills-grid">
      <div><strong>Langages :</strong> Java, Python, JavaScript, C++, SQL</div>
      <div><strong>Frameworks :</strong> Spring Boot, Django, React, JavaFX</div>
      <div><strong>Cloud & DevOps :</strong> Docker, AWS, Git, CI/CD, Kubernetes</div>
      <div><strong>Méthodologies :</strong> Agile, Microservices, Tests unitaires</div>
    </div>
  </section>

  <!-- Projets -->
  <section id="projets" class="section">
    <h2>Projets Phares</h2>
    <div class="projects-grid">
      <div class="card">
        <img src="projet1.png" alt="Projet 1">
        <h3>Système de Gestion de Données</h3>
        <p>Amélioration des performances de +20% grâce à une architecture optimisée.</p>
        <p><em>Technologies :</em> Python, PostgreSQL</p>
        <a href="#" class="btn">Voir en ligne</a>
        <a href="#" class="btn">Code GitHub</a>
      </div>
    </div>
  </section>

  <!-- Expérience -->
  <section id="experience" class="section">
    <h2>Expériences</h2>
    <ul class="timeline">
      <li><strong>2026 - Ingénieur Logiciel</strong> chez [Entreprise] – Missions clés et accomplissements.</li>
      <li><strong>2024 - Stage</strong> chez [Entreprise] – Développement d’applications web.</li>
      <li><strong>Diplôme</strong> : Master en Informatique – [Université]</li>
    </ul>
  </section>

  <!-- Contact -->
  <section id="contact" class="section contact-section">
    <h2>Contact</h2>
    <form class="contact-form">
      <input type="text" placeholder="Nom" required>
      <input type="email" placeholder="Email" required>
      <input type="text" placeholder="Objet" required>
      <textarea placeholder="Message" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
    <div class="socials">
      <a href="#">LinkedIn</a> | <a href="#">GitHub</a> | <a href="mailto:email@example.com">Email</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2026 [Ton Nom]. Tous droits réservés.</p>
  </footer>
</body>

<style>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #121212;
  color: #f0f0f0;
}

.navbar {
  display: flex;
  justify-content: space-between;
  padding: 1rem;
  background: #1e1e1e;
  position: fixed;
  width: 100%;
  top: 0;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 1rem;
}

.nav-links a {
  color: #00e0ff;
  text-decoration: none;
}

.hero {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}

.btn {
  background: #00e0ff;
  color: #121212;
  padding: 0.5rem 1rem;
  margin: 0.5rem;
  text-decoration: none;
  border-radius: 5px;
}

.section {
  padding: 4rem 2rem;
}

.skills-grid, .projects-grid {
  display: grid;
  gap: 1rem;
}

.card {
  background: #1e1e1e;
  padding: 1rem;
  border-radius: 8px;
}

.timeline {
  list-style: none;
  padding: 0;
}

/* 🎨 Contact Section */
.contact-section {
  background: #1e1e1e;
  border-radius: 8px;
  padding: 2rem;
}

.contact-form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.contact-form input,
.contact-form textarea {
  padding: 0.8rem;
  border: none;
  border-radius: 5px;
  background: #2a2a2a;
  color: #f0f0f0;
}

.contact-form input:focus,
.contact-form textarea:focus {
  outline: 2px solid #00e0ff;
}

.contact-form button {
  background: #00e0ff;
  color: #121212;
  padding: 0.8rem;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.contact-form button:hover {
  background: #00ff88;
  transition: 0.3s;
}

.socials {
  margin-top: 1rem;
  text-align: center;
}

.socials a {
  color: #00e0ff;
  margin: 0 0.5rem;
  text-decoration: none;
}

.socials a:hover {
  color: #00ff88;
}
</style>

</html>
