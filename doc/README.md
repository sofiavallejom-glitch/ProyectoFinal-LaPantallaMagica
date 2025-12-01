# MANUAL DE USUARIO 
 Este manual explica de forma clara y sencilla cómo funciona el sistema de reservas del cine La Pantalla Mágica, diseñado para que cualquier persona pueda usarlo sin conocimientos previos de programación.

## ¿Qué es el sistema?
###  Es un programa que permite:
- Registrar usuarios.
 - Reservar asientos para diferentes películas.
- Cancelar reservas.
- Consultar las funciones disponibles.
- Llevar un control administrativo (solo para personal autorizado).
### Se maneja mediante un menú interactivo, donde cada número corresponde a una acción diferente.

## ¿Cómo está organizado el sistema?
### El sistema usa un menú principal con 6 opciones:
1. Registrar Usuario
2. Registrar Reserva
3. Cancelar Reserva
4. Consultar Funciones
5. Administrador
6. Salir

### Cada opción ejecuta un proceso distinto, explicado a continuación.

## Opción 1 — Registrar Usuario
Esta es la primera acción que debe realizar cualquier persona que quiera reservar un asiento.

### ✔️Paso a paso
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

### Si toda la información es válida, el sistema registra al usuario y muestra:
"Usuario registrado correctamente."

### Si algún dato es incorrecto:
El sistema muestra un mensaje de error y cancela el registro.

## Opción 2 — Registrar Reserva
Permite escoger una película, ver su sala y elegir un asiento.
### ✔️ Paso a paso
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
- O = asiento disponible
- X = asiento ocupado
5. El usuario ingresa:
- Fila, Columna 
6. El sistema valida:
- Si el asiento está O → se marca como X y se guarda la reserva.
- Si está X → muestra “Asiento no disponible” y no permite seleccionarlo.
7. Se confirma la reserva y se informa el precio según el tipo de vínculo del usuario.

## Opción 3 — Cancelar Reserva
Sirve para liberar un asiento previamente reservado.

### ✔️ Paso a paso
El sistema pide el documento.

Verifica si existe una reserva registrada para ese usuario.

Solicita identificar la reserva (película/asiento).

Si la reserva existe:

El asiento vuelve a estar disponible (X → O).

La reserva se elimina del historial.

Muestra un mensaje de cancelación exitosa.

Si el usuario intenta cancelar un asiento que nunca reservó:

El sistema le pide verificar la información.

🟦 6. Opción 4 — Consultar Funciones

Permite ver la cartelera disponible del cine.

El usuario puede consultar:

Películas disponibles.

Salas.

Horarios (si están incluidos).

Asientos actuales (solo lectura).

📌 Esta opción no modifica nada del sistema.

🟦 7. Opción 5 — Administrador

Esta opción está protegida con:

Usuario y contraseña exclusivos del administrador.

✔️ Qué puede ver el administrador

Lista de todos los usuarios registrados.

Reservas realizadas (historial completo).

Total de dinero recaudado según las reservas activas.

Información detallada de cada vinculación y precios pagados.

❌ Si las credenciales son incorrectas

Acceso denegado.

🟦 8. Opción 6 — Salir

Cierra el programa.

🟫 9. Resumen visual del funcionamiento general

El usuario se registra.

El usuario elige película y asiento.

El sistema verifica disponibilidad.

Si el asiento está libre → se reserva.

El usuario puede:

Consultar funciones

Cancelar su reserva

El administrador puede ver:

Usuarios

Reservas

Dinero total

🟧 10. Recomendaciones para nuevos usuarios

Siempre registre sus datos antes de intentar reservar.

Revise bien la sala antes de elegir un asiento.

Si un asiento aparece como X, significa que ya fue ocupado.

Anote su fila y columna en caso de necesitar cancelar.

Mantenga su documento a la mano, el sistema lo usa como identificación
