# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 2: Organizar los datos para iniciar el análisis

**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Organizar los datos facilita el uso de los datos en tu análisis. En esta parte del curso, aprenderás la importancia de organizar tus datos a través de ordenación y filtrado. Explorarás estos procesos tanto en hojas de cálculo como en SQL a medida que prepares tus datos para el análisis.

## Objetivos

- Describir qué implica el proceso de análisis de datos en lo que respecta a los objetivos y las tareas claves
- Debatir sobre la importancia de organizar los datos antes de llevar a cabo el análisis en lo que respecta a las ordenaciones y los filtros
- Describir la ordenación en relación con los datos en una hoja de cálculo o base de datos en lo que respecta a la funcionalidad y los beneficios
- Demostrar la comprensión de los pasos involucrados en la ordenación y el filtrado de datos mediante el uso de consultas en SQL

Este primer modulo se divide en:

1. Organicémonos
2. Conceptos básicos del análisis de datos
3. Organizar los datos para el análisis
4. Ordenar datos en hojas de cálculo
5. Ordenar datos usando SQL
6. Desafio semanal 1

---

## 1. Organicémonos 🙋🏻‍♀️ 

### Temario: 


---

## 2. Conceptos básicos del análisis de datos 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos

### Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos 📖

1. Les preguntas a los voluntarios en una producción teatral qué tareas ya completaron y agregas esos datos a una hoja de cálculo que contenga todas las tareas requeridas. Usarás la información proporcionada por los voluntarios para darte cuenta de qué tareas falta realizar. ¿Este es un ejemplo de qué fase de análisis?

   - Formatear y ajustar los datos 
    
      ❌ Incorrecto.

   - Obtener comentarios de los demás 
    
      ✅ Correcto. Este es un ejemplo de obtención de comentarios de los demás. Obtener comentarios significa solicitar información a través de otras fuentes para fundamentar tus decisiones. Organizar los datos implica obtener los datos que necesitas para el análisis; en la hoja de cálculo ya se recopiló el conjunto de datos de las tareas requeridas.

   - Organizar los datos (en un conjunto de datos)
    
      ❌ Incorrecto.

   - Transformar los datos  
    
      ❌ Incorrecto.


2. Estás trabajando con tres conjuntos de datos sobre la participación electoral en tu país. Primero, identificas las relaciones y los patrones existentes entre los conjuntos de datos. Luego, usas fórmulas y funciones para hacer los cálculos en función de tus datos. ¿Este es un ejemplo de qué fase de análisis?

   - Formatear y ajustar los datos 
    
      ❌ Incorrecto.

   - Transformar los datos
    
      ✅ Correcto. Este es un ejemplo de transformación de datos que implica identificar relaciones y patrones existentes entre los conjuntos de datos, y realizar cálculos.

   - Organizar los datos (en un conjunto de datos)
    
      ❌ Incorrecto.

   - Obtener comentarios de los demás   
    
      ❌ Incorrecto.


3. Estás trabajando con un conjunto de datos de una institución pública de educación terciaria. Ordenas a los alumnos alfabéticamente por apellido. ¿Este es un ejemplo de qué fase de análisis?

   - Transformar los datos 
    
      ❌ Incorrecto.

   - Organizar los datos (en un conjunto de datos)
    
      ❌ Incorrecto. 

   - Formatear y ajustar los datos
    
      ✅ Correcto. Ordenar una lista de alumnos alfabéticamente es un ejemplo de formatear y ajustar datos. Organizar los datos es un paso que usan los analistas para recopilar los datos que necesitan para el análisis. 

   - Obtener comentarios de los demás   
    
      ❌ Incorrecto.



---

## 3. Organizar los datos para el análisis 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la organización de datos

### Cuestionario: Pon a prueba tus conocimientos sobre la organización de datos 📖


1. Completa el espacio en blanco: El analista de datos usa _____ para decidir qué datos son relevantes para su análisis y qué tipos de datos y variables son apropiados.

   - normalización de base de datos
    
      ❌ Incorrecto.

   - organización de base de datos
    
      ✅ Correcto. La organización de la base de datos permite a los analistas tomar decisiones sobre qué datos son relevantes para un análisis específico. También los ayuda a decidir qué tipos de datos y variables son apropiados.

   - relaciones de base de datos
    
      ❌ Incorrecto.

   - referencias de base de datos
    
      ❌ Incorrecto.


2. Un analista de datos quiere organizar una base de datos para que muestre solo las 100 ventas inmobiliarias más recientes en Stamford, Connecticut. ¿Cómo puede hacer eso?

   - El analista de datos debería agregar un filtro que muestre solo las ventas en Stamford, Connecticut, luego ordenar las ventas menos recientes en la parte superior de la lista.
    
      ❌ Incorrecto.

   - El analista de datos debería filtrar las ventas en Stamford, Connecticut, luego ordenar las ventas menos recientes en la parte superior de su lista.
    
      ❌ Incorrecto.

   - El analista de datos debería filtrar las ventas en Stamford, Connecticut, luego ordenar las ventas más recientes en la parte superior de su lista.
    
      ✅ Correcto. El analista de datos debería agregar un filtro solo para las ventas en Stamford, Connecticut, luego ordenar las ventas más recientes en la parte superior de su lista.

   - El analista de datos debería excluir las ventas en Stamford, Connecticut, luego ordenar las ventas más recientes en la parte superior de su lista.
    
      ❌ Incorrecto.


3. Estás trabajando con la tabla de una base de datos que contiene datos del cliente. La columna país designa el país en el cual está ubicado el cliente. Deseas averiguar qué clientes se encuentran en Brasil. 

Escribe la consulta SQL a continuación. Agrega una cláusula WHERE que mostrará resultados solo de clientes que se encuentren en Brasil. 

```
SELECT *
FROM customer
WHERE country = "Brazil";
```

```
+-------------+------------+-----------+--------------------------------------------------+---------------------------------+---------------------+-------+---------+-------------+--------------------+--------------------+-------------------------------+----------------+
| customer_id | first_name | last_name | company                                          | address                         | city                | state | country | postal_code | phone              | fax                | email                         | support_rep_id |
+-------------+------------+-----------+--------------------------------------------------+---------------------------------+---------------------+-------+---------+-------------+--------------------+--------------------+-------------------------------+----------------+
|           1 | Luís       | Gonçalves | Embraer - Empresa Brasileira de Aeronáutica S.A. | Av. Brigadeiro Faria Lima, 2170 | São José dos Campos | SP    | Brazil  | 12227-000   | +55 (12) 3923-5555 | +55 (12) 3923-5566 | luisg@embraer.com.br          |              3 |
|          10 | Eduardo    | Martins   | Woodstock Discos                                 | Rua Dr. Falcão Filho, 155       | São Paulo           | SP    | Brazil  | 01007-010   | +55 (11) 3033-5446 | +55 (11) 3033-4564 | eduardo@woodstock.com.br      |              4 |
|          11 | Alexandre  | Rocha     | Banco do Brasil S.A.                             | Av. Paulista, 2022              | São Paulo           | SP    | Brazil  | 01310-200   | +55 (11) 3055-3278 | +55 (11) 3055-8131 | alero@uol.com.br              |              5 |
|          12 | Roberto    | Almeida   | Riotur                                           | Praça Pio X, 119                | Rio de Janeiro      | RJ    | Brazil  | 20040-020   | +55 (21) 2271-7000 | +55 (21) 2271-7070 | roberto.almeida@riotur.gov.br |              3 |
|          13 | Fernanda   | Ramos     | None                                             | Qe 7 Bloco G                    | Brasília            | DF    | Brazil  | 71020-677   | +55 (61) 3363-5547 | +55 (61) 3363-7855 | fernadaramos4@uol.com.br      |              4 |
+-------------+------------+-----------+--------------------------------------------------+---------------------------------+---------------------+-------+---------+-------------+--------------------+--------------------+-------------------------------+----------------+
```

¿Cuántos clientes se encuentran en Brasil? 

   - 3
    
      ❌ Incorrecto.

   - 5
    
      ✅ Correcto. La cláusula WHERE country = “Brazil” mostrará los resultados solo de los clientes que se encuentran en Brasil. La consulta completa es SELECT * FROM customer WHERE country = “Brazil”. La cláusula WHERE filtra los resultados que cumplen con ciertas condiciones. La cláusula WHERE incluye el nombre de la columna, un signo de igual y el valor o los valores para incluir en la columna. 

Hay cinco clientes que se encuentran en Brasil. 

   - 9
    
      ❌ Incorrecto.

   - 7
    
      ❌ Incorrecto.


---

## 4. Ordenar datos en hojas de cálculo 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos

### Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos 📖

1. ¿Qué función del menú de la hoja de cálculo se usa para ordenar todos los datos en una hoja de cálculo mediante la clasificación de una columna ordenada específica?

   - Ordenar por categoría
    
      ❌ Incorrecto.

   - Ordenar hoja 
    
      ✅ Correcto. Se usa Ordenar hoja para ordenar todos los datos en una hoja de cálculo mediante la clasificación de una columna ordenada específica.

   - Ordenar datos
    
      ❌ Incorrecto.

   - Rango de ordenación 
    
      ❌ Incorrecto.


2. En las hojas de cálculo, los analistas de datos pueden ordenar un rango en la pestaña Datos del menú o escribir una función directamente en una celda vacía.

   - Verdadero
    
      ✅ Correcto. La ordenación de un rango y la ordenación de una hoja pueden hacerse desde el menú y escribirse como una función. Los analistas pueden trabajar desde la pestaña Datos del menú o escribir directamente una función en una celda vacía.

   - Falso
    
      ❌ Incorrecto.


3. Un analista usa =SORT para ordenar datos de la hoja de cálculo en orden descendente. ¿Qué escribe al final de la función ordenar?

   - TRUE
    
      ❌ Incorrecto.

   - FALSE
    
      ✅ Correcto. Para ordenar una hoja de cálculo en orden descendente con la función SORT, el analista escribe FALSE al final de su función ordenar. 

   - DESCEND
    
      ❌ Incorrecto.

   - Z-A
    
      ❌ Incorrecto.



---

## 5. Ordenar datos usando SQL 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos

### Cuestionario: Pon a prueba tus conocimientos sobre ordenación en SQL 📖



1. Un analista de datos quiere ordenar una lista de arbustos de invernadero por precio, desde los más económicos hasta los más costosos. ¿Qué instrucción debería usar?

   - ORDER BY shrub_price 
    
      ✅ Correcto. Para ordenar una lista de arbustos de invernadero por precio, desde los más económicos hasta los más costosos, debe usar ORDER BY shrub_price.

   - WHERE shrub_price ASC
    
      ❌ Incorrecto.

   - ORDER BY shrub_price DESC
    
      ❌ Incorrecto.

   - WHERE shrub_price
    
      ❌ Incorrecto.


2. Estás trabajando con una tabla de base de datos que contiene datos sobre géneros musicales. Quieres ordenar los géneros por nombre, en orden ascendente. Los géneros se enumeran en la columna genre_name. 

Escribe la consulta SQL a continuación. Agrega una cláusula ORDER BY que ordenará los géneros por nombre, en orden ascendente. 

```
SELECT *
FROM genre
ORDER BY genre_name ASC;
```

```
+----------+--------------------+
| genre_id | genre_name         |
+----------+--------------------+
|       23 | Alternative        |
|        4 | Alternative & Punk |
|        6 | Blues              |
|       11 | Bossa Nova         |
|       24 | Classical          |
|       22 | Comedy             |
|       21 | Drama              |
|       12 | Easy Listening     |
|       15 | Electronica/Dance  |
|       13 | Heavy Metal        |
|       17 | Hip Hop/Rap        |
|        2 | Jazz               |
|        7 | Latin              |
|        3 | Metal              |
|       25 | Opera              |
|        9 | Pop                |
|       14 | R&B/Soul           |
|        8 | Reggae             |
|        1 | Rock               |
|        5 | Rock And Roll      |
|       20 | Sci Fi & Fantasy   |
|       18 | Science Fiction    |
|       10 | Soundtrack         |
|       19 | TV Shows           |
|       16 | World              |
+----------+--------------------+
```

¿Qué género aparece en la fila 3 del resultado de la consulta? 

   - Música ligera 
    
      ❌ Incorrecto.

   - Alternativa
    
      ❌ Incorrecto.

   - Clásica
    
      ❌ Incorrecto.

   - Blues
    
      ✅ Correcto. La cláusula ORDER BY genre_name ordenará los géneros por nombre, en orden ascendente. La consulta completa es SELECT * FROM genre ORDER BY genre_name. La cláusula ORDER BY le indica a la base de datos cómo organizar los datos que muestra. La cláusula ORDER BY ordena por defecto los datos en forma ascendente. Aparece el género Blues en la fila 3 del resultado de la consulta. 


3. Estás trabajando con una tabla de base de datos que contiene datos de empleados. Quieres ordenar a los empleados por fecha de contratación, en orden descendente. Las fechas de contratación se enumeran en la columna hire_date. 

Escribe la consulta SQL a continuación. Agrega una cláusula ORDER BY que ordenará a los empleados por fecha de 

```
SELECT *
FROM employee
ORDER BY hire_date DESC;
```

```
+-------------+-----------+------------+---------------------+------------+---------------------+---------------------+-----------------------------+------------+-------+---------+-------------+-------------------+-------------------+--------------------------+
| employee_id | last_name | first_name | title               | reports_to | birth_date          | hire_date           | address                     | city       | state | country | postal_code | phone             | fax               | email                    |
+-------------+-----------+------------+---------------------+------------+---------------------+---------------------+-----------------------------+------------+-------+---------+-------------+-------------------+-------------------+--------------------------+
|           8 | Callahan  | Laura      | IT Staff            |          6 | 1968-01-09 00:00:00 | 2004-03-04 00:00:00 | 923 7 ST NW                 | Lethbridge | AB    | Canada  | T1H 1Y8     | +1 (403) 467-3351 | +1 (403) 467-8772 | laura@chinookcorp.com    |
|           7 | King      | Robert     | IT Staff            |          6 | 1970-05-29 00:00:00 | 2004-01-02 00:00:00 | 590 Columbia Boulevard West | Lethbridge | AB    | Canada  | T1K 5N8     | +1 (403) 456-9986 | +1 (403) 456-8485 | robert@chinookcorp.com   |
|           5 | Johnson   | Steve      | Sales Support Agent |          2 | 1965-03-03 00:00:00 | 2003-10-17 00:00:00 | 7727B 41 Ave                | Calgary    | AB    | Canada  | T3B 1Y7     | 1 (780) 836-9987  | 1 (780) 836-9543  | steve@chinookcorp.com    |
|           6 | Mitchell  | Michael    | IT Manager          |          1 | 1973-07-01 00:00:00 | 2003-10-17 00:00:00 | 5827 Bowness Road NW        | Calgary    | AB    | Canada  | T3B 0C5     | +1 (403) 246-9887 | +1 (403) 246-9899 | michael@chinookcorp.com  |
|           4 | Park      | Margaret   | Sales Support Agent |          2 | 1947-09-19 00:00:00 | 2003-05-03 00:00:00 | 683 10 Street SW            | Calgary    | AB    | Canada  | T2P 5G3     | +1 (403) 263-4423 | +1 (403) 263-4289 | margaret@chinookcorp.com |
|           1 | Adams     | Andrew     | General Manager     |       None | 1962-02-18 00:00:00 | 2002-08-14 00:00:00 | 11120 Jasper Ave NW         | Edmonton   | AB    | Canada  | T5K 2N1     | +1 (780) 428-9482 | +1 (780) 428-3457 | andrew@chinookcorp.com   |
|           2 | Edwards   | Nancy      | Sales Manager       |          1 | 1958-12-08 00:00:00 | 2002-05-01 00:00:00 | 825 8 Ave SW                | Calgary    | AB    | Canada  | T2P 2T3     | +1 (403) 262-3443 | +1 (403) 262-3322 | nancy@chinookcorp.com    |
|           3 | Peacock   | Jane       | Sales Support Agent |          2 | 1973-08-29 00:00:00 | 2002-04-01 00:00:00 | 1111 6 Ave SW               | Calgary    | AB    | Canada  | T2P 5M5     | +1 (403) 262-3443 | +1 (403) 262-6712 | jane@chinookcorp.com     |
+-------------+-----------+------------+---------------------+------------+---------------------+---------------------+-----------------------------+------------+-------+---------+-------------+-------------------+-------------------+--------------------------+
```

¿Qué empleado aparece en la fila 1 del resultado de la consulta?

   - Nancy Edwards
    
      ❌ Incorrecto.

   - Laura Callahan
    
      ✅ Correcto. La cláusula ORDER BY hire_date DESC ordenará a los empleados por fecha de contratación, en orden descendente. La consulta completa es SELECT * FROM employee ORDER BY hire_date DESC. La cláusula ORDER BY le indica a la base de datos cómo organizar los datos que muestra. La cláusula ORDER BY ordena por defecto los datos en forma ascendente. Se usa el comando DESC para ordenar los datos en orden descendente. La empleada Laura Callahan aparece en la fila 1 del resultado de la consulta. 

   - Margaret Park
    
      ❌ Incorrecto.

   - Robert King
    
      ❌ Incorrecto.


---

## 6. Desafio semanal 1 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos

### Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos 📖


1. En el proceso de análisis de datos, ¿cuál de las siguientes opciones se refiere a una fase de análisis? Selecciona todas las opciones que correspondan.

   - Obtener comentarios de los demás
    
      ✅ Correcto. Hay cuatro fases de análisis: organizar los datos, formatear y ajustar los datos, obtener comentarios de los demás y transformar los datos mediante la observación de las relaciones existentes entre los puntos de datos y hacer cálculos. 

   - Formatear los datos mediante ordenaciones y filtros
    
      ✅ Correcto. Hay cuatro fases de análisis: organizar los datos, formatear y ajustar los datos, obtener comentarios de los demás y transformar los datos mediante la observación de las relaciones existentes entre los puntos de datos y hacer cálculos. 

   - Organizar los datos en secciones comprensibles
    
      ✅ Correcto. Hay cuatro fases de análisis: organizar los datos, formatear y ajustar los datos, obtener comentarios de los demás y transformar los datos mediante la observación de las relaciones existentes entre los puntos de datos y hacer cálculos. 

   - Visualizar los datos
    
      ❌ Incorrecto.


2. ¿Durante cuál de las cuatro fases de análisis puedes encontrar una correlación entre dos variables?

   - Organizar los datos 
    
      ❌ Incorrecto.

   - Obtener comentarios de los demás
    
      ❌ Incorrecto.

   - Transformar los datos
    
      ✅ Correcto.

   - Formatear y ajustar los datos
    
      ❌ Incorrecto.


3. Estás realizando un cálculo durante el análisis de un conjunto de datos. ¿En qué fase de análisis estás? 

   - Organizar los datos
    
      ❌ Incorrecto.

   - Obtener comentarios de los demás
    
      ❌ Incorrecto.

   - Transformar los datos
    
      ✅ Correcto. Estás en la fase de análisis abocada a la transformación de los datos. Este es un ejemplo de identificación de relaciones y patrones entre los datos.

   - Formatear y ajustar los datos
    
      ❌ Incorrecto.


4. El analista de datos suele usar filtros cuando quiere ampliar la cantidad de datos con los que trabaja.

   - Verdadero
    
      ❌ Incorrecto.

   - Falso
    
      ✅ Correcto. El analista de datos suele usar filtros cuando quiere reducir la cantidad de datos con los que trabaja.


5. Un analista de datos está ordenando datos en una hoja de cálculo. ¿Qué herramienta está usando si todos los datos están ordenados por la clasificación de una columna ordenada específica y los datos de las filas se mantienen juntos? 

   - Ordenar categoría
    
      ❌ Incorrecto.

   - Ordenar hoja
    
      ✅ Correcto. Ordenar la hoja ordena todos los datos en una hoja de cálculo mediante la clasificación de una columna ordenada específica. Además, los datos de las filas se mantienen juntos durante la ordenación.

   - Ordenar juntos
    
      ❌ Incorrecto.

   - Ordenar documento
    
      ❌ Incorrecto.


6. Un analista de datos ordena el rango de una hoja de cálculo entre las celdas F19 y G82. Ordena en orden ascendente por la segunda columna, la Columna G. ¿Cuál es la sintaxis que usa?

   - =SORT(F19:G82, B, TRUE)
    
      ❌ Incorrecto.

   - =SORT(F19:G82, 2, FALSE)
    
      ❌ Incorrecto.

   - =SORT(F19:G82, B, FALSE)
    
      ❌ Incorrecto.

   - =SORT(F19:G82, 2, TRUE)
    
      ✅ Correcto. La sintaxis correcta es =SORT(F19:G82, 2, TRUE). La primera parte de la función ordena los datos en el rango especificado. El 2 representa la segunda columna. Y la instrucción TRUE ordena en orden ascendente.


7. Estás haciendo una consulta en una base de datos que contiene datos sobre música. Cada álbum tiene asignado un número de ID. A ti solo te interesan los datos relacionados con el álbum con el número de ID 6. Los números de ID de álbum se enumeran en la columna album_id. 

Escribe la consulta SQL a continuación. Agrega una cláusula WHERE que te mostrará solo los datos sobre el álbum con número de ID 6.

```
SELECT COUNT(*)
FROM track
WHERE album_id = 6;
```

```
SELECT *
FROM track
WHERE album_id = 6;
```

```
+----------+-----------------------------+----------+---------------+----------+-----------------------------------+--------------+----------+------------+
| track_id | name                        | album_id | media_type_id | genre_id | composer                          | milliseconds |    bytes | unit_price |
+----------+-----------------------------+----------+---------------+----------+-----------------------------------+--------------+----------+------------+
|       38 | All I Really Want           |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       284891 |  9375567 |       0.99 |
|       39 | You Oughta Know             |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       249234 |  8196916 |       0.99 |
|       40 | Perfect                     |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       188133 |  6145404 |       0.99 |
|       41 | Hand In My Pocket           |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       221570 |  7224246 |       0.99 |
|       42 | Right Through You           |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       176117 |  5793082 |       0.99 |
|       43 | Forgiven                    |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       300355 |  9753256 |       0.99 |
|       44 | You Learn                   |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       239699 |  7824837 |       0.99 |
|       45 | Head Over Feet              |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       267493 |  8758008 |       0.99 |
|       46 | Mary Jane                   |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       280607 |  9163588 |       0.99 |
|       47 | Ironic                      |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       229825 |  7598866 |       0.99 |
|       48 | Not The Doctor              |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       227631 |  7604601 |       0.99 |
|       49 | Wake Up                     |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       293485 |  9703359 |       0.99 |
|       50 | You Oughta Know (Alternate) |        6 |             1 |        1 | Alanis Morissette & Glenn Ballard |       491885 | 16008629 |       0.99 |
+----------+-----------------------------+----------+---------------+----------+-----------------------------------+--------------+----------+------------+

+----------+
| COUNT(*) |
+----------+
|       13 |
+----------+

```

¿Cuántas canciones hay en el álbum con el número de ID 6?

   - 13
    
      ✅ Correcto. La cláusula WHERE genre_id = 6mostrará solo datos sobre el álbum con el número de ID 6. La consulta completa es SELECT * FROM track WHERE album_ID = 6. La cláusula WHERE filtra los resultados que cumplen con ciertas condiciones. La cláusula WHERE incluye el nombre de la columna, un signo de igual y el valor o los valores para incluir en la columna. Hay 13 canciones en el álbum con el número de ID 6.

   - 8
    
      ❌ Incorrecto.

   - 5
    
      ❌ Incorrecto.

   - 20
    
      ❌ Incorrecto.


8. Estás trabajando con una base de datos que contiene datos de facturas sobre compras de música en línea. A ti solo te interesan las facturas enviadas a clientes ubicados en la ciudad de Delhi. Quieres ordenar las facturas por total de pedido, en orden ascendente. Los totales de los pedidos se enumeran en la columna total. 

Escribe la consulta SQL a continuación. Agrega una cláusula ORDER BYque ordenará las facturas por total de pedido, en orden ascendente.

```
SELECT *
FROM invoice
WHERE billing_city = "Delhi"
ORDER BY total ASC;
```

```
+------------+-------------+---------------------+---------------------+--------------+---------------+-----------------+---------------------+-------+
| invoice_id | customer_id | invoice_date        | billing_address     | billing_city | billing_state | billing_country | billing_postal_code | total |
+------------+-------------+---------------------+---------------------+--------------+---------------+-----------------+---------------------+-------+
|        120 |          58 | 2010-06-12 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              |  1.98 |
|        315 |          58 | 2012-10-27 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              |  1.98 |
|        412 |          58 | 2013-12-22 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              |  1.99 |
|        338 |          58 | 2013-01-29 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              |  3.96 |
|        360 |          58 | 2013-05-03 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              |  5.94 |
|        186 |          58 | 2011-03-23 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              |  8.91 |
|        131 |          58 | 2010-07-23 00:00:00 | 12,Community Centre | Delhi        |          None | India           | 110017              | 13.86 |
+------------+-------------+---------------------+---------------------+--------------+---------------+-----------------+---------------------+-------+
```

¿Qué total aparece en la fila 4 del resultado de la consulta?

   - 8.91
    
      ❌ Incorrecto.

   - 3.96
    
      ✅ Correcto. La cláusula ORDER BY total ordenará las facturas por total de pedido, en orden ascendente. La consulta completa es SELECT * FROM invoice WHERE billing_city = "Delhi" ORDER BY total. La cláusula ORDER BY le indica a la base de datos cómo organizar los datos que muestra. La cláusula ORDER BY ordena por defecto los datos en forma ascendente. El total 3.96 aparece en la fila 4 del resultado de la consulta.

   - 5.94
    
      ❌ Incorrecto.

   - 1.98
    
      ❌ Incorrecto.


9. ¿Qué fase del proceso de análisis de datos tiene el objetivo de identificar tendencias y relaciones?

   - Preparar
    
      ❌ Incorrecto.

   - Actuar
    
      ❌ Incorrecto.

   - Procesar
    
      ❌ Incorrecto.

   - Analizar
    
      ✅ Correcto. El objetivo del análisis es identificar tendencias y relaciones en esos datos para que puedas responder con precisión la pregunta que te haces. 


10. ¿Durante cuál de las cuatro fases del análisis comparas tus datos con fuentes externas?

   - Organizar los datos 
    
      ❌ Incorrecto.

   - Obtener comentarios de los demás
    
      ✅ Correcto. La comparación de tus datos con fuentes externas se produce mientras obtienes los comentarios de los demás.

   - Transformar los datos
    
      ❌ Incorrecto.

   - Formatear y ajustar los datos
    
      ❌ Incorrecto.


11. Un analista de datos está trabajando en un conjunto de datos e inicia la fase de análisis abocada a la transformación de los datos. ¿Cuáles son algunas de las acciones que ejecutará? Selecciona todas las opciones que correspondan.

   - Ordenar datos
    
      ❌ Incorrecto.

   - Realizar cálculos con los datos
    
      ✅ Correcto. En la fase de transformación de datos del análisis, el analista de datos identifica relaciones y patrones entre los datos. Esto incluye encontrar correlaciones y realizar cálculos en los datos.

   - Filtrar datos
    
      ❌ Incorrecto.

   - Encontrar una correlación en los datos
    
      ✅ Correcto. En la fase de transformación de datos del análisis, el analista de datos identifica relaciones y patrones entre los datos. Esto incluye encontrar correlaciones y realizar cálculos en los datos.


12. Completa el espacio en blanco: Filtrar implica mostrar solo los datos que cumplen con un _____ específico mientras se oculta el resto.

   - modelar
    
      ❌ Incorrecto.

   - criterio
    
      ✅ Correcto. Filtrar implica mostrar solo los datos que cumplen con un criterio específico mientras se oculta el resto.

   - observación
    
      ❌ Incorrecto.

   - medida
    
      ❌ Incorrecto.


13. Un analista de datos está ordenando datos en una hoja de cálculo. Selecciona un conjunto de celdas específico para limitar la ordenación exclusivamente a las celdas especificadas. ¿Qué herramienta de hoja de cálculo está usando?

   - Ordenar hoja
    
      ❌ Incorrecto.

   - Limitar ordenación 
    
      ❌ Incorrecto.

   - Limitar rango
    
      ❌ Incorrecto.

   - Rango de ordenación
    
      ✅ Correcto. Feedback: Rango de ordenación permite que el analista de datos seleccione un conjunto de celdas específico para limitar la ordenación exclusivamente a ese rango. No se reorganiza ningún otro dato en la hoja de cálculo además de las celdas especificadas.
     

14. Un analista de datos ordena el rango de una hoja de cálculo entre las celdas D5 y M5. Ordena en orden descendente por la tercera columna, la Columna F. ¿Cuál es la sintaxis que usa?

   - =SORT(D5:M5, C, FALSE)
    
      ❌ Incorrecto.

   - =SORT(D5:M5, 3, TRUE)
    
      ❌ Incorrecto.

   - =SORT(D5:M5, C, TRUE)
    
      ❌ Incorrecto.

   - = SORT(D5:M5, 3, FALSE)
    
      ✅ Correcto. La sintaxis correcta es =SORT(D5:M5, 3, FALSE). La primera parte de la función ordena los datos en el rango especificado. El 3 representa la tercera columna. Y la instrucción FALSE ordena en orden descendente.


15. Estás trabajando con una base de datos que contiene datos de facturas sobre compras de música en línea. A ti solo te interesan las facturas enviadas a clientes ubicados en la ciudad de Chicago. Quieres ordenar las facturas por total de pedido, en orden ascendente. Los totales de los pedidos se enumeran en la columna total. 

Escribe la consulta SQL a continuación. Agrega una cláusula ORDER BYque ordenará las facturas por total de pedido, en orden ascendente.

```
SELECT *
FROM invoice
WHERE billing_city = "Chicago"
ORDER BY total ASC;
```

```
+------------+-------------+---------------------+-----------------------+--------------+---------------+-----------------+---------------------+-------+
| invoice_id | customer_id | invoice_date        | billing_address       | billing_city | billing_state | billing_country | billing_postal_code | total |
+------------+-------------+---------------------+-----------------------+--------------+---------------+-----------------+---------------------+-------+
|        384 |          24 | 2013-08-20 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               |  0.99 |
|         92 |          24 | 2010-02-08 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               |  1.98 |
|        287 |          24 | 2012-06-25 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               |  1.98 |
|        332 |          24 | 2012-12-30 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               |  5.94 |
|        310 |          24 | 2012-09-27 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               |  7.96 |
|        158 |          24 | 2010-11-19 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               |  8.91 |
|        103 |          24 | 2010-03-21 00:00:00 | 162 E Superior Street | Chicago      | IL            | USA             | 60611               | 15.86 |
+------------+-------------+---------------------+-----------------------+--------------+---------------+-----------------+---------------------+-------+
```

¿Qué total aparece en la fila 4 del resultado de la consulta?

   - 8.91
    
      ❌ Incorrecto.

   - 3.96
    
      ❌ Incorrecto.

   - 5.94
    
      ❌ Incorrecto.

   - 1.98
    
      ✅ Correcto. La cláusula ORDER BY total ordenará las facturas por total de pedido, en orden ascendente. La consulta completa es SELECT * FROM invoice WHERE billing_city = "Chicago" ORDER BY total. La cláusula ORDER BY le indica a la base de datos cómo organizar los datos que muestra. La cláusula ORDER BY ordena por defecto los datos en forma ascendente. El total 1.98 aparece en la fila 2 del resultado de la consulta.
     
