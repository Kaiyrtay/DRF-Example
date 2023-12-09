**1.Clone the Repo**

```sh
git clone https://github.com/Kaiyrtay/DRF-Example.git
```

**2.Setup pipenv & Install Requirements**

```sh
pip install pipenv
pipenv install -r requirements.txt
pipenv shell
```

**3.Migrate Database**

```sh
python manage.py makemigrations
python manage.py migrate
```

**4.Start Server**

```sh
python manage.py runserver
```
