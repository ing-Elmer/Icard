# Icard
Proyecto del curso de django y react
### Comandos de instalacion



##### Configuración del entorno virtual

`python -m venv ./env/env1`

##### Activar el entorno virtual
`./env/env1/Scripts/activate`

Pagina oficial de PIP para buscar documentacion de librerias
Documentacion Python Install Packege
##### Establecer el Idioma del proyecto
modificar el archivo settings.py
`LANGUAGE_CODE = 'es'`

##### Instalar las dependencias

-Instalar django

`pip install django`

Instalar django rest framework ✅

`pip install djangorestframework`

Documentacion djangorestframework
requiere configurar el archivo settings.py, para agrear rest_framework
Instalar drf-yasg ✅
`pip install -U drf-yasg`

requiere configurar el archivo settings.py, para agrear drf_yasg
requiere configurar el archivo settings.py, para definir rutas estaticas
requiere configurar el archivo urls.py, para agrear drf_yasg
Documentacion drf-yasg 
```pip install setuptools```
Se debe instalar para que funcione correctamente otras dependencias
generar achivos estaticos python manage.py collectstatic
agregar los archivos estaticos a settings.py
```STATIC_URL = '/static/'```
```STATIC_ROOT = './static/'```