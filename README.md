<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Abdul Samad | Software Engineer</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
      scroll-behavior: smooth;
    }
    body {
      background: #0a0a0a;
      color: #fff;
      overflow-x: hidden;
    }
    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(0, 0, 0, 0.8);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 70px;
      z-index: 1000;
      backdrop-filter: blur(10px);
    }
    header h1 {
      font-size: 1.5rem;
      color: #00ffee;
      letter-spacing: 1px;
    }
    header nav a {
      text-decoration: none;
      color: #fff;
      margin: 0 15px;
      transition: 0.3s;
    }
    header nav a:hover {
      color: #00ffee;
    }
    .home {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
    }
    .home img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 2px solid #00ffee;
      margin-bottom: 20px;
    }
    .home h1 {
      font-size: 2.3rem;
      color: #00ffee;
      margin-bottom: 10px;
    }
    .home h3 {
      font-size: 1.2rem;
      color: #ccc;
    }
    .skills {
      padding: 100px 0;
      text-align: center;
    }
    .skills h2 {
      font-size: 2rem;
      color: #00ffee;
      margin-bottom: 40px;
    }
    .skills .icons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }
    .skills .icons i {
      font-size: 3rem;
      color: #00ffee;
      transition: 0.3s;
    }
    .skills .icons i:hover {
      color: #fff;
      transform: scale(1.2);
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>
    <h1>Abdul Samad</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="home" id="home">
    <img src="https://i.postimg.cc/Kzj4qvvd/keep-the-face-and-natural.jpg" alt="Abdul Samad">
    <h1>👋 Hi, I'm Abdul Samad</h1>
    <h3>Software Engineer | Frontend Developer</h3>
  </section>

  <section class="skills" id="skills">
    <h2>My Skills</h2>
    <div class="icons">
      <i class="fab fa-html5" title="HTML"></i>
      <i class="fab fa-css3-alt" title="CSS"></i>
      <i class="fab fa-js" title="JavaScript"></i>
      <i class="fab fa-python" title="Python (Basics)"></i>
      <i class="fab fa-java" title="Java (Basics)"></i>
      <i class="fas fa-comments" title="Communication"></i>
      <i class="fas fa-users" title="Team Collaboration"></i>
    </div>
  </section>

  <footer id="contact">
    <p>© 2025 Abdul Samad | Built with ❤️ using HTML & CSS</p>
  </footer>
</body>
</html>
