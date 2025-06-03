# Santa-Sofia
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Visita Virtuale - Hagia Sophia</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Open Sans', sans-serif;
      background-color: #fefefe;
      color: #222;
      line-height: 1.6;
    }
    header {
      background: url('https://upload.wikimedia.org/wikipedia/commons/6/6a/Hagia_Sophia_Mars_2021_img_04.jpg') no-repeat center center/cover;
      height: 100vh;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      flex-direction: column;
      padding: 1rem;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
      max-width: 600px;
    }
    .btn {
      background: #c69c6d;
      color: white;
      padding: 0.8rem 1.5rem;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #a98253;
    }
    nav {
      background: #fff;
      padding: 1rem 2rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav ul li {
      margin: 0 1rem;
    }
    nav ul li a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav ul li a:hover {
      color: #c69c6d;
    }
    main {
      padding: 4rem 2rem;
      max-width: 960px;
      margin: auto;
    }
    footer {
      background: #222;
      color: #ccc;
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Visita Virtuale di Hagia Sophia</h1>
    <p>Un'esperienza digitale multisensoriale tra arte, storia e architettura.</p>
    <a href="#inizia" class="btn">Inizia la visita</a>
  </header>

  <nav>
    <ul>
      <li><a href="#storia">Storia</a></li>
      <li><a href="#protagonisti">Protagonisti</a></li>
      <li><a href="#spazi">Spazi</a></li>
      <li><a href="#sensi">Cinque sensi</a></li>
      <li><a href="#crediti">Crediti</a></li>
    </ul>
  </nav>

  <main id="inizia">
    <section id="storia">
      <h2>Storia</h2>
      <p>Qui potrai inserire una timeline, immagini d’archivio, o narrazioni sul passato millenario di Hagia Sophia.</p>
    </section>

    <section id="protagonisti">
      <h2>Protagonisti</h2>
      <p>Presenta le figure chiave che hanno trasformato Hagia Sophia nei secoli.</p>
    </section>

    <section id="spazi">
      <h2>Spazi della Chiesa</h2>
      <p>Esplora i diversi ambienti con descrizioni, mappe e modelli 3D.</p>
    </section>

    <section id="sensi">
      <h2>I Cinque Sensi</h2>
      <p>Evoca l’esperienza sensoriale con suoni, immagini, parole e simboli.</p>
    </section>

    <section id="crediti">
      <h2>Crediti e Metodologia</h2>
      <p>Informazioni sul progetto, fonti, collaboratori e riferimenti bibliografici.</p>
    </section>
  </main>

  <footer>
    &copy; 2025 Progetto Digital Humanities – Hagia Sophia. Tutti i diritti riservati.
  </footer>

</body>
</html>
