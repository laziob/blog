---
title: Toma de decisiones y experimentación
author: Ezequiel Boehler
date: '2020-07-05'
slug: toma-de-decisiones-y-experimentacion
categories:
  - toma de decisiones
tags:
  - data driven
  - decisiones
  - hipotesis
  - business intelligence
description: 'Utilizar la experimentación como reemplazo o justificación de la toma de decisiones está mal. ¿Como podemos hacer para acercarnos a decisiones data-driven?'
featured: ''
featuredalt: ''
featuredpath: ''
linktitle: ''
type: post
---

Hay un hecho recurrente en equipos que intentan tomar una cultura data-driven que está mal. Y este es cuando los mismos ponen la experimentación como el objetivo. A qué me refiero con esto? A que les importa más decir que “se experimentó”, que 
haber tomado una decisión informada, controlando por ciertos factores.

Si vienen siguiendo mis posteos anteriores, sabrán ya que hay muchos elementos que pueden hacer que una experimentación sea inválida. Si tomamos eso en cuenta, todos estos equipos que tienen como objetivo justificarse en la experimentación porque si, tienen grandes probabilidades de haber tomado decisiones no informadas y hasta contrarias a las correctas.

Esto en general se resume en 3 casos:
Se quiere realizar acción X, y se arma o altera toda una evaluación para que justifique tomar esa acción
No se planea ninguna acción o decisión de forma anticipada, sino que solo se experimenta de forma continua y se hace lo que sea que los experimentos “digan”.
Se realiza una experimentación pero si los resultados no son los deseados (este la misma bien hecha o no), se toma el camino que se quería tomar de todas formas.

Ahora bien, por qué menciono esto como un problema? Empecemos por recordar que la estadística es un campo que se enfoca en “disminuir incertidumbre”. Si volvemos a los 3 casos de recién, en el 1ro, quien toma la decisión no tiene interés en reducir incertidumbre, solo quiere poder justificar la acción que ya tiene decidida de antemano. En el 2do, no se planteó ninguna decisión a querer tomar, por lo tanto no hay ninguna incertidumbre que disminuir. Y en el 3ro, se presume una incertidumbre, pero no se le dio el peso o importancia necesaria a la experimentación para poder direccionar esa decisión. 

Entonces, en esos casos, por que se experimento? Probablemente porque hoy en dia esta de moda decir que la empresa es data-driven, que utiliza los datos para tomar decisiones, (ventaja comunicacional), o porque si alguien dice que la decisión que tomó fue con experimentación previa, su palabra tiene más peso que si dice que no (ventaja gerencial) y a veces para poder solicitar más presupuesto para invertir en la experimentación, que de cierta manera aumenta su “estatus” dentro de una empresa (ventaja corporativa). 

Experimentar consume recursos humanos, monetarios y tecnológicos. Por lo tanto no hacerlo con la intención y forma correcta, no solo nubla tu juicio a un costo alto, sino que tarde o temprano la realidad de los resultados te termina alcanzando, y llega el momento de replantear que paso con todas esas decisiones anteriores y los costos incurridos.

## Un framework correcto

Si bien deben haber muchas formas de utilizar la experimentacion estadistica correctamente en la toma de decisiones, les dejo aca una pequeña guía que creo que cubre los puntos principales. La misma se compone por distintos pasos a seguir desde el problema a resolver hasta la acción final.

### 1) Identificar el problema o la pregunta.

Como dijimos antes, la estadística se basa en reducir incertidumbre, pero incertidumbre respecto a que? Por eso debemos tener bien claro qué problema estamos intentando resolver o de qué pregunta nos gustaría tener una respuesta. La misma puede ser algo de un índole general como “El contenido personalizado genera un efecto positivo en nuestros clientes?” o mas especifico como “Cuál es el número ideal de correos/notificaciones semanales para enviar a nuestros clientes?

Un buen analista de datos suele ser clave para ayudar a generar este tipo de preguntas, ya que puede explorar los datos y encontrar puntos de dolor, u oportunidades específicas del equipo o negocio en cuestión. 

### 2) Decidir la acción por defecto

Este punto intenta establecer específicamente este escenario: **Si no pudieras tener información sobre este problema o pregunta, que decisión tomarías de todas formas? Si tuvieras que tomar la decisión en este mismo momento, cual seria? **

Decidir la acción por defecto es una condición excluyente de la metodología. Si no hubiera una decisión que tomar, no estaríamos buscando disminuir la incertidumbre en un principio. No tenerla refleja el segundo caso de los ejemplos que mencione al principio. 

En cambio, tener una definida una decisión por defecto, nos permite entender mejor cuál es la evidencia que debemos encontrar para querer tomar una decisión distinta. Es un punto que a muchos DM les cuesta, dado que antes de querer comprometerse a una acción, hoy en día más que nunca es fácil darse media vuelta y buscar primero en los datos. 

Un ejemplo aplicado en Marketing digital por ejemplo podría ser:
Tenemos la posibilidad de lanzar una nueva campaña en Facebook Ads y Google Ads.
Pero por temas financieros, lanzarla conlleva cierto riesgo, por lo que nos gustaría hacerlo solo si podemos estar confiados de un determinado retorno de la inversión. Un DM podría decir: Vayamos a buscar los costos y retornos de las campañas anteriores, y en base a eso decidir si lanzamos o no. 

Que pasaria en este caso? Como el DM no se comprometió a una decisión antes de buscar los datos, va a terminar buscando datos hasta encontrar aquellos que se ajusten a la acción que, sea subconsciente, por intuición o por emoción, prefería tomar. Esto es lo que se denomina __ sesgo de confirmación __ . Ahora bien, para no ser tan duros con nuestro hipotético DM, no estoy diciendo que este mal realizar  un análisis de datos exploratorio (EDA) para optar por una decisión. Hacerlo es algo que podría denominarse como una decisión “inspirada en datos” o “informada por datos” , pero como el sesgo de confirmación y varios otros entran en juego, no podemos decir que es una decisión “conducida por datos” (data-driven), que es el tipo de decisión a la que estamos apuntando.

Bajo nuestro framework en cambio antes de mirar cualquier dato, deberíamos haber decidido: “Por defecto no vamos a lanzar la campaña”. Ahora entonces se nos abre un abanico de posibilidades respecto a que evidencia debemos buscar para cambiar de opinión. 

### 3) Imaginar las posibilidades

El sentido de haber pasado por el punto 2 y decidir una acción por defecto, es que ahora que tenemos decidido qué hacer en las condiciones actuales, podemos buscar, imaginar, en qué otras condiciones cambiaramos esa decisión. 

Siguiendo el ejemplo anterior, una de esas posibilidades podría ser “Si podamos obtener un retorno de 1.5x sin gastar más de $50000 mensuales, entonces lanzamos la campaña”. 

Verán que recién en este momento, luego de haber comprometido una decisión por defecto y una de las tantas posibilidades alternas, comenzamos a tener algo similar a un diseño experimental que apoya la toma de decisiones. El mismo se puede resumir en: **“Vamos a hacer tal cosa, al menos de que podamos encontrar evidencia X. Si la encontramos haremos tal otra cosa”**

En el ejemplo de la campaña, esto queda como: “No vamos a lanzar la campaña nueva, al menos de que encontremos evidencia de que podamos obtener un retorno de 1.5x con menos de $50000 mensuales. Si la encontramos, lanzamos la campaña”.

El ejercicio de imaginar posibilidades creo que es de lo más interesante y entretenido en la toma de decisiones, ya que **te obliga a identificar los factores que pesan más respecto a tu decisión, qué cosas, por más locas o improbables que puedan ser, deberían suceder para que tu opinión cambie.** Lo considero inclusive un excelente ejercicio sobre humildad, dado que para hacerlo correctamente uno debe abstraerse de su opinión como certeza, y considerar bajo qué condiciones uno puede estar equivocado. 

Al final de este paso, uno debería tener una o un conjunto de alternativas que reflejen con determinado rigor, que debería suceder para cambiar mi decisión. Estas alternativas pueden ser muy probables o extremadamente improbables y eso debe estar alineado con el riesgo que tiene la decisión que se está intentando tomar. Por lo general esto se denomina **umbral de decisión**, y distintas metodologías estadísticas utilizan determinados umbrales, como el p-value y los intervalos de confianza en casos frecuentistas, y el factor bayes, ROPE, o Loss Function en casos bayesianos, por mencionar algunos.

### 4) Poner los puntos anteriores en práctica

Si nuestro DM llegó a este punto, ya tiene entonces 3 cosas definidas:

El problema / pregunta a resolver
La decisión por defecto con la cual se sentiria comodo de tomar en incertidumbre
Las alternativas del mundo donde cambiaría mi decisión por otra.

En diseño experimental, cada uno de esos elementos tiene un nombre específico.
El problema sigue siendo el problema, nada que hacer ahí. La decisión por defecto es lo que denominamos __la hipótesis nula__ . Y la alternativa es justamente, __la hipótesis alternativa__ .

Continuando con el ejemplo de nuestro DM y su campaña publicitaria obtenemos lo siguiente:

A un nivel bien general sería:
Hipótesis nula: No se puede obtener un retorno de 1.5x con un presupuesto de menos de $50000 mensuales.

Hipótesis alternativa: Sí se puede

Ya con algo mas especifico y llevado a la práctica, esto podría transformarse en:

Hipótesis nula: el retorno de campañas con presupuesto menores a $50mil es menor o igual a 1.49x

Hipótesis alternativa: el retorno de campañas con presupuesto menores a $50mil es mayor 1.49x

Ven como de a poco nuestra decisión por defecto y nuestras alternativas del mundo se van ajustando a un diseño experimental? Este es justamente el fin último de este framework para la toma de decisiones. Poder llevar la parte abstracta de nuestras acciones e incertidumbres a algo concreto, que se pueda experimentar.

A partir de este punto es que hay que considerar varios temas específicos a la metodología estadística que deseen aplicar, y algunos de ellos los cubro en mis otros posteos. Ambos son igual de importantes que lo mencionado en este post, pero lo que vimos en este es condición excluyente para poder luego entrar en la parte estadística. 

### 5) Tomar la acción resultante

Ahora solo nos queda tomar la acción resultante. Acá es crítico comprometerse al diseño experimental que se realizó. Sino, sólo lograron perder tiempo y recursos y demorar la decisión! 

Por lo tanto, si el diseño experimental se desarrolló de forma correcta, y no hay razones para creer que sus resultados son inválidos, la acción que se debe tomar es la que haya resultado del experimento.  Si se encontró evidencia fuerte para rechazar la hipótesis nula, debemos cambiar nuestra decisión por defecto a otra, y si no se encontró dicha evidencia, entonces podemos tomar la decisión por defecto establecida. 

No respetar el resultado del experimento nos pone en el tercer caso de los ejemplos que puse al comienzo del blog. 

En el caso de nuestro DM y su campaña publicitaria, podríamos decir que se evaluaron todas las campañas pasadas con presupuestos menores a $50mil, y el 95% (ojo esto no es el p-value, estoy simplemente dando un ejemplo poco riguroso) de ellas tuvo un retorno mayor a 1.49x. Como consideramos esto evidencia fuerte respecto a la hipótesis nula, decidimos lanzar la campaña! 

### Conclusión

Espero que esta guia les sirva para poner en práctica un framework de toma de decisiones simple que se alinea con la idea de experimentar y utilizar la estadística para una toma de decisiones data-driven. Y también que si actualmente sienten que se encuentran en alguno de los 3 casos que mencioné al comienzo del post, el contenido del mismo los ayude a poder corregir el rumbo y entender por qué motivos su experimentación no los estaba ayudando a realizar una mejor toma de decisiones.


