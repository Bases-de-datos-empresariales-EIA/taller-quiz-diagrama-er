Gestión de Biblioteca Pública

Contexto del Negocio

Una biblioteca pública necesita un sistema para gestionar sus libros, los usuarios que los toman en préstamo, los préstamos y devoluciones, los bibliotecarios que administran los préstamos y las reservas de libros. El objetivo es mantener un registro preciso del inventario de libros y las transacciones de préstamo.

Descripción de los Elementos del Negocio

Libro
	•	Descripción: Libros disponibles en la biblioteca.
	•	Atributos Clave: ISBN, título, autor, año de publicación.

Usuario
	•	Descripción: Personas registradas en la biblioteca que pueden tomar libros en préstamo.
	•	Atributos Clave: ID del usuario, nombre, correo electrónico.

Préstamo
	•	Descripción: Registro de un libro prestado a un usuario.
	•	Atributos Clave: ID de préstamo, fecha de inicio, fecha de devolución, libro prestado, usuario.

Bibliotecario
	•	Descripción: Empleados que administran los préstamos de libros.
	•	Atributos Clave: ID del bibliotecario, nombre.

Reserva
	•	Descripción: Registro de libros reservados por usuarios antes de que estén disponibles.
	•	Atributos Clave: ID de reserva, fecha de reserva, usuario asociado, libro reservado.

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
