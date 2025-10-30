<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ray Chen Zeng — Robotics · Research · Volleyball</title>
  <link rel="stylesheet" href="css/styles.css" />
  <meta name="description" content="Ray Chen Zeng — Robotics, research, volleyball, DECA, singing. Selected projects, resume, and contact." />
</head>
<body>
  <header class="site-header">
    <div class="container header-inner">
      <div class="brand">Ray Chen Zeng</div>

      <button id="nav-toggle" class="nav-toggle" aria-label="Open menu" aria-expanded="false">
        ☰
      </button>

      <nav id="site-nav" class="site-nav">
        <ul>
          <li><a href="#about">About Me</a></li>
          <li><a href="#activities">Activities</a></li>
          <li><a href="#achievements">Achievements</a></li>
          <li><a href="#gallery">Gallery</a></li>
          <li><a href="#resume">Resume</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="container hero-inner">
      <h1 class="hero-title">Ray Chen Zeng</h1>
      <p class="hero-sub">Robotics | Research | Volleyball | DECA | Singing</p>
    </div>
  </section>

  <main class="container main-content">
    <section id="about" class="card about-card">
      <h2>About</h2>
      <p>
        I am a senior at North Allegheny High School. I am passionate about Engineering/Robotics,
        research and innovation. I enjoy exploring mechanical design, physics, coding, applied
        problem-solving and every minute spent with my buddy at BrainStem. Outside academics, I
        stay active through volleyball and express creativity through singing. My goal is to
        continue combining science, creativity and leadership to make a real impact for the
        development of Robotics.
      </p>

      <ul class="about-list">
        <li><strong>Interests:</strong> Robotics, Volleyball, Singing</li>
        <li><strong>High school:</strong> North Allegheny High School</li>
        <li><strong>Available for questions —</strong> <a href="mailto:zengrayc@gmail.com">zengrayc@gmail.com</a></li>
      </ul>
    </section>

    <section id="projects" class="card projects-card">
      <div class="section-head">
        <h2>Selected Projects</h2>
        <p class="muted">Short highlights — link to repos and demos</p>
      </div>

      <div class="project-grid">
        <article class="project">
          <h3><a href="#">EMG research at Harvard</a></h3>
          <p class="project-desc">Use EMG to do signal analysis and apply it to control and research tasks.</p>
          <p class="project-tags">JS · D3 · solo</p>
        </article>

        <article class="project">
          <h3><a href="#">Robotics Pictures</a></h3>
          <p class="project-desc">FTC · FRC documentation and photos from competitions and builds.</p>
          <p class="project-tags">Python · PyTorch</p>
        </article>

        <article class="project">
          <h3><a href="#">Volleyball playing and teaching</a></h3>
          <p class="project-desc">Coaching and playing experience — skills, drills, and team leadership.</p>
          <p class="project-tags">Markdown · Docs</p>
        </article>
      </div>
    </section>

    <section id="resume" class="card resume-card">
      <h2>Resume</h2>
      <p>Download my resume: <a href="resume.pdf" download>resume.pdf</a> or view the <a href="#resume">Markdown resume</a>.</p>
    </section>

    <section id="activities" class="card">
      <h2>Activities</h2>
      <p class="muted">Robotics teams, research groups, competitions, and community work.</p>
      <ul>
        <li>BrainStem research collaboration</li>
        <li>High school robotics (FTC / FRC)</li>
        <li>Volleyball — player and coach</li>
        <li>DECA participation and events</li>
      </ul>
    </section>

    <section id="achievements" class="card">
      <h2>Achievements</h2>
      <ul>
        <li>Research contributions and competition placements (details available on request)</li>
        <li>Team leadership and awards in robotics</li>
        <li>Academic recognitions and extracurricular honors</li>
      </ul>
    </section>

    <section id="gallery" class="card">
      <h2>Gallery</h2>
      <p class="muted">Project screenshots, photos, demo images — add actual images to /assets/images/</p>
      <div class="gallery-grid">
        <div class="img-placeholder">Image 1</div>
        <div class="img-placeholder">Image 2</div>
        <div class="img-placeholder">Image 3</div>
      </div>
    </section>

    <section id="contact" class="card contact-card">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:zengrayc@gmail.com">zengrayc@gmail.com</a></p>
      <p class="muted">Prefer to share GitHub or portfolio links? Add them in the nav or the content above.</p>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <small>&copy; <span id="year"></span> Ray Chen Zeng — Built with a simple static site.</small>
    </div>
  </footer>

  <script src="js/main.js"></script>
</body>
</html>