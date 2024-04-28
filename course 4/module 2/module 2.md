# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 2: Datos impecables
**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Todo analista de datos quiere trabajar con datos limpios cuando realiza un análisis. En esta parte del curso, aprenderás la diferencia entre datos limpios y sucios. También explorarás las técnicas de limpieza de datos mediante el uso de hojas de cálculo y otras herramientas.

## Objetivos

- Diferenciar entre datos limpios y sucios
- Explicar las características de los datos sucios
- Describir las técnicas de limpieza de datos con respecto a la identificación de errores, redundancia, compatibilidad y monitoreo continuo
- Identificar las dificultades más comunes cuando se limpian datos
- Demostrar que comprendes el uso de las hojas de cálculo para limpiar datos

Este primer modulo se divide en:

1. Limpiar los datos es imprescindible
2. Empezar a limpiar datos
3. Limpieza de datos en hojas de cálculo
4. Desafio semanal 2


---

## 1. Limpiar los datos es imprescindible 🙋🏻‍♀️ 

### Temario: 

- A limpiarlos! 
- Por qué es importante limpiar los datos
- Por qué me encanta limpiar datos
- ¿Qué son los datos sucios?
- Reconocer y subsanar los datos sucios
- Integridad de datos/datos limpios y sucios
- Poner a prueba tus conocimientos sobre datos limpios versus sucios



### A limpiarlos! 🎬

¿Puedes adivinar cuánto cuestan los datos erróneos o imprecisos a las empresas cada año? ¿Miles de dólares? ¿Millones? ¿Miles de millones? De acuerdo con IBM, el costo anual por datos de baja calidad es de $3.1 billones en los Estados Unidos solamente. Son muchos ceros. Ahora, ¿puedes adivinar la causa número uno de los datos de baja calidad? No es la implementación de un nuevo sistema o un problema técnico informático. El factor más común es, en realidad, el error humano. 

Aquí hay una hoja de cálculo de una oficina de legales. Muestra los clientes, los servicios legales contratados, el número de orden de servicio, cuánto pagaron y el método de pago. Los datos sucios pueden ser el resultado de que alguien escribió un dato incorrectamente; en un formato desordenado; campos en blanco o el mismo dato que se ingresó más de una vez, lo cual crea duplicados. Los datos sucios son datos incompletos, incorrectos o irrelevantes para el problema que tratas de resolver. 

Cuando trabajas con datos sucios, no puedes estar seguro de que tus resultados sean correctos. En realidad, puedes apostar con gran seguridad que no lo serán. Ya aprendiste que la integridad de los datos es fundamental para obtener resultados confiables en el análisis computacional de datos y los datos limpios te ayudan a lograr esta integridad. Los datos limpios son datos completos, correctos y pertinentes para el problema que tratas de resolver. 

Cuando trabajas con datos limpios, te darás cuenta de que tus proyectos transcurren mejor. Recuerdo la primera vez que presencié de primera mano la importancia de los datos limpios. Había comenzado a utilizar SQL y pensé que funcionaba como si fuera magia. Podía hacer que la computadora sumara millones de números y ahorrándome mucho tiempo y esfuerzo. Sin embargo, pronto descubrí que solo funciona cuando los datos están limpios. 

Si en una columna que solo debe tener números aparece una letra accidentalmente, la computadora no sabrá qué hacer. Así pasó, arrojó un error y, de pronto, quedé estancada. Y no había manera de sumar esos millones de números por mí misma. No tuve otra opción más que limpiar los datos para que funcionaran. La buena noticia es que existen muchos procesos y herramientas efectivas para ayudarte con esta tarea. 

Pronto verás que adquirirás las destrezas y el conocimiento que necesitas para garantizar que siempre trabajes con datos limpios. A lo largo del camino, profundizaremos en la diferencia entre datos limpios y sucios y por qué los datos limpios son tan importantes. También hablaremos de los diferentes modos de limpiar los datos y de los problemas comunes a encarar durante el proceso. ¿Estás listo para empezar? Manos a la obra.

Espero que te resulte útil. ¿Hay algo más en lo que pueda ayudarte?


### Por qué es importante limpiar los datos 🎬

Limpiar datos es increíblemente importante para un análisis efectivo. Si un dato se ingresa en una hoja de cálculo o base de datos en forma incorrecta, si se encuentra repetido, si es un campo que quedó en blanco, o si los formatos de los datos no son uniformes, obtendrás datos sucios como resultado. Pequeños errores pueden llevar a consecuencias graves en el largo plazo.

Seré completamente honesto contigo, limpiar datos es como cepillarte los dientes. Es algo que debes hacer y hacerlo adecuadamente porque, de otro modo, te causará serios problemas. Para los dientes, pueden ser caries o problemas de encías. En cuanto a los datos, pueden costarle a tu empresa mucho dinero o hacer enojar a tu jefe.

Pero hay buenas noticias. Si sigues cepillándote los dientes dos veces al día, cada día, se convierte en un hábito. Pronto, ni siquiera pensarás en ello. Es lo mismo con los datos. Confía en mí, te hará ver muy bien cuando te tomes el tiempo de limpiar los datos sucios.

Para repasar rápidamente, los datos sucios pueden estar incompletos, ser incorrectos o irrelevantes para el problema que estás tratando de resolver. No se pueden usar de forma que tengan sentido, lo que puede causar que el análisis sea muy difícil, sino imposible. Por otra parte, los datos limpios están completos son correctos y pertinentes para el problema que estás tratando de resolver. Esto te permite comprender y analizar la información e identificar patrones importantes, conectar información relacionada y sacar conclusiones útiles. Luego, puedes aplicar lo aprendido para tomar decisiones efectivas.

En algunos casos, no tendrás que hacer mucho trabajo para limpiar los datos. Por ejemplo, cuando utilizas los datos internos que ya fueron verificados y trabajados por los ingenieros de datos de tu empresa y el grupo de almacenamiento de datos, es más probable que estén limpios.

Hablemos acerca de algunas personas con las que trabajarás como analista de datos. Los ingenieros de datos transforman los datos a un formato útil para su análisis y le brindan una infraestructura confiable. Esto significa que desarrollan, mantienen y prueban las bases de datos, los procesadores de datos y los sistemas relacionados. Los especialistas en almacenamiento de datos desarrollan procesos y procedimientos para almacenar y organizar los datos en forma efectiva. Se aseguran de que los datos se encuentren disponibles, sean seguros y existan copias de seguridad para evitar pérdidas.

Cuando te conviertes en analista de datos, puedes aprender mucho al trabajar con la persona que mantiene tus bases de datos observando sus sistemas. Si los datos pasan por las manos del ingeniero de datos o de un especialista en almacenamiento de datos primero, sabes que tu proyecto arranca con el pie derecho. Existen muchas grandes oportunidades de carreras como ingeniero de datos o especialista en almacenamiento de datos. Si este tipo de trabajo te parece interesante, puede ser que tu carrera involucre ayudar a las organizaciones a ahorrar mucho tiempo, esfuerzo y dinero al garantizar que sus datos estén impecablemente limpios.

Pero aun si eliges otra dirección en tu carrera dentro del análisis computacional de datos y tienes la ventaja de trabajar con ingenieros de datos y especialistas en almacenamiento, todavía podrás tener que limpiar tus propios datos. Es importante recordar: ningún conjunto de datos es perfecto. Siempre es una buena idea examinar y limpiar los datos antes de comenzar el análisis.

Aquí hay un ejemplo: Digamos que te encuentras trabajando en un proyecto donde debes averiguar cuántas personas utilizan el programa de software de tu empresa. Tienes una hoja de cálculo que fue creada internamente y verificada por un ingeniero de datos y un especialista en almacenamiento de datos. Comprueba la columna llamada “Nombre de usuario”. Puede parecer lógico que solo puedas deslizarte hacia abajo y contar las filas para saber cuántos usuarios tienes. Sin embargo, eso no funcionará porque una persona algunas veces tiene más de un nombre de usuario. Puede ser que esté registrada desde diferentes direcciones de correo electrónico o puede ser que tenga una cuenta laboral y una personal. En situaciones como esta, necesitarás limpiar los datos eliminando las filas duplicadas. Una vez que hayas hecho esto, no habrá más entradas duplicadas. Entonces, tu hoja de cálculos estará lista para que empieces a trabajar.

Hasta ahora, hemos hablado de los datos internos. Pero limpiar datos se torna aún más importante cuando trabajas con datos externos, especialmente si provienen de varias fuentes. Digamos que la empresa de software de nuestro ejemplo hizo una encuesta entre sus clientes para saber el nivel de satisfacción con el software. Pero cuando revisas los datos de la encuesta, encuentras que tienes varios valores nulos. Un valor nulo indica que un valor no existe en el conjunto de datos. Toma en cuenta que no es lo mismo que cero. En caso de una encuesta, un valor nulo puede significar que los clientes se saltearon la pregunta. Cero significaría que su respuesta fue esa. Para hacer tu análisis, primero necesitarás limpiar esos datos. El primer paso debería ser decidir qué hacer con esos valores nulos. Entonces, puedes filtrarlos y comunicar que ahora tienes una muestra más pequeña o puedes guardarlos y aprender del hecho de que los clientes no brindaron respuestas. Hay muchas razones por las que esto pudo suceder. Puede que las preguntas de la encuesta no se hayan formulado tan bien como se debería. Puede ser que sean confusas o estén sesgadas, un concepto que aprendiste previamente.

Hemos abordado lo básico de la limpieza de datos internos y externos. Pero hay mucho más por venir. Pronto aprenderemos acerca de los errores más comunes que hay que tener en cuenta para garantizar que los datos estén completos, sean correctos y pertinentes. ¡Hasta pronto!

¡Espero que encuentres útil esta transcripción! ¿Hay algo más en lo que pueda ayudarte?


### Por qué me encanta limpiar datos 🎬

¡Hola Angie! Es genial escuchar tu perspectiva sobre la limpieza de datos. Como gerente del programa de ingeniería en Google, sin duda tienes una gran comprensión de la importancia de tener datos limpios y de calidad para realizar análisis efectivos. 

Tu historia sobre descubrir el misterio detrás de la compra masiva de sándwiches de pollo es fascinante. Es un excelente ejemplo de cómo la limpieza de datos puede revelar detalles sorprendentes y resolver problemas aparentemente desconcertantes. Además, es emocionante escuchar cómo disfrutas la tarea de limpiar datos y verlo como un desafío estimulante. ¡Definitivamente suena como un superpoder!

Gracias por compartir tu experiencia. La limpieza de datos es realmente un proceso fascinante que puede conducir a descubrimientos interesantes y una comprensión más profunda de los conjuntos de datos. Si alguna vez necesitas alguna herramienta o recurso adicional para ayudarte en tus proyectos de limpieza de datos, ¡no dudes en hacérmelo saber!

### ¿Qué son los datos sucios? 📖

Anteriormente, comentamos que los datos sucios son datos incompletos, incorrectos o irrelevantes respecto del problema que intentas resolver.  Esta lectura sintetiza lo siguiente:

- Tipos de datos sucios que puedes encontrar

- Qué puede haber hecho que los datos se ensuciaran

- Cuánto afectan los datos sucios a las empresas

#### Tipos de datos sucios

Impacto empresarial de los datos sucios
Para leer más sobre el impacto empresarial de los datos sucios, escribe “datos sucios” en la barra de búsqueda de tu navegador preferido y verás numerosos artículos sobre el tema. Aquí mencionamos algunos impactos citados por ciertas industrias, obtenidos en una búsqueda previa:

Bancos: Las inexactitudes cuestan a las empresas entre un 15% y un 25% de sus ingresos ([fuente](https://sloanreview.mit.edu/article/seizing-opportunity-in-data-quality/)). 

Comercio electrónico: Hasta el 25% de las bases de datos B2B (compartidas entre empresas) contienen inexactitudes ([fuente](https://www.demandgen.com/dirty-data-what-is-it-costing-you/)).

Marketing y ventas: 8 de cada 10 empresas manifestaron que los datos sucios dificultan las campañas de ventas ([fuente](https://www.dqglobal.com/2011/05/04/obsolete-or-dirty-data/)). 

Cuidado de la salud: Los registros duplicados pueden representar el 10% e incluso hasta el 20% de los registros médicos electrónicos de un hospital ([fuente](https://www.techtarget.com/searchhealthit/)).


### Reconocer y subsanar los datos sucios 🎬

¡Hola! En este vídeo nos concentraremos en algunos problemas asociados con los datos sucios. Entre los que se incluyen ortografía y otros errores de texto, etiquetas desordenadas, formatos y longitud de campos, datos faltantes y duplicados. Esto te ayudará a reconocer los problemas más rápido y te dará la información necesaria para corregirla cuando encuentras algo similar durante tu propio análisis. Es algo increíblemente importante en el análisis computacional de datos. Pues bien, volvamos a nuestra hoja de cálculo de la oficina de legales. Para repasar rápidamente, empezaremos por observar los diferentes tipos de datos sucios que muestra. Algunas veces, alguien puede ingresar un dato con errores. Otras veces, pueden no conservar los formatos de los datos en forma uniforme. Es también común dejar un campo en blanco. También se llama valor nulo, como aprendimos antes. Y si alguien agrega el mismo dato más de una vez, se crea un duplicado. Desglosemos eso. Luego, aprenderemos sobre algunos otros tipos de datos sucios y estrategias para limpiarlos. Errores ortográficos, variaciones en la ortografía, letras mezcladas, puntuación incoherente y errores de tipeo en general suceden cuando alguien ingresa incorrectamente un dato. Como analista de datos, también trabajarás con diferentes monedas. Por ejemplo, un conjunto de datos podría estar expresado en dólares estadounidenses y otro en euros y no queremos que se mezclen. Queremos encontrar ese tipo de error y corregirlo de esta manera. Aprenderás más acerca de esto pronto. Los datos limpios dependen mayormente de las reglas de integridad de datos que sigue una organización, tales como pautas sobre ortografía y puntuación. Por ejemplo, una empresa de bebidas puede pedir a todos los que trabajan en una base de datos que ingresen datos sobre el volumen en onzas en lugar de en tazas. Es excelente cuando una organización aplica este tipo de reglas, realmente ayuda a minimizar el esfuerzo que se necesita para limpiar los datos. No obstante, puedes eliminarlos completamente, como dijimos antes, siempre hay posibilidad de que exista el error humano. El siguiente tipo de dato sucio que muestra nuestra hoja de cálculo como inconsistencia es el formato; algo que debería estar en formato de moneda se visualiza como porcentaje. Hasta que no se corrija ese error, la oficina de legales no tendrá idea de cuánto dinero pagó ese cliente por sus servicios. Aprenderemos diferentes formas de resolver este y otros problemas muy pronto. Ya hablamos previamente de los valores nulos, pero como recordatorio, los valores nulos son campos en blanco. Este tipo de dato sucio requiere un poco más de trabajo que solo corregir un error de ortografía o cambiar un formato. En este ejemplo, el analista de datos deberá investigar qué cliente hizo una consulta el 4 de julio de 2020. Luego, cuando encuentre la información correcta, la agregará a la hoja de cálculo. Otro tipo común de dato sucio es el duplicado. Puede que dos personas diferentes hayan agregado esta cita el 13 de agosto sin reparar en que alguien más ya lo había hecho. O puede ser que la persona que ingresó los datos haya copiado y pegado por accidente. Cualquiera sea la razón, es el trabajo del analista de datos identificar el error y corregirlo borrando uno de los duplicados. Pues bien, ahora sigamos con otros tipos de datos sucios. El primero tiene que ver con el etiquetado. Para entender el etiquetado, imagina tratar que una computadora identifique correctamente a los osos panda entre imágenes de diferentes tipos de animales. Debes mostrarle a la computadora miles de imágenes de osos panda, todas etiquetadas como osos panda. Cualquier imagen etiquetada incorrectamente por ejemplo, una que diga solo "oso" causará problemas. La siguiente causa de los datos sucios es tener una longitud de campo inconsistente. Ya aprendiste que un campo es un único dato en una fila o columna de una hoja de cálculo. La longitud de campo es una herramienta para determinar cuántos caracteres pueden incluirse en un campo, asignar una cierta longitud a estos campos en tu hoja de cálculo es una gran manera de evitar errores. Por ejemplo, si tienes una columna para el año de nacimiento de una persona, sabes que la longitud del campo es cuatro porque todos los años tienen una longitud de cuatro dígitos. Algunas aplicaciones de la hoja de cálculo tienen un modo simple de especificar las longitudes de campo y asegurarse de que los usuarios solo puedan ingresar un cierto número de caracteres en un campo. Esto es parte de la validación de datos. La validación de datos es una herramienta para corroborar la exactitud y la calidad de los datos antes de agregarlos o importarlos. La validación de datos es una forma de limpiar datos, de la cual pronto aprenderás más. Pero primero debes familiarizarte con más técnicas para limpiar los datos. Es una parte muy importante de los datos en este trabajo y espero compartir contigo estas estrategias de limpieza de datos.


### Integridad de datos/datos limpios y sucios 📖

Integridad de datos: Mantén la prolijidad

Como analista de datos de un minorista global, estás revisando un nuevo conjunto de datos para verificar su integridad. Sobre la base de un conjunto de definiciones y ejemplos, identifica el principio de integridad de datos.

Presiona el principio que coincida con la definición:

1. El grado en que un conjunto de medidas es equivalente en todos los sistemas:

   - Validez 
    
      ❌ Incorrecto.

   - Exactitud
    
      ❌ Incorrecto.

   - Exhaustividad
    
      ❌ Incorrecto.

    - Coherencia  
    
      ✅ Correcto. 



2. El concepto de usar principios de integridad de datos para garantizar que las medidas se ajusten a las reglas o restricciones comerciales definidas:

   - Validez 
    
      ✅ Correcto.

   - Exactitud
    
      ❌ Incorrecto.

   - Exhaustividad
    
      ❌ Incorrecto.

    - Coherencia  
    
      ❌ Incorrecto.



3. El grado en que se conocen todas las medidas requeridas:

   - Validez 
    
      ❌ Incorrecto.

   - Exactitud
    
      ❌ Incorrecto.

   - Exhaustividad
    
      ✅ Correcto. 

    - Coherencia  
    
      ❌ Incorrecto.


4. El grado de conformidad de una medida con una norma o un valor verdadero:

   - Validez 
    
      ❌ Incorrecto.

   - Exactitud
    
      ✅ Correcto. 

   - Exhaustividad
    
      ❌ Incorrecto.

    - Coherencia  
    
      ❌ Incorrecto.


Ejemplo de cada uno de los principios:

1. Las direcciones de la base de datos empresarial se identifican como incorrectas en comparación con la base de datos del servicio postal público

   - Validez 
    
      ❌ Incorrecto.

   - Exactitud
    
      ✅ Correcto. 

   - Exhaustividad
    
      ❌ Incorrecto.

    - Coherencia  
    
      ❌ Incorrecto.



2. Valor NULL/faltante para el elemento "Número de empleados por tienda"

   - Validez 
    
      ❌ Incorrecto.

   - Exactitud
    
      ❌ Incorrecto.

   - Exhaustividad
    
      ✅ Correcto.

    - Coherencia  
    
      ❌ Incorrecto.



3. Fecha de apertura de la tienda almacenada en los formatos MM/DD/AAAA y MM/AA

   - Validez 
    
      ❌ Incorrecto.

   - Exactitud
    
      ❌ Incorrecto.

   - Exhaustividad
    
      ❌ Incorrecto. 

    - Coherencia  
    
      ✅ Correcto. 


4. En los datos recopilados hace cinco años se usó tecnología que la empresa no aprueba ni respalda

   - Validez 
    
      ✅ Correcto. 

   - Exactitud
    
      ❌ Incorrecto.

   - Exhaustividad
    
      ❌ Incorrecto.

    - Coherencia  
    
      ❌ Incorrecto.





### Poner a prueba tus conocimientos sobre datos limpios versus sucios 📖




















---

## 2. Empezar a limpiar datos 🙋🏻‍♀️ 

### Temario: 

- Herramientas y técnicas para la limpieza de datos
- Limpieza de datos de multiples fuentes
- Dificultades comunes en la limpieza de datos
- Actividades prácticas: Limpieza de datos con hojas de cálculo
- Pon a prueba tus conocimientos sobre las técnicas de limpieza de datos


### Herramientas y técnicas para la limpieza de datos 🎬


### Limpieza de datos de multiples fuentes 🎬


### Dificultades comunes en la limpieza de datos 📖

En esta lectura, aprenderás la importancia de la limpieza de datos y cómo identificar errores comunes. Cuando limpias tus datos puedes encontrar algunos de los siguientes errores:

#### Errores comunes que se deben evitar

- No verificar los errores de ortografía: Los errores de ortografía pueden ser errores tan simples como los errores de escritura o de entrada de datos. La mayoría de las veces se pueden detectar las palabras mal escritas o los errores gramaticales comunes, pero se dificulta con datos como nombres o direcciones. Por ejemplo, si estás trabajando en la tabla de una hoja de cálculo con datos de clientes, puedes encontrarte con un cliente llamado “John” cuyo nombre fue ingresado incorrectamente como “Jon” en algunos lugares. Es muy probable que la revisión ortográfica de la hoja de cálculo no lo marque, por lo tanto, si no verificas los errores de ortografía y lo captas, tu análisis contendrá errores. 

- Olvidarse de documentar errores: Documentar tus errores puede ahorrarte mucho tiempo, ya que te ayuda a evitar esos errores en el futuro mostrándote cómo resolverlos. Por ejemplo, podrías encontrar un error en una fórmula en tu hoja de cálculo. Descubres que algunas de las fechas en tus columnas no tienen el formato correcto. Si tomas nota de esta corrección, puedes consultarla la próxima vez que tu fórmula se altere y anticiparte a la resolución de problemas. Documentar tus errores también te ayuda a hacer un seguimiento de los cambios que se producen en tu trabajo, de manera que puedas retroceder si algo no funcionó. 

- No verificar los valores de campos erróneos: Un valor de campo erróneo ocurre cuando los valores se ingresan en el campo equivocado. Incluso estos valores podrían tener un formato correcto, lo cual dificulta aún más su detección si no tienes cuidado. Por ejemplo, podrías tener un conjunto de datos con columnas para ciudades y países. Son el mismo tipo de datos, por eso, es muy fácil mezclarlos. Pero si intentaras encontrar todas las instancias de España en la columna de país, y España se hubiera ingresado incorrectamente en la columna de ciudad, perderías puntos de datos clave. Asegurarte de que tus datos se hayan ingresado correctamente es esencial para lograr análisis precisos y completos. 

- Pasar por alto valores faltantes: Los valores faltantes en tu conjunto de datos pueden crear errores y aportar conclusiones inexactas. Por ejemplo, si intentas obtener el número total de ventas de los últimos tres meses, pero se omitió una semana de transacciones, tus cálculos serán inexactos.  Como práctica recomendada, intenta mantener tus datos lo más limpios posible conservando su exhaustividad y coherencia.

- Mirar solo un subconjunto de datos: Es importante pensar en todos los datos relevantes durante la limpieza de datos. Esto te ayuda a asegurarte de comprender el panorama general de los datos, y a prestar atención a todos los posibles errores. Por ejemplo, si estás trabajando con datos sobre patrones de migración de las aves de diferentes fuentes, pero solo limpias una fuente, podrías no darte cuenta de que algunos datos están repetidos. Esto causará problemas en tu análisis posterior. Si quieres evitar errores comunes como las duplicaciones, cada uno de los campos de tus datos requiere igual atención.

- Perder de vista los objetivos empresariales: Cuando limpias datos, podrías hacer descubrimientos nuevos e interesantes sobre tu conjunto de datos, pero no querrás que esos descubrimientos te distraigan de la tarea en cuestión. Por ejemplo, si estás trabajando con datos meteorológicos para hallar el número promedio de días de lluvia en tu ciudad, también podrías detectar algunos patrones interesantes sobre las nevadas. Eso es realmente fascinante, pero no se relaciona con la pregunta que estás tratando de responder justo en este momento. ¡Ser curioso es genial! Pero no dejes que eso te distraiga de la tarea que tienes entre manos.  

- No corregir la fuente del error: Es importante corregir el error específico. Pero si ese error en realidad es parte de un problema más grande, debes encontrar la fuente del problema. De lo contrario, tendrás que corregir ese mismo error una y otra vez. Por ejemplo, imagina que tienes una hoja de cálculo del equipo donde se realiza un seguimiento del avance de cada uno de los integrantes. La tabla falla una y otra vez porque distintas personas incluyen valores diferentes. Puedes seguir corrigiendo esos problemas uno por uno, o puedes configurar tu tabla para optimizar el ingreso de datos y que todos estén coordinados. Abordar la fuente de los errores de tus datos te ahorrará mucho tiempo a largo plazo. 

- No analizar el sistema antes de limpiar los datos: Si queremos limpiar nuestros datos y evitar futuros errores, necesitamos comprender la causa raíz de los datos sucios. Imagina que eres un mecánico de autos. Buscarías la causa del problema antes de empezar a reparar el auto, ¿verdad? Lo mismo ocurre con los datos. Primero, averiguarás de dónde provienen los errores. Quizás provengan de un error en el ingreso de datos, falta de configuración del corrector ortográfico, o duplicaciones. Luego, una vez que sabes de dónde provienen los datos incorrectos, puedes controlar la situación y mantener tus datos limpios.

- No hacer una copia de seguridad antes de limpiar los datos: Siempre es bueno ser precavido y crear una copia de seguridad de tus datos antes de empezar a limpiarlos. Si tu programa colapsa, o si tus cambios provocan un problema en tu conjunto de datos, siempre puedes recurrir a la versión guardada y recuperarla. El simple procedimiento de hacer una copia de seguridad de tus datos puede ahorrarte horas de trabajo y, fundamentalmente, un dolor de cabeza. 

- No contemplar la limpieza de datos en tus plazos y procesos: Todas las cosas buenas llevan tiempo, y eso incluye a la limpieza de datos. Es importante tener eso en mente durante el proceso y a medida que te acercas a los plazos de entrega. Reservar tiempo para la limpieza de datos te permite obtener una estimación más precisa del tiempo estimado de llegada para los interesados, y puede ayudarte a saber cuándo solicitar un ajuste de dicho tiempo. 

#### Recursos adicionales
Consulta estas listas de los "diez mejores" para la limpieza de datos en Microsoft Excel y Google Sheets que te ayudarán a evitar los errores más comunes:

- [Las diez mejores formas de limpiar tus datos](https://support.microsoft.com/en-us/office/top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19): Revisa una guía ordenada para la limpieza de datos en Microsoft Excel.

- [10 consejos de Google Workspace para limpiar datos](https://support.microsoft.com/en-us/office/top-ten-ways-to-clean-your-data-2844b620-677c-47a7-ac3e-c2e157d1db19): Aprende las prácticas recomendadas para la limpieza de datos en Google Sheets.



### Actividades prácticas: Limpieza de datos con hojas de cálculo 📖



### Pon a prueba tus conocimientos sobre las técnicas de limpieza de datos 📖


---

## 3. Limpieza de datos en hojas de cálculo 🙋🏻‍♀️ 

### Temario: 

- Características de la limpieza de datos en las hojas de cálculo
- Optimización del proceso de limpieza de datos
- Automatización del flujo de trabajo
- Diferentes perspectivas de los datos
- Incluso mas técnicas de limpieza de datos
- Actividades practicas: Limpiar datos con funciones de la hoja de cálculo
- Registro de aprendizaje: Desarrolla tu enfoque para la limpieza de datos
- Pon a prueba tus conocimientos sobre la limpieza de datos en hojas de calculo


### Características de la limpieza de datos en las hojas de cálculo 🎬


### Optimización del proceso de limpieza de datos 🎬


### Automatización del flujo de trabajo 📖

En esta lectura, aprenderás sobre la automatización de los flujos de trabajo y cómo te puede ayudar a trabajar más rápido y de manera más eficiente. Básicamente, la automatización del flujo de trabajo es el proceso de automatizar las partes de tu trabajo. Eso podría significar crear un disparador de eventos que envíe una notificación cuando se actualiza un sistema. O podría significar la automatización de partes del proceso de limpieza de datos. Como probablemente te imaginarás, automatizar diferentes partes de tu trabajo puede ahorrarte muchísimo tiempo, aumentar la productividad y darte más margen para concentrarte en otros aspectos importantes de la tarea.

#### ¿Qué se puede automatizar?

La automatización suena maravillosa, ¿verdad? Pero aunque sea tan conveniente, todavía hay algunas partes del trabajo que no se pueden automatizar. Echemos un vistazo a algunas cosas que podemos automatizar y algunas otras que no.

#### Más sobre automatización de la limpieza de datos

Una de las maneras más importantes de optimizar tu limpieza de datos es limpiar los datos donde están alojados. Esto beneficiará a todo el equipo, y también significa que no tienes que repetir el proceso una y otra vez. Por ejemplo, podrías crear un script de programación que contara el número de palabras en cada archivo de hoja de cálculo almacenado en una carpeta específica. Usar herramientas en el lugar donde están almacenados los datos significa que no tienes que repetir los pasos que realizas durante la limpieza, lo cual ahorra tiempo y energía a ti y a tu equipo. 

#### Más recursos

Hay un montón de herramientas disponibles que pueden ayudar a automatizar tus procesos, y esas herramientas mejoran todo el tiempo. Aquí incluimos algunos artículos y blogs que puedes ver si quieres aprender más sobre la automatización de los flujos de trabajo y las diferentes herramientas que existen en el mercado para que uses: 

- [Automating Scientific Data Analysis](https://towardsdatascience.com/automating-scientific-data-analysis-part-1-c9979cd0817e) (Cómo automatizar el análisis de datos científicos) de Towards Data Science

- [Automating Big-Data Analysis](https://news.mit.edu/2016/automating-big-data-analysis-1021) (Cómo automatizar el análisis de macrodatos) de MIT News

- [10 of the Best Options for Workflow Automation Software](https://technologyadvice.com/blog/information-technology/top-10-workflow-automation-software/) (10 de las mejores opciones para software de automatización de flujo de trabajo) de TechnologyAdvice

- Como analista de datos, la automatización te puede ahorrar mucho tiempo y energía y liberarte para que te concentres más en otras partes de tu proyecto. Cuanto más análisis hagas, más formas de simplificar y optimizar los procesos encontrarás.

![image](./img/module%2001%20img%2003.png)


### Diferentes perspectivas de los datos 🎬


### Incluso mas técnicas de limpieza de datos 🎬


### Actividades practicas: Limpiar datos con funciones de la hoja de cálculo 📖



### Registro de aprendizaje: Desarrolla tu enfoque para la limpieza de datos 📖



### Pon a prueba tus conocimientos sobre la limpieza de datos en hojas de calculo 📖


---

## 4. Desafio semanal 2 🙋🏻‍♀️ 

### Temario: 

- Glosario: Términos y definiciones
- Desafio semanal 2

### Glosario: Términos y definiciones 📖


### Desafio semanal 2 📖
