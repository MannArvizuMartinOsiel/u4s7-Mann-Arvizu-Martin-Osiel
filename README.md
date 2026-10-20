# Unidad 4 - Semana 7: Pulido funcional, UX y simulacro de defensa

## Datos del alumno

- **Alumno:** Martín Osiel Mann Arvizu
- **Grupo:** 4-1 DSM
- **Carrera:** Ingeniería en Sistemas
- **Universidad:** Universidad Tecnológica de Hermosillo (UTH)
- **Materia:** Aplicaciones Web

## Descripción del proyecto

Aplicación web desarrollada con Django para administrar servicios mediante un sistema CRUD (Crear, Leer, Actualizar y Eliminar), incorporando autenticación de usuarios y mejoras en la experiencia de usuario.

## Funcionalidades

- Registro de usuarios.
- Inicio y cierre de sesión.
- Creación de servicios.
- Consulta del listado de servicios.
- Edición y eliminación de servicios.
- Búsqueda de servicios por título.
- Paginación de resultados.
- Protección de vistas mediante autenticación.
- Separación de los servicios por usuario para evitar que se mezclen los registros.

## Tecnologías utilizadas

- Python
- Django
- HTML
- CSS
- Base de datos configurada en el proyecto

## Instalación y ejecución

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/MannArvizuMartinOsiel/u4s7-Mann-Arvizu-Martin-Osiel.git
   ```

2. Entrar a la carpeta del proyecto:

   ```bash
   cd u4s7-Mann-Arvizu-Martin-Osiel
   ```

3. Instalar Django y las dependencias necesarias del proyecto:

   ```bash
   pip install django
   ```

4. Aplicar las migraciones:

   ```bash
   python manage.py migrate
   ```

5. Iniciar el servidor local:

   ```bash
   python manage.py runserver
   ```

6. Abrir en el navegador:

   `http://127.0.0.1:8000/`

## Objetivo

Mejorar una aplicación web existente mediante la incorporación de búsqueda, paginación, autenticación y controles de acceso, reforzando la seguridad y la facilidad de uso.

## Conclusión

La práctica permite aplicar conceptos de desarrollo web con Django, gestionar sesiones de usuario y mejorar la presentación y organización de los registros mediante búsqueda y paginación.
