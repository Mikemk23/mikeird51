---
tags: [Import-3321]
title: 'UNIDAD 1.4: Operadores'
created: '2023-09-15T01:39:50.020Z'
modified: '2023-09-19T00:16:20.723Z'
---


# UNIDAD 1.4: Operadores
**Dentro de los operadores que existen en programación vamos a utilizar los existentes (hasta el dia de hoy) que nos ayudaran a resolver más rapido los algoritmos presentados y serián los siguientes:**

+ Operadores Aritméticos
+ Operadores de Asignación
+ Operadores de Comparación 
+ Operadores Lógicos

**Vamos a hablar de ellos en cada una de las secciones que se presenten.**

---

# Operadores Aritméticos

**Son aquellos que nos permiten hacer el uso de las matemáticas dentro del lenguaje de programación y que nos ayudan con el algoritmo matemático a sus respectivos usos presentados**

**Los simbolos que usamos dentro de la programación en Python son:**

+ **( + ) -> suma**
+ **( - ) ->resta**
+ **( * ) -> multiplicación**
+ **( / ) -> división**
+ **( // ) -> division entera**
+ **( ** ) -> exponente**
+ **( % ) -> residuo**

**Para un mejor entendido del tema, vamos a usar dos variables de tipo Int y vamos a realizar la suma que al final tiene que dar 10, aquí el ejemplo:**

`````py
num1 = 6 
num2 = 4 
suma = num1 + num2 
print ( suma ) 
`````

**Al final el resultado tendrá que dar 10**

---

# Operadores de Asignación

**Son aquellos que involucran la parte de la asignación a una variable para poder hacer que esto cumpla con la parte de los operadores aritméticos, para ello se utiliza el simbolo de <span style="color:aqua">=</span> y con ello vamos a ver cuales son simbolos que podemos usar**

+ **(+=) ->  incremento**
+ **(-=) -> decremento**
+ **(*=) -> multiplicando**
+ **(/=) -> dividiendo**

**Para entender mejor, el siguiente ejemplo vamos a tener un numero que valga 100 y haga en ese mismo valor incremente o sume 10 y aquí el ejemplo:**

`````py
valor = 100
valor += 10 
print ( valor )
`````

**Al final el resultado tiene que ser de 110**

---

# Operadores de Comparación

**Son aquellos donde con dos o más variables podremos comparar si ese dato es de forma verdadera o falsa, conforme al algoritmo vamos a conocer los simbolos que se presentan para este tipo de operadores y son:**

+ **( < ) -> menor que**
+ **( > ) -> mayor que**
+ **( <= ) -> menor o igual que**
+ **( >= ) -> mayor o igual que**
+ **( == ) -> igual que**
+ **( != ) -> diferente o igual que**

**Para entender mejor, vamos a utilizar dos valores que uno sea mayor a otro y por ente tiene que ser falso y aquí el ejemplo:**

`````py
dato1 = 5
dato2 = 10
comparar = 5 > 10
print ( comparar )
`````

**Al final el resultado tiene que ser falso**

---

# Operadores Lógicos

**Son aquellos donde aparte de que se usa la lógica con los valores, se usan las formas más simples de saber si un dato si cumple con esos datos, si alguno de ellos lo cumple o si ninguno lo debe cumplir, con ello vamos a revisar cuales son esas palabras que nos permite hacer estos operadores y son:**

+ **( and ) -> Y**
+ **( or ) -> O**
+ **( not ) -> NO**

**Para entender mejor, vamos a hacer que dos variables que uno es verdadero y el otro falso me digan en un AND que cuando las dos variables sean igual que True, entonces el valor me tiene que dar falso**

`````py
logica1 = True
logica2 = False
total = ( logica1 and logica2 == True)
print ( total )
`````

**Al final el resultado tiene que ser falso**

**NOTA:** Estos operadores pueden funcionar dentro de la misma variable, pero para ello se tendría que hacer en una lógica muy sencilla o que simplememte se necesita de esa respuesta rápida, pero existen condiciones que son mas elaboradas y para ello los veremos más adelante

---

# RESULTADOS

**Aquí los resultados de los ejemplos anteriores:**

![Alt](/home/jorchitoxyz/Imágenes/Capturas de pantalla/Operadores.png)
