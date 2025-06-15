
# 🚗 Insurance Risk Analytics & Predictive Modeling

**Author:** Nahom Esayas  
**Organization:** AlphaCare Insurance Solutions (ACIS)  
**Project Timeline:** June 11–17, 2025  

---

## 📌 Project Objective

This project is focused on analyzing historical car insurance data to identify low-risk customer segments and optimize premium pricing. The ultimate goal is to support AlphaCare Insurance Solutions in tailoring competitive and profitable insurance products in South Africa.

---

## 📊 Business Goals

- Analyze car insurance claims to uncover insights into profitability and risk.
- Identify low-risk segments where premiums can be optimized.
- Develop machine learning models to predict claims and premium pricing.
- Perform hypothesis testing to validate assumptions about risk distribution.

---

## 🧠 Learning Outcomes

- Applied Exploratory Data Analysis (EDA) and Statistical Modeling
- Built predictive models using supervised ML techniques
- Performed A/B testing with real-world insurance data
- Practiced Data Version Control using DVC
- Collaborated with Git and GitHub using CI/CD practices

---

## 🗃️ Project Structure

```bash
.
├── data/                   # Raw and processed data (DVC-tracked)
├── notebooks/              # Jupyter notebooks for EDA and modeling
├── scripts/                # Python scripts for data processing and modeling
├── reports/                # Generated reports (PDF, markdown)
├── .dvc/                   # DVC tracking and config
├── .github/workflows/      # GitHub Actions CI/CD setup
├── README.md               # Project overview (this file)
├── requirements.txt        # Python dependencies
└── dvc.yaml                # DVC pipeline config
```

---

## 🧪 Setup Instructions

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/insurance-risk-analytics.git
   cd insurance-risk-analytics
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Install and configure DVC**
   ```bash
   pip install dvc
   dvc init
   dvc remote add -d localstorage ../dvc-storage
   dvc pull
   ```

5. **Run notebooks**
   ```bash
   jupyter notebook
   ```

---

## 📈 Key Tasks

- [x] Git & GitHub Setup
- [x] Data Understanding & Cleaning
- [x] Exploratory Data Analysis (EDA)
- [x] Statistical Summary & Visualization
- [x] Data Version Control with DVC
- [ ] Hypothesis Testing (Task 3)
- [ ] Predictive Modeling (Task 4)
- [ ] Final Report and Recommendations (Task 5)

---

## 🧠 Tools & Technologies

- Python, Jupyter Notebooks
- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- DVC (Data Version Control)
- Git, GitHub Actions (CI/CD)

---

## 📝 References

- [50 Common Insurance Terms](https://www.cornerstoneinsurancebrokers.com/blog/common-insurance-terms)
- [A/B Testing Guide](https://www.optimizely.com/optimization-glossary/ab-testing/)
- Project dataset provided by ACIS (Feb 2014 – Aug 2015)

---

## 📬 Contact

For questions or collaboration, feel free to reach out:  
**Nahom Esayas** – nahomesayas3@gmail.com
