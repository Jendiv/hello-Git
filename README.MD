# Cabeceras:
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines:

Underline 1 (-)
-------------

Underline 2 (=)
============

# Formatos de énfasis:

- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold** o __strong__.
- formato ~~tachado~~.
- Prueba de que usamos *italica*, usamos **bold** y usamos ~~tachado~~ todo en un mismo texto.

# Listas:
### Lista ordenada:
1. Item 1.
2. Item 2.
3. Item 3.
4. Item 4.

### Lista desordenada:
- Item.
- Item.
- Item.
- Item.

# Links:
- <a href="#">Esto es un link formato HTML</a>

- [Esto es un link en Markdown](hhttp://www.google.es)

- [Esto es un link al index](index.html)

# Imágenes:
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets:
(highlight.js)
- Código en JSON

```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
- Código en JavaScript
```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas:

| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Max | Burgos | 0000000 |
| Ella | Lopez | 1111111 |
 
# Citas:

Esto es un texto referente a una cita:
>Esto es una cita.

Si damos doble enter podemos escribir fuera de la cita.
>Esto es otra cita.

# Lineas Divisorias:
Esto es un texto dividido.

---
Se necesita espaciar con enter el texto de los guiones o se interpretará como underline. También se puede hacer con asteriscos

***

O también podemos con barra baja, siempre 3

___

# Saltos de línea:

Esto es el primer parrafo.

Esto es el segundo parrafo.
(si no damos enter la línea continua, si damos enter se separan. )


Esto es el tercer parrafo.




