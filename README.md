# RedesInfraestructura
Proyecto de microservicios
Este proyecto consta de 3 microservicios asociados a la gestion de ordenes de compra en un almacén.
Los 3 microservicios son: USUARIOS, PRODUCTOS Y ORDENES y sus funciones:
USUARIOS: Gestionar la información de los usuarios y validar las credenciales.
PRODUCTOS: Gestionar la información de los productos y permitir disminuir el inventario cuando se generen órdenes de compra.
ORDENES: Recibir la información de los productos que desean adquirir los usuarios, validar que existan, solicitar disminuir el inventario y calcular el precio total de la orden, crear la orden. 
Cada microservicio tendrá asociado una tabla con la información requerida para su funcionamiento. 
El script para la creación de las tablas se encuentra en el archivo scripts.sql
Los microservicios se desarrollaron en JavaScript en el entorno de NodeJS y se usaron las siguientes librerías: express, morgan, mysql, mysql2 y axios.
