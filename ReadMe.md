Puppies, Django and Vue Integration
===================================


[Link to Medium Article by @rodrigomaniotto](https://medium.com/@rodrigosmaniotto/integrating-django-and-vuejs-with-vue-cli-3-and-webpack-loader-145c3b98501a)


Postgres DB
-----------
Using [Postgres Docker stack](https://gist.github.com/adagio/e1a7b6edbc0f2c21e32e0cec30a07baa)


Basic Commands
--------------
Two terminals...


**1st Terminal**
```
cd frontend
npm install
npm run serve
```

**2nd Terminal** 

with virtualenv activated:

```
pip install -r requirements.txt
cd puppies
python manage.py createsuperuser
python manage.py migrate
python manage.py runserver
```
