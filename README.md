# IntroduccionAIngSistemas
Proyecto hecho por:

-José Angulo

-Daniel Rincón

-Sebastián Ibáñez

# Introducción
En este repositorio utilizamos una base de datos que contiene los detalles de las pruebas saber 11 de los años 2010 a 2022, se ocuparon 3 perfiles con diferente enfoque. Cada uno de estos perfiles cuenta con dos preguntas que buscan ser resueltas indagando en la base de datos.


# Metodología
<p>En el contexto de este análisis utilizamos un dataset proveniente de datos.gov.co que contenía información recopilada en las pruebas saber 11 desde el año 2010 al 2022, en el dataset se podían encontrar multiples variables como: </p>

<ul>
    <li>Los puntajes globales en el ICFES</li>
    <li>Los puntajes correspondientes a cada temática a evaluar (Naturales, Sociales, Matemáticas, Inglés y Lectura Crítica).</li>
    <li>Información socioeconómica del hogar como: el estrato social, el numero de habitaciones, el numero de familiares, si la familia posee lavadora, si posee internet, el acceso a computador, el nivel educativo de los padres.</li>
    <li>Información del estudiante como: su edad, la jornada de su colegio.</li>
    <li>Información sobre el periodo en el que se realizo la prueba.</li>
    <li>Información geográfica como el departamento donde se realizó la prueba.</li>
</ul>

##### Fecha de adquisición

<p>La fecha de adquisición de los datos comprende entre el año 2010 al año 2022, sin embargo algunos periodos no aparecen debido a problemáticas como la pandemia.</p>

## Perfiles

<p>Para este análisis tuvimos en cuenta tres perfiles relacionados con la mejoría de la educación del país:
<ol>
    <li>Un profesor que busca mejorar los resultados en las pruebas de estado.</li>
    Este perfil procura por el éxito académico de los estudiantes por ello está en la busqueda de resolver preguntas que puedan dar a soluciones para el éxito de los estudiantes en las pruebas de estado.
    <li>Un trabajador del ministerio de educación encargado de la equidad.</li>
    Este perfil busca identificar problemáticas de desigualdad que afectan a los estudiantes en los resultados de las pruebas de estado para así que otros miembros del ministerio se encarguen de solventar las problemáticas.
    <li>Un investigador de educación</li>
    Este perfil busca realizar estudios acerca de las distintas afectaciones que pueden modificar el desempeño de los estudiantes.
</ol>
</p>


### Preguntas Correspondientes a cada perfil

<p> Las preguntas elegidas se encontraran subrayadas </p>

Y ahora mostramos el banco de preguntas del cual hicimos la selección:

#### Perfil 1
<ol>
    <li> <ins>¿Los puntajes en matemáticas han mejorado con el tiempo?</ins> </li>
    <li> </ins>¿Cuál es la materia más baja y la materia más alta?</ins> </li>
    <li> ¿Los estudiantes de colegios privados tienen mejores resultados en matemáticas que los de colegios públicos? </li>
    <li> ¿Cuál ha sido la evolución del puntaje global en los últimos años? </li>
    <li> ¿Los estudiantes que presentan la prueba en un departamento diferente al que residen tienen un puntaje diferente al de quienes la presentan en su lugar de residencia? </li>
</ol>

#### Perfil 2
<ol>
    <li>¿La edad influye en los resultados de los ICFES?</li>
    <li> <ins>¿El nivel educativo de los padres influye en los puntajes de los estudiantes?</ins> </li>
    <li>¿Existe una relación entre el número de habitaciones del hogar y el puntaje?  </li>
    <li> <ins>¿Cuál es la relación entre el departamento y el puntaje, hay diferencia regional?</ins>  </li>
    <li>¿El estrato socioeconómico de la familia influye en el resultado? </li>

#### Perfil 3
<ol>
   <li>¿Hay relación entre el acceso a computadores y los resultados? </li>
   <li>¿Existe relación entre el estrato socioeconómico y los puntajes en cada materia? </li>
   <li> <ins>¿Los estudiantes de jornada nocturna tienen puntajes más bajos que los de jornada diurna?</ins> </li>
   <li> <ins>¿El acceso a internet influye en la mejoría de los resultados ICFES?</ins> </li>
   <li>¿Hay relación entre que los estudiantes tengan internet y computador con el departamento? </li>
</ol>

### Herramientas de análisis
En este trabajo utilizamos principalmente 3 librerías de python:
-pandas: Que nos ayudó a leer los archivos csv y navegar entre las filas y columnas de estos para obtener la información.
-Matplotlyb: Que nos ayudó en la generación de gráficos
-Seaborn: Que también está orientada a la visualización de datos pero un poco más simplificada.

### Gráficos utilizados
-Gráficos de Barras, Boxplots, Gráficos de Violín, Histogramas, entre otros.

### Resultados
Los resultados se encuentran disponibles en las carpetas de los perfiles.

### Conclusiones
