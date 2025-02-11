# Gestión de un Restaurante

## Contexto del Negocio

Un restaurante requiere un sistema para gestionar sus mesas, clientes, órdenes, platos del menú y empleados que atienden a los clientes. El objetivo es mantener un registro organizado de las órdenes, los clientes atendidos y los platos disponibles en el menú.

## Descripción de los Elementos del Negocio

### Mesa
- **Descripción:** Mesas disponibles en el restaurante.
- **Atributos Clave:** `idMesa`, `numeroMesa`, `capacidad`.

### Cliente
- **Descripción:** Personas que visitan el restaurante y realizan órdenes.
- **Atributos Clave:** `idCliente`, `nombre`, `correoElectronico` (opcional).

### Orden
- **Descripción:** Registro de los pedidos realizados por los clientes.
- **Atributos Clave:** `idOrden`, `fechaHora`, `cliente`, `mesa`, `empleado`.

### Empleado
- **Descripción:** Personas que trabajan en el restaurante y atienden a los clientes.
- **Atributos Clave:** `idEmpleado`, `nombre`, `rol`.

### Plato
- **Descripción:** Platos disponibles en el menú del restaurante.
- **Atributos Clave:** `idPlato`, `nombre`, `precio`.

### DetalleOrden
- **Descripción:** Registro de los platos pedidos en cada orden.
- **Atributos Clave:** `idDetalle`, `ordenAsociada`, `plato`, `cantidad`.

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
