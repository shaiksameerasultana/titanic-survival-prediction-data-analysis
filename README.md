# **titanic-survival-prediction-data-analysis**
# **Objective of the project**
The goal of this project is to analyze the Titanic passenger dataset to:
Understand passenger demographics

Handle missing and duplicate 

Detect and remove outliers

Visualize key features

Prepare data for further modeling

# **📊 Dataset Details**
Source: Titanic dataset (Kaggle/open-source)

Rows: 891 passengers

Columns: 12 features

Key Columns: Age, Fare, Sex, Pclass, Embarked, Survived, etc.

# **Techniques Used while Loading data using pandas**
Data Exploration (head, tail, info, describe)

Data Cleaning (null handling, duplicates, outliers)

Data Preprocessing (renaming, filtering)

Data Visualization (matplotlib & seaborn)

Optional: Classification Modeling (Logistic Regression)
# **Tools Used**
Python

pandas

numpy

matplotlib

seaborn

jupyter notebook in vs code
# **Report**
## 📈 Titanic Dataset Analysis – Final Report Output

---

### 🎯 **Project Summary:**

After analyzing the Titanic dataset, we have discovered several important patterns related to passenger survival, demographics, and travel class. The data was cleaned, visualized, and interpreted to understand the factors affecting survival rates during the Titanic disaster.

---

### 📊 **Key Findings:**

#### 1. **Survival Rate**

* Out of 891 passengers:

  * **342 survived** (\~38.4%)
  * **549 did not survive** (\~61.6%)

#### 2. **Gender Impact**

* **Females** had a significantly higher survival rate (\~74%) than **males** (\~19%).
* “Women and children first” policy is reflected in the data.

#### 3. **Class and Survival**

* Passengers in **1st class** had the **highest survival rate (\~63%)**.
* 3rd class passengers had the **lowest survival rate (\~24%)**.
* Class played a **major role** in determining access to lifeboats.

#### 4. **Age Distribution**

* The **average passenger age** was around **29 years**.
* Children (age < 16) had **better chances** of survival than middle-aged adults.

#### 5. **Fare Insights**

* Fare amounts varied widely, indicating class differences.
* Higher fares were mostly associated with **1st class** and **better survival odds**.

#### 6. **Missing and Duplicate Data**

* `Cabin` had a large number of missing values (over 70%) and was dropped.
* Missing values in `Age` were handled using median imputation.
* Dataset was cleaned to remove **duplicate entries and null values**.

#### 7. **Outliers**

* Outliers were found in `Age` and `Fare` using IQR (Interquartile Range) method.
* These were visualized using **box plots** and removed to avoid skewed analysis.

---

### 📈 **Visualization Summary:**

| Chart Type   | Insight Obtained                          |
| ------------ | ----------------------------------------- |
| Countplot    | Gender & Class-wise survival              |
| Boxplot      | Age and Fare outlier detection            |
| Heatmap      | Correlation between numeric features      |
| Histogram    | Age and Fare distribution                 |
| Violin plot  | Survival distribution across gender/class |
| Scatter plot | Fare vs Age (with survival hue)           |

---

### ✅ **Final Conclusion:**

* **Women, children, and 1st class passengers** had significantly higher chances of survival.
* The dataset shows strong correlation between survival and **gender, class, and fare**.
* Data preprocessing and visualization enabled us to clean and interpret the dataset effectively.
* The cleaned dataset is now ready for predictive modeling (e.g., logistic regression, decision trees) for survival prediction.











