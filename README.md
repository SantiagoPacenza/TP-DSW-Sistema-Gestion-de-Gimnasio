# Propuesta TP DSW

## Grupo
### Integrantes
* 42212 - Rodríguez, Germán
* 51413 - Pacenza, Santiago
* 52889 - Cisneros, Juan Pablo

### Repositorios
* [frontend app]
* [backend app]

## Tema
Sistema de Gestión de gimnasio

### Descripción
*Aplicación web para la gestión de un gimnasio, que permitirá administrar planes de membresía, socios, entrenadores y rutinas personalizadas en base a un formulario inicial, así como la inscripción a clases de distintas disciplinas.*

### Modelo
Link al diagrama entidad-relacion: https://drive.google.com/file/d/1VfqnlyZBfzW0xp8UV3I-G1kObSFSzBxU/view

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Plan<br>3. CRUD Disciplina|
|CRUD dependiente|1. CRUD Membresía {depende de} CRUD Plan y CRUD Usuario(cliente)<br>2. CRUD Clase {depende de} CRUD Disciplina y CRUD Usuario(entrenador)|
|Listado<br>+<br>detalle| 1. Listado de solicitud de rutina de clientes filtrado por estado, muestra nombre del cliente, objetivo, fecha de solicitud y estado => detalle CRUD Solicitud<br>2. Listado de clases filtrado por disciplina, muestra día, horario, nombre del entrenador y disponibilidad => detalle CRUD Clase|
|CUU/Epic|1. Crear una rutina<br>2. Asignar una rutina a un cliente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Plan<br>3. CRUD Membresía<br>4. CRUD Pago<br>5. CRUD Disciplina<br>6. CRUD Clase<br>7. CRUD Categoría<br>8. CRUD Ejercicio<br>9. CRUD Solicitud<br>10. CRUD Rutina|
|CUU/Epic|1. Crear una rutina<br>2. Asignar una rutina a un cliente<br>3. Registrar membresía y pago<br>4. Realizar una inscripción a una clase|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros||
