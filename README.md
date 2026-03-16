# 🚗 BMW M Sales Analytics Dashboard

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1aff,100:4d4dff&height=180&section=header&text=BMW%20M%20Sales%20Dashboard&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=Interactive%20Power%20BI%20Sales%20Analytics%20%7C%202019–2023&descAlignY=58&descSize=16&animation=fadeIn" width="100%"/>

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](/)
[![Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com)
[![Period](https://img.shields.io/badge/Period-2019%20–%202023-1a1aff?style=for-the-badge&logo=googlecalendar&logoColor=white)](/)
[![Revenue](https://img.shields.io/badge/Total%20Revenue-1%2C128.1M%20€-success?style=for-the-badge)](/)

</div>

---

## 📌 Project Overview

An interactive **BMW M Sales Analytics Dashboard** built with **Power BI**, providing deep insights into global BMW vehicle sales from **January 2019 to December 2023**. The dashboard enables business stakeholders to explore revenue trends, top-selling models, sales channels, and country-level performance — all in one place.

> 📦 **Dataset source:** [Kaggle](https://www.kaggle.com) — BMW Sales Dataset

---

## 📊 Dashboard Pages

### Page 1 — Global Overview
> *All Cars · Global Sales Summary*

![Dashboard Overview](./screenshots/dashboard1.png)

**What it shows:**
- 📈 **Global Sales bar + line chart** (Revenue vs Revenue PY) — yearly from 2019 to 2023
- 🏆 **Top Selling Models carousel** — BMW Z4 (666), BMW 8 Series (641), BMW M4 (620), BMW i8 (615)
- 🌍 **Country table** — Qty sold, Revenue & Revenue Sparkline per country (Spain, China, Japan, Thailand…)
- 🍩 **Qty sold by Channel** donut chart — Wholesale 44% · Dealership 33% · Online 22%
- 📊 **Qty sold by Year** bar chart — current vs prior year comparison
- 💰 **Most Expensive Models** panel — BMW M8 ($79.1K), BMW iX3 ($78.2K), BMW X4 ($77.7K), BMW M4 ($77.6K)
- 🔢 **KPI card** — Total Revenue **1,128.1M€** vs PY 904.5M€

---

### Page 2 — Model Detail View
> *Drill-through per BMW model*

![Dashboard Model Detail](./screenshots/dashboard2.png)

**What it shows:**
- 🚗 **Large model image** with model name (e.g. BMW M3)
- 💵 **Average Price** — $72.5K
- 📋 **Year-by-year breakdown table** — Qty Sold, Revenue & Revenue Sparkline per year
- 📦 **Total** — 525 units · 38.1M€ revenue
- 🔄 **All models carousel** at the bottom for quick navigation between models

---

## 🔑 Key KPIs

| Metric | Value |
|:---|:---:|
| 💰 Total Revenue (2019–2023) | **1,128.1 M€** |
| 📅 Prior Year Revenue | 904.5 M€ |
| 🚗 Total Units Sold | **15,002** |
| 📈 Revenue Growth | **+24.7% ▲** |
| 🏆 Top Selling Model | **BMW Z4 — 666 units** |
| 💎 Most Expensive Model | **BMW M8 — $79.1K** |
| 🌍 Top Country by Revenue Growth | **Thailand +20.9%** |

---

## 🧩 Features

- ✅ **Time intelligence** — Year / Month / Weekday toggle
- ✅ **Drill-through** — click any model to open its detail page
- ✅ **Sparklines** — mini revenue trends per country and per model
- ✅ **Channel breakdown** — Wholesale vs Dealership vs Online
- ✅ **YoY comparison** — Revenue vs Revenue Prior Year
- ✅ **Fully interactive** — slicers, filters, cross-highlighting
- ✅ **Responsive layout** — clean, corporate BMW M aesthetic

---

## 🗂️ Repository Structure

```
bmw-sales-dashboard/
├── BMW_Sales_Dashboard.pbix     # Power BI file
├── dataset/
│   └── bmw_sales.csv            # Raw dataset (from Kaggle)
├── screenshots/
│   ├── dashboard1.png           # Global overview page
│   └── dashboard2.png           # Model detail page
└── README.md
```

---

## 🚀 How to Use

```bash
# 1. Clone the repository
git clone https://github.com/AbdellahKoulla/bmw-sales-dashboard.git

# 2. Open the Power BI file
# → Requires Power BI Desktop (free)
# → Download: https://powerbi.microsoft.com/desktop

# 3. If needed, relink the dataset
# → Transform Data > Data Source Settings > update path to dataset/bmw_sales.csv
```

---

## 📦 Dataset Info

| Field | Detail |
|:---|:---|
| **Source** | Kaggle — BMW Sales Dataset |
| **Period** | January 2019 – December 2023 |
| **Records** | ~15,000+ transactions |
| **Key columns** | Model, Year, Month, Country, Channel, Qty Sold, Revenue, Price |
| **Countries** | Spain, China, Japan, Thailand + more |
| **Sales Channels** | Wholesale · Dealership · Online |

---

## 🛠️ Tools Used

<div align="center">

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power%20Query-1a1aff?style=for-the-badge&logo=microsoft&logoColor=white"/>
<img src="https://img.shields.io/badge/CSV%20Dataset-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"/>
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>

</div>

---

## 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/abdellah.koulla1@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdellah.koulla1@gmail.com)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/abdellahkoulla-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdellahkoulla)
&nbsp;
[![Portfolio](https://img.shields.io/badge/Portfolio-00F5FF?style=for-the-badge&logo=githubpages&logoColor=black)](https://AbdellahKoulla.github.io)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4d4dff,100:1a1aff&height=100&section=footer&animation=fadeIn" width="100%"/>

⭐ **If you found this project useful, give it a star!**

*Built with ❤️ by [Abdellah Koulla](https://linkedin.com/in/abdellahkoulla)*

</div>
