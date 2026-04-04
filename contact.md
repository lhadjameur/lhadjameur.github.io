---
layout: default
title: Contact
---

<style>
.pg-hero{text-align:center;padding:4rem 2rem 2rem;background:linear-gradient(135deg,#f8fafc,#dbeafe);border-bottom:1px solid #e2e8f0}
.pg-hero h1{font-size:3rem;font-weight:900;color:#1e293b;margin:0 0 .5rem}
.pg-hero p{color:#64748b;font-size:1.1rem;margin:0}
.contact-wrap{display:flex;flex-wrap:wrap;gap:3rem;max-width:1100px;margin:0 auto;padding:4rem 2rem}
.contact-left{flex:1;min-width:260px}
.contact-left h2{font-size:1.75rem;font-weight:800;color:#1e293b;margin:0 0 1rem}
.contact-left p{color:#64748b;line-height:1.7;margin-bottom:2rem}
.contact-item{display:flex;gap:1rem;align-items:flex-start;margin-bottom:1.5rem}
.contact-ico{font-size:1.75rem;flex-shrink:0}
.contact-item strong{display:block;color:#1e293b;margin-bottom:.2rem}
.contact-item p{margin:0;color:#64748b;font-size:.9rem}
.contact-item a{color:#2563eb;text-decoration:none;font-weight:600}
.contact-item a:hover{text-decoration:underline}
.contact-right{flex:1.5;min-width:280px}
.contact-right h2{font-size:1.75rem;font-weight:800;color:#1e293b;margin:0 0 1.5rem}
.form-group{display:flex;flex-direction:column;gap:.4rem;margin-bottom:1.25rem}
.form-group label{font-weight:700;font-size:.9rem;color:#1e293b}
.form-group input,.form-group textarea{border:1.5px solid #e2e8f0;border-radius:10px;padding:.8rem 1rem;font-size:1rem;font-family:inherit;color:#1e293b;background:#fff;transition:border-color .2s,box-shadow .2s;outline:none}
.form-group input:focus,.form-group textarea:focus{border-color:#2563eb;box-shadow:0 0 0 3px rgba(37,99,235,.15)}
.btn-submit{width:100%;background:#2563eb;color:#fff;border:none;padding:.9rem;border-radius:10px;font-size:1rem;font-weight:700;cursor:pointer;transition:all .2s}
.btn-submit:hover{background:#1d4ed8;transform:translateY(-2px);box-shadow:0 8px 20px rgba(37,99,235,.3)}
.form-note{margin-top:1rem;font-size:.8rem;color:#64748b;background:#f8fafc;border:1px solid #e2e8f0;border-radius:10px;padding:.75rem 1rem}
.form-note a{color:#2563eb}
</style>

<div class="pg-hero">
  <h1>Get In Touch</h1>
  <p>I'd love to hear from you — let's connect!</p>
</div>

<div class="contact-wrap">
  <div class="contact-left">
    <h2>Let's Talk 💬</h2>
    <p>Whether you have a question, want to collaborate on a project, or just want to say hello — feel free to reach out. I'll get back to you as soon as possible!</p>
    <div class="contact-item">
      <span class="contact-ico">💼</span>
      <div>
        <strong>GitHub</strong>
        <p><a href="https://github.com/lhadjameur" target="_blank">github.com/lhadjameur</a></p>
      </div>
    </div>
    <div class="contact-item">
      <span class="contact-ico">🌱</span>
      <div>
        <strong>AgriShare Project</strong>
        <p>Currently building my thesis platform — always open to feedback and ideas!</p>
      </div>
    </div>
    <div class="contact-item">
      <span class="contact-ico">📍</span>
      <div>
        <strong>Location</strong>
        <p>Warsaw, Poland 🇵🇱</p>
      </div>
    </div>
    <div class="contact-item">
      <span class="contact-ico">🎓</span>
      <div>
        <strong>University</strong>
        <p>Vistula University (AFiBV)</p>
      </div>
    </div>
  </div>

  <div class="contact-right">
    <h2>Send a Message ✉️</h2>
    <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
      <div class="form-group">
        <label>Your Name</label>
        <input type="text" name="name" placeholder="John Doe" required>
      </div>
      <div class="form-group">
        <label>Your Email</label>
        <input type="email" name="email" placeholder="john@example.com" required>
      </div>
      <div class="form-group">
        <label>Subject</label>
        <input type="text" name="subject" placeholder="What's this about?">
      </div>
      <div class="form-group">
        <label>Message</label>
        <textarea name="message" rows="5" placeholder="Your message here..." required></textarea>
      </div>
      <button type="submit" class="btn-submit">Send Message 🚀</button>
    </form>
    <p class="form-note">💡 To make the form work, sign up free at <a href="https://formspree.io" target="_blank">formspree.io</a> and replace <strong>YOUR_FORM_ID</strong> with your actual ID.</p>
  </div>
</div>
