<img src="https://raw.githubusercontent.com/PradyumnaKrishna/PradyumnaKrishna/master/logo.svg" alt="Logo" title="Logo" align="right" height="50" width="50"/>

# Online Course Django APP

Full Stack online course hosting web application build with Django. Users can enroll into courses read the lessons and take the quiz below. The score also gets evalute in the end.

## Database Structure
I found a database schema that matches this project, It is shown below:

![Database Model](docs/Database%20Model.jpg)


Install Python dependencies

```bash
pip3 install -r requirements.txt
```

**Configure the `settings.py`**: I configured it for the deployment to heroku you can remove the `django_heroku` package from requirements as well as `settings.py` and configure database credentials.

Migrate Django server
```bash
python3 manage.py migrate
```

**Prerequisite**
- Python 3
