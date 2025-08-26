# Text/Markdown → PowerPoint Web App

This app converts bulk text, Markdown, or prose into a fully formatted PowerPoint presentation.  
Supports optional `.pptx`/`.potx` template upload to match your branding.

## 🚀 Run locally
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload