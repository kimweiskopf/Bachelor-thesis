# Kim Bachelor Thesis

This repository contains the central python scripts used in my Bachelor thesis. Those skripts allow you to plot the migration rate and torque for a system with two massive, gap opening planets, over a range of r_p. I would suggest you to read or skim over my thesis first, so that all introduced variables in these scripts are known to you.

The 'alle resonancen np.where' file plots all the introduced Lindblad resonance locations in my Bachelor thesis for comparison.

The files 'Migrationrates_final_withoutBM08' and 'Migrationrates_final_withBM08' compare the migration rates from my simulations to those calculated by the scripts.


# Lindblad resonance locations

The folder 'Lindblad resonance locations' contains three python scripts for D_p, D_p_star and D_K. D can be solved analytically. Starting the 'locations scripts' gives you a dat file with the locations for a certain range of m and r_p, which can be specified in the scripts. The scripts 'start ...' starts the location script several times and changes some parameters like the aspect ratio or Flaringindex between each run. Also the mean motion resonance in which the planets are can be specified (the defaut is a 2:1 MMR).

# Torques

The folder 'torques' contains the scripts for the torques in combination with a Lindblad resonance equation. Running them gives you a plot of the torque and migration rate for your system of two planets with the specified physical parameters which can be found in the beginning of the script. In the end the migration rate at a specific location defined by the file datanew is writtem in a file.

The torque scripts can be run with the 'schnellstart' file and this file changes some physical parameters between the runs of the torque scripts. The current datanew file contains the datapoint from my simulations but can also be changed.

# fargo 3D
In the folder named 'fargo 3D', there is an exaple par file and opt file I used for my simulations as well as the potential.c file I used, which I changed from the original code.
