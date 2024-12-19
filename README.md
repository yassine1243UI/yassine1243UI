<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Front End Developer</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .intro {
            text-align: center;
            padding: 50px 0;
        }

        .intro h1 {
            font-size: 3rem;
            color: #58a6ff;
        }

        .intro h2 {
            font-size: 1.5rem;
            margin-top: 10px;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #58a6ff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
        }

        .skills {
            text-align: center;
            padding: 50px 0;
        }

        .skills h2 {
            margin-bottom: 20px;
        }

        .skills-cloud {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            max-width: 600px;
            margin: 0 auto;
        }

        .skills-cloud span {
            font-size: 1rem;
            color: #58a6ff;
            animation: float 5s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }

        .projects {
            padding: 50px 0;
        }

        .projects h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .project-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .project-card {
            background-color: #161b22;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            color: #c9d1d9;
        }

        .project-card img {
            max-width: 100%;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #161b22;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Introduction Section -->
        <section class="intro">
            <h1>Hello, I am Alex</h1>
            <h2>Front End Developer</h2>
            <a href="#projects" class="btn">Let's get started</a>
        </section>

        <!-- Skills Section -->
        <section class="skills">
            <h2>Skills and Tools</h2>
            <div class="skills-cloud">
                <span>JavaScript</span>
                <span>React.js</span>
                <span>Node.js</span>
                <span>HTML</span>
                <span>CSS</span>
                <span>Express</span>
                <span>MongoDB</span>
                <span>Chart.js</span>
                <span>Styled-Components</span>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects">
            <h2>Projects</h2>
            <div class="project-gallery">
                <div class="project-card">
                    <img src="https://via.placeholder.com/300" alt="Project 1">
                    <h3>Taskly</h3>
                    <p>Manage your daily tasks with ease.</p>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/300" alt="Project 2">
                    <h3>GreenShop</h3>
                    <p>E-commerce platform for eco-friendly products.</p>
                </div>
                <div class="project-card">
                    <img src="https://via.placeholder.com/300" alt="Project 3">
                    <h3>Portfolio</h3>
                    <p>Interactive showcase of my skills and projects.</p>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Alex Dupont. All rights reserved.</p>
    </footer>
</body>
</html>
