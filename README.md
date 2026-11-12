# mlops-ml-project - baseline ML reproductible

## Installation
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt

## Entrainement
python scripts/train.py

## Évaluation
python scripts/evaluate.py

## Tests
python -m pytest -q