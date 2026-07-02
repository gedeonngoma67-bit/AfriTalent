# 🌍 AfriTalent

**Auteur :** Gedeon  
**Classe :** Licence Informatique – Réseaux Télécom 

**Année :** 2025–2026  

---

## Description
AfriTalent est une plateforme web qui met en avant les talents africains du numérique.  
Elle permet aux entreprises de découvrir des freelances qualifiés et de consulter les offres disponibles. 
---

## Technologies utilisées
- HTML5 / CSS3 / JavaScript  
- Bootstrap 5  
- LocalStorage (Dark Mode persistant)  
- GitHub Pages (déploiement en ligne)  

---

## Fonctionnalités principales
- Mode sombre / clair avec sauvegarde dans LocalStorage  
-  Filtrage dynamique des freelances par catégorie  
- Formulaire de contact validé en JavaScript (champs requis, email regex, message ≥ 20 caractères)  
- Design responsive (mobile, tablette, desktop)  
- Animations au scroll et compteurs dynamiques  
- Carousel Bootstrap pour les témoignages  

---

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>AfriTalent - Accueil</title>
    <link rel="stylesheet" href="css/style.css">
    <script src="js/main.js" defer></script>
</head>
<body>
    <header class="navbar">
        <h1>AfriTalent</h1>
        <nav>
            <a href="index.html">Accueil</a>
            <a href="freelances.html">Freelances</a>
            <a href="tarifs.html">Tarifs</a>
            <a href="about.html">À propos</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
</body>
</html>

  <section class="hero">
    <h2>LA PLATEFORME DES FREELANCES TECH EN AFRIQUE</h2>
    <p>Connectez-vous avec des Entreprises et des Talents.</p>
    <button><b>Je suis Freelance</b></button>
    <button><b>Je cherche un Freelance</b></button>
  </section>

  <footer>
    <p>&copy; 2026 AfriTalent</p>
  </footer>
</body>
</html>

<section id="freelances" class="fade-in hidden">
  <h2>Nos Freelances</h2>
  <div class="grid">
    <div class="card"><b>Thomas Durand :</b> Développeur Front-End Senior (Spécialisé en React et intégration pixel-perfect sur VS Code). TJM : 550 €</div>
    <div class="card"><b>Sarah Alami :</b> Développeuse Full-Stack (Experte Node.js et bases de données, idéale pour créer des applications de A à Z). TJM : 600 €</div>
    <!-- 9 cartes minimum -->
  </div>
  <!-- cartes freelances -->
</section>


<section id="tarifs" class="slide-left hidden">
  <h2>Nos Offres</h2>
  <div class="plans">
    <div class="card">Gratuit</div>
    <div class="card">Pro</div>
    <div class="card">Entreprise</div>
  </div>
  <!-- cartes tarifs -->
</section>


<!-- Section Nos Offres -->
<section id="tarifs" class="slide-left hidden">
  <h2>Nos Offres</h2>
  <div class="plans">
    <div class="card">
      <h3>Gratuit</h3>
      <p>0 €/mois</p>
      <ul>
        <li>Accès à la plateforme</li>
        <li>Recherche de freelances</li>
        <li>Support standard</li>
      </ul>
      <button>Choisir</button>
    </div>

    <div class="card">
      <h3>Pro</h3>
      <p>29 €/mois</p>
      <ul>
        <li>Mise en relation prioritaire</li>
        <li>Tableau de bord avancé</li>
        <li>Support 24h/7j</li>
      </ul>
      <button>Choisir</button>
    </div>

    <div class="card">
      <h3>Entreprise</h3>
      <p>99 €/mois</p>
      <ul>
        <li>Gestionnaire de compte dédié</li>
        <li>Facturation centralisée</li>
        <li>Contrats personnalisés</li>
      </ul>
      <button>Choisir</button>
    </div>
  </div>
</section>

<section id="Histoire" class="fade-in hidden">
  <h2>Notre Histoire</h2>
  <div class="about-content">
    <p>
      <b>AfriTalent</b> est né de la volonté de connecter les talents africains du numérique avec les entreprises qui recherchent innovation et expertise. Notre plateforme met en avant des freelances passionnés, créatifs et compétents, tout en offrant aux sociétés un accès simple et rapide à des profils qualifiés.
Nous croyons en la force de la collaboration et en l’impact des projets technologiques sur le développement du continent.
    </p>
    <img class="image-histoire" src="c:\Users\Lenovo\Desktop\image\histoire.png" alt="Notre histoire AfriTalent">
  </div>

  <h3>L’équipe</h3>
  <p>
    Notre équipe est composée de jeunes développeurs, designers et stratèges qui partagent une vision commune : valoriser les compétences locales et créer des opportunités durables.
  </p>
  <div class="team">
    <div class="card">Membre 1 : <h4>Amadou Diop</h4> 24 ans Passionné par le code open-source. Il crée des applications web fluides et légères. Il optimise le code pour les connexions locales limitées. Son but est de rendre la technologie accessible à tous.</div>
    <div class="card">Membre 2 : <h4>Amina Dialla</h4> 23 ans Spécialiste de l'identité visuelle et de l'ergonomie. Elle s'inspire des motifs culturels locaux pour ses créations graphiques. Elle conçoit des interfaces intuitives adaptées aux habitudes des utilisateurs de la région.</div>
    <div class="card">Membre 3 : <h4>Thomas Mendy</h4> 26 ans Expert en croissance et en analyse de marché. Il connecte les talents de l'équipe avec les entreprises locales. Il bâtit des modèles économiques viables pour garantir des emplois durables aux jeunes diplômés.</div>
    <div class="card">Membre 4 : <h4>Fatou Fall</h4> 25 ans Experte en méthodologies agiles. Elle traduit la vision stratégique en plans de travail concrets. Elle organise des ateliers avec les artisans et entrepreneurs de la communauté pour intégrer directement leurs besoins dans les outils créés.</div>
  </div>
  <!-- cartes membres -->
</section>

<section id="contact" class="fade-in hidden">
  <h2>Contactez-Nous</h2>
  <form>
    <input type="text" placeholder="NOM" required>
    <input type="text" placeholder="PRENOM" required>
    <input type="email" placeholder="ADRESSE EMAIL" required>
    <select required>
      <option>Sujet</option>
      <option>Info</option>
      <option>Support</option>
    </select>
    <textarea minlength="20" placeholder="Message"></textarea>
    <button type="submit">Envoyer</button>
    <img src="c:\Users\Lenovo\Pictures\ChatGPT Image 23 juin 2026, 22_08_27.png">
  </form>
  <!-- cartes contact -->
</section>

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #121212;
  color: #fcf5f5;
}

.navbar {
  background: #1e1e1e;
  padding: 1rem;
  display: flex;
  justify-content: space-between;
}

.navbar a {
  color: #f0f0f0;
  margin: 0 0.5rem;
  text-decoration: none;
}

.navbar a:hover {
  color: #ff9800;
}

.hero {
  text-align: center;
  padding: 3rem;
}

button {
  background: #ff9800;
  border: none;
  padding: 0.7rem 1.2rem;
  margin: 0.5rem;
  cursor: pointer;
}

button:hover {
  background: #ffa733;
}

.card {
  background: #1e1e1e;
  padding: 1rem;
  margin: 1rem;
  border-radius: 5px;
  cursor : pointer;
}


/* Animation fade-in (Nos Freelances) */
.fade-in {
  opacity: 0;
  transform: translateY(30px);
  transition: all 0.8s ease-out;
}
.fade-in.show {
  opacity: 1;
  transform: translateY(0);
}

/* Animation slide-in gauche (Nos Offres) */
.slide-left {
  opacity: 0;
  transform: translateX(-50px);
  transition: all 0.8s ease-out;
}
.slide-left.show {
  opacity: 1;
  transform: translateX(0);
}

/* Animation zoom-in (Équipe) */
.zoom-in {
  opacity: 0;
  transform: scale(0.8);
  transition: all 0.8s ease-out;
}
.zoom-in.show {
  opacity: 1;
  transform: scale(1);
}


#tarifs {
  padding: 50px;
  background-color: #111; /* fond sombre */
  color: #fff;
  text-align: center;
}

.plans {
  display: flex;
  flex-wrap: wrap; /* permet de passer en colonne sur petits écrans */
  justify-content: center;
  gap: 20px;
  margin-top: 30px;
}

.plans .card {
  background: #0f0f0f;
  color: #f0f0f0;
  padding: 30px;
  border-radius: 10px;
  flex: 1 1 250px; /* largeur minimale */
  max-width: 300px;
  box-shadow: 0 0 10px rgba(255,255,255,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.plans .card:hover {
  transform: translateY(-5px);
  box-shadow: 0 0 15px rgba(255,255,255,0.3);
}

/* Variables CSS */
:root {
  --primary-color: #ff6600;
  --secondary-color: #ffffff;
  --font-main: 'Arial', sans-serif;
}

body {
  margin: 0;
  font-family: var(--font-main);
  background-color: #030303;
}

h1 {
  color: var(--primary-color);
}

.image-afritalent {
    width: 80%;
    max-width: 900px;
    height: auto;

    display: block;
    margin: 20px auto;
}

.image-histoire {

    width: 600px;
    height: 300px;

    object-fit: cover;

    display: block;

    margin: 30px auto;

    border-radius: 10px;
}

// === Dark Mode / Light Mode ===
const toggleBtn = document.getElementById("darkModeToggle");
const body = document.body;

// Charger le thème sauvegardé
if (localStorage.getItem("theme") === "dark") {
  body.classList.add("dark");
}

if (toggleBtn) {
  toggleBtn.addEventListener("click", () => {
    body.classList.toggle("dark");
    if (body.classList.contains("dark")) {
      localStorage.setItem("theme", "dark");
    } else {
      localStorage.setItem("theme", "light");
    }
  });
}

// === Navbar dynamique au scroll ===
const navbar = document.querySelector(".navbar");
window.addEventListener("scroll", () => {
  if (window.scrollY > 50) {
    navbar.classList.add("scrolled");
  } else {
    navbar.classList.remove("scrolled");
  }
});

// === Bouton retour en haut ===
const backToTop = document.getElementById("backToTop");
window.addEventListener("scroll", () => {
  if (window.scrollY > 200) {
    backToTop.style.display = "block";
  } else {
    backToTop.style.display = "none";
  }
});
if (backToTop) {
  backToTop.addEventListener("click", () => {
    window.scrollTo({ top: 0, behavior: "smooth" });
  });
}

// === Compteurs animés ===
const counters = document.querySelectorAll(".counter");
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      const counter = entry.target;
      let target = +counter.getAttribute("data-target");
      let count = 0;
      const update = setInterval(() => {
        if (count < target) {
          count++;
          counter.textContent = count;
        } else {
          clearInterval(update);
        }
      }, 20);
      observer.unobserve(counter);
    }
  });
});
counters.forEach(c => observer.observe(c));

// === Filtrage freelances ===
const filterBtns = document.querySelectorAll(".filter-btn");
const cards = document.querySelectorAll(".freelance-card");

filterBtns.forEach(btn => {
  btn.addEventListener("click", () => {
    const category = btn.getAttribute("data-category");
    cards.forEach(card => {
      if (category === "all" || card.classList.contains(category)) {
        card.style.display = "block";
      } else {
        card.style.display = "none";
      }
    });
  });
});


// === Validation formulaire contact ===
const form = document.querySelector("form");
if (form) {
  form.addEventListener("submit", e => {
    e.preventDefault();
    let valid = true;

    const email = form.querySelector("input[type='email']");
    const message = form.querySelector("textarea");

    // Vérif email
    const regex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!regex.test(email.value)) {
      valid = false;
      alert("Email invalide !");
    }

    // Vérif longueur message
    if (message.value.length < 20) {
      valid = false;
      alert("Message trop court (20 caractères min)");
    }

    if (valid) {
      alert("Message envoyé avec succès !");
      form.reset();
    }
  });
  
}

document.addEventListener("DOMContentLoaded", () => {
  const hiddenElements = document.querySelectorAll(".hidden");

  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add("show");
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.2 });

  hiddenElements.forEach(el => observer.observe(el));
});

// Script principal AfriTalent
console.log("Bienvenue sur AfriTalent !");


## Capture d’écran
## Capture d’écran

![Capture du site AfriTalent](<img width="1352" height="676" alt="Capture d&#39;écran 2026-06-10 003641" src="https://github.com/user-attachments/assets/5c577b9c-423e-448c-89b3-1ee929360108" />


---

## Lancer le projet localement
1. Clone le dépôt :  
   ```bash
   git clone https://github.com/NGOMA-Emmanuel-AfriTalent.git

Ouvre le fichier index.html dans ton navigateur.

Navigue entre les pages via la navbar.

## Ressources consultées
- [Bootstrap 5 Documentation](https://getbootstrap.com)  
- [MDN Web Docs](https://developer.mozilla.org)  
- [W3Schools](https://www.w3schools.com)

## 🏁 Déploiement
Le site est accessible en ligne via GitHub Pages :  
👉 [https://NGOMA-Emmanuel-Gedeon.github.io/AfriTalent](https://NGOMA-Emmanuel-Gedeon.github.io/AfriTalent)
