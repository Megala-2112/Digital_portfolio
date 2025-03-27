<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Megala P - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ff1744;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #b2ff59;
            padding: 20px;
            text-align: center;
        }
        .header h1 {
            margin: 0;
        }
        .nav {
            background-color: #d50000;
            padding: 10px;
            text-align: center;
        }
        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
        }
        .section {
            margin-bottom: 20px;
        }
        .resume-btn {
            display: block;
            width: 150px;
            margin: auto;
            padding: 10px;
            background-color: #000;
            color: white;
            text-align: center;
            border-radius: 5px;
            text-decoration: none;
        }
        .resume-btn:hover {
            background-color: #333;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Megala P</h1>
        <p>BCA Student</p>
    </div>

    <div class="nav">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container">
        <div id="about" class="section">
            <h2>About Me</h2>
            <p>Currently, I am pursuing a BCA degree.</p>
        </div>

        <div id="education" class="section">
            <h2>Education</h2>
            <p>Madras University, BCA</p>
        </div>

        <div id="skills" class="section">
            <h2>Skills</h2>
            <ul>
                <li>Java</li>
                <li>Python</li>
                <li>C++</li>
                <li>Data Structures</li>
            </ul>
        </div>

        <div id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li>Number Guessing Game Program</li>
            </ul>
        </div>

        <div id="resume" class="section">
            <h2>Resume</h2>
            <a href="resume.pdf" class="resume-btn" download>Download CV</a>
        </div>
    </div>

    <footer style="text-align:center; padding:10px; background:#000; color:white;">
        © 2025 Megala P
    </footer>

</body>
</html>

