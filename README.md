# Rikimaka - Sistema Integral de Gestión Humana

##  Descripción del Proyecto
Rikimaka es una solución web interactiva diseñada para optimizar la administración de proyectos, la solicitud de permisos, la configuración de periodos de vacaciones y el reporte de labores diarias dentro de una organización. El sistema busca fortalecer la trazabilidad del trabajo, la planificación estratégica del personal y la eficiencia en el uso de recursos mediante una interfaz intuitiva dividida por roles clave (Administrador / Talento Humano / Personal de TI y Colaboradores).

##  Integrantes del Equipo 
- **Frenny Montezuma Castillo** 
- **Geisel Tatiana Araya Garita** 
- **Jeiferson Elías Rivera Walker** 

##  Alcance del Sistema (Actualizado - Avance II)
El proyecto contempla el desarrollo de una aplicación web frontend interactiva y funcional que incluye:
- **Módulo de Autenticación:** Control de acceso simulado con validación de credenciales corporativas.
- **Gestión Administrativa y de TI:** Configuración de días feriados, periodos vacacionales permitidos, creación, edición y eliminación en el catálogo de proyectos.
- **Módulo Operativo (Colaborador):** Registro diario de actividades y control de asignaciones.
- **Módulo de Reportes, Métricas y Asignación de Personal TI:** Aprobación de solicitudes de vacaciones, cálculo de dedicación de personal (control de límite de 100%), gráficos de desempeño, reportes y métricas con persistencia de datos local (`localStorage`).

##  Tecnologías y Características Técnicas
- **HTML5 Semántico:** Uso de etiquetas estructuradas (`header`, `nav`, `main`, `section`, `article`, `footer`) y formularios con etiquetas asociadas (`label`).
- **CSS3 Moderno y Responsive:** Estilos organizados, uso de **Flexbox** y **Grid** para la distribución de paneles, variables CSS (`:root`) para la consistencia visual y diseño adaptativo para diferentes dispositivos.
- **Interactividad y Persistencia:** Lógica en JavaScript puro sin dependencias externas, implementando almacenamiento local (`localStorage`) para la gestión dinámica de proyectos y asignaciones de personal.
- **Accesibilidad:** Contraste de color adecuado, atributos de accesibilidad, uso de foco visible y textos alternativos.

##  Estructura del Repositorio
El repositorio se organiza de la siguiente manera para facilitar su revisión:
- `/css` -> Contiene la hoja de estilos modular y centralizada (`styles.css`).
- `/docs` -> Contiene el documento PDF oficial de entrega (el cual incluye el enlace de acceso directo al repositorio de GitHub).
- `/src/ Proyecto Rikahama.html` -> Código fuente de las pantallas funcionales integradas y navegables.

##  Estrategia de Branches y Commits
Para garantizar un flujo de trabajo ordenado y colaborativo, el equipo implementó la siguiente estrategia de control de versiones en Git:
- **`main` / `master`:** Rama principal que contiene la versión estable y final de la entrega.
- **`desarrollo` / `dev`:** Rama de integración continua donde se fusionan los avances de todos los integrantes antes de pasar a producción.
- **Ramas de funcionalidad (`feature/...`):** Creadas de manera individual para el desarrollo de componentes específicos, wireframes e interfaces web.
- **Convención de commits:** Uso de mensajes claros y descriptivos basados en acciones (ej. `feat: implementa catálogo de proyectos y localStorage`, `fix: corrige validación de dedicación de personal`, `docs: incorpora Avance02 en la carpeta docs`).
