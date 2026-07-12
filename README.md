<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samuel Nkanta | Portfolio</title>
    <style>
      :root {
        --bg: #0f172a;
        --card: #1e293b;
        --text: #FFFFFF;
        --accent: #8B5CF6;
      }
      
      [data-theme="light"] {
        --bg: #f1f5f9;
        --card: #FFFFFF;
        --text: #0f12a;
        --accent: #8B5CF6;
      }

      body {
        background-color: var(--bg);
        color: var(--text);
        font-family: 'Segoe UI', Arial, sans-serif;
        margin: 0;
        padding: 20px;
        transition: 0.3s ease;
      }
      
      h1, h2 {
        color: var(--text);
      }
      
      p {
        color: #94a3b8;
      }    
      
      
      img {
        width: 300px;
        height: 300px;
        border-radius: 40%;
        float: left;
        margin-right: 50px;
        border: 8px solid var(--accent);
        object-fit: cover;
      }
      
      button {
        background-color: var(--accent);
        color: #ffffff;
        border: none;
        border-radius: 8px;
        padding: 12px 24px;
        cursor: pointer;
        font-weight: bold;
        transition: 0.3s;
      }
      
      button:hover {
        transform: scale(1.05);
        background-color: #7c3aed;
      }

      /* NEON CARD */
      .neon-card {
        background: var(--card);
        border-radius: 15px;
        padding: 25px;
        margin: 20px 0;
        box-shadow: 0 0 15px rgba(139, 92, 246, 0.3);
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
        gap: 15px;
        transition: 0.3s;
      }

      .neon-card:hover {
        box-shadow: 0 0 30px rgba(139, 92, 246, 0.6);
        transform: translateY(-3px);
      }

      /* SKILL BOX WITH HOVER ANIMATION */
            .skill {
        background: var(--bg);
        padding: 15px;
        border-radius: 10px;
        text-align: center;
        border: 1px solid var(--accent);
        transition: all 0.3s ease;
        cursor: default;
            }
            
      .skill:hover {
        transform: translateY(-8px) scale(1.05);
        box-shadow: 0 0 20px var(--accent);
        background: var(--accent);
        color: white;
      }

      /* PROJECT CARD */
      .project {
        background: var(--card);
        padding: 20px;
        border-radius: 15px;
        border-left: 4px solid var(--accent);
      }

      input, textarea {
        width: 100%;
        padding: 12px;
        margin: 8px 0;
        border-radius: 8px;
        border: 1px solid var(--accent);
        background: var(--card);
        color: var(--text);
      }
      
      section {
        margin-bottom: 50px;
        max-width: 900px;
        margin-left: auto;
        margin-right: auto;
      }
      
      .clear { clear: both; }
 
    </style>
  </head>
  <body>
    <!-- HEADER -->
    <section class="Header">
      <div class="header-top">
        <div>
          <h1>Samuel Nkanta</h1>
          <p>Frontend Developer | AI Enthusiast</p>
        </div>
      </div>
      <a href="#contact"><button>Get In Touch</button></a>
    </section>

    <!-- ABOUT -->
    <section id="image">
      <img src="Image_1276.jpeg" alt="dev image">
      <div class="about">
        <h2>About Me</h2>
        <p>I'm a frontend developer capable of building
          scalable websites/web applications and solving
          real world problems through code. Currently learning
          React and building AI-powered tools.</p>
      </div>
      <div class="clear"></div>
    </section>

    <!-- SKILLS -->
    <section class="skills">
      <h2>My Skills</h2>
      <div class="neon-card">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JAVASCRIPT</div>
        <div class="skill">REACT</div>
        <div class="skill">PYTHON</div>
        <div class="skill">GIT</div>
      </div>
    </section>
    
    <!-- PROJECTS - NEW SECTION -->
    <section class="projects">
      <h2>What I'm Building</h2>
      <div class="neon-card" style="grid-template-columns: 1fr;">
        <div class="project">
          <h3>🎵 AI Lyrics Player</h3>
          <p>Plays music + shows synced lyrics + AI explains in Pidgin & English</p>
          <p><b>Tech:</b> Python, VLC, OpenAI API</p>
          <em><p>still building🔥</p></em>
          <button>View Code</button>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="contact">
      <h2>Contact Me</h2>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="4"></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
    <script>
      
    </script>

    <!-- FOOTER -->
    <section id="footer" style="text-align: center;">
      <p>&copy; SamuelNkanta 2026 </p>
    </section>
  </body>
</html>
