<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abba James | Portfolio</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    scroll-behavior: smooth;
}

/* NAVBAR */
header {
    background: #111;
    color: white;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    position: sticky;
    top: 0;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

/* HERO */
.hero {
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(to right, #1e90ff, #00c6ff);
    color: white;
}

/* SECTIONS */
section {
    padding: 50px 20px;
}

.card {
    background: #f4f4f4;
    padding: 20px;
    margin: 10px 0;
    border-radius: 10px;
}

/* SKILLS */
.skill .bar {
    background: #ddd;
    height: 10px;
    border-radius: 5px;
}

.skill .bar div {
    height: 10px;
    background: #1e90ff;
}

/* GALLERY */
.gallery {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

.gallery img {
    width: 200px;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    transition: 0.3s;
}

.gallery img:hover {
    transform: scale(1.1);
}

/* CONTACT */
button {
    padding: 10px 20px;
    border: none;
    background: #1e90ff;
    color: white;
    cursor: pointer;
    border-radius: 5px;
}

/* FOOTER */
footer {
    text-align: center;
    background: #111;
    color: white;
    padding: 10px;
}
</style>

</head>
<body>

<!-- NAVBAR -->
<header>
    <h1>ABBA JAMES</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero">
    <h2>UI/UX Designer & Developer</h2>
    <p>Creating intuitive and visually appealing digital experiences</p>
    <button onclick="scrollToSection('contact')">Hire Me</button>
</section>

<!-- ABOUT -->
<section id="about">
    <h2>About Me</h2>
    <p>
        I am a passionate UI/UX designer and junior developer with strong interest in
        building user-friendly and visually appealing digital products.
    </p>
</section>

<!-- EXPERIENCE -->
<section id="experience">
    <h2>Experience</h2>

    <div class="card">
        <h3>Product Designer (UI/UX)</h3>
        <p>Pej Technical Complex LTD (2024 - Present)</p>
    </div>

    <div class="card">
        <h3>Data Processor</h3>
        <p>Pej Technical Complex LTD (2022 - 2023)</p>
    </div>
</section>

<!-- EDUCATION -->
<section id="education">
    <h2>Education</h2>

    <div class="card">
        <p><strong>University of Nigeria, Nsukka</strong></p>
        <p>BSc Computer Science (In View)</p>
    </div>

    <div class="card">
        <p><strong>New Vision Institute of Technology</strong></p>
        <p>Diploma in Data Processing</p>
    </div>

    <div class="card">
        <p><strong>Wesley High School</strong></p>
        <p>WAEC / NECO</p>
    </div>
</section>

<!-- SKILLS -->
<section id="skills">
    <h2>Skills</h2>

    <div class="skill">
        <p>UI/UX Design</p>
        <div class="bar"><div style="width:85%"></div></div>
    </div>

    <div class="skill">
        <p>Frontend Development</p>
        <div class="bar"><div style="width:75%"></div></div>
    </div>

    <div class="skill">
        <p>Project Management</p>
        <div class="bar"><div style="width:80%"></div></div>
    </div>
</section>

<!-- GALLERY -->
<section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
        <img src="jimmy001.jpg">
        <img src="pic2.jpg">
        <img src="pic3.jpg">
        <img src="pic4.jpg">
        <img src="pic5.jpg">
    </div>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact</h2>
    <p>ðŸ“ž +234 816 820 4205</p>
    <p>ðŸ“§ jamesabba2030@gmail.com</p>

    <button onclick="showMessage()">Send Message</button>
</section>

<footer>
    <p>Â© 2026 Abba James</p>
</footer>

<script>
function scrollToSection(id) {
    document.getElementById(id).scrollIntoView({
        behavior: "smooth"
    });
}

function showMessage() {
    alert("Thanks for reaching out! I will get back to you.");
}
</script>

</body>
</html>
