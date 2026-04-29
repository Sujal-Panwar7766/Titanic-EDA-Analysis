#  Titanic EDA Analysis

##  Project Overview

This project performs a **Mini Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns related to passenger survival.

The analysis includes:

* Data Cleaning
* Feature Engineering
* Data Visualization
* Insight Generation

---

##  Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Data Cleaning

* Filled missing **Age** values using mean
* Handled missing **Embarked** values using mode
* Dropped unnecessary columns like **Cabin**

---

##  Feature Engineering

* Created **Age Groups** (Child, Teen, Adult, etc.)
* Created **Family Size** using `SibSp + Parch`

---

##  Exploratory Data Analysis (EDA)

### 🔹 Age Distribution

* Visualized using histogram
* Shows distribution of passengers by age

### 🔹 Survival by Age Group

* Children had higher survival rates

### 🔹 Survival by Embarkation Port

* Passengers from Cherbourg (C) had higher survival

### 🔹 Survival by Family Size

* Small families had better survival chances

### 🔹 Correlation Heatmap

* Shows relationships between numerical features

---

##  Key Insights

* Women and children had higher survival rates
* Passenger class significantly affected survival
* Smaller families were more likely to survive

---

##  Project Structure

```
Titanic-EDA-Analysis/
│── Titanic_EDA_Project.ipynb
│── titanic.csv
│── README.md
```

---

##  How to Run

1. Download the dataset
2. Open the notebook in Jupyter/Colab
3. Run all cells step by step

---

##  Conclusion

This project demonstrates how **EDA helps in understanding data patterns** and extracting meaningful insights using visualization techniques.

---

##  Author

**Sujal Panwar**
