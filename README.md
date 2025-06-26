### 🧠 Mental Health in Tech – Exploratory Data Analysis (EDA)

---

### 📌 **Project Overview**

This project explores the state of mental health in the technology industry using data from a global survey conducted in 2014 by Open Sourcing Mental Illness (OSMI). The aim is to uncover insights about employee perceptions, workplace policies, treatment-seeking behavior, and stigma related to mental health.

---

### 🎯 **Business Objective**

To analyze patterns in mental health awareness, support systems, and treatment behavior within tech workplaces, and help organizations:

* Identify key indicators that influence mental health outcomes
* Create actionable, data-driven policies for improving employee well-being
* Reduce stigma and promote open mental health culture in the workplace

---

### 📁 **Dataset Information**

* **Source:** OSMI Mental Health in Tech Survey (2014)
* **Rows:** 1251 responses
* **Columns:** 25 features related to demographics, work environment, mental health treatment, and employer support
* **License:** Public domain (research use)

---

### 🧼 **Data Cleaning Highlights**

* Dropped high-missing-value columns like `state`, `comments`
* Standardized and encoded gender, treatment, and work interference fields
* Filtered unrealistic age entries
* Encoded categorical features (Yes/No → 1/0) for numerical analysis
* Filled missing values in key columns (`self_employed`, `work_interfere`)

---

### 📊 **Key Visualizations & Insights**

* **Gender Distribution**: Male-dominated, with limited representation from women and non-binary individuals.
* **Work Interference vs Treatment**: Strong correlation — the more work is affected, the more likely people seek treatment.
* **Remote Work**: No major influence on treatment-seeking behavior.
* **Company Size**: Larger companies offer more mental health benefits; small firms often lack structured support.
* **Disclosure Fears**: Most employees feel uncomfortable discussing mental health with supervisors or during interviews.
* **Observed Consequences**: Many have seen coworkers suffer after disclosing mental health issues.

---

### 📈 **Tools Used**

* Python (Pandas, NumPy, Seaborn, Matplotlib)
* Jupyter Notebook
* Microsoft PowerPoint (for visual presentation)

---

### ✅ **Final Conclusion**

Mental health support in the tech industry remains inconsistent and stigmatized. While some progress exists, many employees are still unsure about their rights or fear consequences of openness. The data emphasizes the need for clear communication, proactive HR policies, and a workplace culture where **mental health is treated as seriously as physical health**.

---

### 📂 **Files Included**

* `final_cleaned_mental_health_survey.csv` – Original cleaned dataset
* `Mental_Health_EDA.ipynb` – Jupyter notebook with full EDA
* `Mental_Health_in_Tech_Survey.pptx` – PowerPoint presentation
* `README.md` – Project documentation

---

### 🤝 **Acknowledgments**

* Open Sourcing Mental Illness (OSMI) for open dataset
* Google & Coursera – Project Management and Data Analysis foundations
