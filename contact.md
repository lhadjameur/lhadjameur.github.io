---
layout: default
title: Contact
---

<section class="page-hero">
  <h1 class="page-title">Get In Touch</h1>
  <p class="page-subtitle">I'd love to hear from you — let's connect!</p>
</section>

<section class="section contact-grid">
  <div class="contact-info">
    <h2>Let's Talk</h2>
    <p>Whether you have a question, a project idea, or just want to say hello — my inbox is always open.</p>
    <div class="contact-methods">
      <div class="contact-method">
        <span class="contact-icon">💼</span>
        <div>
          <strong>GitHub</strong>
          <p><a href="https://github.com/lhadjameur" target="_blank">github.com/lhadjameur</a></p>
        </div>
      </div>
      <div class="contact-method">
        <span class="contact-icon">📍</span>
        <div>
          <strong>Location</strong>
          <p>Warsaw, Poland 🇵🇱</p>
        </div>
      </div>
    </div>
  </div>

  <div class="contact-form-wrapper">
    <h2>Send a Message</h2>
    <form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
      <div class="form-group">
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" placeholder="John Doe" required>
      </div>
      <div class="form-group">
        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" placeholder="john@example.com" required>
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5" placeholder="Your message here..." required></textarea>
      </div>
      <button type="submit" class="btn btn-primary" style="width:100%">Send Message 🚀</button>
    </form>
  </div>
</section>
