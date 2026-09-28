# Student Performance Data Analysis

## 📌 Project Overview

This project analyzes the performance of students using their demographic information and exam scores.

The dataset contains information about:

* Gender
* Race/Ethnicity
* Parent's education
* Lunch type
* Test preparation course
* Math score
* Reading score
* Writing score

The main goal is to understand student performance using basic data analysis and statistics.

---

## 🎯 Objectives

The project performs the following tasks:

1. Clean categorical data.
2. Calculate statistical measures for subject scores.
3. Calculate total marks for each student.
4. Calculate percentage performance.
5. Detect extreme performance outliers.

---

## 📂 Dataset Features

| Feature                     | Description                               |
| --------------------------- | ----------------------------------------- |
| Gender                      | Gender of the student                     |
| Race/Ethnicity              | Student's group                           |
| Parental Level of Education | Education level of the student's parent   |
| Lunch                       | Type of lunch received                    |
| Test Preparation Course     | Whether the student completed preparation |
| Math Score                  | Student's math marks                      |
| Reading Score               | Student's reading marks                   |
| Writing Score               | Student's writing marks                   |

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook / Google Colab

---

## 📊 Statistical Analysis

The following statistical measures are calculated for:

* Math Score
* Reading Score
* Writing Score

### Measures Used

* Mean
* Median
* Standard Deviation
* First Quartile (Q1)
* Second Quartile (Q2)
* Third Quartile (Q3)

These measures help us understand the average performance and how much the scores vary.

---

## 🧮 Calculated Features

### Total Marks

The total marks are calculated by adding the three subject scores.

```text
Total Marks = Math + Reading + Writing
```

Since each subject is out of 100, the maximum total is **300**.

### Percentage

```text
Percentage = (Total Marks / 300) × 100
```

This gives the overall percentage of each student.

---

## 🚨 Outlier Detection

The project uses the **IQR (Interquartile Range)** method to find unusual or extreme scores.

### Formula

```text
IQR = Q3 - Q1
```

```text
Lower Limit = Q1 - 1.5 × IQR
```

```text
Upper Limit = Q3 + 1.5 × IQR
```

Scores below the lower limit or above the upper limit are considered outliers.

Outliers are checked separately for:

* Math
* Reading
* Writing

---

## 📈 Expected Output

The analysis provides:

* Clean categorical data
* Statistical summary of subject scores
* Total marks for each student
* Percentage for each student
* Number of outliers in each subject
* Outlier scores

---

## ✅ Conclusion

This project helps us understand student academic performance using simple statistical methods.

It shows the average scores, score variation, overall percentage, and unusual performance values in different subjects.

The analysis can help identify patterns in student performance and understand areas where students perform differently.
