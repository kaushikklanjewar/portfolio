# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f4f4;
    }

    /* NAVIGATION MENU STYLING */
    nav {
      background-color: #222;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      font-size: 16px;
    }

    nav a:hover {
      color: #00bcd4;
    }

    header {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }

    section {
      padding: 20px;
    }

    footer {
      background-color: #333;
      color: white;
      padding: 10px;
      text-align: center;
    }

    ul {
      list-style-type: square;
      padding-left: 20px;
    }

    .btn {
      background-color: #007BFF;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <!-- Navigation Menu -->
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <header id="home">
    <img src="profile.png"alt="Kaushik's Photo" style="width:100px; height:100px; border-radius:50%; float:left; margin-right:15px;" />

    <h1>Kaushik Nitin Lanjewar</h1>
    <p>Computer Science Student</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a Computer Science student with a passion for technology and innovation. I enjoy building websites and exploring new tools in development. My aim is to become a skilled developer and contribute to impactful projects.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul>
      <li>C</li>
      <li>C++</li>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Basic Web Design</li>
    </ul>
    <h3>Skills Demonstration</h3>
    <button class="btn" onclick="showAlert()">Click Me</button>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:LANJEWARKAUSHIK285@gmail.com">LANJEWARKAUSHIK285@gmail.com</a></p>
    <p>Phone: <a href="tel:8261859435">8261859435</a></p>
  </section>

  <footer>
    <p>© 2025 Kaushik Nitin Lanjewar</p>
  </footer>

  <script>
    function showAlert() {
      alert("Hello! This is a JavaScript alert from Kaushik.");
    }
  </script>

</body>
</html>
