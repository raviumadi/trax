---
layout: page
title: "Contact"
permalink: /Contact/
---

If you have any questions, feedback, or just want to say hello, please reach out to us through the form below. We would love to hear from you!

<form action="https://formsubmit.co/ravi@trax.fitness" method="POST" style="width: 100%; max-width: 600px; margin: auto;">
  <div style="margin-bottom: 10px;">
    <label for="name" style="display: block; margin-bottom: 5px;">Name:</label>
    <input type="text" id="name" name="name" required style="width: 100%; padding: 8px;"/>
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="email" style="display: block; margin-bottom: 5px;">Email:</label>
    <input type="email" id="email" name="email" required style="width: 100%; padding: 8px;"/>
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="message" style="display: block; margin-bottom: 5px;">Message:</label>
    <textarea id="message" name="message" rows="5" required style="width: 100%; padding: 8px;"></textarea>
  </div>
  
  <!-- Google reCAPTCHA -->
  <div class="g-recaptcha" data-sitekey="6LcV31EqAAAAAJNUKNpNG8rnufwfm5R5rhdGalxU"></div>

  <button type="submit" style="padding: 10px 15px; background-color: #4CAF50; color: white; border: none; cursor: pointer;">Send</button>
</form>

<!-- Include Google reCAPTCHA script -->
<script src="https://www.google.com/recaptcha/api.js" async defer></script>
