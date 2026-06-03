Leak Detection Using LeakDB and Random Forest
Project Overview: This project uses the LeakDB benchmark dataset to detect leaks in a water distribution network.

Dataset
-LeakDB (Hanoi_CMH Network)
-Scenario-10 used for analysis

Methodology
-Load pressure data from Node_10
-Load leak labels
-Merge pressure and label data
-Train Random Forest Classifier
-Evaluate model performance

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

Future Work
1. Use multiple pressure nodes
2. Apply ANN and Deep Learning models
3. Perform leak localization
4. Study sensor placement optimization
