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
* [About the Project](#-about-the-project)
* [Dataset Overview](#-dataset-overview)
* [Key Insights](#-key-insights)
* [Tech Stack](#-tech-stack)
* [Project Structure](#-project-structure)
* [Getting Started](#-getting-started)
* [Analysis Workflow](#-analysis-workflow)
* [Author](#-author)

---

## 🧠 About the Project

This project performs a full-cycle data analysis on **Blinkit** (India's quick-commerce platform), covering product sales, outlet performance, inventory distribution, and geographic trends.

The goal is to extract actionable business insights from raw transactional data — helping understand which item categories drive the most revenue, how different outlet types compare, and where growth opportunities exist.

> 💡 **Context:** Blinkit (formerly Grofers) is one of India's leading instant delivery platforms. This analysis simulates a real-world business intelligence scenario using Python and SQL.

---

## 📂 Dataset Overview

The analysis is based on a dataset of **8,523 transactions** across 12 key features:

| Column | Description |
|:---|:---|
| `Item Fat Content` | Low Fat / Regular |
| `Item Type` | Product category (e.g., Dairy, Snack Foods) |
| `Outlet Size` | Small / Medium / High |
| `Outlet Type` | Grocery Store / Supermarket Type 1, 2, 3 |
| `Outlet Location` | Tier 1 / Tier 2 / Tier 3 city |
| `Sales` | Total item sales value (₹) |
| `Rating` | Customer rating (1–5) |

---

## 📊 Key Insights

### 📈 Performance Metrics
* **Total Revenue:** ₹1.20M
* **Average Rating:** 3.97 ★
* **Top Outlet:** Supermarket Type 1 (65.5% Revenue Share)
* **Top Region:** Tier 3 Cities (₹472K Revenue)

### 🏅 Top 5 Categories by Sales
| Rank | Category | Revenue |
|:---:|:---|:---|
| 1 | 🍎 Fruits & Vegetables | **₹1,78,124** |
| 2 | 🥨 Snack Foods | **₹1,75,434** |
| 3 | 🏠 Household | **₹1,35,977** |
| 4 | ❄️ Frozen Foods | **₹1,18,559** |
| 5 | 🥛 Dairy | **₹1,01,276** |

---

## 🛠 Tech Stack

| Domain | Tools |
|:---|:---|
| **Language** | Python 3.10+ |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Database** | SQLite3 |
| **Environment** | Jupyter Notebook |
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |

---

## 📁 Project Structure

```bash
Blinkit-Sales-Analysis/
├── 📓 index.ipynb            # Data Cleaning & Analysis Logic
├── 📊 blinkit_data.csv        # Raw Dataset
├── 🗄️ inventory.db           # SQLite Database for Inventory
├── 🌐 blinkit_dashboard.html  # Interactive Web Dashboard
├── 🖼️ blinkit_logo.png       # Assets
└── 📄 README.md              # Documentation


---

## 🚀 Getting Started

### 1️⃣ Clone Repository
```bash
git clone https://github.com/codecsuman/Blinkit-Sales-Analysis.git
cd Blinkit-Sales-Analysis

2️⃣ Install Libraries

pip install pandas matplotlib seaborn jupyter

3️⃣ Run Notebook

jupyter notebook index.ipynb

4️⃣ Open Dashboard

Open this file in browser:

blinkit_dashboard.html

🔍 Workflow

📥 Data Collection
🧹 Data Cleaning
⚙️ Processing & Aggregation
📈 Visualization
💡 Insights Generation

🖥️ Dashboard Features
📊 KPI Cards
📉 Interactive Charts
🍩 Donut Visualization
📍 Tier-based Insights
🎨 Modern UI
📱 Responsive Layout
👤 Author

Suman
🔗 https://github.com/codecsuman

<div align="center">

⭐ If you like this project, give it a star!

Made with ❤️ using Python & Data Analytics

</div> ```
