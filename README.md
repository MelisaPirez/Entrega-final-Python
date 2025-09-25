Proyecto Final Python – Blog con Django
Es una aplicación web desarrollada con Django que permite gestionar usuarios, publicaciones de blog y un sistema de mensajería interna.

Funcionalidades principales

Gestión de usuarios

Registro de nuevos usuarios.
Login y logout.
Perfil de usuario con imagen y biografía.
Blog

Creación de publicaciones (CRUD básico).
Título, subtítulo, cuerpo, autor, fecha y opcionalmente imagen.
Listado de publicaciones en la página principal.
Detalle de cada publicación.
Mensajería interna

Enviar mensajes entre usuarios registrados.
Bandeja de entrada (Inbox).
Historial de mensajes recibidos.
Tecnologías utilizadas

Python 3.10+
Django 5.0.6
SQLite3 (base de datos por defecto)
Bootstrap 5 (para estilos y diseño responsivo)
Usuario creado

Nombre de usuario: Invitado Contraseña: Prueba2025

Estructura del proyecto

blogproject/ │ ├── blog/ # App de publicaciones ├── accounts/ # App de usuarios y perfiles ├── messages_app/ # App de mensajería interna ├── templates/ # Archivos HTML con Bootstrap │ ├── base.html │ ├── blog/ │ ├── accounts/ │ └── messages_app/ ├── db.sqlite3 # Base de datos ├── manage.py # Comando principal de Django └── blogproject/ # Configuración principal (settings, urls)

Tests

Cada app incluye un archivo básico de tests para verificar:

Creación de usuario y perfil.

Creación de post.

Envío de mensajes.

Futuras mejoras

Paginación de publicaciones.

Edición y borrado de posts desde el frontend.

Editar perfil con formulario dinámico.

Notificaciones en tiempo real para mensajes nuevos.

LINK AL VIDEO DE LA WEB FUNCIONANDO: https://drive.google.com/file/d/1dYDpGK6KeYj7a0X7r6ieogcSvWWEOzjW/view?usp=drive_link
