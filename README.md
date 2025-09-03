# tracker-de-objetivos-personaless
El usuario elige un objetivo (ej: leer 20 paginas, tomar 2L de agua al dia, caminar 10k), visualizando avance en una barra de progreso

Explicación del Diagrama DER:

La aplicación está pensada como una herramienta de gestión de objetivos personales, donde cada usuario puede crear metas, dividirlas en etapas y tareas concretas, registrar su progreso y recibir recordatorios para no perder de vista sus avances.

Usuarios y Objetivos
- El Usuario es la entidad central del sistema, ya que cada persona registrada puede crear y administrar sus propios objetivos.
- En el objetivo se guarda un título, descripción, fecha de inicio y fecha de finalización.
- De esta manera, cada usuario puede manejar varios objetivos en simultáneo.


Hitos y Tareas
- Los objetivos se descomponen en Hitos, que representan logros parciales o pasos importantes dentro de la meta general.
- Cada hito está vinculado a un objetivo y tiene nombre, descripción, fecha estimada y estado de completado.
- A su vez, los hitos se dividen en Tareas, que son las acciones concretas a realizar.
- Las tareas cuentan con nombre, descripción, fecha límite, estado y si están completadas.


Registro de Progreso
- Para llevar un seguimiento, existe la entidad Registro_Progreso, que permite documentar los avances de un objetivo en fechas específicas.
- Allí se guardan porcentajes de progreso y comentarios.
- Esto facilita ver la evolución de cada meta a lo largo del tiempo.


Categorías
- Cada objetivo puede clasificarse en una Categoría (por ejemplo: Salud, Estudios, Trabajo, Finanzas), lo que permite organizar y filtrar las metas según su tipo.

Recordatorios
- Finalmente, el sistema incluye la entidad Recordatorio, que se asocia tanto al usuario como al objetivo.
- Los recordatorios almacenan un mensaje y una fecha/hora, con el fin de enviar notificaciones y ayudar al cumplimiento de plazos.



- Un usuario puede tener varios objetivos.

- Cada objetivo se divide en hitos y estos en tareas.

- El progreso se registra en los objetivos.

- Los objetivos se organizan por categorías.

- Los recordatorios permiten avisos personalizados.




