# Caucasus DZ
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dyvasey/dz-caucasus/HEAD)

This repository consists of data and code used to analyze existing detrital zircon U-Pb data from the Greater Caucasus. It is primarily intended as an archive of how data analysis and figure construction were done for manuscript preparation. 

The code relies heavily on the package [geoscripts](https://github.com/dyvasey/geoscripts), which is intended for broader reusability.

## Use
The code is primarily housed with Jupyter Notebooks, which are intended to be run using the conda environment specified in `environment.yml`. The easiest way to do this is by clicking the Binder badge at the top of the README and then running the individual Jupyter Notebooks. The suggested workflow is:

1. Run `process_caucasus.ipynb` and `process_eecgond.ipynb`. These do some initial data processing needed for the other notebooks.
2. Run `figs.ipynb` to see the bulk of main text detrital zircon figures included in Vasey et al. (in prep).
3. Run `hf.ipynb` to see construction of Figure 5 in Vasey et al. (in prep).
4. Run `supp.ipynb` to see construction of supplementary figures in Vasey et al. (in prep).
5. Run `supp_tables.ipynb` to see construction of supplementary tables in Vasey et al. (in prep).

## References
Vasey, D.A., Garcia, L., Cowgill, E., and Godoladze, T., in prep., Episodic evolution of a protracted convergent margin revealed by detrital zircon geochronology in the Greater Caucasus: _Solid Earth_.





