# Usamos una imagen de maven con Eclimpse temurin 17 JDK
FROM maven:3.9.6-eclipse-temurin-17-focal
# Crea un directorio de trabajo dentro del contenedor
WORKDIR /app
# Copiar el código fuente y el archivo pom.xml
COPY pom.xml .
COPY src ./src
# Ejecuta el proceso de construcción con Maven
RUN mvn clean package -DskipTests -Dmaven.compiler.source=17 -Dmaven.compiler.target=17 -e
# Cambiamos al directorio donde se encuentra el archivo JAR
WORKDIR /app/target

ENTRYPOINT ["java", "-jar", "crud-0.0.1-SNAPSHOT.jar"]
