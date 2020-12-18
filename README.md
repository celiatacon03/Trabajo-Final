Celia Tacón Serrano 2ºBachA
___
### Caso 1
En este caso he utilizado el siguiente código de flex box:
~~~
#container{
    display: flex;
    flex-direction: column;
}
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se desplacen hacia abajo en forma de columna.

### Caso 2
En este caso he utilizado el siguiente código de flex box:
~~~
   #container{
       display: flex;
       justify-content: flex-end;
}
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se desplacen hacia el final del `div`horizontalmente.

### Caso 3
En este caso he utilizado el siguiente código de flex box:
~~~
     #container{
         display: flex;
         justify-content: space-around;
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se distribuyan horizontalmente de manera que quede un espacio igual entre ellos.

### Caso 4
En este caso he utilizado el siguiente código de flex box:
~~~
    #container{
        display: flex;
        justify-content: space-between;
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se distribuyan horizontalmente de manera que quede un espacio igual entre ellos, pero esta vez aprovechan todo el espacio horizontal del `div`.

### Caso 5
En este caso he utilizado el siguiente código de flex box:
~~~
    #container{
        display: flex;
        align-items: center;
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se coloquen en el centro respetando en el centro de estos una línea invisible que coincide con el medio del `div`.

### Caso 6
En este caso he utilizado el siguiente código de flex box:
~~~
    #container{
        display: flex;
        align-items: flex-start;
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se alineen al principio del `div`.

### Caso 7
En este caso he utilizado el siguiente código de flex box:
~~~
     #container{
         display: flex;
         align-items: stretch;
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` ocupen el espacio del `div` verticalmente. La anchura la conservará.

### Caso 8
En este caso he utilizado el siguiente código de flex box:
~~~
       #container{
           display: flex;
           align-items: flex-end;
~~~
Al aplicar este código de Flex Box conseguimos que los elementos que contiene el `div` se alineen al final del `div`.

### Caso 9
En este caso he utilizado el siguiente código de flex box:
~~~
    #container{
        display: flex;
	      flex-wrap: wrap;
        align-content: space-around;
~~~
Al aplicar el código `flex-wrap: wrap;` conseguimos que los elementos que contiene el `div` se coloquen en varias líneas hacia abajo según no vayan cabiendo horizontalmente, y con el código `align-content: space-around;` conseguimos que los elementos se alineen dejando un mismo espacio entre ellos.


### Caso 10
En este caso he utilizado el siguiente código de flex box:
~~~
   #container{
       display: flex;
	     flex-wrap: wrap;
       align-content: space-between;
~~~
Al aplicar el código `flex-wrap: wrap;` conseguimos que los elementos que contiene el `div` se coloquen en varias líneas hacia abajo según no vayan cabiendo horizontalmente, y con el código `align-content: space-between;` conseguimos que la primera línea que se genera de elementos se coloca al principio del `div` y la última línea al final de este, creándose un espacio uniforme entre las líneas.


### Caso 11
En este caso he utilizado el siguiente código de flex box:
~~~
  #container{
      display: flex;
	    flex-wrap: wrap;
      align-content: stretch;
~~~
Al aplicar el código `flex-wrap: wrap;` conseguimos que los elementos que contiene el `div` se coloquen en varias líneas hacia abajo según no vayan cabiendo horizontalmente, y con el código `align-content: stretch;` conseguimos que los elementos se expandan verticalmente ocupando el espacio entre las líneas.


### Caso 12
En este caso he utilizado el siguiente código de flex box:
~~~
 #container{
     display: flex;
	   flex-wrap: wrap;
     align-content: center;
~~~
Al aplicar el código `flex-wrap: wrap;` conseguimos que los elementos que contiene el `div` se coloquen en varias líneas hacia abajo según no vayan cabiendo horizontalmente, y con el código `align-content: center;` conseguimos que todas las líneas se coloquen en el centro del `div`.

### Caso 13
En este caso he utilizado el siguiente código de flex box:
~~~
 #container{
     display: flex;
	   flex-wrap: wrap;
     align-content: flex-start;
~~~
Al aplicar el código `flex-wrap: wrap;` conseguimos que los elementos que contiene el `div` se coloquen en varias líneas hacia abajo según no vayan cabiendo horizontalmente, y con el código `align-content: flex-start;` conseguimos que todas las líneas se coloquen al principio `div`.


### Caso 14
En este caso he utilizado el siguiente código de flex box:
~~~
    #container{
        display: flex;
	      flex-wrap: wrap;
        align-content: flex-end;
~~~
Al aplicar el código `flex-wrap: wrap;` conseguimos que los elementos que contiene el `div` se coloquen en varias líneas hacia abajo según no vayan cabiendo horizontalmente, y con el código `align-content: flex-start;` conseguimos que todas las líneas se coloquen al final `div`.

### Caso 15
En este caso he utilizado el siguiente código de flex box en el `div` donde están todas las cajas:
~~~
     #container{
         display: flex;
         align-items: stretch;
~~~
Y este otro para cada una de las cajas:
~~~
     #box{
        display: flex;
        flex-grow: n;
~~~
El primer código,`align-items: stretch;`, lo he utilizado para que los elementos del `div` se expandan verticalmente y se adecuen a la altura de este. El otro, `flex-grow: n;`, siendo "n" un número cualquiera, ensancha las cajas del `div` según el número que le demos.

### Caso 16
En este caso he utilizado el siguiente código de flex box:
~~~
   #container{
       display: flex;
       flex-wrap: nowrap;
~~~
Al aplicar el código `flex-wrap: nowrap;` conseguimos que los elementos que contiene el `div` se acomoden en una sola línea y no se desplacen hacia abajo.
