# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underline 1
-----------
Underline 2
===========

# Formatos de enfasis
- Formato *italica* de la primera forma.
- Formato _italica_ de la segunda forma.
- Formato **bold o strong** de la primera forma.
- Formato __bold o strong__ de la segunda forma.
- Formato ~~tachado~~.
- Aquí podemos usar *formato italico*, pero tambien **_~~italico bold y tachado.~~_**

# Listas
1. Esto es un  ordenada.
2. Esto es un  ordenada.
3. Esto es un  ordenada.
- Esto es un  ordenada.
- Esto es un  ordenada.
- Esto es un  ordenada.

# Links
- <a href="https://github.com/alfredolopeznunes">Esto es un link HTML</a>
- [Esto es un link en Markdown](https://github.com/alfredolopeznunes)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Perfil](https://avatars2.githubusercontent.com/u/62631538?s=250&u=ac8fc6f2ec83e4392a1c2e748e79f0cff1563fe8&v=4)

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
Código en JavaScript
```javascript
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
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Alfredo| López    | 26312152  |
| Chelsy | López    | N/A       |

# Citas
Esto es una referencia a una cita:
> Esto es una cita.

dos enter para salir de la cita.
> Solo con el mayor que.

# Líneas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto divido por asterisco.

***
Esto es otro texto divido por asterisco.

___

# Saltos de línea
Esto nuestro primer parrafo.

Esto nuestro segundo parrafo.

Esto nuestro tercer parrafo.
- Lista