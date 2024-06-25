
# Challenge Literalura


- Buscar libros por título en la API

- Buscar libros por autor que se encuentre en la base de datos.

- Listar libros y autores registrados.

- Buscar autores vivos en un año específico.

- Listar libros por idioma.

- Obtener el top 10 de libros más buscados.

- Generar estadísticas sobre las descargas de libros.

## ¿Cómo funciona Literalura?

Literalura utiliza una API externa para obtener información sobre libros y autores: https://gutendex.com/ También almacena información en una base de datos local para que puedas acceder a ella incluso sin conexión a internet.

## Estructura del proyecto:

src/main/java:

com.aluracursos.challengeliteralura:

model: Contiene las clases que representan los datos de libros y autores.

repository: Contiene las interfaces y clases que se utilizan para acceder a la base de datos.

service: Contiene las clases que implementan la lógica de negocio de la aplicación.

principal: Contiene la clase principal de la aplicación.

src/main/resources: Contiene los archivos de configuración de la aplicación.

pom.xml: Contiene las dependencias del proyecto.

## Tecnologías utilizadas:

Java 17

Spring Boot 3.2.4

PostgreSQL

Maven

## Instalación

### Clona el repositorio:

git clone https://github.com/tu-usuario/tu-proyecto.git
cd tu-proyecto
Configura la base de datos PostgreSQL y actualiza las credenciales en el archivo application.properties.

### Ejecuta la aplicación:

./mvnw spring-boot:run

