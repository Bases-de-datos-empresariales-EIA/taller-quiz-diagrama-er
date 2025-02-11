Gestión de Clínica Dental

Contexto del Negocio

Una clínica dental requiere un sistema para gestionar a sus pacientes, los dentistas que trabajan en la clínica, las citas programadas, los tratamientos que se realizan en cada cita y los pagos asociados a los servicios prestados. El objetivo es mantener un registro organizado de las citas, los tratamientos realizados y los pagos de los pacientes.

Descripción de los Elementos del Negocio

Paciente
	•	Descripción: Personas que reciben tratamiento en la clínica.
	•	Atributos Clave: ID del paciente, nombre, correo electrónico, teléfono.

Dentista
	•	Descripción: Profesionales de la salud que atienden a los pacientes.
	•	Atributos Clave: ID del dentista, nombre, especialidad.

Cita
	•	Descripción: Registro de una cita programada entre un paciente y un dentista.
	•	Atributos Clave: ID de cita, fecha, hora, paciente, dentista.

Tratamiento
	•	Descripción: Procedimiento realizado durante una cita.
	•	Atributos Clave: ID del tratamiento, descripción, costo, cita asociada.

Pago
	•	Descripción: Registro de pagos realizados por los pacientes.
	•	Atributos Clave: ID de pago, monto, fecha de pago, paciente.

Instrucciones
	1.	Construya en Figma o a mano el diagrama Entidad-Relación del negocio descrito anteriormente siguiendo el estándar explicado en clase (70%).
	2.	Justifique la elección de cada tipo de relación (one-to-one, one-to-many, many-to-many) (10%).
	3.	Justifique por qué cada tabla es transaccional o maestra (20%).

Estándar de construcción del diagrama E-R
	•	Entidades: PascalCase.
	•	Campos: camelCase.
	•	Cada relación “one” debe ser denotada en la fuente con un singular y llevar un círculo en el destino.
	•	Cada relación “many” debe ser denotada en la fuente con un plural y llevar un triángulo en el destino.
	•	Cada entidad maestra es de color verde (si el diagrama es a mano, el estudiante debe especificarlo).
	•	Cada entidad transaccional es de color púrpura (si el diagrama es a mano, el estudiante debe especificarlo).
