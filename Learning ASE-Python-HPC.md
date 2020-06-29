### Learning ASE/Python/HPC

#### ASE

##### Getting Started with ASE
- make sure you have ase downloaded and on your anaconda PATH -> the `import ase` command in the python command line should give no errors

##### ASE Practice Problems
- First, download a structure from the internet (e.g. from this [zeolite database](https://asia.iza-structure.org/IZA-SC/ftc_table.php))or from someone in the group
- Move the structure to the folder where you are writing and running practice scripts
- Write a new script with the following:

``` 
from ase.io import read, write
a = read('STRUCTUREFILE') 
```
Where STRUCTUREFILE is the name of the structure file you downloaded.
'a' is an object with the positions of the atoms in your structure, you can manipulate this to complete the practice problems below.

#### Python

##### Getting started with Python
Make sure you have Anaconda downloaded and an IDE to write code in. Set up your folders and path ... 
See [this page](https://github.com/kul-group/Group-Handbook/blob/master/Programming.md#programming) for group coding guidelines.

##### Python Practice Problems
- see [here](http://www.practicepython.org/) for good python practice problems. Once you are comfortable with manipulating lists, for loops, and if/else statements, focus on the ASE practice problems.

#### HPC

##### Getting Started on HPC: Logging in
Make sure you have an account with the HPC you want to log in to. HPC account creation [here](https://github.com/kul-group/Group-Handbook/blob/master/Account%20Setup.md#essential). You will need your account information and (possibly) your 2FA set up to log in.
- In your command line, type ```ssh -XY username@address``` and hit enter. where 'username' is your account username and 'address' differs based on the hpc you are logging into:
HPC1: address=hpc1.cse.ucdavis.edu 
Stampede: address=stampede2.tacc.utexas.edu
cori: address=cori.nersc.gov

- you will be prompted for your password and your 2FA, no dots or letters will show up as you type, just type each and press enter.

##### Getting Started on HPC: Basic Commands
This is a basic introduction to the most commonly used bash commands. A more detailed tutorial can be found [here](https://github.com/kul-group/Group-Handbook/blob/master/Command%20Line.md#command-line)


