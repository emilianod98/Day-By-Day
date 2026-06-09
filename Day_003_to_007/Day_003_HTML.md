# 🏗️ ¿Qué es HTML?
**HTML** significa ***HyperText Markup Language*** (Lenguaje de Marcado de Hipertexto). Lo primero que debes saber es que no es un lenguaje de programación, porque no maneja lógica (no hace cálculos matemáticos ni toma decisiones); es un lenguaje de maquetación.
Para entenderlo de forma fácil, imagina que estás construyendo una casa:

- HTML es la estructura gruesa: las columnas, las paredes de ladrillo y los huecos para las ventanas. Es el esqueleto desnudo.
- CSS (que lo verás más adelante) será la pintura, los muebles y la decoración.
- JavaScript será el sistema eléctrico y la domótica (que las luces se enciendan solas, que el portón se abra con un botón).

En la web, HTML le dice al navegador: "Esto que sigue es un título, esto es un párrafo de texto y esto es una lista". El navegador lee ese archivo de arriba a abajo y lo dibuja en la pantalla.

## 🏷️ ¿Qué es una etiqueta y cómo funciona?
HTML funciona a base de **etiquetas (tags)**. La mayoría de las etiquetas funcionan como "llaves" que encierran un contenido: se abren, se pone el texto y se cierran.
Su estructura es la siguiente:

```
<etiqueta> El contenido va aquí </etiqueta>
```
⚠️ Nota la diferencia: La etiqueta de apertura lleva piquitos < > y la de cierre lleva una barra inclinada antes del nombre </ >.

## 📝 Las Etiquetas que vas a dominar Hoy (Día 3)
Para tu archivo `textos.html` de hoy, vas a utilizar este arsenal de etiquetas:

### 1. El Esqueleto Obligatorio (La estructura base)
Todo documento HTML debe tener esta estructura para que el navegador sepa qué está leyendo:

- `<!DOCTYPE html>:` Le avisa al navegador que estás usando la versión más moderna de HTML (HTML5).
- `<html>:` Es la etiqueta raíz. Todo tu código debe vivir dentro de ella.
- `<head>:` Es la "mente" de la página. Aquí va información que el usuario no ve directamente (como el título de la pestaña del navegador o configuraciones de idioma).
- `<body>:` Es el "cuerpo". Todo lo que metas aquí adentro es lo que realmente se va a renderizar en la pantalla del usuario.

### 2. Títulos y Encabezados (`<h1> al <h6>`)
Sirven para jerarquizar la importancia de los textos.

- `<h1>` es el título principal de la página (solo debe haber uno por archivo).
- `<h2>` son los subtítulos, `<h3>` los sub-subtítulos, y así hasta llegar al `<h6>`, que es el más pequeño. El navegador los muestra automáticamente en negrita y con diferentes tamaños.

### 3. Párrafos (`<p>`)
Es la etiqueta más usada para bloques de texto normal. Cada vez que abres y cierras un `<p>`, el navegador entiende que termina un párrafo y da un salto de línea automático para el siguiente.

### 4. Estilos de Texto (`<strong> y <em>`)
Se usan dentro de los párrafos para resaltar palabras específicas:

- `<strong>:` Tradicionalmente hace que el texto se vea en negrita, pero su función real es decirle al buscador que esa palabra tiene mucha importancia visual o conceptual.
- `<em> (emphasis):` Hace que el texto se curve en cursiva. Sirve para dar un énfasis de tono a una palabra.

### 5. Listas (`<ul>, <ol> y <li>`)
Para cuando necesitas ordenar ideas en viñetas o números:

- Listas Desordenadas (`<ul>`): Viene de Unordered List. Muestra los elementos con puntitos (viñetas).
- Listas Ordenadas (`<ol>`): Viene de Ordered List. Muestra los elementos numerados (1, 2, 3...).
- Elementos de Lista (`<li>`): Viene de List Item. Es la etiqueta que encierra a cada uno de los elementos de la lista, y siempre deben vivir adentro de un `<ul>` o un `<ol>`.