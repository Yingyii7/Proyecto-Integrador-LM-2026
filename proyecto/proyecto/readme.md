## Parte 1:
Proyecto Web: Web de Películas
Nombre del estudiante: Yingyi Li Pan
Usuario de GitHub: Yingyii7
Módulo: Lenguajes de Marcas y Sistemas de Gestión de Información (1º DAM, curso 2026/2027)

Tema elegido:
El tema principal de este proyecto es una web de películas.

¿Por qué he elegido este tema?
Personalmente me gusta mucho pasar tiempo con mi familia o con amigos viendo una película graciosa o de miedo en algunas ocasiones. Considero que es una temática ideal para este proyecto, ya que ofrece un campo de temas muy amplio y entretenido para estructurar datos, redactar contenidos y desarrollar la web a lo largo de este curso.

*Palabra del día: contexto*
 
Qué he hecho en esta entrega:
En esta entrega he estructurado el proyecto integrador creando un sitio web básico con HTML (index.html) y un catálogo estructurado con XML (datos.xml). He incluido secciones
sobre mis películas y series recomendadas con imágenes y formateo de texto, además de organizar los datos equivalentes en XML respetando todas las reglas de sintaxis e incluyendo atributos propios. He incluido datos sobre 3 películas y 3 series populares, como los protagonistas principales, su fecha de estreno y otros.

## «UD3 · Estructura HTML» 

Cosas que le faltan a mi index.html inicial:
1. Faltan metadatos adicionales dentro de <head>, como una descripción de la página.
2. Falta orgnizar el contenido en bloques <div> para separar las secciones de series, películas y presentación.
3. Se debe organizar el contenido con títulos jerácquicos (<h1>, <h2> y <h3>) para mantener una estructura clara y ordenada.

## Mapa del sistio
Fichero           | title                 | Qué contiene                                   |
--------------------------------------------------------------------------------------------
index.html        |Inicio | CineVibe      | Portada, presentación de las series y pelucilas|
series.pelis.html |Series-Pelis | CineVibe| Datos generales                                |
actores.html      |Actores | CineVibe     | Los actores, sus peliculas y series            |
director.html     |Director | CineVibe    | Los directores y que dirigieron                |

## Errores y corrección:
- actores.html: abrí un <div>, que me sobrara, y la borre. 
- director.html: ningún fallo.
- datos.xml: error de esquema (documento XML sin espacio de nombres). (No entiendo el fallo, no se como solucionarlo).
- Series.pelis.html y index.html: errores de elemento