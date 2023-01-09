# Elementos estructurales

**< HTML>** Este elemento delimita el código HTML.

```HTML
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML</title>
</head>
<body>
    
</body>
</html>
```

**< Head>** Este elemento se usa para definir la información necesaria para configurar la página web.

```HTML
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML</title>
</head>
```

**< body>** Este elemento delimita el contenido del documento.

```HTML
<body>
    
</body>
```

**< title>** Este elemento define el título de la página.

```HTML
    <title>HTML</title>
```

**< base>** Este elemento define la URL relativas.

**< meta>** Este elemento representa metadatos asociados con el documento, como la descripción del documento, palabras claves, etc.

```HTML
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
```

**< link>** Este elemento especifica la relación entre el documento y un recurso externo (generalmente usado para cargar archivos CSS).

```HTML
    <link rel="stylesheet" href="style.css">
```

Un ejemplo de *link* es para poner el icono que se muestrsa cuando abrimos una ventana en el navegador:

```HTML
<link rel="icon" href="image/nav.png" type="image/png" sizes="16x16">
```

**< style>** Este elemento se usa para declarar estilos CSS dentro del documento.

```HTML
<style> body{background: yellow;} </style>
```

**< scrip>** Este elemento se usa para cargar o declarar código JavaScript. más adelante se hablara de JavaScript [link](https://hydr0bius.github.io/coming-soon/).

```HTML
    <script> alert("No disponible") </script>
```

**< div>** Este elemento define una división genérica. Se usa cuando no se puede aplicar ningún otro elemento.

```HTML
    <div></div>
```

**< main>** Este elemento define una división que contiene el contenido principal del documento.

```HTML
    <main></main>
```

**< nav>** Este elemento define una división que contiene ayuda para la navegación, como el menú principal de la página o bloques de enlaces necesarios para navegar en el sitio web.

```HTML
    <nav></nav>
```

**< section>** Este elemento define una sección genérica, se usa frecuentemente para separar contenido temático, o para generar columnas o bloques que ayudan a organizar el contenido principal.

```HTML
    <section></section>
```

**< aside>** Este elemento define una división que contiene información relacionada con el contenido principal pero que no es parte del mismo, como referencias a artículos o enlaces que apuntan a publicaciones anteriores.

**< article>** Este elemento representa un artículo independiente, como un mensaje de foro, el artículo de una revista, una entrada de un blog, un comentario, etc.

**< header>** Este elemento define la cabecera del cuerpo o de secciones dentro del cuerpo.

 ```HTML
    <header></header>
```

**< footer>** Este elemento define el pie del cuerpo de secciones dentro del cuerpo.

 ```HTML
    <footer></footer>
```

**< span>** Este elemento puede contener un párrafo, una frase o una palabra. No aplica ningún estilo al texto, pero se usa para asignar estilos personalizados.

**< br>** Este elemento se usa para insertar saltos de línea.

**< a>** Este elemento crea un enlace. El texto o la imagen que representa el enlace se incluye entre las etiquetas de apertura y cierre.

 ```HTML
    <a href="#">Home</a>
```

Los enlaces se pueden crear para conectar el documento actual con otros documentos en el mismo sitio web o en otros sitios.

Al elemento **< a>** se le puede incluir el atributo **target** para especificar el destino en el cual el documento será abierto.

 ```HTML
    <a href="#" target="_blank">Home</a>
```

*_self* Se asigna por defecto, abre el documento en la misma ubicación que el documento actual.

*_blank* El documento se abre en una nueva ventana.

*_parent* El documento se abre en el recuadro padre.

*_top* El documento se abre en la ventana actual.

![body](../image/body.JPG)

[Volver &ldca;](../README.md)
