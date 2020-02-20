# Radon detector calibration simulator (`radcalsim`)


[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/agriff86/radcalsim/master?filepath=calibration_simulation.ipynb)

This tool simulates the response of ANSTO's two filter dual flow loop radon detectors during calibration.

## Theory

A model of the ANSTO two filter radon detector is described in [this paper](https://www.atmos-meas-tech.net/9/2689/2016/).  We have solved the system of ordinary differential equations symbolically using [SageMath](https://www.sagemath.org/), then copied the solution into Python code.

## What to do now

You can view a [static simulation result](https://github.com/agriff86/radcalsim/blob/master/calibration_simulation.ipynb) or run the tool to experiment with different parameter settings.  To run with Binder use [this link](https://mybinder.org/v2/gh/agriff86/radcalsim/master?filepath=calibration_simulation.ipynb)

