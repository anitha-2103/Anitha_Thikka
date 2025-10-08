<!--
Portfolio for: Thikka Anitha
File: index.html
Instructions:
1. Create a new GitHub repository (example: anitha-2103.github.io) and push this index.html file to the root.
2. Add your Resume.pdf to the repository root and update RESUME_URL below if needed.
3. Enable GitHub Pages (branch: main, folder: / (root)).
4. Visit: https://<your-username>.github.io after deployment.
-->

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Thikka Anitha — Portfolio</title>
  <meta name="description" content="Thikka Anitha — B.Tech CSE. AI, Web Development, and IoT Projects Portfolio.">
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#9aa4b2;--accent:#6ee7b7}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;background:linear-gradient(180deg,#071028 0%, #071b2f 100%);color:#e6eef6;line-height:1.5}
    .container{max-width:980px;padding:28px;margin:0 auto}
    header{display:flex;gap:18px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#60a5fa);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:#05202a}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin-top:6px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:24px}
    .card{background:rgba(255,255,255,0.03);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
    .section-title{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .chip{background:rgba(255,255,255,0.04);padding:8px 10px;border-radius:999px;color:var(--muted);font-size:13px}
    .projects{display:flex;flex-direction:column;gap:12px}
    .project{padding:12px;border-radius:10px;background:linear-gradient(180deg,rgba(255,255,255,0.015),transparent);border:1px solid rgba(255,255,255,0.03)}
    a.cta{display:inline-block;background:var(--accent);color:#05202a;padding:10px 14px;border-radius:10px;text-decoration:none;font-weight:600}
    footer{margin-top:26px;color:var(--muted);font-size:13px;text-align:center}
    nav{display:flex;gap:10px;flex-wrap:wrap}
    nav a{color:var(--muted);text-decoration:none;font-size:14px}
    .contact-list{display:flex;flex-direction:column;gap:8px}
    .certs{display:flex;flex-direction:column;gap:6px}
    pre.reslink{background:rgba(255,255,255,0.02);padding:8px;border-radius:8px;color:var(--muted);overflow:auto}
    @media (max-width:880px){.grid{grid-template-columns:1fr;}.avatar{width:80px;height:80px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">AT</div>
      <div>
        <h1>Thikka Anitha</h1>
        <p class="lead">B.Tech (CSE) — AI, Web Development &amp; IoT Enthusiast<br>Ongole, Andhra Pradesh · <a href="mailto:anithaanithathikka@gmail.com" style="color:var(--accent);text-decoration:none">anithaanithathikka@gmail.com</a></p>
      </div>
      <nav style="margin-left:auto">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <div class="grid">
      <main>
        <section id="about" class="card">
          <div class="section-title"><h2>About</h2><small style="color:var(--muted)">B.Tech CSE | 2022-2026</small></div>
          <p>I am <strong>Thikka Anitha</strong>, currently pursuing Computer Science Engineering. I have a deep interest in Python, Java, Web Development (Flask), and IoT projects. I’m passionate about learning new technologies and solving real-world problems.</p>
          <p style="margin-top:8px;color:var(--muted)"><strong>Objective:</strong> To apply my technical skills, gain experience, and contribute effectively to an organization while continuously learning.</p>
          <p style="margin-top:10px"><a class="cta" href="#projects">View My Projects</a></p>
        </section>

        <section id="projects" class="card" style="margin-top:16px">
          <div class="section-title"><h2>Projects</h2><small style="color:var(--muted)">Add GitHub links to each project</small></div>
          <div class="projects">
            <div class="project">
              <h3>Career Recommendation System</h3>
              <p style="color:var(--muted)">Tech Used: Python, Flask, HTML, CSS, JavaScript, MySQL</p>
              <p>Description: A web application that helps students find career paths based on their interests, skills, and academic background.</p>
              <p style="margin-top:8px"><a href="https://github.com/anitha-2103/career-recommendation-system" target="_blank">GitHub Repo</a></p>
            </div>

            <div class="project">
              <h3>Language Translator</h3>
              <p style="color:var(--muted)">Tech Used: Python, Speech Recognition, Translation APIs, Text-to-Speech</p>
              <p>Description: A real-time translator that converts speech or text between different languages, helping people communicate seamlessly.</p>
              <p style="margin-top:8px"><a href="https://github.com/anitha-2103/language-translator" target="_blank">GitHub Repo</a></p>
            </div>

            <div class="project">
              <h3>Other Projects / Demos</h3>
              <p style="color:var(--muted)">Make sure your public GitHub repositories include a clear README with tech stack, setup instructions, and screenshots.</p>
            </div>
          </div>
        </section>

        <section id="skills" class="card" style="margin-top:16px">
          <div class="section-title"><h2>Skills</h2><small style="color:var(--muted)">Technical & Soft Skills</small></div>
          <div class="skills">
            <span class="chip">Python</span>
            <span class="chip">Java</span>
            <span class="chip">HTML</span>
            <span class="chip">CSS</span>
            <span class="chip">JavaScript</span>
            <span class="chip">Flask</span>
            <span class="chip">MySQL</span>
            <span class="chip">NumPy</span>
            <span class="chip">Pandas</span>
            <span class="chip">Matplotlib</span>
            <span class="chip">Git / GitHub</span>
          </div>
        </section>

        <section id="certifications" class="card" style="margin-top:16px">
          <div class="section-title"><h2>Certifications</h2></div>
          <div class="certs">
            <div>Internet Of Things - NPTEL</div>
            <div>Python Programming - CodeTantra</div>
            <div>Web Full Stack Developer Internship - Eduskills</div>
          </div>
        </section>

      </main>

      <aside>
        <div class="card">
          <h3>Contact</h3>
          <div class="contact-list">
            <div><strong>Phone:</strong> 6320645123</div>
            <div><strong>Email:</strong> <a href="mailto:anithaanithathikka@gmail.com">anithaanithathikka@gmail.com</a></div>
            <div><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/anitha-thikka-705176291" target="_blank">anitha-thikka</a></div>
            <div><strong>GitHub:</strong> <a href="https://github.com/anitha-2103" target="_blank">anitha-2103</a></div>
          </div>

          <hr style="margin:14px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">

          <h4>Resume</h4>
          <p class="muted" style="color:var(--muted)">Use the button below to view or download your resume (add Resume.pdf to your repo root).</p>
          <pre class="reslink">RESUME_URL = ./Resume.pdf</pre>
          <p style="margin-top:8px"><a id="downloadResume" class="cta" href="./Resume.pdf" target="_blank">View / Download Resume</a></p>

          <hr style="margin:14px 0;border:none;border-top:1px solid rgba(255,255,255,0.03)">

          <h4>Quick Links</h4>
          <p style="margin:0"><a href="#projects">Projects</a> · <a href="#skills">Skills</a> · <a href="#contact">Contact</a></p>
        </div>

        <div class="card" style="margin-top:14px">
          <h3>Deployment Instructions</h3>
          <ol style="color:var(--muted);padding-left:18px;margin:8px 0">
            <li>Create a new GitHub repo (example: <code>anitha-2103.github.io</code>).</li>
            <li>Upload this file as <code>index.html</code> in the repository root.</li>
            <li>Upload your <code>Resume.pdf</code> to the repository root as well.</li>
            <li>Go to Settings → Pages → Branch: <code>main</code>, Folder: <code>/ (root)</code> → Save.</li>
            <li>After a few minutes, visit your page at https://anitha-2103.github.io (or your username.github.io).</li>
          </ol>
        </div>
      </aside>
    </div>

    <footer>
      <div style="display:flex;justify-content:center;gap:12px;align-items:center;flex-wrap:wrap">
        <div>© <strong>Thikka Anitha</strong> 2025</div>
        <div style="color:var(--muted)">Made with ❤️ • Hosted on GitHub Pages</div>
      </div>
    </footer>
  </div>

  <script>
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',function(e){
        e.preventDefault();
        const id = this.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if(el) el.scrollIntoView({behavior:'smooth',block:'start'});
      });
    });
  </script>
</body>
</html>
