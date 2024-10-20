# Type 1 Diabetes: Investigating Age at Diagnosis and Risk of Long-Term Complications

## Project Overview

This project aims to explore the relationship between the age at diagnosis of Type 1 diabetes and the risk of developing long-term complications. Type 1 diabetes (T1D) is a chronic condition that typically develops early in life, and long-term complications can include cardiovascular disease, neuropathy, retinopathy, and kidney disease. The analysis seeks to determine whether younger diagnosis age is associated with a higher risk of these complications.

## Dataset

The dataset used for this project includes patient data filtered to include only those diagnosed with Type 1 diabetes. Key variables in the dataset include:

- **Diagnosis Age:** The age at which the patient was diagnosed with Type 1 diabetes.
- **Complication Status:** Whether the patient has developed any long-term complications.
- **Complication Types:** Specific complications (e.g., cardiovascular, neuropathy, retinopathy).
- **Other Variables:** Gender, ethnicity, socioeconomic status, treatment history, and more.

The dataset is sourced from [insert data source, e.g., a healthcare provider, open data platform], and contains anonymized patient information.

## Research Question

The primary research question for this project is:

**Does a younger age at diagnosis increase the likelihood of developing long-term complications in Type 1 diabetes patients?**

This question will be investigated using statistical analysis, including:

- Exploratory Data Analysis (EDA)
- Hypothesis testing
- Logistic regression and/or survival analysis

## Analysis Plan

### 1. Data Cleaning and Preprocessing
- Handle missing values.
- Filter the dataset to include only Type 1 diabetes patients.
- Create new variables if necessary (e.g., binary indicator for the presence of complications).

### 2. Exploratory Data Analysis (EDA)
- Descriptive statistics for diagnosis age and complication status.
- Visualize the distribution of diagnosis age.
- Compare complication rates across different diagnosis age groups.

### 3. Statistical Analysis
- Hypothesis testing to investigate whether there is a statistically significant difference in complication rates between patients diagnosed at a younger vs. older age.
- Logistic regression to model the likelihood of complications based on diagnosis age and other covariates.
- Survival analysis to explore time-to-complication in relation to diagnosis age.

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
- **Lifelines**: Survival analysis

## How to Run

1. Clone this repository: 
    ```bash
    git clone https://github.com/your-repo/type1-diabetes-complications.git
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

The key findings of the project, including statistical summaries, visualizations, and model results, will be presented in the **results** folder or within the project report.

## Conclusion

The conclusion section of the project will summarize the findings and their implications for Type 1 diabetes treatment and patient management, particularly in terms of early diagnosis and risk management for long-term complications.

## Future Work

This project has the potential for further analysis, such as:
- Expanding the dataset to include a larger cohort.
- Investigating the role of additional risk factors (e.g., socioeconomic status, treatment types).
- Performing time-series analysis of patient outcomes over time.

## Authors

- **Rishab Jain** - Operations Research and Information Engineering, Cornell Tech
- **Mindshu Liu** - Co-author and collaborator

