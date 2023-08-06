# ecommerce-spring


##IMPORTANTE
- crear un esquema (schema) en tu base de datos MYSQL con el nombre "ecommerce"

## Conexion a tu base de datos 
- ir al archivo src/main/resources/application.properties
- configurar la linea 3 y 4 modificando el nombre y contraseña de tu base de datos
- spring.datasource.username=root (por lo general)
- spring.datasource.password=Tu_contraseña

## para poder iniciarlizar el proyecto, ubicarse en la carpeta raiz, ejecutar CMD:
 -  $ mvn spring-boot:run


# end points:

  ## CRUD de productos: 
  - (Agregar productos para poder visualizar)
  - localhost:8080/productos

  ## Vista ADMIN:
   - localhost:8080/administrador

   ## Vista usuario:
    - localhost:8080
  - (Desde ahí se puede acceder a productos y a carrito de compras a traves del template)
