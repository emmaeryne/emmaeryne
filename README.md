<!doctype html>

<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Emna Awini — Portfolio</title>

  <!-- Fonts & icons -->

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --accent:#00bfff;
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#9aa4b2;
      --glass: rgba(255,255,255,0.03);
      --radius:14px;
      color-scheme: dark;
    }

    *{box-sizing:border-box}
    html,body{height:100%;}
    body{
      margin:0;
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(180deg,#071021 0%, #071827 100%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:32px;
      display:flex;
      align-items:flex-start;
      justify-content:center;
    }

    .container{
      width:100%;
      max-width:980px;
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:20px;
      padding:28px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.6);
      border:1px solid rgba(255,255,255,0.03);
    }

    header{
      display:flex;
      gap:20px;
      align-items:center;
      justify-content:space-between;
      margin-bottom:18px;
    }

    .intro{
      display:flex;
      gap:18px;
      align-items:center;
    }

    .avatar{
      width:92px;
      height:92px;
      border-radius:14px;
      background:linear-gradient(135deg,var(--accent),#6ad6ff);
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      font-size:34px;
      color:#022b3a;
      box-shadow: 0 6px 18px rgba(0,0,0,0.5), inset 0 -6px 22px rgba(255,255,255,0.02);
      flex-shrink:0;
    }

    .title h1{
      margin:0;
      font-size:20px;
      letter-spacing:0.2px;
    }
    .title p{
      margin:4px 0 0 0;
      color:var(--muted);
      font-size:13px;
    }

    .badges{
      display:flex;
      gap:8px;
      align-items:center;
    }

    .badges a img{height:34px; border-radius:8px; border:1px solid rgba(255,255,255,0.02)}

    main{
      margin-top:8px;
      display:grid;
      grid-template-columns: 1fr 340px;
      gap:18px;
    }

    .card{
      background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.015));
      border-radius: var(--radius);
      padding:18px;
      border: 1px solid rgba(255,255,255,0.03);
    }

    .about p{color:var(--muted); margin:0 0 8px 0; line-height:1.5}

    h2{
      margin:0 0 12px 0;
      font-size:16px;
      display:flex;
      gap:10px;
      align-items:center;
    }

    .projects ul{list-style:none; padding:0; margin:0; display:grid; gap:10px}
    .projects li{background:var(--glass); padding:10px; border-radius:10px; font-size:14px; color:#dbe9f8;}
    .values ul{list-style:none; padding:0; margin:0; display:flex; gap:8px; flex-direction:column}
    .values li{font-size:14px; color:var(--muted)}

    .techs{display:flex; gap:8px; flex-wrap:wrap; align-items:center; justify-content:flex-start}
    .techs img{height:36px; border-radius:8px; background:transparent}

    .right-column{display:flex; flex-direction:column; gap:12px}

    .stats-row{
      display:flex; gap:12px; align-items:center; justify-content:space-between;
      padding:12px; border-radius:12px; background:linear-gradient(180deg, rgba(0,0,0,0.12), rgba(255,255,255,0.01));
    }
    .stat{
      text-align:center;
      flex:1;
    }
    .stat h3{margin:0;font-size:22px;}
    .stat p{color:var(--muted); margin:6px 0 0 0; font-size:13px}

    .centered{display:flex; align-items:center; justify-content:center}

    .trophies img{max-width:100%; border-radius:10px}
    .contact{display:flex; gap:8px; align-items:center; justify-content:center}
    .contact a img{height:34px; border-radius:8px}

    footer{
      margin-top:18px;
      text-align:center;
      color:var(--muted);
      font-size:13px;
    }

    /* responsive */
    @media (max-width:900px){
      main{grid-template-columns: 1fr; }
      .right-column{order:2}
    }

    /* small utility */
    .muted{color:var(--muted)}
    .pill{display:inline-flex;gap:8px;align-items:center;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,0.02);font-size:13px}
    .copy-btn{background:transparent;border:1px solid rgba(255,255,255,0.04);padding:8px 10px;border-radius:10px;color:var(--muted);cursor:pointer}
  </style>

</head>
<body>
  <div class="container" role="main">

```
<header>
  <div class="intro">
    <div class="avatar">EA</div>
    <div class="title">
      <h1>Hello 👋, I'm <span style="color:var(--accent)">Emna Awini</span></h1>
      <p>A passionate Web & Mobile developer from Tunisia — Student @ ESPRIT</p>
    </div>
  </div>

  <div class="badges">
    <!-- badges: update links if needed -->
    <a href="https://www.youtube.com" title="Youtube"><img src="https://img.shields.io/badge/YouTube-Subscribe-red?logo=youtube&style=for-the-badge" alt="YouTube" /></a>
    <a href="https://www.linkedin.com/in/emma-awini-49b9671ba/" title="LinkedIn" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/LinkedIn-Emna%20Awini-blue?logo=linkedin&style=for-the-badge" alt="LinkedIn" /></a>
    <a href="https://github.com/emna-awini" title="GitHub" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/GitHub-emna--awini-black?logo=github&style=for-the-badge" alt="GitHub" /></a>
    <button class="copy-btn" id="copyEmailBtn" title="Copier l'email">📧 Copier email</button>
  </div>
</header>

<!-- top visitor counter (image from komarev) -->
<div class="centered" style="margin-bottom:14px">
  <img src="https://komarev.com/ghpvc/?username=emna-awini&style=flat-square&color=blue" alt="Visitors" />
</div>

<main>
  <!-- left -->
  <section class="card about">
    <h2>About Me</h2>
    <p>🎓 Software Engineering Student @ <strong>ESPRIT</strong>. Passionate about Web Development, Machine Learning, and Data Visualisation. I build full-stack apps, mobile prototypes with FlutterFlow, and analytics tools integrated with Power BI.</p>

    <h2 style="margin-top:18px">🎯 Recent Projects</h2>
    <div class="projects">
      <ul>
        <li>🚴‍♀️ <strong>Sports Complex Management</strong> — gestion des abonnements, plannings, réservations et inventaire.</li>
        <li>📱 <strong>FlutterFlow Mobile Apps</strong> — prototypes & apps cross-platform.</li>
        <li>🤖 <strong>Predictive Systems</strong> — modèles ML intégrés à Power BI pour la prise de décision.</li>
        <li>👩‍💼 <strong>HR Scoring</strong> — application de scoring pour recrutement.</li>
        <li>⚖️ <strong>Avocat Connect</strong> — plateforme sécurisée (lancement prévu en 2026).</li>
      </ul>
    </div>

    <h2 style="margin-top:18px">🌟 My Values</h2>
    <div class="values">
      <ul>
        <li>🤝 Teamwork & Communication</li>
        <li>🎯 Autonomy & Leadership</li>
        <li>📚 Continuous Learning & Sharing</li>
      </ul>
    </div>

    <h2 style="margin-top:18px">🧰 Languages, Tools & DB</h2>
    <div class="techs" title="Technologies">
      <!-- skillicons provides many icons -->
      <img src="https://skillicons.dev/icons?i=html" alt="HTML" />
      <img src="https://skillicons.dev/icons?i=css" alt="CSS" />
      <img src="https://skillicons.dev/icons?i=js" alt="JS" />
      <img src="https://skillicons.dev/icons?i=php" alt="PHP" />
      <img src="https://skillicons.dev/icons?i=symfony" alt="Symfony" />
      <img src="https://skillicons.dev/icons?i=flutter" alt="Flutter" />
      <img src="https://skillicons.dev/icons?i=figma" alt="Figma" />
      <img src="https://skillicons.dev/icons?i=github" alt="GitHub" />
      <img src="https://skillicons.dev/icons?i=git" alt="Git" />
      <img src="https://skillicons.dev/icons?i=vscode" alt="VSCode" />
      <img src="https://skillicons.dev/icons?i=linux" alt="Linux" />
      <img src="https://skillicons.dev/icons?i=postgres" alt="Postgres" />
      <img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" />
      <img src="https://skillicons.dev/icons?i=powerbi" alt="PowerBI" />
      <img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" />
      <img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" />
      <img src="https://skillicons.dev/icons?i=spring" alt="Spring" />
    </div>

    <h2 style="margin-top:18px">✨ Fun</h2>
    <p class="muted">"Coding is not just logic — it’s art in motion." 🎨</p>

  </section>

  <!-- right column -->
  <aside class="right-column">
    <div class="card centered" style="flex-direction:column;gap:12px;">
      <h2>📊 GitHub Stats</h2>
      <!-- GitHub stats images - replace username if needed -->
      <img src="https://github-readme-stats.vercel.app/api?username=emna-awini&show_icons=true&theme=radical" alt="GitHub Stats" style="width:100%;height:auto;border-radius:10px" />
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=emna-awini&theme=radical" alt="Streak" style="width:100%;height:auto;margin-top:8px;border-radius:10px" />
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=emna-awini&layout=compact&theme=radical" alt="Top Languages" style="width:100%;height:auto;margin-top:8px;border-radius:10px" />
    </div>

    <div class="card trophies">
      <h2>🏆 GitHub Trophies</h2>
      <div class="centered" style="padding-top:8px">
        <img src="https://github-profile-trophy.vercel.app/?username=emna-awini&theme=onedark&row=1&column=6" alt="Trophies" />
      </div>
    </div>

    <div class="card">
      <h2>📈 Contributions Snake</h2>
      <!-- The snake SVG often generated in GitHub READMEs; this path assumes a repo named emna-awini -->
      <div class="centered" style="padding:12px;">
        <img src="https://raw.githubusercontent.com/emna-awini/emna-awini/output/github-contribution-grid-snake.svg" alt="Contribution Snake" style="max-width:100%;border-radius:8px" />
      </div>
    </div>

    <div class="card stats-row">
      <div class="stat">
        <h3 id="totalContrib">218</h3>
        <p>Total Contributions</p>
      </div>
      <div class="stat">
        <h3 id="currentStreak">0</h3>
        <p>Current Streak</p>
      </div>
      <div class="stat">
        <h3 id="longestStreak">5</h3>
        <p>Longest Streak</p>
      </div>
    </div>

    <div class="card contact">
      <h2 style="width:100%;text-align:center">🌐 Connect</h2>
      <div class="contact" style="padding-top:8px">
        <a href="https://www.linkedin.com/in/emma-awini-49b9671ba/" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/LinkedIn-Emna%20Awini-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn" /></a>
        <a href="https://github.com/emna-awini" target="_blank" rel="noopener"><img src="https://img.shields.io/badge/GitHub-emna--awini-black?style=for-the-badge&logo=github" alt="GitHub" /></a>
        <a href="mailto:emna.awini@esprit.tn"><img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" alt="Email" /></a>
      </div>
    </div>

  </aside>
</main>

<footer>
  <small>Made with ❤️ • <span class="muted">Always learning • Always building</span></small>
</footer>
```

  </div>

  <script>
    // Replace these values if you want them to be dynamic or fetch via GitHub API.
    const githubMetrics = {
      totalContributions: 218,
      currentStreak: 0,
      longestStreak: 5
    };

    document.getElementById('totalContrib').textContent = githubMetrics.totalContributions;
    document.getElementById('currentStreak').textContent = githubMetrics.currentStreak;
    document.getElementById('longestStreak').textContent = githubMetrics.longestStreak;

    // copy email button
    const copyBtn = document.getElementById('copyEmailBtn');
    copyBtn.addEventListener('click', async () => {
      try{
        await navigator.clipboard.writeText('emna.awini@esprit.tn');
        copyBtn.textContent = '✅ Email copié';
        setTimeout(()=> copyBtn.textContent = '📧 Copier email', 2200);
      }catch(e){
        alert('Impossible de copier l\'email automatiquement. Email: emna.awini@esprit.tn');
      }
    });

    // Optional: load GitHub images fallback handling
    // If you want to display live numbers, you can call the GitHub REST API (requires CORS proxy or server-side).
  </script>

</body>
</html>
