# HTML
Lenguaje de marcado de texto, es la parte que nos permite estructurar nuestra pagina web, 
es como el esqueleto de nuestra apicacion .
Su principal objetivo es darle formato semantico a nuestra informacion a travez de uso 
de 'elementos' que esta a su vez esta conformado por 'etiquetas' de apertura y cierre y 'contenido'
>[!TIP] En algunos casos encontraremos los 'elementos' huerfano estos solo estan conformados
por una sola etiqueta.

## Tarea Estructura de un elemento en HTML


## Estructura fundmental del documento HTML 
- <!DOCTYPE html> - Declaramos el tipo de documento, este elemento huerfano indica al navegador 
que el documento con el que se esta trabajando y que debera renderizar es 'html',
**siempre debe estar en la primera linea**
- '<html></html>' - Elemento raiz, envuelve todo el contenido de la pagina HTML, este elemento tiene 
dos hijos principales.
- '<head></head>' -Elemento de configuracion, contiene informacion importante sobre el documento como
(titulo,enlaces css, informacion para motores de busqueda, descripcion entre otros).
 - '<title></title>' - Elemento de titulo de pagina, es el hijo de 'head' y define el titulo
que aparecera en la pestaña del navegador
- '<body></body>' -

##  TAREA: estructura de contenido semantico (seccion principales)

# HTML

Lenguaje de marcado de texto, es la parte que nos permite estructurar nuestra página web,  
es como el esqueleto de nuestra aplicación.

Su principal objetivo es darle formato semántico a nuestra información a través del uso  
de elementos, los cuales están conformados por etiquetas de apertura, cierre y contenido.

> [!TIP]
> En algunos casos encontraremos elementos huérfanos, estos solo están conformados
> por una sola etiqueta.

---

# Estructura de contenido semántico (secciones principales)

Las etiquetas semánticas permiten organizar correctamente el contenido de una página web.  
Ayudan al navegador y a los motores de búsqueda a comprender la función de cada sección.

## Etiquetas semánticas principales

### `<header></header>`
Representa la cabecera de la página o de una sección.  
Generalmente contiene el logo, título y menú principal.

### `<nav></nav>`
Define la sección de navegación del sitio web.  
Contiene enlaces o menús principales.

### `<main></main>`
Contiene el contenido principal del documento HTML.  
Solo debe existir un `main` por página.

### `<section></section>`
Agrupa contenido relacionado dentro de una misma sección temática.

### `<article></article>`
Representa contenido independiente como noticias, publicaciones o artículos.

### `<aside></aside>`
Contiene información complementaria o secundaria, como publicidad o enlaces relacionados.

### `<footer></footer>`
Representa el pie de página.  
Generalmente contiene información de contacto, derechos de autor o redes sociales.
---


---

# TAREA:Estructura de texto

Las etiquetas de texto permiten organizar y dar formato al contenido de una página web.

---

# Jerarquía de encabezados

Los encabezados permiten organizar la información según su importancia.  
Existen desde `<h1>` hasta `<h6>`.

| Etiqueta | Función |
|---|---|
| `<h1>` | Título principal |
| `<h2>` | Subtítulo |
| `<h3>` | Sección |
| `<h4>` | Subsección |
| `<h5>` | Detalle |
| `<h6>` | Nota final |

## Ejemplo

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Sección</h3>
<h4>Subsección</h4>
<h5>Detalle</h5>
<h6>Nota final</h6>
```

---

# Párrafos y énfasis

Los párrafos se crean con la etiqueta `<p>`.  
Para resaltar texto se utilizan:
- `<strong>` → negrita
- `<em>` → cursiva

| Etiqueta | Función |
|---|---|
| `<p>` | Crear párrafos |
| `<strong>` | Resaltar texto importante |
| `<em>` | Dar énfasis al texto |

## Ejemplo

```html
<p>Este es un párrafo.</p>

<p>
    Este texto es <strong>importante</strong> y este es
    <em>enfatizado</em>.
</p>
```

---

# Listas

Las listas permiten organizar información.

| Etiqueta | Función |
|---|---|
| `<ul>` | Lista desordenada |
| `<ol>` | Lista ordenada |
| `<li>` | Elemento de lista |

## Ejemplo

```html
<ul>
    <li>Arroz</li>
    <li>Pollo</li>
    <li>Verduras</li>
</ul>

<ol>
    <li>Lavar ingredientes</li>
    <li>Cocinar</li>
    <li>Servir</li>
</ol>
```

---

# Citas y referencias

Permiten mostrar citas y autores o referencias.

| Etiqueta | Función |
|---|---|
| `<blockquote>` | Mostrar citas |
| `<cite>` | Mostrar referencias |

## Ejemplo

```html
<blockquote>
    "La cocina es el corazón del hogar."
</blockquote>

<cite>Recetas Peruanas</cite>
```

---

# Código y texto técnico

Se utilizan para mostrar código HTML y conservar formatos de texto.

| Etiqueta | Función |
|---|---|
| `<code>` | Mostrar código |
| `<pre>` | Mantener espacios y saltos |

## Ejemplo

```html
<p>Etiqueta de párrafo: <code><p></code></p>

<pre>
Ingredientes:
- Arroz
- Pollo
- Verduras
</pre>
```

---

# Líneas y saltos

Permiten separar contenido y realizar saltos de línea.

| Etiqueta | Función |
|---|---|
| `<hr>` | Línea horizontal |
| `<br>` | Salto de línea |

## Ejemplo

```html
<hr>

<p>
Nombre: Nancy <br>
Curso: HTML <br>
Tema: Estructura de Texto
</p>
```

---

# Ejemplo práctico integrador

## Descripción

En la carpeta raíz se debe crear una carpeta llamada:

```txt
ejercicio_01
```

Dentro de esta carpeta se debe crear el archivo:

```txt
index.html
```

En este archivo se desarrollará un ejemplo práctico integrador utilizando todas las etiquetas trabajadas anteriormente.
El tema del ejemplo será una receta de cocina.