# FitBuddy - AI Fitness Plan Generator using Gemini Models

Wellness-focused activity planner with Gemini AI, weekly plans, daily tips, progress checklist and notes.

Run:
python -m venv fitbuddy-env
fitbuddy-env\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload

Open http://127.0.0.1:8000

Add GEMINI_API_KEY to .env for Gemini responses. Without a key, demo fallback responses work.

Safety: no calorie restriction or weight-loss targets. Focus on healthy movement, recovery, hydration and gradual activity.
