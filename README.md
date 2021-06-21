# Files BEP Robustness MPC

2 files are located in this repository.
MPC_experiments.zip
PNLSS_estimation.zip

## MPC_experiments (derived from Master Thesis M.M.P. Floren https://research.tue.nl/en/studentTheses/a-robust-data-driven-model-predictive-control-approach-towards-fe)

This folder contains all files to run the MPC experiments on the flexible beam setup.
The base file is named runMPCFreeBeam.m. Running this file starts the simulation and 
automatically provides the NLDA's and the rms values for the selected alpha value. 

Closed_loop_MPC.mdl is the corresponding Simulink model. 

SingleSidedSpectrum2TimeDomainSignal.m is the function that translates the output spectrum
to time domain signals. 
This is used to calculate the rms values. 

## PNLSS_estimation (derived from Schouckens PNLSS software http://homepages.vub.ac.be/~jschouk/#)

This folder contains all files to estimate a new PNLSS model. This is a work in progress since
it has not been achieved to estimate the PNLSS model correctly.

The base file is PNLSS_Est.m, this file automatically estimates a new PNLSS model.
