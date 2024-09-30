Descripción
Este repositorio alberga toda la información relacionada con el desarrollo y gestión de la Progressive Web App (PWA) del proyecto Trina 1 10B - TI, desarrollado por Alvaro, Josue, y Jaime. Aquí se gestiona tanto el código del proyecto como las tareas definidas en Asana, lo que permite una integración entre la codificación y el seguimiento del progreso.

Objetivos
Alojar y revisar el código del proyecto: Mantener el código constantemente revisado y actualizado para evitar errores de codificación.
Gestión de tareas e issues: Facilitar la comunicación de issues a través de Asana y gestionar nuevas tareas para el desarrollo del proyecto.
Entregas rápidas y continuas: Proporcionar entregas frecuentes de valor mediante revisiones constantes del proyecto.
Metodología
Se eligió la metodología Extreme Programming (XP) debido a la naturaleza cambiante de los requisitos y la necesidad de entregas rápidas. XP promueve la retroalimentación continua y el mejoramiento constante mediante prácticas clave que optimizan el ciclo de vida del desarrollo.

Entre las prácticas principales de XP se incluyen:

Iteraciones frecuentes y cortas para desarrollar y entregar funcionalidades de forma ágil.
Refactorización continua para mejorar la calidad del código sin afectar la funcionalidad.
Feedback constante para asegurar que el equipo de desarrollo y el cliente estén alineados.
Herramienta de Control de Versiones y Flujo de Trabajo
Se seleccionó GitHub como la herramienta principal de control de versiones. El flujo de trabajo utilizado es de integración continua (CI), lo que asegura que el código que se sube a la rama principal sea estable y libre de errores, gracias a pruebas automatizadas que se ejecutan antes de integrar cualquier cambio.

En este flujo de trabajo:

Los desarrolladores trabajan en ramas individuales que corresponden a cada nueva funcionalidad o corrección.
Se ejecutan pruebas automáticas antes de realizar cualquier integración en la rama principal.
La rama principal contiene el código más estable y actualizado, accesible para todos los miembros del equipo.
Estrategia de Versionamiento y Gestión de Ramas
El proyecto implementa una estrategia de versionado continuo (Rolling Release), donde se actualiza el software continuamente, garantizando siempre una versión reciente y funcional.

La estructura de ramas es la siguiente:

Main o Master: Es la rama principal que contiene la versión estable del proyecto.
Ramas de características o features: Cada nueva funcionalidad se desarrolla en una rama independiente, que luego se integra a la rama principal tras pasar las pruebas.
Clonación del Repositorio
Para comenzar a trabajar con el proyecto de la PWA, es necesario clonar el repositorio desde GitHub.

Clonar el repositorio: Esto permite descargar una copia local del código fuente del proyecto.
Instalar las dependencias: Este paso es fundamental para garantizar que el entorno de desarrollo tenga todas las bibliotecas necesarias.
Ejecutar el proyecto: Permite levantar el entorno de desarrollo local y ver la PWA en el navegador.
Instalación de Dependencias
Una vez clonado el repositorio, se debe realizar la instalación de las dependencias especificadas en el archivo de configuración del proyecto. Esto garantiza que todos los módulos necesarios para el funcionamiento de la PWA estén disponibles.

Ejecución del Proyecto
Para ejecutar el proyecto en el entorno de desarrollo local, se necesita iniciar el servidor de desarrollo para visualizar la aplicación en el navegador.

Además, cuando el proyecto esté listo para ser desplegado, se pueden generar los archivos de la versión optimizada para producción.

Pruebas y Emulación
Es esencial utilizar herramientas como el Simulador móvil y las herramientas de desarrollo de Google Chrome para verificar que la PWA sea completamente responsiva y funcione correctamente en dispositivos móviles. Estas herramientas permiten emular diferentes tamaños de pantalla y dispositivos, garantizando que la experiencia del usuario sea óptima en todos los entornos.

Además, se recomienda la automatización de pruebas en el flujo de integración continua para identificar posibles errores y mantener la calidad del código.