
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya Dev | Portfolio</title>
    <meta name="description" content="Aditya Dev's personal portfolio website. BCA student and aspiring web developer.">

    <link rel="stylesheet" href="style.css">

    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <!-- Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
</head>

<body>

    <!-- Navigation -->
    <header>
        <nav class="navbar container">
            <a href="#home" class="logo">Aditya<span>.</span></a>

            <button class="menu-toggle" id="menu-toggle"
                    aria-label="Toggle navigation" aria-expanded="false">
                <i class="fas fa-bars"></i>
            </button>

            <ul class="nav-links" id="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section class="hero container" id="home">
            <div class="hero-content">
                <p class="intro">HELLO, I'M</p>

                <h1>Aditya <span>Dev</span></h1>

                <h2>BCA Student &amp; <span>Web Developer</span></h2>

                <p class="hero-description">
                    I am a passionate student interested in web development,
                    technology and creating creative digital experiences.
                </p>

                <div class="hero-buttons">
                    <a href="#projects" class="btn primary-btn">
                        View My Work <i class="fas fa-arrow-right"></i>
                    </a>

                    <a href="#contact" class="btn secondary-btn">
                        Contact Me
                    </a>
                </div>

                <div class="social-links">
                    <a href="https://github.com/YOUR_USERNAME"
                       target="_blank" rel="noopener noreferrer"
                       aria-label="GitHub">
                        <i class="fab fa-github"></i>
                    </a>

                    <a href="https://www.instagram.com/YOUR_INSTAGRAM/"
                       target="_blank" rel="noopener noreferrer"
                       aria-label="Instagram">
                        <i class="fab fa-instagram"></i>
                    </a>

                    <a href="mailto:devv9v@gmail.com"
                       aria-label="Email">
                        <i class="fas fa-envelope"></i>
                    </a>
                </div>
            </div>

            <div class="hero-image">
                <!-- Replace profile.jpg with your own photo -->
                <img src="profile.jpg" alt="Aditya Dev profile picture"
                     onerror="this.style.display='none'; this.nextElementSibling.style.display='flex';">

                <div class="profile-placeholder">
                    <i class="fas fa-user"></i>
                    <span>Add Your Photo</span>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section class="section container" id="about">
            <div class="section-heading">
                <p class="section-label">GET TO KNOW ME</p>
                <h2>About <span>Me</span></h2>
            </div>

            <div class="about-card">
                <p>
                    Hi! I'm Aditya Dev, a Bachelor of Computer Applications
                    (BCA) student at GEMS Arts and Science College.
                    I completed my higher secondary education at
                    PPMHSS Kottukkara.
                </p>

                <p>
                    I enjoy learning new technologies, improving my
                    programming skills and building websites. My goal is
                    to become a skilled developer and work on meaningful
                    projects.
                </p>

                <div class="about-details">
                    <div>
                        <i class="fas fa-graduation-cap"></i>
                        <span><strong>Course:</strong> BCA</span>
                    </div>

                    <div>
                        <i class="fas fa-university"></i>
                        <span><strong>College:</strong> GEMS Arts and Science College</span>
                    </div>

                    <div>
                        <i class="fas fa-code"></i>
                        <span><strong>Interest:</strong> Web Development</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section class="section container" id="skills">
            <div class="section-heading">
                <p class="section-label">WHAT I AM LEARNING</p>
                <h2>My <span>Skills</span></h2>
            </div>

            <div class="skills-grid">
                <div class="skill-card">
                    <i class="fab fa-html5"></i>
                    <h3>HTML5</h3>
                    <p>Web page structure</p>
                </div>

                <div class="skill-card">
                    <i class="fab fa-css3-alt"></i>
                    <h3>CSS3</h3>
                    <p>Web design and styling</p>
                </div>

                <div class="skill-card">
                    <i class="fab fa-js"></i>
                    <h3>JavaScript</h3>
                    <p>Interactive websites</p>
                </div>

                <div class="skill-card">
                    <i class="fas fa-database"></i>
                    <h3>MySQL</h3>
                    <p>Database fundamentals</p>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section class="section container" id="projects">
            <div class="section-heading">
                <p class="section-label">MY RECENT WORK</p>
                <h2>My <span>Projects</span></h2>
            </div>

            <div class="projects-grid">
                <article class="project-card">
                    <div class="project-icon">
                        <i class="fas fa-globe"></i>
                    </div>

                    <h3>Personal Portfolio</h3>
                    <p>
                        A responsive personal website to introduce myself,
                        showcase my skills and share my projects.
                    </p>

                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                        <span>JavaScript</span>
                    </div>

                    <a href="https://github.com/YOUR_USERNAME"
                       target="_blank" rel="noopener noreferrer">
                        View Project <i class="fas fa-arrow-right"></i>
                    </a>
                </article>

                <article class="project-card">
                    <div class="project-icon">
                        <i class="fas fa-book"></i>
                    </div>

                    <h3>Library Management System</h3>
                    <p>
                        A student project concept for managing books,
                        student records and library transactions.
                    </p>

                    <div class="project-tags">
                        <span>C</span>
                        <span>File Handling</span>
                    </div>

                    <a href="https://github.com/YOUR_USERNAME"
                       target="_blank" rel="noopener noreferrer">
                        View Project <i class="fas fa-arrow-right"></i>
                    </a>
                </article>

                <article class="project-card">
                    <div class="project-icon">
                        <i class="fas fa-laptop-code"></i>
                    </div>

                    <h3>More Projects</h3>
                    <p>
                        I am continuously learning and working on new
                        projects to improve my programming skills.
                    </p>

                    <div class="project-tags">
                        <span>Learning</span>
                        <span>Development</span>
                    </div>

                    <a href="https://github.com/YOUR_USERNAME"
                       target="_blank" rel="noopener noreferrer">
                        My GitHub <i class="fas fa-arrow-right"></i>
                    </a>
                </article>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="section container" id="contact">
            <div class="section-heading">
                <p class="section-label">LET'S CONNECT</p>
                <h2>Contact <span>Me</span></h2>
            </div>

            <div class="contact-card">
                <p>
                    Have a project idea or want to connect?
                    Feel free to contact me.
                </p>

                <a href="mailto:devv9v@gmail.com" class="contact-item">
                    <i class="fas fa-envelope"></i>
                    devv9v@gmail.com
                </a>

                <a href="https://github.com/YOUR_USERNAME"
                   target="_blank" rel="noopener noreferrer"
                   class="contact-item">
                    <i class="fab fa-github"></i>
                    GitHub Profile
                </a>

                <a href="https://www.instagram.com/YOUR_INSTAGRAM/"
                   target="_blank" rel="noopener noreferrer"
                   class="contact-item">
                    <i class="fab fa-instagram"></i>
                    Instagram Profile
                </a>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>
            © <span id="year"></span> Aditya Dev.
            Designed with <i class="fas fa-heart"></i> and code.
        </p>
    </footer>

    <button id="back-to-top" aria-label="Back to top">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script src="script.js"></script>
</body>
</html>
