---
layout: page
title: "Quick Survey"
permalink: /Quick-Survey/
---

## Tell Us About Your Fitness Tracking Habits

We'd love to learn more about how you currently track your workouts and any insights or suggestions you might have for us! Please fill out the survey below.

<form id="survey-form" action="https://formsubmit.co/ravi@trax.fitness" method="POST" style="width: 100%; max-width: 600px; margin: auto;">
  
  <!-- Name Field -->
  <div style="margin-bottom: 10px;">
    <label for="name" style="display: block; margin-bottom: 5px;">Full Name (Optional):</label>
    <input type="text" id="name" name="name" style="width: 100%; padding: 8px;" />
  </div>
  
  <!-- Email Field -->
  <div style="margin-bottom: 10px;">
    <label for="email" style="display: block; margin-bottom: 5px;">Email (Optional):</label>
    <input type="email" id="email" name="email" style="width: 100%; padding: 8px;" />
  </div>
  
  <!-- Fitness Tracking Methods -->
  <div style="margin-bottom: 10px;">
    <label for="tracking_method" style="display: block; margin-bottom: 5px;">How do you currently track your workouts?</label>
    <select id="tracking_method" name="tracking_method" required style="width: 100%; padding: 8px;">
      <option value="" disabled selected>Select your method</option>
      <option value="App-based tracking">App-based tracking</option>
      <option value="Manual notebook/journal">Manual notebook/journal</option>
      <option value="Excel sheet or digital logs">Excel sheet or digital logs</option>
      <option value="No tracking; just by memory">No tracking; just by memory</option>
      <option value="Other">Other</option>
    </select>
  </div>
  
  <!-- Frequency of Tracking -->
  <div style="margin-bottom: 10px;">
    <label for="tracking_frequency" style="display: block; margin-bottom: 5px;">How often do you track your workouts?</label>
    <select id="tracking_frequency" name="tracking_frequency" required style="width: 100%; padding: 8px;">
      <option value="" disabled selected>Select frequency</option>
      <option value="Every workout">Every workout</option>
      <option value="Weekly">Weekly</option>
      <option value="Occasionally">Occasionally</option>
      <option value="Rarely">Rarely</option>
    </select>
  </div>
  
  <!-- Importance of Tracking -->
  <div style="margin-bottom: 10px;">
    <label for="tracking_importance" style="display: block; margin-bottom: 5px;">How important is tracking your workouts to you?</label>
    <select id="tracking_importance" name="tracking_importance" required style="width: 100%; padding: 8px;">
      <option value="" disabled selected>Select importance</option>
      <option value="Very important">Very important</option>
      <option value="Somewhat important">Somewhat important</option>
      <option value="Neutral">Neutral</option>
      <option value="Not very important">Not very important</option>
    </select>
  </div>
  
  <!-- Personal Comments Section -->
  <div style="margin-bottom: 10px;">
    <label for="comments" style="display: block; margin-bottom: 5px;">Any comments or suggestions? We'd love to hear your thoughts!</label>
    <textarea id="comments" name="comments" rows="5" style="width: 100%; padding: 8px;"></textarea>
  </div>

  <!-- Hidden reCAPTCHA token field -->
  <input type="hidden" name="recaptcha_response" id="recaptchaResponse">
  
  <!-- Next to thank you page-->
  <input type="hidden" name="_next" value="https://trax.fitness/Thanks">
  
  <button type="submit" style="padding: 10px 15px; background-color: #4CAF50; color: white; border: none; cursor: pointer;">Submit Survey</button>
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