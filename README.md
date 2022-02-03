# Comparative-study-of-chronic-kidney-disease-prediction-using-machine-learning-approaches

## Dataset used:
We selected the dataset "Chronic_Kidney_Disease DataSet " from UCI Machine Learning Repository [a]
The dataset is gathered from many medical labs, pharmacies,community health centers and hospitals. In our dataset we have 400 rows and 25 columns . There are 13 categorical columns and 11 numerical columns and 1 column for class, there are only two classes in our dataset which are:

CKD - having Chronic Kidney Disease
notCKD - not having Chronic Kidney Disease

The features in dataset are : age , blood pressure , specific gravity ,albumin ,sugar, red blood cells, pus cells, pus cell clumps, bacteria, blood glucose random, blood urea, serum creatinine , sodium, potassium, haemoglobin, packed cell volume, white blood cell count , red blood cell count , hypertension, diabetes mellitus , coronary artery disease, appetite, pedal edema ,anemia ,class.

## Imputation Techniques:

MICE : Multivariate Imputation by Chained Equations or sometimes called "sequential regression multiple imputation " has emerged in the statistical literature as one principled method for addressing missing data. It works on assumption of missingness at random (MAR), i.e., missingness only depends on observed values. Creating multiple imputations , as opposed to single imputations,account for the uncertainty in the imputations. In addition, the chained equations approach is very flexible and can handle variables of varying types(e.g. continuous or binary).

KNN imputation : KNN finds the k most relevant nearest neighbors for a instance with missing data from complete instances using Euclidean distance, and the contribution of each instance is weighted to replace the missing data.[2s]
Since our dataset has 13 categorical columns , we need to convert them into numerical type so we can perform data analysis techniques on them. For this we have used two methods , one is Label Encoding and other is One Hot Encoding.

## ML algorithms used:

1. SVM
2. KNN Classifier
3. XGBoost
4. Random Forest
