## Task 2

### Instructions to run the application:
> Install modules via `VENV` (for MAC and Linux) 

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

> for Windows (Bash):

```bash
$ python -m venv venv
$ venv\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

> Note: To use the app, please access the registration page and create a new user. After authentication, the app will unlock the private pages.

<br />

### Screenshots of Features:
![Lab1_running_SS1](https://github.com/user-attachments/assets/438c61e2-ec5d-4bf3-af25-9f72eaacb111)

![Lab1_running_SS2](https://github.com/user-attachments/assets/de17a559-7553-47a9-8e6d-e0237893e5b7)

![Lab1_running_SS3](https://github.com/user-attachments/assets/464087d1-ef6a-42fd-b1ce-bb4e20ce1569)




