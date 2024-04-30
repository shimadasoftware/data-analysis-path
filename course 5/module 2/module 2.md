# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 2: Formatear y ajustar datos

**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

A medida que te acerques al análisis de tus datos, querrás tener los datos formateados y listos para avanzar. En esta parte del curso, aprenderás sobre la conversión y el formateo de los datos, incluso cómo las consultas en SQL pueden ayudarte a combinar datos. También descubrirás el valor de la retroalimentación y la colaboración de tus colegas y cómo puede conducir a nuevos aprendizajes para que apliques a tu trabajo.

## Objetivos

- Demostrar comprensión de lo que implica la conversión y el formateo de datos
- Demostrar comprensión de cómo se usan las consultas en hojas de cálculo y en SQL para combinar distintos tipos de datos
- Debatir acerca de lo importante que es obtener comentarios y apoyo de terceros

---

## 1. Convertir y formatear datos 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre cómo convertir y formatear datos

### Cuestionario: Pon a prueba tus conocimientos sobre cómo convertir y formatear datos 📖


1. Una celda de la hoja de cálculo contiene la temperatura más baja que se registró alguna vez en Nueva Zelanda: -22 °C. ¿Qué función mostraría esa temperatura en grados Fahrenheit? 

   - =CONVERT(-22, C, F)
    
      ❌ Incorrecto.

   - =CONVERT(-22, F, C)
    
      ❌ Incorrecto.

   - =CONVERT(-22, "F", "C")
    
      ❌ Incorrecto.

   - =CONVERT(-22, "C", "F")
    
      ✅ Correcto. =CONVERT(-22, "C", "F") mostrará -22 °C en grados Fahrenheit.


2. Un analista de datos quiere estar seguro de que las fórmulas de la hoja de cálculo seguirán funcionando correctamente aunque alguien escriba un dato incorrecto por error. ¿Qué opción de validación de datos debería seleccionar del menú para marcar errores en el ingreso de datos?

   - Eliminar validación
    
      ❌ Incorrecto.

   - Denegar texto de ayuda
    
      ❌ Incorrecto.

   - Rechazar entradas inválidas
    
      ✅ Correcto. Para garantizar que las fórmulas de la hoja de cálculo sigan funcionando correctamente aunque alguien escriba un dato incorrecto por error, selecciona Rechazar entradas inválidas para marcar esos datos como inválidos.

   - Prohibir entradas
    
      ❌ Incorrecto.


3. Un analista de datos abre el menú desplegable y hace clic en la opción Formato de celdas. Luego, selecciona El texto es exactamente noviembre. Así, se modifica el color de todas las celdas que contengan la palabra noviembre. ¿Qué herramienta de la hoja de cálculo está usando el analista?

   - Validación de datos
    
      ❌ Incorrecto.

   - CONVERT
    
      ❌ Incorrecto.

   - Filtrado
    
      ❌ Incorrecto.

   - Formato condicional
    
      ✅ Correcto. El analista de datos está usando el formato condicional. El formato condicional es una herramienta de la hoja de cálculo que cambia la forma en que se ven las celdas cuando los valores cumplen con condiciones específicas.


---

## 2. Combatir distintos conjuntos de datos 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre combinar distintos conjuntos de datos

### Cuestionario: Pon a prueba tus conocimientos sobre combinar distintos conjuntos de datoss 📖



1. Completa el espacio en blanco: En SQL, se usa _____ para combinar cadenas de texto de distintas tablas y, así, crear una nueva cadena.

   - CONCAT
    
      ✅ Correcto. En SQL, se usa CONCAT para combinar cadenas de texto de distintas tablas y, así, crear una nueva cadena.

   - CONCATENATE
    
      ❌ Incorrecto.

   - COMBINE
    
      ❌ Incorrecto.

   - CONNECT
    
      ❌ Incorrecto.


2. CEstás trabajando con una tabla de base de datos que contiene datos sobre listas de reproducción de diferentes tipos de medios digitales. Solo te interesan las primeras 4 listas de reproducción. Escribe la consulta SQL a continuación. Agrega una cláusula LIMIT para que solo puedas ver las primeras 4 listas de reproducción. 

```
SELECT *
FROM playlist
LIMIT 4;
```

```
+-------------+------------+
| playlist_id | name       |
+-------------+------------+
|           1 | Music      |
|           2 | Movies     |
|           3 | TV Shows   |
|           4 | Audiobooks |
+-------------+------------+
```

¿Qué lista de reproducción aparece en la fila 2 del resultado de la consulta?

   - Música
    
      ❌ Incorrecto.

   - Películas
    
      ✅ Correcto. La cláusula LIMIT 4 te permitirá ver solo las primeras 4 listas de reproducción. La consulta completa es SELECT * FROM playlist LIMIT4. La cláusula LIMIT te permite establecer un límite en la cantidad de filas que te muestra tu consulta. La lista de reproducción Películas aparece en la fila 2 del resultado de la consulta.

   - Programas de TV
    
      ❌ Incorrecto.

   - Audiolibros
    
      ❌ Incorrecto.


3. ¿Qué función puedes usar para ver el número de caracteres en la celda B8 de modo que puedas confirmar que contiene exactamente 20 caracteres?

   - =LEN(B8, 20)
    
      ❌ Incorrecto.

   - =LEN(20)
    
      ❌ Incorrecto.

   - =LEN(20, B8)
    
      ❌ Incorrecto.

   - =LEN(B8)
    
      ✅ Correcto. La función =LEN(B8) te mostrará el número de caracteres en la celda B8. La función LEN devuelve la longitud de una cadena de texto al contar el número de caracteres que contiene.


---

## 3. Obtener ayuda durante el análisis 🙋🏻‍♀️ 



---

## 6. Desafio semanal 2 🙋🏻‍♀️ 

### Temario: 

- Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos

### Cuestionario: Pon a prueba tus conocimientos sobre la comprensión del análisis de datos 📖


1. Un analista que trabaja para un sistema educativo británico acaba de descargar un conjunto de datos que se generó en los Estados Unidos. Los datos numéricos son correctos, pero tienen el formato de dólares estadounidenses y el analista necesita que estén en libras esterlinas. ¿Qué herramienta de la hoja de cálculo podría ayudarlo a seleccionar el formato correcto?

   - CURRENCY
    
      ❌ Incorrecto.

   - Formato de libra
    
      ❌ Incorrecto.

   - Formato de moneda
    
      ✅ Correcto. Puedes usar la herramienta Formato de moneda para seleccionar el formato correcto según la moneda.

   - EXCHANGE
    
      ❌ Incorrecto.


2. Estás preparando una hoja de cálculo para realizar el seguimiento de un proyecto. Al lado de cada tarea del proyecto, tienes que agregar el nombre del miembro del equipo que estará a cargo. Para ahorrar tiempo, ¿qué herramienta de la hoja de cálculo te permitiría crear una lista desplegable con los nombres de los miembros del equipo?

   - Menús emergentes
    
      ❌ Incorrecto.

   - Formato condicional
    
      ❌ Incorrecto.

   - Buscar
    
      ❌ Incorrecto.

   - Validación de datos
    
      ✅ Correcto. Puedes usar la validación de datos para agregar listas desplegables con opciones predeterminadas para los nombres de los miembros del equipo.


3. Un analista de datos de recursos humanos está usando una hoja de cálculo para realizar un seguimiento del aniversario de trabajo de los empleados. Agrega color a la celda de los empleados que hayan trabajado en la empresa durante 10 años o más. ¿Qué herramienta de la hoja de cálculo usa para cambiar el formato de las celdas cuando el valor es igual a 10 o superior?

   - CONVERT 
    
      ❌ Incorrecto.

   - Formato condicional
    
      ✅ Correcto. El formato condicional cambia la forma en que se ven las celdas cuando los valores cumplen con condiciones específicas, como tener un valor igual a 10 o superior.

   - Añadir color
    
      ❌ Incorrecto.

   - Validación de datos
    
      ❌ Incorrecto.


4. Estás analizando datos sobre las capitales de distintos países. En tu base de datos de SQL, tienes una columna con los nombres de los países y otra con las capitales. ¿Qué función podrías usar en tu consulta para combinar los países y las capitales en una nueva columna?

   - CONCAT
    
      ✅ Correcto. Podrías usar la función CONCAT, que te permite unir distintas cadenas de texto de fuentes diferentes. 

   - GROUP
    
      ❌ Incorrecto.

   - COMBINE
    
      ❌ Incorrecto.

   - JOIN
    
      ❌ Incorrecto.


5. Estás consultando una base de datos sobre sabores de helado para ver qué tiendas venden la mayor cantidad de menta granizada. Para tu proyecto, solo necesitas los primeros 80 registros. ¿Qué cláusula deberías agregar a la siguiente consulta de SQL?

```
SELECT flavors
FROM ice_cream_table
WHERE flavor = "mint_chip"
```

   - LIMIT,80
    
      ❌ Incorrecto.

   - LIMIT_80
    
      ❌ Incorrecto.

   - LIMIT 80
    
      ✅ Correcto. Para obtener resultados de los primeros 80 registros, escribe LIMIT 80.

   - LIMIT = 80
    
      ❌ Incorrecto.


6. Completa el espacio en blanco: Un analista de datos está trabajando con una hoja de cálculo que tiene cadenas de texto muy largas. Usa la función LEN para contar la cantidad de _____ en las cadenas de texto.

   - valores
    
      ❌ Incorrecto.

   - campos
    
      ❌ Incorrecto.

   - caracteres
    
      ✅ Correcto. Usa la función LEN para contar la cantidad de caracteres en las cadenas de texto.

   - subcadenas
    
      ❌ Incorrecto.


7. La celda L6 de la hoja de cálculo contiene la cadena de texto “Función”. Para que devuelva la subcadena “Fun”, ¿cuál sería la sintaxis correcta?

   - =LEFT(L6, 3)
    
      ✅ Correcto. La función =LEFT(L6, 3) mostrará como resultado “Fun”. La función LEFT devuelve un número establecido de caracteres a la izquierda de una cadena de texto. En este caso, muestra una subcadena de tres caracteres desde el final de la cadena de texto en la celda L6 si empezamos por la izquierda.

   - =LEFT(3,L6)
    
      ❌ Incorrecto.

   - =RIGHT(L6, 3)
    
      ❌ Incorrecto.

   - =RIGHT(3,L6)
    
      ❌ Incorrecto.


8. Completa el espacio en blanco: Cuando los analistas de datos trabajan con una hoja de cálculo, pueden usar la función _____ para ubicar ciertos caracteres específicos en una cadena.

   - Buscar
    
      ✅ Correcto. Cuando los analistas de datos trabajan con una hoja de cálculo, pueden usar la función FIND para ubicar ciertos caracteres específicos en una cadena.

   - FROM
    
      ❌ Incorrecto.

   - WHERE
    
      ❌ Incorrecto.

   - IDENTIFY
    
      ❌ Incorrecto.



