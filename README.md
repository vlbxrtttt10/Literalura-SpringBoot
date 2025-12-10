# Catálogo de Libros - Cliente de Consola con Gutendex API

Este proyecto es una aplicación de **Java con Spring Boot** que permite consultar libros de la API [Gutendex](https://gutendex.com/) (Project Gutenberg) y almacenar información de libros y autores en memoria. La aplicación se ejecuta completamente desde la **consola**, sin necesidad de navegador.

---

## Tecnologías utilizadas

- Java 17
- Spring Boot 4.0
- Maven
- Jackson (para parseo JSON)
- API Gutendex (Project Gutenberg)

---

## Funcionalidades

La aplicación permite:

1. **Buscar libros por título**  
   - Realiza una consulta a la API Gutendex.
   - Guarda todos los resultados en memoria.
   - Muestra los libros encontrados en consola.

2. **Listar todos los libros almacenados**  
   - Muestra todos los libros que fueron buscados y guardados en memoria.

3. **Listar todos los autores almacenados**  
   - Muestra todos los autores de los libros guardados.
   - Evita mostrar duplicados.

4. **Listar autores vivos en un año específico**  
   - Filtra los autores según su año de nacimiento y fallecimiento.
   - Solo considera autores con fecha conocida.

5. **Mostrar estadísticas por idioma**  
   - Agrupa los libros por idioma.
   - Muestra la cantidad de libros por idioma.

---

## Estructura del proyecto

