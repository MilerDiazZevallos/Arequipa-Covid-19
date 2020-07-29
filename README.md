Data Analytics COVID-19 Arequipa, Peru (Updated, July 2020)
=============

Este es un análisis de la situación actual que se vive en la Región Arequipa a causa de la pandemia del Coronavirus.

Dentro del estudio podemos apreciar diferentes métricas con dos distintos datasets: MINSA (Ministerio de Salud del Perú) y GERESA (Gerencia Regional de Salud de Arequipa)

Las métricas utilizadas son:

**1. Gráficas generales del estado actual de muestras, contagios, fallecidos y recuperados.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_1.png)

CONCLUSIONES: Se puede observar como el número de pruebas diarias esta aumentando, lo que en realidad es un factor positivo.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_2.png)

CONCLUSIONES: Se puede observar como el número de casos positivos también esta aumentando. Haciendo un análisis de regresión, la tendencia es que vaya en aumento.

Actualización(2020-07-28): La tendencia de los últimos días es que los contagios llegaron a estabilizarse.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_3.png)

CONCLUSIONES: Se puede observar como el número de fatalidades también esta aumentando. Haciendo un análisis de regresión, la tendencia es que vaya en aumento pero la pendiente no es tan elevada.

Actualización(2020-07-28): El número de fallecidos esta disminuyendo diariamente.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_4.png)

CONCLUSIONES: Este es una de las principales métricas y se ve que la positividad va a aumentar y estará entre un 17 y 23% en las proximas semanas.

Actualización(2020-07-28): La positividad empezó a estabilizarse.

**2. Factor Rt. Factor de reproducción del virus.**

Referencias:

https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb

https://medium.com/@rburhum/el-martillazo-y-el-huayno-278716f49938

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_5.png)

CONCLUSIONES: Este es otra de las principales métricas y se ve que el Factor R se mantiene constante entre 1.3 y 1.4. Este dato es muy preocupante debido a que otros estudios realizados con los datos de todo el país, el tiempo para que este valor este por debajo de 1 es más de un mes. Esto indica a que los contagios no estaran controlados en mínimo un 1 hacia adelante.

Actualización(2020-07-28): El factor R esta disminuyendo rapidamente, esto es sumamente bueno.

**3. Doubling time. Periodo de tiempo en el que el virus se duplicará.**

Referencias:

https://github.com/COVID-19-AI-Research-Project/AI-Data-Analysis/blob/master/Projects/1/Prediction_Covid_19_WorldWide.ipynb

https://www.npr.org/sections/health-shots/2020/04/10/829167659/are-we-flattening-the-curve-states-keep-watch-on-coronavirus-doubling-times

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_6.png)

CONCLUSIONES: Esta métrica mide el número de días que los contagios se duplicarán. Con los datos actuales de Arequipa se puede observar que los contagios se duplican cada 15 días. Mientras este valor aumente las medidas en que se están tomando son las adecuadas, pero el caso es totalmente contrario en Arequipa donde la tendencia es a disminuir.

Actualización(2020-07-28): Por fin se puede apreciar una tendencia a subir este factor, se espera mucho más.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_7.png)

CONCLUSIONES: Esta métrica mide el número de días que las fatalidades se duplicarán. Con los datos actuales de Arequipa se puede observar que las fatalidades se duplican también cada 15 días. Caso contrario a los contagios, la tendencia de esta métrica en las fatalidades esta aumentando y ese es un factor positivo.

Actualización(2020-07-28): Este factor en fallecidos pasó de 15 a 17 días, son excelentes noticias.

**4. Activos, Recuperados y Fallecidos.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_8.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_9.png)

CONCLUSIONES: En este gráfico se puede ver, que a diferencia de los datos de todo el Perú, el area de los activos son más que los recuperados.

Actualización(2020-07-28): Ya casi la cantidad de recuperados es el mismo a los contagiados. Esto no significa que todas las personas contagiadas ya están recuperadas, sino que el número de recuperadas acumuladas esta por alcanzar al número de personas contagiadas acumuladas.

**5. Confirmados diarios vs Recuperados diarios**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_10.png)

CONCLUSIONES: En este gráfico se puede ver que solo entre el 20 y el 25 de Mayo la tasa de recuperados supero a la de contagiados, luego las tasa de recuperados es inferior a los contagiados.

Actualización(2020-07-28): El promedio de los últimos 7 días esta aumentando, que excelente.

**6. Metodo SIR. Un modelo que grafíca el ciclo de vida del virus.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_11.png)

CONCLUSIONES: Esta función grafíca el comportamiento del coronavirus con los datos de Arequipa. Los datos importantes son:

Poblacion de Arequipa: 1503547
Contact rate (beta) : Diversos estudios catalogarón que en esta pandemia este valor se encontraría entre 0.2 y 0.3. (Se necesita mas investigación pero en caso del Perú un beta de 0.15 gráfica mejor la situación actual).
Mean recovery rate (gamma): Básicamente este valor es 1/<Periodo de incubación>. Este dato para Perú es de 14 días.

Se puede observar que el límite de contagios en Arequipa llegaría en aproximadamente al día 170 y 180 que se inició la pandemia. Esto sería en un mes aproximadamente.

Actualización(2020-07-28): Según todas las métricas, puede que se llegue al pico de contagiados algunas semanas antes de lo esperado.

**7. Estudio de días donde se contagian más las personas.**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_12.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_13.png)

CONCLUSIONES: Esta, aunque no parezca, es una métrica importante; indica, aproximadamente, cuando es que las personas de Arequipa contraen el virus. Según la OMS, el virus tiende a provocar sintomas entre 5 y 6 días después de la exposición (pero pude variar entre 1 y 14 días), debido a la actual realidad de Arequipa (la temporada de invierno), en este estudio se cree que los sintomas tienden a aparecer lo mas antes posible (5 días).

Como vemos en las gráficas, los días (dentro de la provincia de Arequipa), más personas son diagnosticadas con COVID-19 son los MIERCOLES y SABADOS, si a estos días le quitamos los 5 días que demoraría una persona normal en tener los sintomas, eso quiere decir que las personas tienden a contagiarse más los días SABADOS y MARTES. SE SUGIERE A LAS PERSONAS NO SALIR LOS DIAS SABADO, LUNES Y MARTES

Referencia : https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/naming-the-coronavirus-disease-(covid-2019)-and-the-virus-that-causes-it

Tenemos que notar que los datos para esta métrica son extraídos de los datos liberados del MINSA.

**8. Diversos estudios aún no finalizados.**
