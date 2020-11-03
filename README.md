# RecetarioSOA-OSB
 Proyecto final integrador de la escuelita SOA-OSB. Recetario que permite realizar un altas, modificaciones y consultas de recetas y cocineros. Servicio expuesto como Rest, permite cargar recetas desde un archivo local. Permite guardar un archivo local con las recetas. Realizado en SOA-BPEL-OSB.

 1- Desarrollar un servicio que permita operar con recetas de comida 
   a- el servicio debe permitir consultar una receta por nombre.
   b- el servicio debe permitir modificar una receta.
   c- el servicio debe permitir crear recetas.
  2- El servicio debe ser rest y tener un flujo por cada método usado
  3- Usar tablas de base de datos para  
       recetas (codigo, nombre, tiempo, dificultad, porciones).
       cocinero(codigo, nombre).
  4- 
      Si consulto 1 receta me debo retornar los datos de la receta mas el nombre del cocinero. 
      Si quiero agregar una receta debo especificar : codigo, nombre, tiempo, dificultad, porciones, nombreCocinero
      Si quiero modificar una receta debo especificar codigo receta y que modifico. 
      Los cocineros de las recetas deben existir previamente en la tabla. 
      Es opcional exponer el servicio para dar de alta cocineros, modificar y consultarlos.
5- Debe exponer un servicio bpel para guardar las recetas en un archivo pero deber estar expuesto como rest en osb.
6- Debe poder brindar la opción de cargar recetas por archivo. Poll de file
7- opcional uso de cache, autenticacion, y manejo de errores, reportes y alertas.
