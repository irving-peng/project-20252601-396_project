# Project: Fast Food Ordering System (Option 1)

## Contributors
- **Xuyang Li**
- **Irving Peng**
- **Jenny Zhou**

---

# Project Overview

A full-stack Fast Food Ordering System implemented with:

- **Flask Backend** (REST API, SQLite DB)
- **React TypeScript Frontend** (customer ordering interface)
- Three-layer architecture: Presentation → Application → Domain

---

# Dependencies

## Backend
- Python 3.10+
- Flask
- SQLAlchemy
- SQLite (default)
- Other dependencies in `backend/requirements.txt`

## Frontend
- Node.js 18+
- React + TypeScript
- Other dependencies in `frontend/package.json`

# Build Instructions

## Backend Setup
```bash
cd backend
pip install -r requirements.txt
python seed_data.py
python app.py
