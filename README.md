# CodeAlpha_Iris_Flower_Classification
---

### Project Overview
This notebook implements a **multi-class flower species classification** system using the classic Iris dataset. The goal is to predict the species of an Iris flower:  *Setosa*, *Versicolor*, or *Virginica*  based on four morphological measurements.

### Dataset
| Feature | Description |
|---|---|
| `SepalLengthCm` | Length of the sepal in centimeters |
| `SepalWidthCm` | Width of the sepal in centimeters |
| `PetalLengthCm` | Length of the petal in centimeters |
| `PetalWidthCm` | Width of the petal in centimeters |
| `Species` | Target label: Iris-setosa / versicolor / virginica |

- **Total Samples:** 150 (50 per class)
- **Source:** Uploaded `Iris.csv` or downloadable from [Kaggle](https://www.kaggle.com/datasets/uciml/iris)

### Models Used
- **Random Forest Classifier** ▶ primary model (ensemble, robust, interpretable)
- **K-Nearest Neighbors (KNN)** ▶ baseline comparison model
- **Support Vector Machine (SVM)** ▶ additional benchmark

### Workflow
1. Data Loading & Inspection
2. Exploratory Data Analysis (EDA)
3. Preprocessing & Train/Test Split
4. Model Training (3 classifiers)
5. Model Evaluation (Accuracy, Classification Report, Confusion Matrix)
6. Feature Importance Analysis
7. Interactive Prediction

### Requirements
```
pandas, numpy, matplotlib, seaborn, scikit-learn
```
