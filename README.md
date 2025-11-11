# 🎾 Serving Through Change: Evolution of ATP Surfaces (2000–2024)

**Author:** Gabriele Giugliarelli  

This project analyzes how ATP court surfaces and match dynamics have evolved over the past two decades.  
Using Jeff Sackmann’s open ATP dataset, it explores how the importance of serve and return statistics has changed over time, and whether modern surfaces have converged in playing characteristics.

---

## Overview
- Collected and cleaned ATP data (2000–2024) from Jeff Sackmann’s public repository  
- Focused on standard surfaces: Hard, Clay, Grass  
- Built key performance indicators: 1stServe%, 1stWon%, 2ndWon%, ServicePointsWon%, ReturnPointsWon%  
- Trained yearly Random Forest models to study the evolution of feature importance by surface  
- Visualized serve/return trends and discussed the convergence of playing styles

---

## 📊 Key Findings
- Serve-related metrics (1stServe%, 1stWon%, ServicePointsWon%) remain dominant across all surfaces.  
- Return performance shows slight decline in importance over time.  
- Despite surface slowdowns, overall playing styles have converged due to increased player power and athleticism.

---

## Tech Stack
Python · pandas · numpy · matplotlib · seaborn · scikit-learn

---

## How to Run
You can open and run the notebook directly in **Google Colab**.  
If you want to run it locally:  
1. Clone this repository: git clone https://github.com/<your-username>/tennis-surface-evolution.git  
2. (Optional) Install dependencies: pip install -r requirements.txt  
3. Download ATP match data from Jeff Sackmann’s tennis_atp repository and place the CSV files inside `data/raw/`.  
4. Open the notebook `notebooks/tennis_surface_evolution.ipynb` and run all cells.

---

## Note on Data Download
Some systems (especially Windows) may not have `wget` installed.  
If so, download the CSVs manually or use this Python alternative:  
`import urllib.request`  
`urllib.request.urlretrieve(url, "data/raw/atp_matches_2024.csv")`

---

## Contact
**Author:** Gabriele Giugliarelli  
**GitHub:** [@your-username](https://github.com/your-username)

