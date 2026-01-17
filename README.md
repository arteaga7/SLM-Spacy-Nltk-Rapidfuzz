# SLM-Spacy-Nltk-Rapidfuzz
A SLM (Small Language Model) is implemented to search patterns in text.

## 🌎 Repository Structure 
```
SLM-Spacy-Nltk-Rapidfuzz/
├── main.py
├── .gitignore
├── env/                # Virtual enviroment
└── requirements.txt
└── pkg                 # Contains all needed files
    └── __init__.py     # Specifies that folder 'pkg' is a Python package
    └── modules.py      # Contains all functions
    └── settings.py     # Contains all global variables
```

## ✨ Details
**main.py:** 

## 🚀 How to run locally
1. Clone this repository:
```
git clone https://github.com/arteaga7/SLM-Spacy-Nltk-Rapidfuzz.git
```
2. Set virtual environment and install dependencies.

For Windows:
```
python -m venv env
env/Scripts/activate
pip install -r requirements.txt
```
For Linux:
```
python -m venv env && source env/bin/activate && pip install -r requirements.txt
```
3. Run "main.py".

## 📦 Portability
To make this project executable, run (Windows):
```
pyinstaller --onefile --add-data "pkg/.env;." main.py
```