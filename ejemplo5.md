# Gestión de una Tienda en Línea

## Contexto del Negocio

Una tienda en línea necesita un sistema para gestionar sus productos, clientes, órdenes de compra, pagos y envíos. El objetivo es mantener un registro detallado del inventario, las ventas realizadas y la logística de entrega de los pedidos.

## Descripción de los Elementos del Negocio

### Producto
- **Descripción:** Artículos disponibles en la tienda para la venta.
- **Atributos Clave:** `idProducto`, `nombre`, `precio`, `stockDisponible`.

### Cliente
- **Descripción:** Personas que compran productos en la tienda en línea.
- **Atributos Clave:** `idCliente`, `nombre`, `correoElectronico`, `direccion`.

### Orden
- **Descripción:** Registro de las compras realizadas por los clientes.
- **Atributos Clave:** `idOrden`, `fechaCompra`, `cliente`.

### DetalleOrden
- **Descripción:** Registro de los productos comprados en una orden específica.
- **Atributos Clave:** `idDetalle`, `ordenAsociada`, `producto`, `cantidad`, `precioUnitario`.

### Pago
- **Descripción:** Registro de los pagos realizados por los clientes.
- **Atributos Clave:** `idPago`, `monto`, `fechaPago`, `metodoPago`, `ordenAsociada`.

### Envío
- **Descripción:** Registro de los envíos de las órdenes procesadas.
- **Atributos Clave:** `idEnvio`, `direccionEntrega`, `fechaEnvio`, `transportista`, `ordenAsociada`.

## Instrucciones

1. Construya en **Figma** o a mano el diagrama **Entidad-Relación** del negocio descrito anteriormente siguiendo el estándar explicado en clase **(70%)**.
2. Justifique la elección de cada tipo de relación (**one-to-one**, **one-to-many**, **many-to-many**) **(10%)**.
3. Justifique por qué cada tabla es **transaccional** o **maestra** **(20%)**.

## Estándar de construcción del diagrama E-R

- **Entidades:** `PascalCase`.
- **Campos:** `camelCase`.
- Cada relación **"one"** debe ser denotada en la fuente con un **singular** y llevar un **círculo** en el destino.
- Cada relación **"many"** debe ser denotada en la fuente con un **plural** y llevar un **triángulo** en el destino.
- Cada **entidad maestra** es de color **verde** (si el diagrama es a mano, el estudiante debe especificarlo).
- Cada **entidad transaccional** es de color **púrpura** (si el diagrama es a mano, el estudiante debe especificarlo).
