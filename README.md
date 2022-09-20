# Empresa-2

1. traer el nombre.cedula y salario de un empleado, ordenando los campos de la siguiente manera: Ascendete por nombre y descendente por cedula

SELECT Nombre,Cedula,Sueldo FROM Empleado WHERE (Ciudad = 'medellin')ORDER BY Nombre;

![consulta1]( img/ejercicio1 "consulta 1")

![consulta1]( img/consulta1.1 "consulta 1")


2. Traer el nombre y salario de los primeros 25 empleados cuyo sueldo sea mayor de $600000 ordenandolos en forma ascendente por el numero de la cedula 

SELECT 25 Nombre,Sueldo FROM Empleado WHERE (Sueldo>600000)ORDER BY Cedula;


![consulta2]( img/consulta2 "consulta 2")

3. mostrar el nombre, id y cedula de los primeros 15 empleados cuyos nombres sean distintos. orden la consulta en forma descendente por cedula

SELECT DISTINCT 15 Nombre,id,Cedula FROM Empleado ORDER BY Cedula DESC;

![consulta3]( img/consulta"consulta 3 ")

4. entregar los primeros 15 empleados con nombre y cedula cuya ciudad sea BOGOTA. se necesita que los encabezados de las columnas tengan los siguientes titulos

a. para el campo NOMBRE .... RAZON SOCIAL
b. para el campo CEDULA ... IDENTIFICACION
C. ordene la lista en forma descendente por cedula 

SELECT Nombre AS "RAZON SOCIAL", Cedula AS"identificacion"FROM Empleado WHERE (Ciudad = 'bogota') ORDER BY Cedula DESC LIMIT 15;

![consulta4]( img/consulta4.png "consulta 4")

5. realizar una consulta que entregue el nombre, identificacion, sueldo, edad de los empleados cuyos sueldos esten entre $800000 y $1200000 y cuyas edades esten entre los 23 y 30 años

SELECT Nombre,Cedula,Sueldo,Edad FROM Empleado WHERE (Sueldo BETWEEN 800000 AND 1200000 AND Edad BETWEEN 23 AND 30);


![consulta5]( img/consulta%205 "consulta 5")

6. realizar una consulta que muestre nombre, cedula y salario de los empleados cuyo nombre comience por la letra c. ordene esta lista por salario en forma descendente 


![consulta6]( img/consulta%205 "consulta 6")