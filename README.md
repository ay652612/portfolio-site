<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Khushi Tyagi | Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #fdfbfb;
            color: #333;
            line-height: 1.6;
        }

        nav {
            background-color: #000;
            color: white;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav h1 {
            font-size: 24px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            background: linear-gradient(to right, #ff4e50, #f9d423);
            padding: 100px 20px;
            text-align: center;
            color: white;
        }

        .hero h2 {
            font-size: 36px;
        }

        .hero p {
            margin-top: 10px;
            font-size: 18px;
        }

        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }

        h2 {
            color: #e91e63;
            margin-bottom: 15px;
        }

        #skills ul {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 15px;
            padding: 0;
        }

        #skills li {
            background-color: #ffe0e6;
            padding: 15px;
            border-left: 5px solid #e91e63;
            border-radius: 5px;
            list-style: none;
            color: #222;
            font-weight: 500;
        }

        ul {
            margin-left: 20px;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        form button {
            padding: 10px 20px;
            background-color: #e91e63;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #c2185b;
        }
    </style>
</head>

<body>
    <nav>
        <h1>Khushi Tyagi</h1>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="hero">
        <h2>Hello, I'm Khushi Tyagi</h2>
        <p>Full Stack Web Developer | BCA Student | Passionate Coder</p>
    </div>

    <section id="about">
        <h2>About Me</h2>
        <p>Self-motivated and ambitious BCA student with strong skills in web development, DSA, and problem-solving. I enjoy transforming ideas into reality through code and love building impactful web projects.</p>
    </section>

    <section id="skills">
        <h2>Technical Skills</h2>
        <ul>
            <li>Languages: C++, JavaScript, Python, HTML, CSS</li>
            <li>Web Technologies: DOM, jQuery, ReactJS, Form Handling</li>
            <li>Frameworks: ReactJS</li>
            <li>Tools: Git, GitHub, VS Code</li>
            <li>Soft Skills: Debugging, Teamwork, Learning Attitude</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li><strong>Portfolio Website</strong> – A personal website to showcase my skills and projects.</li>
            <li><strong>To-Do App</strong> – Task management app built with ReactJS.</li>
            <li><strong>Student Result Management System</strong> – Built using Python and MySQL.</li>
        </ul>
    </section>

    <section id="education">
        <h2>Education</h2>
        <p>Bachelor of Computer Applications (BCA)<br> [Your University Name], [Year]</p>
    </section>

    <section id="certifications">
        <h2>Certifications</h2>
        <ul>
            <li>Responsive Web Design – freeCodeCamp</li>
            <li>JavaScript Algorithms and Data Structures – freeCodeCamp</li>
            <li>React Basics – Coursera</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
</body>

</html>
