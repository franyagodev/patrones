#Singleton: Patron de los más comunes.

## Problema que resuelve: Tener una sola instancia y proveer un acceso global. Es la buena forma de tener una especie de "variable global" que siempre esté disponible

## Ejemplo: Cola de impresión. Manejador de archivos , ORM con bbdd

Lo más relevante, es el acceso global, realmente.


Podría ser una jerarquía de clases, podría haber cierta especialización de objetos, subclases, pero solo 1. La clase singleton no debería ser final, se podría tener que extender, para ayuda a esa posible especialización.

Es un objeto de creación perezosa, se crea cuando se llama por primera vez.

Constructor privado, para que otros no creen más objetos

Atributo y método estático para ompartir objeto singleton

El singleton no es devuelto por un método estático, porque sino no permite la herencia

También se da que a veces, no es solo 1 instancia, sino una cantidad muy reducida de objetos.