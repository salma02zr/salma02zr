## Hi there, I'm Salma👋

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Salma — Tech Enthusiast</title>
  <link rel="stylesheet" href="styles.css">
  <meta name="description" content="Hi there, I'm Salma — a hardworking tech enthusiast. Portfolio and contact.">
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1>Hi there, I'm Salma 👋</h1>
      <p class="tagline">A hardworking person and passionate technophile. Always learning, building, and collaborating.</p>
      <nav class="nav">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="about" class="card">
      <h2>About</h2>
      <p>
        A highly hardworking and dedicated person who loves technology.
        Passionate about learning, experimenting, and finding creative solutions to problems.
      </p>
      <ul>
        <li><strong>Interests:</strong> technology, innovation, continuous learning</li>
        <li><strong>Philosophy:</strong> every day is a new opportunity to grow and improve</li>
        <li><strong>Goal:</strong> add value, share knowledge, and keep evolving</li>
      </ul>
    </section>

    <section id="projects" class="card">
      <h2>Projects</h2>
      <p>Examples of projects you can list or link here:</p>
      <ul id="project-list">
        <li><a href="#">Project One — Short description</a></li>
        <li><a href="#">Project Two — Short description</a></li>
      </ul>
      <button id="add-sample" class="btn">Add sample project</button>
    </section>

    <section id="contact" class="card">
      <h2>Contact</h2>
      <p>If you'd like to collaborate or say hi, reach me at <em>your-email@example.com</em> (replace with real email) or connect on <a href="https://github.com/your-username" target="_blank" rel="noopener">GitHub</a>.</p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>Made with ❤️ by Salma • <small>Repository template</small></p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
:root{
  --bg:#0f1724;
  --card:#0b1220;
  --muted:#bfc8d9;
  --accent:#6ee7b7;
  --glass: rgba(255,255,255,0.03);
  --radius:12px;
  --maxwidth:900px;
  font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
}

*{box-sizing:border-box}
html,body{height:100%;}
body{
  margin:0;
  background: linear-gradient(180deg,#061021 0%, #0a1220 100%);
  color:var(--muted);
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  line-height:1.6;
  padding-bottom:40px;
}

.container{
  width:calc(100% - 40px);
  max-width:var(--maxwidth);
  margin:0 auto;
}

.site-header{
  padding:32px 0;
  text-align:center;
}
.site-header h1{
  margin:0;
  font-size:1.8rem;
  color: white;
}
.tagline{margin:8px 0 16px; color: #9fb0c6}

.nav a{
  margin:0 8px;
  text-decoration:none;
  color:var(--accent);
  font-weight:600;
}

.card{
  background:var(--card);
  border-radius:var(--radius);
  padding:18px;
  margin:18px 0;
  box-shadow: 0 6px 20px rgba(2,6,23,0.6);
  border:1px solid rgba(255,255,255,0.03);
}

h2{color:#e6eef8; margin-top:0}
ul{padding-left:1.1rem}

.btn{
  display:inline-block;
  padding:10px 14px;
  border-radius:10px;
  border:none;
  background:linear-gradient(90deg,#3dd6a5,#1aa18a);
  color:#02221a;
  font-weight:700;
  cursor:pointer;
  margin-top:10px;
}

.site-footer{
  margin-top:28px;
  text-align:center;
  color:#89a0b8;
  font-size:0.9rem;
}

/* Responsive */
@media (min-width:820px){
  .site-header{padding:44px 0}
  .site-header h1{font-size:2.4rem}
}

