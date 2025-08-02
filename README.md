<!-- ────────────────────────────────────────────
     Abhik Anand • Dynamic 3-D GitHub Profile
     Save this entire block as README.md
────────────────────────────────────────────── -->

<!-- ✨ Parallax multitone background -->
<style>
/* Core reset */
*{margin:0;padding:0;box-sizing:border-box;font-family:system-ui,Segoe UI,Roboto}
/* Animated gradient backdrop */
body{
  --c1:#0f0c29;
  --c2:#302b63;
  --c3:#24243e;
  background:linear-gradient(-45deg,var(--c1),var(--c2),var(--c3));
  background-size:400% 400%;
  animation:bgShift 18s ease infinite;
  color:#f0f0f0;
}
@keyframes bgShift{0%{background-position:0 50%}50%{background-position:100% 50%}100%{background-position:0 50%}}
section{max-width:950px;margin:6rem auto;padding:2rem 1.6rem}

/* Glassy “card” containers */
.card{
  background:#151522cc;
  border:1px solid #ffffff22;
  border-radius:16px;
  backdrop-filter:blur(10px);
  box-shadow:0 6px 24px #00000088;
  padding:2.3rem 2rem;
  margin-bottom:3rem;
}

/* 3-D spinning name */
#name3d{
  font-size:clamp(2.8rem,7vw,5.6rem);
  font-weight:900;
  text-align:center;
  letter-spacing:2.5px;
  perspective:700px;
}
#name3d span{
  display:inline-block;
  transform-style:preserve-3d;
  animation:spin 9s linear infinite;
}
@keyframes spin{
  0%{transform:rotateY(0deg) translateZ(0)}
  100%{transform:rotateY(360deg) translateZ(0)}
}

/* Badge bar */
.badges a{margin:0 .35rem}
.badges img{height:28px}

/* Skill icons grid */
.skills{display:flex;flex-wrap:wrap;justify-content:center;gap:.8rem}
.skills img{height:42px;filter:drop-shadow(0 0 4px #0009)}

/* Tables */
table{width:100%;border-collapse:collapse}
th,td{padding:.65rem;border:1px solid #ffffff2a}
tr:nth-child(odd){background:#ffffff07}

/* Center helpers */
.center{display:flex;flex-wrap:wrap;justify-content:center;gap:1.2rem}
</style>

<!-- ╭───────────────────╮ -->
<!-- │ 3-D Name Banner   │ -->
<!-- ╰───────────────────╯ -->
<section>
  <div id="name3d"><span>ABHIK&nbsp;ANAND</span></div>
  <p align="center"><i>Backend craftsman • Flutter padawan • API perfectionist</i></p>
</section>

<!-- ╭─────────────╮ -->
<!-- │ About Me    │ -->
<!-- ╰─────────────╯ -->
<section class="card">
  <h2>🚀 What I’m Doing</h2>
  <ul>
    <li>🔭 Migrating legacy monoliths → micro-services (Node.js & Express).</li>
    <li>🌱 Building mobile front-ends in Flutter + Dart.</li>
    <li>💬 Ping me about web dev, CI/CD on a budget, or clean API design.</li>
    <li>📫 <b>anand.firm.dev@gmail.com</b></li>
  </ul>
</section>

<!-- ╭────────────────╮ -->
<!-- │ Social Links   │ -->
<!-- ╰────────────────╯ -->
<section class="card">
  <h2>🌍 Connect</h2>
  <p class="badges" align="center">
    <a href="https://github.com/AbhikAnand">
      <img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white">
    </a>
    <a href="https://www.instagram.com/avixoxo_7">
      <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
    </a>
    <!-- <a href="https://twitter.com/YOUR_HANDLE">
      <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">
    </a> -->
  </p>
</section>

<!-- ╭──────────────╮ -->
<!-- │ Tech Stack   │ -->
<!-- ╰──────────────╯ -->
<section class="card">
  <h2>🛠️ Tech Stack</h2>
  <div class="skills">
    <img src="https://skillicons.dev/icons?i=flutter" alt="Flutter">
    <img src="https://skillicons.dev/icons?i=dart" alt="Dart">
    <img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js">
    <img src="https://skillicons.dev/icons?i=express" alt="Express">
    <img src="https://skillicons.dev/icons?i=html" alt="HTML">
    <img src="https://skillicons.dev/icons?i=css" alt="CSS">
    <img src="https://skillicons.dev/icons?i=javascript" alt="JavaScript">
    <img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB">
    <img src="https://skillicons.dev/icons?i=git" alt="Git">
    <img src="https://skillicons.dev/icons?i=unity" alt="Unity">
  </div>
</section>

<!-- ╭────────────────────╮ -->
<!-- │ GitHub Statistics │ -->
<!-- ╰────────────────────╯ -->
<section class="card">
  <h2>📈 GitHub Stats</h2>
  <div class="center">
    <img src="https://github-readme-stats.vercel.app/api?username=AbhikAnand&show_icons=true&theme=transparent&hide_rank=true" width="48%">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AbhikAnand&layout=compact&theme=transparent&langs_count=8" width="48%">
  </div>
</section>

<!-- ╭────────────╮ -->
<!-- │ Projects   │ -->
<!-- ╰────────────╯ -->
<section class="card">
  <h2>✨ Recent Projects</h2>
  <table>
    <tr><th>Project</th><th>Description</th><th>Tech</th></tr>
    <tr><td><b>TaskNest</b></td><td>Real-time Kanban with drag-and-drop</td><td>Flutter • Firebase RTDB</td></tr>
    <tr><td><b>API-Quickstart</b></td><td>Express boilerplate with auth & tests</td><td>Node.js • MongoDB</td></tr>
    <tr><td><b>Pixel-Runner</b></td><td>Weekend 2-D endless-runner</td><td>Unity • C#</td></tr>
  </table>
</section>

<!-- ╭─────────╮ -->
<!-- │ Footer  │ -->
<!-- ╰─────────╯ -->
<section>
  <blockquote align="center">“Code is like humor. When you have to explain it, it’s bad.” — Cory House</blockquote>
  <p align="center">Thanks for stopping by – ⭐ if you like the vibe!</p>
</section>
