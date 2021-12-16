# Descripción
Este caso de uso es activado cuando un Usuario desea utilizar la plataforma, para lo cual pasa primero por un proceso de autenticación y autorización.
# Actores
* Usuario
# Pre-condiciones
El Usuario debe estar registrado en el sistema y tener un Rol válido (Admin, Participante, Tutor, Facilitador o Mentor)
# Basic flow
1.	El Usuario inicia el caso de uso al dirigirse al URL de la plataforma
2.	La plataforma presenta los campos de autenticación soportados
3.	El Usuario llena sus credenciales e inicia la autenticación
4.	La plataforma realiza la autenticación y determina el tipo de rol asignado al usuario, en base a esto invoca al caso de uso “Mostrar Dashboard” y le pasa la información adquirida.
5.	El CU termina.
# Flujos Alternos
## Flujo Alterno 1: Usuario con credenciales erróneas
1.	En el punto 3 el usuario ingresa credenciales erróneas
2.	En el punto 4 el sistema informa de esto al usuario y vuelve a preguntar credenciales
3.	El CU termina.
# Post-conditions
* Existe en la sesión del usuario información respecto a quién es y qué Rol tiene.
# Requerimientos No Funcionales
* El CU debe soportar autenticación contra los registros en plataforma
* El CU debe soportar autenticación contra credenciales de Google
