# Setting Up a New Wagtail Site

```
git pull
python3 -m venv env
. env/bin/activate
pip install wagtail
wagtail start techblog
cd techblog
pip install wheel
pip install techblog/requirements.txt
python manage.py migrate
python manage.py createsuperuser
```

```
python manage.py runserver
git add .
git commit -am "Initialised site"
git push origin master
```
