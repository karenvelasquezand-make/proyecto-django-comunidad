# Proyecto Django Comunidad (Diseño Rosita)

Proyecto web desarrollado en Django bajo el patrón arquitectónico MVT (Modelo-Vista-Template) con aplicación interna `comunidad`.

## Instrucciones de instalación y ejecución

1. Abrir la carpeta del proyecto en Visual Studio Code.
2. Crear el entorno virtual:
   ```bash
   python -m venv env
   ```
3. Activar el entorno virtual:
   - Windows (PowerShell): `.\env\Scripts\Activate`
   - Windows (CMD): `env\Scriptsctivate.bat`
   - Mac/Linux: `source env/bin/activate`
4. Instalar Django:
   ```bash
   pip install django
   ```
5. Ejecutar las migraciones de la base de datos:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
6. Crear usuario administrador:
   ```bash
   python manage.py createsuperuser
   ```
7. Iniciar el servidor de desarrollo:
   ```bash
   python manage.py runserver
   ```
8. Abrir en el navegador:
   - `http://127.0.0.1:8000/` (Listado de servicios)
   - `http://127.0.0.1:8000/hola/` (Vista Hola Mundo)
   - `http://127.0.0.1:8000/crear/` (Crear servicio)
   - `http://127.0.0.1:8000/admin/` (Panel de Administración)
