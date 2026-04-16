# Propuesta TP DSW

## Grupo
### Integrantes
* 51377 - Mirko Recchi
* 50176 - Matias Arrebillaga
* 53750 - Leandro Battocchio
* 54129 - Lucas Fernández

### Repositorios
* [frontend app](https://github.com/matiasArrebillaga/Managment-karting-frontend)
* [backend app](https://github.com/matiasArrebillaga/Managment-karting-backend)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
sistema de gestion de reserva de kartings con posibilidad de inscribirse a torneos trimestrales ligado a un sistema de licencias para manejar los karting.

### Modelo
<img width="1151" height="744" alt="Kartings-Management-MD" src="https://github.com/user-attachments/assets/d0deac7e-2a6e-4e92-8940-b28337ca5341" />



## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Licencia<br>2. CRUD Karting<br>3. CRUD Localidad<br>4. CRUD Circuito|
|CRUD dependiente|1. CRUD Licencia {depende de} CRUD Tipo Licencia<br>2. CRUD Persona {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de torneos disponibles filtrado por tipo de licencia, muestra id y tipo de licencia => detalle CRUD Torneo<br> 2. Listado de reservas filtrado por rango de fecha, muestra id de karting y nombre de la persona => detalle muestra datos completos de la reserva y de la persona|
|CUU/Epic|1. Reservar un karting para un circuito<br>2. Anotarse a un torneo disponible|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

