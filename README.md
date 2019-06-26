# PROYECTO-ORGA
La popular franquicia de alquiler de películas DVD Blockbuster desea volver al negocio y, para ello, consideran que necesitan mejorar su sistema de búsqueda; por ello usted ha sido contratado para realizar el diseño de dicho sistema.
De cada cliente se debe tener la siguiente información:
● Numero de cedula (clave primaria)
● Nombre y Apellido (40 caracteres)
● ID de película alquilada (0 si no tiene ninguna en alquiler)
● Fecha de alquiler y devolución. (En caso de tener una película alquilada)
De cada película se debe tener la siguiente información:
● Título (clave primaria)
● Género (clave secundaria)
● Descripción (60 caracteres)
● Precio de Alquiler por día
● Rating (entero [0-5]) (clave secundaria)
● Stock (Cantidad de películas restantes en inventario)
Funcionalidades:
1. Se debe poder agregar, modificar, eliminar y consultar películas
2. Se debe poder agregar, modificar, eliminar y consultar clientes.
3. Se debe poder buscar películas por:
a. Clave Primaria: Título (Búsqueda sobre índice primario)
b. Clave Secundaria: Rating:(Leer sobre índices secundarios y claves secundarias)
c. Clave Secundaria: Género (Leer sobre índices secundarios y claves secundarias).
4. El cliente debe poder alquilar y devolver películas (Un cliente solo puede tener una película alquilada a la vez)
5. Al buscar una película, el sistema deberá indicar su nombre, género, descripción, precio, rating y si hay stock o no, de no haberlo, también indicará el nombre del cliente que está más pronto a devolverla y la fecha de devolución.
