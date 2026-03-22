### Humoria — Joke & Meme Generator:
Humoria is a fun web application that generates clean jokes and memes instantly.
It combines a modern frontend with a backend API to deliver random humor content in real time.

### Live Demo:
https://humoria-6bon.vercel.app/

### Features:
# Random Joke Generator 
# Meme Generator
# Fully deployed(Vercel + Render)

### Tech Stack:
## Frontend:
# React/Vite
# CSS
# Hosted on Vercel

## Backend:
# FastAPI
# Hosted on Render

### Setup
## Backend
- Install dependencies: `pip install -r backend/requirements.txt`
- Set up your `.env` file with `HUMOR_API_KEY=your_key_here`
- Run: `uvicorn Backend.app:app --reload`

## Frontend
Navigate to Frontend/
Run npm install to install React, Vite, etc.
Run npm run dev to start the development server (typically on http://localhost:5173)
Note to ensure the backend is running on port 8000 for the API calls.

## Usage
- Start the backend, then open the frontend in a browser.
