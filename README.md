<div align="center">

<img src="blinkit_logo.png" alt="Blinkit Logo" width="120" style="border-radius: 20px;" />

# 🛒 Blinkit Sales Analysis

**A comprehensive data analysis project on Blinkit's sales, inventory, and outlet performance**

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

[📊 View Dashboard](https://codecsuman.github.io/Blinkit-Sales-Analysis/blinkit_dashboard.html) · [📁 Repository](https://github.com/codecsuman/Blinkit-Sales-Analysis) · [🐛 Report Bug](https://github.com/codecsuman/Blinkit-Sales-Analysis/issues)

</div>

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Dataset Overview](#-dataset-overview)
- [Key Insights](#-key-insights)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Analysis Workflow](#-analysis-workflow)
- [Dashboard Features](#-dashboard-features)
- [Author](#-author)

---

## 🧠 About the Project

This project performs a **full-cycle data analysis** on [Blinkit](https://blinkit.com) — India's leading quick-commerce platform — covering product sales, outlet performance, inventory distribution, and geographic trends.

The goal is to extract actionable business insights from raw transactional data, helping understand:

- Which **item categories** drive the most revenue
- How different **outlet types** compare in performance
- Where **growth opportunities** exist across city tiers

> 💡 **Context:** Blinkit (formerly Grofers) delivers groceries and essentials in under 10 minutes across India. This analysis simulates a real-world **Business Intelligence** scenario using Python and SQL.

---

## 📂 Dataset Overview

The analysis is based on **8,523 transactions** across 12 key features:

| Column | Description |
|:---|:---|
| `Item Fat Content` | Low Fat / Regular |
| `Item Type` | Product category (e.g., Dairy, Snack Foods) |
| `Item Visibility` | Display prominence score (0–1) |
| `Item Weight` | Weight of the product (grams) |
| `Outlet Size` | Small / Medium / High |
| `Outlet Type` | Grocery Store / Supermarket Type 1, 2, 3 |
| `Outlet Location` | Tier 1 / Tier 2 / Tier 3 city |
| `Outlet Year` | Year the outlet was established |
| `Sales` | Total item sales value (₹) |
| `Rating` | Customer rating (1–5) |

---

## 📊 Key Insights

### 📈 Top-Line Performance Metrics

| Metric | Value |
|:---|:---|
| 💰 Total Revenue | ₹1,201,681 |
| ⭐ Average Rating | 3.97 / 5.00 |
| 🏪 Best Outlet Type | Supermarket Type 1 (65.5% share) |
| 📍 Best Region | Tier 3 Cities (₹472K revenue) |
| 📦 Total Transactions | 8,523 |

### 🏅 Top 5 Categories by Revenue

| Rank | Category | Revenue |
|:---:|:---|---:|
| 1 | 🍎 Fruits & Vegetables | ₹1,78,124 |
| 2 | 🥨 Snack Foods | ₹1,75,434 |
| 3 | 🏠 Household | ₹1,35,977 |
| 4 | ❄️ Frozen Foods | ₹1,18,559 |
| 5 | 🥛 Dairy | ₹1,01,276 |

### 🔍 Notable Findings

- **Tier 3 cities outperform** Tier 1 and Tier 2 in total revenue — suggesting strong market penetration in smaller cities.
- **Low-fat products** marginally outsell regular items, reflecting growing health consciousness.
- **Supermarket Type 1** dominates with nearly two-thirds of all revenue, but **Grocery Stores** show higher per-item ratings.
- Outlets established between **2000–2010** consistently outperform newer ones, indicating brand loyalty effects.

---

## 🛠 Tech Stack

| Domain | Tools |
|:---|:---|
| **Language** | Python 3.10+ |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Database** | SQLite3 |
| **Environment** | Jupyter Notebook |
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |

---

## 📁 Project Structure

```
Blinkit-Sales-Analysis/
│
├── 📓 index.ipynb              # Main analysis notebook (cleaning, EDA, SQL queries)
├── 📊 blinkit_data.csv         # Raw dataset (8,523 rows × 12 columns)
├── 🗄️  inventory.db            # SQLite database for inventory queries
├── 🌐 blinkit_dashboard.html   # Interactive web dashboard
├── 🖼️  blinkit_logo.png        # Project assets
└── 📄 README.md                # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10 or higher
- pip package manager

### 1. Clone the Repository

```bash
git clone https://github.com/codecsuman/Blinkit-Sales-Analysis.git
cd Blinkit-Sales-Analysis
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch the Notebook

```bash
jupyter notebook index.ipynb
```

### 4. Open the Dashboard

Open `blinkit_dashboard.html` directly in any modern web browser — no server required.

---

## 🔍 Analysis Workflow

```
📥 Data Collection
      ↓
🧹 Data Cleaning & Validation
      ↓
🗄️  SQLite Integration & Querying
      ↓
⚙️  Aggregation & Feature Engineering
      ↓
📈 Visualization & EDA
      ↓
💡 Insight Generation & Reporting
```

---

## 🖥 Dashboard Features

The interactive HTML dashboard includes:

- **📊 KPI Cards** — Live revenue, rating, and transaction metrics
- **📉 Bar & Line Charts** — Category and outlet performance over time
- **🍩 Donut Chart** — Revenue share by outlet type
- **📍 Tier-based Heatmap** — Geographic sales distribution
- **🎨 Modern UI** — Clean design with Blinkit brand colors
- **📱 Responsive Layout** — Works on desktop and mobile

---

## 👤 Author

**Suman**  
GitHub: [@codecsuman](https://github.com/codecsuman)

---

<div align="center">

⭐ **Found this useful? Give the repo a star!**

Made with ❤️ using Python & Data Analytics

</div>
