## cell-signaling
The price of information transfer in living cells

Here we provide the detail of the [chemical Langevin approximation](https://github.com/hincz-lab/cell-signaling/blob/master/chemical_Langevin_approximation.nb) of the enzymatic push pull loop and hence the [algorithm](https://github.com/hincz-lab/cell-signaling/blob/master/derivation_of_Fig_3.nb) to reproduce scatter points (green and blue clouds) in Fig. 3 of the maintext (shown as follows).

Note: Apply our mathematica notebook with mathematica v.11 or higher.


[chemical Langevin approximation](https://github.com/hincz-lab/cell-signaling/blob/master/chemical_Langevin_approximation.nb): In this notebook, we provide the details of chemical Langevin solution, the coefficients of power spectra, the variances of input X/output Y, and hence the mutual information as a function of &gamma;<sub>k</sub>, &kappa;<sub>-r</sub>, &rho;<sub>-r</sub> and parameters choice. Using our result for mutual information, one can easily reproduce the following Fig. A and B.     

[derivation_of_Fig_3](https://github.com/hincz-lab/cell-signaling/blob/master/derivation_of_Fig_3.nb): In this notebook, we provide the algorithm to reproduce scatter points (green and blue clouds) in figure D to I (shown as follows). Insert our [data](https://github.com/hincz-lab/cell-signaling/tree/master/data) for 1/1.5/2 bits generated by this algorithm, one can easily reproduce figure C. 

![Image of clouds](https://github.com/hincz-lab/cell-signaling/blob/master/clouds.png)
