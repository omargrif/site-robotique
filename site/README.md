# Autonomous Solar-Powered Vehicle – Showcase Website

An interactive showcase website presenting a comprehensive engineering project: **Auto** – a solar-powered, fully autonomous golf cart designed and built by EMINES engineering students.

---

## Overview

This project demonstrates a multi-disciplinary approach to sustainable autonomous mobility:

- **Mechanical Engineering**: Optimized chassis, suspension, braking, and steering systems
- **Electrical & Power Management**: 48V lithium-ion battery, solar panel integration, MPPT charge controller
- **AI & Autonomous Navigation**: Multi-sensor fusion (LiDAR, camera, IMU), real-time path planning
- **Systems Integration**: Seamless coordination between mechanical, electrical, and software subsystems

---

## Technical Specifications

### Vehicle Platform
- **Type**: Solar-Powered Golf Cart (Golfette)
- **Max Speed**: 30 km/h
- **Autonomy Range**: 40 km minimum (solar conditions dependent)
- **Payload Capacity**: 2 passengers (~80 kg each)
- **Total Vehicle Weight**: 460 kg
- **Dimensions**: 2 m length, optimized urban footprint

### Drivetrain & Mechanics
- **Motor**: 1.2 kW electric motor (50 N⋅m torque)
- **Transmission**: Direct drive, smooth acceleration profile
- **Suspension**: Double-wishbone A-arm + spring-damper (150 mm travel)
- **Steering**: Rack-and-pinion with Ackermann geometry
- **Braking**: Hydraulic redundancy + AI-controlled emergency stop
- **Wheels**: 0.45 m radius, optimized for urban maneuverability

### Power & Energy Systems
- **Battery**: 48V lithium-ion, 15 kWh capacity
- **Solar Array**: 4 m² monocrystalline panels (22% efficiency, 600 W peak)
- **Energy Production**: ~800 Wh/day (weather-dependent)
- **Charge Controller**: MPPT (Maximum Power Point Tracking) for optimal solar conversion
- **Supply Voltage**: 48V DC distributed architecture

### Autonomous Navigation System
- **Sensor Stack**:
  - 2D LiDAR (10 m range, obstacle detection)
  - 1280×720 front camera @30 fps (lane detection)
  - 9-axis IMU (orientation & acceleration feedback)
  
- **AI Processing**:
  - Canny edge detection + Hough transform for lane marking
  - Multi-sensor fusion (camera, LiDAR, IMU)
  - Real-time control loop: 30 Hz, <50 ms latency
  - Exponential smoothing for trajectory stability
  
- **Safety Features**:
  - Autonomous emergency braking on obstacle detection
  - Manual override capability
  - Validated on controlled test environments

### Validated Capabilities
- Max slope: 8% (4.57°)
- Turning radius: Optimized for urban navigation
- FEA & CFD simulations: Full structural and aerodynamic validation
- Safety protocols: Emergency braking, stability tests

---

## Website Architecture

### Content Structure
- **`index.html`** – Main landing page with carousel, overview sections
- **`projet.html`** – Technical specifications & core systems
- **`brainstorming.html`** – Project ideation & requirements analysis
- **`conception.html`** – 3D CAD models, FEA simulations, electrical schematics
- **`fabrication.html`** – Build process, assembly documentation, real-world testing
- **`fonctionnalite.html`** – Autonomous driving features & capabilities
- **`equipe.html`** – 13-member team profiles + 5 faculty advisors
- **`contact.html`** – Contact form & EMINES information
- **`forum.html`** – Community discussion & feedback
- **`a-developper.html`** – Planned future improvements

### Interactive Features
- **`chatbot-kb.js`** – AI-powered navigation assistant with 60+ Q&A pairs covering all technical aspects
- **Dark Mode Toggle** – Accessibility & user preference support
- **Image Carousel** – Dynamic gallery rotation through project phases
- **Responsive Design** – Mobile-first, desktop optimized
- **Organized Asset Library** – `/photos/` folder with 83 organized project images

### Styling
- **`styles.css`** – Modular CSS3 with CSS variables for theming, animations, responsive breakpoints

---

## Project Team

- **Project Lead**: Rayane Bentaleb
- **Mechanical Systems**: Ahmed Lebbar
- **Safety & Compliance**: Anass Benbella
- **Electrical Engineering**: Ali Ennoulali
- **Systems Integration**: Mohammed El Abirdi
- **Faculty Advisors**: Abdelkrim Alahyane, Anas Cherradi, Youssef Derrazi, Mohamed Lahnine, Mostafa Baba

**Institution**: EMINES – School of Industrial Management (UM6P, Ben Guerir, Morocco)
**Project Module**: Mécatronique (Mechatronics Engineering)
**Academic Year**: 2025–2026

---

## Technologies & Tools

### Frontend
- HTML5 (semantic markup)
- CSS3 (flexbox, grid, animations)
- Vanilla JavaScript (DOM manipulation, event handling)

### Project Development
- CAD: SolidWorks (3D modeling)
- Simulation: FEA (structural), CFD (aerodynamics), SPICE (electrical)
- Motor Control: PWM drivers, real-time feedback loops
- ROS 2: Future autonomous stack (planned)

---

## Getting Started

### Quick Start
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. Navigate using the top menu or explore each section

### Development
- **Live Server**: Use VS Code Live Server extension for auto-refresh during development
- **Dark Mode Testing**: Toggle theme button to verify CSS variables
- **Mobile Testing**: Use browser DevTools responsive mode (375px – 1920px+)

---

## Key Highlights

✅ **Fully Functional Prototype**: 20 km/h autonomous capability validated
✅ **Solar Integration**: Real-time energy harvesting from roof panels
✅ **Multi-Sensor Fusion**: Robust perception under varied conditions
✅ **Safety-First Design**: Redundant braking, emergency protocols
✅ **Educational Excellence**: Demonstrates integrated systems thinking
✅ **Scalable Architecture**: Foundation for future autonomous vehicle research

---

## Project Impact

This vehicle demonstrates how constraints-based engineering (solar power, limited weight, urban footprint) drives innovation. The project serves as a teaching tool for:
- Interdisciplinary systems design
- Real-world prototyping methodology
- AI integration in embedded systems
- Sustainable mobility solutions

---

## Contact & Collaboration

For questions, collaboration opportunities, or technical discussions:
- **Email**: robotique25_26_voiture@um6p.onmicrosoft.com
- **Institution**: EMINES – UM6P, Ben Guerir, Morocco
- **Website**: This showcase (contact form available)

---

*Last Updated: May 2026*
*License: See LICENSE file for details*
