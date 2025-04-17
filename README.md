# Python Project Setup on macOS

This project uses a virtual environment and includes common data science packages.

## 📦 Setup

```bash
# 1. Clone this repo or navigate into your project folder
cd code-playground

# 2. Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Start Jupyter Notebook
jupyter notebook
```

## 🔚 Deactivate Environment

```bash
deactivate
```

## 📁 Files

- `requirements.txt`: Common Python packages for data science
- `.gitignore`: Clean Git repo setup for Python + macOS + VS Code
