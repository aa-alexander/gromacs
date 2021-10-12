# GROMACS - Protein Ligand Complex

## Introduction

Script to run molecular simualtion in gromacs for Protein-Ligand complex using acpype force field.

I have changed some steps from the official tutorial for acpype. The link for the acpype protein ligand complex tutorial : https://github.com/alanwilter/acpype/blob/master/acpype_gmx_tutorial.md

The tutorial for protein ligand complex in gromacs website is also available. The link for that tutorial is : http://www.mdtutorials.com/gmx/complex/01_pdb2gmx.html

This is the script I used for running my simulation. I will also attach the .mdp files used by me. 

## Installation

For running gromacs using acpype force field you need to install **gromacs, acpype, antechamber, avogadro** installed. The installation is easy with conda and docker installed. I highly recommend docker for easy installation. 

If you have gromacs installed in your system, it is great. If not you can install gromacs by using conda. Create a new environment.

+ `conda create -n gromacs`                #creating a new environment
+ `conda activate gromacs`                 #activating the environment

Installing Gromacs

+ `conda install -c bioconda gromacs`      #installing gromacs

Installing antechamber

+ `conda install -c conda-forge ambertools=21 compilers`

Also install **`avogadro` program** : https://sourceforge.net/projects/avogadro/

Installing and using `acpype` is easily done with docker. 

## Running Gromacs
