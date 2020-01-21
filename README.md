# Google Sheets Starter
a base for google sheets api access

Getting Started:
```bash
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

Or, starting without existing `requirements.txt`
```bash
python3 -m venv env
source env/bin/activate
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
pip freeze > requirements.txt
```

Finally:
```bash
(env)$ python main.py
```
