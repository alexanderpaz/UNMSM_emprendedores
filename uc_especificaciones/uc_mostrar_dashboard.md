# Descripción
Este CU muestra un resumen del contenido, actividades y avance del programa para los usuarios debidamente autenticados y autorizados del sistema que se encuentren matriculados en un programa.
# Actores
* Usuario 
# Pre-condiciones
El Usuario debe estar autenticado, autorizado y matriculado en un programa. 
# Flujo Básico
1.	El actor inicia el CU al pedir al sistema se muestre su dashboard
2.	El sistema muestra el dashboard del usuario con el siguiente detalle:
    a.	Nombres y apellidos completos del usuario
    b.	Tipo y edición del programa en el que está inscrito
    c.	Avance del programa
    d.	Talleres
    e.	Mentorías
    f.	Mensajería interna
    g.	Calificaciones
    h.	Calendario de actividades
    i.	Herramientas externas
3.	El CU termina
# Post-condiciones
1.	El Sistema queda en capacidad de ejecutar los CUs relacionados con las opciones desplegadas en el dashboard.
2.	Se mantiene la sesión del usuario en el sistema
# Requerimientos No Funcionales
1.	El dashboard podrá ser consumido desde los siguientes dispositivos:
    a.	Web browser
    b.	Tablet
    c.	Teléfono