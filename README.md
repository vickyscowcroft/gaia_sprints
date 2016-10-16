# gaia_sprints

## variable_star_visualisation.ipynb

* Code to plot light curves of variable stars in the Gaia DR1 archive.
* Also contains function to pull time series photmetetry for **flagged** variable stars in Gaia (more on this below...)
* photometry data files *source_id.csv* are saved to the phot_files directory when you make them
* variable_stars.csv and variable_stars_sourceinfo.csv are the files with the overview info about the variables.
  - TODO - switch this up so it's not doing repeated calls to the archive for these files now they're downloaded. 
  - Check whether a photometry file exists before calling the archive for another version.
* Right now the notebook just plots up a random star (using a random number generator)

### Weird thing 
* Not all variables are flagged in DR1-TGAS
* There is only 1 flagged variable in TGAS, despite there being a large number of RRL and Cepheids in this data (I know they are there, I have checked.)
* Are Gaia not releasing the time series data for these stars yet?
* It would be really useful to have these - these are the ones that have HST FGS parallaxes, well sampled ground based data etc, but they're flagged with NOT_AVAILABLE in the phot_variable_flag (i.e. no time series)
* I need to read the Clementini paper in more detail (and the Eyer one when it's published...)
