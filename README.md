# Elevate-Labs-Task-5

Approach:

1. Imported important libraries and the dataset.
2. Explored dataset to check for any categorical columns (that need encoding - All were found to be numeric columns).
3. Extracted the 'target' columns and did train_test_split.
4. Tested Decision Tree Classifier for different maximum depths and plotted the tree as well.
5. Tested Random Forest Classifier and compared the accuracy with Decision Tree Classifier.
6. Interpreted the feature importances using mutual information score from sklearn.
7. Found the average cross val score for Decision Tree and Random Forest Classifier with 5-fold cross validation.

References:
1. Data - https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?select=heart.csv
2. https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html
3. https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html
4. https://scikit-learn.org/stable/modules/generated/sklearn.tree.plot_tree.html
