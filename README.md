Data Analytics COVID-19 Arequipa, Peru (Actualizado, 12 Octubre 2020)
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

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_2.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_3.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_4.png)

**2. Factor Salud - Hospitalizados y UCI (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_5.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_6.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_7.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_8.png)

**3. Factor Rt. Factor de reproducción del virus (Datos GERESA).**

Referencias:

https://github.com/k-sys/covid-19/blob/master/Realtime%20R0.ipynb

https://medium.com/@rburhum/el-martillazo-y-el-huayno-278716f49938

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_9.png)

**4. Doubling time. Periodo de tiempo en el que el virus se duplicará (Datos GERESA).**

Referencias:

https://github.com/COVID-19-AI-Research-Project/AI-Data-Analysis/blob/master/Projects/1/Prediction_Covid_19_WorldWide.ipynb

https://www.npr.org/sections/health-shots/2020/04/10/829167659/are-we-flattening-the-curve-states-keep-watch-on-coronavirus-doubling-times

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_10.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_11.png)

**5. Activos, Recuperados y Fallecidos (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_12.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_13.png)

**6. Confirmados diarios vs Recuperados diarios (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_14.png)

**7. Metodo SIR. Un modelo que grafíca el ciclo de vida del virus (Datos GERESA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_15.png)

CONCLUSIONES: Esta función grafíca el comportamiento del coronavirus con los datos de Arequipa. Los datos importantes son:

Poblacion de Arequipa: 1503547
Contact rate (beta) : Diversos estudios catalogarón que en esta pandemia este valor se encontraría entre 0.2 y 0.3. (Se necesita mas investigación pero en caso del Perú un beta de 0.15 gráfica mejor la situación actual).
Mean recovery rate (gamma): Básicamente este valor es 1/<Periodo de incubación>. Este dato para Perú es de 14 días.

Se puede observar que el límite de contagios en Arequipa llegaría en aproximadamente al día 170 y 180 que se inició la pandemia. Esto sería en un mes aproximadamente.

**8. Estudio de días donde se contagian más las personas (Datos MINSA).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_16.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_17.png)

Como vemos en las gráficas, los días (dentro de la provincia de Arequipa), más personas son diagnosticadas con COVID-19 son los MIERCOLES, si a estos días le quitamos los 10 días que demoraría una persona normal en tener los sintomas, eso quiere decir que las personas tienden a contagiarse más LUNES. SE SUGIERE A LAS PERSONAS NO SALIR ESTE DIA.

Referencia : https://www.who.int/emergencies/diseases/novel-coronavirus-2019/technical-guidance/naming-the-coronavirus-disease-(covid-2019)-and-the-virus-that-causes-it

Tenemos que notar que los datos para esta métrica son extraídos de los datos liberados del MINSA.

**9. Análisis por etapas y edad de las personas (Datos MINSA).**

Este análisis se realizó debido a que en los últimos días, y según las noticias, la cantidad de menores de edad contagiados del COVID-19 aumentó y queremos ver si esto se puede apreciar en los datos. Cabe mencionar que este y el siguiente análisis son realizados con datos del MINSA y solo dentro de la provincia de Arequipa.

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_18.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_19.png)

**10. Comparación con datos del SINADEF (Datos SINADEF).**

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_20.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_24.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_21.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_25.png)

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_22.png)

Este gráfico es una comparación anual y semanal entre los datos del SINADEF y los de la GERESA en el departamento de Arequipa. Como los datos del SINADEF son de todos los tipos de defunciones dentro del Perú, para la comparación con los datos de la GERESA (que son solamente causadas por el Coronavirus) se filtraron los datos del SINADEF por los siguientes critérios: 

1. Departamento de Arequipa.
2. Muertes no violentas
3. Causas del tipo U07
4. Aquellas defunciones que contengan las palabras "covid" y "coronavirus". 

**11. Factores de Riesgo con datos del SINADEF (Datos SINADEF).**

El objetivo de este estudio es encontrar las causas o factores de riesgo más probables que acompañan a las defunciones por Coronavirus en el departamento de Arequipa. Para lo cual primero se aplicaron algunas técnicas de NLP (Natural Language Processing) para encontrár clusters de las causas de defunciones sobre los datos del SINADEF. Para medir solo el impacto del virus de este departamento, solo se tomarón en cuenta datos de este año y solo del departamento de Arequipa.

Referencia: https://www.kaggle.com/maksimeren/covid-19-literature-clustering

![alt text](https://github.com/MilerDiazZevallos/Arequipa-Covid-19/blob/master/images/image_23.png)

En el gráfico anterior se puede apreciar que el cluster 3 es el que representa a las defunciones por Coronavirus.

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
