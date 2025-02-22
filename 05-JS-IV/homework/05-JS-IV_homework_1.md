﻿Objetos: Un objeto contiene un conjunto de datos identificados por una clave y con propiedades
a las que llamamos valores. De esta manera podemos decir que en un objeto manejamos pares de
clave:valor. Estas propiedades pueden incluir cualquier cosa desde un tipo de dato (string,
numero, boolean), hasta arrays, funciones (que cuando estan dentro de un objeto se las llama
'metodos') o inclusive otros objetos.


Metodos: Un metodo es el nombre que le damos a una funcion que ocurre dentro de un objeto. 
Funciona de la misma manera que una funcion en otra instancia. En este caso, el nombre de un
metodo es dado por el nombre de la clave del objeto y la funcion se declara en el espacio del
valor o propiedad.


Bucles for...in: Los bucles for...in se usan en un objeto para iterar en cada par clave:valor 
del mismo. En estos bucles definimos una variable que va a representar la iteración del bucle
por cada clave del objeto. Es especialmente util cuando queremos cambiar algun dato en todos los
pares.


Notaciones: Al movernos por las claves de un objeto tenemos dos tipos de notaciones: notacion 
de puntos y notacion de corchetes.
La notacion de puntos tiene la ventaja de ser rapida de tipear ('objeto.clave'), pero la
desventaja de no poder usar variables en el espacio de la clave. Despues del punto solo puede ir
una clave perteneciente al objeto o en su defecto una clave que se quiera agregar al mismo.
La notacion de corchetes tiene la ventaja de permitirnos usar una variable como 'clave'. Tiene
dos posibles notaciones: objeto ['clave'] u objeto [varClave].
