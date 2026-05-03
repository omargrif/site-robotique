# Autonomous Solar-Powered Vehicle – Project Notes

This document gives a practical overview of **Auto**, a solar-powered autonomous golf cart built by EMINES engineering students. It is written to help visitors understand the project without turning the page into a spec sheet.

## What the project is about

Auto is a small autonomous vehicle designed around a simple idea: make the platform efficient, safe, and easy to explain. The team worked across mechanics, electrical power, perception, and software integration to build a vehicle that can navigate in controlled environments while harvesting energy from the roof-mounted solar panels.

## Main technical choices

- **Chassis and mechanics**: suspension, steering, braking, and wheel layout designed for a compact vehicle
- **Power system**: 48V lithium-ion battery with solar charging support and MPPT regulation
- **Perception**: camera, LiDAR, and IMU combined to improve navigation and safety
- **Software integration**: a control loop that turns sensor data into navigation decisions

## Key technical data

### Vehicle
- Type: solar-powered golf cart
- Maximum speed: 30 km/h
- Range: about 40 km, depending on solar conditions
- Vehicle weight: 460 kg
- Capacity: 2 passengers

### Drivetrain and mechanics
- Motor: 1.2 kW electric motor
- Torque: 50 N⋅m
- Suspension: double-wishbone with spring-damper architecture
- Steering: rack-and-pinion with Ackermann geometry
- Braking: hydraulic system with emergency stop support

### Energy system
- Battery: 48V lithium-ion, 15 kWh
- Solar array: 4 m² of monocrystalline panels
- Peak solar output: 600 W
- Charge control: MPPT

### Navigation and safety
- LiDAR range: 10 m
- Camera: 1280×720 at 30 fps
- IMU: 9-axis sensor
- Control loop: 30 Hz
- Latency target: below 50 ms

## Website structure

- `index.html`: home page and overview
- `projet.html`: technical presentation
- `brainstorming.html`: early ideas and requirements
- `conception.html`: CAD, design, and electrical work
- `fabrication.html`: assembly and build process
- `fonctionnalite.html`: autonomous behaviour and features
- `equipe.html`: team and supervision
- `contact.html`: contact details
- `forum.html`: discussion space
- `a-developper.html`: future improvements

## Assets and interface

- `styles.css`: responsive layout and visual design
- `chatbot-kb.js`: navigation helper for the website content
- `photos/`: the organized image library used across the pages
- The site is static and works locally without a backend or external API

Institution: EMINES – School of Industrial Management (UM6P, Ben Guerir, Morocco)

## How to use this repository

1. Open `index.html` in a browser, or
2. Serve the `site/` folder locally during development

Example:

```bash
python -m http.server 8000
```

Then open the local address shown by the server.

## Contact

- Email: robotique25_26_voiture@um6p.onmicrosoft.com
- Institution: EMINES – UM6P, Ben Guerir, Morocco

*Last updated: May 2026*
