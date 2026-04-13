# 📊 Student Skill Gap Analysis & Career Prediction

## 📌 Project Overview

This project analyzes the **skill gap among students** by evaluating their **technical and soft skills**. It also predicts whether a student is **career-ready or needs improvement** using a Machine Learning model.

The goal is to identify gaps and help students improve their readiness for job opportunities.

---

## 🚀 Features

* 📂 Data cleaning and preprocessing
* 📊 Exploratory Data Analysis (EDA)
* 📈 Visualization of student performance
* 🧠 Skill gap detection (Technical & Soft Skills)
* 🤖 Machine Learning model using Logistic Regression
* 📉 Confusion Matrix & Performance Evaluation
* 🎯 Career readiness prediction for new students

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📁 Dataset

* File: `Studentskillgap.xlsx`
* Contains:

  * Student name
  * Course
  * Technical skill rating
  * Soft skill rating
  * Projects
  * Job role aspirations

---

## 🔍 Key Analysis Performed

### 1. Data Cleaning

* Removed null values
* Converted ratings into numeric format
* Cleaned column names

### 2. Exploratory Data Analysis

* Average technical and soft skills
* Student distribution by course
* Top performing students

### 3. Skill Gap Detection

* Threshold-based classification:

  * Rating < 3 → Needs Improvement
  * Rating ≥ 3 → Good
* Overall skill gap classification

### 4. Career Readiness Score

```
Career Readiness Score = (Technical + Soft Skills) / 2
```

### 5. Machine Learning Model

* Model: Logistic Regression
* Input Features:

  * Technical Skills
  * Soft Skills
* Output:

  * 0 → Needs Improvement
  * 1 → Career Ready

---

## 📊 Results

* Students with scores closer to **5** are highly career-ready
* Students with scores around **2–3** need improvement
* Model provides good accuracy in predicting career readiness

---

## 📉 Visualizations

* Bar chart (students per course)
* Skill comparison chart
* Skill gap distribution
* Career readiness histogram
* Confusion matrix

---

## 🔮 Prediction Example

```python
new_student = [[2, 4]]
```

Output:

```
Needs Improvement
```

---

## 📂 Project Structure

```
skill-gap-analysis/
│── skill_gap_analysis.py
│── skill_gap_analysis.ipynb
│── Studentskillgap.xlsx
│── README.md
```

---

## ⚙️ How to Run

### ▶️ Using Python

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
python skill_gap_analysis.py
```

### ▶️ Using Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
skill_gap_analysis.ipynb
```

---

## 🎯 Future Improvements

* Add more features (attendance, certifications)
* Use advanced models (Random Forest, XGBoost)
* Build a web dashboard using Flask/Spring Boot
* Real-time student analysis system

---

## 👨‍💻 Author

**Pallavi Kumari**

---

## ⭐ Conclusion

This project helps in identifying student skill gaps and predicting career readiness, making it useful for **students, educators, and recruiters**.
