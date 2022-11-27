##Abstract Factory (n-objetos):  Patron para abstraer la lógica de creación de **grupos de objetos relacionados, una familia de objetos** entre sí con alguna dependencia, sin especificar sus clases concretas. Te da interfaces de familias de objetos,sin acoplarte a detalles.

##Problema que resuelve: Abstracción de los detalles de implementación mediante una clases abstractas relacionadas que tienden a crecer.

###Ejemplo: Tengo una problematica que exige la creación de multiplies objetos con responsabilidades extendidas, es decir, que cubren no solo el problema principal sino multiples detalles

Ejemplo: Creación de coches. Aprovisionamiento de piezas y mano de obra, preparación de maquinaria, requerir especialistas de diversas empresas. Podría incluso considerarse el caso de fabricación de diversos modelos,con lo que el utillaje, escandallo de piezas, instrumental podría cambiar en cada caso. NO es solo crear el coche, sino que es la creacioń de toda esa familia de objetos.