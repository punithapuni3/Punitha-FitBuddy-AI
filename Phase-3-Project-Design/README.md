# Phase 3: Project Design

Architecture:
Frontend (Jinja2 HTML) -> FastAPI Routes (routes.py) -> Gemini AI (gemini_generator.py, gemini_flash_generator.py) -> SQLite DB (database.py) -> Result Page

Flow:
1. index.html la user form fill pannuvanga
2. /generate-workout route data vaangi Gemini ku anupum
3. Gemini 7-day plan + tip generate pannum
4. DB la save panni result.html la kaatum
5. Feedback kudutha /submit-feedback route update pannum

Templates: index.html, result.html, all_users.html
