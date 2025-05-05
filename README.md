# Task-7
In this task, I worked on binary classification using the Breast Cancer dataset. I first scaled the data and reduced it to 2D using PCA for visualization. Then, I trained two SVM models one with a linear kernel and one with an RBF kernel and evaluated their performance using accuracy and classification metrics.
To better understand their decision boundaries, I visualized them using a custom function on the PCA-transformed data. Finally, I used GridSearchCV to find the best hyperparameters (C and gamma) for the RBF kernel and evaluated the optimized model for its accuracy.
