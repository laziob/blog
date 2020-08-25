---
title: Factores importantes a tener en cuenta cuando experimentamos
author: Ezequiel Boehler
date: '2020-08-24'
slug: factores-importantes-a-tener-en-cuenta-cuando-experimentamos
categories:
  - ab test
tags:
  - experimentacion
  - estadistica
  - inferencia
description: 'Cuando experimentamos estamos realizando inferencias y al hacerlo debemos considerar cómo la metodología que decidimos utilizar afecta a la validez interna y externa de la relación causal que queremos descubrir.'
featured: ''
featuredalt: ''
featuredpath: ''
linktitle: ''
type: post
---

En artículos anteriores estuve hablando sobre los beneficios de experimentar en nuestros productos digitales y en el negocio en general. También mencioné algunos errores frecuentes que se cometen al experimentar y cómo evitarlos. Sin embargo, todo eso siempre estuvo relacionado a experimentos de hipótesis nula aleatorios, mejor conocidos como Test A/B, donde la asignación es aleatoria y el tratamiento (un cambio en UX, en precio,etc) es introducido por nosotros mismos. 

Pero la experimentación y el diseño experimental es un tema mucho más amplio, donde hay muchas metodologías distintas de las cuales elegir, dependiendo el contexto en el que operamos, y ciertos factores que afectan a todas estas metodologías y que es importante tener presentes. El objetivo de este artículo es describir un poco esos factores e introducir distintas metodologías para que las tengan presentes. 

Para comenzar este recorrido, lo primero que hay que entender es **qué buscamos lograr cuando experimentamos**. 

Beneficios de experimentación hay muchos. Nos permiten reducir incertidumbre, nos permiten enmarcar y documentar nuestra toma de decisiones, y nos permite aprender. Pero cómo es que funciona este aprendizaje realmente? Este aprendizaje deriva de la causalidad. Cuando experimentamos, lo hacemos bajo una creencia general de que el tratamiento que estamos induciendo _causa_ un _efecto_ en algún ámbito de interés. Por ejemplo, hacemos un Test A/B entre un sistema de precios mensual v/s uno semanal, porque creemos que cambiar el sistema de precios puede llegar a causar un aumento en la cantidad de suscriptores. O testeamos una versión del sitio con contenido personalizado; y otra, con contenido general, porque creemos que un contenido más relevante causa una mejor experiencia de usuario y por lo tanto un aumento en una métrica objetivo. 

### Relaciones causales

Por lo tanto, si hacemos un test donde introducimos tratamiento A, y eso genera efecto B, aprendimos que A genera B, verdad? Bueno resulta que no. No es tan simple. Primero hay que entender 2 tipos de relaciones causales. La primera es la *descripción causal*. La descripción causal es el tipo de resultado que nos devuelve un experimento, donde si yo hago A, sucede B. Por ejemplo, si yo sobrecargo de scripts de terceros mi sitio y en consecuencia disminuye mi tasa de conversión. La descripción causal solo hace lo que el nombre nos indica. Nos describe una relación causal de la forma más elemental posible. Pero en verdad, el mecanismo que causa una disminución en la tasa de conversión no es tan simple como A luego B, como no lo son la mayoría de los mecanismos causales. Ahí es donde entra la segunda relación causal, que se denomina *explicación causal*. Esta, nos explica mediante qué mecanismos y bajo qué condiciones esa relación causal existe. Al sobrecargar mi sitio de scripts de terceros pesados, la velocidad del sitio disminuye considerablemente, lo que genera una peor experiencia en el usuario y de todos los usuarios que me visitaban, ahora muchos se van antes de siquiera interactuar en el mismo y por lo tanto no convierten, y ahí es donde cae mi tasa de conversión. Además, esto solo sucede en el navegador y no en la app, dado que la app no carga la misma cantidad de scripts. 
Por lo tanto, con un experimento solemos aprender que existe una descripción causal entre A y B, pero poco conocemos sobre la explicación causal entre ambas.

### Validez Interna y Externa

Bueno, pero si aprendimos que si en las personas que fueron tratadas con A, logramos B, podemos aplicar A al resto de las personas y esperar que suceda B, cierto? Resulta que, eso tampoco es tan fácil. Todos los diseños experimentales son afectados por dos tipos de validez. La **validez interna** hace referencia a si la metodología utilizada es válida respecto a nuestras unidades de observación, a nuestro tratamiento, y al resto de variables o contextos en el que el experimento opera. Por ejemplo, cuando hacemos un Test A/B de hipótesis nula, sin haber realizado un test de potencia previo y por lo tanto no sabemos si recolectamos observaciones suficientes para un tamaño de efecto específico, podemos decir, que nuestro test no cumple con la validez interna. Esto es, porque ejecutamos un experimento sin haber cumplido con las condiciones necesarias de la metodología para que la inferencia sea válida. Una baja validez interna se traduce en  una baja confianza sobre la inferencia o conclusión de que existe una descripción causal entre A y B. 

Pero, supongamos que hicimos un test de hipótesis nula y cumplimos con todos los requisitos. La pregunta que nos queda entonces es, si la descripción causal que encontramos y probamos es generalizable al resto de las personas. Esto es lo que intenta representar la **validez externa**. Hasta qué medida se mantiene generalizable el aprendizaje. Si nuestro experimento lo realizamos solo con los visitantes logeados de nuestro sitio, podemos decir que el efecto logrado se mantendrá en los visitantes no logeados? O, que se mantendrá con los visitantes logeados pero dentro de 1 mes, o de 1 año? 
O supongamos que el test fue un cambio en el texto de nuestra landing. Cualquier cambio en el texto hubiera generado B? O solo ese cambio específicamente? ¿Cuán similares pueden ser otros cambios a este para que el efecto B se mantenga?

**Los experimentos bien realizados, por lo general, controlan mucho la validez interna pero no tan bien la validez extern.** Y la medida de esto, depende específicamente del diseño experimental y la metodología seleccionada. Por otro lado, **en la mayoría de la experimentación en negocios y productos digitales, el foco está puesto en descubrir descripciones causales**, más que entender explicaciones causales, lo que es lógico, debido a la cantidad de decisiones que hay que tomar y la velocidad con la que se deben hacer . Por lo tanto, para asegurarnos de encontrar correctamente las descripciones causales, la validez interna es condición Sine Qua Non. Tomarse tiempo para realizar experimentos de los cuales no se puede inferir correctamente nada sobra la causa y el efecto, debido a que no poseen ninguna validez interna, es una pérdida de tiempo y ningún experimentador haría eso a conciencia. Sin embargo, dada la cantidad de empresas que realizan experimentos aleatorios erróneamente, nos demuestra que a nivel de negocios, aún estamos muy lejos de entender la importancia de dicha validez interna.  

### El rol de la aleatoriedad 
El muestreo aleatorio, que suele ser el muestreo por defecto en experimentación online, utilizando las cookies de navegadores para servir experiencias aleatoriamente, simplifica en gran medida tanto la validez interna como la externa. Supongamos que nuestra población fuera todos los visitantes a nuestro sitio, y que en un mes recibimos 1 millón de visitantes únicos. Si realizamos un Test A/B de dos versiones, donde participan aleatoriamente 200 mil visitantes, y de esos 200 mil , 100 mil son aleatoriamente asignados a la variante A y los otros 100 mil a la variante B, el muestreo aleatorio nos garantiza que, dentro de los límites del error muestral,  la relación causal promedio observada en esta muestra de 200 mil personas:

1. es la misma que la relación causal promedio observada si hubiéramos seleccionado otras 200 mil personas aleatorias de nuestra población de 1 millón.
2. es la misma que la relación causal promedio observada entre todo el resto de los visitantes (800 mil) que no fueron seleccionados en el muestreo de 200 mil.

Esto se debe a que al ser aleatorio, todas las variables que afectan la descripción causal son distribuidas de forma “pareja” o “justa” dentro de los límites del error muestral (comparabilidad entre grupos). Y por otro lado, al ser aleatorios y que su única diferencia sea el tratamiento, elimina explicaciones alternativas del efecto. La comparabilidad entre grupo tratamiento y control se puede resolver mediante otras prácticas; al igual que se pueden eliminar explicaciones alternativas al tratamiento mediante lógica y otros métodos. **Pero no hay ningún otro tipo de muestreo que resuelva ambas cosas a la vez y de mejor forma que el aleatorio. **

En las ciencias sociales, el muestreo aleatorio no se usa frecuentemente debido a la complejidad de seleccionar muestras de gran tamaño aleatoriamente. En cambio **en experimentación online, tenemos la enorme ventaja de que contamos en general con muchas observaciones**, no tan costosas, y que casi siempre podemos muestrear aleatoriamente. Por eso, es que debemos aprovechar la oportunidad de experimentar, lo mejor posible! 


### La aleatoriedad no siempre es posible

Hay casos donde el tratamiento que queremos introducir no puede ser aleatoriamente asignado. Por ejemplo, si quisiéramos saber el impacto que tienen los reclamos de los clientes en su frecuencia de compra, nosotros no podemos obligar a que un cliente reclame aleatoriamente. O cuando nuestro sitio tiene muy poco tráfico, quizás no podemos hacer un Test A/B aleatorio porque no cumpliría con tamaños mínimos muestrales. 

Por suerte, **existen otros tipos de diseños experimentales, denominados Cuasi-Experimentos**. La siguiente es una breve descripción de Experimentos y Cuasi-Experimentos. 

> Experimento Aleatorio: Un experimento en el cual las unidades a recibir el tratamiento son asignadas por algún proceso aleatorio. 

> Cuasi-Experimento: Experimentos donde el tratamiento no es asignado aleatoriamente. 

> Experimento Natural: No es estrictamente un experimento, dado que el tratamiento no puede ser introducido, sino que sucede de manera natural (como los reclamos, o ciudades que sufren terremotos, etc). Son experimentos donde se contrasta el evento “natural” respecto a otras condiciones de comparación.  

> No Experimento u Observacional: Es cuando solo se estudia la magnitud y dirección de correlación entre variables, sin introducir ningún tratamiento de ningún tipo y forma. 

El rol de los Cuasi-Experimentos sigue siendo el mismo que el de los experimentos aleatorios, es decir: probar relaciones de descripción causal entre un tratamiento y un efecto. 

Porque los Cuasi-Experimentos carecen de asignación aleatoria, **la validez interna y externa de este tipo de experimentos debe ser controlada de diversas maneras**, específicas al diseño del mismo. En general, se trata de enumerar explicaciones alternativas del efecto, decidir cuáles son posibles, y utilizar lógica, conocimiento de dominio, y mediciones para determinar de qué forma pueden estar operando para explicar el efecto observado. 

Algunos tipos de Cuasi-Experimentos son:
1. Pre test v/s Post test
2. Diferencia en diferencias
3. Series de tiempo interrumpidas
4. Grupos de control sintéticos 
5. Regresión discontinua

Dependiendo de si tenemos o no grupo de control, de si tenemos o no periodo previo y posterior, y otros factores, es que determinaremos cuál es la metodología más adecuada para nuestro diseño cuasi experimental. Y eso determinará también, la validez interna y externa que podremos obtener de sus resultados.

### Conclusión

Como habrán visto, el mundo de la experimentación es bastante amplio, lo que es bueno dado que nos da muchas herramientas para experimentar en distintos contextos. Pero a la vez, es complejo, dado que a la hora de experimentar y hacer inferencias, hay que tener presente muchos factores que son afectados por la metodología seleccionada de alguna u otra manera. 

Con eso en mente, se preguntarán, ¿y entonces por qué experimentar, si lleva tanto trabajo? A eso tengo dos respuestas. La primera es que solo porque las cosas sean difíciles no quiere decir que no haya que hacerlas. Son difíciles porque intentan responder algo complejo, que es descubrir patrones de comportamiento del mundo que nos rodea, lo que sin lugar a duda no es tarea fácil. 
La otra respuesta es que, la ganancia de experimentar es muy alta. Piensen que, por cada descubrimiento que ustedes realizan sobre sus clientes y su interacción con sus productos, le ganan una ventaja a sus competidores que no experimentan. Por supuesto que, un mejor producto y servicio y un buen fit de precio con el mercado son indispensables, y la experimentación no puede reemplazar eso. Pero asumiendo un mercado altamente competitivo donde esas condiciones están dadas, experimentar nos da la posibilidad de aprender más y más rápido sobre nuestros clientes y su relación con nuestras ofertas y experiencias, y a la vez disminuir riesgos de futuras decisiones, manteniendo una operación más previsible y controlada. 

En futuros artículos estaré profundizando en los distintos tipos de Experimentos y Cuasi-Experimentos para que cuenten con más herramientas en su arsenal de experimentación. 
