---
title: "Chat"
permalink: /chat/
layout: single
author_profile: true
---

Have a question or note for Ali? Send a message below.

<form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
  <div class="form-group">
    <label for="name">Your name</label>
    <input type="text" id="name" name="name" required>
  </div>

  <div class="form-group">
    <label for="email">Your email</label>
    <input type="email" id="email" name="_replyto" required>
  </div>

  <div class="form-group">
    <label for="message">Your message</label>
    <textarea id="message" name="message" rows="6" required></textarea>
  </div>

  <!-- Optional: honeypot to reduce spam -->
  <input type="text" name="_gotcha" style="display:none">

  <button type="submit">Send</button>
</form>

_You can also email Ali directly at_ [you@example.com](mailto:you@example.com).
