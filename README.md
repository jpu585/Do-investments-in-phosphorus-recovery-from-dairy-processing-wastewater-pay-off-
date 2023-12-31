# Do investments in phosphorus recovery from dairy processing wastewater pay off?

This repository DOI: (XXX) contains files that contribute to our supplementary materials of the Manuscript: 'Do investments in phosphorus recovery from dairy processing wastewater pay off?' by Uhlemann J. R., Dalhaus T., Leahy J.J., Oude Lansink A.  (The DOI of the Manuscript can be found here when published). Within this repository we provide all necessary files to comprehend procedure of code calculations. We illustrate our code for data visualization that enables reproduction of our figures. To fully replicate the results run master_code.R in a working directory with the other files. The code was run on R version 4.2.3 successfully. The data from EUROSTAT was last accessed on the 01/10/2023.

## master_code.R
This file installs all the packages runs the code scripts and creates the figures in the manuscript.

## code.R
This file contains all the code to import, clean and transform the data. To calculate the net present values, the efficiency scores and the sensitivity analysis.

## code_plot.R
This file contains the code to reproduce the figures in the manuscript relying on the data from the code file.

## exp.csv
This file contains the data for the inputs and outputs of the process specifications.

## par.csv
This file contains parameter and prices for the model.
