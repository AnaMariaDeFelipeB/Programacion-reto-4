# **Programacón (Reto 4)**
## _Desarrallado por Ana Maria De Felipe Briñez._
***
### Usando el seudocódigo y diagramas de flujo para entender un poco del mundo de la programación.
***
* En primer lugar desarrollamos una lista con una serie de pasos para enconcontrar números primos. 

![Pasosprimos](https://i.postimg.cc/02v7r69r/Pasoprimos.jpg) 

* Luego desarrollamos el pseudocódigo y el diagrama de flujo relacionados los pasos para encontrar números primos. 

 `Pseudocódigo para encontrar números primos.` 
```pseudocode
  [Datos variables]
  
n: Entero. 
i: Entero. 

Inicio.
 
i := 1

Mientras que (i ≤ n/2) hacer: 
   Si modulo (n,i) = 0 entonces
Escribir (i es divisor de n y agregarlo a una lista conformada por n)
   Si no, entonces
Escribir (i no es divisor de n) 

i : i + 1 

Mientras que (i> n/2) hacer: 
   Si la lista tiene 3 elementos o más entonces
Escribir (n no es un número primo).
   Si no, entonces
Escribir (n es un número primo).

Fin. 

```
`Diagrama de flujo para encontrar números primos.` 

![Diagramaprimos](https://i.postimg.cc/Gt5BXNw7/Diagramaprimos.png)

* Ahora bien, en segundo lugar desarrollamos la misma actividad, solo que esta vez estableciendo los pasos para hallar raices. 

 `Pseudocódigo para hallar raices cuadradas.`
 ```pseudocode
  [Datos variables]
n: Entero positivo. 
i: Entero positivo.
j: Entero. 

Inicio. 
i: =1
j: =0

Mientras que (i < n) hacer: 
   Si n tiene cifras pares, entonces: 
Separar a n en parejas de derecha a izquierda.
Tomar la primera pareja de la izquierda de n.

   Si no tiene cifras pares, entonces: 
Separar a n en parejas de derecha a izquierda, dejando la última cifra sin pareja. 
Tomar a esa cifra sin pareja de n. 

   Si i2 = Pareja/digito o es el número menor más cercano a la pareja/digito, entonces: 
Restar: Pareja - i2

   Si no, entonces: 
Sumar: i + 1 y repetir el proceso hasta que i2 = Pareja/digito o es el número menor más cercano a la pareja/digito.

Mientras que haya más parejas de n, hacer: 
Tomar la siguiente pareja y agregarla al residuo de (Pareja/digito - i2)
Luego, multiplicar a i por 2. 
Al resultado de (i*2) agregar a j y multiplicarlo por j) = p

   Si p = Pareja, entonces: 
Agregar p a i y restar: pareja – p. 

   Si no, entonces: 
j+1 y repetir hasta cumplir condición. 

Luego, tomar la siguiente pareja y agregarla al residuo de (Pareja – p). 
Después, multiplicar a p junto a i por 2. 
Al resultado de (i junto a p) agregar a j y multiplicarlo por j) = p

   Si p= Pareja, entonces: 
Agregar p a i y restar: pareja – p. 

   Si no, entonces: 
j+1 y repetir hasta cumplir condición. 

Fin. 

```

`Diagrama de flujo hallar raices cuadradas.`

![Diagramaraices](https://i.postimg.cc/6pjx3wW7/Diagramaraices.png)
