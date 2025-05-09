# 🐎 Predicting Horse Races with Data

This is a data science project focused on **UK horse racing**, using real-world data to estimate race outcomes — just like a bookmaker or bettor would.

We’re using this project to:
- Learn end-to-end sports modeling (from raw data to decision-making)
- Build reusable tools for racing, betting, and beyond
- Document the journey clearly for ourselves and future employers

---

## 🎯 Goal

> Can we estimate a horse’s **chance of winning**, using only the data available *before* a race?

We’re not just modelling — we’re exploring:
- How racing works (distances, classes, going, form, odds)
- What features matter — and which don’t
- How odds reflect market beliefs
- Whether we can spot **value bets** the market has missed

This isn’t a betting tipster project — it’s a **data science learning lab**.

---

## 📍 Current Focus: The Epsom Derby (Flat Racing)

We’re starting with elite UK flat races for **3-year-olds**, like the **Epsom Derby**.

Our early questions:
- What do “Derby-type” races look like?
- How do favourites perform?
- What signals might help us predict future winners?

---

## 🧰 Tools & Tech

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter notebooks
- Public Kaggle datasets (2019 UK racing)
- Git & GitHub for reproducibility and sharing

---

## 📂 Project Structure

```bash
.
├── 01-data-understanding/
│   └── 01-data-audit-2019.ipynb
├── 02-eda/
│   └── 02-eda-derby-structure.ipynb
├── 03-models/
│   └── (coming soon)
├── data/
│   ├── races_2019.csv
│   └── horses_2019.csv
├── README.md
└── requirements.txt
```

## 🗓️ Roadmap: May–June 2025

We're building this project in the run-up to the **2025 Epsom Derby (June 7)**.

This is a short-term learning sprint with a clear goal:

- 🧠 Build a working model using public data  
- 🏇 Apply it to the 2025 Derby field  
- 💸 Make a few small, informed bets for fun and insight

---

### ✅ Phase 1: Data Foundations (✅ In Progress)
- Load & audit raw 2019 racing data  
- Document feature availability  
- Explore data integrity (missing, weird, placeholder values)  
- Structure notebooks around clean process  

---

### 🔎 Phase 2: Early Analysis
- What do Derby-like races look like?  
- How often do favourites win?  
- What features might help us predict outcomes?  

---

### 🤖 Phase 3: First Model
- Train simple model on 2019 races (LogReg, Decision Tree)  
- Estimate win probabilities  
- Compare to market odds  

---

### 🧮 Phase 4: Derby Application
- Scrape (or manually collect) 2025 Epsom Derby racecard  
- Run predictions using our model  
- Look for potential value bets  
- Place small real bets for learning/testing  

---

📌 **Note:** We're *not* using premium or paid data — all modelling is based on **free, public sources only**.

---

⭐ *Want to follow the project? Star this repo and check back for updates.*
