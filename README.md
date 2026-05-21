# Pokebot Showcase

Este repositorio contiene la demostración del Pokebot, enfocado en la automatizacion del farmeo en el juego.

> Nota: El código fuente completo se mantiene privado para garantizar la integridad del sistema. 
<video src="NOMBRE_DE_TU_VIDEO.mp4" controls="true" width="100%"></video>

### Capacidades del Sistema
El bot ha sido desarrollado bajo una arquitectura modular que permite:
* Reconocimiento Visual: Sistema de detección en tiempo real para identificar eventos específicos en pantalla (Shinys, encuentros, hordas).
* Navegación Autónoma: Motor de reproducción de rutas personalizadas con capacidad de grabación y lectura de waypoints.
* Módulos: Lógica separada para farmeo económico (Payday), caza de variocolores (shinys) y actividades secundarias.
* Gestión de Sesiones: Registro automático de resultados y configuración flexible mediante archivos JSON.

### Arquitectura del Proyecto
La solución está estructurada para ser mantenible y escalable:

```text
Pokebot/
├── Configurations/    # Parámetros ajustables  (JSON)
├── CoreLogic/         # Motor de visión, selección y utils
├── Modules/           # Lógica específica de cada tarea
├── Routing/           # Sistema de navegación y waypoints
└── main.py            # Interfaz gráfica
