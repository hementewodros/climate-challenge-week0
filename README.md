![CI](https://github.com/hementewodros/climate-challenge-week0/actions/workflows/ci.yml/badge.svg)
![Python](https://img.shields.io/badge/python-3.10-blue)
# Climate Challenge – Week 0

## 📌 Overview

This repository contains the setup for Week 0 of the Climate Challenge. The goal of this task is to establish a clean development environment, version control workflow, and basic Continuous Integration (CI) pipeline before working with any data.
---
## 🐍 Environment

- Python version: 3.10
---
## 🔄 Development Workflow

- Feature branches are used for each task (e.g., `setup-task`, `eda-ethiopia`)
- Changes are merged into `main` via Pull Requests
- Commit messages follow Conventional Commits (e.g., `feat:`, `chore:`, `ci:`)
---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/hementewodros/climate-challenge-week0.git
cd climate-challenge-week0
```

---

### 2. Create a Virtual Environment

#### Using `venv` (recommended)

```bash
python -m venv venv
```

#### Activate the environment

* **Mac/Linux:**

```bash
source venv/bin/activate
```

* **Windows:**

```bash
venv\Scripts\activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📂 Project Structure

```
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── .gitignore
├── README.md
├── requirements.txt
├── src/
├── notebooks/
│   ├── __init__.py
│   ├── README.md
│   ├── ethiopia_eda.ipynb
│   ├── kenya_eda.ipynb
│   ├── tanzania_eda.ipynb
│   ├── nigeria_eda.ipynb
│   └── sudan_eda.ipynb
├── tests/
│   └── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
```

---

## 🔄 Git Workflow

* A feature branch `setup-task` was created for this setup.
* Changes were committed using **Conventional Commits**.
* The branch was merged into `main` via a Pull Request.

---

## ⚙️ Continuous Integration (CI)

This project uses **GitHub Actions** for basic CI.

### What it does:

* Runs on every push to the `main` branch
* Installs dependencies from `requirements.txt`
* Verifies Python setup

### Workflow file:

```
.github/workflows/ci.yml
```

---
## 🤝 Contributing

- Create a new branch for each task (e.g., `eda-country`, `compare-countries`)
- Follow Conventional Commit messages
- Open a Pull Request before merging to `main`
---

## ✅ Task Completion Criteria

* Development environment is set up and reproducible
* Version control workflow (branching + commits) is followed
* CI pipeline runs successfully on push to `main`
* Repository structure is organized and ready for further development
---
## References & Learning Sources

To better understand climate data analysis and preprocessing, the following resources were used:

- NASA POWER Data Documentation: https://power.larc.nasa.gov/
- Pandas Time Series Guide: https://pandas.pydata.org/docs/user_guide/timeseries.html
- Z-score Outlier Detection: https://en.wikipedia.org/wiki/Standard_score
- Matplotlib Documentation: https://matplotlib.org/stable/
- Seaborn Heatmap Guide: https://seaborn.pydata.org/generated/seaborn.heatmap.html
---

## 📝 Notes

* The `data/` folder and `.csv` files are ignored via `.gitignore`
* Virtual environments (`venv/`) and cache files are excluded from version control

---

## 👤 Author
Hemen Tewodros
