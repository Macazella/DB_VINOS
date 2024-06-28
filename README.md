# DB_VINOS
DB creada a partir de ejercicios de nivel inicial e intermedio en Apex Oracle
El orden correcto para crear las tablas E insertar datos es el siguiente: 

BODEGA: Esta tabla debe crearse primero porque es la tabla principal para la entidad BODEGA. Las otras tablas tienen una relación de clave foránea con la tabla BODEGA, por lo que deben crearse después de que la tabla BODEGA exista. 

CATEGORIA: Esta tabla debe crearse a continuación porque es la tabla principal para la entidad CATEGORIA. Las tablas VINO y CATEGORIA_PROVEEDOR tienen una relación de clave foránea con la tabla CATEGORIA, por lo que deben crearse después de que la tabla CATEGORIA exista. 

PROVEEDOR: Esta tabla debe crearse a continuación porque es la tabla principal para la entidad PROVEEDOR. La tabla PEDIDO tiene una relación de clave foránea con la tabla PROVEEDOR, por lo que debe crearse después de que la tabla PROVEEDOR exista. 

CLIENTE: Esta tabla debe crearse a continuación porque es la tabla principal para la entidad CLIENTE. Las tablas PEDIDO y COMPRA tienen una relación de clave foránea con la tabla CLIENTE, por lo que deben crearse después de que la tabla CLIENTE exista. 

VINO: Esta tabla debe crearse a continuación porque tiene una relación de clave foránea con la tabla BODEGA. 

PEDIDO: Esta tabla debe crearse a continuación porque tiene relaciones de clave foránea con las tablas VINO, PROVEEDOR y CLIENTE. 

COMPRA: Esta tabla debe crearse a continuación porque tiene relaciones de clave foránea con las tablas VINO y CLIENTE. 

CATEGORIA_PROVEEDOR: Esta tabla debe crearse por último porque tiene relaciones de clave foránea con las tablas CATEGORIA y PROVEEDOR. 
