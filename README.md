# Hi, I'm Nour El Houda 👋

B.Sc. student in Statistics and Data Science at LMU Munich (minor: Computer Science). I build carefully evaluated projects on real data: data quality, process analysis and prediction models, with baselines, leakage checks and honest train/test splits (by time or by company).

- 🎓 Statistics & Data Science, LMU München — since 2024
- 📍 Munich, Germany
- 🗣️ Arabic & French (native) · German & English (fluent)
- 🛠️ Python · R · SQL · scikit-learn · Excel
- 🧰 DuckDB · pandas · PM4Py · Matplotlib · Git/GitHub · Jupyter
- 🔨 Currently building: projects in data analysis, process mining and machine learning

## Featured projects

### [Executive Job Screener](https://github.com/nour-nessah/exec-job-screener)

Screens job postings against a $100k salary benchmark, even when no salary is stated, and sends only the uncertain cases to a person (123,849 LinkedIn postings, 2023–2024).

- Data-quality pipeline in SQL (DuckDB): salary annualisation, plausibility checks, 57 automated tests
- Salary-disclosure bias and text leakage analysed and corrected; train/test split by company
- Calibrated text classifier: F1 0.82 vs 0.61 for a keyword baseline; 66% of postings decided automatically at 95% accuracy
- Interactive demo with word-level explanations; every analytical decision documented

`Python` `SQL` `DuckDB` `scikit-learn` `pytest` `Streamlit`

### [Purchase-to-Pay Process Mining and Late-Order Prediction](https://github.com/nour-nessah/p2p-process-mining)

Process mining and a first prediction model on a real purchase-order event log (BPI Challenge 2019).

- Cleaned and analysed 1.6 million events (251,654 orders) with SQL (DuckDB) and Python
- Process map, variants, rework and conformity checks
- Predicts at order creation whether an order will not be settled within 126 days (time-based split, comparison with a baseline, checks against leakage)

`Python` `SQL` `DuckDB` `PM4Py` `scikit-learn`

## 🔨 Work in progress

New projects on real data are added to this profile as they are finished.

## Contact

nournessahninou@gmail.com
