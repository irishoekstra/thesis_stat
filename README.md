# thesis_stat

This repository contains the R-code used in my thesis. The files are:
- data_collection.RMD, this file contains the code used to read in the GRIB-files containing our forecast. 
- training_model.RMD, this file has the code used to train and verify the models on our training set. It contains the code for fitting the models, the 5-fold-cross validation-procedure, Brier (Skill) Score and CRPS. 
- test_models.RMD, contains the code used to verify our trained models on the test set. It also contains the code for most of the plots that are in the thesis, the code for the other plots can be found in the plots_figure.RMD file. 
- Casestudy.RMD, the code for our case study can be found in this file. 
- plots_figure.RMD, contains the code used to plot the figures.
