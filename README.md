# Propedeutico de Python para la EGobiernoyTP - Verano 2024

¡Bienvenidos!

Para este curso, utilizaremos Google Colab. Es una plataforma que permite correr Python en servidores de Google. La principal ventaja es que elimina el obstáculo de tener computadoras y sistemas operativos diferentes; sin embargo, no es escalable para proyectos con impacto real. Una vez que comiencen sus clases, trabajarán con herramientas dentro de la infraestructura de la Escuela.

Cada una de las sesiones en este curso se corresponde con uno o dos _notebooks_, que contendrá las instrucciones que todos seguiremos de manera conjunta. Todos ellos están dentro de la carpeta `notebooks`, que pueden encontrar en la estructura principal de este repositorio de GitHub. Para poder trabajar sobre ellos, es decir, "correr el código", es necesario presionar el botón "Open in Colab" que se encuentra al principio de cada uno. Esto abrirá una nueva ventana con una copia del _notebook_ que es solamente para ustedes, que podrán editar con su propio trabajo. Para poder guardarla, deben hacerlo de manera explícita en Google Drive: por medio del menú `Archivo->Guardar una copia en Drive`. 

Los datos con los que trabajaremos en este curso, que se pueden encontrar para su facilidad ya descargados dentro de la carpeta `datos`, serán:
* [Indicadores demográficos de México de 1950 a 2050 y de las entidades federativas de 1970 a 2050, publicados en 2018 por datos.gob.mx](https://datos.gob.mx/herramientas/indicadores-demograficos-de-mexico-de-1950-a-2050-y-de-las-entidades-federativas-de-1970-a-2050?category=web&tag=economia)

## Temario

### 1: Introducción a Python

1.  ¿Qué es y cómo funciona Python?
2.  ¿Qué es un notebook?
3.  Variables
4.  Operadores
    - Tipos de operadores
5.  Comentarios
    - Comentario de una sola línea
    - Comentario multilinea
6.  Tipo de datos
    - Boolean
    - Númericos
    - Strings
    - Formatting
7. Tipos de estructuras de datos
    - Listas
    - Tuplas
    - Sets
    - Diccionarios

### 2: Más de introducción a Python.

1. Input
2. Indexación y Slicing
3. Conversión en tipo de datos
4. Conditionals
5. Loops
   - for
   - while 
   - range y enumerate
6. Funciones
   - Recursivas
   - Lambda
7. Clases & Objetos

### 3: Paquetes, archivos, más intro python

1. Paquetes
   - pip
   - Importar paquetes
   - Ambientes Virtuales
2. Cargar archivos
    - Importas archivos de Google Drive
    - open
    - csv con pandas
3. Arreglos (numpy)

### 4: Exploración de bases de datos (pandas 1)

1. Generalidades de bases de datos
    - ¿Cuántas variables y observaciones tenemos?
    - Diccionario de variables
    - Explorando más
2. Tipos de datos en db
    - Cambiar tipos de datos
        - str
        - float
        - int
        - datetime
3. Variables categóricas
4. Variables numéricas
5. Variables temporales
6. NA's
    - Drop
    - Replace
7. Subconjuntos de bases
    - Quitar columnas
    - Seleccionar subconjuntos de la base
    - Seleccionar subconjuntos basados en condiciones
8. Reset index

### 5: Más de pandas

1. Arrays y Dataframes
2. Operaciones básicas en Dataframes
    * Creación de columnas nuevas
        * Suma, resta, multiplicación o divisón
        * Comandos básicos de texto
    * Agrupación
3. Operaciones avanzadas en Dataframes
    * Funciones Lambda
4. Combinación de Dataframes
    * Tipos de joins
    * Merge

### 5: EDA y GEDA

1. Introducción a análisis de datos
    - Objetivos 
    - Tipos de estructura de datos
    - Tipos de exploración de datos
2. EDA (Exploratory Data Analysis) / GEDA (Graphical Exploratory Data Analysis)
    - Definir el tipo de dato
        - Categóricas
        - Numéricas
        - Fechas
        - Texto
        - Geolocalización
    - Algunos principios de visualización 
    - Análisis práctica


### 7: SQL básico

1. Introducción
    * Bases de datos
    * Lenguaje SQL
2. Establecer conexiones con las bases de datos
    * sqlite 
    * psycopg2 
3. Acciones básicas con SQL
    * Instrucciones desde Python
    * Obtener información con SQL
    * Modificar información con SQL

### 8: Errores y _debugging_

1. Errores comunes
    * Signos faltantes (e.g. paréntesis, dos puntos, comas, etc.)
    * Indentación
    * Typos
    * Tipo incorrecto de variable
2. Debugging
   * Recomendaciones generales
   * Buenas prácticas de programación
3. Herramientas útiles
    * Stack Overflow
    * ChatGPT
    * Documentación oficial
