# KNIME-Workflows-for-Applications-in-Medicinal-and-Computational-Chemistry
This file contains a brief description of the KNIME workflows included in the poster. 

Figure 1: KNIME workflow for data input, data cleaning, including manipulation of pKa values to extract the most acidic pKa for compounds with multiple acidic groups; decision tree analysis, and a preliminary machine learning model. 

Figure 2: KNIME workflow for data input, insertion of a linear correlation routine to eliminate features based on autocorrelation, generation of a list of features, application of a genetic algorithm using the feature selection loop and counting of the resulting features.  

Figure 3: KNIME workflow taking input for variation of thresholds and data output from Figure 2 for use in a machine learning model.

The CSV file entitled "Features_GA_LC.csv" is a list of all features with their counts as selected solely by the genetic algorithm as well as after running both the genetic algorithm and linear correlation routines. 
