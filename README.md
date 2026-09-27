# AI PPT Analyzer & Scoring System

## Project structure

AI-PPT-Analyzer-Website/
- frontend/
  - index.html
  - style.css
  - script.js
- backend/
  - main.py
  - __init__.py
- uploads/
- reports/
- requirements.txt

## Run

Open a terminal in the project root:

```powershell
pip install -r requirements.txt
uvicorn backend.main:app --reload
```

Open a second terminal:

```powershell
python -m http.server 3000 --directory frontend
```

Open:

http://localhost:3000

Backend health check:

http://127.0.0.1:8000/api/health
