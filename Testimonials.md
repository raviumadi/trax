---
layout: page
title: "Testimonials"
permalink: /Testimonials/
---

## Share Your Testimonial

We'd love to hear about your impression of the technoogy are building! Please share your insights with us!

We would also appreciate if you shared with us a little about your workout tracking methods. [Take a Quick Survery](/Quick-Survey)

<form id="testimonial-form" action="https://formsubmit.co/ravi@trax.fitness" method="POST" style="width: 100%; max-width: 600px; margin: auto;">
  
  <div style="margin-bottom: 10px;">
    <label for="name" style="display: block; margin-bottom: 5px;">Full Name:</label>
    <input type="text" id="name" name="name" required style="width: 100%; padding: 8px;" />
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="description" style="display: block; margin-bottom: 5px;">Organization/Personal Description:</label>
    <input type="text" id="description" name="description" required style="width: 100%; padding: 8px;" />
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="email" style="display: block; margin-bottom: 5px;">Email:</label>
    <input type="email" id="email" name="email" required style="width: 100%; padding: 8px;" />
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="testimonial" style="display: block; margin-bottom: 5px;">Your Testimonial:</label>
    <textarea id="testimonial" name="testimonial" rows="5" required style="width: 100%; padding: 8px;"></textarea>
  </div>

  <!-- Publish Permission Checkbox -->
  <div style="margin-bottom: 10px;">
    <input type="checkbox" id="publish_permission" name="publish_permission" required />
    <label for="publish_permission">I agree to have my testimonial published on the website.</label>
  </div>
  <!-- Next to thank you page-->
  <input type="hidden" name="_next" value="/Thanks">
  <!-- Hidden reCAPTCHA token field -->
  <input type="hidden" name="recaptcha_response" id="recaptchaResponse">

  <button type="submit" style="padding: 10px 15px; background-color: #4CAF50; color: white; border: none; cursor: pointer;">Submit</button>
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
