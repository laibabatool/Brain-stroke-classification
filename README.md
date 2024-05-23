# Brain-stroke-classification
This repository contains the implementation and analysis of a machine learning project aimed at classifying brain strokes into ischemic and hemorrhagic types. Leveraging Random Forest, K-Nearest Neighbors (KNN), and Decision Tree algorithms, we achieve high classification accuracy, providing a potential tool for aiding in the rapid diagnosis and treatment of strokes.

# Dataset
We utilized a publicly available dataset from Kaggle, which includes demographic information, medical history, lifestyle factors, and socioeconomic variables. Key features include:

Age \n
Gender
Hypertension 
Heart disease 
Blood sugar levels 
Body Mass Index (BMI) 
Smoking status 
Work type 
Residence type

The target variable is the presence or absence of a stroke.
# Data Analysis

Age Distribution: Stroke incidence increases with age.

![image](https://github.com/laibabatool/Brain-stroke-classification/assets/77329900/f09bcdad-d0dd-4fae-b61b-db6af0b5a566)

Smoking Status: Higher stroke prevalence among smokers.

![image](https://github.com/laibabatool/Brain-stroke-classification/assets/77329900/9dfc8ceb-7ecb-4862-8bd8-726917475e7b)

Heart Disease: Strong correlation between heart disease and stroke incidence.

![image](https://github.com/laibabatool/Brain-stroke-classification/assets/77329900/c6d007d9-5400-4309-b873-95a0ed8dee56)


Correlation Analysis: Explored relationships between features to understand stroke risk factors.

![image](https://github.com/laibabatool/Brain-stroke-classification/assets/77329900/88706950-3a6a-4d76-bbfd-3b8c578ef2c1)

# Models and Performance
We evaluated three machine learning models:

# Random Forest

Accuracy: 95.3%
Precision: 0.478
Recall: 0.498
F1 Score: 0.488

# K-Nearest Neighbors (KNN)

Accuracy: 95.6%
Precision: 0.478
Recall: 0.499
F1 Score: 0.489

# Decision Tree

Accuracy: 95.5%
Precision: 0.955
Recall: 0.478
F1 Score: 0.489

# Conclusion
All models achieved high overall accuracy, but faced challenges with class imbalance, leading to lower precision and recall for stroke classification. Future work will focus on addressing this imbalance and incorporating additional clinical data to enhance model performance.




