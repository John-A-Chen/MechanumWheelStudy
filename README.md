# MecanumWheelStudy  
An open-source exploration of low-cost, 3D-printable mecanum wheels designed to make omnidirectional robotics more accessible to students, hobbyists and educators.

---

## Overview  
Mecanum wheels are extremely useful for robotics projects—allowing holonomic movement, fine control, and tight manoeuvring.  
But they are also **ridiculously expensive** for beginners.  
My friends bought a set of four for about **$90 AUD**, and when I took the same subject earlier I couldn’t afford them at all.

This project exists because these mechanisms **shouldn’t be locked behind high prices**.  
So this repository documents an attempt to design, model and refine a **fully open-source, tolerance-aware, 3D-printable mecanum wheel** that anyone can manufacture.

Everything here is experimental and iterative, with the long-term goal of making a robust, reproducible design that anyone can print.

---

## Project Goals  
- Create an open-source mecanum wheel design that is affordable and reproducible  
- Provide proper tolerances for FDM printing (no mystery dimensions)  
- Explore wheel geometry, roller angles, hub strength and print orientation  
- Study how roller shape affects friction, smoothness, and holonomic performance  
- Eventually release proper slicer settings or a MakerWorld profile for plug-and-play printing  
- Make mecanum wheels accessible to students who can’t justify expensive commercial sets  

---

## Motivation  
Commercial mecanum wheels are:  
- overpriced  
- opaque in design  
- inconsistent in quality  

There’s no reason the fundamentals of these wheels should be hidden or locked behind proprietary designs.  
By open-sourcing the models, students can:  
- learn how the geometry works  
- modify designs for assignments  
- repair broken rollers easily  
- scale wheel sizes up or down  
- improve the design with community contributions  

Robotics should be something everyone can participate in—not something limited by budget.

---

## Features  
- Parametric CAD (solid modelled from scratch)  
- Roller housings with adjustable tolerances  
- Robust hub design suited for hobby motors  
- Approximated 45° roller geometry for omnidirectional movement  
- 3D-printer-friendly dimensions and part separation  
- Designed for iterative testing and educational use  

More refinements will be added as real-world testing continues.

---

## CAD + Printing  
All CAD is produced in SolidWorks.  
STL files are included (or will be added as designs stabilise).  
Print tolerance information will be included soon.

Planned additions:  
- MakerWorld link for ready-to-use print profiles  
- Recommended infill, supports and filament types  
- Strength-tested assembly versions  
- Better roller pin designs  

---
## Repository Structure  
```

/cad            SolidWorks source files
/print          File exports for printing
/docs           Notes and references
README.md       Documentation

```


---

## Why This Matters  
Mecanum wheels open up a world of robotics possibilities: strafing, diagonal motion, precision alignment, full holonomic control.  
They’re powerful tools—but the price barrier stops many students from ever trying them.

By making an open-source version with tolerances and full documentation, this project aims to give every student the chance to experiment with omnidirectional drive systems without breaking the bank.

---

## Future Work  
- Print testing with different tolerances  
- Strength testing under load  
- Improved roller axle mechanism  
- Modular wheel sizes  
- Assembly guides  
- Video demonstrations  
- Fusion 360 parametric versions  
- ROS2 kinematic models (maybe)  

---
