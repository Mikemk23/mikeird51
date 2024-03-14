---
tags: [Import-ba5b]
title: 'UNIDAD 1.2: Declaración de variables'
created: '2023-09-15T01:39:30.550Z'
modified: '2023-09-19T00:10:58.043Z'
---

# UNIDAD 1.2: Declaración de variables
**En Python existe una forma de poder declarar variables, pero debemos de saber que existen dos tipos de declaración de variables y son las siguientes:**

<span style="color:pink">*Variable:*</span> Significa que este valor que se asigne puede variar según la ejecución del algoritmo y dar otro resultado al inicial que se pretendia tener, algunos ejemplos es la edad, la estatura, la temperatura, entre otros factores.

<span style="color:gray">*Constante:*</span> Todo valor que esta definido estáticamente y que no puede ser modificado aunque se haga las ejecuciones del algoritmo, por ello se considera que son fijos y leales a sus valores declarados, algunos ejemplos serian el valor de pi, la CURP, matricula de escuela, etc.

**Aquí un ejemplo de una declaración de una variable**

`variable = " "`

Para poder declarar una variable necesitamos de un nombre para definir nuestro dato que vamos a asignar ese valor, al final de todo es cuando ya tenemos ese dato declarado y con un valor, aunque si nos damos cuenta esta vacio ese valor, pero es un dato de tipo String o str.

Otra manera de declarar una variable es con otra variable que ya este definida, pero que a esa variable definida tengamos que condicionar o cambiar a otra forma, por ejemplo:

```py
numero = 10 
numero2 = 20 
resultado = numero + numero2
print(resultado)
```

**De esta forma podemos hacer que nuestra variable esta definida por otra variable que ya tiene esa definición anterior y con ello se pueda hacer uso de esa información**

---

# Entrada de datos a través del teclado por el usuario

**Sabemos que todos los valores tienen que ser definidos por el usuario y por ello es que utilizamos la palabra <span style="color:aqua">**input**</span> dentro de la variable y con ello vamos a colocar un ejemplo**

```py
nombre = input("Escribe tu nombre: ")
print ( "Nombre: " + nombre )
```

**NOTA:** Para poder saber la direccion de memoria de una variable podemos usar la palabra <span style="color:aqua">**id**</span> y se utiliza asi:
`print(id (resultado) )`

---

# RESULTADOS

**Aquí algunos resultados de los ejemplos aplicados**

![Alt](/home/jorchitoxyz/Imágenes/Capturas de pantalla/Variables 2.png)
![Alt](/home/jorchitoxyz/Imágenes/Capturas de pantalla/Variables 1.png)
