# [Flask Dashboard Star Admin](https://appseed.us/admin-dashboards/flask-dashboard-staradmin) - WIP

**[Open-Source Admin Dashboard](https://appseed.us/admin-dashboards/open-source)** with Star Admin Design coded in **[Flask](https://palletsprojects.com/p/flask/)**. **Dashboard** features:

- SQLite database, SQLAlchemy ORM
- Session based authentication flow (login, register)
- Static Build via Frozen-Flask
- **MIT License**

<br />

![Flask Dashboard Star Admin - Open-Source Admin Panel](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-staradmin-intro.gif)

<br />

## Build from sources - WIP

```bash
$ # clone the sources
$ git clone https://github.com/app-generator/flask-dashboard-staradmin.git
$ cd flask-dashboard-staradmin
$
$ # install modules using a virtualenv
$ virtualenv --no-site-packages env
$ source env/bin/activate
$
$ # install deps 
$ pip install -r requirements.txt
$
$ # Create SQLite database using the Flask console
$ flask shell
>> from app import db
>> db.create_all()
>> quit() 
$
$ # SQLite database.db should be created in the app folder:
$ # app\database.db
$
$ # Set the FLASK_APP environment variable
$ (Windows) set FLASK_APP=app.py
$ (Unix) export FLASK_APP=app.py
$ (Powershell) $env:FLASK_APP = ".\app.py"
$ 
$ flask app.py
$ # app is running on port 5000
```

<br />

## Want more? Go PRO!

<br />

| [Flask Dashboard Material](https://appseed.us/admin-dashboards/flask-dashboard-material-pro) | [Flask Dashboard Argon](https://appseed.us/admin-dashboards/flask-dashboard-argon-pro) | [Flask Dashboard Black](https://appseed.us/admin-dashboards/flask-dashboard-black-pro) |
| --- | --- | --- |
| [![Flask Dashboard Material PRO](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-material-pro-intro.gif)](https://appseed.us/admin-dashboards/flask-dashboard-material-pro)  | [![Flask Dashboard Argon PRO](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-argon-pro-intro.gif)](https://appseed.us/admin-dashboards/flask-dashboard-argon-pro) | [![Flask Dashboard Black PRO](https://raw.githubusercontent.com/app-generator/static/master/products/flask-dashboard-black-pro-intro.gif)](https://appseed.us/admin-dashboards/flask-dashboard-black-pro)

<br />

## Resources

- [Flask Dashboard Star Admin](https://appseed.us/admin-dashboards/flask-dashboard-staradmin) - Official Product Page
- [Flask Dashboard Star Admin](https://flask-dashboard-staradmin.appseed.us/) - Live DEMO
- [Flask Framework](https://palletsprojects.com/p/flask/) - official website
 
<br />
 
---
[Flask Dashboard Star Admin](https://appseed.us/admin-dashboards/flask-dashboard-staradmin) provided by **AppSeed**
