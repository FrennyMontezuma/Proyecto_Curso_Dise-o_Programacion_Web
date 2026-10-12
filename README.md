# Rikimaka - Sistema Integral de Gestión Humana

##  Descripción del Proyecto
Rikimaka es una solución web interactiva diseñada para optimizar la administración de proyectos, la solicitud de permisos, la configuración de periodos de vacaciones y el reporte de labores diarias dentro de una organización[cite: 3]. El sistema busca fortalecer la trazabilidad del trabajo, la planificación estratégica del personal y la eficiencia en el uso de recursos mediante una interfaz intuitiva dividida por roles clave (Administrador / Talento Humano / Personal de TI y Colaboradores)[cite: 3].

##  Integrantes del Equipo y Roles
* **Frenny Montezuma Castillo** 
* **Geisel Tatiana Araya Garita** 
* **Jeiferson Elías Rivera Walker** 

##  Alcance del Sistema
El proyecto contempla el desarrollo de una aplicación web interactiva que incluye:
* **Módulo de Autenticación:** Control de acceso seguro por roles (Administrador, TI y Colaboradores) con opción de recuperación de credenciales[cite: 4].
* **Gestión Administrativa y de TI:** Configuración de días feriados, periodos vacacionales permitidos, creación y mantenimiento del catálogo de proyectos, y asignación de personal[cite: 3].
* **Módulo Operativo (Colaborador):** Solicitud de vacaciones con visualización de calendario y feriados, junto con un sistema detallado de registro diario de actividades por proyecto[cite: 3].
* **Módulo de Reportes y Métricas:** Consolidación de horas dedicadas por proyecto, análisis de eficiencia presupuestaria, distribución de carga de trabajo e indicadores de productividad[cite: 3].

##  Estructura del Repositorio
El repositorio se organiza de la siguiente manera para facilitar su revisión:
* `/docs` -> Contiene el documento PDF con la maquetación completa y los wireframes del sistema.
* `/src` o raíz del proyecto -> Código fuente de la aplicación web desarrollado con HTML, CSS y JavaScript.

##  Estrategia de Branches y Commits
Para garantizar un flujo de trabajo ordenado y colaborativo, el equipo implementó la siguiente estrategia de control de versiones en Git:
* **`main` / `master`:** Rama principal que contiene la versión estable y final de la entrega.
* **`desarrollo` / `dev`:** Rama de integración continua donde se fusionan los avances de todos los integrantes antes de pasar a producción.
* **Ramas de funcionalidad (`feature/...`):** Creadas de manera individual para el desarrollo de componentes específicos, wireframes e interfaces web.
* **Convención de commits:** Uso de mensajes claros y descriptivos basados en acciones (ej. `feat: implementa dashboard de colaborador`, `fix: corrige validación en formulario de vacaciones`, `docs: actualiza wireframes en carpeta docs`).
