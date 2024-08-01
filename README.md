
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yash Soni</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="media-queries.css">
</head>
<body>
    <nav id="desktop-nav">
        <div class="logo" >Yash Soni</div>
        <div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>    
            </ul>
        </div>
    </nav>
    <nav id="hamburger-nav">
        <div class="logo">Yash Soni</div>
        <div class="hamburger-menu">
            <div class="hamburger-icon" onclick="toggleMenu()">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="menu-links">
                <li><a href="#about" onclick="toggleMenu()">About</a></li>
                <li><a href="#skills" onclick="toggleMenu()">Skills</a></li>
                <li><a href="#projects" onclick="toggleMenu()">Projects</a></li>
                <li><a href="#contact" onclick="toggleMenu()">Contact</a></li>
            </div>
        </div>
    </nav>    
    <section id="profile">
        <div class="section__pic-container">
            <img src="398219326_744406450844807_1494331837746073535_n-modified.png" alt="Ashutosh Pandey profile picture">
        </div>
        <div class="section__text">
            <p class="section__text__p1">Hello I'm</p>
            <h1 class="title">Yash Soni</h1>
            <p class="section__text__p2", style="margin-bottom: 20px;">Aspiring Software Engineer</p>
            <div class="btn-container">
                <button class="btn btn-color-2" onclick="window.open('./assets/Ashutosh_CV.pdf')">Download CV</button>
                <button class="btn btn-color-2" onclick="location.href='./#contact'">Contact Me</button>
            </div>
            <div id="socials-container">
                <img src="linkedin.png" alt="My linkedin profile" class="icon" onclick="location.href='https://www.linkedin.com/in/ashup/'">
                <img src="github.png" alt="My Github profile" class="icon" onclick="location.href='https://github.com/ashup227'">
                <img src="x_icon.png" alt="My Twitter profile" class="icon" onclick="location.href='https://x.com/_aa_shu_tosh_'">
                <img src="insta1.png" alt="My Instagram profile" class="icon" onclick="location.href='https://www.instagram.com/_aa_shu_tosh_'">
            </div>
        </div>
        <img src="arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='#about'">
    </section>
    <section id="about">
        <div class="about-header">
            <p class="section__text__p1">Get To Know More</p>
            <h1 class="title">About Me</h1>
        </div>
        <div class="section-container">
            <div class="section__pic-container">
                <img src="1665399326218.jpeg" alt="Profile picture" class="about-pic">
            </div>
            <div class="about-details-container">
                <div class="about-containers">
                    <div class="details-container">
                        <img src="experience.png" alt="Experience icon" class="icon">
                        <h3>Experience</h3>
                        <p>1+ year<br>AI and Machine Learning</p>
                    </div>
                    <div class="details-container">
                        <img src="education.png" alt="Education icon" class="icon">
                        <h3>Education</h3>
                        <p>Diploma in Mechanical Engineering<br>B.tech in Computer Science and Engineering</p>
                    </div>
                </div>
                <div class="text-container">
                    <p>I am a passionate developer with a keen interest in Machine Learning and a strong foundation in both frontend and backend technologies. My technical skills include HTML, CSS, JavaScript, React, Python, Java, MongoDB, MySQL, and a solid understanding of Data Structures. I thrive on turning ideas into reality through code and am committed to continuous learning and staying updated with the latest industry trends.</p>
                </div>
            </div>
        </div>
        <img src="arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='#skills'">
    </section>        
    <section id="skills">
        <p class="section__text__p1">Explore My</p>
        <h1 class="title">Skills</h1>
        <div class="skills-details-container">
            <div class="about-containers">
                <div class="details-container">
                    <div class="article-container">
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>HTML</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>CSS</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>JavaScript</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>React</h2>
                            </div>
                        </article>
                        <!-- <article>
                            <img src="./assets/checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Tailwind CSS</h2>
                            </div>
                        </article> -->
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Node.js</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Express.js</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>MongoDB</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Java</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Python</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>MySQL</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Docker</h2>
                            </div>
                        </article>
                        <article>
                            <img src="checkmark.png" alt="Skills icon" class="icon">
                            <div>
                                <h2>Git & Github</h2>
                            </div>
                        </article>
                    </div>
                </div>
            </div>
        </div>
        <img src="arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='#projects'">
    </section>
    <section id="projects">
        <p class="section__text__p1">Have A Look On My</p>
        <h1 class="title">Projects</h1>
        <div class="projects-details-container">
            <div class="about-containers">
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assets/ML-Water.png" alt="Project 1" class="project-img">
                </div>
                <h2 class="projects-sub-title project-title">Water Well Predictor</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 project-btn" onclick="location.href='https://github.com/ashup227/AI_Enabled_Water_Well_Predictor'">Github</button>
                </div>
            </div>
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assets/Portfolio.png" alt="Project 2" class="project-img">
                </div>
                <h2 class="projects-sub-title project-title">My Portfolio</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 project-btn" onclick="location.href='https://github.com/ashup227/html-css-js-portfolio'">Github</button>
                </div>
            </div>
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assets/S-Calci.png" alt="Project 3" class="project-img">
                </div>
                <h2 class="projects-sub-title project-title">Scientific Calculator</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 project-btn" onclick="location.href='https://github.com/ashup227/Scientific-Calculator'">Github</button>
                </div>
            </div></div>
        </div>
        <img src="arrow.png" alt="Arrow icon" class="icon arrow" onclick="location.href='#contact'">
    </section>
    <section id="contact">
        
        <h1 class="title">Contact Me</h1>
        <div class="contact-form-container">
            <form action="https://formspree.io/f/xzzpzara" method="POST">
                <div class="form-group">
                    <input type="text" id="name" name="name" placeholder="Name" required>
                </div>
                <div class="form-group">
                    <input type="email" id="email" name="email" placeholder="Email" required>
                </div>
                <div class="form-group">
                    <textarea id="message" name="message" rows="4" placeholder="Message" required></textarea>
                </div>
                <div class="btn-container">
                    <button type="submit" class="btn btn-color-2">Submit</button>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <nav>
            <div class="nav-links-container">
                <ul class="nav-links">
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>    
                </ul>
            </div>
        </nav>
        <p>Copyright © 2024 Yash Soni. All rights reserved.</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
