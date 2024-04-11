# Isentropic-Supersonic-Nozzle-in-SU2
Spring 2024 Compressible Flow Project
This project utilizes SU2 to study isentropic supersonic flow in a convergent-divergent nozzle as part of a project for the class MANE-6960 Compressible Flow.

An outline for the top half of the nozzle is generated using MATLAB in the form of a .GEO file. 
An SU2-compatible file is generated from the .GEO file using GMASH.
A configuration file for an isentropic supersonic nozzle with the appropriate boundary conditions and initial conditions will be developed using modified SU2 templates. 
With the SU2 CFD solver, a fluid dynamics simulation of the CD nozzle is run to produce Navier-Stokes solutions. 
Results are visualized via Paraview. These results will be compared to the Method of Characteristics solver in MATLAB for validation of accuracy.
