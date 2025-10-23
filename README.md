
## 🧠 Analyzing Students’ Habits and Academic Performance

### 🎯 Project Overview

This project explores how various student lifestyle habits—such as study time, sleep, diet, exercise, and social media usage—impact academic performance.
Using a dataset of **1,000 students**, the team conducted statistical analysis, hypothesis testing, and data visualization to identify the key factors that influence academic success.

---

### 📊 Objective

To analyze correlations between **academic performance (exam scores)** and multiple behavioral, lifestyle, and demographic variables, helping universities and students make data-driven improvements to academic outcomes.

---

### 🔍 Research Question

> What student habits most strongly correlate with higher academic performance?

---

### 🧩 Hypotheses

* **H1:** More study hours per day are significantly associated with higher exam scores.
* **H2:** Habits like sleep, diet, and exercise positively impact academic performance.
* **H3:** High screen time (social media, Netflix) negatively affects academic outcomes.

---

### 🧮 Dataset

* **Source:** [Kaggle – Student Habits vs Academic Performance](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)
* **Samples:** 1,000 students
* **Format:** `student_habits_performance.csv`
* **Data Collected:**

  * 📚 Study hours, attendance rate
  * 💤 Sleep hours, diet quality, exercise frequency
  * 📱 Social media & Netflix usage
  * 👨‍👩‍👧 Parental education, part-time job status, extracurriculars
  * 🧾 Exam score (target variable)

---

### 🧰 Tools & Technologies

| Category                   | Tools Used                                               |
| -------------------------- | -------------------------------------------------------- |
| **Programming & Analysis** | Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)       |
| **Statistical Testing**    | Pearson/Spearman correlation, t-tests, ANOVA, Regression |
| **Notebook Environment**   | Jupyter Notebook (`Gym rats code.ipynb`)                 |
| **Documentation**          | MS Word, PowerPoint, PDF Report                          |
| **Visualization**          | Matplotlib, Seaborn                                      |
| **Presentation**           | PowerPoint Poster & Slides                               |

---

### 🧠 Statistical Tests Summary

The project involved **35 hypothesis tests** across individual and combined variables.
Key examples include:

| Test                | Variables                               | Result                     | Significance      |
| ------------------- | --------------------------------------- | -------------------------- | ----------------- |
| Pearson Correlation | Study Hours ↔ Exam Score                | r = 0.33                   | ✅ Significant     |
| Independent t-test  | Part-Time Job ↔ Exam Score              | p = 0.086                  | ❌ Not significant |
| One-way ANOVA       | Diet Quality ↔ Exam Score               | p = 0.018                  | ✅ Significant     |
| Pearson Correlation | Sleep Hours ↔ Exam Score                | Positive moderate relation | ✅ Significant     |
| Two-way ANOVA       | Study Hours + Social Media ↔ Exam Score | Interaction found          | ✅ Significant     |

*(Full table available in `Hypothesis Tests.docx`)*

---

### 📈 Key Findings

* 📚 **Study Hours:** Strong positive relationship with academic performance.
* 😴 **Sleep (6–8 hrs):** Optimal range for higher scores.
* 🍎 **Diet & Exercise:** Better lifestyle choices → higher scores and mental health.
* 📱 **Screen Time:** High social media and Netflix usage lowers exam performance.
* 👩‍🏫 **Attendance:** Consistently linked with better outcomes.
* 💼 **Part-time Jobs:** Minor, non-significant effect on grades.
* 🧠 **Mental Health:** Improved mental health is positively correlated with scores.

---

### 📊 Visualization Highlights

Created using **Matplotlib & Seaborn**:

* Exam Score vs Study Hours
* Exam Score vs Social Media Use
* Exam Score vs Gym Attendance
* Exam Score vs Diet Quality
* Sleep Hours vs Exam Score
* Exam Score by Gender
  *(see PowerPoint & Notebook for visuals)*

---


### 🧾 Results Summary

| Habit         | Relationship with Performance | Interpretation                                        |
| ------------- | ----------------------------- | ----------------------------------------------------- |
| Study Hours   | Positive                      | More study → better performance                       |
| Sleep Hours   | Positive (6–8 hrs optimal)    | Balanced sleep helps learning                         |
| Social Media  | Negative                      | Screen addiction reduces scores                       |
| Diet Quality  | Positive                      | Healthy eating improves focus                         |
| Exercise      | Positive                      | Regular exercise improves performance & mental health |
| Attendance    | Positive                      | Higher attendance → higher grades                     |
| Part-Time Job | Weak negative                 | Small, statistically insignificant impact             |

---

### 🧭 Conclusion

Academic performance is **multifactorial**, influenced not just by study time but also by overall lifestyle and well-being.
Healthy routines—adequate sleep, exercise, and diet—combined with controlled screen time, contribute to better student success.

---

### 💡 Recommendations

* Promote **time management workshops** for balanced study and rest.
* Encourage **healthy campus lifestyle**: sleep hygiene, exercise programs, balanced diets.
* Limit **excessive social media use** through digital wellness campaigns.
* Universities should adopt a **holistic approach** to student well-being.

---

### ⚠️ Limitations

* Self-reported survey data → potential bias.
* Simplified variables (diet, mental health) may reduce precision.
* Unequal group sizes in categorical data.
* Lack of longitudinal data (no long-term tracking).

---

### 📂 Repository Contents

| File                                                       | Description                                                              |
| ---------------------------------------------------------- | ------------------------------------------------------------------------ |
| `student_habits_performance.csv`                           | Cleaned dataset used for analysis                                        |
| `Gym rats code.ipynb`                                      | Python notebook with data cleaning, visualization, and statistical tests |
| `Hypothesis Tests.docx`                                    | Detailed list of all hypothesis tests performed                          |
| `Student_Habits_Performance_Report_updated.pdf`            | Full project report                                                      |
| `Analyzing Students’ Habits and Academic Performance.pptx` | Presentation slides                                                      |
| `Team Member Roles and Contributions.pdf`                  | Team roles and responsibilities                                          |

---

### 🏫 Academic Information

**Egypt University of Informatics**
**Faculty of Computer and Information Systems**
**Course:** Data Analysis
**Date of Submission:** May 25, 2025

