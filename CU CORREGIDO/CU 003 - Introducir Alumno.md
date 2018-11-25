## ID: 003 Introducir Alumno

**Breve descripción:** El sistema introduce un nuevo alumno en la base de datos.

**Actores principales:** Profesor

**Actores secundarios:** Alumno

**Precondiciones:**

 1. No se pueden registrar más de 150 alumnos.
 2. No puede coincidir el DNI con el de otro alumno.

**Flujo principal:**

 1. El caso de uso empieza cuando el profesor hace llamada a la función.
 2. El sistema comprueba que haya espacio para registar nuevo alumno.
 3. El profesor introduce los datos del alumno y el sistema comprueba que el alumno no exista en la base de datos.
 4. El sistema recoge los datos del alumno y los introduce en la base de datos.

**Postcondiciones:**

 - Si se provoca algún error, el sitema mandará un mensaje de error y finalizará.
 - Si no hay ningún error, el alumno se habrá registrado en la base de datos y finalizará con éxisto.

**Flujos alternativos:**

- 2.a Si hay 150 alumnos registrados, el sistema mandará un mensaje de error.
- 3.a Si el alumno ya existe, el sistema lanzará un mensaje de error.
