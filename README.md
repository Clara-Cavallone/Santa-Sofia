<!DOCTYPE html>
<html lang="it">
  <head>
    <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Visita Virtuale - Hagia Sophia</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="stile.css">
</head>
<body>
   <nav>
      <ul class="navbar">
    <li><a href="#storia" target="blank" title="Scopri la storia di Santa Sofia">Storia</a></li>
    <li><a href="#protagonisti">Protagonisti</a></li>
    <li><a href="spazi.html">Spazi</a></li>
    <li><a href="#sensi">Cinque sensi</a></li>
    <li><a href="#crediti">Crediti</a></li>
    </ul>
  </nav>

<header>
  <div class="slideshow">
    <div class="slide" style="background-image: url('images/index.jpg');"></div>
    <div class="slide" style="background-image: url('images/volta.jpg');"></div>
    <div class="slide" style="background-image: url('images/archi.jpg');"></div>
    </div>
  </div>

  <div class="overlay">
    <h1>Visita Virtuale di Hagia Sophia</h1>
    <p>Un'esperienza digitale multisensoriale tra arte, storia e architettura.</p>
    <a href="#inizia" class="btn">Inizia la visita</a>
  </div>
</header>



<main id="inizia">
  <section id="progetto">
    <h2>Il progetto</h2>
    <p>Scopo del progetto è quello di offrire una visita virtuale della famosa Moschea di Santa Sofia a Istanbul. L'intento è quello di andare oltre una pura presentazione degli elementi apprezzabili sul piano architettonico, cercando di offrire un'esperienza immersiva attraverso una navigazione multimodale. Sarà infatti possibile conoscere la storia del luogo, individuarne i protagonisti e il ruolo che hanno avuto nella formazione e nello sviluppo e, infine, vivere un'esperienza di navigazione che sfrutti i cinque sensi.</p>
  </section>
</main>

<footer>
  &copy; 2025 Progetto Digital Humanities – Hagia Sophia. Tutti i diritti riservati.
</footer>
  <script>
  document.addEventListener('DOMContentLoaded', () => {
    let slides = document.querySelectorAll('.slide');
    let current = 0;

    setInterval(() => {
      slides[current].classList.remove('active');
      current = (current + 1) % slides.length;
      slides[current].classList.add('active');
    }, 5000);
  });
  </script>
</body>
</html>
