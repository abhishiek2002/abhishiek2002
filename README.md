<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        .about-me {
            text-align: center;
            padding: 50px;
            background-color: #fff;
        }

        .about-me h1 {
            color: #0073e6;
            font-size: 36px;
        }

        .about-me p {
            font-size: 16px;
            color: #333;
        }

        .projects {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 50px;
            background-color: #f9f9f9;
        }

        .project-summary {
            text-align: center;
            background-color: #0073e6;
            color: #fff;
            padding: 20px;
            border-radius: 10px;
            width: 80%;
            margin-bottom: 30px;
        }

        .project-summary img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }

        .project-summary h2 {
            font-size: 24px;
        }

        .project-summary a {
            color: #fff;
            text-decoration: none;
            background-color: #005bb5;
            padding: 10px 20px;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }

        .project-grid {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .project-card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 200px;
            padding: 20px;
            text-align: center;
        }

        .project-card h3 {
            font-size: 20px;
            color: #0073e6;
        }

        .project-card a {
            color: #0073e6;
            text-decoration: none;
            font-weight: bold;
            margin-top: 10px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <section class="about-me">
        <h2>A Bit About Me</h2>
        <h1>Who Am I?</h1>
        <p>Hi I'm Jack Smith. Click here to add your own text and edit me. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        <p>Image by <a href="https://www.freepik.com">Freepik</a></p>
    </section>
    <section class="projects">
        <div class="project-summary">
            <img src="your-image-url-here.jpg" alt="Profile Image">
            <h2>I am happy to know you that 300+ projects done successfully!</h2>
            <a href="#">Learn More</a>
        </div>
        <div class="project-grid">
            <div class="project-card">
                <h3>Graphic Design</h3>
                <a href="#">MORE</a>
            </div>
            <div class="project-card">
                <h3>Web Design</h3>
                <a href="#">MORE</a>
            </div>
            <div class="project-card">
                <h3>Software</h3>
                <a href="#">MORE</a>
            </div>
            <div class="project-card">
                <h3>Application</h3>
                <a href="#">MORE</a>
            </div>
        </div>
    </section>
</body>
</html>


