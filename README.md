<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Abdul Samad — Software Engineer</title>

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0a0a0a;
      --panel:#0f0f0f;
      --accent:#00e6e6;
      --muted:#bdbdbd;
      --radius:14px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family:"Poppins",system-ui,Segoe UI,Roboto,Arial;
      background:var(--bg);
      color:#fff;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }

    header{
      position:fixed;
      top:0;left:0;right:0;
      display:flex;
      align-items:center;
      justify-content:space-between;
      padding:14px 6%;
      background:linear-gradient(180deg, rgba(0,0,0,0.65), rgba(0,0,0,0.25));
      backdrop-filter: blur(6px);
      z-index:999;
      border-bottom:1px solid rgba(255,255,255,0.03);
    }
    header .brand{color:var(--accent); font-weight:700; letter-spacing:0.6px}
    nav a{color:#ddd; text-decoration:none; margin-left:18px; font-size:0.95rem}
    nav a:hover{color:var(--accent)}

    /* Hero */
    .hero{
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:100px 6% 60px;
      text-align:center;
      gap:36px;
      flex-direction:column;
    }
    .avatar{
      width:170px;height:170px;border-radius:50%;
      border:3px solid rgba(0,230,230,0.12);
      box-shadow:0 8px 30px rgba(0,0,0,0.6), 0 0 30px rgba(0,230,230,0.03) inset;
      object-fit:cover;
    }
    .name{
      margin-top:8px;
      color:var(--accent);
      font-size:2rem;
      font-weight:700;
    }
    .title{
      color:var(--muted);
      font-size:1.05rem;
      margin-top:6px;
    }

    /* Skills */
    .skills{
      padding:80px 6%;
      display:block;
      text-align:center;
    }
    .skills h2{color:var(--accent); font-size:1.7rem; margin-bottom:26px}
    .skill-grid{
      display:flex;
      flex-wrap:wrap;
      justify-content:center;
      gap:28px;
      align-items:center;
    }
    .skill{
      width:120px;
      display:flex;
      flex-direction:column;
      align-items:center;
      gap:10px;
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.02);
      padding:18px;
      border-radius:12px;
      transition:transform .22s ease, box-shadow .22s ease;
    }
    .skill:hover{ transform:translateY(-6px); box-shadow:0 14px 40px rgba(0,0,0,0.6)}
    .skill img{ width:44px; height:44px; display:block; }
    .skill span{ color:#ddd; font-size:0.95rem }

    /* Contact / footer */
    footer{
      padding:40px 6%;
      text-align:center;
      color:#9b9b9b;
      border-top:1px solid rgba(255,255,255,0.02);
    }

    /* Responsive */
    @media (min-width:900px){
      .hero{flex-direction:row; text-align:left}
      .hero .left{flex:0 0 48%}
      .hero .right{flex:0 0 48%}
      .name{font-size:2.4rem}
    }
    @media (max-width:520px){
      header{padding:12px 4%}
      .skills .skill{width:110px;padding:14px}
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
      <div class="left" style="display:flex;flex-direction:column;align-items:center;">
        <img class="avatar" src="https://i.postimg.cc/Kzj4qvvd/keep-the-face-and-natural.jpg" alt="Abdul Samad">
      </div>

      <div class="right" style="max-width:720px;">
        <div class="name">Abdul Samad</div>
        <div class="title">Software Engineer &nbsp;|&nbsp; Frontend Developer</div>
        <p style="color:#bdbdbd;margin-top:18px;line-height:1.6;">
          I build clean, responsive user interfaces and keep improving with every project. Currently focused on HTML, CSS, JavaScript and learning React.
        </p>
      </div>
    </section>

    <section id="skills" class="skills">
      <h2>Skills</h2>

      <div class="skill-grid" role="list">
        <div class="skill" role="listitem" title="HTML">
          <img src="https://skillicons.dev/icons?i=html" alt="HTML">
          <span>HTML</span>
        </div>

        <div class="skill" role="listitem" title="CSS">
          <img src="https://skillicons.dev/icons?i=css" alt="CSS">
          <span>CSS</span>
        </div>

        <div class="skill" role="listitem" title="JavaScript">
          <img src="https://skillicons.dev/icons?i=javascript" alt="JavaScript">
          <span>JavaScript</span>
        </div>

        <div class="skill" role="listitem" title="Python (Basics)">
          <img src="https://skillicons.dev/icons?i=python" alt="Python">
          <span>Python (Basics)</span>
        </div>

        <div class="skill" role="listitem" title="Java (Basics)">
          <img src="https://skillicons.dev/icons
