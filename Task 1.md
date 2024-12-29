<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
    }

    .container {
      width: 80%;
      margin: 0 auto;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      font-size: 2em;
    }

    nav ul {
      list-style-type: none;
      margin: 20px 0 0;
    }

    nav ul li {
      display: inline;
      margin-right: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1.1em;
    }

    nav ul li a:hover {
      text-decoration: underline;
    }

    section {
      padding: 40px 0;
    }

    section h2 {
      font-size: 2em;
      margin-bottom: 20px;
    }

    section p {
      font-size: 1.1em;
      line-height: 1.6;
    }

    .project {
      background-color: white;
      padding: 20px;
      margin: 10px 0;
      border-radius: 8px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }

    .project h3 {
      font-size: 1.5em;
      margin-bottom: 10px;
    }

    .project p {
      font-size: 1.1em;
    }

    footer {
      background-color: #333;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    footer p {
      font-size: 1em;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1>My Portfolio</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="about">
    <div class="container">
      <h2>About Me</h2>
      <p>Hello! , I'am Divyadharshini , I'm a web developer with a passion for creating beautiful and functional websites using HTML, CSS, JavaScript.</p>
    </div>
  </section>

  <section id="projects">
    <div class="container">
      <h2>My Projects</h2>
      <div class="project">
        <h3>Project 1</h3>
        <p>PERSONAL PORTFOLIO WEBSITE : A personal portfolio website is a place online where you can show your skills and work, built using HTML, CSS, and JavaScript.</p>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>TO DO LIST APP : A To-Do List app is a simple tool that helps you organize and manage your tasks which is built using HTML, CSS, and JavaScript</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Feel free to reach out to me via email: <a href="mailto:your-email@example.com">divyadharshini262005@gmail.com</a></p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2024 My Portfolio</p>
    </div>
  </footer>

</body>
</html>
