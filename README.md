# Nour's Birthday Website ❤️

The website interface is in English. The only Arabic text is the personal birthday love letter, as requested.

## Run locally
1. Install Python 3.10+: https://www.python.org/downloads/
2. Extract the ZIP and open a terminal in the project folder.
3. Install packages: `pip install -r requirements.txt`
4. Start: `python app.py`
5. Open http://127.0.0.1:5000

## Publish photos
Photos selected on the page are browser previews only. To show photos to everyone, put them in `static/images/` and add image tags in `templates/index.html`. Publish personal photos only with consent.

## Deploy
Push the project to GitHub, create a Web Service at https://render.com/, set build command to `pip install -r requirements.txt` and start command to `gunicorn app:app`. After deployment, Render gives you a public URL to share.
