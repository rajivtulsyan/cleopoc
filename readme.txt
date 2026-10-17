# 1. Create virtual environment
python -m venv venv

# 2. Activate virtual environment (PowerShell)
.\venv\Scripts\Activate.ps1

# For CMD instead, use:
# venv\Scripts\activate.bat

# 3. Upgrade pip
python -m pip install --upgrade pip

# 4. Create requirements.txt
New-Item requirements.txt -ItemType File -Force

# 5. Install dependencies listed in requirements.txt
pip install -r requirements.txt

# 6. Run your Python script
python main.py
