# data_analytics-

## ANALYSIS DONE by fuck

# 📦 Dependency Management Guide (pip-tools)

To ensure all team members use the exact same package versions and prevent environment conflicts, this project uses **`pip-tools`** instead of standard `pip install`. 

We split dependencies into two files:
1. `requirements.in` – **The Logical File:** Contains only the top-level libraries we explicitly want (e.g., `pandas`, `seaborn`).
2. `requirements.txt` – **The Locked File:** Automatically generated. Contains the exact version pins and dependencies of dependencies.

---

## 🚀 Setup & Workflow

### 1. Initial Environment Setup
Run these commands in your project root terminal to activate your virtual environment and install the deployment tools:

```bash
# Activate your virtual environment (Windows)
.venv\Scripts\activate

# Activate your virtual environment (Mac/Linux)
source .venv/bin/activate

# Upgrade base pip and install pip-tools
pip install --upgrade pip
pip install pip-tools

