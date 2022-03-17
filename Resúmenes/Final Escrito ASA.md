# Final ASA escrito

1. Etapas de metodologia de estudio de sistemas: tareas, tecnicas y herramientas de la etapa de construccion o programacion.

- Tareas:

    - Desarrollo de logica de los programas
    - Codificar
    - Elaborar datos de prueba
    - Preparar datos, archivos y resultados esperados
    - Realizar prueba de sistema
    - Documentar, definir metodos de archivo
    - Elaborar normas de procedimiento
    - Diseñar y probar los formularios y registros

- Tecnicas y herramientas:

    - Tecnicas de programacion
    - Diagramacion logica
    - Tecnicas de documentacion
    - Tecnicas de diseño de formularios
    - Tecnicas de diseño, organizacion y estructuracion de archivos
    - Tecnicas de diseño de registros manuales
    - Normas de emision de informes.

2. Herramientas para la logica de procesos: caracteristicas, ventajas y desventajas del pseudolenguaje

El pseudolenguaje o lenguaje estructurado permite definir la logica mediante el uso de un lenguaje mas natural, que mantiene algunas reglas de los lenguajes de computacion, pero aproximandose al del usuario para que pueda entenderlo. Su estructura se realiza:

> Si *condicion* entonces *accion
>
>>sino *accion2*
>
>  finsi

- Ventajas:

    - Tiene una verificacion de la logica buena
    - Representa muy bien la estructura logica
    - Su facilidad de uso es buena para quien lo acostumbre a usar
    - Se convierte muy facilmente a un programa, dado que por lo general la sintaxis es bastante similar
    - Es facil poder hacer cambios y modificaciones

- Desventajas:

    - Su verificacion por el usuario es mala
    - Se tienen que poner varias reglas, lo que puede generar un lenguaje mas complejo que el mismo lenguaje de programacion
    - Puede ser muy extenso al describirlo, siendo posible ser mas sintetico usando otras herramientas.

3. Ciclo de vida de los sistemas: desarrollar los aspectos relacionados con el mantenimiento

Luego de iniciar la operacion del nuevo sistema, se desarrolla el control de la puesta en marcha y se evaluan los primeros resultados de este ultimo. Se identifican y realizan los ajustes necesarios al nuevo sistema, lleva a cabo la prueba de aceptacion, corrigen y completan los manuales de procedimiento y la documentacion, para entregar el sistema al usuario.

La documentacion a usar son los manuales de uso y tecnicos, el informe de usuario que detalle las diferencias detectadas entre los objetivos y el requerimiento y el resultado obtenido, un formulario de solicitud de mejoras o cambios, el acta de recepcion del sistema que deje constancia de que la empresa recibio el sistema, y por ultimo el informe final del analista que detalle los resultados obtenidos al implementar el nuevo sistema.

Participan los usuarios directos y el analista de sistemas, con la supervisacion del jefe de proyecto y la comunicacion con el gerente, ademas de la participacion de los programadores para realizar los ajustes que surgiesen como necesarios.

4. Tipos de archivos segun los datos: enumerarlos y dar un ejemplo de cada uno

- Maestros: contienen informacion permantente de los datos que constituyen la base de un sistema de informacion. Por ejemplo, datos de clientes.
- Auxiliares: facilitan el empleo de determinados datos que se pueden codificar de manera simple. Un ejemplo de estos archivos lo comprenden las tablas de comprobantes.
- Operaciones: comprenden el conjunto de informacion detallada de un sistema, y actualizan los archivos maestros, tales como la carga de un comprobante de un proveedor.
- Temporales: se usan por razones operativas, pudiendo ser eliminadas luego de haber cumplido su proposito. Por ejemplo, el borrador de un asiento contable, el cual se elimina al hacerse definitivo
- Control: su funcion es la de conservar datos necesarios y controlar procesos. Un ejemplo es el ultimo numero de cliente.

5. Seguridad: definir seguridad y enumerar las amenazas intencionales

La seguridad se considera a un conjunto de medidas preventivas, detectivas y correctivas, que protegen los recursos o activos informaticos, tanto el sistema fisico, sus aplicaciones, las personas y la informacion, usando un plan de seguridad. Dicho plan no es infalible, pero permite asegurar la continuidad de trabajo, limitar las consecuencias de una amenaza concretada, y recuperar la capacidad de trabajo en el menor tiempo posible y al menor costo.

Las amenazas intencionales que afectan al sistema son:

- Perjuicio con motivacion economica: se realiza una intromision o daño al sistema por motivos economicos, ya sea un rescate monetario por encriptacion de datos, un daño realizado para forzar a pagar un sistema de seguridad especifico, como la fuga de informacion para ser vendida a competidores.
- Perjuicio sin motivacion economica: en este caso no se persigue un fin material si no exponer o filtrar datos sensibles de la empresa, dañar software y hardware o utilizar dichos recursos para otros ataques.  
- Invasion a la privacidad: dicha invasion permite a los atacantes obtener acceso a datos personales de la empresa y los entes con los que se relaciona, ademas de datos de los usuarios y la estructura de dicha organizacion, que pueden ser usados para otros fraudes como para robo de identidad.

6. Papel del analista como agente de cambio

El analista se encarga de recoger los requerimientos de una organizacion para un sistema determinado, analizar y detallar dichos requerimientos, el orden de la empresa, sus elementos y relaciones, evaluar el sistema existente y sus relaciones con los modulos, para luego poder comunicar dichas necesidades a los programadores para el diseño del nuevo sistema, y luego corroborar que dicho sistema cumpla con lo requerido por la organizacion. De esta manera, se elimina la interpretacion de los requerimientos realizados, se conoce la estructura y las relaciones de la empresa a la que el sistema se tiene que adecuar, se trabaja en funcion de dicha documentacion, se elabora el sistema con todas las pruebas necesarias para poder presentarse al cliente, ayuda a vencer la resistencia al cambio por parte de los usuarios introduciendo el sistema nuevo y capacitando al personal, y busca garantizar la adecuacion de dicho sistema a la organizacion.

7. Corrida en paralelo: aspectos a tener en cuenta al comenzar la prueba

Los aspectos a tener en cuenta cuando se hace la prueba en paralelo son:

- Los datos a usar tienen que estar convertidos y adaptados al nuevo sistema
- Se debe instalar los equipos y soft necesario
- Hay que asignar al personal involucrado al sistema
