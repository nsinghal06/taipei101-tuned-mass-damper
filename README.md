# Structural Vibration Modeling – Taipei 101 Tuned Mass Damper 
This project analyzes how the 660-ton tuned mass damper (TMD) installed in Taipei 101 mitigates wind-induced oscillations in the skyscraper. The project combines mathematical modeling, Python simulations, and engineering analysis to demonstrate the effectiveness of TMDs in reducing structural sway. Developed as part of MAT187 Calculus II Mini-Project.

## Overview  
- Modeled Taipei 101 as a **2-DOF mass-spring-damper system** using Newton’s Second Law.  
- Derived and analyzed **coupled differential equations** representing building motion with and without a TMD.  
- Implemented **Python simulations (NumPy, )** to evaluate dynamic responses under sinusoidal wind loads to compare displacement of the building alone vs. coupled with the TMD.
- Documented findings in a technical report integrating mathematical derivations, computational analysis, and real-world implications for structural engineering.

## Key Results  
- Without a TMD, Taipei 101 experiences steadily increasing displacement under harmonic wind loads, but with a 660-ton TMD tuned to the building’s natural frequency, **out-of-phase** oscillations significantly reduce displacement and improve stability.
- Simulations confirm that the TMD absorbs and dissipates a large portion of wind energy, validating its effectiveness as an engineering solution.

## Repository Details
The repository includes: 
- A technical report (([Structural Vibration Modeling – Taipei 101 Tuned Mass Damper .pdf](./Structural Vibration Modeling – Taipei 101 Tuned Mass Damper .pdf))) with mathematical derivations, analysis, and engineering implications.
- Python code () implementing the 2-DOF coupled oscillator dynamic model.
- Simulation graphs () showing the comparison of displacement with and without the TMD.

## Technologies Used
- Python (NumPy, SciPy, Matplotlib, Pandas)  
- Differential equations and damping concepts  
- Structural dynamics and tuned mass dampers

## Authors

