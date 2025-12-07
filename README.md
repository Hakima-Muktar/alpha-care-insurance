# Alpha Care Insurance Project

## Project Overview
This project analyzes insurance portfolio data to understand risk, profitability, and trends.  
It also implements a **reproducible data pipeline** using **DVC (Data Version Control)**, ensuring all datasets are versioned and auditable.

---

## Task 1 — Exploratory Data Analysis (EDA) & Statistics

### 1. Git & GitHub
- Repository initialized for version control
- Task branches created and merged (`task-1` → `main`)
- Frequent commits with descriptive messages

### 2. Data Understanding
- Dataset: `machine.csv`
- Key columns: TotalPremium, TotalClaims, VehicleType, etc.
- Cleaned and standardized column names

### 3. EDA Performed
- Descriptive statistics and data summarization
- Distribution plots for numerical variables
- Value counts for categorical variables
- Correlation analysis and trends over time and geography
- Outlier detection using boxplots
- Created 3+ visualizations highlighting key insights

---

## Task 2 — Reproducible Data Pipeline with DVC

### 1. DVC Setup
- Installed DVC: `pip install dvc`
- Initialized DVC in project: `dvc init`
- Configured local remote storage:  
  `C:/Users/user/Desktop/Project/alpha-care-insurance/dvc_storage`
- `.dvcignore` created to exclude unnecessary files

### 2. Data Versioning
- Dataset tracked with DVC: `dvc add data/machine.csv`
- `.dvc` files committed to Git
- Data pushed to local DVC remote: `dvc push`

### 3. Benefits
- Ensures reproducibility of analyses
- Supports regulatory compliance in finance/insurance
- Allows branching, updating, and tracking multiple dataset versions

---

## How to Run This Project

1. Clone the repository:
```bash
git clone <your-repo-url>
cd alpha-care-insurance
