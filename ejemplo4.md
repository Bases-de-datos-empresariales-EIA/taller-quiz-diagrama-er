# Gestión de un Hospital

## Contexto del Negocio

Un hospital necesita un sistema para gestionar a sus pacientes, médicos, citas médicas, tratamientos y los historiales médicos de los pacientes. El objetivo es mantener un registro organizado de las consultas médicas y los tratamientos recibidos por cada paciente.

## Descripción de los Elementos del Negocio

### Paciente
- **Descripción:** Personas que reciben atención médica en el hospital.
- **Atributos Clave:** `idPaciente`, `nombre`, `fechaNacimiento`, `correoElectronico`.

### Médico
- **Descripción:** Profesionales de la salud que atienden a los pacientes.
- **Atributos Clave:** `idMedico`, `nombre`, `especialidad`.

### Cita
- **Descripción:** Registro de una consulta médica programada entre un paciente y un médico.
- **Atributos Clave:** `idCita`, `fecha`, `hora`, `paciente`, `medico`.

### Tratamiento
- **Descripción:** Procedimiento médico o medicamento prescrito durante una consulta.
- **Atributos Clave:** `idTratamiento`, `descripcion`, `costo`, `citaAsociada`.

### HistorialMédico
- **Descripción:** Registro de las enfermedades y tratamientos previos de un paciente.
- **Atributos Clave:** `idHistorial`, `paciente`, `fechaCreacion`, `observaciones`.

### Factura
- **Descripción:** Registro de los pagos realizados por los pacientes por sus tratamientos.
- **Atributos Clave:** `idFactura`, `monto`, `fechaPago`, `paciente`.

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
