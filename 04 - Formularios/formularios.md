# Formularios

Los formularios son herramientas que podemos incluir en un documento para permitir a los usuarios insertar información, tomar decisiones, comunicar datos y cambiar el comportamiento de una aplicación.

**Method** Este atributo determina el método a utilizar para enviar la información al servidor. Existe dos valores disponibles: *GET* y *POST*.

**Action** este atributo declara la URL del archivo en el servidor que va a procesar la información enviada por el formulario.

**Target** Este atributo determina donde se mostrará la respuesta recibida desde el servidor.

**Enctype** Este atributo declara la codificación aplicada a los datos que envía el formulario.

## Elementos

Un formulario puede incluir diferentes herramientas para permitir al usuario seleccionar o insertar información.

**< input>** Este elemento crea un campo de entrada. Puede recibir diferentes tipos de entra, dependiendo del valor del atributo *type*, para ver más de click al siguiente enlace [input](../06%20-%20Inputs/inputs.md).

 ```HTML
    <input type="text" name="tarea" placeholder="ingrese tarea">
```

**< textarea>** Este elemento crea un campo de entrada para insertar múltiples líneas de texto.

**< select>** Este elemento crea una lista de opciones que el usuario puede elegir. Trabaja junto con el elemento **< option>** para definir cada opción y el elemento **< optgroup>** para organizar las opciones en grupos.

 ```HTML
    <select name="lugares" id="lugares">
    <option value="Norte" disabled>Norte</option>
    <option value="Centro">Centro</option>
    <option value="Sur">Sur</option>
    </select>
```

**< button>** Este elemento crea un botón. Incluye el atributo *type* para definir el propósito del botón. Los valores disponibles son *submit* para enviar el formulario, *reset* para reiniciar el formulario, y *button* para realizar tareas personalizadas.

 ```HTML
        <button>Click here</button>
```

**< output>** Este elemento representa un resultado producido por el formulario. Se implementa por medio de código JavaScript para mostrar el resultado de una operación al usuario.

**< meter>** Este elemento representa una medida o el valor actual de un rango.

**< progress>** Este elemento representa el progreso de una operación.

**< datalist>** Este elemento crea un listado de valores disponibles para otros controles. Trabaja junto con el elemento **< option>** para definir cada valor.

**< label>** Este elemento crea una etiqueta para identificar un elemento de formulario.
 ```HTML
    <label for="work">Tarea</label>
    <input type="text" id="work" name="tarea" placeholder="ingrese tarea">
```

**< fieldset>** Este elemento agrupa otros elementos de formulario. Se usa para crear secciones dentro de formularios extensos. El elemento puede contener un elemento **< legend>** para definir el título de la sección.

 ```HTML
         <fieldset>
            <legend>Inputs</legend>
        </fieldset>
```

Para incluir un formulario en nuestro documento, tenemos que declararlo con el elemento **< form>**, y luego incorporar en su interior todos los elementos que el usuario necesitara para insertar la información y enviar al servidor.


[Volver &ldca;](../README.md)