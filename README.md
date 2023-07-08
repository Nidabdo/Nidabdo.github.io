<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="css/reset.css">
    <title>Portfolio</title>
    <script src="index.js"></script>
    <script type="text/javascript"
        src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js">
    </script>
    <script type="text/javascript">
      (function(){
          emailjs.init("jZWwSnl782US_8SI2");
      })();
    </script>
</head> 
<body>
  <nav>
    <div class="main-nav">
      <li class="navigation">
        <a href="#home" >HOME</a>
        <a href="#about">ABOUT ME</a>
        <a href="#experience">EXPERIENCE</a> 
        <a href="#parcours">PARCOURS</a>
        <a href="#contact">CONTACT</a>
      </li>
    </div>
  </nav>
  <section id="home">
      <article class="hp-center-text">
        <h2>Nicolas Lambert</h2>
        <p class="typing-effect">Recherche alternance Developpeur Web</p>
      </article>
  </section>
  <section id="about">
    <h2>About me</h2>
      <article>
        <div class="profil">
          <div class="cadre"><a href="https://www.linkedin.com/in/nicolas-lambert-980465241/" target="_blank"><img src="images/moi.jpeg" alt="lien vers linkedin" title="Nicolas Lambert"></a></div>
          <div class="desc">
            <b>Présentation :</b><br><br>
            Actuellement en formation DISII (Développeur Intégrateur de Solutions Internet et Intranet) au Havre chez ScholarFab, je suis à la recherche d'une alternance pour poursuivre mon parcours professionnel dans le développement sur Le Havre ou Caen.<br><br>
            Je suis passionné par le développement et j'ai hâte de rejoindre une entreprise dynamique où je pourrais travailler sur des projets passionnants. <br><br>
          </div>
        </div>
        <div class="profil-bas">
          <div class="info">
            <b>Nom : </b>Lambert <br>
            <b>Prénom : </b>Nicolas <br>
            <b>Age : </b> 21 ans <br>
            <b>Email : </b>nicolas.lambert02@orange.fr <br>
            <b>Tel : </b>06 88 69 80 33
          </div>
          <div class="skill">
            <b>Compétences :</b> 
            <div class="langage">
              <img src="images/html.png" alt="html">
              <img src="images/css-3.png" alt="css">
              <img src="images/js.png" alt="js">
              <img src="images/php.png" alt="php">
              <img src="images/mysql.png" alt="mysql">
            </div>
            <div></div>
          </div>
        </div>
      </article>
  </section>
  <section id="experience">
      <article>
        <h2>Mes expériences</h2><br><br>
        <div class="xp-container">
          <div class="xp-box">
            <div class="hp-center-text">
              <img src="images/cat-line-logo.png" alt="cat-line">
            </div>
              <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus sed, deserunt ipsam cupiditate aperiam modi vitae, deleniti consectetur quisquam, temporibus aliquam officia in adipisci! Cupiditate, repellendus nostrum. Beatae, voluptas numquam.</div>
          </div>
          <div class="xp-box">
            <div class="hp-center-text">
              <img src="images/logo-eram.png" alt="eram" width="100px">
            </div>
            <div>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Asperiores in incidunt porro ducimus, vero illo, nulla eum vitae perspiciatis, iste laudantium soluta doloribus sit nesciunt quas voluptas atque quidem. Fuga.`</div>
          </div>
          <div class="xp-box">
            <div class="hp-center-text">
              <img src="images/Logo_Intermarché.svg.png" alt="intermarché" width="300px">
            </div>
            <div>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Asperiores in incidunt porro ducimus, vero illo, nulla eum vitae perspiciatis, iste laudantium soluta doloribus sit nesciunt quas voluptas atque quidem. Fuga.`</div>
          </div>
        </div>
      </article>
  </section>
  <section id="parcours">
      <article>
        <h2>Mon parcours</h2>
          <div class="parcours-container">
            <div class="parcours-card1">
              <img src="images/scholarfab-logo.png" alt="scholarfab-logo">
              <h2>Scholar Fab</h2>
              <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Necessitatibus sed, deserunt ipsam cupiditate aperiam modi vitae, deleniti consectetur quisquam, temporibus aliquam officia in adipisci! Cupiditate, repellendus nostrum. Beatae, voluptas numquam.</div>
            </div>
            <div class="parcours-card2">
              <img src="images/iut-lehavre-logo.png" alt="iut-lehavre-logo">
              <h2>IUT Le Havre</h2>
              <div>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Asperiores in incidunt porro ducimus, vero illo, nulla eum vitae perspiciatis, iste laudantium soluta doloribus sit nesciunt quas voluptas atque quidem. Fuga.`</div>
            </div>
            <div class="parcours-card3">
              <img src="images/lycee-logo.png" alt="lycee-logo">
              <h2>Lycée Jules Siegfried</h2>
              <div>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Et iste voluptatibus tenetur voluptas, animi dolores. Explicabo laboriosam reiciendis obcaecati cumque. Doloribus, natus! Distinctio explicabo enim, officia ea ratione sunt cupiditate.</div>
            </div>
          </div>
      </article>
  </section>
  <section id="contact">
      <article>
        <div class="container2">
          <div class="form-container">
            <div class="form-reseaux">
              <h3>Pour me contacter :</h3><a href="https://github.com/Nidabdo" target="_blank"><img src="./images/github.png" alt="github"></a><a href="https://www.linkedin.com/in/nicolas-lambert-980465241/" target="_blank"><img src="./images/linkedin.png" alt="linkedin"></a><a href="mailto:nicolas.lambert02@orange.fr"><img src="./images/email.png" alt="email"></a>
            </div>
            <form id="contact-form">
              <input type="hidden" name="contact_number">
              <label>Nom :</label>
              <input type="text" id="name" name="user_name" placeholder="Entrez votre nom" required>
              <label>Email :</label>
              <input type="email" id="email" name="user_email" placeholder="Entrez votre adresse mail" required>
              <label>Message :</label>
              <textarea name="message" id="message" placeholder="Entrez votre message" required></textarea>
              <button type="submit">Envoyer</button>
            </form>
          </div>
        </div>
      </article>
  </section>
  <script>// Get all sections that have an ID defined
    const sections = document.querySelectorAll("section[id]");
    
    // Add an event listener listening for scroll
    window.addEventListener("scroll", navHighlighter);
    
    function navHighlighter() {
      
      // Get current scroll position
      let scrollY = window.pageYOffset;
      
      // Now we loop through sections to get height, top and ID values for each
      sections.forEach(current => {
        const sectionHeight = current.offsetHeight;
        const sectionTop = current.offsetTop - 50;
        sectionId = current.getAttribute("id");
        
        /*
        - If our current scroll position enters the space where current section on screen is, add .active class to corresponding navigation link, else remove it
        - To know which link needs an active class, we use sectionId variable we are getting while looping through sections as an selector
        */
        if (
          scrollY > sectionTop &&
          scrollY <= sectionTop + sectionHeight
        ){
          document.querySelector(".navigation a[href*=" + sectionId + "]").classList.add("active");
        } else {
          document.querySelector(".navigation a[href*=" + sectionId + "]").classList.remove("active");
        }
      });
    }
  </script>
</body>
</html> 
