#Builder: Patron para abstraer la lógica de creación de un objeto complejo de forma diferida, olvidandose de detalles complejos

##Problema que resuelve: Da la responsabilidad de fabricar cada objeto al experto que sabe hacerla. Es como ir de compras, le pido a cada responsable objetos de su sector. Son objetos complejos, que requieren especialización. El caso es que la propia construcción puede generar diferentes productos, puede variar en sus detalles o representación.

Suele evitar la acumulación de ifs... se generarán más builders conforme sea necesario.

###Ejemplo: Construcción de objetos complejos.Proceso de separar dicha fabricación. Se suele utilizar en el diseño de pruebas unitarias, el mockeo de objetos.