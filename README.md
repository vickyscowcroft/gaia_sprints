# gaia_sprints

## variable_star_visualisation.ipynb

* Code to plot light curves of variable stars in the Gaia DR1 archive.
* Uses adql queries to the gaia archive 
* Also contains function to pull time series photmetetry for variable stars in Gaia 
* photometry data files *source_id.csv* are saved to the phot_files directory when you make them
* variable_stars.csv and variable_stars_sourceinfo.csv are the files with the overview info about the variables.
  - TODO - switch this up so it's not doing repeated calls to the archive for these files now they're downloaded. 
  - Check whether a photometry file exists before calling the archive for another version.
* Right now the notebook just plots up a random star (using a random number generator)

