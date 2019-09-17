# ¿Cómo es la relación entre el puntaje de la prueba Saber 11 2019-I y características sociodemográficas del estudiante y el colegio donde estudia?

## Una visualización que permite ver la mediana de los puntajes por departamento, sexo del estudiante, naturaleza del colegio y si posee o no un componente bilingüe.

Las pruebas Saber 11 son un examen de estado aplicado por el Instituto Colombiano para la Evaluación de la Educación (Icfes) a todos los estudiantes de último grado del colegio
el cual les permite validar su bachillerato e incluso, acceder a una educación superior. Como evaluación, el objetivo es medir los conocimientos básicos en múltiples áreas a todos los estudiantes del
territorio colombiano sin exclusión. Sin embargo, los resultados de la prueba alrededor de todo el territorio colombiano dejan ver a la luz que existen patrones "atípicos" de distribuciones inequitativas del puntaje resultado de la prueba.
La siguiente [visualización](https://public.tableau.com/views/Viz3Icfes/Hoja1?:embed=y&:display_count=yes&publish=yes&:origin=viz_share_link) permite descubrir algunos de estos patrones "atípicos". 

<div class='tableauPlaceholder' id='viz1568698227457' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz3Icfes&#47;Hoja1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Viz3Icfes&#47;Hoja1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Vi&#47;Viz3Icfes&#47;Hoja1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div>

Hecha por: [Mónica Gutierrez](https://twitter.com/moni_gutierrezb)

Fuente: [Datos Abiertos](https://www.datos.gov.co/Educaci-n/Saber-11-2019-1/tkn6-e4ic)

La tarea principal de la visualización es permitirle *descubrir* al usuario las diferencias del puntaje mediano entre el sexo del estudiante por departamento y la naturaleza del colegio, dándole prioridad en la comparación a los colegios oficiales, mejor conocidos como colegios públicos. Como tareas adicionales, se le permite al usuario observar si los colegios son o no son bilingües, entendiendo como colegios bilingües los que ofrecen una educación orientada al aprendizaje de una lengua extranjera, con un alto contacto de los estudiantes con la misma: más 50% de su currículo se desarrolla en ella, según el [Ministerio de Educación.](https://www.mineducacion.gov.co/1759/w3-article-364450.html?_noredirect=1)

*¿Qué hay en la visualización? *

La *tabla* utilizada para la visualización contiene información secuencial que contiene *ítems* que corresponden a cada uno de los estudiantes que presentaron la prueba Saber 11 para el periodo 2019-I en todo el país, y *atributos* correspondientes al departamento de residencia del estudiante (categórica), el puntaje global que sacó en el examen (ordenada numérica con un dominio entre 0 y 500 puntos posibles), la naturaleza del colegio de donde está matriculado el estudiante (categórico), si el colegio es o no bilingüe (categórico) y el sexo del estudiante (categórico).
Se debe aclarar que, para realizar la visualización, se realizó un preprocesamiento sencillo de los datos, filtrando la base para seleccionar sólo los estudiantes colombianos. Además, se utiliza la media como punto de referencia de comparación debido a que es una medida de posición que no está influenciada por posibles sesgos en los datos.

*¿Por qué la visualización? *

La visualización se realiza con el fin de que el usuario *descubra* como es el comportamiento del puntaje global de los estudiantes colombianos por departamento, sexo y naturaleza del colegio, para que él *explore* sobre los datos y además *compare* los sesgos que existen en cada una de las variables anteriormente mencionadas. Allí podrá *identificar* visualmente además si existe un componente bilingüe del colegio al que pertenecen los estudiantes. 

*¿Cómo es la visualización? *

La visualización tiene un nivel sencillo de *navegación*, la cual simplemente *expresa* por un canal de posición la mediana calculada de los estudiantes desagregado por diferentes atributos y que además posee un componente de *tono* debido a que es una variable categórica, lo que permite realizar la comparación más eficientemente. Finalmente, se agregó un componente de filtro para las características del colegio para que el usuario pueda ver más detalladamente las comparaciones que la visualización le propone.

*Conclusión*

La visualización le propone al usuario encontrar **insights** como por ejemplo, la mediana del puntaje de las mujeres en el Valle es 23 puntos por encima que el de los hombres en colegio público, mientras que la diferencia para colegio privado es de casi 4 veces por debajo, con una diferencia de 8 puntos. En la Guajira, ocurre un fenómeno similar donde las mujeres superan a los hombres en 24 puntos en dicha prueba dentro de los colegios públicos. Pero la diferencia más grande la presenta Bolívar, con una diferencia de 44 puntos. También se encontró que, según datos reportados, Norte de Santander no posee colegios oficiales, así como Putumayo, Vichada y Chocó, mientras que Guainía sólo tiene colegios oficiales. Lo más particular que permite analizar la visualización es que 15 de los 29 departamentos visualizados, *no* poseen colegios bilingües a pesar de que desde el año 1994, en la Ley General de Educación se reconoció la importancia de aprender una lengua extranjera, así que en la definición de las áreas obligatorias de la básica y de la media incluyó: “Humanidades, lengua castellana e idiomas extranjeros”. Y el único departamento que posee colegios públicos bilingües es César. 

## MIT License

#### Copyright (c) 2019 Mónica Tatiana Gutierrez Ballen.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.








