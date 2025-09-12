<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Portfolio</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body and Background */
        body {
            font-family: Arial, sans-serif;
            color: #fff;
            background: url('https://www.example.com/your-background-image.jpg') no-repeat center center fixed;
            background-size: cover;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Main container for the whole page */
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

        /* Section Styles */
        section {
            background: rgba(0, 0, 0, 0.5);
            margin-bottom: 40px;
            padding: 40px;
            border-radius: 8px;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        section p {
            font-size: 1.2rem;
            line-height: 1.6;
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

        /* Responsive Design */
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
        <!-- Navigation Bar -->
        <nav>
            <div>
                <h1>Your Name</h1>
            </div>
            <div>
                <a href="#about">About Me</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>

        <!-- About Me Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hello! I'm [Your Name], a passionate web developer. I specialize in front-end development and love to create clean, user-friendly websites. 
                Feel free to explore my portfolio to see some of the projects I've worked on!
            </p>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>Projects</h2>
            <p>
                Below are some of the projects I have worked on. You can click on the links to explore the details or view the live versions of these websites.
            </p>
            <ul>
                <li><a href="https://www.example.com/project1" target="_blank">Project 1: Web Application</a></li>
                <li><a href="https://www.example.com/project2" target="_blank">Project 2: Portfolio Website</a></li>
                <li><a href="https://www.example.com/project3" target="_blank">Project 3: E-commerce Site</a></li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contact</h2>
            <p>
                You can reach out to me through the following platforms:
            </p>
            <ul>
                <li>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">LinkedIn Profile</a></li>
                <li>GitHub: <a href="https://github.com/yourusername" target="_blank">GitHub Profile</a></li>
            </ul>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 [Your Name]. All Rights Reserved.</p>
        <a href="#about">Back to top</a>
    </footer>

</body>
</html>
