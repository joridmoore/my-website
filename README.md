# my-website
My JTC 572 Web Design Project

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">

  <meta name="description"
        content="Explore Jori Moore's work in marketing,
        communications, recruitment, event planning,
        and web design.">

  <title>Projects | Jori Moore</title>

  <style>
    * {
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #fff9fb;
      color: #44333d;
      line-height: 1.7;
    }

    /* HEADER */

    header {
      background-color: #f8e5ee;
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      color: #743f59;
      margin: 0;
      font-size: 32px;
    }

    header p {
      color: #80566b;
      margin: 5px 0 0;
    }

    /* NAVIGATION */

    nav {
      background-color: #743f59;
      padding: 12px;
      text-align: center;
    }

    nav a {
      display: inline-block;
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 12px;
      margin: 3px;
      border-radius: 6px;
    }

    nav a:hover,
    nav a:focus-visible {
      background-color: #572c41;
      text-decoration: underline;
    }

    nav a[aria-current="page"] {
      background-color: #572c41;
      text-decoration: underline;
    }

    a:focus-visible {
      outline: 3px solid #bd638b;
      outline-offset: 3px;
    }

    /* MAIN CONTENT */

    main {
      max-width: 1100px;
      margin: auto;
      padding: 40px 20px;
    }

    h2, h3 {
      color: #743f59;
    }

    /* INTRO */

    .intro {
      background-color: #f9e5ef;
      padding: 45px 25px;
      border-radius: 18px;
      text-align: center;
      margin-bottom: 45px;
    }

    .intro h2 {
      font-size: 30px;
      margin: 0 0 15px;
    }

    .intro p {
      max-width: 650px;
      margin: auto;
    }

    /* SECTION HEADINGS */

    .section-heading {
      text-align: center;
      margin: 40px 0 25px;
    }

    .section-heading h2 {
      font-size: 27px;
      margin-bottom: 5px;
    }

    .section-heading p {
      color: #80566b;
      margin-top: 0;
    }

    /* FEATURED PROJECT */

    .featured-project {
      background-color: white;
      border: 1px solid #efd3e0;
      border-radius: 18px;
      padding: 30px;
      margin-bottom: 45px;
      box-shadow: 0 5px 18px rgba(116, 63, 89, 0.08);
    }

    .featured-project h3 {
      font-size: 24px;
      margin-top: 0;
    }

    .featured-image {
      display: block;
      width: 100%;
      max-width: 700px;
      height: auto;
      margin: 25px auto;
      border: 4px solid #f4c8dc;
      border-radius: 12px;
    }

    /* PROJECT GRID */

    .project-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 25px;
      margin-bottom: 45px;
    }

    .project-card {
      background-color: white;
      border: 1px solid #efd3e0;
      border-radius: 18px;
      padding: 28px;
      box-shadow: 0 5px 18px rgba(116, 63, 89, 0.07);
    }

    .project-card h3 {
      margin-top: 0;
      font-size: 22px;
    }

    /* PROJECT INFORMATION */

    .project-details {
      background-color: #fff1f7;
      border-radius: 12px;
      padding: 20px;
      margin-top: 20px;
    }

    .project-details p {
      margin: 10px 0;
    }

    .project-details strong {
      color: #743f59;
    }

    .project-label {
      display: inline-block;
      background-color: #f8e5ee;
      color: #743f59;
      font-size: 13px;
      font-weight: bold;
      border-radius: 20px;
      padding: 6px 14px;
      margin-bottom: 15px;
    }

    /* SKILL TAGS */

    .skill-tag {
      display: inline-block;
      background-color: #f8e5ee;
      color: #743f59;
      padding: 6px 12px;
      border-radius: 20px;
      font-size: 13px;
      font-weight: bold;
      margin: 4px 4px 4px 0;
    }

    /* BUTTONS */

    .button {
      display: inline-block;
      background-color: #743f59;
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 12px 24px;
      border-radius: 8px;
      margin-top: 15px;
    }

    .button:hover,
    .button:focus-visible {
      background-color: #572c41;
      color: white;
    }

    /* CONTACT SECTION */

    .closing {
      background-color: #f9e5ef;
      text-align: center;
      border-radius: 18px;
      padding: 35px 25px;
    }

    .closing h2 {
      margin-top: 0;
    }

    /* FOOTER */

    footer {
      background-color: #743f59;
      color: white;
      text-align: center;
      padding: 20px;
    }

    /* RESPONSIVE DESIGN */

    @media (max-width: 700px) {
      .project-grid {
        grid-template-columns: 1fr;
      }

      .intro {
        padding: 30px 20px;
      }

      .intro h2 {
        font-size: 25px;
      }

      .featured-project,
      .project-card {
        padding: 20px;
      }

      nav a {
        padding: 8px;
        margin: 3px;
      }
    }

    @media (prefers-reduced-motion: reduce) {
      html {
        scroll-behavior: auto;
      }
    }

  </style>
</head>

<body>

  <header>
    <h1>Jori Moore</h1>
    <p>Communications & Marketing Professional</p>
  </header>

  <nav aria-label="Main navigation">
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="resume.html">Resume</a>
    <a href="projects.html"
       aria-current="page">Projects</a>
    <a href="contact.html">Contact</a>
  </nav>

  <main id="main-content">

    <!-- INTRODUCTION -->

    <section class="intro">
      <h2>My Creative Portfolio</h2>

      <p>
        Welcome to my portfolio! Explore projects
        highlighting my experience in marketing,
        communications, recruitment, event planning,
        and web design. I enjoy creating meaningful
        connections and developing ideas that
        engage audiences.
      </p>
    </section>

    <!-- FEATURED WORK -->

    <section aria-labelledby="featured-title">

      <div class="section-heading">
        <h2 id="featured-title">Featured Work</h2>
        <p>Personal branding and visual communication</p>
      </div>

      <article class="featured-project">

        <span class="project-label">
          Featured Project
        </span>

        <h3>Marketing & Communications Portfolio</h3>

        <p>
          A visual overview of my professional
          experience, education, and strengths
          in marketing and communications.
        </p>

        <img
          class="featured-image"
          src="a_polished_marketing_portfolio_resume_infographic.png"
          alt="Pink and plum marketing portfolio graphic
          presenting Jori Moore's professional
          experience, education, and skills">

        <div class="project-details">

          <p>
            <strong>Problem:</strong>
            Present my professional qualifications
            in a visually engaging and easy-to-read
            format.
          </p>

          <p>
            <strong>My Role:</strong>
            Developed the concept, provided the
            professional content, and selected
            the color palette and visual direction.
          </p>

          <p>
            <strong>Tools:</strong>
            Digital design and content development.
          </p>

          <p>
            <strong>Result:</strong>
            Created a portfolio graphic that
            communicates my professional background
            and complements my website branding.
          </p>

        </div>

        <a
          class="button"
          href="a_polished_marketing_portfolio_resume_infographic.png"
          target="_blank"
          rel="noopener">
          View Full Graphic
        </a>

      </article>

    </section>

    <!-- PROJECTS -->

    <section aria-labelledby="projects-title">

      <div class="section-heading">
        <h2 id="projects-title">Explore My Projects</h2>
        <p>Communication, creativity, and professional growth</p>
      </div>

      <div class="project-grid">

        <!-- PROJECT ONE -->

        <article class="project-card">

          <span class="project-label">Project 01</span>

          <h3>Graduate Recruitment & Marketing</h3>

          <p>
            Developing outreach and communication
            strategies to connect prospective
            students with academic opportunities.
          </p>

          <div class="project-details">

            <p>
              <strong>Problem:</strong>
              Prospective students need clear,
              personalized information to navigate
              graduate program options.
            </p>

            <p>
              <strong>My Role:</strong>
              Develop outreach emails, coordinate
              recruitment activities, and collaborate
              with university faculty and staff.
            </p>

            <p>
              <strong>Tools:</strong>
              Email communication, recruitment
              platforms, and event planning.
            </p>

            <p>
              <strong>Result:</strong>
              Supported student engagement,
              program awareness, and communication
              throughout the enrollment process.
            </p>

          </div>

          <p>
            <span class="skill-tag">Recruitment</span>
            <span class="skill-tag">Marketing</span>
            <span class="skill-tag">Communication</span>
          </p>

        </article>

        <!-- PROJECT TWO -->

        <article class="project-card">

          <span class="project-label">Project 02</span>

          <h3>Social Media & Digital Content</h3>

          <p>
            Creating engaging digital messaging
            that communicates information clearly
            and connects with audiences.
          </p>

          <div class="project-details">

            <p>
              <strong>Problem:</strong>
              Academic programs need engaging
              digital content to communicate
              opportunities to prospective students.
            </p>

            <p>
              <strong>My Role:</strong>
              Develop promotional messaging,
              digital content, and communication
              materials for student audiences.
            </p>

            <p>
              <strong>Tools:</strong>
              Social media platforms, digital
              content development, and writing.
            </p>

            <p>
              <strong>Result:</strong>
              Produced content supporting
              program communication and
              recruitment outreach.
            </p>

          </div>

          <p>
            <span class="skill-tag">Social Media</span>
            <span class="skill-tag">Content Creation</span>
            <span class="skill-tag">Digital Marketing</span>
          </p>

        </article>

        <!-- PROJECT THREE -->

        <article class="project-card">

          <span class="project-label">Project 03</span>

          <h3>Creative Event Planning</h3>

          <p>
            Planning memorable group experiences
            through creative ideas, organization,
            and attention to detail.
          </p>

          <div class="project-details">

            <p>
              <strong>Problem:</strong>
              Create unique, coordinated
              celebrations that are enjoyable
              and memorable for participants.
            </p>

            <p>
              <strong>My Role:</strong>
              Helped plan bachelorette celebrations
              in Las Vegas and Nashville, including
              a scavenger hunt, themed wig night,
              and group activities.
            </p>

            <p>
              <strong>Tools:</strong>
              Event planning, scheduling,
              communication, and creative
              activity coordination.
            </p>

            <p>
              <strong>Result:</strong>
              Organized successful celebrations
              with personalized activities
              and memorable group experiences.
            </p>

          </div>

          <p>
            <span class="skill-tag">Event Planning</span>
            <span class="skill-tag">Creativity</span>
            <span class="skill-tag">Organization</span>
          </p>

        </article>

        <!-- PROJECT FOUR -->

        <article class="project-card">

          <span class="project-label">Project 04</span>

          <h3>Website Design & Development</h3>

          <p>
            Building a professional online
            portfolio that showcases my
            experience and creative projects.
          </p>

          <div class="project-details">

            <p>
              <strong>Problem:</strong>
              Create an accessible, organized,
              and professional website that
              presents my work effectively.
            </p>

            <p>
              <strong>My Role:</strong>
              Developed a five-page portfolio
              using HTML and CSS as part of
              my web design coursework.
            </p>

            <p>
              <strong>Tools:</strong>
              HTML, CSS, GitHub, and GitHub Pages.
            </p>

            <p>
              <strong>Result:</strong>
              Published a portfolio featuring
              consistent branding, connected
              navigation, and responsive layouts.
            </p>

          </div>

          <p>
            <span class="skill-tag">HTML</span>
            <span class="skill-tag">CSS</span>
            <span class="skill-tag">Web Design</span>
          </p>

        </article>

      </div>

    </section>

    <!-- CONTACT -->

    <section class="closing">
      <h2>Let's Connect!</h2>

      <p>
        Interested in learning more about
        my experience or discussing a
        creative collaboration?
      </p>

      <a class="button" href="contact.html">
        Contact Me
      </a>
    </section>

  </main>

  <footer>
    <p>
      &copy; 2026 Jori Moore |
      Professional Portfolio
    </p>
  </footer>

</body>
</html>
