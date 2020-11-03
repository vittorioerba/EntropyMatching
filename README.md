# Material for the paper "The number of optimal matchings for Euclidean Assignment on the line"

This repository contains the code, the data and the analysis notebooks to reproduce the results of "The number of optimal matchings for Euclidean Assignment on the line".

You will find:
- ```simulations.jl```: a Julia file containing the code to perform the simulations;
- ```data```: a folder containing the result of the simulations. File names record:
    1) the ensamble simulated: ```exc``` for escursions, ```brd``` for bridges;
    2) the size of the paths simulated ```Npts```;
    3) the number of random paths simulated ```Nsim```.

    Each line of the file contains the non-rescaled entropy associated to a path in scientific notation;
- ```figures.nb```: the Mathematica notebook used to plot the simulations.

