---
layout: default
title: "Kavin Wesley | Machine Learning & Robotics Student"
description: "High school student from Virginia focused on machine learning, ethical AI, and robotics. View my Alzheimer’s SHAP research, CogniQuest cognitive screening app, internships, FTC robotics, programming contests, CyberPatriots, varsity crew, and more."
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

  :root {
    --bg: #0f172a;
    --bg-alt: #020617;
    --card: #020617;
    --accent: #38bdf8;
    --accent-soft: rgba(56,189,248,0.12);
    --text: #e5e7eb;
    --muted: #9ca3af;
    --border: rgba(148,163,184,0.3);
    --radius-lg: 18px;
    --shadow-soft: 0 18px 45px rgba(15,23,42,0.65);
  }

  body {
    font-family: "Inter", system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background: radial-gradient(circle at top, #1e293b 0, #020617 45%, #000 100%);
    color: var(--text);
  }

  .profile-page {
    max-width: 960px;
    margin: 0 auto;
    padding: 3.5rem 1.5rem 4rem;
  }

  @media (min-width: 768px) {
    .profile-page {
      padding: 4.5rem 1.5rem 5rem;
    }
  }

  .hero {
    background: radial-gradient(circle at top left, rgba(56,189,248,0.24), transparent 55%), linear-gradient(135deg, rgba(15,23,42,0.9), rgba(15,23,42,0.98));
    border-radius: 24px;
    padding: 2.2rem 2.1rem 2.3rem;
    box-shadow: var(--shadow-soft);
    border: 1px solid rgba(148,163,184,0.4);
    position: relative;
    overflow: hidden;
  }

  .hero::after {
    content: "";
    position: absolute;
    inset: 0;
    background: radial-gradient(circle at top right, rgba(56,189,248,0.16), transparent 55%);
    pointer-events: none;
    mix-blend-mode: screen;
  }

  .eyebrow {
    font-size: 0.9rem;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: var(--muted);
    margin-bottom: 0.6rem;
  }

  .hero h1 {
    font-size: clamp(2rem, 3vw, 2.4rem);
    margin: 0 0 0.7rem;
  }

  .hero .tagline {
    margin: 0 0 1.2rem;
    color: #e5e7eb;
    max-width: 36rem;
    line-height: 1.6;
  }

  .hero-meta {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem 0.9rem;
    font-size: 0.9rem;
    color: var(--muted);
  }

  .hero-meta span {
    padding: 0.25rem 0.7rem;
    border-radius: 999px;
    border: 1px solid rgba(148,163,184,0.5);
    background: rgba(15,23,42,0.95);
    backdrop-filter: blur(12px);
  }

  .hero-actions {
    margin-top: 1.6rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.8rem;
  }

  .btn-primary,
  .btn-ghost {
    display: inline-flex;
    align-items: center;
    gap: 0.35rem;
    padding: 0.55rem 1.1rem;
    border-radius: 999px;
    font-size: 0.9rem;
    font-weight: 500;
    text-decoration: none;
    transition: transform 0.12s ease, box-shadow 0.12s ease, background 0.12s ease, border-color 0.12s ease;
    border: 1px solid transparent;
  }

  .btn-primary {
    background: linear-gradient(135deg, #38bdf8, #0ea5e9);
    color: #0b1120;
    box-shadow: 0 11px 30px rgba(56,189,248,0.40);
  }

  .btn-primary:hover {
    transform: translateY(-1px);
    box-shadow: 0 14px 38px rgba(56,189,248,0.55);
  }

  .btn-ghost {
    background: rgba(15,23,42,0.9);
    color: var(--text);
    border-color: rgba(148,163,184,0.6);
  }

  .btn-ghost:hover {
    background: rgba(15,23,42,1);
    transform: translateY(-1px);
  }

  .section {
    margin-top: 2.8rem;
  }

  .section-header {
    display: flex;
    align-items: baseline;
    justify-content: space-between;
    gap: 1rem;
    margin-bottom: 1.4rem;
  }

  .section-title {
    font-size: 1.2rem;
    font-weight: 600;
  }

  .section-kicker {
    font-size: 0.85rem;
    color: var(--muted);
  }

  .pill-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-top: 0.2rem;
  }

  .pill {
    font-size: 0.75rem;
    padding: 0.22rem 0.65rem;
    border-radius: 999px;
    border: 1px solid rgba(148,163,184,0.5);
    color: var(--muted);
    background: rgba(15,23,42,0.8);
  }

  .grid-2 {
    display: grid;
    grid-template-columns: minmax(0, 1.1fr) minmax(0, 0.9fr);
    gap: 1.6rem;
  }

  @media (max-width: 768px) {
    .grid-2 {
      grid-template-columns: minmax(0, 1fr);
    }
  }

  .card {
    background: radial-gradient(circle at top, rgba(15,23,42,0.9), rgba(15,23,42,0.98));
    border-radius: var(--radius-lg);
    border: 1px solid var(--border);
    padding: 1.4rem 1.3rem 1.35rem;
    box-shadow: 0 14px 36px rgba(15,23,42,0.65);
    position: relative;
    overflow: hidden;
  }

  .card + .card {
    margin-top: 1rem;
  }

  .card h3 {
    font-size: 1.05rem;
    margin-top: 0;
    margin-bottom: 0.35rem;
  }

  .card-subtitle {
    font-size: 0.85rem;
    color: var(--muted);
    margin-bottom: 0.6rem;
  }

  .card p {
    font-size: 0.9rem;
    line-height: 1.6;
    margin-bottom: 0.5rem;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 0.3rem;
    padding: 0.2rem 0.55rem;
    border-radius: 999px;
    font-size: 0.75rem;
    background: var(--accent-soft);
    color: #e0f2fe;
    margin-bottom: 0.55rem;
  }

  .meta-list {
    list-style: none;
    padding: 0;
    margin: 0.4rem 0 0;
    font-size: 0.82rem;
    color: var(--muted);
  }

  .meta-list li {
    margin-bottom: 0.2rem;
  }

  .list-compact {
    list-style: disc;
    padding-left: 1.1rem;
    margin: 0.6rem 0 0;
    font-size: 0.9rem;
    color: var(--muted);
  }

  .list-compact li {
    margin-bottom: 0.25rem;
  }

  .muted {
    color: var(--muted);
    font-size: 0.85rem;
  }

  .footer-note {
    margin-top: 3rem;
    font-size: 0.8rem;
    color: var(--muted);
    text-align: center;
    opacity: 0.85;
  }
</style>

<main class="profile-page">
  <header class="hero">
    <p class="eyebrow">Hi, I’m Kavin Wesley</p>
    <h1>Student Researcher in Machine Learning and Robotics</h1>
    <p class="tagline">
      I am a high school student at the Academies of Loudoun and Broad Run High School.  
      I am interested in computer science, data science, and using ethical AI to help doctors
      make earlier and more accurate diagnoses.
    </p>
    <div class="hero-meta">
      <span>Intended major: Computer Science / Data Science</span>
      <span>Weighted GPA: 4.58</span>
      <span>SAT: 1540 (780 Math, 760 English)</span>
    </div>
    <div class="hero-actions">
      <a class="btn-primary" href="#research">View My Research</a>
      <a class="btn-ghost" href="#activities">See Activities & Teams</a>
    </div>
  </header>

  <section id="about" class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">About Me & Academics</h2>
        <p class="section-kicker">STEM-focused coursework and preparation for studying computer science.</p>
      </div>
      <div class="pill-row">
        <span class="pill">Academies of Loudoun</span>
        <span class="pill">Broad Run High School</span>
        <span class="pill">AP Scholar with Distinction</span>
      </div>
    </div>

    <article class="card">
      <h3>Schools</h3>
      <p class="card-subtitle">STEM Academy + Base School</p>
      <p>
        I attend two schools on alternating days. At the Academies of Loudoun, I take advanced STEM
        and research classes. At Broad Run High School, I complete my core courses and participate in
        activities such as crew and computer science clubs.
      </p>

      <h3 style="margin-top:1.1rem;">Coursework</h3>
      <p class="card-subtitle">Challenging STEM and humanities courses</p>
      <ul class="list-compact">
        <li>12 AP classes so far, including AP Computer Science A, AP Calculus BC, AP Biology, AP Physics, AP Chemistry, AP Statistics, AP World History, AP U.S. History, and AP English Language and Literature.</li>
        <li>Dual Enrollment course in Data Structures and Algorithms.</li>
        <li>Advanced math sequence at AOS: Integrated Math I & II, AP Calculus BC, and Multivariable Calculus.</li>
        <li>Three years of research at AOS: Sophomore, Junior, and Senior Science Research.</li>
      </ul>

      <h3 style="margin-top:1.1rem;">Goal</h3>
      <p>
        My long-term goal is to study computer science or data science and work on ethical AI systems
        that support doctors in making better decisions, especially in fields like neurology and cognitive
        health.
      </p>
    </article>
  </section>

  <section id="research" class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">Machine Learning Research on Alzheimer’s Disease</h2>
        <p class="section-kicker">Junior and senior research at the Academies of Loudoun.</p>
      </div>
      <div class="pill-row">
        <span class="pill">Convolutional Neural Networks</span>
        <span class="pill">VAE-GAN Data Augmentation</span>
        <span class="pill">SHAP Interpretability</span>
      </div>
    </div>

    <article class="card">
      <div class="badge">AOS Junior Science Research</div>
      <h3>Enhancing Machine Learning Interpretability with the SHAP Algorithm</h3>
      <p class="card-subtitle">Classifying stages of dementia from brain MRI scans</p>
      <p>
        In my junior research project, I studied how to use machine learning to identify different stages
        of Alzheimer’s disease from grayscale MRI brain scans. I wanted my model to be accurate, but
        also understandable for doctors and patients.
      </p>
      <p>
        I worked with a public dataset of brain images that had four labels: no dementia, very mild
        dementia, mild dementia, and moderate dementia. The classes were unbalanced, especially for
        mild and moderate dementia. To fix this, I used a VAE-GAN (a type of generative model) to
        create realistic synthetic images and expand the smaller classes before training my main model.
      </p>
      <p>
        I then trained a Convolutional Neural Network (CNN) on both the original and augmented
        images. The final model reached an overall accuracy of about 82% across the four classes,
        with high sensitivity and specificity for most categories.
      </p>
      <p>
        Accuracy alone was not enough. I wanted to see <em>why</em> the CNN made each prediction.
        To do this, I applied the SHAP (Shapley Additive Explanations) algorithm to generate
        heatmaps that show which parts of each MRI image were most important to the model’s
        decision. These heatmaps revealed that the top and bottom parts of the brain contributed the
        most to the classification for all dementia stages.
      </p>
      <p>
        To check if the SHAP explanations were reliable, I trained a decision tree using only the most
        important pixels identified by SHAP. The decision tree reached an accuracy of about 86%,
        which showed that the highlighted regions were truly meaningful and that the CNN was not
        just using random noise.
      </p>
      <p class="muted">
        This project showed me that powerful models can still be made more transparent. In the
        future, I hope to extend this work with larger, more diverse datasets and collaborate with
        clinicians to align the model’s focus areas with real medical practice.
      </p>
    </article>

    <article class="card" style="margin-top:1.2rem;">
      <div class="badge">Toshiba Freshman Research</div>
      <h3>Genetic Approach to Controlling Kudzu Spread</h3>
      <p class="card-subtitle">Early research on invasive species and gene editing</p>
      <p>
        During my freshman year, I worked with two teammates on a research project about the
        invasive kudzu plant in the southern United States. We proposed a method that uses
        <em>Agrobacterium tumefaciens</em> as a vector to deliver a CRISPR-based modification that
        would cause tumor growth in kudzu plants, reducing their ability to spread.
      </p>
      <p>
        This project was my first experience reading scientific papers, designing a theoretical solution,
        and writing a research-style paper. It helped me learn how to frame a problem clearly and
        think carefully about benefits and risks when using genetic tools.
      </p>
    </article>
  </section>

  <section id="cogniquest" class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">CogniQuest Cognitive Screening App</h2>
        <p class="section-kicker">A mobile app prototype for early screening of cognitive fitness.</p>
      </div>
      <div class="pill-row">
        <span class="pill">SwiftUI</span>
        <span class="pill">iOS Development</span>
        <span class="pill">Cognitive Health</span>
      </div>
    </div>

    <article class="card">
      <h3>From Paper Test to Interactive iOS App</h3>
      <p class="card-subtitle">Digitizing the SLUMS cognitive screening exam</p>
      <p>
        CogniQuest is an iOS app I designed to turn the Saint Louis University Mental Status
        (SLUMS) cognitive screening exam into a clear, voice-guided digital experience. The goal is
        to make early screening for cognitive changes easier and more accessible.
      </p>
      <p>
        The app includes 11 types of tasks, such as orientation questions, memory recall, math
        problems, animal naming, clock drawing, shape recognition, and short story recall. I built
        the app in SwiftUI using an MVVM structure so that the screens, logic, and data stay
        organized and easy to maintain.
      </p>
      <p>
        CogniQuest uses text-to-speech to read instructions out loud, simple animations to show
        audio levels, and flexible timers that adjust based on the user’s education level. Users can
        type answers, select choices, or draw directly on the screen for tasks like clock drawing.
      </p>
      <p>
        After the test, the app calculates a score that matches SLUMS guidelines and generates a
        PDF summary through the native iOS Share Sheet. This summary can be shared with a
        doctor or caregiver. I am working toward publishing the app on the App Store and testing it
        with real users under proper guidance.
      </p>
      <p class="muted">
        Building CogniQuest taught me how to connect UI design, data models, and real user needs
        while staying careful about what an app like this can and cannot replace in medical
        practice.
      </p>
    </article>
  </section>

  <section id="programs" class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">Internships, Programs & STEM Experiences</h2>
        <p class="section-kicker">Applying my skills in real projects and teams.</p>
      </div>
      <div class="pill-row">
        <span class="pill">NASA VASTS</span>
        <span class="pill">Machine Learning Internship</span>
        <span class="pill">Team Collaboration</span>
      </div>
    </div>

    <article class="card">
      <div class="badge">Machine Learning Intern • Power Braining</div>
      <h3>Summer Internship in Cognitive and Physical Fitness Assessment</h3>
      <p class="card-subtitle">Motion capture, AI tools, and product pipelines</p>
      <p>
        I worked as a summer intern at Power Braining, a company focused on cognitive and
        physical fitness. Our team built content that guided users through combined brain and
        workout routines.
      </p>
      <ul class="list-compact">
        <li>Used motion capture tools and video editing software to create realistic workout videos.</li>
        <li>Applied prompt engineering and tools like Google’s VEO3 in the content pipeline.</li>
        <li>Helped design and improve a pipeline that upgraded content from the older product into the new one.</li>
      </ul>
      <p class="muted">
        This internship gave me experience working in a small engineering team, communicating
        progress, and shipping real product changes on a deadline.
      </p>
    </article>

    <article class="card" style="margin-top:1.2rem;">
      <div class="badge">Virginia Space Grant Consortium • VASTS</div>
      <h3>NASA / VASTS Residential Academy</h3>
      <p class="card-subtitle">Mock mission design at NASA Langley Research Center</p>
      <p>
        I was selected for the Virginia Aerospace Science and Technology Scholars (VASTS)
        program after an eight-week online course that covered space mission planning and
        engineering. I earned a top score and was invited to a seven-day residential academy at
        NASA’s Langley Research Center.
      </p>
      <p>
        At the academy, I worked with other students on a mock mission related to the Artemis
        program. We had to plan systems, budgets, and timelines while being guided by NASA
        staff. This experience helped me practice technical communication, teamwork, and
        systems-level thinking.
      </p>
    </article>
  </section>

  <section id="activities" class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">Competitions, Robotics & Teams</h2>
        <p class="section-kicker">Programming, cybersecurity, robotics, and rowing.</p>
      </div>
      <div class="pill-row">
        <span class="pill">Programming Contests</span>
        <span class="pill">FTC Robotics</span>
        <span class="pill">CyberPatriots</span>
        <span class="pill">Varsity Crew</span>
      </div>
    </div>

    <article class="card">
      <h3>Computer Science Programming Contests</h3>
      <p class="card-subtitle">Lead programmer and problem analyst</p>
      <p>
        I am the lead programmer and problem analyst on my school’s competitive programming
        team. We compete in state-level and national contests that focus on algorithms, data
        structures, and problem solving under time pressure.
      </p>
      <ul class="list-compact">
        <li>VCU HSPC – 1st in our division, 2nd overall (25+ teams).</li>
        <li>UMD HSPC – 7th out of 30 teams.</li>
        <li>UVA HSPC – finished in the top 15% of teams.</li>
        <li>CALICO Berkeley, TeamsCode, and MBIT (MIT) – participation in additional contests.</li>
        <li>USACO – reached the Silver division.</li>
      </ul>
      <p class="muted">
        These contests have strengthened my ability to think clearly under time limits and break
        complex problems down into smaller pieces that a computer can solve.
      </p>
    </article>

    <article class="card" style="margin-top:1.2rem;">
      <h3>CyberPatriots</h3>
      <p class="card-subtitle">National youth cybersecurity competition</p>
      <p>
        For the past two years, I have competed on my school’s CyberPatriots team. We work on
        securing virtual machines, fixing vulnerabilities, and protecting services during timed
        rounds.
      </p>
      <p>
        Our team reached the Platinum tier, which is the top level and represents roughly the top
        15% of teams in the nation. Through this program, I learned basic system hardening,
        teamwork under pressure, and careful attention to detail.
      </p>
    </article>

    <article class="card" style="margin-top:1.2rem;">
      <h3>FTC Robotics – Cyber Sages</h3>
      <p class="card-subtitle">Founding member and lead programmer</p>
      <p>
        I am a founding member of Cyber Sages, an FTC (FIRST Tech Challenge) robotics team.
        I serve as the lead programmer and also help with design and build.
      </p>
      <ul class="list-compact">
        <li>Programmed autonomous routines that let the robot score points in the first 30 seconds without driver control.</li>
        <li>Wrote TeleOp code that maps driver inputs to smooth robot movement.</li>
        <li>Integrated sensors such as color, distance, and gyroscope sensors, and added vision components for better accuracy.</li>
        <li>Tested and debugged code to keep the robot reliable during competitions.</li>
      </ul>
      <p>
        Our team earned the Connect Award at a regional competition, recognizing our outreach
        and connection to the engineering community.
      </p>
    </article>

    <article class="card" style="margin-top:1.2rem;">
      <h3>Broad Run Varsity Crew</h3>
      <p class="card-subtitle">3rd seat on the Second Men’s Four</p>
      <p>
        I row on the varsity crew team at Broad Run High School. My usual position is the 3rd seat
        on the Second Men’s Four boat. We compete in races sanctioned by VASRA and in larger
        regattas.
      </p>
      <ul class="list-compact">
        <li>Placed 3rd among Virginia boats at the National Head of the Schuylkill Regatta.</li>
        <li>1st place at the Walter Mess Regatta.</li>
        <li>2nd place at the Al Urquia Regatta.</li>
      </ul>
      <p class="muted">
        Rowing has taught me consistency, discipline, and how to work as part of a crew where
        everyone has to move in sync.
      </p>
    </article>
  </section>

  <section id="service" class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">Service & Leadership</h2>
        <p class="section-kicker">Tutoring, community events, and mentoring.</p>
      </div>
      <div class="pill-row">
        <span class="pill">National Honor Society</span>
        <span class="pill">Peer Tutoring</span>
      </div>
    </div>

    <article class="card">
      <h3>National Honor Society</h3>
      <p class="card-subtitle">Tutoring and community support</p>
      <p>
        As a member of the National Honor Society, I have completed over 30 hours of service.
        Most of my time has gone into tutoring younger students in math and science. I also help at
        events such as a Saint Patrick’s Day community dinner, a Christmas party for elderly
        residents, and parents’ nights where I help watch their children.
      </p>
      <p class="muted">
        These experiences have helped me become better at explaining ideas clearly and listening
        to what other people need.
      </p>
    </article>
  </section>

  <section class="section">
    <div class="section-header">
      <div>
        <h2 class="section-title">What I’m Working On Next</h2>
        <p class="section-kicker">Continuing research and preparing for college.</p>
      </div>
    </div>

    <article class="card">
      <p>
        Right now, I am continuing my senior research at the Academies of Loudoun and working
        on improving both my Alzheimer’s models and the CogniQuest app. I am also preparing
        for college, where I hope to study computer science or data science and keep working at
        the intersection of AI, healthcare, and robotics.
      </p>
      <p>
        In the future, I want to join research labs, compete on college programming or robotics
        teams, and build tools that help doctors and patients make better decisions.
      </p>
    </article>
  </section>

  <p class="footer-note">
    © <span id="year"></span> Kavin Wesley. Built and hosted with GitHub Pages.
  </p>
</main>

<script>
  const yearEl = document.getElementById('year');
  if (yearEl) {
    yearEl.textContent = new Date().getFullYear();
  }
</script>
