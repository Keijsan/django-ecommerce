# django-ecommerce
Create virtual environment if you want to. Install requirements (upgrade pip might solve some installation errors).
pip install -r requirements.txt
Create a database name 'ecommerce'. You can change it on settings.py. Run these commands in terminal:
cd ecommerce
py manage.py createsuperuser
py manage.py migrate
Run project:
py manage.py runserver 8888
