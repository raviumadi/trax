---
layout: page
title: "Contact"
permalink: /Contact/
---

If you have any questions, feedback, or just want to say hello, please reach out to us through the form below. We would love to hear from you!

We would also appreciate if you shared with us a little about your workout tracking methods. [Take a Quick Survery](/Quick-Survey)

<form id="contact-form" action="https://formsubmit.co/ravi@trax.fitness" method="POST" style="width: 100%; max-width: 600px; margin: auto;">
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
  
  <!-- Next to thank you page-->
  <input type="hidden" name="_next" value="https://trax.fitness/Thanks">

  <!-- Hidden reCAPTCHA token field -->
  <input type="hidden" name="recaptcha_response" id="recaptchaResponse">

  <button type="submit" style="padding: 10px 15px; background-color: #4CAF50; color: white; border: none; cursor: pointer;">Send</button>
</form>

<!-- Google reCAPTCHA v3 Script -->
<script src="https://www.google.com/recaptcha/api.js?render=6LcV31EqAAAAAJNUKNpNG8rnufwfm5R5rhdGalxU"></script>

<script>
  grecaptcha.ready(function() {
    grecaptcha.execute('6LcV31EqAAAAAJNUKNpNG8rnufwfm5R5rhdGalxU', {action: 'submit'}).then(function(token) {
      // Add the token to the hidden input field
      document.getElementById('recaptchaResponse').value = token;
    });
  });
</script>
