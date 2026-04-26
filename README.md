<<<<<<< Updated upstream
# climate-challenge-week0
=======
# Climate Challenge – Week 0

## 📌 Overview

This repository contains the setup for Week 0 of the Climate Challenge. The goal of this task is to establish a clean development environment, version control workflow, and basic Continuous Integration (CI) pipeline before working with any data.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/climate-challenge-week0.git
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
│   └── README.md
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

## ✅ Task Completion Criteria

* Development environment is set up and reproducible
* Version control workflow (branching + commits) is followed
* CI pipeline runs successfully on push to `main`
* Repository structure is organized and ready for further development

---

## 📝 Notes

* The `data/` folder and `.csv` files are ignored via `.gitignore`
* Virtual environments (`venv/`) and cache files are excluded from version control

---

## 👤 Author

Hemen Tewodros
>>>>>>> Stashed changes
