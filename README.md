## Evaluación final Módulo 1

### Introducción

> ##### <span style = "color:blue"> Crear una clase TiendaOnline

Este repositorio contiene el código para crear una clase ```TiendaOnline``` con los siguientes atributos:

1. ```inventario``` (lista de diccionarios) que almacena los productos del inventario. Cada producto es un diccionario.
        
>``inventario = {``
`producto_1 = {'nombre':'camisa', 'precio':15, 'cantidad': 10},`
```producto_2 = {'nombre':'falda', 'precio':20, 'cantidad': 15}```
`producto_n ={}`
    `}`


2. `clientes` (diccionario). A su vez, cada cliente debe ser representado como un diccionario con las siguientes claves: 'nombre' y 'email' . Al inicio deberá ser un diccionario vacío. Además, cada cliente debe tener un historial de compras.

>``clientes = {``
`'cliente_1': {'email': 'cliente1@email.com', 'compras': []},`
`'cliente_2': {'email': 'cliente2@email.com', 'compras': []},`
`'cliente_n': {}` 
`}`

3. ```ventas_totales```tipo float. Que se define inicialmente como 0


<span style = "color:blue"> La clase TiendaOnline debe tener los siguientes métodos:

- [x] ```agregar_producto(self, nombre, precio, cantidad)```: Este método agrega un producto al inventario o actualiza su cantidad si ya existe

- [x] ```ver_inventario(self)```: Muestra el inventario de productos con sus detalles.

- [x] ```buscar_producto(self, nombre)```: Busca un producto en el inventario por nombre y muestra sus detalles si se encuentra.

- [x] ```actualizar_stock(self, nombre, cantidad)```: Actualiza el stock de un producto en el inventario.

- [x] ```eliminar_producto(self, nombre)```: Elimina un producto del inventario por nombre.

- [x] ```calcular_valor_inventario(self)```: Calcula y muestra el valor total del inventario.

- [x] ```realizar_compra(self)```: Permite a un cliente realizar una compra seleccionando productos del inventario. Debe interactuar con el cliente para seleccionar productos y calcular el costo total de la compra. No debe estar 100% correcto, hay algunas situaciones en las que no se ejecuta bien

- [x] `procesar_pago(self)`: Procesa el pago de una compra, calcula el cambio y muestra un mensaje de confirmación.

- [x] `agregar_cliente(self, nombre, email)`: Agrega un nuevo cliente al registro de clientes.

- [x] `ver_clientes(self)`: Muestra la lista de clientes registrados con sus nombres y correos electrónicos.