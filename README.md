# *Proyecto Final*
## **Cinema The Friends**

### Integrantes:
* Santiago Mejia Guerra
>* Hola soy Santiago Mejia Me gusta mucho la Universidad de Antioquia estoy aprendiendo demasiado y me esta desarrollando mucho el pensamiento cognitivo.
* Marilyn Rios David
>* Hola soy marilyn y me gusta mucho aprender cosas nuevas, quiero sacarle mucho provecho a la materia algoritmia y programacion, es muy divertida.

### Vinculos academicos y descripcion:
* Santiago Mejia Guerra
>* Estudiante UdeA de ingenieria industrial, tengo habilidad en ajedrez y fortalezas en administracion, contabilidad y finanzas.

* Marilyn Rios David
>* Estudiante UdeA de ingenieria industrial, tengo algo de habilidad en el dibujo y escritura,  mis fortalezas son la constancia y resiliencia.

### Nombre del proyecto y detalles: 
* Nombre: The Friends
* Descripcion: creacion de un espacio cinematográfico también conocido como cinema, para ofrecer a la comunidad universitaria la capacidad de asistir a cine en las inmediaciones
de la ciudadela universitaria los fines de semana. Permitiendo registrar usuarios, consultar la disponibilidad de películas para el próximo fin de semana, crear reservas, cancelar reservas, imprimir facturas, y mostrar el estado administrativo de los ingresos y del servicio de cine en la UdeA.
<img width="352" height="352" alt="image" src="https://github.com/user-attachments/assets/b7282ccb-fcbc-4d8e-a770-302e243c15e4" />

### Licencia del software:
<a href="https://github.com/santiagomejia3-glitch/The-Friends">The Friends</a> © 2025 by <a href="https://github.com/santiagomejia3-glitch,https://github.com/marilynrios-dev">Santiago Mejia Guerra, Marilyn Rios David</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

### Reporte de vision: 
#### Objetivo:
* Desarrollar un cine para la universidad de Antioquia llamado The Friends, en donde los usuarios puedan tener una experiencia organizada en la asignación de los puestos, las reservas, consultas y  cancelaciones de las funciones cinematograficas.

#### Beneficios:
* Controlar la programación  de la sala de cine.
* Fomentar la cultura de ver cine en la Universidad de Antioquia.
* Facilitar la compra, la asignacion, la cancelación, la visualización y consultas  de puestos.
  
### Especificacion de requisitos:
#### Requisitos funcionales: 
* Registrar usuarios y reservas, cancelar reservas, consultar funciones de fines de semana de los diferentes usuarios
* Funciones del administrador: llevar control estadistico de totales de reservas asignadas, tiquetes vendidos, reservas realizadas, pago realizado, promedio de venta diaria del cine, usuarios con  mayor y menor cantidad de reservas.
#### Requisitos no funcionales: 
* Debe haber proteccion de datos personales
* El software debe verse desde diferentes componentes tecnologicos como computadoras, tablets y celulares.
* El software debe de ser facil de usar.
### Diagrama de Gantt y presupuesto			
#### Diagrama de Gant:
<img width="1687" height="301" alt="image" src="https://github.com/user-attachments/assets/ec8471db-1e31-422f-85d8-aa0a9cb01e3e" />

#### Presupuesto:
<img width="398" height="101" alt="image" src="https://github.com/user-attachments/assets/c9dc4630-9ca0-45b5-9f97-41f8f9854ed1" />

### Plan de versionado:
#### v.1 -Estructura base (13/11/2025) 
1. Creación de la función CrearCinema()
2. Creación de la función ImprimirSalaCine()
3. Creación del menú utilizando match case
#### v.2 -Creación de la factura (17/11/2025) 
#### v.3 -Registro de usuario (19/11/2025) 
Case 1
1. Creación del diccionario de usuario vacío
2. Creación de la validación del nombre
3. Creación de la validación del apellido 
4. Creación de la validación del documento
5. Creación de opción de escoger el tipo de vinculo
Agregado:
Al diccionario con llave documento la información obtenida
#### v.2 -Registro de reserva (21-23/11/2025) 
Case 2:
1. Creación del diccionario de reserva vacío
2. Creación de la restricción que no deja hacer la reserva a usuarios no registrados
3. Creación de la opción para seleccionar películas
4. Creación de la selección de fila y columna del asiento
5. Creación de la verificación de asientos disponibles  
6. Creacion de la ocupacion de asientos
Agregado:
7. Al diccionario de reserva con llave documento la información obtenida
8. la factura
#### v.3 -Cancelación de reserva (25/11/2025) 
Case 3:
1. Creación de la restricción que no deja cancelar reserva a usuarios sin reserva
2. Creación de la validacion de usuario registrado
3. Creación de la visualización de reservas existentes  
4. Creación de la selección de reserva a cancelar 
5. Creación de la liberacion del asiento
6. Creacion de la eliminacion de la reserva 
#### v.4 -Consultar funciones fin de semana (27/11/2025) 
Case 4:
1. Creación de la lista de funciones programadas
2. Creación de la tabla con información: idpelicula, día, hora, nombre película y asientos disponibles
3. Creación del contador total de funciones
4. Creación de contador de películas en cartelera
#### v.5 - Administrador (28-30/11/2025) 
Case 5: 
1. Creacion del diccionario de administrador para validación
2. Creación del sistema de autentificacion con usuario y contraseña 
3. Creación del submenú


