<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sourya Kumar - Journey into Technology</title>
  <!-- Font Awesome for icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    /* ----------------------- Global Styles ----------------------- */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background-color: #f0f0f0;
      color: #333;
      line-height: 1.8;
    }
    nav {
      background-color: #444;
      text-align: center;
      padding: 15px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-size: 18px;
      transition: color 0.3s ease, transform 0.3s ease;
    }
    nav a:hover {
      color: #ffd700;
      transform: scale(1.1);
    }
    header {
      background: url('header_bg.jpg') no-repeat center center/cover;
      background-image: linear-gradient(to bottom right, #333, #555);
      color: white;
      padding: 30px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
    header h1 {
      font-size: 2.5rem;
    }
    section {
      padding: 30px;
      margin: 30px auto;
      max-width: 900px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
    }
    h2 {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #333;
      font-size: 28px;
      margin-bottom: 20px;
    }
    p {
      font-size: 16px;
      margin: 15px 0;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      margin: 20px auto;
      display: block;
    }
    ul {
      list-style: none;
      padding: 0;
      text-align: center;
    }
    ul li {
      display: inline-block;
      background-color: #f7f7f7;
      color: #333;
      padding: 10px 20px;
      margin: 10px;
      border-radius: 20px;
      font-size: 16px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    /* Projects section */
    .project {
      margin-bottom: 30px;
    }
    .project img {
      transition: transform 0.3s ease;
    }
    .project img:hover {
      transform: scale(1.05);
    }
    .project-description {
      font-size: 15px;
      color: #666;
    }
    /* ----------------------- Enhanced Contact Section ----------------------- */
    /* This section uses a dark background with a two-column grid layout */
    #contact.enhanced {
      background: linear-gradient(135deg, #1a1a1a, #2d2d2d);
      color: #fff;
      padding: 60px 20px;
      text-align: center;
    }
    #contact.enhanced .contact-container {
      max-width: 800px;
      margin: 0 auto;
    }
    #contact.enhanced h2 {
      margin-bottom: 40px;
      font-size: 2.5rem;
    }
    #contact.enhanced .contact-content {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
      align-items: center;
      padding: 20px;
    }
    /* Image column */
    #contact.enhanced .contact-image img {
      width: 100%;
      border-radius: 15px;
      transition: transform 0.3s ease;
    }
    #contact.enhanced .contact-image img:hover {
      transform: scale(1.05);
    }
    #contact.enhanced .contact-image p {
      font-size: 0.9rem;
      margin-top: 10px;
      color: #aaa;
    }
    /* Details column */
    #contact.enhanced .contact-details {
      display: flex;
      flex-direction: column;
      gap: 20px;
      text-align: left;
    }
    #contact.enhanced .contact-details p {
      font-size: 1.1rem;
    }
    /* Social media */
    #contact.enhanced .social-media {
      margin-top: 20px;
    }
    #contact.enhanced .social-media h3 {
      margin-bottom: 15px;
      font-size: 1.5rem;
    }
    #contact.enhanced .social-icons {
      display: flex;
      gap: 20px;
      justify-content: flex-start;
    }
    #contact.enhanced .social-icons a {
      color: #fff;
      font-size: 2rem;
      transition: transform 0.3s ease;
      position: relative;
      text-decoration: none;
    }
    #contact.enhanced .social-icons a:hover {
      transform: translateY(-5px);
    }
    #contact.enhanced .social-icons a::after {
      content: attr(data-platform);
      position: absolute;
      bottom: -25px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 0.9rem;
      opacity: 0;
      transition: opacity 0.3s ease;
    }
    #contact.enhanced .social-icons a:hover::after {
      opacity: 1;
    }
    /* Specific social icon colors */
    #contact.enhanced .fa-instagram { color: #e1306c; }
    #contact.enhanced .fa-twitter   { color: #1da1f2; }
    #contact.enhanced .fa-youtube   { color: #ff0000; }
    /* Contact form */
    #contact.enhanced .contact-form {
      margin-top: 30px;
      background: rgba(255, 255, 255, 0.1);
      padding: 30px;
      border-radius: 10px;
    }
    #contact.enhanced .contact-form h3 {
      margin-bottom: 20px;
      font-size: 1.8rem;
      text-align: center;
    }
    #contact.enhanced .contact-form input,
    #contact.enhanced .contact-form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 15px;
      border: none;
      border-radius: 5px;
      background: rgba(255, 255, 255, 0.2);
      color: #fff;
      font-size: 1rem;
    }
    #contact.enhanced .contact-form input:focus,
    #contact.enhanced .contact-form textarea:focus {
      outline: 2px solid #00ff88;
      background: rgba(255, 255, 255, 0.15);
    }
    #contact.enhanced .contact-form button {
      background: #00ff88;
      color: #1a1a1a;
      padding: 12px 25px;
      border: none;
      border-radius: 25px;
      font-size: 1.1rem;
      cursor: pointer;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      width: 100%;
      display: block;
    }
    #contact.enhanced .contact-form button:hover {
      transform: scale(1.05);
      box-shadow: 0 4px 15px rgba(0, 255, 136, 0.4);
    }
    /* ----------------------- Media Queries ----------------------- */
    @media only screen and (max-width: 768px) {
      body {
        font-size: 16px;
      }
      header {
        font-size: 24px;
        padding: 20px 10px;
      }
      nav {
        padding: 10px 0;
      }
      nav a {
        margin: 0 10px;
        font-size: 16px;
      }
      section {
        padding: 20px;
        margin: 10px;
      }
      ul li {
        padding: 8px 16px;
        margin: 8px;
        font-size: 14px;
      }
      .project-description {
        font-size: 14px;
      }
      /* Adjust enhanced contact section */
      #contact.enhanced .contact-content {
        grid-template-columns: 1fr;
      }
      #contact.enhanced .contact-details {
        text-align: center;
      }
      #contact.enhanced .social-icons {
        justify-content: center;
      }
    }
  </style>
</head>
<body>
  <!-- Navigation -->
  <nav>
    <a href="#" onclick="scrollToSection('coding-skills')">Skills &amp; Technologies</a>
    <a href="#" onclick="scrollToSection('interests')">My Interests</a>
    <a href="#" onclick="scrollToSection('contact')">Get in Touch</a>
    <a href="#" onclick="scrollToSection('projects')">Projects</a>
  </nav>

  <!-- Header -->
  <header>
    <h1>Step into the Uncharted Territory</h1>
  </header>

  <!-- Skills & Technologies Section -->
  <section id="coding-skills">
    <h2>Skills &amp; Technologies</h2>
    <img src="coding_skills.jpg" alt="Coding Skills">
    <ul id="coding-skills-list"></ul>
    <p>Step into the realm of technology where creativity meets innovation. With proficiency in various programming languages and tools, I'm ready to turn ideas into reality.</p>
  </section>

  <!-- Interests Section -->
  <section id="interests">
    <h2>My Interests</h2>
    <img src="interests.jpg" alt="Interests">
    <p>Outside the world of coding, I find solace in exploring various interests. Whether it's diving into the world of literature or exploring the depths of the cosmos, there's always something new to discover.</p>
  </section>

  <!-- Enhanced Contact Section -->
  <section id="contact" class="enhanced">
    <div class="contact-container">
      <h2>Let's Connect &amp; Create</h2>
      <div class="contact-content">
        <!-- Left Column: Illustration -->
        <div class="contact-image">
          <img src="https://undraw.co/illustration/contact-us_kcoa.svg" 
               alt="Contact Us Illustration by unDraw" loading="lazy">
          <p>Contact Us Illustration by unDraw</p>
        </div>
        <!-- Right Column: Details & Form -->
        <div class="contact-details">
          <p>Have a project idea or just want to chat about tech? I'm always open to exciting collaborations and new ideas. Drop me a message and let's make something amazing!</p>
          <!-- Social Media -->
          <div class="social-media">
            <h3>Find Me Online</h3>
            <div class="social-icons">
              <a href="https://instagram.com/yourprofile" target="_blank" data-platform="Instagram">
                <i class="fab fa-instagram"></i>
              </a>
              <a href="https://twitter.com/yourprofile" target="_blank" data-platform="Twitter">
                <i class="fab fa-twitter"></i>
              </a>
              <a href="https://youtube.com/yourchannel" target="_blank" data-platform="YouTube">
                <i class="fab fa-youtube"></i>
              </a>
            </div>
          </div>
          <!-- Contact Form -->
          <div class="contact-form">
            <h3>Send a Direct Message</h3>
            <form id="messageForm">
              <input type="text" name="name" placeholder="Your Name" required>
              <input type="email" name="email" placeholder="Your Email" required>
              <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
              <button type="submit">Send Message 🚀</button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <h3>IT WILL BE UPDATED SOON...</h3>
    <img src="projects.jpg" alt="Projects Showcase">
    <div id="projects-list"></div>
    <p>Explore some of my recent projects that showcase my skills and passion for technology. Each project is a journey in itself, filled with challenges and triumphs.</p>
  </section>

  <script>
    // Data arrays
    const codingSkills = ['Java', 'HTML', 'CSS', 'Python', 'C++'];
    const projects = [
      { name: 'Project 1', image: 'project1.jpg', description: 'Description of Project 1' },
      { name: 'Project 2', image: 'project2.jpg', description: 'Description of Project 2' }
    ];

    // Populate the coding skills list
    function populateCodingSkills() {
      const skillsList = document.getElementById('coding-skills-list');
      codingSkills.forEach(skill => {
        const li = document.createElement('li');
        li.textContent = skill;
        skillsList.appendChild(li);
      });
    }

    // Populate the projects section
    function populateProjects() {
      const projectsList = document.getElementById('projects-list');
      projects.forEach(project => {
        const projectDiv = document.createElement('div');
        projectDiv.classList.add('project');

        const img = document.createElement('img');
        img.src = project.image;
        img.alt = project.name;
        projectDiv.appendChild(img);

        const desc = document.createElement('p');
        desc.classList.add('project-description');
        desc.textContent = project.description;
        projectDiv.appendChild(desc);

        projectsList.appendChild(projectDiv);
      });
    }

    // Smooth scroll to section
    function scrollToSection(sectionId) {
      const section = document.getElementById(sectionId);
      section.scrollIntoView({ behavior: 'smooth' });
    }

    // Handle contact form submission
    document.getElementById('messageForm').addEventListener('submit', function(e) {
      e.preventDefault();
      alert("Message sent successfully! I'll respond within 24 hours.");
      this.reset();
    });

    window.onload = function() {
      populateCodingSkills();
      populateProjects();
    };
  </script>
</body>
</html>
