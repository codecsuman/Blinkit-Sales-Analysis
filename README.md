<div align="center">

<img src="blinkit_logo.png" alt="Blinkit Logo" width="120" style="border-radius: 20px;" />

# 🛒 Blinkit Sales Analysis

**A comprehensive data analysis project on Blinkit's sales, inventory, and outlet performance**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

[📊 Live Dashboard](http://127.0.0.1:5501/blinkit_dashboard.html) · [📁 Repository](https://github.com/codecsuman/Blinkit-Sales-Analysis) · [🐛 Report Bug](https://github.com/codecsuman/Blinkit-Sales-Analysis/issues)

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Live Demo](#-live-demo)
- [Dataset Overview](#-dataset-overview)
- [Key Insights](#-key-insights)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Analysis Workflow](#-analysis-workflow)
- [Dashboard Preview](#-dashboard-preview)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 🧠 About the Project

This project performs a full-cycle data analysis on **Blinkit** (India's quick-commerce platform), covering product sales, outlet performance, inventory distribution, and geographic trends.

The goal is to extract actionable business insights from raw transactional data — helping understand which item categories drive the most revenue, how different outlet types compare, and where growth opportunities exist.

> 💡 Blinkit (formerly Grofers) is one of India's leading instant delivery platforms. This analysis simulates a real-world business intelligence scenario.

---

## 🌐 Live Demo

🔗 **Interactive Dashboard:** [http://127.0.0.1:5501/blinkit_dashboard.html](http://127.0.0.1:5501/blinkit_dashboard.html)

The dashboard features:
- KPI summary cards (Total Revenue, Records, Avg Rating)
- Animated horizontal bar charts for item-wise sales
- Donut chart for fat content distribution
- Outlet type & location tier performance
- Outlet establishment timeline (1998–2022)

---

## 📂 Dataset Overview

| Column | Description |
|--------|-------------|
| `Item Fat Content` | Low Fat / Regular |
| `Item Identifier` | Unique product code |
| `Item Type` | Product category (e.g., Dairy, Snack Foods) |
| `Outlet Establishment Year` | Year outlet was set up |
| `Outlet Identifier` | Unique outlet code |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 city |
| `Outlet Size` | Small / Medium / High |
| `Outlet Type` | Grocery Store / Supermarket Type 1/2/3 |
| `Item Visibility` | Display prominence in store |
| `Item Weight` | Weight of the item (kg) |
| `Sales` | Total item sales value (₹) |
| `Rating` | Customer rating (1–5) |

**Dataset Size:** 8,523 rows × 12 columns

---

## 📊 Key Insights

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | ₹12,01,681 |
| 📦 Total Records | 8,523 |
| ⭐ Average Rating | 3.97 / 5 |
| 🏆 Top Category | Fruits & Vegetables (₹1.78L) |
| 🏬 Best Outlet Type | Supermarket Type1 (65.5% revenue share) |
| 📍 Top Performing Tier | Tier 3 (₹4.72L) |
| 🥗 Most Common Fat Type | Low Fat (64.7% of products) |

### 🏅 Top 5 Item Categories by Sales

```
1. Fruits & Vegetables   ████████████████  ₹1,78,124
2. Snack Foods           ███████████████   ₹1,75,434
3. Household             ████████████      ₹1,35,977
4. Frozen Foods          ██████████        ₹1,18,559
5. Dairy                 █████████         ₹1,01,276
```

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.10+** | Core programming language |
| **Pandas** | Data cleaning, manipulation & aggregation |
| **Matplotlib / Seaborn** | Static data visualizations |
| **SQLite** | Inventory database querying |
| **Jupyter Notebook** | Interactive analysis environment |
| **HTML / CSS / JavaScript** | Interactive web dashboard |

---

## 📁 Project Structure

```
Blinkit-Sales-Analysis/
│
├── 📓 index.ipynb               # Main Jupyter Notebook (full analysis)
├── 📊 blinkit_data.csv          # Primary dataset (8,523 records)
├── 🗄️  inventory.db             # SQLite inventory database
├── 🌐 blinkit_dashboard.html    # Interactive HTML dashboard
├── 🖼️  blinkit_logo.png         # Project logo
└── 📄 README.md                 # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

```bash
Python 3.10+
Jupyter Notebook or JupyterLab
```

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/codecsuman/Blinkit-Sales-Analysis.git
cd Blinkit-Sales-Analysis
```

2. **Install required libraries**

```bash
pip install pandas matplotlib seaborn jupyter
```

3. **Launch Jupyter Notebook**

```bash
jupyter notebook index.ipynb
```

4. **Open the dashboard**

Open `blinkit_dashboard.html` in any modern browser — no server needed.

---

## 🔍 Analysis Workflow

```
📥 Data Collection
    └── Load CSV + Query SQLite DB

🧹 Data Cleaning
    ├── Handle missing values (.dropna())
    ├── Fix inconsistencies (e.g., "LF" → "Low Fat")
    └── Verify unique values (.nunique())

⚙️ Data Processing
    ├── Group by Item Type, Outlet Type, Location Tier
    └── Aggregate Sales, Count, Average Rating

📈 Visualization
    ├── Bar charts (Item-wise & Outlet-wise Sales)
    ├── Donut chart (Fat Content Distribution)
    ├── Timeline chart (Outlet Establishments)
    └── Tier comparison blocks

💡 Insights & Reporting
    └── Export to HTML Dashboard
```

---

## 🖥️ Dashboard Preview

> Interactive dashboard built with pure HTML, CSS & JavaScript — no frameworks needed.

**Features:**
- 🎨 Blinkit brand theme (Yellow + Green on Dark)
- ✨ CSS-animated bar fills and chart reveals
- 📱 Responsive grid layout
- 🔢 Real data from the CSV (no mock values)

---

## 🔮 Future Improvements

- [ ] 📊 **Power BI Dashboard** — richer interactive reporting
- [ ] 🤖 **Predictive ML Model** — forecast sales by category/outlet
- [ ] 📬 **Automated Reporting** — scheduled email/PDF reports
- [ ] 🔄 **Real-time Data Pipeline** — live database integration
- [ ] 🗺️ **Geo-map Visualization** — Tier-wise city-level heatmap

---

## 👤 Author

**Suman** — [@codecsuman](https://github.com/codecsuman)

> 📬 Found this useful? Give it a ⭐ on [GitHub](https://github.com/codecsuman/Blinkit-Sales-Analysis) — it really helps!

---

<div align="center">

Made with ❤️ and Python · Blinkit Sales Analysis Project

</div>
