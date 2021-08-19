## Prueba técnica Backend
La prueba consiste en hacer una web para llevar el control de una TODO list.

Tecnologías requeridas:
- Symfony
- JavaScript/Jquery
- Sqlite

La entrega final será presentada como un repositorio público de GitHub y se proporcionarla la URL para su revisión. Añadir en el README del proyecto el tiempo estimado dedicado a cada tarea

Cada punto del siguiente listado se tratará como una rama aparte que se mergeará contra máster.

La parte frontal es secundaria, usar una plantilla bootstrap/materializae está permitido.

La lista de tareas es:
1.  Crear estructura para proyecto Symfony
2.  Crear entidad TODO con los siguintes campos: 
     - nombre 
     - fecha creación (automática) 
     - fecha tope
     - estado
3.  Crear interfaz para añadir elementos a la lista y visualizar el listado.
4.  Posibilidad de marcar como realizada la tarea y diferenciar visualmente de las pendientes.
5.  (Opcional) Crear un comando de Symfony para añadir elementos a la lista por terminal.
6.  (Opcional) Modificar la interfaz realizada en el punto 3 para realizar las modificaciones por ajax.
7.  Añadir login y autenticar la aplicación. Crear un rol admin para gestionar todas las listas. Un rol usuario accederá únicamente a su lista.
8.  Añadir para un usuario con rol admin la posibilidad de modificar el dueño de la lista, pudiendo un usuario tener varias listas de TODO.
9. (Opcional) Añadir creación de usuarios.
10. Un admin puede visualizar las listas TODO del resto de usuarios, pero no modificar sus elementos.
11. (Opcional) Añadir logs de aplicación para trackear el seguimiento de las iteraciones con cada una de las listas.
12. (Opcional) Crear un servicio de notificaciones para enviar un email al administrador cada vez que se completan todas las tareas de una lista.


