
# Setup

1) Change into the project directory

```
cd "hand-gesture-recognition-mediapipe#"
```

2) (Optional) Create and activate a Python virtual environment (PowerShell)

```
Requires Python 3.12.12
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

3) (Recommended) Recreate the environment using conda from `environment.yml` (if provided)

```
conda env create -f environment.yml -n ASL
conda activate ASL
```

4) Run command to start

```
python .\app.py
```

Notes:
- Run conda commands in Anaconda Prompt if `conda` is not initialized in PowerShell.
