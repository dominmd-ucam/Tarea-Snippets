# Tarea-Snippets
Tareas - Tema 1. Snippets VSCode

## Introducción

Este repositorio contiene una serie de snippets HTML que se utilizan para crear una estructura básica de una página web. En el video adjunto, se muestra cómo implementar estos snippets utilizando la abreviación de Emmet `!` en un entorno de desarrollo.

## Snippets Utilizados

A continuación se detallan los snippets utilizados en el video:

### 1. Metas.html

Este snippet incluye las etiquetas `<meta>` que proporcionan información sobre la página, como la codificación de caracteres, la descripción, las palabras clave y las propiedades de Open Graph para redes sociales.

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Esta es una tarea de Interfaces.">
<meta name="keywords" content="INTERFACES WEB UCAM">
<meta name="author" content="Domingo Martinez Diaz - 2º DAW">
<meta name="robots" content="index, follow">
<meta property="og:title" content="Tarea 1 Interfaces">
<meta property="og:description" content="Este es un ejemplo de meta para redes.">
<meta property="og:image" content="/espana.png">
<meta property="og:url" content="https://dominmd-ucam.github.io/">
```

### 2. Metas Google.html

Este snippet especifica instrucciones para los motores de búsqueda sobre cómo indexar la página. En este caso, se indica que no se debe indexar.

```html
<meta name="robots" content="noindex" />
<meta name="googlebot" content="noindex" />
<meta name="googlebot-news" content="noindex" />
<meta name="slurp" content="noindex" />
<meta name="msnbot" content="noindex" />
```

### 3. Styles.html

Este snippet incluye enlaces a hojas de estilo CSS, incluyendo una hoja de estilo personalizada y Normalize.css para estandarizar estilos.

```html
<link rel="stylesheet" href="/styles.css">
<link rel="stylesheet" href="https://necolas.github.io/normalize.css/8.0.1/normalize.css">
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
```

### 4. Footer.html

Este snippet crea un pie de página con iconos de redes sociales y derechos de autor.

```html
<footer id="footer">
    <div class="social-icons">
        <a href="https://facebook.com" target="_blank"><img src="/icons/facebook.png" alt="Facebook" class="social-icon"></a>
        <a href="https://twitter.com" target="_blank"><img src="/icons/twitter.png" alt="Twitter" class="social-icon"></a>
        <a href="https://instagram.com" target="_blank"><img src="/icons/instagram.png" alt="Instagram" class="social-icon"></a>
        <a href="https://linkedin.com" target="_blank"><img src="/icons/linkedin.png" alt="LinkedIn" class="social-icon"></a>
    </div>
    <p>&copy; 2024 - Todos los derechos reservados</p>
</footer>
```

## Cómo Usar

1. Abre tu editor de código y crea un nuevo archivo HTML.
2. Escribe la abreviación de Emmet `!` y presiona `Tab` para generar la estructura básica.
3. Añade los snippets en el orden proporcionado en este README.
4. Guarda el archivo y visualiza en tu navegador para ver el resultado.

![Demostración de uso](https://imgur.com/czCjQQB)

## Conclusión

Este video y los snippets proporcionados demuestran cómo utilizar Emmet para agilizar el desarrollo de páginas web. Para más información sobre Emmet, consulta la [documentación oficial](https://emmet.io/).

