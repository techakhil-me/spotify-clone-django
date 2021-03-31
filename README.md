# spotify-clone-django
python Django clone music app

check it out here https://youttify.pythonanywhere.com/demo/



## Setup

The first thing to do is to clone the repository:

```sh
$ git clone https://github.com/techakhil-me/spotify-clone-django
$ cd spotify-clone-django
```

Create a virtual environment to install dependencies in and activate it:

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Then install the dependencies:

```sh
(env)$ pip install -r requirements.txt
```
Note the `(env)` in front of the prompt. This indicates that this terminal
session operates in a virtual environment set up by `virtualenv2`.

Once `pip` has finished downloading the dependencies:
```sh
(env)$ cd spotify-clone-django
(env)$ python manage.py runserver
```
And navigate to `http://127.0.0.1:8000/demo`.
