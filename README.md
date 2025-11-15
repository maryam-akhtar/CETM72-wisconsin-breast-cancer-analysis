# CETM72-wisconsin-breast-cancer-analysis
Machine learning classification of the Wisconsin Breast Cancer dataset using RStudio — Logistic Regression, Decision Tree, and Support Vector Machine.

This project was developed as part of the **CETM72 module** in my MSc Computer Science (graduating 2026).  
It focuses on applying **machine learning techniques in R** to classify breast cancer cases using the **Wisconsin Breast Cancer dataset**.

## Objective
To compare the performance of three machine learning algorithms—**Logistic Regression**, **Decision Tree**, and **Support Vector Machine (SVM)**—and identify the most accurate model for breast cancer classification.

## Dataset
- **Source:** Wisconsin Breast Cancer dataset (FNA biopsy data)  
- **Instances:** 569 (357 Benign, 212 Malignant)  
- **Key Features:** Cell radius, texture, smoothness, and other morphological measurements.

## Methodology
1. **Data Pre-processing**
   - Handled missing values and encoded categorical variables (Malignant = 1, Benign = 0).  
   - Conducted exploratory data analysis (EDA) to ensure data quality.

2. **Machine Learning Algorithms**
   - Logistic Regression  
   - Decision Tree (via `partykit` library)  
   - Support Vector Machine (SVM)

3. **Evaluation Metrics**
   - Confusion matrix  
   - Accuracy  
   - Comparative visualization between classifiers

## Results
| Model | Accuracy |
|--------|-----------|
| Logistic Regression | 96.1% |
| Decision Tree | 94.3% |
| Support Vector Machine (SVM) | **97.1%** ✅ |

The **SVM model** achieved the highest classification accuracy, demonstrating strong potential for real-world breast cancer prediction.

## Key Learning
- Pre-processing healthcare datasets in R  
- Training and evaluating ML models  
- Visualizing classification accuracy using `ggplot2`

## Tools Used
- **RStudio**
- **R Libraries:** `caret`, `glmnet`, `rpart`, `partykit`, `ggplot2`, `e1071`

## Result
**Score:** 66% 

## File
- [Maryam Akhtar - Assignment 2.pdf](./Maryam%20Akhtar%20-%20Assignment%202.pdf)

---

### Author
**Maryam Akhtar**  
MSc Computer Science (Graduating 2026)  
BSc Natural Science (Biology)  

