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
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background: #eaf2f8;
            color: #2c3e50;
        }

        header {
            background: linear-gradient(90deg, #6a11cb 0%, #2575fc 100%);
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }

        nav {
            margin: 1rem 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
            font-size: 1.2rem;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 2rem;
        }

        section {
            margin-bottom: 2rem;
            padding: 2rem;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-bottom: 1rem;
            color: #2575fc;
            font-size: 1.8rem;
            border-bottom: 3px solid #6a11cb;
            display: inline-block;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            text-align: center;
        }

        .skills span {
            background: #2575fc;
            color: #fff;
            padding: 0.7rem;
            border-radius: 30px;
            font-size: 1rem;
            font-weight: bold;
        }

        .projects .project {
            margin-bottom: 1.5rem;
        }

        .projects .project a {
            text-decoration: none;
            color: #6a11cb;
            font-weight: bold;
        }

        .projects .project a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 1.5rem 0;
            background: #6a11cb;
            color: #fff;
        }

        footer a {
            color: #f1c40f;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 768px) {
            .skills {
                grid-template-columns: 1fr;
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
