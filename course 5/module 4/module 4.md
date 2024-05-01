# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 4: Realizar cálculos de datos

**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Los cálculos son una de las tareas más comunes que realizan los analistas de datos durante el análisis. En esta parte del curso, explorarás fórmulas, funciones y tablas dinámicas en hojas de cálculo y consultas en SQL. Todo esto te ayudará a realizar los cálculos que necesites. También aprenderás sobre los beneficios de utilizar SQL para gestionar las tablas temporales.

## Objetivos

- Describir el uso de funciones para realizar cálculos básicos con datos en hojas de cálculo
- Analizar el uso de tablas dinámicas para realizar cálculos con datos en hojas de cálculos
- Demostrar que entiendes cómo utilizar las consultas de SQL para completar los cálculos
- Explicar la importancia del proceso de validación de datos para garantizar la precisión y coherencia en el análisis
- Analizar el uso de las consultas de SQL para gestionar las tablas temporales
- Reflexionar sobre cómo se pueden utilizar las instrucciones condicionales para crear consultas y funciones complejas
- Crear varios puntos de resumen basados en una amplia variedad de condiciones mediante COUNTIF, SUMIF, MAXIF y AVERAGEIF

---

## 6. Desafío semanal 4 🙋🏻‍♀️ 

### Temario: 

- Desafío semanal 4

### Cuestionario: Desafío semanal 4 📖

    
1. Un analista de datos quiere calcular la cantidad de filas que tienen un valor de SKU de “K102145”. ¿Qué función puede usar?

   - =COUNTIF(G2:G30,K102145)
    
      ❌ Incorrecto.

   - =COUNTIF(G2:G30,“=K102145”)
    
      ❌ Incorrecto. Resuesta incorrecta.

   - =COUNTIF(K102145=G2:G30)
    
      ❌ Incorrecto.

   - =COUNTIF(G2:G30,“K102145”)
    
      ✅ Correcto. 

 
2. Estás trabajando en una hoja de cálculo y usas la función SUMIF en la siguiente fórmula como parte de tu análisis. 

```
=SUMIF(D2:D10,”>=50”,E2:E10)
```

¿Qué parte de esta fórmula indica el rango de valores que se deben sumar? 

   - E2:E10
    
      ✅ Correcto. 

   - >=50
    
      ❌ Incorrecto.

   - D2:D10
    
      ❌ Incorrecto. Respuesta incorrecta.   

   - =SUMIF 
    
      ❌ Incorrecto.

    
3. ¿Qué parte de una tabla dinámica cambiarías si quieres usar un cálculo diferente para combinar los resultados?

   - Valores
    
      ✅ Correcto. 

   - Filas
    
      ❌ Incorrecto.

   - Filtro
    
      ❌ Incorrecto.

   - Columnas
    
      ❌ Incorrecto.

   
4. ¿Cuál columna está configurada como un valor en la siguiente tabla dinámica?

![image](./img/module%2001%20img%2001.png)

+-----------------+-------------+------------+
| MAX de duración | Dirección   |            |
+-----------------+-------------+------------+
| Fecha           | Disminución | Aumento    | 
+-----------------+-------------+------------+
| 2/1             |             | 200        |
| 2/3             | 300         | 100        |
| 2/4             | 100         | 100        |
| 2/5             | 450         |            |
+-----------------+-------------+------------+

   - Duración
    
      ✅ Correcto. 

   - MAX
    
      ❌ Incorrecto. No es la respuesta correcta.

   - Dirección
    
      ❌ Incorrecto.

   - Fecha
    
      ❌ Incorrecto.

    
5. ¿Qué finalidad tiene la función EXTRACT de SQL?

   - Mostrar la parte específica de una fecha
    
      ✅ Correcto. 

   - Mostrar un par clave-valor específico de un objeto JSON
    
      ❌ Incorrecto.

   - Calcular la operación de extracción matemática
    
      ❌ Incorrecto.

   - Calcular con datos extraídos de otras tablas
    
      ❌ Incorrecto.

   
6. Cuando se escriben cálculos personalizados en SQL, ¿qué caracteres se pueden usar para agrupar cálculos que permitan cambiar su orden?

   - Llaves, {}
    
      ❌ Incorrecto.

   - Corchetes, []
    
      ❌ Incorrecto.

   - Paréntesis, ()
    
      ✅ Correcto.  

   - Comillas, “”
    
      ❌ Incorrecto.

    
7. ¿Cuál es el propósito de usar la validación de datos durante el proceso de análisis?

   - Garantizar que puedas usar todos los datos de tus datos sin procesar
    
      ❌ Incorrecto.

   - Garantizar que todos los datos estén completos y sean precisos, seguros y coherentes
    
      ✅ Correcto.

   - Garantizar que las visualizaciones sean atractivas a la vista
    
      ❌ Incorrecto.

   - Garantizar que todas las partes interesadas estén conformes con sus resultados
    
      ❌ Incorrecto.

   
8. Un analista de datos intenta calcular de nuevo y manualmente una columna de su conjunto de datos. Su intención es encontrar filas en las que los valores de la columna no coincidan con los de la columna original. ¿Cuál de las siguientes cláusulas de SQL podría usar?

   - WHERE original_column NOT EQUALS recalcualted_column
    
      ❌ Incorrecto.

   - WHERE original_column !! recalcualted_column
    
      ❌ Incorrecto.

   - WHERE original_column <> recalcualted_column
    
      ✅ Correcto.

   - WHERE original_column ~= recalcualted_column
    
      ❌ Incorrecto.

  
9. ¿Cuál es el motivo para usar una cláusula WITH AS en una instrucción de SQL?

   - El resultado es una visualización
    
      ❌ Incorrecto.

   - El resultado es temporal
    
      ✅ Correcto.

   - El resultado es una tabla dinámica
    
      ❌ Incorrecto.

   - El resultado se calcula más rápido
    
      ❌ Incorrecto.

    
10. ¿Cuál de las siguientes instrucciones de SQL se puede usar para crear tablas temporales en SQL?

   - WITH my_table FROM (SELECT * FROM other_table);
    
      ❌ Incorrecto.

   - WITH my_table AS (SELECT * FROM other_table WHERE x = 0);
    
      ✅ Correcto.

   - SELECT * FROM table;
    
      ❌ Incorrecto.

   - CREATE TABLE my_table AS (SELECT * FROM other_table);
    
      ❌ Incorrecto. No es la respuesta correcta.


11. Estás trabajando en una hoja de cálculo y usas la función SUMIF en la siguiente fórmula como parte de tu análisis. 

```
=SUMIF(A1:A25,”<10”,C1:C25)
```

¿Qué parte de ella corresponde a los criterios o la condición? 

   - ”<10”
    
      ✅ Correcto. 

   - SUMIF
    
      ❌ Incorrecto.

   - C1:C25
    
      ❌ Incorrecto.

   - A1:A25
    
      ❌ Incorrecto.


12. Creaste una tabla dinámica y quieres sumar el total de todas las celdas por cada valor de fila y columna en la tabla. ¿Qué función del menú de valores usarías para resumir los datos?

   - PRODUCT
    
      ❌ Incorrecto.

   - AVERAGE
    
      ❌ Incorrecto.

   - COUNTA
    
      ❌ Incorrecto.

   - SUM
    
      ✅ Correcto.


13. ¿Qué valores de fecha y dirección se usan para calcular el valor 450 en la siguiente tabla dinámica?

+------+---------+-------------+---------+
| N/A  | N/A     | Dirección   |         |
+------+---------+-------------+---------+
| Fecha| Valores | Disminución | Aumento |
+------+---------+-------------+---------+
| 2/3  | MAX de A|        300  |     100 |
|      | MIN de C|         12  |       1 |
| 2/4  | MAX de A|        100  |     100 |
|      | MIN de C|         14  |      19 |
| 2/5  | MAX de A|        450  |         |
|      | MIN de C|          9  |         |
+------+---------+-------------+---------+


   - 2/4 y Aumento
    
      ❌ Incorrecto.

   - 2/3 y Disminución
    
      ❌ Incorrecto. Respuesta falsa.

   - 2/5 y Disminución
    
      ❌ Incorrecto.

 
8. Un analista de datos encuentra algunos datos que parecen incoherentes. ¿Qué es lo primero que debería hacer?

   - Quitar los valores incoherentes
    
      ❌ Incorrecto.

   - Convertir los valores incoherentes en JSON
    
      ❌ Incorrecto.

   - Determinar si los valores incoherentes son válidos
    
      ✅ Correcto.

   - Sustituir los valores incoherentes por otros de relleno
    
      ❌ Incorrecto.


9. ¿Cuál de las siguientes afirmaciones sobre tablas temporales es correcta?

   - Se deben crear usando la cláusula WITH AS de SQL.
    
      ❌ Incorrecto.

   - Se declaran ubicando una sentencia FROM entre ##.
    
      ❌ Incorrecto.

   - Son una función especial de BigQuery que no está disponible en otros RDBMS.
    
      ❌ Incorrecto.

   - Se borran automáticamente cuando finaliza la sesión de la base de datos SQL.
    
      ✅ Correcto.




---

## 6. Desafío semanal 4 🙋🏻‍♀️ 

### Temario: 

- Desafío semanal 4

### Cuestionario: Desafío semanal 4 📖

El cliente te ha pedido que envíes dos listas de correo por separado: uno a personas dentro de las 50 millas de Rock Springs; la otra a cualquier persona fuera de esa área. Por lo tanto, para investigar la distancia de cada donante desde la ciudad, primero tienes que descubrir dónde viven estas personas.

Podrías desplazarte por las 209 filas de datos, pero sabes que existe una forma más eficiente de organizar las ciudades. 

¿Cuál de las siguientes funciones te permitirá ordenar tu hoja de cálculo por ciudad (columna K) en orden ascendente?
   
1. Un analista de datos quiere calcular la cantidad de filas que tienen un valor de SKU de “K102145”. ¿Qué función puede usar?

   - =SORT(A2:R210, K, ASC)
    
      ❌ Incorrecto.

   - =SORT(A2:R210, 11, ASC)
    
      ❌ Incorrecto.

   - =SORT(A2:R210, 11, TRUE)
    
      ✅ Correcto. Para ordenar tu hoja de cálculo por ciudad en orden ascendente, usa la sintaxis de la función SORT =SORT(A2:R210, 11, TRUE). También puedes seleccionar A2-R210 y luego usar el menú desplegable para ordenar la hoja por la columna K de la A a la Z. 

   - =SORT(A2:R210, K, TRUE)
    
      ❌ Incorrecto.


Escenario 1, continuación
    
2. Observas que a muchas celdas en la columna ciudad, columna K, les falta un valor. Por lo tanto, usas los códigos postales para investigar las ciudades correctas. Ahora, deseas agregar las ciudades a la fila de cada donante. Sin embargo, te preocupa cometer un error, por ejemplo, un error ortográfico.

¿Qué herramienta de la hoja de cálculo puedes usar para agregar una lista desplegable con opciones predeterminadas para cada nombre de ciudad?

   - VLOOKUP
    
      ❌ Incorrecto.

   - Validación de datos
    
      ✅ Correcto. Usas la validación de datos para agregar listas desplegables con opciones predeterminadas para cada nombre de ciudad. Esto te permite controlar lo que puedes y no puedes escribir en tu hoja de cálculo.

   - Lista
    
      ❌ Incorrecto.

   - Buscar
    
      ❌ Incorrecto.


Escenario 1, continuación
  
3. Ahora, decides abordar la solicitud de Tayen de incluir una nota manuscrita en la pieza de publicidad por correo directo para todos los que hayan aportado como mínimo USD 100 el último año. 

¿Cuál de las siguientes herramientas de la hoja de cálculo te permitirá cambiar la forma en que aparecen las celdas si contienen un valor de USD 100 o más?

   - La función COUNTA
    
      ❌ Incorrecto.

   - Formato condicional
    
      ✅ Correcto. Para cambiar la forma en que aparecen las celdas, usa el formato condicional. Elegir dar formato a las celdas si su valor es mayor que o igual a 100.   

   - La función MAX
    
      ❌ Incorrecto.

   - Validación de datos
    
      ❌ Incorrecto.
    

4. En este punto, observas que la información sobre estado y código postal está en la misma celda. Sin embargo, el software de la lista de direcciones de correos electrónicos de la empresa exige que los estados estén en una línea separada de los códigos postales. 

¿Qué función te permitirá mover la abreviatura del estado de 2 dígitos de la celda L2 a una columna propia? 

   - =LEFT(L2,2)
    
      ❌ Incorrecto.

   - =RIGHT(2,L2)
    
      ✅ Correcto. Podría ser.

   - =RIGHT(L2,2)
    
      ❌ Incorrecto. No es la respuesta

   - =LEFT(2,L2)
    
      ❌ Incorrecto.

   
5. Luego, duplicas tu conjunto de datos dos veces usando el menú Hoja de cálculo. Cambias el nombre de la primera hoja Donation Form List y eliminas las ciudades que están a una distancia de más de 50 millas de Rock Springs. Cambias el nombre de la segunda hoja Postcard List y eliminas las ciudades que están dentro de las 50 millas de Rock Springs.

Luego, importas estos conjuntos de datos a tu base de datos con la lista de direcciones de correos electrónicos de la empresa. En una base de datos con la lista de direcciones de correos electrónicos, creas dos tablas: Donation_Form_List y Postcard_List. Decides limpiar Donation_Form_List primero. 

El software que se usa para la lista de direcciones de correos electrónicos de la empresa requiere que las unidades estén en la misma línea que las direcciones. Sin embargo, actualmente están en dos columnas separadas (street_address y unit). 

¿Qué función de SQL indicará a la base de datos que combine dos columnas en una columna nueva llamada “address”?

   - COMBINE
    
      ❌ Incorrecto.

   - CONCAT
    
      ✅ Correcto. La función CONCAT se usa para indicar a la base de datos que combine dos columnas en una columna nueva llamada “address”.

   - COALESCE
    
      ❌ Incorrecto.

   - CAST
    
      ❌ Incorrecto.
     

6. Tu base de datos contiene personas que viven en muchas áreas de Wyoming. Sin embargo, es importante que alinees tus datos internos con los datos de Food Justice Rock Springs. También debes separar tus datos en dos listas: Donation_Form_List y Postcard_List. Se basarán en la distancia de cada ciudad de Rock Springs.

¿Qué función de SQL usas para seleccionar todos los datos de Donation_Form_List organizados por código postal?

   - ARRANGE BY
    
      ❌ Incorrecto.

   - SEQUENCE
    
      ❌ Incorrecto.

   - ORDER BY
    
      ✅ Correcto. Para seleccionar todos los datos de Donation_Form_List organizados por código postal, usas la función ORDER BY. La función ORDER BY ordena los resultados devueltos en una consulta. 

   - ORGANIZE
    
      ❌ Incorrecto.

    
7. Finalizas la limpieza de tus conjuntos de datos, así que decides revisar el correo electrónico de Tayen una vez más para asegurarte de que completaste la tarea íntegramente. Es bueno que hayas verificado porque olvidaste identificar a personas que se desempeñaron como miembros del directorio o el consejo directivo. Tayen desea escribirles y enviarles una nota de agradecimiento; por lo tanto, necesitas ubicarlos en la base de datos.

Para recuperar solo esos registros que incluyen personas que se han desempeñado como miembros del directorio o del consejo directivo, ¿cuál es la consulta correcta?

   - SELECT * FROM Donation_Form_List WHERE Board_Member = TRUE AND Trustee = TRUE
    
      ❌ Incorrecto.

   - SELECT * FROM Donation_Form_List WHERE Board_Member = TRUE, Trustee = TRUE
    
      ❌ Incorrecto.

   - SELECT * FROM Donation_Form_List WHERE Board_Member = "TRUE" AND Trustee = "TRUE"
    
      ❌ Incorrecto.

   - SELECT * FROM Donation_Form_List WHERE Board_Member = "TRUE" OR Trustee = "TRUE"
    
      ✅ Correcto.  

   
8. Tu campaña de correos directos de la empresa fue muy exitosa, y Food Justice Rock Springs continuó asociándose con Directly Dynamic. Algo en que has estado trabajando es la asignación de números de identificación a todos los donantes. Esto te permitirá limpiar y organizar las listas de manera más efectiva.

Mientras tanto, otro miembro del equipo ha estado creando una lista de potenciales donantes que contiene datos sobre personas que demostraron interés en involucrarse con Food Justice Rock Springs. A estas personas también se les asigna un ID único. Ahora, tienes que comparar la lista de donantes con el conjunto de datos en tu base de datos y recolectar determinados datos de ambos.

¿Qué función de SQL combinará RIGHT y LEFT JOIN para devolver todos los registros coincidentes en ambas tablas?

   - RIGHT JOIN
    
      ❌ Incorrecto.

   - LEFT JOIN
    
      ❌ Incorrecto.

   - OUTER JOIN
    
      ✅ Correcto. La función OUTER JOIN combinará RIGHT y LEFT JOIN para devolver todos los registros coincidentes en ambas tablas.  

   - INNER JOIN 
    
      ❌ Incorrecto.

  
9. Tu próxima tarea es identificar la contribución promedio hecha por los donantes durante los últimos dos años. Tayen usará esta información para establecer una donación mínima para invitar a los donantes al próximo evento.

Comienzas con 2019. Para obtener las contribuciones promedio en 2019 (contributions_2019), usas la función AVG. ¿Qué parte de tu instrucción en SQL indicará a la base de datos que debe encontrar este promedio y guardarlo en la variable AvgLineTotal?

   - AVG(“contributions_2019”) IN AvgLineTotal
    
      ❌ Incorrecto.

   - AVG(“contributions_2019”) AS AvgLineTotal
    
      ❌ Incorrecto.

   - AVG(contributions_2019) AS AvgLineTotal
    
      ✅ Correcto. Para obtener las contribuciones promedio en 2019, la parte correcta de la consulta SQL es: AVG(contributions_2019) AS AvgLineTotal  

   - AVG(contributions_2019) = “AvgLineTotal”
    
      ❌ Incorrecto.

    
10. Ahora que le proporcionaste el monto de la donación promedio, Tayen decide invitar a 50 personas a la gran apertura de un nuevo jardín comunitario. Vuelves a tu hoja de cálculo New Donor List para determinar cuánto aportó cada donante en los últimos dos años. Usarás esa información para identificar a los 50 donantes más importantes e invitarlos al evento. 

¿Cuál es la sintaxis correcta para sumar los montos de las contribuciones en las celdas O2 y P2?

   - =SUM(O2/P2)
    
      ❌ Incorrecto.

   - =SUM(O2*P2)
    
      ❌ Incorrecto.

   - =SUM(O2,P2)
    
      ✅ Correcto. Para sumar las celdas O2 y P2, usa la función =SUM(O2,P2). También puedes usar la fórmula =O2+P2.

   - =SUM(“O2,P2”)
    
      ❌ Incorrecto.


11. Tayen informa que también está pensando en invitar a todos los que hayan donado como mínimo USD 100 en 2018. Sin embargo, solo tiene cinco espacios abiertos. Te pide que informes cuántas personas aportaron como mínimo USD 100 para que pueda determinar si también las puede invitar al evento.

La sintaxis correcta para contar cuántas donaciones de USD 100 o más aparecen en la columna O es =SUMIF(O2:O210,">=100").

   - Verdadero
    
      ❌ Incorrecto.

   - Falso
    
      ✅ Correcto. Para contar cuántas donaciones de USD 100 o más aparecen en la columna O, la sintaxis correcta es =COUNTIF(O2:O210,">=100").

    
12. La gran apertura del jardín comunitario fue un éxito. Además de los 55 donantes que Food Justice Rock Springs invitó, otros 20 potenciales donantes asistieron al evento. Ahora, Tayen desea saber más sobre las donaciones realizadas por los potenciales nuevos donantes en comparación con las de los donantes originales.

¿Cuál es la sección de una consulta en SQL que calculará el porcentaje de contribuciones de los potenciales donantes?

   - (Total_prospects + Total_donors = 100) AS Prospects_Percent
    
      ❌ Incorrecto.

   - (Total_prospects * Total_donors / 100) AS Prospects_Percent
    
      ❌ Incorrecto.

   - (“Total_prospects” , “Total_donors” * 100) AS Prospects_Percent
    
      ❌ Incorrecto.

   - (Total_prospects / Total_donors * 100) AS Prospects_Percent
    
      ✅ Correcto. Para identificar el porcentaje de contribuciones de los potenciales donantes, la consulta correcta es: (Total_prospects / Total_donors * 100) AS Prospects_Percent


13. Tu equipo crea una lista de potenciales donantes altamente efectiva para Food Justice Rock Springs. Después de unos meses, muchos de estos potenciales donantes se convierten en donantes. Ahora, Tayen desea saber las tres ciudades más importantes donde viven estos nuevos donantes. Usará esa información para determinar si aún es verdad que existe una mayor probabilidad de que las personas que viven más cerca de Rock Springs donen.

¿Qué cláusula agregas a la siguiente consulta para ordenar los donantes en cada ciudad de mayor a menor?

```
SELECT COUNT(DonorID), City
FROM new_donor_list
GROUP BY City
```

   - ORDER BY CITY(DonorID) DESC
    
      ❌ Incorrecto.

   - ORDER BY COUNT(DonorID) ASC
    
      ❌ Incorrecto.

   - ORDER BY COUNT(DonorID) DESC
    
      ✅ Correcto.

   - ORDER BY CITY(DonorID) ASC
    
      ❌ Incorrecto.
