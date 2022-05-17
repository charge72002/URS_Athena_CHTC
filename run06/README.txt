Sherry Wong
bwong24@wisc.edu
5 May 2022

Running first highres long-term simulation. 
- alpha=beta=0.2
- increased randAmplitude from 10e-4 to 10e-2
pgen:
- FIXED theta to be selected from 0 to 2pi
- TEMPFIXED amplitude of perturbation
athena_run_single:
- Increased node request from 2 to 4
- Added -t flag to make a restart file if necessary
