# Harold_BBogota
crud de una entidad con relación recursiva  


# Getting Started
este poryecto fue realizado con maven y framework spring.
pasos y sugerencias para correr la aplicación 

1- es necesario crear un schema o base de datos con el nombre Banco_Bogota y tener arriba el servidor de mySql el cual es el motor en el que se desarrollo
si desea utilizar otro motor de base de datos debe modificar el archivo application.properties el cual se encuentra en la carpeta src/main/resources

2- importe el proyecto al explorador de archivo del IDE en que se encuentre

3- de click derecho sobre el nombre del proyecto y luego en run

4- le pedira que seleccione la clase main la cual es:   "DemoApplication"

5- si esta usando eclipse con el plugin de spring solo se utiliza el boot dashboard que trae por defaul, da click derecho en el proyecto y da en la opcion (Re)start,
esto levanta el servidor que viene por default el cual es apache.

6- El endpoint que se levanta por defecto (si tiene configurado el puerto es necesesario que cambie el numero por el puerto que corresponda ej: si esta en el 4500 la dirección quedaria http://localhost:4500/..) http://localhost:8080/apiBancoBogota luego de esto los recursos quedaron así:

INGRESAR EMPLOYEE
http://localhost:8080/apiBancoBogota/save/employee

LISTA DE EMPLOYEE
http://localhost:8080/apiBancoBogota/employees


BORRAR EMPLOYEE POR ID
http://localhost:8080/apiBancoBogota/employee/{id}     

4- verifique en consola que la aplicacion haya inciado correctamente si problemas.


