# Tech Industry Mental Health Predictor & Classifier

*   **[📁 View Complete Source Code Repository](Link to your actual Mental Health Repo URL)**

###  Tech stack and Library 
*   **Language:** Python
*   **Libraries:** Pandas, Scikit-Learn, NumPy, Matplotlib
*   **Environment:** RStudio / Python execution workspace

###  Core Architecture
*  **Feature Engineering & Preprocessing:** Cleaned a 1,259-row dataset by isolating 27 variables, imputing missing values, mapping categorical baseline references, applying one-hot encoding, and scaling numeric predictors.
*  **Multi-Model Classification Pipeline:** Built, trained, and tested three distinct predictive algorithms to find the optimal fit for the binary target variable: Logistic Regression, Linear Discriminant Analysis (LDA), and Random Forest.
*  **Rigorous Statistical Evaluation:** Utilized bootstrap analysis to generate 95% confidence intervals for model comparison. This mathematical proof showed that the LDA model outperformed the others on this dataset, achieving 83.3% test accuracy and a 0.886 AUC.
*  **Coefficient Analysis:** Extracted and interpreted the model coefficients to identify the strongest predictors for seeking treatment, specifically flagging "Work Interference" and "Family History" as the primary drivers.

### Model Evaluation & Metrics
LDA proved to be the most optimal configuration for this dataset, achieving **83.3% test accuracy** and a **0.886 AUC**. Below are the comparative performance curves:

![Model Performance Curves](roc_curve.png)

[Back to Home](README)
