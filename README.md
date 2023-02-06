# TODO
## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/todo
$ cd django_todo_app
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv Venv
$ source Venv/bin/activate
```

Then install the dependencies:

```sh
(Venv)$ pip install -r requirements.txt
```
Note the `(Venv)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv`.

Once `pip` has finished downloading the dependencies:
```sh
(Venv)$ cd project
(Venv)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000
