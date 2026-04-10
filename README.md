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
Link al diagrama entidad-relacion: https://drive.google.com/file/d/1Kj_Ur9eNGBPWh26qf4SX6UqjvhjXIxX_/view?usp=sharing

## Alcance Funcional

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Plan<br>3. CRUD Alimento<br>4. CRUD Ejercicio|
|CRUD dependiente|1. CRUD Rutina {depende de} CRUD Ejercicio<br>2. CRUD Dieta {depende de} CRUD Alimento|
|Listado<br>+<br>detalle| 1. Listado de formularios de clientes filtrado por estado, muestra nombre, objetivo y estado => detalle CRUD FormularioCliente<br>2. Listado de clases filtrado por entrenador, muestra nombre de la clase, horario, duración y disponibilidad => detalle CRUD Clase|
|CUU/Epic|1. Realizar una inscripción a una clase<br>2. Asignar una rutina a un cliente|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Plan<br>3. CRUD Membresía<br>4. CRUD Pago<br>5. CRUD FormularioCliente<br>6. CRUD RelaciónClienteEntrenador<br>7. CRUD Clase<br>8. CRUD Inscripción<br>9. CRUD Rutina<br>10. CRUD Ejercicio<br>11. CRUD Categoría<br>12. CRUD EjercicioRutina<br>13. CRUD Dieta<br>14. CRUD Alimento<br>15. CRUD AlimentoDieta|
|CUU/Epic|1. Realizar una inscripción a una clase<br>2. Asignar una rutina a un cliente<br>3. Registrar membresía y pago<br>4. Asignar una dieta a un cliente|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros||
