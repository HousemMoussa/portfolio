<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Housem Moussa - Aerospace Engineer</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        header {
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #1a2a6c;
        }
        .nav-links a {
            margin-left: 20px;
            text-decoration: none;
            color: #333;
            transition: color 0.3s ease;
        }
        .nav-links a:hover {
            color: #1a2a6c;
        }
        .hero {
            background: linear-gradient(to right, #1a2a6c, #b21f1f, #fdbb2d);
            color: white;
            text-align: center;
            padding: 150px 0 100px;
            margin-top: 60px;
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 24px;
            max-width: 600px;
            margin: 0 auto;
        }
        .section {
            padding: 80px 0;
            background-color: #fff;
            margin: 40px 0;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .section h2 {
            font-size: 36px;
            margin-bottom: 40px;
            color: #1a2a6c;
            text-align: center;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        .project {
            background-color: #f9f9f9;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .project:hover {
            transform: translateY(-5px);
        }
        .project img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .project-content {
            padding: 20px;
        }
        .project h3 {
            margin-top: 0;
            color: #1a2a6c;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }
        .skill {
            background-color: #1a2a6c;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-size: 14px;
        }
        .contact-form {
            max-width: 500px;
            margin: 0 auto;
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #1a2a6c;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .contact-form button:hover {
            background-color: #15215c;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">Housem Moussa</div>
                <div class="nav-links">
                    <a href="#about">About</a>
                    <a href="#projects">Projects</a>
                    <a href="#skills">Skills</a>
                    <a href="#contact">Contact</a>
                </div>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Innovative Solutions in Aerospace Engineering</h1>
            <p>MEng Graduate | Flight Dynamics | Systems Design | Problem Solver</p>
        </div>
    </section>

    <section id="about" class="section">
        <div class="container">
            <h2>About Me</h2>
            <p>As a highly motivated MEng Aerospace Engineering graduate, I bring a strong passion for research and proven skills in independent study. My goal is to pursue a career as a Flight Dynamics Engineer, Systems Engineer, Structural Engineer, or Design Engineer, leveraging my multilingual abilities and technical expertise to drive innovation in the aerospace industry.</p>
        </div>
    </section>

    <section id="projects" class="section">
        <div class="container">
            <h2>Featured Projects</h2>
            <div class="projects">
                <div class="project">
                    <img src="/api/placeholder/300/200" alt="Aerial Surveillance Drone">
                    <div class="project-content">
                        <h3>Aerial Surveillance Drone</h3>
                        <p>Engineered a quadrotor drone for ecological research, optimized for capturing high-resolution imagery of remote puffin islands.</p>
                    </div>
                </div>
                <div class="project">
                    <img src="/api/placeholder/300/200" alt="Hydrogen Generation Process">
                    <div class="project-content">
                        <h3>Hydrogen Generation Process</h3>
                        <p>Developed a sustainable energy solution to power Liverpool John Lennon Airport using wind energy and hydrogen generation.</p>
                    </div>
                </div>
                <div class="project">
                    <img src="/api/placeholder/300/200" alt="ASTOVL Aerodynamics Flight Model">
                    <div class="project-content">
                        <h3>ASTOVL Aerodynamics Flight Model</h3>
                        <p>Created a comprehensive aerodynamics model and simulation framework for low-speed flight regimes, focusing on transition and hover flight conditions.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="section">
        <div class="container">
            <h2>Technical Skills</h2>
            <div class="skills">
                <span class="skill">MATLAB</span>
                <span class="skill">Python</span>
                <span class="skill">CFD</span>
                <span class="skill">CAD</span>
                <span class="skill">Structural Analysis</span>
                <span class="skill">Aerodynamic Analysis</span>
                <span class="skill">Experimental Design</span>
                <span class="skill">Flight Dynamics</span>
                <span class="skill">Systems Engineering</span>
            </div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="container">
            <h2>Get in Touch</h2>
            <form class="contact-form">
                <input type="text" placeholder="Name" required>
                <input type="email" placeholder="Email" required>
                <textarea placeholder="Message" rows="5" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Housem Moussa. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
