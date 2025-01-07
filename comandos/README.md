Iniciar projeto python


python3 -m venv venv
. venv/bin/activate
pip3 install django
django-admin startproject project .

configurar o gitt

git init
git add .
git commit -m 'Mensagem'
git remote add origin URL_DO_GIT

Migrando a base de dados do Django

python3 manage.py makemigrations
python3 manage.py migrate


Criando e modificando a senha de um super usuário Django

python3 manage.py createsuperuser
python3 manage.py changepassword USERNAME