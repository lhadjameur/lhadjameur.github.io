---
layout: default
title: Home
---

<style>
.hero{display:flex;flex-wrap:wrap;gap:2rem;align-items:center;justify-content:space-between;padding:4rem 2rem;max-width:1100px;margin:0 auto}
.hero-left{flex:1;min-width:280px}
.hero-tag{display:inline-block;background:#dbeafe;color:#2563eb;font-size:.75rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;padding:.3rem .9rem;border-radius:100px;margin-bottom:1rem}
.hero-name{font-size:3.5rem;font-weight:900;line-height:1.1;color:#1e293b;margin:0 0 .75rem;letter-spacing:-1px}
.hero-name span{color:#2563eb}
.hero-sub{color:#64748b;font-size:1.05rem;margin-bottom:2rem}
.hero-btns{display:flex;gap:1rem;flex-wrap:wrap}
.btn-blue{display:inline-block;background:#2563eb;color:#fff!important;padding:.8rem 1.8rem;border-radius:8px;font-weight:700;text-decoration:none!important;transition:all .2s}
.btn-blue:hover{background:#1d4ed8;transform:translateY(-2px);box-shadow:0 8px 20px rgba(37,99,235,.3)}
.btn-out{display:inline-block;border:2px solid #2563eb;color:#2563eb!important;padding:.8rem 1.8rem;border-radius:8px;font-weight:700;text-decoration:none!important;transition:all .2s}
.btn-out:hover{background:#dbeafe;transform:translateY(-2px)}
.hero-right{flex:1;min-width:280px}
.code-box{background:#0f172a;border-radius:14px;padding:1.5rem;box-shadow:0 20px 50px rgba(0,0,0,.2)}
.dots{display:flex;gap:6px;margin-bottom:1rem}
.dots span{width:12px;height:12px;border-radius:50%}
.dots span:nth-child(1){background:#ef4444}
.dots span:nth-child(2){background:#f59e0b}
.dots span:nth-child(3){background:#22c55e}
.code-box pre{margin:0;background:transparent!important;border:none!important;padding:0!important}
.code-box code{color:#93c5fd!important;font-size:.875rem;font-family:'Courier New',monospace;line-height:1.7;background:transparent!important}
.cards-row{display:flex;flex-wrap:wrap;gap:1.5rem;max-width:1100px;margin:0 auto;padding:3rem 2rem}
.card{flex:1;min-width:220px;background:#fff;border:1px solid #e2e8f0;border-radius:14px;padding:2rem;box-shadow:0 4px 20px rgba(0,0,0,.06);transition:all .2s}
.card:hover{transform:translateY(-5px);box-shadow:0 16px 40px rgba(0,0,0,.12)}
.card-ico{font-size:2rem;margin-bottom:.75rem}
.card h3{margin:0 0 .5rem;color:#1e293b;font-size:1.05rem}
.card p{margin:0;color:#64748b;font-size:.9rem;line-height:1.6}
.cta-box{background:linear-gradient(135deg,#2563eb,#1d4ed8);border-radius:16px;padding:4rem 2rem;text-align:center;max-width:1100px;margin:0 auto 4rem;padding-left:2rem;padding-right:2rem}
.cta-box h2{color:#fff;font-size:2rem;margin:0 0 .75rem}
.cta-box p{color:rgba(255,255,255,.85);margin-bottom:2rem;font-size:1.05rem}
.btn-white{display:inline-block;background:#fff;color:#2563eb!important;padding:.85rem 2rem;border-radius:8px;font-weight:800;text-decoration:none!important;transition:all .2s}
.btn-white:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(0,0,0,.2)}
</style>

<div class="hero">
  <div class="hero-left">
    <span class="hero-tag">Welcome to my portfolio</span>
    <h1 class="hero-name">Lhadj<br><span>Mhandou Ameur</span></h1>
    <p class="hero-sub">Web Developer · Student · Tech Enthusiast<br>Warsaw, Poland 🇵🇱</p>
    <div class="hero-btns">
      <a href="/projects.html" class="btn-blue">View My Work →</a>
      <a href="/about.html" class="btn-out">About Me</a>
    </div>
  </div>
  <div class="hero-right">
    <div class="code-box">
      <div class="dots"><span></span><span></span><span></span></div>
      <pre><code>const developer = {
  name: "Lhadj Ameur",
  uni: "Vistula AFiBV",
  skills: ["HTML","CSS",
           "Jekyll","Git"],
  status: "Building & Learning 🚀",
  goal: "Full-Stack Developer"
};</code></pre>
    </div>
  </div>
</div>

<div class="cards-row">
  <div class="card">
    <div class="card-ico">🌐</div>
    <h3>Web Development</h3>
    <p>Building modern, responsive websites with HTML, CSS and JavaScript.</p>
  </div>
  <div class="card">
    <div class="card-ico">🛠</div>
    <h3>Tools & Workflow</h3>
    <p>Git, GitHub, Jekyll — shipping projects with a clean, efficient workflow.</p>
  </div>
  <div class="card">
    <div class="card-ico">📚</div>
    <h3>Always Learning</h3>
    <p>Constantly exploring new technologies and improving my skills every day.</p>
  </div>
</div>

<div class="cta-box">
  <h2>Let's Work Together</h2>
  <p>Open to new opportunities, collaborations and interesting projects.</p>
  <a href="/contact.html" class="btn-white">Get In Touch 👋</a>
</div>
