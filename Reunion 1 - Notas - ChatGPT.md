### Funcionamiento del Sistema de Compras

El sistema de compras describe el flujo de trabajo para gestionar la adquisición de bienes dentro de una empresa, desde la identificación de la necesidad hasta la recepción de los productos. A continuación, se detalla el funcionamiento del sistema basado en los roles de los usuarios y el proceso:

---

#### **Roles de Usuarios**

1. **Área de Necesidad**
    
    - Este es el usuario que identifica y genera la necesidad de un pedido específico.
    - Selecciona los ítems requeridos, especifica cantidades y proporciona una fecha de necesidad.
2. **Usuario Calificado**
    
    - Es el responsable de revisar y aprobar el pedido generado por el área de necesidad.
    - Puede agregar observaciones durante la aprobación del pedido.
3. **Responsable de Administración (Compras)**
    
    - Gestiona la disponibilidad del stock en el depósito central.
    - En caso de insuficiencia en el depósito central, solicita presupuestos a proveedores externos.
    - Emite las órdenes de compra, ya sea al depósito central o a proveedores externos.
4. **Responsable del Depósito de Llegada**
    
    - Supervisa la recepción de la mercadería en el depósito correspondiente.
    - Envia el remito firmado como confirmación de recepción.

---

#### **Flujo del Proceso**

1. **Generación de Necesidad**
    
    - El área de necesidad crea un pedido especificando los ítems, las cantidades requeridas y la fecha en que los necesita.
    - El pedido incluye detalles como observaciones y estado inicial.
2. **Aprobación del Pedido**
    
    - El usuario calificado revisa el pedido.
    - Una vez aprobado, el pedido está listo para la creación de una o varias órdenes de compra.
3. **Creación de Órdenes de Compra**
    
    - El responsable de administración analiza si los ítems están disponibles en el depósito central.
        - **Si hay stock disponible:** se emite una orden de compra interna para el depósito central.
        - **Si no hay stock:** se solicita presupuesto a proveedores externos, seleccionando el más adecuado, y se emite una orden de compra externa.
    - La orden de compra incluye:
        - Identificador único.
        - Lista de ítems y cantidades.
        - Proveedor o destino del pedido.
        - Fechas de emisión y entrega estimada.
4. **Recepción de la Mercadería**
    
    - **Desde proveedores externos:**
        - La mercadería llega al depósito central con remito y factura.
        - La obra firma el remito y se registra la orden de pago.
    - **Desde el depósito central:**
        - La mercadería es enviada al depósito de obra correspondiente junto con un remito, que debe ser firmado por la obra al momento de la recepción.
5. **Actualización del Estado**
    
    - Una vez recibido el remito firmado por el depósito de llegada, la orden de compra se marca como "recibida".
    - Se actualiza el stock en los depósitos correspondientes y, si corresponde, se ajustan los precios de los ítems según la orden de compra.

---

#### **Manejo de Datos**

1. **Gestión de Ítems**
    
    - Los ítems se definen por un código, descripción, rubro, subrubro y unidad de medida.
    - Es posible agregar nuevos ítems o modificar sus descripciones.
2. **Gestión de Pedidos**
    
    - Los pedidos pueden ser filtrados por estado (pendiente, aprobado, rechazado, completado) y otras características.
3. **Gestión de Órdenes de Compra**
    
    - Las órdenes de compra incluyen detalles sobre precios, fechas y el estado actual.
    - Se gestionan por los responsables de compras y los administradores.
4. **Gestión de Remitos y Facturas**
    
    - El acceso a los remitos y facturas es similar al de las órdenes de compra, asegurando trazabilidad en todo el proceso.

---

#### **Resumen del Flujo**

1. **Necesidad detectada por el área → Pedido por ítems → Aprobación.**
2. **Creación de orden de compra → Asignación a proveedor o depósito.**
3. **Envío de mercadería → Recepción en depósito → Confirmación mediante remito firmado.**
4. **Actualización del estado del pedido y del stock.**

Este sistema permite gestionar eficientemente el flujo de compras, garantizando trazabilidad, control de inventarios y optimización del proceso.