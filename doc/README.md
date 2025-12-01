# MANUAL DE USUARIO 
 Este manual explica de forma clara y sencilla cómo funciona el sistema de reservas del cine La Pantalla Mágica, diseñado para que cualquier persona pueda usarlo sin conocimientos previos de programación.

## ¿Qué es el sistema?
###  Es un programa que permite:
- Registrar usuarios.
 - Reservar asientos para diferentes películas.
- Cancelar reservas.
- Consultar las funciones disponibles.
- Llevar un control administrativo (solo para personal autorizado).
#####  Se maneja mediante un menú interactivo, donde cada número corresponde a una acción diferente.

## ¿Cómo está organizado el sistema?
### El sistema usa un menú principal con 6 opciones:
1. Registrar Usuario
2. Registrar Reserva
3. Cancelar Reserva
4. Consultar Funciones
5. Administrador
6. Salir

#####  Cada opción ejecuta un proceso distinto, explicado a continuación.

## Opción 1 — Registrar Usuario
Esta es la primera acción que debe realizar cualquier persona que quiera reservar un asiento.

### Paso a paso
1. El sistema solicita el nombre del usuario.
   - Debe contener solo letras y tener mínimo 3 caracteres.
2. El sistema solicita el apellido del usuario  
   - Debe contener solo letras y tener mínimo 3 caracteres.
3. El sistema solicita la cédula.
   - Debe contener únicamente números (Mínimo 3 y máximo 15 dígitos)
4. El sistema muestra los tipos de vínculo y sus precios:
* Estudiante → $7.500
* Docente → $10.000
* Administrativo → $8.500
* Oficial interno → $7.000
* Público externo → $15.000
#### El usuario digita una opción entre 1 y 5.
5.  - Si toda la información es válida, el sistema registra al usuario y muestra:
"Usuario registrado correctamente."
    - Si algún dato es incorrecto:
El sistema muestra un mensaje de error y cancela el registro.

## Opción 2 — Registrar Reserva
Permite escoger una película, ver su sala y elegir un asiento.
### Paso a paso
1. El sistema pide el documento del usuario.
Verifica si el usuario está registrado:
- Si está registrado → continúa.
- Si no está registrado → lo devuelve al menú y le indica que debe registrarse primero.
2. Se muestran las películas disponibles, por ejemplo:
- Interstellar
- Batman
- Oppenheimer
- Kung Fu Panda
3. El usuario selecciona una película.
  
4. El sistema imprime la sala correspondiente:
    O = asiento disponible
    X = asiento ocupado
5. El usuario ingresa:
    Fila, Columna 
6. El sistema valida:
- Si el asiento esta en O → se marca como X y se guarda la reserva.
- Si el asiento esta en X → muestra “Asiento no disponible” y no permite seleccionarlo.
7. Se confirma la reserva y se informa el precio según el tipo de vínculo del usuario.

## Opción 3 — Cancelar Reserva
Sirve para liberar un asiento previamente reservado.
### Paso a paso
#### El sistema pide el documento.
1. Verifica si existe una reserva registrada para ese usuario.
2. Solicita identificar la reserva (película/asiento).
3. - Si la reserva existe: El asiento vuelve a estar disponible, La reserva se elimina del historial.
   - Si la reserva no existe: El sistema le pide verificar la información.

## Opción 4 — Consultar Funciones
Permite ver la cartelera disponible del cine.
1. El usuario puede consultar:
- Películas disponibles.
- Salas.
- Horarios (si están incluidos).
- Asientos actuales (solo lectura).

## Opción 5 — Administrador
#### Esta opción está protegida con usuario y contraseña exclusivos del administrador.
1. Puede ver
 - Total de reservas registradas
 - Total de tiquetes vendidos
 - Total de reservas realizadas
 - Total pago realizado
 - Promedio por venta diario del cine
 - Lista de usuarios
 - Usuario con mayor cantidad de reservas y menor cantidad de reservas
2. Si las credenciales son incorrectas
 - Acceso denegado.

## Opción 6 — Salir
Cierra el programa.


## Recomendaciones para un buen funcionamiento 
* Siempre registre sus datos antes de intentar reservar.
* Revise bien la sala antes de elegir un asiento.
* Si un asiento aparece como X, significa que ya fue ocupado.
* Tenga presente el codigo de reserva en caso de necesitar cancelar.
* El sistema lo identificara con su documento de identidad 
