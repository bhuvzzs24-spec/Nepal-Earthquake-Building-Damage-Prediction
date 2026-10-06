# Application of Machine Learning Methods to Predict Building Damage in the Nepal Earthquake

## Project Overview

This project investigates the application of machine learning techniques to predict the level of building damage caused by the 2015 Nepal Earthquake.

The main objective is to develop and compare multiple supervised machine learning classification models that can classify individual buildings into one of three damage categories based on geographical, structural, construction, ownership, and usage-related characteristics.

The project implements and compares the following three machine learning algorithms:

- K-Nearest Neighbors (KNN)
- Neural Network
- Random Forest

The models are trained using the Nepal Earthquake building damage dataset. Their classification performance is evaluated using Accuracy and Micro-F1 score.

The project also includes exploratory data analysis, preprocessing of numerical and categorical features, confusion matrix analysis, Random Forest feature importance analysis, and prediction of damage grades for the provided test dataset.

---

# 1. Problem Statement

The 2015 Nepal Earthquake caused extensive damage to buildings and infrastructure.

Different buildings experienced different levels of structural damage depending on factors such as their geographical location, construction materials, foundation type, building height, number of floors, structural systems, and other building characteristics.

The objective of this project is to use these available building characteristics to develop machine learning models capable of predicting the damage grade of individual buildings.

The problem is formulated as a multiclass classification problem with three possible target classes.

| Damage Grade | Description |
|---|---|
| 1 | Low damage |
| 2 | Medium damage |
| 3 | Almost complete destruction |

The machine learning models learn patterns from the available building characteristics and use those patterns to predict the damage grade.

---

# 2. Project Objectives

The main objectives of this project are:

1. Load and prepare the Nepal Earthquake building damage dataset.
2. Merge the training feature data with the corresponding damage labels.
3. Explore the structure and characteristics of the dataset.
4. Identify numerical and categorical features.
5. Check the dataset for missing values.
6. Analyze the distribution of the three damage classes.
7. Split the dataset into training and validation subsets.
8. Apply appropriate preprocessing to numerical and categorical variables.
9. Train a K-Nearest Neighbors classifier.
10. Train a Neural Network classifier.
11. Train a Random Forest classifier.
12. Evaluate the models using Accuracy and Micro-F1 score.
13. Compare the performance of the three models.
14. Analyze confusion matrices for the models.
15. Analyze Random Forest feature importance.
16. Use the trained models to generate predictions for the test dataset.
17. Identify the best-performing model based on validation performance.

---

# 3. Dataset

The project uses the Nepal Earthquake building damage dataset associated with the 2015 Nepal Earthquake.

The dataset contains building-level information describing geographical location, structural characteristics, construction characteristics, ownership status, and usage characteristics.

The original dataset is divided into three main files:

```text
train_values.csv
train_labels.csv
test_values.csv
