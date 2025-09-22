<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gleta</title>
  <link rel="icon" href="img/me.png" type="image/x-icon">

  <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.0/css/line.css">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header class="header" id="header">
    <nav class="nav container">
      <a href="#" class="nav_logo">Gleta</a>
      <div class="nav_menu" id="nav-menu">
        <ul class="nav_list grid">
          <li class="nav_item"><a href="#home" class="nav_link active-link"><i class="uil uil-estate nav_icon"></i> Home</a></li>
          <li class="nav_item"><a href="#about" class="nav_link"><i class="uil uil-user nav_icon"></i> About</a></li>
          <li class="nav_item"><a href="#skills" class="nav_link"><i class="uil uil-heart nav_icon"></i> Skills</a></li>
          <li class="nav_item"><a href="#services" class="nav_link"><i class="uil uil-suitcase-alt nav_icon"></i> Services</a></li>
          <li class="nav_item"><a href="#portfolio" class="nav_link"><i class="uil uil-scenery nav_icon"></i> Portfolio</a></li>
          <li class="nav_item"><a href="mailto:nevillemwimah12@gmail.com" class="nav_link"><i class="uil uil-location-arrow nav_icon"></i> Contact</a></li>
        </ul>
        <i class="uil uil-multiply nav_close" id="nav-close"></i>
      </div>
      <div class="nav_btns">
        <i class="uil uil-moon change-theme" id="theme-button"></i>
        <div class="nav_toggle" id="nav-toggle"><i class="uil uil-apps"></i></div>
      </div>
    </nav>
  </header>

  <main class="main">
    <section class="home section" id="home">
      <div class="home_container container grid">
        <div class="home_content grid">
          <div class="home_social">
            <a href="https://github.com/Gleta-K" target="_blank" class="home_social-icon"><i class="uil uil-github-alt"></i></a>
            <a href="https://www.linkedin.com/in/gleta-kijogi/" target="_blank" class="home_social-icon"><i class="uil uil-linkedin-alt"></i></a>
            <a href="https://x.com/Gleta_K" target="_blank" class="home_social-icon"><i class="uil uil-twitter-alt"></i></a>
          </div>
          <div class="home_img"><img src="img/me2.png" alt="home_img"></div>
          <div class="home_data">
            <h1 class="home_title">Hi, I am Gleta</h1>
            <h3 class="home_subtitle">Software Engineer</h3>
            <p class="home_description">I merge problem-solving and storytelling to create software that connects with people in meaningful ways.</p>
            <a href="#contact" class="button button--flex">Hire Me <i class="uil uil-message button_icon"></i></a>
          </div>
        </div>
        <div class="home_scroll">
          <a href="#about" class="home_scroll-button button--flex"><i class="uil uil-mouse-alt home_scroll-mouse"></i><span class="home_scroll-name">Scroll down</span><i class="uil uil-arrow-down home_scroll-arrow"></i></a>
        </div>
      </div>
    </section>

    <section class="about section" id="about">
      <h2 class="section_title">About Me</h2>
      <span class="section_subtitle">My Introduction</span>
      <div class="about_container container grid">
        <img src="img/about2.png" alt="" class="about_img">
        <div class="about_data">
          <p class="about_description">Hello,
I am Gleta Kijogi, a storyteller, YouTuber, and aspiring backend web developer currently studying Mathematics and Computer Science. I am also enrolled in a bootcamp where I’m developing both my technical and soft skills, gaining hands-on experience in backend development.
What makes me unique is my ability to merge two worlds that often seem far apart; creativity and technology. Whether through engaging YouTube content or coding scalable systems, I bring together imagination, logic, and problem solving to create meaningful work.
My passions lie in storytelling, culture, and technology. Through storytelling, I connect with people, spark dialogue, and explore human experiences in ways that are both entertaining and thought provoking. Through technology, I channel that same creativity into building impactful digital platforms that support expression, preserve culture, and inspire communities.
Backend web development enables me to live out this passion by giving me the tools to design reliable, innovative systems that power creative platforms. In this way, I can bridge my love for art and science, using both to inspire, educate, and create change.
</p>
        </div>
      </div>
    </section>

    <section class="skills section" id="skills">
      <h2 class="section_title">Skills</h2>
      <span class="section_subtitle">My Technical Level</span>
      <div class="skills_container container grid">
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-brackets-curly skills_icon"></i>
            <div><h1 class="skills_title">System Design & Scalability</h1><span class="skills_subtitle">Building hands-on experience through projects that showcase technical growth.</span></div>
          </div>
        </div>
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-server-connection skills_icon"></i>
            <div><h1 class="skills_title">Backend Development</h1><span class="skills_subtitle">Strengthening my foundation with projects, coursework, and continuous learning.</span></div>
          </div>
        </div>
      </div>
      <span class="section_subtitle">My Creative Level</span>
      <div class="skills_container container grid">
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-palette skills_icon"></i>
            <div><h1 class="skills_title">Storytelling</h1><span class="skills_subtitle">Crafting narratives that make technology more relatable and engaging.</span></div>
          </div>
        </div>
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-video skills_icon"></i>
            <div><h1 class="skills_title">Content Creation</h1><span class="skills_subtitle">Designing digital content that blends creativity with technology.</span></div>
          </div>
        </div>
      </div>
      <span class="section_subtitle">My Soft Skills Level</span>
      <div class="skills_container container grid">
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-shield-check skills_icon"></i>
            <div><h1 class="skills_title">Resilience</h1><span class="skills_subtitle">Adapting to challenges and pushing through obstacles with determination.</span></div>
          </div>
        </div>
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-pen skills_icon"></i>
            <div><h1 class="skills_title">Creativity</h1><span class="skills_subtitle">Bringing fresh perspectives and innovative solutions to problems.</span></div>
          </div>
        </div>
        <div class="skills_content skills_close">
          <div class="skills_header"><i class="uil uil-chart-line skills_icon"></i>
            <div><h1 class="skills_title">Analytical Thinking</h1><span class="skills_subtitle">Breaking down complex issues to create clear, effective solutions.</span></div>
          </div>
        </div>
      </div>
    </section>

    <section class="qualification section">
      <h2 class="section_title">Qualification</h2>
      <span class="section_subtitle">My Personal Journey</span>
      <div class="qualification_container container">
        <div class="qualification_tabs">
          <div class="qualification_button button--flex qualification_active" data-target="#education"><i class="uil uil-graduation-cap qualification_icon"></i> Education</div>
          <div class="qualification_button button--flex" data-target="#work"><i class="uil uil-suitcase qualification_icon"></i> Work</div>
        </div>
        <div class="qualification_sections">
          <div class="qualification_content qualification_active" data-content id="education">
            <div class="qualification_data">
              <div></div>
              <div><span class="qualification_rounder"></span><span class="qualification_line"></span></div>
              <div><h3 class="qualification_title">BSc Mathematics & Computer Science</h3><span class="qualification_subtitle">JKUAT</span><div class="qualification_calendar"><i class="uil uil-schedule"></i> 2023 - 2027</div></div>
            </div>
            <div class="qualification_data">
              <div><h3 class="qualification_title">Backend Web Development</h3><span class="qualification_subtitle">ALX School</span><div class="qualification_calendar"><i class="uil uil-schedule"></i> June 2025 - Ongoing</div></div>
              <div><span class="qualification_rounder"></span><span class="qualification_line"></span></div>
            </div>
          </div>
          <div class="qualification_content" data-content id="work">
            <div class="qualification_data">
              <div><h3 class="qualification_title">Academic Projects</h3><span class="qualification_subtitle">Personal & University</span><div class="qualification_calendar"><i class="uil uil-schedule"></i> 2023 - Present</div></div>
              <div><span class="qualification_rounder"></span></div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="services section" id="services">
      <h2 class="section_title">Services</h2>
      <span class="section_subtitle">What I Offer</span>
      <div class="services_container container grid">
        <div class="services_content">
          <div><i class="uil uil-web-grid services_icon"></i><h3 class="services_title">Back end Web Development</h3></div>
        </div>
        <div class="services_content">
          <div><i class="uil uil-pen services_icon"></i><h3 class="services_title">Programming</h3></div>
        </div>
        <div class="services_content">
          <div><i class="uil uil-lightbulb services_icon"></i><h3 class="services_title">Creative Storytelling</h3></div>
        </div>
      </div>
    </section>

     <!--==================== PORTFOLIO ====================-->
        <section class="portfolio section " id="portfolio">
            <h2 class="section_title">Portfolio</h2>
            <span class="section_subtitle">Most recent work</span>
        
            <div class="portfolio_container container swiper-container">
                <div class="swiper-wrapper">
                    <!--==================== PORTFOLIO 1 ====================
                    <div class="portfolio_content grid swiper-slide">
                        <img src="img/project2.png" alt="" class="portfolio_img">
        
                        <div class="portfolio_data">
                            <h3 class="portfolio_title">Edunique Transformation</h3>
                            <p class="portfolio_description">
                                Website adaptable to all devices, with modern and clean design.
                            </p>
                            <a href="https://eduniquetransform.org/" target="_blank" class="button button--flex button--small portfolio_button">
                                View
                                <i class="uil uil-eye button_icon"></i>
                            </a>
                        </div>
                    </div>
        
                </div>
        
            </div>
        </section>-->
        
            <div class="portfolio_container container swiper-container">
                <div class="swiper-wrapper">
                    <!--==================== PORTFOLIO 2 ====================-->
                    <div class="portfolio_content grid swiper-slide">
                        <img src="img/mca.png" alt="" class="portfolio_img">
        
                        <div class="portfolio_data">
                            <h3 class="portfolio_title">The Mobile Camp App</h3>
                            <p class="portfolio_description">
                                n rural Kenyan primary schools, many children in Grades 1–6 struggle to acquire essential reading skills under the Competency-Based Curriculum (CBC). This learning gap places them at risk of long-term academic failure, poverty, and limited future opportunities. To address this challenge, my team and I developed an app that helps students learn in an engaging, interactive way while nurturing qualities such as grit and resilience; the mobile camp app. 
                            </p>
                            <a href="https://youtu.be/OZed_8KeF9Q?si=wRpYuXQbeDzeRl29" target="_blank" class="button button--flex button--small portfolio_button">
                                View
                                <i class="uil uil-eye button_icon"></i>
                            </a>
                        </div>
                    </div>
        
                </div>
        
            </div>
        </section> <br>
        
            <div class="portfolio_container container swiper-container">
                <div class="swiper-wrapper">
                    <!--==================== PORTFOLIO 3 ====================-->
                    <div class="portfolio_content grid swiper-slide">
                        <img src="img/lilmaina.png" alt="" class="portfolio_img">
        
                        <div class="portfolio_data">
                            <h3 class="portfolio_title">Under the Spotlight (Ep 1)</h3>
                            <p class="portfolio_description">
                                This is an animated series narrated in my own voice, where I share other people’s stories in a radio-style storytelling format. The episodes unfold like video biographies, blending entertainment with meaningful life lessons.
                            </p>
                            <a href="https://youtu.be/nwFJH0GqRS4?si=aLSzPA_WNHDd22JR" target="_blank" class="button button--flex button--small portfolio_button">
                                View
                                <i class="uil uil-eye button_icon"></i>
                            </a>
                        </div>
                    </div>
        
                </div>
        
            </div>
        </section>

    <section class="project section">
      <div class="project_bg">
        <div class="project_container container grid">
          <div class="project_data">
            <h2 class="project_title">Impressed? Let's talk.</h2>
            <p class="project_description">An interesting idea for a project that you have or just a quick hello
            </p>
            <a href="#contact" class="button button--flex button--white">Contact Me <i class="uil uil-message project_icon button_icon"></i></a>
          </div>
        </div>
      </div>
    </section>

    <section class="contact section " id="contact">
            <h2 class="section_title">Contact Me</h2>
            <span class="section_subtitle">Get in touch</span>
        
            <div class="contact_container container grid">
                <div>
                    <div class="contact_info">
                        <i class="uil uil-phone contact_icon"></i>
                        <div>
                            <h3 class="contact_title">Call Me</h3>
                            <span class="contact_subtitle">N/A</span>
                        </div>
                    </div>
                    <div class="contact_info">
                        <i class="uil uil-envelope contact_icon"></i>
                        <div>
                            <h3 class="contact_title">Email</h3>
                            <span class="contact_subtitle">gkkijogi@gmail.com</span>
                        </div>
                    </div>
                    <div class="contact_info">
                        <i class="uil uil-map-marker contact_icon"></i>
                        <div>
                            <h3 class="contact_title">Location</h3>
                            <span class="contact_subtitle">Nairobi, Kenya</span>
                        </div>
                    </div>
                </div>
                <form action="" class="contact_form grid">
                    <div class="contact_inputs grid">
                        <div class="contact_content">
                            <label for="" class="contact_label">
                                Name
                            </label>
                            <input type="text" class="contact_input">
                        </div>
                        <div class="contact_content">
                            <label for="" class="contact_label">
                                Email
                            </label>
                            <input type="email" class="contact_input">
                        </div>
        
                    </div>
                    <div class="contact_content">
                        <label for="" class="contact_label">
                            Project
                        </label>
                        <input type="text" class="contact_input">
                    </div>
                    <div class="contact_content">
                        <label for="" class="contact_label">
                            Message
                        </label>
                        <textarea name="" id="" cols="0" rows="7" class="contact_input"></textarea>
                    </div>
                    <div>
                        <a href="#" class="button button--flex">
                            Send Message
                            <i class="uil uil-message button_icon"></i>
                        </a>
                    </div>
                </form>
            </div>
        </section>

    </main>

    <!--==================== FOOTER ====================-->
    <footer class="footer ">
        <div class="footer_bg">
            <div class="footer_container container grid">
                <div>
                    <h1 class="footer_title">Gleta</h1>
                    <span class="footer_subtitle">Software Engineer</span>
                </div>
                <ul class="footer_links">
                    <li>
                        <a href="#services" class="footer_link">Services</a>
                    </li>
                    <li>
                        <a href="#portfolio" class="footer_link">Portfolio</a>
                    </li>
                    <li>
                        <a href="#contact" class="footer_link">Contact</a>
                    </li>
                </ul>
                <div class="footer_socials">
                    <a href="" target="_blank" class="footer_social">
                        <i class="uil uil-github-alt"></i>
                    </a>
                    <a href="https://www.linkedin.com/in/gleta-kijogi/" target="_blank" class="footer_social">
                        <i class="uil uil-linkedin-alt"></i>
                    </a>
                    <a href="#" target="_blank" class="footer_social">
                        <i class="uil uil-twitter-alt"></i>
                    </a>
                </div>
            </div>
            <p class="footer_copy">&#169; 2025 <a class="footerd" href="https://www.instagram.com/gleta_k/">Gleta</a></p>
        </div>
    
    </footer>
    
    <!--==================== SCROLL TOP ====================-->
    <a href="#" class="scrollup" id="scroll-up">
        <i class="uil uil-arrow-up scrollup_icon"></i>
    </a>
    
</body>
</html>

<script src="app.js"></script>
