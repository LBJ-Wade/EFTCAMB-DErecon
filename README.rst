===================
EFTCAMB mods
===================
:CAMB:  Code for Anisotropies in the Microwave Background, Fortran 95 code
:Homepage: http://camb.info/

:EFTCAMB: Effective Field Theory in CAMB, Fortran 2008 code, https://github.com/EFTCAMB 

Description and installation
=============================

For full details email azucca@sfu.ca

uses Fortran 2008, requires ifort or gfortran v6

Install:
- `$ make clean`
- `$ make eftcamb_dep`
- `$ make eftcamb_apps`

Running instructions
=============================

./xDE_sampler_sources params_counts.ini

Branches
=============================

The master branch contains latest changes to the main release version.

CAMB_sources is the updated public `CAMB Sources <http://camb.info/sources/>`_ code.

The vehre_formatted branch is a developement version, which integrates CAMB and CAMB sources, and uses Fortran 2008 (and hence requires gfortran 6).
This branch also has an integrated test suite, which runs on Travis automatically for new commits.
