# PregnancyTrends2002-DataScience: Statistical Insights on Pregnancy Patterns

**Author:** Darious Brown  
**GitHub:** [Dare215](https://github.com/Dare215)  
**Email:** dariousbrown3@icloud.com  

## 1) Project Overview
PregnancyTrends2002-DataScience analyzes data from the 2002 National Survey of Family Growth (NSFG) to explore patterns in pregnancy frequency, outcomes, and related demographic factors.  
The project applies Python-based statistical and visualization methods to uncover key health and social insights.

## 2) Dataset
- **Source:** 2002 NSFG dataset (public health survey)  
- **Files:**  
  - `2002FemPreg.dat.csv` — Cleaned dataset version  
  - `2002 Female Pregency data.ipynb` — Jupyter Notebook with analysis and visuals  
- **Key Variables:** Age, Birth Weight, Pregnancy Outcome, Pregnancy Length, Demographics

## 3) Key Features
- **Descriptive Statistics:** Compute mean, median, and spread for pregnancy-related variables.
- **Outcome Analysis:** Compare birth, miscarriage, and abortion rates by age group.
- **Demographic Insights:** Explore socio-economic factors linked to pregnancy outcomes.
- **Visualization:** Histograms, scatter plots, and bar charts to represent findings.

## 4) Project Structure
```
PregnancyTrends2002-DataScience/
│── 2002 Female Pregency data.ipynb    # Notebook with analysis & visualizations
│── 2002FemPreg.dat.csv                # Dataset
│── README.md                          # Documentation
```

## 5) How to Run

### Option A — Python / Terminal
```bash
# Create and activate virtual environment
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate    # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook "2002 Female Pregency data.ipynb"
```

### Option B — PyCharm
1. Open folder in PyCharm  
2. Configure Python interpreter (point to `.venv`)  
3. Install dependencies from `requirements.txt`  
4. Run the notebook

## 6) Results Summary
- Younger and older maternal age groups show higher rates of non-live birth outcomes.
- Birth weights and pregnancy lengths vary significantly across age and socio-economic groups.
- Clear demographic patterns emerge, indicating the influence of education and income on pregnancy outcomes.

## 7) Ethical Considerations
- Ensure confidentiality when handling sensitive health data.
- Avoid drawing conclusions that stigmatize specific groups.
- Promote data usage for public health improvements.

## 8) Future Enhancements
- Expand analysis to include multiple NSFG years for longitudinal trends.
- Build predictive models for pregnancy outcomes.
- Integrate regional health policy data for correlation studies.

## 9) License
MIT License — Free to use with attribution.
