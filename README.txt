# AdarshNikose.com — Python Flask website

## Run locally on Windows
1. Install Python 3 from https://www.python.org/downloads/
2. Extract this ZIP.
3. Open Command Prompt in this folder.
4. Run:
   pip install -r requirements.txt
   python app.py
5. Open http://127.0.0.1:5000

## Deploy free on Render
1. Create a GitHub account at https://github.com/ and a Render account at https://render.com/.
2. Upload this project folder to a GitHub repository.
3. In Render choose New + > Web Service, connect the repository.
4. Set:
   Build Command: pip install -r requirements.txt
   Start Command: gunicorn app:app
   Instance Type: Free
5. Create the service. Render will provide a public *.onrender.com URL.

Free Render services sleep after 15 minutes without visits and can take about a minute to wake up. See https://render.com/docs/free.

## WhatsApp
The form pre-fills a message to +91 9359295670. The applicant must press Send in WhatsApp; websites cannot silently send a WhatsApp message through an ordinary wa.me link.

## Privacy
The form opens WhatsApp with the submitted details. It does not store applicant data on the website server. Add a privacy notice and collect only details you need.
