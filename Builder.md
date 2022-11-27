#Builder: Patron para abstraer la lógica de creación de grupos de objetos relacionados entre sí con alguna dependencia, sin especificar sus clases concretas. Te da interfaces de familias de objetos,sin acoplarte a detalles.

##Problema que resuelve: Da la responsabilidad de fabricar cada objeto al experto que sabe hacerla. Es como ir de compras, le pido a cada responsable objetos de su sector. Son objetos complejos, que requieren especialización. El caso es que la propia construcción puede generar diferentes productos, puede variar en sus detalles o representación.

###Ejemplo: Construcción de objetos complejos.Proceso de separar dicha fabricación. Se suele utilizar en el diseño de pruebas unitarias, el mockeo de objetos.