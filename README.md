Leak Detection Using LeakDB and Random Forest

Project Overview: This project uses the LeakDB benchmark dataset to detect leaks in a water distribution network.

Dataset
-LeakDB (Hanoi_CMH Network)
-Scenario-10 used for analysis

Methodology
1. Load pressure data from Node_10
2. Load leak labels
3. Merge pressure and label data
4. Train Random Forest Classifier
5. Evaluate model performance

Results
1. Accuracy: 70.1%
2. Precision (Leak): 0.67
3. Recall (Leak): 0.66

Tools Used
-Python
-Pandas
-Matplotlib
-Scikit-learn
-Jupyter Notebook

## Dataset

LeakDB benchmark dataset (Hanoi_CMH network)

Scenario-10 was selected for leak detection analysis.

## Model Performance
Accuracy: 70.1%
Precision (Leak): 0.67
Recall (Leak): 0.66

Future Work
1. Use multiple pressure nodes
2. Apply ANN and Deep Learning models
3. Perform leak localization
4. Study sensor placement optimization
