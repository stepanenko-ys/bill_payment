# BILL PAYMENT

## Installation
1. Create virtualenv and activate:
```bash
virtualenv venv_bill --python=python3.8

source venv_bill/bin/activate
```

2. Requirements
```bash
pip install -r requirements.txt
```

3. Database
```bash
python manage.py db init

python manage.py db migrate

python manage.py db upgrade
```

## Run backend
```bash
python manage.py run
```

## Logs
```bash
tail -f logs/log.log 
```

## Frontend (client-side)
In field ``client-side`` open ``index.html`` in browser.


* Project was tested on manOS Big Sur 
* Version 11.0.1
