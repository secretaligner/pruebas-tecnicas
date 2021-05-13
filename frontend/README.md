## Prueba técnica Frontend
La prueba consiste en adaptar algunos diseños a un formato web

Tecnologías requeridas:
- VueJs
- JavaScript / jQuery
- CSS / SASS

La entrega final será presentada como un repositorio público de GitHub y se proporcionarla la URL para su revisión. 
Añadir en el README del proyecto el tiempo estimado dedicado a cada tarea (Max 12h.)

La lista de tareas es:
1. Crear la vista de Listado de Pacientes
    - La lista se debe poner descargarse en un csv
    - Tendrá dos modos de visionado, en lista o en tarjetas
    - Opción de elementos por página, poder elegir cuantos elementos se muestran por pagina
    - El buscador tendrá que buscar por nombre y/o apellidos del paciente
    - El desplegable “Acciones”, debe mostrar las siguientes opciones, en vista tarjetas las opciones se muestran como botones:
         - Editar
         - Finalizar
         - Borrar
    - Cambiar las siguiente columnas:
         - Dirección > Objetivo Tratamiento
    - Las columnas "Dentista" y "Disttribuidor" no son necesarias
2. El botón “Nuevo Paciente” abrirá una modal con las siguiente caracterizas:
    - Nombre > Text
    - Apellidos > Text
    - Fecha de naciemiento > DatePicker
    - Sexo > Select(Masculino, Femenino)
    - Clínica > Text
    - Recorte Alineadores > Checkbox (Recortar dejando 1-3 mm de encía, Recortar a nivel de los cuellos)
    - ¿SecretRetainer? > Checkbox (SI, NO)
    - Tres botones de acción:
         - Guardar > guardara en formulario enviado al backend los datos del formulario, no es necesario dicha funcionalidad
         - Cancelar > cerrar el model, pero no borra los campos rellenos
         - Limpiar > borra todas las entradas del formulario
3. Al pulsar sobre un paciente de la lista se abrirá en una modal la ficha del paciente según muestra el [Anexo-Ficha Paciente](Anexo-Ficha Paciente.pdf). 
Dicha información se debe descargar en un PDF. Los dientes que no se mueven, aparecen en la ficha marcados con un círculo rojo


