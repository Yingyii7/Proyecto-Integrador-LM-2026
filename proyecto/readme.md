## Parte 1:
Proyecto Web: Web de Películas
Nombre del estudiante: Yingyi Li Pan
Usuario de GitHub: Yingyii7
Módulo: Lenguajes de Marcas y Sistemas de Gestión de Información (1º DAM, curso 2026/2027)

Tema elegido:
El tema principal de este proyecto es una web de películas.

¿Por qué he elegido este tema?
Personalmente me gusta mucho pasar tiempo con mi familia o con amigos viendo una película graciosa o de miedo en algunas ocasiones. Considero que es una temática ideal para este proyecto, ya que ofrece un campo de temas muy amplio y entretenido para estructurar datos, redactar contenidos y desarrollar la web a lo largo de este curso. 

*Palabra del día: dia*
 
Qué he hecho en esta entrega:
En esta entrega he estructurado el proyecto integrador creando un sitio web básico con HTML (index.html) y un catálogo estructurado con XML (datos.xml). He incluido secciones
sobre mis películas y series recomendadas con imágenes y formateo de texto, además de organizar los datos equivalentes en XML respetando todas las reglas de sintaxis e incluyendo atributos propios. He incluido datos sobre 3 películas y 3 series populares, como los protagonistas principales, su fecha de estreno y otros.

## «UD3 · Estructura HTML» 

Cosas que le faltan a mi index.html inicial:
1. Faltan metadatos adicionales dentro de <head>, como una descripción de la página.
2. Falta orgnizar el contenido en bloques <div> para separar las secciones de series, películas y presentación.
3. Se debe organizar el contenido con títulos jerácquicos (<h1>, <h2> y <h3>) para mantener una estructura clara y ordenada.

## Mapa del sistio
|     Fichero      |          title          |                   Qué contiene                  |
|------------------|-------------------------|-------------------------------------------------|
|index.html        |Inicio      \| CineVibe  | Portada, presentación de las series y pelucilas |
|series.pelis.html |Series-Pelis\| CineVibe  | Datos generales                                 |
|actores.html      |Actores     \| CineVibe  | Los actores, sus peliculas y series             |
|director.html     |Director    \| CineVibe  | Los directores y que dirigieron                 |
|contacto.hmtl     |Contacto    \| CineVibe  | Custionario para el usuario                     |

## Errores y corrección:
- actores.html: ningún fallo.
- director.html: ningún fallo.
- datos.xml: ningún fallo.
- Series.pelis.html: ningñun fallo.
- index.html: nigún fallo.
- contacto.html: 
    - error líneas 52, 54, 77: poner - en vez de poner espacios en blancos.
    - error líneas 79, 82: el id tiene que ser igual al que pone en el for.
    - error líneas 64, 77, 90: usar <span> en vez de <Label>, porque sirve para texto normal y no una entrada interactivo.

## UD5 · Tablas y formularios
La URL del cuestionario cuando lo cambio a "get": http://127.0.0.1:5500/proyecto/contacto.html?nombre=yingyi&email=jennyingyi7%40gmail.com&telefono=652946697&edad=19&serie_favorita=Off-campus&plataforma=Amazon+Prime&opinion=Genial&comentario=hola+mundo# 

¿Por qué usamos "post" en vez de "get"?
Los datos introducidos en el formulario, son datos personales. Si usamos "get" los datos del cuestionario se publica en la barra de direcciones de la URL. En caso de usar "post" los oculta. Por eso usamos "post" y no "get".

¿Qué he hecho en esta unidad?
En esta unidad he aprendido a hacer formularios, donde puedes hcaer unas series de preguntas para informarte del usuario, como por ejemplo el nombre, el telefono, y otros datos personales, en los cuales podria ser de tipo "get" (te sale los datos en la URL) o en "post" (losn datos no se va a publicar). Además, también aprendí otros comandos para mejorar la tabla de información.