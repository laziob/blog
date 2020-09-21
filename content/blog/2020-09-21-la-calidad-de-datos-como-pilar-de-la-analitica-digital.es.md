---
title: La calidad de datos como pilar de la analítica digital
author: Ezequiel Boehler
date: '2020-09-21'
slug: la-calidad-de-datos-como-pilar-de-la-analitica-digital
categories:
  - analytics
tags:
  - analytics
  - decisiones
  - recoleccion de datos
  - business intelligence
description: 'Una mala calidad de datos genera desconfianza en todo el programa de analítica digital de la empresa, perjudicando tanto la toma de decisiones como la cultura de la misma. ¿Por qué motivos sucede y qué podemos hacer para evitarlo?'
featured: ''
featuredalt: ''
featuredpath: ''
linktitle: ''
type: post
---
Un dato de mi trabajo freelance es que quizás el 80% del tiempo lo dedico a arreglar recolecciones de datos web. Es curioso como por un lado vendors y clientes comunican las cosas increíbles que están logrando con técnicas avanzadas de Machine Learning y AI, y por otro lado el grueso de las empresas de ecommerce por ejemplo no tienen ni bien configurado su Comercio Electrónico Mejorado en Google Analytics, o tienen problemas hasta para medir ciertas conversiones en sus canales de publicidad.

Lo más interesante es que el problema de la calidad de los datos afecta tanto a empresas chicas como grandes, en diferentes medidas y formas, pero les afecta a ambas. ¿Y por qué esto es un problema? A mi me gusta resumirlo de la siguiente forma:

**Una mala recolección de datos genera pérdida de confianza en los mismos, y en consecuencia, problemas mayores en la toma de decisiones y en la cultura del negocio**

Para ejemplificar esto establezcamos primero dos ideas:

## ¿Por qué queremos datos? 

Si bien parece una pregunta simple y obvia, a la hora de su ejecución es donde más empresas fallan al no lograr poner en papel las preguntas de negocios importantes que quieren responder. En consecuencia, caen en la famosa trampa de “medir todo lo que se pueda”. Esto es un error, en especial en empresas con poca experiencia en datos y analítica, porque están pasando por alto que a mayor cantidad de datos recolectados, más fácil es perder la noción de que es cada cosa, de cuando los datos se están recolectando bien, de cuales son críticos para el negocio y cuáles no, de quien es responsable de mantener la recolección y la calidad de dichos datos vigentes. Y es aún más frecuente cuando trabajamos con datos web, donde el potencial de recolección es aún más fácil que otro tipo de datos. 

Por eso mi recomendación es que a la hora de encarar cualquier proyecto de analítica, ya sea algo cómo implementar Google Analytics o Adobe Analytics en el sitio web o app del cliente, donde más trabajo se debe dedicar es en definir las preguntas que nos interesan contestar. Algunas serán sobre objetivos de negocio, otras sobre características de nuestros clientes, otras sobre comportamiento de navegación, etc. Pero es crucial identificarlas y priorizarlas. La calidad de cualquier programa de analítica en una empresa comienza en este paso, no en la recolección per se, sino en la definición misma de que queremos contestar. 

## ¿Por qué es importante la calidad de los datos?

Supongamos que como líderes de un área, hay ciertas decisiones que las toman en base a un reporte automatizado semanal, puede ser el presupuesto de campañas en Redes Sociales, o decidir qué versión de diseño se sirve en las páginas de producto.  Vienen operando de esa forma hace 6 meses. Y de repente un día se enteran que los últimos 4 meses, entre un 10% y 30% de los datos diarios del reporte automático no se estuvieron recolectando bien. Ya sea porque directamente no se recolectaron, o porque se recolectaron pero con valores erróneos. ¿Cómo se sentirían? ¿Que harían ¿Volverían para atrás las decisiones que tomaron durante esos 4 meses con data errónea? ¿Continuarán usando el reporte pero sabiendo que la data es mala? ¿Seguirán tomando las decisiones pero sin usar el reporte? 

Volviendo a la idea mencionada al comienzo de este artículo, si una situación así se da, independiente de que acción se tome, se genera una pérdida de confianza en los datos, y en consecuencia, se volverá a una toma de decisiones basada en otro factores. Por lo tanto el valor del programa de analítica se reduce significativamente, y esa confianza es muy difícil de recuperar. Siguiendo el ejemplo, te invito a pensar que evidencia tendría que mostrar la persona encargada del reporte para que vuelvas a ese proceso de toma de decisiones semanal automatizado en base a los datos que el reporte muestra? ¿Confiarías en ese reporte de un día para el otro nuevamente?

Habiendo aclarado estos dos conceptos, procedamos sobre porqué suceden tan frecuentemente en el mundo de la analítica digital y unos pequeños consejos sobre cómo evitarlos.

## El error más frecuente se da por la forma que se trabaja

La mayoría de las empresas aún tratan sus programas de analítica digital como un sistema de “implementar y listo”. Tu agencia de marketing digital te está ofreciendo “configurar Google Analytics” y te dicen que solo necesitan que tus programadores peguen un par de códigos en el sitio. Una vez hecho eso, listo, ya está implementado, y nos olvidamos del asunto. O quizás tu equipo de marketing interno te dice que van a utilizar alguna herramienta de tagging para medir eventos, y por lo tanto una vez que se implementa una actividad el evento se comienza a medir y ahí queda. 

En el mejor de los casos, al momento de implementar una etiqueta o pegar algún script, se utiliza alguna herramienta de debugging para revisar que se está recolectando el dato correctamente. El problema de esto es que eso solo se hace al momento de implementar.

Luego el tiempo pasa, las herramientas cambian, los sitios cambian, hasta las agencias con las que trabajas cambian, y no hay un proceso de control de calidad sobre los datos recolectados. Y un día terminamos en el ejemplo de los 4 meses de datos erróneos, porque el control de calidad no se trabajó como algo continuo, sino que se utilizó como la captura de una foto, un momento en el tiempo solo a la hora de comenzar la implementación. 

Las empresas están acostumbradas a trabajar los programas de analítica digital de esta forma por dos motivos principales:
1. Inmadurez Analítica: La empresa no cuenta en sus talentos gerenciales con personas informadas sobre los esfuerzos necesarios para una correcta implementación de un programa de analítica. Se lo trata aún como algo “plug and play” o se cree que la solución está en tercerizar la responsabilidad a un ente externo.
2. Costos: Cualquier implementación de un proceso de control de calidad requiere recursos, y no creen que el valor generado o que potencialmente pueda generar el programa de analítica digital amerite cubrir recursos extra. 

Respecto al primer punto, creo que no hay nada que pueda hacerse al respecto salvo que la empresa misma decida invertir en dicho talento para encarar un programa de analítica digital como corresponde.

Pero el segundo es más frecuente y completamente superable. En este caso estamos frente a una empresa que de alguna forma u otra decidió invertir en un programa de analítica digital, y por lo tanto es de esperar que van a intentar tomar decisiones basadas en los datos recolectados. Entonces ¿por qué no dar el paso extra e invertir en un proceso de control de calidad continuo? Además de la pérdida de confianza, que en mi opinión personal es el factor más importante, estos son otras consecuencias que puede generar no tener un control de calidad continuo:

1. Costos financieros aún mayores: Es cierto que el proceso de control de calidad conlleva un costo, pero el costo de arreglar los datos una vez que se rompieron suele ser mucho mayor, por las siguientes razones:

  A. El tiempo en identificar que se rompió y por qué: Si de pronto nuestras conversiones dejaron de medirse, o estamos perdiendo visitas, debemos hacer un análisis profundo de toda nuestra recolección de datos con la esperanza de encontrar en el menor tiempo posible qué fue lo que sucedió. Hay veces que eso será simple, cómo algún cambio en una metadata de algún elemento del DOM, pero otras veces puede ser algo complejo, cómo ver que nuestras conversiones están cayendo levemente en el tiempo, y que creamos que es una tendencia del negocio, pero en verdad es algo que se fue dando por el aumento de visitantes utilizando iOS 14 de Apple con su ITP implementado por defecto.
  
  B. La posibilidad de poder arreglar datos retroactivamente: Dependiendo del sistema de recolección de datos que utilicemos, hay veces que no es posible arreglar la calidad de los datos retroactivamente. Por lo tanto si recolectamos mal datos por 4 meses, debemos afrontar el costo de diseñar e implementar el sistema que arregle los datos de esos 4 meses, y de no ser posible, entonces debemos afrontar el costo de no poder usar 4 meses de datos para análisis, por lo tanto son 4 meses de costos hundidos en nuestras herramientas de reportería, de automatización, y de tiempo personas dedicados a análisis hechos en malos datos.

2. Costos culturales: Siguiendo el ejemplo de los 4 meses de data errónea y la toma de decisiones, supongamos que al gerente general le llega la noticia que se tomaron 4 meses de decisiones en datos erróneos, y quiere responsabilizar a alguien. ¿Quién es el responsable? ¿La líder del área quien tomó las decisiones? ¿El analista que armó el reporte y lo automatizó creyendo que siempre iba a estar bien? ¿El equipo de marketing a cargo del taggeo vía la herramienta de tagging? ¿El equipo de desarrollo que realizó los cambios solicitados en el sitio que luego romperían la recolección de datos “independiente” del equipo de marketing? Al no trabajar el programa de analítica digital como un pilar interdisciplinario del negocio, este tipo de situaciones se da frecuentemente. Y pasan una factura importante a la cultura de la empresa que por un lado quiere tomar más decisiones basadas en datos, pero por otro lado no puede ni confiar en los mismos y teme responsabilizarse por ellos. 

## ¿Qué podemos hacer entonces para evitar estas consecuencias?

Como saben me gusta mucho ofrecer pequeños “frameworks” de trabajo que puedan poner en práctica. En este caso es un proceso de 4 pasos:

1. Listar y priorizar las preguntas a responder: ¿Cuáles son las necesidades más urgentes de mi negocio que me gustaría abordar? ¿Qué preguntas ejemplifican esas necesidades? ¿Qué datos necesito para responderlas?

2. Diseñar la recolección de datos como parte del producto: Agregar la medición al Definition of Done de los features. A la hora de implementar un componente al producto preguntarse si es algo que se debe medir (alineado al punto 1), y de  ser así, cómo se va a medir, qué objetivos debe cumplir una vez medido.
3. Diseñar un QA continuo: No todo lo que se mide tiene porque pasar por un QA continuo, pero las cosas críticas sí, como pueden ser  las conversiones, las visitas, ciertos datos cualitativos. Un ejemplo básico de esto podría ser algo cómo un validador del dataLayer, donde cada vez que se envía un objeto al dataLayer, primero pase por un validador en el servidor para corroborar que la estructura del mismo sea válida. Otro puede ser un análisis de serie de tiempo de las métricas críticas con algún método cuasi experimental para ver si se produjo un cambio inesperado en los valores de un determinado período. 
4. Llevar un registro de los problemas encontrados: Aunque realicen los pasos 1 al 3, errores en el trackeo aparecerán. Los pasos anteriores nos ayudan a disminuirlos y a identificarlos rápidamente. Sin embargo, una vez aparecen, es importante llevar un registro de dichos errores. Esto nos ayudará a ir mejorando nuestras herramientas y procesos de QA, a identificar factores que antes habíamos pasado por alto e incluso les brinda a los analistas el contexto de saber que cosas sucedieron en determinadas fechas para sus análisis. Por último, llevar una medición del tipo y cantidad de errores en la recolección de datos es inclusive una métrica de optimización en sí misma.

Espero que de este artículo se lleven la siguiente idea: **un buen programa de analítica digital comienza en la definición de las preguntas a responder** y **su continuidad generando valor depende exclusivamente de cuánto dure la confianza en los datos recolectados**

Con eso en mente, los invito a que miren dentro de sus empresas y se pregunten cómo están manejando este asunto en la misma, y se fijen de qué forma pueden ayudar a resolver esas dificultades, dado que hay mucho valor por ganar en esa área.

