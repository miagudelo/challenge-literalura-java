# Challenger - Literalura

Esta aplicacion corresponde al desarrollo del Challenge 2 de la especializacion en BACK END en el programa de Alura Latam ONEG6, que consiste en realizar un catálogo de libros consumiendo una API y que además ofrece interacción con el usuario a través de la consola

## Comenzando 🚀

Para obtener una copia del proyecto y probarlo, debes hacer clic en enlace del repositorio: https://github.com/miagudelo/challenge-literalura-java  - luego debes hacer clic en el boton verde de la parte superior derecha que dice "<> Code", luego haz clic en la ultima opcion "Download Zip" para descargar los archivos, despues los debes descomprimir y abrir el proyecto desde el IDE Intellig para luego ejecutarlo desde la clase llamada ChallengeLiteraluraApplication.

![challenge-literalura](https://i.postimg.cc/K89gvdr0/Presentacion-programa.jpg)


En la aplicacion podemos consultar libros consumiendo la API Gutendex  que es un catálogo de información de más de 70.000 libros presentes en Project Gutenberg (biblioteca en línea y gratuita), guardarlos en la base de datos y luego generar reportes de libros consultados, autores, top 10 de libros descargados, estadísticas sobre el número de descargas de los libros, entre otros.


### Pre-requisitos 📋

- Tener instalado el JDK Java 17 en adelante
- Tener instalado el IDE IntelliJ IDEA
- Maven (Initializr utiliza la versión 4)
- Spring Boot (versión 3.2.3)
- Postgres: versión 16 en adelante
- Crear base de datos en PGAdmin llamada literalura

### Para ejecutar el programa:
 Estando en la pestalla o clase llamada "Principal" damos Clic al boton en forma de triangulo horizontal verde (Run) como lo indica la flecha en la siguiente imagen:

![challenge-literalura](https://i.postimg.cc/m2fYvf8M/Ejecucion-programa.jpg)


## Opciones del Menú
[![challenge-literalura](https://i.postimg.cc/brpXD6vy/menu.jpg)


### *Opción 1:* Buscar libros por título, es posible realizar la búsqueda por el nombre completo o parte del nombre del libro, si ya está en la base de datos, no es posible registrarlo nuevamente.
![challenge-literalura](https://i.postimg.cc/25y4Qv6n/opcion1.jpg)

### *Opción 2:* Listar libros registrados. Muestra la información de los libros registrados en la base de datos con los datos del autor, idioma y número de descargas.
![challenge-literalura](https://i.postimg.cc/kGv63XGn/opcion2.jpg)

### *Opción 3:* Listar los autores registrados, con los libros incluídos. teniendo en cuenta que si tiene más de un libro, sólo se mostrará una vez el autor con los distintos libros de su autoría
![challenge-literalura](https://i.postimg.cc/NGDjcnbf/opcion3.jpg)

### *Opción 4:* Listar autores vivos en un determinado año
![challenge-literalura](https://i.postimg.cc/sD8yfCWy/opcion-4.jpg)

### *Opción 5:* Listar libros por idioma, teniendo en cuenta que soporta sólo los idiomas: español, inglés, francés, portugués e italiano
![challenge-literalura](https://i.postimg.cc/YCnXBtLf/opcion5.jpg)

### *Opción 6:* Ver estadísticas de descargas: cantidad media de descargas, cantidad máxima y mínima de descargas y cantidad de registros evaluados para esas estadísticas
![challenge-literalura](https://i.postimg.cc/vBQD7wXk/opcion6.jpg)

### *Opción 7:* Ver Top 10 de libros descargados
![challenge-literalura](https://i.postimg.cc/bvvwd9Jf/opcion7.jpg)

### *Opción 8:* Buscar datos de un autor por nombre
![challenge-literalura](https://i.postimg.cc/fL9Z02Qp/opcion8.jpg)

### *Opción 9:* Buscar autores nacidos a partir del año indicado
![challenge-literalura](https://i.postimg.cc/VLjqFmFL/opcion9.jpg)

### *Opción 10:* Para SALIR del Programa.



### Aplicacion Construida en JAVA, usando Spring, JPA, JPQL  🛠️


## Autor ✒️

Marta Isabel Agudelo Restrepo
