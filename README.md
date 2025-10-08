<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Abdul Samad — Software Engineer</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0a0a0a;
      --panel:#0f0f0f;
      --accent:#00e6e6;
      --muted:#bdbdbd;
      --card:#111;
      --radius:12px;
    }
    *{box-sizing:border-box}
    html,body{height:100%; margin:0; font-family:"Poppins",system-ui,Segoe UI,Roboto,Arial;}
    body{background:var(--bg); color:#fff; -webkit-font-smoothing:antialiased;}

    header{
      position:fixed; top:0; left:0; right:0;
      display:flex; justify-content:space-between; align-items:center;
      padding:14px 6%;
      background:linear-gradient(180deg, rgba(0,0,0,0.7), rgba(0,0,0,0.35));
      backdrop-filter: blur(6px); z-index:999;
      border-bottom:1px solid rgba(255,255,255,0.03);
    }
    .brand{ color:var(--accent); font-weight:700; letter-spacing:0.6px; }
    nav a{ color:#ddd; text-decoration:none; margin-left:18px; font-size:0.95rem; }
    nav a:hover{ color:var(--accent); }

    main{ padding-top:78px; }

    /* Hero */
    .hero{
      min-height: calc(100vh - 78px);
      display:flex; align-items:center; justify-content:center;
      padding:60px 6%;
      gap:40px; text-align:center; flex-direction:column;
    }
    .hero-inner{ max-width:980px; width:100%; display:flex; gap:40px; align-items:center; justify-content:center; flex-direction:column; }
    .avatar{
      width:180px; height:180px; border-radius:50%;
      border:3px solid rgba(0,230,230,0.06);
      box-shadow:0 8px 30px rgba(0,0,0,0.6);
      object-fit:cover;
      transition: transform .35s ease;
    }
    .avatar:hover{ transform:translateY(-6px); }

    .name{ color:var(--accent); font-size:2rem; font-weight:700; margin-top:8px;}
    .title{ color:var(--muted); font-size:1.02rem; margin-top:8px; }

    .intro{ color:#bfbfbf; margin-top:18px; line-height:1.6; max-width:760px; }

    /* Skills */
    .skills{ padding:72px 6%; text-align:center; }
    .skills h2{ color:var(--accent); font-size:1.6rem; margin-bottom:26px; }
    .skill-grid{
      display:flex; flex-wrap:wrap; gap:20px; justify-content:center; align-items:center;
    }
    .skill{
      width:140px; background:var(--card); border-radius:10px; padding:14px;
      display:flex; flex-direction:column; align-items:center; gap:10px;
      border:1px solid rgba(255,255,255,0.02);
      transition: transform .18s ease, box-shadow .18s ease;
    }
    .skill:hover{ transform:translateY(-6px); box-shadow:0 14px 40px rgba(0,0,0,0.6); }
    .skill img{ width:48px; height:48px; display:block; }
    .skill span{ color:#e6e6e6; font-size:0.95rem; }

    /* Contact */
    .contact{ padding:48px 6%; text-align:center; color:#bfbfbf; }
    .contact a{ color:var(--accent); text-decoration:none; }

    footer{ padding:26px 6%; text-align:center; color:#9b9b9b; border-top:1px solid rgba(255,255,255,0.02); }

    /* Responsive */
    @media (min-width:900px){
      .hero-inner{ flex-direction:row; text-align:left; align-items:center; }
      .hero .left{ flex:0 0 42%; display:flex; justify-content:center; }
      .hero .right{ flex:0 0 58%; }
      .name{ font-size:2.4rem; }
    }
    @media (max-width:520px){
      header{ padding:12px 4% }
      .skill{ width:120px; padding:12px }
    }
  </style>
</head>
<body>
  <header>
    <div class="brand">Abdul Samad</div>
    <nav aria-label="Main navigation">
      <a href="#home">Home</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <div class="hero-inner">
        <div class="left">
          <img class="avatar" src="https://i.postimg.cc/Kzj4qvvd/keep-the-face-and-natural.jpg" alt="Abdul Samad">
        </div>

        <div class="right">
          <div class="name">Abdul Samad</div>
          <div class="title">Software Engineer &nbsp;|&nbsp; Frontend Developer</div>

          <p class="intro">
            I build clean, responsive user interfaces and keep improving with every project. Currently focused on HTML, CSS and JavaScript — learning React and enhancing my problem-solving skills.
          </p>
        </div>
      </div>
    </section>

    <section id="skills" class="skills">
      <h2>Skills</h2>

      <div class="skill-grid" role="list">
        <!-- HTML -->
        <div class="skill" role="listitem" title="HTML">
          <img src="https://skillicons.dev/icons?i=html" alt="HTML">
          <span>HTML</span>
        </div>

        <!-- CSS -->
        <div class="skill" role="listitem" title="CSS">
          <img src="https://skillicons.dev/icons?i=css" alt="CSS">
          <span>CSS</span>
        </div>

        <!-- JavaScript -->
        <div class="skill" role="listitem" title="JavaScript">
          <img src="https://skillicons.dev/icons?i=javascript" alt="JavaScript">
          <span>JavaScript</span>
        </div>

        <!-- Python (Basics) -->
        <div class="skill" role="listitem" title="Python (Basics)">
          <img src="https://skillicons.dev/icons?i=python" alt="Python">
          <span>Python (Basics)</span>
        </div>

        <!-- Java (Basics) -->
        <div class="skill" role="listitem" title="Java (Basics)">
          <img src="https://skillicons.dev/icons?i=java" alt="Java">
          <span>Java (Basics)</span>
        </div>

        <!-- Communication (simple svg) -->
        <div class="skill" role="listitem" title="Communication">
          <svg width="44" height="44" viewBox="0 0 24 24" fill="none" aria-hidden>
            <path d="M21 15a2 2 0 0 1-2 2H8l-5 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z" fill="#00e6e6"/>
          </svg>
          <span>Communication</span>
        </div>

        <!-- Team Collaboration (simple svg) -->
        <div class="skill" role="listitem" title="Team Collaboration">
          <svg width="44" height="44" viewBox="0 0 24 24" fill="none" aria-hidden>
            <path d="M16 11c1.657 0 3-1.567 3-3.5S17.657 4 16 4s-3 1.567-3 3.5S14.343 11 16 11zM8 11c1.657 0 3-1.567 3-3.5S9.657 4 8 4 5 5.567 5 7.5 6.343 11 8 11z" fill="#00e6e6"/>
            <path d="M2 19a6 6 0 0 1 12 0v2H2v-2zM12 19a6 6 0 0 1 12 0v2h-8v-2z" fill="#00e6e6" opacity="0.9"/>
          </svg>
          <span>Team Collaboration</span>
        </div>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2 style="color:var(--accent); margin-bottom:12px">Contact</h2>
      <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a> · GitHub: <a href="https://github.com/your-username">github.com/your-username</a></p>
    </section>
  </main>

  <footer>
    © 2025 Abdul Samad — Built with HTML & CSS
  </footer>
</body>
</html>
