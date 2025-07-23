<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Naveen | Portfolio</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

  <header>
    <h1>Naveen</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="hero">
    <h2>Hello, I'm Naveen</h2>
    <p>A passionate web developer and tech enthusiast.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a web developer who loves creating beautiful and functional websites. I enjoy learning new technologies and solving real-world problems through code.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li><strong>Portfolio Website</strong> – My personal portfolio (this one!)</li>
      <li><strong>Weather App</strong> – Real-time weather updates using OpenWeather API</li>
      <li><strong>Todo List</strong> – Task manager using JavaScript and localStorage</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: kaushiknaveen120.com</p>
    <p>GitHub: <a href="https://github.com/naveen" target="_blank">github.com/naveen</a></p>
  </section>

  <footer>
    <p>© 2025 Naveen. All rights reserved.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
}

header h1 {
  margin-bottom: 0.5rem;
}

nav a {
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
}

#hero {
  background: #007acc;
  color: white;
  padding: 60px 20px;
  text-align: center;
}

section {
  padding: 40px 20px;
  max-width: 800px;
  margin: auto;
}

h2 {
  color: #007acc;
  margin-bottom: 15px;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 1rem;
}

a {
  color: #007acc;
}
// You can add interactive features later
console.log("Welcome to Naveen's Portfolio!");
