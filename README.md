# Pokebot Showcase

Este repositorio contiene la demostración del Pokebot, enfocado en la automatizacion del farmeo en el juego.

> Nota: El código fuente completo se mantiene privado.




[![Showcase](https://img.youtube.com/vi/t5VTM1uwjd0/0.jpg)](https://youtu.be/t5VTM1uwjd0)

### Capacidades del Sistema
El bot ha sido desarrollado bajo una arquitectura modular que permite:
* Reconocimiento OCR: Sistema de detección para identificar eventos específicos en pantalla (Shinys, encuentros, hordas).
* Navegación: Motor de reproducción de rutas personalizadas con capacidad de grabación y lectura de waypoints.
* Módulos: Lógica separada para farmeo (Payday), caza de variocolores (shinys) y actividades secundarias.
* Gestión de Sesiones: Registro automático de resultados y configuración flexible mediante archivos JSON.

### Arquitectura del Proyecto

```text
Pokebot/
├── Configurations/    # Parámetros ajustables  (JSON)
├── CoreLogic/         # Motor de visión, selección y utils
├── Modules/           # Lógica específica de cada tarea
├── Routing/           # Sistema de navegación y waypoints
└── main.py            # Interfaz gráfica
