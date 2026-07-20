# Sistema-extremo-a-extremo-FPGA-UART-Pluto-Tx-Rx.
Proyecto académico con bitácora de avance semanal
Semana 1
Fecha:8 - 12 de abril  del 2026

Actividades realizadas por cada integrante:
- Stiven Perez: Investigación inicial del tema del proyecto  
- Fernando Sánchez: Organización del equipo y planificación general  
- Jair Balseca: Apoyo en la investigación y definición de ideas  

Análisis de fallas y ajustes realizados:
- Falta de claridad inicial sobre el enfoque del proyecto pero se revisó información adicional y se discutieron ideas en grupo hasta definir una dirección

 Decisiones de diseño y justificación:
- Decisión: Definir el tema del proyecto y la estructura de trabajo en equipo  
- Justificación: Permite una mejor organización y avance progresivo durante el desarrollo

 Estado actual:
- Planificado: Formar el grupo y definir el tema del proyecto realizando una planificación inical completa.

  /////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Semana 2 (Fecha: 15 - 19 de abril de 2026)

Actividades realizadas:

* Se continuó con la investigación del sistema de comunicación UART en FPGA y su integración con el Pluto SDR.
* Se revisaron ejemplos y documentación sobre transmisión y recepción de datos (Tx/Rx).
* Se definieron con mayor claridad los objetivos específicos del proyecto.
* Se avanzó en la distribución de tareas entre los integrantes del grupo.

 Problemas encontrados:

* Dificultad para comprender completamente la interacción entre FPGA y el módulo Pluto SDR.
* Falta de experiencia práctica previa con este tipo de sistemas.

Decisiones tomadas:

* Profundizar en la investigación teórica antes de iniciar la implementación.
* Dividir el proyecto en etapas: comunicación UART, configuración de FPGA y pruebas de transmisión/recepción.

///////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////7

Semana 3 (Fecha: 22 - 26 de abril de 2026)

Actividades realizadas:

* Se inició el estudio práctico del protocolo UART y su funcionamiento en sistemas digitales.
* Se revisaron herramientas de desarrollo para FPGA y su entorno de programación.
* Se investigó la configuración básica del módulo Pluto SDR para transmisión y recepción de señales.
* Se realizaron pruebas iniciales de comunicación a nivel teórico mediante diagramas de bloques.

Problemas encontrados:

* Dificultad en la comprensión de la configuración inicial del entorno de desarrollo para FPGA.
* Limitaciones en el acceso a ejemplos prácticos claros para la integración con Pluto SDR.

Decisiones tomadas:

* Enfocar el trabajo en dominar primero la comunicación UART antes de integrar todos los componentes.
* Buscar documentación adicional y tutoriales más prácticos para facilitar el aprendizaje.

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


Semana 4 (Fecha: 29 de abril - 3 de mayo de 2026)

Actividades realizadas:

* Se avanzó en la comprensión de la transmisión y recepción de datos (Tx/Rx) en UART.
* Se realizaron pruebas básicas de simulación del comportamiento de la comunicación.
* Se organizó mejor la estructura del proyecto y los próximos pasos a seguir.
* Se investigaron posibles herramientas de simulación y depuración.

Problemas encontrados:

* Errores iniciales en la interpretación de señales Tx y Rx.
* Dificultad para validar resultados sin implementación física completa.

Decisiones tomadas:

* Continuar con simulaciones antes de pasar a pruebas físicas.
* Refinar la comprensión de las señales digitales involucradas en UART.

Estado actual:

* En proceso de investigación y preparación técnica para la implementación del sistema.
* Se tiene una mejor comprensión general del funcionamiento del proyecto.

 Semana 5 (Fecha: 6 - 10 de mayo de 2026)

Actividades realizadas:

* Se inició la etapa de implementación del sistema de comunicación UART dentro del entorno de desarrollo para FPGA.
* Se realizó la configuración inicial de los módulos de transmisión (Tx) y recepción (Rx).
* Se ejecutaron pruebas preliminares para verificar el envío y recepción de datos entre bloques del sistema.
* Se documentaron los primeros resultados obtenidos durante la implementación.

Problemas encontrados:

* Se presentaron errores iniciales en la sincronización de transmisión y recepción de datos.
* Fue necesario revisar parámetros de configuración para mejorar la comunicación del sistema.

Decisiones tomadas:

* Ajustar los parámetros del sistema UART para optimizar la transmisión de datos.
* Continuar con pruebas incrementales para detectar y corregir errores de manera progresiva.

Estado actual:

* Implementación inicial completada satisfactoriamente.
* El sistema presenta avances funcionales en comunicación básica y continúa en fase de pruebas.

* {Semana 6 (Fecha: 11 - 15 de mayo de 2026)}

{Actividades realizadas:}

* Se continuó con el desarrollo del módulo transmisor UART.
* Se implementó el módulo receptor UART.
* Se realizaron simulaciones funcionales para validar ambos módulos.
* Se verificó la correcta detección de bits de inicio y parada.

Problemas encontrados:}

* Se detectaron errores durante la recepción de algunos datos.
* Fue necesario ajustar la lógica de sincronización del receptor.

{Decisiones tomadas:}

* Modificar la lógica de muestreo del receptor UART.
* Continuar validando el sistema mediante simulaciones.

{Estado actual:}

* Los módulos Tx y Rx funcionan de forma independiente.
* Continúan las pruebas de integración.

{Semana 7 (Fecha: 18 - 22 de mayo de 2026)}

{Actividades realizadas:}

* Se integraron los módulos transmisor y receptor.
* Se realizaron pruebas internas de comunicación.
* Se verificó el intercambio correcto de información.
* Se registraron los resultados obtenidos.

{Problemas encontrados:}

* Se detectaron pequeños desfases durante la comunicación.
* Fue necesario ajustar señales de control.

{Decisiones tomadas:}

* Optimizar la sincronización entre módulos.
* Mantener pruebas continuas del sistema.

{Estado actual:}

* La comunicación UART básica funciona correctamente.
* El sistema continúa en optimización.

{Semana 8 (Fecha: 25 - 29 de mayo de 2026)}

{Actividades realizadas:}

* Se optimizó el código desarrollado en VHDL.
* Se eliminaron advertencias de síntesis.
* Se ejecutaron nuevas simulaciones.
* Se verificó el rendimiento general del sistema.

{Problemas encontrados:}

* Persistieron algunas advertencias durante la síntesis.
* Fue necesario reorganizar parte del código.

\textbf{Decisiones tomadas:}

* Simplificar la lógica implementada.
* Mantener una estructura modular del diseño.

{Estado actual:}

* El código presenta un mejor desempeño.
* La implementación continúa avanzando.

{Semana 9 (Fecha: 1 - 5 de junio de 2026)}

{Actividades realizadas:}

* Se programó la FPGA con el diseño desarrollado.
* Se configuró el archivo de restricciones (XDC).
* Se realizaron pruebas en hardware.
* Se verificó la correcta asignación de pines.

{Problemas encontrados:}

* Se detectaron errores en la configuración de algunos pines.
* Fue necesario revisar el archivo de restricciones.

{Decisiones tomadas:}

* Corregir la asignación de pines.
* Repetir las pruebas sobre la FPGA.

{Estado actual:}

* La FPGA ejecuta correctamente el diseño implementado.
* El sistema responde de forma estable.

  {Semana 10 (Fecha: 8 - 12 de junio de 2026)}

{Actividades realizadas:}

* Se realizaron pruebas de comunicación con el puerto serial.
* Se verificó el envío y recepción de caracteres.
* Se documentaron los resultados obtenidos.
* Se evaluó la estabilidad de la comunicación.

{Problemas encontrados:}

* Se observaron pérdidas ocasionales de información.
* Fue necesario revisar la velocidad de transmisión.

{Decisiones tomadas:}

* Ajustar el Baud Rate utilizado.
* Repetir las pruebas bajo diferentes condiciones.

{Estado actual:}

* La comunicación presenta un funcionamiento estable.
* Continúan las pruebas de validación.


{Semana 11 (Fecha: 15 - 19 de junio de 2026)}

{Actividades realizadas:}

* Se evaluó el comportamiento del sistema con diferentes velocidades.
* Se registraron los tiempos de respuesta.
* Se compararon los resultados obtenidos.
* Se verificó la estabilidad del sistema.

{Problemas encontrados:}

* Se presentaron pérdidas de datos a velocidades elevadas.
* Fue necesario limitar algunos parámetros de operación.
{Decisiones tomadas:}

* Mantener una velocidad estable para garantizar la comunicación.
* Continuar realizando pruebas de rendimiento.

{Estado actual:}

* El sistema presenta un funcionamiento confiable.
* Se continúa optimizando el desempeño.
