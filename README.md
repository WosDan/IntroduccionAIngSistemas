# IntroduccionAIngSistemas
Proyecto hecho por:

-José Angulo

-Daniel Rincón

-Sebastián Ibáñez

# Introducción
En este repositorio utilizamos una base de datos que contiene los detalles de las pruebas saber 11 de los años 2010 a 2022, se ocuparon 3 perfiles con diferente enfoque. Cada uno de estos perfiles cuenta con dos preguntas que buscan ser resueltas indagando en la base de datos.


## Metodología
<p>En el contexto de este análisis utilizamos un dataset proveniente de datos.gov.co que contenía información recopilada en las pruebas saber 11 desde el año 2010 al 2022, en el dataset se podían encontrar multiples variables como: </p>

<ul>
    <li>Los puntajes globales en el ICFES</li>
    <li>Los puntajes correspondientes a cada temática a evaluar (Naturales, Sociales, Matemáticas, Inglés y Lectura Crítica).</li>
    <li>Información socioeconómica del hogar como: el estrato social, el numero de habitaciones, el numero de familiares, si la familia posee lavadora, si posee internet, el acceso a computador, el nivel educativo de los padres.</li>
    <li>Información del estudiante como: su edad, la jornada de su colegio.</li>
    <li>Información sobre el periodo en el que se realizo la prueba.</li>
    <li>Información geográfica como el departamento donde se realizó la prueba.</li>
</ul>

#### Fecha de adquisición

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

<p> Las preguntas elegidas   encontraran subrayadas </p>

Y ahora mostramos el banco de preguntas del cual hicimos la selección:

#### Perfil 1
<ol>
    <li> <ins>¿Los puntajes en matemáticas han mejorado con el tiempo?</ins> </li>
    <li> <ins>¿Cuál es la materia más baja y la materia más alta?</ins> </li>
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
</ol>

#### Perfil 3
<ol>
    <li>¿Hay relación entre el acceso a computadores y los resultados? </li>
    <li>¿Existe relación entre el estrato socioeconómico y los puntajes en cada materia? </li>
    <li> <ins>¿Los estudiantes de jornada nocturna tienen puntajes más bajos que los de jornada diurna?</ins> </li>
    <li> <ins>¿El acceso a internet influye en la mejoría de los resultados ICFES?</ins> </li>
    <li>¿Hay relación entre que los estudiantes tengan internet y computador con el departamento? </li>
</ol>

## Herramientas de análisis
<p>En este trabajo utilizamos principalmente 3 librerías de python:
<ul>
    <li>-pandas: Que nos ayudó a leer los archivos csv y navegar entre las filas y columnas de estos para obtener la información.</li>
    <li>-Matplotlyb: Que nos ayudó en la generación de gráficos</li>
    <li>-Seaborn: Que también está orientada a la visualización de datos pero un poco más simplificada.</li>
</ul>
</p>

## Datos Extráidos
<ul>
    <li>Promedios de cada materia en forma de distintos gráficos.</li>
    <li>Promedios según el nivel de educación de los padres en tablas.</li>
    <li>Promedios globales por departamento.</li>
    <li>Promedios según acceso a internet de los alumnos.</li>
    <li>Acceso a internet en la región en gráficos (frecuencias en gráfico de calor).</li>
    <li>Puntaje de acuerdo al estilo de horario.</li>
    <li>Coeficiente de correlación del puntaje de matemáticas con el periodo.</li>
</u>

### Gráficos utilizados
-Gráficos de Barras, Boxplots, Gráficos de Violín, Histogramas, entre otros.

### Resultados
Los resultados se encuentran disponibles en las carpetas de los perfiles.

##### Perfil 1
```Perfil-1/Pmatematicas-ha-mejorado.ipynb``` 
```Perfil-1/Promedio-por-materia.ipynb```
##### Perfil 2 
```Perfil-2/Nvel-educativo-padres-influye.ipynb``` 
```Perfil-2/PGlobal-por-departamento.ipynb``` 
##### Perfil 3
```Perfil-3/Acceso-a-internet-afecta.ipynb``` 
```Perfil-3/Diferencia-Noct-Diurn.ipynb``` 

## Conclusiones

##### <ins> Antes de leer estas conclusiones es clave aclarar que las conclusiones concretas de cada perfil están en sus documentos en formato ipyb respectivos.</ins>

### Factores que Influyen en el Puntaje Global  

El análisis de los datos revela que diversos factores, como la región de origen, el nivel educativo de los padres, el acceso a internet, la jornada escolar y las diferencias entre materias, tienen un impacto significativo en el desempeño académico de los estudiantes.  

### 🌍 Región de origen y desigualdad educativa  
Los estudiantes provenientes de regiones con mayor desarrollo económico e histórico, como **Bogotá, Cundinamarca, Santander y Boyacá**, presentan puntajes significativamente más altos en comparación con aquellos de regiones con menor economía y mayor presencia de zonas rurales, como **La Guajira, Chocó, Vaupés, Vichada y Guainía**.  

> Esto evidencia la persistente desigualdad en el país, donde el acceso a educación de calidad sigue dependiendo de la ubicación geográfica.  

Además, la **baja densidad poblacional** en algunas regiones amplifica estas dificultades, limitando el acceso a recursos educativos esenciales.  

### 🎓 Nivel educativo de los padres  
Existe una correlación clara entre el **nivel educativo de los padres** y el desempeño académico de sus hijos.  

✅ A mayor nivel educativo de los padres, mayor es el **puntaje global promedio** de los estudiantes.  
✅ La educación de la madre tiene un impacto más pronunciado, lo que podría deberse a una mayor interacción con los hijos en las primeras etapas de aprendizaje.  

### 🌐 Acceso a internet y desigualdad estructural  
Los estudiantes con acceso a internet obtienen en promedio **20 puntos más** que aquellos sin conectividad.  

📌 Sin embargo, esta diferencia no se debe exclusivamente al uso de internet, sino que está ligada a **desigualdades estructurales**, como el **estrato socioeconómico** y la **ubicación geográfica**.  

En regiones con **baja densidad poblacional**, el acceso a internet es significativamente menor, lo que refuerza la brecha educativa y limita las oportunidades de aprendizaje.  

### 📈 Evolución de los puntajes a lo largo del tiempo  
A pesar de que en algunos periodos se han observado mejoras en el puntaje global, el **coeficiente de correlación de Pearson** indica que no existe una relación significativa entre el paso del tiempo y el desempeño académico.  

🔹 Aunque algunos años muestran una mejoría, los cambios son **mínimos** y parecen estar influenciados por otros factores no relacionados con el tiempo.  

🔹 Esto resalta la necesidad de **implementar estrategias efectivas** para mejorar el aprendizaje en el largo plazo.  

### 📚 Diferencias entre materias  
El análisis muestra que las materias con **menor promedio** son:  

- 🟠 **Sociales y ciudadanas**  
- 🔵 **Inglés**  

Por otro lado, la materia con **mayor promedio** es:  

- 📖 **Lectura crítica**  

📊 Sin embargo, materias como **inglés y matemáticas** muestran una **mayor cantidad de estudiantes con puntajes máximos**.  

Esto sugiere que, aunque el **promedio de inglés** sea bajo, tiene más casos de **alto rendimiento** en comparación con **sociales o lectura crítica**, donde es más difícil alcanzar el máximo puntaje.  

### ⏰ Impacto de la jornada escolar  
Los estudiantes de **jornada nocturna** presentan un **desempeño inferior** en comparación con aquellos que asisten a jornadas **matutinas o completas**.  

🔎 Esto puede deberse a:  

- Factores **biológicos**, ya que los seres humanos somos **diurnos** y nuestro rendimiento cognitivo tiende a ser mejor en las mañanas.  
- Diferencias en la **calidad de enseñanza** según el horario.  
- Condiciones **socioeconómicas** de quienes optan por jornadas nocturnas.  

## 🏆 Conclusión general  
Los datos evidencian que el puntaje global en la prueba de estado **no es un simple reflejo de las habilidades individuales**, sino el resultado de **múltiples factores interconectados**, como:  

- 📍 **Región de origen**  
- 🏡 **Acceso a internet**  
- 🎓 **Educación de los padres**  
- 📚 **Condiciones de estudio**  

Para cerrar estas brechas, es fundamental:  

✅ Abordar la **desigualdad estructural** en el acceso a oportunidades educativas.  
✅ Mejorar la enseñanza en **todas las regiones**.  
✅ Garantizar que **factores externos** no limiten el potencial de los estudiantes en el país.  

## 10 Conclusiones finales ☝️🤓
<ol>
    <li>La <em>región de origen</em> puede afectar tu educación.</li>
    <li>El <em>acceso a internet</em> es un gran apoyo para el estudio.</li>
    <li>El <em>nivel educativo</em> al que llegaron a los padres puede afectar de manera <em>positiva</em> a los hijos si fue <em>mayor</em>.</li>
    <li>El tipo de horario o <em>jornada</em> del estudiante afecta su estudio.</li>
    <li>La materia con menor promedio es inglés, sin embargo es más fácil de conseguir la máxima nota.</li>
    <li>La materia con mejor promedio es lectura crítica, pero es más difícil de conseguir la máxima nota.</li>
    <li>El promedio general en materias como matemáticas está <em>estancado</em>.</li>
    <li>Las regiones con menor acceso a internet son las que tienen peor promedio.</li>
    <li>Las regiones menos pobladas son las que peor acceso a internet tienen.</li>
    <li>Las condiciones socioeconómicas de los estudiantes puede condicionar su educación y por tanto su resultado.</li>
</ol> 
