#Running Project

python -m venv .venv
source env/Scripts/activate
pip install fastapi
pip install uvicorn
uvicorn main:app --reload
