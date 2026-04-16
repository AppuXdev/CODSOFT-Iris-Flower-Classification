# CODSOFT Task 3 - Iris Flower Classification

## Objective
Classify iris flowers into 3 species - Setosa, Versicolor, Virginica - based on sepal and petal measurements.

## Dataset
Iris dataset from sklearn: 150 samples, 4 features (sepal length, sepal width, petal length, petal width), 3 classes.

## Models Used
1. Logistic Regression
2. Decision Tree Classifier  
3. Random Forest Classifier

## Final Results
- **Best Model**: Random Forest Classifier
- **Accuracy**: 90%
- **Test Size**: 30 samples (20% of data)

## Key Insights
Setosa is linearly separable and predicted with 100% accuracy. Versicolor and Virginica show slight overlap, causing 3 misclassifications. Petal length and petal width are the most important features for classification.

## Confusion Matrix
- Setosa: 10/10 correct
- Versicolor: 9/10 correct, 1 misclassified as Virginica
- Virginica: 8/10 correct, 2 misclassified as Versicolor

## Tech Stack
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Files
1. `Iris_Flower_Classification.ipynb` - Complete analysis with EDA and model outputs
2. `Iris_Flower_Classification.py` - Python script version
