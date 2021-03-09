[`Procesamiento de Datos con Python`](../Readme.md) > `Sesión 1`

## Sesión 01: Fundamentos de Python

<img src="../imagenes/pizarron.png" align="right" height="100" width="100" hspace="10">

### 1. Objetivos :dart:

1. Asignar variables, operadores matemáticos y tipos de datos.
2. Realizar interpolación de Strings.
3. Realizar comparaciones y estructuras de control de flujo.

### 2. Contenido :blue_book:

#### <ins>Revisión de Software</ins>

Asegurarse de que todos los alumnos hayan realizado con éxito la conexión entre Google Drive, Github y Google Colab. 

Es necesario saber leer archivos .ipynb en Colab desde el repositorio del módulo.

También es necesario haber creado el Acceso Directo a los Datasets desde el Drive del alumno para poder acceder a los conjuntos de datos desde Colab.

---

#### <ins>Jupyter Notebooks</ins>

Ya hablamos sobre Jupyter Notebooks en el Prework. Vamos a hacer un pequeño repaso para que quede claro cómo aprovechar al máximo este REPL.

[**`Ejemplo 1`**](Ejemplo-01/notebook_de_practica.ipynb)

---

#### <ins>Variables en Python</ins>

En Python usamos `variables` para asignarles contenido que queremos utilizar después.

- La sintaxis es:

   `nombre_de_variable = valor`

`valor` puede ser muchas cosas, que ya iremos aprendiendo poco a poco.

[**`Ejemplo 2`**](Ejemplo-02/variables.ipynb)
[**`Reto 1`**](Reto-01/variables.ipynb)

---

#### <ins>Operaciones numéricas</ins>

Hemos estado asignando números a variables. En Python podemos realizar operaciones matemáticas de una forma muy sencilla. Simplemente tenemos que usar los `operadores aritméticos` que ya conocemos para hacer operaciones entre las variables que hayamos definido previamente. Los operadores aritméticos en Python son los siguientes:

- Suma: `+`
- Resta: `-`
- Multiplicación: `*`
- División: `/`
- Exponente: `**`

¡Practiquemos con ellos!

[**`Ejemplo 3`**](Ejemplo-03/operaciones_numericas.ipynb)
[**`Reto 2`**](Reto-02/operaciones_numericas.ipynb)

---

#### <ins>Tipos de datos en Python</ins>

Python tiene diferentes tipos de datos para representar diferentes cosas. Por el momento vamos a aprender los 4 más básicos y esenciales:

- `int` => números enteros
- `float` => números decimales
- `string` => secuencias de caracteres (texto)
- `boolean` => booleanos (True o False)

Por el momento no importa si no entiendes para qué sirven las strings y los booleanos. Eso lo veremos más adelante.

[**`Ejemplo 4`**](Ejemplo-04/tipos_de_datos.ipynb)

---

#### <ins>Interpolación de Strings</ins>

Más adelante veremos que las Strings pueden contener información muy relevante dentro de nuestros conjuntos de datos (como nombres de personas, descripciones de procesos, categorías, etc). Por lo pronto, vamos a utilizar nuestras Strings para imprimir anotaciones en nuestros `outputs`. Queremos obtener resultados que se vean más o menos así:

`Suma de variable_1 y variable_2: 10`

Vamos a ver cómo hacer eso.

[**`Ejemplo 5`**](Ejemplo-05/interpolacion_de_strings.ipynb)
[**`Reto 3`**](Reto-03/interpolacion_de_strings.ipynb)

---

#### <ins>Booleanos y operadores de comparación</ins>

Ya practicamos con `ints`, `floats` y `strings`. Sólo nos falta entender para qué usar los `booleanos`. Nuestros programas necesitan una manera de "tomar decisiones". Nosotros en la vida real solemos tomar decisiones haciendo comparaciones entre las opciones y tomando la decisión que más nos convenga tomando en cuenta el contexto. El primer paso para lograr esto son los `operadores de comparación`. Sirven para comparar valores. Regresan un booleano `True` cuando la comparación es cierta y un booleano `False` cuando la comparación es falsa.

Python tiene los siguientes `operadores de comparación`:

```
Mayor que: >
Mayor o igual que: >=
Menor que: <
Menor o igual que: <=
Igual que: ==
No igual (distinto) que: !=
```

Veamos cómo funcionan.

[**`Ejemplo 6`**](Ejemplo-06/operadores_de_comparacion.ipynb)
[**`Reto 4`**](Reto-04/operadores_de_comparacion.ipynb)

---

#### <ins>Estructuras de control de flujo</ins>

Para finalizar, vamos a juntar todo lo que hemos aprendido el día de hoy y vamos a darle a nuestro programa la capacidad de tomar decisiones. Los programas tienen datos de entrada (inputs) y datos de salida (outputs). Varían sus outputs dependiendo del input que reciban. Para poder tomar decisiones, utilizan las llamadas `estructuras de control de flujo`. Que se ven así:

```
if var_1 > var_2:
    print("OK")
else:
    print("ERROR")
```

Vamos a ver cómo funcionan.

[**`Ejemplo 7`**](Ejemplo-07/estructuras_de_control_de_flujo.ipynb)
[**`Reto 5`**](Reto-05/estructuras_de_control_de_flujo.ipynb)

---

### 3. Postwork :memo:

[**`Postwork Sesión 1`**](Postwork/Readme.md)

<br/>

[`Anterior`](../Readme.md) | [`Siguiente`](../Sesion-02/Readme.md)
