# Autonomous Solar-Powered Vehicle – Showcase Website

An interactive showcase website presenting a comprehensive engineering project: **Auto** – a solar-powered, fully autonomous golf cart designed and built by EMINES engineering students.

---

## Overview

This repository contains the **interactive showcase website** for the Auto solar vehicle project. It demonstrates a multi-disciplinary approach to sustainable autonomous mobility through engaging web design and interactive documentation.

### Project Scope
- **Mechanical Engineering**: Optimized chassis, suspension, braking, and steering systems
- **Electrical & Power Management**: 48V lithium-ion battery, solar panel integration, MPPT charge controller
- **AI & Autonomous Navigation**: Multi-sensor fusion (LiDAR, camera, IMU), real-time path planning
- **Systems Integration**: Seamless coordination between mechanical, electrical, and software subsystems

---

## Quick Links

- **Live Website**: Open `site/index.html` in your browser
- **Project Documentation**: See [site/README.md](site/README.md) for full technical specifications
- **Team Information**: [site/equipe.html](site/equipe.html)
- **Contact**: [site/contact.html](site/contact.html)

---

## Repository Structure

```
.
├── site/                          # Interactive showcase website
│   ├── index.html                 # Main landing page
│   ├── projet.html                # Technical specifications
│   ├── brainstorming.html         # Project ideation
│   ├── conception.html            # 3D models & CAD
│   ├── fabrication.html           # Build process
│   ├── fonctionnalite.html        # Autonomous features
│   ├── equipe.html                # Team profiles
│   ├── contact.html               # Contact form
│   ├── forum.html                 # Discussion forum
│   ├── a-developper.html          # Future improvements
│   ├── styles.css                 # Responsive styling
│   ├── chatbot-kb.js              # AI navigation assistant
│   ├── photos/                    # 83 organized project images
│   └── README.md                  # Technical documentation
├── README.md                       # This file
└── LICENSE                        # Project license
```

---

## Technical Specifications (Quick Reference)

### Vehicle Platform
- **Type**: Solar-Powered Golf Cart (Golfette)
- **Max Speed**: 30 km/h
- **Autonomy**: 40 km (solar-dependent)
- **Weight**: 460 kg
- **Payload**: 2 passengers (~80 kg each)

### Powertrain
- **Motor**: 1.2 kW electric motor (50 N⋅m torque)
- **Battery**: 48V lithium-ion, 15 kWh
- **Solar Array**: 4 m² monocrystalline panels (22% efficiency, 600 W peak)

### Autonomous Navigation
- **Sensors**: 2D LiDAR (10 m), 1280×720 camera @30 fps, 9-axis IMU
- **AI Processing**: Canny edge detection, Hough transform, multi-sensor fusion
- **Control Loop**: 30 Hz, <50 ms latency
- **Safety**: Autonomous emergency braking, obstacle detection

---

## Getting Started

### View the Website
1. Navigate to the `site/` folder
2. Open `site/index.html` in any modern web browser
3. Explore the project through interactive sections

### Local Development
```bash
# Use VS Code Live Server extension for auto-refresh
# Or use Python's built-in server:
cd site
python -m http.server 8000
# Visit http://localhost:8000
```

### Features
- ✨ Responsive design (mobile to desktop)
- 🌙 Dark mode toggle
- 💬 AI chatbot with 60+ Q&A pairs
- 📸 Image carousel
- 📱 Touch-optimized navigation

---

## Project Team

**Lead Engineers**:
- Rayane Bentaleb (Project Lead)
- Ahmed Lebbar (Mechanical Systems)
- Anass Benbella (Safety & Compliance)
- Ali Ennoulali (Electrical Engineering)
- Mohammed El Abirdi (Systems Integration)

**Faculty Advisors**: Abdelkrim Alahyane, Anas Cherradi, Youssef Derrazi, Mohamed Lahnine, Mostafa Baba

**Institution**: EMINES – School of Industrial Management (UM6P, Ben Guerir, Morocco)
**Project Module**: Mécatronique (Mechatronics Engineering)
**Academic Year**: 2025–2026

---

## Key Achievements

✅ Fully functional prototype (20 km/h autonomous capability)
✅ Solar panel integration with real-time energy harvesting
✅ Multi-sensor perception system validated
✅ Safety-critical systems with redundancy
✅ Comprehensive documentation & interactive showcase
✅ Educational foundation for future AV research

---

## Technologies

### Frontend
- HTML5 (semantic markup)
- CSS3 (flexbox, grid, animations, dark mode)
- Vanilla JavaScript (DOM, events, state management)

### Development Tools
- CAD: SolidWorks
- Simulation: FEA, CFD, SPICE
- Version Control: Git / GitHub

---

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

---

## Documentation

For comprehensive technical specifications, system architecture, and design details, see [site/README.md](site/README.md).

---

## Contact & Collaboration

- **Email**: robotique25_26_voiture@um6p.onmicrosoft.com
- **Institution**: EMINES – UM6P, Ben Guerir, Morocco
- **Website**: Interactive showcase available in this repository

---

## License

See [LICENSE](LICENSE) file for details.

---

*Last Updated: May 2026*
*Project Status: Production Ready*
