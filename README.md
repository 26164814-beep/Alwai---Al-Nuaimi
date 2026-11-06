<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alwai Al-Nuaimi | IT Student</title><style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        scroll-behavior: smooth;
    }

    body {
        font-family: Arial, sans-serif;
        background: #f8fafc;
        color: #1e293b;
    }

    /* Navigation */

    header {
        background: white;
        box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    nav {
        width: 90%;
        max-width: 1200px;
        margin: auto;
        height: 80px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    .logo {
        color: #2563eb;
        font-size: 28px;
        font-weight: bold;
    }

    nav ul {
        display: flex;
        gap: 25px;
        list-style: none;
    }

    nav a {
        text-decoration: none;
        color: #475569;
        font-weight: bold;
        transition: 0.3s;
    }

    nav a:hover {
        color: #2563eb;
    }

    /* Hero */

    .hero {
        max-width: 1200px;
        width: 90%;
        min-height: 550px;
        margin: auto;
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 40px;
    }

    .hero-content {
        max-width: 600px;
    }

    .welcome {
        color: #2563eb;
        letter-spacing: 3px;
        font-weight: bold;
        margin-bottom: 20px;
    }

    .hero h1 {
        font-size: 42px;
        margin-bottom: 15px;
    }

    .hero h1 span {
        color: #2563eb;
    }

    .hero h3 {
        color: #64748b;
        margin-bottom: 20px;
    }

    .description {
        line-height: 1.8;
        color: #64748b;
        margin-bottom: 30px;
    }

    .btn {
        display: inline-block;
        background: #2563eb;
        color: white;
        padding: 13px 28px;
        border-radius: 8px;
        text-decoration: none;
        transition: 0.3s;
    }

    .btn:hover {
        background: #1d4ed8;
        transform: translateY(-3px);
    }

    /* Profile Circle */

    .circle {
        width: 280px;
        height: 280px;
        border-radius: 50%;
        background: linear-gradient(135deg, #2563eb, #06b6d4);
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        color: white;
        box-shadow: 0 15px 40px rgba(37,99,235,0.2);
    }

    .circle h2 {
        font-size: 85px;
    }

    .circle p {
        letter-spacing: 5px;
    }

    /* Sections */

    section:not(.hero) {
        padding: 80px 10%;
        text-align: center;
    }

    .about {
        background: white;
    }

    section h2 {
        color: #2563eb;
        font-size: 32px;
        margin-bottom: 25px;
    }

    .about p {
        max-width: 700px;
        margin: auto;
        line-height: 1.8;
        color: #64748b;
    }

    /* Skills */

    .skills-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 25px;
        margin-top: 40px;
    }

    .card {
        background: white;
        padding: 35px 20px;
        border-radius: 12px;
        box-shadow: 0 5px 20px rgba(0,0,0,0.05);
        transition: 0.3s;
    }

    .card:hover {
        transform: translateY(-8px);
    }

    .card h3 {
        color: #2563eb;
        margin-bottom: 12px;
    }

    .card p {
        color: #64748b;
    }

    /* Goals */

    .goals {
        background: white;
    }

    .goals ul {
        list-style: none;
        line-height: 2.5;
        color: #64748b;
    }

    /* Footer */

    footer {
        background: #0f172a;
        color: white;
        text-align: center;
        padding: 25px;
    }

    /* Responsive */

    @media (max-width: 768px) {

        nav {
            height: auto;
            padding: 20px 0;
            flex-direction: column;
            gap: 20px;
        }

        nav ul {
            gap: 15px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .hero {
            flex-direction: column;
            text-align: center;
            padding: 60px 0;
        }

        .hero h1 {
            font-size: 32px;
        }

        .circle {
            width: 220px;
            height: 220px;
        }

        .skills-container {
            grid-template-columns: 1fr;
        }
    }

</style>

</head><body><header>
    <nav>
        <h2 class="logo">Alwai.</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#goals">Goals</a></li>
        </ul>
    </nav>
</header>

<main>

    <section class="hero" id="home">

        <div class="hero-content">

            <p class="welcome">WELCOME TO MY PROFILE</p>

            <h1>
                Hi, I'm <span>Alwai Al-Nuaimi</span>
            </h1>

            <h3>Information Technology Student</h3>

            <p class="description">
                I'm an IT student passionate about programming,
                web development, databases and computer networks.
                Always learning and improving my skills.
            </p>

            <a href="#about" class="btn">Explore More</a>

        </div>

        <div class="circle">
            <h2>IT</h2>
            <p>STUDENT</p>
        </div>

    </section>

    <section class="about" id="about">

        <h2>About Me</h2>

        <p>
            My name is Alwai Al-Nuaimi.
            I am an Information Technology student interested
            in software development, programming and modern
            technologies. My goal is to become a professional
            software developer.
        </p>

    </section>

    <section class="skills" id="skills">

        <h2>My Skills</h2>

        <div class="skills-container">

            <div class="card">
                <h3>Python</h3>
                <p>Programming and OOP</p>
            </div>

            <div class="card">
                <h3>HTML</h3>
                <p>Web Page Structure</p>
            </div>

            <div class="card">
                <h3>CSS</h3>
                <p>Web Page Design</p>
            </div>

            <div class="card">
                <h3>JavaScript</h3>
                <p>Web Programming</p>
            </div>

            <div class="card">
                <h3>SQL</h3>
                <p>Database Management</p>
            </div>

            <div class="card">
                <h3>Git & GitHub</h3>
                <p>Version Control</p>
            </div>

        </div>

    </section>

    <section class="goals" id="goals">

        <h2>My Goals</h2>

        <ul>
            <li>Become a Professional Developer.</li>
            <li>Build Real-World Applications.</li>
            <li>Improve My Programming Skills.</li>
            <li>Contribute to Open Source Projects.</li>
        </ul>

    </section>

</main>

<footer>
    <p>© 2026 Alwai Al-Nuaimi | All Rights Reserved</p>
</footer>

</body>
</html>
