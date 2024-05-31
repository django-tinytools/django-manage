# django-manage

A simple shell script for django which lets you run *manage.py* in your project
root with imported *python virtual environment*.

The virtual environment **needs** to be in the *venv* or *python-venv*
directory in the project-root-path or in its parent directory if the 
environment variable *DJANGO_VENV*, which points the virtual environment to be
used by django, is not set.

The script automatically changes the path to the location of the script file
and runs the root file from there.

To use the script copy the *manage* file to the root directory of your django
project. You don't need to copy the *LICENSE* file to your project, hence the
manage file contains the copyright notice.

```
cp /path/to/django-manage /path/to/django-project
```

You can run the script with all of the parameters accepted by manage.py

```
/path/to/django-project/manage makemigrations
```


If you edit the *manage* file, keep the copyright notice in the file and add
your onw copyright for the changes if you publish it.
