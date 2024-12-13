<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background: #f4f4f9;
            color: #333;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
        }

        nav {
            margin: 1rem 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }

        .container {
            max-width: 1100px;
            margin: 2rem auto;
            padding: 0 2rem;
        }

        section {
            margin-bottom: 2rem;
            padding: 1.5rem;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-bottom: 1rem;
            color: #333;
            border-bottom: 2px solid #333;
            display: inline-block;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .skills span {
            background: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }

        .projects .project {
            margin-bottom: 1rem;
        }

        .projects .project a {
            text-decoration: none;
            color: #0066cc;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: #fff;
        }

        footer a {
            color: #0066cc;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            .skills {
                flex-direction: column;
                align-items: flex-start;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>My GitHub Portfolio</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Hello! I'm a passionate developer with experience in web development, always eager to learn and contribute to exciting projects. Welcome to my portfolio!</p>
        </section>

        <section id="skills">
            <h2>Skills</h2>
            <div class="skills">
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
                <span>React</span>
                <span>Node.js</span>
                <span>Git</span>
            </div>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <h3>Project 1: Portfolio Website</h3>
                    <p>A personal portfolio website to showcase my work and skills.</p>
                    <a href="#">View on GitHub</a>
                </div>
                <div class="project">
                    <h3>Project 2: To-Do App</h3>
                    <p>A simple and functional to-do list application built with React.</p>
                    <a href="#">View on GitHub</a>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>If you'd like to collaborate or learn more, feel free to reach out:</p>
            <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <p>GitHub: <a href="https://github.com/yourusername">github.com/yourusername</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 My GitHub Portfolio | <a href="#">Back to Top</a></p>
    </footer>
</body>
</html>
