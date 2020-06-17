
### Tips
- jupyter trick for code dev on hpc
- automate logins to hpc
- use ase.db
- automated rsync
- scripts on hpc to quickly do repetitive tasks
- code for getting papers off campus
- folder organization
- reading papers and organizing lit
- presentation tips, how to do a lit review

### Sticking points
- vasp scripts crashing (check header is correct, use debug queue, fix environment variable, make sure modules are loaded)
- optimization/vibration output is bad, how to fix
- neb tips (opt fs and use vasprun for is .. )
- python scripts crashing (start with really simple problem, make sure PATH is set up, break into separate subtestable scripts, print internal variables)
- python code not running on hpc: make sure utf8 header is there, chmod u+x, in bin folder

HPC1 
There seems to be difference between different CPUs. I find that c6-XX (Intel(R) Xeon(R) Silver 4110 CPU @ 2.10GHz) is faster than c5-XX ( Intel(R) Xeon(R) CPU E5-2630 v3 @ 2.40GHz). If you find similar behavior with other codes (I tested cp2k), please let me know. 


CP2K 
Metadynamics - Be careful about the units being used. CP2K defaults into internal_cp2k while providing output, we usually care about Ang. 
Indexing - cp2k counts from index 1 .. N, while ASE/VMD starts from index 0 


