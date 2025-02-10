# SCIFY

SCIFY stands for Self Calibrating Interferometry for exoplanet spectroscopY.

## SCIFYsim

SCIFYsim is an end-to-end simulator designed to reproduce the behaviour of interferometers. It is designed to simulate integrated optics beam combination, with a specific emphasis on Nulling interferometry.

* Github repository: [SCIFYsim](https://github.com/rlaugier/SCIFYsim)
* Documentation: [Documentation](https://rlaugier.github.io/scifysim_doc.github.io/)

It is used to simulate the performance of the Asgard/NOTT (formerly Hi-5) instrument, and can be used to simulate kernel-nulling instruments.

## Nulling data reduction software and data standard
* Full LBTI nulling pipeline: [nodrs](https://github.com/ddefrere/nodrs)
* Generic nulling data reduction pipeline: [grip-nulling](https://github.com/ddefrere/grip-nulling) [documentation](https://mamartinod.github.io/grip-nulling/)
* Nulling Interferometric data standard: [nifits](https://github.com/ddefrere/nifits)

## NOTT observing preparation tool
* Tool to prepare observations with NOTT ([NOTT observing tool](https://github.com/SCIFY-IvS/NOTT-observation-preparation-tool))

## GRAVITY+ Vibration control and mitigation
* pytac is a python library to work with ESO Tools for Advanced Control (TAC): [pytac](https://github.com/rlaugier/pytac) 
* Code to compute the *equivalent noise of charge accelerometers: [Manhattan2](https://github.com/AzzurraB-rr/Charge-accelerometer-equivalent-noise)

# Acknowledgements
SCIFY has received funding from the European Research Council (ERC) under the European Union's Horizon 2020 research and innovation program (grant agreement No 8660). The documentation of the software package is funded by the European Union's Horizon 2020 research and innovation program under grant agreement No. 101004719.
