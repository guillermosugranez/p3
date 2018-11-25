## ID: 005 Guardar Copia de Seguridad

**Breve descripción:** El sistema hace una copia de seguridad de la base de datos del sistema.

**Actores principales:** Profesor

**Actores secundarios:** Alumno

**Precondiciones:**

 1. Solo puede hacer la copia de seguridad si es usuario-coordinador.
 2. Se debe gestionar cuando el nombre del fichero coincida con uno existente.

**Flujo principal:**

 1. El caso de uso empieza cuando el usuario-profesor necesita realizar una copia de seguridad.
 2. El sitema solicita clave coordinador.
 3. El sistema pide un nombre de fichero, mete los datos y lo guarda.

**Postcondiciones:**

 - Si se provoca algún error, el sitema mandará un mensaje de error y finalizará.
 - Si no hay ningún error, se habrá efectuado una copia de seguridad de los datos.

**Flujos alternativos:**

- 2.a Si no es usuario coordinador dinalizará la función y mostrará un error.
- 3.a Si el fichero ya existe se mostrará error.
