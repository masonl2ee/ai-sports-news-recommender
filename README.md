# AI Sports News Recommender

> 🚧 This project is currently in its early development stage!  
> Features are actively being developed in the `test` and `feature/*` branches.  
> The `main` branch contains only the initial project structure for now.

An AI-powered sports news recommendation platform that delivers personalized news articles based on users' interests in teams, players, and more.

This project is built with a full-stack architecture:
- **Frontend**: Developed using [Next.js](https://nextjs.org/)
- **Backend**: Built with [FastAPI](https://fastapi.tiangolo.com/)
- **Recommender System**: AI-based engine using Python and PyTorch
- **Databases**: MongoDB and/or PostgreSQL for storing user data, news, and logs
---

## Project Structure

```
ai-sports-news-recommender/
│
├── frontend/                      # Next.js frontend
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
├── backend/                       # Backend server (FastAPI)
│   ├── api/                       # API routes (e.g., /api/news, /api/user)
│   ├── models/                    # Database models (MongoDB, PostgreSQL schemas)
│   ├── controllers/               # Business logic controllers
│   ├── utils/                     # Utility/helper functions
│   ├── main.py                    # Server entry point
│   └── requirements.txt
│
├── recommender/                   # AI recommendation system
│   ├── model/                     # Recommendation model logic (PyTorch)
│   ├── preprocess/                # News preprocessing, tokenization, etc.
│   ├── api/                       # Recommendation API (FastAPI)
│   ├── datasets/                  # Sample news data or crawled dataset
│   └── inference.py               # Main file to run inference
│
├── README.md
└── .gitignore
```
---

## Features

- Personalized sports news recommendations
- _(To be added soon)_

---

## Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | Next.js, Tailwind CSS |
| Backend | FastAPI, Python |
| Recommender | PyTorch, Sentence Transformers |
| Database | MongoDB, PostgreSQL |
| API Protocol | REST (JSON) |

---

## Getting Started

### 1. Frontend

```bash
cd frontend
npm install
npm run dev
```

### 2. Backend
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3. Recommender
```bash
cd recommender
pip install -r requirements.txt
python inference.py
```
---
## To Do
- _(To be added soon)_
