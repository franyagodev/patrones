#Aspectos a evitar

* Crear un objeto especificando su clase explicitamente, y no su interfaz. Estoy acoplado, me costará más en el futuro.

* Dependencia de operaciones concretas, hardware, software,..Mejor si tengo pequeños objetos que conocen sus métodos más privados ,... oculta esta información a tus clientes... evitando que me acople a esos métodos/librerias/ORMs ligados a frameworks o hardware.

Lo mismo con determinados algoritmos que probablemente cambien. Aislalos 
 
* Fuerte acoplamiento. Esto nos lleva a sistemas monolíticos. Dificiles de usar por separado. No se pueden cambiar o reutilizar porque depende de otras muchas mas. Muy denso, muy dificil de mantener y costoso


* Añadir funcionalidad mediante herencia es poco flexible y más acoplado que hacer composición. Hay que tener un equilibrio entre ambas cosas: herencia y composición.

* Incapacidad para modificar las clases convenientemente