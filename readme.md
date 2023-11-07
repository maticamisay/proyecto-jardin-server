# README - Proyecto Backend Centro Educativo de Infantes

Este proyecto tiene como objetivo desarrollar un backend sencillo y funcional para gestionar un centro educativo de infantes. Está diseñado para ser abordado en sprints por estudiantes de nivel principiante en desarrollo de software, por lo que las tareas se han dividido en bloques pequeños y manejables.

## Objetivo General

Crear un sistema backend que permita registrar estudiantes, profesores, cursos y asistencias en un centro educativo de infantes.

## Tecnologías Sugeridas

- **Lenguaje de Programación:** JavaScript (Node.js)
- **Base de Datos:** MongoDB
- **Framework Web:** Express.js

## Estructura del Proyecto

El proyecto se divide en sprints de dos semanas. Cada sprint incluye tareas específicas que se deben completar para avanzar hacia el producto final.

### Sprint 1: Configuración Inicial y Estructura del Proyecto

#### Objetivos

- Configurar el entorno de desarrollo.
- Comprender las herramientas básicas.
- Establecer la estructura del proyecto.

#### Tareas

1. **Configuración del Entorno de Desarrollo:**

   - Instalar Node.js y npm.
   - Configurar un editor de código (VSCode, Atom, etc.).

2. **Creación del Proyecto:**

   - Inicializar un nuevo proyecto con `npm init`.
   - Crear la estructura de carpetas (por ejemplo, `/models`, `/routes`, `/controllers`).

3. **Control de Versiones:**

   - Iniciar un repositorio de Git.
   - Añadir un archivo `.gitignore` para Node.js.
   - Realizar el primer commit.

4. **Introducción a Node.js y Express.js:**
   - Crear un servidor básico con Express.js.
   - Aprender a manejar rutas y respuestas.

### Sprint 2: Modelado de Datos y Conexión con la Base de Datos

#### Objetivos

- Diseñar modelos de datos simples.
- Establecer conexión con la base de datos.

#### Tareas

1. **Modelado de Datos:**

   - Diseñar esquemas básicos para `Estudiante`, `Profesor`, y `Curso` utilizando Mongoose.

2. **Conexión con MongoDB:**

   - Configurar MongoDB y conectarlo con la aplicación.
   - Aprender operaciones CRUD básicas.

3. **Implementación de Modelos:**
   - Crear archivos de modelo para `Estudiante`, `Profesor`, y `Curso` en Mongoose.
   - Realizar pruebas de creación de datos en la base de datos.

### Sprint 3: Creación de Rutas y Controladores

#### Objetivos

- Implementar la lógica de negocio.
- Aprender sobre middleware y routing en Express.js.

#### Tareas

1. **Rutas de API:**

   - Definir rutas para las operaciones CRUD de `Estudiante`, `Profesor`, y `Curso`.

2. **Controladores:**

   - Crear controladores para manejar la lógica de las rutas.

3. **Middlewares:**
   - Aprender a utilizar middlewares en Express.js para manejar errores y validar datos.

### Sprint 4: Autenticación y Autorización

#### Objetivos

- Añadir seguridad al proyecto.
- Comprender los conceptos de autenticación y autorización.

#### Tareas

1. **Autenticación:**

   - Implementar un sistema de autenticación básico usando JSON Web Tokens (JWT).
   - Crear rutas para el registro y login de usuarios.

2. **Autorización:**

   - Restringir el acceso a ciertas rutas basándose en roles de usuario.

3. **Seguridad Adicional:**
   - Aprender sobre buenas prácticas de seguridad, como almacenamiento seguro de contraseñas y manejo de sesiones.

### Sprint 5: Testing y Documentación

#### Objetivos

- Asegurar la calidad del software.
- Documentar el uso del backend.

#### Tareas

1. **Testing:**

   - Introducción a las pruebas unitarias con frameworks como Jest o Mocha.
   - Escribir pruebas básicas para los modelos y rutas.

2. **Documentación:**
   - Documentar las rutas de la API con Swagger o alguna herramienta similar.
   - Crear un `README.md` detallado para el proyecto.

### Sprint 6: Refinamiento y Despliegue

#### Objetivos

- Pulir el proyecto y prepararlo para un entorno de producción.
- A

prender sobre despliegue y operaciones.

#### Tareas

1. **Refinamiento del Código:**

   - Revisión de código y refactoring.
   - Asegurar que todas las funciones estén correctamente comentadas.

2. **Despliegue:**
   - Aprender sobre opciones de despliegue (Heroku, AWS, etc.).
   - Desplegar la aplicación en un entorno de producción.

## Conclusión

Este proyecto está diseñado para ser una introducción amigable al desarrollo de backend, enfocándose en la práctica y el aprendizaje paso a paso. A medida que los estudiantes progresan, se espera que adquieran habilidades en la configuración de entornos de desarrollo, programación en JavaScript con Node.js y Express, diseño de bases de datos con MongoDB, y prácticas básicas de seguridad y despliegue de aplicaciones web.
