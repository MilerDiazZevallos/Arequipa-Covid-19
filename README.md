Data Analytics COVID-19 Arequipa, Peru (Actualizado, 13 Setiembre 2020)
=============

Este es un análisis de la situación actual que se vive en la Región Arequipa a causa de la pandemia del Coronavirus.

Dentro del estudio podemos apreciar diferentes métricas con tres distintos datasets: MINSA (Ministerio de Salud del Perú), GERESA (Gerencia Regional de Salud de Arequipa) y SINADEF (Sistema de Informacion Nacional de Defunciones)

Todos estos análisis vienen siendo desarrollados por:

MSc. Miler Diaz Zevallos

DSc. student Jenny Copara Zea

DSc. Yvan Tupac Valdivia

Las métricas utilizadas son:

**1. Gráficas generales del estado actual de cantidad de muestras, cantidad de contagios, cantidad de fallecidos y positividad diaria (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_1.png)

Actualización(02-09-2020): La cantidad de muestras realizadas en promedio durante los últimos 7 días no muestran una tendencia a incrementarse, se puede observar que desde la segunda quincena de Julio el promedio de pruebas diarias se mantiene en una pequeña meseta (Aprox 7000 al día).

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_2.png)

Actualización(02-09-2020): A diferencia de la semana antepasada, donde se puede observar que los contagios llegarón a un pico, esta última semana los contagios volvieron a decrecer con una pendiente no vista en semanas pasadas, por debajo de los 1500 confirmados al día.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_3.png)

Actualización(02-09-2020): Desde hace dos semanas atrás la cantidad de personas fallecidas se mantuvieron por debajo de 20, esperamos que siga disminuyendo.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_4.png)

Actualización(02-09-2020): La positividad tiende a disminuir y se posiciona un 20%, la pendiente también tiende positivamente a la baja. Buenas noticias.

**2. Factor Salud - Hospitalizados y UCI (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_5.png)

Actualización(02-09-2020): Esta métrica es bien dinámica, esto debido a que diariamente las personas entran y salen de la hospitalización. Desde hace 60 días atrás esta métrica mantiene un pequeño incremento diario y el análisis de regresión manifiesta que la tendencia es que se llegó a una meseta, este es un factor positivo ya que mientras la cantidad de hospitalizados no aumente considerablemente, las nuevas camas hospitalarias habilitadas serán utilizadas para otras personas que lleguen con el virus. Los ultimos 4 días mostrarón una tendencia a disminuir, es muy bueno.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_6.png)

Actualización(02-09-2020): Esta métrica, como la anterior, también es bien dinámica, esto debido a que diariamente las personas entran y salen de las UCIs y algunas de ellas fallecen. A diferencia de la cantidad de hospitalizados, esta métrica estaba disminuyendo desde hace 60 días aproximadamente hasta la semana antepasada, la semana pasada hubo una disminución muy significativa en las personas que se encuentran en UCI.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_7.png)

Actualización(02-09-2020): En este gráfico se aprecian las fluctuaciones de los hospitalizados en el tiempo, se puede observar que los días 2020-06-29, 2020-07-11 y 2020-07-25 hubieron una cantidad de personas hospitalizadas muy superior al promedio, esto ocasionó caos en algunos hospitales de la región. De forma general, esta métrica se mantiene estable y tiende a una meseta.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_8.png)

Actualización(18-08-2020): En este gráfico se aprecian las fluctuaciones de las personas internadas en UCI en el tiempo, se puede observar que las fluctuaciones de esta métrica tiene muchas variaciones. De forma general, se observar que el promedio de 7 días, esta última semana, tuvo un deremento muy significativo. Otra muy buena noticia.

**3. Factor Rt. Factor de reproducción del virus (Datos GERESA).**

Referencias:

https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb

https://medium.com/@rburhum/el-martillazo-y-el-huayno-278716f49938

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_9.png)

Actualización(02-09-2020): Este factor tuvo un declive muy positivo y por primera vez está por debajo de 1 (se ubica en 0.94), que es el objetivo principal para controlar la reproduccion del virus. Esto es EXCELENTE.

**4. Doubling time. Periodo de tiempo en el que el virus se duplicará (Datos GERESA).**

Referencias:

https://github.com/COVID-19-AI-Research-Project/AI-Data-Analysis/blob/master/Projects/1/Prediction_Covid_19_WorldWide.ipynb

https://www.npr.org/sections/health-shots/2020/04/10/829167659/are-we-flattening-the-curve-states-keep-watch-on-coronavirus-doubling-times

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_10.png)

Actualización(02-09-2020): La tendencia de este factor sigue en aumento, ahora se encuentra en 19 días, esperemos que siga aumentando. Esta métrica significa que las personas contagiadas se duplicán cada 23 días.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_11.png)

Actualización(02-09-2020): Esta tendencia es muy positiva, ahora se encuentra en 23 días. Son excelentes noticias y esperemos que siga aumentando. Esta métrica significa que las personas fallecidas se duplicán cada 27 días.

**5. Activos, Recuperados y Fallecidos (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_12.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_13.png)

Actualización(02-09-2020): Gracias al esfuerzo que el sector salud esta poniendo al controlar la pandemia, la cantidad de personas recuperadas es mucho mayor a la cantidad de personas contagiadas, esto no significa que todas las personas contagiadas ya están recuperadas, sino que el número de recuperadas acumuladas es mucho mayor al número de personas contagiadas acumuladas. Esta tendencia se mantuvo desde hace 45 días atrás. EXCELENTE.

**6. Confirmados diarios vs Recuperados diarios (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_14.png)

Actualización(02-09-2020): Se puede ver que solo entre el 20 y el 25 de Mayo la tasa de recuperados supero a la de contagiados, actualmente la cantidad de recuperados aumentó considerablemente, esto también se puede observar en este gráfico donde el promedio de los últimos 7 días, esta última semana, esta aumentando. Esperemos que la tendencia siga.

**7. Metodo SIR. Un modelo que grafíca el ciclo de vida del virus (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_15.png)

CONCLUSIONES: Esta función grafíca el comportamiento del coronavirus con los datos de Arequipa. Los datos importantes son:

Poblacion de Arequipa: 1503547
Contact rate (beta) : Diversos estudios catalogarón que en esta pandemia este valor se encontraría entre 0.2 y 0.3. (Se necesita mas investigación pero en caso del Perú un beta de 0.15 gráfica mejor la situación actual).
Mean recovery rate (gamma): Básicamente este valor es 1/<Periodo de incubación>. Este dato para Perú es de 14 días.

Se puede observar que el límite de contagios en Arequipa llegaría en aproximadamente al día 170 y 180 que se inició la pandemia. Esto sería en un mes aproximadamente.

Actualización(02-09-2020): Según todas las métricas, puede que se llegue al pico de contagiados esta semana.

**8. Estudio de días donde se contagian más las personas (Datos MINSA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_16.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_17.png)

Actualización(02-09-2020): Esta, aunque no parezca, es una métrica importante; indica, aproximadamente, cuando es que las personas de Arequipa contraen el virus. Según la OMS, el virus tiende a provocar sintomas entre 5 y 6 días después de la exposición (pero pude variar entre 1 y 14 días), debido a la actual realidad de Arequipa y algunos comentarios de doctores del departamento de Arequipa, en este estudio se cree que los sintomas tienden a aparecer pasados 10 días después de la exposición.

Como vemos en las gráficas, los días (dentro de la provincia de Arequipa), más personas son diagnosticadas con COVID-19 son los MIERCOLES, si a estos días le quitamos los 10 días que demoraría una persona normal en tener los sintomas, eso quiere decir que las personas tienden a contagiarse más LUNES. SE SUGIERE A LAS PERSONAS NO SALIR ESTE DIA.

Referencia : https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/naming-the-coronavirus-disease-(covid-2019)-and-the-virus-that-causes-it

Tenemos que notar que los datos para esta métrica son extraídos de los datos liberados del MINSA.

**9. Análisis por etapas y edad de las personas (Datos MINSA).**

Este análisis se realizó debido a que en los últimos días, y según las noticias, la cantidad de menores de edad contagiados del COVID-19 aumentó y queremos ver si esto se puede apreciar en los datos. Cabe mencionar que este y el siguiente análisis son realizados con datos del MINSA y solo dentro de la provincia de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_18.png)

Actualización(02-09-2020): En el gráfico anterior se puede ver que la mayor cantidad de contagiados, todos los días, se ubican dentro del intervalo de los 26 a 60 años. Un factor importante a notar es que desde el 15 de Julio aumentó la cantidad de jovenes, adolescentes, niños e infantes que contraen el virus, esperemos que el sector salud investigue un poco las causas de este comportamiento.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_19.png)

Actualización(02-09-2020): Con la finalidad de observar mejor el incremento de contagio dentro de las personas menores a los 25 años, se desarrollo el gŕafico anterior donde se normalizaron los contagios a un 100%. En este gráfico se observa que desde el 2020-06-04 la cantidad de personas contagidas mayores de 60 años aumento considerablemente y se posicionó como el segundo grupo con mas contagios solo por debajo de los adultos. También se puede apreciar claramente que en las 6 últimas semanas la cantidad de personas menores de 25 años (jovenes, adolescentes, niños e infantes) aumentó. Entonces la noticias de que existen más personas menores de 25 años, incluido niños e infantes, que se están contagiando es cierta.

**10. Comparación con datos del SINADEF (Datos SINADEF).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_20.png)

Actualización(02-09-2020): Este gráfico es una comparación anual y semanal de los datos del SINADEF (número de fallecidos) en el Perú en los años anteriores. Se puede ver que en todo el Perú apartir de la semana 15 de este año las defunciones aumentaron de forma exponencial y llego a un pico en la semana 24. A diferencia de otros años, la influencia del Coronavirus marcará un hito importante en el número de defunciones en el Perú. Estas 3 últimas semanas las defunciones disminuyeron considerablemente. Mas buenas noticias.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_24.png)

Actualización(02-09-2020): Este gráfico es una comparación anual y semanal de los datos del SINADEF en todos los departamentos del Perú en los años anteriores. Podemos ver que departamentos como Ucayali y Loreto ya pasaron lo mas preocupante y alcanzarón lo que se denomina "la inmunidad del rebaño", pero otros departamentos como Puno y Cuzco aún se encuentran en la etapa más preocupante, pero están disminuyendo. En relación a Arequipa se puede ver que las defunciones estas 4 últimas semanas disminuyeron considerablemente ¿Será que estamos logrando la ansiada "imnunidad del rebaño"?

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_21.png)

Actualización(02-09-2020): Este gráfico es una comparación anual y semanal de los datos del SINADEF en el departamento de Arequipa. A diferencia del gráfico anterior, en Arequipa el impacto del Coronavirus en las defunciones empezó en la semana 21 y llegó (al parecer) a un pico en la semana 30. Según las tendencias de otras regiones y el decremento de las últimas 4 semanas, se puede pensar que ya pasó el pico de defunciones en el departamento de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_25.png)

Actualización(02-09-2020): Este gráfico es una comparación anual y diario de los datos del SINADEF en el departamento de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_22.png)

Actualización(02-09-2020): Este gráfico es una comparación anual y semanal entre los datos del SINADEF y los de la GERESA en el departamento de Arequipa. Como los datos del SINADEF son de todos los tipos de defunciones dentro del Perú, para la comparación con los datos de la GERESA (que son solamente causadas por el Coronavirus) se filtraron los datos del SINADEF por los siguientes critérios: 

1. Departamento de Arequipa.
2. Muertes no violentas
3. Causas del tipo U07
4. Aquellas defunciones que contengan las palabras "covid" y "coronavirus". 

Se puede apreciar que los datos del SINADEF soy mucho mayores que los datos expuestos por la GERESA. Esta métrica es muy variable debido a que la aplicación de los filtros puede causar una distorsión en los resultados, pero lo que es cierto es que las defunciones por motivos del Coronavirus que el SINADEF registra son mayores.

**11. Factores de Riesgo con datos del SINADEF (Datos SINADEF).**

El objetivo de este estudio es encontrar las causas o factores de riesgo más probables que acompañan a las defunciones por Coronavirus en el departamento de Arequipa. Para lo cual primero se aplicaron algunas técnicas de NLP (Natural Language Processing) para encontrár clusters de las causas de defunciones sobre los datos del SINADEF. Para medir solo el impacto del virus de este departamento, solo se tomarón en cuenta datos de este año y solo del departamento de Arequipa.

Referencia: https://www.kaggle.com/maksimeren/covid-19-literature-clustering

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_23.png)

Actualización(02-09-2020): En el gráfico anterior se puede apreciar que el cluster 3 es el que representa a las defunciones por Coronavirus.

Los factores de riesgo que representan el cluster 3 esta compuesto por las siguientes 50 palabras principales (palabra y frecuencia):

1. 'respiratoria': 2002
2. 'insuficiencia': 1787
3. 'covid': 1493
4. 'neumonia': 1427
5. 'j960': 1276
6. '19': 1164
7. 'u071': 1148
8. 'aguda': 1129
9. 'u072': 736
10. 'virus': 484
11. 'identificado': 447
12. 'j80x': 423
13. 'viral': 330
14. 'severa': 313
15. 'infeccion': 273
16. 'j969': 251
17. 'dificultad': 246
18. 'j129': 232
19. 'sindrome': 232
20. 'covid-19': 223
21. 'j189': 215
22. 'arterial': 194
23. 'atipica': 187
24. 'sars': 187
25. 'i10x': 182
26. 'hipertension': 181
27. 'diabetes': 163
28. 'mellitus': 161
29. '2': 154
30. 'adulto': 143
31. 'j128': 135
32. 'j22x': 133
33. 'obesidad': 120
34. 'falla': 120
35. 'coronavirus': 113
36. 'covid19': 113
37. 'sospechoso': 111
38. 'cov': 106
39. 'caso': 104
40. 'especificada': 96
41. 'e669': 88
42. 'infección': 88
43. 'multiorganica': 79
44. 'renal': 77
45. 'neumonía': 65
46. 'confirmado': 64
47. 'enfermedad': 58
48. 'shock': 58
49. 'respiratorio': 58
50. 'r579': 58

La nube de palabras que se puede obtener del topico del cluster 3 es:

![](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/factores_riesgo.jpg)

Algunos de los factores de riesgo más importantes son:

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
11. DIABETES.
12. NEUMONÍA.

**12. Diversos estudios aún no finalizados.**
