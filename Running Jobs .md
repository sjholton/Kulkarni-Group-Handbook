### Chapter Contents
- running/checking on jobs
- optimization
- vibrations
- MD
- NEB
- MC
- Metadynamics

### Optimization
#### theory
- optimization finds the lowest energy configuration of your atoms
- the energy of the optimized state is the electronic energy of the state and is used in energy diagrams
#### how-to
- set encut to [], set ibrion to [] ...
- kul-group code for optimization [link]
#### tips
- start with a reasonable initial structure, a bad guess can lead to adsorbates falling apart
- submit jobs for the right amount of time so your job isn't in the queue too long
- check the final structure after optimization to make sure it is reasonable

### Vibrations

#### tips
- make sure the optimization before vibration run has the same ENCUT and ediff
- set NSW=1 !!!
### Molecular Dynamics

- http://devonwa.com/2016/09/01/installing-and-using-LAMMPS-with-ASE/

### Nudged Elastic Band

### Monte Carlo

### Metadynamics

