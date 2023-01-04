# Formato de texto

**< p>** Este elemento representa un párrafo. Por defecto los navegadores le asignan un margen en la parte superior para separar un párrafo de otro. Se utiliza ampliamente para representar el cuerpo del texto.

```HTML
<p>Este es un parrafo</p>
```

**< pre>** Este elemento representa un texto con formato predefinido.

```HTML
    <pre> Este es un texto predefinido,
          a diferencia del parrafo este respeta la forma en la que se ha dejado
          el texto
    </pre>
```

**< wbr>** Este elemento sugiere la posibilidad de un salto de línea para ayudar al navegador a decidir dónde cortar el texto cuando no hay suficiente espacio para mostrarlo entero.

**< em>** Este elemento se usa para indicar énfasis. El texto se muestra por defecto con letra cursiva.

```HTML
<p> Se usa para dar <em>énfasis</em> </p>
```

**< strong>** Este elemento se utiliza para indicar importancia. El texto se muestra por defecto en negrita.

```HTML
<p>Se usa para dar<strong>importancia</strong></p>
```

**< i>** Este elemento representa una voz alternativa o un estado de humor, como un pensamiento, un término técnico. El texto se muestra por defecto en cursiva.

```HTML
<p>Se usa para un<i>termino técnico</i></p>
```

**< u>** Este elemento representa texto no articulado. Por defecto se muestra subrayado.

```HTML
<p>Texto no<u>articulado</u></p>
```

**< b>** Este elemento se usa para indicar importancia. Debería ser implementado solo cuando ningún otro elemento es apropiado para la situación. El texto se muestra por defecto en negrita.

```HTML
<p>Se usa para dar<b>importancia</b></p>
```

**< mark>** Este elemento resalta texto que es relevante en las circunstancias actuales.

**< small>** Este elemento representa letra pequeña, como declaraciones legales, descargos, etc.

**< cite>** Este elemento representa el autor o título de una obra, como un libre, una película, etc.

**< address>** Este elemento representa información de contacto. Se implementa con frecuencia dentro de los pies de página para definir la dirección de la empresa o el sitio web.

**< time>** Este elemento representa una fecha en formato legible para el usuario. Incluye el atributo ***datetime***  para especificar un valor en formato de ordenador y el atributo ***pubdate***, el cual indica que el valor asignado al atributo ***datetime***, representa la fecha de publicacion.

**< code>** Este elemento representa código de programación. Se usa en conjunto con el elemento **< pre>** para presentar código de programación en el formato original.

**< data>** Este elemento representa datos genéricos.

**< download>** Este es un atributo booleano que, cuando se incluye, indica que en lugar de leer el archivo el navegador debería descargarlo.

**< blockquote>** Este elemento representa un bloque de texto que incluye una cita tomada de otro texto en el documento.

**< details>** Este elemento crea una herramienta que se expande cuando se hace clic en ella para mostrar información adicional. La parte visible se define con el elemento **< summary>**.

## Listados

**< ul>** Este elemento crea una lista sin orden, trabaja junto con el elemento **< li>** para definir cada uno de los ítems de la lista.

```HTML
    <ul>
        <li>Capítulo 1</li>
        <li>Capítulo 2</li>
        <li>Capítulo 3</li>
    </ul>
```

**< ol>** Este elemento crea una lista ordenada de ítems. Este puede incluir los atributos *reversed* para invertir el orden de los indicadores, *start* para determinar el valor desde el cual los indicadores tienen que comenzar a contar y *type* para determinar el tipo de indicador que queremos usar.

```HTML
    <ol>
        <li>Agradecimientos</li>
        <li>Introduccion</li>
        <li>Indice</li>
    </ol>

    <ol type="A">
        <li>Agradecimientos</li>
        <li>Introduccion</li>
        <li>Indice</li>
    </ol>
```

[Volver &ldca;](../README.md)
