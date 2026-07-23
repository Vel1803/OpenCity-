# OpenCity — Backend

FastAPI backend for the OpenCity platform.

## Planned Modules
- **Authentication** — Supabase Auth integration for departments and citizens
- **Project APIs** — create/read/update infrastructure projects
- **AI Services** — conflict detection, maintenance prediction, risk analysis (Google Gemini API)
- **Notifications** — alerts to departments and citizens on conflicts, approvals, and closures
- **Asset Management** — digital lifecycle tracking for public assets

## Status
🚧 Not yet implemented. This README will be replaced with setup and run instructions once development begins.

## Planned Setup (once code exists)
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```
