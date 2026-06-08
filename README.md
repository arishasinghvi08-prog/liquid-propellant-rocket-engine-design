# Liquid Propellant Rocket Engine Design
<img width="1096" height="650" alt="Screenshot 2026-06-08 120805" src="https://github.com/user-attachments/assets/baf1d748-4acf-41ef-9cd6-6a672747fede" />

## Overview

This project presents the design and visualization of a gas-generator-cycle liquid rocket engine developed as an aerospace engineering portfolio project.

The objective of the project was to demonstrate an understanding of liquid rocket propulsion architecture, CAD design workflows, engineering visualization, and technical communication. The engine was modeled in FreeCAD and rendered in Blender.

This project is intended as an engineering visualization and portfolio project rather than a CFD-validated propulsion system. The focus is on clearly communicating how the major subsystems of a liquid rocket engine interact and function together.

---
## Project Files and Resources

Additional project resources are included within this repository to document the complete design and visualization workflow.

### CAD Files

* [ Engine.FCStd](https://github.com/arishasinghvi08-prog/liquid-propellant-rocket-engine-design/blob/ee7d1575f46ec3368c5c688051892fe0c0ae49db/Engine.FCStd) — Primary FreeCAD model used for the engine design.

### Documentation

* [Material Summary][(documentation/MATERIAL_SUMMARY.pdf)](https://github.com/arishasinghvi08-prog/liquid-propellant-rocket-engine-design/blob/5c60aa13e01355d617cdd9abfbd4e63a708f0197/MATERIAL%20SUMMARY.pdf) — Overview of material selections and Blender rendering parameters.
* [Component Material Breakdown][(documentation/nozzle_chamber_turbo_materials.pdf)](https://github.com/arishasinghvi08-prog/liquid-propellant-rocket-engine-design/blob/5c60aa13e01355d617cdd9abfbd4e63a708f0197/nozzlechamberturbo_Page002__.pdf) — Detailed material configuration for the nozzle, combustion chamber, gas generator, and turbomachinery assemblies.

### Development Videos

The complete development process was documented through a series of progress videos covering CAD modeling, assembly development, rendering, and visualization workflows.

* Part 1 – Turbo pump 
* Part 2 – side pumps
* Part 3 – finished structure in FreeCAD
* Part 4 – Visualization in Blender

Video links:

* [Development Playlist]((https://youtube.com/playlist?list=PLZFpPKCAKpdfHmYVIzNSFygtYN31yTf79&si=FbyX0-8CQCXjkIGT))

### Blender Files

The Blender project file is not currently included in the repository due to file size limitations. However, all final renders, documentation, and source CAD files required to understand the project workflow are available within this repository.

## Project Objectives

* Design a complete liquid rocket engine architecture
* Practice CAD modeling and assembly organization
* Develop technical visualization skills
* Create engineering documentation suitable for portfolio use
* Demonstrate understanding of rocket propulsion fundamentals
* Build a project suitable for aerospace club, internship, research, and professor outreach applications

---

## Engine Architecture

The engine consists of the following major subsystems:

### Propellant Storage

* Fuel Tank
* Oxidizer Tank

These tanks store the liquid propellants required for engine operation.

### Feed System

Feed lines transport propellants from the tanks to the turbopumps and injector system.

### Turbopumps

The engine utilizes separate turbopumps for fuel and oxidizer.

Purpose:

* Increase propellant pressure
* Deliver propellants to the injector at combustion-chamber operating pressures

### Gas Generator

A small quantity of fuel and oxidizer is burned inside the gas generator.

Purpose:

* Produce high-temperature gas
* Drive turbine machinery connected to the turbopumps

### Injector Assembly

The injector is responsible for introducing fuel and oxidizer into the combustion chamber.

Purpose:

* Atomize propellants
* Promote efficient mixing
* Enable stable combustion

### Combustion Chamber

Fuel and oxidizer combust inside the chamber.

Purpose:

* Convert chemical energy into high-pressure thermal energy

### Expansion Nozzle

The nozzle accelerates combustion products to high velocity.

Purpose:

* Convert pressure energy into directed exhaust velocity
* Generate thrust through momentum exchange

---

## Operating Principle

The engine follows a gas-generator-cycle architecture.

1. Propellants are stored in separate tanks.
2. Propellants flow through feed lines into dedicated turbopumps.
3. A portion of the propellants is routed into the gas generator.
4. The gas generator produces hot gas.
5. Turbine machinery uses this gas to power the turbopumps.
6. High-pressure propellants enter the injector.
7. Combustion occurs inside the chamber.
8. Exhaust gases expand through the nozzle.
9. Thrust is generated according to Newton's Third Law.

---

## CAD Development Workflow

### Phase 1 – Architecture Planning
<img width="1536" height="1024" alt="ChatGPT Image May 22, 2026, 01_04_22 PM" src="https://github.com/user-attachments/assets/9b9dd01b-697a-4823-b90f-b74340975def" />
<img width="1672" height="941" alt="ChatGPT Image May 13, 2026, 10_20_22 PM" src="https://github.com/user-attachments/assets/984e4b9f-f1f3-447c-86b7-a6543065afab" />
LOGIC FLOW DIAGRAM
Initial subsystem layout was created based on gas-generator-cycle rocket engine concepts.

### Phase 2 – FreeCAD Modeling
<img width="1402" height="812" alt="Screenshot 2026-05-31 225146" src="https://github.com/user-attachments/assets/373da05b-1482-415b-83e5-f67b16e7d2b1" />

Major components were modeled individually:

* Tanks
* Feed lines
* Turbopumps
* Injector
* Gas generator
* Combustion chamber
* Nozzle

### Phase 3 – Blender Import
<img width="1913" height="1078" alt="Screenshot 2026-06-07 112630" src="https://github.com/user-attachments/assets/bb85b3c8-f039-4450-b90f-0b2585a52d92" />
<img width="1918" height="1078" alt="Screenshot 2026-06-07 115041" src="https://github.com/user-attachments/assets/c402c804-cf3a-437f-abff-8f04a99e61f8" />

The assembly was imported into Blender for visualization and presentation.

Tasks included:

* Part separation
* Material assignment
* Lighting setup
* Camera configuration
* Scene organization

### Phase 4 – Engineering Visualization


Additional visual assets were created:

* Beauty renders
* Exploded views
* Propellant flow visualizations
* Technical presentation graphics

---

## Material Development

Material choices were selected to visually distinguish major subsystems while maintaining an aerospace-inspired appearance.

### Tanks

Appearance:

* Brushed aluminum style

Purpose:

* Represent lightweight structural hardware
* Improve subsystem identification

### Feed Pipes

Appearance:

* Stainless-steel style finish

Purpose:

* Increase visibility of flow routing
* Provide contrast against tanks

### Turbopumps

Appearance:

* Dark titanium-inspired metal

Purpose:

* Communicate dense mechanical hardware
* Separate turbomachinery visually from surrounding systems

### Injector

Appearance:

* Polished metallic finish

Purpose:

* Draw attention to the engine's primary mixing interface

### Combustion Chamber and Nozzle

Appearance:

* Dark Inconel-inspired material

Purpose:

* Represent high-temperature engine components
* Emphasize the propulsion core of the system

---

## Propellant Flow Visualization

<img width="1918" height="1078" alt="Screenshot 2026-06-07 223221" src="https://github.com/user-attachments/assets/42c15d83-30d3-4297-a35b-f0ca05cae4b6" />


A simplified flow visualization was developed to communicate engine operation.

Color Convention:

* Blue: Oxidizer flow path
* Orange: Fuel flow path

The visualization was designed to improve understanding of system architecture rather than simulate physical fluid behavior.

---

## Exploded View

<img width="1918" height="1078" alt="Screenshot 2026-06-07 154559" src="https://github.com/user-attachments/assets/840edffc-3a1c-4e50-bc2a-9b64b5604136" />

An exploded assembly view was created to reveal subsystem relationships and overall engine organization.

This visualization helps communicate:

* Component hierarchy
* Assembly structure
* Flow path routing
* Mechanical layout

---

## Software Used

* FreeCAD
* Blender
* GitHub

---

## Documentation

Additional project documentation:

* Material Summary
* Design Notes
* Rendering Configuration
* Visualization Workflow

See the Documentation folder for detailed files.

---

## Development Videos

Project progress videos:

* CAD development
* Assembly progress
* Visualization workflow
* Rendering development

Links available in the Media folder.

---

## Skills Demonstrated

* CAD Modeling
* Engineering Visualization
* Rocket Propulsion Fundamentals
* Technical Documentation
* Design Iteration
* Rendering and Presentation
* Engineering Communication
* Project Organization

---

## Future Improvements

Planned future work includes:

* Sectional cutaway renders
* Nozzle thermal visualization
* Turbine exhaust visualization
* Animated propellant flow
* Improved technical drawings
* Additional engineering documentation

---

## Disclaimer

This project is an educational engineering portfolio project intended to demonstrate propulsion-system architecture, CAD workflows, and engineering visualization techniques. It is not intended to represent a flight-qualified engine design or a validated propulsion simulation.

