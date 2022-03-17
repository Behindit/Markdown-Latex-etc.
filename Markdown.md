# Markdown

Markdown es un lenguaje de marcado ligero, a continuación te mostrare como utilizar este lenguaje y su sintaxis

## Titulos

Para escribir títulos solo hace falta usar el símbolo # antes del titulo con 1 espacio entre ellos, para escribir un titulo mas pequeño se le agrega un # mas, así hasta la cantidad máxima de 6.

EJ:
~~~
# Titulo grande
###### Titulo pequeño
~~~
Resultado:
# Titulo grande
###### Titulo pequeño

## Modificador italic

Para utilizar el modificador italic se escribe el símbolo * antes y después de una palabra.

EJ:
~~~
*italic*
~~~
Resultado:

*italic*

## Modificador strong

Para utilizar el modificador Strong se escribe 2 veces el símbolo * antes y después de una palabra.
EJ:
~~~
**Strong**
~~~
Resultado:

**Strong**

## Modificador strikethrough

Para utilizar el modificador strikethrough se escribe 2 veces el símbolo ~ antes y después de una palabra.
EJ:
~~~
~~strikethrough~~
~~~
Resultado:

~~strikethrough~~

## Listas

se pueden generar listas de 2 maneras, ordenadas o desordenadas

#### Listas desordenadas

Las listas desordenadas se crean ubicando un * al principio de la linea, luego de un espacio se escribe el elemento de la lista.
EJ:
~~~
* Manzana
* Pera
~~~
Resultado:

* Manzana
* Pera

También se pueden añadir elementos dentro de elementos
EJ:
~~~
* Salas
    * Sala 1
    * Sala 2
~~~
Resultado:

* Salas
    * Sala 1
    * Sala 2

#### Listas ordenadas

Las listas ordenadas se crean ubicando un numero seguido de un punto y luego un espacio
EJ:
~~~
1. Frutas
    1. Manzanas
    2. Naranjas
    3. Peras
~~~
Resultado:

1. Frutas
    1. Manzanas
    2. Naranjas
    3. Peras

## Introducir enlaces en textos

Para introducir enlaces en texto primero se escribe el texto dentro de corchetes y seguido de paréntesis donde se introduce el enlace.
EJ:
~~~
[Mi GitHub](https://github.com/Behindit)
~~~
Resultado:

[Mi GitHub](https://github.com/Behindit)

También se puede customisar el titulo que aparece al mantener el cursor encima del link, dentro de los paréntesis luego del enlace abre comillas y escribe el titulo que desees
EJ:
~~~
[Mi GitHub](https://github.com/Behindit "GitHub")
~~~
Resultado:

[Mi GitHub](https://github.com/Behindit "GitHub")

##  Citas

Para indicar que el texto es una cita se puede escribir el símbolo >
EJ:
~~~
> Esto es una cita
~~~
Resultado:

> Esto es una cita

## Separadores

También se pueden generar separadores escribiendo 3 - o _ seguidos
EJ:
~~~
___

~~~
Resultado:

___

## Introducir Código

Para poder escribir un bloque de código se utilizan 3 tildes una linea antes y después del código.

También cabe destacar que se puede indicar el lenguaje del código a continuación de las 3 primeras tildes, para que aparezca la sintaxis del lenguaje

EJ:

```
~~~python
print("Programa generacion de triangulos")

def cretri(x):
    for i in range(x+1):
        print("*"*i)
    for i in range(x-1,0,-1):
        print("*"*i)

def genotr(yeno):

    if yeno.lower()=="si":
        return True
    else:
        return False

gentri=True
while (gentri):
    x=int(input("Introduce la altura del triangulo: "))
    cretri(x)
    yeno=input("Quiere generar otro triangulo?(si/no): ")
    gentri=genotr(yeno)

print("Programa Finalizado")
~~~
```

Resultado:
~~~python
print("Programa generacion de triangulos")

def cretri(x):
    for i in range(x+1):
        print("*"*i)
    for i in range(x-1,0,-1):
        print("*"*i)

def genotr(yeno):

    if yeno.lower()=="si":
        return True
    else:
        return False

gentri=True
while (gentri):
    x=int(input("Introduce la altura del triangulo: "))
    cretri(x)
    yeno=input("Quiere generar otro triangulo?(si/no): ")
    gentri=genotr(yeno)

print("Programa Finalizado")
~~~
## Tablas

Se pueden crear tablas utilizando 2 metodos, manualmente y a través de librerías, en este caso señalare la manual. se puede utilizar la siguiente platilla para crear tablas.

~~~
| Juego             | Compañia    | Clasificacion | Precio (MXN) |
|-------------------|-------------|---------------|--------------|
| Animal Crossing   | Nintendo    | E             | 1600         |
| Persona 5         | Atlus       | T             | 1500         |
| Final Fantasy VII | Square Enix | T             | 1500         |
| Fortnite          | Epic Games  | M             | 0            |
~~~

Resultado:

| Juego             | Compañia    | Clasificacion | Precio (MXN) |
|-------------------|-------------|---------------|--------------|
| Animal Crossing   | Nintendo    | E             | 1600         |
| Persona 5         | Atlus       | T             | 1500         |
| Final Fantasy VII | Square Enix | T             | 1500         |
| Fortnite          | Epic Games  | M             | 0            |

## Imagenes

Se pueden introducir imágenes en un texto de 2 maneras, a través de enlaces y
archivos locales, de la siguientes maneras.

* Enlace

EJ:

~~~
![Python](https://i.pinimg.com/originals/a8/53/14/a8531424a5fac660e4261f72ca817141.png)
~~~
Resultado:

![Python](https://i.pinimg.com/originals/a8/53/14/a8531424a5fac660e4261f72ca817141.png)

* Archivo Local

EJ:

~~~
![Python](python.png)
~~~
Resultado:

![Python](python.png)

Y al igual que con los enlaces, se puede nombrar las imágenes de manera que al posicionar el cursor encima de la imagen aparesca un titulo/nombre

EJ:

~~~
![Python](python.png "Python")
~~~
Resultado:

![Python](python.png "Python")

# Markdown de GitHub

GitHub implementa Markdown, pero añade unos cuantos extras. a continuación te mostrare dichos extras y como utilizarlos

## To do

Son tareas con una checkbox

EJ:
~~~
*[x]Hecho
*[ ]No hecho
~~~
Resultado:

*[x]Hecho
*[ ]No hecho

## Mencionar a otro usuario de GitHub

se puede mencionar a otros usuarios de GitHub al escribir @ seguido de su nombre de usuario

EJ:
~~~
@Valrojo
~~~
resultado:

@Valrojo

## Emojis

tambien se pueden introducir emojis, para saber como introducir cada emoji esta esta pagina: [Emojis](https://gist.github.com/rxaviers/7360908 "Lista completa de los emojis")

EJ:
~~~
:smiley:
~~~
Resultado:

:smiley:
