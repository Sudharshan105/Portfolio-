# Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Portfolio Example</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f4f6f9;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #2e86de, #1b4f72);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffeb3b;
    }
    main {
      max-width: 900px;
      margin: 20px auto;
      padding: 20px;
    }
    section {
      margin-bottom: 40px;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
    }
    footer {
      background: #2e86de;
      color: white;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #ffeb3b;
    }
  </style>
</head>
<body>

<header>
  <h1>Dasappagari Sudharshan</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main>
  <section id="about">
    <h2>About Me</h2>
    <p>Motivated MCA graduate passionate about creating impactful solutions using Python, Java, and modern web technologies.</p>
  </section>

  <section id="skills">
    <h2>Technical Skills</h2>
    <ul>
      <li>Python, Java</li>
      <li>HTML, CSS, JavaScript</li>
      <li>Django, Spring</li>
      <li>MySQL, ADBMS</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="card">
      <h3>SQL Injection Detection Web App</h3>
      <p>Built with Django and ML models to enhance web security and prevent attacks.</p>
    </div>
    <div class="card">
      <h3>Seminar Review System</h3>
      <p>College seminar management app using Django and SQLite.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:dsudharshan105@gmail.com">dsudharshan105@gmail.com</a></p>
    <p>GitHub: <a href="https://github.com/Sudharshan105" target="_blank">View Profile</a></p>
  </section>
</main>

<footer>
  <p>© 2025 Dasappagari Sudharshan</p>
</footer>

</body>
</html>
