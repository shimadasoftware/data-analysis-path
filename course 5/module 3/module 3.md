# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 3: Agregar datos para análisis

**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Como parte de tu análisis, a menudo tendrás que combinar datos para obtener información y completar objetivos de negocios. En esta parte del curso, explorarás las funciones, los procedimientos y la sintaxis involucrada en combinar, o agregar, datos. Aprenderás cómo hacerlo a partir de múltiples celdas en hojas de cálculo y múltiples tablas de bases de datos usando consultas de SQL.

## Objetivos

- Demostrar la comprensión de funciones y procedimientos que pueden usarse para combinar datos de múltiples celdas en una hoja de cálculo
- Demostrar la comprensión de funciones y sintaxis para crear consultas de SQL a fin de combinar datos de varias tablas de bases de datos
- Usar VLOOKUP para consultar datos, recortar datos, convertir datos de texto en datos numéricos y crear una tabla de resumen a partir de la información consultada


---

## 1. VLOOKUP para agregación de datos 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tu conocimiento sobre VLOOKUP

### Cuestionario: Pon a prueba tu conocimiento sobre VLOOKUP 📖



1. Para cambiar una cadena de texto en la celda F8 de una hoja de cálculo a un valor numérico, ¿cuál es la función correcta? 

   - =NUM(F8)
    
      ❌ Incorrecto.

   - =MATCH(F8)
    
      ❌ Incorrecto.

   - =CONVERT(F8)
    
      ❌ Incorrecto.

   - =VALUE(F8)
    
      ✅ Correcto. Para cambiar una cadena de texto en la celda F8 de una hoja de cálculo a un valor numérico, la sintaxis correcta es =VALUE(F8). Dentro del paréntesis, la sintaxis VALUE debe incluir una referencia a la celda específica cuyo valor la función debería convertir.


2. ¿Cuál es la finalidad de una referencia absoluta dentro de una función como "$C$3"?

   - Eliminar instrucciones innecesarias de una fórmula o función
    
      ❌ Incorrecto.

   - Representar valores faltantes en una fórmula o función
    
      ❌ Incorrecto.

   - Que las fórmulas y funciones sean incondicionales
    
      ❌ Incorrecto.

   - Bloquear filas y columnas para que no cambien cuando se copie una función
    
      ✅ Correcto. La finalidad de una referencia absoluta es bloquear la referencia a una fila o columna para que los valores no cambien cuando se copie una función. 


3. En VLOOKUP, TRUE le indica a la función que busque coincidencias exactas y FALSE le dice a la función que busque coincidencias aproximadas.

   - Verdadero
    
      ❌ Incorrecto.

   - Falso
    
      ✅ Correcto. En VLOOKUP, TRUE le indica a la función que busque coincidencias aproximadas y FALSE le dice a la función que busque coincidencias exactas.


4. La siguiente es una selección de una hoja de cálculo:

![image](./img/module%2001%20img%2001.png)

Para buscar la población de Nigeria, ¿cuál es la sintaxis correcta de VLOOKUP?

   - =VLOOKUP("Nigeria", A2:C10, 2, false)
    
      ✅ Correcto. Para buscar la población de Nigeria, la sintaxis es =VLOOKUP("Nigeria", A2:C10, 2, falso). “Nigeria” es la referencia. A2:C10 es la matriz de la tabla. El 2 indica la posición de la columna de la que debe devolverse el valor. Y la palabra false le indica a la función que devuelva una coincidencia exacta.

   - =VLOOKUP(Nigeria, A2:C10, 3, true)
    
      ❌ Incorrecto.

   - =VLOOKUP(Nigeria, A2,C10, 2, true)
    
      ❌ Incorrecto.

   - =VLOOKUP(Nigeria, A2:C10, 3, false)
    
      ❌ Incorrecto.


5. La siguiente es una selección de una hoja de cálculo:

![image](./img/module%2001%20img%2002.png)

Para buscar la altura de la construcción en La Meca, ¿cuál es la sintaxis correcta de VLOOKUP?

   - =VLOOKUP(Mecca, A2:D7, 2, true)
    
      ❌ Incorrecto.

   - =VLOOKUP(Mecca, A2:D7, 2, false)
    
      ❌ Incorrecto.

   - =VLOOKUP("Mecca", A2:D7, 3, false)
    
      ✅ Correcto. Para buscar la altura de la construcción en La Meca, la sintaxis correcta es =VLOOKUP("Mecca", A2:D7, 3, false). “Mecca” es la referencia. A2:D7 es la matriz de la tabla. El 3 indica el número de la columna de la que debe devolverse el valor. Y la palabra false le indica a la función que devuelva una coincidencia exacta.
     
   - =VLOOKUP(Mecca, A2,D7, 3, true)
    
      ❌ Incorrecto.
     

---

## 2. Usa JOINS para agregar datos en SQL 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre el uso de JOINS para agregar datos

### Cuestionario: Pon a prueba tus conocimientos sobre el uso de JOINS para agregar datos 📖

1. Un analista de datos quiere recuperar solo registros de una base de datos que tengan valores coincidentes en dos tablas diferentes. ¿Qué función JOIN debe usar?

   - LEFT JOIN
    
      ❌ Incorrecto.

   - RIGHT JOIN
    
      ❌ Incorrecto.

   - INNER JOIN
    
      ✅ Correcto. Para recuperar solo registros de una base de datos que tengan valores coincidentes en dos tablas diferentes, el analista debería usar INNER JOIN. 

   - OUTER JOIN
    
      ❌ Incorrecto.


2. Estás escribiendo una consulta SQL para instruirle a una base de datos que recuente valores en un rango especificado. Solo quieres recontar cada valor una vez, aunque aparezca en múltiples ocasiones. ¿Qué función deberías incluir en tu consulta?

   - COUNT
    
      ❌ Incorrecto.

   - COUNT DISTINCT
    
      ✅ Correcto. Para decirle a una base de datos que devuelva valores distintos en un rango especificado, el analista debería usar COUNT DISTINCT en su consulta.

   - COUNT VALUES
    
      ❌ Incorrecto.

   - COUNT RANGE
    
      ❌ Incorrecto.


3. Un analista de datos quiere nombrar temporalmente una columna en su consulta para que sea más fácil de leer y escribir. ¿Qué técnica debería usar?

   - Asignación de alias
    
      ✅ Correcto. Para nombrar temporalmente una columna en una consulta para que sea más fácil de leer y escribir, el analista debería usar asignación de alias.

   - Filtrado
    
      ❌ Incorrecto.

   - Etiquetado
    
      ❌ Incorrecto.

   - Nomenclatura
    
      ❌ Incorrecto.


---

## 3. Funcionan con subconsultas 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre cómo trabajar con subconsultas

### Cuestionario: Pon a prueba tus conocimientos sobre cómo trabajar con subconsultas 📖


1. ¿Cuáles de las siguientes consultas contienen subconsultas? Selecciona todas las opciones que correspondan.

   - ```
      SELECT price
      FROM sales
      WHERE price = (SELECT MAX(salary) FROM sales)
     ```
    
      ✅ Correcto. Las tres consultas con instrucciones entre paréntesis contienen subconsultas.

   - ```
      SELECT call
      FROM recordings
      ORDER BY call.employee_id, call.start_time
     ```
    
      ❌ Incorrecto.

   - ```
      SELECT employee_id
      FROM employees
      WHERE department_id IN (SELECT department_id
        FROM departments
        WHERE location_id = 1900)
     ```
    
      ✅ Correcto. Las tres consultas con instrucciones entre paréntesis contienen subconsultas.

   - ```
      SELECT first_name, last_name
      FROM customers
      WHERE customer_id NOT IN (SELECT customer_id FROM customers WHERE store = 704)
     ```
    
      ✅ Correcto. Las tres consultas con instrucciones entre paréntesis contienen subconsultas.


2. Completa el espacio en blanco: Un analista de datos usa la asignación de alias para que sea más fácil leer y escribir una consulta. La asignación de alias implica _____ temporalmente una tabla o columna en una consulta.

   - eliminar
    
      ❌ Incorrecto.

   - nombrar
    
      ✅ Correcto. La asignación de alias implica nombrar temporalmente una tabla o columna en una consulta.

   - copiar
    
      ❌ Incorrecto.

   - ocultar
    
      ❌ Incorrecto.


3. Al trabajar con subconsultas, la consulta exterior se ejecuta primero.

   - Verdadero
    
      ❌ Incorrecto.

   - Falso
    
      ✅ Correcto. La consulta interior se ejecuta primero, luego los resultados se pasan a la consulta exterior para su uso. 


---

## 4. Desafio semanal 3 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre cómo convertir y formatear datos

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos

### Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos 📖


1. En el análisis computacional de datos, ¿qué es la agregación de datos?

   - El proceso de recolectar datos de múltiples fuentes y combinarlos en una sola colección resumida.
    
      ✅ Correcto. La agregación de datos es el proceso de recolectar datos de múltiples fuentes y combinarlos en una sola colección resumida.

   - El proceso de mover determinados puntos de datos a un rango o posición superior.
    
      ❌ Incorrecto.

   - El proceso de garantizar que los datos de una empresa se almacenen, gestionen y mantengan de manera correcta. 
    
      ❌ Incorrecto.

   - El proceso de modificar datos para que sean adecuados para el análisis.
    
      ❌ Incorrecto.


2. Un analista de datos quiere asegurarse de que todos los números en una hoja de cálculo sean numéricos. ¿Qué función debería usar para convertir el texto en valores numéricos? 

   - VALUE
    
      ✅ Correcto. El analista debería usar la función VALUE para convertir texto en valores numéricos.

   - EXCHANGE
    
      ❌ Incorrecto.

   - CONVERT
    
      ❌ Incorrecto.

   - PROCESS
    
      ❌ Incorrecto.


3. Al usar VLOOKUP, existen algunas limitaciones comunes que los analistas de datos deberían conocer. Identifica estas limitaciones. Selecciona todas las opciones que correspondan.

   - VLOOKUP solo devuelve la primera coincidencia que encuentra, aun si existen muchas coincidencias posibles.
    
      ✅ Correcto. Una de las limitaciones de VLOOKUP es que solo devuelve la primera coincidencia que encuentra, aun si existen muchas coincidencias posibles. Otra es que solo puede devolver un valor de los datos que están a la derecha de la columna del valor coincidente.

   - VLOOKUP solo puede devolver un valor de los datos que están a la izquierda de la columna en la que se escribe.
    
      ❌ Incorrecto.

   - VLOOKUP solo puede devolver un valor de los datos que están a la derecha de la columna del valor coincidente.
    
      ✅ Correcto. Una de las limitaciones de VLOOKUP es que solo devuelve la primera coincidencia que encuentra, aun si existen muchas coincidencias posibles. Otra es que solo puede devolver un valor de los datos que están a la derecha de la columna del valor coincidente.

   - VLOOKUP solo devuelve coincidencias que encuentra mientras busca en una fila.
    
      ❌ Incorrecto.


4. Completa el espacio en blanco: Al escribir una función, un analista de datos encapsula una matriz de tabla entre signos de dólar. Esta es una _____ , que se usa para bloquear una matriz para que las filas y columnas no cambien si se copia la función. 

   - referencia auténtica
    
      ❌ Incorrecto.

   - referencia exacta
    
      ❌ Incorrecto.

   - referencia absoluta
    
      ✅ Correcto. Encapsular una matriz de tabla entre signos de dólar crea una referencia absoluta, que bloquea la matriz de modo tal que las filas y columnas no cambien si se copia la función. 

   - referencia arbitraria 
    
      ❌ Incorrecto.

    
5. La siguiente es una selección de una hoja de cálculo:

![image](./img/module%2001%20img%2003.png)

Para buscar la población de Paquistán, ¿cuál es la sintaxis correcta de VLOOKUP? 

   - =VLOOKUP(Pakistan, A2:B10, 3, false)
    
      ❌ Incorrecto.

   - =VLOOKUP("Pakistan", A2:B10, 2, false)
    
      ✅ Correcto. Para buscar la población de Paquistán, la sintaxis es =VLOOKUP("Pakistan", A2:B10, 2, falso). “Pakistan” es la referencia. A2:B10 es la matriz de la tabla. El 2 indica el número de la columna de la que debe devolverse el valor. Y la palabra false le indica a la función que devuelva una coincidencia exacta.

   - =VLOOKUP("Pakistan", A2:B10, 3, false)
    
      ❌ Incorrecto.

   - =VLOOKUP(Pakistan, A2*B10, 2, false)
    
      ❌ Incorrecto.

    
6. Al crear una consulta de SQL, ¿qué cláusula JOIN devuelve solo registros con valores coincidentes en dos o más tablas de bases de datos?

   - OUTER
    
      ❌ Incorrecto.

   - LEFT
    
      ❌ Incorrecto.

   - RIGHT
    
      ❌ Incorrecto.

   - INNER
    
      ✅ Correcto. La cláusula INNER JOIN devuelve solo registros con valores coincidentes en dos o más tablas de bases de datos.

    
7. Un analista de datos escribe una consulta solicitando a una base de datos que devuelva el número de filas en un rango especificado. ¿Qué función usa?

   - RANGE
    
      ❌ Incorrecto.

   - COUNT 
    
      ✅ Correcto. Al escribir consultas SQL, un analista puede usar la función COUNT para devolver el número de filas en un rango especificado.

   - RETURN RANGE
    
      ❌ Incorrecto.

   - COUNT DISTINCT
    
      ❌ Incorrecto.

   
8. Completa el espacio en blanco: En una instrucción de SQL, la _____ es el nombre del segmento que se ejecuta primero. Selecciona todas las opciones que correspondan.

   - selección interna
    
      ✅ Correcto. En una instrucción SQL, la subconsulta — también llamada consulta interna, selección interna o consulta anidada — es el segmento que se ejecuta primero. 

   - consulta central
    
      ❌ Incorrecto.

   - selección central
    
      ❌ Incorrecto.

   - consulta interna 
    
      ✅ Correcto. En una instrucción SQL, la subconsulta — también llamada consulta interna, selección interna o consulta anidada — es el segmento que se ejecuta primero. 



     
