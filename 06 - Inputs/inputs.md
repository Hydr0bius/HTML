# Input

El elemento **< input>** es el más versátil de todos. Este elemento genera un campo de entrada en el que el usuario puede seleccionar o insertar información, pero puede adoptar diferentes características y aceptar varios tipos de valores dependiendo del valor de su atributo *type*.

**Text** Este valor genera un campo de entrada para insertar texto genérico.

**Email** Este valor genera un campo de entrada para insertar cuentas de correo.

**Search** Este valor genera un campo de entrada para insertar términos de búsqueda.

**url** Este valor genera un campo de entrada para insertar URL

**tel** Este valor genera un campo de entrada para insertar números de teléfono.

**Number** Este valor genera un campo de entrada para insertar números.

**Range** Este valor genera un campo de entrada para insertar un rango de números.

**Date** Este valor genera un campo de entrada para insertar una fecha

**datetime-local** Este valor genera un campo de entrada para insertar fecha y hora.

**Week** Este valor genera un campo de entrada para insertar el número de la semana.

**Month** Este valor genera un campo de entrada para insertar el número del mes.

**Time** Este valor genera un campo de entrada para insertar una hora.

**Hidden** Este valor oculta el campo de entrada. Se usa para enviar información complementaria al servidor.

**Password** Este valor genera un campo de entrada para insertar una clave. Reemplaza los caracteres insertados con estrellas o puntos para ocultar información sensible.

**Color** Este valor genera un campo de entrada para insertar un color.

**Checkbox** Este valor genera una casilla de control que permite al usuario activar o desactivar una opción.

**Radio** Este valor genera un botón de opción para seleccionar una opción de varias posibles.

**File** Este valor genera un campo de entrada para seleccionar un archivo en el ordenador del usuario.

**Button** Este valor genera un botón. El botón trabaja como el elemento **< button>** de tipo button. No realizada ninguna acción por defecto; la acción debe ser definida desde JavaScript.

**Submit** Este valor genera un botón para enviar el formulario.

**Reset** Este valor genera un botón para reiniciar el formulario.

**Image** Este valor carga una imagen que se usa como botón para enviar el formulario. Un elemento **< input>** de este tipo debe incluir el atributo *src* para especificar la URL de la imagen.

---
Para determinar cuántos caracteres se puede introducir, el elemento **< input>** debe incluirse los siguientes atributos;

**Maxlength** Este atributo especifica el máximo número de caracteres que se permite introducir en el campo.

**Minlength** Este atributo especifica el mínimo número de caracteres que se permite introducir en el campo.

---
Para establecer restricciones en los números podemos utilizar los siguientes atributos;

**Min** El valor de este atributo determina el valor mínimo que acepta el campo.

**Max** El valor de este atributo determina el valor máximo que acepta el campo.

Step El valor de este atributo determina el número por el cual el valor del campo se puede incrementar o reducir. Por ejemplo, si declaramos el valor 5 para este atributo y un valor mínimo de 0 y máximo de 10 para el campo, el navegador no nos dejará introducir valores entre 0 y 5 o 5 y 10.

**Range** Crea un campo que nos permite seleccionar un número desde un rango de valores.

[Volver &ldca;](../README.md)