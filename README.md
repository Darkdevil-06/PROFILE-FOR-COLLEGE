<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Manikandan P | Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    background: #0b0b0b;
    color: #ffffff;
  }

  /* NAVBAR */
  nav {
    width: 100%;
    background: #000;
    padding: 15px 0;
    position: fixed;
    top: 0;
    z-index: 1000;
  }

  .nav-container {
    max-width: 1100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
  }

  nav h1 {
    color: #ffcc00;
    font-size: 22px;
  }

  nav a {
    color: #fff;
    text-decoration: none;
    margin-left: 20px;
    font-size: 14px;
  }

  nav a:hover {
    color: #ffcc00;
  }

  /* MAIN WRAPPER */
  .wrapper {
    max-width: 1100px;
    margin: auto;
    padding: 120px 20px 40px;
  }

  section {
    margin-bottom: 50px;
    background: linear-gradient(135deg, #111, #1a1a1a);
    padding: 30px;
    border-left: 4px solid #ffcc00;
  }

  h2 {
    color: #ffcc00;
    margin-bottom: 15px;
  }

  ul {
    line-height: 1.8;
    padding-left: 20px;
  }

  footer {
    text-align: center;
    padding: 20px;
    color: #aaa;
    border-top: 1px solid #222;
  }
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
  <div class="nav-container">
    <h1>Manikandan P</h1>
    <div>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
    </div>
  </div>
</nav>

<!-- CONTENT -->
<div class="wrapper">

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a Biotechnology student with strong coordination and teamwork skills.
      I communicate clearly, manage responsibilities effectively, and ensure
      smooth execution of tasks. I am interested in learning technology alongside
      my academic background.
    </p>
  </section>

  <section id="skills">
    <h2>Technical Skills</h2>
    <ul>
      <li>Basic Web Technologies (HTML, CSS, JavaScript)</li>
      <li>Data Handling & Documentation</li>
      <li>Research Assistance & Analysis</li>
      <li>Technology Adaptability</li>
    </ul>
  </section>

  <section>
    <h2>Soft Skills & Coordination</h2>
    <ul>
      <li>Excellent Coordination & Teamwork</li>
      <li>Clear Communication</li>
      <li>Leadership & Responsibility Handling</li>
      <li>Time Management & Discipline</li>
    </ul>
  </section>

  <section id="projects">
    <h2>Projects / Work</h2>
    <ul>
      <li>Academic coordination for college activities</li>
      <li>Support role in events and group tasks</li>
    </ul>
  </section>

</div>

<footer>
  © 2026 Manikandan P | Profile for College
</footer>

</body>
</html>
