#Adapter: Patron para cambiar la interfaz de una clase para que pueda engancharse a otro sistema con el que no se habla, que sea compatible. Crear interfaces particulares.Es como hacer un wrapper de algo para hacerlo compatible. Imagina una libreria asquerosa. Le haces un wrapper para comunicarte con ella y te aislas de esos detalles, no hablas con la liberia directamente. 

##Problema que resuelve: Conectar o adaptarse a sistemas diferentes con los que no es compatible actualmente con su interfaz definida inicial. No te comunicas directamente con el objeto,sino que el adapter se encarga de proporcionar esa habilidad

###Ejemplo: Permite a más clases trabajar juntas sin duplicar los datos o moverlos a otro sistemas, sino tener nuevas interfaces de comunicación que le permitan comunicarse.

Tienes que conectar con un nuevo proveedor via API. No son compatibles con tu interfaz. Hay una clase que te resuelve esto, te hace ser compatible.

Otro ejemplo: un adaptador de corriente, conversor digital. 