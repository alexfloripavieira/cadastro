Primeiro:

'docker start neoway-postgres 2>/dev/null || docker run --name neoway-postgres -p 5432:5432 -e POSTGRES_PASSWORD='postgres' -d postgres:10-alpine'

Segundo:
'python -m venv venv'

Terceiro
Na raiz do projeto
'source venv/bin/activate'
'pip install -r requeriments.txt'
'python manage.py migrate'

Quarto
'python manage.py runserver'