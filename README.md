# Propuesta TP DSW

## Grupo
### Integrantes
* 42212 - Rodríguez, Germán
* 50460 - Aguirres, Bautista
* 51413 - Pacenza, Santiago
* 52889 - Cisneros, Juan Pablo

### Repositorios
* [frontend app]
* [backend app]

## Tema
Sistema de Gestión de gimnasio

### Descripción
*Aplicación web para la gestión de un gimnasio, que permitirá administrar planes de membresía, socios, entrenadores, rutinas, y dietas personalizadas en base a un formulario inicial, así como la inscripción a clases de distintas disciplinas.*

### Modelo
Link al diagrama entidad-relacion: https://drive.google.com/file/d/1quuuroTxIEoXwH3phTveIiNF5PbdPytR/view

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Plan<br>3. CRUD Disciplina<br>4. CRUD Categoría|
|CRUD dependiente|1. CRUD Membresía {depende de} CRUD Plan y CRUD Cliente<br>2. CRUD Clase {depende de} CRUD Disciplina y CRUD Entrenador|
|Listado<br>+<br>detalle| 1. Listado de formularios de clientes filtrado por estado, muestra nombre, objetivo y estado => detalle CRUD FormularioCliente<br>2. Listado de clases filtrado por entrenador, muestra nombre de la clase, horario, duración y disponibilidad => detalle CRUD Clase|
|CUU/Epic|1. Crear una rutina<br>2. Asignar una rutina a un cliente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Entrenador<br>2. CRUD Cliente<br>3. CRUD Plan<br>4. CRUD Membresía<br>5. CRUD Pago<br>6. CRUD FormularioCliente<br>7. CRUD Clase<br>8. CRUD Disciplina<br>9. CRUD Rutina<br>10. CRUD Ejercicio<br>11. CRUD Categoría|
|CUU/Epic|1. Crear una rutina<br>2. Asignar una rutina a un cliente<br>3. Registrar membresía y pago<br>4. Realizar una inscripción a una clase|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros||
