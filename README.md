# improved-fiesta
Computational Physics 2019 Assignment #2
Results in the report were arrived at using Python 3 notebook with Anaconda on Windows 10.

TDSE does the following:
  - Solves the SE for a particle in a box with or without a potential barrier in the middle third of the box
  - Calculates analytic results for the solutions to the SE for a free particle in a box (no potential barrier) and compares the results
  - Calculates a solution to the time-evolution of the wavefunction with a choice of three initial conditions:
    - 1st analytic solution for free particle in a box
    - Delta function (spike localized in the middle of the box)
    - Superposition of 1st and 2nd numerical states
  - Creates an animation for quantum tunneling*
  - Plots the root equation, visualizes negative slope in the function, and finds roots based on numerical eigenvalues
*Animations may require that one calls the animation a second time in another cell after the main program is run.

Crank-Nicolson does the following:
  - Solves the SE for a particle in a box with or without a potential barrier in the middle third of the box USING CRANK-NICOLSON instead
  - Generates animations and figures for the time-evolution of states (note: only tested for initial condition = superposition, option 2)
*As before, animation may require calling the animation a second time in another cell after the main program is run.
