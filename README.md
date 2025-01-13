# Dr. Semmelweis and Handwashing: Data Analysis Project

## 📜 Project Description
This project is inspired by the groundbreaking work of Dr. Ignaz Semmelweis, who discovered the importance of handwashing in reducing maternal mortality. Using historical data from 1841 to 1849, we analyze trends in maternal mortality and demonstrate the impact of mandatory handwashing on reducing deaths from puerperal fever.

The analysis is performed using Python and includes visualizations, statistical tests, and interactive charts.

---

## 🔍 Features
1. **Data Exploration:**
   - Overview of the dataset (shape, columns, missing values).
   - Calculations for average monthly births and deaths.
   
2. **Visualizations:**
   - Time-series plots of births and deaths.
   - Twin-axis plots for monthly trends.
   - Annual death proportions by clinic.
   
3. **Impact of Handwashing:**
   - Comparison of mortality rates before and after handwashing was made mandatory.
   - Rolling averages, box plots, KDE plots, and statistical tests to validate findings.

4. **Statistical Analysis:**
   - T-test to assess the significance of changes in mortality rates.

---

## 📂 Project Structure
Analise_Fièvre_Puérpérale/
│
├── clinic_data/
│   ├── annual_deaths_by_clinic.csv   # Données annuelles
│   ├── monthly_death.csv             # Données mensuelles
│
├── clinic_analyses/
│   ├── _analyser_données_Fièvre_Puérpérale.pdf  # Rapport ou documentation
│   ├── clinic.py                    # Script Python principal pour les analyses
│
├── README.md                        # Description du projet
├── requirements.txt                 # Dépendances Python nécessaires

---

## 📊 Technologies Used
- **Python 3.7+**: Programming language.
- **Libraries**:
  - Pandas: Data manipulation.
  - Matplotlib & Seaborn: Data visualization.
  - Plotly: Interactive visualizations.
  - NumPy: Numerical computations.
  - SciPy: Statistical testing.

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   https://github.com/asmaaoualidi/Analise_Fi-vre_Puerp-rale.git

2. Navigate to the project directory:
   ```bash
    cd Analise_Fi-vre_Puerp-rale

3. Install required libraries:
   ```bash
   pip install -r requirements.txt

4. Run the analysis script:
   ```bash
   python clinic_analyses/clinic.py

5. Review the visualizations generated in the visualizations/ folder.

---

✨ Acknowledgments
Inspired by the work of Dr. Ignaz Semmelweis.
Data sources: Historical datasets for analysis of maternal mortality.
=======
# Analise_Fi-vre_Puerp-rale
Une analyse des données hospitalières de 1841 à 1849 pour sauver des vies.

