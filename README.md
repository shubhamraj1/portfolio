
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Shubham Raj | Machine Learning Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-color: #1e1e2f;
      --card-color: rgba(255, 255, 255, 0.05);
      --glass-border: rgba(255, 255, 255, 0.2);
      --text-color: #eaeaea;
      --accent: #7f5af0;
      --link-hover: #ffd60a;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      padding-bottom: 80px;
      scroll-behavior: smooth;
    }

    a {
      color: var(--accent);
      text-decoration: none;
      transition: color 0.3s ease;
    }
    a:hover {
      color: var(--link-hover);
    }

    header {
      text-align: center;
      padding: 50px 20px;
      background: linear-gradient(to bottom, #2d2d44, transparent);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      margin: 5px 0;
      font-size: 1rem;
    }

    #tagline {
      font-size: 1.2rem;
      font-style: italic;
      color: var(--accent);
      margin-top: 10px;
      animation: fadeIn 2s ease forwards;
    }

    main {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    section {
      margin-bottom: 60px;
      background: var(--card-color);
      padding: 25px;
      border-radius: 20px;
      border: 1px solid var(--glass-border);
      box-shadow: 0 8px 32px rgba(2, 2, 64, 0.2);
      backdrop-filter: blur(10px);
      transition: transform 0.3s ease;
      opacity: 0;
      transform: translateY(40px);
      animation: fadeIn 1s ease forwards;
    }

    section:hover {
      transform: translateY(-5px);
    }

    h2, h3 {
      color: #ffffff;
      border-bottom: 1px solid var(--accent);
      padding-bottom: 5px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    ul li {
      margin-bottom: 10px;
    }

    .skill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 10px;
    }

    .skill-row span {
      display: flex;
      align-items: center;
      gap: 5px;
      background: rgba(255,255,255,0.08);
      padding: 5px 10px;
      border-radius: 10px;
    }

    .project {
      background: rgba(255,255,255,0.03);
      padding: 15px;
      border-radius: 15px;
      border: 1px solid rgba(255,255,255,0.1);
      margin-bottom: 25px;
      transition: all 0.3s ease;
    }

    .project:hover {
      background: rgba(127, 90, 240, 0.1);
      transform: translateY(-4px);
      box-shadow: 0 4px 20px rgba(127, 90, 240, 0.3);
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #2b2b3d;
      color: #aaa;
      position: fixed;
      bottom: 0;
      width: 100%;
    }

    #scrollTopBtn {
      background: var(--accent);
      color: #fff;
      border: none;
      padding: 10px 14px;
      font-size: 1rem;
      border-radius: 50px;
      cursor: pointer;
      position: fixed;
      right: 20px;
      bottom: 90px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
      display: none;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }
      section {
        padding: 15px;
      }
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Shubham Raj</h1>
    <p>Machine Learning | Creative Thinker</p>
    <p id="tagline">Transforming Ideas Into Intelligent Systems</p>
    <p>📧 <a href="mailto:srshubhammuz1@gmail.com">srshubhammuz1@gmail.com</a> | 🌐 <a href="https://github.com/shubhamraj1">Portfolio</a></p>
    <p>
      <a href="https://www.linkedin.com/in/shubham-raj-b823a8252/" target="_blank">LinkedIn</a> |
      <a href="https://github.com/shubhamraj1" target="_blank">GitHub</a>
    </p>
    <p>📱 +91 7677142057</p>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <p>Hi, I'm Shubham Raj, a 3rd-year B.Tech CSE student at Lovely Professional University, with a minor in Machine Learning and Artificial Intelligence. I'm passionate about emerging tech and using AI to solve real-world challenges. I'm driven by curiosity and always eager to learn and build through hands-on projects and collaborations.</p>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li><strong>Languages:</strong>
          <div class="skill-row">
            <span>C <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" width="20"/></span>
            <span>C++ <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" width="20"/></span>
            <span>Python <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="20"/></span>
            <span>Java <img src="https://upload.wikimedia.org/wikipedia/en/3/30/Java_programming_language_logo.svg" width="20"/></span>
          </div>
        </li>
        <li><strong>Web:</strong>
          <div class="skill-row">
            <span>HTML <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" width="20"/></span>
            <span>CSS <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" width="20"/></span>
            <span>JavaScript <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" width="20"/></span>
          </div>
        </li>
        <li><strong>Tools:</strong>
          <div class="skill-row">
            <span>Blender <img src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Blender_logo_no_text.svg" width="20"/></span>
            <span>Unity <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Unity_Technologies_logo.svg" width="60"/></span>
          </div>
        </li>
        <li><strong>Soft Skills:</strong> Quick learner, Communication Skill, Confidence</li>
      </ul>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="project">
        <h3>Python Number Guessing Game – Dec 2023</h3>
        <p><b>Tech:</b> Python</p>
        <p>Built a simple CLI number guessing game to strengthen programming fundamentals and logic building.</p>
      </div>
      <div class="project">
        <h3>Real-Time Human Activity Detection – Apr 2025</h3>
        <p><b>Role:</b> Developer, Researcher</p>
        <p><b>Tech:</b> Python, OpenCV, YOLOv5, TensorFlow</p>
        <p>Designed a safety monitoring system for construction sites using live object detection and deep learning models.</p>
      </div>
      <div class="project">
        <h3>IPL Scheduler (C)</h3>
        <p>Created a console-based IPL match scheduler and tracker using C and file handling.</p>
      </div>
    </section>

    <section id="live-projects">
      <h2>Live Projects</h2>
      <ul>
        <li><strong>Ecommerce Organic Food:</strong> <a href="https://shashankrazz.github.io/Ecommerce-organic/" target="_blank">Visit</a></li>
        <li><strong>ClothsBazzar.com:</strong> <a href="https://shashankrazz.github.io/Clothsbazzar.com/" target="_blank">Visit</a></li>
      </ul>
    </section>

    <section id="certificates">
      <h2>Certificates</h2>
      <ul>
        <li>Algorithms on Strings | <a href="https://coursera.org/verify/PF8EJ95J4BBU" target="_blank">View Certificate</a></li>
        <li>Approximation Algorithms and Linear Programming | <a href="https://coursera.org/verify/LS3QJXZJAY7A" target="_blank">View Certificate</a></li>
        <li>Network Communication | <a href="https://coursera.org/verify/GWVJ2SGC2RW4" target="_blank">View Certificate</a></li>
        <li>ChatGPT Advanced Data Analysis | <a href="https://coursera.org/verify/FV77PG5F92N9" target="_blank">View Certificate</a></li>
        <li>DSA (GeeksforGeeks) | <a href="https://media.geeksforgeeks.org/courses/certificates/bcaf5fe4afa11a6a9768cb1dbfbe31f4.pdf" target="_blank">View Certificate</a></li>
        <li>Mastering DSA with C/C++ (Udemy) | <a href="https://www.udemy.com/certificate/UC-4a23a756-ee09-4618-85b0-3504cb095392/" target="_blank">View Certificate</a></li>
      </ul>
    </section>

    <section id="education">
      <h2>Education</h2>
      <p><strong>B.Tech in CSE</strong> – Lovely Professional University (2022–2026)</p>
      <p><strong>Intermediate:</strong> Delhi Public School, Muzaffarpur (62.2%)</p>
      <p><strong>Matriculation:</strong> D.A.V Public School, Muzaffarpur (68.2%)</p>
    </section>
    <section>
        <h2>CV</h2>
        <p>
            <a href="c:\Users\srshu\Downloads\shubhamcv.pdf" target="_blank" style="color: #ffd60a; font-weight: bold;">📄 View My CV</a>
          </p>
      </section>
      <section id="contact">
        <h2>Contact Us</h2>
        <form action="mailto:srshubhammuz1@gmail.com" method="POST" enctype="text/plain" style="display: flex; flex-direction: column; gap: 15px;">
          <input type="text" name="name" placeholder="Your Name" required style="padding: 10px; border-radius: 10px; border: none; background: #2d2d44; color: white;">
          <input type="email" name="email" placeholder="Your Email" required style="padding: 10px; border-radius: 10px; border: none; background: #2d2d44; color: white;">
          <input type="text" name="subject" placeholder="Subject" style="padding: 10px; border-radius: 10px; border: none; background: #2d2d44; color: white;">
          <textarea name="message" rows="5" placeholder="Your Message" required style="padding: 10px; border-radius: 10px; border: none; background: #2d2d44; color: white;"></textarea>
          <button type="submit" style="background: var(--accent); color: white; padding: 10px; border: none; border-radius: 10px; font-size: 1rem; cursor: pointer;">Send Message</button>
        </form>
      </section>
  </main>

  <footer>
    <p>&copy; 2025 Shubham Raj</p>
    <button id="scrollTopBtn">↑ Back to Top</button>
  </footer>
  

  <script>
    const scrollBtn = document.getElementById("scrollTopBtn");

    window.onscroll = () => {
      scrollBtn.style.display = window.scrollY > 300 ? "block" : "none";
    };

    scrollBtn.onclick = () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    };
  </script>
</body>
</html>
