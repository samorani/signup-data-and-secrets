# signup

The office-hours sign-up sheet from *Building Software Systems with AI*, as it is at the end of chapter 12, *Deployment*: accounts, the sheet, a SQLite database, the security review applied, and the Google Cloud setup script. This is the starting point for chapter 13, *Data and Secrets*.

To start chapter 13 from here: click *Use this template* on GitHub, name your repository `signup`, clone it into your home folder, then in `~/signup`:

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
flask --app app run
```

Chapter 13 also expects the sheet to be deployed on Cloud Run as the service `office-hours`. If it is not, run the setup script first, as in chapter 12.
