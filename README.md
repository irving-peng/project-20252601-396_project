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
```

## Frontend Setup
```bash
cd frontend
npm install
npm start
```
---

# Project Structure

## Backend Structure
```
backend/
├── app.py
├── config.py
├── database.py
├── requirements.txt
├── seed_data.py
├── models/
│   ├── menu_item.py
│   ├── order.py
│   ├── order_item.py
│   └── payment.py
├── services/
│   ├── menu_service.py
│   ├── order_service.py
│   └── payment_service.py
└── routes/
    ├── main.py
    ├── menu_routes.py
    ├── order_routes.py
    └── payment_routes.py
```
## Frontend Structure
```
frontend/
├── src/
│   ├── components/
│   ├── services/
│   │   └── api.ts
│   ├── types/
│   ├── utils/
│   └── App.tsx
```
---

## Quick Start

1. Start the backend:
```bash
cd backend
pip install -r requirements.txt
python seed_data.py
python app.py
```

2. Start the frontend:
```bash
cd frontend
npm install
npm start
```

3. Visit<br>
Frontend UI: http://localhost:3000<br>
Backend API: http://localhost:5001






