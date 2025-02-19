Descripción
Este es un proyecto básico de Spring Boot que expone un endpoint HTTP en /hello, el cual responde con un mensaje de Hola Mundo.

Tecnologias Utilizadas
Java 21 (Amazon Corretto)
Spring Boot 3.4.2
Maven

Requisitos previos
Antes de ejecutar el proyecto, asegúrate de tener instalado:
Java 21 (Verifica con java -version)
Maven (Verifica con mvn -version)

Para el desarrollo del Proyecto de Spring se consultó el siguiente enlace
https://spring.io/quickstart

Para poder ejecutar el projecto
mvn spring-boot:run

Se utilizo el puerto 8081 para evitar conflictos con el puerto 8080, se puede cambiar en src/main/resources/application.properties
server.port=8081

Para comprobar la aplicacion acceder desde un navegador a 
http://localhost:8081/hello

Proyecto realizado por: Flores Rangel Mauricio Alberto 
Grupo: 6CV4
