# Enterprise Ransomware Risk Assessment

**Internship project:** Cybersecurity Virtual Internship  
**Framework:** NIST Cybersecurity Framework (CSF) 2.0  
**Case study:** ABC Services (hypothetical organization)

## Project description
This notebook demonstrates a documentation-based ransomware risk assessment. It defines ten illustrative risk scenarios, calculates risk scores using likelihood × impact, categorizes the scores, maps recommended actions to the six NIST CSF 2.0 functions, and exports a CSV risk register.

**Important scope statement:** This is a hypothetical case study. It does not scan, exploit, or test a real organization. Risk ratings and residual-risk estimates are examples and should not be represented as findings from a live audit.

## Technologies used
- Python 3
- Jupyter Notebook
- pandas
- NIST Cybersecurity Framework (CSF) 2.0 as the risk-management reference

## Files
- `Nikyaa_EnterpriseRansomwareAssessment.ipynb` — complete notebook code and explanations
- `requirements.txt` — Python dependency list
- `Ransomware_Risk_Assessment_Report.docx` — project report
- `Ransomware_Risk_Register.xlsx` — risk register and scoring guide
- `Ransomware_Risk_Assessment_Presentation.pptx` — presentation slides
- `README.md` — project overview and run instructions

## Dataset
No external dataset is required. The risk scenarios are illustrative and are embedded in the notebook. They are not a measured dataset and should not be interpreted as real incident statistics.

## Setup and run instructions

### Option 1: Run in Google Colab
1. Open Google Colab: https://colab.research.google.com/
2. Upload `Nikyaa_EnterpriseRansomwareAssessment.ipynb`.
3. Run the notebook cells from top to bottom.
4. If pandas is missing, run `!pip install -r requirements.txt` after uploading the requirements file, or run `!pip install pandas`.
5. The last code cell exports `ransomware_risk_register.csv`.

### Option 2: Run locally
1. Install Python 3.10 or later and Jupyter Notebook.
2. Open a terminal in the project folder.
3. Install dependencies: `python -m pip install -r requirements.txt`
4. Start Jupyter: `python -m pip install notebook` then `jupyter notebook`
5. Open `Nikyaa_EnterpriseRansomwareAssessment.ipynb` and run all cells.

## Risk scoring
- Likelihood: 1 (rare) to 5 (almost certain)
- Impact: 1 (insignificant) to 5 (severe)
- Score = Likelihood × Impact
- Project-defined bands: 1–5 Low, 6–14 Medium, 15–25 High

These thresholds are illustrative project choices, not universal NIST ratings.

## NIST CSF 2.0 mapping
- Govern
- Identify
- Protect
- Detect
- Respond
- Recover

The mapping is high-level and not a formal compliance certification.

## References
- NIST CSF: https://www.nist.gov/cyberframework
- NIST CSF 2.0: https://doi.org/10.6028/NIST.CSWP.29
- CISA StopRansomware: https://www.cisa.gov/stopransomware
