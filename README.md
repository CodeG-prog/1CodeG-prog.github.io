<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Portfolio</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="burger">
                <div class="line1"></div>
                <div class="line2"></div>
                <div class="line3"></div>
            </div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Hi, I'm a Front-end and Backend Developer</h2>
            <p>I create beautiful, responsive websites with HTML and CSS, JavaScript, Python, MySQL among others</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
        <div class="hero-image">
            <div class="profile.jpg.jpg."></div>
        </div>
    </section>

    <section id="about" class="about">
        
        <h2 class="section-title">About Me</h2>
        <div class="about-content">
            <div class="about-image">
                    <img src= "profile.jpg.jpg"  width="400" height="auto"   alt="Profile Picture">

            </div>
            <div class="about-text">
                <p>I'm a passionate frontend developer with expertise in HTML and CSS. I love creating visually appealing and user-friendly websites that provide great user experiences.</p>
                <p>When I'm not coding, you can find me hiking, reading tech blogs, or experimenting with new design trends.</p>
                <div class="about-details">
                    <div class="detail">
                        <span>Name:</span> Augustine Wekesa
                    </div>
                    <div class="detail">
                        <span>Email:</span> wekesaaugustine28@gmail.com
                    </div>
                    <div class="detail">
                        <span>Experience:</span> 1+ year
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="skills">
        <h2 class="section-title">My Skills</h2>
        <div class="skills-container">
            <div class="skill">
                <div class="skill-icon">
                    <i class="fab fa-html5"></i>
                </div>
                <h3>HTML5</h3>
                <p>Semantic markup, accessibility, SEO optimization</p>
            </div>
            <div class="skill">
                <div class="skill-icon">
                    <i class="fab fa-css3-alt"></i>
                </div>
                <h3>CSS3</h3>
                <p>Flexbox, Grid, animations, responsive design</p>
            </div>
            <div class="skill">
                <div class="skill-icon">
                    <i class="fas fa-mobile-alt"></i>
                </div>
                <h3>Responsive Design</h3>
                <p>Mobile-first approach, media queries</p>
            </div>
            <div class="skill">
                <div class="skill-icon">
                    <i class="fas fa-paint-brush"></i>
                </div>
                <h3>UI Design</h3>
                <p>Clean interfaces, user experience principles</p>
            </div>
        </div>
    </section>

    <section id="projects" class="projects">
        <h2 class="section-title">My Projects</h2>
        <div class="projects-grid">
            <div class="project-card">
                <div class="project-image">
                    <div class="image-placeholder"></div>
                </div>
                <div class="project-info">
                    <h3>E-commerce Website</h3>
                    <p>A fully responsive online store with product listings and cart functionality.</p>
                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                    </div>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <div class="image-placeholder"></div>
                </div>
                <div class="project-info">
                    <h3>Portfolio Template</h3>
                    <p>A clean, modern portfolio template for creative professionals.</p>
                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                    </div>
                </div>
            </div>
            <div class="project-card">
                <div class="project-image">
                    <div class="image-placeholder"></div>
                </div>
                <div class="project-info">
                    <h3>Restaurant Website</h3>
                    <p>An elegant website for a fine dining restaurant with menu and reservation section.</p>
                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2 class="section-title">Get In Touch</h2>
        <div class="contact-container">
            <div class="contact-info">
                <h3>Contact Information</h3>
                <p>Feel free to reach out if you're looking for a developer, have a question, or just want to connect.</p>
                <div class="info-item">
                    <i class="fas fa-envelope"></i>
                    <span>wekesaaugustine28a@gmail.com</span>
                </div>
                <div class="info-item">
                    <i class="fas fa-phone"></i>
                    <span>+254715641169</span>
                </div>
                <div class="info-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <span>Nairobi, Kenya</span>
                </div>
            </div>
            <form class="contact-form">
                <div class="form-group">
                    <input type="text" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <input type="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <input type="text" placeholder="Subject">
                </div>
                <div class="form-group">
                    <textarea placeholder="Your Message" required></textarea>
                </div>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <div class="social-links">
                <a href="https://github.com/CodeG-prog"><i class="fab fa-github"></i></a>
                <a href="https://www.linkedin.com/in/juma-augustine-3bb977100/"><i class="fab fa-linkedin"></i></a>
                <a href="https://x.com/sir_wake"><i class="fab fa-twitter"></i></a>
                <a href="https://web.facebook.com/wekesa.masibo/"><i class="fab fa-facebook"></i></a>
            </div>
            <p>&copy; Wekesa Augustine. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
