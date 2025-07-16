* Las estructuras de control de flujo en Python son herramientas que nos permiten decidir qué instrucciones se ejecutan y cuándo, en función de condiciones o repeticiones. 
* En lugar de que el código se ejecute siempre de forma lineal, estas estructuras le dan al programa la capacidad de tomar decisiones, repetir tareas o responder a diferentes situaciones, igual que haríamos nosotros al seguir instrucciones dependiendo de lo que ocurra.

<br>

## 📌 Definición práctica ejm(semáforo):

* Si la luz es verde → puedes avanzar (if)  
* Si es amarilla → tal vez frenes (elif)  
* Si es roja → debes detenerte (else)  
* Y si tienes que contar autos que pasan hasta llegar a 10, eso sería un bucle (for o while).

<br>

## 🚁 Sentencia IF

* La sentencia de control de flujo `if` es probablemente una de las estructuras de control de flujo más importante de cualquier lenguaje de programación.  

__Esta estructura nos permite implementar sentencias condicionales dentro de nuestro programa__   

* La sintaxis que tiene `if` es la siguiente:  
<br>
  `if <expresion>`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`

`<expresion>` : Esta expresión evalua un contexto booleano, el resultado será <b>True</b> o <b>False</b>  
`<sentencia(s)>` : Este es el o los bloques de sentencias que <b>Python</b> ejecutará cuando se cumpla <b>True</b>, caso contrario se omitirá.

<br>

## 🚁 Sentencia ELSE

* En algunas ocasiones nos encontramos con casos de uso en los que queremos una estructura adicional que ejecute una sentencia en <b>Python</b> que no sea <b>True</b>, y que imprima el otro resultado; en estas ocasiones usamos la cláusula `else`.

* La sintaxis que tiene `else` es la siguiente:  
<br>
  `if <expresion>`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`  
  `else`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`

<br>

## 🚁 Sentencia ELIF

* Otros de los casos de uso que nos encontramos con mucha frecuencia, es la de hacer diferentes consultas en nuestro programa en <b>Python</b>, y no solo depender de un `if` y `else`.

* La sintaxis que tiene `elif` es la siguiente:  
<br>
  `if <expresion>`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`  
  `elif <expresion>`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`  
    `elif <expresion>`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`  
  .
  .
  .  
  `else`:  
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`<sentencia(s)>`

<br>

## 💎 Operador Ternario (condicional) en Python

* <b>Python</b> soporta una construcción más relacionada con la sentencia `if` que puede resultar muy interezando para casos más determinados. A esta construcción le denominamos <b><i>Operador Ternario</i></b>

* La sintaxis que tiene es la siguiente: 

  `valor = resultado_si_true if condicion else resultado_si_false`  

  Esto nos permite simplificar mucho el codigo para casos de uso muy importantes.

#### ✅ Recomendación:

* Usa el operador ternario solo para condiciones simples.

* Si tienes varios casos (if / elif / else), es mejor usar la estructura clásica por claridad.

<br>

