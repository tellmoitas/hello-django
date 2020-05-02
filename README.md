# hello-django
Mini projeto django com servidor wsgi gunicorn

## Preparando o ambiente
python3 -m venv myvenv
Source myvenv/bin/activate
pip install -r requirements.txt

## Executando

### em desenvolvimento: 
python hello.py runserver

### em produção:
gunicorn hello --log-file=-

