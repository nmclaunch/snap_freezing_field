# snap_freezing_field

This data accompanies the publication: Snap-freezing in the field: effect of sample holding time on performance of bactericidal assays in Integrative and Comparative Biology. https://doi.org/10.1093/icb/icac007

Column header ID descriptions are below:

animal_id : the identification code for an individual animal
time : the holding time in minutes for the aliquotted sample
Plate.ID : identification code for the plate used in microbiocidal assay
species : the species of the animal

#column headers F (6) through V (22) represent serum dilutions. Numbers in these columns correspond to % bacterial killing at that dilution; NA indicates there were not samples run at that dilution for a given individual.#
0.00390625
0.005859
0.007813
0.011719
0.023438
0.023438
0.03125
0.046875
0.0625
0.09375
0.125
0.1875
0.25
0.375
0.5
1  : this corresponds to raw, undiluted serum.

npar : Number of parameters used in model; number of dilutions (5, 4, 3, etc.)
Infl.logX : Inflection point on the x axis (log formatted)
Infl.propY : Inflection point on the Y axis (proportion of Y based on converToProp)
Log.BottomAsym : The proportional BKA value at the very start of killing
Log.TopAsym : The proportional BKA value at the max of killing
Log.Xinfl : The log of the concentration value in the middle of the killing (50% antibacterial capacity)
Log.Slope : Slope of the line created by the model in log form
Asym.Coef : Asymmetric coefficient (a number if npar=5, or it is 1 if npar=4,3 , etc.)
gof : Goodness of fit for the model 
wgof : Weighted goodness of fit
stdErr : Standard error for the model
wstdErr : Weighted standard error
