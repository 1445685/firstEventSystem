# firstEventSystem

## Descripción
Sistema de eventos que se ejecuta dentro de un proceso.

## Caracteristicas
- La comunicación esta basada en colas bloqueantes.
- El broker se ejecuta en un hilo aparte dentro del mismo proceso.
- Los eventos se envian a todos los suscriptores de un canal.
- El sistema se limita únicamente al proceso en el que se creo; no usa comunicación entre diferentes procesos ni sockets.

## Proximos cambios
- Colección de eventos sin suscriptores.
- Colas de prioridad por canal.
- Posiblemente persistencia de eventos.

## Referencia de diseño:
[GeeksforGeeks](https://www.geeksforgeeks.org/system-design/event-driven-architecture-system-design/)