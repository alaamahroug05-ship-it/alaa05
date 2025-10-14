# alaa05
portfolio-alaa
<!DOCTYPE html>
<!-- saved from url=(0054)file:///C:/Users/DELL/Desktop/Portfolio/portfolio.html -->
<html lang="fr"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio — Stage Radio | 2ᵉ Licence Art et Médiation</title>
  <style>
    /* --------------------
       STYLE GLOBAL
    -------------------- */
    :root {
      --bg: #f8f9fc;
      --text: #1e293b;
      --accent: #ff4d6d;
      --card: #ffffff;
      --radius: 16px;
      --shadow: 0 10px 25px rgba(0,0,0,0.08);
      --muted: #64748b;
      font-family: "Poppins", sans-serif;
    }

    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, var(--accent), #ff758f);
      color: #fff;
      text-align: center;
      padding: 60px 20px;
      border-radius: 0 0 40px 40px;
      box-shadow: var(--shadow);
    }

    header h1 {
      margin: 0;
      font-size: 2.2em;
      font-weight: 700;
    }

    header p {
      margin-top: 10px;
      font-size: 1.1em;
      opacity: 0.9;
    }

    .container {
      max-width: 1100px;
      margin: 50px auto;
      padding: 0 20px;
    }

    section {
      background: var(--card);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 30px;
      margin-bottom: 30px;
    }

    h2 {
      color: var(--accent);
      margin-bottom: 20px;
      font-size: 1.6em;
      border-left: 5px solid var(--accent);
      padding-left: 10px;
    }

    .about p {
      color: var(--muted);
      font-size: 1.05em;
    }

    .video-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .video-card {
      background: #fff;
      border-radius: var(--radius);
      overflow: hidden;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .video-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    video {
      width: 100%;
      display: block;
    }

    .video-info {
      padding: 15px;
    }

    .video-info h3 {
      margin: 0 0 10px 0;
      font-size: 1.1em;
      color: var(--accent);
    }

    .video-info p {
      margin: 0;
      color: var(--muted);
      font-size: 0.95em;
    }
.hero-content {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 30px;
}

.hero-image img {
  width: 300px;     
  border-radius: 0;   
  border: 2px solid #fff; 
}

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background: var(--accent);
      color: #fff;
      padding: 8px 14px;
      border-radius: 50px;
      font-size: 0.9em;
      font-weight: 500;
    }

    footer {
      text-align: center;
      padding: 30px;
      color: var(--muted);
      font-size: 0.9em;
    }

    footer a {
      color: var(--accent);
      text-decoration: none;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h1 { font-size: 1.8em; }
      h2 { font-size: 1.3em; }
    }
   .videos {
  text-align: center;
  padding: 40px;
  background-color: #f9f9f9;
}
.videos {
  text-align: center;
  padding: 40px;
  background-color: #f9f9f9;
}

.video-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
}

.video-card {
  background: #fff;
  padding: 15px;
  border-radius: 15px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  width: 45%;
  min-width: 300px;
}

/* 🟢 الجزء المهم */
.video-card video {
  width: 100%;
  aspect-ratio: 4 / 5; /* يخلي الفيديو مستطيل ثابت (مش مربع ولا طويل بزاف) */
  border-radius: 12px;
  border: 2px solid #ddd;
  object-fit: cover; /* باش الفيديو يكون مليان كامل الإطار */
  display: block;
  background-color: #000; /* باش وقت ما يتحمّلش، يطلع أسود وأنيق */
}

/* النص */
.video-card h3 {
  margin-top: 12px;
  color: #333;
}

.video-card p {
  color: #555;
  line-height: 1.6;
}

  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <h1>Portfolio de Stage — Radio Média</h1>
    <p>Étudiante en 2ᵉ Licence Art et Médiation | Institut Supérieur de l'Informatique et Multimédia de Gabès </p>
  </header>

  <!-- À PROPOS -->
  <div class="container">
    <section class="about">
      <h2>À Propos de moi</h2>
      <p>
      
  Je suis <strong>Alaa Mahroug</strong>, étudiante en deuxième année de licence en <strong>Arts et Médiation</strong>.  
  J’ai effectué mon stage à distance au sein de la <strong>NEFZAWA</strong>, avec une présence d’un jour par semaine.  
  Mon travail s’est principalement concentré sur le <strong>Montage Vidéo</strong>, ainsi que sur quelques réalisations graphiques avec <strong>Adobe Illustrator</strong>.
  
      </p>
    </section>

    <!-- VIDÉOS DU STAGE -->
    <section class="videos">
      <h2>Vidéos &amp; Réalisations</h2>
      <div class="video-gallery">
        
        <!-- Vidéo 1 -->
        <div class="video-card">
          <video controls poster="transport-poster.jpg">
            <source src="Transport.mp4" type="video/mp4">
            Votre navigateur ne supporte pas la vidéo.
          </video>
          <div class="video-info">
           <h3>Trasnsport</h3>
        
           <p>
Cette vidéo traite des problèmes de transport dans une région de la gouvernorat de Kébili, et elle a été réalisée à l'aide des logiciels Canva et CapCut.</p>
 
          </div>
        </div>

         <!-- Vidéo 2 -->
        <div class="video-card">
          <video controls poster="transport-poster.jpg">
            <source src="seha.mp4" type="video/mp4">
            Votre navigateur ne supporte pas la vidéo.
          </video>
          <div class="video-info">
           
             <h3>Problèmes de santé</h3>
    <p>
Cette vidéo traite des problèmes de santé survenus à l'hôpital de Kébili, et elle a été réalisée avec les mêmes logiciels, Canva et CapCut.</p>
          </div>
        </div>
         <!-- Vidéo 3 -->
        <div class="video-card">
          <video controls poster="transport-poster.jpg">
            <source src="Nefzawa Academy.mp4" type="video/mp4">
            Votre navigateur ne supporte pas la vidéo.
          </video>
          <div class="video-info">
            <h3>Académie Nefzawa</h3>
            <p>
Cette vidéo traite de l’Académie Nefzawa et des services qu’elle offre dans le gouvernorat de Kébili, et elle a été réalisée avec les logiciels Canva et CapCut.</p>
          </div>
        </div>
          <!-- Vidéo 4 -->
        <div class="video-card">
          <video controls poster="transport-poster.jpg">
            <source src="seha01.mp4" type="video/mp4">
            Votre navigateur ne supporte pas la vidéo.
          </video>
          <div class="video-info">
            <h3>Problèmes de santé</h3>
          </div>
        </div>
          <!-- Vidéo 5 -->
        <div class="video-card">
          <video controls poster="transport-poster.jpg">
            <source src="short taxi nefzawa fini .mp4" type="video/mp4">
            Votre navigateur ne supporte pas la vidéo.
          </video>
          <div class="video-info">
            <h3> Des insuffisances du gouvernorat de Kébili</h3>
            <p>
Cette vidéo traite des insuffisances du gouvernorat de Kébili, et elle a été réalisée avec les logiciels Canva et CapCut.</p>
          </div>
        </div>
           <!-- Vidéo 6-->
        <div class="video-card">
          <video controls poster="transport-poster.jpg">
            <source src="معدناش في صحة حالة تاعبة.mp4" type="video/mp4">
            Votre navigateur ne supporte pas la vidéo.
          </video>
          <div class="video-info">
            <h3> l’état de santé dans le gouvernorat de Kébili</h3>
            <p>
Cette vidéo traite de l’état de santé dans le gouvernorat de Kébili, et elle a été réalisée avec les logiciels Canva et CapCut.</p>
          </div>
        </div>
        
        
        <div class="hero-image">
      <img src="04.jpg" alt="Alaa Mahroug">
    </div>

     
        <div class="hero-image">
      <img src="aff4.jpg" alt="Alaa Mahroug">
    </div>

  
      <div class="hero-image">
      <img src="dc.png." alt="Alaa Mahroug">
    </div>


      </div>
    </section>

    <!-- COMPÉTENCES -->
    <section class="skills-section">
      <h2>Compétences acquises</h2>
      <div class="skills">
        <div class="skill">Montage vidéo</div>
        <div class="skill">Prise de son</div>
        <div class="skill">Communication visuelle</div>
        <div class="skill">Interview &amp; médiation</div>
        <div class="skill">Adobe Premiere Pro</div>
        <div class="skill">Canva</div>
        <div class="skill">Travail en équipe</div>
      </div>
    </section>

    <!-- CONCLUSION -->
    <section>
      <h2>Bilan du stage</h2>
      <p>
        Ce stage m’a permis de découvrir le fonctionnement d’une rédaction radio et de participer activement
        à la création de contenus culturels et artistiques. J’ai appris à gérer la communication médiatique
        et à valoriser les projets culturels à travers l’image et le son.
      </p>
    </section>
  </div>

  <!-- FOOTER -->
  <footer>
    © <span id="year">2025</span> [Ton Nom] — Portfolio de Stage Radio |
    <a href="file:///C:/Users/DELL/Desktop/Portfolio/portfolio.html#">LinkedIn</a> | <a href="file:///C:/Users/DELL/Desktop/Portfolio/portfolio.html#">Email</a>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>




</body></html>
