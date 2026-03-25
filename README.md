<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Alok Pradhan | AI/ML Engineer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0A66C2, #6C63FF);
      color: white;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 80px 20px;
    }

    header h1 {
      font-size: 3rem;
      animation: fadeIn 2s ease-in-out;
    }

    header p {
      margin-top: 10px;
      font-size: 1.2rem;
      opacity: 0.9;
    }

    nav {
      text-align: center;
      margin: 20px 0;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 500;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .card {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      padding: 20px;
      border-radius: 15px;
      margin: 20px 0;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .tech span {
      display: inline-block;
      background: rgba(255,255,255,0.2);
      padding: 8px 12px;
      margin: 5px;
      border-radius: 8px;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: rgba(0,0,0,0.2);
    }

    @keyframes fadeIn {
      from {opacity: 0; transform: translateY(20px);}
      to {opacity: 1; transform: translateY(0);}
    }

  </style>
</head>

<body>

<header>
  <h1>Alok Pradhan</h1>
  <p>AI | ML Engineer | Full Stack Developer 🚀</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#tech">Tech Stack</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <div class="card">
    <h2>👨‍💻 About Me</h2>
    <p>
      B.Tech CSE (AI & ML) student passionate about building intelligent, scalable systems.
      Strong focus on AI, backend, and system design.
    </p>
  </div>
</section>

<section id="tech">
  <div class="card">
    <h2>🛠 Tech Stack</h2>
    <div class="tech">
      <span>Python</span>
      <span>Java</span>
      <span>C++</span>
      <span>JavaScript</span>
      <span>TensorFlow</span>
      <span>PyTorch</span>
      <span>Node.js</span>
      <span>MongoDB</span>
      <span>Docker</span>
    </div>
  </div>
</section>

<section id="projects">
  <div class="card">
    <h2>🚀 Projects</h2>

    <h3>Machine Records Management System</h3>
    <p>Node.js, Express, MongoDB based industrial data system with analytics dashboard.</p>

    <h3>Airline Management System</h3>
    <p>Java Swing desktop application for booking and reservations.</p>

    <h3>AI Chatbot</h3>
    <p>Python-based rule-driven chatbot with modular design.</p>

    <h3>Face Recognition System</h3>
    <p>Java-based biometric prototype for face detection.</p>
  </div>
</section>

<section id="contact">
  <div class="card">
    <h2>🌐 Contact</h2>
    <p>Email: alokpradhan719@gmail.com</p>
    <p>
      <a href="https://github.com/alokpradhan719" style="color:white;">GitHub</a> |
      <a href="https://linkedin.com" style="color:white;">LinkedIn</a>
    </p>
  </div>
</section>

<footer>
  <p>⚡ Turning Ideas into Intelligent Systems ⚡</p>
</footer>

</body>
</html>
