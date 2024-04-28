# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 1: La importancia de la integridad
**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Mientras empiezas a pensar cómo preparar tus datos para la exploración, esta parte del curso te mostrará por qué la integridad de los datos es tan importante para los procesos de toma de decisiones. Aprenderás cómo se generan los datos y las técnicas que usan los analistas para decidir qué datos recopilar para su análisis. También descubrirás qué son los datos estructurados y no estructurados, los tipos de datos y los formatos de datos.

## Objetivos

- Describir las mediciones estadísticas relacionadas con la integridad de los datos, inclusive la potencia estadística, la prueba de hipótesis y el margen de error
- Describir las estrategias que se pueden usar para manejar datos insuficientes
- Debatir la importancia del tamaño de la muestra en relación con el sesgo de la muestra y las muestras aleatorias
- Describir la relación entre los datos y los objetivos empresariales relacionados
- Definir la integridad de datos y hacer referencia a sus tipos y riesgos
- Debatir la importancia de las actividades previas de limpieza de datos

Este primer modulo se divide en:

1. Enfoque de la integridad
2. Objetivos de la integridad y análisis de datos
3. Supera los desafíos de datos insuficientes
4. Cómo usar el poder estadístico
5. Considerar el margen de error
6. Desafío semanal 1


---

## 1. Enfoque de la integridad 🙋🏻‍♀️ 

### Temario: 

- Introducción al enfoque en la integridad 
- Programa del curso
- Repaso: Hoja de ruta del certificado del análisis computacional de datos


### Introducción al enfoque en la integridad 🎬

¡Hola! Qué bueno volver a encontrarnos. Mi nombre es Sally y estoy aquí para enseñarte todo sobre el procesamiento de datos. Soy directora de analítica y mediciones en Google. Mi trabajo es ayudar a agencias publicitarias y empresas a medir el éxito y analizar sus datos, de modo que me reúno con muchas personas diferentes para mostrarles cómo el análisis de datos los ayuda en la publicidad. Hablando de análisis, hiciste un gran trabajo antes al aprender cómo recopilar y organizar los datos para análisis. Definitivamente es un paso importante en el proceso de análisis de datos, ¡bien hecho! Ahora hablemos sobre cómo asegurarnos de que tus datos organizados estén completos y sean precisos. Los datos limpios son la clave para asegurarte de la integridad de tus datos antes de analizarlos. Te mostraremos cómo asegurarte de que tus datos estén limpios y ordenados. Limpiar y procesar datos es una parte de todo proceso de análisis de datos. Como recordatorio rápido, ese proceso consiste en preguntar, preparar, procesar, analizar, compartir y actuar. Esto significa que es momento para que exploremos la fase de procesar y estoy aquí para guiarte en todo el camino. Conozco bien el lugar adonde estás ahora. Nunca había escuchado sobre análisis computacional de datos hasta que hice un programa similar a este. Una vez que comencé a avanzar, me di cuenta de cuanto disfrutaba el análisis computacional de datos y las puertas que podría abrir. ¡Y ahora estoy entusiasmada en ayudarte a abrir esas mismas puertas! Algo que comprendí mientras trabajaba para distintas empresas, es que los datos limpios son importantes en todas las industrias. Por ejemplo, al inicio de mi carrera, aprendí a estar atentar para identificar datos duplicados, un problema común con el que los analistas se encuentran al limpiar datos. Solía trabajar para una empresa que tenía distintos tipos de suscripciones. En nuestro conjunto de datos, cada usuario tendría una nueva fila para cada tipo de suscripción contratada, lo que significa que los usuarios aparecerían más de una vez en mis datos. De modo que si hubiera contado el número de usos en una tabla sin percatarme de los duplicados como este, habría contado a algunos usuarios dos veces en lugar de una. Como resultado, mi análisis habría resultado erróneo, lo que habría llevado a problemas en mis informes y para los interesados que confían en mis análisis. ¡Imagina si le contase al director general que tengo dos veces más clientes de los que realmente hay! Es por eso por lo que los datos limpios son tan importantes. De modo que el primer paso en el procesamiento de datos es aprender sobre la integridad de los datos. Descubrirás qué es la integridad de los datos y porqué es importante mantenerla durante todo el proceso de análisis de datos. Algunas veces puede que ni siquiera tengas los datos que necesitas, de modo que deberás crearlos. Esto te ayudará a aprender cómo el tamaño de la muestra y el muestreo aleatorio pueden ahorrarte tiempo y esfuerzo. Las pruebas de datos son otro paso importante al procesar datos. Compartiremos algunas pautas sobre cómo realizar pruebas de datos antes de que tus análisis comiencen oficialmente. Del mismo modo en que lavas tu ropa y tus platos en la vida diaria, los analistas limpian todos sus datos todo el tiempo, también. La importancia de los datos limpios será definitivamente el punto de atención aquí. Aprenderás técnicas de limpieza de datos para todos los escenarios, junto con algunas trampas para tener en cuenta durante el proceso. Explorarás la limpieza de datos en hojas de cálculo y bases de datos, a partir de lo que has aprendido sobre las hojas de cálculo. Hablaremos más sobre SQL y cómo puedes usarlo para limpiar datos y hacer otras cosas útiles, también. Cuando los analistas limpian sus datos, hacen mucho más que un control puntual para asegurarse de que la limpieza de datos está bien. Aprenderás formas de verificar e informar los resultados de tu tarea de limpieza. Esto incluye documentar tu proceso de limpieza, que tiene muchos beneficios que exploraremos. Es importante recordar que el procesamiento de datos es solo una de las tareas que completarás como analista de datos. Realmente, tus habilidades de limpieza de datos podrían ser algo que luego terminarás destacando en tu currículum cuando comiences a buscar trabajo. Hablando de tu currículum, podrás comenzar a pensar en cómo hacerlo desde la perspectiva de un analista de datos. Una vez que termines, tendrás una sólida apreciación de los datos limpios y de cuán importantes son en el proceso de análisis de datos. ¡Empecemos!.


### Programa del curso

1. Aspectos básicos: Datos, datos, en todas partes

2. Haz preguntas para tomar decisiones basadas en datos

3. Prepara datos para la exploración
 
**4. Procesa datos para pasarlos en limpio (este curso)**

5. Analiza datos para responder preguntas

6. Comparte datos a través del arte de la visualización

7. Análisis de datos con programación en R

8. Google Data Analytics Capstone: completa un caso práctico

¡Te damos la bienvenida al cuarto curso del programa! A medida que avanzas en la obtención del certificado, este curso y los siguientes comenzarán a centrarse más en tareas prácticas y proyectos, ambos reales. Esto aumentará progresivamente la cantidad de tiempo que tendrás para desarrollar destrezas clave para la tarea.

En el último curso, trabajaste sobre algunas habilidades básicas que necesitarías como analista de datos de nivel inicial. Aprendiste sobre estructuras de datos, y descubriste cómo obtener, aplicar, organizar y proteger datos. 

En este curso, aprenderás cómo estar seguro de que tus datos estén limpios por medio del control de su exhaustividad y exactitud. Podrás analizar diferentes enfoques sobre datos limpios en hojas de datos y bases de datos. También aprenderás cómo verificar que tus datos estén limpios y cómo crear informes para comunicar esa información a otros. Asegurar la precisión y la confiabilidad de los datos es clave para el trabajo de un analista de datos.  

##### Contenido del curso

Curso 4 -Procesamiento de Datos: de sucios a limpios 

1. Garantizar la integridad de los datos. La integridad de los datos es necesaria para asegurar un análisis exitoso. En esta parte del curso, explorarás métodos y pasos que realizan los analistas para controlar la integridad de los datos. Esto incluye saber qué hacer cuando los datos son insuficientes. También aprenderás sobre el tamaño de la muestra, cómo evitar el sesgo de la muestra, y cómo usar muestras aleatorias. Todas estas medidas también te ayudarán para asegurar un análisis de datos exitoso.

2. Comprender la limpieza de datos. Los analistas de datos quieren datos limpios para trabajar cuando llevan a cabo un análisis. En esta parte del curso, aprenderás la diferencia entre datos limpios y sucios. También practicarás técnicas de limpieza de datos en hojas de cálculo y otras herramientas.

3. Cómo limpiar datos usando SQL Conocer diversas formas de limpiar datos puede facilitar mucho el trabajo de un analista. En esta parte del curso, usarás SQL para limpiar datos en bases de datos. Explorarás cómo se pueden usar las consultas en SQL y las distintas funciones que existen para limpiar y transformar tus datos antes de cada análisis.

4. Cómo verificar e informar los resultados de la limpieza de datos. La limpieza de datos es un paso importante del proceso del análisis de datos. En esta parte del curso, verificarás que los datos estén limpios e informarás de los resultados de la limpieza de datos. Con datos limpios verificados, estarás listo para el siguiente paso en el proceso de análisis de datos.

5. (Opcional) Cómo agregar datos a tu currículum. Crear un currículum efectivo te ayudará en tu trayectoria profesional en el análisis computacional de datos. En esta parte del curso, aprenderás todo sobre el proceso de solicitud de empleo. Te enfocarás en crear un currículum que destaque tus fortalezas y experiencia más importante. 

6. Cómo completar el Desafío del curso. Al final de este curso, podrás poner en práctica todo lo que has aprendido con el Desafío del curso. El Desafío del curso te hará preguntas sobre los conceptos clave y, luego, te dará la oportunidad de ponerlos en práctica a través de distintos escenarios preparados.


### Programa del curso 📖


### Repaso: Hoja de ruta del certificado del análisis computacional de datos 📖


---

## 2. Objetos de la integridad de datos y del análisis de datos 🙋🏻‍♀️ 

### Temario:

- Motivos por los cuales la integridad de datos es importante
- Más información sobre la integridad de datos y el cumplimiento normativo
- Equilibrio entre los objetivos y la integridad de datos
- Objetivos y datos alineados
- Cuestionario


### Motivos por los cuales la integridad de datos es importante 🎬

¡Hola de nuevo! En este vídeo, vamos a hablar sobre la integridad de los datos y algunos riesgos que podrías correr al trabajar como analista de datos. Un análisis robusto depende de la integridad de los datos. Si los datos que estás usando están comprometidos de alguna manera, tu análisis no será tan sólido como debería. La integridad de los datos consiste en la exactitud, integridad, consistencia y confiabilidad de los datos a lo largo de su ciclo de vida. Esto puedo sonar como muchas cualidades para que los datos estén a la altura de las circunstancias. Pero créeme, vale la pena verificar todas estas cualidades por completo antes de proceder con tu análisis. De lo contrario, tu análisis podría ser erróneo. No porque hayas hecho algo mal, sino porque los datos con los cuales estabas trabajando eran erróneos desde el principio. Cuando la integridad de los datos es baja, puede causar cualquier inconveniente desde la pérdida de un píxel en una imagen hasta una decisión médica incorrecta. En algunos casos, una pieza faltante puede hacer que todos tus datos se tornen inservibles. La integridad de los datos puede estar comprometida de muchas formas diferentes. Existe la posibilidad de que los datos puedan estar comprometidos cada vez que se replican, transfieren o manipulan de cualquier forma. La replicación de datos es el proceso de almacenar datos en varios sitios. Si estás replicando datos en distintos momentos en distintos lugares, existe la posibilidad de que tus datos no estén sincronizados. Esos datos carecen de integridad porque distintas personas pueden no utilizar los mismos datos para sus conclusiones, lo cual puede causar inconsistencias. También está el tema de la transferencia de datos, que es el proceso de copiar datos desde un dispositivo de almacenamiento a la memoria o de una computadora a otra. Si tu transferencia de datos se interrumpe, podrías terminar con un conjunto de datos incompletos, lo cual podría no ser útil para tus necesidades. El proceso de manipulación de datos implica modificar los datos para que estén más organizados y sean más fáciles de leer. La manipulación de datos tiene como objetivo hacer que el proceso de análisis de datos sea más eficiente, pero un error durante el proceso puede comprometer la eficacia. Por último, los datos también pueden estar comprometidos por un error humano, virus, malware, piratería informática y fallas del sistema, que pueden llevar a más dolores de cabeza. Voy a parar aquí. Estas son suficientes potenciales malas noticias para digerir. Pasemos a algunas potenciales buenas noticias. En muchas empresas, el almacén de datos o el equipo de ingeniería de datos se encarga de garantizar la integridad de los datos. Próximamente, aprenderemos sobre cómo verificar la integridad de los datos como analista de datos. Pero quédate tranquilo, alguien más por lo general te cubrirá la espalda. Luego de averiguar con qué datos estás trabajando, es importante que compruebes dos veces que tus datos están completos y son válidos antes de analizarlos. Esto te ayudará a asegurar que tu análisis y conclusiones son precisas. Verificar la integridad de los datos es un paso crucial en el procesamiento de tus datos para tenerlos listos para el análisis, ya sea que tú u otra persona en la empresa lo hagan. Luego, aprenderás más sobre integridad de datos ¡Hasta pronto!.


### Más información sobre la integridad de datos y el cumplimiento normativo 📖

Este documento refleja la importancia de la integridad de datos y brinda un ejemplo con datos de una empresa global. Las definiciones de los términos clave sobre integridad de datos serán proporcionadas al final de este documento. 

Escenario: fechas del calendario de una empresa global
Las fechas del calendario se presentan en una amplia gama de formas abreviadas. Según el lugar donde vives, se puede usar una forma abreviada diferente. 

En algunos países, 12/10/20 (DD/MM/AA) significa 12 de octubre de 2020. 

En otros países, el estándar oficial es AAAA-MM-DD, por lo tanto el 12 de octubre de 2020 pasa a ser 2020-10-12. 

En los Estados Unidos, la forma aceptada es mes, día, año (MM/DD/AA), por lo tanto el 12 de octubre de 2020 será 10/12/20.

Ahora, piensa lo que podría suceder si estás trabajando como analista de datos para una empresa internacional y no tienen en cuenta los diferentes formatos de las fechas. La integridad de datos resultante puede ser cuestionable. El análisis de los datos sería inexacto. ¿Qué pasaría si pidieras stock de más para diciembre cuando en realidad lo necesitaban para octubre?

Un buen análisis depende de la integridad de los datos, y la integridad de los datos generalmente depende del uso de un formato único. Por lo tanto, es importante verificar varias veces el formato de las fechas para asegurarse de que lo que creías que era el 10 de diciembre de 2020 en realidad era el 12 de octubre de 2020 y viceversa.

A continuación, se incluyen algunos temas para tener en cuenta:

- La replicación de datos puede comprometer la integridad de los datos: Siguiendo con el ejemplo anterior, imagina que pides a tus colegas internacionales que verifiquen las fechas y se ajusten a un formato. Entonces, un analista copia un gran conjunto de datos para controlar las fechas. Sin embargo, por temas relacionados con la memoria, se copia solamente parte del conjunto de datos. El analista podría así verificar y estandarizar datos incompletos. En consecuencia, una parte del conjunto de datos se certificaría como conforme, pero la totalidad del conjunto de datos aún tendría fechas sin verificar. Dos versiones de un mismo conjunto de datos pueden provocar resultados inconsistentes. Una auditoría final de los resultados podría ser necesaria para descubrir qué fue lo que sucedió y corregir todas las fechas. 

- La transferencia de datos puede comprometer la integridad de los datos: Otro analista controla las fechas en una hoja de cálculo y elije importar los datos validados y estandarizados de nuevo a la base de datos. Pero supongamos que el campo de datos de la hoja de cálculo se clasificó erróneamente como campo de texto durante el proceso de importación (transferencia) de datos. Ahora, algunas de las fechas en la base de datos quedaron registradas como cadenas de texto. En este punto, se deben limpiar los datos deben para poder restaurar su integridad. 

- La manipulación de datos puede comprometer la integridad de los datos: Al controlar las fechas, otro analista se da cuenta de lo que parece ser un registro duplicado en la base de datos y lo borra. Pero, en realidad, el analista borró un registro único de una filial de la empresa y no un registro duplicado de la empresa. A tu conjunto de datos ahora le faltan datos y los datos deben ser restaurados para que sean exhaustivos.

##### Conclusión

Afortunadamente, la integridad de los datos se puede mantener con un formato de fecha estándar y el cumplimiento normativo por parte de todas las personas y de los sistemas que trabajan con los datos. Pero más allá de dónde provienen tus datos, siempre debes asegurarte de controlar si los datos son válidos, están completos y limpios antes de comenzar cualquier tipo de análisis. 

##### Referencias: Restricciones de datos y ejemplos

A medida que avances en tu recorrido por los datos, encontrarás muchos tipos de restricciones relacionadas con los datos (o criterios que determinan su validez). La tabla que aparece a continuación detalla definiciones y ejemplos de términos sobre limitaciones de datos que podrías encontrar. 

![image](./img/module%2001%20img%2001.png)
![image](./img/module%2001%20img%2002.png)


### Equilibrio entre los objetivos y la integridad de datos 🎬


### Objetivos y datos alineados 📖

#### Objetivos y datos alineados

Puedes obtener información muy valiosa y tomar decisiones precisas cuando los datos están alineados con los objetivos de negocios. Como analista de datos, la alineación es algo que deberás juzgar. Una buena alineación significa que los datos son relevantes y pueden ayudarte a resolver un problema corporativo o a decidir qué acción tomar para lograr un objetivo comercial específico. 

En este sentido, revisarás los objetivos de negocios relacionados con tres escenarios. Explorarás cómo los datos limpios y los objetivos corporativos bien alineados pueden ayudarte a tomar decisiones más precisas. Además, aprenderás cómo las nuevas variables que descubras a través del análisis de datos pueden ayudarte a crear restricciones de datos para alinear datos con un objetivo de negocios.  

Limpieza de datos + alineación al objetivo de negocio = conclusiones precisas

#### Objetivo comercial

Los administradores de cuentas en Impress Me, una empresa de servicios de contenido en línea, quieren conocer la rapidez con que sus usuarios pueden ver el contenido después de que se activan sus suscripciones. 

Para comenzar, el analista de datos verifica si los datos exportados a las hojas de cálculo están limpios y confirma que los datos que necesita se encuentren disponibles (cuando los usuarios acceden al contenido). Con esta información, el analista decide si hay una buena alineación de los datos respecto del objetivo comercial. Lo único que falta entonces es darse cuenta exactamente cuánto tiempo le lleva a cada usuario ver el contenido después de que se activa su suscripción.

A continuación, se incluyen los pasos del procesamiento de datos que realiza el analista para un usuario de una cuenta llamada V&L Consulting. (Estos pasos deberían repetirse para cada cuenta que se suscribe y para cada usuario relacionado con esa cuenta).

##### Paso 1

![image](./img/module%2001%20img%2003.png)

##### Paso 2

![image](./img/module%2001%20img%2003.png)

##### Paso 3

![image](./img/module%2001%20img%2004.png)

##### Paso 4

![image](./img/module%2001%20img%2005.png)

##### Consejo de expertos 1

En el proceso detallado arriba, el analista podría usar la función VLOOKUP para buscar los datos en los Pasos 1, 2 y 3 para completar los valores en la hoja de cálculos mencionada en el Paso 4. 
[VLOOKUP](https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1) es la función de una hoja de cálculo que busca cierto valor en una columna y arroja la información relacionada. Se puede ahorrar mucho tiempo usando la función VLOOKUP. Sin ella, tienes que buscar fechas y nombre de forma manual.

Puedes consultar más información en la página [VLOOKUP](https://support.google.com/docs/answer/3093318?hl=en) del Centro de asistencia de Google para conocer cómo usar la función en Google Sheets.

##### Consejo de expertos 2

En el Paso 4 del proceso mencionado, el analista podría usar la función [DATEDIF](https://support.microsoft.com/en-us/office/datedif-function-25dba1a4-2812-480b-84dd-8b32a451b35c) para calcular automáticamente la diferencia entre las fechas de la columna C y la columna D. Esta función calcula el número de días entre dos fechas. 

Puedes consultar más información en la página [DATEDIF](https://support.microsoft.com/en-us/office/days360-function-b9a509fd-49ef-407e-94df-0cbda5718c2a) del Soporte técnico de Microsoft para conocer cómo se usa esta función en Excel. La función [DAYS360](https://support.microsoft.com/en-us/office/days360-function-b9a509fd-49ef-407e-94df-0cbda5718c2a)
 hace lo mismo en hojas de cálculo con datos contables que utilizan un año de 360 días (12 meses de 30 días).

Puedes consultar más información en la página [DATEDIF](https://support.google.com/docs/answer/6055612?hl=en) del Centro de asistencia de Google para conocer cómo usar la función en Google Sheets.

#### Alineación con el objetivo comercial + limpieza de datos adicional = conclusiones precisas 

##### Objetivo comercial

Recientemente, la empresa de software Cloud Gate llevó a cabo una serie de seminarios públicos como introducción a sus productos de manera gratuita. El analista de datos y el gerente del programa del webinar quieren identificar a las empresas con cinco o más asistentes a estas sesiones. Quieren darle esta lista de empresas a los gerentes de ventas para que hagan un seguimiento para posibles ventas.  

![image](./img/module%2001%20img%2006.png)


##### Limpieza de datos

Los datos de asistencia al webinar parecían estar alineados con el objetivo comercial. Pero el analista de datos y el gerente del programa decidieron que hacía falta realizar una limpieza de datos antes del análisis. Creen que se necesita llevar a cabo una limpieza de datos porque:

- El nombre de la empresa no era un campo obligatorio. Si el nombre de la empresa quedaba vacío, podría obtenerse de la dirección de correo electrónico. Por ejemplo, si la dirección de correo electrónico es username@google.com, el campo del nombre de la empresa se podría completar con Google para el análisis de datos. Este paso de limpieza de datos supone que personas con direcciones de correo electrónico corporativo asistieron al webinar con fines comerciales.

- Los asistentes podían ingresar cualquier nombre. Sin embargo, dado que su asistencia a una serie de webinars se está controlando, deben validar sus nombres con direcciones de correo específicas. Por ejemplo, si Joe Cox asistió a dos webinars, pero accedió como Joe Cox en uno de ellos y como Joseph Cox en el otro, podría ser contabilizado como dos personas diferentes. Para evitar esto, necesitan controlar la dirección de correo electrónico específica para determinar si era la misma persona. Luego de la validación, Joseph Cox podría ser modificado a Joe Cox para que coincida con el otro nombre.


#### Alineación con el objetivo comercial + nuevas variables descubiertas + restricciones = conclusiones precisas 

##### Objetivo comercial

Una empresa de tutoría extraescolar, A+ Education, quiere conocer si hay un número mínimo de horas de tutoría requerido para que los alumnos mejoren los resultados de sus evaluaciones al menos un 10%. 

The data analyst thinks there is good alignment between the data available and the business objective because:

- Students log in and out of a system for each tutoring session, and the number of hours is tracked

- Assessment scores are regularly recorded  

El analista de datos considera que hay una buena alineación entre los datos disponibles y el objetivo comercial porque:

- Los estudiantes inician y cierran sesión en un sistema para asistir a casa sesión de tutoría y se controla el número de horas

- Los resultados de las evaluaciones se registran regularmente  

##### Restricciones de datos para nuevas variables

Luego de mirar los datos, el analista de datos descubre que hay otras variables a considerar. Algunos alumnos tienen sesiones semanales constantes y otros tienen sesiones programadas de manera más aleatoria, a pesar de que el número de horas de tutoría es la misma. Finalmente, los datos no se alinean tan bien con el objetivo comercial, por lo tanto el analista agrega una restricción de datos para enfocarse solamente en los alumnos con sesiones semanales constantes. Esta modificación ayuda a obtener una visión más precisa sobre el tiempo de inscripción que se necesita para alcanzar una mejora del 10% en los resultados de evaluaciones. 

#### Conclusiones clave

Espero que estos ejemplos te hayan brindado un panorama de lo que estabas buscando aprender sobre la alineación de datos con tu objetivo comercial. 

- Cuando tienes datos claros y una buena alineación, puedes obtener información precisa y sacar conclusiones respaldadas por datos.

- Si hay una buena alineación, pero se necesita limpiar los datos, limpia los datos antes de realizar el análisis. 

- Si los datos se alinean solo parcialmente con un objetivo, cómo puedes modificar el objetivo o usa restricciones de datos para asegurarte de que el subconjunto de datos se alinea mejor con el objetivo comercial.


### Cuestionario 📖




---

## 3. Supera los desafios de datos insuficientes 🙋🏻‍♀️ 

### Temario:

- Qué hacer en caso de datos insuficientes
- Qué hacer cuando encuentras un problema en tus datos
- La importancia del tamaño de la muestra
- Cómo calcular el tamaño de la muestra
- ¿Por qué son tan importantes las actividades previas a la limpieza?
- Cuestionario


### Qué hacer en caso de datos insuficientes 🎬

Todos los analistas estuvieron en la situación en la que los datos son insuficientes para el objetivo comercial. Considerando la cantidad de datos que se generan diariamente, puede ser difícil de creer, pero es verdad. Entonces, veamos qué puedes hacer cuando tus datos no son suficientes. Veremos cómo establecer límites para el alcance de tu análisis y qué datos deberías incluir. En un momento, fui analista de datos en un centro de soporte. Todos los días recibíamos preguntas de los clientes, que se registraban como tickets de soporte. Me pidieron una proyección del número de tickets de soporte entrantes por mes para determinar cuántas personas adicionales necesitábamos contratar. Era muy importante tener una cantidad suficiente de datos que se remontasen como mínimo a un par de años atrás porque debía informar cambios interanuales y estacionales. Si solo hubiera tenido disponibles los datos del año en curso, no hubiera sabido que es normal un pico en enero y tiene que ver con las personas que piden reembolsos después de las fiestas. Como tenía una cantidad suficiente de datos, pude sugerir la contratación de más personal en enero para estar preparados. Es inevitable que aparezcan desafíos, pero las buenas noticias son que una vez que conoces tu objetivo comercial, podrás reconocer si tienes suficientes datos. Y si no los tienes, podrás resolverlo antes de comenzar tu análisis. Ahora, veamos algunas de esas limitaciones con las que puedes encontrarte y cómo puedes manejar distintos tipos de datos insuficientes. Digamos que estás trabajando en la industria del turismo y necesitas saber cuáles son los planes de viaje buscados con más frecuencia. Si solamente usas datos de un sitio de reservas, te estás limitando a los datos de una fuente únicamente. Otros sitios de reservas pueden mostrar distintas tendencias que quisieras considerar para tu análisis. Si una limitación como esta afecta tu análisis, puedes detenerte aquí y consultar nuevamente con los interesados para trazar un plan. Si tu conjunto de datos se sigue actualizando, significa que todavía hay ingreso de datos y pueden no estar completos. Por lo tanto, si hay una atracción turística nueva y estás analizando el interés y la concurrencia, probablemente no haya suficientes datos para que determines las tendencias. Por ejemplo, podrías querer esperar un mes para recolectar más datos. También puedes comprobar con los interesados y pedirles ajustar el objetivo. Por ejemplo, podrías analizar tendencias semana por semana en lugar de mes a mes. También podrías basar tu análisis en tendencias de los últimos tres meses y decir: "Así es como se vería la concurrencia a la atracción para el mes cuatro". Puedes no tener suficientes datos para saber si este número es demasiado alto o demasiado bajo. Pero le dirías a los interesados que es tu mejor cálculo basado en los datos que tienes actualmente. Por otra parte, tus datos podrían ser más antiguos y ya no ser pertinentes. Los datos desactualizados sobre la satisfacción al cliente no incluirán las respuestas más recientes. De modo que estarás confiando en las calificaciones para hoteles o alquileres de verano que podrían ya no ser precisos. En este caso, tu mejor opción sería encontrar un nuevo conjunto de datos para trabajar. Los datos limitados geográficamente también pueden ser poco confiables. Si tu empresa es global, no querrías usar datos limitados a viajes en solo un país. Querrías un conjunto de datos que incluyera a todos los países. De modo que esa es una de las limitaciones más comunes que encontrarás y algunas de las formas de resolverlas. Puedes identificar las tendencias con los datos disponibles o esperar más datos si el tiempo lo permite; también puedes hablar con los interesados y ajustar tu objetivo; o puedes buscar un conjunto de datos nuevo. La necesidad de tomar esas decisiones dependerá de tu rol en la empresa y posiblemente de las necesidades de la industria en general. Pero aprender cómo abordar los datos insuficientes siempre es una forma genial de prepararte para el éxito. Tus facultades como analista de datos están fortaleciéndose. Y justo a tiempo. Después de aprender más sobre limitaciones y soluciones, también aprenderás sobre poder estadístico, otra herramienta fantástica para que uses. ¡Hasta pronto!


### Qué hacer cuando encuentras un problema en tus datos 📖

Qué hacer cuando encuentras un problema en tus datos

Cuando te preparas para realizar un análisis de datos, podrías darte cuenta de que no tienes los datos que necesitas o que no son suficientes. En algunos casos, puedes usar lo que se conoce como datos indirectos en lugar de datos reales. Considéralo como si se tratara de reemplazar aceite por manteca en una receta, cuando no tienes manteca. En otros casos, puede no haber un sustituto razonable y tu única opción será recopilar más datos.

Considera los siguientes problemas y sugerencias sobre datos y cómo los puedes resolver.


#### Problema 1: Falta de datos

![image](./img/module%2001%20img%2007.png)



#### Problema 2: Muy pocos datos

![image](./img/module%2001%20img%2008.png)


#### Problema 3: Datos incorrectos, incluidos los datos con errores*


Utiliza el siguiente diagrama de toma de decisiones para recordar cómo manejar los errores en los datos o la falta de datos:

![image](./img/module%2001%20img%2009.png)


![image](./img/module%2001%20img%2010.png)

![image](./img/module%2001%20img%2011.png)


### La importancia del tamaño de la muestra 🎬

Bien, antes hablamos de tener el tipo correcto de datos para cumplir con tus objetivos comerciales y la importancia de tener la cantidad correcta de datos para asegurarte de que tu análisis sea lo más preciso posible. Quizás recuerdes que para los analistas de datos, una población representa a todos los valores de datos posibles de un conjunto de datos determinado. Si puedes usar el 100% de una población en tu análisis, ¡es genial! Pero a veces recabar información sobre una población entera no es posible. Consume mucho tiempo o es muy caro. Por ejemplo, digamos que una organización internacional quiere saber más sobre dueños de mascotas que tienen gatos. Tu tarea es determinar qué tipo de juguetes prefieren los dueños de gatos en Canadá. Pero hay millones de dueños de gatos en Canadá, de manera que obtener datos de todos ellos sería un desafío enorme. Pues bien, ¡no temas! Permíteme presentarte..... ¡al tamaño de la muestra! Cuando utilizas un tamaño de muestra o una muestra, usas una parte de una población que es representativa de la población. El objetivo es obtener suficiente información de un grupo pequeño dentro de una población para formular predicciones o conclusiones sobre la población total. El tamaño de la muestra ayuda a asegurar el grado respecto del cual puedes estar confiado en que tus conclusiones representan con precisión a la población. Para los datos sobre dueños de gatos, un tamaño de la muestra podría incluir datos sobre cientos o miles de personas en lugar de millones. Usar una muestra para análisis es más rentable y lleva menos tiempo. Si se hace con cuidado y a conciencia, puedes obtener los mismos resultados usando un tamaño de muestra en lugar de intentar encontrar a cada uno de los dueños de los gatos para averiguar cuáles son sus juguetes favoritos. Sin embargo, existe una desventaja potencial. Cuando utilizas únicamente una muestra pequeña de una población, puede llevar a la incertidumbre. No puedes estar el 100% seguro de que tus estadísticas son una representación precisa y completa de la población. Esto lleva a un sesgo del muestreo, que se trató anteriormente en el programa. El sesgo del muestreo ocurre cuando una muestra no es representativa de la población en su conjunto. Esto significa que algunos miembros de la población están siendo sobre o subrepresentados. Por ejemplo, si la encuesta usada para recoger datos de los dueños de gatos solamente incluyó a personas con teléfonos inteligentes; entonces, los dueños de gatos que no tienen un teléfono inteligente no estarían representados en los datos. Utilizar un muestreo aleatorio puede ayudar a resolver algunos de esos problemas relacionados con el sesgo del muestreo. El muestreo aleatorio es una forma de seleccionar una muestra de una población de manera que cada tipo posible de la muestra tenga una posibilidad igual de ser elegido. Volviendo a los dueños de gatos, usar una muestra aleatoria de dueños de gatos significa que los dueños de gatos de cada tipo tienen una posibilidad igual de ser elegidos. Los dueños de gatos que viven en departamentos en Ontario tendrían la misma posibilidad de ser representados que aquellos que viven en casas en Alberta. Como analista de datos, encontrarás que crear tamaños de muestras usualmente se hace aún antes de recibir los datos. Pero aun así es bueno que sepas que los datos que vas a analizar son representativos de una población y sirven para tu objetivo. También es bueno saber con qué te encontrarás a continuación en tu recorrido por los datos. En el próximo vídeo, tendrás la opción de sentirte aún más cómodo con los tamaños de las muestras. ¡Nos vemos!


### ¿Por qué son tan importantes las actividades previas a la limpieza? 📖

![image](./img/module%2001%20img%2012.png)

Puntos para recordar al momento de determinar el tamaño de tu muestra
Al planificar el tamaño de una muestra, hay algunos puntos para tener en cuenta:

- No utilizar muestras menores de 30. Está probado estadísticamente que 30 es el tamaño mínimo de muestra a partir del cual el resultado promedio de la muestra comienza a representar el resultado promedio de la población.

- El nivel de confianza comúnmente utilizado es 95%, pero 90% puede funcionar en algunos casos. 

Aumentar el tamaño de la muestra para cumplir con ciertas necesidades del proyecto:

- Para un mayor nivel de confianza, utilizar un tamaño de muestra más grande

- Para disminuir el margen de error, utilizar un tamaño de muestra más grande

- Para una mayor significancia estadística, utilizar un tamaño de muestra más grande

Nota: Las calculadoras de tamaños de las muestras utilizan fórmulas estadísticas para determinar el tamaño de una muestra. ¡Encontrarás más información sobre este tema en el curso! Mantente atento.

##### ¿Por qué un tamaño mínimo de muestra de 30?

Esta recomendación está basada en el Teorema del límite central (TLC) del campo de probabilidades y estadísticas. A medida que aumenta el tamaño de la muestra, los resultados se asemejan más a la distribución normal (en forma de campana) de una gran cantidad de muestras. El mínimo de la muestra es 30 para que el teorema TLC sea válido. Los investigadores que se basan en el análisis de regresión (métodos estadísticos para determinar las relaciones entre variables controladas y dependientes) también prefieren un mínimo de muestra de 30.

¿Te interesa conocer más sobre este tema? Sin ahondar en los cálculos matemáticos, lee estos artículos: 

- [Teorema del límite central (TLC)](https://www.investopedia.com/terms/c/central_limit_theorem.asp): Este artículo de Investopedia explica el Teorema del límite central y describe brevemente cómo se aplica a un análisis de un índice bursátil. 

- [Fórmula del tamaño de la muestra](https://www.statisticssolutions.com/dissertation-resources/sample-size-calculation-and-sample-size-justification/sample-size-formula/): Este artículo sobre Soluciones estadísticas brinda más detalles sobre los motivos por los cuales algunos investigadores utilizan un mínimo de muestra de 30.

#### Los tamaños de muestras varían según el problema del negocio

El tamaño de la muestra variará en base al tipo de problema del negocio que estés intentando resolver. 

Por ejemplo, si vives en una ciudad con una población de 200,000 personas y 180,000 personas responden una encuesta, este es un tamaño de muestra grande. Pero sin hacer eso, ¿qué tamaño debería tener una muestra más pequeña para ser aceptable? 

¿Estaría bien si las 200 personas encuestadas representan a cada uno de los distritos en la ciudad? 

Respuesta: Depende de lo que esté en juego. 

Una muestra de 200 podría ser lo suficientemente grande si tu problema comercial es descubrir qué opinan los residentes sobre la nueva biblioteca.

Una muestra de 200 podría no ser lo suficientemente grande si tu problema comercial es determinar cómo votarían los residentes para financiar la biblioteca

Podrías probablemente aceptar un margen de error más amplio en una encuesta sobre qué opinan los residentes sobre la nueva biblioteca versus la encuesta sobre cómo votarían para financiarla. Por ese motivo, seguramente utilizarías un tamaño de muestra mayor para la encuesta sobre la votación.

#### Los tamaños de encuestas más grandes son más costosos

También debes evaluar el costo frente al beneficio de obtener resultados más precisos con un tamaño de muestra más grande. Alguien que intenta conocer las preferencias de los consumidores sobre una nueva línea de productos no necesitaría un tamaño de muestra tan grande como alguien que intenta conocer los efectos de una nueva droga. En el caso de la seguridad de los medicamentos, los beneficios superan el costo adicional de utilizar un tamaño de muestra más grande. Pero para las preferencias de los consumidores, una muestra más pequeña podría brindar resultados aceptables a menor costo.

#### El beneficio de conocer los aspectos básicos

Conocer los aspectos básicos te ayudará a tomar decisiones correctas al momento de elegir el tamaño de la muestra. Siempre puedes plantear tus dudas en caso de que te encuentres con tamaños de muestras que sean demasiado pequeñas. Una calculadora de tamaño de muestras también es una gran herramienta para utilizar en este caso. Las calculadoras de tamaños de muestras te permiten ingresar el nivel de confianza y el margen de error deseados para una población de un tamaño determinado. Luego, calculan el tamaño de la muestra para lograr estadísticamente esos resultados. 

### Cuestionario 📖







---

## 4. Cómo usar el poder estadístico 🙋🏻‍♀️ 

### Temario:

- Cómo usar el poder estadístico
- Qué hacer cuando no hay datos
- Cómo determinar el mejor tamaño de la muestra
- Calculadora de tamaño de muestra
- Cuestionario

### Cómo usar el poder estadístico 🎬

¡Hola! Probablemente todos hemos soñado con tener un superpoder al menos una vez en nuestras vidas. Yo sé cuál. Me encantaría poder volar. Pero hay otro superpoder del cual quizá no hayas oído hablar: el poder estadístico.

El poder estadístico es la probabilidad de obtener resultados significativos de una prueba. Creo que este no es un superpoder con el cual hayan soñado. Aun así, es un poder bastante genial. Para los analistas de datos, tus proyectos pueden comenzar con la prueba o el estudio. La prueba de hipótesis es una forma de ver si una encuesta o experimento tiene resultados significativos. Aquí hay un ejemplo: Digamos que trabajas en una cadena de restaurantes que está planificando una campaña de marketing para sus nuevos batidos. Debes realizar una prueba de publicidad en un grupo de clientes antes de realizarla a nivel nacional.

En la prueba, quieres verificar si a los clientes les gusta o no la campaña. También quieres descartar cualquier factor externo a la publicidad que pueda llevarlos a indicar que no les gusta ese aviso.

Utilizar a todos tus clientes llevaría mucho tiempo y sería muy caro. Por lo tanto, necesitas saber cuántos clientes necesitarás para demostrar que la publicidad es efectiva. Cincuenta probablemente no serían suficientes. Incluso si eligieras 50 clientes al azar, podrías terminar con clientes a quienes no les gustan para nada los batidos. Y si eso sucede, no podrás medir la efectividad de tu publicidad para obtener más pedidos de batidos dado que ninguno de los que están en el tamaño de la muestra los pediría. Es por eso por lo que necesitas un tamaño mayor de muestra: para que puedas asegurarte de obtener un buen número de todos los tipos de personas para tu prueba. Usualmente, cuanto más grande es el tamaño de la muestra, mayor será la posibilidad de obtener resultados estadísticamente significativos con tu prueba. Y ese es el poder estadístico.

En este caso, usar tantos clientes como sea posible mostrará las diferencias reales entre los grupos a quienes les gusta o no versus las personas cuya decisión no estaba basada en absoluto en la publicidad.

Existen formas de calcular con precisión el poder estadístico, pero no vamos a verlas ahora. Puede que necesites hacer ese cálculo por ti mismo como analista de datos.

Por ahora, debes saber que el poder estadístico generalmente se muestra como un valor de uno. De manera que si tu poder estadístico es 0.6; es lo mismo que decir 60%. En la prueba de la publicidad del batido, si calculaste un poder estadístico de 60%, eso significa que existe un 60% de posibilidades de que obtengas un resultado estadísticamente significativo en la eficacia de la publicidad.

"Estadísticamente significativo" es un término utilizado en estadísticas. Si quieres aprender más sobre el significado técnico, puedes buscar en línea. Pero en términos básicos, si una prueba es estadísticamente significativa, eso significa que los resultados de la prueba son reales y no un error causado por factores aleatorios.

De manera que hay 60% de chances de que los resultados de la prueba de publicidad del batido sean confiables y reales y un 40% de chances de que el resultado de la prueba sea incorrecto.

Usualmente, se necesita un poder estadístico de al menos 0.8 u 80% para considerar que tus resultados son estadísticamente significativos.

Consideremos un escenario más. Quedémonos con los batidos porque, bueno, porque me gustan los batidos. Imagina que trabajas en una cadena de restaurantes que quiere lanzar un nuevo batido con sabor a torta de cumpleaños con sabor a batido.

El costo de producción de este batido será más caro que el de tus otros batidos. Tu empresa espera que el entusiasmo por el nuevo sabor atraiga a más clientes y dinero para compensar el costo. Quieren probarlo primero en algunos restaurantes. Entonces, pensemos cuántos locales deberías usar para que tus resultados sean confiables.

Primero, deberías pensar qué es lo que evita que consigas resultados estadísticamente significativos. ¿Hay otros restaurantes que estén ofreciendo otras promociones que puedan atraer a nuevos clientes? ¿Algunos de esos restaurantes tienen clientes que siempre compran el producto más nuevo, sin importar qué es? ¿Algunos de esos restaurantes comenzaron algunas construcciones que evitarían que los clientes fueran al restaurante?

Para lograr un poder estadístico más alto, deberías considerar todos estos factores antes de decidir cuántos locales incluir en el tamaño de la muestra para tu estudio.

Quieres asegurarte de que cualquier efecto se deba, más probablemente, al nuevo sabor del batido, no a otros factores.

Los efectos mensurables serían un incremento en las ventas o el número de clientes en los locales en el tamaño de tu muestra. Muy bien, eso es todo por ahora. Próximamente, vamos a explorar los tamaños de las muestras en detalle, para obtener una mejor idea de cómo impactan en tus pruebas y estudios.

Mientras tanto, has aprendido un poco más sobre los batidos y los superpoderes. Y, por supuesto, sobre el poder estadístico. Lamentablemente, solo el poder estadístico puede ser realmente útil para los analistas de datos. Sin embargo, ponerme mi capa y volar a comprar un batido justo ahora suena bastante bien.


### Qué hacer cuando no hay datos 📖

Anteriormente aprendiste cómo podías hacer un análisis utilizando datos indirectos si no tienes datos. Debido a que puedes tener algunas preguntas sobre los datos indirectos, en esta lectura te daremos algunos ejemplos de los tipos de conjunto de datos que pueden servir como fuentes de datos alternativos.

#### Ejemplos de datos indirectos

A veces, los datos que respaldan un objetivo comercial no serán de fácil acceso. Aquí es donde los datos indirectos son útiles. A continuación, podrás observar escenarios con ejemplos de datos indirectos:

##### Conjunto de datos abiertos (de acceso público)

Si eres parte de una gran organización, es posible que tengas acceso a una gran cantidad de fuentes de datos. Pero si buscas algo específico o algo que no pertenezca a tu misma línea de negocios, también puedes utilizar conjuntos de datos abiertos o de acceso público. (En este artículo puedes encontrar una brece explicación de la diferencia entre los datos abiertos y públicos: 
[Hacia la ciencia de datos](https://towardsdatascience.com/is-there-a-difference-between-open-data-and-public-data-6261cd7b5389)).

Aquí hay un ejemplo. Recientemente se ha puesto a disposición la versión nasal de una vacuna. Una clínica quiere saber qué esperar respecto de las contraindicaciones, pero recién ha comenzado a recopilar datos de primera fuente de sus pacientes. Una contraindicación es una condición que puede hacer que un paciente no se aplique una vacuna por el daño que le podría ocasionar si lo hace. Para calcular el número posible de contraindicaciones, los analistas de datos toman de referencia un conjunto de datos abierto de un ensayo de la versión inyectable de la misma vacuna. El analista selecciona un subconjunto de datos con perfiles de pacientes que más se acercan a la composición de los pacientes de la clínica. 

Hay muchas formas de compartir datos y colaborar con el aporte de datos dentro de una comunidad. Kaggle (kaggle.com), mencionada anteriormente, tiene conjuntos de datos en diversos formatos que incluyen desde el más básico hasta archivos en formato de valores separados por comas (CVS).

##### Conjuntos de datos CSV, JSON, SQLite y BigQuery

- CSV: Analiza este conjunto de datos [Clientes de tarjetas de crédito](https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers), que tiene información de 10,000 clientes con su respectiva edad, salario, estado civil, tarjeta de crédito y categoría, etc. (CC0: Dominio público, Sakshi Goyal). 

- JSON: Analiza este conjunto de datos de JSON sobre [Vídeos de YouTube que son tendencia](https://www.kaggle.com/datasets/datasnaek/youtube-new) (CC0: Dominio público, Mitchell J).

- SQLite: Analiza este conjunto de datos de SQLite con datos de hace 24 años sobre [Incendios forestales en los Estados Unidos](https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires)  (CC0: Dominio público, Rachael Tatman).

BigQuery: Analiza este conjunto de datos de [Google Analytics 360](https://www.kaggle.com/datasets/bigquery/google-analytics-sample) de la Tienda de Merchandising de Google (CC0 Dominio público, Google BigQuery).

Consulta la [documentación para conjuntos de datos](https://www.kaggle.com/docs/datasets) de Kaggle para obtener más información y busca y explora conjuntos de datos por tu cuenta en kaggle.com/datasets.

Tal como sucede con otros tipos de conjuntos de datos, deberás estar atento a los datos ‘Nulos’ y a los duplicados en los conjuntos de datos abiertos. Los datos nulos generalmente significan que un campo de datos no fue asignado (quedó vacío), pero a veces el término Nulo puede ser interpretado como el valor 0. Es importante entender cómo se utilizó el término Nulo antes de comenzar a analizar un conjunto de datos con datos Nulos. 



### Cómo determinar el mejor tamaño de la muestra 🎬

El poder estadístico es la probabilidad de obtener resultados significativos de una prueba. Creo que este no es un superpoder con el cual hayan soñado. Aun así, es un poder bastante genial. Para los analistas de datos, tus proyectos pueden comenzar con la prueba o el estudio. La prueba de hipótesis es una forma de ver si una encuesta o experimento tiene resultados significativos. Aquí hay un ejemplo: Digamos que trabajas en una cadena de restaurantes que está planificando una campaña de marketing para sus nuevos batidos. Debes realizar una prueba de publicidad en un grupo de clientes antes de realizarla a nivel nacional.

En la prueba, quieres verificar si a los clientes les gusta o no la campaña. También quieres descartar cualquier factor externo a la publicidad que pueda llevarlos a indicar que no les gusta ese aviso. Utilizar a todos tus clientes llevaría mucho tiempo y sería muy caro. Por lo tanto, necesitas saber cuántos clientes necesitarás para demostrar que la publicidad es efectiva. Cincuenta probablemente no serían suficientes. Incluso si eligieras 50 clientes al azar, podrías terminar con clientes a quienes no les gustan para nada los batidos. Y si eso sucede, no podrás medir la efectividad de tu publicidad para obtener más pedidos de batidos dado que ninguno de los que están en el tamaño de la muestra los pediría. Es por eso por lo que necesitas un tamaño mayor de muestra: para que puedas asegurarte de obtener un buen número de todos los tipos de personas para tu prueba. Usualmente, cuanto más grande es el tamaño de la muestra, mayor será la posibilidad de obtener resultados estadísticamente significativos con tu prueba. Y ese es el poder estadístico.

En este caso, usar tantos clientes como sea posible mostrará las diferencias reales entre los grupos a quienes les gusta o no versus las personas cuya decisión no estaba basada en absoluto en la publicidad. Existen formas de calcular con precisión el poder estadístico, pero no vamos a verlas ahora. Puede que necesites hacer ese cálculo por ti mismo como analista de datos.

Por ahora, debes saber que el poder estadístico generalmente se muestra como un valor de uno. De manera que si tu poder estadístico es 0.6; es lo mismo que decir 60%. En la prueba de la publicidad del batido, si calculaste un poder estadístico de 60%, eso significa que existe un 60% de posibilidades de que obtengas un resultado estadísticamente significativo en la eficacia de la publicidad.

"Estadísticamente significativo" es un término utilizado en estadísticas. Si quieres aprender más sobre el significado técnico, puedes buscar en línea. Pero en términos básicos, si una prueba es estadísticamente significativa, eso significa que los resultados de la prueba son reales y no un error causado por factores aleatorios.

De manera que hay 60% de chances de que los resultados de la prueba de publicidad del batido sean confiables y reales y un 40% de chances de que el resultado de la prueba sea incorrecto. Usualmente, se necesita un poder estadístico de al menos 0.8 u 80% para considerar que tus resultados son estadísticamente significativos. Consideremos un escenario más. Quedémonos con los batidos porque, bueno, porque me gustan los batidos. Imagina que trabajas en una cadena de restaurantes que quiere lanzar un nuevo batido con sabor a torta de cumpleaños con sabor a batido.

El costo de producción de este batido será más caro que el de tus otros batidos. Tu empresa espera que el entusiasmo por el nuevo sabor atraiga a más clientes y dinero para compensar el costo. Quieren probarlo primero en algunos restaurantes. Entonces, pensemos cuántos locales deberías usar para que tus resultados sean confiables.

Primero, deberías pensar qué es lo que evita que consigas resultados estadísticamente significativos. ¿Hay otros restaurantes que estén ofreciendo otras promociones que puedan atraer a nuevos clientes? ¿Algunos de esos restaurantes tienen clientes que siempre compran el producto más nuevo, sin importar qué es? ¿Algunos de esos restaurantes comenzaron algunas construcciones que evitarían que los clientes fueran al restaurante? Para lograr un poder estadístico más alto, deberías considerar todos estos factores antes de decidir cuántos locales incluir en el tamaño de la muestra para tu estudio. Quieres asegurarte de que cualquier efecto se deba, más probablemente, al nuevo sabor del batido, no a otros factores.

Los efectos mensurables serían un incremento en las ventas o el número de clientes en los locales en el tamaño de tu muestra. Muy bien, eso es todo por ahora. Próximamente, vamos a explorar los tamaños de las muestras en detalle, para obtener una mejor idea de cómo impactan en tus pruebas y estudios. Mientras tanto, has aprendido un poco más sobre los batidos y los superpoderes. Y, por supuesto, sobre el poder estadístico. Lamentablemente, solo el poder estadístico puede ser realmente útil para los analistas de datos. Sin embargo, ponerme mi capa y volar a comprar un batido justo ahora suena bastante bien.


### Calculadora de tamaño de muestra 📖

En esta lectura, aprenderás los conceptos básicos de las calculadoras de tamaño de muestras, cómo utilizarlas y cómo interpretar los resultados. Una calculadora de tamaño de muestras te indica cuántas personas necesitas para la encuesta (o cuántas cosas necesitas evaluar) para obtener resultados que representen a la población objetivo. Veamos algunos términos con los que te encontrarás al utilizar una calculadora de tamaño de muestras:

- Nivel de confianza: El grado de probabilidad de que el tamaño de tu muestra refleje con precisión a la mayoría de la población.

- Margen de error: Cantidad máxima que se espera que los resultados de la muestra difieran de los de la población real.

- Población: Es el número total del cual deseas extraer tu muestra.

- Muestra: Es una parte representativa de la población.

Tasa de respuesta estimada: Si estás realizando una encuesta de personas, esta tasa representa qué porcentaje esperas que complete tu encuesta de las personas que recibieron la encuesta.

#### Cómo usar una calculadora de tamaño de muestras

Para usar una calculadora de tamaño de muestras, necesitas conocer el tamaño de la población, el nivel de confianza y el margen de error aceptable que se definió para poder ingresar esa información en la herramienta. Si cuentas con toda esa información, a continuación, podrás ver ejemplos sobre cómo funciona la calculadora de tamaño de muestras:

- Calculadora de tamaño de muestras de surveymonkey.com

- Calculadora de tamaño de muestras de raosoft.com

#### Qué hacer con los resultados

Después de que hayas cargado la información en alguna de estas calculadoras, aparecerá el tamaño de muestra sugerido. Recuerda que el tamaño de muestra calculado es el número mínimo que debes utilizar para alcanzar lo que cargaste como nivel de confianza y margen de error esperado. Si estás trabajando con una encuesta, también deberás pensar cuál es la tasa de respuesta estimada para definir cuántas encuestas necesitas enviar. Por ejemplo, si necesitas un tamaño de muestra de 100 personas y tu tasa de respuesta estimada es del 10%, necesitarás enviar tu encuesta a 1,000 personas para alcanzar las 100 respuestas que necesitas para tu análisis. 

Ahora que conoces los conceptos básicos, intenta realizar algunos cálculos utilizando las calculadoras de tamaño de muestras y vuelve a esta lectura si necesitas repasar algunas definiciones. 


### Cuestionario 📖




---

## 5. Considerar el margen de error 🙋🏻‍♀️ 

### Temario:

- Evaluar la confiabilidad de tus datos
- Todo sobre el margen de error
- Cuestionario

### Evaluar la confiabilidad de tus datos 🎬

Como analista de datos, es importante que calcules el tamaño de las muestras y las variables como el nivel de confianza y el margen de error antes de comenzar a realizar cualquier tipo de pruebas o encuestas. Es la mejor forma de asegurar la objetividad de tus resultados y te brinda una mayor posibilidad de obtener resultados estadísticamente importantes. Pero si ya conoces el tamaño de la muestra, como, por ejemplo, cuando recibes resultados de encuestas para analizar; entonces, puedes calcular el margen de error tú mismo. De ese modo tendrás una mejor idea de cuál es la diferencia entre tu muestra y tu población. 

Empezaremos por el principio con una definición más completa. El margen de error es el máximo que se espera que difieran los resultados de la muestra de los de la población real. Pensemos en un ejemplo de margen de error. Sería genial encuestar o realizar una prueba sobre una población entera, pero generalmente es imposible o poco práctico. Entonces, en cambio, se toma una muestra de la población más grande. Basado en el tamaño de la muestra, el margen de error resultante nos mostrará lo distinto que pueden ser los resultados comparados con los resultados si hubiéramos encuestado a toda la población. 

El margen de error te ayuda a entender lo confiable que son los datos de la prueba de tu hipótesis. Cuanto más cerca a cero esté el margen de error, más cerca los resultados de tu muestra coincidirán con los resultados de la población total. Por ejemplo, digamos que realizaste una encuesta nacional utilizando una muestra de la población. Le preguntaste a personas que trabajan cinco días a la semana si les gustaría la idea de trabajar cuatro días a la semana. De modo que tu encuesta dice que el 60% prefiere una semana de cuatro días. El margen de error fue del 10%, lo cual indica que entre el 50 y 70% de las personas les gustó la idea. 

De esta manera, si tuviéramos que encuestar a todos los trabajadores de cinco días en toda la nación, entre el 50 y el 70% estaría de acuerdo con nuestros resultados. Ten en cuenta que nuestro rango es entre el 50 y el 70%. Esto es así porque el margen de error se cuenta en ambas direcciones de los resultados de la encuesta de 60%. Si estableces un nivel de confianza de 95% para tu encuesta, habrá una posibilidad del 95% de que las respuestas de toda la población estén entre el 50 y el 70% que dirán que sí, que quieren una semana laboral de cuatro días. Dado que tu margen de error se superpone con la marca de 50%, no puedes asegurar que al público le agrada la idea de una semana laboral de cuatro días. En ese caso, tendrás que decir que tu encuesta fue no concluyente. 

Ahora, si querías un margen de error más bajo, por ejemplo, 5% con un rango entre 55 y 65%, podrías incrementar el tamaño de la muestra. Pero si te indicaron el tamaño de la muestra, puedes calcular el margen de error tú mismo. De ese modo, puedes decidir por ti mismo el nivel de probabilidad de que tus resultados sean estadísticamente significativos con base en tu margen de error. 

En general, a mayor cantidad de personas que incluyas en tu encuesta, será más probable que tu muestra sea representativa de toda la población. Disminuir el nivel de confianza también tendría el mismo efecto, pero eso haría menos probable que tu encuesta sea precisa. 

Es decir que, para calcular el margen de error, necesitas tres cosas: el tamaño de la población, el tamaño de la muestra, y el nivel de confianza. Y del mismo modo que con el tamaño de la muestra, puedes encontrar muchas calculadoras en línea si buscas "calculadora de margen de error". Pero vamos a mostrarte en una hoja de cálculo del mismo modo que cuando calculamos el tamaño de la muestra. Digamos que estás realizando un estudio sobre la eficacia de un medicamento nuevo. Tienes un tamaño de muestra de 500 participantes cuya enfermedad afecta al 1% de la población mundial. Es decir, aproximadamente 80 millones de personas, que es la población para tu estudio. Dado que es un estudio sobre medicamentos, necesitas tener un nivel de confianza del 99%. También necesitas tener un margen de error bajo. 

Vamos a calcularlo. Vamos a escribir los números para la población, el nivel de confianza y el tamaño de la muestra, en las celdas correspondientes de la hoja de cálculo. Y nuestro resultado es un margen de error cercano a 6%, más o menos. Cuando el estudio del medicamento esté completo, aplicarás el margen de error a tus resultados para determinar su nivel de confiabilidad. Las calculadoras como esta en las hojas de cálculo son una de las muchas herramientas que puedes utilizar para asegurar la integridad de tus datos. 

Y también es bueno recordar que verificar la integridad de los datos y alinearlos con tus objetivos te pondrá en buena forma para completar tus análisis. Tener conocimientos sobre tamaño de muestras, poder estadístico, margen de error y otros temas que hemos tratado ayudará a que tus análisis se realicen sin problemas. Son muchos conceptos nuevos para asimilar. Si te gustaría revisarlos en cualquier momento, puedes encontrarlos todos en el glosario, ¡o puedes ver nuevamente el vídeo! Pronto explorarás los pros y los contras de los datos limpios. ¡La aventura de los datos continúa! ¡Y me alegra que avances con ellos! ¡Tú puedes!


### Todo sobre el margen de error 📖

El margen de error es la cantidad máxima que se espera que los resultados de la muestra difieran de los de la población real. El margen de error, técnicamente, indica el rango de valores por debajo y sobre el resultado promedio de la muestra. Se espera que el resultado promedio de toda la población se ubique en ese rango. Podríamos comprender mejor el concepto del margen de error con los ejemplos que aparecen a continuación.

#### Margen de error en béisbol

Imagina que estás jugando al béisbol y que te toca batear. El público grita desaforadamente y tú te preparas para intentar golpear la pelota. El lanzador lanza una bola rápida a unos 90-95 mph, que tarda unos 400 milisegundos (ms) en llegar al guante del receptor. Haces un swing y fallas el primer lanzamiento porque te demoraste un poquito. Te preguntas si deberías haber hecho el swing un poco antes o un poco después para conseguir atajarla y hacer un jonrón. Esa diferencia de tiempo puede considerarse el margen de error, y nos indica lo cerca o lo lejos que estuvo tu velocidad de reacción respecto del promedio de velocidad de reacción necesaria para atajar la pelota.    

#### Margen de error en el área de marketing

El margen de error también es importante en el área de marketing. Utilicemos las pruebas A/B como ejemplo. La prueba A/B (o prueba dividida) analiza dos variaciones de la misma página web para determinar qué página es más exitosa para atraer tráfico de usuarios y generar ingresos. El tráfico de usuarios que se monetiza se conoce como tasa de conversión. La prueba A/B permite a los profesionales del marketing probar los mensajes de correo electrónico, los anuncios y las páginas destino para encontrar los datos de lo que funciona y lo que no. Los profesionales del marketing utilizan el intervalo de confianza (determinado por la tasa de conversión y el margen de error) para interpretar los resultados. 

Por ejemplo, vamos a suponer que realizas una prueba A/B para comparar la efectividad de dos asuntos de correo electrónico diferentes para tentar a las personas a abrir el mensaje. Descubres que el texto del asunto A: “Oferta especial solo para ti” tuvo un índice de apertura del 5% en comparación con el texto del asunto B: “No te pierdas esta oportunidad” que tuvo un 3%. 

¿Eso significa que el texto del asunto A es mejor que el texto del asunto B? Depende de tu margen de error. Si el margen de error fue del 2%; entonces, el índice de apertura o el intervalo de confianza del texto del asunto A se encuentra entre el 3% y el 7%. Dado que la base inferior del intervalo se solapa con los resultados del texto del asunto B en un 3%, no se puede concluir que exista una diferencia estadísticamente significativa entre el texto del asunto A y el B. Es importante evaluar el margen de error al momento de sacar conclusiones basadas en los resultados de la prueba. 

#### ¿Quieres calcular tu margen de error? 

Todo lo que necesitas es el tamaño de la población, el nivel de confianza y el tamaño de la muestra. Para entender mejor esta calculadora, analiza estos términos:

- Nivel de confianza: Es un porcentaje que indica la probabilidad de que tu muestra incluya de manera precisa a la mayor parte de la población 

- Población: El número total del cual extraes tu muestra

- Muestra: Es una parte representativa de la población

- Margen de error: Cantidad máxima que se espera que los resultados de la muestra difieran de los de la población real

En muchos casos, se utiliza un nivel de confianza del 90% al 95%. Pero, dependiendo de tu industria, podrías querer establecer un nivel de confianza más estricto. El nivel de confianza del 99% es razonable para algunas industrias, por ejemplo, para la industria farmacéutica.  

Como ya has establecido el tamaño de tu población, el tamaño de la muestra y el nivel de confianza, carga la información en una calculadora de margen de error como las que aparecen a continuación: 

En muchos casos, se utiliza un nivel de confianza del 90% al 95%. Pero, dependiendo de tu industria, podrías querer establecer un nivel de confianza más estricto. El nivel de confianza del 99% es razonable para algunas industrias, por ejemplo, para la industria farmacéutica.  

Como ya has establecido el tamaño de tu población, el tamaño de la muestra y el nivel de confianza, carga la información en una calculadora de margen de error como las que aparecen a continuación: 

- [Calculadora de margen de error de Good Calculators (calculadoras en línea gratuitas)](https://goodcalculators.com/margin-of-error-calculator/)

- [Calculadora de margen de error de CheckMarket](https://www.checkmarket.com/sample-size-calculator/#sample-size-margin-of-error-calculator)  

#### Conclusión clave

El margen de error se utiliza para determinar qué tan cerca se encuentran los resultados de tu muestra con los resultados que hubieras obtenido si hubieras consultado a toda la población. El margen de error te ayuda a entender e interpretar los resultados de la encuesta o de la prueba en la vida real.  Calcular el margen de error es particularmente útil al momento que te entregan los datos para analizar. Luego de usar la calculadora para calcular el margen de error, conocerás cuánto pueden diferir los resultados de la muestra de los resultados de la población completa. 


### Cuestionario 📖



---

## 6. Desafio semanal 1 🙋🏻‍♀️ 

### Temario:

- Glosario: Términos y definiciones
- Cuestionario final


### Glosario: Términos y definiciones 📖


### Cuestionario 📖














































































