
<!DOCTYPE html>
<html lang="rw">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="MBTV MENYA BYOSE - Amakuru y'imyidagaduro, umuziki n'ibyamamare mu Rwanda no ku isi.">
  <title>MBTV MENYA BYOSE | Amakuru y'imyidagaduro</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f4f8;
      color: #20232a;
    }
    header {
      background: #071b36;
      color: white;
      text-align: center;
      padding: 28px 12px;
      border-bottom: 5px solid #f4b400;
    }
    header h1 { margin: 0; font-size: clamp(27px, 5vw, 43px); }
    header p { margin-bottom: 0; }
    nav {
      background: #102d52;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 6px;
      padding: 12px;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 10px 12px;
      font-weight: bold;
    }
    nav a:hover { background: #f4b400; color: #071b36; }
    .hero {
      background: linear-gradient(135deg, #071b36, #1766a5);
      color: white;
      text-align: center;
      padding: 55px 18px;
    }
    .hero h2 { font-size: 32px; margin-top: 0; }
    .hero p { line-height: 1.7; }
    .container { max-width: 1100px; margin: auto; padding: 22px 15px; }
    .section-title {
      border-left: 5px solid #f4b400;
      padding-left: 12px;
      color: #071b36;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 18px;
    }
    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 3px 12px #00000012;
    }
    .card-top {
      background: #dce8f5;
      min-height: 125px;
      display: grid;
      place-items: center;
      font-size: 42px;
    }
    .card-content { padding: 17px; }
    .card h3 { color: #102d52; margin-top: 0; }
    .card p { line-height: 1.6; }
    .tag { color: #9b6900; font-weight: bold; font-size: 13px; }
    .about, .contact {
      background: white;
      padding: 22px;
      border-radius: 10px;
      margin-top: 25px;
      line-height: 1.8;
    }
    .socials { display: flex; flex-wrap: wrap; gap: 12px; }
    .socials a {
      background: #102d52;
      color: white;
      padding: 12px 16px;
      text-decoration: none;
      border-radius: 6px;
    }
    footer {
      background: #071b36;
      color: white;
      text-align: center;
      padding: 22px 12px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

<header id="home">
  <h1>MBTV MENYA BYOSE</h1>
  <p>Menya amakuru mashya. Menya ibigezweho.</p>
</header>

<nav>
  <a href="#home">Ahabanza</a>
  <a href="#rwanda">Mu Rwanda</a>
  <a href="#music">Umuziki</a>
  <a href="#africa">Afurika & Isi</a>
  <a href="#about">Abo turi bo</a>
  <a href="#contact">Twandikire</a>
</nav>

<section class="hero">
  <h2>IKAZE KURI MBTV MENYA BYOSE</h2>
  <p>Urubuga rwanyu rw'amakuru y'imyidagaduro, abahanzi,<br>
  indirimbo, ibyamamare n'ibigezweho mu Rwanda no ku isi.</p>
</section>

<main class="container">
  <section id="rwanda">
    <h2 class="section-title">Amakuru yo mu Rwanda</h2>
    <div class="cards">
      <article class="card">
        <div class="card-top">🇷🇼</div>
        <div class="card-content">
          <span class="tag">IMYIDAGADURO</span>
          <h3>Amakuru mashya mu Rwanda</h3>
          <p>Aha tuzajya tubagezaho amakuru y'abahanzi, ibitaramo n'ibindi bigezweho.</p>
        </div>
      </article>
      <article class="card">
        <div class="card-top">🎤</div>
        <div class="card-content">
          <span class="tag">IBYAMAMARE</span>
          <h3>Menya ibyamamare</h3>
          <p>Inkuru, ibiganiro n'amakuru ajyanye n'abahanzi n'abandi bantu bazwi.</p>
        </div>
      </article>
    </div>
  </section>

  <section id="music">
    <h2 class="section-title">Umuziki</h2>
    <div class="cards">
      <article class="card">
        <div class="card-top">🎵</div>
        <div class="card-content">
          <span class="tag">MUSIC NEWS</span>
          <h3>Indirimbo nshya</h3>
          <p>Tuzajya tubagezaho amakuru y'indirimbo nshya, abahanzi n'ibikorwa byabo.</p>
        </div>
      </article>
      <article class="card">
        <div class="card-top">🎬</div>
        <div class="card-content">
          <span class="tag">VIDEOS</span>
          <h3>Amashusho n'ibiganiro</h3>
          <p>Aha hazajya hongerwamo amashusho n'ibiganiro bya MBTV MENYA BYOSE.</p>
        </div>
      </article>
    </div>
  </section>

  <section id="africa">
    <h2 class="section-title">Afurika n'Isi</h2>
    <div class="cards">
      <article class="card">
        <div class="card-top">🌍</div>
        <div class="card-content">
          <span class="tag">AFRICA & WORLD</span>
          <h3>Amakuru mpuzamahanga</h3>
          <p>Inkuru z'imyidagaduro, umuziki n'ibyamamare byo muri Afurika no ku isi.</p>
        </div>
      </article>
    </div>
  </section>

  <section class="about" id="about">
    <h2 class="section-title">Abo turi bo</h2>
    <p>MBTV MENYA BYOSE ni urubuga rugamije kugeza ku bakunzi bacu amakuru y'imyidagaduro, umuziki, ibyamamare n'ibindi bigezweho. Intego yacu ni ukubagezaho amakuru asobanutse kandi ku gihe.</p>
  </section>

  <section class="contact" id="contact">
    <h2 class="section-title">Dukurikire kandi utwandikire</h2>
    <p>Ushaka kutugezaho inkuru, amakuru cyangwa ubufatanye? Twandikire ukoresheje imbuga zacu.</p>
    <div class="socials">
      <a href="https://www.youtube.com/" target="_blank" rel="noopener">YouTube</a>
      <a href="https://www.facebook.com/" target="_blank" rel="noopener">Facebook</a>
      <a href="https://www.instagram.com/" target="_blank" rel="noopener">Instagram</a>
      <a href="https://www.tiktok.com/" target="_blank" rel="noopener">TikTok</a>
    </div>
    <p><strong>Email:</strong> mbtvmenyabyose@gmail.com</p>
    <p><em>Hindura email niba utarayifungura cyangwa atari yo ukoresha.</em></p>
  </section>
</main>

<footer>
  <p>© 2026 MBTV MENYA BYOSE. Uburenganzira bwose burabitswe.</p>
  <p>Amakuru y'imyidagaduro mu Rwanda no ku isi.</p>
</footer>

</body>
</html>
