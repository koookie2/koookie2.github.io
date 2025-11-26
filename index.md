---
layout: default
title: "Kavin Wesley | Machine Learning & Robotics Student"
description: "High school student from Virginia focused on machine learning, ethical AI, and robotics. View my Alzheimer’s SHAP research, CogniQuest cognitive screening app, internships, FTC robotics, programming contests, CyberPatriots, varsity crew, and more."
---

# Student Researcher in Machine Learning and Robotics

I am a high school student at the Academies of Loudoun and Broad Run High School. I am interested in computer science, data science, and using ethical AI to help doctors make earlier and more accurate diagnoses.

**Intended major:** Computer Science / Data Science

[View My Research](#machine-learning-research-on-alzheimers-disease) • [See Activities & Teams](#competitions-robotics--teams)

---

## About Me & Academics

**STEM-focused coursework and preparation for studying computer science.**

### Schools
I attend two schools on alternating days. At the **Academies of Loudoun**, I take advanced STEM and research classes. At **Broad Run High School**, I complete my core courses and participate in activities such as crew and computer science clubs.

### Coursework
*   **12 AP classes so far**, including AP Computer Science A, AP Calculus BC, AP Biology, AP Physics, AP Chemistry, AP Statistics, AP World History, AP U.S. History, and AP English Language and Literature.
*   **Dual Enrollment** course in Data Structures and Algorithms.
*   **Advanced math sequence** at AOS: Integrated Math I & II, AP Calculus BC, and Multivariable Calculus.
*   **Three years of research** at AOS: Sophomore, Junior, and Senior Science Research.

### Goal
My long-term goal is to study computer science or data science and work on ethical AI systems that support doctors in making better decisions, especially in fields like neurology and cognitive health.

---

## Machine Learning Research on Alzheimer’s Disease

**Junior and senior research at the Academies of Loudoun.**

### Enhancing Machine Learning Interpretability with the SHAP Algorithm
*Classifying stages of dementia from brain MRI scans*

In my junior research project, I studied how to use machine learning to identify different stages of Alzheimer’s disease from grayscale MRI brain scans. I wanted my model to be accurate, but also understandable for doctors and patients.

I worked with a public dataset of brain images that had four labels: no dementia, very mild dementia, mild dementia, and moderate dementia. The classes were unbalanced, especially for mild and moderate dementia. To fix this, I used a VAE-GAN (a type of generative model) to create realistic synthetic images and expand the smaller classes before training my main model.

I then trained a Convolutional Neural Network (CNN) on both the original and augmented images. The final model reached an overall accuracy of about 82% across the four classes, with high sensitivity and specificity for most categories.

Accuracy alone was not enough. I wanted to see *why* the CNN made each prediction. To do this, I applied the SHAP (Shapley Additive Explanations) algorithm to generate heatmaps that show which parts of each MRI image were most important to the model’s decision. These heatmaps revealed that the top and bottom parts of the brain contributed the most to the classification for all dementia stages.

To check if the SHAP explanations were reliable, I trained a decision tree using only the most important pixels identified by SHAP. The decision tree reached an accuracy of about 86%, which showed that the highlighted regions were truly meaningful and that the CNN was not just using random noise.

> This project showed me that powerful models can still be made more transparent. In the future, I hope to extend this work with larger, more diverse datasets and collaborate with clinicians to align the model’s focus areas with real medical practice.

### Genetic Approach to Controlling Kudzu Spread
*Early research on invasive species and gene editing*

During my freshman year, I worked with two teammates on a research project about the invasive kudzu plant in the southern United States. We proposed a method that uses *Agrobacterium tumefaciens* as a vector to deliver a CRISPR-based modification that would cause tumor growth in kudzu plants, reducing their ability to spread.

This project was my first experience reading scientific papers, designing a theoretical solution, and writing a research-style paper. It helped me learn how to frame a problem clearly and think carefully about benefits and risks when using genetic tools.

---

## CogniQuest Cognitive Screening App

**A mobile app prototype for early screening of cognitive fitness.**

### From Paper Test to Interactive iOS App
*Digitizing the SLUMS cognitive screening exam*

CogniQuest is an iOS app I designed to turn the Saint Louis University Mental Status (SLUMS) cognitive screening exam into a clear, voice-guided digital experience. The goal is to make early screening for cognitive changes easier and more accessible.

The app includes 11 types of tasks, such as orientation questions, memory recall, math problems, animal naming, clock drawing, shape recognition, and short story recall. I built the app in SwiftUI using an MVVM structure so that the screens, logic, and data stay organized and easy to maintain.

CogniQuest uses text-to-speech to read instructions out loud, simple animations to show audio levels, and flexible timers that adjust based on the user’s education level. Users can type answers, select choices, or draw directly on the screen for tasks like clock drawing.

After the test, the app calculates a score that matches SLUMS guidelines and generates a PDF summary through the native iOS Share Sheet. This summary can be shared with a doctor or caregiver. I am working toward publishing the app on the App Store and testing it with real users under proper guidance.

> Building CogniQuest taught me how to connect UI design, data models, and real user needs while staying careful about what an app like this can and cannot replace in medical practice.

---

## Internships, Programs & STEM Experiences

**Applying my skills in real projects and teams.**

### Summer Internship in Cognitive and Physical Fitness Assessment
*Machine Learning Intern • Power Braining*

I worked as a summer intern at Power Braining, a company focused on cognitive and physical fitness. Our team built content that guided users through combined brain and workout routines.

*   Used motion capture tools and video editing software to create realistic workout videos.
*   Applied prompt engineering and tools like Google’s VEO3 in the content pipeline.
*   Helped design and improve a pipeline that upgraded content from the older product into the new one.

> This internship gave me experience working in a small engineering team, communicating progress, and shipping real product changes on a deadline.

### NASA / VASTS Residential Academy
*Virginia Space Grant Consortium • VASTS*

I was selected for the Virginia Aerospace Science and Technology Scholars (VASTS) program after an eight-week online course that covered space mission planning and engineering. I earned a top score and was invited to a seven-day residential academy at NASA’s Langley Research Center.

At the academy, I worked with other students on a mock mission related to the Artemis program. We had to plan systems, budgets, and timelines while being guided by NASA staff. This experience helped me practice technical communication, teamwork, and systems-level thinking.

---

## Competitions, Robotics & Teams

**Programming, cybersecurity, robotics, and rowing.**

### Computer Science Programming Contests
*Lead programmer and problem analyst*

I am the lead programmer and problem analyst on my school’s competitive programming team. We compete in state-level and national contests that focus on algorithms, data structures, and problem solving under time pressure.

*   **VCU HSPC** – 1st in our division, 2nd overall (25+ teams).
*   **UMD HSPC** – 7th out of 30 teams.
*   **UVA HSPC** – finished in the top 15% of teams.
*   **CALICO Berkeley, TeamsCode, and MBIT (MIT)** – participation in additional contests.
*   **USACO** – reached the Silver division.

> These contests have strengthened my ability to think clearly under time limits and break complex problems down into smaller pieces that a computer can solve.

### CyberPatriots
*National youth cybersecurity competition*

For the past two years, I have competed on my school’s CyberPatriots team. We work on securing virtual machines, fixing vulnerabilities, and protecting services during timed rounds.

Our team reached the Platinum tier, which is the top level and represents roughly the top 15% of teams in the nation. Through this program, I learned basic system hardening, teamwork under pressure, and careful attention to detail.

### FTC Robotics – Cyber Sages
*Founding member and lead programmer*

I am a founding member of Cyber Sages, an FTC (FIRST Tech Challenge) robotics team. I serve as the lead programmer and also help with design and build.

*   Programmed autonomous routines that let the robot score points in the first 30 seconds without driver control.
*   Wrote TeleOp code that maps driver inputs to smooth robot movement.
*   Integrated sensors such as color, distance, and gyroscope sensors, and added vision components for better accuracy.
*   Tested and debugged code to keep the robot reliable during competitions.

Our team earned the Connect Award at a regional competition, recognizing our outreach and connection to the engineering community.

### Broad Run Varsity Crew
*3rd seat on the Second Men’s Four*

I row on the varsity crew team at Broad Run High School. My usual position is the 3rd seat on the Second Men’s Four boat. We compete in races sanctioned by VASRA and in larger regattas.

*   Placed 3rd among Virginia boats at the National Head of the Schuylkill Regatta.
*   1st place at the Walter Mess Regatta.
*   2nd place at the Al Urquia Regatta.

> Rowing has taught me consistency, discipline, and how to work as part of a crew where everyone has to move in sync.

---

## Service & Leadership

**Tutoring, community events, and mentoring.**

### National Honor Society
*Tutoring and community support*

As a member of the National Honor Society, I have completed over 30 hours of service. Most of my time has gone into tutoring younger students in math and science. I also help at events such as a Saint Patrick’s Day community dinner, a Christmas party for elderly residents, and parents’ nights where I help watch their children.

> These experiences have helped me become better at explaining ideas clearly and listening to what other people need.

---

## What I’m Working On Next

**Continuing research and preparing for college.**

Right now, I am continuing my senior research at the Academies of Loudoun and working on improving both my Alzheimer’s models and the CogniQuest app. I am also preparing for college, where I hope to study computer science or data science and keep working at the intersection of AI, healthcare, and robotics.

In the future, I want to join research labs, compete on college programming or robotics teams, and build tools that help doctors and patients make better decisions.

---
© Kavin Wesley. Built and hosted with GitHub Pages.
