# 🎓 GATE CS MTech College Finder

> An interactive, score-based college finder for GATE CS aspirants — covering all IITs, NITs & IIITs across India.

![HTML](https://img.shields.io/badge/Built%20With-HTML%2FCSS%2FJS-blue?style=flat-square)
![GATE](https://img.shields.io/badge/Exam-GATE%20CS-orange?style=flat-square)
![Colleges](https://img.shields.io/badge/Colleges-65%2B-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

---

## 📌 What is this?

Every GATE CS student faces the same question after results: **"Which college can I get with my score?"**

This tool answers that — instantly. Drag a slider to your GATE score and see real-time admission chances for **65+ colleges** across India, filtered by institute type and region.

**No login. No signup. No backend. Just open the HTML file.**

---

## ✨ Features

- 🎚️ **Live score slider** — drag from 400 to 1000, chances update instantly
- 🏛️ **65+ colleges** — all 24 IITs, all 31 NITs, 15 top IIITs
- 📊 **Admission chance bars** — Very High / High / Good / Possible / Low
- 🗂️ **Filter by type** — IIT, NIT, IIIT, or all
- 🗺️ **Filter by region** — North, South, East, West, Central, North East
- 🔍 **Search by name** — find any college instantly
- 📈 **Sortable columns** — sort by name, score, tier, region
- 🌙 **Dark theme** — easy on the eyes during late-night prep sessions

---

## 📸 Preview

> Open `gate_cs_mtech_colleges.html` in any browser — works fully offline.

---

## 🚀 How to Use

1. **Clone or download** this repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/gate-cs-mtech-college-finder.git
   ```
2. Open `gate_cs_mtech_colleges.html` in any browser (Chrome, Firefox, Edge, Safari)
3. Drag the **GATE Score slider** to your score
4. Use the **filters** to narrow down by institute type or region
5. Check the **Admission Chance** column to plan your CCMT/COAP choices

> ✅ No installation needed. No internet required after download.

---

## 📊 Data Source & Accuracy

| Institute Type | Counselling Portal | Data Used |
|---|---|---|
| NITs & IIITs | CCMT (ccmt.admissions.nic.in) | 2025 Last-Round Closing Score, General Category |
| IITs & IISc | COAP | 2025 Round 1 Shortlisting Score, General Category |

**Important notes:**
- IIT scores are COAP **shortlisting** scores — a written test/interview is still required after
- NIT scores are CCMT **last-round closing** scores — actual cutoffs vary round by round
- Cutoffs shift ±20–50 points year to year depending on exam difficulty and competition
- Spot Round cutoffs can be 50–100 points lower than Round 1

---

## 🎯 Score → Chance Guide

| Score vs Cutoff | Chance Label | Meaning |
|---|---|---|
| Score ≥ Cutoff + 50 | 🟢 Very High (95%) | Safe bet, apply confidently |
| Score ≥ Cutoff + 20 | 🟢 High (80%) | Strong chance |
| Score ≥ Cutoff | 🔵 Good (60%) | Right at cutoff, good position |
| Score within 30 below | 🟡 Possible (35%) | Try in later rounds / spot round |
| Score 30–60 below | 🟠 Low (15%) | Worth adding as backup |
| Score > 60 below | 🔴 Very Low (5%) | Unlikely even in spot rounds |

---

## 🏗️ Built With

- Plain **HTML5**, **CSS3**, **Vanilla JavaScript** — zero dependencies
- No frameworks, no build tools, no npm — just one file
- Works on mobile browsers too

---

## 📁 Repository Structure

```
gate-cs-mtech-college-finder/
│
├── gate_cs_mtech_colleges.html   # Main app — open this in browser
└── README.md                     # You're reading this
```

---

## 🗺️ Colleges Covered

| Category | Count | Examples |
|---|---|---|
| IITs + IISc | 24 | IIT Bombay, IIT Delhi, IIT Roorkee... |
| NITs | 31 | NIT Trichy, NIT Jalandhar, NIT Hamirpur... |
| IIITs | 15 | IIIT Hyderabad, IIIT Allahabad, IIIT Delhi... |

---

## 🙋 Who is this for?

- Students who appeared for **GATE CS / DA** and want MTech admission
- Anyone planning CCMT counselling choices
- Students comparing **North India vs South India NITs**
- Anyone confused about which tier of college their score qualifies for

---

## 🤝 Contributing

Found outdated cutoffs? Know a college that should be added? Contributions are welcome!

1. Fork this repo
2. Update the `colleges` array in the HTML file with new data
3. Submit a Pull Request with the source of the updated cutoff data

Please mention the data source (CCMT official site, year, round) in your PR.

---

## 📄 License

MIT License — free to use, share, and modify. If you find it helpful, a ⭐ on the repo goes a long way!

---

## 🔗 Useful Links

- [CCMT Official Site](https://ccmt.admissions.nic.in) — NIT/IIIT counselling
- [COAP Portal](https://coap.iitd.ac.in) — IIT counselling
- [GATE Official](https://gate2026.iitg.ac.in) — GATE exam info

---

*Data based on 2025 CCMT/COAP official archives. Updated annually. Not affiliated with any institution or exam authority.*
