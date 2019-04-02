---
layout: page
title: Contact
permalink: /contact/
---

<form action="https://formspree.io/{{ site.email }}" method="POST" class="form">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" name="name" id="name" class="form-control" required>
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" name="_replyto" id="email" class="form-control" required>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea name="message" id="message" rows="6" class="form-control"></textarea>
  </div>
  <button type="submit" class="btn btn-outline-dark">Send Message</button>
</form>
