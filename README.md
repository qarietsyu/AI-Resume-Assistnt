# Resume ATS Score Checker

Upload a resume (PDF, DOCX or TXT) and get an ATS score, section scores,
missing keywords and concrete improvements. Built with Streamlit and Google Gemini Flash.

## Run locally
```bash
pip install -r requirements.txt
export GEMINI_API_KEY="your-key"      # Windows PowerShell: $env:GEMINI_API_KEY="your-key"
streamlit run app.py
```
Get a free API key at https://aistudio.google.com/apikey

## Deploy on Streamlit Community Cloud
1. Push `app.py`, `requirements.txt` and `README.md` to a GitHub repo.
2. Go to https://share.streamlit.io, click **Create app**, pick the repo, branch `main`, main file `app.py`.
3. Open **Advanced settings > Secrets** and add:
   ```toml
   GEMINI_API_KEY = "your-key"
   ```
4. Click **Deploy**.

Note: the score is an AI estimate, not the output of a real ATS.# AI-Resume-Assistnt
