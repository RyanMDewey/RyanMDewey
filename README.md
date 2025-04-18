<!-- Matrix Header Block -->
<div style="height: 300px; overflow: hidden; position: relative;">
  <canvas id="matrixCanvas"></canvas>
</div>

<!-- GitHub-Style CV Layout -->
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono&display=swap" rel="stylesheet">
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: 'JetBrains Mono', monospace;
    background-color: #0b0b0b;
    color: #f4f4f4;
  }

  .container {
    max-width: 900px;
    margin: 0 auto;
    padding: 3rem 2rem;
  }

  h1, h2, h3 {
    color: #00ffcc;
    margin-top: 2.5rem;
    text-shadow: 0 0 6px #00ffcc;
  }

  .skills, .developer-metrics img, .tools, .project-links ul {
    margin-top: 1rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    justify-content: center;
  }

  .skill-tag {
    background-color: #1a1a1a;
    color: #00ffcc;
    border: 1px solid #00ffcc88;
    padding: 0.4rem 0.8rem;
    border-radius: 6px;
    font-size: 0.9rem;
  }

  canvas {
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1;
  }

  .theme-toggle {
    position: fixed;
    top: 1rem;
    right: 1rem;
    background: #00ffcc22;
    color: #00ffe1;
    border: 1px solid #00ffe188;
    padding: 0.5rem 1rem;
    border-radius: 6px;
    cursor: pointer;
    font-size: 0.85rem;
    z-index: 9999;
  }

  body.light-mode {
    background-color: #ffffff;
    color: #222;
  }
  body.light-mode h1, 
  body.light-mode h2, 
  body.light-mode h3 {
    color: #222;
  }
  body.light-mode .skill-tag,
  body.light-mode .skills img,
  body.light-mode a {
    filter: grayscale(0.2);
  }
</style>

<button class="theme-toggle" onclick="toggleTheme()">🌗 Toggle Theme</button>

<div class="container">
  <header style="text-align: center;">
    <h1>🚀 Ryan Dewey</h1>
    <p><strong>Architect of Intelligence</strong> · <strong>Founder of NEXUSARC</strong> · <strong>Creator of Lumina (ORC Language)</strong></p>
    <p><em>Designing systems that evolve, languages that learn, and futures that remember us.</em></p>
  </header>

  <section>
    <h2>🧠 About Me</h2>
    <p>I'm a forward-thinking computer scientist focused on the convergence of AI, quantum computing, blockchain, and post-silicon infrastructure. My work revolves around building autonomous systems, intelligent compilers, and full-stack architectures designed for long-term adaptation and sentient interaction.</p>
  </section>

  <section>
  <h2>📂 Featured Projects</h2>
  <div class="tools">
    <a href="https://github.com/RyanMDewey/ORC" target="_blank">
      <img src="https://img.shields.io/badge/Lumina_ORC-Language-00ffcc?style=flat-square&logo=code&logoColor=white" alt="Lumina ORC">
    <a href="https://github.com/RyanMDewey/oracle-ledger" target="_blank">
      <img src="https://img.shields.io/badge/Oracle_Ledger-AI%20Chain-00ffcc?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNjQiIGhlaWdodD0iNjQiIHZpZXdCb3g9IjAgMCA2NCA2NCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnL3N2ZyI+PHJlY3QgeD0iNiIgeT0iNiIgd2lkdGg9IjUyIiBoZWlnaHQ9IjUyIiByeD0iMTIiIHN0eWxlPSJmaWxsOm5vbmU7c3Ryb2tlOiMwMGZmY2M7c3Ryb2tlLXdpZHRoOjIiLz48cGF0aCBkPSJNMTYgMzIgMzIgMTYgNDggMzIiIHN0eWxlPSJmaWxsOm5vbmU7c3Ryb2tlOiNmZjAwODg7c3Ryb2tlLXdpZHRoOjIiLz48Y2lyY2xlIGN4PSIzMiIgY3k9IjMyIiByPSI0IiBmaWxsPSIjMDBmZmNjIi8+PC9zdmc+" alt="Oracle Ledger">
    </a>
    <a href="https://github.com/RyanMDewey/nexus-ide" target="_blank">
      <img src="https://img.shields.io/badge/NEXUS_IDE-AI_Editor-ff00cc?style=flat-square&logo=visualstudiocode&logoColor=white" alt="NEXUS IDE">
    </a>
  </div>
</section>

  <section>
  <h2>🧰 Full Technical Arsenal</h2>
  <div class="skills">
    <!-- Languages -->
    <img src="https://img.shields.io/badge/Rust-Fullstack-orange?style=flat-square&logo=rust&color=dea584" alt="Rust">
    <img src="https://img.shields.io/badge/C++-Performance-blue?style=flat-square&logo=c%2B%2B&color=00599C" alt="C++">
    <img src="https://img.shields.io/badge/Python-Scripting-yellow?style=flat-square&logo=python&color=FFD43B" alt="Python">
    <!-- Platforms & Infra -->
    <img src="https://img.shields.io/badge/Docker-Containers-blue?style=flat-square&logo=docker&color=2496ED" alt="Docker">
    <img src="https://img.shields.io/badge/GitHub%20Actions-CI/CD-2088ff?style=flat-square&logo=githubactions" alt="GitHub Actions">
    <!-- Security & Assembly -->
    <img src="https://img.shields.io/badge/Cybersecurity-Hardening-green?style=flat-square&logo=hackthebox&color=00ff99" alt="Cybersecurity">
    <img src="https://img.shields.io/badge/Neon-Assembly-critical?style=flat-square&logo=arm&color=cc0066" alt="Neon">
    <!-- Frontend/UI -->
    <img src="https://img.shields.io/badge/TailwindCSS-UI-blue?style=flat-square&logo=tailwindcss&color=38bdf8" alt="TailwindCSS">
    <!-- Backend -->
    <img src="https://img.shields.io/badge/FastAPI-Backend-green?style=flat-square&logo=fastapi&color=06b6d4" alt="FastAPI">
    <!-- Compilers & ML -->
    <img src="https://img.shields.io/badge/LLVM-Compiler-blueviolet?style=flat-square&logo=llvm&color=5a5aff" alt="LLVM">
    <img src="https://img.shields.io/badge/TensorFlow-ML-orange?style=flat-square&logo=tensorflow&color=FF6F00" alt="TensorFlow">
    <!-- Emerging Tech -->
    <img src="https://img.shields.io/badge/Quantum-Computing-purple?style=flat-square&logo=quarkus&color=7f00ff" alt="Quantum">
    <img src="https://img.shields.io/badge/Sentient_AI-Compiler-informational?style=flat-square&logo=openai&color=00ffcc" alt="Sentient AI">
    <img src="https://img.shields.io/badge/WebAssembly-WASM-critical?style=flat-square&logo=webassembly&color=654FF0" alt="WebAssembly">
    <img src="https://img.shields.io/badge/Blockchain-Infra-black?style=flat-square&logo=ethereum&color=3C3C3D" alt="Blockchain">
    <!-- Tools -->
    <img src="https://img.shields.io/badge/Vim-Editor-informational?style=flat-square&logo=vim&color=33cc33" alt="Vim">
    <img src="https://img.shields.io/badge/Tmux-Terminal-444444?style=flat-square&logo=gnometerminal" alt="Tmux">
  </div>
</section>

  <section>
    <h2>📊 Developer Metrics</h2>
    <div class="developer-metrics">
      <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=RyanMDewey&theme=tokyonight" alt="GitHub Summary">
      <img src="https://github-readme-stats.vercel.app/api?username=RyanMDewey&show_icons=true&theme=tokyonight" alt="GitHub Stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RyanMDewey&layout=compact&theme=tokyonight" alt="Top Languages">
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=RyanMDewey&theme=tokyo-night&hide_border=true&custom_title=My+Daily+Dev+Flow" alt="Commit Activity Graph">
    </div>
  </section>

  <section>
    <h2>🎖️ Dev Accolades</h2>
    <ul>
      <li>✨ Maintainer of AI-powered low-level compiler stack (ORC)</li>
      <li>🚀 Built autonomous blockchain infrastructure and IDE</li>
      <li>🧠 Created quantum-aware runtime environments for agent deployment</li>
      <li>📜 Recognized for advancing post-silicon programming language design</li>
    </ul>
  </section>

  

  

  <section>
  <h2>📬 Get in Touch</h2>
  <div class="tools" style="justify-content: center;">
    <a href="mailto:ryanmichaeldewey@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-ryanmichaeldewey@gmail.com-00ffcc?style=flat-square&logo=gmail&logoColor=white" alt="Email Me">
    </a>
    <a href="https://github.com/RyanMDewey" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-RyanMDewey-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub">
    </a>
    <a href="https://www.linkedin.com/in/ryan-dewey-b486a11ab/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Ryan%20Dewey-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
    <a href="https://ryanmdewey.github.io" target="_blank">
      <img src="https://img.shields.io/badge/Portfolio-RyanMDewey.github.io-00ffcc?style=flat-square&logo=internetexplorer&logoColor=white" alt="Portfolio">
    </a>
  </div>
  <div style="margin-top: 2rem; font-size: 0.85rem; text-align: center; color: #00ffcc;">
    ✨ This universe designed by Ryan Dewey © 2025<br>
    Powered by <strong>ORC</strong> • AI-Native Runtime • Hosted on <a href="https://pages.github.com/" target="_blank" style="color:#00ffcc">GitHub Pages</a>
  </div>
  <div id="local-time" style="margin-top: 1rem; font-size: 1rem; text-align: center; color: #00ffcc;">
  🕒 Your Local Time: <span id="clock"></span>
  </div>
</section>

<script>
  function updateClock() {
    const clockElement = document.getElementById('clock');
    const now = new Date();
    clockElement.textContent = now.toLocaleTimeString([], { hour: '2-digit', minute: '2-digit', second: '2-digit' });
  }
  setInterval(updateClock, 1000);
  updateClock();

  const canvas = document.getElementById('matrixCanvas');
  const ctx = canvas.getContext('2d');
  canvas.width = window.innerWidth;
  canvas.height = 300;

  const katakana = 'ｱｲｳｴｵｶｷｸｹｺｻｼｽｾｿﾀﾁﾂﾃﾄﾅﾆﾇﾈﾉﾊﾋﾌﾍﾎﾏﾐﾑﾒﾓﾔﾕﾖﾗﾘﾙﾚﾛﾜｦﾝ';
  const latin = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
  const digits = '0123456789';
  const characters = (katakana + latin + digits).split('');

  const fontSize = 16;
  const columns = canvas.width / fontSize;
  const drops = Array(Math.floor(columns)).fill(1);

  function draw() {
    ctx.fillStyle = 'rgba(0, 0, 0, 0.08)';
    ctx.fillRect(0, 0, canvas.width, canvas.height);

    ctx.fillStyle = '#00ff00';
    ctx.font = `${fontSize}px monospace`;

    for (let i = 0; i < drops.length; i++) {
      const text = characters[Math.floor(Math.random() * characters.length)];
      ctx.fillText(text, i * fontSize, drops[i] * fontSize);
      if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) drops[i] = 0;
      drops[i]++;
    }
  }

  setInterval(draw, 50);

  function toggleTheme() {
    document.body.classList.toggle('light-mode');
    localStorage.setItem('theme', document.body.classList.contains('light-mode') ? 'light' : 'dark');
  }

  window.addEventListener('DOMContentLoaded', () => {
    const savedTheme = localStorage.getItem('theme');
    if (savedTheme === 'light') document.body.classList.add('light-mode');
  });
</script>
