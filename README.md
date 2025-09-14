
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mamilla Rishikesh Reddy - Portfolio</title>
  <style>
/* Body and Background */
body {
  font-family: Arial, sans-serif;
  color: #fff;
  background: url('BreakingBadMikeWalt.jpg') 
              no-repeat center center fixed;
  background-size: cover;
  height: 100vh;
  display: flex;
  flex-direction: column;
}

/* Container */
.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

/* Navbar */
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background: rgba(0, 0, 0, 0.6);
  border-radius: 8px;
  margin-bottom: 40px;
}

nav h1 {
  font-size: 24px;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-size: 18px;
  padding: 10px;
  border-radius: 5px;
}

nav a:hover {
  background: rgba(255, 255, 255, 0.2);
}

/* Sections */
section {
  background: rgba(0, 0, 0, 0.6);
  margin-bottom: 40px;
  padding: 40px;
  border-radius: 8px;
}

section h2 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

section p, section li {
  font-size: 1.2rem;
  line-height: 1.6;
}

ul {
  list-style-type: none;
  margin-top: 15px;
}

ul li {
  margin-bottom: 10px;
}

ul li a {
  color: #00aced;
  text-decoration: none;
}

ul li a:hover {
  text-decoration: underline;
}

/* Movies Grid */
.movies-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.movie-card {
  background: rgba(255, 255, 255, 0.1);
  border-radius: 10px;
  overflow: hidden;
  text-align: center;
  transition: transform 0.3s ease;
}

.movie-card:hover {
  transform: scale(1.05);
}

.movie-card img {
  width: 100%;
  height: 320px;
  object-fit: cover;
}

.movie-card h3 {
  margin: 10px 0;
  font-size: 1.3rem;
  color: #fff;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: rgba(0, 0, 0, 0.7);
  margin-top: auto;
  border-radius: 8px;
}

footer a {
  color: #fff;
  text-decoration: none;
  font-size: 16px;
}

footer a:hover {
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 768px) {
  nav {
    flex-direction: column;
    text-align: center;
  }

  section {
    padding: 20px;
  }
}
  </style>
</head>
<body>
  <div class="container">
    <!-- Navbar -->
    <nav>
      <div>
        <h1>Mamilla Rishikesh Reddy</h1>
      </div> 
   


      <div>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#favorites">Favorites</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  
    <!-- Profile Picture -->
     
<div id="profile-picture"  
  width="50" 
       height="80" 
       style="border-radius: 50%; object-fit: cover;">
  
  <img src="rishi m.jpg" 
       alt="Mamilla width: 100px;
    height: 100px; 
       >
</div>


    <!-- About -->
    <section id="about">
      <h2>About Me</h2>
      <p>
        Hello! I'm Mamilla Rishikesh Reddy, a passionate computer science student and aspiring developer.  
        I enjoy working with <b>Java, Python, Node.js, and MySQL</b>.  
        My interests include <b>AI, Machine Learning, and App Development</b>.  
        I love solving problems and building useful applications.
      </p>
    </section>

    <!-- Projects -->
    <section id="projects">
      <h2>Projects</h2>
      <p>Here are some of the projects I worked on:</p>
      <ul>
        <li><a href="#">Smart Price Alert - Automated E-commerce Price Monitoring</a></li>
      </ul>
    </section>
<section id="hobbies">
  <h2>Hobbies</h2>
  <p>
    Outside of academics, I enjoy a balance of sports and entertainment.  
    I’m passionate about <b>watching cricket</b>, following exciting matches and supporting my favorite teams.  
    I also love <b>watching movies</b>, as they inspire creativity and storytelling.  
    Staying active is important to me — I regularly play <b>badminton</b>, which sharpens my reflexes and teamwork,  
    and I dedicate time to the <b>gym</b> to build strength and maintain a healthy lifestyle.  
  </p>
</section>


    <!-- Favorites -->
    <section id="favorites">
      <h2>Favorite Movies & TV Shows</h2>
      <div class="movies-grid">
        <div class="movie-card">
          <a href="https://www.imdb.com/title/tt0903747/" target="_blank">
            <img src="https://www.imdb.com/title/tt0903747/mediaviewer/rm3116305665/?ref_=tt_ov_i">
            <h3>Breaking Bad</h3>
          </a>
        </div>
        <div class="movie-card">
          <a href="https://www.imdb.com/title/tt0111161/" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/en/8/81/ShawshankRedemptionMoviePoster.jpg" alt="The Shawshank Redemption">
            <h3>The Shawshank Redemption</h3>
          </a>
        </div>
        <div class="movie-card">
          <a href="https://www.imdb.com/title/tt0137523/" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/en/f/fc/Fight_Club_poster.jpg" alt="Fight Club">
            <h3>Fight Club</h3>
          </a>
        </div>
        <div class="movie-card">
          <a href="https://www.imdb.com/title/tt2198161/" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/en/9/9a/Seethamma_Vakitlo_Sirimalle_Chettu.jpg" alt="SVSC">
            <h3>Seethamma Vakitlo Sirimalle Chettu</h3>
          </a>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Contact</h2>
      <p>You can reach me through:</p>
      <ul>
        <li>Email: <a href="mailto:rmami001@odu.edu">rmami001@odu.edu</a></li>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/rishikesh-reddy-mamilla-53b066164/" target="_blank">LinkedIn</a></li>
        <li>GitHub: <a href="https://github.com/Rishikesh232003" target="_blank">GitHub</a></li>
      </ul>
    </section>
  </div>
.resume-btn {
  display: inline-block;
  background: #00aced;
  color: #fff;
  padding: 12px 24px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s;
}

.resume-btn:hover {
  background: #0084b4;
}
<section id="resume">
  <h2>Resume</h2>
  <p>If you’d like to know more about my experience, you can download my resume below:</p>
  <a href="resume.pdf" download class="resume-btn">📄 Download Resume</a>
</section>



  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Mamilla Rishikesh Reddy. All Rights Reserved.</p>
    <a href="#about">Back to top</a>
  </footer>
</body>
</html>

