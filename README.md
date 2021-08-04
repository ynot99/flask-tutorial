# Flask tutorial

I just copy/pasted all code from [flask tutorial documentation](https://flask.palletsprojects.com/en/2.0.x/tutorial/)

## Installation

1. Create new python virtual environment ```python -m venv venv```
2. Activate venv ```. venv/bin/activate```
3. Install python requirements ```pip install -r requirements.txt```
4. Export app variables:
```bash
export FLASK_APP=flaskr \
export FLASK_ENV=development
```
5. Init database ```flask init-db```
6. Run app ```flask run```

Than you can access flask app by url http://127.0.0.1:5000/
