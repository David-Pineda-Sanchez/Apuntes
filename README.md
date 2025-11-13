# Mis Apuntes de Clase



## 1. GitHub

Es la página web (plataforma) donde subimos nuestros repositorios de Git.
* Sirve como una **copia de seguridad** en la nube.
* Permite **colaborar** con otra gente en el mismo proyecto.
* Sirve para mostrar tus proyectos (como un portfolio).
* Tiene **GitHub Pages**, que es lo que usamos para publicar el horario (páginas web estáticas gratis).


## 2. Git

Es el **programa** que usamos en la terminal para guardar "fotos" (versiones) de nuestro código. Es un sistema de control de versiones.

### Comandos básicos

* `git init`: Empieza un repositorio nuevo en una carpeta.
* `git add .`: Prepara todos los archivos nuevos/modificados para la "foto".
* `git commit -m "Mi mensaje"`: Hace la "foto" (guarda los cambios) con un mensaje.
* `git push`: Sube tus commits a GitHub.
* `git pull`: Baja los cambios que estén en GitHub a tu ordenador.


## 3. Markdown (.md)

Es un lenguaje de marcas simple para escribir texto con formato, como este mismo archivo. Los archivos se guardan con la extensión `.md`.

* **Encabezados:** Se usan para títulos. Se ponen con `#`.
    ```markdown
    # Título 1
    ## Título 2
    ### Título 3
    ```
* **Estilos de letra:**
    * `**Negrita**` (así se pone en negrita).
    * `*Cursiva*` (así se pone en cursiva).
* **Listas:**
    ```markdown
    - Un punto de la lista
    - Otro punto
    
    1. Un elemento numerado
    2. Otro elemento
    ```
* **Enlaces:**
    ```markdown
    [Texto que se ve](https://www.google.com)
    ```
* **Bloques de código:**
    ```html
    <p>Así se pone un bloque de código</p>
    ```


## 4. HTML

Es un **lenguaje de marcas** (no de programación) que le dice al navegador qué contenido poner y cómo estructurarlo.

### Estructura Básica

Toda la página se mete en `<html>`. Se divide en dos partes:

* `<head>`: Contiene cosas que no se ven, como metadatos, el título de la pestaña (`<title>`) y los enlaces a CSS (`<link>`) o JS (`<script>`).
* `<body>`: Contiene todo lo que se ve en la página (títulos, texto, imágenes...).

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>El título de la pestaña</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1>Hola mundo</h1>
        <p>Este es el contenido.</p>
    </body>
</html>
Elementos de Bloque vs. Línea
Bloque: Ocupan todo el ancho y empiezan en una línea nueva.

Ejemplos: <h1>, <p>, <div>, <br>, <hr>.

Línea: Ocupan solo lo necesario y se ponen uno al lado del otro.

Ejemplos: <strong>, <em>, <span>, <code>.

Etiquetas comunes
<h1>...<h6>: Títulos y subtítulos.

<p>: Párrafo.

<br>: Salto de línea.

<hr>: Línea horizontal de separación.

<strong>: Para negrita (importante).

<em>: Para cursiva (énfasis).

<span>: Contenedor en línea, para agrupar texto.

Listas
<ul>: Lista desordenada (con puntos).

<ol>: Lista ordenada (con números).

<li>: Cada elemento de la lista.

Rutas (para enlazar)
Para enlazar imágenes o CSS.

Absoluta: La URL completa (empieza por https://...). Para webs externas.

Relativa: La ruta desde nuestro archivo (ej. images/foto.png). Para nuestro propio proyecto.

Contenedores (Cajas)
<div>: Es una "caja" o contenedor en bloque. Sirve para organizar y aplicar estilos, pero no significa nada.

HTML Semántico: Son etiquetas que sí tienen significado y describen el contenido. Esto es mejor para SEO y accesibilidad.

Ejemplos: <header>, <footer>, <nav>, <main>, <section>, <article>.

Formularios
<form>: Envuelve todo el formulario.

action: La web que recibe los datos.

method: Cómo se envían (GET o POST).

<input>: El campo para rellenar.

type: El tipo de campo (text, password, checkbox, radio, file, submit...).

placeholder: Texto de ayuda que se borra al escribir.

required: Hace que el campo sea obligatorio.

<button>: Un botón (puede ser type="submit").

Comentarios
Son notas para el programador que el navegador no muestra.

Validación
Sirve para comprobar que nuestro HTML está bien escrito y sigue los estándares de la W3C.

Se usa la web: validator.w3.org.
