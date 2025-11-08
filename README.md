[pixel_thinkers_club.html](https://github.com/user-attachments/files/23430874/pixel_thinkers_club.html)
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pixel Thinkers — ARPS Middle School</title>
  <meta name="description" content="Pixel Thinkers: logic meets magic — creative coding & design club for ARPS middle school." />
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Orbitron:wght@400;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --primary:#D96666; /* Soft Cherry Red */
      --accent:#5A5EDB;  /* Electric Indigo */
      --pop:#9A8CFD;     /* Pixel Violet */
      --light:#F0F0F0;   /* Cloud White */
      --dark:#000000;    /* True Black */
      --muted:rgba(240,240,240,0.78);
      font-family: 'Orbitron', system-ui, -apple-system, 'Segoe UI', Roboto, Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#030305 0%,#0b0710 100%);color:var(--light);}

    .container{max-width:1100px;margin:28px auto;padding:20px}
    header{display:flex;gap:18px;align-items:center}

    .logo-wrap{width:96px;height:96px;border-radius:14px;background:linear-gradient(180deg,var(--dark),#0b0b0b);display:flex;align-items:center;justify-content:center;padding:8px;border:4px solid rgba(255,255,255,0.03)}
    .logo-wrap img{width:100%;height:100%;object-fit:contain;image-rendering:pixelated}

    h1{font-family:'Press Start 2P','Orbitron';font-size:24px;margin:0;letter-spacing:1px}
    .subtitle{color:var(--muted);font-size:13px;margin-top:6px}

    .hero{display:grid;grid-template-columns:1fr 340px;gap:20px;margin-top:18px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);padding:18px;border-radius:12px;border:1px solid rgba(255,255,255,0.03)}

    .lead{font-size:14px;line-height:1.55;color:#e9f0ff}

    .btn{display:inline-block;padding:10px 14px;border-radius:6px;border:0;cursor:pointer;font-weight:700;text-decoration:none}
    .btn-cta{background:var(--primary);color:var(--dark);box-shadow:0 6px 0 rgba(0,0,0,0.6);font-family:'Press Start 2P'}
    .btn-outline{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}

    .levels{margin-top:14px}
    .level{display:flex;gap:12px;align-items:flex-start;padding:12px;border-radius:8px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);border:1px solid rgba(255,255,255,0.03);margin-bottom:10px}
    .num{width:44px;height:44px;border-radius:6px;background:linear-gradient(180deg,var(--accent),var(--pop));display:flex;align-items:center;justify-content:center;font-family:'Press Start 2P';color:var(--dark)}
    .level h3{margin:0;font-size:14px}
    .level p{margin:6px 0 0;color:var(--muted);font-size:13px}

    aside .card h3{margin-top:0}
    .avatar{width:44px;height:44px;border-radius:8px;background:linear-gradient(180deg,var(--primary),var(--accent));display:flex;align-items:center;justify-content:center;font-weight:900}

    footer{margin-top:26px;text-align:center;color:var(--muted);font-size:12px}

    .ig{display:inline-flex;gap:8px;align-items:center;padding:8px;border-radius:8px;background:linear-gradient(90deg,var(--accent),var(--pop));color:var(--dark);font-weight:800;font-family:'Press Start 2P';text-decoration:none}

    @media(max-width:880px){
      .hero{grid-template-columns:1fr}
      header{gap:12px}
      .logo-wrap{width:76px;height:76px}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo-wrap">
        <img src="pixel%20thinkers%20logo.png" alt="Pixel Thinkers logo">
      </div>
      <div>
        <h1>Pixel Thinkers</h1>
        <div class="subtitle">Logic meets magic — creative coding & design for ARPS Middle School</div>
      </div>
    </header>

    <section class="hero">
      <main class="card">
        <p class="lead">Pixel Thinkers is a friendly space for middle-schoolers to learn coding, 3D modeling, digital design, and storytelling through playful projects using beginner-friendly tools like Scratch, Tinkercad, Canva, and Storyboard That.</p>

        <div style="margin-top:12px;display:flex;gap:10px;flex-wrap:wrap;align-items:center">
          <a class="btn btn-cta" href="#join">Join Us</a>
          <a class="btn btn-outline" href="https://www.instagram.com/pixelthinkers/" target="_blank">Follow @pixelthinkers</a>
        </div>

        <div class="levels" aria-hidden>
          <h2 style="font-size:15px;margin:10px 0;font-family:'Press Start 2P'">Club Learning Levels</h2>

          <div class="level">
            <div class="num">1</div>
            <div>
              <h3>Level 1 — Tech Foundations</h3>
              <p>How computers think, internet basics, files & storage. Project: "How Tech Works" visual map.</p>
            </div>
          </div>

          <div class="level">
            <div class="num">2</div>
            <div>
              <h3>Level 2 — Code Warrior</h3>
              <p>Scratch & HTML/CSS basics. Projects: mini games, personal page.</p>
            </div>
          </div>

          <div class="level">
            <div class="num">3</div>
            <div>
              <h3>Level 3 — AI Explorer</h3>
              <p>Intro to simple ML tools, ethics, and creative AI experiments.</p>
            </div>
          </div>

          <div class="level">
            <div class="num">4</div>
            <div>
              <h3>Level 4 — Creator Mode</h3>
              <p>Make mini games, digital art, or 3D models. Showcase at club expo.</p>
            </div>
          </div>

          <div class="level">
            <div class="num">5</div>
            <div>
              <h3>Level 5 — Leadership & Teaching</h3>
              <p>Run workshops, mentor teammates, and organize a Tech Fun Day.</p>
            </div>
          </div>
        </div>

        <section id="join" style="margin-top:16px">
          <h2 style="font-size:15px;margin:8px 0;font-family:'Press Start 2P'">Get Involved</h2>
          <p style="color:var(--muted)">Open to ARPS middle school students. To join, scan the posters around school or message the club on Instagram — details and audition form are shared there.</p>

          <div style="margin-top:10px;display:flex;gap:8px;flex-wrap:wrap">
            <a class="btn btn-outline" href="#projects">See Projects</a>
            <a class="btn btn-outline" href="https://www.instagram.com/pixelthinkers/" target="_blank">Contact on Instagram</a>
          </div>
        </section>

      </main>

      <aside>
        <div class="card">
          <h3 style="font-family:'Press Start 2P'">Club Snapshot</h3>
          <div style="color:var(--muted);font-size:13px;margin-top:8px">
            <strong>Founder:</strong> Laia isa<br>
            <strong>Who:</strong> Middle school students only
          </div>

          <div style="margin-top:12px">
            <h3 style="font-family:'Press Start 2P'">Tools & Apps</h3>
            <ul style="color:var(--muted);padding-left:18px;margin:8px 0;font-size:13px">
              <li>Scratch • Tinkercad • Canva</li>
              <li>Storyboard That • Sweet Home 3D</li>
              <li>Teachable Machine • Replit</li>
            </ul>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h3 style="font-family:'Press Start 2P'">Projects & Events</h3>
          <ul style="color:var(--muted);padding-left:18px;margin:8px 0;font-size:13px">
            <li>Game Jam • StoryVerse Showdown</li>
            <li>3D Inventors’ Expo • Pixel Cup</li>
            <li>Monthly showcases & awards</li>
          </ul>
          <div style="margin-top:8px;display:flex;gap:8px">
            <a class="ig" href="https://www.instagram.com/pixelthinkers/" target="_blank">IG • @pixelthinkers</a>
          </div>
        </div>
      </aside>
    </section>

    <footer>
      Made with 💖 by Pixel Thinkers — © <span id="year"></span>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
