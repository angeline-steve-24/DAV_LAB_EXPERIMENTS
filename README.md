# 📊 Data Analytics and Visualization Lab

This repository contains the programs and experiments performed as part of the **Data Analytics and Visualization (DAV)** laboratory.

The experiments focus on **Python-based data manipulation, statistical analysis, data visualization, hypothesis testing, regression modeling, and model validation** using libraries such as NumPy, Pandas, Matplotlib, Seaborn, SciPy, Statsmodels, Plotly, Bokeh, and Scikit-learn.

---

## 🛠️ Technologies & Libraries

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Statsmodels
* Plotly
* Bokeh
* Scikit-learn

---

## 📚 Experiments

### 1. Installation and Exploration

Installation and exploration of:

* NumPy
* SciPy
* Jupyter Notebook
* Statsmodels
* Pandas
* Matplotlib
* Seaborn
* Plotly
* Bokeh

The experiment verifies the installation and basic functionality of the libraries.

---

### 2. Data Handling and Analysis

#### A. NumPy Array Operations

Performed:

* Array creation
* Indexing and slicing
* Element-wise operations
* Aggregation
* Boolean operations
* Boolean masking
* Fancy indexing
* Reshaping
* Structured arrays

#### B. Pandas DataFrame Operations

Performed:

* Loading datasets
* Data inspection
* Handling missing values
* Data transformation
* Filtering
* Grouping
* Sorting
* Removing duplicates
* Exporting processed data

#### C. Reading Data from Different Sources

Data was read and processed from:

* Text/CSV files
* Excel files
* Web-based sources

#### D. Descriptive Analytics using Iris Dataset

Performed:

* Basic dataset exploration
* Summary statistics
* Univariate analysis
* Bivariate analysis
* Histograms
* Boxplots
* Pair plots

The Iris dataset contains 150 samples belonging to Setosa, Versicolor, and Virginica species.

---

## 3. Statistical Analysis Using Diabetes Datasets

The experiments use **UCI Diabetes** and **Pima Indians Diabetes** datasets.

### A. Univariate Analysis

Calculated:

* Frequency
* Mean
* Median
* Mode
* Variance
* Standard Deviation
* Skewness
* Kurtosis

### B. Bivariate Analysis

Performed:

* Linear Regression
* Logistic Regression
* R² score evaluation
* Accuracy evaluation

### C. Multiple Regression Analysis

Multiple regression was performed to predict **BMI** using multiple independent variables such as:

* Glucose
* Blood Pressure
* Age

The models were evaluated using R² scores.

### D. Comparison of UCI and Pima Diabetes Datasets

Compared the datasets based on:

* Central tendency
* Dispersion
* Skewness
* Kurtosis
* Regression performance
* Classification performance

---

## 4. Data Visualization and Hypothesis Testing

### A. Normal Curves

Visualized the distributions of important attributes such as:

* Glucose
* BMI

using histograms, KDE curves, and normal distribution curves.

### B. Z-Test

Performed a Z-test to determine whether the mean glucose level significantly differs from a specified population mean.

The experiment uses a significance level of **0.05** and interprets the result using the p-value.

### C. T-Test

Performed an independent T-test to compare numerical variables between the UCI and Pima Diabetes datasets.

Variables include:

* Glucose
* Blood Pressure
* BMI

### D. ANOVA

Performed ANOVA to analyze differences between group means.

The experiment includes One-Way ANOVA and discusses Two-Way ANOVA.

---

## 5. Model Building and Validation

### A. Linear Regression Model

Built and validated Linear Regression models using the diabetes datasets.

Evaluation metrics:

* R² Score
* Mean Squared Error (MSE)
* Mean Absolute Error (MAE)

### B. Logistic Regression Model

Built Logistic Regression models for diabetes classification.

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

### C. Time Series Analysis

Performed time-series analysis to study sequential diabetes-related data and identify:

* Trends
* Patterns
* Seasonality

---

## 📁 Repository Structure

```text
Data-Analytics-and-Visualization/
│
├── Experiment-1/
│   └── Installation_and_Exploration.ipynb
│
├── Experiment-2/
│   ├── NumPy_Operations.ipynb
│   ├── Pandas_DataFrame.ipynb
│   ├── Reading_Data.ipynb
│   └── Iris_Descriptive_Analytics.ipynb
│
├── Experiment-3/
│   ├── Univariate_Analysis.ipynb
│   ├── Bivariate_Analysis.ipynb
│   ├── Multiple_Regression.ipynb
│   └── Dataset_Comparison.ipynb
│
├── Experiment-4/
│   ├── Normal_Curves.ipynb
│   ├── Z_Test.ipynb
│   ├── T_Test.ipynb
│   └── ANOVA.ipynb
│
├── Experiment-5/
│   ├── Linear_Regression_Model.ipynb
│   ├── Logistic_Regression_Model.ipynb
│   └── Time_Series_Analysis.ipynb
│
├── datasets/
│   ├── iris_dataset.csv
│   ├── uci_diabetes.csv
│   └── pima_diabetes.csv
│
└── README.md
```

> Rename the folders/files above according to the actual names in your GitHub repository.

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### 2. Open the Project

```bash
cd Data-Analytics-and-Visualization
```

### 3. Install Required Libraries

```bash
pip install numpy scipy jupyter statsmodels pandas matplotlib seaborn plotly bokeh scikit-learn
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the required `.ipynb` file and run the cells.

---

## 📊 Datasets Used

* Iris Dataset
* UCI Diabetes Dataset
* Pima Indians Diabetes Dataset

The diabetes experiments analyze variables including glucose, blood pressure, BMI, insulin, age, and diabetes outcome.

---

## 🎯 Learning Outcomes

Through these experiments, the following skills were developed:

* Data preprocessing and cleaning
* NumPy array manipulation
* Pandas DataFrame operations
* Statistical analysis
* Descriptive analytics
* Data visualization
* Hypothesis testing
* Regression analysis
* Classification
* Model evaluation and validation
* Time-series analysis

---

## 👩‍💻 Author

**Angeline Steve**

Computer Science and Engineering

---

## ⭐ Repository

If you find this repository useful, consider giving it a ⭐!
