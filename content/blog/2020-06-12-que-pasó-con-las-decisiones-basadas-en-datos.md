---
title: ¿Que pasó con las decisiones basadas en datos?
author: 'Ezequiel Boehler'
date: '2020-06-11'
categories:
  - analytics
tags:
  - analytics
  - decisiones
  - estadistica
slug: la-falacia-de-la-analitica-digital
type: post
description: Las empresas no están obteniendo el valor deseado de su inversión en datos. La clave para solucionar ese problema se encuentra en tener personas en el equipo con los conocimientos estadísticos necesarios.
---
La realidad es que **la mayoría de los equipos de marketing digital, o analytics, no toman decisiones en base a datos**, no son "data-driven".

Hoy en día, la comunicación sobre el presente y futuro de los datos y su impacto en los negocios abunda. Alcanza con buscar "negocios data" en Google para encontrar un sinfin de notas sobre el tema. 

Con el aumento de herramientas de recolección de datos web, su facilidad de uso y la poca regulación (que en el último año comenzo a cambiar), los equipos de Marketing y UX fueron quizás de los más beneficiados, obteniendo datos no solo de la adquisición (campañas, audiencias, canales) de posibles clientes sino también de sus interacciones con todo su producto o servicio. 

### ¿Están esos equipos usando los datos para tomar decisiones? 

[Esta](https://hbr.org/2012/08/marketers-flunk-the-big-data-test/ "HBR2012") nota del Harvard Business Review, escrita en 2012, encuestó a casi 800 especialistas en marketing de las compañías Fortune 1000 y descubrió que la gran mayoría de los especialistas en marketing todavía confían demasiado en la intuición. Y, para empeorar la situación, los pocos que usan los datos de forma consistente, en su mayor parte lo hacen mal.

Los dos elementos que considero más importantes de la nota son los siguientes:

> La mayoria de estos profesionales tiene dificultades respecto a estadística.
Cuando probamos la aptitud estadística de los especialistas en marketing con cinco preguntas que van desde básicas a intermedias, casi la mitad (44%) obtuvo cuatro o más preguntas incorrectas y solo el 6% respondió correctamente las cinco. Por lo tanto, no nos sorprendió que solo el 5% de los especialistas en marketing posean un libro de texto de estadísticas.

> Algunos están peligrosamente distraídos por los datos.
Si bien la mayoría de los especialistas en marketing subutilizan los datos, una pequeña fracción (11% en este estudio) consultan los paneles diariamente y basan la mayoría de las decisiones en los datos.(...) El problema es que no tienen la aptitud estadística o el juicio necesario para usar los datos de manera efectiva. Cada vez que ven un mal desempeño en el tablero, se ajustan y terminan cambiando de dirección con tanta frecuencia que pierden de vista los objetivos finales.

Este estudio evidenciaba en el 2012 que ya había un gran acceso a los datos, pero que **hacían falta conocimientos estadísticos para hacer un uso correcto de los mismos**. 

6 años más adelante, en el 2018, HBR publica [esta otra nota](https://hbr.org/2018/05/why-marketing-analytics-hasnt-lived-up-to-its-promise/ "HBR2018") que nos cuenta cómo, a pesar de opinar que el uso de la analítca tuvo un impacto modesto (4.1 en una escala del 1 al 7), las empresas pensaban aumentar la inversión en analítica en un 198% para los próximos 3 años. Cabe destacar que la misma pregunta sobre el impacto de la analítica se les hizo en el 2013, y su puntaje había sido de 3.8, por lo tanto aumentó solo un 7%.

De esta nota quisiera destacar estos dos puntos:

>*El Desafío de los Datos*
Los datos se están volviendo omnipresentes, por lo que a primera vista parecería que los análisis deberían cumplir su promesa de creación de valor. Sin embargo, los datos crecen en sus propios términos, y este crecimiento a menudo es impulsado por inversiones en TI, en lugar de objetivos de marketing coherentes. Como resultado, las bibliotecas de datos a menudo se ven como un armario desordenado, donde es difícil separar las ideas de la basura.

>*El Desafío de los Analistas*
La encuesta también encontró que solo el 1.9% de los líderes de marketing informaron que sus compañías tienen el talento adecuado para aprovechar los análisis de marketing. Los buenos analistas de datos, como los buenos datos, son difíciles de encontrar. Lamentablemente, la calificación general en una escala de siete puntos, donde 1 es "no tiene el talento adecuado" y 7 es "tiene el talento adecuado", no ha cambiado entre la primera vez que se hizo la pregunta en 2013 (media 3.4, DE = 1,7) y 2017 (media 3,7, DE = 1,7).

Qué pasó entonces en esos 6 años entre el 2012 y el 2018? **Las empresas obtuvieron muchísimos más datos, pero no obtuvieron ningún valor adicional de ellos**, y una de las causas parece ser la falta de talentos/capacidades para obtener ese valor.

La nota más reciente sobre el tema que leí es [esta de acá](https://hbr-org.cdn.ampproject.org/c/s/hbr.org/amp/2020/05/is-your-business-masquerading-as-data-driven/ "HBR2020"), que explica como las empresas actuales tienen la fachada de ser "Data Driven" pero no lo son. Ejemplifica 3 tipos de situaciones muy típicas sobre el mal uso de los datos para la toma de decisiones, y resalta que **uno de los reqiusitos para sobrepasar esa situación es tener trabajadores capacitados para actuar sobre los datos y que esto puede requerir un cambio cultural significativo**. Pero que la oportunidad es sustancial: capitalizar lo que es posible y ser una organizacion verdadermaente impulsada por los datos.

### ¿Donde entra la estadística en todo esto?

Si recuerdan, en la primer nota de HBR se menciona el poco conocimiento de los profesionales de marketing en estadística. ¿Por qué es la estadistica importante para estos equipos? 

Casi todo el conocimiento que existe en el mundo se obtiene a través de la _inferencia_ o se lo aproxima a través de la _probabilidad_. Observando que los objetos al ser levantados y luego soltados, estos caen, podemos inferir la existencia de la ley de gravedad. Pero si un perro nos muerde, podemos inferir que todos los perros nos van a morder?

Para evitar hacer inferencias incorrectas, como la del perro, es necesario un correcto diseño de test de hipótesis y el uso correcto de la estadística. Por lo general, esto incluye seleccionar la población sobre la que queremos inferir, calcular el tamaño necesario de muestreo, revisar que el muestreo sea representativo y aleatorio de dicha población, entre otros factores. 

Sumado a eso, hay que tener un correcto entendimiento de "significancia estadística", "test de potencia", "intervalos de confianza" más otros conceptos. Y eso solo si nos enfocamos en lo que se denomina "métodos frecuentistas". Si buscamos un enfoque Bayesiano, aparecen otros factores y términos que debemos entender. 

¿Por qué esto es importante? Porque lo que buscamos lograr acá es aplicar el metodo cientifico. **El método científico es una metodología para obtener nuevos conocimientos**, que ha caracterizado históricamente a la ciencia, y que **consiste en la observación sistemática, medición, experimentación, y la formulación, análisis y modificación de hipótesis.** Basicamente, es lo que nos permite disitnguir hechos verdaderos de aleatorios. Y para utilizarlo correctamente se requieren conocimientos solidos tanto de estadística como de lógica. 

Por lo contrario, no aplicar el método cientifico, por más buenas que sean las intenciones del equipo, y lo poco sesgado que esté, es basar las decisiones en preconceptos, intuciones, o cualquier creencia que no puede ser puesta a prueba o cuestionada de forma sistemática, y por lo tanto no se puede confirmar o negar.


### ¿Y como afecta esto a equipos de Marketing o UX?

Cuando un equipo decide que una creatividad performa mejor que otra, que una experiencia de usuario es mejor que otra, etc, lo que está haciendo es **establecer que algo es verdadero.** Y en el momento que decidis establecer algo así, estas involucrandote en el mundo de la ciencia. 

Cuando observamos que una variante performa mejor que un control en la métrica de interes (sea CTR, Tasa de Conversión, Venta por Visita, etc), no podemos simplemente decir que la variante es mejor para toda la población futura de usuarios, dado que nuestra conclusión proviene de una cantidad limitada de observaciones, de las cuales no hemos hecho ningún control para saber si podemos hacer inferencias correctas a partir de ellas. 

Vamos con un ejemplo.

Anuncio | Impresiones | Clicks | CTR
--------|-------------|--------|------
Control |             |        | 5.7%
Variante|             |        | 6,8%

En algún lado aún existen equipos de marketing que frente a estos datos podrían concluir que la variante performa mejor que control. Pero qué pasa si agregamos más información?

Anuncio | Impresiones | Clicks | CTR  | Significancia
--------|-------------|--------|------|---------------
Control | 245         | 14     | 5,7% | 
Variante| 247         | 17     | 6,8% | 70%

Si analizamos estos datos como un test de proporciones, con un riesgo de error de tipo 1 del 5% (alpha = 0,05), y con una hipótesis nula de no-inferioridad (que la diferencia observable es menor o igual a cero), nos da que el siguiente test tiene solo un 70% de significancia. No hay evidencia suficiente para rechazar la hipótesis nula de que la diferencia entre CTR sea menor o igual a cero. Por lo tanto, no podemos concluir que la variante sea de hecho mejor que el control.

Además, este test, para realizarse con la potencia correcta para detectar un efecto de ese tamaño, hubiera requerido 5986 impresiones en control y en variante. Este cálculo es lo que se denomina test de potencia, y debe preceder cualquier test de hipótesis, pero hablaré de esto más adelante.

Este es un ejemplo de un test de hipótesis nula simple. **En la práctica, hay muchos factores que complejizan la realización de este tipo de pruebas**. Entonces imaginense cuantos equipos de Marketing o UX de verdad deciden si pausar o no anuncios, creatividades, experiencias en la web o no, con experimentos así o similares? (Una empresa que es famosa por su cultura de experimentación es Booking.com, los invito a que busquen sobre su forma de experimentar y tomar decisiones)

Otra cara de la moneda, es que los equipos muchas veces están sesgados a solo optimizar sus métricas de gestión, y no el impacto verdadero en el negocio, por lo que experimentar respecto a ese impacto, no es una prioridad.

Hay muchos casos de equipos que sí realizan experimentos, pero no con la metodología correcta y eso resulta en dos tipos de errores a mi parecer más graves: 

1. Creer que se encontró un efecto, o una "verdad" sobre el cliente que no es cierta

2. Creer que no hubo efecto en absoluto.

Llegar a estas conclusiones de forma incorrecta se debe principalmente a 5 tipos de errores:

### Errores a los que estar atentos cuando se busca experimentar

1. No realizar cálculos de significancia: 
Esto nos pone en el espectro de equipos que directamente no están midiendo el real impacto de sus decisiones, y por lo tanto, no las están cuestionando. Estos equipos tienen pocas probabilidades de aprender sobre sus acciones.

2. Realizar cálculos de significancia erroneamente: 
Ejemplos de esto son los experimentos que se frenan a penas ven que una variante es significante, sin esperar a obtener las muestras necesarias según el diseño del experimiento, o que los dejan corriendo por tiempo indefinido esperando que se vuelvan significantes en algún momento. Estos equipos si bien están encaminados, no logran llegar a las conclusiones correctas de sus decisiones porque sus experimentos están mal ejecutados.

3. Interpretar erronamente el efecto generado por la variante:
Algunos equipos realizan bien los experimentos, pero no miden el impacto probable de la variante. Esto significa que cuando un experimento concluye siendo significante para la variante, la eligen, **sin tener en cuenta el intervalo de confianza del efecto generado**. Quizás cuando el experimento terminó, la variante fue un 30% mejor, pero el intervalo de confianza de ese efecto puede variar entre [-5% y 35%]. Es importante entender el intervalo posible de impacto, dado que hay decisiones que dependiendo el intervalo quizás no vale la pena tomarlas.

4. Creer que la falta de evidencia es evidencia de la falta:
Cuando un experimento no logra rechazar la hipótesis nula, osea, no es significante, no quiere decir que la hipótesis nula sea cierta, por ejemplo, que no haya efecto. Muchas veces los experimentos no se diseñan con la potencia correcta para detectar efectos del tamaño deseado. Eso quiere decir que ese experimento muy dificilmente iba a detectar un efecto, pero no quiere decir que el efecto no existe. Quizás hay un efecto, pero es más chico de lo que el experimento estaba diseñado a detectar. Por eso, es importante recordar que **la falta de evidencia NO ES evidencia de la falta**.

5. Asumir que la herramienta que contrataron les resuelve todos los problemas:
Es sorpredente como muchos equipos contratan herramientas de este tipo, sin ningún miembro interno que revise qué métodos y supuestos esas herramientas utilizan. Cada vez hay más casos de empresas que cambian de proveedores porque el actual no les da los resultados que esperan. Pero **el problema no esta solo en el proveedor, sino en la inexperiencia del equipo sobre que es lo que necesita realmente para a experimentar bien**

Uno de los errores más frecuentes es el punto 4 de la lista. En mi experiencia son muy pocos los equipos que realizan cálculos de potencia para determinar cuantas observaciones, y por lo tanto cuanto tiempo, deben correr el experimento para observar un efecto como el que desean observar. 


### ¿Que puedo hacer entonces?

No todo está perdido. Si llegaron hasta acá, asumo que es porque tienen un genuino interés en mejorar la toma de decisiones de sus equipos. Los invito a que:

1. Sigán aprendiendo sobre test de hipótesis y diseño de experimentos:

La idea de este artículo, y de los futuros artículos de este blog, es introducir y explicar conceptos, metodologías e ideas sobre experimentación. Enfocado principalmente en experimentación en Web y Marketing Digital, pero también temas abstractos que pueden ser replicados en cualquier ámbito.

2. Sigan aprendiendo sobre estadística y probabilidad:
Es un mundo super interesante, que se puede aplicar para mejorar el desempeño en todo tipo de tareas diarias.

3. Miren hacía adentro en sus equipos, y fíjense cómo están operando:
¿C´omo es la toma de decisiones? ¿Qué herramientas utilizan? ¿Qué cosas se pueden mejorar?

4. Enseñen al resto:
Cuando se sientan cómodos, intenten enseñarle no solo a sus pares, sino también a sus jefes, donde seguro encuentren más resistencia, pero donde también hay más valor, ya que ellos luego podrán darles el empuje necesario para mejorar sus prácticas en mayor escala.


### Unas últimas palabras

Quiero destacar que, como mencioné al principio, las empresas no están encontrando personas que puedan generar valor de toda su inversión, tanto en datos como en marketing digital. Y esos estudios además se realizan con empresas en Estados Unidos y Europa principalmente, donde para bien o para mal, los mercados son más maduros que en America Latina, y el conocimiento en esas areas suele ser mayor. 

Habiendo dicho eso opino que debemos estar a la altura, y que tanto las empresas como las  personas que logren apalancarse de estas técnicas van a poder sacar una gran ventaja competitiva sobre el resto. Sin embargo es necesario que el conocimiento no solo exista sino que sea accesible.

Mucho de lo que yo aprendí fue de autores que escriben en inglés, o que dan cursos en dolares o euros y que por lo tanto no son de fácil acceso para todos. Además las universidades, en especial en carreras como Marketing, no mencionan estos temas, por lo que aprenderlos ya de por sí requiere un esfuerzo y tiempo extra por fuera de la vida académica normal. Pero definitivamente el mercado laboral necesita gente que sepa cosas que la educación clásica no esta ofreciendo. Es por eso que me puse como objetivo facilitar estos conocimientos y espero poder ayudar a quienes decidan seguir por este camino.