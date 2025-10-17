<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>GitHub Profile — Professional README</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#f59e0b;--glass: rgba(255,255,255,0.03)}
    html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial}
    body{display:flex;align-items:center;justify-content:center;background:linear-gradient(180deg,#071024 0%, #071a2b 100%);color:#e6eef8;padding:32px}
    .card{width:100%;max-width:900px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));box-shadow:0 10px 30px rgba(2,6,23,0.6);border-radius:14px;padding:28px;border:1px solid rgba(255,255,255,0.03)}
    .top{display:flex;gap:20px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:14px;overflow:hidden;border:2px solid rgba(255,255,255,0.04);flex:0 0 96px}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    .intro{flex:1}
    h1{margin:0;font-size:22px;letter-spacing:0.2px}
    .subtitle{color:var(--muted);margin-top:6px;font-size:14px}
    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badges img{height:22px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px;margin-top:22px}
    .section{background:var(--glass);padding:18px;border-radius:10px;border:1px solid rgba(255,255,255,0.02)}
    .section h3{margin:0 0 10px 0;font-size:14px}
    .about p{margin:0;color:var(--muted);line-height:1.45}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .skill{font-size:13px;background:rgba(255,255,255,0.03);padding:8px 10px;border-radius:8px;border:1px solid rgba(255,255,255,0.02)}
    .projects a{display:block;color:#dbeafe;text-decoration:none;margin-bottom:8px}
    .stats img{width:100%;border-radius:8px}
    .contact{display:flex;flex-direction:column;gap:8px}
    .contact a{color:#cfe8ff;text-decoration:none}
    .footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}
    @media (max-width:880px){.grid{grid-template-columns:1fr;}.top{flex-direction:row;}}
  </style>
</head>
<body>
  <article class="card">
    <div class="top">
      <div class="avatar">
        <!-- Replace src with your avatar url -->
        <img src="https://avatars.githubusercontent.com/u/9919?s=200&v=4" alt="avatar">
      </div>
      <div class="intro">
        <h1> Pawan Chouhan — B.Tech Student & Aspiring Full-Stack Developer</h1>
        <div class="subtitle">Learning full-stack web development • Building real-world projects • Keen on clean, maintainable code</div>
        <div class="badges">
          <!-- Example badges — replace `username` and `repo` where needed -->
          <img src="https://img.shields.io/badge/Status-Learning%20MERN-blueviolet" alt="status">
          <img src="https://img.shields.io/badge/Stack-MERN-green" alt="stack">
          <img src="https://img.shields.io/badge/Experience-Projects%20%3E%203-ffb703" alt="projects">
          <img src="https://img.shields.io/badge/Email-deepak%40example.com-lightgrey" alt="email">
        </div>
      </div>
    </div>

    <div class="grid">
      <section class="section about">
        <h3>About</h3>
        <p>
          I'm a B.Tech student focused on full-stack development. I enjoy turning ideas into working web applications — building user-friendly frontends and robust backends. Currently learning MERN (MongoDB, Express, React, Node) and applying concepts by building real-world projects: authentication systems, CRUD dashboards, and deployable apps.
        </p>

        <div style="margin-top:14px">
          <h3 style="font-size:13px;margin-bottom:8px">Core Focus</h3>
          <div class="skills">
            <span class="skill">JavaScript (ES6+)</span>
            <span class="skill">React / Next.js</span>
            <span class="skill">Node.js & Express</span>
            <span class="skill">MongoDB / SQL</span>
            <span class="skill">HTML & CSS (Tailwind)</span>
            <span class="skill">REST APIs & Auth</span>
            <span class="skill">Git & CI/CD</span>
          </div>
        </div>
      </section>

     /* <aside class="section">
        <div class="projects">
          <h3>Highlighted Projects</h3>
          <!-- Replace href with actual repo links -->
          <a href="#">🔗 NextZone Championship — Tournament website (React + Node)</a>
          <a href="#">🔗 Study Tracker App — Habit & session tracker (MERN)</a>
          <a href="#">🔗 Letter Generator — React dynamic form tool</a>
        </div>*/

        <div style="margin-top:12px" class="stats">
          <h3 style="font-size:13px;margin-bottom:10px">GitHub Stats</h3>
          <!-- These images are examples from common GitHub README stat tools — replace `username` -->
          <img src="https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=radical" alt="github-stats">
        </div>

        <div style="margin-top:12px" class="contact">
          <h3 style="font-size:13px;margin-bottom:6px">Contact</h3>
          <a href="mailto:deepak@example.com">📧 deepak@example.com</a>
          <a href="#">🔗 LinkedIn</a>
          <a href="#">🔗 Portfolio / Website</a>
        </div>
      </aside>
    </div>

    <div class="footer">Want this personalized (name, avatar, repos, badges)? Tell me what to replace and I'll update it.</div>
  </article>
</body>
</html>
