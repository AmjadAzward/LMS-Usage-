# LMS-Usage-

A Statistical research on LMS (Learning Management System) usage.

##  Dataset

The Excel document used to analyze the collected data is available in repository

#  Statistical Analysis in Excel

This section explains how to perform **Descriptive Statistics**, **Correlation**, **Regression**, and **T-Test** using **Microsoft Excel** with the **Data Analysis ToolPak**.

---

##  1. Enable Data Analysis ToolPak

1. Go to **File** → **Options**
2. Select **Add-ins**
3. At the bottom, next to **Manage: Excel Add-ins**, click **Go**
4. Check the box for **Analysis ToolPak**
5. Click **OK**

> You will now see **Data Analysis** under the **Data** tab.

---

##  2. Descriptive Statistics

**Purpose:** Summarize data with mean, median, mode, standard deviation, etc.

**Steps:**
1. Go to the **Data** tab → Click **Data Analysis**
2. Choose **Descriptive Statistics** → Click **OK**
3. Set:
   - Input Range (e.g., `A1:A50`)
   - Check **Labels in First Row** (if applicable)
   - Check **Summary Statistics**
4. Select output location → Click **OK**

---

##  3. Correlation

**Purpose:** Measure the strength and direction of the linear relationship between two variables.

**Steps:**
1. Click **Data Analysis** → Select **Correlation**
2. Set:
   - Input Range (e.g., `A1:B50`)
   - Check **Labels in First Row**
   - Grouped by: **Columns**
3. Select output location → Click **OK**

**Interpretation:**
- `+1` = perfect positive correlation  
- `-1` = perfect negative correlation  
- `0` = no correlation

---

##  4. Regression

**Purpose:** Analyze how a dependent variable is affected by one or more independent variables.

**Steps:**
1. Click **Data Analysis** → Select **Regression**
2. Set:
   - Input Y Range = Dependent variable (e.g., `B1:B50`)
   - Input X Range = Independent variable(s) (e.g., `A1:A50`)
   - Check **Labels** if headers are included
3. Optional: Enable **Line Fit Plots**, set **Confidence Level**
4. Select output range → Click **OK**

**Key Outputs:**
- **R Square (R²)**: Goodness of fit
- **P-values**: Check if independent variables are significant
- **Coefficients**: Impact of each variable

---

##  5. T-Test

**Purpose:** Compare the means of two groups to see if they are statistically different.

**Steps:**
1. Click **Data Analysis** → Choose:
   - **t-Test: Two-Sample Assuming Equal Variances**  
   - or **t-Test: Two-Sample Assuming Unequal Variances**
2. Set:
   - Variable 1 Range (e.g., `A1:A50`)
   - Variable 2 Range (e.g., `B1:B50`)
   - Check **Labels**
3. Select output location → Click **OK**

**Interpretation:**
- **P-value < 0.05** → Significant difference
- **P-value ≥ 0.05** → No significant difference
