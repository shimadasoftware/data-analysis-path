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


✅ Correcto.     
1. Un analista de datos quiere calcular la cantidad de filas que tienen un valor de SKU de “K102145”. ¿Qué función puede usar?

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.


✅ Correcto.     
2. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.

✅ Correcto.     
3. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.

✅ Correcto.     
4. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.


✅ Correcto.     
5. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.


✅ Correcto.     
6. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.

✅ Correcto.     
7. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.

✅ Correcto.     
8. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.


✅ Correcto.     
9. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.


✅ Correcto.     
10. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ❌ Incorrecto.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.
