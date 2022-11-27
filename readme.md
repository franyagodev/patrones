#Resumen teórico de patrones de diseño

Problemas con soluciones recurrentes que pueden utilizarse para diseños concretos, técnicas probadas que facilitan la reutilización, bajo acoplamiento, cooperacion, fácil mantenimiento.

Permite elevar el nivel de las conversaciones en diseño, ingenieria, comunicar más efectivamente.

De cada patrón, quedarnos con el nombre,problema contextualizado, solución, consecuencias (malas y buenas)

~Patrones de comportamiento, creacionales , de estructura

## Creacionales
* Abstract factory
* Builder
* Factory method
* Prototype
* Singleton

## Estructurales
* Adapter
* Proxy
* Decorator

## De comportamiento
* Chain of responsibility 



###Casi todos los patrones van dirigidos a facilitar la 
####-Granularidad: que las clases hagan una sola cosa
####-Facilitar el cambio a futuro: Cuando creemos que podrían haber cambios funcionales o de implementación, librerias..
####-Poco acoplamiento: 


Bad smells:

* Código díficil de entender. Complejidad arbitraria
* IFs anidados
* Código repetido
* Switches
* Metodos vacíos
* Typeof
* Malos poliformismos
* Código rígido
* Alto acoplamiento
* Metodos gordos que no respetan el open-close
* Objetos que se conocen demasiado entre sí.
* Clases llenas de getters y setters
* Clases que crecen constantemente, muchos cambios constantes
* Dificultad para extender y reutilizar código
* Ausencia de interfaces o tipos genéricos
* Código muy difícil de cambiar, muy acoplado a todo el contexto
* Exceso de herencias
* Métodos estáticos. Es como volver a la programación de antes, rompen un poco la orientación a objetos. Las clases derivadas no lo pueden redefinir. Son datos que están creados, ocupan en memoria si o si cuando se lanza la aplicación.. es malo por todos lados. No se puede pasar como objeto a otros, componerlo...


Libro de referencia:
Design Patterns, Erich Gamma