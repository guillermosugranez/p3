**_Diagramas de Secuencia_**
============================


# 001 - Buscar Alumno #

![Buscar Alumno DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/001%20-%20Buscar%20Alumno.jpg)

### Breve Descripción ###

- El sistema recoge los datos del alumno.
- Si no encuentra al alumno, el sistema muestra un mensaje de error.
- Si hay más de un resultado, el sistema mostrará las coincidencias y permitirá realizar una nueva busqueda por otro criterio.



# 002 - Mostrar Alumno #

![Mostrar Alumno DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/002%20-%20Mostrar%20Alumno.jpg)

### Breve descripción ###

- El sistema recoge los datos del alumno introducido.
- El sistema muestra los datos del alumno por pantalla.
- Si no encuentra al alumno, el sistema muestra un mensaje de error.


# 003 - Introducir Alumno #

![Introducir Alumno DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/003%20-%20Introducir%20Alumno.jpg)

### Breve Descripción ###

- El sistema debe comprobar que el alumno no exista y que no haya más de 150 alumnos registrados.
- El sistema recoge los datos del alumno y los introduce en la base de datos.
- Si el alumno ya existía, el sistema lanzará un mensaje de error.
- Si hay 150 alumnos registrados, el sistema mandará un mensaje de error.
- Si el dni del nuevo alumno ya existía, el sistema lanzará un mensaje de error.



# 004 - Borrar Alumno #

![Borrar Alumno DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/004%20-%20Borrar%20Alumno.jpg)

### Breve descripción ###

- El sistema debe encontrar al alumno por su dni o apellidos y lo deberá borrar.
- Si no coincide dni o apellidos con ningún alumno, el sistema lanzará un mensaje de error.



# 005 - Guardar copia de seguridad #

![Guardar copia de seguridad DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/005%20-%20Guardar%20Copia%20De%20Seguridad.jpg)

### Breve descripción ###

- El sistema deberá pedir el nombre de un fichero, comprobar la apertura correcta del mismo, y realizar la copia de seguridad.
- Si el fichero ya existe, pregustar si desea sobreescribirlo.
- Si no se pudo realizar la copia de seguridad por algún motivo, el sistema lanzará un mensaje de error.



# 006 - Restaurar copia de seguridad #

![Restaurar copia de seguridad DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/006%20-%20Restaurar%20Copia%20De%20Seguridad.jpg)

### Breve Descripción ###

- El sistema pedirá el nombre del fichero donde se ha guardado la ultima copia de seguridad, leerla y escribirla en el fichero principal.
- Si no existe el fichero introducido, el sistema mostrará un mensaje de error.
- Si no hay información guardada en el fichero creado para guardar la copia de seguridad, el sistema debe mostrar un mensaje de error.



# 007 - Modificar Alumno #

![Modificar Alumno DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/007%20-%20Modificar%20Alumno.jpg)

### Breve descripción ###

- El sistema debe recoger los datos del alumno que se quiere modificar.
- Si no existe el alumno, el sistema debe mostrar un mensaje de error.



# 008 - Listar todos los alumnos #

![Listar todos los alumnos DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/008%20-%20Listar%20Todos%20Los%20Alumnos.jpg)

### Breve Descripción ###

- El sistema lee todos los alumnos inscritos en el sistema.
- Si no hay ningún alumno inscrito en el sistema, el sistema debe mostrar un mensaje de error.



# 009 - Establecer líder de grupo #

![Establecer líder de grupo DS](https://github.com/p92supeg/p3/blob/master/imagenes/Diagramas%20de%20secuencia/009%20-%20Establecer%20L%C3%ADder%20De%20Grupo.jpg)

### Breve descripción ###

- El sistema deberá leer todos los alumnos de un grupo determinado.
- Si el alumno no se encuentra en el grupo, el sistema debe mostrar un mensaje de error.
- Si el grupo ya tiene líder, el sistema le preguntará al profesor si quiere sustituirlo.