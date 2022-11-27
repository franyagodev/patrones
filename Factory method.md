#Factory method (1 objeto): Patroń para separar la creación de un objeto,con un solo metodo,  mediante una interfaz única generica pero permitiendo a las subclases decidir que tipo de instancia son. Permite permitir a una subclase la creación de instancias.

##Problema que resuelve: Da la responsabilidad de fabricar cada objeto al experto que sabe hacerla. Podrán salir nuevas clases según la problematica vaya avanzando, pero cada clase en sí ya no crecerá mucho provablemenete. Facilita el open close. Está abierto a añadir nuevas clases y nuevos métodos que no estropearán lo que ya funcione.

###Ejemplo: Clase que se responsabiliza del delivery. Hay subclases que se crean con el tipo de transporte más adecuado: camión, moto, avión...saben optimizar la ruta y conducir cada tipo de vehículo, permisos, etc..

EL cliente sabe que necesita un reparto,llama a una que implementa un transporte.