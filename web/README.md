# Prepare data

Use the tools in `../patcher` to populate game data

# Automated tests

```
pytest tests
```

Note that the tests are very limited

# Testing locally

## Method 1: Use dev_appserver.py from Google Cloud SDK

```
dev_appserver.py app.yaml
```

## Method 2: Use a virtual environment

```
virtualenv venv
venv/bin/pip install -r requirements.txt
venv/bin/python local_web.py
```
