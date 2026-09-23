From 98ecffa0270abffcf58c4a6215c3cccc043cf11b Mon Sep 17 00:00:00 2001
From: Omar Grif <omargrif@users.noreply.github.com>
Date: Wed, 23 Sep 2026 22:04:48 +0000
Subject: [PATCH] docs: rewrite README to highlight website features and my
 contribution

---
 README.md | 136 ++++++++++++++++++++++++++++++++++++------------------
 1 file changed, 92 insertions(+), 44 deletions(-)

diff --git a/README.md b/README.md
index 612ac7e..ba4e623 100644
--- a/README.md
+++ b/README.md
@@ -1,66 +1,114 @@
-# Autonomous Solar-Powered Vehicle – Showcase Website
+<p align="center">
+  <img src="site/photos/photo-047.png" alt="Auto logo" width="260" />
+</p>
 
-This repository hosts the website for **Auto**, a solar-powered autonomous golf cart developed by EMINES engineering students. The goal of the site is simple: present the project clearly, show how it was built, and make it easy to explore the different phases of the work.
+<h1 align="center">Auto — Showcase Website for an Autonomous Solar Vehicle</h1>
 
-## What this repository contains
+<p align="center">
+  <b>12-page responsive website, built from scratch in HTML, CSS and vanilla JavaScript,<br/>
+  to present an autonomous solar-powered vehicle designed by a 13-student engineering team.</b>
+</p>
 
-- The public showcase website
-- Project pages for design, fabrication, and validation
-- A photo gallery organized in a single folder
-- Team and contact information
+<p align="center">
+  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" />
+  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" />
+  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=black" />
+  <img alt="No dependencies" src="https://img.shields.io/badge/dependencies-0-success" />
+  <img alt="License MIT" src="https://img.shields.io/badge/license-MIT-blue" />
+</p>
 
-## Project at a glance
+---
 
-- **Vehicle**: solar-powered golf cart designed for autonomous navigation
-- **Speed**: up to 30 km/h
-- **Range**: about 40 km, depending on solar conditions
-- **Energy**: 48V battery with roof-mounted solar panels
-- **Perception**: camera, LiDAR, and IMU working together for navigation
+## In short
 
-## Repository layout
+As part of the 2025–2026 mechatronics project at **EMINES – School of Industrial Management (UM6P, Ben Guerir, Morocco)**, our team designed and built **Auto**, a two-seat autonomous golf cart powered by a 48 V battery and roof-mounted solar panels.
 
-```
-.
-├── site/            # Website files
-│   ├── index.html   # Home page
-│   ├── projet.html  # Technical summary
-│   ├── conception.html / fabrication.html / fonctionnalite.html
-│   ├── equipe.html / contact.html / forum.html
-│   ├── styles.css
-│   ├── chatbot-kb.js
-│   ├── photos/      # Project images
-│   └── README.md    # Detailed project notes
-├── README.md
-└── LICENSE
-```
+I was a member of the 13-student project team and **designed and developed this website**, which turns a year of engineering work (brainstorming, CAD design, fabrication, perception, energy management) into a clear, visual story for a non-specialist audience: jury, faculty, partners and future students.
+
+## My contribution
+
+- **Designed and built the full website** — information architecture, visual identity, layout and every page — without any framework or template engine.
+- **Developed an interactive FAQ chatbot** in plain JavaScript: a knowledge base of 50+ question/answer entries with accent-insensitive keyword matching and scoring, so visitors can ask questions in French or English and get instant answers about the vehicle, the team and the school.
+- **Translated technical content into accessible content** by working with the mechanical, electrical and perception sub-teams to collect, check and simplify specifications (speed, range, battery, sensors, control loop).
+- **Organised and integrated 80+ project photos and diagrams** into a single image library, with a zoomable lightbox on the design, fabrication and brainstorming pages.
+- **Maintained the project with Git**: versioned history, content corrections after team review, and technical documentation.
+
+## Website features
+
+| Feature | How it works |
+|---|---|
+| Multi-page structure | 12 static pages: home, project, context, brainstorming, design, fabrication, features, team, forum, contact, roadmap |
+| FAQ chatbot | Local knowledge base (`chatbot-kb.js`) + scoring algorithm with accent normalisation — no backend, no external API |
+| Dark mode | Theme toggle saved in `localStorage` so the visitor's choice persists between visits |
+| Image lightbox | Click to enlarge photos and diagrams; close with a click or the `Esc` key |
+| Carousel | Arrow buttons, dots and keyboard navigation (← →) |
+| Responsive design | CSS custom properties, flexible grids and breakpoints for mobile and tablet |
+| Zero dependencies | Pure HTML/CSS/JS, system fonts, runs offline by simply opening `index.html` |
+
+## Skills demonstrated
 
-## How to view it
+**Front-end development** · HTML5, CSS3 (custom properties, responsive layout), vanilla JavaScript (DOM manipulation, events, `localStorage`)
+**Algorithmic thinking** · text normalisation and keyword-scoring logic for the chatbot
+**Technical communication** · turning engineering documentation into content a non-expert can follow
+**Teamwork in a multidisciplinary project** · coordination with mechanical, electrical, perception and safety sub-teams
+**Version control** · Git / GitHub
 
-1. Open `site/index.html` in a browser, or
-2. Serve the `site/` folder locally with any simple web server
+## The vehicle presented on the site
 
-Example:
+| | |
+|---|---|
+| Type | Two-seat autonomous solar golf cart |
+| Top speed | 30 km/h |
+| Range | about 40 km, depending on sunlight |
+| Energy | 48 V lithium-ion battery (15 kWh), 4 m² of monocrystalline panels, MPPT charge control |
+| Drivetrain | 1.2 kW electric motor, 50 N·m |
+| Mechanics | Tubular chassis, double-wishbone suspension, rack-and-pinion steering with Ackermann geometry, hydraulic brakes with emergency stop |
+| Perception | Camera (1280×720, 30 fps) + LiDAR (10 m) + 9-axis IMU; lane detection with Canny and Hough transforms |
+| Control | 30 Hz control loop, latency target below 50 ms |
+
+Full technical notes: [`site/README.md`](site/README.md)
+
+## Run it locally
 
 ```bash
-cd site
+git clone https://github.com/omargrif/site-robotique.git
+cd site-robotique/site
 python -m http.server 8000
 ```
 
-Then open `http://localhost:8000`.
+Then open <http://localhost:8000> — or simply double-click `site/index.html`.
+
+## Repository structure
+
+```
+.
+├── site/
+│   ├── index.html            # Home page (carousel, chatbot, dark mode)
+│   ├── projet.html           # Technical summary
+│   ├── contexte.html         # Project context
+│   ├── brainstorming.html    # Requirements and early ideas
+│   ├── conception.html       # CAD and electrical design
+│   ├── fabrication.html      # Assembly and build process
+│   ├── fonctionnalite.html   # Autonomous and energy features
+│   ├── equipe.html           # Team
+│   ├── forum.html / contact.html / accueil.html / a-developper.html
+│   ├── styles.css            # Design system (light and dark themes)
+│   ├── chatbot-kb.js         # Chatbot knowledge base and matching algorithm
+│   ├── photos/               # 80+ project images
+│   └── README.md             # Detailed technical notes
+├── LICENSE
+└── README.md
+```
 
-## Team
+## Project team
 
-- Rayane Bentaleb — project lead
-- Ahmed Lebbar — mechanical systems
-- Anass Benbella — safety and compliance
-- Ali Ennoulali — electrical engineering
-- Mohammed El Abirdi — systems integration
+13 EMINES students, including Rayane Bentaleb (project lead), Ahmed Lebbar (hardware), Anass Benbella (safety), Ali Ennoulali (electrical design), Mohammed El Abirdi (integration), and **Omar Grif (website design and development)**.
 
 Faculty supervision: Abdelkrim Alahyane, Anas Cherradi, Youssef Derrazi, Mohamed Lahnine, Mostafa Baba.
 
-## Contact
+## Author
 
-- Email: robotique25_26_voiture@um6p.onmicrosoft.com
-- Institution: EMINES – UM6P, Ben Guerir, Morocco
+**Omar Grif** — engineering student at EMINES – UM6P
+GitHub: [@omargrif](https://github.com/omargrif)
 
-See [site/README.md](site/README.md) for the detailed technical documentation.
+Released under the [MIT License](LICENSE).
-- 
2.43.0
