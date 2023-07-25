# Diagramas ER

## Ejercicios

### Ejercicio 1 (rrhhprueba)

Una empresa vende productos a varios clientes. Se necesita conocer los datos personales de los clientes (nombre, apellidos, dni, dirección y fecha de nacimiento). Cada producto tiene un nombre y un código, así como un precio unitario. 

Un cliente puede comprar varios productos a la empresa, y un mismo producto puede ser comprado por varios clientes.
Los productos son suministrados por diferentes proveedores. 

Se debe tener en cuenta que un producto sólo puede ser suministrado por un proveedor, y que un proveedor puede suministrar diferentes productos. De cada proveedor se desea conocer el NIF, nombre y dirección.


Actividad: 

Ejecutar queries SQL para:

- Obtener todos los clientes (nom, apellido y fecha de nacimiento).
- Obtener todos los proveedores que cumplan con una condición, por ejemplo que esten asignados al empleado 1.
- Obtener los empleados (nombre, apellidos, email y telf) cuyo salario sea mayor de 1500.
- Obtener los productos (nombre de producto y su precio) que son suministrados por un proveedor concreto (el que querais).

### Ejercicio 2 (optica)

Una òptica, anomenada “Cul d'Ampolla”, vol informatitzar la gestió dels clients i vendes d'ulleres.

En primer lloc l'òptica vol saber quin és el proveïdor de cadascuna de les ulleres. En concret vol saber de cada proveïdor el nom, l'adreça (carrer, número, pis, porta, ciutat, codi postal i país), telèfon, fax, NIF.

La política de compres de l'òptica es basa en que les ulleres d'una marca es compraran a un únic proveïdor (així en podrà treure més bons preus), però poden comprar ulleres de diverses marques a un proveïdor. De les ulleres vol saber, la marca, la graduació de cadascun dels vidres, el tipus de muntura (flotant, pasta o metàl·lica), el color de la muntura, el color de cada vidre i el preu.

Dels clients vol emmagatzemar el nom, l'adreça postal, el telèfon, el correu electrònic i la data de registre. També ens demanen, quan arriba un client nou, d'emmagatzemar el client que li ha recomanat l'establiment (sempre i quan algú li hagi recomanat). El nostre sistema haurà d’indicar qui ha sigut l’empleat que ha venut cada ullera.

## Creación de la base de datos a partir del diagrama ER (MySQLWorkbench)

1. Me conecto al servidor MySQL.
2. Abro el modelo del diagrama ER.
3. Menú Database -> Forward Engineer
4. Elijo la conexión.
5. Opciones de creación de la base de datos: lo dejo todo por defecto.
6. Objetos a exportar: lo dejo por defecto (no cambio nada).
7. Me muestra el código SQL. Next.
8. Me crea la base de datos y las tablas.

## Creación de la base de datos a partir de un fichero SQL

1. Conectamos con el servidor MySQL.
2. Cargamos el fichero SQL (icono carpeta).
3. Ejecutamos el contenido cargado (icono rayo).

