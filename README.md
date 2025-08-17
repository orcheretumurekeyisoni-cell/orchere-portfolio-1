 <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Orchere Tumurekeyisoni — Portfolio</title>
  <style>
    body {font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; color: #222;}
    header, footer {background: #1a1a1a; color: #fff; padding: 1rem;}
    nav a {margin: 0 10px; color: #fff; text-decoration: none;}
    .container {max-width: 900px; margin: auto; padding: 1.5rem;}
    section {margin-bottom: 2rem;}
    h1, h2 {color: #333;}
    .card {background: #fff; padding: 1rem; border-radius: 8px; box-shadow: 0 2px 6px rgba(0,0,0,0.1); margin-top: 1rem;}
    a {color: #0066cc;}
  </style>
</head>
<body>
  <header>
    <h1>Orchere Tumurekeyisoni</h1>
    <p>Aspiring Software Engineer • ALX Rwanda Pathway</p>
    <nav>
      <a href="#bio">Bio</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#elevator">Elevator Pitch</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section id="bio">
      <h2>Bio</h2>
      <div class="card">
        <p>I am Orchere Tumurekeyisoni, a motivated student currently on the ALX Rwanda Pathway in Software Engineering. I am passionate about building user-friendly web apps that solve real problems in my community.</p>
      </div>
    </section>

    <section id="portfolio">
      <h2>Portfolio</h2>
      <div class="card">
        <p><strong>Phase 2 Project Video:</strong> <a href="https://www.youtube.com/watch?v=YOUR_VIDEO_ID" target="_blank">Watch Here</a></p>
        <p><strong>Phase 2 Project Slides (PDF):</strong> <a href="https://example.com/Your-Phase-2-Slides.pdf" target="_blank">View PDF</a></p>
      </div>
    </section>

    <section id="elevator">
      <h2>Elevator Pitch</h2>
      <div class="card">
        <p>Placeholder for my elevator pitch. Coming soon.</p>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <div class="card">
        <p>Email: <a href="mailto:orchere@example.com">orchere@example.com</a></p>
        <p>LinkedIn: <a href="#" target="_blank">Add Link</a></p>
      </div>
    </section>
  </main>

  <footer>
    <p>© <span id="year"></span> Orchere Tumurekeyisoni</p>
  </footer>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
