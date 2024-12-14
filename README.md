# Ramkumar Haribaskar - Portfolio

An example of my portfolio website created using HTML, CSS, and basic web design principles.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramkumar Haribaskar - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #007bff;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 0.5rem 0;
        }

        nav {
            background: #0056b3;
            padding: 0.5rem;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin: 0 1rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }

        h2 {
            color: #007bff;
        }

        .skills, .projects {
            margin: 1.5rem 0;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        .contact a {
            color: #007bff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ramkumar Haribaskar</h1>
        <p>Experienced Python Developer | Analyst | Automation Enthusiast</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a passionate Python developer with over 4 years of experience in planning, designing, implementing, and deploying software solutions. Currently working as a Python Developer & SRE Engineer at Accenture, I specialize in backend development, automation, and creating seamless workflows for clients. My journey has been enriched with hands-on experience in Django, REST APIs, and database management, enabling me to drive impactful changes in the tech landscape.</p>
    </section>

    <section id="skills" class="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Django</li>
            <li>REST API</li>
            <li>MSSQL / Sybase</li>
            <li>Docker</li>
            <li>HTML / CSS</li>
            <li>Git</li>
            <li>SSIS</li>
            <li>Data Structures and Algorithms</li>
        </ul>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <strong>Voice of Customer (VOC) Survey Management System:</strong>
                Improved feedback response rates by 30% using Python, Django, REST API, and MSSQL.
            </li>
            <li>
                <strong>Process and Report Automation Tool:</strong>
                Automated client report generation using Excel macros, VBA, and SQL, delivering critical information promptly.
            </li>
            <li>
                <strong>IIS Reset Automation:</strong>
                Reduced 80-minute manual server reset processes to 2 minutes for seamless production deployment.
            </li>
        </ul>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:rammechk@gmail.com">rammechk@gmail.com</a></p>
        <p>Phone: +91 8072246160</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/ramkumar-haribaskar/">linkedin.com/in/ramkumar-haribaskar</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Ramkumar Haribaskar. All Rights Reserved.</p>
    </footer>
</body>
</html>
