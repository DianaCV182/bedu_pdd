[`Procesamiento de Datos con Python`](../Readme.md) > `Sesión 3`

## Sesión 03: Programación funcional y Operadores Lógicos

<img src="../imagenes/pizarron.png" align="right" height="100" width="100" hspace="10">

### 1. Objetivos :dart:

1. Usar dos funciones representativas de la programación funcional: `map` y `filter`.
2. Utilizar operadores lógicos combinar dos condiciones o más.
3. Conocer la sintaxis de las funciones `lambda` para simplificar la definición de algunas funciones y/o fragmentos de código.

### 2. Contenido :blue_book:

---

#### <ins>Programación Funcional</ins>

Aprendimos en el Prework que la `programación funcional` es un paradigma de programación. Este paradigma permite usar a las funciones como cualquier otro valor en el lenguaje. En particular, las funciones pueden:

1. Recibir otras funciones como parámetro.
2. Devolver funciones como resultado.
3. Almacenar funciones en estructuras de datos (como una lista, por ejemplo).

En este curso no profundizaremos mucho en estos conceptos de la `programación funcional`, pero vamos a aprender a usar dos de sus funciones más comunes: `map` y `filter`. ¿Por qué? Porque la manera como funcionan es de gran utilidad a los científicos de datos.

Entendiendo `map` y `filter` al 100 te será más fácil aproximarte a las funciones universales en `numpy` y `pandas` y a cómo funcionan sus filtros.

¡Vamos adelante!

---

#### <ins>Mapeos</ins>

La primera función que vamos a aprender es la función `map`. Esta función toma una función como entrada y una lista y nos regresa una nueva lista donde la función a sido aplicada a cada elemento de la lista original:

```python
> numeros = [1,2,3,4,5,6,7,8,9,10]

> list(map(multiplica_por_2,numeros))
[2,4,5,8,10,12,16,18,20]
```

Veamos cómo funciona.

[**`Ejemplo 1`**](Ejemplo-01/map.ipynb)
[**`Reto 1`**](Reto-01/map.ipynb)

---

#### <ins>Filtros</ins>

Nuestra segunda función se llama `filter`. Tal y como su nombre lo dice, `filter` nos ayuda a filtrar elementos que no queremos de la lista.

Recibe una función que regresa un valor booleano (`True` o `False`) y una `lista`. Después usa la función para verificar "elemento por elemento" de la `lista`. Cada vez que la función regrese `True`, el elemento se queda en la nueva lista; cuando la función regrese `False`, el elemento es descartado:

```python
> numeros = [5,8,-2,-34,9,78,45,-67,12,48,-94,-76,-3,25,47]

> def es_negativo(n):
     return n < 0

> list(filter(es_negativo,numeros))
[-2,-34,-67,-94,-76,-3]
```

Veamos a detalle cómo funciona.

[**`Ejemplo 2`**](Ejemplo-02/filter.ipynb)
[**`Reto 2`**](Reto-02/filter.ipynb)

---

#### <ins>Conjunciones (`and`)</ins>

Hasta ahora sólo hemos utilizado `filter` con una función (una sola condición) para filtrar nuestra lista. ¿Pero qué pasa si queremos usar múltiples condiciones? Aquí es donde entran los *operadores lógicos*, que nos permiten unir dos valores lógicos. El primero es el operador `and`, que regresa `True` cuando las dos comparaciones que está uniendo regresan `True`, y `False` en todos los demás casos:

| `p`     | `q`     | `p and q` |
| ------- | ------- | --------- |
| `False` | `False` | `False`   | 
| `False` | `True`  | `False`   |
| `True`  | `False` | `False`   |
| `True`  | `True`  | `True`    |

Vayamos ahora a algunos ejemplos.

[**`Ejemplo 3`**](Ejemplo-03/and.ipynb)
[**`Reto 3`**](Reto-03/and.ipynb)

---

#### <ins>Disyunciones (`or`)</ins>

`or` es muy parecido a `and`. También nos sirve para unir dos condiciones y obtener un nuevo resultado. La diferencia es que `or` regresa `True` cuando **una de las dos o ambas** comparaciones regresen `True`:


| `p`     | `q`     | `p or q`  |
| ------- | ------- | --------- |
| `False` | `False` | `False`   | 
| `False` | `True`  | `True`    |
| `True`  | `False` | `True`    |
| `True`  | `True`  | `True`    |


Vayamos a algunos ejemplos.

[**`Ejemplo 4`**](Ejemplo-04/or.ipynb)
[**`Reto 4`**](Reto-04/or.ipynb)

---

#### <ins>Negaciones (`not`)</ins>

`not` simplemente invierte el valor de verdad de un valor booleano.


| `p`     | `not p` |
| ------- | ------- |
| `False` | `True`  |
| `True`  | `False` |


Vamos a ver cómo funciona.

[**`Ejemplo 5`**](Ejemplo-05/not.ipynb)

---

#### <ins>Funciones Anónimas (`lambda`)</ins>

Las funciones `lambda` son simplemente una manera distinta de declarar nuestras funciones. Tienen el mismo comportamiento de una función, pero una sintaxis diferente. Se ven así:

```python
lambda x: x * 100
```

Esto nos permite usar funciones sin necesidad de darles un nombre, por ejemplo si sólo las usamos en un fragamento particular y no la necesitamos para nada más. Además pueden usarse en combinación con funciones como `map` y `filter`.

Veámoslas en funcionamiento.

[**`Ejemplo 6`**](Ejemplo-06/lambda.ipynb)
[**`Reto 5`**](Reto-05/lambda.ipynb)

---

### 3. Postwork :memo:

[**`Postwork Sesión 3`**](Postwork/Readme.md)

<br/>

[`Anterior`](../Sesion-02/Readme.md) | [`Siguiente`](../Sesion-04/Readme.md)
