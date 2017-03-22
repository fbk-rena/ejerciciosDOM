# ejerciciosDOM

## Ejercicio 1

#### Descubrir cuantos enlaces <a> hay en el sitio web dado y escribirlo en pantalla
###### Utilizando _document.getElementsByTagName("A")_ accedemos a todas las etiquetas <a>
###### aplicando la propiedad __.length__ sabremos cuantos elementos el selector encontró 
###### identificando donde tenemos que colocar el dato en esta ocasión _<span id="num_enlaces"></span>_
###### con __.innerHTML__ escribimos nuestro resultado en el lugar deseado.

## Ejercicio 2

#### Decubrir cuantos elementos tienen la clase mensaje en el sitio web dado y escribirlo un texto definido dependiendo la cantidad
###### Utilizando _getElementsByClassName("mensaje")_ accedemos a todos los elementos que contenga la clase mensaje
###### aplicando la propiedad __.length__ sabremos cuantos elementos el selector encontró 
###### identificando creamos una funcion que en base a la cantidad de elemetos arroje una respuesta
###### creamos donde colocar la respuesta determinado por la etiqueta __<span>__ a la que enlistamos una serie de caracteristicas
###### y con __.innerHTML__ escribimos nuestro resultado en el lugar deseado.

## Ejercicio 3

#### Crear una función que arroje los datos obtenidos al rellenar el formulario en la pantalla
###### Lo primero es obtener el valor de los datos obtenidos mediante __.value__ ejecutado en _document.getElementById("idCorrespondiente")_
###### con estos valores obtenidos hacemos uso de __.innerHTML__ para escribir los datos en el lugar deseado.


