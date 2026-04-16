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
|CRUD |1. CRUD Tipo Licencia<br>2. CRUD Karting<br>3. CRUD Localidad<br>4. CRUD Circuito<br>5. CRUD Torneo<br>6. CRUD Licencia<br>7. CRUD Persona<br>8. CRUD Reserva|
|CUU/Epic|1. Reservar un karting para un circuito<br>2. Anotarse a un torneo disponible<br>3. Registrar los resultados de una carrera y actualizar la tabla de puntos del torneo.|


### Alcance Adicional Voluntario


|Req|Detalle|
|:-|:-|


