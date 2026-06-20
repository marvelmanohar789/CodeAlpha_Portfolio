# CodeAlpha_Portfolio

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Portfolio</title>

    <link rel="stylesheet" href="portfolio.css">
</head>

<body>

    <!-- Navbar -->

    <nav>

        <h2 class="logo"> Portfolio </center></h2>

        <ul>

            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>

        </ul>

    </nav>

    <!-- Hero Section -->

    <section id="home" class="hero">

        <div class="hero-text">

            <h1><center> Hello, I'm <span>Manohar</span></center></h1>

            <p>Frontend Developer | Java Programmer</p>

            <a href="#projects" class="btn">View Projects</a>

        </div>

        <div class="hero-image">

            <img src="./profile image/pass photo.jpg " alt="Profile ">

        </div>

    </section>

    <!-- About Section -->

    <section id="about" class="about">

        <h2>About Me</h2>

        <p>
            <p>
I am a highly motivated and enthusiastic Frontend Developer and Java Programmer with a strong interest in building modern, responsive, and user-friendly web applications. I have hands-on experience in developing websites using HTML, CSS, JavaScript, and Java, along with a solid understanding of programming concepts and problem-solving techniques.

As a recent graduate, I am passionate about continuously learning new technologies and improving my technical skills. I enjoy transforming ideas into functional and visually appealing digital solutions that provide an excellent user experience across different devices and platforms.

In addition to web development, I have a keen interest in Machine Learning and Artificial Intelligence. I have worked on projects such as an Agriculture Management System for crop yield prediction using Machine Learning algorithms, which enhanced my analytical and development skills.


</p>
        </p>

    </section>

    <!-- Skills Section -->

    <section id="skills" class="skills">

        <h2>Skills</h2>

        <div class="skill-box">

            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">Java</div>
            <div class="skill">Python</div>
            <div class="skill">SQL</div>
            <div class="skill">Machine Learning</div>
            <div class="skill">Github</div>

        </div>

    </section>

    <!-- Projects Section -->

    <section id="projects" class="projects">

        <h2>Projects</h2>

        <div class="project-container">

            <div class="project-card">

                <h3>Calculator</h3>

                <p>Basic calculator using HTML, CSS and JavaScript.</p>

            </div>

            <div class="project-card">

                <h3>Image Gallery</h3>

                <p>Responsive image gallery with lightbox functionality.</p>

            </div>

            <div class="project-card">

                <h3>Agriculture Management System</h3>

                <p>ML-based crop prediction and recommendation system.</p>

            </div>

        </div>

    </section>

    <!-- Resume Section -->

    <section class="resume">

        <h2>Resume</h2>

        <a href="./resume/my_resume (1).pdf" download class="btn">
            Download Resume
        </a>

    </section>

    <!-- Contact Section -->

    <section id="contact" class="contact">

        <h2>Contact Me</h2>

        <p>Email: manoharravula576@gmail.com</p>

        <p>Phone: 7893136326</p>

    </section>

    <!-- Footer -->

    <footer>

        <p>© 2026 Manohar | All Rights Reserved</p>

    </footer>

    <script src="portfolio.js"></script>

</body>

</html>


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial;
    background: #ece9df;
    color: #333;
}

/* Navbar */

nav {
    
    text-align: center;
    justify-content: space-between;
    align-items: center;
    padding: 20px 595px;
    background: #222;
    position:absolute;
    top: 0;
}

.logo {
    display: center ;
    color: white;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #00adb5;
}

/* Hero Section */

.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 80px 300px;
    min-height: 100vh;
}

.hero-text h1 {
    font-size: 50px;
}

.hero-text span {
    color: #00adb5;
}

.hero-text p {
    margin: 20px 0;
    font-size: 20px;
}

.btn {
    display: inline-block;
    padding: 12px 25px;
    background: #00adb5;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover {
    background: #007b80;
}

.hero-image img {
    display: flexbox;
    justify-content: center;
    align-items: center;
    width: 350px;
    border-radius: 50%;
    box-shadow: 0 0 10px gray;
}

/* Sections */

section {
    padding: 80px 50px;
    text-align: center;
}


h2 {
    margin-bottom: 30px;
    font-size: 36px;
}

/* Skills */

.skill-box {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
}

.skill {
    background: #00adb5;
    color: white;
    padding: 15px 25px;
    border-radius: 5px;
    transition: 0.3s;
}

.skill:hover {
    transform: scale(1.1);
}

/* Projects */

.project-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.project-card {
    background: rgb(92, 203, 227);
    width: 300px;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px gray;
    transition: 0.3s;
}

.project-card:hover {
    transform: translateY(-10px);
}

/* Footer */

footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Responsive */

@media(max-width: 768px) {

    nav {
        flex-direction: column;
    }

    .hero {
        flex-direction: column;
        text-align: center;
    }

    .hero-image img {
        width: 250px;
        margin-top: 30px;
    }

    nav ul {
        margin-top: 10px;
    }
}






// Simple welcome alert

window.onload = function () {

    console.log("Portfolio Website Loaded Successfully");

};
