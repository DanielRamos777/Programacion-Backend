
Lista de productos http://localhost:8080/

Lista de productos que trabajara con websockets, y cada vez que creemos un producto nuevo, o bien cada vez que
eliminemos un producto, se debe actualizar automáticamente en dicha vista la lista. http://localhost:8080/realtimeproducts



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