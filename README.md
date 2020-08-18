Data Analytics COVID-19 Arequipa, Peru (Actualizado, 17 Agosto 2020)
=============

Este es un análisis de la situación actual que se vive en la Región Arequipa a causa de la pandemia del Coronavirus.

Dentro del estudio podemos apreciar diferentes métricas con dos distintos datasets: MINSA (Ministerio de Salud del Perú), GERESA (Gerencia Regional de Salud de Arequipa) y SINADEF (Sistema de Informacion Nacional de Defunciones)

Las métricas utilizadas son:

**1. Gráficas generales del estado actual de cantidad de muestras, cantidad de contagios, cantidad de fallecidos y positividad diaria (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_1.png)

Actualización(10-08-2020): La cantidad de muestras realizadas en promedio durante los últimos 7 días no muestran una tendencia a incrementarse, se puede observar que desde la segunda quincena de Julio el promedio de pruebas diarias se mantiene en una pequeña meseta.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_2.png)

Actualización(10-08-2020): A diferencia de la semana antepasada, donde se puede observar que los contagios disminuyeron, esta última semana los contagios volvieron a aumentar aunque no con la misma fuerza que las semanas pasadas.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_3.png)

Actualización(10-08-2020): La semana antepasada la cantidad de personas fallecidas tuvo un decremento importante, pero la semana pasada volieron a aumentar.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_4.png)

Actualización(10-08-2020): La positividad nuevamente tiende a incrementar y se posiciona un 24%, nunca estuvo más alto en promedio para los últimos 7 días. Malas noticias.

**2. Factor Salud - Hospitalizados y UCI (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_5.png)

Actualización(10-08-2020): Esta métrica es bien dinámica, esto debido a que diariamente las personas entran y salen de la hospitalización. Desde hace 15 días atrás esta métrica mantiene un pequeño incremento y el análisis de regresión manifiesta que la tendencia es que se llegó a una meseta, este es un factor positivo ya que mientras la cantidad de hospitalizados no aumente considerablemente, las nuevas camas hospitalarias habilitadas serán utilizadas para otras personas que lleguen con el virus.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_6.png)

Actualización(10-08-2020): Esta métrica, como la anterior, también es bien dinámica, esto debido a que diariamente las personas entran y salen de las UCIs y algunas de ellas fallecen. A diferencia de la cantidad de hospitalizados, esta métrica esta disminuyendo desde hace 30 días aproximadamente, es un factor positivo solo por el hecho de que habrán más camas UCI disponibles, pero a su vez es negativa por que algunas de las personas fallecieron.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_7.png)

Actualización(10-08-2020): En este gráfico se aprecian las fluctuaciones de los hospitalizados en el tiempo, se puede observar que los días 2020-06-29, 2020-07-11 y 2020-07-25 hubieron una cantidad de personas hospitalizadas muy superior al promedio, esto ocasionó caos en algunos hospitales de la región. De forma general, esta métrica se mantiene estable y tiende a una meseta.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_8.png)

Actualización(10-08-2020): En este gráfico se aprecian las fluctuaciones de las personas internadas en UCI en el tiempo, se puede observar que las fluctuaciones de esta métrica tiene muchas variaciones. De forma general, se observar que el promedio de 7 días esta por debajo del promedio, esto es un factor muy positivo ya que se encuentra así los últimos 30 días, esto quiere decir que más personas salen de UCI de las que entran.

**3. Factor Rt. Factor de reproducción del virus (Datos GERESA).**

Referencias:

https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb

https://medium.com/@rburhum/el-martillazo-y-el-huayno-278716f49938

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_9.png)

Actualización(10-08-2020): Este factor tuvo un declive muy positivo pero nuevamente subio y se posicionó en 1.24, es muy fluctuante pero este último domingo tuvo el valor màs bajo desde el inicio de la pandemia 1.04.

**4. Doubling time. Periodo de tiempo en el que el virus se duplicará (Datos GERESA).**

Referencias:

https://github.com/COVID-19-AI-Research-Project/AI-Data-Analysis/blob/master/Projects/1/Prediction_Covid_19_WorldWide.ipynb

https://www.npr.org/sections/health-shots/2020/04/10/829167659/are-we-flattening-the-curve-states-keep-watch-on-coronavirus-doubling-times

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_10.png)

Actualización(10-08-2020): La tendencia de este factor sigue en aumento, ahora se encuentra en 16.5 días, esperemos que siga aumentando.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_11.png)

Actualización(10-08-2020): Esta tendencia es muy positiva, ahora se encuentra en 20 días. Son excelentes noticias y esperemos que siga aumentando.

**5. Activos, Recuperados y Fallecidos (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_12.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_13.png)

Actualización(10-08-2020): Gracias al esfuerzo que el sector salud esta poniendo al controlar la pandemia, la cantidad de personas recuperadas es mayor a la cantidad de personas contagiadas, esto no significa que todas las personas contagiadas ya están recuperadas, sino que el número de recuperadas acumuladas esta por alcanzar al número de personas contagiadas acumuladas. Esta tendencia se mantuvo desde hace 10 días atrás.

**6. Confirmados diarios vs Recuperados diarios (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_14.png)

CONCLUSIONES: En este gráfico se puede ver que solo entre el 20 y el 25 de Mayo la tasa de recuperados supero a la de contagiados, luego las tasa de recuperados es inferior a los contagiados.

Actualización(2020-07-28): El promedio de los últimos 7 días esta aumentando, que excelente.

Actualización(10-08-2020): En este gráfico se puede ver que solo entre el 20 y el 25 de Mayo la tasa de recuperados supero a la de contagiados, actualmente la cantidad de recuperados aumentó considerablemente, esto también se puede observar en este gráfico donde el promedio de los últimos 7 días esta aumentando.

**7. Metodo SIR. Un modelo que grafíca el ciclo de vida del virus (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_15.png)

CONCLUSIONES: Esta función grafíca el comportamiento del coronavirus con los datos de Arequipa. Los datos importantes son:

Poblacion de Arequipa: 1503547
Contact rate (beta) : Diversos estudios catalogarón que en esta pandemia este valor se encontraría entre 0.2 y 0.3. (Se necesita mas investigación pero en caso del Perú un beta de 0.15 gráfica mejor la situación actual).
Mean recovery rate (gamma): Básicamente este valor es 1/<Periodo de incubación>. Este dato para Perú es de 14 días.

Se puede observar que el límite de contagios en Arequipa llegaría en aproximadamente al día 170 y 180 que se inició la pandemia. Esto sería en un mes aproximadamente.

Actualización(2020-07-28): Según todas las métricas, puede que se llegue al pico de contagiados algunas semanas antes de lo esperado.

**8. Estudio de días donde se contagian más las personas (Datos MINSA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_16.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_17.png)

Actualización(10-08-2020): Esta, aunque no parezca, es una métrica importante; indica, aproximadamente, cuando es que las personas de Arequipa contraen el virus. Según la OMS, el virus tiende a provocar sintomas entre 5 y 6 días después de la exposición (pero pude variar entre 1 y 14 días), debido a la actual realidad de Arequipa (la temporada de invierno), en este estudio se cree que los sintomas tienden a aparecer lo mas antes posible (5 días).

Como vemos en las gráficas, los días (dentro de la provincia de Arequipa), más personas son diagnosticadas con COVID-19 son los MIERCOLES y SABADOS, si a estos días le quitamos los 5 días que demoraría una persona normal en tener los sintomas, eso quiere decir que las personas tienden a contagiarse más los días SABADOS y MARTES. SE SUGIERE A LAS PERSONAS NO SALIR LOS DIAS SABADO, LUNES Y MARTES

Referencia : https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/naming-the-coronavirus-disease-(covid-2019)-and-the-virus-that-causes-it

Tenemos que notar que los datos para esta métrica son extraídos de los datos liberados del MINSA.

**9. Análisis por etapas y edad de las personas (Datos MINSA).**

Este análisis se realizó debido a que en los últimos días, y según las noticias, la cantidad de menores de edad contagiados del COVID-19 aumentó y queremos ver si esto se puede apreciar en los datos. Cabe mencionar que este y el siguiente análisis son realizados con datos del MINSA y solo dentro de la provincia de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_18.png)

Actualización(10-08-2020): En el gráfico anterior se puede ver que la mayor cantidad de contagiados, todos los días, se ubican dentro del intervalo de los 26 a 60 años. Un factor importante a notar es que desde el 15 de Julio aumentó la cantidad de jovenes, adolescentes, niños e infantes que contraen el virus, esperemos que el sector salud investigue un poco las causas de este comportamiento.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_19.png)

Actualización(10-08-2020): Con la finalidad de observar mejor el incremento de contagio dentro de las personas menores a los 25 años, se desarrollo el gŕafico anterior donde se normalizaron los contagios a un 100%. En este gráfico se observa que desde el 2020-06-04 la cantidad de personas contagidas mayores de 60 años aumento considerablemente y se posicionó como el segundo grupo con mas contagios solo por debajo de los adultos. También se puede apreciar claramente que en las 2 últimas semanas la cantidad de personas menores de 25 años (jovenes, adolescentes, niños e infantes) aumentó. Entonces la noticias de que existen más personas menores de 25 años, incluido niños e infantes, que se están contagiando es cierta.

**10. Comparación con datos del SINADEF (Datos SINADEF).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_20.png)

Actualización(10-08-2020): Este gráfico es una comparación anual y semanal de los datos del SINADEF en el Perú en los años anteriores. Se puede ver que en todo el Perú apartir de la semana 15 de este año las defunciones aumentaron de forma exponencial y llego a un pico en la semana 24. A diferencia de otros años, la influencia del Coronavirus marcará un hito importante en el número de defunciones en el Perú.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_24.png)

Actualización(10-08-2020): Este gráfico es una comparación anual y semanal de los datos del SINADEF en todos los departamentos del Perú en los años anteriores.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_21.png)

Actualización(10-08-2020): Este gráfico es una comparación anual y semanal de los datos del SINADEF en el departamento de Arequipa. A diferencia del gráfico anterior, en Arequipa el impacto del Coronavirus en las defunciones empezó en la semana 21 y llegó (al parecer) a un pico en la semana 30. Según las tendencias de otras regiones y el decremento de las últimas dos semanas, se puede pensar que ya pasó el pico de defunciones en el departamento de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_25.png)

Actualización(10-08-2020): Este gráfico es una comparación anual y diario de los datos del SINADEF en el departamento de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_22.png)

Actualización(10-08-2020): Este gráfico es una comparación anual y semanal entre los datos del SINADEF y los de la GERESA en el departamento de Arequipa. Como los datos del SINADEF son de todos los tipos de defunciones dentro del Perú, para la comparación con los datos de la GERESA (que son solamente causadas por el Coronavirus) se filtraron los datos del SINADEF por los siguientes critérios: 

1. Departamento de Arequipa.
2. Muertes no violentas
3. Causas del tipo U07
4. Aquellas defunciones que contengan las palabras "covid" y "coronavirus". 

Se puede apreciar que los datos del SINADEF soy mucho mayores que los datos expuestos por la GERESA. Esta métrica es muy variable debido a que la aplicación de los filtros puede causar una distorsión en los resultados, pero lo que es cierto es que las defunciones por motivos del Coronavirus que el SINADEF registra son mayores.

**11. Factores de Riesgo con datos del SINADEF (Datos SINADEF).**

El objetivo de este estudio es encontrar las causas o factores de riesgo más probables que acompañan a las defunciones por Coronavirus en el departamento de Arequipa. Para lo cual primero se aplicaron algunas técnicas de NLP (Natural Language Processing) para encontrár clusters de las causas de defunciones sobre los datos del SINADEF. Para medir solo el impacto del virus de este departamento, solo se tomarón en cuenta datos de este año y solo del departamento de Arequipa.

Referencia: https://www.kaggle.com/maksimeren/covid-19-literature-clustering

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_23.png)

Actualización(10-08-2020): En el gráfico anterior se puede apreciar que el cluster 2 (que es el que representa a las defunciones por Coronavirus), se diferencia de los otros clusters, lo que hace posbiel el entrenamiento de un modelo para predecir las defunciones por este virus (este es un estudio a realizarse).

Los factores de riesgo que representan el cluster 2 esta compuesto por las siguientes 40 palabras principales (palabra y frecuencia):

1. 'respiratoria': 1884, 
2. 'insuficiencia': 1685, 
3. 'neumonia': 1366, 
4. 'covid': 1350, 
5. 'j960': 1190, 
6. 'u071': 1117, 
7. '19': 1054, 
8. 'aguda': 1017, 
9. 'u072': 680, 
10. 'virus': 427, 
11. 'j80x': 422, 
12. 'identificado': 398, 
13. 'severa': 308, 
14. 'viral': 303, 
15. 'infeccion': 273, 
16. 'sars': 251, 
17. 'dificultad': 229, 
18. 'j969': 228, 
19. 'sindrome': 219, 
20. 'j129': 214, 
21. 'covid-19': 198, 
22. '2': 196, 
23. 'j189': 187, 
24. 'arterial': 185, 
25. 'atipica': 176, 
26. 'i10x': 175, 
27. 'hipertension': 170, 
28. 'cov': 160, 
29. 'diabetes': 152, 
30. 'mellitus': 147, 
31. 'j128': 141, 
32. 'adulto': 132, 
33. 'coronavirus': 126, 
34. 'j22x': 124, 
35. 'obesidad': 120, 
36. 'covid19': 113, 
37, 'falla': 108, 
38. 'sospechoso': 105, 
39. 'caso': 95, 
40. 'infección': 92, 

La nube de palabras que se puede obtener del topico del cluster 1 es:

![](https://drive.google.com/uc?export=view&id=1mT00AP58ek6SKbZpsW3bXZjlVO-5W56T)

Algunos de los codigos importantes son y factores de riesgo mas importantes son:

1. j960: INSUFICIENCIA RESPIRATORIA
2. u071: COVID-19 IDENTIFICADO
3. u072: COVID-19 NO IDENTIFICADO
4. j80x: SÍNDROME DE DIFICULTAD RESPIRATORIA AGUDA
5. j969: INSUFICIENCIA RESPIRATORIA AGUDA
6. j129: NEUMONIA VIRAL
7. j189: NEUMONIA
8. i10x: HIPERTENSION ARTERIAL
9. j128: NEUMONIA ATIPICA
10. j22x: INFECCIÓN DE VÍAS RESPIRATORIAS BAJAS

**12. Diversos estudios aún no finalizados.**
