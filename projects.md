---
layout: default
title: Projects
---

<style>
.pg-hero{text-align:center;padding:4rem 2rem 2rem;background:linear-gradient(135deg,#f8fafc,#dbeafe);border-bottom:1px solid #e2e8f0}
.pg-hero h1{font-size:3rem;font-weight:900;color:#1e293b;margin:0 0 .5rem}
.pg-hero p{color:#64748b;font-size:1.1rem;margin:0}
.proj-wrap{max-width:1100px;margin:0 auto;padding:4rem 2rem}
.proj-wrap h2{font-size:1.75rem;font-weight:800;color:#1e293b;margin-bottom:2rem}
.proj-grid{display:flex;flex-wrap:wrap;gap:1.5rem}
.proj-card{flex:1;min-width:280px;background:#fff;border:1px solid #e2e8f0;border-radius:16px;padding:2rem;box-shadow:0 4px 20px rgba(0,0,0,.06);transition:all .2s;position:relative}
.proj-card:hover{transform:translateY(-5px);box-shadow:0 16px 40px rgba(0,0,0,.12)}
.proj-card.featured{border:2px solid #2563eb}
.proj-card.thesis{border:2px solid #7c3aed;background:linear-gradient(135deg,#faf5ff,#ede9fe)}
.badge{display:inline-block;font-size:.7rem;font-weight:700;text-transform:uppercase;letter-spacing:.1em;padding:.25rem .7rem;border-radius:100px;margin-bottom:1rem}
.badge-live{background:#dcfce7;color:#16a34a}
.badge-thesis{background:#ede9fe;color:#7c3aed}
.badge-soon{background:#f1f5f9;color:#64748b}
.proj-ico{font-size:2.2rem;margin-bottom:.75rem}
.proj-card h3{font-size:1.15rem;font-weight:800;color:#1e293b;margin:0 0 .75rem}
.proj-card p{color:#64748b;font-size:.92rem;line-height:1.6;margin:0 0 1.25rem}
.tags{display:flex;flex-wrap:wrap;gap:.4rem;margin-bottom:1.25rem}
.tag{background:#dbeafe;color:#1d4ed8;font-size:.72rem;font-weight:700;padding:.2rem .6rem;border-radius:100px}
.tag-purple{background:#ede9fe;color:#7c3aed}
.proj-links{display:flex;gap:.75rem;flex-wrap:wrap}
.btn-blue{display:inline-block;background:#2563eb;color:#fff!important;padding:.55rem 1.2rem;border-radius:8px;font-weight:700;font-size:.875rem;text-decoration:none!important;transition:all .2s}
.btn-blue:hover{background:#1d4ed8;transform:translateY(-2px)}
.btn-out{display:inline-block;border:2px solid #2563eb;color:#2563eb!important;padding:.55rem 1.2rem;border-radius:8px;font-weight:700;font-size:.875rem;text-decoration:none!important;transition:all .2s}
.btn-out:hover{background:#dbeafe;transform:translateY(-2px)}
.cta-box{background:linear-gradient(135deg,#2563eb,#1d4ed8);border-radius:16px;padding:4rem 2rem;text-align:center;max-width:1100px;margin:0 auto 4rem}
.cta-box h2{color:#fff;font-size:2rem;margin:0 0 .75rem}
.cta-box p{color:rgba(255,255,255,.85);margin-bottom:2rem;font-size:1.05rem}
.btn-white{display:inline-block;background:#fff;color:#2563eb!important;padding:.85rem 2rem;border-radius:8px;font-weight:800;text-decoration:none!important;transition:all .2s}
.btn-white:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(0,0,0,.2)}
</style>

<div class="pg-hero">
  <h1>My Projects</h1>
  <p>Things I've built and am currently working on</p>
</div>

<div class="proj-wrap">
  <h2>🚀 Featured Projects</h2>
  <div class="proj-grid">

    <div class="proj-card thesis">
      <span class="badge badge-thesis">🎓 Thesis Project</span>
      <div class="proj-ico">🌱</div>
      <h3>AgriShare — Smart Farming Platform</h3>
      <p>My main thesis project at Vistula University. AgriShare is a web-based platform designed to connect farmers, enabling them to share agricultural resources, equipment, and knowledge. The goal is to make farming smarter, more collaborative, and more efficient using modern web technologies.</p>
      <p><strong>Currently in active development.</strong> Building the frontend interface, user authentication, and resource-sharing features.</p>
      <div class="tags">
        <span class="tag tag-purple">Thesis Project</span>
        <span class="tag tag-purple">Web Platform</span>
        <span class="tag tag-purple">HTML/CSS</span>
        <span class="tag tag-purple">JavaScript</span>
        <span class="tag tag-purple">In Development</span>
      </div>
      <div class="proj-links">
        <a href="https://lhadjameur.github.io" class="btn-blue" target="_blank">🔗 Preview</a>
      </div>
    </div>

    <div class="proj-card featured">
      <span class="badge badge-live">✅ Live</span>
      <div class="proj-ico">🌐</div>
      <h3>Personal Portfolio Website</h3>
      <p>This website! A multi-page static portfolio built with Jekyll and hosted on GitHub Pages. Features a responsive layout, custom CSS styling, and 5 fully designed pages.</p>
      <div class="tags">
        <span class="tag">Jekyll</span>
        <span class="tag">GitHub Pages</span>
        <span class="tag">CSS</span>
        <span class="tag">Markdown</span>
      </div>
      <div class="proj-links">
        <a href="https://lhadjameur.github.io" class="btn-blue" target="_blank">🔗 Live Site</a>
        <a href="https://github.com/lhadjameur/lhadjameur.github.io" class="btn-out" target="_blank">📁 Source Code</a>
      </div>
    </div>

    <div class="proj-card">
      <span class="badge badge-soon">Coming Soon</span>
      <div class="proj-ico">💡</div>
      <h3>Next Project</h3>
      <p>More projects coming as I continue learning JavaScript and expanding my web development skills throughout my studies.</p>
      <div class="tags">
        <span class="tag">JavaScript</span>
        <span class="tag">HTML/CSS</span>
      </div>
    </div>

  </div>
</div>

<div class="cta-box">
  <h2>Interested in collaborating?</h2>
  <p>Always open to new ideas, feedback, or working together on something great.</p>
  <a href="/contact.html" class="btn-white">Contact Me 👋</a>
</div>
