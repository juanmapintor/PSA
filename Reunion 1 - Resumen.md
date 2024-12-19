- **Propósito del Software:**
    - ¿Para qué quieren usar este software?
    - ¿Qué problema necesitan resolver con este sistema?
    
- **Usuarios Finales:**
    - ¿Quiénes van a usar este software en su empresa?

		- 1er usuario: Area de necesidad
		- 2do usuario: Usuario calificado - Quien aprueba el pedido
		- 3ero: Responsable de administracion (Compras) - Disponibilidad en deposito central y Pedidos de presupuestos en proveedores externos. Emite la orden de compra (a deposito central o a proveedor externo). 
			- Proveedor externo entrega mercadria en deposito - Remito +  factura - Firmado por la obra. -> (Orden de pago----) Recibida
			- Deposito ppal entrega mercaderia en deposito de obra - Remito - Firmado por la obra. 
		- 4to - responsable del deposito de llegada: envia remito. 
		- Una vez que el remito llega, se marca la orden de compra como recibido. 
	
- Deposito central: valorizacion de stock en deposito central. Actualizar precios del stock del deposito central dependiendo del pedido del proveedor externo. 
- Depositos de obras: manejo de stock. 

Tango:
- Stock deposito central.
- Proveedores
- Ordenes de compra 

Items:
	Codigo
	Descirpcion
	Rubro*
	Subrubro*
	Unidad de medida. 

Pedido
	Lista de items + Cantidad
		Cuando
		Quien
		Fecha de necesidad
	Aprobacion
		Observacion
		Cuando
	Estado

Pedido -> N ordenes de compra:
	Identificador de tango
	Items
	Proveedor
	Fecha de emision
	Fecha tentativa de entrega
	Fecha de entrega
	Destino.**
	Estado

Orden de compra -> Remito / Factura


--------------------
Items - Cargar nuevos items/modificar descripcion. 
Pedidos - Todos - Estado - Filtros. 
Orden de compra - Precios (quien genera la orden y administradores). 
Remitos y facturas -> accesos iguales que orden de compras. 



		
	
	



    - ¿Hay diferentes tipos de usuarios que lo van a usar? Si es así, ¿qué necesitan hacer cada uno?

- **Flujo de Trabajo Actual:**
    - ¿Cómo manejan actualmente los pedidos en su empresa?
    - ¿Hay partes de este proceso que les toman mucho tiempo o que son complicadas?
    
- **Información Crítica:**
    - ¿Qué datos o información necesitan guardar y gestionar sobre cada pedido?
    - ¿Qué problemas tienen ahora al manejar esta información? Por ejemplo, ¿hay datos que faltan o que se pierden?
    
- **Seguimiento y Entrega:**
    - ¿Cómo siguen el progreso de un pedido desde que lo hacen hasta que lo entregan?
    - ¿Qué cosas les gustaría mejorar en este proceso?
    
- **Reportes y Métricas:**
    - ¿Qué informes o estadísticas necesitan obtener del sistema para su trabajo?
    - ¿Hay números o datos específicos que les ayudarían a tomar mejores decisiones?
    
- **Definición del MVP:**
    - ¿Qué funciones consideran más importantes para que el software sea útil desde el principio?
    - ¿Cómo sabrán que este primer paso (MVP) es exitoso?


Sistema Principal + Sistemas Satelites:

Sistema de Compras:
	- Telefono + Compu: 
		- Pedido de inicio de la obra
		- Trazabilidad de compras de materiales

Sistema de Recursos Humanos:

Sistema de Equipamiento:


Ferreteria virtual:
- Stock propio - Sobrantes
- Sin stock. 

Sistema de alquiler de maquinarias:
- Funcionamiento



Necesidad de area  -> 
Pedido por items ->
Aprobacion -> 
Orden de Compra -> 
Proveedor/Deposito -> 
Comprado/Enviado ->
Recibido en un deposito de area. 




