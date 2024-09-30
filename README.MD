## Project Objective

The Beta Bank is facing a customer churn issue, with many clients leaving each month. The bank's goal is to retain existing clients, which is more cost-effective than acquiring new ones. The objective of this project is to build a predictive model to forecast whether a client will leave the bank soon. The model aims to achieve a high F1-score, with a minimum requirement of 0.59 on the test dataset, and also measure the AUC-ROC metric to compare against the F1-score.

## Project Structure and Steps

**1. Data Preparation**:
- Load and prepare the dataset (/datasets/Churn.csv) for analysis.
- Explain each step in the data preprocessing, ensuring all features are processed appropriately.

**2. Class Balance Examination:**
- Analyze the class distribution of the target variable (whether a customer leaves the bank).
- Train an initial model without addressing class imbalance and document initial findings.

**3. Model Improvement and Class Imbalance Correction:**
- Implement at least two approaches to correct the class imbalance.
- Use the training and validation datasets to determine the best model and the optimal set of parameters.
- Provide a brief description of results from tuning models and hyperparameters.

**4. Final Testing:**
- Conduct final model testing to evaluate performance on the test dataset.
- Measure the F1-score and the AUC-ROC, and compare both metrics for a comprehensive evaluation.

## Tools and Techniques Utilized

**Data Processing & Analysis:**
- Pandas, Numpy: For data manipulation and preprocessing.
- Scikit-learn: For building and evaluating machine learning models, including handling imbalanced classes through techniques like oversampling or undersampling.

**Visualization & Evaluation:**
- Matplotlib, Seaborn: For data visualization to better understand class distribution and model performance.
- AUC-ROC Curve, F1-Score: For evaluating the classification model's effectiveness and predictive power.

## Specific Results and Outcomes
- The F1-score for the random forest model achieved a value above the threshold of 0.59 and AUC-ROC score of 0,85.
- The AUC-ROC score was calculated and compared with the F1-score, providing a more nuanced view of model performance.
- Class imbalance was effectively handled through techniques like resampling or using model-based approaches for better generalization.


## What I Have Learned from This Project

- **Data Preprocessing & Feature Engineering:** Effective handling of raw data, cleaning, and preparation for machine learning models.
- **Model Building & Tuning**: Building classification models with a focus on improving metrics like F1-score, and tuning hyperparameters to enhance performance.
- **Class Imbalance Strategies**: Gained experience in dealing with imbalanced datasets using verious techniques like to ensure model performance remains robust.
- **Model Evaluation Metrics:** Learned to use F1-score and AUC-ROC as key metrics to assess classification models, understanding their trade-offs and implications on model selection.