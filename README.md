# babu-website
My first website
<!doctype html>
<html lang="si">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ඔබේ වෙබ් අඩවිය — නම ඇතුළත් කරන්න</title>
  <meta name="description" content="සරාන්ගී, responsive single-page website template (Sinhala)" />
  <style>
    /* Simple responsive styling (change as you like) */
    :root{--accent:#2563eb;--muted:#666}
    *{box-sizing:border-box}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Noto Sans', sans-serif;margin:0;color:#111;line-height:1.5}
    header{display:flex;justify-content:space-between;align-items:center;padding:18px 24px;border-bottom:1px solid #eee}
    .logo{font-weight:700;color:var(--accent)}
    nav a{margin-left:16px;text-decoration:none;color:var(--muted)}
    .container{max-width:1000px;margin:36px auto;padding:0 18px}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center}
    .hero h1{font-size:2rem;margin:0}
    .hero p{margin:8px 0;color:var(--muted)}
    .btn{display:inline-block;padding:10px 16px;border-radius:8px;background:var(--accent);color:#fff;text-decoration:none}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;margin-top:24px}
    .card{padding:18px;border-radius:12px;border:1px solid #f0f0f0;background:#fff;box-shadow:0 4px 18px rgba(20,20,20,0.03)}
    footer{padding:28px 18px;text-align:center;color:var(--muted);border-top:1px solid #f1f1f1;margin-top:36px}
    form input, form textarea{width:100%;padding:10px;margin-top:8px;border:1px solid #ddd;border-radius:8px}
    @media(min-width:800px){
      .hero{grid-template-columns:1fr 420px}
      .hero h1{font-size:2.4rem}
    }
  </style>
</head>
<body>
  <!--
    Simple single-page website template (Sinhala)
    ------------------------------------------------
    කොහොමද භාවිත කළ යුතුද:
    1) මේ ගොනුව local එකේ open කර බලන්න (double-click). Chrome/Edge/Firefox වලින්.
    2) ඔබගේ නම, සේවාවන් සහ සම්බන්ධ විස්තර "CONTENT HERE" හිින් වෙනස් කරන්න.
    3) GitHub Pages හෝ Netlify/Render මගින් deploy කල හැක.
    4) වෙනස්කම් අවශ්‍ය නම්, මට කියන්න — මම එය update කර දෙනවා.
  -->

  <header>
    <div class="logo">ඔබේ ලාංඡනය</div>
    <nav>
      <a href="#about">ගැන</a>
      <a href="#services">සේවාවන්</a>
      <a href="#contact">සම්බන්ධ වන්න</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <h1>ඔබේ ව්‍යාපාරය/වැඩ<strong> සරලව</strong> පෙන්නන්න</h1>
        <p>මෙම වෙබ් අඩවිය සරල, responsive single-page template එකක්. ඔබගේ සේවාවන්, ආයතනය හෝ ව්‍යාපාරය ඉදිරිපත් කිරීමට අවශ්‍ය මුලික කොටස් ඇත.</p>
        <p>
          <a class="btn" href="#contact">දැන් සම්බන්ධ වන්න</a>
        </p>
      </div>

      <aside class="card">
        <h3>අවම විස්තර</h3>
        <p style="color:var(--muted)">ඔබගේ ලිපිනය, දුරකථන අංකය, ඊමේල් දැනට මෙහි සටහන් කරන්න.</p>
        <p><strong>ඊමේල්:</strong> babushakthi52@gmail.com</p>
        <p><strong>දුරකථන:</strong> +94 77 123 4567</p>
      </aside>
    </section>

    <section id="about" style="margin-top:36px">
      <h2>ගැන</h2>
      <p class="muted">CONTENT HERE — ඔබගේ ව්‍යාපාරය, කතාව, ඉතිහාසය ඇතුළත් කරන්න.</p>
    </section>

    <section id="services" style="margin-top:28px">
      <h2>සේවාවන්</h2>
      <div class="grid">
        <div class="card">
          <h4>සේවාව 1</h4>
          <p class="muted">කෙටි විස්තරයක් දැම්මහොත් හොඳයි.</p>
        </div>
        <div class="card">
          <h4>සේවාව 2</h4>
          <p class="muted">කෙටි විස්තරයක් දැම්මහොත් හොඳයි.</p>
        </div>
        <div class="card">
          <h4>සේවාව 3</h4>
          <p class="muted">කෙටි විස්තරයක් දැම්මහොත් හොඳයි.</p>
        </div>
      </div>
    </section>

    <section id="contact" style="margin-top:28px">
      <h2>සම්බන්ධ වන්න</h2>
      <div class="grid">
        <div class="card">
          <form action="mailto:babushakthi52@gmail.com" method="post" enctype="text/plain">
            <label>නම</label>
            <input type="text" name="name" placeholder="ඔබේ නම" />
            <label>ඊමේල්</label>
            <input type="email" name="email" placeholder="you@example.com" />
            <label>පණිවිඩය</label>
            <textarea name="message" rows="6" placeholder="පණිවිඩය..."></textarea>
            <div style="margin-top:10px">
              <button class="btn" type="submit">යවන්න</button>
            </div>
          </form>
        </div>

        <div class="card">
          <h4>ලිපිනය</h4>
          <p>CONTENT HERE — ඔබගේ ලිපිනය සහ වැඩ කරන වේලාවන් දැක්වන්න.</p>
          <h4 style="margin-top:12px">සමාජ මාධ්‍ය</h4>
          <p>Facebook / Instagram / X links දැක්වන්න.</p>
        </div>
      </div>
    </section>

    <footer>
      © <span id="year"></span> ඔබේ නම • සියලු හිමිකම් අරක්ෂිතයි
    </footer>
  </main>

  <script>
    // small script to set current year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
