---
layout: page
title: "Testimonials"
permalink: /Testimonials/
---

## Share Your Testimonial

We'd love to hear about your impression of the technoogy are building! Please share your insights with us!

<form action="https://formsubmit.co/ravi@trax.fitness" method="POST" style="width: 100%; max-width: 600px; margin: auto;">
  
  <div style="margin-bottom: 10px;">
    <label for="name" style="display: block; margin-bottom: 5px;">Full Name:</label>
    <input type="text" id="name" name="name" required style="width: 100%; padding: 8px;" required/>
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="description" style="display: block; margin-bottom: 5px;">Organization/Personal Description:</label>
    <input type="text" id="description" name="description" required style="width: 100%; padding: 8px;" required/>
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="email" style="display: block; margin-bottom: 5px;">Email:</label>
    <input type="email" id="email" name="email" required style="width: 100%; padding: 8px;"/>
  </div>
  
  <div style="margin-bottom: 10px;">
    <label for="testimonial" style="display: block; margin-bottom: 5px;">Your Testimonial:</label>
    <textarea id="testimonial" name="testimonial" rows="5" required style="width: 100%; padding: 8px;" required></textarea>
  </div>
  
  <!-- Publish Permission Checkbox -->
  <div style="margin-bottom: 10px;">
    <input type="checkbox" id="publish_permission" name="publish_permission" required />
    <label for="publish_permission">I agree to have my testimonial published on the website.</label>
  </div>
  
  <!-- Google reCAPTCHA -->
  <div class="g-recaptcha" data-sitekey="6LcV31EqAAAAAJNUKNpNG8rnufwfm5R5rhdGalxU"></div>

  <button type="submit" style="padding: 10px 15px; background-color: #4CAF50; color: white; border: none; cursor: pointer;">Submit</button>
</form>

<!-- Include Google reCAPTCHA script -->
<script src="https://www.google.com/recaptcha/api.js" async defer></script>
