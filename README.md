# HappyStaffLandingPage
<html>
<head>
  <style>
 /* Base Styling */
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  color: #3a5a40;
  background-color: #dad7cd;
}

a {
  text-decoration: none;
  color: inherit;
}

/* Header */
.navbar {
  background-color: #344e41;
  color: #dad7cd;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
  position: sticky;
  top: 0;
  z-index: 1000;
}

.logo-wrapper {
display: flex;
align-items: center;
gap: 10px;
}

.logo-img {
height: 48px;
border-radius: 8px;
}

.header-graphic {
height: 42px;
width: auto;
object-fit: contain;
}

.logo img {
  height: 48px;
  border-radius: 8px;
  object-fit: contain;
}

.nav-links {
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  color: #dad7cd;
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #a3b18a;
}

.menu-icon {
  display: none;
  font-size: 1.5rem;
  color: #dad7cd;
}

/* Hero Section */
.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-between;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #dad7cd, #a3b18a);
}

.hero-text {
  flex: 1 1 400px;
  max-width: 600px;
}

.hero-text h1 {
  font-size: 3rem;
  color: #344e41;
  margin: 0;
}

.hero-text h2 {
  font-size: 2rem;
  color: #588157;
  margin: 0.5rem 0 1rem;
}

.hero-text p {
  font-size: 1.1rem;
  margin-bottom: 2rem;
}

.cta-button {
  background-color: #588157;
  color: white;
  padding: 0.8rem 1.5rem;
  border-radius: 5px;
  font-weight: 600;
  transition: background 0.3s ease;
}

.cta-button:hover {
  background-color: #3a5a40;
}

.hero-image {
  flex: 1 1 300px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 1rem;
}

.hero-image img {
  display: block;
  max-width: 100%;
  height: auto;
  border-radius: 20px;
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.2);
}

/* Responsive */
@media (max-width: 768px) {
  .nav-links {
    display: none;
  }

  .menu-icon {
    display: block;
  }

  .hero {
    flex-direction: column-reverse;
    text-align: center;
    padding: 3rem 1.5rem;
  }

  .hero-text h1 {
    font-size: 2.5rem;
  }

  .hero-text h2 {
    font-size: 1.5rem;
  }

  .hero-text p {
    font-size: 1rem;
  }
}

.problems-section {
background-color: #dad7cd;
padding: 4rem 2rem;
text-align: center;
}

.section-title {
font-size: 2rem;
color: #3a5a40;
margin-bottom: 2rem;
font-weight: 700;
}

.problem-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
gap: 2rem;
max-width: 1000px;
margin: 0 auto;
}

.problem-card {
background-color: #f2f2f2;
border: 2px solid #a3b18a;
border-radius: 12px;
padding: 2rem 1rem;
box-shadow: 0 4px 12px rgba(0,0,0,0.1);
color: #3a5a40;
display: flex;
flex-direction: column;
align-items: center;
transition: transform 0.3s ease;
}

.problem-card:hover {
transform: translateY(-5px);
}

.problem-icon {
font-size: 2rem;
color: #588157;
margin-bottom: 1rem;
}

.solution-intro {
background-color: #a3b18a;
color: #fff;
padding: 4rem 2rem;
text-align: center;
}

.solution-intro h2 {
font-size: 2.2rem;
font-weight: bold;
margin-bottom: 1rem;
}

.solution-intro .highlight {
color: #344e41;
}

.solution-intro .subtext {
font-size: 1.1rem;
max-width: 700px;
margin: 0 auto;
color: #fefefe;
}


.features-section {
background-color: #f2f2f2;
padding: 4rem 2rem;
text-align: center;
}

.features-section .section-title {
font-size: 2rem;
color: #3a5a40;
margin-bottom: 3rem;
font-weight: 700;
}

.features-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 2rem;
max-width: 1100px;
margin: 0 auto;
}

.feature-card {
background-color: #ffffff;
border-radius: 12px;
padding: 2rem;
box-shadow: 0 4px 12px rgba(0,0,0,0.05);
transition: transform 0.3s ease;
border-top: 5px solid #588157;
color: #3a5a40;
}

.feature-card:hover {
transform: translateY(-5px);
}

.feature-icon {
font-size: 2rem;
color: #588157;
margin-bottom: 1rem;
}

.feature-card h3 {
margin-bottom: 0.5rem;
font-size: 1.2rem;
font-weight: bold;
}

.feature-card p {
font-size: 0.95rem;
}





.features-section {
background-color: #f2f2f2;
padding: 4rem 2rem;
text-align: center;
}

.section-title {
font-size: 2.2rem;
color: #3a5a40;
margin-bottom: 3rem;
font-weight: 700;
}

.features-grid {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 2rem;
max-width: 1100px;
margin: 0 auto;
}

.feature-card {
background-color: #ffffff;
border-radius: 12px;
padding: 2rem;
box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
transition: transform 0.3s ease;
border-top: 5px solid #588157;
color: #3a5a40;
}

.feature-card:hover {
transform: translateY(-5px);
}

.feature-img {
width: 60px;
height: auto;
margin-bottom: 1rem;
}

.feature-card h3 {
font-size: 1.2rem;
margin-bottom: 0.5rem;
font-weight: bold;
}

.feature-card p {
font-size: 0.95rem;
}
 









/* App Preview Slider Section */
.app-preview-slider {
background-color: #fff;
padding: 4rem 2rem;
text-align: center;
position: relative;
}

.section-title {
font-size: 2.2rem;
color: #3a5a40;
margin-bottom: 2rem;
font-weight: 700;
}

.slider-container {
position: relative;
max-width: 700px;
margin: 0 auto;
}

.slide {
display: none;
}

.slider-img {
width: 100%;
height: auto;
border-radius: 16px;
box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
}

.fade {
animation: fadeEffect 0.6s ease-in-out;
}

@keyframes fadeEffect {
from {opacity: 0.4;}
to {opacity: 1;}
}

.nav-btn {
position: absolute;
top: 50%;
transform: translateY(-50%);
background-color: #588157;
color: #fff;
border: none;
padding: 12px 16px;
font-size: 1.5rem;
cursor: pointer;
border-radius: 50%;
z-index: 10;
}

.nav-btn:hover {
background-color: #3a5a40;
}

.prev {
left: 0;
}

.next {
right: 0;
}







/* Pricing Section Styling */
.pricing-section {
padding: 4rem 2rem;
background-color: #dad7cd;
text-align: center;
}

.section-title {
font-size: 2rem;
margin-bottom: 2rem;
color: #3a5a40;
}

.pricing-cards {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 2rem;
}

.pricing-card {
background-color: #fff;
border-radius: 16px;
padding: 2rem;
width: 300px;
box-shadow: 0 6px 12px rgba(0, 0, 0, 0.08);
transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.pricing-card:hover {
transform: scale(1.05);
box-shadow: 0 12px 20px rgba(0, 0, 0, 0.15);
}

.plan-title {
font-size: 1.2rem;
font-weight: bold;
color: #a3b18a;
margin-bottom: 0.5rem;
}

.plan-title.free {
color: #2d6a4f; /* green */
}

.price {
font-size: 2.5rem;
font-weight: bold;
color: #344e41;
margin: 0.5rem 0;
}

.price-desc {
font-size: 0.95rem;
color: #555;
margin-bottom: 1.2rem;
}

.btn-pricing {
background-color: #a3b18a;
color: white;
border: none;
padding: 0.75rem 1.2rem;
border-radius: 8px;
font-size: 1rem;
margin-bottom: 1rem;
cursor: pointer;
transition: background-color 0.3s ease;
}

.btn-pricing:hover {
background-color: #588157;
}

.features {
list-style: none;
padding: 0;
margin: 0;
text-align: left;
}

.features li {
padding: 0.4rem 0;
font-size: 0.95rem;
color: #333;
}



.founder-section {
background-color: #f6f6f6;
padding: 60px 20px;
text-align: center;
font-family: 'Segoe UI', sans-serif;
}

.founder-section h2 {
font-size: 2.5rem;
color: #3a5a40;
margin-bottom: 30px;
}

.founder-content {
display: flex;
flex-direction: column;
align-items: center;
gap: 30px;
max-width: 1000px;
margin: 0 auto;
}

.founder-img {
width: 220px;
height: 220px;
object-fit: cover;
border-radius: 50%;
box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
}

.founder-text p {
font-size: 1.1rem;
color: #333;
line-height: 1.7;
text-align: left;
max-width: 700px;
margin: 0 auto;
}

.founder-socials-wrapper {
margin-top: 30px;
}

.reach-text {
font-size: 1rem;
font-weight: 600;
color: #555;
margin-bottom: 10px;
  text-align: center; 
width: 100%; 
}

.founder-socials {
display: flex;
flex-wrap: wrap;
justify-content: center;
gap: 15px;
}

.social-btn {
display: inline-block;
padding: 10px 18px;
border-radius: 6px;
color: white;
text-decoration: none;
font-weight: 500;
transition: background 0.3s ease;
}

.social-btn.linkedin {
background-color: #0077b5;
}

.social-btn.instagram {
background-color: #e1306c;
}

.social-btn.youtube {
background-color: #ff0000;
}

.social-btn.gmail {
background-color: #d44638;
}

.social-btn:hover {
opacity: 0.85;
}






.reviews-section {
  background-color: #dad7cd; /* soft sage green */
  color: #3a5a40; /* dark green for text */
  padding: 60px 20px;
  font-family: 'Segoe UI', sans-serif;
}

.reviews-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  max-width: 1200px;
  margin: auto;
}

.reviews-left {
  flex: 1;
  min-width: 280px;
  padding: 20px;
}

.quote-icon {
  font-size: 80px;
  line-height: 1;
  color: #588157; /* medium green accent */
  margin-bottom: 10px;
}

.reviews-left h2 {
  font-size: 48px;
  margin: 0;
}

.star {
  color: gold;
  font-size: 2em;
  vertical-align: middle;
}

.review-subtitle {
  margin-top: 10px;
  font-size: 18px;
  color: #3a5a40;
  font-weight: 700;
}

.review-summary {
  font-size: 16px;
  margin-top: 20px;
}

.reviews-slider {
  display: flex;
  gap: 20px;
  flex: 2;
  flex-wrap: wrap;
  justify-content: flex-start;
  padding: 20px;
}

.review-card {
  background-color: #ffffff;
  color: #3a5a40;
  border-radius: 8px;
  padding: 20px;
  flex: 1 1 260px;
  max-width: 300px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.review-card:hover {
  transform: scale(1.05);
}

.review-card img {
  width: 60px;
  height: 60px;
  object-fit: cover;
  margin-bottom: 10px;
}

.review-text {
  font-size: 14px;
  margin-bottom: 15px;
}

.reviewer-name {
  font-weight: bold;
  font-size: 15px;
}

.review-date {
  font-style: italic;
  font-size: 13px;
  color: #6c757d;
  margin-bottom: 5px;
}

.review-helpful {
  font-size: 13px;
  color: #588157;
  margin-top: 10px;
}







/* Contact Section Styling */
.contact-section {
padding: 60px 20px;
background-color: #ffffff;
text-align: center;
color: #1a1a1a;
}

.contact-title {
font-size: 2.5rem;
font-weight: 700;
margin-bottom: 30px;
color: #14532d; /* deep green */
}

.contact-form {
max-width: 500px;
margin: 0 auto 40px;
display: flex;
flex-direction: column;
gap: 20px;
}

.contact-form input,
.contact-form textarea {
padding: 15px;
border: 1px solid #d1d5db;
border-radius: 8px;
font-size: 1rem;
}

.contact-form textarea {
resize: vertical;
min-height: 120px;
}

.send-btn {
background-color: #10b981; /* emerald green */
color: white;
padding: 15px;
font-size: 1rem;
font-weight: 600;
border: none;
border-radius: 8px;
cursor: pointer;
transition: background-color 0.3s ease;
}

.send-btn:hover {
background-color: #059669; /* darker green on hover */
}

/* App Download Section */
.download-app {
margin-top: 40px;
}

.download-app p {
font-size: 1.1rem;
margin-bottom: 16px;
color: #1a1a1a;
}

.app-buttons {
display: flex;
justify-content: center;
gap: 30px;
flex-wrap: wrap;
}

.store-badge {
height: 120px; /* doubled from ~60px */
width: auto;
transition: transform 0.2s ease;
}

.store-badge:hover {
transform: scale(1.05);
}



.footer {
background-color: #064e3b; /* dark green background */
color: #ffffff;
text-align: center;
padding: 20px 10px;
font-size: 1rem;
}

.footer a {
color: #34d399; /* medium-light green link */
text-decoration: underline;
transition: color 0.2s ease;
}

.footer a:hover {
color: #10b981; /* slightly darker green on hover */
}

.footer strong {
font-weight: 600;
} 
 </style>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Staff</title>
  <link rel="stylesheet" href="styles.css" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

  <!-- Header -->
  <header class="navbar"> <div class="logo-wrapper"> <img src="https://i.ibb.co/fzjfn1vH/happy.jpg" alt="Happy Staff Logo" class="logo-img" /> <img src="https://i.ibb.co/jPQQ59kT/1222-removebg-preview.png" alt="Team Illustration" class="header-graphic" /> </div> <nav class="nav-links"> <a href="#features">Features</a> <a href="#reviews">Reviews</a><a href="https://play.google.com/store/apps/details?id=com.anmolthedeveloper.happystaff.happy_staff&hl=en_IN&source=sh/x/srp/wr/m1/1&kgs=0e0d3fb0e51f083e" target="_blank" rel="noopener noreferrer"> Get Started </a>
 <a href="#pricing">Pricing</a> </nav> <div class="menu-icon"> <i class="fas fa-bars"></i> </div> </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-text">
      <h1>Smarter Task Management</h1>
      <h2>Happier Teams</h2>
      <p>Happy Staff empowers small businesses to delegate, monitor, and reward tasks—effortlessly, with AI.</p>
      <a href="https://play.google.com/store/apps/details?id=com.anmolthedeveloper.happystaff.happy_staff&hl=en_IN&source=sh/x/srp/wr/m1/1&kgs=0e0d3fb0e51f083e" target="_blank" rel="noopener noreferrer" class="cta-button">Try Happy Staff</a>
    </div>
    <div class="hero-image">
      <img src="https://i.ibb.co/Z6wM4wf8/1212.jpg" alt="Happy Staff App Preview">
    </div>
  </section>
  
  <!-- Problems Section -->
  <section id="problems" class="problems-section"> <h2 class="section-title">Challenges Faced by SMBs & MSMEs</h2> <div class="problem-grid"> <div class="problem-card"> <i class="fas fa-tasks problem-icon"></i> <p>Struggle with managing and tracking employee tasks</p> </div> <div class="problem-card"> <i class="fas fa-chart-line problem-icon"></i> <p>Lack insights into staff performance</p> </div> <div class="problem-card"> <i class="fas fa-user-shield problem-icon"></i> <p>Fail to retain accountability in operations</p> </div> <div class="problem-card"> <i class="fas fa-file-excel problem-icon"></i> <p>Use WhatsApp or spreadsheets with no automation or data visibility</p> </div> </div> </section>
  
  <!-- Solution Intro Section -->
  <section class="solution-intro"> <div class="container"> <h2>This is where <span class="highlight">HAPPY STAFF</span> comes in handy</h2> <p class="subtext"> We simplify team management with AI-powered tools that eliminate guesswork, bring visibility to operations, and keep your staff on track — all in one place. </p> </div> </section>
  
  <!-- Features Section -->
<section id="features" class="features-section"> <h2 class="section-title">Key Features That Make Work Effortless</h2> <div class="features-grid">
  <div class="feature-card">
  <img src="https://i.ibb.co/QFDzBgYh/task-management-removebg-preview.png" alt="task-management-removebg-preview" class="feature-img">
  <h3>AI-Powered Task Assignment</h3>
  <p>Delegate smarter with AI that understands team habits and optimizes assignments automatically.</p>
</div>

<div class="feature-card">
  <img src="https://i.ibb.co/dwrvB8sx/analytics-removebg-preview.png" alt="analytics feature icon" class="feature-img">
  <h3>Performance Analytics</h3>
  <p>Track team performance through real-time analytics that highlight productivity gaps and wins.</p>
</div>

<div class="feature-card">
  <img src="https://i.ibb.co/1tvc5xCs/coin-removebg-preview.png" alt="reward feature icon" class="feature-img">
  <h3>Productivity Rewards</h3>
  <p>Motivate staff with achievement-based rewards using goal tracking and incentive coins.</p>
</div>

<div class="feature-card">
  <img src="https://i.ibb.co/8gqpzVvv/whatsapp-icon-removebg-preview.png" alt="whatsapp feature icon" class="feature-img">
  <h3>WhatsApp Reminders</h3>
  <p>Keep your team aligned with real-time task alerts and progress updates directly on WhatsApp.</p>
</div>

<div class="feature-card">
  <img src="https://i.ibb.co/2YSfcQXG/ai-removebg-preview.png" alt="AI assistant icon" class="feature-img">
  <h3>AI Assistant</h3>
  <p>Ask the AI assistant anything—from task history to employee productivity reports—instantly.</p>
</div>

<div class="feature-card">
  <img src="https://i.ibb.co/V0SXhwmv/leaderboard-removebg-preview.png" alt="leaderboard-removebg-preview" class="feature-img">
  <h3>Live Leaderboards</h3>
  <p>Drive healthy competition and accountability with real-time ranking boards.</p>
</div>
</div> </section>
  
  <!-- App Preview Section -->
  <section id="app-preview" class="app-preview-slider"> <h2 class="section-title">App Preview</h2> <div class="slider-container"> <button class="nav-btn prev" onclick="changeSlide(-1)">&#10094;</button>
    <div class="slide fade">
  <img src="https://i.ibb.co/Z6mhr3b5/1abc.jpg" alt="1abc" class="slider-img" />
</div>

<div class="slide fade">
  <img src="https://i.ibb.co/Kch1xR4K/2abc.jpg" alt="2abc" class="slider-img" />
</div>

<div class="slide fade">
  <img src="https://i.ibb.co/BKzpyNc9/3abc.jpg" alt="3abc" class="slider-img" />
</div>

<div class="slide fade">
  <img src="https://i.ibb.co/TxDL3n0N/4abc.jpg" alt="4abc" class="slider-img" />
</div>

<button class="nav-btn next" onclick="changeSlide(1)">&#10095;</button>
</div> </section>
  
  
<script>let slideIndex = 0;
showSlide(slideIndex);

function changeSlide(n) {
slideIndex += n;
showSlide(slideIndex);
}

function showSlide(n) {
const slides = document.getElementsByClassName("slide");
if (n >= slides.length) slideIndex = 0;
if (n < 0) slideIndex = slides.length - 1;

for (let i = 0; i < slides.length; i++) {
slides[i].style.display = "none";
}
slides[slideIndex].style.display = "block";
}
</script>
  
  <section id="pricing" class="pricing-section"> <h2 class="section-title">Pricing</h2> <div class="pricing-cards">
    
    <!-- Free Plan -->
<div class="pricing-card">
  <h3 class="plan-title free">FREE</h3>
  <p class="price">₹0</p>
  <p class="price-desc">For first 2 employees</p>
  <button class="btn-pricing">Get Started</button>
  <ul class="features">
    <li>✅ No setup fees</li>
    <li>✅ AI task tracking</li>
    <li>✅ Employee check-ins</li>
    <li>✅ Dashboard & basic analytics</li>
    <li>✅ Add more employees at ₹350/employee</li>
  </ul>
</div>

<!-- WhatsApp API Plan -->
<div class="pricing-card highlighted">
  <h3 class="plan-title">WhatsApp API</h3>
  <p class="price">₹1</p>
  <p class="price-desc">per message</p>
  <button class="btn-pricing">Learn More</button>
  <ul class="features">
    <li>✅ Automated attendance alerts</li>
    <li>✅ Shift reminders & task prompts</li>
    <li>✅ Daily digests & manager summaries</li>
    <li>✅ Pay only for what you use</li>
  </ul>
</div>

<!-- Scalable Plan -->
<div class="pricing-card">
  <h3 class="plan-title">Scale Up</h3>
  <p class="price">Custom</p>
  <p class="price-desc">based on team size</p>
  <button class="btn-pricing">Contact Us</button>
  <ul class="features">
    <li>✅ Add unlimited employees</li>
    <li>✅ Team performance tracking</li>
    <li>✅ Advanced rewards & automation</li>
    <li>✅ Dedicated support</li>
  </ul>
</div>

    </div> </section>
  
  
  
 <section id="founder" class="founder-section"> <h2>About Our Founder</h2> <div class="founder-content"> <img src="https://i.ibb.co/P0y3nsL/Lakshit-Sethia.webp" alt="Lakshit Sethiya" class="founder-img" /> <div class="founder-text"> <p> Lakshit Sethiya is the visionary solo founder of Happy Staff—an entrepreneur, creator, marketer, and accomplished athlete. With a BA. LLB (Hons) from O.P. Jindal Global University and over a decade of hands-on experience in tech and marketing agency operations, Lakshit has trained over 25,000 digital entrepreneurs, built and led a team of 50+, and developed more than 10 SaaS products. He's a consultant to Shark Tank-backed brands, runs a government incubation center, commands a digital following of over 1 million, and has been a guest speaker at top institutions like IITs, IIMs, and NITs. His work has earned recognition from the Chief Minister and Ritesh Agarwal. </p> <div class="founder-socials-wrapper"> <p class="reach-text">CONTACT INFO :</p> <div class="founder-socials"> <a href="https://in.linkedin.com/in/lakshit-sethiya-5701a8179" target="_blank" class="social-btn linkedin">LinkedIn</a> <a href="https://www.instagram.com/socialseller_academy/?hl=en" target="_blank" class="social-btn instagram">Instagram</a> <a href="https://www.youtube.com/c/SocialSellerAcademy" target="_blank" class="social-btn youtube">YouTube</a> <a href="mailto:sethiyalakshit@gmail.com" class="social-btn gmail">Gmail</a> </div> </div> </div> </div> </section>
  
  
  
  <section id="reviews" class="reviews-section"> <div class="reviews-container"> <div class="reviews-left"> <div class="quote-icon">“</div> <h2>4.7 <span class="star">★</span></h2> <p class="review-subtitle">Average Rating from Our Users</p> <p class="review-summary"> Happy Staff helps simplify scheduling, track performance, and boost employee morale. Here’s what our users say: </p> </div> <div class="reviews-slider"> <div class="review-card"> <img src="https://i.ibb.co/YB6CxsF3/person-removebg-preview.png" alt="person" /> <p class="review-text"> We’ve been impressed with Happy Staff from day one. It simplifies scheduling, improves communication, and saves us time. Our team finds it easy to use and highly effective. </p> <p class="reviewer-name">Ashutosh Pal</p> <p class="review-date">May 9, 2025</p> <p class="review-helpful">Did you find this helpful?</p> </div> <div class="review-card"> <img src="https://i.ibb.co/YB6CxsF3/person-removebg-preview.png" alt="person" /> <p class="review-text"> “Happy Staff is a Game-Changer for Employee Efficiency!” I’ve recently started using Happy Staff, and I must say—it’s one of the best investments I’ve made for managing employee performance. The platform is clean, intuitive, and packed with powerful features that make tracking productivity effortless.💼 Since implementing it, our team has become more organized, motivated, and efficient. It’s saved us time, reduced manual effort, and improved overall transparency. Highly recommend Happy Staff. </p> <p class="reviewer-name">Avinash Prasad Shah</p> <p class="review-date">May 9, 2025</p> <p class="review-helpful">Did you find this helpful?</p> </div> <div class="review-card"> <img src="https://i.ibb.co/YB6CxsF3/person-removebg-preview.png" alt="person" /> <p class="review-text"> Simple and helpful to manage day to day task. </p> <p class="reviewer-name">Sunny Dewangan</p> <p class="review-date">May 9, 2025</p> <p class="review-helpful">Did you find this helpful?</p> </div> <div class="review-card"> <img src="https://i.ibb.co/YB6CxsF3/person-removebg-preview.png" alt="person" /> <p class="review-text"> It is an awesome app for management. </p> <p class="reviewer-name">Abhishek Dewangan</p> <p class="review-date">May 26, 2025</p> <p class="review-helpful">Did you find this helpful?</p> </div> </div> </div> </section>
  
  
  
  <section class="contact-section" id="contact"> <h2 class="contact-title">Contact Us</h2> <form class="contact-form"> <input type="text" placeholder="Your Name" required /> <input type="email" placeholder="Your Email" required /> <textarea placeholder="Your Message" required></textarea> <button type="submit" class="send-btn">Send Message</button> </form> <div class="download-app"> <p>Download the App using :</p> <div class="app-buttons"> <a href="https://play.google.com/store/apps/details?id=com.anmolthedeveloper.happystaff.happy_staff&hl=en_IN&source=sh/x/srp/wr/m1/1&kgs=0e0d3fb0e51f083e" target="_blank"> <img src="https://i.ibb.co/S4MwZt9K/giogp-removebg-preview.png" alt="giogp-removebg-preview" class="store-badge" /> </a> <a href="https://apps.apple.com/us/app/happy-staff/id6743959741" target="_blank"> <img src="https://i.ibb.co/ymGWdZ8S/app-store-removebg-preview.png" alt="app-store-removebg-preview" class="store-badge" /> </a> </div> </div> </section>
  
  
<footer class="footer"> <p>© 2025 <strong>Happy Staff</strong> | <a href="https://www.happystaff.in" target="_blank" rel="noopener noreferrer">www.happystaff.in</a> </p> </footer>

</body>
</html>
