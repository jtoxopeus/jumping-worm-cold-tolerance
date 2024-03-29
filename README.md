# jumping-worm-cold-tolerance

These data files and code are associated with the manuscript 
"Invasive adult jumping worms in New Brunswick, Canada are chill-susceptible"

# RCode file
The code can be run in R v4.0.3, and was used to conduct statistical analysis and generate the manuscript figures from the data files below. (Recommendation: use RStudio for easier visualization of figures.)


# Data files
These are used for statistical analysis and figure generation in the RCode file.

## LTemp.csv

We exposed groups of 8 worms to the indicated low temperatures for 1 h and measured survival post-cold shock.

VARIABLE:									DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Expt:                Date of of the experiment (cold exposure) in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#Temp:                     Temperature (in °C) of the 1 h cold shock<br>
#NWorms:                   Number of worms that were exposed to that temperature<br>
#NAlive:                   Number of worms that were alive 24 h post-cold shock<br>
#NDead:                    Number of worms that were dead 24 h post-cold shock<br>
#PAlive:                   Proportion of worms that were alive 24 h post-cold shock<br>
#SEP:                      Standard error of proportion of living worms<br>

## LTime.csv

We exposed one group of 12 worms to the 5°C for 48 hours and measured survival at several time points during chilling.

VARIABLE:                  DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Expt:                Date of of the experiment (cold exposure) in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#TimeInCold:               Time (in hours) that worms were exposed to 5°C prior to survival assessment<br>
#NWorms:                   Number of worms that were exposed to that temperature<br>
#NAlive:                   Number of worms that were alive after chilling for the indicated duration<br>
#NDead:                    Number of worms that were dead after chilling for the indicated duration<br>
#PAlive:                   Proportion of worms that were alive after chilling for the indicated duration<br>
#SEP:                      Standard error of proportion of living worms<br>
