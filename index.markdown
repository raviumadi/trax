---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<!--What is Trax Fitness? -->
<div class="feature-box" style="margin-bottom: 40px; background-color: #FAFFF6;">
  <div style="text-align: center; padding: 50px;">
    <h2 style="margin-bottom: 20px;">What is Trax Fitness?</h2>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto;">
    Trax Fitness is an innovative fitness tracking system designed to revolutionize the way you monitor your workouts. At its core, it’s an AI-based platform built for fitness enthusiasts by fitness enthusiasts. Traxware AI, the team behind Trax Fitness, is dedicated to providing a reliable, automated, and smart way to track your routines, workouts, and overall fitness progress.
    </p>
  </div>
   <!-- Learn More Button -->
<div style="text-align: center; margin: 20px;">
  <a href="/Start-up" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Learn the Story
  </a>
</div>
</div>
 
<!-- Logo -->
<div class="image-container" style="margin-bottom: 40px;">
  <img src="/images/logo.png" alt="Trax Fitness Logo">
</div>

<!-- One line description -->
<div class="feature-box" style="margin-bottom: 40px; background-color: #F6F8FF">
<div style="text-align: center; padding: 50px;">
  <p style="margin-bottom: 40px; max-width: 800px; margin: auto;">
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

<!--What does it do? -->
<div class="feature-box" style="margin-bottom: 40px; background-color: #FFFFF6 ">
  <div style="text-align: center; padding: 50px;">
    <h2 style="margin-bottom: 20px;">What Does Trax Fitness Do?</h2>
    <h3 style="margin-bottom: 20px;">Accurate Tracking, Every Time:</h3>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
      Trax Fitness automates the process of tracking your workouts. It uses advanced sensors and AI algorithms to identify your exercises, measure your performance, and monitor your progress—all without the need for manual input. This means you can focus on your workout, while Trax Fitness takes care of the tracking.
    </p>
    <h3 style="margin-bottom: 20px;">Performance Evaluation & Routine Analytics:</h3>
     <p style="margin-bottom: 40px; max-width: 800px; margin: auto;">
      With real-time data collection and analysis, Trax Fitness evaluates your workout performance. Whether it’s reps, sets, or intensity, the platform provides you with an in-depth view of how you’re doing and how you’re improving over time. You get personalized insights and feedback on every session.
    </p>
  </div>
   <!-- Learn More Button -->
  <div style="text-align: center; margin: 20px;">
  <a href="/Technology" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Discover  the  Technology
  </a>
  </div>
</div>

<!--What Does it look like? -->
<div class="feature-box" style="margin-bottom: 40px; background-color: #FFFCF6">
  <div style="text-align: center; padding: 50px;">
    <h2 style="margin-bottom: 20px;">What Does It Look Like?</h2>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
    Imagine a sleek, lightweight wearable device that seamlessly integrates into your fitness routine. The Trax Fitness Tracker is designed to be non-intrusive and stylish while providing maximum functionality. It syncs effortlessly with the Trax app, where all your workout data is visualized in clean, easy-to-read dashboards.
  </p>
  <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
    The app’s user-friendly interface provides real-time tracking, activity logs, performance charts, and more. You can dive deep into your stats or just get a quick snapshot of your progress—all with a few taps.
  </p>
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

<div class="feature-box" style=" background-color: #FAFFF6;">
<div style="text-align: center; padding: 20px;">
  <h1 style="margin-bottom: 20px;">Why Choose Trax Fitness?</h1>
</div>

<!-- Why choose Trax Fitness? -->
<div class="features-grid">
  <div class="feature-box" style="background-color: #E0B8FE;">
    <h3>Automatic Workout Classification</h3>
    <p>Trax Fitness uses advanced AI algorithms to automatically recognize and classify your workouts in real-time. No need to manually log exercises – whatever machine, free weight routine, or cardio exercise you are engaged in, Trax identifies and records the activity seamlessly, ensuring accurate tracking of your routines.</p>
  </div>
  <div class="feature-box" style="background-color: #E0B8FE;">
    <h3>Performance Evaluation</h3>
    <p>Get in-depth analysis and feedback on your workout performance. Trax Fitness evaluates multiple parameters like strength, endurance, and consistency, offering personalized insights to help you understand your progress. With clear performance metrics, you can track improvements and identify areas for enhancement.</p>
  </div>
  <div class="feature-box" style="background-color: #E0B8FE;">
    <h3>Routine Tracking & Customization</h3>
    <p>Easily create and customize workout routines tailored to your fitness goals. Trax Fitness provides detailed tracking for every session, enabling you to monitor not only the type of workouts performed but also the duration, frequency, and intensity. Your routines are stored in a structured format, making it simple to adjust and optimize as you go.</p>
  </div>
  <div class="feature-box" style="background-color: #E0B8FE;">
    <h3>AI-Driven Insights & Recommendations</h3>
    <p>Our AI engine analyzes your workout history and progress to provide tailored recommendations for improving your fitness. Based on your past performance and current routine, Trax suggests optimized workouts, recovery periods, and goal-based plans to keep you motivated and on track to reach your fitness targets efficiently.</p>
  </div>
</div>
</div>

<!-- Discover the Latest Button -->
<div style="text-align: center; margin: 20px; margin-bottom: 40px;">
  <a href="/Blogs" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Discover the Latest
  </a>
</div>

<!--How to track my routine? -->
<div class="feature-box" style="margin-bottom: 40px; background-color: #FFFFF6;">
  <div style="text-align: center; padding: 50px;">
    <h2 style="margin-bottom: 20px;">How to Track My Rooutine?</h2>
    <h3 style="margin-bottom: 20px;">Step 1: Connect & Start Moving</h3>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
      Pair your Trax Fitness Tracker with the app through Bluetooth. Once connected, the tracker will automatically start logging data as soon as you begin your workout. Whether you’re lifting weights, running, or doing yoga, the app detects and records it all.
    </p>
    <h3 style="margin-bottom: 20px;">Step 2: Personalized Feedback & Insights</h3>
     <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
      The app intelligently categorizes your workouts, offering personalized feedback on your form, intensity, and progress. Each session is automatically labeled, and the AI behind Trax identifies areas of improvement and suggests ways to optimize your performance.
    </p>
     <h3 style="margin-bottom: 20px;">Step 3: Visualize & Optimize Your Progress</h3>
     <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
      You can view your workout history, see which muscles you’ve trained most, track improvements in strength or endurance, and plan future routines based on past performance. It’s like having a personal coach who knows you better than anyone—because all the data is based on your performance.
    </p>
  </div>
   <!-- Learn More Button -->
<div style="text-align: center; margin: 20px;">
  <a href="/Technology" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Learn More
  </a>
</div>
</div>

<!--What is Traxware AI -->
<div class="feature-box" style="margin-bottom: 40px; background-color: #CEFEFC">
  <div style="text-align: center; padding: 50px;">
    <h2 style="margin-bottom: 20px;">What is Traxware AI?</h2>
    <h3 style="margin-bottom: 20px;">The Team & Vision</h3>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;">
      Traxware AI is a startup powered by a group of passionate fitness enthusiasts and tech innovators who aim to solve the challenge of reliable and automatic fitness tracking. The vision is simple: to provide an intelligent way to monitor your workouts and fitness routines, so you can stay motivated and see tangible results in your progress over time.
    </p>
    <h3 style="margin-bottom: 20px;">Allied Products: Expanding the Traxware Ecosystem</h3>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;"> 
      <strong>Trax Posture:</strong> The technology allows you to set a target posture and calibrate yourself to achieve and maintain it. Whether you prefer to monitor your posture through a tabletop device, a widget on your computer, or even within a VR environment, Trax Posture provides a clear view of your alignment in relation to your ideal posture.
    </p>
    <p style="argin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;"> 
      <strong>Trax Stride:</strong>  Trax Stride is an AI-powered wearable device designed to constantly accompany and learn your walking gait and balance, helping to track potential dangers of losing balance. Built on custom-trained AI models, the technology is specifically designed to understand the unique movement and balance of each user, providing tailored insights and notifications to enhance safety and awareness.
    </p>
    <p style="fmargin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;"> 
	    <strong>Trax Myophone:</strong> Want to know how your muscles are growing and how active they are during different workouts? Trax Myophone is a unique wearable device designed to be worn on the target muscle during activities like lifting, isolated movements, or any exercise where muscle engagement is key. This innovative technology translates surface EMG (electromyography) signals into audible feedback through your regular earphones, allowing you to listen to your muscle activation in real-time.
    </p>
    <p style="margin-bottom: 40px; max-width: 800px; margin: auto; margin-bottom: 40px;"> 
      By using Traxware AI products, you have access to a whole suite of tools designed to help you track, improve, and achieve your fitness goals.
    </p>
  </div>
  <div style="text-align: center; margin: 20px;">
  <a href="/Start-up" style="display: inline-block; padding: 12px 24px; background-color: #4CAF50; color: white; text-decoration: none; font-size: 18px; border-radius: 8px; transition: background-color 0.3s ease;">
    Explore the Start-up
  </a>
</div>
</div>