# Cabeceras

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines

Underline 1
-----------

Underline 2
===========

# Formatos de énfasis

- formato *itálica* de la primer forma.
- formato _itálica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aquí podemos usar *formato itálico*, pero también **bold** y ~~tachado~~.
 
# Listas

 1. Esto es un ítem de lista ordenada.
 2. Esto es un ítem de lista ordenada.
 3. Esto es un ítem de lista ordenada.

 - Esto es un ítem de lista desordenada.
 - Esto es un ítem de lista desordenada.
 - Esto es un ítem de lista desordenada.
 
# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link en index](index.html)

# Imágenes
![Logo github](https://www.startpage.com/av/proxy-image?piurl=https%3A%2F%2Fgithub.githubassets.com%2Fimages%2Fmodules%2Fopen_graph%2Fgithub-mark.png&sp=1595180197T0e33ded2f4510e721bfd4113a9cfdc7849d5062f0b634f1b641b5b9d1fee1082)

# Code Snippets
Código en JSON
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
código en Javascript
```Javascript
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
# Tablas
| Nombre | Apellidos | Documento |
|-|-|-|
| Maxi | Burgos | 234155 |
| Tomas | Tompson | 314532452 |

# Citas
Esto es un texto referente a una cita que pondremos debajo: 
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita

# Lineas divisoras
Esto es un texto que será dividido por guiones medios

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guipnes bajos
___

# Saltos de linea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.