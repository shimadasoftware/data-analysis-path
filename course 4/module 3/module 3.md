# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 3: Limpieza de datos con SQL
**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Conocer diversas formas de limpiar los datos puede facilitar mucho el trabajo de un analista. En esta parte del curso, comprobarás cómo limpiar tus datos usando SQL. Explorarás las consultas y funciones que puedes usar en SQL para limpiar y transformar tus datos y dejarlos listos para el análisis.

## Objetivos

- Describir cómo se puede usar SQL para limpiar grandes conjuntos de datos
- Comparar las funciones de limpieza de datos de las hojas de cálculo con las asociadas a SQL en bases de datos
- Desarrollar consultas SQL básicas para su uso con bases de datos
- Aplicar funciones básicas de SQL para su uso en la limpieza de variables de cadena en una base de datos
- Aplicar funciones básicas de SQL para transformar variables de datos

Este primer modulo se divide en:

1. Uso de SQL para limpiar los datos
2. Aprende sobre consultas básicas de SQL
3. Transformación de datos
4. Desafio semanal 3


---

## 1. Uso de SQL para limpiar los datos 🙋🏻‍♀️ 

### Temario: 

- Uso de SQL para limpiar los datos
- Por el amor de SQL
- Comprender las capacidades de SQL
- Usar SQL como analista de datos junior
- Hojas de cálculo vs. SQL
- Dialectos de SQL y sus usos
- Actividad práctica: Tiempo de procesamiento con SQL
- Cuestionario: Pon a prueba tus conocimientos sobre SQL


### Uso de SQL para limpiar los datos 🎬

Bienvenido de nuevo y gran trabajo en el último desafío semanal. Ahora que sabemos la diferencia entre limpiar datos sucios y algunas técnicas generales de limpieza de datos, vamos a centrarnos en la limpieza de datos mediante SQL. A continuación aprenderemos sobre las diferentes funciones de limpieza de datos en hojas de cálculo y SQL y cómo se puede utilizar SQL para limpiar grandes conjuntos de datos. También te mostraré cómo desarrollar algunas consultas de búsqueda básicas para bases de datos y cómo aplicar funciones básicas de SQL para transformar datos y limpiar cadenas. 

La limpieza de los datos es el último paso en el proceso de análisis de datos antes de pasar al análisis propiamente dicho, y SQL tiene muchas herramientas excelentes que pueden ayudarte a hacerlo. Pero antes de empezar a limpiar las bases de datos, vamos a echar un vistazo más de cerca a SQL y cuándo utilizarlo. Nos vemos luego.


### Por el amor de SQL 🎬

¡Hola Sally! Es genial escuchar sobre tu experiencia y cómo estás ayudando a las agencias publicitarias a aprovechar al máximo las plataformas de datos para crear informes más rápidos y efectivos para sus clientes. 

El análisis de datos es realmente fundamental en todos los sectores, y es fantástico ver cómo estás promoviendo su uso en el ámbito de la publicidad y más allá. SQL, en particular, ha demostrado ser una herramienta invaluable para analizar grandes volúmenes de datos de manera eficiente, y es genial saber que has desarrollado tus habilidades en este campo por tu cuenta.

El hecho de que el análisis de datos esté en constante evolución y que la tecnología esté mejorando para proporcionar resultados más rápidos y precisos es emocionante. Sin duda, el futuro de la carrera de analista de datos es prometedor, y tu experiencia y pasión seguramente te llevarán lejos en este campo.

¡Gracias por compartir tu historia y tu perspectiva en el emocionante mundo del análisis de datos!


### Comprender las capacidades de SQL 🎬

¡Hola de nuevo! Gracias por esa presentación completa de SQL. Es impresionante pensar en la cantidad de datos que este lenguaje puede manejar de manera eficiente y rápida. Además, conocer un poco de la historia detrás de SQL agrega un contexto interesante a su desarrollo y evolución.

Es genial escuchar cómo descubriste SQL por necesidad en tu primer trabajo como analista de datos y cómo te lanzaste a aprenderlo por tu cuenta. Realmente resalta la importancia de la autodisciplina y el autodescubrimiento en el mundo del análisis de datos.

Estoy emocionado de seguir adelante y aprender sobre las aplicaciones prácticas de SQL en el manejo de datos. ¡Hasta pronto!


### Usar SQL como analista de datos junior 📖

En esta lectura, aprenderás más sobre cómo decidir cuándo usar SQL, o lenguaje de consulta estructurado. Como analista de datos, tendrás que manejar muchos datos, y SQL es una de las herramientas que pueden facilitarte mucho el trabajo. SQL es la principal forma en que los analistas de datos extraen datos de las bases de datos. Como analista de datos, trabajarás con bases de datos todo el tiempo, por lo que SQL es una habilidad clave. Veamos cómo un analista de datos júnior utiliza SQL para resolver una tarea empresarial.  

#### La tarea empresarial y el contexto

El analista de datos júnior de este ejemplo trabaja para una empresa de redes sociales. El 15 de febrero de 2020 se implantó un nuevo modelo de negocio y la empresa quiere saber cómo se compara su crecimiento de usuarios con el año anterior. En concreto, se pidió al analista de datos que averiguara cuántos usuarios se han incorporado desde el 15 de febrero de 2020.

#### ¿Funciones y fórmulas de las hojas de cálculo o consultas SQL?

Antes de abordar esta cuestión, este analista de datos debe elegir qué herramienta usar. En primer lugar, hay que pensar en dónde residen los datos. Si se almacenan en una base de datos, entonces SQL es la mejor herramienta para el trabajo. Pero si se almacenan en una hoja de cálculo, entonces habrá que realizar el análisis en esa hoja de cálculo. En ese escenario, se podría crear una tabla dinámica de los datos y luego aplicar fórmulas y filtros específicos a sus datos hasta obtener el número de usuarios que se unieron después del 15 de febrero. No es un proceso realmente complicado, pero implicaría muchos pasos. 

En este caso, los datos se almacenan en una base de datos, por lo que tendrá que trabajar con SQL. Y este analista de datos sabe que podría obtener los mismos resultados con una sola consulta SQL: 

![image](./img/module%2001%20img%2001.png)

Tanto las hojas de cálculo como el SQL tienen sus ventajas y desventajas:

![image](./img/module%2001%20img%2002.png)

A la hora de la verdad, el lugar donde se encuentren los datos definirá qué herramienta utilizar. Si trabajas con datos que ya están en una hoja de cálculo, lo más probable es que sea ahí donde realices tu análisis. Y si estás trabajando con datos almacenados en una base de datos, SQL será la mejor herramienta que puedas usar para tu análisis. A continuación aprenderás más sobre SQL, para que estés preparado para abordar cualquier problema de negocios con la mejor herramienta posible. 


### Hojas de cálculo vs. SQL 🎬

¡Hola! Es genial ver cómo comparas y contrastas las hojas de cálculo con SQL. Realmente resalta las fortalezas y diferencias de cada uno y cómo pueden complementarse entre sí en diferentes contextos de análisis de datos.

Es interesante ver cómo SQL puede manejar conjuntos de datos mucho más grandes y complejos de una manera más eficiente que las hojas de cálculo, lo que lo hace ideal para situaciones donde se requiere trabajar con datos a gran escala.

También aprecio cómo destacas que, si bien las hojas de cálculo son excelentes para trabajos más pequeños y para usuarios individuales, SQL brinda ventajas significativas cuando se trata de colaboración en equipos grandes y acceso a bases de datos complejas.

Estoy emocionado de seguir aprendiendo sobre nuevas consultas y funciones en SQL que nos ayudarán a explorar aún más el potencial de este lenguaje en el análisis de datos. ¡Hasta la próxima!


### Dialectos de SQL y sus usos 📖

En esta lectura, aprenderás más sobre los dialectos de SQL y algunos de sus diferentes usos. Como repaso rápido, el lenguaje de consulta estructurado, o SQL, es un lenguaje que se usa para hablar con las bases de datos. Aprender SQL puede ser muy parecido a aprender un nuevo idioma, incluyendo el hecho de que los idiomas suelen tener diferentes dialectos dentro de ellos. Algunos productos de bases de datos tienen su propia variante de SQL, y estas diferentes variedades de dialectos de SQL son las que te ayudan a comunicarte con cada producto de base de datos.

Estos dialectos serán diferentes de una empresa a otra y pueden cambiar con el tiempo si la empresa pasa a otro sistema de base de datos. Por lo tanto, muchos analistas comienzan con el SQL estándar y luego ajustan el dialecto que utilizan en función de la base de datos con la que trabajan. El SQL estándar funciona con la mayoría de las bases de datos y requiere un pequeño número de cambios sintácticos para adaptarse a otros dialectos.

Como analista de datos júnior, es importante saber que existen ligeras diferencias entre los dialectos. Pero si dominas el SQL estándar, que es el dialecto con el que trabajarás en este programa, estarás preparado para utilizar SQL en cualquier base de datos. 

#### Más información

Puede que no necesites conocer todos los dialectos de SQL, pero es útil saber que existen. Si estás interesado en aprender más sobre los dialectos de SQL y cuándo se utilizan, puedes consultar estos recursos para obtener más información:

- El blog de LearnSQL, [¿Qué es un dialecto SQL y cuál deberías aprender?](https://learnsql.com/blog/what-sql-dialect-to-learn/)

- El artículo de Software Testing Help, [Diferencias entre SQL Vs MySQL vs SQL Server](https://www.softwaretestinghelp.com/sql-vs-mysql-vs-sql-server/)

- El blog de Datacamp, [SQL Server, PostgreSQL, MySQL... ¿Cuál es la diferencia? ¿Por dónde empiezo?](https://www.datacamp.com/blog/sql-server-postgresql-mysql-whats-the-difference-where-do-i-start) Nota que hay un error en este artículo del blog. En la tabla comparativa se indica incorrectamente que SQlite utiliza subconsultas en lugar de funciones de ventana. Consulta la documentación de las [funciones de ventana de SQLite](https://sqlite.org/windowfunctions.html) para una aclaración adecuada.

- El tutorial de SQL Tutorial, [¿Qué es SQL?](https://www.sqltutorial.org/what-is-sql/)


### Actividad práctica: Tiempo de procesamiento con SQL 📖



### Cuestionario: Pon a prueba tus conocimientos sobre SQL 📖


1. ¿Cuáles de los siguientes son los beneficios de usar SQL? Selecciona todas las opciones que correspondan. 

   - SQL ofrece potentes herramientas para la limpieza de datos. 
    
      ✅ Correcto. SQL puede manejar grandes cantidades de datos, puede ser adaptado y usado con múltiples programas de bases de datos, y ofrece potentes herramientas para la limpieza de datos.

   - SQL puede manejar grandes cantidades de datos.
    
      ✅ Correcto. SQL puede manejar grandes cantidades de datos, puede ser adaptado y usado con múltiples programas de bases de datos, y ofrece potentes herramientas para la limpieza de datos.

   - Se puede utilizar SQL para programar microprocesadores en servidores de bases de datos.
    
      ❌ Incorrecto.

    - Se puede adaptar y utilizar SQL con múltiples programas de bases de datos. 
    
      ✅ Correcto. SQL puede manejar grandes cantidades de datos, puede ser adaptado y usado con múltiples programas de bases de datos, y ofrece potentes herramientas para la limpieza de datos.


2. ¿Cuál de las siguientes tareas pueden realizar los analistas de datos utilizando tanto hojas de cálculo como SQL? Selecciona todas las opciones que correspondan. 

   - Realizar operaciones aritméticas   
    
      ✅ Correcto. Los analistas pueden usar SQL y hojas de cálculo para realizar operaciones aritméticas, usar fórmulas y unir datos.

   - Unir datos  
    
      ✅ Correcto. Los analistas pueden usar SQL y hojas de cálculo para realizar operaciones aritméticas, usar fórmulas y unir datos.
 
   - Usar fórmulas
    
      ✅ Correcto. Los analistas pueden usar SQL y hojas de cálculo para realizar operaciones aritméticas, usar fórmulas y unir datos.

    - Procesar grandes cantidades de datos de forma eficiente 
    
      ❌ Incorrecto.


3. SQL es un lenguaje que se usa para comunicarse con las bases de datos. Como la mayoría de los lenguajes, SQL tiene dialectos. ¿Cuáles son las ventajas de aprender y usar el SQL estándar? Selecciona todas las opciones que correspondan. 

   - Las bases de datos traducen automáticamente el SQL estándar a otros dialectos. 
    
      ❌ Incorrecto.

   - El SQL estándar requiere un pequeño número de cambios de sintaxis para adaptarse a otros dialectos.
    
      ✅ Correcto. El SQL estándar funciona con la mayoría de las bases de datos y requiere un pequeño número de cambios sintácticos para adaptarse a otros dialectos. 

   - El SQL estándar es mucho más fácil de aprender que otros dialectos.
    
      ❌ Incorrecto.

    - El SQL estándar funciona con la mayoría de las bases de datos.
    
      ✅ Correcto. El SQL estándar funciona con la mayoría de las bases de datos y requiere un pequeño número de cambios sintácticos para adaptarse a otros dialectos. 









---

## 2. Aprende sobre consultas básicas de SQL 🙋🏻‍♀️ 

### Temario: 

- A limpiarlos! 
- Por qué es importante limpiar los datos
- Por qué me encanta limpiar datos
- ¿Qué son los datos sucios?
- Reconocer y subsanar los datos sucios
- Integridad de datos/datos limpios y sucios
- Poner a prueba tus conocimientos sobre datos limpios versus sucios





---

## 3. Transformación de datos 🙋🏻‍♀️ 

### Temario: 

- A limpiarlos! 
- Por qué es importante limpiar los datos
- Por qué me encanta limpiar datos
- ¿Qué son los datos sucios?
- Reconocer y subsanar los datos sucios
- Integridad de datos/datos limpios y sucios
- Poner a prueba tus conocimientos sobre datos limpios versus sucios







---

## 4. Desafio semanal 3 🙋🏻‍♀️ 

### Temario: 

- A limpiarlos! 
- Por qué es importante limpiar los datos
- Por qué me encanta limpiar datos
- ¿Qué son los datos sucios?
- Reconocer y subsanar los datos sucios
- Integridad de datos/datos limpios y sucios
- Poner a prueba tus conocimientos sobre datos limpios versus sucios
