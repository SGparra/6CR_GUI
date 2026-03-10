# 6CR_GUI

Aplicación web desarrollada con Shiny for Python para revisar documentos PDF y registrar errores o comentarios asociados a cada entrada en una base de datos.

La aplicación permite a distintos revisores iniciar sesión, visualizar archivos PDF asignados en busqueda de formas 6CR y registrar observaciones directamente desde una interfaz web interactiva.

Características

- Sistema de inicio de sesión para revisores

- Selección de PDFs según estado de revisión

- Apertura directa del PDF desde la aplicación

- Registro de comentarios o errores frecuentes

- Creación de nuevas entradas (formas) para un PDF

- Guardado de cambios en la base de datos

- Navegación entre documentos

project/
│
├── app.py
├── modules.py
├── PDF/
│   └── (pdfs temporales servidos por la app)
│
├── database/
│   └── database.db
│
└── README.md

Requisitos:

Instalar Python 3.9+.
Dependencias principales:
Shiny for Python

Instalación:

ejecutar `pip install -r requirements`

Ejecución

`shiny run app.py`

Luego abrir en el navegador:

http://localhost:8000

`shiny run --host 0.0.0.0 --port 8000 app.py`

En el caso de que se desee lanzar la aplicación para una red de computadores. Luego de introducir el comando, abrir en el navegador web:

http://<ip del computador>:8000



