<h1 style="font-size: 45px; margin-top: 20px;"> Tech Industry Mental Health Predictor & Classifier</h1>


*   **[Download Complete Executive PDF Report (Final_Project_Report.pdf)](Mental-Health.pdf)**
*   **[Raw Quarto Source Code File (.qmd)](Mental-Health.qmd)**

A statistical machine learning project analyzing the OSMI 2016 survey to predict whether tech professionals will seek mental health treatment based on workplace environments, demographics, and personal attitudes.

###  Tech stack and Library 
*   **Language:** Python
*   **Libraries:** Pandas, Scikit-Learn, NumPy, Matplotlib
*   **Environment:** RStudio / Python execution workspace

###  Core Architecture
*  **Feature Engineering & Preprocessing:** Cleaned a 1,259-row dataset by isolating 27 variables, imputing missing values, mapping categorical baseline references, applying one-hot encoding, and scaling numeric predictors.
*  **Multi-Model Classification Pipeline:** Built, trained, and tested three distinct predictive algorithms to find the optimal fit for the binary target variable: Logistic Regression, Linear Discriminant Analysis (LDA), and Random Forest.
*  **Rigorous Statistical Evaluation:** Utilized bootstrap analysis to generate 95% confidence intervals for model comparison. This mathematical proof showed that the LDA model outperformed the others on this dataset, achieving 83.3% test accuracy and a 0.886 AUC.
*  **Coefficient Analysis:** Extracted and interpreted the model coefficients to identify the strongest predictors for seeking treatment, specifically flagging "Work Interference" and "Family History" as the primary drivers.

### Quantitative/Business Value
Provides HR departments and corporate leadership with an empirical framework to understand mental health trends in the tech sector. By isolating the exact variables that correlate with employees seeking help, organizations can proactively optimize their wellness benefits, adjust leave policies, and allocate support resources where they are most effective.

### Model Evaluation & Metrics
LDA proved to be the most optimal configuration for this dataset, achieving **83.3% test accuracy** and a **0.886 AUC**. Below are the comparative performance curves:


[Back to Home](index.html)
