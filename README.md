# INT_data_reduction
The pipeline for reducing the data obtained at the INT on September 2022.


Chris Lintott, David O'Ryan and myself (Tobias Géron) spent 5 nights on the INT at the end of September 2022. However, due to storm Hermine, we were only able to observe one target. We were also able to take multiple calibration frames. The target, which is a strongly barred galaxy, was observed with the INT using the IDS spectrograph. We used the R300V grating and the EEV10 detector. We observed the target using a slit placed parallel to the bar and a slit placed perpendicular to the bar.

The SDSS objid of the target is 587727223561584734
RA: 00 05 24.1267
DEC: +16 02 59.9322

In the notebook foudn in this repo, I will go through the different steps in the data reduction using the ccdproc library in Python. I visualise every step along the way.


### Useful link:

CCD reduction overview: https://www.astropy.org/ccd-reduction-and-photometry-guide/v/dev/notebooks/01-05-Calibration-overview.html  

INT: https://www.ing.iac.es/astronomy/telescopes/int/    
IDS: https://www.ing.iac.es/astronomy/instruments/ids/    

