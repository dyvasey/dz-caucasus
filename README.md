# Caucasus DZ
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dyvasey/dz-caucasus/HEAD)

This repository consists of data and code used to analyze existing detrital zircon U-Pb data from the Greater Caucasus. It is primarily intended as an archive of how data analysis and figure construction were done for manuscript preparation. 

The code relies heavily on the package [geoscripts](https://github.com/dyvasey/geoscripts), which is intended for broader reusability.

## Use
The code is primarily housed with Jupyter Notebooks, which are intended to be run using the conda environment specified in `environment.yml`. The easiest way to do this is by clicking the Binder badge at the top of the README and then running the individual Jupyter Notebooks. The suggested workflow is:

1. Run `process_caucasus.ipynb`, `data_processing/proc_agecalc.ipynb`, and `process_eecgond.ipynb` in any order. These do some initial data processing needed for the other notebooks.
2. In the `data_processing` directory, run `output_to_isoplotr.ipynb`, `proc_isoplotr.ipynb`, and `input_from_isoplotr.ipynb` in that order. These process some data in R using IsoplotR used in other notebooks. Note that the second notebook needs to be run with an R rather than Python kernel.
3. Run `figs.ipynb` to see the bulk of main text detrital zircon figures included in Vasey et al. (in revision).
4. Run `hf.ipynb` to see construction of Figure 5 in Vasey et al. (in revision).
5. Run `supp.ipynb` to see construction of supplementary figures in Vasey et al. (in revision).
6. Run `supp_tables.ipynb` to see construction of supplementary tables in Vasey et al. (in revision).

## References
Vasey, D.A., Garcia, L., Cowgill, E., Trexler, C.C. and Godoladze, T., in revision, Episodic evolution of a protracted convergent margin revealed by detrital zircon geochronology in the Greater Caucasus: _Basin Research_.





