Proyecto con la configuración básica para funcionar sobre Heroku basado en el tutorial oficial https://devcenter.heroku.com/articles/getting-started-with-django.
Sin embargo como estamos usando Python3 es necesario editar el archivo wsgi.py y usar la libreria whitenoise en lugar de dj_static como recomienda la guia, dado que esta última aun no es compatible con Python3.