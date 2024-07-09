# Automatizacion-de-Tanques-de-Preparacion-y-Dosificacion
Este repositorio contiene el programa desarrollado en lenguaje Ladder utilizando TIA Portal para la automatización de un sistema de preparación y dosificación de tanques. El sistema está equipado con interfaces HDMI para la visualización y un sistema SCADA para el monitoreo y control en tiempo real.
Características Principales

Automatización del Tanque 1:

Inicio de la preparación cuando se presiona P1 y se cumplen todas las condiciones de seguridad y niveles requeridos.
Dosificación secuencial utilizando básculas 1 y 2 con un peso máximo de 100kg para báscula 1 y 5kg para báscula 2.
Control preciso del peso de los componentes de la receta y agitación del contenido antes de transferir al tanque 1.

Automatización del Tanque 2:

Inicio de la preparación cuando se presiona P3 y se cumplen todas las condiciones de seguridad y niveles requeridos.
Dosificación secuencial utilizando básculas 1, 2, y 3 con un peso máximo de 100kg para báscula 1, 5kg para báscula 2, y 40kg para báscula 3.
Control preciso del peso de los componentes de la receta, agitación del contenido y transferencias controladas entre básculas y tanque 2.

Instrucciones de Uso

Inicialización:

Verifique que no haya fallas en los sistemas y que los niveles de los tanques sean adecuados.
Presione P1 para iniciar la preparación del tanque 1 o P3 para iniciar la preparación del tanque 2.

Proceso de Dosificación:

El sistema verificará las condiciones y comenzará la dosificación de los componentes en las básculas.
Se realizarán cálculos precisos del peso de cada componente y se dosificará secuencialmente.
Agitación y Transferencia:

Una vez completada la dosificación, el sistema agitará el contenido de las básculas.
El contenido será transferido a los tanques respectivos después de cumplir el tiempo de agitación.

Finalización:

El proceso se completará y el sistema estará listo para la siguiente operación.
Archivos Incluidos
Programación en Ladder (TIA Portal): Código fuente del programa en Ladder para la automatización de los tanques.
