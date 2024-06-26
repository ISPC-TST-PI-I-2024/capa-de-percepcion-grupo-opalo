
# Proyecto Final - Capa de Percepcion

- **Institución**: Instituto Superior Politécnico Córdoba (ISPC)
- **Curso**: Proyecto Integrador I
- **Docente**: Cristian Gonzalo Vera
- **Equipo de Desarrollo Opalo**:
  - Luciano Lujan | GitHub: https://github.com/lucianoilujan
  - Joaquin Garzón | GitHub: https://github.com/Joacogarzonn
  - Durigutti, Vittorio | GitHub: https://github.com/vittoriodurigutti
  - Joaquin Zalazar | GitHub: https://github.com/breaakerr
  - Lisandro Juncos | GitHub: https://github.com/Lisandro-05
  - Nahuel Velez | GitHub: https://github.com/ISPC-TST-PI-I-2024/ISPC_PI_Lucas_Nahuel_Velez 
  - Jose Marquez | GitHub: https://github.com/ISPC-TST-PI-I-2024/josemarquez.git
  - Tomas Repossi | GitHub:  https://github.com/TomasRepossi

------------------------------------------

## Sobre el Proyecto

Este repositorio está dedicado a la Capa de Almacenamiento del proyecto IoT. Incluye todos los componentes desarrollados y documentación generada por los estudiantes conforme avanzan en la implementación de esta capa del proyecto.

El objetivo principal de este proyecto es crear un sistema IoT que permita monitorear los niveles de glucosa en sangre de un paciente en tiempo real. La arquitectura del sistema incluye un dispositivo IoT que recogerá los datos de glucemia y los enviará a una base de datos para su almacenamiento y análisis. Actualmente, la aplicación Flask se ejecuta localmente y proporciona acceso a una base de datos estática. Esta base de datos será actualizada en tiempo real una vez que el dispositivo IoT prototipo esté en funcionamiento.

### Estructura del Repositorio

- **A requisitos**: Contiene documentos de requisitos proporcionados por el docente.
- **B investigacion**: Investigaciones realizadas por los estudiantes.
- **C prototipo**: Implementaciones específicas de la capa de almacenamiento.
  - **Componentes Principales**
    - app.py: El archivo principal de la aplicación Flask, que define las rutas y la lógica del servidor web.
    - static/ y templates/: Directorios utilizados por Flask para servir archivos estáticos y plantillas HTML.
    - Dockerfile: Archivo utilizado para construir una imagen de Docker que contiene la aplicación Flask.
    - docker-compose.yml: Archivo de configuración para Docker Compose, que facilita la configuración y ejecución de servicios de Docker.
    - requirements.txt: Archivo que lista las dependencias de Python necesarias para ejecutar la aplicación Flask.
    - Proyecto PI.sql: Archivo que contiene las instrucciones SQL para la configuración de la base de datos.
- **D presentacion**: Incluye grabaciones y bitácoras de las reuniones de Scrum, así como las presentaciones de progreso.
- **zassets**: Contiene recursos gráficos como imágenes y otros archivos necesarios para la documentación.

------------------------------------------

**OBJETIVOS**

### Semana 1: (08/04 - 14/04)
- Avance del Proyecto Final: Introducción al IoT, formación de equipos.
- Sprint 1: Como integrantes del equipo, queremos familiarizarnos con el entorno de desarrollo y herramientas de colaboración para comenzar eficazmente nuestro proyecto IoT.

### Semana 2: (15/04 - 21/04)
- Avance del Proyecto Final: Fundamentos de programación para IoT. Introducción a los controladores (ESP32).
- Sprint 2: Como equipo, queremos comprender los fundamentos de programación específicos para IoT y empezar a experimentar con módulos de desarrollo para establecer las bases de nuestro prototipo.

### Semana 3: (22/04 - 28/04)
- Avance del Proyecto Final: Sensores en IoT: tipos, selección y aplicación.
- Sprint 3: Como equipo, buscamos diseñar y desarrollar un módulo inicial para nuestro controlador que pueda leer
datos de varios sensores y realizar una comunicación básica con actuadores,

### Semana 4: (29/04 - 05/05)
- Avance del Proyecto Final: Taller práctico sobre sensores y actuadores.
- Sprint 4: Como equipo  buscamos finalizar el desarrollo de nuestro controlador, implementando completamente
los protocolos de comunicación y asegurando una integración eficiente y
efectiva con sensores y actuadores,
