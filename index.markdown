---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!-- Logo -->
<div class="image-container">
  <img src="/images/logo.png" alt="Trax Fitness Logo">
</div>

<div class="feature-box">
<div style="text-align: center; padding: 50px;">
  <!-- <h1 style="font-size: 36px; margin-bottom: 20px;">Trax</h1> -->
  <p style="font-size: 24px; margin-bottom: 40px; max-width: 800px; margin: auto;">
    The AI-powered wearable that tracks every rep, every set — ensuring smarter workouts, stronger gains, and unstoppable progress.
  </p>
 <!-- Learn More Button -->
<div style="text-align: center; margin: 20px;">
  <a href="/Technology" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Learn More
  </a>
</div>
</div>
</div>


<!-- Showcase -->
<div class="gallery-container" style="position: relative; max-width: 600px; margin: auto; overflow: hidden;">
  <!-- Arrow Left -->
  <a class="prev" onclick="plusSlides(-1)" style="cursor: pointer; position: absolute; top: 50%; left: 0; padding: 16px; background-color: rgba(0, 0, 0, 0.5); color: white; text-decoration: none; font-size: 18px; transform: translateY(-50%);">❮</a>

  <!-- Image Slides -->
  <div class="slides" style="display: flex; transition: transform 0.5s ease-in-out;">
    <img src="/images/model_top.png" alt="Photo 1" style="width: 100%; max-width: 600px;">
    <img src="/images/model_back.png" alt="Photo 2" style="width: 100%; max-width: 600px;">
    <img src="/images/model_side.png" alt="Photo 3" style="width: 100%; max-width: 600px;">
    <img src="/images/model_front.png" alt="Photo 4" style="width: 100%; max-width: 600px;">
  </div>

  <!-- Arrow Right -->
  <a class="next" onclick="plusSlides(1)" style="cursor: pointer; position: absolute; top: 50%; right: 0; padding: 16px; background-color: rgba(0, 0, 0, 0.5); color: white; text-decoration: none; font-size: 18px; transform: translateY(-50%);">❯</a>
</div>

<!-- JavaScript for Scrolling Functionality -->
<script>
  let slideIndex = 0;
  const slides = document.querySelector('.slides');
  const totalSlides = slides.children.length;

  function plusSlides(n) {
    slideIndex += n;

    // Wrap around if we go beyond the first or last slide
    if (slideIndex >= totalSlides) {
      slideIndex = 0;
    } else if (slideIndex < 0) {
      slideIndex = totalSlides - 1;
    }

    // Move slides to show the current image
    slides.style.transform = `translateX(-${slideIndex * 100}%)`;
  }
</script>

<div class="feature-box">
<div style="text-align: center; padding: 20px;">
  <h1 style="font-size: 36px; margin-bottom: 20px;">Feature Highlights</h1>
</div>
</div>
<!-- Features grid -->
<div class="features-grid">
  <div class="feature-box">
    <h3>Automatic Workout Classification</h3>
    <p>Trax Fitness uses advanced AI algorithms to automatically recognize and classify your workouts in real-time. No need to manually log exercises – whatever machine, free weight routine, or cardio exercise you are engaged in, Trax identifies and records the activity seamlessly, ensuring accurate tracking of your routines.</p>
  </div>
  <div class="feature-box">
    <h3>Performance Evaluation</h3>
    <p>Get in-depth analysis and feedback on your workout performance. Trax Fitness evaluates multiple parameters like strength, endurance, and consistency, offering personalized insights to help you understand your progress. With clear performance metrics, you can track improvements and identify areas for enhancement.</p>
  </div>
  <div class="feature-box">
    <h3>Routine Tracking & Customization</h3>
    <p>Easily create and customize workout routines tailored to your fitness goals. Trax Fitness provides detailed tracking for every session, enabling you to monitor not only the type of workouts performed but also the duration, frequency, and intensity. Your routines are stored in a structured format, making it simple to adjust and optimize as you go.</p>
  </div>
  <div class="feature-box">
    <h3>AI-Driven Insights & Recommendations</h3>
    <p>Our AI engine analyzes your workout history and progress to provide tailored recommendations for improving your fitness. Based on your past performance and current routine, Trax suggests optimized workouts, recovery periods, and goal-based plans to keep you motivated and on track to reach your fitness targets efficiently.</p>
  </div>
</div>







<!-- Discover the Latest Button -->
<div style="text-align: center; margin: 20px;">
  <a href="/Blogs" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Discover the Latest
  </a>
</div>
