# 4-Stroke Engine: 3D Kinematic & Dynamic Stress Analysis ⚙️🚀

## Project Overview
This repository contains the complete 3D CAD modeling, kinematic motion study, and Finite Element Analysis (FEA) of a 4-stroke engine mechanism. The objective of this project was to bridge the gap between static mechanical design and dynamic simulation by extracting real-world inertial forces and transferring them into structural stress tests.

## Engineering & Simulation Highlights
* **Kinematic Motion Analysis:** Configured rotary motors, solid body contacts, and gravity parameters to simulate the continuous 360-degree rotational cycle of the crankshaft and piston assemblies.
* **Dynamic Load Transfer:** Exported exact dynamic pin reaction forces and inertial loads from specific milliseconds of the motion timeline directly into SolidWorks Static Simulation.
* **Structural Validation (FEA):** Evaluated von Mises stress gradients across the connecting rods and generated Factor of Safety (FOS) plots to validate the engine block's structural integrity under peak loads. 

## Technical Specifications & Materials
The following materials were applied to the assembly to accurately calculate mass, momentum, and yield strength:
* **Crankshaft:** AISI 4340 Steel (High-strength alloy for torsional fatigue resistance)
* **Connecting Rods & Caps:** Plain Carbon / AISI 4340 Steel
* **Pistons:** 6061-T6 Aluminum Alloy (Low mass to reduce inertial forces)
* **Piston Pins:** Alloy Steel
* **Piston Rings:** Gray Cast Iron

## Repository Contents
* **`/Parts`**: Contains all native SolidWorks part files (`.SLDPRT`) including the piston, rings, connecting rod, cap, pin, and crankshaft.
* **`Assem2.SLDASM`**: The master SolidWorks assembly file containing all mates and motion study definitions.
* **`Engine_Universal.STEP`**: A universal 3D CAD file (STEP AP214) for viewing the assembly in non-SolidWorks software.
* **`/Media`**: Contains `.avi` video exports demonstrating the kinematic motion, real-time stress overlay, and deformation plots.

## How to View
To interact with the native files, you will need **Dassault Systèmes SolidWorks**. 
1. Download or clone this repository to your local machine.
2. Open `Assem2.SLDASM`. (Ensure all `.SLDPRT` files remain in the same directory so the assembly can locate them).
3. Universal viewers (like Autodesk Viewer or eDrawings) can be used to open the `.STEP` file if SolidWorks is unavailable.

## Authors & Credits
* **Muhammad Aqib Bashir** - *Mechatronics Engineering, National University of Sciences and Technology (NUST), CEME*
