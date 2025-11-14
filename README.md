<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sangram Gite | Portfolio</title>
  <style>
    /* ===== Basic Styles ===== */
    body {
      font-family: Arial, Helvetica, sans-serif;
      background-color: #f7f9fc;
      color: #111827;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
      background-color: #004aad;
      color: white;
      padding: 12px 5%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 10;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    }

    .brand {
      font-weight: bold;
      font-size: 18px;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 50px 5%;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: #004aad;
      text-align: center;
      margin-bottom: 20px;
    }

    .hero {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 30px;
    }

    .hero img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 5px solid white;
      object-fit: cover;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    .hero-content {
      flex: 1;
      min-width: 250px;
    }

    .hero-content h1 {
      color: #004aad;
    }

    .hero-content h3 {
      color: #ffd700;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 14px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .btn-main {
      background-color: #004aad;
      color: white;
    }

    .btn-main:hover {
      background-color: #003a8f;
    }

    .btn-outline {
      border: 2px solid #004aad;
      color: #004aad;
    }

    .card {
      background-color: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
      margin: 15px 0;
    }

    .skills span {
      display: inline-block;
      background-color: rgba(0, 74, 173, 0.1);
      color: #004aad;
      padding: 6px 10px;
      border-radius: 20px;
      margin: 5px;
      font-weight: 600;
      font-size: 14px;
    }

    .contact a {
      color: #004aad;
      text-decoration: none;
    }

    footer {
      background-color: #004aad;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    @media (max-width: 700px) {
      .hero {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="brand">Sangram Gite</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

<!-- ===== HOME SECTION ===== -->
<section id="home" class="hero">
  <div class="hero-content">

    
    <h1>Hi, I’m <span style="color:#ffd700;">Sangram Gite</span></h1>
    <p>
      I’m a B.Tech CSE student from Delhi Technological University. I enjoy coding, building websites, and exploring new technologies.  
      When I’m not coding, I’m usually driving or exploring the world!!
    </p>
    <a href="#projects" class="btn btn-main">View Projects</a>
    <a href="#contact" class="btn btn-outline">Contact Me</a>
  </div>
  <img src="25a02057 profile picture.jpg" alt="Sangram Gite">
</section>


  <!-- ===== ABOUT SECTION ===== -->
  <section id="about">
    <h2>About Me</h2>
    <div class="card">
      <p>Hello! I’m <b>Sangram Gite</b>, a Computer Science student at Delhi Technological University. I love learning new technologies, building creative websites, and improving my coding skills every day.</p>
      <p><b>Hobbies:</b> Driving cars, exploring new gadgets, photography</p>
      <p><b>Languages Known:</b> Marathi, Hindi, English</p>
    </div>
  </section>

<!-- ===== EDUCATION & SKILLS ===== -->
<section id="education">
  <h2 style="color:#004aad;text-align:center;">Education & Skills</h2>
  <div class="card" style="display:grid;grid-template-columns:1fr 1fr;gap:20px;">
    <div>
      <h3 style="color:#004aad;">Education</h3>
      <p><b>B.Tech in Computer Science</b><br>Delhi Technological University (2025 - Present)</p>
      <p><b>12th:</b> Narayana Junior College</p>
      <p><b>10th:</b> Podar International School</p>
    </div>

    <div>
      <h3 style="color:#004aad;">Skills</h3>
      <div style="display:flex;flex-wrap:wrap;gap:8px;padding-top:6px;">
        <span style="background:rgba(0,74,173,0.08);color:#004aad;padding:6px 12px;border-radius:20px;font-weight:600;">HTML</span>
        <span style="background:rgba(0,74,173,0.08);color:#004aad;padding:6px 12px;border-radius:20px;font-weight:600;">CSS</span>
        <span style="background:rgba(0,74,173,0.08);color:#004aad;padding:6px 12px;border-radius:20px;font-weight:600;">C</span>
        <span style="background:rgba(0,74,173,0.08);color:#004aad;padding:6px 12px;border-radius:20px;font-weight:600;">Python</span>
      </div>
    </div>
  </div>
</section>


  <!-- ===== PROJECTS SECTION ===== -->
  <section id="projects">
    <h2>Projects / Portfolio</h2>
    <div class="card" style="text-align:center;">
      <p style="color:#6b7280;">No projects added yet — currently learning and working on new ones.</p>
    </div>
  </section>

  <!-- ===== CONTACT SECTION ===== -->
  <section id="contact">
    <h2>Contact</h2>
    <div class="card contact">
      <p><b>Email:</b> <a href="mailto:gitesangram26@gmail.com">gitesangram26@gmail.com</a></p>
      <p><b>Phone:</b> 9552300777</p>
      <p><b>Location:</b> Dharashiv, Maharashtra</p>
      <p><b>LinkedIn:</b> <a href="https://www.linkedin.com/in/sangram-gite-977436378" target="_blank">linkedin.com/in/sangram-gite-977436378</a></p>
      <p><b>GitHub:</b> <a href="https://github.com/gitesangram26" target="_blank">github.com/gitesangram26</a></p>
      <p><b>Instagram:</b> <a href="https://instagram.com/sangramgite_" target="_blank">@sangramgite_</a></p>
    </div>
  </section>

  <!-- ===== FOOTER ===== -->
  <footer>
    © 2025 Sangram Gite
  </footer>

</body>
</html>
