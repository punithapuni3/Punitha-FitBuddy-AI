# PunithaNidra-FitBuddy-AI - AI Fitness Plan Generator

FitBuddy is an AI-powered fitness application built with FastAPI and Google Gemini AI.

## Features
- Generates personalized 7-day workout plans based on age, weight, goal, intensity
- Provides nutrition & recovery tips using Gemini Flash
- Feedback-based plan update feature
- Admin dashboard to view all users
- SQLite database support

## Tech Stack
- FastAPI, Uvicorn, Jinja2
- SQLAlchemy, SQLite
- Google Gemini 1.5 Pro & Flash

## How to Run
```bash
pip install fastapi uvicorn jinja2 sqlalchemy python-multipart google-generativeai
uvicorn app.main:app --reload
