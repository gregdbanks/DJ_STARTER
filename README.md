# DJ_STARTER

In this proof of concept I use Django's command line utility `django-admin` to set up a boilerplate Documentation: https://www.djangoproject.com/start/

---
*Caution: Usinga Django development server, for convenience and ease.*

> **Note:** Don’t use this server in anything resembling a production environment. It’s intended only for use while developing.

> **Database:** Using sqlLite since its included with Python, when starting a real project you may want to use a more scalable database such as PostgreSQl

### File Structure:

```
mysite /
    manage.py
    mysite / 
        __init__.py
        settings.py
        urls.py
        asgi.py
        wsgi.py
```

<details>
<summary>More details</summary>

- The outer `mysite/` root directory is a container for your project. 

- `manage.py`: A command-line utility that lets you interact with this Django project in various ways. 

- The inner `mysite/` directory is the actual Python package for your project. 
*Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).*

- `mysite/__init__.py`: An empty file that tells Python that this directory should be considered a Python package. 

- `mysite/settings.py`: Settings/configuration for this Django project. 

- `mysite/urls.py`: The URL declarations for this Django project; a “table of contents” of your Django-powered site. 

- `mysite/asgi.py`: An entry-point for ASGI-compatible web servers to serve your project. 

- `mysite/wsgi.py`: An entry-point for WSGI-compatible web servers to serve your project. 
</details>

---
