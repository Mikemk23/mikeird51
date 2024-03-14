---
tags: [Import-c658]
title: 'UNIDAD 1.3: Tipos de datos'
created: '2023-09-15T01:39:40.600Z'
modified: '2023-09-19T00:14:08.713Z'
---


# UNIDAD 1.3: Tipos de datos

**Sabemos como declarar una variable aunque tambien podemos saber el tipo de dato que estamos ocupando y por ello tenemos los siguientes tipos en el lenguaje de Python**

```py
nombre = "Jorge" 
edad = 19 
estatura =  1.66 
Estudio = True 
```

Como podemos ver en el <span style="color:red">**nombre**</span> tiene declarado su valor como de tipo **String**, que si sabemos los de tipo String guardar un carácter o una cadena de carácteres, por ello es que se usa mucho en los lenguajes de programación y se declara con comillas dobles o simples.

En la <span style="color:blue">**edad**</span> tenemos que esta declarada de tipo **Integer** o famoso por ser llamado Int, que esto lo que nos dice es que son valores enteros y que pertenecen a todo los numeros naturales que no sean usados con decimales, por ello es que son enteros por usar números sin decimales.

En la <span style="color:yellow">**estatura**</span> podemos ver que esta declarada con un **Float**, es decir que nos permite usar números que lleven decimales que pueden definir un dato mas indicador en ese aspecto. 

En el <span style="color:green">**Estudio**</span> esta declarado el valor de tipo **Booleano**, es decir que el valor booleano es para definir si un dato es verdadero o en su caso es falso, por ello es que se usa mucho en algunos de los condicionales que se plantearan más adelante.

Al final cuando queremos mostrar los resultados de un valor con su tipo de dato tenemos que escribir lo siguiente:

`print(nombre, edad, estatura, Estudio)`

Esto es una forma de poder mandar a imprimir muchos resultados, pero si desean solamente coloquen de una en una variable para poder imprimir por partes y no todo junto.

El resultado que mostrara es el siguiente: <span style="color:blue">**Jorge 19 1.66 True**</span> 

---

# Concatenación de unir 2 o más cadenas
Primero, una concatenación es la unión o la presentación de las cadenas que tenemos por utilizar y que queremos que no se presenten por partes, si no todo junto, para ello en Python utilizamos el simbolo del <span style="color:yellow">**+**</span> y aquí un ejemplo:

```py
nombre = "Jorge"
genero = "Hombre"
print( nombre + " es " + genero )
```
---

# Conversion de un valor
**Se sabe que los valores pueden ser convertidos a otros, pero solo en casos donde los requieran, para ello tenemos un ejemplo que vamos utilizar dos variables de tipo String y los vamos a comvertir en Integers, aquí el ejemplo:**

`````py
numero1 = "10"
numero2 = "2" 
puntaje = int(numero1) + int(numero2)  
print( puntaje )
`````

**NOTA:** Para saber el tipo de dato que estamos ocupando podemos utilizar la palabra <span style="color:aqua">**type**</span> y así se veria el ejemplo:
`print(nombre, type(nombre) )`

---

# RESULTADOS

**Aquí los resultados de los ejemplos anteriores:**

![Alt](/home/jorchitoxyz/Imágenes/Capturas de pantalla/Tipos de datos.png)


