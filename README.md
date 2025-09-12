<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mamilla Rishikesh Reddy - Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: #fff;
      background: url('https://raw.githubusercontent.com/<your-username>/<repo-name>/main/BreakingBadMikeWalt.jpg')

      background-size: cover;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }

    .container {
      width: 100%;
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 8px;
      margin-bottom: 40px;
    }

    nav h1 { font-size: 1.8rem; }
    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 16px;
      padding: 8px 12px;
      border-radius: 5px;
      transition: 0.3s;
    }
    nav a:hover { background: rgba(255, 255, 255, 0.2); }

    section {
      background: rgba(0, 0, 0, 0.5);
      margin-bottom: 40px;
      padding: 40px;
      border-radius: 8px;
    }
    section h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      color: #ff9800;
    }
    section p, section li { font-size: 1.1rem; line-height: 1.6; }

    /* Projects grid */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .project-card {
      background: rgba(255, 255, 255, 0.1);
      padding: 20px;
      border-radius: 8px;
      transition: 0.3s;
    }
    .project-card:hover { background: rgba(255, 255, 255, 0.2); }
    .project-card h3 { margin-bottom: 10px; color: #4fc3f7; }
    .project-card a { color: #ff9800; text-decoration: none; }
    .project-card a:hover { text-decoration: underline; }

    footer {
      text-align: center;
      padding: 20px;
      background: rgba(0, 0, 0, 0.7);
      border-radius: 8px;
      margin-top: auto;
    }
    footer a { color: #ff9800; text-decoration: none; }
    footer a:hover { text-decoration: underline; }

    html { scroll-behavior: smooth; }

    @media (max-width: 768px) {
      nav { flex-direction: column; text-align: center; }
      section { padding: 20px; }
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Navbar -->
    <nav>
      <h1>Mamilla Rishikesh Reddy</h1>
      <div>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <!-- About Section -->
    <section id="about">
      <h2>About Me</h2>
      <p>
        Hi! I'm <strong>Mamilla Rishikesh Reddy</strong>, a Computer Science graduate from 
        <strong>Neil Gogte Institute of Technology</strong> (2020–2024).  
        Currently pursuing my Master’s in Computer Science at <strong>Old Dominion University, Virginia</strong>.  
        My interests include <strong>Artificial Intelligence, Machine Learning, and App Development</strong>.
      </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
      <h2>Technical Skills</h2>
      <ul>
        <li>Programming: Java, Python, HTML, Node.js, MySQL</li>
        <li>Problem-Solving: Solved 90+ LeetCode problems</li>
        <li>Specializations: Machine Learning, AI, Data Structures</li>
        <li>Certifications: Machine Learning (Udemy)</li>
      </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
      <h2>Projects</h2>
      <div class="projects">
        <div class="project-card">
          <h3>Smart Price Alert</h3>
          <p>An automated e-commerce price monitoring system.</p>
          <a href="#">View Project</a>
        </div>
        <div class="project-card">
          <h3>15-Puzzle Solver</h3>
          <p>Implemented BFS, DFS, and heuristic-based informed search.</p>
          <a href="#">View Project</a>
        </div>
        <div class="project-card">
          <h3>Portfolio Website</h3>
          <p>This personal portfolio showcasing my skills and projects.</p>
          <a href="#">View Site</a>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:rishikesh@example.com">rishikesh@example.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/mamilla-rishikesh-reddy" target="_blank">linkedin.com/in/mamilla-rishikesh-reddy</a></p>
      <p>GitHub: <a href="https://github.com/RishikeshMamilla" target="_blank">github.com/RishikeshMamilla</a></p>
    </section>
  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Mamilla Rishikesh Reddy. All Rights Reserved.</p>
    <a href="#about">Back to top</a>
  </footer>

</body>
</html>
