# progs
Implementation of QM/MM simulation algorithms doable with Fireball.

This repository realizes several algorithm to perform 
quantum mechanical/molecular mechanical simulations using
Fireball's methodology.


Downloading / Getting the program
---------------------------------

        git clone https://github.com/fireball-QMD/progs 


Installation
------------

        cd progs     # change directory to the root of the Fireball project.
        
        Edit the Makefile in this directory and choose a MACHINE option.
        The purpose of this is in a correct definition of F90 and F77 
        variables for compilation. If you choose GLINUX, it should use
        gfortran for both variables and thus usable on most Linux systems.
        
        make         # compilation of the code
 
Usage
-----

