INSTRUCCIONES
=============

0. Crea un repo en github y compártelo de manera privada conmigo. Realiza un commit como mínimo al pasar cada caso test propuesto o **no corregiré** tu examen.
Realiza un `push` al repo remoto en GitHub **SOLO cuando hayas terminado el proyecto**. El proyecto ha de ser privado y compartido conmigo.

1. Crea un proyecto REST Quarkus con Maven. Instala las dependencias del proyecto según las vayas necesitando.

2. Situa los archivos proporcionados: `schema.sql` en sus directorios correspondientes del proyecto. **No** modifiques el contenido de este archivo. 
   
3. La base de datos ha de ser H2 corriendo en memoria en el mismo proceso que la app.
   
4. Has de establecer en el fichero `application.properties` las opciones adecuadas para configurar de este modo el acceso a datos.

5. Comienza implementando los casos test del archivo `RepoTest.java`. **No** modifiques su código. Implementa las entidades y la capa correspondiente al repositorio o acceso a datos **con el patrón que prefieras (Active Record o DAO)**. Los casos test son agnósticos a esta decisión de diseño.

6. Los casos test del repositorio involucran los contenidos mínimos del módulo necesarios para aprobarlo.

7. Una vez codificado el repositorio, continua con los casos test del archivo `ResourceTest.java` para implementar el servicio y controlador (`Resource`) de la app. Todas las peticiones al controlador ha de pasar por el servicio antes de dirigirlas al método correspondiente del repositorio.
   
```bash
            ___
	. -^    `--,
       /# =========`-_
      /# (--===___====\
     /#   .- --.  . --.|
    /##   |  * ) (   * ),
    |###  \    /\ \    /|
    |###   ----  \  --- |
    |####      ___)    #|
     \####            ##|
      \### ----------  /
       \###           (
        '\###         |
          \##         |
           \###.    .)
            '======/
       
       SHOW ME WHAT YOU'VE GOT! 
```