# Breast Cancer Analysis

## Project Overview
This project analyzes a breast cancer dataset to classify tumors as **benign** or **malignant**. It includes:

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Visualization and interpretation of results

The goal is to build predictive models and extract insights from the dataset.

---

## Repository Structure
```

/Breast_cancer
├── breast_cancer_06_11_2025.ipynb  # Main Jupyter Notebook
└── README.md                        # Project README

````

---

## Data Source
The dataset used in this project is publicly available and was obtained from:

```bash
git clone https://github.com/MachineLearnia/breast_cancer_public_data.git
````

All analysis in this project uses the data from this repository.

---

## Methodology

1. **Data Loading** – Load the dataset from the cloned repository.
2. **Data Preprocessing** – Handle missing values, encode categorical variables, and scale features.
3. **Exploratory Data Analysis (EDA)** – Analyze feature distributions, correlations, and class balance.
4. **Feature Engineering** – Create or select features to improve model performance.
5. **Model Training** – Train classifiers such as Logistic Regression, Decision Tree, Random Forest, and SVM.
6. **Model Evaluation** – Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC/AUC.
7. **Results & Interpretation** – Compare models, identify key predictive features, and interpret insights.

---

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Ayaindeed/Breast_cancer.git
   cd Breast_cancer
   ```
2. Clone the dataset into the `data/` folder:

   ```bash
   git clone https://github.com/MachineLearnia/breast_cancer_public_data.git data/
   ```
3. Install required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

   *(If `requirements.txt` is not available, manually install: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`)*
4. Open and run the notebook:

   ```bash
   jupyter notebook breast_cancer_06_11_2025.ipynb
   ```

   or

   ```bash
   jupyter lab
   ```

---


## 📚 References

* [Scikit-learn Classification Documentation](https://scikit-learn.org/stable/modules/classification.html)
* [Breast Cancer Public Dataset](https://github.com/MachineLearnia/breast_cancer_public_data)

---
