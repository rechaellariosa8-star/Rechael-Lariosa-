# Rechael-Lariosa-

<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Rechael | Personal Portfolio</title>

<link rel="stylesheet" href="index.css">

</head><body><!-- BACKGROUND DECORATION -->
<div class="orb orb-one"></div>
<div class="orb orb-two"></div>

<!-- NAVIGATION -->
<header class="header">

    <a href="#" class="brand" onclick="hideAll()">
        <span>R</span>
        RECHAEL
    </a>

    <nav class="navigation">

        <button onclick="showSection('home')">
            <span>⌂</span>
            Home
        </button>

        <button onclick="showSection('gallery')">
            <span>▦</span>
            Gallery
        </button>

        <button onclick="showSection('skills')">
            <span>✦</span>
            Skills
        </button>

        <button onclick="showSection('contacts')">
            <span>✉</span>
            Contact
        </button>

    </nav>

</header>


<!-- MAIN CONTENT -->
<main>

    <!-- HOME -->
    <section id="home" class="content">

        <div class="home-card">

            <div class="home-image">
                <img src="rechael.jpg" alt="Rechael O. Lariosa">
            </div>

            <div class="home-info">

                <p class="small-title">WELCOME TO MY PORTFOLIO</p>

                <h1>
                    Hello, I'm <span>Rechael.</span>
                </h1>

                <p class="description">
                    A BSIT student passionate about technology,
                    creativity, design, and learning new things.
                </p>

                <div class="student-info">

                    <div>
                        <strong>BSIT 2-E</strong>
                        <small>Program & Section</small>
                    </div>

                    <div>
                        <strong>CPSU</strong>
                        <small>My University</small>
                    </div>

                </div>

                <button class="main-button" onclick="showSection('gallery')">
                    Explore My Portfolio
                    <span>→</span>
                </button>

            </div>

        </div>

    </section>


    <!-- GALLERY -->
    <section id="gallery" class="content">

        <div class="section-header">

            <div>
                <p class="section-label">MY WORK</p>
                <h2>My Gallery</h2>
            </div>

            <p>
                A collection of my activities,
                projects, experiences, and achievements.
            </p>

        </div>


        <div class="gallery-grid">

            <article class="gallery-card">
                <img src="acrivity.jpg" alt="My Activity">

                <div class="gallery-overlay">
                    <span>01</span>
                    <h3>My Activity</h3>
                    <p>School activities and memorable moments.</p>
                </div>
            </article>


            <article class="gallery-card">
                <img src="project.jpg" alt="School Project">

                <div class="gallery-overlay">
                    <span>02</span>
                    <h3>School Project</h3>
                    <p>Projects and outputs created during my studies.</p>
                </div>
            </article>


            <article class="gallery-card">
                <img src="experience.jpg" alt="My Experience">

                <div class="gallery-overlay">
                    <span>03</span>
                    <h3>My Experience</h3>
                    <p>Experiences that helped me grow and learn.</p>
                </div>
            </article>


            <article class="gallery-card">
                <img src="certificate.jpg" alt="Certificate">

                <div class="gallery-overlay">
                    <span>04</span>
                    <h3>Certificate</h3>
                    <p>Achievements and certificates I've earned.</p>
                </div>
            </article>

        </div>

        <button class="close-button" onclick="hideAll()">
            Close Gallery
        </button>

    </section>


    <!-- SKILLS -->
    <section id="skills" class="content">

        <div class="section-header">

            <div>
                <p class="section-label">WHAT I CAN DO</p>
                <h2>My Skills</h2>
            </div>

            <p>
                Skills I continue to develop through
                practice, projects, and experience.
            </p>

        </div>


        <div class="skills-container">

            <div class="skill-card">

                <div class="skill-top">
                    <div class="skill-name">
                        <span class="skill-number">01</span>
                        <h3>HTML</h3>
                    </div>

                    <strong>90%</strong>
                </div>

                <div class="skill-bar">
                    <div class="skill-progress html"></div>
                </div>

                <p>Building structured and interactive web pages.</p>

            </div>


            <div class="skill-card">

                <div class="skill-top">
                    <div class="skill-name">
                        <span class="skill-number">02</span>
                        <h3>CSS</h3>
                    </div>

                    <strong>80%</strong>
                </div>

                <div class="skill-bar">
                    <div class="skill-progress css"></div>
                </div>

                <p>Creating clean, responsive, and modern designs.</p>

            </div>


            <div class="skill-card">

                <div class="skill-top">
                    <div class="skill-name">
                        <span class="skill-number">03</span>
                        <h3>C++</h3>
                    </div>

                    <strong>75%</strong>
                </div>

                <div class="skill-bar">
                    <div class="skill-progress cpp"></div>
                </div>

                <p>Learning programming logic and object-oriented concepts.</p>

            </div>


            <div class="skill-card">

                <div class="skill-top">
                    <div class="skill-name">
                        <span class="skill-number">04</span>
                        <h3>Java</h3>
                    </div>

                    <strong>80%</strong>
                </div>

                <div class="skill-bar">
                    <div class="skill-progress adobe"></div>
                </div>

                <p>Creative editing, design, and digital content creation.</p>

            </div>

        </div>

        <button class="close-button" onclick="hideAll()">
            Close Skills
        </button>

    </section>


    <!-- CONTACT -->
    <section id="contacts" class="content">

        <div class="section-header">

            <div>
                <p class="section-label">GET IN TOUCH</p>
                <h2>Contact Me</h2>
            </div>

            <p>
                Here are my personal and academic
                contact details.
            </p>

        </div>


        <div class="contact-grid">

            <div class="contact-card">
                <div class="contact-icon">♟</div>
                <div>
                    <span>Name</span>
                    <h3>Rechael O. Lariosa</h3>
                </div>
            </div>


            <div class="contact-card">
                <div class="contact-icon">▰</div>
                <div>
                    <span>Course</span>
                    <h3>BSIT 2-E</h3>
                </div>
            </div>


            <div class="contact-card">
                <div class="contact-icon">⚑</div>
                <div>
                    <span>School</span>
                    <h3>
                        <a href="https://www.facebook.com/profile.php?id=100081610303435"
                           target="_blank">
                            Central Philippine State University
                        </a>
                    </h3>
                </div>
            </div>


            <div class="contact-card">
                <div class="contact-icon">✉</div>
                <div>
                    <span>Email</span>
                    <h3>
                        <a href="mailto:rechaellariosa8@gmail.com">
                            rechaellariosa8@gmail.com
                        </a>
                    </h3>
                </div>
            </div>


            <div class="contact-card">
                <div class="contact-icon">ⓕ</div>
                <div>
                    <span>Facebook</span>
                    <h3>
                        <a href="https://www.facebook.com/pretty.chell0"
                           target="_blank">
                            Çhell lì
                        </a>
                    </h3>
                </div>
            </div>


            <div class="contact-card">
                <div class="contact-icon">♪</div>
                <div>
                    <span>TikTok</span>
                    <h3>
                        <a href="https://www.tiktok.com/@urprtychell"
                           target="_blank">
                            urprtychell
                        </a>
                    </h3>
                </div>
            </div>

        </div>

        <button class="close-button" onclick="hideAll()">
            Close Contacts
        </button>

    </section>

</main>


<!-- FOOTER -->
<footer>
    <div class="footer-line"></div>

    <p>© 2026 Rechael O. Lariosa</p>
    <span>MY PERSONAL PORTFOLIO</span>
</footer>


<!-- JAVASCRIPT -->
<script>

    function showSection(id) {

        const sections = document.querySelectorAll(".content");

        sections.forEach(function(section) {
            section.classList.remove("active");
        });

        const selected = document.getElementById(id);

        selected.classList.add("active");

        setTimeout(function() {
            selected.scrollIntoView({
                behavior: "smooth",
                block: "start"
            });
        }, 50);
    }


    function hideAll() {

        const sections = document.querySelectorAll(".content");

        sections.forEach(function(section) {
            section.classList.remove("active");
        });

        window.scrollTo({
            top: 0,
            behavior: "smooth"
        });
    }

</script>

</body>
</html>