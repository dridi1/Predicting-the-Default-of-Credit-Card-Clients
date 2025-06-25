# Predicting the Default of Credit Card Clients

This repository is a complete, end-to-end analysis of the “Default of Credit Card Clients” dataset (UCI ML Repository). It guides you step by step—from raw data cleaning all the way through model development and reporting:

## 📂 Repository Structure

- **`main.Rproj`**  
  RStudio project file to open the entire analysis in one place.

- **Data Cleaning & Preparation**  
  - `Cleaning and Manipulating our DATA.Rmd` / `.html`  
    Shows how we import raw data, handle missing values, recode factors and create derived variables.

- **Exploratory Analysis**  
  - `Analyse.Rmd` / `.html`  
    Descriptive statistics, distributions and initial insights on key predictors (age, limit balance, payment status, etc.).

- **Correlation Analysis**  
  - `Correlation.Rmd` / `.html`  
    Pairwise correlation matrices and heatmaps to identify multicollinearity issues.

- **Sampling**  
  - `Sampling.Rmd` / `.html`  
    Techniques for train/test splitting, stratified sampling to preserve default rate proportions.

- **Modeling**  
  - `Modeling1,0.Rmd` & `Modeling.html`  
    Builds and evaluates a logistic regression model. Includes coefficient interpretation, ROC curve, confusion matrix and performance metrics.

- **Report Overview**  
  - `overview.Rmd` / `.html`  
    A polished executive summary compiling key findings, model results and recommendations.

- **Supporting Files**  
  - `model_logistic.RData` – the pre-trained logistic regression object.  
  - `istockphoto-1409700717-612x612.jpg` – illustrative cover image.  
  - `index.html` & `index1` – entry-point web pages for navigating the HTML reports.

---

If you’d like to explore an **interactive version** of this analysis—complete with dynamic inputs, risk gauges and exportable predictions—check out the R Shiny app here:  
🔗 https://github.com/dridi1/Credit_card_default_shiny  
