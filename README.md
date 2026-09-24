# Wind Turbine Aerodynamic Modelling
Python-based modelling of wind turbine blade aerodynamics, forces, torque and mechanical power, with an interactive simulation.

## Project Overview
This project delves into the impact of blade characteristics and operating conditions on the aerodynamic forces and power generation of wind turbines.

The model develops progressively from analysing individual airfoil sections to modelling aerodynamic forces along a blade and calculating the resulting torque and mechanical power of a complete wind turbine.

## Current Work
- Modelling aerodynamic lift and drag using simplified aerodynamic relationships.
- Applying blade geometry based on the NREL 5-MW Reference Wind Turbine.
- Calculating aerodynamic forces along the blade.
- Investigating tangential forces, torque and mechanical power.
- Developing an interactive simulation to explore the influence of operating conditions and blade characteristics.

## Interactive Simulation
Watch a small clip of the interactive simulation:

https://github.com/user-attachments/assets/7cd4f35b-ed0a-471e-b20b-68ea107836d1

## Development
The project is developed primarily in Python, with HTML used to support the interactive simulation. Numerical calculations and data visualisation are used to explore the aerodynamic behaviour of wind turbine blades.

The model is intended as a learning and exploration tool. Its assumptions and limitations are considered throughout development, including relative velocity, axial induction, stall correction and tip vortex effects.

## Technologies
- Python
- HTML
- NumPy
- SciPy
- Matplotlib (including 3D visualisation)
- Jupyter Notebook
- Interactive Widgets

## Further Development
- Improve the accuracy of the aerodynamic model by accounting for additional limitations, such as dynamic wake effects.
- Investigate the effect of different operating conditions and blade parameters.
- Develop further interactive visualisations.
- Compare model results with relevant theoretical expectations and reference data.

## References

[1] Anderson JD. *Introduction to Flight.* 3rd ed. New York: McGraw-Hill; 1989.

[2] Jonkman J, Butterfield S, Musial W and Scott G. *Definition of a 5-MW Reference Wind Turbine for Offshore System Development* [online]. Golden, CO: National Renewable Energy Laboratory; 2009. https://docs.nlr.gov/docs/fy09osti/38060.pdf.

[3] Moriarty PJ and Hansen AC. *AeroDyn Theory Manual* [online]. Golden, CO: National Renewable Energy Laboratory; 2005. NREL/TP-500-36881. https://docs.nlr.gov/docs/fy05osti/36881.pdf.

[4] Hynes CS, Hardy GH and Sherry L. *Synthesis from Design Requirements of a Hybrid System for Transport Aircraft Longitudinal Control* [online]. Volume II. Moffett Field, CA: NASA Ames Research Center; 2007. p. 16. https://ntrs.nasa.gov/api/citations/20120003268/downloads/20120003268.pdf.

[5] Cornell University. *Aerodynamic Background* [online]. Ithaca, NY: Cornell University; n.d. https://courses.cit.cornell.edu/mae5070/AeroBackground.pdf.

[6] Zheng X, Yao Y, Hu Z and Hu S, *Influence of Turbulence Intensity on the Aerodynamic Performance of Wind Turbines Based on the Fluid-Structure Coupling Method* [online]. *Applied Sciences.* 2023;13(1):250. https://doi.org/10.3390/app13010250.

[7] Scholz D. *13 – Drag Prediction* [online]. Hamburg: Hamburg University of Applied Sciences; n.d. https://www.fzt.haw-hamburg.de/pers/Scholz/HOOU/AircraftDesign_13_Drag.pdf.
