<!DOCTYPE html>
<html lang="fr">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TFE - Lescut Lorie</title>
  <link rel="stylesheet" href="css/style.css">
</head>

<!-- Note perso : mise en page auto ALT SHIFT F !! -->

<body>
  <!-- HEADER -->
  <header>
    <div class="container header-flex">
      <img src="img/Logo Pop production v3.png" alt="Logo" class="logo">
      <h1>PoP Production </h1>
      <button class="menu-toggle" aria-label="Ouvrir le menu">☰</button>
      <nav class="nav-links">
        <a href="#acc" class="active">Accueil</a>
        <a href="#projets">Projets</a>
        <a href="#portfolio">Portfolio</a>
      <a href="#apropos">À propos</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>


  <main>
    <!-- ACCUEIL -->
    <section id="acc" class="acc fade-in">
      <div class="container">
        <h2>POP PRODUCTION by KINNIE GRAPH</h2>
        <p>Une autocollaboration d'une adulte et son enfant intérieur. </p>
        <a href="#projets" class="btn">Découvrez cet univers</a>
      </div>
    </section>

    <!-- PROJETS -->
    <section id="projets" class="projets fade-in">
      <div class="container">
        <h2>UN AMI POUR POPSKY</h2>
        <div class="projs">
          <div class="proj">
            <h3>Livre pour enfant</h3>
            <p>Réalisation d'un livre pour les enfants de 3 à 6 ans sur le thème de l'amitié et des différences.</p>
          </div>
          <div class="proj">
            <h3>Vidéo promotionnelle</h3>
            <p>Vidéo réalisée par mes soins avec l'aide de mes enfants, Aria et Pierce. </p>
          </div>
          <div class="proj">
            <h3>Peluches officielles</h3>
            <p>Popsky et Pimsky ont été créés à partir de matériaux 100% recyclés et avec amour.</p>
          </div>
        </div>
      </div>
    </section>


    <!-- GALERIE -->
     <img src="img/elemdroite.png" alt="Image flottante D" class="img-flottante-d">
    <section id="galerie" class="galerie fade-in">
      <h2>GALERIE PROMOTIONNELLE</h2>
      <div class="container">

        <div class="galerie-grid">
          <img src="img/livre.png" alt="Livre" data-title="Livre illustré <Un ami pour Popsky.>"
            data-description="Livre Illustré entièrement réalisé par Lescut Lorie. Ce livre aborde le thème de l'amitié et des différences. "
            data-price="5€">

          <img src="img/_DSC4607.png" alt="Popsky" data-title="Peluche Popsky"
            data-description="Petite peluche d'environ 40cm a l'effigie de Popsky entièrement réalisée à la main avec des matériaux recyclés."
            data-price="30€">

          <img src="img/_DSC4611.png" alt="Pimsky" data-title="Peluche Pimsky"
            data-description="Petite peluche d'environ 40cm a l'effigie de Pimsky entièrement réalisée à la main avec des matériaux recyclés."
            data-price="30€">

          <div class="video-container">
            <video src="img/videotest.mp4" title="Vidéo promo" frameborder="0" allowfullscreen> </video>
          </div>
        </div>
      </div>
    </section>

    <div id="lightbox" class="lightbox">
      <span class="close-lightbox">&times;</span>

      <div class="lightbox-content">
        <img id="lightbox-img" src="" alt="Aperçu">

        <div class="lightbox-info">
          <h3 id="lightbox-title">Titre du projet</h3>
          <p id="lightbox-description">Description courte...</p>
          <div class="lightbox-price" id="lightbox-price">Prix : 0€</div>
        </div>
      </div>
    </div>


  <!--  Portfolio -->
   <section id="portfolio" class="Portfolio">
    <h2>PORTFOLIO</h2>

	<div class="slider-wrapper">
		<div class="slider">
			<img id="slide-1" src="img/projet2.png" alt="Amethyste" />
			<img id="slide-2" src="img/projet5.png" alt="Sac a dos halloween"/>
			<img id="slide-3" src="img/projet6.png" alt="Ekko" />
      <img id="slide-4" src="img/projet7.png" alt="Bowser x Peach"/>
		</div>
		<div class="slider-nav">
			<a href="#slide-1"></a>
			<a href="#slide-2"></a>
			<a href="#slide-3"></a>
      <a href="#slide-4"></a>
		</div>
	</div>

</section>

<!-- A PROPOS -->
<section id="apropos" class="A Propos">
     <img src="img/elemgauche.png" alt="Image flottante G" class="img-flottante-g">

      <div class="apropos-container">

        <div class="apropos-image">
            <img src="img/Moi.png" alt="À propos image">
        </div>

        <div class="apropos-texte">
            <h2>À propos</h2>
            <p>Bienvenue dans notre univers !</p>
            <p>Je m'appelle Lescut Lorie, connue sous mon nom de graphiste Kinnie Graph et créatrice de l'univers de Popsky. Je suis âgée de 26 ans et
              je suis l'heureuse maman de deux petits amours qui se prénoment Aria et Pierce, âgés de 4 et 2 ans.</p>
            <p>Cette aventure est née en 2021 durant ma première grossesse pour mon TFE de 6e année secondaire. Popsky a été le premier personnage
              à être créé et à avoir marqué mon aventure scolaire. C'est donc avec une certaine logique qu'il viendra cloturer mes études bachelière.</p>
            <p> Avec ce projet, j'ai mis à rude épreuve ma patience et mon ambition afin de produire un travail qualitatif et qui représenterait tout ce 
              dont je suis capable.</p>

            <p> Merci à vous d'avoir pris part à cette aventure !</p>
        </div>

    </div>
</section>
    <!-- CONTACT -->
    <section id="contact" class="contact">
      <h2>Contact</h2>

      <form class="contact-form">
        <label>Nom</label>
        <input type="text" placeholder="Votre nom" required>

        <label>Email</label>
        <input type="email" placeholder="Votre email" required>

        <label>Message</label>
        <textarea placeholder="Votre message" required></textarea>

        <button type="submit">Envoyer</button>
      </form>

      <div class="map-container">
        <h2> Retrouvez-moi à cette adresse :</h2>
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5084.627021632276!2d4.4474823!3d50.4166302!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47c22609642bc019%3A0x9f7915cfd9f11bdc!2sInstitut%20Sup%C3%A9rieur%20Industriel%20(ISI)!5e0!3m2!1sfr!2sbe!4v1764857391716!5m2!1sfr!2sbe"
           width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        </iframe>
      </div>

      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer>
    <div class="footer-contenu">

      <p>&copy; ISI EA 2025-2026 - Lescut Lorie - Tout droits réservés</p>

      <div class="footer-logos">
        <a href="https://facebook.com" target="_blank">
        <img src="img/facebook.svg" alt="FB">
      </a>

         <a href="https://www.instagram.com/kinniegraph/" target="_blank">
                <img src="img/insta.svg" alt="INSTA">
      </a>
        
            <a href="https://www.tiktok.com/@kindraesher" target="_blank">
        <img src="img/tiktok.svg" alt="TT">

      </a>
            <a href="https://www.etudierenhainaut.be/institut-superieur-industriel.html" target="_blank">
        <img src="img/ecole.svg" alt="ISI EA">
      
      </a>
      </div>

    </div>
  </footer>

  <script src="js/script.js"></script>
</body>

</html>
