# 178KaggleCompetiton-Prediction of the Presence or Absence of Rainfall at a Particular Location      
The competition data are satellite-based measurements of cloud temperature (infrared imaging), being used to predict the presence or absence of rainfall at a particular location. The target value is a binary indicator of whether there was rain (measured by radar) at that location; and data are slightly imbalanced (positives make up about 30% of the training data).

The method that worked the best is random forest and  worst method was a linear model by far. It might be our fault in that we did not thoroughly try to find the best features, but we think that it’s also because the pattern is complex.
