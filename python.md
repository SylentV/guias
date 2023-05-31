### PYTHON 🐍
Python es un lenguaje de programación de alto nivel y de propósito general. Es conocido por su sintaxis simple y legible, lo que facilita su aprendizaje y uso. Python se destaca por su enfoque en la legibilidad del código y la productividad del programador.

Es un lenguaje interpretado, lo que significa que no necesita ser compilado antes de ser ejecutado. Esto permite una mayor agilidad en el desarrollo, ya que los programas se pueden probar y modificar rápidamente.

Python es utilizado en una amplia gama de aplicaciones, desde el desarrollo web hasta el análisis de datos, la inteligencia artificial y la automatización de tareas. Es muy popular entre los científicos de datos debido a su amplia colección de bibliotecas y herramientas especializadas.

## TIPOS DE DATOS

1. String: Cadena de texto representada por "" todo lo que esté dentro de las comillas es una cadena de texto
2. Numerico: Integer, son los números no decimales ejemplo 1, 2, 3
3. Float: Los flotantes son los números reales, básicamente con comas
4. Boolean: Los booleanos, son valores de verdadero o falso (True, False)

## VARIABLES

Una variable es un contenedor que contiene un tipo de dato y se almacena en memoria
Para definir una variable simplemente pondremos el nombre de la variable con un igual y el valor que queramos

```python
mivariable = "Hola Mundo"
```
### PODEMOS SOBREESCRIBIR ESA VARIABLE
Para sobre escribir esa variable simplemente deberemos hacer lo siguiente

```python
mivar = "Hola"
mivar = 9
```
> ¿Qué crees que devolverá si imprimo la variable?

## CONDICIONES
Bien las condiciones como ya dice su nombre se encarga de comprobar que si la condición que le hemos dado se cumple y si no pasa a la siguiente en caso de que haya si no hay simplemente no devolverá nada.

1. if else
2. elif

# OPERADORES ARITMÉTICOS
1. `>` Mayor que
2. `<` Menor que
3. `>=` Mayor o igual
4. `<=` Menor o igual
5. `!=` Diferente de
6. `==` Igual

# OPERADORES LÓGICOS
1. `is`
2. `or`
3. `and`
4. `not`

Estos 2 son los que se usan bien pongamos un ejemplo muy simple

```python
variable1 = 1
variable2 = 2

if variable1 == variable2:
  print("Si son iguales")
elif variable1 != variable2:
  print("No son iguales") 
elif variable1 > variable2:
  print("Si es mas grande")
```

## DECLARACIÓN DE FUNCIONES

Una función es un bloque de código reutilizable que realiza una tarea específica.

```python
def ejemplo():
  print("Hola Mundo")
```
Para definir una función usaremos la clave `def nombredelafunción():` y para llamarla el nombre de la funcion

# PARÁMETROS
Los parámetros son argumentos que nosotros le pasamos a una función para agregarle funcionalidades.

Ejemplo:
```python
def decir(texto):
  print(texto)
decir("Hola")
```
En este caso le hemos pasado un argumento que le hemos llamado texto, si yo le pongo cuando llamamos la función "Hola", me devolverá hola.

# FUNCIONES ASÍNCRONAS
Son funciones que permiten realizar más de una tarea a la vez.

Ejemplo

```python
import asyncio
async def decir():
    print("Hola")
    await asyncio.sleep(1)
    print("Hola de nuevo")

asyncio.run(decir())
```
En esta función le estamos diciendo que imprima Hola y un segundo despues Hola de nuevo, para poder ejecutar estas funciones necesitamos la librería asyncio.

## EXTRAER VALORES DE UNA LISTA
Bien una lista es una lista de valores, puede contener cualquier tipo de dato.

# ÍNDICES
Lo que usamos para identificar un valor dentro de una lista son los índices.

```python
ejemplo = [
  True,
  False,
  "Hola",
  1,
  2.3
]
print(tipos[0])
```
> **IMPORTANTE** Se empieza a contar desde 0

## EXTRAER VALORES DE UN DICCIONARIO

```python
tipos = {
    'int': 'int',
    'float': 'float',
    'str': 'str',
    'bool': 'bool',
    'list': 'list',
}

print(tipos['int'])
```









