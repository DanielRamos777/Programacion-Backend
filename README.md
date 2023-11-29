# ProductManager

<!-- addParticipante  en la clase  TicketManager 
Nota: 
este método es útil si deseas llevar un registro de los participantes que han comprado entradas para un evento en particular. Si no necesitas esta funcionalidad, puedes omitir el uso de este método sin ningún problema. -->


Products:
Obtener todos los productos: http://localhost:8080/api/products
Obtener un producto por ID (reemplaza :pid con un ID real): http://localhost:8080/api/products/:pid
Crear un nuevo producto (usar un cliente como Postman o cURL): http://localhost:8080/api/products (Método POST)
Actualizar un producto por ID (reemplaza :pid con un ID real): http://localhost:8080/api/products/:pid (Método PUT)
Eliminar un producto por ID (reemplaza :pid con un ID real): http://localhost:8080/api/products/:pid (Método DELETE)

Carts:
Obtener todos los carritos: http://localhost:8080/api/carts
Obtener un carrito por ID (reemplaza :cid con un ID real): http://localhost:8080/api/carts/:cid
Crear un nuevo carrito: http://localhost:8080/api/carts (Método POST)
Agregar un producto a un carrito (reemplaza :cid y :pid con IDs reales): http://localhost:8080/api/carts/:cid/product/:pid (Método POST)
Actualizar un carrito por ID (reemplaza :cid con un ID real): http://localhost:8080/api/carts/:cid (Método PUT)
Eliminar un carrito por ID (reemplaza :cid con un ID real): http://localhost:8080/api/carts/:cid (Método DELETE)