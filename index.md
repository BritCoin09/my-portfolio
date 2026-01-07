---
layout: default
title: Britny Chambers
---
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <header class="site-header">
    <div class="container header-inner">
      <nav class="main-nav" aria-label="Main navigation">
        <ul>
          <li><a href="#hero">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

 <section id="hero" class="hero">
  <div class="hero-banner-wrapper">
    <img src="plasma_globe.jpg" alt="Plasma globe banner" class="hero-banner">
  </div>
</section>



  <main>
    <section id="about" class="about container">
      <h2>About Me</h2>
      <p>About Me  
I’m a data scientist with experience in exploratory data analysis, modeling, and communicating insights to stakeholders. I enjoy working end‑to‑end — from cleaning and structuring messy data to building models and delivering clear, actionable results.

My path into data science is unconventional but intentional. After years of factory work as a single mother, I wanted a career that offered growth, creativity, and the chance to solve meaningful problems. I’ve always loved working with computers, and when I discovered TripleTen’s Data Science program, everything clicked. I realized how much I enjoy working with numbers, words, and visualizations to help organizations make smarter decisions.

Today, I’m building projects that showcase my skills in Python, SQL, and data visualization, and I’m excited to contribute to teams that value clarity, collaboration, and impact.</p>
    </section>

   <section id="skills" class="skills container">
      <h2>Skills</h2>
      <p>Below are some data science skills and tools I use:</p>

  <div class="skills-grid">
        <div class="skill-card">
          <h3>Languages & Libraries</h3>
          <ul>
            <li>Python (Pandas, NumPy)</li>
            <li>R</li>
            <li>Scikit-learn</li>
            <li>TensorFlow &amp; PyTorch</li>
          </ul>
        </div>

   <div class="skill-card">
          <h3>Data Manipulation & Storage</h3>
          <ul>
            <li>SQL</li>
            <li>PostgreSQL / MySQL</li>
            <li>Big Data: Spark</li>
          </ul>
        </div>

  <div class="skill-card">
          <h3>Visualization</h3>
          <ul>
            <li>Matplotlib / Seaborn</li>
            <li>Plotly</li>
            <li>Tableau</li>
          </ul>
        </div>

  <div class="skill-card">
          <h3>Modeling & ML</h3>
          <ul>
            <li>Supervised &amp; Unsupervised Learning</li>
            <li>Deep Learning</li>
            <li>NLP</li>
            <li>Model evaluation &amp; feature engineering</li>
          </ul>
        </div>

   <div class="skill-card">
          <h3>Deployment & Tools</h3>
          <ul>
            <li>Docker</li>
            <li>Flask / FastAPI</li>
            <li>CI/CD basics</li>
          </ul>
        </div>

  <div class="skill-card">
          <h3>Statistics & Math</h3>
          <ul>
            <li>Probability &amp; Statistics</li>
            <li>Hypothesis testing</li>
            <li>Time series analysis</li>
          </ul>
        </div>
      </div>
    </section>
  </main>

  <footer id="contact" class="site-footer">
  <div class="container">
    <h2>Let’s Connect</h2>
    <p>📧 <strong>Email:</strong> <a href="mailto:britny.chambers@proton.me">britny.chambers@proton.me</a></p>
    <p>🧠 <strong>GitHub:</strong> <a href="https://github.com/BritCoin09" target="_blank" rel="noopener">BritCoin09</a></p>
    <p>💼 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/britny-chambers-562096327" target="_blank" rel="noopener">Britny Chambers</a></p>
    <p>📃 <strong>Resume:</strong> <a href="./Britny_Chambers_Resume.pdf" target="_blank" rel="noopener">Download Resume</a></p>
  </div>
</footer>

  <script>
    const sections = document.querySelectorAll("section");
    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add("visible");
        }
      });
    }, { threshold: 0.1 });

    sections.forEach(section => {
      observer.observe(section);
    });
  </script>
</body>
</html>
