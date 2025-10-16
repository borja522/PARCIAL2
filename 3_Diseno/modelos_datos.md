# Modelo de datos propuesto

| Entidad | Descripción | Atributos principales |
|----------|--------------|-----------------------|
| Usuario | Persona con discapacidad visual | id_usuario, nombre, edad, tipo_discapacidad, nivel_autonomia |
| Dispositivo | Gafas asistidas registradas | id_dispositivo, modelo, versión, fecha_uso |
| Sesión de uso | Interacción entre usuario y gafas | id_sesion, fecha, hora_inicio, hora_fin, funciones_utilizadas |
| Reporte | Registro de actividades realizadas | id_reporte, id_usuario, autonomía_percibida, observaciones |
