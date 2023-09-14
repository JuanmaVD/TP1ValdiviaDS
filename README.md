# TP1ValdiviaDS
Iniciar el proyecto, se mostraran algunos datos por consola y para ver otro se debe acceder a la base de datos H2 a traves del siguiente link "http://localhost:8082/h2-console".

Luego cambiar el nombre de la base de datos en H2 a juandb y conectarse.

Primero creo un cliente con el metodo builder de Lombot con todos sus atributos correspondietes, a continuacion creo un domicilio tambien con el metodo builder con sus respectivos atributos. Al terminar la creacion asigno el o los domicilios al cliente.

En el siguiente paso creo un pedido (Metodo Builder) con sus atributos, esto para asignarselo al cliente con el metodo agregar pedido. Creo un detalle pedido y lo agrego al pedido anteriormente creado.

En el siguiente paso se crea una factura con sus atributos y se la asigna al pedido ya creado con anterioridad. Se crean los productos y al detalle de la factura se le asignan, al igual que el rubro correspondiente.

Por ultimo realizo la persistencia del cliente con ClienteRepository con el metodo save pasandole el cliente.

Por ultimo muestro algunos datos por pantalla.

Existe un cliente mas, el cual se puede ver a traves de la base de datos.

Juan Manuel Valdivia, 3K10, 48843.
