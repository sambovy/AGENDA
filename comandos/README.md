INICIAR O PROJETO DJANGO

...

python3 -m venv venv
source venv/bin/activate
pip install django
django-admin startproject project .

...

CONFIGURAR O GIT

...

git config --global user.name 'sambovy'
git config --global user.email 'sambovy@gmail.com'
git config --global init.defaultBranch main
git init
git add .
git commit -m 'Mensagem'
git remote add origin https://github.com/sambovy/Agenda.git

git push orign main -u