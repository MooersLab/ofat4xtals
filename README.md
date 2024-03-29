# Varying One Factor at a Time (OFAT) Experimental Designs for Crystallization Experiments

![Version](https://img.shields.io/static/v1?label=ofat4xtals&message=0.1&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


## Purpose
This repository contains Excel spreadsheets for applying OFAT Designs (OFATs) to the size optimization of crystals of biological macromolecules (proteins and nucleic acids).
Crystal size is generally proportional to its diffraction power, provided that the crystal is not internally disordered and that it was properly cryoprotected.
Crystallographers seek large crystals to obtain high-resolution data for high-quality structures.

## What are OFAT experiments
These OFAT experiments involve holding all factors constant except for one while it is varried over several factor levels. 
We recommend the that the variation start at 0 so that one can also test whether the presence or absence of a factor has an influence on crystal growth. 
We also recommend using four factor levels including the zero level so that the three points that have the factor present can be used to assess whether or not the response is linear or curvilinear.

Most factors are expected to have a curvenier effect on crystallization of biological molecules.
The effect might appear to be linear if the range of factor levels being tested is narrow.
In this case, you might actually be exploring only the rising or falling shoulder of a quadratic response.
This is a very minimal approach to trying to detect the curvilinear response.
Five or six levels might be more appropriate to for the better characterization of the curvilinear your nature of the response.

This is about all you can expect out of these kind of experiments.
You might be able to propagate your lead when you are testing factors that have no influence on crystallization.
This might be a side benefit if the crystallization conditions are close to the optimum.

These fat experiments are a horrible way to try to find the optimal conditions when you apply them in serial fashion.
they should probably be limited to initial expiration of the nature of a factor in terms of whether it is presence has an effect and in terms of detecting a curvilinear response.
this information can then be used to select the factors and their levels in a full factorial, incomplete factorial, or optimal experimental designs.
These latter designs are capable of detecting at least two-way interactions in addition to quadratic responses.

## Replication and randomization
These spreadsheets contain replica OFAT experiments.
the treatments within the replicas are randomly assigned.
each of that experiment is treated as a independent experiment, so there is no randomization across of ofat experiments.




## Customizing the design for you experiment
It takes about 3 minutes to edit a spreadsheet to customize it for a new crystallization experiment.
These spreadsheets ease applying DSDs in laboratory experiments.
These spreadsheets could also be adapted to other laboratory and field experiments.
Please post an issue if you need a design with a run configuration that differs from a 4 x 6 array.
