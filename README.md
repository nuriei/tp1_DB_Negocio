1. Generar Diagrama Entidad Relación
2. Encontrar los Esquemas
3. Realizar pasaje a tablas.
   
 A partir del siguiente enunciado se desea realizar el modelo entidad-relación.
Se quiere diseñar una base de datos relacional para administrar la logística,
compras e inventario de un negocio, asegurando el registro de los productos,
los proveedores con los que se trabaja y el control del stock disponible para
evitar desabastecimientos.
De cada producto se requiere conocer su código identificador, nombre,
descripción, precio de venta, la cantidad disponible (stock actual) y el stock
mínimo (límite de alerta para reposición).
De cada proveedor se debe almacenar un identificador único, nombre
completo, razón social, dirección y número de teléfono. Un producto puede ser
provisto por distintos proveedores, y un proveedor puede suministrar múltiples
productos a la vez.
El sistema debe registrar las compras que el negocio realiza a sus proveedores.
De cada compra se conoce su número de transacción o pedido, la fecha en que
se emitió el pedido y el proveedor al que se le solicitó.
Además, se debe guardar información detallada sobre cada transacción
mediante un detalle de compra. Este detalle asocia una compra específica con
los productos solicitados, registrando para cada uno la cantidad adquirida y el
precio de costo acordado.
A nivel de consultas e información de apoyo, el sistema debe responder de
manera eficiente a los siguientes comportamientos y listados:
Listar todos los productos comprados en una fecha específica (por ejemplo, el
día de ayer). Listar todas las compras realizadas a un proveedor determinado
(por ejemplo, Bazar S.A.) para evaluar la frecuencia de compra. Mostrar todos
los productos adquiridos en una compra específica (por ejemplo, la última
compra registrada). Mostrar qué proveedores están registrados como aptos
para proveer un producto en particular (por ejemplo, Heladera Gala 457L).
Identificar cuáles han sido los productos más comprados (con mayor volumen
acumulado) entre un rango de fechas. Identificar de forma inmediata aquellos
productos cuya cantidad disponible actual sea menor o igual al stock mínimo
configurado, facilitando la creación del próximo pedido.
