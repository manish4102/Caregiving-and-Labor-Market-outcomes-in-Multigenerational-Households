# 🧓👨‍👩‍👧‍👦 Caregiving & Labor Market Outcomes in Multigenerational Households (ATUS)

📌 **WIL Data Summit Project**  
👤 **Author:** Manish Champalal Parmar  
📊 **Data:** American Time Use Survey (ATUS) via IPUMS  
🧾 **Method:** Survey-weighted analysis (WT06 + strata + cluster)

---

## ✨ Project Overview

This project studies how **multigenerational households** differ from the overall population and whether **caregiving responsibilities** relate to **labor market attachment**.

Key focus areas:
- ✅ Economic and demographic differences: **multigenerational vs full population**
- ✅ Within multigenerational households: **caregivers vs non-caregivers**
- ✅ Whether **higher caregiving intensity** reduces weekly work hours

The analysis uses **survey-weighted estimates** to reflect national patterns (WT06, STRATA, CLUSTER). :contentReference[oaicite:1]{index=1}

---

## ❓ Research Questions

1. **Do multigenerational households differ economically from the overall population?**  
2. **Within multigenerational households, do caregivers exhibit weaker labor market attachment?**  
3. **Does higher caregiving intensity reduce weekly work hours?** :contentReference[oaicite:2]{index=2}

---

## 🧠 Data & Methodology

### 📦 Data Source
- **American Time Use Survey (ATUS)**
- **159,937** person-level observations
- Survey design adjustments using:
  - weights: **WT06**
  - strata: **STRATA**
  - PSU/cluster: **CLUSTER** :contentReference[oaicite:3]{index=3}

### 🏷️ Key Constructed Variables
- **Multigenerational household (proxy):** kids in household + adult-care proxy (based on non-child household care time)
- **Caregiving minutes/day:**
  - childcare minutes
  - adult-care proxy minutes
  - total care minutes
- **Care intensity (weekly):**
  - Part-time: **< 20 hrs/week**
  - Mid-range: **20–39 hrs/week**
  - Full-time: **≥ 40 hrs/week** :contentReference[oaicite:4]{index=4}

---

## 🔎 Snapshot of Findings (From Presentation)

### 📌 Sample + Scale
- Total observations: **159,937**
- Multigenerational households (sample): **21,876**
- Multigenerational households are about **13% of the weighted population**
- Weighted estimate corresponds to **~15 million multigenerational households** nationally :contentReference[oaicite:5]{index=5}

### ⏱️ Caregiving Time (Multigenerational Caregivers)
- Childcare: **107.5 min/day**
- Adult care: **48.3 min/day**
- Total care: **155.8 min/day (~2.6 hours/day)** :contentReference[oaicite:6]{index=6}

### 💼 Labor Market Outcomes
- Average weekly work hours:
  - Full population: **41.81**
  - Multigenerational: **32.1** :contentReference[oaicite:7]{index=7}

### 🧩 Structural Differences
- Average household size:
  - Full population: **2.85**
  - Multigenerational: **4.26**
- Average number of children:
  - Full population: **0.62**
  - Multigenerational: **2.03** :contentReference[oaicite:8]{index=8}

### 🌎 Ethnic Distribution (Multigenerational Households)
- Native Hawaiian & Pacific Islander: **19.2%**
- Hispanic (any race): **17.1%**
- Non-Hispanic AIAN: **15.0%**
- Non-Hispanic Asian: **14.8%**
- Non-Hispanic Black: **11.5%**
- Non-Hispanic White: **11.0%** :contentReference[oaicite:9]{index=9}

---

## 🧪 Hypotheses & Results

- **H1:** Multigenerational households differ economically  
  ✅ **Supported**

- **H2:** Caregivers have weaker labor market attachment  
  ❌ **Not supported**

- **H3:** Higher caregiving intensity reduces work hours  
  ❌ **Not supported** :contentReference[oaicite:10]{index=10}

---

## 📈 Visuals & Outputs Included

This repo includes exploratory analysis and plots such as:
- Distribution of caregiving time among multigenerational caregivers
- Caregiving minutes vs weekly work hours
- Employment and income composition comparisons
- Care intensity vs work hours
- Ethnicity breakdown: counts + shares + household structure comparisons

---

