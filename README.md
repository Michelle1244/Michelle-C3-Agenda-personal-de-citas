# Resumen del sistema Agenda personal de citas
## Descripcion del caso

El sistema de Agenda Personal de Citas es una herramienta digital creada para facilitar la administración de actividades y compromisos del usuario. Su propósito es brindar un espacio organizado donde se pueda planificar el día a día, programar citas y mantener un registro claro de tareas pendientes. Gracias a esta aplicación, el usuario puede gestionar su tiempo de manera eficiente, evitar solapamientos en su agenda y contar con alertas que le ayuden a recordar eventos importantes.


## Objetivos del sistema

Los objetivos del sistema están orientados a asegurar que la aplicación desempeñe adecuadamente su función de organizar y administrar citas de forma clara y práctica. Para ello, se definen dos categorías de objetivos que permiten estructurar el alcance y las metas principales del sistema.

 Los objetivos del sistema: 
  
  * Funciones que el sistema **"debe cumplir"** (RF)
Representan las operaciones específicas que el usuario podrá ejecutar dentro de la aplicación. Estos objetivos se orientan a brindar opciones claras para crear, consultar y gestionar sus citas de manera práctica y accesible.
  * Características **"obligatorias"** del sistema (RNF)
Definen los atributos y parámetros que la aplicación debe mantener para garantizar un funcionamiento confiable y óptimo. Estas cualidades abarcan factores como eficiencia en el desempeño, adaptación a distintos entornos, facilidad de interacción para el usuario y resguardo adecuado de los datos.


## Requerimientos

### Requerimientos funcionales  (RF)
* **RF1 – Alta de citas:** El sistema debe permitir registrar una nueva cita indicando fecha, hora, descripción y categoría.
* **RF2 – Consulta de citas:** El sistema debe permitir visualizar la lista de citas registradas ordenadas por fecha.
* **RF3 – Modificación de citas:** El sistema debe permitir editar los datos de una cita previamente registrada.
* **RF4 – Eliminación de citas :** El sistema debe permitir eliminar citas que ya no sean necesarias. 



### Requerimientos no funcionales (RNF)
* **RNF1 – Usabilidad :** La interfaz debe ser intuitiva y fácil de usar para todo tipo de usuario.
* **RNF2 – Rendimiento :** El sistema debe mostrar o actualizar la información en menos de 2 segundos.
* **RNF3 – Portabilidad :** El sistema debe poder ejecutarse en computadoras de escritorio y dispositivos móviles.


## Casos de prueba (Sin tabla)

* **PU-01**

 *Tipo: Unitario
 *Requerimiento: RF1
 *Datos: Usuario ingresa la fecha y la hora de la cita
 *Resutado esperado: La cita se registra correctamente
 *Resultado obtenido: **Correcto**


* **PU-02**

 *Tipo: Unitario
 *Requerimiento: RF3
 *Datos: Modifica de **Cita medica** a **Cita medica con analisis**
 *Resutado esperado: Cita actualizada con nuevos datos
 *Resultado obtenido: **Correcto**


* **PV-01**

 *Tipo: Validacion
 *Requerimiento: RF2
 *Datos: Usuario consulta sus citas
 *Resutado esperado: Se muestran todas las citas ordenadas por fecha.
 *Resultado obtenido: **Correcto**


* **PV-02**

 *Tipo: Validacion
 *Requerimiento: RF5
 *Datos: Ingresa **Hora:** y **tiempo a recordar antes de la cita:**
 *Resutado esperado: Se muestra notificación de recordatorio 10 min antes
 *Resultado obtenido: **Correcto**


## Tipos de propuesta de mantenimiento 

* **Problema:** Ocasionalmente, el sistema no logra sincronizar correctamente las citas entre los distintos dispositivos, generando discrepancias y evitando que ciertos cambios se reflejen de manera inmediata.
 
 
  * **Tipo de Mantenimiento:** Mantenimiento correctivo
  * **Accion:** Evaluar el funcionamiento del módulo de sincronización y aplicar las correcciones necesarias para optimizar el intercambio de datos, garantizando una actualización adecuada en tiempo real.
  * **Justificacion:** Atender este inconveniente es esencial para preservar la consistencia de la información y asegurar que el usuario cuente con sus citas correctamente sincronizadas en todos sus dispositivos.

* **Problema:** Se han detectado inconsistencias durante el proceso de sincronización entre dispositivos, lo que ocasiona que ciertas modificaciones realizadas por el usuario no se actualicen adecuadamente.
  

 
  * **Tipo de Mantenimiento:** Mantenimiento Correctivo
  * **Accion:** Analizar el componente encargado de la sincronización y aplicar correcciones en la gestión de datos en tiempo real, asegurando que la transmisión y actualización de la información se ejecuten sin errores.
  * **Justificacion:** Corregir este comportamiento es fundamental para garantizar la integridad de los datos y que las citas se mantengan coherentes en todos los equipos donde se utilice la aplicación.


## Reflexion sobre el control de versiones 

El control de versiones constituye un recurso fundamental para mantener el desarrollo del sistema de forma ordenada y transparente. Gracias a esta herramienta es posible llevar un historial detallado de cada modificación, detectar el origen de problemas, registrar mejoras y recuperar estados anteriores del proyecto cuando sea necesario.
