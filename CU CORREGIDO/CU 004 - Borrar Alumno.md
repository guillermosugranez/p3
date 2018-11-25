## ID: 004 Borrar Alumno

**Breve descripción:** El sistema borra un alumno existente en la base de datos.

**Actores principales:** Profesor

**Actores secundarios:** Alumno

**Precondiciones:**

 1. El alumno debe existir en el sistema.

**Flujo principal:**

 1. El caso de uso empieza cuando se realiza la llamada a la función.
 2. El sistema busca al alumno por su dni o apellidos.

**Postcondiciones:**

 - Si se provoca algún error, el sitema mandará un mensaje de error y finalizará.
 - Si no hay ningún error, el alumno se habrá eliminado de la base de datos y finalizará con éxisto.

**Flujos alternativos:**

- 2.a Si no coincide dni con ningún alumno, el sistema lanzará un mensaje de error.
