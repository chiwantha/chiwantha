<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kasun Chiwantha | Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0f172a;
      color: #fff;
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    /* HERO */
    .hero {
      text-align: center;
      padding: 80px 20px;
    }

    .hero h1 {
      font-size: 3rem;
      font-weight: 700;
    }

    .hero h3 {
      color: #38bdf8;
      margin-top: 10px;
      font-weight: 400;
    }

    .hero p {
      margin-top: 20px;
      color: #94a3b8;
    }

    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 12px 25px;
      background: #38bdf8;
      color: #000;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    .btn:hover {
      background: #0ea5e9;
    }

    /* SECTION */
    section {
      padding: 60px 0;
    }

    .section-title {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2rem;
    }

    /* ABOUT */
    .about {
      text-align: center;
      max-width: 800px;
      margin: auto;
      color: #cbd5f5;
    }

    /* SKILLS */
    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 20px;
      text-align: center;
    }

    .skill {
      background: #1e293b;
      padding: 20px;
      border-radius: 12px;
      transition: 0.3s;
    }

    .skill:hover {
      transform: translateY(-5px);
      background: #334155;
    }

    /* SOCIAL */
    .socials {
      text-align: center;
    }

    .socials a {
      margin: 0 10px;
      text-decoration: none;
      color: #38bdf8;
      font-weight: 600;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 20px;
      color: #94a3b8;
      border-top: 1px solid #1e293b;
    }

  </style>
</head>

<body>

  <!-- HERO -->
  <section class="hero">
    <div class="container">
      <h1>👋 Hi, I'm Kasun Chiwantha</h1>
      <h3>🇱🇰 Software Engineer | Full-Stack Developer</h3>
      <p>Building scalable apps, modern web platforms & tech solutions</p>
      <a href="mailto:kasunchiwantha789@gmail.com" class="btn">Contact Me</a>
    </div>
  </section>

  <!-- ABOUT -->
  <section>
    <div class="container">
      <h2 class="section-title">🧠 About Me</h2>
      <p class="about">
        I'm a full-stack developer working on multi-tenant systems, React & Next.js apps,
        and studio tech solutions. I also run a tech + music production company.
      </p>
    </div>
  </section>

  <!-- SKILLS -->
  <section>
    <div class="container">
      <h2 class="section-title">🛠️ Tech Stack</h2>
      <div class="skills">
        <div class="skill">JavaScript</div>
        <div class="skill">React</div>
        <div class="skill">Next.js</div>
        <div class="skill">Python</div>
        <div class="skill">C#</div>
        <div class="skill">C++</div>
        <div class="skill">PHP</div>
        <div class="skill">MySQL</div>
        <div class="skill">MSSQL</div>
        <div class="skill">Node.js</div>
        <div class="skill">Linux</div>
        <div class="skill">Tailwind</div>
      </div>
    </div>
  </section>

  <!-- SOCIAL -->
  <section>
    <div class="container">
      <h2 class="section-title">🔗 Connect With Me</h2>
      <div class="socials">
        <a href="https://linkedin.com/in/kasun-chiwantha-5168b4323" target="_blank">LinkedIn</a>
        <a href="https://fb.com/kasunchiwantha" target="_blank">Facebook</a>
        <a href="https://www.youtube.com/c/kasunchiwantha" target="_blank">YouTube</a>
        <a href="https://github.com/chiwantha" target="_blank">GitHub</a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    © 2026 Kasun Chiwantha | Built with ❤️
  </footer>

</body>
</html>
