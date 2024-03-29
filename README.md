# jumping-worm-cold-tolerance

These data files and code are associated with the manuscript 
"Invasive adult jumping worms in New Brunswick, Canada are chill-susceptible"

# RCode file
The code can be run in R v4.0.3, and was used to conduct statistical analysis and generate the manuscript figures from the data files below. (Recommendation: use RStudio for easier visualization of figures.)


# Data files
These are used for statistical analysis and figure generation in the RCode file.

## LTemp.csv

We exposed groups of 8 worms to the indicated low temperatures for 1 h and measured survival post-cold shock.
Each row pertains to a different group of worms, with information provided for each variable (column heading), as described below.

VARIABLE:                  DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Expt:                Date of the experiment (cold exposure) in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#Temp:                     Temperature (in °C) of the 1 h cold shock<br>
#NWorms:                   Number of worms that were exposed to that temperature<br>
#NAlive:                   Number of worms that were alive 24 h post-cold shock<br>
#NDead:                    Number of worms that were dead 24 h post-cold shock<br>
#PAlive:                   Proportion of worms that were alive 24 h post-cold shock<br>
#SEP:                      Standard error of proportion of living worms<br>

## LTime.csv

We exposed one group of 12 worms to the 5°C for 48 hours and measured survival at several time points during chilling. 
Each row pertains to a particular duration of chilling for a single group of worms, with information provided for each variable (column heading), as described below.

VARIABLE:                  DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Expt:                Date of the experiment (cold exposure) in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#TimeInCold:               Time (in hours) that worms were exposed to 5°C prior to survival assessment<br>
#NWorms:                   Number of worms that were exposed to that temperature<br>
#NAlive:                   Number of worms that were alive after chilling for the indicated duration<br>
#NDead:                    Number of worms that were dead after chilling for the indicated duration<br>
#PAlive:                   Proportion of worms that were alive after chilling for the indicated duration<br>
#SEP:                      Standard error of proportion of living worms<br>

## CTmin.csv

We exposed each worm to a gradual temperature decrease and recorded the CTmin (Critical Thermal Minimum): the temperature at which voluntary movement ceased.
Each row pertains to one worm, with information provided for each variable (column heading), as described below.

VARIABLE:                  DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Expt:                Date of the experiment (cold exposure) in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#CTmin:                    Temperature (in °C) at which CTmin occurred<br>
#Mass:                     Mass (in grams) of each worm<br>

## SCP.csv

We exposed each worm to a gradual temperature decrease and recorded the SCP (Supercooling Point): the temperature at which internal ice formation began.
Each row pertains to one worm, with information provided for each variable (column heading), as described below.

VARIABLE:                  DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Expt:                Date of the experiment (cold exposure) in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#SCP:                      Temperature (in °C) at which SCP occurred<br>
#Mass:                     Mass (in grams) of each worm<br>

## Glucose.csv

We flash-froze worms in liquid nitrogen, and then measured whole body glucose concentrations via a biochemical assay.
Each row pertains to one worm, with information provided for each variable (column heading), as described below.

VARIABLE:                  DESCRIPTION <br>
#Date Collected:           Date of field collection in dd-mmm-yy format<br>
#Date Flash-Frozen:        Date on which worms were flash-frozen in dd-mmm-yy format<br>
#Treatment:                Whether worms were summer-acclimated or fall-acclimated prior to the cold shock<br>
#Glucose:                  Glucose concentration (in mg per g of tissue) for each worm<br>
