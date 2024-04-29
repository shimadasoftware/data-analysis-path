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

Hola de nuevo. Hasta ahora aprendimos que SQL tiene algunas de las mismas herramientas que las hojas de cálculo, pero a una escala mucho mayor. En este video, aprenderemos algunas de las consultas SQL más utilizadas que puedes empezar a usar para tu propia limpieza de datos y su posterior análisis. ¡Empecemos! Hemos hablado de las consultas como solicitudes que se hacen a la base de datos para pedirle que haga cosas por ti. Las consultas son una parte importante del uso de SQL. Después de todo, es un lenguaje de consulta estructurado. Las consultas pueden ayudarte a hacer muchas cosas, pero hay algunas comunes que los analistas de datos usan todo el tiempo. Así que vamos a empezar por ahí. Primero, te mostraré cómo usar la consulta SELECT. He mencionado esta antes, pero ahora añadiré algunas cosas nuevas para que las probemos. Ahora mismo, el visor de la tabla está en blanco porque todavía no hemos extraído nada de la base de datos. Para este ejemplo, la tienda con la que estamos trabajando está organizando un sorteo para los clientes de ciertas ciudades. Tenemos una base de datos que contiene información de los clientes que podemos usar para determinar qué clientes pueden participar en el sorteo. Hagamos eso ahora. Podemos usar SELECT para especificar exactamente con qué datos queremos interactuar en una tabla. Si combinamos SELECT con FROM, podemos extraer datos de cualquier tabla en esta base de datos siempre que sepamos cómo se llaman las columnas y las filas. Podríamos querer sacar los datos sobre nombres de clientes y ciudades de una de las tablas. Para ello, podemos introducir SELECT nombre, coma, ciudad FROM cliente guión bajo datos punto cliente guión bajo dirección. Para obtener esta información de la tabla cliente guión bajo domicilio, que se encuentra en el conjunto de datos cliente guión bajo datos. SELECT y FROM ayudan a especificar qué datos queremos extraer de la base de datos y utilizar. También podemos insertar nuevos datos en una base de datos o actualizar los datos existentes. Por ejemplo, tal vez tengamos un nuevo cliente que queremos insertar en esta tabla. Podemos usar la consulta INSERT INTO para introducir esa información. Comencemos con el lugar donde estamos tratando de insertar estos datos, la tabla cliente guión bajo domicilio. También queremos especificar a qué columnas estamos añadiendo estos datos escribiendo sus nombres en los paréntesis. De esta manera, SQL puede decirle a la base de datos exactamente dónde estamos introduciendo nueva información. Luego le diremos qué valores estamos introduciendo. Ejecutamos la consulta, y como si nada, lo agrega a nuestra tabla por nosotros. Ahora, digamos que solo necesitamos cambiar la dirección de un cliente. Bien, podemos decirle a la base de datos que la actualice por nosotros. Para ello, tenemos que decirle que estamos tratando de actualizar la tabla cliente guión bajo domicilio. Luego tenemos que decirle qué valor estamos tratando de cambiar. Pero también hay que indicarle dónde estamos haciendo ese cambio específicamente para que no cambie cada dirección en la tabla. Ahí está. Ahora la dirección de este cliente fue actualizada. Si queremos crear una nueva tabla para esta base de datos, podemos usar la instrucción CREATE TABLE IF NOT EXISTS. Recuerda que el hecho de ejecutar una consulta SQL no crea realmente una tabla para los datos que extraemos. Solo los almacena en nuestra memoria local. Para guardarla, tendremos que descargarla como una hoja de cálculo o guardar el resultado en una nueva tabla. Como analista de datos, hay algunas situaciones en las que podrías necesitar hacer eso. Realmente depende de qué tipo de datos estés extrayendo y con qué frecuencia. Si solo estás usando un número total de clientes, probablemente no necesites un archivo CSV o una nueva tabla en tu base de datos. Si estás usando el número total de clientes por día para hacer algo como el seguimiento de una promoción de fin de semana en una tienda, podrías descargar esos datos como un archivo CSV para poder visualizarlo en una hoja de cálculo. Pero si se te pide que extraigas esta tendencia de forma regular, puedes crear una tabla que se actualiza automáticamente con la consulta que hayas escrito. De este modo, puedes descargar directamente los resultados cuando los necesites para un informe. Otra cosa positiva a tener en cuenta, si estás creando muchas tablas dentro de una base de datos, es que querrás usar la instrucción DROP TABLE IF EXISTS para limpiarla después. Es una buena limpieza. Es probable que no elimines tablas existentes muy a menudo. Después de todo, son los datos de la empresa, y no querrás borrar datos importantes de su base de datos. Pero puedes asegurarte de limpiar las tablas que has hecho personalmente para que no haya tablas viejas o sin usar con información redundante desordenando la base de datos. Ahí está. Ahora viste algunas de las consultas SQL más usadas en acción. Definitivamente hay más palabras clave de consulta para que puedas aprender y combinaciones únicas que te ayudarán a trabajar con las bases de datos. Pero este es un buen lugar para comenzar. Próximamente, aprenderemos aún más sobre las consultas en SQL y cómo usarlas para limpiar nuestros datos. Hasta la próxima.


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

- Opcional: Cargar el conjunto de datos del cliente en BigQuery
- Consultas SQL más utilizadas
- Divirtiéndose con SQL
- Limpieza de cadenas de variables con SQL
- Actividad práctica: Limpieza de datos usando SQL Cuestionario práctico
- Pon a prueba tus conocimientos sobre las consultas SQL

### Opcional: Cargar el conjunto de datos del cliente en BigQuery 📖

En el siguiente video, el instructor utiliza un conjunto de datos específico. Las instrucciones en esta lectura son para que puedas cargar el mismo conjunto de datos en tu consola de BigQuery. 

Debes tener una cuenta de BigQuery para seguir el curso. Si saltaste de un curso a otro, 
[El uso de BigQuery](https://www.coursera.org/learn/preparar-datos-para-la-exploracion/supplement/DYOQK/utilizar-bigquery) del curso Preparar datos para la exploración explica cómo configurar una cuenta de BigQuery.

#### Prepárate para el siguiente video

Primero, descarga el archivo CSV del archivo adjunto de abajo.

https://d3c33hcgiwev3.cloudfront.net/F0iSyYcLT9iIksmHCw_Y-Q_191f150a80d74fda96f9df2aa2e3b533_Customer-Table---Sheet1.csv?Expires=1714521600&Signature=Y6uX5WB7Jl8h7uMjQYfhq0vjGWcrogAvM2gM59xblKJb8hibpSIVcABEF8DLuNfzXA2rSdF1onebirB15D6sAEsTLhZyxGKPJTOeOKobTgVLYYjNqyjfiOXKd1aqLFDEcb2Z~ylqs7E7HsA64-odgrAE8ocI9MmgtJKtETnsgDM_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A

A continuación, completa los siguientes pasos en tu consola de BigQuery para cargar el conjunto de datos de la Tabla de Clientes.

Paso 1: Abre tu consola de BigQuery y haz clic en el proyecto al que quieres subir los datos.

Paso 2: En el Explorador de la izquierda, haz clic en el icono de Acciones (tres puntos verticales) junto al nombre de tu proyecto y selecciona Crear conjunto de datos.

Paso 3: En el próximo video, se usará el nombre "customer_data" para el conjunto de datos. Si piensas seguir el video, introduce customer_data como ID del conjunto de datos.

Paso 4: Haz clic en CREAR CONJUNTO DE DATOS (botón azul) para añadir el conjunto de datos a tu proyecto. 

Paso 5: En el Explorador de la izquierda, haz clic para expandir tu proyecto, y luego haz clic en el conjunto de datos customer_data que acabas de crear. 

Paso 6: Haz clic en el icono de acciones (tres puntos verticales) junto a customer_data y selecciona Abrir. 

Paso 7: Haz clic en el icono azul + de la parte superior derecha para abrir la ventana Crear tabla.

Paso 8: En Origen, para Crear tabla desde la selección, elige de dónde vendrán los datos. 

- Selecciona Cargar. 

- Haz clic en Examinar para seleccionar el archivo CSV de la tabla de clientes que descargaste.

- Elige CSV en el menú desplegable de formato de archivo. 

Paso 9: Si piensas seguir el video, introduce customer_address como nombre de la Tabla.

Paso 10: Para Esquema, haz clic en la casilla Detección automática.

Paso 11: Haz clic en Crear tabla (botón azul). Ahora verás la tabla customer_address bajo tu conjunto de datos customer_data en tu proyecto.

Paso 12: Haz clic en customer_address y luego selecciona la pestaña Vista previa. Confirma que ves los datos que se muestran a continuación. 

Y ahora tienes todo lo que necesitas para seguir con el siguiente video. Esta tabla también es ideal para practicar la consulta de datos por tu cuenta. Además, puedes utilizar estos pasos para cargar cualquier otro dato con el que quieras trabajar. 


### Consultas SQL más utilizadas 🎬


### Divirtiéndose con SQL 🎬


### Limpieza de cadenas de variables con SQL 🎬


### Actividad práctica: Limpieza de datos usando SQL Cuestionario práctico 📖



### Pon a prueba tus conocimientos sobre las consultas SQL 📖

1. ¿Cuál de las siguientes funciones SQL pueden usar los analistas de datos para limpiar variables de cadena? Selecciona todas las opciones que correspondan. 

   - LENGTH
    
      ❌ Incorrecto.
     
   - SUBSTR
    
      ✅ Correcto. Los analistas de datos pueden usar las funciones SUBSTR y TRIM para limpiar las variables de cadena. 

   - TRIM
    
      ✅ Correcto. Los analistas de datos pueden usar las funciones SUBSTR y TRIM para limpiar las variables de cadena. 

    - COUNTIF 
    
      ❌ Incorrecto.


2. Estás trabajando con una tabla de base de datos que contiene datos sobre listas de reproducción de diferentes tipos de medios digitales. La tabla incluye columnas para playlist_id y name. Quieres eliminar las entradas duplicadas de los nombres de las listas de reproducción y ordenar los resultados por el ID de la lista de reproducción.

Escribe la consulta SQL a continuación. Añade una cláusula DISTINCT que elimine las entradas duplicadas de la columna name.

NOTA: Los tres puntos (...) indican dónde añadir la cláusula.

```
SELECT DISTINCT name
FROM playlist
ORDER BY playlist_id;
```

```
+----------------------------+-------------+
| name                       | playlist_id |
+----------------------------+-------------+
| Music                      |           1 |
| Movies                     |           2 |
| TV Shows                   |           3 |
| Audiobooks                 |           4 |
| 90’s Music                 |           5 |
| Audiobooks                 |           6 |
| Movies                     |           7 |
| Music                      |           8 |
| Music Videos               |           9 |
| TV Shows                   |          10 |
| Brazilian Music            |          11 |
| Classical                  |          12 |
| Classical 101 - Deep Cuts  |          13 |
| Classical 101 - Next Steps |          14 |
| Classical 101 - The Basics |          15 |
| Grunge                     |          16 |
| Heavy Metal Classic        |          17 |
| On-The-Go 1                |          18 |
+----------------------------+-------------+
```

¿Qué nombre de lista de reproducción aparece en la fila 6 del resultado de la consulta? 

   - Movies (películas)
    
      ❌ Incorrecto.
     
   - TV shows (programas de TV)
    
      ❌ Incorrecto.

   - Audiobooks (audiolibros)
    
      ❌ Incorrecto.

    - Music Videos (videos musicales) 
    
      ✅ Correcto. La cláusula DISTINCT name eliminará las entradas duplicadas de la columna name. La consulta completa es SELECT DISTINCT name FROM playlist ORDER BY playlist_id. La cláusula DISTINCT elimina las entradas duplicadas del resultado de la consulta. El nombre de la lista de reproducción Videos musicales aparece en la fila 6 del resultado de la consulta. 



3. Estás trabajando con una tabla de base de datos que contiene datos sobre álbumes de música. La tabla incluye columnas para album_id, titley artist_id. Quieres comprobar si los títulos de los álbumes tienen menos de 4 caracteres.

Escribe la consulta SQL a continuación. Añade una función LENGTH que mostrará los títulos de los álbumes que tengan menos de 4 caracteres.

```
SELECT album_id, title, artist_id
FROM album
WHERE LENGTH(title) < 4;
```

```
+----------+-------+-----------+
| album_id | title | artist_id |
+----------+-------+-----------+
|      131 | IV    |        22 |
|      181 | Ten   |       118 |
|      182 | Vs.   |       118 |
|      236 | Pop   |       150 |
|      239 | War   |       150 |
+----------+-------+-----------+
```

¿Qué número de identificación del álbum aparece en la fila 3 del resultado de la consulta? 

   - 236
    
      ❌ Incorrecto.
     
   - 182
    
      ✅ Correcto. La función LENGTH(title) < 4 mostrará cualquier nombre de álbum que tenga menos de 4 caracteres. La consulta completa es SELECT * FROM album WHERE LENGTH(title) < 4. La función LENGTH cuenta el número de caracteres que contiene una cadena. El número de identificación del álbum 182 aparece en la fila 3 del resultado de la consulta. 

   - 131
    
      ❌ Incorrecto.

    - 239 
    
      ❌ Incorrecto.


4. Estás trabajando con la tabla de una base de datos que contiene datos de clientes. La tabla incluye columnas sobre la ubicación del cliente, como city, statey country. Quieres recuperar las 3 primeras letras del nombre de cada país. Decides utilizar la función SUBSTR para recuperar las 3 primeras letras del nombre de cada país y usar el comando AS para almacenar el resultado en una nueva columna llamada new_country.

Escribe la consulta SQL a continuación. Añade una instrucción a tu consulta SQL que recupere las 3 primeras letras del nombre de cada país y almacene el resultado en una nueva columna como new_country.

NOTA: Los tres puntos (...) indican dónde añadir la instrucción.

```
SELECT customer_id, SUBSTR(country, 1, 3) AS new_country
FROM customer
ORDER BY country;
```

```
+-------------+-------------+
| customer_id | new_country |
+-------------+-------------+
|          56 | Arg         |
|          55 | Aus         |
|           7 | Aus         |
|           8 | Bel         |
|           1 | Bra         |
|          10 | Bra         |
|          11 | Bra         |
|          12 | Bra         |
|          13 | Bra         |
|           3 | Can         |
|          14 | Can         |
|          15 | Can         |
|          29 | Can         |
|          30 | Can         |
|          31 | Can         |
|          32 | Can         |
|          33 | Can         |
|          57 | Chi         |
|           5 | Cze         |
|           6 | Cze         |
|           9 | Den         |
|          44 | Fin         |
|          39 | Fra         |
|          40 | Fra         |
|          41 | Fra         |
+-------------+-------------+
(Output limit exceeded, 25 of 59 total rows shown)
```

¿Qué número de identificación del cliente aparece en la fila 2 del resultado de la consulta? 

   - 28
    
      ❌ Incorrecto.
     
   - 3
    
      ❌ Incorrecto.

   - 47
    
      ❌ Incorrecto.

    - 55 
    
      ✅ Correcto. La instrucción SUBSTR(country, 1, 3) AS new_country recuperará las 3 primeras letras del nombre de cada estado y almacenará el resultado en una nueva columna como new_country. La consulta completa es SELECT customer_id, SUBSTR(country, 1, 3) AS new_country FROM customer ORDER BY country. La función SUBSTR extrae una subcadena de una cadena. Esta función indica a la base de datos que devuelva 3 caracteres de cada país, empezando por el primero. El número de identificación del cliente 55 aparece en la fila 2 del resultado de la consulta. 


---

## 3. Transformación de datos 🙋🏻‍♀️ 

### Temario: 









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
