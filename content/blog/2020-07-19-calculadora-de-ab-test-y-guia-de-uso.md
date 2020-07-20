---
title: Calculadora de AB Test y guia de uso
author: Ezequiel Boehler
date: '2020-07-19'
slug: calculadora-de-ab-test-y-guia-de-uso
categories:
  - ab test
tags:
  - ab test
  - estadistica
  - test ab
  - test de hipotesis
  - calculadora ab test
  - ab test calculator
description: 'Cree una calculadora en Google Sheets para realizar Tests AB de tamaño de muestra fijo, desde su diseño hasta su evaluación de resultados. En esta nota pueden obtener el link a la misma y un video de como usarla.'
featured: ''
featuredalt: ''
featuredpath: ''
linktitle: ''
type: post
---

# Si, otra calculadora para tests A/B clásicos

Existen muchas calculadoras para tests A/B en internet. Pero la mayoría no solo está en inglés, si no que además se centran solo en la evaluación de los resultados, sin tener en cuenta el diseño experimental detrás del mismo. Por último, los cálculos que utilizan suele estar escondidos dentro del código, lo que hace difícil tener un entendimiento claro de cómo llegó a sus resultados. 

Con eso en mente, y dado los resultados de una pequeña encuesta que realice en Linkedin, me propuse crear [esta plantilla en Google Sheets](https://docs.google.com/spreadsheets/d/1OqSqwUqPoiBnm6kDI7OTCyttLp5EP3ZW8IIvRJW__lg/edit?usp=sharing "Plantilla Test AB") que resuelva esos temas. Está en español, dividida en 3 pasos desde diseño del experimento, evaluación de la recolección, y evaluación de los resultados. Y como es un spreadsheet, las fórmulas están visibles para todos.

El objetivo de este artículo es guiarlos por el uso de la plantilla para que puedan sacarle el máximo provecho y brindar un par de recomendaciones sobre su uso. Separe el artículo en 2 partes, una en texto y otra en video. La parte de texto es sobre la estructura de la plantilla y algunas recomendaciones generales. El video es un ejemplo sobre el uso específico de la plantilla, dado que en texto se volvía extenso y poco claro. 

Comencemos. 

### Estructura de la plantilla

La plantilla contiene 2 hojas distintas:
Test de Proporciones
Test de Medias

La hoja de Test de Proporciones es la que deben usar cuando la métrica objetivo sea alguna proporción, como por ejemplo Tasa de Conversión o CTR. Esto es así dado que sus cálculos están ajustados para este tipo de métricas.

La hoja de Test de Medias a su vez, tiene algunos campos necesarios adicionales y algunas celdas con cálculos distintos para adecuarse a aquellos tests donde la métrica objetivo sea alguna media, como por ejemplo Valor de compra promedio, Cantidad de productos en el carrito, etc. 

A su vez cada hoja está compuesta por 3 pasos.
Test de Potencia
Evaluación de la recolección de datos
Evaluación de los resultados

Cada paso en sí tiene 3 tipos de celdas: 
Fondo azul: Son las que el usuario debe llenar con valores
Fondo blanco: Son cálculos adicionales necesarios para obtener los resultados
Fondo verde: Son los resultados de dicho paso

Por lo tanto, en cada paso el usuario solo debe ocuparse de llenar los valores de las celdas de fondo azul, y observar el resultado de las celdas de fondo verde. 

### Recomendaciones generales

La plantilla está diseñada de forma tal que si o si haya que pasar por los 3 pasos para cada experimento. Esto es así porque las fórmulas de un paso requieren de los valores en celdas de pasos anteriores. El motivo por el que la diseñe de esa forma, es para disminuir la probabilidad de un experimento inválido. Recuerden que en [este articulo](https://eboehler.com/blog/errores-frequentes-en-tests-ab-clasicos/ "Errores frecuentes en Test AB") les comente que uno de los errores más frecuentes es realizar test A/B sin un diseño experimental previo y por consiguiente, sin un test de potencia. Esto resulta en tests de tamaños muestrales que no controlan debidamente por el riesgo del error de tipo 1 y tipo 2, y por lo tanto la interpretación de sus resultados no es válida.

Dado que entre el paso 1 y el paso 2 debe pasar el tiempo entre que lanzan el experimento y se recolectan las observaciones, recomiendo que para cada experimento que realicen, hagan una copia nueva de la plantilla y la llenen con los valores de ese experimento.  De esa forma cuando el experimento finalicen, tienen ya documentado el diseño experimental que decidieron, y luego cuando completan los pasos 2 y 3, les queda documentado todo el experimento de principio a fin. 

### Video del uso de la plantilla

Aquí les dejo un video donde explico como utilizar la plantilla:

{{< youtube tNFPl8a6vmE >}}



