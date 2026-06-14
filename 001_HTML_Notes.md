# 🏗️ 1. ¿Qué es HTML realmente?
HTML significa **HyperText Markup Language** (Lenguaje de Marcado de Hipertexto). Lo primero que debes saber (y que te dará estatus de profesional) es que HTML no es un lenguaje de programación. No tiene lógica, no hace cálculos matemáticos ni toma decisiones.

HTML es un lenguaje de marcado. Sirve para definir la estructura y el contenido de una página web mediante el uso de etiquetas. Piensa en HTML como los planos y los ladrillos de una casa; más adelante, CSS se encargará de la pintura y la decoración, y JavaScript de la electricidad y la plomería.

## 🏷️ 2. La Anatomía de una Etiqueta
Casi todo en HTML se construye con etiquetas que encierran un contenido. La estructura típica se ve así:

```
<etiqueta>Contenido que se muestra en la pantalla</etiqueta>
```

- `<etiqueta>`: Es la etiqueta de apertura. Le dice al navegador dónde empieza el elemento.
- `</etiqueta>`: Es la etiqueta de cierre. Lleva una barra diagonal (/) y le dice al navegador dónde termina el elemento.

⚠️ Nota importante: Existen excepciones. Algunas etiquetas son "autofinalizables" o vacías (no encierran texto, solo insertan algo), por lo que no llevan etiqueta de cierre (como `<br>` para saltos de línea o `<img>` para imágenes).

## 💀 3. El Esqueleto Estándar (La Anatomía del Documento)
Cualquier página web del mundo, desde Google hasta la que vas a programar hoy, empieza obligatoriamente con la misma estructura base. Abre tu editor de código (como Visual Studio Code) y mira este bloque:

```
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página Web</title>
</head>
<body>
    </body>
</html>
```

Explicación línea por línea para que lo entiendas al 100%:

- `<!DOCTYPE html>`: Le avisa al navegador que estás usando la versión más moderna de HTML (HTML5).
- `<html lang="es">`: Es la raíz de todo el documento. El atributo lang="es" le dice a los motores de búsqueda que tu web está en español.
- `<head>`: Es la "cabeza" de la página. Todo lo que pongas aquí no se ve en la pantalla principal. Sirve para configuraciones, configurarle el idioma al navegador o conectarla con archivos externos.
- `<meta charset="UTF-8">`: Configura el juego de caracteres. Esto garantiza que los acentos, la "ñ" y los caracteres especiales se lean correctamente y no aparezcan símbolos raros.
- `<meta name="viewport" content="...">`: Es la configuración para que la página sea responsiva. Le dice al navegador que adapte el tamaño del contenido según si se abre en una PC, una tablet o un celular.
- `<title>`: Es el nombre que aparece arriba, en la pestaña del navegador.
- `<body>`: El "cuerpo". Aquí sucede la magia. Todo lo que metas dentro de estas etiquetas es lo que el usuario final podrá ver y leer en la pantalla.

## 📝 4. Etiquetas de Texto y Jerarquía