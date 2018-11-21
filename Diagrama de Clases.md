## Diagrama de Clases

![Diagrama de clases](https://github.com/p92supeg/p3/blob/master/imagenes/Diagrama%20de%20Clases.jpg)

### Breve Descripción:

 - La clase agenda es una composición de alumnos. Si la agenda se borra, se borran todos los alumnos almacenados en ella.
 - La agenda puede ser consultada y/o modificada por los profesores.
 - Tanto profesor como alumno son clases hijas de Persona, y heredan todos sus atributos (dni, nombre, primerApellido...), además de tener los suyos propios.
 - Para el coordinador y el ayudante, no se han considerado clases especificas. Lo que permite clasificar a un profesor en ayudante o coordinador es el atributo "Coordinador" de la clase Profesor.
