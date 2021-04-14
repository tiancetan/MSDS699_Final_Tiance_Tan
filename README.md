# Final Project - Heart Disease 
Tiance Tan

03/08/2021

Abstract

Statistical learning models were applied to Heart Disease data in order to analyze the presense of heart disease based on some differenct facets. In this analysis, we consider both multinomial response and binary response for the model and perform cross validation on them. Ultimately the predictive power of the models appears to be effective but a little bit limited by the available data. Additional data collection is recommended.

Introduction

Heart disease is a form of heart disease and blood vessel disease. Heart ailments are the leading reason of dying globally. Some danger factors for heart illnesses encompass smoking, high blood pressure and so on. Analyzing datasets associated to heart ailment can assist scientific specialists comprehend about what contributes extra to the patient’s seriousness of disease, for that reason suitable treatment can be utilized earlier.

Research Question / Hypothesis

Research Question:

Can we use patients' demographics information to predict if they have heart disease?

How accurate is the prediction?

Hypothesis:

It is possible to make the prediction. However, the dateset is not large enough, the results might not be applicable for all heart-disease patients.

Modeling method:
ExtraTrees
RandomForest
SVC
KNeighbors

Final Model:
RandomForest
F1 score - 0.8674
RMSE - 0.3804

Conclusion

We can see the F1 score looks pretty good, which means the final model can assist scientific specialists to make prediction whether the patient has heart disease or not.

There are still some limitations on this analysis. First of all, the sample size is not large enough since it only contains about 300 observations. There are millions of people get heart disease in the world. It is unreasonable to do the analysis only based on 300 observations. Second, there could be other ways of variable selection instead of selecting all variables in the dataset.
