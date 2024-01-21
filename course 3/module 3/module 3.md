# <img src="https://github.com/shimadasoftware/data-analysis-path/assets/73977456/9dfa6ce6-b8d0-44d0-b472-74f530bd4728" alt="Italian Trulli" style="width:25px;height:25px;"> Módulo 3: Bases de datos: Donde se alojan los datos
**©** Copyright es reservado para la plataforma Google y Coursera.

[![Tiempo](https://img.shields.io/badge/Tiempo-120%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Cuando estés analizando datos, accederás a gran parte de los datos de una base de datos. Es allí donde se alojan los datos. En esta parte del curso, aprenderás todo sobre las bases de datos, incluso la forma de acceder a ellas y extraer, filtrar y ordenar los datos que contienen. También le echarás un vistazo a los metadatos para descubrir los diferentes tipos y cómo los usan los analistas.

## Objetivos

- Describir bases de datos con referencias a sus funciones y componentes.
- Explicar los metadatos en relación con las bases de datos.
- Analizar la importancia de los metadatos y cómo se relacionan con el trabajo de un analista de datos.
- Demostrar comprensión de los problemas y los pasos necesarios para acceder a datos de varias fuentes.
- Explicar el uso de filtros y la funcionalidad de ordenación en las hojas de cálculo.
- Demostrar que se sabe cómo usar la funcionalidad de la hoja de cálculo para importar e inspeccionar un conjunto determinado de datos.
- Demostrar que se sabe cómo usar las funciones de SQL para extraer datos de una base de datos

Este tercer modulo se divide en:

1. Trabajar con bases de datos
2. Gestionar datos con metadatos
3. Accede a diferentes fuentes de datos
4. Ordenar y filtrar
5. Trabajar con conjuntos de datos grandes en SQL
6. Desafio semanal 3

---

## 1. Trabajar con bases de datos 📋 

### Temario: 
 
- Todo sobre las bases de datos (Vídeo - 2 min)
- Características de las bases de datos (Vídeo - 3 min)
- Bases de datos en el análisis computacional de datos (Lectura - 10 min)
- Claves primarias y externas (Complemento no calificado - 15 min)
- Examinar un conjunto de datos: Un recorrido práctico y guiado (Lectura - 10 min)
- Pon a prueba tus conocimientos sobre cómo trabajar con conjuntos de datos (Cuestionario práctico - 3 preguntas)

### Todo sobre las bases de datos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-2%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Hola de nuevo. Hasta ahora, has visto cómo se pueden reunir y analizar los datos para resolver todo tipo de problemas. El siguiente paso es aprender todo sobre bases de datos a modo de repaso. Una base de datos es un conjunto de datos almacenados en un sistema informático, pero el almacenamiento es solo el comienzo. Descubrirás cómo las bases de datos posibilitan encontrar la información exacta que necesitas para tu análisis. También aprenderás cómo ordenar los datos para acercar aquellos que necesites para generar informes perspicaces y mucho más. Luego profundizaremos estos temas muy, pero muy a fondo. Estoy hablando de metadatos. Es probable que hayas escuchado a alguien decir que algo es “**autoconsciente**” (en inglés, “**meta**”). En general, están hablando de algo que se refiere a sí mismo o que está siendo consciente de sí mismo. Por ejemplo, si el personaje de un libro sabe que está dentro de un libro, es autoconsciente.. Si realizas un documental sobre cómo hacer documentales, eso también es algo autoconsciente. Y aquí, en Google, constantemente analizo la forma en que analizo los datos. No hay duda de que eso es autoconsciente.

Hago eso para que mi trabajo cuente con una revisión de calidad, para asegurarme de que mis métodos son justos. Y para asegurarme de que estoy prestando atención a cualquier sesgo que pueda afectar el resultado. Como analista, debes hacer esto también. A veces nos acercamos demasiado a nuestros datos. Y es clave tomar distancia y preguntarnos a nosotros mismos si nuestros procesos tienen sentido. Pero regresemos un poco hacia atrás y definamos metadatos. Los metadatos son datos sobre los datos. Como ya dije: es muy profundo.

**Los metadatos son muy importantes cuando trabajas con bases de datos**. Piensa en ellos como una guía de referencia. Sin esa guía lo único que tienes es un montón de datos sin un contexto que explique lo que significan. **Los metadatos indican de dónde vienen los datos, cuándo y cómo se crearon, y de qué se tratan.**

A continuación, aprenderás cómo tomar datos de una base de datos u otra fuente y agregarlos a una hoja de cálculo. Podrás hacer esto importando datos directamente o utilizando SQL para generar la solicitud. Y una vez que tengas los datos en una hoja de cálculo, las posibilidades son infinitas. Todo lo que estamos a punto de aprender es una parte muy importante de la fase de preparación del proceso de análisis de datos. Es cómo los analistas de datos descubren qué tipo de datos serán útiles para ellos. Si tienes los datos correctos, es muy probable que puedas resolver los problemas de tu empresa de forma exitosa. ¿Estás listo para aprovechar el increíble poder de las bases de datos? Empecemos.

### Características de las bases de datos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Las bases de datos son herramientas esenciales para los analistas de datos. Yo las utilizo constantemente. Todos los datos a los que accedo están almacenados en bases de datos. Las bases de datos almacenan y organizan datos, lo que facilita la gestión y el acceso a la información por parte de los analistas de datos. Nos ayudan a obtener información de forma más rápida, a tomar decisiones basadas en datos y a resolver problemas. Ya has oído hablar un poco acerca de qué son las bases de datos y cómo las usan los analistas de datos. Ahora vamos a aprender más sobre las funciones y los componentes de las bases de datos. Aquí puedes ver una estructura simple de una base de datos. Contiene tablas con información sobre un fabricante de automóviles. El nivel superior incluye concesionarios de automóviles, detalles de productos y piezas de repuesto. Luego, si examinas a fondo el siguiente nivel tras seleccionar una de esas tablas, encontrarás detalles más específicos sobre cada una de ellas. Esto se denomina una base de datos relacional. 

![image](./img/module%3001%20img%3001.png)

**Una base de datos relacional es una base de datos que contiene una serie de tablas relacionadas que pueden conectarse mediante sus relaciones**. Para que dos tablas tengan una relación, debe haber uno o más campos iguales dentro de ambas tablas. Por ejemplo, en este caso, branch ID puede verse en esta tabla y en esta otra. Si existe el mismo campo en ambas tablas, podemos utilizarlo para conectar las dos tablas. El campo con branch ID es clave para conectar estas tablas. Hay dos tipos de claves. **Una clave primaria es un identificador que hace referencia a una columna en la que cada valor es único**. Puedes considerarla como un identificador único para cada fila de la tabla. Para nuestra tabla del concesionario, que contiene información sobre las distintas sucursales del concesionario, branch ID es la clave primaria. De manera similar, para la tabla que contiene detalles de los productos de cada automóvil, nuestra clave primaria es el número de inspección del vehículo (VIN). Como analista, es posible que necesites crear tablas. **Si decides incluir una clave primaria, debe ser única, lo que quiere decir que no puede haber dos filas con la misma clave primaria. Tampoco puede tener un valor nulo o en blanco.**

También hay claves externas. Una clave externa es un campo en una tabla que es una clave primaria en otra tabla. En otras palabras, **una clave externa es cómo una tabla puede conectarse con otra**. Dado que nuestra tabla con las piezas de repuesto contiene información sobre cada parte del automóvil, la clave primaria es part ID. Cada fila de nuestra tabla de piezas de repuesto representa una pieza única. Todas las otras claves de esta tabla, como el número de inspección del vehículo, son claves externas que permiten que la tabla de las piezas de repuesto esté conectada con las otras tablas. Como puedes ver, una tabla solo puede tener una clave primaria, pero puede contar con muchas claves externas. 

Comprender la clave primaria y las claves externas puede ser complicado, pero tendrás más oportunidades para practicarlas próximamente. A modo de resumen general, una clave primaria se utiliza para asegurar que los datos de una columna específica son únicos. Solamente identifica un registro en una tabla de base de datos relacional. **Solo se permite una clave primaria en una tabla y no puede contener valores nulos o en blanco. Una clave externa es una columna o un grupo de columnas de una tabla de base de datos relacional que proporciona un enlace entre los datos y las dos tablas**. Se refiere al campo de una tabla que es la clave primaria de otra tabla. Por último, **es importante recordar que puede haber más de una clave externa en una tabla**.

![image](./img/module%3001%20img%3002.png)

![image](./img/module%3001%20img%3003.png)

### Bases de datos en el análisis computacional de datos 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-10%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Las bases de datos permiten a los analistas manipular, almacenar y procesar datos. Esto les ayuda a buscar datos de manera mucho más eficiente para obtener la mejor información. 

#### Bases de datos relacionales

Una base de datos relacional es una base de datos que contiene una serie de tablas que se pueden conectar para mostrar relaciones. Básicamente, permiten a los analistas de datos organizar y vincular datos en función de lo que los datos tienen en común. 

En una tabla no relacional, encontrarás todas las variables posibles que podría interesarte analizar agrupadas conjuntamente. Esto puede hacer que sean realmente difíciles de clasificar. Esa es una de las razones por las que las bases de datos relacionales son tan comunes en el análisis de datos: simplifican muchos procesos de análisis y hacen que los datos sean más fáciles de encontrar y de usar en toda una base de datos. 

#### La clave de las bases de datos relacionales

Las tablas de una base de datos relacional están conectadas por los campos que tienen en común. Es posible que recuerdes haber aprendido sobre las claves primarias y externas antes. Para repasar rápidamente, una clave primaria es un identificador que hace referencia a una columna en la que cada valor es único. En otras palabras, es una columna de una tabla que se utiliza para identificar de forma única cada registro dentro de esa tabla. El valor asignado a la clave primaria en una fila determinada debe ser único en toda la tabla. Por ejemplo, si customer_id es la clave primaria para la tabla del cliente, no puede haber dos clientes con el mismo customer_id. 

Por el contrario, una **clave externa** es un campo en una tabla que es una clave primaria en otra tabla. Una tabla puede tener solo una clave primaria, pero puede tener varias claves externas. Esas claves son las que generan las relaciones entre las tablas en una base de datos relacional, lo que ayuda a organizar y conectar los datos entre varias tablas en la base de datos. 

Algunas tablas no requieren una clave primaria. Por ejemplo, una tabla de ingresos puede tener muchas claves externas y ninguna clave primaria. Una clave primaria también puede construirse a partir de varias columnas de una tabla. Este tipo de clave primaria se denomina clave compuesta. Por ejemplo, si customer_id y location_id son dos columnas de una clave compuesta en la tabla de un cliente, los valores asignados a esos campos en cualquier fila dada deben ser únicos en toda la tabla.

![image](./img/module%3001%20img%3004.png)

#### ¿SQL? Estás hablando mi idioma 

Las bases de datos utilizan un lenguaje especial para comunicarse denominado lenguaje de consulta. El lenguaje de consulta estructurado (SQL) es un tipo de lenguaje de consulta que permite a los analistas de datos comunicarse con la base de datos. De este modo, un analista de datos usará SQL para crear una consulta con el fin de ver los datos específicos que quiere visualizar en un conjunto más grande. En una base de datos relacional, los analistas de datos pueden escribir consultas para obtener información de las tablas relacionadas. SQL es una herramienta poderosa para trabajar con bases de datos; ¡por eso aprenderás más sobre esta herramienta a continuación! 

### Examinar un conjunto de datos: Un recorrido práctico y guiado 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-10%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Las claves crean relaciones entre tablas en bases de datos relacionales. En este ejercicio, identificarás similitudes y diferencias entre claves primarias y externas.

1. Una tabla puede tener solo una _____.

    - Llave primaria (PK)
    
      ✅ Correcto. Una clave primaria es única y puede existir solo una vez dentro de una tabla determinada. No puede contener valores nulos o en blanco.
  
    - Llave foránea (FK)
    
      ❌ Incorrecto.
    
    - Ambas
    
      ❌ Incorrecto.
      
    - Ninguna
    
      ❌ Incorrecto.


2. Una tabla puede tener muchas _____.

    - Llave primaria (PK)
    
      ❌ Incorrecto.
  
    - Llave foránea (FK)
    
      ✅ Correcto. Una clave externa es un campo que es una clave primaria en otra tabla. Las tablas pueden contener varias claves externas.
    
    - Ambas
    
      ❌ Incorrecto.
      
    - Ninguna
    
      ❌ Incorrecto.


3. No puede tener valores nulos o en blanco _____.

    - Llave primaria (PK)
    
      ✅ Correcto. Una clave primaria es única y puede existir solo una vez dentro de una tabla determinada. No puede contener valores nulos o en blanco.
  
    - Llave foránea (FK)
    
      ❌ Incorrecto. En el caso de la llave foránea (FK), puede permitirse que contenga valores nulos. Una llave foránea nula indica que no hay una relación correspondiente con la tabla referenciada. Por ejemplo, en una relación "muchos a uno", donde varios registros de una tabla pueden relacionarse con un solo registro en otra, algunos registros pueden no tener una relación establecida y, por lo tanto, tendrían valores nulos en la llave foránea.
    
    - Ambas
    
      ❌ Incorrecto. 
      
    - Ninguna
    
      ❌ Incorrecto. 


4. Es un campo en una tabla que es una clave primaria en otra tabla.

    - Llave primaria (PK)
    
      ❌ Incorrecto.
  
    - Llave foránea (FK)
    
      ✅ Correcto. Una clave externa es un campo que es una clave primaria en otra tabla. Las tablas pueden contener varias claves externas.
    
    - Ambas
    
      ❌ Incorrecto.
      
    - Ninguna
    
      ❌ Incorrecto.


5. Se utiliza para conectar tablas en bases de datos relacionales.

    - Llave primaria (PK)
    
      ❌ Incorrecto.
  
    - Llave foránea (FK)
    
      ❌ Incorrecto.
    
    - Ambas
    
      ✅ Correcto. Tanto las claves primarias como las externas conectan tablas en bases de datos relacionales. Las tablas pueden tener solo una clave primaria, pero pueden tener varias claves externas.
      
    - Ninguna
    
      ❌ Incorrecto.


6. Se utiliza para conectar tablas en bases de datos relacionales.

    - Llave primaria (PK)
    
      ✅ Correcto. Una clave primaria es única y puede existir solo una vez dentro de una tabla determinada. No puede contener valores nulos o en blanco.
  
    - Llave foránea (FK)
    
      ❌ Incorrecto.
    
    - Ambas
    
      ❌ Incorrecto.
      
    - Ninguna
    
      ❌ Incorrecto.


### Cuestionario práctico 📑

[![Tiempo](https://img.shields.io/badge/Tiempo-20%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Pon a prueba tus conocimientos sobre cómo trabajar con conjuntos de datos.

1. Completa el espacio en blanco: Un _____ es un identificador que hace referencia a una columna de una base de datos en la que cada valor es único. 

    - campo
    
      ❌ Incorrecto.
  
    - clave externa
    
      ❌ Incorrecto.
    
    - clave primaria
    
      ✅ Correcto. Una clave primaria es un identificador que hace referencia a una columna en la que cada valor es único. Una clave externa es un campo en una tabla que es una clave primaria en la tabla original.
      
    - relación
    
      ❌ Incorrecto.


2. Completa el espacio en blanco: Una base de datos relacional contiene una serie de _____ que se pueden conectar para formar relaciones.

    - hojas de cálculo
    
      ❌ Incorrecto.
  
    - celdas
    
      ❌ Incorrecto.
    
    - tablas
    
      ✅ Correcto. Una base de datos relacional contiene una serie de tablas que se pueden conectar para formar relaciones.
      
    - campos
    
      ❌ Incorrecto.


3. Un beneficio clave de trabajar con bases de datos normalizadas es que ayudan a reducir la redundancia de datos. ¿Cuál de las siguientes opciones es un ejemplo de redundancia?

    - Una base de datos que forma dos o más relaciones
    
      ❌ Incorrecto.
  
    - Los mismos datos se almacenan en dos lugares diferentes.
    
      ✅ Correcto. Los mismos datos que se almacenan en dos lugares diferentes son un ejemplo de redundancia.
    
    - Los miembros del equipo en las distintas oficinas que trabajan con los mismos datos.
    
      ❌ Incorrecto.
      
    - Una base de datos que contiene dos claves externas.
    
      ❌ Incorrecto.

      
---

## 2. Gestionar datos con metadatos 🗄️ 

### Temario: 

- Explorar los metadatos (Vídeo - 3 min)
- Los metadatos son tan importantes como los datos en sí (Lectura - 10 min)
- Utilizar metadatos como un analista (Vídeo - 3 min)
- Gestión de metadatos (Vídeo - 3 min)
- Diversión con metadatos (Vídeo - 2 min)
- Pon a prueba tus conocimientos sobre metadatos (Cuestionario práctico - 4 preguntas)

### Explorar los metadatos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Ahora que conoces las distintas formas de organizar datos en una base de datos, veamos cómo puedes describir esos datos. En este video comenzaremos a explorar los metadatos, que son un aspecto muy importante de la gestión de la base de datos. Sin embargo, el concepto “metadatos” es abstracto. Empecemos con un ejemplo simple y cotidiano. ¿Sabías que cada vez que tomas una fotografía con un teléfono inteligente se recopilan datos automáticamente y se almacenan junto con esa fotografía? Echa un vistazo. Elije cualquier fotografía de tu computadora. Aquí hay una linda toma de los perros de mi amigo, Rudy y Matilda. Haz clic con el botón derecho sobre tu fotografía y selecciona “Obtener información” o “Propiedades”.

Así podrás ver los metadatos de tu fotografía, que te dirán el tipo de archivo que es, la fecha y la hora en que la tomaste, la geolocalización o dónde la tomaste, qué tipo de dispositivo utilizaste para tomarla y mucho más. Asombroso, ¿verdad? Aquí tienes otro ejemplo. Cada vez que envías o recibes un correo electrónico, los metadatos acompañan ese mensaje. Puedes encontrarlos haciendo clic en “Ver original” o “Ver detalles del mensaje”.

Los metadatos de un correo electrónico incluyen su asunto, el remitente, el destinatario, y la fecha y la hora en que fue enviado. Los metadatos incluso saben qué tan rápido fue enviado una vez que el remitente presionó “Enviar”. Los metadatos son información que se utiliza para describir los datos que algo contiene, como una fotografía o un correo electrónico. Recuerda que los metadatos no son los datos. En cambio, son datos sobre datos. En el análisis computacional de datos, **los metadatos ayudan al analista de datos a interpretar el contenido de los datos de una base de datos**. Por eso los metadatos son tan importantes cuando trabajas con bases de datos. Le indican al analista de qué se tratan los datos. Eso posibilita poner los datos a trabajar para resolver problemas y tomar decisiones basadas en datos. Como analista de datos, hay tres tipos comunes de metadatos con los que te vas a cruzar: descriptivos, estructurales y administrativos. Los metadatos descriptivos son metadatos que describen una pieza de datos y pueden utilizarse para identificarla más adelante. Por ejemplo, los metadatos descriptivos de un libro que se encuentra en una biblioteca incluirían el código que ves en el lomo, que se conoce como código normalizado internacional para libros, también denominado ISBN.

También incluiría el autor y el título del libro. Luego pasamos a los metadatos estructurales, que son los metadatos que indican cómo se organiza un dato y si forma parte de una o más recopilaciones de datos. Volvamos a la biblioteca. Un ejemplo de datos estructurales sería cómo se reúnen las páginas de un libro para crear los diferentes capítulos. Es importante dar cuenta de que los metadatos estructurales también hacen un seguimiento de la relación entre dos cosas. Por ejemplo, pueden mostrarnos que el documento digital del manuscrito de un libro era en realidad la versión original de un libro que hoy está impreso. Finalmente, tenemos los metadatos administrativos. Los metadatos administrativos son metadatos que indican la fuente técnica de un recurso digital. Cuando observamos los metadatos de la fotografía, esos eran metadatos administrativos. Te dirán el tipo de archivo que era, la fecha y la hora en que tomaste la fotografía, y mucho más. Aquí tienes una reflexión final que te ayudará a comprender los metadatos. Si estás yendo a la biblioteca a buscar un libro, podrías buscar el título de un libro, el autor, la extensión y la cantidad de capítulos. Esos son metadatos, y pueden decirte mucho sobre el libro, pero tendrás que leer realmente el libro para saber de qué se trata. Del mismo modo, puedes leer sobre análisis computacional de datos pero debes tomar este curso para obtener al certificado de Google Data Analytics. Sigue adelante para obtener esa nueva perspectiva.

![image](./img/module%3001%20img%3005.png)

### Los metadatos son tan importantes como los datos en sí 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-10%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Echa un vistazo a cualquier dato que encuentres. ¿Qué es? ¿De dónde provino? ¿Es útil? ¿Cómo lo sabes? Aquí es donde entran en juego los metadatos para proporcionar una mejor comprensión de los datos. En pocas palabras, los metadatos son datos sobre datos. En la gestión de la base de datos, proporcionan información sobre otros datos y ayudan a los analistas de datos a interpretar los contenidos de los datos en una base de datos.

Independientemente de si estás trabajando con una gran cantidad de datos o con una pequeña, los metadatos son la marca de un equipo de análisis bien informado, que ayuda a comunicar datos a toda la empresa y a simplificar la reutilización de los datos. Básicamente, los metadatos informan el quién, qué, cuándo, dónde, cuál, cómo y por qué de los datos.

#### Elementos de los metadatos

Antes de mirar ejemplos de metadatos, es importante comprender qué tipo de información suelen proporcionar los metadatos.

#### Título y descripción

¿Cuál es el nombre del archivo o del sitio web que estás examinando? ¿Qué tipo de contenido tiene?

#### Etiquetas y categorías

¿Cuál es la descripción general de los datos que tienes? ¿Los datos están indexados o descriptos de algún modo específico? 

#### Quién los creó y cuándo

¿De dónde vinieron los datos y cuándo se crearon? ¿Son recientes o existen desde hace mucho tiempo?

#### Quién los modificó por última vez y cuándo

¿Se realizaron cambios en los datos?  De ser así, ¿las modificaciones eran recientes?

#### Quién puede acceder a ellos o actualizarlos

¿Este conjunto de datos es público? ¿Se necesitan permisos especiales para personalizar o modificar el conjunto de datos?

#### Ejemplos de metadatos

En el mundo digital actual, los metadatos están en todos lados y es una práctica cada vez más común brindar metadatos en muchos medios e información con la que interactúas. Aquí tienes algunos ejemplos de la vida real sobre dónde encontrar metadatos:

#### Fotografías

Cuando se toma una fotografía con una cámara, se recopilan y se guardan metadatos relacionados con el nombre del archivo en la cámara, la fecha, la hora y la geolocalización.

#### Correos electrónicos

Cuando envías o recibes un correo electrónico, hay muchos metadatos visibles, como la línea del asunto, el destinatario, y la fecha y la hora del envío. También hay metadatos ocultos que incluyen nombres de servidores, direcciones IP, formatos HTML y detalles de software.

#### Hojas de cálculo y documentos

Las hojas de cálculo y los documentos contienen una gran cantidad de datos, así que no resulta sorprendente que los metadatos también los acompañen. Los títulos, el autor, la fecha de creación, el número de páginas, los comentarios del usuario, así como los nombres de las pestañas, de las tablas y de las columnas son metadatos que pueden encontrarse en hojas de cálculo y en documentos. 

#### Sitios web

Cada página web tiene un número de campos de metadatos estándar; por ejemplo, etiquetas y categorías, nombre del creador del sitio, título y descripción de la página web, hora de creación y cualquier iconografía. 

#### Archivos digitales

Por lo general, si haces clic con el botón derecho en cualquier archivo de la computadora, verás sus metadatos. Pueden consistir en el nombre de un archivo, su tamaño, la fecha de creación y de modificación, y el tipo de archivo. 

#### Libros

Los metadatos no son solamente digitales. Cada libro tiene una cantidad de metadatos estándares en las tapas y en el interior que te informarán sobre el título, el nombre del autor, la tabla de contenidos, la información editorial, la descripción de copyright, el índice y una breve descripción de los contenidos del libro.

#### Los datos como los conoces

Conocer el contenido y el contexto de tus datos, así como la forma en la que están estructurados, es muy valioso en tu carrera como analista de datos. A la hora de analizar los datos, es importante que siempre entiendas el panorama general. No solo se trata de los datos que estás observando, sino de cómo se integran esos datos. Los metadatos garantizan que puedas encontrar, utilizar, preservar y reutilizar los datos en el futuro. Recuerda que será tu responsabilidad gestionar y utilizar los datos en su totalidad; los metadatos son tan importantes como los datos.

### Utilizar metadatos como un analista 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Ahora que sabes qué son los metadatos, es hora de explorar por qué los analistas de datos los utilizan. Ya sabes que los datos necesitan ser identificados y descriptos antes de que puedan ayudarte a resolver un problema o a tomar una decisión efectiva para la empresa. Poner los datos en contexto es probablemente lo más valioso que hacen los metadatos, pero hay muchos más beneficios de utilizar metadatos. Este es uno de ellos. Los metadatos crean una única fuente de verdad al mantener las cosas coherentes y uniformes. Nosotros, los analistas de datos, amamos la coherencia. Siempre buscamos este tipo de uniformidad en nuestros datos y en nuestras bases de datos. Después de todo, los datos que **son uniformes pueden organizarse, clasificarse, almacenarse, accederse y utilizarse de manera efectiva**. Además, cuando una base de datos es coherente, es mucho más fácil descubrir relaciones entre los datos que están dentro de ella y los datos que están en otro lugar. 

**Los metadatos también permiten que los datos sean más confiables al asegurar que sean exactos, precisos, relevantes y oportunos**. Eso hace que sea más fácil para los analistas de datos identificar las causas raíz de cualquier problema que pueda surgir. La conclusión es que, cuando los datos con los que trabajamos son de buena calidad, las cosas se vuelven más simples y mejoran los resultados. Una de las formas en que los analistas de datos se aseguran de que sus datos sean coherentes y confiables es mediante el uso de algo llamado repositorio de metadatos. 

**Un repositorio de metadatos es una base de datos creada específicamente para almacenar metadatos**. Los repositorios de metadatos pueden **almacenarse en una locación física o pueden ser virtuales, como los datos que existen en la nube**. Estos repositorios describen de dónde vienen los metadatos, los mantienen accesibles para que puedan ser utilizados de forma rápida y simple, y los mantienen en una estructura común para quienes necesiten utilizarlos. Los repositorios de metadatos hacen que sea más fácil y rápido reunir muchas fuentes para el análisis de datos. Para hacer esto, describen el estado y la ubicación de los metadatos, la estructura de las tablas que están dentro y cómo fluyen los datos por el repositorio. Incluso registran quién accede a los metadatos y cuándo. 

Aquí hay un ejemplo del mundo real. Como analista del cuidado de la salud en Google, utilizo datos de segunda y de tercera fuente. Como sabes, los datos de segunda fuente son datos que recopila un grupo directamente de su audiencia y que, luego, se venden. Los datos de tercera fuente vienen de fuentes externas que no son las recopiladoras originales de los datos. Los obtienen de páginas web o de programas que extraen los datos de distintas plataformas donde se generaron originalmente. Es un poco complejo, pero lo más importante es recordar que los datos de terceras partes no provienen del interior de tu propia empresa. Si mi equipo necesita trabajar con datos que no fueron creados en Google, eso quiere decir que a veces nosotros no sabemos demasiado sobre su calidad y credibilidad, pero necesitamos estar seguros de que nuestros datos pueden ser confiables y que se recopilaron de manera responsable. Después de todo, si los datos no son confiables, nuestros resultados tampoco serán confiables. Por eso es tan importante comprender los metadatos de la base de datos externa. Nos permite confirmar que los datos están limpios, son precisos, relevantes y oportunos. Eso es muy importante si los datos provienen de otra organización. 

Otro paso importante cuando uno trabaja con datos externos es confirmar que estamos autorizados a utilizarlos. Solemos contactar al dueño para asegurarnos de que podemos acceder a ellos o comprarlos. En resumen, los repositorios de metadatos son útiles por todas estas razones. Además, me ayudan a garantizar que mi equipo está extrayendo el contenido correcto para un proyecto particular y que lo está utilizando de forma apropiada. Podemos confirmar esto porque los metadatos describen de manera clara cómo y cuándo se recopilaron los datos, cómo están organizados y mucho más. Pronto aprenderás mucho más sobre el uso de metadatos en análisis computacional de datos, y si piensas que los metadatos son particularmente fascinantes, descubrirás algunas opciones profesionales muy emocionantes que se enfocan en los metadatos. Mantente atento.

### Gestión de metadatos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Los metadatos y los repositorios de metadatos son herramientas muy poderosas de la caja de herramientas de los analistas de datos. Como hemos visto anteriormente, los analistas de datos las utilizan para crear una única fuente de verdad, mantener la coherencia y uniformidad de los datos y asegurarse de que los datos con los que trabajamos sean exactos, precisos, relevantes y oportunos. Estas herramientas también facilitan el acceso a los datos y su utilización al estandarizar nuestros procesos. En este video, analizaremos más componentes sobre los metadatos y aprenderemos cómo trabajan los analistas de metadatos para mantener las cosas organizadas. Sabemos que la cantidad de datos que hay allí afuera continúa creciendo, pero muchas empresas no están usando sus datos. 

A veces, no saben lo que tienen; otras, no pueden encontrarlo; y otras, la empresa simplemente no confía en lo que tiene. Especialmente en las grandes empresas, los datos pueden abarcar numerosos procesos y sistemas diferentes. Y reunir datos de tantos lugares diferentes puede ser un gran desafío. Por ejemplo, digamos que una empresa comienza con un sistema de almacenamiento de datos tradicional en sus oficinas. Pero luego, a medida que la cantidad de datos que tiene continúa expandiéndose, también necesita almacenamiento en la nube. Además, esta empresa puede estar accediendo y utilizando datos de segundas y terceras partes de una organización asociada. Cada uno de estos sistemas tiene sus propias reglas y requisitos, de modo que cada uno organiza los datos de una forma completamente diferente, lo que le da incluso más complejidad. 

No es de extrañar que muchas organizaciones tengan dificultades para encontrar los datos correctos en el momento preciso. Por otro lado, los metadatos se almacenan en una ubicación única, central y le brindan a la empresa información estandarizada sobre todos sus datos. Eso se realiza de dos maneras. En primer lugar, los metadatos incluyen información sobre dónde está localizado cada sistema y dónde se ubican los conjuntos de datos dentro de esos sistemas. En segundo lugar, los metadatos describen cómo se conectan todos esos datos entre varios sistemas. Otro aspecto importante de los metadatos es algo llamado gobierno de datos. 

**El gobierno de datos es un proceso para asegurar la gestión formal de los recursos de datos de una empresa**. Eso le brinda a la organización un mejor control de sus datos y le ayuda a la empresa a gestionar problemas relacionados con la seguridad y privacidad de los datos, con la integridad y la facilidad de uso, y con los flujos de datos internos y externos. Es importante señalar que el gobierno de datos es más que solo la estandarización de terminología y de procedimientos. Se trata de las funciones y responsabilidades de las personas que trabajan todos los días con metadatos. Son especialistas en metadatos, y organizan y mantienen los datos de la empresa para asegurar que sean de la mejor calidad posible. Esas personas crean identificación de metadatos e información de descubrimiento básicas, describen la forma en la que los conjuntos de datos trabajan juntos, y explican los variados y diferentes tipos de recursos de datos. Los especialistas en metadatos también crean estándares muy importantes que todos siguen, y los modelos que se utilizan para organizar los datos. Hay una cosa que todos tienen en común. Ya sea que trabajen en una empresa de tecnología, una asociación sin fines de lucro o una institución financiera, los analistas de metadatos tienen un gran espíritu de equipo. Les apasiona que los datos sean accesibles y los comparten con colegas y otros interesados. Si estás buscando un puesto que te impulse a explorar todos los datos que el mundo digital tiene para ofrecer, seguir el camino para convertirte en un analista de metadatos puede ser la opción correcta para ti. Pero, de todas maneras, todo tipo de empresas enfrentan las tendencias del mercado y la competencia, y necesitan comprender la razón por la que un proceso funciona y otro no. El análisis computacional de datos les permite responder preguntas clave y seguir mejorando.

### Diversión con metadatos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-2%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Mi nombre es Megan y soy directora de mediciones de agencia en Google. Básicamente, ayudo a desmitificar las mediciones y el análisis de datos para agencias publicitarias. Ya sean las personas a cargo de la ejecución de los planes de medios para los anunciantes como las personas interesadas en medir el impacto que tienen los medios para sus clientes. He estado haciendo esto durante unos 17 años y he visto la evolución en el espacio de la disponibilidad de datos, de diferentes técnicas de modelado que han avanzado y se han vuelto más accesibles y ha sido un viaje realmente interesante ver cómo ha evolucionado, cómo el análisis de datos se ha vuelto más masivo y cómo las personas están más entusiasmadas por ello. Los metadatos son básicamente la clave de tu conjunto de datos mayor. Esto ayuda a describir qué hay en las filas y las columnas de los datos con los que estarás trabajando. Los metadatos son una especie de taquigrafía o una versión de las guías de estudio CliffsNotes de un conjunto de información más complejo. Pueden ser útiles en el sentido de ayudarte a manejar el contenido de un solo conjunto de datos al que puedas tener acceso.

Es una parte importante del proceso de descubrimiento de un proyecto de análisis de datos mientras trabajas con un cliente o un proveedor para comprender los recursos con los que contarás para resolver un problema y qué es lo que falta. Te da las claves para desbloquear los datos de modo simple y directo y es una gran herramienta de comunicación. Cuando estaba trabajando para un publicitario, una de las cosas que estábamos tratando de hacer era construir algo llamado lago de datos. En esencia, se trata de reunir todas las fuentes de datos que quieras utilizar en un análisis en un solo lugar, lo que puede resultar realmente riesgoso. Uno de los beneficios de los metadatos era imaginar que teníamos fuentes que podían superponerse, donde había fuentes de datos que tenían cosas en común. Y cuáles son las piezas únicas de información que estábamos obteniendo de cada uno de esos conjuntos de datos. De modo que al pensar cómo encarar este proyecto realmente enorme e importante pudimos utilizar los metadatos para alcanzar en forma rápida y fácil los constructos básicos que estamos tratando de manejar. Cuando estás trabajando con personas que pueden no realizar análisis de datos en su trabajo normal llegar al momento en que dicen "claro", ayudarlos a entender cómo las herramientas de medición y análisis de datos pueden ayudarlos a lograr sus metas, es muy importante. Y darte cuenta de que hiciste algo que previamente era inaccesible un poco más accesible para el equipo y lo has convertirlo en algo más cómodo para poner en práctica es realmente importante y algo genial como resultado de una sociedad.

### Cuestionario práctico 📑

[![Tiempo](https://img.shields.io/badge/Tiempo-20%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Pon a prueba tus conocimientos sobre metadatos.

1. Una empresa grande tiene varias recopilaciones de datos en sus diversos departamentos. ¿Qué tipo de metadatos indica exactamente en cuántas recopilaciones se encuentra un dato?

    - Administrativos
    
      ❌ Incorrecto.
  
    - Descriptivos
    
      ❌ Incorrecto.
    
    - Estructurales
    
      ✅ Correcto. Los metadatos estructurales indican exactamente en cuántas recopilaciones se encuentran ciertos datos. Proporciona información sobre cómo se organizan los datos y si forman parte de una o de más de una recopilación de datos. 
      
    - Representativos
    
      ❌ Incorrecto.


2. ¿La fecha y el momento en que se tomó una foto es un ejemplo de qué tipo de metadatos?

    - Administrativos
    
      ✅ Correcto. La fecha y el momento en que se tomó una foto es un ejemplo de metadatos administrativos. Los metadatos administrativos indican la fuente técnica y los detalles para un activo digital.
  
    - Descriptivos
    
      ❌ Incorrecto.
    
    - Estructurales
    
      ❌ Incorrecto.
      
    - Representativos
    
      ❌ Incorrecto.


3. ¿La fecha y el momento en que se tomó una foto es un ejemplo de qué tipo de metadatos?

    - Administrativos
    
      ❌ Incorrecto.
  
    - Descriptivos
    
      ✅ Correcto. Los números de ID son metadatos descriptivos. Los metadatos descriptivos describen a un dato y se pueden utilizar para identificarlo en cualquier momento.
    
    - Estructurales
    
      ❌ Incorrecto.
      
    - Representativos
    
      ❌ Incorrecto.


4. Una empresa necesita fusionar datos de terceros con sus propios datos. ¿Cuál de las siguientes acciones ayudarán a que este proceso sea exitoso? Selecciona todas las opciones que correspondan.

    - Utilizar los metadatos para estandarizar los datos.
    
      ✅ Correcto. La empresa puede utilizar los metadatos para estandarizar los datos y evaluar la calidad y credibilidad de los datos de terceros.
  
    - Alterar los metadatos de la empresa para reflejar más minuciosamente los metadatos entrantes.
    
      ❌ Incorrecto.
    
    - Utilizar los metadatos para evaluar la calidad y credibilidad de los datos de terceros.
    
      ✅ Correcto. La empresa puede utilizar los metadatos para estandarizar los datos y evaluar la calidad y credibilidad de los datos de terceros.
      
    - Reemplazar los metadatos de los datos entrantes con los metadatos de su propia empresa.
    
      ❌ Incorrecto.


---

## 3. Accede a diferentes fuentes de datos 🔎 

### Temario: 

- Trabaja con más fuentes de datos (Vídeo - 3 min)
- Importar datos desde hojas de cálculo y bases de datos (Vídeo - 3 min)
- Explorar conjuntos de datos publicos (Lectura - 10 min)
- Pon a prueba tus conocimientos sobre el acceso a las fuentes de datos (Cuestionario práctico - 3 preguntas)

### Trabaja con más fuentes de datos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

En este video, hablaremos sobre los diferentes lugares a los que van los analistas de datos para conectar con los datos. Hay muchos tipos de datos y es importante saber cómo acceder a ellos. Anteriormente, aprendiste que hay dos tipos básicos de datos que utilizan los analistas de datos: **internos y externos**. 

**Los datos internos son datos que están alojados en los sistemas propios de una empresa**. Normalmente, también son generados desde dentro de la misma empresa. Es posible que escuches que los datos internos son descriptos como datos primarios. **Los datos externos son datos que se alojan y son generados fuera de una organización**. Pueden venir de una variedad de lugares, incluso de otras empresas, fuentes gubernamentales, los medios, asociaciones profesionales, escuelas y muchos más. A veces, los **datos externos son denominados datos secundarios**. 

Reunir datos internos puede ser complicado. Según tu proyecto de análisis computacional de datos, puedes necesitar datos de muchas fuentes y departamentos diferentes, que pueden incluir ventas, marketing, gestión de las relaciones con los clientes, finanzas, recursos humanos e incluso archivos de datos. Pero el esfuerzo lo vale. Los datos internos tienen muchas ventajas para una empresa. Proporcionan información que es relevante para los problemas que estás tratando de resolver y son de acceso gratuito porque son de la empresa. Con los datos internos, los analistas pueden trabajar en todos los proyectos de datos sin siquiera salir de sus cuatro paredes. Pero, a veces, los datos internos no proporcionan un panorama general. En esos casos, los analistas de datos pueden recurrir a datos externos y aplicar esa información a sus análisis. 

Por ejemplo, como analista del cuidado de la salud, a menudo nos asociamos con otras organizaciones de cuidados de la salud o con organizaciones sin fines de lucro, y usamos sus datos para brindar un análisis más profundo y agregar una perspectiva que esté más al nivel de la industria. En un video anterior, aprendiste que la apertura ha creado muchos datos para analizar, en gran medida a través de iniciativas de datos abiertos. Como recordatorio, apertura o datos abiertos se refiere al acceso, uso e intercambio libre de los datos. Por ejemplo, el gobierno de los Estados Unidos crea cientos de miles de conjuntos de datos que están disponibles para el público en Data.gov. Esos conjuntos de datos contienen información sobre patrones climáticos, progresos de la educación, tazas de delincuencia, transportes y mucho más. 

Hay muchas razones para que existan estas iniciativas de datos abiertos. Una es otorgarle más transparencia a las actividades del gobierno, como permitir que el público vea dónde se gasta el dinero. También ayuda a educar a los ciudadanos en relación con la votación y a problemas locales. Los datos abiertos también mejoran el servicio público, ya que les brindan a las personas formas para ser parte de la planificación pública o de proporcionar retroalimentación al gobierno. Para finalizar, los datos abiertos conducen a la innovación y al crecimiento económico, al ayudar a las personas y a las empresas a comprender mejor sus mercados. Google almacena un montón de bases de datos públicos que brindan información sobre ciencia, transporte, economía, el clima y mucho más. Como ejemplo, una empresa de bicicletas de uso compartido podría usar datos sobre el tráfico que se encuentran en nuestra base de datos sobre transporte público para ver si hay mucho tráfico en las calles. Luego, podría elegir esas ubicaciones para colocar sus bicicletas con el fin de reducir los automóviles que hay en la calle y brindarles a las personas otra opción de transporte. Ya estás familiarizado con los datos internos y externos y cómo acceder a ellos. A continuación, aprenderemos cómo importar todos los datos que has recopilado de diferentes fuentes en una hoja de cálculo.

### Importar datos desde hojas de cálculo y bases de datos 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

A esta altura, ya has aprendido todo sobre datos internos y externos, y cómo prepararlos para utilizarlos. Ahora comenzaremos el proceso de importación real de datos desde distintas fuentes. A veces quieres cargar una hoja de cálculo desde tus archivos, por ejemplo, un archivo CSV. CSV significa valores separados por coma. Un archivo CSV guarda datos en formato de tabla. Ahora traigamos ese archivo a una hoja de cálculo nueva.

Comenzaremos por seleccionar un archivo y, luego, lo importaremos.

![image](./img/module%3001%20img%3006.png)

A continuación, elegiremos cargar un archivo. Búscalo, ábrelo e insértalo como una hoja nueva.

![image](./img/module%3001%20img%3007.png)

Los archivos CSV usan texto normal y están delineados por caracteres. Así que cada columna o campo es muy diferente de la otra a la hora de importar. Como sabes, los archivos CSV están separados por comas y, en general, la aplicación de la hoja de cálculo detectará automáticamente esas separaciones. Sin embargo, a veces, puedes necesitar indicar que un separador es otro carácter o un espacio, y para ello seleccionas las distintas opciones en esta ventana.

![image](./img/module%3001%20img%3008.png)

Asimismo, si estás planificando trabajar con un conjunto de datos, en general, lo convertirías a texto, números u otras opciones desde aquí. Pero un texto normal está bien para los propósitos de un informe. Así que podemos dejar tranquilos esos campos. Finalmente, selecciona Importar datos.

Ahora nuestro archivo CSV está listo para funcionar en nuestra hoja de cálculo. Paso la mayor cantidad de tiempo en el trabajo analizando hojas de cálculo llenas de información sobre cuidados de la salud. En general, comienzo por buscar en un conjunto de datos más grande. Luego, extraigo un subconjunto a una hoja de cálculo para poder trabajar con él. Quizás quiero analizar el crecimiento año por año en la demanda de usuario en Google Search para ciertos servicios de cuidado de la salud, como telemedicina. O quizás quiero mirar conjuntos de datos de organizaciones o agencias externas sobre cuidados de la salud para obtener más información sobre esta tendencia. Por ejemplo, con telemedicina quizás observaría una hoja de cálculo que enumera los proveedores de telemedicina. Hay muchas formas en que las hojas de cálculo pueden ayudarte a encontrar la información que necesitas. Una fuente que utilizo mucho es el repositorio de datos de la Organización Mundial de la Salud.

En ese sitio cualquiera puede acceder a datos de fuente abierta. Como puedes ver, hay cientos de datos disponibles. Puedes buscar por tema, categoría, indicador y país. También puedes acceder a los metadatos de la Organización Mundial de la Salud si quieres aprender más sobre los datos en este repositorio.

![image](./img/module%3001%20img%3009.png)

Para nuestro ejemplo, buscaremos doctores por país y año.

![image](./img/module%3001%20img%3010.png)

Esa información será útil para un proyecto de análisis de datos que busque cuántos doctores están disponibles para tratar pacientes en una cierta población en comparación con otras poblaciones. Para obtener estos datos comenzaremos en esta página web, que contiene el conjunto de datos que queremos. Luego, descargaremos los datos como un archivo CSV.

Después, abriremos una hoja de cálculo nueva e importaremos el archivo seleccionando Archivo, Importar.

Luego, cargarás tu archivo y seleccionarás Importar datos.

Tras revisar los datos para asegurarte de que se vean limpios, podemos ponerles un título y comenzar a trabajar.

Sé que es demasiada información para recordar, pero te sentirás más cómodo a medida que vayas practicando. A continuación, aprenderemos cómo ordenar y filtrar tus datos para enfocarte en la información que te resulte pertinente.

![image](./img/module%3001%20img%3011.png)

### Explorar conjuntos de datos publicos 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-10%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Datos abiertos ayuda a crear muchos conjuntos de datos públicos a los que puedes acceder para tomar decisiones basadas en datos. Aquí hay algunos recursos que puedes utilizar para comenzar a buscar conjuntos de datos públicos por tu cuenta:

Los Conjuntos de datos públicos de Google Cloud permiten a los analistas de datos acceder a conjuntos de datos públicos de gran demanda y facilitan el descubrimiento de información en la nube. 
 
[Dataset Search](https://datasetsearch.research.google.com/) puede ayudarte a encontrar conjuntos de datos disponibles en línea mediante la búsqueda de palabras clave. 

[Kaggle](https://www.kaggle.com/datasets) tiene una función de búsqueda de Datos abiertos que puede ayudarte a encontrar conjuntos de datos para practicar.

Por último, [BigQuery](https://cloud.google.com/bigquery/public-data?hl=es-419) almacena más de 150 conjuntos de datos públicos a los que puedes acceder y utilizar. 

#### Conjuntos de datos públicos sobre salud

[Datos del Observatorio Mundial de la Salud](https://www.who.int/data/collections): Puedes buscar conjuntos de datos en esta página o explorar las colecciones de datos destacadas de la Organización Mundial de la Salud.  

[El conjunto de datos del Archivo de imágenes de cáncer (TCIA)](https://cloud.google.com/healthcare-api/docs/resources/public-datasets/tcia?hl=es-419): Al igual que el conjunto de datos anterior, estos datos están almacenados en los conjuntos de datos públicos de Google Cloud y puedes cargarlos a BigQuery.

[1000 genomas](https://cloud.google.com/life-sciences/docs/resources/public-datasets/1000-genomes?hl=es-419): Este es otro conjunto de datos de los recursos públicos de la Google Cloud que puedes cargar a BigQuery. 

#### Conjuntos de datos públicos sobre el clima

[Centro Nacional de Datos Climáticos](https://www.ncdc.noaa.gov/data-access/quick-links): La página de enlaces rápidos del Centro Nacional de Datos Climáticos (NCDC) tiene una selección de conjuntos de datos que puedes explorar. 

[Galería del conjunto de datos públicos de la Asociación Nacional de Asuntos Oceánicos y Atmosféricos](https://www.climate.gov/maps-data/datasets): La Galería del conjunto de datos públicos de la Asociación Nacional de Asuntos Oceánicos y Atmosféricos (NOAA) contiene una colección de conjuntos de datos que puedes consultar.

#### Conjuntos de datos públicos sobre política y sociedad

[El Estado de la infancia a nivel mundial de UNICEF](https://data.unicef.org/resources/dataset/sowc-2019-statistical-tables/): El conjunto de datos de UNICEF incluye una colección de tablas que puedes descargar.

[Estadísticas del mercado laboral de la Encuesta continua de población](https://www.bls.gov/cps/tables.htm): Esta página contiene enlaces hacia muchos conjuntos de datos disponibles que puedes explorar.

[El proyecto abierto sobre mantenimiento del orden en Stanford](https://openpolicing.stanford.edu/): Puedes descargar este conjunto de datos como un archivo .CSV para tu propio uso.


### Cuestionario práctico 📑

[![Tiempo](https://img.shields.io/badge/Tiempo-20%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Pon a prueba tus conocimientos sobre el acceso a las fuentes de datos.

1. Un archivo CSV guarda datos en formato de tabla. ¿Qué significa CSV?

    - Variables científicas compatibles
    
      ❌ Incorrecto.
  
    - Valores estimados de hojas de cálculo
    
      ❌ Incorrecto.
    
    - Valores separados por coma
    
      ✅ Correcto. CSV significa valores separados por coma.
      
    - Variables estructuradas por celdas
    
      ❌ Incorrecto.


2. Un analista de datos desea agregar datos de un archivo CSV a una hoja de cálculo. ¿Este es un ejemplo de qué proceso?

    - Importación de datos
    
      ✅ Correcto. Un analista de datos que agrega datos de un archivo CSV en una hoja de cálculo es un ejemplo de la importación de datos.
  
    - Archivado de datos
    
      ❌ Incorrecto.
    
    - Edición de datos
    
      ❌ Incorrecto.
      
    - Normalización de datos
    
      ❌ Incorrecto.


3. ¿Un archivo CSV les facilita a los analistas de datos completar qué tipo de tareas? Selecciona todas las opciones que correspondan.

    - Importar datos a una nueva hoja de cálculo
    
      ✅ Correcto. Un archivo CSV les facilita a los analistas de datos examinar una pequeña parte de un conjunto de datos grande, importar datos a una nueva hoja de cálculo y distinguir valores entre sí.
  
    - Examinar un pequeño subconjunto de un conjunto de datos grande
    
      ✅ Correcto. Un archivo CSV les facilita a los analistas de datos examinar una pequeña parte de un conjunto de datos grande, importar datos a una nueva hoja de cálculo y distinguir valores entre sí.
    
    - Gestionar varias pestañas en una hoja de cálculo
    
      ❌ Incorrecto.
      
    - Distinguir valores entre sí
    
      ✅ Correcto. Un archivo CSV les facilita a los analistas de datos examinar una pequeña parte de un conjunto de datos grande, importar datos a una nueva hoja de cálculo y distinguir valores entre sí.

---

## 4. Ordenar y filtrar 📚

### Temario: 

- Ordenar y filtrar (Vídeo - 5 min)
- Actividades prácticas: Limpia los datos en hojas de cálculo con la ordenación y el filtrado (Cuestionario práctico - 1 pregunta)
- Autorreflexión: Teniendo en cuenta las bases de datos y las hojas de cálculo para la ordenación y el filtrado (Cuestionario práctico - 1 pregunta)
- Pon a prueba tus conocimientos sobre ordenación y filtrado (Cuestionario práctico - 4 preguntas)

### Ordenar y filtrar 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-5%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

En los videos anteriores, aprendiste sobre datos internos y externos. Ahora te mostraré cómo enfocarte solamente en los datos que son pertinentes para el problema que tratas de resolver. Esto es útil si estás trabajando con una hoja de cálculo compleja y extensa, algo muy común para los analistas de datos. Tener muchos datos puede dificultar la búsqueda y el análisis de la información que necesitas. No hay dos proyectos de análisis iguales. A menudo, los analistas de datos procesan, ven y usan los datos de maneras muy diferentes, incluso si vienen de la misma fuente. Aquí hay un ejemplo. Analiza esta hoja de cálculo que muestra los representantes de ventas de una empresa y dónde trabajan. Distintos analistas de datos pueden querer información diferente de esta hoja de cálculo, y ahí es donde aparece la ordenación y el filtrado. Ordenar y filtrar los datos en una hoja de cálculo nos ayuda a personalizar la forma en que se presentan los datos. También pueden organizar datos para que los analistas puedan acercar los datos que son importantes. Piensa que son una lupa de nuestros datos. Comencemos con la ordenación. Ordenar significa organizar los datos en un orden significativo para que sea más fácil comprenderlos, analizarlos y visualizarlos. Los datos pueden organizarse en orden ascendente o descendente, alfabético o numérico. La ordenación puede realizarse en toda la hoja de cálculo o solo en una columna o en una tabla. También puedes clasificar según múltiples variables. Por ejemplo, si nuestro conjunto de datos contiene campos de ciudad y estado, podemos ordenarlos primero por ciudad y luego por estado.

Cuando ordenas datos, siempre es mejor inmovilizar la fila del encabezado primero. Para hacer esto, destacaremos la fila. Luego, en el menú Ver, selecciona inmovilizar y una fila.

Esto inmoviliza la fila en ese lugar. Ahora cuando desplacemos el cursor hacia abajo en la hoja de cálculo, la fila del encabezado seguirá visible y así sabremos la categoría de cada columna.

Me parece bien. Ahora ordenemos toda la hoja de cálculo. Primero la ordenaremos por ciudad. Para hacer esto, selecciona la columna ciudad,

luego, utiliza la flecha desplegable hacia abajo para ordenar la hoja. Selecciona A a Z.

Todas las columnas se ordenarán de la A a la Z por fila, y la columna seleccionada será el criterio principal de ordenación. Ahora las ciudades están ordenadas alfabéticamente y siguen agrupadas con sus respectivos estados, representantes de ventas y auto partes. Los detalles de cada fila se mantienen juntos automáticamente cuando se ordena una selección particular, como puedes ver aquí. La ordenación de varios criterios es otra herramienta muy útil del análisis de datos. Por ejemplo, digamos que queremos ver una lista de representantes de ventas en base a las ciudades y a los estados en los que trabajan. Primero, seleccionamos todo el conjunto de datos, luego elegimos los datos y el rango de clasificación.

En el cuadro de diálogo, asegúrate de que “Los datos tienen fila de encabezado” esté destacado. De esa forma, la fila A, ciudad, estados, representante de ventas y auto partes no formarán parte de la ordenación.

Luego, en la ordenación mediante el menú desplegable, selecciona el estado y, luego, el criterio para la ordenación de la A a la Z. Ahora agrega otra columna para ordenar. En el desplegable “luego por”, selecciona ciudad y el criterio para la ordenación de la A a la Z.

Finalmente, selecciona Ordenar. Ahora podemos buscar los datos y encontrar fácilmente un representante de ventas que trabaje en un estado y en una ciudad particular. La ordenación es útil cuando quieres ver todo en orden alfabético o numérico en una hoja de cálculo. Pero, a veces, los analistas de datos quieren aislar un dato en particular. Para hacer eso, utilizan un filtro. Filtrar significa mostrar solamente los datos que cumplen con un criterio específico mientras se esconde el resto. Un filtro simplifica una hoja de cálculo al mostrar solamente la información que necesitamos. Por ejemplo, podemos agregar un filtro para ver solo los representantes de ventas que trabajaron con un producto en particular. Para hacer eso, primero seleccionamos Datos y Crear un filtro. Elige la columna con los datos que necesitamos. En este caso, Auto Partes. Aparecerán botones de filtrado en la esquina de cada encabezado de columna. Para filtrar nuestra hoja de cálculo por auto parte, haz clic en el botón del encabezado de Auto Partes. En este ejemplo, digamos que queremos ver solamente los representantes de ventas que trabajaron con llantas. Quita las marcas de verificación de las categorías que no queremos ver, que son todas excepto las de las llantas.

Luego selecciona Aceptar. El filtro esconde momentáneamente todo lo que no cumple con la condición. Pero ten en cuenta que, aunque no están visibles, aún están allí. Cuando sea el momento de ver toda el área de la hoja de cálculo de nuevo, simplemente desactiva el filtro.

Ordenar y filtrar datos son herramientas muy importantes de la caja de herramientas de un analista de datos. En el siguiente video descubrirás más formas de acotar la búsqueda a la información exacta que necesitas para cualquier proyecto de análisis de datos.

### Actividades prácticas: Limpia los datos en hojas de cálculo con la ordenación y el filtrado 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-60%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

### Resumen de la actividad

Por el momento, ya conoces cómo limpiar datos en las hojas de cálculo, además de las destrezas de la hoja de cálculo principal como por ejemplo la ordenación y el filtrado. En esta actividad, utilizarás la ordenación y el filtrado para limpiar un conjunto de datos sucio.

La limpieza de datos corrige o elimina los datos incorrectos, faltantes o erróneos. La limpieza de datos es de suma importancia porque un análisis basado en datos sucios puede originar conclusiones incorrectas y malas decisiones. Cuanto más limpios estén tus datos, mejores resultados obtendrás.

Para esta actividad, imagínate que eres analista de datos y que trabajas para el supervisor de un gran distrito escolar público de Portugal. El supervisor desea saber qué factores afectan a las calificaciones de los estudiantes en las materias principales y qué cambios se pueden realizar para mejorar el desempeño de los estudiantes. Tu equipo va a analizar los datos de desempeño en relación con los logros de estudiantes de escuelas secundarias de dos escuelas públicas de Portugal: Gabriel Pereira (GP) y Mousinho da Silveira (MS). El distrito escolar recopiló los datos mediante informes académicos y encuestas a los estudiantes. Los datos incluyen la siguiente información:

- Calificaciones de los estudiantes.

- Información sobre los antecedentes de los estudiantes.

- Tiempo de estudio de los estudiantes.

- Participación de los estudiantes en actividades extracurriculares.

No obstante, antes de analizar los datos, es importante asegurarse de que estos estén limpios. Analizar datos incorrectos o sucios podría hacer que el distrito escolar llegue a conclusiones incorrectas e implemente cambios ineficaces. Tu tarea es ayudar a limpiar los datos.

Cuando finalices esta actividad, podrás ordenar los datos de distintas maneras, aplicar filtros para eliminar los datos incorrectos, completar los datos faltantes y convertir datos de texto en formato numérico. Limpiar los datos es una fase fundamental del proceso de análisis de datos. La ordenación y el filtrado son técnicas útiles para limpiar los datos y, además, son destrezas clave a las que recurrirás a lo largo de tu carrera como analista de datos.

### Limpia tus datos

Es importante asegurarse de que los datos estén limpios para que tu eventual análisis sea correcto. Lo primero que hay que hacer es revisar los valores en las columnas más importantes para tu análisis y averiguar si hay algo que se deba limpiar. En este ejemplo, el principal objetivo del supervisor es determinar qué factores impulsan el desempeño del estudiante. Para comenzar a responder esta pregunta, las columnas en las que deseas centrarte en primer lugar son escuela, edad, motivo, Medu, Fedu. Puedes utilizar la ordenación y el filtrado para limpiar los datos en cada una de estas columnas. 

![image](./img/module%3001%20img%3012.png)

#### Ordenación de los datos

Debido a que cuentas con datos de dos escuelas, Gabriel Pereira (GP) y Mousinho da Silveira (MS), puedes comenzar ordenando los datos por escuela. Luego, puedes ordenarlos por edad para descubrir los rangos etarios de los estudiantes para cada escuela. Ordenar implica organizar los datos en un orden significativo para que sea más fácil entenderlos, analizarlos y visualizarlos.

1. Primero, cámbiale el nombre a tu hoja de cálculo. En la esquina superior izquierda, haz clic en Hoja de cálculo sin nombre y escribe un nombre nuevo. Puedes usar el nombre student_performance_datau otro similar que describa los datos que contiene la hoja de cálculo.

2. Ahora, ordena por escuela. Debido a que quieres ordenar varias columnas, debes seleccionar todos los datos de tu hoja de cálculo. Haz clic en el rectángulo negro arriba de la fila 1 y a la izquierda de la columna A. Esto te permitirá seleccionar todos los datos en tu hoja. 

![image](./img/module%3001%20img%3013.png)

3. Luego, en la barra de menús, selecciona Datos,luego Ordenar rango. (Nota: Para algunas versiones de Google Sheets, la selección de Opciones avanzadas de ordenación de rango puede aparecer en el menú desplegable Datos en lugar de Ordenar rango). 

![image](./img/module%3001%20img%3014.png)

4. En la ventana emergente, selecciona Los datos tienen una fila de encabezado. Ahora puede elegir encabezados de columna específicos para ordenar.

![image](./img/module%3001%20img%3015.png)

5. En el menú desplegable Ordenar por, elije el encabezado escuela.Luego, haz clic en A → Z para ordenar en orden ascendente.

![image](./img/module%3001%20img%3016.png)

6. También deseas ordenar por edad. Antes de poder ordenar por edad, debes hacer clic en Agregar otra columna para ordenar para elegir un encabezado de la segunda columna.

7. En el menú desplegable Ordenar por,elije el encabezado edad.Esta vez, haz clic en Z → A para ordenar en orden descendente. De esta manera, los estudiantes mayores aparecerán primero.

![image](./img/module%3001%20img%3017.png)

8. Una vez realizadas ambas selecciones, haz clic en Ordenar.

![image](./img/module%3001%20img%3018.png)

Ahora, si te desplazas por los datos, observarás que el rango etario de los estudiantes en Gabriel Pereira (GP) es entre 15 y 22 años, y el rango etario en Mousinho da Silveira (MS) es entre 15 y 20 años. Parece que ambas escuelas tienen rangos etarios similares, pero la escuela GP tiene estudiantes que son un poco mayores. 

![image](./img/module%3001%20img%3019.png)

![image](./img/module%3001%20img%3020.png)

![image](./img/module%3001%20img%3021.png)

![image](./img/module%3001%20img%3022.png)

![image](./img/module%3001%20img%3023.png)

![image](./img/module%3001%20img%3024.png)

Al ordenar los datos, descubriste un posible problema con ellos. Debido a que este conjunto de datos representa el logro del estudiante de la escuela secundaria, toda edad mayor que 18 puede indicar que se cometió un error al escribir la edad del estudiante. Ahora sabes qué datos etarios posiblemente deban investigarse y corregirse. El próximo paso es el de preguntarle al supervisor sobre el rango etario legítimo para los estudiantes en la escuela secundaria pública. Luego, sabrás qué datos etarios son incorrectos y deberán eliminarse. 

#### Eliminación de datos incorrectos

El supervisor te comenta que el límite etario máximo para el que se proporciona educación pública es de 19 años y que el rango etario debe ser entre 15 y 19 años para ambas escuelas. Todo estudiante que no corresponda a este rango etario deberá eliminarse del conjunto de datos.

Para limpiar los datos, deberás eliminar las edades 20, 21 y 22 de tu conjunto de datos. Puedes comenzar aplicando un filtro en la columna edad. El filtradoes el proceso que muestra solo los datos que cumplen con un criterio específico mientras oculta el resto. El filtrado facilita la búsqueda de los datos que necesitas.

1. Primero, aplica un filtro en la columna edad. Selecciona la columna edadhaciendo clic en la letra de la parte superior de la columna (C).

![image](./img/module%3001%20img%3025.png)

2. Luego, desde la barra de menús, selecciona Datos, luego Crear un filtro.

3. Ahora puedes inspeccionar los valores en la columna edadsi vas a la parte superior de la columna y haces clic en el ícono Filtro ().

4. En Google Sheets, hay nueve valores posibles para el campo (15, 16, 17, 18, 19, 20, 21 y 22). Es posible que notes que todos los valores tienen marcas de comprobación. Filtra esta columna para los valores que deseas seleccionar desactivando todos los demás valores (15, 16, 17, 18 y 19). 

6. Para eliminar las nueve filas, primero selecciónalas haciendo clic en los números de fila.

5. Luego, haz clic en Aceptar. Esto separará las filas que contienen las edades 20, 21 y 22. Luego de aplicar el filtro, debe haber nueve filas de ese tipo (siete para la escuela GP y dos para la escuela MS). 

7. Luego, desde la barra de menús, selecciona Editary Eliminar filas seleccionadas.

![image](./img/module%3001%20img%3026.png)

8. Haz clic en el ícono Filtro en la parte superior de la columna edadpara inspeccionar los valores nuevamente. Ahora que eliminaste las tres edades incorrectas (20, 21 y 22), hay cinco edades restantes (15, 16, 17, 18 y 19). Las edades restantes son legítimas y se pueden utilizar para el análisis.

![image](./img/module%3001%20img%3027.png)

9. Por último, desactiva el filtro. Desde la barra de menús, elije Datosy Desactivar filtro.

#### Completar los datos faltantes

Completar los datos faltantes es una parte importante de la limpieza de datos. Debes encargarte de completar los espacios en blanco de tus datos con valores precisos.

El supervisor desea conocer los factores que influyen en el desempeño del estudiante y para realizar el análisis será importante saber el motivo por el que el estudiante elige una escuela específica. La columna motivo muestra el motivo principal por el que el estudiante elige inscribirse en una escuela específica, según la respuesta de la encuesta; por ejemplo, debido a la reputación de la escuela, o porque ofrece ciertos cursos, etc. Por ende, debes asegurarte de que la columna motivo esté completa y sin espacios en blanco.

1. Comienza aplicando un filtro en toda la hoja de cálculo. Haz clic en cualquier celda de la hoja. Luego, desde la barra de menús, selecciona Datosy Crear un filtro.

2. Todas las celdas aparecen ahora resaltadas y hay filtros en la parte superior de cada columna que contiene datos. Haz clic en el ícono Filtro en la columna motivo (K).

3. Es posible que adviertas que los valores de los datos en la columna motivoincluyen espacios en blanco. Filtra esta columna para los espacios en blanco desactivando todos los demás valores (curso, casa, reputación). 

![image](./img/module%3001%20img%3028.png)

4. Luego, haz clic en Aceptar. Ahora, tu hoja muestra todas las filas en blanco en la columna motivo.

5. Para limpiar los datos, deberás buscar una buena manera de completar los valores faltantes. En este caso, no puedes saber cuál debería ser cada valor faltante (es decir, sin una nueva encuesta, no puedes descubrir el motivo por el cual cada estudiante eligió una escuela específica). Por ende, puedes reemplazar los valores faltantes con el valor none_given. Para hacer esto mientras la columna todavía está filtrada para los espacios en blanco, escribe none_givenen la primera celda vacía (K2). Luego, presiona Enter. 

![image](./img/module%3001%20img%3029.png)

6. Selecciona nuevamente la celda K2. Aparecerá un pequeño cuadrado azul, conocido como controlador de relleno, en la esquina inferior derecha de la celda. Haz doble clic en el controlador de relleno para completar todas las demás celdas en blanco con el valor none_given.

![image](./img/module%3001%20img%3030.png)

7. Por último, desactiva el filtro. Desde la barra de menús, elije Datosy Desactivar filtro. Si te desplazas hacia abajo en la columna motivo, verás que el valor none_given ha reemplazado todos los espacios en blanco en la columna motivo.

#### Conversión de los datos

Durante el proceso de análisis de datos, a veces es necesario cambiar los datos del texto (palabras) por datos numéricos (números). Por ejemplo, algunos paquetes estadísticos como los que se utilizan para realizar el aprendizaje automático solo aceptarán valores de datos numéricos como entrada.

En este caso, el supervisor desea conocer si el nivel de educación de los padres es un factor significativo en el desempeño del estudiante. Los datos relevantes son las columnas Medu y Fedu;que, respectivamente, se refieren al nivel de educación de la madre y el padre del estudiante. Actualmente, los datos se encuentran en formato de texto. Para los propósitos del análisis, será útil conocer el nivel de educación promedio de los padres de cada estudiante. Para realizar este cálculo, primero debes convertir los datos en las columnas Meduy Fedual formato numérico.

Para hacer esto, puedes hacer coincidir los valores de números específicos con los datos de texto en cada columna. Comienza con la columna Medu. Si haces clic en el ícono Filtro en la parte superior de la columna Medu (G), verás que la columna contiene los datos de texto que se muestran en la siguiente tabla. Puedes utilizar los siguientes códigos numéricos para cada uno de los datos de texto: 

![image](./img/module%3001%20img%3031.png)

1. Para comenzar, elimina el filtro de la columna Medu.

2. Luego, selecciona los datos de la columna Medu sin filtro haciendo clic en la letra de su columna (G).

3. Luego, desde la barra de menús, selecciona Editary, luego, Buscar y reemplazar.

![image](./img/module%3001%20img%3032.png)

4. Completa la ventana emergente para el valor ninguno. Luego de Buscar, escribe ninguno. Luego de Reemplazar por, escribe 0. Marca la casilla al lado de Hacer coincidir todo el contenido de la celda.

5. Luego, haz clic en Reemplazar todo.

![image](./img/module%3001%20img%3033.png)

6. Estando en la ventana emergente, repite este proceso (pasos 4-5) para los otros cuatro niveles de educación: educación primaria (4º grado), de 5º a 9º grado, educación secundaria y educación superior.

- 5th to 9th grade

![image](./img/module%3001%20img%3033.png)

- secondary education

![image](./img/module%3001%20img%3034.png)

- higher education

- primary education (4th grade)

![image](./img/module%3001%20img%3036.png)

7. Luego de reemplazar los cinco niveles de educación por los valores numéricos, haz clic en Listo para cerrar la ventana emergente.

8. Analiza tu hoja de cálculo. Todas las celdas en la columna Medu ahora muestran valores numéricos.

9. Cambia los datos de texto en la columna Fedu (H) del mismo modo. 

### Confirmación y reflexión

¿Cómo se denomina el proceso que muestra solo los datos que cumplen con un criterio específico mientras oculta el resto?

    - Filtrado
    
      ✅ Correcto. El filtrado es el proceso que muestra solo los datos que cumplen con un criterio específico mientras oculta el resto. El filtrado es una técnica extremadamente útil para la limpieza de los datos y es una herramienta esencial del kit de herramientas del analista de datos. 
  
    - Inspeccionar
    
      ❌ Incorrecto.
    
    - Ordenación
    
      ❌ Incorrecto.
      
    - Conversión
    
      ❌ Incorrecto.

### Autorreflexión: Teniendo en cuenta las bases de datos y las hojas de cálculo para la ordenación y el filtrado 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-30%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

#### Descripción general

Ahora que ya has ordenado y filtrado los datos en una hoja de cálculo y te hemos presentado las bases de datos, puedes hacer una pausa y pensar acerca de lo que aprendiste. En esta autorreflexión, considerarás tus ideas sobre las hojas de cálculo y las bases de datos y, luego, responderás unas breves preguntas.

Esta autorreflexión te ayudará a desarrollar conceptos sobre tu propio aprendizaje y te preparará para aplicar tus conocimientos sobre la preparación de los datos a tus situaciones del mundo real. A medida que respondas las preguntas, y plantees tus propias preguntas, tendrás en cuenta los conceptos, las prácticas y los principios que te ayudarán a refinar tu comprensión y reforzar tu aprendizaje. Ya hiciste el trabajo arduo, así que asegúrate de sacarle el máximo provecho: ¡Esta reflexión te ayudará a fijar tus conocimientos!

#### Comparar y contrastar

Piensa en todo lo que has aprendido sobre las hojas de cálculo y las bases de datos. De muchas formas, son similares. De otras formas, son diferentes.

Por ejemplo, ambas hojas de cálculo y bases de datos almacenan y organizan los datos. No obstante, las bases de datos pueden ser relacionales mientras que las hojas de cálculo no. Esto significa que las hojas de cálculo son más adecuadas para datos autocontenidos, donde los datos existen en un lugar. Mientras tanto, puedes utilizar bases de datos para almacenar datos de tablas externas, lo que te permite cambiar los datos de varios lugares realizando la edición en un solo lugar.

Tómate un momento para considerar estos ejemplos y crea algunos propios. Aquí hay algunas áreas que posiblemente desees tener en cuenta:

- ¿Cómo almacenan los datos?

- ¿Cómo se utilizan para interactuar con los datos?

- ¿Cuán poderosa es cada una?

- ¿Cuáles son los pros y los contras de cuando se realiza la ordenación?

- ¿Cuáles son los pros y los contras de cuando se realiza el filtrado?

A medida que consideras cada una de estas preguntas, deberás compilarlas en una tabla simple. Puedes utilizar lápiz y papel o tu software de hoja de cálculo preferido. Agrega la pregunta a la izquierda, y compara y contrasta las hojas de cálculo y las bases de datos a la derecha. Tu tabla puede ser similar a la siguiente:

![image](./img/module%3001%20img%3037.png)

Utiliza tu tabla para comparar y contrastar. Una vez que finalices, responde las preguntas sobre reflexión a continuación.

#### Reflexión

Ten en cuenta lo que aprendiste mientras comparas y contrastas las hojas de cálculo y las bases de datos en esta reflexión:

- ¿Qué similitudes has notado entre las hojas de cálculo y las bases de datos? ¿Qué diferencias has notado?

- Piensa en qué se siente al aprender cada tema. ¿Uno fue más fácil o más difícil que el otro? De ser así, ¿por qué crees que fue?

Ahora, escribe 2 o 3 oraciones (de 40 a 60 palabras) en respuesta a cada una de estas preguntas. Escribe tu respuesta en el cuadro de texto que aparece a continuación.

#### Desarrollo

Almacenamiento de datos:
Las hojas de cálculo almacenan datos en celdas organizadas en filas y columnas, permitiendo una estructura tabular flexible. Las bases de datos utilizan tablas relacionadas para almacenar datos de manera más eficiente, manteniendo la integridad y la consistencia mediante claves primarias y foráneas.

Interacción con datos:
Las hojas de cálculo ofrecen fórmulas y funciones para realizar cálculos y análisis. Las bases de datos permiten consultas SQL avanzadas, relaciones entre tablas y procedimientos almacenados, facilitando la gestión y manipulación de grandes conjuntos de datos de manera eficiente.

Potencia:
Las bases de datos son más potentes para gestionar grandes volúmenes de datos y garantizar la integridad. Las hojas de cálculo son adecuadas para análisis rápidos y cálculos simples, pero pueden volverse limitadas en términos de escalabilidad y control de acceso.

Ordenación:
La ordenación en hojas de cálculo facilita la visualización de datos, pero puede ser manual y consumir tiempo. En las bases de datos, la ordenación se realiza de manera más eficiente mediante consultas SQL, pero puede ser más compleja de implementar.

Filtrado:
El filtrado en hojas de cálculo es intuitivo y rápido, pero puede carecer de flexibilidad en comparación con las consultas de bases de datos. En bases de datos, el filtrado se realiza con mayor precisión mediante condiciones complejas, pero puede requerir conocimientos de SQL.

Similitudes:
Ambas hojas de cálculo y bases de datos permiten organizar datos en tablas, realizar cálculos y análisis, y ofrecen funciones de búsqueda. Ambas también son herramientas esenciales para la gestión de información en entornos profesionales.

Diferencias:
Las bases de datos son más robustas para el manejo de grandes conjuntos de datos, garantizando la integridad y permitiendo consultas complejas. Las hojas de cálculo son más simples y accesibles para análisis rápidos pero pueden carecer de la estructura y seguridad de las bases de datos.

### Cuestionario práctico 📑

[![Tiempo](https://img.shields.io/badge/Tiempo-20%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Pon a prueba tus conocimientos sobre ordenación y filtrado.

1. ¿Cuál es el proceso de organizar los datos en un sistema de clasificación significativo para que sea más fácil entenderlos, analizarlos y visualizarlos?

    - Capacidad para priorizar
    
      ❌ Incorrecto.
  
    - Reformulación
    
      ❌ Incorrecto.
    
    - Filtrado
    
      ❌ Incorrecto.
      
    - Ordenación
    
      ✅ Correcto. La ordenación es el proceso de organizar los datos en un orden significativo para que sea más fácil entenderlos, analizarlos y visualizarlos.


2. Una analista de datos revisa una base de datos nacional de las ventas de inmobiliaria. Solo le interesan las ventas de los condominios. ¿Cómo puede el analista acotar su alcance?

    - Ordenar por ventas no relacionadas con los condominios
    
      ❌ Incorrecto.
  
    - Ordenar por ventas de condominios
    
      ❌ Incorrecto.
    
    - Filtrar por ventas no relacionadas con condominios
    
      ✅ Correcto. El analista puede acotar su alcance filtrando las ventas que no están relacionadas con los condominios. Esto le permitirá ver solo los datos sobre las ventas de condominios.
      
    - Filtrar las ventas de condominios
    
      ❌ Incorrecto.


3. Un analista de datos trabaja para una empresa de alquiler de automóviles. Tiene una hoja de cálculo que enumera los números de ID y las fechas en las que se devolvieron los automóviles. ¿Cómo puede ordenar la hoja de cálculo para buscar los automóviles devueltos recientemente?

    - Por el ID numérico del vehículo, en orden ascendente.
    
      ❌ Incorrecto.
  
    - Por el ID numérico del vehículo, en orden descendente.
    
      ❌ Incorrecto.
    
    - Por la fecha de devolución, en orden ascendente.
    
      ❌ Incorrecto.
      
    - Por la fecha de devolución, en orden descendente.
    
      ✅ Correcto. Para ordenar la hoja de cálculo para buscar los automóviles devueltos más recientemente, deberá ordenar por fecha de devolución, en orden descendente.


4. Completa el espacio en blanco: Para mantener una fila de encabezado en la parte superior de una hoja de cálculo, destaca la fila y selecciona _____ desde el menú Ver.

    - Anclar
    
      ❌ Incorrecto.
  
    - Inmovilizar
    
      ✅ Correcto. Para mantener una fila de encabezado en la parte superior de una hoja de cálculo, destaca la fila y selecciona Inmovilizar desde el menú Ver.
    
    - Bloquear
    
      ❌ Incorrecto.
      
    - Configurar
    
      ❌ Incorrecto.

---

## 5. Trabajar con conjuntos de datos grandes en SQL ⚙️ 

### Temario: 

- Configurar BigQuery, incluso el espacio aislado y las opciones de facturación (Vídeo - 3 min)
- Cómo utilizar BigQuery (Vídeo - 4 min)
- BigQuery en acción (Vídeo - 6 min)
- Utilizar BigQuery (Lectura - 10 min)
- Actividades prácticas: Introducción a BigQuery (Cuestionario práctico - 2 preguntas)
- Actividades prácticas: Crea una tabla de datos personalizada en BigQuery (Cuestionario práctico - 1 pregunta)
- Guia detallada prácticas recomendadas en SQL (Lectura - 10 min)
- Actividades prácticas: Aplicar SQL (Cuestionario práctico - 2 preguntas)
- Pon a prueba tus conocimientos sobre el uso de SQL con conjuntos de datos grandes (Cuestionario práctico - 4 preguntas)

### Configurar BigQuery, incluso el espacio aislado y las opciones de facturación 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-3%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Hola. Bienvenido de nuevo. A lo largo de este curso, has aprendido que puedes usar BigQuery para ver y analizar datos de muchísimas fuentes distintas. Ahora vamos a explorar los distintos tipos de cuenta que ofrece BigQuery, de modo que puedas elegir la correcta según tus necesidades y sepas cómo acceder a ellas. Puedes usar BigQuery de forma gratuita. Si bien también tiene opciones pagas, no las necesitas para las actividades de este curso. Así que vamos a hablar de dos tipos de cuentas: de espacio aislado o **sandbox** y de prueba gratuita. La cuenta de espacio aislado está disponible gratis y cualquier persona con una cuenta de Google puede iniciar sesión y usarla. Sin embargo, tiene algunas limitaciones. 

Por ejemplo, puedes hacer hasta 12 proyectos por vez. Esto significa que si quieres hacer el proyecto número 13, tendrás que eliminar uno de los 12 que ya tienes. Tampoco te permite insertar nuevos registros a la base de datos ni actualizar el valor de los campos de los registros existentes. Sandbox no admite este tipo de lenguaje de manipulación de datos, estas operaciones no son compatibles. Sin embargo, sí tendrás que hacer esto en las actividades del curso. Para más información sobre las limitaciones de una cuenta de espacio aislado, consulta la documentación de BigQuery. Este es el tipo de cuenta que más usaremos para nuestras actividades. Es fácil de configurar. Así que, más adelante en este video, repasaremos los pasos que tienes que seguir para crear una cuenta. Antes de eso, deberíamos hablar un poco sobre la otra forma de usar BigQuery sin pagar nada. La prueba gratuita de Google Cloud. La prueba gratuita te brinda acceso a más funciones que BigQuery tiene para ofrecer, y las limitaciones son menores. La prueba gratuita ofrece $300 de crédito para usar en Google Cloud durante los primeros 90 días. Y no alcanzarás ni por asomo ese límite de crédito si solo usas la consola de BigQuery para practicar las consultas de SQL. Cuando gastes los $300 de crédito o pasen los 90 días, finalizará tu prueba gratuita y tú mismo deberás elegir si quieres suscribirte a una cuenta paga y seguir trabajando en Google Cloud. No recibirás cargos automáticos en el método de pago que hayas elegido una vez que finalice la prueba gratuita, aunque para registrarte sí debes configurar una opción de pago en Google Cloud. 

![image](./img/module%3001%20img%3038.png)

Entonces, a menos que elijas suscribirte a BigQuery, no deberás pagar nada. Pero sí debes ingresar algún tipo de pago al principio. Por eso, entendemos si no te sientes del todo cómodo con esta opción. Esta es una de las razones por las que existe la cuenta de espacio aislado en BigQuery: para que no tengas que ingresar ninguna información de pago. Con cualquiera de las dos cuentas, puedes suscribirte a una cuenta paga en el momento que quieras y seguir teniendo tus proyectos existentes. Así que, si configuras una cuenta gratuita pero no quieres suscribirte a una paga cuando finaliza el período de prueba, puedes configurar una cuenta de espacio aislado gratuita cuando quieras. Pero ten en cuenta que los proyectos de la prueba gratuita no se transferirán al espacio aislado. Sería como empezar de cero otra vez. Es algo para tener en cuenta. Ahora, vamos a configurar tu cuenta de espacio aislado, que puedes modificar a prueba gratuita o a cuenta paga si así lo deseas. Primero, vamos a la página de documentación de la cuenta de espacio aislado de BigQuery. Luego, en la esquina superior derecha iniciamos sesión en la cuenta de Google que queramos usar para la cuenta de espacio aislado de BigQuery. Después, hacemos clic en "Ir a BigQuery" de la página de documentación. Allí, tenemos un menú desplegable para seleccionar el país y leer los términos y condiciones del acuerdo de servicio. Es entonces que podremos ingresar al espacio de trabajo de SQL, que vamos a usar en las próximas actividades. Elige "Crear proyecto", ponle un nombre al proyecto y elige una identificación. Haz clic en "Crear" y, luego, en "Listo". Ya está. En el próximo video, exploraremos para qué sirve cada parte del espacio de trabajo de SQL y cómo lo usaremos en las actividades futuras. Nos vemos ahí.

![image](./img/module%3001%20img%3039.png)

### Cómo utilizar BigQuery 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-4%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

¡Hola! En este video, vamos a aprender sobre cada parte del espacio de trabajo SQL de BigQuery para que puedas usarlo durante este curso y a lo largo de tu carrera como analista de datos. Es una herramienta sumamente valiosa y muy popular, así que es muy útil entender cómo funciona. Siéntete libre de seguirlo en tu pantalla a medida que exploramos BigQuery. Notarás que mi pantalla se ve un poco diferente a la tuya, ya que BigQuery actualiza constantemente su interfaz. No te preocupes si pasa eso, ya que las pequeñas diferencias no te impedirán comprender los conceptos básicos. Para empezar, ve a la página de destino de BigQuery, luego inicia sesión en la cuenta que creaste anteriormente. 

![image](./img/module%3001%20img%3039.png)

![image](./img/module%3001%20img%3040.png)

![image](./img/module%3001%20img%3041.png)

![image](./img/module%3001%20img%3042.png)

![image](./img/module%3001%20img%3043.png)

![image](./img/module%3001%20img%3044.png)

![image](./img/module%3001%20img%3046.png)

![image](./img/module%3001%20img%3047.png)

![image](./img/module%3001%20img%3048.png)

Para navegar en el espacio de trabajo SQL, selecciona el menú del lado izquierdo de la pantalla y deslízate hasta el encabezado ''Macrodatos''. Luego, pasa el mouse por encima de la etiqueta BigQuery y haz clic en ''Espacio de trabajo SQL'', en el menú desplegable. Ahora que ya estamos en el espacio de trabajo SQL, vamos a buscar conjuntos de datos públicos, seleccionar un conjunto de datos a través del Explorador de datos, ejecutar una consulta y cargar nuestros propios datos para consultar. Primero, vamos a buscar un conjunto de datos públicos para usar. Para seleccionar un conjunto de datos públicos, navega hasta el menú del Explorador, en el lado izquierdo de la pantalla. Haz clic en el botón "Agregar datos", en la parte superior derecha del menú. Luego, en el menú desplegable, selecciona "Explorar conjuntos de datos públicos". Esto abrirá el marketplace y te mostrará los conjuntos de datos públicos disponibles. Vayamos a la barra de búsqueda de marketplace y busca “noaa_lightning”, el conjunto de datos que usaremos en la próxima actividad. Haz clic en el conjunto de datos "Cloud-to-Ground Lightning Strikes". Esto nos traerá una descripción y una vista previa del conjunto de datos que captura observaciones sobre la actividad de rayos y los patrones meteorológicos en los Estados Unidos. Haz clic en "Ver conjunto de datos". Esto te hará volver al espacio de trabajo SQL y creará una pestaña para el conjunto de datos. Luego, podemos volver a la pestaña del Editor que hemos abierto, o hacer clic en "Componer consulta nueva" para empezar a escribir con SQL. Observa a la izquierda y verás que la lista desplegable de datos públicos de BigQuery está en el menú del Explorador. Podemos hacer clic en la flecha para ampliar la lista de datos de BigQuery y seleccionar un nuevo conjunto de datos. Vamos a seleccionar el primer conjunto de datos, "austin_311", en la lista desplegable. Cuando lo hagamos, se ampliará para mostrar la tabla en el conjunto de datos. Podemos abrir el conjunto de datos para obtener una vista previa. La pestaña Esquema contiene los nombres de cada columna en el conjunto de datos. La pestaña Detalles contiene metadatos adicionales, como la fecha de creación del conjunto de datos. La pestaña Vista previa contiene las primeras filas en el conjunto de datos. En esta página, podemos hacer clic en "Consultar" para crear automáticamente una nueva ventana de editor con la plantilla para una consulta ya completada. A partir de aquí, pon un asterisco después de Select, donde aparece nuestro cursor, luego, ejecuta la consulta. Felicitaciones, ejecutaste una consulta de SQL en BigQuery. La consulta que ejecutaste arrojó filas en el conjunto de datos que se completan en una ventana debajo de la interfaz de editor. Aquí también se visualizarán los resultados de cualquier consulta que ejecutes. Digamos que ya tienes los resultados de una consulta que quieres cargar a BigQuery y analizar usando SQL. Para agregar tus propios datos a BigQuery, elige el ID del proyecto que quieres agregar. Selecciona el ícono de los tres puntos verticales para abrir las opciones del proyecto, luego elige "Crear conjunto de datos". Dale un nombre al conjunto de datos que te ayude a identificarlo, más adelante, por ejemplo, "upload_test_dataset". Luego haz clic en "Crear conjunto de datos". A continuación, ve al menú del Explorador y elige los tres puntos verticales junto al conjunto de datos, debajo del menú desplegable de "Proyectos". Ahora, seleccionaremos el ícono para crear una tabla, que abre una ventana emergente. Debajo de Fuente y crear tabla desde, seleccionamos "Cargar" o cualquier método que prefieras para cargar tus datos. Aquí, podemos cargar cualquier archivo de datos, por ejemplo, un archivo CSV. Vamos a darle a nuestra tabla un nombre útil como "test_table". Asegúrate de que el esquema esté configurado para detectar y seleccionar automáticamente "Crear tabla". Hay mucho más por conocer sobre BigQuery. Siéntete libre de volver a ver este video en cualquier momento y sigue practicando. Nos vemos pronto.

### BigQuery en acción 🎬

[![Tiempo](https://img.shields.io/badge/Tiempo-6%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Has aprendido la forma en que ordenar y filtrar datos en hojas de cálculos ayuda a los analistas de datos a personalizar la información. Personalizar datos hace que sea más significativo y sencillo comprenderlos, analizarlos y visualizarlos. También has descubierto que algunas hojas de cálculo pueden ser extremadamente largas y complejas. Saber cómo acercar los datos exactos que necesitas mientras dejas a un lado el resto de los datos te ayudará a enfocarte en tu análisis. Esto también es cierto para las bases de datos. A veces, un conjunto de datos es demasiado grande para descargar, o no cabe en una hoja de cálculo. Entonces, un analista de datos usará SQL para crear una consulta con el fin de ver datos específicos de una serie más amplia. Hemos aprendido que una base de datos es una recopilación de datos almacenados en un sistema informático. Y que SQL significa Lenguaje de consulta estructurado. Los analistas de datos utilizan lenguaje de consulta para comunicarse con la base de datos. En un video anterior también aprendiste que una base de datos relacional contiene una serie de tablas que pueden conectarse para formar relaciones. Esas relaciones están representadas mediante claves primarias y externas. Los analistas de datos escriben consultas para obtener datos de estas tablas. Veamos cómo funciona. Empezaremos con nuestro visualizador de tabla.

Aquí podemos ver los conjuntos de datos públicos que están disponibles. Nos desplazaremos por los datos antes de empezar a usarlos para tener una idea de qué se trata y para asegurarnos de que estén limpios.

Algunos visualizadores de tablas te permiten previsualizar algunas filas antes de escribir una consulta. Esto es útil si quieres echarle un vistazo para asegurarte de que el conjunto de datos será el adecuado para tu proyecto. Para mostrarte cómo funciona, veamos un ejemplo de un conjunto de datos. Este muestra cuánta luz solar reciben los tejados durante un año.

Eso sería muy útil para un analista de datos que esté trabajando en un proyecto sobre energía solar, por ejemplo.

![image](./img/module%3001%20img%3049.png)

Empezaremos por previsualizar el conjunto de datos. Haz clic en él, de esta manera.

Luego, seleccionaremos un subconjunto de estos datos, donde encontraremos regiones, estados, luz solar anual y más. Para ver todo el conjunto de datos, escribamos una consulta. El primer paso es encontrar el nombre completo correcto del conjunto de datos. Para hacer esto, selecciona el conjunto de datos, el potencial solar por código postal y selecciona una tabla de consulta.

El nombre del conjunto de datos aparece entre dos comillas simples. Esto nos ayudará a leer la consulta de forma mucho más fácil. También podemos quitar las comillas simples en este caso, y nuestra consulta seguirá funcionando.

Las palabras que ves antes del punto representan el nombre de la base de datos.

Y las palabras que están después del punto representan el nombre de la tabla.

Seleccionemos y copiemos el nombre del conjunto de datos porque lo necesitaremos dentro de poco.

Ahora hacemos clic en el signo más para crear una nueva consulta.

La mayoría de las consultas comienzan con la palabra SELECT (seleccionar).

Luego agregamos un espacio.

Como queremos ver todo el conjunto de datos, pondremos un asterisco a continuación. El asterisco indica que queremos incluir todas las columnas. Ese es un gran atajo, ya que sin él tendríamos que completar cada nombre de campo.

Luego presionaremos mostrar resultados y escribiremos FROM (desde). FROM hace justo lo que parece. Indica de dónde vienen los datos. Luego, agregaremos otro espacio. Ahora pegamos el nombre del conjunto de datos que copiamos antes.

Y, finalmente, realizamos la consulta.

![image](./img/module%3001%20img%3050.png)

Ahora, puedes examinar el conjunto de datos con cuidado antes de empezar a trabajar con él. Es importante tener en cuenta lo siguiente: Las consultas SQL pueden estar escritas de muchas maneras diferentes, pero proporcionarán los mismos resultados. Por ejemplo, podríamos haber escrito esta consulta como una línea larga de instrucciones como esta,

y obtendríamos los mismos resultados.

Las líneas y los espacios adicionales no impactan en el resultado de la consulta, pero mantienen tu consulta organizada y más fácil de leer para ti y para otros. Ahora bien, si el proyecto no requiere todos estos campos, podemos utilizar SQL para ver una o varias piezas de datos. Para hacer esto, especificamos un nombre de columna determinado en la consulta. Por ejemplo, quizás solo queremos ver los datos de Pensilvania. Así que comenzaremos nuestra consulta de la misma manera que hemos aprendido. SELECT, espacio y un asterisco.

Luego, FROM nuestra base de datos de potencial solar. Pero esta vez agregaremos WHERE (dónde).

WHERE también hace exactamente lo que parece. Le dice a la base de datos dónde buscar información. En este caso, en la columna state name. Entonces, agrega un espacio y escribe state guion bajo name, el nombre de la columna.

![image](./img/module%3001%20img%3051.png)

Como solo queremos ver los datos de Pensilvania, agregamos un signo igual y la palabra Pensilvania entre comillas simples.

En SQL, las comillas simples indican el comienzo y el final de una cadena. Finalmente, ejecutamos la consulta.

Ahora podemos ver los datos sobre el potencial solar solo para Pensilvania. Ahora ya tenemos los datos que queremos y estamos listos para comenzar a ponerlos a trabajar, algo que veremos más adelante. Por ahora, celebremos que hemos terminado otro módulo. Has abordado un montón de información compleja y muy técnica. A medida que vayas practicando, las cosas comenzarán a sentirse más naturales. Por ahora, tómate un momento para relajarte y pensar en todo lo que has aprendido. Has descubierto los metadatos y cómo mantienen a los datos organizados al describir de qué se tratan esos datos. Has visto cómo acceder a los datos internos y externos, y cómo los analistas de datos los utilizan para encontrar información convincente para resolver problemas de la empresa. Y puedes ordenar y filtrar tus datos para encontrar la información que necesitas. Por último, has aprendido sobre consultas y hasta has practicado cómo escribirlas. A continuación, tendrás algunas lecturas y, luego, un desafío semanal para comprobar tus conocimientos. Esto te ayudará a confirmar que has comprendido lo que hemos trabajado en estos videos. Y, como siempre, si llegas a tener alguna duda sobre una pregunta, te recomiendo que repases los videos y las lecturas para encontrar la respuesta. Ahora eres el detective de datos, así que usa esas habilidades. ¡Buen trabajo, sigue así! Nos vemos en el desafío semanal.

![image](./img/module%3001%20img%3052.png)

### Utilizar BigQuery 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-30%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

[BigQuery](https://cloud.google.com/bigquery/docs) es un depósito de datos en Google Cloud que los analistas de datos pueden utilizar para realizar consultas, filtrar conjuntos de datos grandes, agregar resultados y realizar operaciones complejas. 

La próxima actividad está realizada en BigQuery. Esta lectura proporciona instrucciones para crear tu propia cuenta en BigQuery, seleccionar conjuntos de datos públicos y cargar archivos CSV. Al final de esta lectura puedes confirmar tu acceso a la consola de BigQuery antes de pasar a la actividad.

Nota: Al final de esta lectura, también proporcionamos recursos adicionales introductorios que se encuentran en algunas plataformas de la base de datos SQL, por si eliges trabajar con ellos en lugar de BigQuery. 

TO DO!!!!

### Actividades prácticas: Introducción a BigQuery 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-30%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

![image](./img/module%3001%20img%3053.png)

![image](./img/module%3001%20img%3054.png)

![image](./img/module%3001%20img%3055.png)

![image](./img/module%3001%20img%3056.png)

### Actividades prácticas: Crea una tabla de datos personalizada en BigQuery 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-30%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

![image](./img/module%3001%20img%3057.png)

![image](./img/module%3001%20img%3058.png)

![image](./img/module%3001%20img%3059.png)

![image](./img/module%3001%20img%3060.png)

![image](./img/module%3001%20img%3061.png)

![image](./img/module%3001%20img%3062.png)

![image](./img/module%3001%20img%3063.png)

### Guia detallada prácticas recomendadas en SQL 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-30%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)



### Actividades prácticas: Aplicar SQL 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-30%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

![image](./img/module%3001%20img%3077.png)

### Cuestionario práctico 📑

[![Tiempo](https://img.shields.io/badge/Tiempo-20%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

Pon a prueba tus conocimientos sobre el uso de SQL con conjuntos de datos grandes (Cuestionario práctico - 4 preguntas)

1. En MySQL, ¿cuál es la sintaxis aceptable para la palabra clave SELECT? Selecciona todas las opciones que correspondan.

    - "SELECT"
    
      ❌ Incorrecto.
  
    - SELECT
    
      ✅ Correcto. En MySQL, SELECT o seleccionar es una sintaxis aceptable.
    
    - 'SELECT'
    
      ❌ Incorrecto.
      
    - select
    
      ✅ Correcto. En MySQL, SELECT o seleccionar es una sintaxis aceptable.


2. ¿Qué tipo de notación se utiliza con mayor frecuencia en los nombres de las columnas de una tabla de una base de datos y representa una mejor práctica? Selecciona todas las opciones que correspondan.

    - Tipo oración
    
      ❌ Incorrecto.
  
    - Camel case
    
      ❌ Incorrecto.
    
    - Minúscula
    
      ✅ Correcto. Los nombres de las columnas deben escribirse con minúscula y los nombres compuestos por varias palabras en Snake case, que separa cada palabra con un guion bajo para que sea más legible. Los nombres de las columnas nunca deben tener espacios.
      
    - Snake Case
    
      ✅ Correcto. Los nombres de las columnas deben escribirse con minúscula y los nombres compuestos por varias palabras en Snake case, que separa cada palabra con un guion bajo para que sea más legible. Los nombres de las columnas nunca deben tener espacios.


3. En BigQuery, ¿qué sintaxis opcional se puede eliminar de la siguiente cláusula FROM sin dejar de realizar la consulta?: FROM `bigquery-public-data.sunroof_solar.solar_potential_by_postal_code`

    - Guiones
    
      ❌ Incorrecto.
  
    - Guiones bajos
    
      ❌ Incorrecto.
    
    - Puntos
    
      ❌ Incorrecto.
      
    - Comillas simples
    
      ✅ Correcto. El nombre del conjunto de datos se muestra entre dos comillas simples para ayudar a las personas a leer la consulta más fácilmente. Si quitas las comillas simples, la consulta seguirá ejecutándose.


4. En la siguiente cláusula FROM, ¿cuál es el nombre de la tabla en la consulta SQL?: FROM bigquery-public-data.sunroof_solar.solar_potential_by_postal_code

    - public-data.sunroof
    
      ❌ Incorrecto.
  
    - solar.solar
    
      ❌ Incorrecto.
    
    - solar_potential_by_postal_code
    
      ✅ Correcto. El nombre de la tabla en la consulta SQL es solar_potential_by_postal_code. La tabla está en el conjunto de datos sunroof_solar, un conjunto de datos público en BigQuery.
      
    - sunroof_solar
    
      ❌ Incorrecto.


---

## 6. Desafio semanal 🏆

### Temario: 

- Glosario: Términos y definiciones (Reading - 5 min)
- Desafio semanal 3 (Quiz - 8 questions)

### Glosario: Términos y definiciones 📖

[![Tiempo](https://img.shields.io/badge/Tiempo-5%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)

A

- Agenda: Una lista de citas programadas.

- Alcance del trabajo (SOW): Esquema acordado de las tareas a realizar durante un proyecto.

- Algoritmo: Proceso o conjunto de reglas a seguir para una tarea específica.

- Análisis (computacional) de datos: La ciencia de los datos.

- Análisis de datos: La recopilación, transformación y organización de los datos para sacar conclusiones, hacer predicciones e impulsar una toma de decisiones fundamentada.

- Análisis de déficits: Un método para examinar y evaluar el estado actual de un proceso con el fin de identificar las oportunidades de mejora en el futuro.

- Analista de datos: Alguien que recopila, transforma y organiza los datos para sacar conclusiones, hacer predicciones e impulsar la toma de decisiones fundamentada.

- Apertura (openness): El aspecto de la ética de datos que promueve el acceso libre a los datos, su uso y también el uso compartido.

- Archivo de audio: Almacenamiento digitalizado de audio generalmente en MP3, AAC u otro formato comprimido.

- Archivo de video: Conjunto de imágenes, archivos de audio y otros datos generalmente codificados en un formato comprimido, por ejemplo, MP4, MV4, MOV, AVI o FLV. 

- Atributo: Característica o calidad de los datos que se usa para etiquetar una columna en una tabla.

- AVERAGE: Función de una hoja de cálculo que muestra el resultado de un promedio de los valores de un rango seleccionado.

B

- Base de datos: Recopilación de datos almacenados en un sistema informático.

- Base de datos relacional: Base de datos que contiene una serie de tablas que se pueden conectar para mostrar relaciones.
  
- Bordes: Líneas que se pueden agregar alrededor de dos o más celdas en una hoja de cálculo.

C

- Campo: Información de una fila o columna de una hoja de cálculo; en una tabla de datos; suele ser una columna de la tabla.

- Causa raíz: La razón por la que ocurre un problema.

- Ciclo de vida de los datos: Secuencia de etapas por las que pasan los datos, que incluye planificar, capturar, gestionar, analizar, archivar y destruir.

- Ciencia de datos: Un campo de estudio que utiliza datos brutos para crear nuevas formas de modelar y entender lo desconocido.

- Conjunto de datos: Una colección de datos que pueden ser manipulados o analizados como una unidad.

- Consentimiento: El aspecto de la ética de datos que considera el derecho de una persona de conocer cómo y por qué se utilizarán sus datos personales antes de estar de acuerdo de proporcionarlos.

- Consulta: Solicitud de datos o información de una base de datos.

- Contexto: La condición en la que algo existe o sucede.

- Controlador de relleno: Cuadro en la esquina inferior derecha de una celda seleccionada de una hoja de cálculo que se puede arrastrar a través de las celdas vecinas para seguir una instrucción.

- COUNT: Función de la hoja de cálculo que cuenta el número de celdas en un rango que cumplen con un criterio especificado.

- Cookie: Pequeño archivo almacenado en una computadora que contiene información acerca de sus usuarios.

D

- Datos abiertos: Datos que están disponibles para el público.

- Datos booleanos: Tipo de datos con solo dos valores posibles, generalmente verdadero o falso.

- Datos continuos: Datos que se miden y que pueden tener casi cualquier valor numérico.

- Datos cualitativos: Medida subjetiva y explicativa de una cualidad o característica.

- Datos cuantitativos: Medida específica y objetiva, como un número, cantidad o rango.

- Datos: Una colección de hechos.

- Datos de primera fuente: Datos recopilados por una persona o por un grupo por medio de sus propios recursos.

- Datos de segunda fuente: Datos que recopila un grupo directamente de su audiencia y que, luego, se venden. 

- Datos de terceros: Datos proporcionados por fuentes externas que no recopilaron de forma directa.

- Datos discretos: Datos que se cuentan y tienen un número limitado de valores

- Datos en formato ancho: Conjunto de datos en el que cada tema tiene una sola fila con varias columnas para describir los valores de los distintos atributos del tema.

- Datos en formato largo: Conjunto de datos en el que cada fila constituye un punto en el tiempo por sujeto, es decir que cada sujeto tiene datos en varias filas.

- Datos estructurados: Datos organizados de cierta forma, por ejemplo, en filas y columnas.

- Datos externos: Datos que se alojan y se generan fuera de una organización.

- Datos internos: Datos alojados en los sistemas propios de una empresa.

- Datos no estructurados: Datos que no se organizan de forma que sea fácil identificarlos.

- Datos nominales: Tipo de datos cualitativos que se categoriza sin un orden establecido.

- Datos ordinales: Datos cualitativos con un orden o escala establecidos.
Datos: Una colección de hechos.

- Destrezas analíticas: Cualidades y características asociadas al uso de hechos para resolver problemas.

- Diseño de datos: Cómo se organiza la información.
  
- Dominio del problema: Área de análisis que abarca cada actividad que afecta a un problema o se ve afectada por él.

E

- Ecosistema de datos: Los distintos elementos que interactúan entre sí para producir, gestionar, almacenar, organizar, analizar y compartir datos.

- Ecuación: Cálculo que implica suma, resta, multiplicación o división (también se denomina expresión matemática).

- Elemento de datos: Cierta información dentro de un conjunto de datos. 

- Encabezado: Primera fila en una hoja de cálculo que hace referencia al tipo de datos en cada columna.

- Equidad: Cualidad del análisis de datos que no genera sesgos ni los reafirma.

- Estrategia de datos: La gestión de las personas, los procesos y las herramientas que se usan en el análisis de datos.

- Ética de datos: Normas justificadas respecto de lo que está bien y lo que está mal a la hora de recopilar, compartir y usar datos.

- Ética: Normas justificadas respecto de lo que está bien y lo que está mal. Por lo general, presuponen lo que deben hacer los seres humanos, usualmente en términos de derechos, obligaciones, beneficios para la sociedad, equidad o virtudes específicas.

- Expresión matemática: Cálculo que implica suma, resta, multiplicación o división (también se denomina ecuación).

F

- Filtrado: Proceso que muestra solo los datos que cumplen con un criterio específico mientras oculta el resto.

- Fórmula: Conjunto de instrucciones que se utilizan para realizar un cálculo al utilizar los datos de una hoja de cálculo.

- Foto digital: Una imagen electrónica o computarizada, generalmente en formato BMP o JPG.

- Fuente de datos correctos: Fuente de datos confiable, original, integral, actual y citada (ROCCC). 

- Fuente de datos erróneos: Fuente de datos que no es confiable, original, integral, actual ni citada (ROCCC). 

- Función: Un comando preestablecido que realiza automáticamente un proceso o tarea especificado al utilizar los datos de una hoja de cálculo.

- Función matemática: Función que se utiliza como parte de una fórmula matemática.

G

- Gráfico dinámico: Gráfico creado a partir de los campos en una tabla dinámica.

H

- Hoja de cálculo: Hoja de cálculo digital.

I

- Informe: Recopilación estática de datos que se entrega periódicamente a los interesados.

- Ingresos: Cantidad total de ingresos generados por la venta de mercaderías o servicios.

- Interesados: Personas que invierten tiempo y recursos en un proyecto y se interesan por su resultado.

- Interoperabilidad de los datos: Factor clave que conlleva el uso satisfactorio de los datos abiertos entre empresas y gobiernos.

J

K

L

- Lenguaje de consulta: Lenguaje de programación informática utilizado para comunicarse con una base de datos.

- Lenguaje de consulta estructurado: Lenguaje de programación informática usado para comunicarse con una base de datos.

- Los interesados: Personas que invierten tiempo y recursos en un proyecto y se interesan por su resultado.

M

- Macrodatos: Conjuntos de datos grandes y complejos que, generalmente, se recopilan durante largos períodos y que permiten que los analistas de datos. aborden los problemas comerciales de gran alcance

- MAX: Función de la hoja de cálculo que muestra el valor numérico más alto de un rango de celdas.

- Mentalidad técnica: La capacidad de dividir las cosas en pasos o piezas más pequeñas y trabajar con ellas de forma ordenada y lógica.

- Metodología SMART: Herramienta para determinar la eficacia de una pregunta basándose en si es específica, medible, orientada a la acción, relevante y con plazos determinados.

- Métrica: Tipo único y cuantificable de datos que pueden utilizarse para medición.

- Microdatos: Puntos de datos pequeños, específicos, que generalmente involucran un breve período y que son útiles para tomar decisiones diarias.

- MIN: Función de la hoja de cálculo que muestra el resultado del valor numérico más bajo de un rango de celdas.

- Modelo de datos: Herramienta para organizar los elementos de datos y la forma en que se relacionan entre ellos.

- Muestra: En el análisis computacional de datos, segmento de una población que la representa en su totalidad.

- Muestreo imparcial: Muestra de la población que la representa en su totalidad.

N

- Nube: Lugar para mantener los datos en línea, en vez de guardarlos en el disco duro de una computadora.

O

- Objetivo métrico: Objetivo medible establecido por una empresa y evaluado mediante métricas.

- Observación: Los atributos que describen una pieza de datos contenida en una fila de una tabla.

- Oficina del Censo de los Estados Unidos: Agencia del Departamento de Comercio de los Estados Unidos que funciona como proveedora principal de datos de calidad sobre las personas y la economía a nivel nacional.

- Operador: Símbolo que designa la operación o cálculo a realizarse.

- Orden de las operaciones: Uso de paréntesis para agrupar los valores de la hoja de cálculo a fin de aclarar el orden en el que deben realizarse las operaciones.

- Ordenación: Proceso de organizar los datos en un sistema de clasificación significativo para que sean más fáciles de entender, analizar y visualizar.

P

- Panel: Herramienta que monitorea los datos entrantes en vivo.

- Pensamiento analítico: El proceso de identificar y definir un problema, para luego resolverlo mediante el uso de datos de manera organizada, paso a paso.

- Pensamiento estructurado: Proceso de reconocer el problema o la situación actuales, organizar la información disponible, revelar déficits y oportunidades e identificar opciones.

- Píxel: En imágenes digitales, es un área pequeña de iluminación en una pantalla de visualización que, cuando se combina con otras áreas adyacentes, forma una imagen digital.

- Población: En análisis computacional de datos, todos los valores de datos posibles en un conjunto de datos.

- Pregunta con límite de tiempo: Pregunta que especifica un plazo para ser analizada.

- Pregunta específica: Pregunta simple, significativa y enfocada en un solo tema o en algunas ideas estrechamente relacionadas entre sí.

- Pregunta injusta: Pregunta en la que se hacen suposiciones o que es difícil de responder honestamente.

- Pregunta medible: Pregunta cuyas respuestas se pueden cuantificar y evaluar.

- Pregunta orientada a la acción: Pregunta cuyas respuestas conducen al cambio.

- Pregunta principal: Pregunta que orienta a las personas hacia cierta respuesta.

- Pregunta relevante: Pregunta que tiene importancia para el problema que se debe resolver.

- Privacidad de los datos: Preservación de la información sobre los datos de una persona cada vez que ocurre una transacción de datos.

- Proceso de análisis de datos: Las seis fases de preguntar, preparar, procesar, analizar, compartir y actuar cuyo propósito es el de obtener conocimiento que propicie la toma de decisiones informada.

- Propiedad: El aspecto de la ética de datos que presupone que cada persona es dueña de los datos sin procesar que proporciona y que tiene control primordial sobre su uso, procesamiento y uso compartido. 

Q

R

- Rango: Conjunto de dos o más celdas en una hoja de cálculo.

- Redes sociales: Sitios web y aplicaciones en los que los usuarios crean y comparten contenido o interactúan entre sí.

- Referencia de celda: Celda o rango de celdas en una hoja de cálculo que se usa generalmente en fórmulas y funciones.

- Reformulación: Proceso de replantear un problema o desafío, que se redirecciona luego hacia una posible resolución. 

- Retorno de la inversión (ROI): Fórmula que utiliza las métricas de inversión y ganancias para evaluar el éxito de una inversión.

- Reglamento General de Protección de Datos de la Unión Europea (GDPR): Organismo formulador de políticas en la Unión Europea, creado para ayudar a proteger a las personas y sus datos.

- Registro: Conjunto de datos relacionados en una tabla de datos, generalmente sinónimo de fila.

S

- Sesgo: Preferencia consciente o no a favor o en contra de una persona, un grupo de personas o una cosa.

- Sesgo de confirmación: La tendencia de buscar o interpretar la información de manera que confirma creencias preexistentes.

- Sesgo de interpretación: Tendencia a interpretar situaciones ambiguas de manera positiva o negativa.

- Sesgo de los datos: Cuando una preferencia a favor o en contra de una persona, un grupo de personas o una cosa sesga sistemáticamente los resultados del análisis de datos en una cierta dirección.

- Sesgo del investigador: Tendencia de distintas personas a observar las cosas de forma diferente (también se denomina “sesgo del observador”).

- Sesgo del muestreo: Representar en mayor o en menor medida a ciertos miembros de una población debido a que se trabaja con una muestra que no representa a la población en su totalidad.

- Sesgo del observador: Tendencia de distintas personas a observar las cosas de forma diferente (también se denomina “sesgo del investigador”).

- SQL: (Ver “Lenguaje de consulta estructurado”).
  
- SUM: Función de una hoja de cálculo que suma los valores de un rango de celdas seleccionadas.

T

- Tabla dinámica: Herramienta de resumen de datos que se utiliza para clasificar, reorganizar, agrupar, contar, totalizar o promediar datos.

- Tarea empresarial: La pregunta o el problema que el análisis de datos resuelve para un negocio.

- Tasa de rotación: Ritmo en el que los empleados abandonan voluntariamente una empresa.

- Tipo de datos de texto: Secuencia de caracteres y puntuación que contiene información textual (también denominado tipo de datos de cadena).

- Tipo de datos en cadena: Secuencia de caracteres y puntuación que contiene información textual (ver Tipo de datos de texto).

- Tipo de datos: Un atributo que describe cierto dato según sus valores, su lenguaje de programación o las operaciones que puede realizar.

- Tipos de problemas: Distintos problemas que encuentra el analista de datos; entre ellos, categorizar elementos, descubrir conexiones, hallar patrones, identificar temas, hacer predicciones y detectar algo inusual.

- Toma de decisiones basada en datos: Uso de datos para guiar la estrategia empresarial.

- Toma de decisiones inspirada en datos: El proceso de explorar diferentes fuentes de datos para descubrir qué tienen en común.

- Transparencia de la transacción: Aspecto de la ética de datos que presupone que se deben explicar todas las actividades de procesamiento de datos y los algoritmos a la persona que proporciona los datos y que también presupone que esta persona debe comprenderlos.

U
V

- Vigencia: El aspecto de la ética de datos que presupone que las personas deben conocer las transacciones financieras resultantes del uso de sus datos personales y la magnitud de esas transacciones.

- Visualización de datos: La representación gráfica de los datos.

- Visualización: (Consulta la visualización de datos).

W
X
Y
Z

### Cuestionario de diagnóstico 📑

Desafio semanal 3

[![Tiempo](https://img.shields.io/badge/Tiempo-40%20minutos-blue.svg)](https://www.coursera.org/professional-certificates/analisis-de-datos-de-google)


1. Las claves primarias y externas son dos identificadores conectados dentro de tablas separadas. ¿Estas tablas existen en qué tipo de bases de datos?

    - Metadatos
    
      ❌ Incorrecto.
  
    - Normalizada 
    
      ❌ Incorrecto.
    
    - Relacional
    
      ✅ Correcto. Las claves primarias y externas son dos identificadores conectados dentro de tablas separadas en una base de datos relacional.
      
    - Primaria
    
      ❌ Incorrecto.


2. ¿Para qué tareas utilizan los metadatos los analistas de datos? Selecciona todas las opciones que correspondan.

    - Para combinar datos desde más de una fuente
    
      ❌ Incorrecto.
  
    - Para interpretar el contenido de una base de datos 
    
      ✅ Correcto. Los analistas de datos utilizan los metadatos para combinar datos, evaluar datos e interpretar una base de datos.
    
    - Para realizar análisis de datos
    
      ❌ Incorrecto.
      
    - Para evaluar la calidad de los datos
    
      ✅ Correcto. Los analistas de datos utilizan los metadatos para combinar datos, evaluar datos e interpretar una base de datos.


3. Los metadatos estructurales indican cómo se organizan los datos y si forman parte de una o más de una recopilación de datos.

    - Verdadero
    
      ❌ Incorrecto.
  
    - Falso 
    
      ✅ Correcto. Los metadatos estructurales indican cómo se organizan los datos y si forman parte de una o más de una recopilación de datos. 
    

4. Completa el espacio en blanco: Gobierno de datosover es el proceso que garantiza que los _____ de una empresa se gestionen de manera formal. 

    - ingenieros de datos
    
      ❌ Incorrecto.
  
    - recursos de datos 
    
      ✅ Correcto. Gobierno de datos es el proceso que garantiza que los recursos de datos de una empresa se gestionen de manera formal. 
    
    - tareas empresariales
    
      ❌ Incorrecto.
      
    - estrategias empresariales
    
      ❌ Incorrecto.


5. ¿Cuáles son algunos de los beneficios claves de utilizar datos externos? Selecciona todas las opciones que correspondan.

    - Los datos externos son siempre confiables.
    
      ❌ Incorrecto.
  
    - Los datos externos pueden proporcionar perspectivas a nivel de la industria. 
    
      ✅ Correcto. Algunos de los beneficios clave de utilizar datos externos son que tienen un amplio alcance y proporcionan perspectivas a nivel de la industria.
    
    - Los datos externos tienen un amplio alcance.
    
      ✅ Correcto. Algunos de los beneficios clave de utilizar datos externos son que tienen un amplio alcance y proporcionan perspectivas a nivel de la industria.
      
    - Los datos externos son gratuitos.
    
      ❌ Incorrecto.


6. Un analista de datos analiza una base de datos de ventas de automóviles de Wisconsin para descubrir los últimos modelos de automóviles vendidos en Milwaukee en 2019. ¿Cómo puede ordenar y filtrar los datos para mostrar los resultados de los últimos cinco automóviles vendidos en la parte superior de la lista? Selecciona todas las opciones que correspondan. 

    - Ordenar por fecha de venta en orden ascendente.
    
      ❌ Incorrecto.
  
    - Filtrar las ventas fuera de Milwaukee. 
    
      ✅ Correcto. El analista puede filtrar las visualizaciones fuera de Milwaukee en 2019 y ordenarlas por fecha en orden descendente. 
    
    - Ordenar por fecha de venta en orden descendente.
    
      ✅ Correcto. El analista puede filtrar las visualizaciones fuera de Milwaukee en 2019 y ordenarlas por fecha en orden descendente. 
      
    - Filtrar las ventas que no se realizaron en 2019.
    
      ✅ Correcto. El analista puede filtrar las visualizaciones fuera de Milwaukee en 2019 y ordenarlas por fecha en orden descendente. 


7. Al escribir una consulta, debes eliminar las dos comillas simples para encerrar el nombre del conjunto de datos para que la consulta se ejecute adecuadamente.

    - Verdadero
    
      ❌ Incorrecto.
  
    - Falso 
    
      ✅ Correcto. Al escribir una consulta, el nombre del conjunto de datos puede estar dentro de las dos comillas simples o no, y aun así la consulta se ejecutará adecuadamente.


Estás trabajando con una tabla de una base de datos que contiene datos del cliente. La columna city incluye la ciudad donde se encuentra cada cliente. Deseas averiguar qué clientes se encuentran en Berlín.

Escribes la consulta SQL a continuación. Agrega una cláusula WHERE que mostrará resultados solo de clientes que se encuentren en Berlín.

SELECT
*
FROM
customer
WHERE
city = 'Berlin' 

+-------------+------------+-----------+---------+---------------------+--------+-------+---------+-------------+------------------+------+---------------------------+----------------+
| customer_id | first_name | last_name | company | address             | city   | state | country | postal_code | phone            |  fax | email                     | support_rep_id |
+-------------+------------+-----------+---------+---------------------+--------+-------+---------+-------------+------------------+------+---------------------------+----------------+
|          36 | Hannah     | Schneider |    None | Tauentzienstraße 8  | Berlin |  None | Germany | 10789       | +49 030 26550280 | None | hannah.schneider@yahoo.de |              5 |
|          38 | Niklas     | Schröder  |    None | Barbarossastraße 19 | Berlin |  None | Germany | 10779       | +49 030 2141444  | None | nschroder@surfeu.de       |              3 |
+-------------+------------+-----------+---------+---------------------+--------+-------+---------+-------------+------------------+------+---------------------------+----------------+

8. ¿Cuántos clientes se encuentran en Berlín?

    - 7
    
      ❌ Incorrecto.
  
    - 2
    
      ✅ Correcto. La cláusula WHERE city = 'Berlin' mostrará los resultados solo de los clientes que se encuentran en Berlín. La consulta completa es SELECT * FROM customer WHERE city = 'Berlin'. La cláusula WHERE filtra los resultados que cumplen con ciertas condiciones. La cláusula WHERE incluye el nombre de la columna, un signo de igual y el valor o los valores para incluir en la columna. Coloca comillas para encerrar los valores de texto. Hay dos clientes que se encuentran en Berlín. 
    
    - 9
    
      ❌ Incorrecto.
      
    - 12
    
      ❌ Incorrecto.
