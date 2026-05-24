# CodeAlpha_IrisClassification
# CodeAlpha Data Science Internship — Task 
> End-to-end Data Science projects completed as part of the **CodeAlpha Data Science Internship**.
> Built with Python, Scikit-learn, Pandas, Matplotlib and Seaborn.
##  Repository Structure
---
##  Repository Structure
CodeAlpha_IrisClassification/
└── irisclassification.ipynb
---


##  Task 1 — Iris Flower Classification

### Objective
Classify Iris flower species (*Setosa*, *Versicolor*, *Virginica*) based on sepal and petal measurements using supervised machine learning.

### Dataset
- **Source**: UCI Iris Dataset via `sklearn.datasets` (no download needed)
- **Features**: Sepal length, sepal width, petal length, petal width (cm)
- **Classes**: 3 species | **Samples**: 150 rows

### Models Trained
| Model | Notes |
|---|---|
| Logistic Regression | Linear baseline |
| K-Nearest Neighbors | k=5, distance-based |
| Support Vector Machine | RBF kernel |
| Decision Tree | Max depth 4, fully visualized |
| Random Forest | 100 estimators ensemble |

All models use `StandardScaler` inside a `Pipeline` to prevent data leakage.

### Evaluation
- 80/20 stratified train-test split
- 5-fold Stratified Cross-Validation
- Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Best model selected automatically by highest CV mean score

### Key Results
- All models achieved **95–100% accuracy**
- **Petal measurements** are the most important features (confirmed by Random Forest feature importance)
- Decision Tree visualized for full interpretability

### Visualizations Included
- Feature distribution histograms by species
- Pair plot across all 4 features
- Correlation heatmap
- Model comparison bar chart (Test Accuracy vs CV Accuracy)
- Confusion matrix of best model
- Decision Tree structure
- Random Forest feature importance

---
## Author

Maha Anwar
LinkedIn: [www.linkedin.com/in/maha-anwar-063b27395]
GitHub: [https://github.com/mahaanwar1903-spec]

---

*Completed as part of the CodeAlpha Data Science Internship Program*
*[codealpha.tech](https://www.codealpha.tech)*
