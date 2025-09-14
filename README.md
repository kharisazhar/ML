# Machine Learning Environment Setup

This repository provides a simple setup for creating a Python virtual environment and installing the basic libraries for machine learning experiments.

---

## 🚀 Installation

Clone the repository (or create your project folder), then set up a virtual environment:

```bash
# Create virtual environment
python3 -m venv venv

# Activate environment
# macOS / Linux
source venv/bin/activate
# Windows
venv\Scripts\activate

python -m pip install --upgrade pip setuptools wheel

pip install jupyter pandas numpy scikit-learn matplotlib

jupyter lab

