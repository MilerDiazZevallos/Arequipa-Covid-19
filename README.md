Data Analytics COVID-19 Arequipa, Peru (Actualizado, 09 Agosto 2020)
=============

Este es un análisis de la situación actual que se vive en la Región Arequipa a causa de la pandemia del Coronavirus.

Dentro del estudio podemos apreciar diferentes métricas con dos distintos datasets: MINSA (Ministerio de Salud del Perú) y GERESA (Gerencia Regional de Salud de Arequipa)

Las métricas utilizadas son:

**1. Gráficas generales del estado actual de muestras, contagios, fallecidos y recuperados.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_1.png)

CONCLUSIONES: Se puede observar como el número de pruebas diarias esta aumentando, lo que en realidad es un factor positivo.

Actualización(2020-07-31): La cantidad de muestras realizadas tuvieron un descenso importante al inicio de esta semana, pero volvieron a tener un aumento considerable al final de la misma. Es un factor importante que podemos tomarlo como positivo.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_2.png)

CONCLUSIONES: Se puede observar como el número de casos positivos también esta aumentando. Haciendo un análisis de regresión, la tendencia es que vaya en aumento.

Actualización(2020-07-28): La tendencia de los últimos días es que los contagios llegaron a estabilizarse.

Actualización(2020-07-31): Al igual que la cantidad de muestras, el inicio de la semana la cantidad de personas confirmadas disminuyo, pero los últimos días volvió a aumentar y mantiene una tendencia a aumentar. Un factor negativo lamentablemente.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_3.png)

CONCLUSIONES: Se puede observar como el número de fatalidades también esta aumentando. Haciendo un análisis de regresión, la tendencia es que vaya en aumento pero la pendiente no es tan elevada.

Actualización(2020-07-28): El número de fallecidos esta disminuyendo diariamente.

Actualización(2020-07-31): Este factor tiene un tendencia a disminuir, a diferencia de la cantidad de contagiados, este es una excelente noticia.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_4.png)

CONCLUSIONES: Este es una de las principales métricas y se ve que la positividad va a aumentar y estará entre un 17 y 23% en las proximas semanas.

Actualización(2020-07-28): La positividad empezó a estabilizarse.

Actualización(2020-07-31): La positividad nuevamente tiende a incrementar pero esta vez estara entre un 20 y un 25%. Malas noticias.

**2. Factor Salud - Hospitalizados y UCI.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_5.png)

CONCLUSIONES: Esta métrica es bien dinámica, esto debido a que diariamente las personas entran y salen de la hospitalización. Desde hace 15 días atrás esta métrica se mantiene estable y el análisis de regresión manifiesta que la tendencia es que disminuya, otro factor positivo ya que mientras la cantidad de hospitalizados disminuya habrá más camas disponibles para las otras personas que lleguen con el virus.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_6.png)

CONCLUSIONES: Esta métrica, como la anterior, también es bien dinámica, esto debido a que diariamente las personas entran y salen de las UCIs y algunas de ellas fallecen. A diferencia de la cantidad de hospitalizados, esta métrica esta disminuyendo desde hace 15 días aproximadamente, es un factor positivo solo por el hecho de que habrán más camas UCI disponibles, pero a su vez es negativa por que algunas de las personas fallecieron.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_7.png)

CONCLUSIONES: En este gráfico se aprecian las fluctuaciones de los hospitalizados en el tiempo, se puede observar que los días 2020-06-29, 2020-07-11 y 2020-07-25 hubieron una cantidad de personas hospitalizadas muy superior al promedio, esto ocasionó caos en algunos hospitales de la región. De forma general, esta métrica se mantiene estable.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_8.png)

CONCLUSIONES: En este gráfico se aprecian las fluctuaciones de las personas internadas en UCI en el tiempo, se puede observar que las fluctuaciones de esta métrica tiene muchas variaciones. De forma general, se observar que el promedio de 7 días esta por debajo del promedio, esto es un factor positivo.

**3. Factor Rt. Factor de reproducción del virus.**

Referencias:

https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb

https://medium.com/@rburhum/el-martillazo-y-el-huayno-278716f49938

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_9.png)

CONCLUSIONES: Este es otra de las principales métricas y se ve que el Factor R se mantiene constante entre 1.3 y 1.4. Este dato es muy preocupante debido a que otros estudios realizados con los datos de todo el país, el tiempo para que este valor este por debajo de 1 es más de un mes. Esto indica a que los contagios no estaran controlados en mínimo un 1 hacia adelante.

Actualización(2020-07-28): El factor R esta disminuyendo rapidamente, esto es sumamente bueno.

Actualización(2020-07-31): Este factor tuvo un declive muy positivo pero nuevamente subio y se posicionó en 1.24, es muy fluctuante pero se espera que vuelva su tendencia a disminuir.

**4. Doubling time. Periodo de tiempo en el que el virus se duplicará.**

Referencias:

https://github.com/COVID-19-AI-Research-Project/AI-Data-Analysis/blob/master/Projects/1/Prediction_Covid_19_WorldWide.ipynb

https://www.npr.org/sections/health-shots/2020/04/10/829167659/are-we-flattening-the-curve-states-keep-watch-on-coronavirus-doubling-times

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_10.png)

CONCLUSIONES: Esta métrica mide el número de días que los contagios se duplicarán. Con los datos actuales de Arequipa se puede observar que los contagios se duplican cada 15 días. Mientras este valor aumente las medidas en que se están tomando son las adecuadas, pero el caso es totalmente contrario en Arequipa donde la tendencia es a disminuir.

Actualización(2020-07-28): Por fin se puede apreciar una tendencia a subir este factor, se espera mucho más.

Actualización(2020-07-31): La tendencia de este factor sigue en aumento, ahora se encuentra en 16 días, esperemos que siga aumentando.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_11.png)

CONCLUSIONES: Esta métrica mide el número de días que las fatalidades se duplicarán. Con los datos actuales de Arequipa se puede observar que las fatalidades se duplican también cada 15 días. Caso contrario a los contagios, la tendencia de esta métrica en las fatalidades esta aumentando y ese es un factor positivo.

Actualización(2020-07-28): Este factor en fallecidos pasó de 15 a 17 días, son excelentes noticias.

Actualización(2020-07-31): Esta tendencia es muy positiva, ahora se encuentra en 18 días. Son excelentes noticias y esperemos que siga aumentando.

**5. Activos, Recuperados y Fallecidos.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_12.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_13.png)

CONCLUSIONES: En este gráfico se puede ver, que a diferencia de los datos de todo el Perú, el area de los activos son más que los recuperados.

Actualización(2020-07-28): Ya casi la cantidad de recuperados es el mismo a los contagiados. Esto no significa que todas las personas contagiadas ya están recuperadas, sino que el número de recuperadas acumuladas esta por alcanzar al número de personas contagiadas acumuladas.

Actualización(2020-07-31): A inicios de esta semana se dio un hecho nunca visto y es que la cantidad de recuperados fue mayor a la cantidad de contagiados en el acumulado, pero a finales de la misma, la cantidad de contagiados volvió a ser mayor. Siendo optimista y viendo el esfuerzo que el sector salud esta poniendo al controlar la pandemia, se cree que en la próxima semana la cantidad de recuperados vuelva a ser mayor.

**6. Confirmados diarios vs Recuperados diarios**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_14.png)

CONCLUSIONES: En este gráfico se puede ver que solo entre el 20 y el 25 de Mayo la tasa de recuperados supero a la de contagiados, luego las tasa de recuperados es inferior a los contagiados.

Actualización(2020-07-28): El promedio de los últimos 7 días esta aumentando, que excelente.

Actualización(2020-07-31): Como se pudo ver en las gráficas anteriores, la cantidad de recuperados aumentó considerablemente, esto también se puede observar en este gráfico donde el promedio de los últimos 7 días esta aumentando. Se tiene que revisar la siguiente semana.

**7. Metodo SIR. Un modelo que grafíca el ciclo de vida del virus.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_15.png)

CONCLUSIONES: Esta función grafíca el comportamiento del coronavirus con los datos de Arequipa. Los datos importantes son:

Poblacion de Arequipa: 1503547
Contact rate (beta) : Diversos estudios catalogarón que en esta pandemia este valor se encontraría entre 0.2 y 0.3. (Se necesita mas investigación pero en caso del Perú un beta de 0.15 gráfica mejor la situación actual).
Mean recovery rate (gamma): Básicamente este valor es 1/<Periodo de incubación>. Este dato para Perú es de 14 días.

Se puede observar que el límite de contagios en Arequipa llegaría en aproximadamente al día 170 y 180 que se inició la pandemia. Esto sería en un mes aproximadamente.

Actualización(2020-07-28): Según todas las métricas, puede que se llegue al pico de contagiados algunas semanas antes de lo esperado.

**8. Estudio de días donde se contagian más las personas.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_16.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_17.png)

CONCLUSIONES: Esta, aunque no parezca, es una métrica importante; indica, aproximadamente, cuando es que las personas de Arequipa contraen el virus. Según la OMS, el virus tiende a provocar sintomas entre 5 y 6 días después de la exposición (pero pude variar entre 1 y 14 días), debido a la actual realidad de Arequipa (la temporada de invierno), en este estudio se cree que los sintomas tienden a aparecer lo mas antes posible (5 días).

Como vemos en las gráficas, los días (dentro de la provincia de Arequipa), más personas son diagnosticadas con COVID-19 son los MIERCOLES y SABADOS, si a estos días le quitamos los 5 días que demoraría una persona normal en tener los sintomas, eso quiere decir que las personas tienden a contagiarse más los días SABADOS y MARTES. SE SUGIERE A LAS PERSONAS NO SALIR LOS DIAS SABADO, LUNES Y MARTES

Referencia : https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/naming-the-coronavirus-disease-(covid-2019)-and-the-virus-that-causes-it

Tenemos que notar que los datos para esta métrica son extraídos de los datos liberados del MINSA.

**9. Análisis por etapas y edad de las personas.**

Este análisis se realizó debido a que en los últimos días, y según las noticias, la cantidad de menores de edad contagiados del COVID-19 aumentó y queremos ver si esto se puede apreciar en los datos. Cabe mencionar que este y el siguiente análisis son realizados con datos del MINSA y solo dentro de la provincia de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_18.png)

Actualización(2020-07-31): En el gráfico anterior se puede ver que la mayor cantidad de contagiados, todos los días, se ubican dentro del intervalo de los 26 a 60 años. Un factor importante a notar es que desde el 15 de Julio aumentó la cantidad de jovenes, adolescentes, niños e infantes que contraen el virus, esperemos que el sector salud investigue un poco las causas de este comportamiento.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_19.png)

Actualización(2020-07-31): Con la finalidad de observar mejor el incremento de contagio dentro de las personas menores a los 25 años, se desarrollo el gŕafico anterior donde se normalizaron los contagios a un 100%. En este gráfico se observa que desde el 2020-06-04 la cantidad de personas contagidas mayores de 60 años aumento considerablemente y se posicionó como el segundo grupo con mas contagios solo por debajo de los adultos. También se puede apreciar claramente que en las 2 últimas semanas la cantidad de personas menores de 25 años (jovenes, adolescentes, niños e infantes) aumentó. Entonces la noticias de que existen más personas menores de 25 años, incluido niños e infantes, que se están contagiando es cierta.

**10. Comparación con datos del SINADEF.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_20.png)

Actualización(2020-08-07): Comparación anual y semanal de los datos del SINADEF en el Perú.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_21.png)

Actualización(2020-08-07): Comparación anual y semanal de los datos del SINADEF en el departamento de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_22.png)

Actualización(2020-08-07): Comparación anual y semanal entre los datos del SINADEF y los de la GERESA en el departamento de Arequipa.

**11. Diversos estudios aún no finalizados.**
