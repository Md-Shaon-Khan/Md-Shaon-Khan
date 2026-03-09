<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Md. Shaon Khan | Portfolio</title>
  <!-- Devicon for programming language icons -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css" />
  <!-- Google Fonts (Inter) -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet" />
  <!-- Custom CSS (provided separately) -->
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- ========================
        NAVBAR
  ========================= -->
  <header class="portfolio-navbar">
    <div class="container navbar-container">
      <div class="portfolio-logo">
        <a href="#home">Md. Shaon Khan</a>
      </div>
      <nav class="portfolio-nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#learning">Learning</a>
        <a href="#stats">GitHub</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <!-- ========================
        HOME SECTION
  ========================= -->
  <section id="home" class="portfolio-home-section">
    <div class="container home-container">
      <div class="home-content">
        <h1>Md. Shaon Khan</h1>
        <p class="home-subtitle">
          3rd Year Undergraduate | Institute of Information Technology (IIT), Jahangirnagar University
        </p>
        <div class="home-buttons">
          <a href="#contact" class="btn-home-contact">Get in Touch</a>
          <a href="#" class="btn-home-resume" download>Download Resume</a>
        </div>
      </div>
      <div class="home-image">
        <!-- Replace with actual image -->
        <img src="shaon.jpg" alt="Shaon Khan" />
      </div>
    </div>
  </section>

  <!-- ========================
        ABOUT SECTION
  ========================= -->
  <section id="about" class="portfolio-about-section">
    <div class="container about-container">
      <div class="about-image">
        <img src="shaon2.jpg" alt="Shaon About" />
      </div>
      <div class="about-content">
        <h2>About Me</h2>
        <p>
          I am a highly motivated undergraduate student at the Institute of Information Technology (IIT), Jahangirnagar University. My academic focus lies in software architecture, scalable applications, and algorithmic problem-solving. Currently, I am strengthening my foundation in Data Structures and Algorithms, software development, and machine learning, while consistently refining my problem-solving abilities on platforms like Codeforces and LeetCode.
        </p>
        <p>
          I believe in learning from the core — a habit that once seemed challenging now empowers me to master complex topics and deliver robust solutions. I actively build real‑world projects, contribute to open source, and participate in hackathons to sharpen my skills.
        </p>
        <p>
          My goal is to combine technical knowledge with creative thinking to develop innovative AI applications and research that make a difference.
        </p>
      </div>
    </div>
  </section>

  <!-- ========================
        SKILLS SECTION (Languages, Libraries, Tools)
  ========================= -->
  <section id="skills" class="portfolio-skills-section">
    <div class="container skills-container">
      <h2>Technical Skills</h2>

      <!-- Languages -->
      <h3 class="skill-category">Languages I Use</h3>
      <div class="skill-icons">
        <i class="devicon-cplusplus-plain colored" title="C++"></i>
        <i class="devicon-c-plain colored" title="C"></i>
        <i class="devicon-java-plain colored" title="Java"></i>
        <i class="devicon-python-plain colored" title="Python"></i>
        <i class="devicon-html5-plain colored" title="HTML5"></i>
        <i class="devicon-css3-plain colored" title="CSS3"></i>
        <i class="devicon-javascript-plain colored" title="JavaScript"></i>
      </div>

      <!-- Libraries -->
      <h3 class="skill-category">Libraries I Use</h3>
      <div class="skill-icons">
        <i class="devicon-numpy-plain colored" title="NumPy"></i>
        <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="Scikit-learn" width="40" height="40" style="filter: brightness(0) invert(1);" title="Scikit-learn"/>
        <i class="devicon-pandas-plain colored" title="Pandas"></i>
        <i class="devicon-matplotlib-plain colored" title="Matplotlib"></i>
        <img src="https://raw.githubusercontent.com/scipy/scipy/main/doc/source/_static/logo.svg" alt="SciPy" width="40" height="40" style="filter: brightness(0) invert(1);" title="SciPy"/>
        <i class="devicon-tensorflow-original colored" title="TensorFlow"></i>
        <i class="devicon-keras-plain colored" title="Keras"></i>
        <i class="devicon-fastapi-plain colored" title="FastAPI"></i>
      </div>

      <!-- Tools / Environments -->
      <h3 class="skill-category">Tools & Environments</h3>
      <div class="skill-icons">
        <i class="devicon-jupyter-plain colored" title="Jupyter"></i>
        <i class="devicon-mysql-plain colored" title="MySQL"></i>
        <i class="devicon-bootstrap-plain colored" title="Bootstrap"></i>
        <i class="devicon-git-plain colored" title="Git"></i>
        <i class="devicon-github-original colored" title="GitHub"></i>
        <i class="devicon-vscode-plain colored" title="VS Code"></i>
      </div>
    </div>
  </section>

  <!-- ========================
        PROJECTS SECTION (Featured)
  ========================= -->
  <section id="projects" class="portfolio-projects-section">
    <div class="container projects-container">
      <h2>Featured Projects</h2>
      <div class="projects-grid">
        <!-- IoT Health Monitoring -->
        <div class="project-card">
          <img src="IoTBased.png" alt="IoT Health Monitoring" />
          <div class="project-info">
            <h3>IoT Health Monitoring & Disease Prediction</h3>
            <p>
              A system utilizing IoT sensors to collect real-time body data combined with user-reported symptoms. A Machine Learning model predicts possible diseases and provides drug/treatment suggestions.
            </p>
            <div class="project-tech">
              <span class="tech-tag">Python</span>
              <span class="tech-tag">ML/DL</span>
              <span class="tech-tag">IoT</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Md-Shaon-Khan/IoT-Health-Monitoring-and-Disease-Prediction-with-ML-Drug-Treatment-Recommendations" target="_blank" class="btn-project">GitHub</a>
            </div>
          </div>
        </div>

        <!-- UniFix 2.0 -->
        <div class="project-card">
          <img src="UniFix.png" alt="UniFix 2.0" />
          <div class="project-info">
            <h3>UniFix 2.0</h3>
            <p>
              An advanced, full-stack university complaint management system. Features real-time status tracking via Socket.io, role-based dashboards, and logic-based categorization algorithms for efficient administrative management.
            </p>
            <div class="project-tech">
              <span class="tech-tag">React</span>
              <span class="tech-tag">Node.js</span>
              <span class="tech-tag">MySQL</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Md-Shaon-Khan/UniFix-2.0" target="_blank" class="btn-project">GitHub</a>
            </div>
          </div>
        </div>

        <!-- LockGuard -->
        <div class="project-card">
          <img src="lockguard.jpg" alt="LockGuard" />
          <div class="project-info">
            <h3>LockGuard</h3>
            <p>
              A security-focused application providing advanced protection and monitoring features to safeguard personal and institutional digital assets.
            </p>
            <div class="project-tech">
              <span class="tech-tag">C++</span>
              <span class="tech-tag">Android</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Md-Shaon-Khan/LockGuard-Dual-Factor-Smart-Door-Security-with-Alerts" target="_blank" class="btn-project">GitHub</a>
            </div>
          </div>
        </div>

        <!-- IIT Academic Website -->
        <div class="project-card">
          <img src="iit_web.jpg" alt="IIT Academic Website" />
          <div class="project-info">
            <h3>IIT Academic Website</h3>
            <p>
              A comprehensive academic portal for IIT students providing access to research papers, project archives, past examination papers, academic calendars, and subject overviews.
            </p>
            <div class="project-tech">
              <span class="tech-tag">HTML/CSS</span>
              <span class="tech-tag">JS</span>
              <span class="tech-tag">PHP</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Md-Shaon-Khan/IIT-Academic-Website-Design" target="_blank" class="btn-project">GitHub</a>
            </div>
          </div>
        </div>

        <!-- Student Attendance System -->
        <div class="project-card">
          <img src="attendance.png" alt="Student Attendance System" />
          <div class="project-info">
            <h3>Student Attendance System</h3>
            <p>
              A digital solution designed to track and manage student attendance records efficiently.
            </p>
            <div class="project-tech">
              <span class="tech-tag">Java</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Md-Shaon-Khan/Student_Attendance_System" target="_blank" class="btn-project">GitHub</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================
        LEARNING GOALS SECTION
  ========================= -->
  <section id="learning" class="portfolio-learning-section">
    <div class="container learning-container">
      <h2>Learning Goals</h2>
      <ul class="learning-list">
        <li>Master advanced Data Structures and Algorithms for complex problem-solving and competitive programming.</li>
        <li>Explore and apply Machine Learning and Artificial Intelligence techniques through practical project implementation.</li>
        <li>Integrate academic knowledge with real-time project development experience.</li>
        <li>Contribute effectively to open-source software projects.</li>
        <li>Enhance coding efficiency and adhere to industry-standard best practices.</li>
      </ul>
    </div>
  </section>

  <!-- ========================
        GITHUB STATISTICS SECTION
  ========================= -->
  <section id="stats" class="portfolio-stats-section">
    <div class="container stats-container">
      <h2>GitHub Statistics</h2>
      <div class="github-stats">
        <a href="https://github.com/Md-Shaon-Khan" target="_blank">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Md-Shaon-Khan&layout=compact&theme=default" alt="Top Languages Used"/>
        </a>
      </div>
    </div>
  </section>

  <!-- ========================
        CONTACT SECTION (with social icons)
  ========================= -->
  <section id="contact" class="portfolio-contact-section">
    <div class="container contact-container">
      <h2>Connect with Me</h2>
      <p>Feel free to reach out for collaborations, projects, or just to say hello!</p>

      <div class="contact-cards">
        <div class="contact-card">
          <h3>Email</h3>
          <p><a href="mailto:shaon.iit52@gmail.com">shaon.iit52@gmail.com</a></p>
        </div>
        <div class="contact-card">
          <h3>LinkedIn</h3>
          <p><a href="https://www.linkedin.com/in/shaon-khan-01003433a/" target="_blank">linkedin.com/in/shaon-khan</a></p>
        </div>
        <div class="contact-card">
          <h3>GitHub</h3>
          <p><a href="https://github.com/Md-Shaon-Khan" target="_blank">github.com/Md-Shaon-Khan</a></p>
        </div>
        <div class="contact-card">
          <h3>Phone</h3>
          <p><a href="tel:+8801633040670">+880 1633 040670</a></p>
        </div>
      </div>

      <div class="social-icons">
        <a href="https://www.facebook.com/sa.ona.khana.803112" target="_blank">
          <img src="https://img.icons8.com/fluency/48/facebook-new.png" alt="Facebook" />
        </a>
        <a href="https://www.instagram.com/___shaon__/" target="_blank">
          <img src="https://img.icons8.com/fluency/48/instagram-new.png" alt="Instagram" />
        </a>
        <a href="https://www.linkedin.com/in/shaon-khan-01003433a/" target="_blank">
          <img src="https://img.icons8.com/fluency/48/linkedin.png" alt="LinkedIn" />
        </a>
        <a href="https://x.com/_shaon_khan" target="_blank">
          <img src="https://img.icons8.com/ios-filled/48/1DA1F2/twitterx--v2.png" alt="X (Twitter)" />
        </a>
        <a href="mailto:shaon.iit52@gmail.com" target="_blank">
          <img src="https://img.icons8.com/fluency/48/000000/email.png" alt="Email" />
        </a>
      </div>

      <form class="contact-form" action="#" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit" class="btn-contact">Send Message</button>
      </form>
    </div>
  </section>

  <!-- ========================
        FOOTER
  ========================= -->
  <footer class="portfolio-footer-section">
    <div class="container footer-container">
      <p>&copy; 2025 Md. Shaon Khan. All rights reserved.</p>
      <div class="footer-socials">
        <a href="https://github.com/Md-Shaon-Khan" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com/in/shaon-khan-01003433a/" target="_blank">LinkedIn</a>
        <a href="https://www.facebook.com/sa.ona.khana.803112" target="_blank">Facebook</a>
      </div>
    </div>
  </footer>

  <!-- JavaScript -->
  <script src="script.js"></script>
</body>
</html>
