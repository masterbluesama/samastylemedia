<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SAMA Style Media</title>

  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@300;400;600&family=Syne:wght@400;600;800&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #080808;
      --surface: #111;
      --border: #1e1e1e;
      --text: #fff;
      --muted: #888;
      --accent: #c9a96e;
    }

    *, *::before, *::after {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Cormorant Garamond', Georgia, serif;
      line-height: 1.7;
      overflow-x: hidden;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* NAV */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 100;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 22px 48px;
      background: rgba(8,8,8,0.85);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid var(--border);
    }

    .nav-logo {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 1.1rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
    }

    .nav-links {
      display: flex;
      gap: 36px;
      list-style: none;
    }

    .nav-links a {
      font-family: 'Syne', sans-serif;
      font-size: 0.78rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: var(--muted);
      transition: color 0.3s;
    }

    .nav-links a:hover {
      color: var(--accent);
    }

    /* HERO */
    .hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 120px 24px 80px;
      position: relative;
    }

    .hero-eyebrow {
      font-family: 'Syne', sans-serif;
      font-size: 0.72rem;
      letter-spacing: 0.3em;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 28px;
    }

    .hero h1 {
      font-size: clamp(3rem, 8vw, 7rem);
      font-weight: 300;
      margin-bottom: 28px;
    }

    .hero h1 em {
      color: var(--accent);
    }

    .hero p {
      font-size: clamp(1rem, 2vw, 1.3rem);
      color: var(--muted);
      max-width: 560px;
      margin-bottom: 44px;
    }

    .hero-actions {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .btn {
      padding: 14px 32px;
      font-family: 'Syne', sans-serif;
      font-size: 0.8rem;
      font-weight: 600;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      border-radius: 2px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn-primary {
      background: var(--accent);
      color: #000;
      border: 1px solid var(--accent);
    }

    .btn-primary:hover {
      background: transparent;
      color: var(--accent);
    }

    .btn-outline {
      border: 1px solid var(--border);
    }

    .btn-outline:hover {
      border-color: var(--text);
    }

    section {
      padding: 100px 48px;
      max-width: 1140px;
      margin: auto;
    }

    h2 {
      font-size: clamp(2rem, 4vw, 3.5rem);
      font-weight: 300;
      margin-bottom: 20px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2px;
    }

    .card {
      background: var(--surface);
      padding: 40px;
      border: 1px solid var(--border);
    }

    .card h3 { margin-bottom: 12px; }

    .card p {
      color: var(--muted);
    }

    .cta {
      text-align: center;
      padding: 100px 24px;
      border-top: 1px solid var(--border);
    }

    footer {
      text-align: center;
      padding: 28px;
      font-size: 0.75rem;
      color: #333;
      border-top: 1px solid var(--border);
    }

    @media (max-width: 768px) {
      .nav-links { display: none; }
      section { padding: 70px 24px; }
    }
  </style>
</head>

<body>

<nav>
  <span class="nav-logo">SAMA Style Media</span>
  <ul class="nav-links">
    <li><a href="#services">Services</a></li>
    <li><a href="#work">Work</a></li>
    <li><a href="#testimonials">Clients</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<div class="hero">
  <p class="hero-eyebrow">Visual Storytelling & Creative Direction</p>
  <h1>Make Every Frame <em>Matter</em></h1>
  <p>Photography, videography, and creative direction crafted to elevate your brand.</p>
  <div class="hero-actions">
    <a href="#contact" class="btn btn-primary">Book a Session</a>
    <a href="#services" class="btn btn-outline">Explore Services</a>
  </div>
</div>

<section id="services">
  <h2>Services</h2>
  <div class="grid">
    <div class="card">
      <h3>Photography</h3>
      <p>Portraits, lifestyle, and branding content.</p>
    </div>
    <div class="card">
      <h3>Videography</h3>
      <p>High-quality video production.</p>
    </div>
    <div class="card">
      <h3>Creative Direction</h3>
      <p>Concept and storytelling to elevate your brand.</p>
    </div>
  </div>
</section>

<div class="cta" id="contact">
  <h2>Let's Create Something Powerful</h2>
  <p>Ready to elevate your visuals? Let's talk.</p>
  <a href="mailto:youremail@example.com" class="btn btn-primary">Contact Now</a>
</div>

<footer>
  &copy; 2026 SAMA Style Media. All rights reserved.
</footer>

</body>
</html>
