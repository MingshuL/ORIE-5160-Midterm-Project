# Diabetes: Investigating Age at Diagnosis and Risk of Long-Term Complications

## Project Overview

This project explores the relationship between the age at diagnosis of both Type 1 and Type 2 diabetes and the risk of developing long-term complications. Diabetes, particularly when diagnosed at a young age, can lead to complications such as cardiovascular disease, neuropathy, retinopathy, and kidney disease. The primary aim is to determine whether a younger diagnosis age is associated with a higher risk of these complications in both Type 1 and Type 2 diabetes patients.

## Dataset

The dataset used for this project includes patient data filtered to include only those diagnosed with either Type 1 or Type 2 diabetes. Key variables in the dataset include:

- **Diagnosis Age:** The age at which the patient was diagnosed with diabetes.
- **Diabetes Type:** Whether the patient has Type 1 or Type 2 diabetes.
- **Complication Status:** Whether the patient has developed any long-term complications.
- **Complication Types:** Specific complications (e.g., cardiovascular, neuropathy, retinopathy).

The dataset is sourced from [], and contains anonymized patient information.

## Research Question

The primary research question for this project is:

**Does a younger age at diagnosis increase the likelihood of developing long-term complications in Type 1 and Type 2 diabetes patients?**

This question will be investigated using statistical analysis, including:

- Exploratory Data Analysis (EDA)
- Hypothesis testing
- Logistic regression and/or survival analysis

## Analysis Plan

### 1. Data Cleaning and Preprocessing
- Handle missing values.
- Filter the dataset to include only diabetes patients (both Type 1 and Type 2).
- Create new variables if necessary (e.g., binary indicator for the presence of complications, separate indicators for Type 1 and Type 2 diabetes).

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics for diagnosis age, diabetes type, and complication status.
- Visualize the distribution of diagnosis age across Type 1 and Type 2 patients.
- Compare complication rates across different diagnosis age groups and between diabetes types.

### 3. Statistical Analysis
- Hypothesis testing to investigate whether there is a statistically significant difference in complication rates between patients diagnosed at a younger vs. older age, and between diabetes types.
- Logistic regression to model the likelihood of complications based on diagnosis age, diabetes type, and other covariates.

### 4. Model Evaluation
- Evaluate model performance using accuracy, precision, recall, and AUC for logistic regression.
- Use cross-validation to assess model robustness.

## Tools & Libraries

The following tools and libraries are used in this project:

- **Python 3.8+**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib / Seaborn**: Data visualization
- **SciPy / Statsmodels**: Hypothesis testing and statistical analysis
- **Scikit-learn**: Machine learning algorithms for logistic regression and model evaluation

## How to Run

1. Clone this repository: 
    ```bash
    git clone https://github.com/your-repo/diabetes-complications.git
    ```

2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebooks or scripts to perform the analysis:
    ```bash
    jupyter notebook EDA.ipynb
    ```
    or
    ```bash
    python analysis.py
    ```

## Results

The key findings of the project, including statistical summaries, visualizations

