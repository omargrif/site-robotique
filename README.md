# Autonomous Solar-Powered Vehicle – Showcase Website

This repository hosts the website for **Auto**, a solar-powered autonomous golf cart developed by EMINES engineering students. The goal of the site is simple: present the project clearly, show how it was built, and make it easy to explore the different phases of the work.

## What this repository contains

- The public showcase website
- Project pages for design, fabrication, and validation
- A photo gallery organized in a single folder
- Team and contact information

## Project at a glance

- **Vehicle**: solar-powered golf cart designed for autonomous navigation
- **Speed**: up to 30 km/h
- **Range**: about 40 km, depending on solar conditions
- **Energy**: 48V battery with roof-mounted solar panels
- **Perception**: camera, LiDAR, and IMU working together for navigation

## Repository layout

```
.
├── site/            # Website files
│   ├── index.html   # Home page
│   ├── projet.html  # Technical summary
│   ├── conception.html / fabrication.html / fonctionnalite.html
│   ├── equipe.html / contact.html / forum.html
│   ├── styles.css
│   ├── chatbot-kb.js
│   ├── photos/      # Project images
│   └── README.md    # Detailed project notes
├── README.md
└── LICENSE
```

## How to view it

1. Open `site/index.html` in a browser, or
2. Serve the `site/` folder locally with any simple web server

Example:

```bash
cd site
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Team

- Rayane Bentaleb — project lead
- Ahmed Lebbar — mechanical systems
- Anass Benbella — safety and compliance
- Ali Ennoulali — electrical engineering
- Mohammed El Abirdi — systems integration

Faculty supervision: Abdelkrim Alahyane, Anas Cherradi, Youssef Derrazi, Mohamed Lahnine, Mostafa Baba.

## Contact

- Email: robotique25_26_voiture@um6p.onmicrosoft.com
- Institution: EMINES – UM6P, Ben Guerir, Morocco

See [site/README.md](site/README.md) for the detailed technical documentation.
