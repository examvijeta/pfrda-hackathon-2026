# 📊 NPS FutureCalc
### Interactive Retirement Corpus & Pension Forecasting Tool

> **PFRDA Innovate4NPS Hackathon 2026** | Problem Statement 3  
> Organized by PFRDA + SIIC IIT Kanpur

---

## 👥 Team
| Name | Role |
|------|------|
| Aman Kumar | Team Lead & Full Stack Developer |
| Rausheen Hasan | UI/UX Designer, Python Developer & Research Analyst |

---

## 📌 Problem Statement
Most NPS subscribers don't know how much to contribute to meet retirement goals. Existing calculators are static, single-scenario, and have no reverse planning — making retirement planning confusing and overwhelming for average Indians.

---

## 💡 Our Solution
**NPS FutureCalc** is a real-time, interactive retirement planning tool that transforms complex pension math into simple visual experiences — helping every Indian subscriber understand exactly how much to save and what they will get at retirement.

---

## ✨ Key Features
- 🧮 Retirement Corpus Estimator — real-time projection based on age, income, contribution
- 💰 Monthly Pension Estimator — 40% annuity + 60% lump sum breakdown
- 🎯 Reverse Goal Planner — enter desired pension → get required monthly contribution
- 📊 3-Scenario Comparison — conservative vs moderate vs aggressive side-by-side
- 📉 Inflation-Adjusted Projections — today's rupees + future value both shown
- 🎚️ Dynamic Sliders — real-time recalculation on every move, no submit needed
- 🚦 Traffic Light Indicator — Green/Yellow/Red on-track status at a glance
- 📄 Downloadable PDF Report — personalized retirement projection to share

---

## 🛠️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React.js + Recharts + Chart.js |
| Mobile | Flutter |
| Calculation Engine | Python FastAPI (actuarial math) |
| Visualizations | Recharts + D3.js |
| PDF Export | React-PDF / jsPDF |
| Multilingual | i18n — 8 languages |
| Deployment | Docker + APIX Platform |

---

## 🧮 Calculation Engine
```
Future Value    → FV = P × [(1+r)^n - 1] / r
Annuity         → IRDA standard rates (6-7%)
Employer Match  → 10% of basic salary (Tier I)
Tax Benefit     → Section 80CCD(1B) — Rs 50,000 extra
Inflation Adj.  → Real value in today's purchasing power
```

---

## 📈 Visualization Dashboard
```
Area Chart   → Corpus growth over time (animated)
Donut Chart  → Own contribution vs returns vs employer
Bar Chart    → Year-wise breakdown
Milestones   → 10yr, 20yr, retirement corpus cards
Traffic Light → On track / Needs attention / Critical
```

---

## 👤 User Personas
| Persona | Use Case |
|---------|----------|
| 23-yr first jobber | How much should I start with? |
| 35-yr self-employed | How much will I have at 60? |
| 50-yr late starter | Can I still get decent pension? |
| HR Manager | Explain NPS benefit to employees |

---

## 🎯 Expected Impact
- 🧠 85%+ users report better contribution clarity after use
- 📈 50%+ first-time users begin NPS enrollment within 7 days
- 💹 Existing subscribers increase contribution by 15-25%
- ✅ 99%+ calculation accuracy vs PFRDA official calculator
- ⏱️ Average session time 8+ minutes due to scenario exploration

---

## 📁 Project Status
> 🚧 Currently in Idea Stage — Prototype to be built on APIX Platform post shortlisting

---

## 📬 Contact
- Aman Kumar — Team Lead
- Rausheen Hasan — UI/UX & Research

*Submitted for PFRDA Innovate4NPS Hackathon 2026*  
*#NPSZaruriHai | #Innovate4NPS | #PFRDA2026*
