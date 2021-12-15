# covid-bifurcation-analysis
### Authors
Ian Thomas, Ishaan Rajan, Tanner Watts.

### Overview
This is the final project for MathBio 5110. We analyzed the differential equations from "COST-EFFECTIVENESS AND BACKWARD BIFURCATION ANALYSIS ON COVID-19 TRANSMISSION MODEL CONSIDERING DIRECT AND INDIRECT TRANSMISSION" a paper written by DIPO ALDILA (Department of Mathematics, Universitas Indonesia, Depok 16424, Indonesia) https://doi.org/10.28919/cmbn/4779.

### Tools
The analysis used Python as the main programming language. Google collab was the lightweight online IDE we used to collaborate on the analysis. Mathematically, Euler's method was used to solve the differential equations. And Matplotlib was used for the figures.

### How to Run Simulation
Use the open in google colab button, and the simulation will be loaded into colab. After loading information, simply compile the first block by pressing run. After the first block has run, the figures can be recreated by running the rest of the blocks. Pressing run all will also run every block in the correct order. To use the function on other parameters simply type runSimulation() with 3 double values to run on different values. The runSimulation() function will generate 3 figures, Susceptibility, Covid Infection Population, and Viral Particles (in that order).
