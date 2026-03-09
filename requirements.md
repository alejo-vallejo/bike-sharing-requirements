# Sistema de préstamo de bicicletas
## Stakeholders

- Comunidad Estudiantil: Usuarios principales que requieren movilidad eficiente dentro del campus y acceso a la disponibilidad de bicicletas.
- Departamento de Bienestar Universitario: Encargados de la gestión administrativa, registro de usuarios vinculados al carnet y aplicación de normativas.
- Unidad de Soporte Técnico y Mantenimiento: Personal responsable de recibir alertas de fallas, reparar las unidades y asegurar el buen estado mecánico.
- Cuerpo de Seguridad del Campus: Interesados en el monitoreo de la ubicación GPS de las bicicletas y la prevención de salidas no autorizadas del recinto.
  
## Requisitos funcionales

- RF1: El sistema debe permitir a los estudiantes registrarse vinculando su carnet universitario.
- RF2: El sistema debe mostrar un mapa en tiempo real con las estaciones de bicicletas activas.
- RF3: El sistema debe permitir al usuario reservar una bicicleta por un máximo de 15 minutos antes de recogerla.
- RF4: El sistema debe generar un código QR para que el estudiante desbloquee la bicicleta físicamente.
- RF5: El sistema debe permitir al usuario calificar el estado de la bicicleta al finalizar el préstamo.
- RF6: El sistema debe enviar una alerta automática al equipo de mantenimiento cuando una bicicleta sea reportada con fallas.
- RF7: El sistema debe guardar un historial detallado de las rutas y tiempos de uso de cada estudiante.

## Requisitos no funcionales

- RNF1: La interfaz debe ser amigable y fácil de usar en dispositivos móviles (Android e iOS).
- RNF2: El sistema debe ser capaz de procesar hasta 100 solicitudes de préstamo simultáneamente sin perder datos.
- RNF3: La base de datos debe realizar copias de seguridad automáticas cada 24 horas.
- RNF4: El tiempo de carga de la disponibilidad de bicicletas no debe superar los 3 segundos.
- RNF5: El sistema debe funcionar correctamente bajo las redes Wi-Fi oficiales del campus universitario.
- RNF6: Los datos personales de los estudiantes deben estar protegidos mediante protocolos de cifrado estándar.
- RNF7: El sistema debe registrar la ubicación GPS exacta de la bicicleta cada vez que sea bloqueada o desbloqueada.
