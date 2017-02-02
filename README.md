
Practicas EGC Maven
===================


Proyecto para el aprendizaje de la herramienta maven.

----------
Desarrollo
-------------
Se crea un proyecto maven

    $mvn archetype:generate -DgroupId=egc.practicas.maven -DartifactId=Practicas-Maven -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

Se compila y empaqueta para verificar el correcto funcionamiento:

    $mvn compile
    $mvn package
Se añaden plugins al proyecto.

 - PMD
 - Assembly: para la mejora del empaquetamiento de la aplicación.
 - Javadoc : para la creación automática de la documentación.
