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


### Cuestionario: Poner a prueba tus conocimientos sobre datos limpios versus sucios 📖


1. Describe la diferencia entre nulo y cero en un conjunto de datos.

   - Nulo representa un valor de cero. Cero representa una celda vacía. 
    
      ❌ Incorrecto.

   - Nulo significa datos inválidos. Cero indica datos faltantes.
    
      ❌ Incorrecto.

   - Nulo representa un número insignificante. Cero representa el número cero.
    
      ❌ Incorrecto.

    - Nulo indica que un valor no existe. Cero es una respuesta numérica.  
    
      ✅ Correcto. Nulo indica que un valor no existe. Cero es una respuesta numérica.

 
2. ¿Cuáles son los procesos y procedimientos más comunes que manejan los ingenieros de datos? Selecciona todas las opciones que correspondan.

   - Verificar resultados del análisis de datos 
    
      ❌ Incorrecto.

   - Dar a los datos una infraestructura confiable
    
      ✅ Correcto. Los ingenieros de datos transforman los datos en un formato útil para el análisis; le dan una infraestructura confiable, y desarrollan, mantienen y prueban bases datos y sistemas relacionados.

   - Desarrollar, mantener y probar bases de datos y sistemas relacionados
    
      ✅ Correcto. Los ingenieros de datos transforman los datos en un formato útil para el análisis; le dan una infraestructura confiable, y desarrollan, mantienen y prueban bases datos y sistemas relacionados.

    - Transformar los datos en un formato útil para el análisis  
    
      ✅ Correcto. Los ingenieros de datos transforman los datos en un formato útil para el análisis; le dan una infraestructura confiable, y desarrollan, mantienen y prueban bases datos y sistemas relacionados.


3. ¿Cuáles son los procesos y procedimientos más comunes que manejan los especialistas en almacenamiento de datos? Selecciona todas las opciones que correspondan.

   - Garantizar que los datos se limpien correctamente 
    
      ❌ Incorrecto.

   - Garantizar que se hagan copias de seguridad de los datos para evitar pérdidas
    
      ✅ Correcto. Los especialistas en almacenamiento de datos son responsables de garantizar que los datos estén disponibles, sean seguros y estén respaldados por copias de seguridad para evitar pérdidas.

   - Garantizar que los datos estén disponibles
    
      ✅ Correcto. Los especialistas en almacenamiento de datos son responsables de garantizar que los datos estén disponibles, sean seguros y estén respaldados por copias de seguridad para evitar pérdidas.

    - Garantizar que los datos sean seguros  
    
      ✅ Correcto. Los especialistas en almacenamiento de datos son responsables de garantizar que los datos estén disponibles, sean seguros y estén respaldados por copias de seguridad para evitar pérdidas.



4. Un analista de datos está limpiando un conjunto de datos. Quiere confirmar que los usuarios hayan ingresado correctamente los códigos postales de cinco dígitos mediante la verificación de los datos en cierta columna de una hoja de cálculo. ¿Qué sería lo más útil como próximo paso?

   - Dar formato a las celdas en la columna como número 
    
      ❌ Incorrecto.

   - Cambiar el ancho de columna para que coincida solo con cinco dígitos 
    
      ❌ Incorrecto.

   - Usar la función MAX para determinar el valor máximo en las celdas en la columna
    
      ❌ Incorrecto.

    - Usar la herramienta de longitud de campo para especificar el número de caracteres en cada celda de la columna  
    
      ✅ Correcto. Usar la herramienta de longitud de campo para especificar el número de caracteres en cada celda de la columna sería lo más útil.


---

## 2. Empezar a limpiar datos 🙋🏻‍♀️ 

### Temario: 

- Herramientas y técnicas para la limpieza de datos
- Limpieza de datos de multiples fuentes
- Dificultades comunes en la limpieza de datos
- Actividades prácticas: Limpieza de datos con hojas de cálculo
- Pon a prueba tus conocimientos sobre las técnicas de limpieza de datos


### Herramientas y técnicas para la limpieza de datos 🎬

¡Hola! En este vídeo nos concentraremos en algunos problemas asociados con los datos sucios. Entre los que se incluyen ortografía y otros errores de texto, etiquetas desordenadas, formatos y longitud de campos, datos faltantes y duplicados. Esto te ayudará a reconocer los problemas más rápido y te dará la información necesaria para corregirla cuando encuentras algo similar durante tu propio análisis. Es algo increíblemente importante en el análisis computacional de datos. Pues bien, volvamos a nuestra hoja de cálculo de la oficina de legales. Para repasar rápidamente, empezaremos por observar los diferentes tipos de datos sucios que muestra. Algunas veces, alguien puede ingresar un dato con errores. Otras veces, pueden no conservar los formatos de los datos en forma uniforme. Es también común dejar un campo en blanco. También se llama valor nulo, como aprendimos antes. Y si alguien agrega el mismo dato más de una vez, se crea un duplicado. Desglosemos eso. Luego, aprenderemos sobre algunos otros tipos de datos sucios y estrategias para limpiarlos. Errores ortográficos, variaciones en la ortografía, letras mezcladas, puntuación incoherente y errores de tipeo en general suceden cuando alguien ingresa incorrectamente un dato. Como analista de datos, también trabajarás con diferentes monedas. Por ejemplo, un conjunto de datos podría estar expresado en dólares estadounidenses y otro en euros y no queremos que se mezclen. Queremos encontrar ese tipo de error y corregirlo de esta manera. Aprenderás más acerca de esto pronto. Los datos limpios dependen mayormente de las reglas de integridad de datos que sigue una organización, tales como pautas sobre ortografía y puntuación. Por ejemplo, una empresa de bebidas puede pedir a todos los que trabajan en una base de datos que ingresen datos sobre el volumen en onzas en lugar de en tazas. Es excelente cuando una organización aplica este tipo de reglas, realmente ayuda a minimizar el esfuerzo que se necesita para limpiar los datos. No obstante, puedes eliminarlos completamente, como dijimos antes, siempre hay posibilidad de que exista el error humano. El siguiente tipo de dato sucio que muestra nuestra hoja de cálculo como inconsistencia es el formato; algo que debería estar en formato de moneda se visualiza como porcentaje. Hasta que no se corrija ese error, la oficina de legales no tendrá idea de cuánto dinero pagó ese cliente por sus servicios. Aprenderemos diferentes formas de resolver este y otros problemas muy pronto. Ya hablamos previamente de los valores nulos, pero como recordatorio, los valores nulos son campos en blanco. Este tipo de dato sucio requiere un poco más de trabajo que solo corregir un error de ortografía o cambiar un formato. En este ejemplo, el analista de datos deberá investigar qué cliente hizo una consulta el 4 de julio de 2020. Luego, cuando encuentre la información correcta, la agregará a la hoja de cálculo. Otro tipo común de dato sucio es el duplicado. Puede que dos personas diferentes hayan agregado esta cita el 13 de agosto sin reparar en que alguien más ya lo había hecho. O puede ser que la persona que ingresó los datos haya copiado y pegado por accidente. Cualquiera sea la razón, es el trabajo del analista de datos identificar el error y corregirlo borrando uno de los duplicados. Pues bien, ahora sigamos con otros tipos de datos sucios. El primero tiene que ver con el etiquetado. Para entender el etiquetado, imagina tratar que una computadora identifique correctamente a los osos panda entre imágenes de diferentes tipos de animales. Debes mostrarle a la computadora miles de imágenes de osos panda, todas etiquetadas como osos panda. Cualquier imagen etiquetada incorrectamente por ejemplo, una que diga solo "oso" causará problemas. La siguiente causa de los datos sucios es tener una longitud de campo inconsistente. Ya aprendiste que un campo es un único dato en una fila o columna de una hoja de cálculo. La longitud de campo es una herramienta para determinar cuántos caracteres pueden incluirse en un campo, asignar una cierta longitud a estos campos en tu hoja de cálculo es una gran manera de evitar errores. Por ejemplo, si tienes una columna para el año de nacimiento de una persona, sabes que la longitud del campo es cuatro porque todos los años tienen una longitud de cuatro dígitos. Algunas aplicaciones de la hoja de cálculo tienen un modo simple de especificar las longitudes de campo y asegurarse de que los usuarios solo puedan ingresar un cierto número de caracteres en un campo. Esto es parte de la validación de datos. La validación de datos es una herramienta para corroborar la exactitud y la calidad de los datos antes de agregarlos o importarlos. La validación de datos es una forma de limpiar datos, de la cual pronto aprenderás más. Pero primero debes familiarizarte con más técnicas para limpiar los datos. Es una parte muy importante de los datos en este trabajo y espero compartir contigo estas estrategias de limpieza de datos.


### Limpieza de datos de multiples fuentes 🎬

¡Bienvenido nuevamente! Hasta ahora has aprendido mucho acerca de los datos sucios y cómo limpiar los errores más comunes en un conjunto de datos. Ahora vamos a dar otro paso y hablaremos de cómo limpiar múltiples conjuntos de datos. Limpiar los datos que provienen de dos o más fuentes es muy común para los analistas de datos. Sin embargo, esto trae aparejados desafíos interesantes. Un buen ejemplo es una fusión, un acuerdo que une a dos organizaciones en una nueva. En el campo de la logística, recientemente ocurrieron muchos cambios, en su mayoría, por el furor del comercio electrónico. Con tantas personas comprando en línea, tiene sentido que las empresas responsables de llevar esos productos a sus casas estén en medio de un gran terremoto. Cuando las grandes cosas suceden en una industria, es común que dos organizaciones se unan y se conviertan en una más fuerte a través de una fusión. Hablemos de cómo eso afectará nuestra asociación de logística. A modo de recordatorio, esta hoja de cálculo contiene la lista de los números de identificación de los miembros de la asociación, nombre y apellido, dirección, cuánto paga cada miembro por la cuota, cuándo vence la membresía y los tipos de membresías. Ahora pensemos qué pasaría si la Asociación Internacional de Logística decidiera unirse con la Asociación de Logística Global a fin de ayudar a sus miembros a manejar la increíble demanda del comercio electrónico. Primero, todos los datos de cada organización deben combinarse utilizando la fusión de datos. Fusionar datos es el proceso de combinar dos o más conjuntos de datos en un único conjunto de datos. Esto presenta un desafío único porque, cuando se combinan dos conjuntos de datos totalmente distintos, está casi garantizado que la información estará mal alineada y no será uniforme. Por ejemplo, la hoja de cálculo de la Asociación de Logística Global tiene una columna separada para el departamento, la oficina o el número de unidad de una persona, pero la Asociación Internacional de Logística combina esa información con la dirección postal. Esto se debe corregir para que el número de columnas con la dirección sea uniforme. A continuación, observemos cómo la Asociación de Logística Global utiliza el correo electrónico como identificación de los miembros, mientras que la Asociación Internacional de Logística utiliza números. Esto es un gran problema porque las personas en determinadas industrias, como en la logística, en general, se unen a múltiples asociaciones profesionales. Existe una gran posibilidad de que esos conjuntos de datos incluyan información de la membresía sobre exactamente la misma persona, pero de maneras diferentes. Es muy importante eliminar esos duplicados. También, la Asociación de Logística Global tiene más tipos de miembros que la otra organización. Además, utiliza el término "Joven profesional" en lugar de "Estudiante asociado". Pero ambos describen a los miembros que aún están estudiando o que se encuentran comenzando su carrera. Si estuviste fusionando esos dos conjuntos de datos, debes trabajar con tu equipo para corregir el hecho de que dos asociaciones describen a sus afiliados de manera diferente. Ahora entenderás por qué la fusión de las organizaciones también requiere fusionar los datos, lo cual puede ser delicado. Pero hay muchas otras razones por las que los analistas de datos fusionan los conjuntos de datos. Por ejemplo, en uno de mis últimos trabajos, fusioné muchos datos de múltiples fuentes para obtener información sobre las compras de los clientes. Este tipo de datos me ayudó a identificar los patrones de compra de los clientes. Al fusionar conjuntos de datos, siempre comienzo formulándome algunas preguntas clave para evitar caer en la redundancia y confirmar que los conjuntos de datos son compatibles. En el análisis computacional de datos, la compatibilidad describe si dos o más conjuntos de datos pueden trabajar juntos o no. La primera pregunta que puedes hacerte es: ¿tengo todos los datos que necesito? Para obtener información sobre las compras de los clientes, quise asegurarme de tener los datos de los clientes, sus compras y dónde las realizaron. Luego, me preguntaría: ¿los datos que necesito están en estos conjuntos de datos? Como aprendiste antes en este programa, esto implica considerar todo el conjunto de datos analíticamente. Mirar todos los datos antes de empezar a usarlos me permite intuir de qué se trata el trabajo, cómo se ve el esquema, si es relevante para mi conocimiento de las compras de los clientes y si son datos limpios. Eso nos lleva a la siguiente pregunta. ¿Deben limpiarse los conjuntos de datos o están listos para ser utilizados? Debido a que estoy trabajando con más de una fuente, también me pregunto: ¿los conjuntos de datos se limpiaron según los mismos estándares? Por ejemplo, ¿qué campos se repiten regularmente? ¿Cómo se manejan los valores faltantes? ¿Hace cuánto se actualizaron los datos? Encontrar las respuestas a estas preguntas y entender si necesito solucionar algún problema al inicio de un proyecto es un paso muy importante para la fusión de los datos. En ambos ejemplos que abordamos aquí, los analistas de datos podrían utilizar cualquiera de las herramientas de la hoja de cálculo o las consultas de SQL para limpiar, fusionar y preparar un conjunto de datos para su análisis. Dependiendo de la herramienta que decidas utilizar, la limpieza de datos puede tornarse un proceso simple o muy complejo. Pronto aprenderás a elegir lo mejor para cada situación. Como comentario final, programar lenguajes como el lenguaje R también es muy útil para limpiar datos. Aprenderás a utilizar el lenguaje R y otros conceptos que pronto cubriremos.


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



### Cuestionario: Pon a prueba tus conocimientos sobre las técnicas de limpieza de datos 📖

1. Completa el espacio en blanco: Cada base de datos tiene su propio formato, lo que puede hacer que los datos parezcan desordenados. Los analistas de datos usan la herramienta _____ para crear una apariencia prolija y uniforme visualmente de las hojas de cálculo.

   - revisar ortografía 
    
      ❌ Incorrecto.

   - formato condicional
    
      ❌ Incorrecto. Los analistas de datos usan la herramienta “borrar formatos” para crear una apariencia visual prolija y uniforme de las hojas de cálculo.

   - autocorrección
    
      ❌ Incorrecto.

    - borrar formatos
    
      ✅ Correcto. Los analistas de datos usan la herramienta “borrar formatos” para crear una apariencia visual prolija y uniforme de las hojas de cálculo.


2. ¿Cuál es el proceso para combinar dos o más conjuntos de datos en un único conjunto de datos?

   - Validación de datos 
    
      ❌ Incorrecto.

   - Fusión de datos 
    
      ✅ Correcto. Fusionar datos es el proceso para combinar dos o más conjuntos de datos en un único conjunto de datos.

   - Transferencia de datos
    
      ❌ Incorrecto.

    - Composición de datos
    
      ❌ Incorrecto.


3. Completa el espacio en blanco: En análisis computacional de datos, _____ describe qué tan bien dos o más conjuntos de datos pueden trabajar juntos.

   - la compatibilidad 
    
      ✅ Correcto. La compatibilidad describe qué tan bien dos o más conjuntos de datos pueden trabajar juntos.

   - la alineación
    
      ❌ Incorrecto. La compatibilidad describe qué tan bien dos o más conjuntos de datos pueden trabajar juntos.

   - la concordancia
    
      ❌ Incorrecto.

    - la idoneidad
    
      ❌ Incorrecto.

      
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

Hola de nuevo. Como ya aprendiste, existen muchos modos diferentes de limpiar datos. Ya te mostré algunos ejemplos de cómo se pueden limpiar los datos manualmente, por ejemplo, buscar y corregir errores de escritura o eliminar espacios vacíos o duplicados. También aprendimos que muchas aplicaciones de las hojas de cálculo tienen herramientas que ayudan a simplificar y acelerar el proceso de limpieza de datos. Existen muchas herramientas eficientes que el analista de datos utiliza todo el tiempo, por ejemplo, formato condicional, eliminación de duplicados, formato de fechas, ajuste de cadenas y subcadenas de texto, y división de texto en columnas. Ahora, exploraremos este tema en mayor detalle.

Lo primero que veremos es algo denominado formato condicional. El formato condicional se trata de una herramienta de la hoja de cálculo que cambia la forma en que se ven las celdas cuando los valores cumplen ciertas condiciones. Del mismo modo, puede indicarte cuándo una celda no cumple con las condiciones establecidas. Las indicaciones visuales como esta son muy útiles para los analistas de datos, especialmente cuando se trabaja con una hoja de cálculo grande con muchos datos. Asegurarte de resaltar algunos puntos específicos hace que la información sea más fácil de comprender y analizar. Para limpiar datos, saber cuándo esos datos no siguen la condición es muy útil. Volvamos a la hoja de cálculo de la asociación de logística para comprobar el formato condicional en acción. Utilizaremos el formato condicional para resaltar celdas en blanco. De ese modo, sabemos dónde falta información para que podamos agregarla a la hoja de cálculo. Para esto, comenzaremos por seleccionar el rango que queremos buscar. En este ejemplo no nos enfocaremos en la dirección 3 ni en la dirección 5. Estos campos incluirán todas las columnas en nuestra hoja de cálculo, excepto por F y H. Luego, iremos a Formato y elegiremos Formato condicional. Excelente. Nuestro rango queda indicado automáticamente en el campo. La regla de formato se aplicará para dar formato a las celdas si la celda está vacía. Por último, elegiremos el estilo de formato. Elegiré un color rosado fuerte para que mis espacios en blanco se destaquen. Luego, haz clic en "Hecho" y las celdas en blanco quedarán destacadas inmediatamente.

La siguiente herramienta de la hoja de cálculo elimina los duplicados. Como ya aprendiste, siempre es inteligente hacer una copia del conjunto de datos antes de eliminar algo. Hagamos eso ahora. Excelente, ahora podemos continuar. Recordarás que uno de los miembros de la asociación aparece dos veces en la lista de nuestra hoja de cálculo de ejemplo. Para solucionar este problema, vayamos a Datos y seleccionemos "Quitar duplicados". "Quitar duplicados" es una herramienta que busca automáticamente y elimina entradas duplicadas de una hoja de cálculo. Elige "Los datos tienen una fila de encabezado" porque nuestra hoja de cálculo tiene una fila arriba de todo que describe el contenido de cada columna. Luego, selecciona "Todo" porque queremos inspeccionar la totalidad de nuestra hoja de cálculo. Por último, "Quitar duplicados". Notarás que se encontró y eliminó la fila duplicada de inmediato.

Otras herramientas útiles de la hoja de cálculo te permiten lograr formatos uniformes. Por ejemplo, algunos de los datos en esta hoja de cálculo están en un formato de fecha estándar. Esto puede ser confuso si quieres analizar cuándo se asociaron ciertas personas, la frecuencia en que renuevan sus afiliaciones o cuánto tiempo han sido socios. Para hacer que los datos sean uniformes, primero, selecciona la columna J, luego dirígete a "Formato", selecciona "Número" y, luego, "Fecha". Ahora todas nuestras fechas tienen un formato uniforme.

Antes de pasar a la siguiente herramienta, quiero explicar qué es una cadena de texto. En análisis computacional de datos, una cadena de texto es un grupo de caracteres dentro de una celda, más frecuentemente compuesto por letras. Una característica importante de una cadena de texto es su longitud, que es el número de caracteres en ella. Aprenderemos más al respecto muy pronto. Por ahora, es útil saber también que una subcadena es un subconjunto más pequeño de una cadena de texto. Ahora, hablemos de SPLIT. SPLIT es una herramienta que divide una cadena de texto en un carácter especificado y ubica cada fragmento en una celda nueva y separada. SPLIT es útil cuando tienes más de un dato en una celda y quieres separarlos. Puede ser el nombre y apellido de una persona juntos en la lista o puede ser una celda que contiene la ciudad, el estado, el país y el código postal de una determinada persona, pero que, en realidad, quieres que cada uno de esos datos esté en una columna independiente. Digamos que esta asociación quiere analizar todas las diferentes certificaciones profesionales de sus miembros. Para hacerlo, quieres que cada certificación esté separada en su propia columna. En este momento, las certificaciones están separadas por una coma. Este es el texto específico que separa a cada elemento, también denominado delimitador. Separemos los datos. Resalta la columna y, luego, selecciona "Datos" y "Dividir texto en columnas". Esta aplicación de la hoja de cálculo sabrá automáticamente que la coma es el delimitador y separará cada certificación. Pero, algunas veces, puedes necesitar especificar cuál sería el delimitador. Puedes hacerlo aquí. Dividir el texto en columnas también es útil para corregir instancias en que los números se guardaron como texto. Algunos valores en tu hoja de cálculo pueden verse como números, pero están formateados como texto. Esto puede ocurrir cuando se copia y pega desde un lugar a otro o si el formato es incorrecto. Para este ejemplo, observemos nuestra nueva hoja de cálculo de un fabricante de cosméticos. Si el analista de datos quiere determinar las ganancias totales, puede sumar todo en la columna F. Pero hay un problema, una de las celdas tiene un error. Si la controlas, verás que el número "707" en esta celda es texto y no se puede cambiar a número. Cuando la hoja de cálculo trata de multiplicar el costo del producto por el número de unidades vendidas, no logras realizar ese cálculo. Pero si seleccionamos ordenar por columna y "Dividir texto en columna" el error se resuelve porque ahora se lo puede tratar como número.

Luego, aprenderás sobre una herramienta que hace exactamente lo opuesto. CONCATENATE es una función que une múltiples cadenas de texto para formar una sola. Las hojas de cálculo son una parte muy importante del análisis computacional de datos. Ahorran tiempo y esfuerzo a los analistas de datos y ayudan a eliminar los errores todos los días. Pues bien, ya aprendiste algunas cosas sobre las herramientas de uso más comunes. Pero hay mucho más por venir. Después aprenderemos más sobre la limpieza de datos con las herramientas de las hojas de cálculo. ¡Hasta pronto!


### Optimización del proceso de limpieza de datos 🎬

¡Bienvenido nuevamente! Ya conoces algunas herramientas muy útiles para limpiar datos incluidas en las aplicaciones de las hojas de cálculo. Ahora exploraremos cómo las funciones pueden optimizar tus esfuerzos para garantizar la integridad de los datos.

Como recordatorio, una función es un conjunto de instrucciones que realizan un cálculo específico usando los datos de una hoja de cálculo. La primera función que abordaremos se denomina COUNTIF. COUNTIF es la función que devuelve un número de celdas que coinciden con un valor específico. Básicamente, cuenta el número de veces que aparece un valor en un rango de celdas.

Volvamos a nuestra hoja de cálculo de una asociación profesional. En este ejemplo, queremos asegurarnos de que los precios de la membresía a la asociación en la lista sean precisos. Utilizaremos COUNTIF para controlar algunos de los problemas comunes, como números negativos o valores muy inferiores o superiores a lo esperado.

Para comenzar, encontremos el valor de afiliación más bajo: $100 por asociado. Ese será el número más bajo que existe en esa columna. Si una celda tiene un valor inferior a 100, COUNTIF nos dará el alerta.

Agregaremos unas filas más al final de nuestra hoja de cálculo, luego, debajo de la columna H, escribe "valor de afiliación menor a $100". A continuación, escribe la función en la celda contigua. Cada función tiene una cierta sintaxis que hay que seguir para que funcione. La sintaxis es una estructura predeterminada que incluye toda la información necesaria y su lugar exacto.

La sintaxis de la función COUNTIF debería ser la siguiente: `=COUNTIF(rango, "valor")`. Donde "rango" es de I2 hasta I72 y el "valor" es inferior a 100. Esto le indica a la función que atraviese la columna I y devuelva un conteo de todas las celdas que contienen un número inferior a 100. ¡Y resulta que solo hay uno!

Al revisar los datos, encontramos que un dato se ingresó por error como número negativo. Corrijamos eso. Ahora usaremos COUNTIF para buscar cualquier valor mayor a lo esperado. El tipo más costoso de membresía es de $500 para socios corporativos. Escribe la función en la celda. Esta vez aparecerá de esta forma: `=COUNTIF(rango, "valor")`. De I2 hasta I72 es todavía el rango, pero el "valor" es superior a 500. También hay uno. Vamos a analizarlo. Esta entrada tiene un cero extra. Debería ser $100.

La próxima función que abordaremos se llama LEN. LEN es una función que indica la longitud de una cadena de texto al contar el número de caracteres en una cadena de texto. Esto es útil cuando se limpian datos, si tienes un determinado dato en tu hoja de cálculo que sabes que debe tener una cierta longitud.

La sintaxis de LEN es `=LEN(rango)`. Insertaremos una nueva columna después del número de ID de socio. Luego, el `=LEN(rango)` nos indica que hay seis caracteres en la celda A2. Continuemos con la función en toda la columna y veamos si hay algún resultado que no sea seis.

Pero, en lugar de hacerlo manualmente recorriendo toda la hoja de cálculo para buscar estas instancias, utilizaremos el formato condicional. Hablamos del formato condicional anteriormente. Se trata de una herramienta de la hoja de cálculo que cambia cómo aparecen las celdas cuando los valores cumplen condiciones específicas. Practiquemos ahora.

Selecciona toda la columna B, excepto el encabezado. Luego dirígete a Formato y elige Formato condicional. La regla de formato está para dar formato a celdas que no arrojen seis como resultado. Haz clic en "Hecho". La celda que contiene el siete queda resaltada.

Ahora, vamos a hablar de LEFT y RIGHT. LEFT es la función que te brinda un cierto número de caracteres a la izquierda de una cadena de texto. RIGHT es la función que te brinda un cierto número de caracteres a la derecha de una cadena de texto.

Como recordatorio rápido, una cadena de texto es un grupo de caracteres dentro de una celda, compuesta comúnmente por letras, números o ambos.

Para ver estas funciones en acción, volvamos a la hoja de cálculo del fabricante de cosméticos que ya usamos. Esta hoja de cálculo contiene códigos de productos. Cada producto tiene un código numérico de cinco dígitos y un identificador de texto de cuatro letras. Pero digamos que solo queremos trabajar con uno o el otro.

Puedes usar LEFT o RIGHT para obtener el conjunto específico de caracteres o números que necesitas. Practicaremos limpiar nuestros datos usando la función LEFT primero. La sintaxis de LEFT es `=LEFT(rango, num_caracteres)`. Aquí, nuestro proyecto requiere solo los código numéricos de cinco dígitos. En una columna separada, escribe `=LEFT(rango, 5)`. Nuestra función se debe ver así. Presiona "Enter". Ahora, tenemos una subcadena que es la parte numérica del código de producto solamente. Haz clic y arrastra esta función por toda la columna para separar el resto de los códigos de producto solo por número.

Bien, ahora, digamos que nuestro proyecto solo necesita el identificador de texto de cuatro caracteres. Para eso, usaremos la función RIGHT y la función comenzará en la siguiente columna. La sintaxis es `=RIGHT(rango, num_caracteres)`. Escribe `=RIGHT(rango, 4)`. Luego, arrastra la función por toda la columna. Ahora podemos analizar el producto en nuestra hoja de cálculo de acuerdo con alguna de las subcadenas. El código numérico de cinco dígitos o el identificador de texto de cuatro caracteres.

Espero que esto clarifique cómo utilizar LEFT y RIGHT para extraer subcadenas de la izquierda y derecha de una cadena. Ahora, aprendamos a extraer datos que se encuentran en el medio. Aquí usaremos algo llamado MID.

MID es la función que te brinda un segmento desde la mitad de una cadena de texto. La sintaxis para MID es: `=MID(rango, punto_inicio, num_caracteres)`. Al utilizar MID, siempre necesitas colocar un punto de referencia. En otras palabras, puedes establecer dónde debería comenzar la función. Después de eso, escribes cuántos caracteres quieres en el medio.

En una nueva columna, escribe `=MID(rango, 4, 2)`. Presiona "Enter" y ¡eureka!, solo obtenemos la abreviatura del estado. Continúa utilizando la función MID en el resto de la columna.

Hemos aprendido algunas funciones que ayudan a separar cadenas de texto específicas. Pero, ¿qué pasa si queremos combinarlas? Para eso, utilizaremos CONCATENATE, que es una función que une dos o más cadenas de texto.

La sintaxis es `=CONCATENATE(cadena1, cadena2, ...)`. Solo para practicar, digamos que necesitamos volver a unir las cadenas de texto de la izquierda y de la derecha para volver a formar códigos completos de producto. En una nueva columna, comencemos nuestra función. Escribe `=CONCATENATE(cadena1, cadena2)`. Luego, arrastra eso por toda la columna y, así de sencillo, nuestros códigos de producto vuelven a unirse.

La última función que abordaremos es TRIM. TRIM es una función que quita los espacios de más al principio, al final o repetidos en los datos.

La sintaxis para TRIM es: `=TRIM(rango)`. En una columna separada, escribe `=TRIM(rango)`. TRIM corregirá los espacios extra.

Ahora conocemos algunas funciones útiles que pueden hacer de tu limpieza de datos un éxito. Como siempre, siéntete libre de volver a ver este vídeo y practicar por tu cuenta. Continuaremos agregando conocimientos sobre estas herramientas en breve y también tendrás la oportunidad de practicar. Muy pronto, estos pasos para limpiar datos serán algo totalmente natural, como cepillarte los dientes.


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

¡Hola! Parece que estás listo para comenzar. En el mundo del análisis de datos, como dijo Wayne Dyer, cambiar la forma en que vemos las cosas puede cambiar las cosas que vemos. En el análisis computacional de datos, esto es especialmente cierto. Cada proyecto de análisis de datos es único, y es crucial adaptar nuestros enfoques para cada situación específica.

En este video, exploraremos diferentes métodos utilizados por los analistas de datos para cambiar su perspectiva sobre los datos, lo que los lleva a realizar una limpieza más eficiente y efectiva de los mismos. Algunos de estos métodos incluyen ordenar y filtrar datos, trabajar con tablas dinámicas, utilizar la función VLOOKUP y realizar trazados para identificar valores atípicos.

Comencemos con el ordenamiento y el filtrado. Estas herramientas no solo son útiles para organizar y personalizar los datos, sino que también son excelentes para la limpieza de datos. Ordenar los datos puede ayudar a identificar entradas duplicadas o a organizar los datos de manera que sea más fácil encontrar la información necesaria. Por otro lado, los filtros son útiles para encontrar datos específicos que cumplen con ciertos criterios, lo que facilita separar la información relevante del resto.

Otro método para cambiar la perspectiva sobre los datos es mediante el uso de tablas dinámicas. Estas herramientas son excelentes para resumir y visualizar datos de manera rápida y clara. Pueden proporcionar una vista rápida y sin desorden de tus datos, lo que facilita identificar tendencias o patrones importantes.

Vamos a crear una tabla dinámica utilizando la hoja de cálculo de los fabricantes de cosméticos nuevamente. Seleccionaremos los datos que queremos usar y crearemos una nueva tabla dinámica. Digamos que queremos analizar los productos más rentables. Podemos ordenar la tabla dinámica en función de las ganancias totales y filtrar los productos que generan al menos $10,000 en órdenes de compra.

Después de identificar los productos más rentables, es posible que necesitemos obtener más información sobre ellos. Aquí es donde entra en juego la función VLOOKUP. VLOOKUP nos permite buscar un valor específico en una columna y devolver la información correspondiente de otra columna. Esta función es útil cuando necesitamos buscar información en diferentes hojas de cálculo o bases de datos.

Por último, el trazado de datos nos permite visualizar los datos de una manera que nos ayude a identificar rápidamente cualquier anomalía o valor atípico. Por ejemplo, podemos trazar los precios de los productos en un gráfico de columnas para identificar cualquier precio anormalmente bajo o alto.

En resumen, cambiar la forma en que vemos los datos nos permite identificar y limpiar más eficientemente cualquier dato incorrecto o inconsistente. Estos métodos son herramientas poderosas en el arsenal de cualquier analista de datos y pueden marcar la diferencia en la calidad y precisión de los resultados obtenidos.

¡Gran trabajo hasta aquí! ¿Listo para practicar estos nuevos conceptos y continuar aprendiendo más estrategias para garantizar la integridad de los datos?


### Incluso mas técnicas de limpieza de datos 🎬

¡Hola de nuevo! Es genial que estemos profundizando en los aspectos generales relacionados con la limpieza de datos. El mapeo de datos es una parte fundamental de este proceso, ya que nos permite hacer coincidir campos entre diferentes bases de datos para garantizar la compatibilidad y la integridad de los datos durante la migración, la integración y otras actividades de administración de datos.

Como ya hemos aprendido, los diferentes sistemas almacenan los datos de manera diferente, lo que puede resultar en discrepancias en los formatos de los datos. Por ejemplo, un estado puede estar almacenado como "Maryland" en una hoja de cálculo y como "MD" en otra. El mapeo de datos nos ayuda a identificar y abordar estas diferencias para garantizar que los datos sean compatibles cuando se transfieren y combinen.

El proceso de mapeo de datos comienza identificando qué datos deben moverse, incluyendo las tablas y los campos dentro de ellas. Luego, definimos el formato deseado para los datos una vez que lleguen a su destino. Esto puede incluir decisiones sobre el tipo de datos que se utilizarán, como números o direcciones de correo electrónico.

El mapeo de datos puede ser simple o complejo, dependiendo del esquema y el número de claves primarias y externas en la fuente de datos. Para proyectos más desafiantes, existen herramientas de software especializadas en mapeo de datos que pueden automatizar y simplificar este proceso.

Al seleccionar una herramienta de software para mapear datos, es importante asegurarse de que sea compatible con el tipo de archivo con el que estás trabajando, como Excel, SQL, Tableau, entre otros.

Ahora, vamos a practicar el mapeo manual de datos. Esto implica determinar el contenido de cada sección de datos y asegurarnos de que los datos terminen en el lugar correcto en la fuente de datos fusionada. También puede implicar la transformación de los datos en un formato uniforme utilizando funciones como la concatenación.

Una vez que los datos están mapeados correctamente, es hora de transferirlos a su destino utilizando diversas herramientas y métodos, como consultas, asistentes de importación o simplemente arrastrar y soltar. Después, realizaremos pruebas para asegurarnos de que los datos estén limpios y tengan el formato adecuado antes de comenzar su análisis.

En resumen, el mapeo de datos es una parte crucial del proceso de limpieza de datos que garantiza la integridad y la compatibilidad de los datos durante su transferencia y combinación. Es fundamental para evitar errores que puedan afectar los resultados del análisis y proporciona una hoja de ruta clara para garantizar que los datos lleguen seguros a su destino.


### Actividades practicas: Limpiar datos con funciones de la hoja de cálculo 📖


### Registro de aprendizaje: Desarrolla tu enfoque para la limpieza de datos 📖


### Cuestionario: Pon a prueba tus conocimientos sobre la limpieza de datos en hojas de calculo 📖

1. Completa el espacio en blanco: Cada base de datos tiene su propio formato, lo que puede hacer que los datos parezcan desordenados. Los analistas de datos usan la herramienta _____ para crear una apariencia prolija y uniforme visualmente de las hojas de cálculo.

   - revisar ortografía 
    
      ❌ Incorrecto.

   - formato condicional
    
      ❌ Incorrecto. Los analistas de datos usan la herramienta “borrar formatos” para crear una apariencia visual prolija y uniforme de las hojas de cálculo.

   - autocorrección
    
      ❌ Incorrecto.

    - borrar formatos
    
      ✅ Correcto. Los analistas de datos usan la herramienta “borrar formatos” para crear una apariencia visual prolija y uniforme de las hojas de cálculo.


2. ¿Cuál es el proceso para combinar dos o más conjuntos de datos en un único conjunto de datos?

   - Validación de datos 
    
      ❌ Incorrecto.

   - Fusión de datos 
    
      ✅ Correcto. Fusionar datos es el proceso para combinar dos o más conjuntos de datos en un único conjunto de datos.

   - Transferencia de datos
    
      ❌ Incorrecto.

    - Composición de datos
    
      ❌ Incorrecto.


3. Completa el espacio en blanco: En análisis computacional de datos, _____ describe qué tan bien dos o más conjuntos de datos pueden trabajar juntos.

   - la compatibilidad 
    
      ✅ Correcto. La compatibilidad describe qué tan bien dos o más conjuntos de datos pueden trabajar juntos.

   - la alineación
    
      ❌ Incorrecto. La compatibilidad describe qué tan bien dos o más conjuntos de datos pueden trabajar juntos.

   - la concordancia
    
      ❌ Incorrecto.

    - la idoneidad
    
      ❌ Incorrecto.


---

## 4. Desafio semanal 2 🙋🏻‍♀️ 

### Temario: 

- Glosario: Términos y definiciones
- Desafio semanal 2

### Glosario: Términos y definiciones 📖


### Desafio semanal 2 📖


1. Como parte del proceso de limpieza de datos, un analista de datos crea una regla para resaltar cualquier celda vacía con un color azul brillante. Este es un ejemplo de visualización de datos.

   - Verdadero 
    
      ❌ Incorrecto.

   - Falso
    
      ✅ Correcto.


2. El delimitador es un carácter que indica el principio o el fin de un elemento de datos. ¿La herramienta de división de texto en columnas utiliza un delimitador para realizar qué tarea?

   - Dividir una columna en dos 
    
      ❌ Incorrecto.

   - Separar subcadenas duplicadas
    
      ❌ Incorrecto. 

   - Especificar dónde separar una cadena de texto
    
      ✅ Correcto.

    - Cambiar el formato de una columna de texto 
    
      ❌ Incorrecto. 


✅ Correcto.
3. Para que una función funcione correctamente, el analista de datos debe seguir la estructura predeterminada de cada función. ¿Cómo se llama esa estructura?

   - Algoritmo 
    
      ❌ Incorrecto.

   - Sintaxis
    
      ❌ Incorrecto. 

   - Resumen
    
      ❌ Incorrecto.

    - Validación
    
      ❌ Incorrecto.


✅ Correcto.
4. Estás trabajando con la siguiente selección de una hoja de cálculo. ¿Cuál es la función correcta para extraer el código postal de cinco dígitos de Brandon, FL? 

   - =LEFT(5,B4) 
    
      ❌ Incorrecto.

   - =LEFT(B4,5)
    
      ❌ Incorrecto. 

   - =RIGHT(5,B4)
    
      ❌ Incorrecto.

    - =RIGHT(B4,5)
    
      ❌ Incorrecto. 


✅ Correcto.
5. El analista de datos de un departamento de recursos humanos está trabajando con la siguiente selección de una hoja de cálculo. Quiere crear números de identificación (ID) de empleados en la columna D. Los ID deben incluir el año de contratación y los últimos cuatro dígitos del Número de Seguro Social (SS#). ¿Qué función creará el ID 20142683 para el empleado en la fila 3?

   - =CONCATENATE(A3+B3) 
    
      ❌ Incorrecto.

   - =CONCATENATE(A3,B3)
    
      ❌ Incorrecto. 

   - =CONCATENATE(A3!B3)
    
      ❌ Incorrecto.

    - =CONCATENATE(A3*B3)
    
      ❌ Incorrecto.


✅ Correcto.
6. El analista de datos de una empresa de comercio electrónico está trabajando con una hoja de cálculo que contiene las ventas del último mes. El producto más caro que vende la empresa cuesta $49.99, así que quiere confirmar rápidamente que todos los datos de la columna Ventas sean $49.99 o inferiores. ¿Qué función puede usar?

   - COUNTIF 
    
      ❌ Incorrecto.

   - COUNT
    
      ❌ Incorrecto. 

   - SUMIF
    
      ❌ Incorrecto.

    - SUM
    
      ❌ Incorrecto. 


✅ Correcto.
7. VLOOKUP busca un valor en una fila y brinda la información correspondiente.

   - Verdadero 
    
      ❌ Incorrecto.

   - Falso
    
      ❌ Incorrecto. 


✅ Correcto.
8. Para evaluar el funcionamiento conjunto de dos o más fuentes de datos, los analistas de datos usan el mapeo de datos. 

   - Verdadero 
    
      ❌ Incorrecto.

   - Falso
    
      ❌ Incorrecto. 





































































































      
