
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nesika | Digital Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0b1020;
      color: #f3f6ff;
      line-height: 1.7;
    }

    header {
      background: #131b30;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    header h2 {
      color: #77e5cf;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 8px;
    }

    nav a:hover {
      color: #77e5cf;
    }

    section {
      padding: 65px 8%;
    }

    .hero {
      min-height: 80vh;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 35px;
      flex-wrap: wrap;
    }

    .hero h1 {
      font-size: clamp(40px, 7vw, 65px);
      line-height: 1.2;
    }

    .hero h1 span {
      color: #8b9cff;
    }

    .hero p {
      color: #b5c0d9;
      max-width: 600px;
      margin: 20px 0;
    }

    .hero-art {
      width: 220px;
      height: 220px;
      border-radius: 35px;
      background: linear-gradient(135deg, #8b9cff, #77e5cf);
      color: #0b1020;
      display: grid;
      place-items: center;
      font-size: 35px;
      font-weight: bold;
      text-align: center;
    }

    .btn {
      display: inline-block;
      background: #77e5cf;
      color: #0b1020;
      padding: 12px 20px;
      border-radius: 10px;
      text-decoration: none;
      font-weight: bold;
      margin: 5px 8px 5px 0;
    }

    h2 {
      font-size: 30px;
      margin-bottom: 20px;
    }

    .accent {
      color: #77e5cf;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
    }

    .card {
      background: #131b30;
      border: 1px solid #293653;
      padding: 24px;
      border-radius: 16px;
    }

    .card h3 {
      color: #8b9cff;
      margin-bottom: 12px;
    }

    .card p {
      color: #b5c0d9;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .skills span {
      background: #202c48;
      border: 1px solid #39466a;
      border-radius: 20px;
      padding: 8px 14px;
    }

    .score {
      color: #77e5cf;
      font-size: 24px;
      font-weight: bold;
    }

    #contact {
      background: #131b30;
      text-align: center;
    }

    #contact p {
      margin-bottom: 20px;
      color: #b5c0d9;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #b5c0d9;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
      }

      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }

      section {
        padding: 45px 6%;
      }

      .hero {
        min-height: auto;
        padding-top: 55px;
      }

      .hero-art {
        width: 180px;
        height: 180px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h2> Nesika<span>.</span> </h2>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div>
      <p class="accent">B.Sc. Computer Science | 2026–2029</p>
      <h1>Hello, I'm<br><span>Nesika!</span></h1>
      <p>
        I am a Computer Science student at Bishop Heber College
        with an interest in technology, programming, and problem-solving.
        My dream is to become a Software Developer in the IT field
        and build useful digital solutions.
      </p>
      <a href="#projects" class="btn">View My Projects</a>
      <a href="#contact" class="btn">Contact Me</a>
    </div>

    <div class="hero-art">
      &lt; Code /&gt;<br>
      Learn. Build.
    </div>
  </section>

  <section id="about">
    <h2>About <span class="accent">Me</span></h2>
    <div class="card">
      <p>
        I am Nesika, a B.Sc. Computer Science student at
        Bishop Heber College (2026–2029). I enjoy learning
        about programming, algorithms, and database concepts.
        I believe that problem-solving, communication, and
        teamwork are important for creating successful
        software. I aim to improve my technical knowledge
        and grow into a skilled software developer.
      </p>
    </div>
  </section>

  <section id="education">
    <h2>My <span class="accent">Education</span></h2>
    <div class="cards">
      <div class="card">
        <h3>B.Sc. Computer Science</h3>
        <p>Bishop Heber College</p>
        <p>2026–2029</p>
      </div>

      <div class="card">
        <h3>Higher Secondary (12th)</h3>
        <p>Holy Redeemer's Girls Hr. Sec. School</p>
        <p>Mark: 550 / 600</p>
        <p>Percentage: 91.67%</p>
      </div>

      <div class="card">
        <h3>Secondary (10th)</h3>
        <p>Holy Redeemer's Girls Hr. Sec. School</p>
        <p>Mark: 483 / 500</p>
        <p>Percentage: 96.6%</p>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>My <span class="accent">Skills</span></h2>
    <div class="skills">
      <span>Programming Languages</span>
      <span>Problem Solving</span>
      <span>Algorithms</span>
      <span>Database Concepts</span>
      <span>Communication</span>
      <span>Teamwork</span>
      <span>Logical Thinking</span>
      <span>Debugging</span>
    </div>
  </section>

  <section id="projects">
    <h2>My <span class="accent">Projects</span></h2>
    <div class="cards">
      <div class="card">
        <h3>01. Bank Management System</h3>
        <p>
          A project focused on banking account management
          and common banking operations.
        </p>
      </div>

      <div class="card">
        <h3>02. Heap Sort Project</h3>
        <p>
          An algorithm project exploring Heap Sort,
          data structures, and efficient sorting.
        </p>
      </div>

      <div class="card">
        <h3>03. Vector Calculus in Weather Prediction</h3>
        <p>
          An academic project exploring vector calculus
          concepts and their relationship to weather prediction.
        </p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Let's <span class="accent">Connect</span></h2>
    <p>
      I am interested in learning opportunities,
      collaboration, and growing in the IT industry.
    </p>

    <a class="btn" href="mailto:nesika570@gmail.com">
      Email Me
    </a>

    <a class="btn"
       href="https://www.linkedin.com/in/nesika-t-5b1193424/"
       target="_blank"
       rel="noopener noreferrer">
      LinkedIn Profile
    </a>
  </section>

  <footer>
    <p>© 2026 Nesika | Digital Portfolio</p>
    <p>Learning Today, Building Tomorrow.</p>
  </footer>

</body>
</html>
