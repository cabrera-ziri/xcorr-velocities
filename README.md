# xcorr-velocities

This repository contains a Jupyter Notebook for measuring radial velocities from astronomical spectra using cross-correlation with a template spectrum.

## Overview

The new_xcorr.ipynb notebook demonstrates how to measure the radial velocity (RV) of an observed spectrum by cross-correlating it with a template spectrum. The method involves:

1. Resampling the spectra onto a common logarithmic wavelength grid.
2. Normalizing the spectra to remove continuum variations.
3. Performing cross-correlation to determine the shift between the observed and template spectra.
4. Calculating the radial velocity based on the shift.

Additionally, the notebook includes a Monte Carlo simulation to estimate the uncertainty in the RV measurement by adding noise to the observed spectrum and repeating the cross-correlation procedure multiple times.
