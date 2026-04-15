Vetsoft
Aplicación web para veterinarias utilizada en la cursada 2024 de Ingeniería y Calidad de Software (UTN-FRLP).

Estado de este repositorio
Este repositorio es un fork con fines de portfolio profesional.
Proyecto original: https://github.com/JuaniLezcano/vetsoft

Mi contribución en el proyecto original
Participé como contributor en mejoras funcionales y de calidad, principalmente en:

Validaciones de dominio y formularios (por ejemplo, teléfono y fecha de nacimiento).
Corrección de errores de visualización de mensajes y templates.
Mejora de cobertura de pruebas (unitarias, integración y e2e).
Ajustes de calidad de código (reglas estáticas y documentación).
Evidencia pública de contribuciones

PRs creados por mí (6):
https://github.com/search?q=repo%3AJuaniLezcano%2Fvetsoft+is%3Apr+author%3AValentinMilocco&type=pullrequests

PRs donde participé (26):
https://github.com/search?q=repo%3AJuaniLezcano%2Fvetsoft+is%3Apr+involves%3AValentinMilocco&type=pullrequests

Commits en el repo:
https://github.com/JuaniLezcano/vetsoft/commits?author=ValentinMilocco

Convención de commits
Formato:
[type]: mensaje-commit

Tipos:
fix: corrección de bugs
feat: nueva funcionalidad
refactor: refactorización de código
Instrucciones para dockerizar la aplicación
Aclaración: se debe tener Docker instalado previamente.

Construir la imagen:
docker build -t vetsoft .

Desplegar el contenedor:
docker run -d -p 8000:80 vetsoft

Abrir en navegador:
http://localhost:8000

Dependencias y ejecución local
Dependencias principales:

Python 3.12.3-slim
Django 5.0.4
SQLite
Playwright
Ruff
Pasos:

Instalar dependencias:
pip install -r requirements.txt

Inicializar base de datos:
python manage.py migrate

Iniciar aplicación:
python manage.py runserver

Integrantes del proyecto original
Peres, Benjamin
Peres, Valentin
Eguren, Rafael
Lezcano, Juan Ignacio
Milocco, Valentin
Nota de transparencia
Este fork no busca reemplazar ni atribuir autoría total del proyecto original.
Se mantiene como registro de contribución técnica para portfolio.
