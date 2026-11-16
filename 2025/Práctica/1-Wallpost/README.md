# Ejercicio 1 - WallPost


## Requerimientos

Java 11+. Recomendamos usar algun JDK que sea open source y con licencia de uso libre; los más habituales son Oracle OpenJDK ( jdk.java.net) y Adoptium(AdoptOpenJDK), aunque también se pueden usar Amazon – Corretto, RedHat GraalVM y SAP SapMachine.


## Run

Requiere Maven instalado (la carpeta `.mvn/` del wrapper no está versionada, así que `mvnw` no alcanza por sí solo).

Para correr los tests: `mvn test`

Para correr la aplicación y mostrar la UI: 

```sh
mvn clean package
java -jar target/ejercicio1-wallpost-1.0.0-jar-with-dependencies.jar
```

