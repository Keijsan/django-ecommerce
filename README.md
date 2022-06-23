# django-ecommerce
<br>
## Installation
* Clone project.
<pre>
git clone https://github.com/Keijsan/django-ecommerce.git
</pre>
* Create virtual environment if you want to. Install requirements.
<pre>
pip install -r requirements.txt
</pre>
* Create a database name 'ecommerce' with XAMPP. You can change it on settings.py. Run these commands in terminal:
<pre>
cd ecommerce
py manage.py createsuperuser
py manage.py migrate
</pre>
* Run project:
<pre>
py manage.py runserver 8888
</pre>
