# Mobile-Application
  Tell you suitable quotes according to your mood 

## Installation
We will use the kivy library to build a mobile app in Python. Below you will find the instructions on how to install kivy.

### Important note:
Do not simply use pip install kivy to install kivy because even though the command may run without errors, you may get a [CRITICAL] [App] Unable to get a Window, abort error later on when you run a kivy app. Instead, see the instructions below in order to install kivy correctly.

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install kivy.

## Mac or Linux users
Kivy currently only works with Python 3.7 or earlier on Mac and Linux. You might want to install Python 3.7 first, and then install kivy for your Python 3.7 with:

```bash
python3.7 -m pip install kivy
```
Tip: If you just installed Python 3.7, make sure to configure your IDE to use Python 3.7, otherwise your IDE may be still using the other version of Python.

### Python 3.7 or earlier
If you are using Python 3.7 or earlier, run all three following commands one by one:
```bash
pip install kivy
pip install kivy.deps.glew
pip install docutils pygments pypiwin32 kivy.deps.sdl2
```
### Python 3.8
If you are using Python 3.8, run all four following commands one by one:
```bash
pip install --upgrade pip setuptools wheel

pip install https://github.com/kivy/kivy/archive/master.zip

pip install kivy.deps.glew

pip install docutils pygments pypiwin32 kivy.deps.sdl2
```
