Auditoría con Hibernate Envers

En este proyecto, se ha implementado la auditoría de los cambios realizados en las entidades utilizando Hibernate Envers. Esta funcionalidad permite registrar automáticamente las modificaciones (creación, actualización y eliminación) en tablas de auditoría específicas.
#Configuración de Auditoría

  Clase de Revisión Personalizada: Se ha configurado una clase personalizada de revisión (Revision) para almacenar información adicional sobre cada cambio. Esto incluye la fecha y el identificador de la revisión.

  Listener Personalizado: Se ha implementado un listener (CustomRevisionListener) que permite capturar y almacenar información adicional sobre las revisiones realizadas.

  Auditoría de Entidades: Se ha auditado el mapeo de las entidades principales, lo que permite mantener un historial detallado de sus relaciones y estados. Las tablas de auditoría se generan automáticamente por Envers, proporcionando un seguimiento           completo de todas las modificaciones.

#Beneficios

  Historial Completo: Mantiene un registro detallado de todos los cambios en las entidades, facilitando el rastreo y la recuperación de estados anteriores.
  Transparencia: Permite una mayor transparencia en la gestión de datos y la auditoría de las operaciones realizadas en el sistema.
