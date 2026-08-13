# Special Topics in Computational Physics: Computational Fluid Dynamics

## Yachay Tech University - 2026

## About this repository:
This is a collection of lecture notes and programming exercises carried out as part of the Special Topics in Computational Physics course at Yachay Tech University, which in this edition is devoted to computational fluid dynamics.

## Lecturer:
Wladimir E. Banda-Barragán

## Course description:
This course develops computational fluid dynamics as a current research topic in computational physics, using specialised computing, simulation and visualisation tools throughout. Starting from the fundamental properties of fluids, hydrostatics and control-volume analysis, it builds the differential formulation of fluid motion and the numerical methods used to solve it. Each unit combines the underlying theory with the design, implementation and validation of numerical solvers, and with the analysis and visualisation of the resulting simulation data.

## Programming languages and tools:
- We work in Linux environments throughout the course.
- Python is our main language.
- We will possibly also use C++ and Julia, where execution speed matters.
- Open-source flow solvers are used as benchmarks for verification and validation.

## Syllabus:

### UC.1 Fluids, conservation laws and a first solver
- Fluid properties, the continuum hypothesis, viscosity, and surface tension
- Fluid statics: pressure distribution, manometry, hydrostatic forces, and buoyancy
- Control-volume analysis: conservation of mass, momentum and energy; Bernoulli's equation
- From conservation laws to computation: grids, discretisation, and a first advection solver

### UC.2 Kinematics, transport and numerical stability
- Flow kinematics: Lagrangian and Eulerian descriptions, material derivative, streamlines and pathlines
- Linear and nonlinear transport: wave steepening and shock formation in Burgers' equation
- Diffusion, the CFL condition and numerical stability: numerical dissipation and dispersion
- Finite-volume formulation: conservative fluxes, boundary conditions, and verification tests

### UC.3 Differential analysis and viscous flow
- Differential analysis: continuity and Navier–Stokes equations, stream function, and vorticity
- Exact solutions and potential flow: Couette and Poiseuille flow, and elementary flow superposition
- Advection and diffusion in two dimensions: the vorticity–streamfunction formulation
- Pressure–velocity coupling: the pressure–Poisson equation and projection methods

### UC.4 Incompressible solvers, similitude and validation
- Two-dimensional incompressible solvers: lid-driven cavity and channel flow
- Flow past a cylinder: vortex shedding, Strouhal number, and wake structure
- Dimensional analysis, the Buckingham Pi theorem, similitude, and dimensionless groups
- Verification and validation: grid convergence, benchmark data, and open-source flow solvers

### UC.5 Internal and external flow, boundary layers and turbulence
- Laminar and turbulent internal flow: velocity profiles, friction factors, and the Moody chart
- Boundary layers: displacement and momentum thickness, transition, and flow separation
- Drag and lift on immersed bodies: pressure and friction contributions, and aerofoil polars
- Turbulence: the energy cascade, statistical description, and turbulence modelling in simulations

### UC.6 Compressible flow, instabilities and large-scale simulation
- Compressible flow: speed of sound, Mach number, isentropic relations, and nozzle flow
- Shocks and expansion waves: the Riemann problem and Godunov-type finite-volume schemes
- High-resolution methods and hydrodynamic instabilities: Kelvin–Helmholtz, Rayleigh–Taylor, Richtmyer–Meshkov
- Beyond grid-based serial solvers: parallel domain decomposition and mesh-free particle methods

## Full Course Syllabus and Programme:
The full course syllabus can be found here:
- For BSc in Physics: *(link to be added)*

## References and bibliography:
1. Munson, Bruce; Okiishi, Theodore; Huebsch, Wade; Rothmayer, Alric, *Fundamentals of Fluid Mechanics*, 7th Edition, 2013.
2. Toro, Eleuterio F., *Riemann Solvers and Numerical Methods for Fluid Dynamics*, 3rd Edition, 2009.
3. Çengel, Yunus; Cimbala, John, *Fluid Mechanics: Fundamentals and Applications*, 3rd Edition, 2014.
4. White, Frank M., *Fluid Mechanics*, 7th Edition, 2011.


## Evaluation:
Evaluation has 4 components, each worth 25 %, distributed evenly over the two terms of the period (12.5% + 12.5% each):

**1. Quizzes:** 25%
**2. Homework defences:** 25%
**3. 1 Midterm Exam:** 25%
**4. 1 Final Exam:** 25%

**All defences are written and closed-book.**

## On deadlines:
The assignment deadlines and exam dates will be discussed and agreed upon in class. Once fixed, all deadlines are hard deadlines.

## Weekly class schedule:
- 17:00 - 19:00 Tuesday
- 17:00 - 19:00 Wednesday
- 13:00 - 15:00 Thursday

## Weekly tutoring schedule:
If you have questions on the material, you can find me in the office:
- 16:00 - 17:00 Tuesday
- 16:00 - 17:00 Wednesday

Location: 2nd floor, Senescyt Building, or on Zoom.

## Class attendance:
- As per regulations of the Vicerrector's office of Yachay Tech, you should attend 70% of the classes to pass the course.

## On academic integrity:
- Students are responsible for ensuring the academic integrity of their submitted assignments and exams.
- Cheating in exams, plagiarising, and copying code or solutions from other students, from previous years' solutions, and/or from Internet sources are all breaches of academic integrity.
- The above includes copying code from AI chatbots (which are neither designed nor optimised for physics and programming), e.g. copying and pasting code from chatGPT infringes academic integrity.
- Academic misconduct will be penalised according to our University's regulations.

## Late assignment policy:
Late assignments accompanied by appropriate justification (e.g. an official medical certificate, etc.) will receive no penalisation. Late assignments without appropriate justification will receive a penalisation of **-1% per late hour**.

## Useful repositories:
- Data repository: https://github.com/wbandabarragan/physics-teaching-data
- Computational Physics I: https://github.com/wbandabarragan/computational-physics-1
- Computational Physics II: https://github.com/wbandabarragan/computational-physics-2
- Archived versions of the CP1 course taught in previous semesters: https://github.com/wbandabarragan/computational-physics-1-arxiv
