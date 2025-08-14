CV Interactivo y Dinámico de Álvaro Sola Martínez
¡Bienvenido! Este no es un CV estático, es un proyecto vivo que demuestra mis habilidades en DevOps, Cloud, automatización y desarrollo web. Aquí puedes explorar mi trayectoria profesional de forma interactiva, ver un resumen visual de mis habilidades e incluso usar herramientas de IA para analizar mi perfil en profundidad.

✨ Características Principales

CV Interactivo: Una SPA (Single Page Application) construida con HTML, Tailwind CSS y JavaScript para una experiencia de usuario fluida y moderna.

Visualización de Habilidades: Un gráfico de radar (hecho con Chart.js) muestra mis áreas de expertise de un solo vistazo.

Funciones con IA (Google Gemini):

Sugerencias para Entrevistas: Crea preguntas de entrevista técnicas y conductuales basadas en los detalles de cada puesto.

Resúmenes para Managers: Genera resúmenes de alto nivel enfocados en el valor de negocio de mi experiencia.

Análisis de Habilidades: Permite introducir una nueva tecnología y recibir un análisis de cómo encajaría en mi perfil.

Entorno de Desarrollo Contenerizado: Usa Dev Containers para una configuración de desarrollo y pruebas con un solo clic, demostrando buenas prácticas de DevOps.

Despliegue Automatizado: Configurado para un despliegue sencillo en servicios como Render o Netlify.

🚀 Cómo Empezar

Tienes dos opciones para levantar este proyecto. La opción con Dev Containers es la más recomendada.

Opción 1: Dev Containers (Recomendada)
La forma más sencilla y profesional de ejecutar este proyecto.

Requisitos:

Git

Docker Desktop

Visual Studio Code

Extensión Dev Containers para VS Code.

Pasos:

Clona el repositorio.

Abre la carpeta en VS Code.

VS Code detectará el .devcontainer y mostrará una notificación. Haz clic en "Reopen in Container".

Una vez dentro del contenedor, haz clic derecho en index.html y selecciona "Open with Live Server".

Opción 2: Ejecución Local (Sin Docker)
Si prefieres no usar Docker, puedes ejecutar el index.html directamente.

Configura tu API Key de Gemini:

Para que las funciones de IA funcionen, necesitas una clave de API. Consigue una gratis en Google AI Studio.

En la raíz del proyecto, renombra el archivo config.example.js a config.js.

Abre config.js y pega tu clave de API donde se indica.

Lanza el Servidor:

Para evitar problemas de CORS al cargar los archivos .json, necesitas un servidor local. Si tienes VS Code, puedes usar la extensión Live Server.

Haz clic derecho en index.html y selecciona "Open with Live Server".

🔒 Seguridad de la API Key

La clave de la API es un secreto y nunca debe subirse a un repositorio de Git. Para garantizar esto:

El archivo config.js donde guardas tu clave está incluido en el archivo .gitignore.

Esto le dice a Git que ignore ese archivo, por lo que nunca se incluirá en un commit o push, manteniendo tu clave segura y privada.

Este proyecto es un reflejo de mi filosofía de trabajo: aplicar la automatización y las herramientas más modernas para crear soluciones eficientes y de alta calidad. ¡Espero que disfrutes explorándolo!