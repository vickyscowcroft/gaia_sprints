# gaia_sprints

## variable_star_visualisation.ipynb

* Code to plot light curves of variable stars in the Gaia DR1 archive.
* Also contains function to pull time series photmetetry for **flagged** variable stars in Gaia (more on this below...)

### Weird thing ### 
* Not all variables are flagged in DR1-TGAS
* There is only 1 flagged variable in TGAS, despite there being a large number of RRL and Cepheids in this data (I know they are there, I have checked.)
* Are Gaia not releasing the time series data for these stars yet?
* It would be really useful to have these - these are the ones that have HST FGS parallaxes, well sampled ground based data etc, but they're flagged with NOT_AVAILABLE in the phot_variable_flag (i.e. no time series)
* I need to read the Clementini paper in more detail (and the Eyer one when it's published...)
