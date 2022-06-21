# Credit Risk Analysis
## Overview
The following analysis was performed in order to investigate which of the six working machine learning statistical algorithms is most suited to predict potential risky creditors based on the readily available past loans' information. The six models investigated in this analysis are, as follows: Random Oversampling, Synthetic Minority Oversampling Technique (SMOTE), Cluster Centroid Undersampling, SMOTEENN, Balanced Random Forest Classifier (BRFC), and Easy Ensemble Classifier (EEC).

## Results
The results of a 6-model supervised machine learning analysis are presented below:
### Random oversampling
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/174695699-581d5255-d5e6-4c89-894a-208fa0257407.png" />
</p>

* For the oversampling, the balanced accuracy score was equal to approximately 65%.

* The precision rate was at 1% for high risk loan taker, while for low risk loan takers, it was a 100%.

* The recall rate, on the other hand, was 63% for the high risk loans, and 67% for low risk loans.
### SMOTE
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/174695712-3852d72b-40bd-45a1-85d9-806f59c37b73.png" />
</p>

* For the SMOTE, the balanced accuracy score was equal to approximately 64%.

* The precision rate was at 1% for high risk loan taker, while for low risk loan takers, it was a 100%.

* The recall rate, on the other hand, was 60% for the high risk loans, and 68% for low risk loans.
### CC Undersampling
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/174695721-b2876f88-b25a-4766-a01e-9c5c03745251.png" />
</p>

* For the CC undersampling, the balanced accuracy score was equal to approximately 53%.

* The precision rate was at 1% for high risk loan taker, while for low risk loan takers, it was a 100%.

* The recall rate, on the other hand, was 57% for the high risk loans, and 48% for low risk loans.
### SMOTEENN
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/174695739-3bc98557-c52e-41e5-a0ae-0e7b514fc889.png" />
</p>

* For the SMOTEENN, the balanced accuracy score was equal to approximately 65%.

* The precision rate was at 1% for high risk loan taker, while for low risk loan takers, it was a 100%.

* The recall rate, on the other hand, was 72% for the high risk loans, and 58% for low risk loans.

## Summary

### Key Takeaway
It appears that most of the machine learning algorithms produced approximately similar results in their judgement, with 3 out of the 4 available algorithm results estimating the accuracy rate at about 64-65% average. The precision rates, moreso, are exactly the same across all examined statistical algorithms. However, the recall rates vary significantly across the different algorithms.

### Recommendations
It is possible that the EEC or BRFC models would produce a better precision rate, but I was unable to utilize them for the current analysis, thus the results are based off of the four models provided above. As such, I cannot choose a model that I would recommend over the others in the current scenario, as they are all predicting the results with approximately the same precision rate (although, I would advise against the CC undersampling, as it yielded the lowest precision rate across the board).
