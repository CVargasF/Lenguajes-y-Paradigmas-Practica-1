# Metodos Numericos
## Explicación de trabajos
Se desarrollaron 3 códigos diferentes para esta sección del trabajo. Cada uno calcúla una función diferente. Estás funciones son: La función exponencial de euler, la funcion de seno, y la funcion logaritmo natural. Cada una de estas luego se comparan con la funcion integrada a la función que ya viene implementada con Haskell y se calcula el porcentaje de error. 
## Funcion Exponencial
### Explicación
La función de euler con exponente se calcúla con una sumatoria de (x^n)/(n!) donde n tiende al infinito. Esta sumatoria es la más fácil de el resto por su falta de complejidad.

<img width="927" height="120" alt="FuncionExponencialMatematica" src="https://github.com/user-attachments/assets/f488b131-4084-4eca-8e13-946a49dcc075" />


### Pruebas
<img width="1852" height="845" alt="PruebaEuler1" src="https://github.com/user-attachments/assets/f2bf2bd4-4e0c-4c93-9683-e75f794c33d8" />
En esta prueba se puede ver el porcentaje de error de 95% cuando hay 8 elementos en la sumatoria. 

<img width="1850" height="817" alt="PruebaEuler2" src="https://github.com/user-attachments/assets/614644fd-344b-4fbf-ad70-11de38487b49" />

En esta prueba subí la cantidad de elementos en la sumatoria y me entrego un mejor estimado, llegando a ser 99% del resultado del computador

<img width="1861" height="830" alt="PruebaEuler3" src="https://github.com/user-attachments/assets/14b7cf04-8096-4214-a4e7-6200d086a533" />

En esta prueba hice que sea un exponente ridiculamente grande para ver la diferencia de los resultados. Se puede notar que el porcentaje de diferencia está ridiculamente elevado. Esto está bien porque entre mayor sea el exponente y menor sean los elementos de las sumas, el estimado va a ser más lejano al resultado real.

### Código
<img width="1247" height="801" alt="EulerExponencial" src="https://github.com/user-attachments/assets/478f1a22-e8e3-4a77-a2b5-b829a68a1cc1" />
https://play.haskell.org/saved/KqzJJX06


## Funcion Coseno

### Explicación
La función Coseno, desde mi punto de vista fue la más dificil. Esto fue por que implementa la función sumatoria que es una función que me dio resultados erronios por la facilidad de sobrepasar el limite de números del computador. Además, este problema requirio de mucha paciencia mía por que tuve dificultades con los tipos de datos en Haskell.

<img width="477" height="118" alt="FuncionCosenoMatematica" src="https://github.com/user-attachments/assets/7ddcb6bf-3c9a-4f61-acda-82d6c493dfa2" />



### Pruebas



### Código
<img width="870" height="800" alt="CosenoCodigo" src="https://github.com/user-attachments/assets/4818b4b0-98fa-4d9d-af30-e5e9166ee2d6" />
https://play.haskell.org/saved/hShc5QyK


## Funcion Logaritmo Natural



### Explicación

### Pruebas

### Código

