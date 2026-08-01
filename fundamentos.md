---
site: sandpaper::sandpaper_site
title: "Fundamentos de Ciencia Abierta"
teaching: 100
exercises: 40
---
:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

## Antes de empezar:
- Bienvenida
- Este encuentro va a ser grabado y si bien nos encantaría que estén con las cámaras prendidas para poder interactuar de forma más fluida, si prefieren, pueden apagarlas. Nuestro equipo de apoyo va a estar iniciando la grabación ahora.
- Esta presentación que vamos a usar tiene una licencia CC-BY, lo que permite que puedan reusarla libremente mencionando la fuente. 
- Todos los espacios de MetaDocencia se rigen por nuestras [Pautas de Convivencia](https://doi.org/10.5281/zenodo.12534195). En resumen, buscamos que este sea un espacio seguro, respetuoso e inclusivo, donde podamos intercambiar ideas con empatía, escuchar distintas perspectivas y tratarnos con amabilidad. Y, por supuesto, evitar cualquier tipo de acoso, destrato o comentarios que puedan incomodar a otras personas.
- Para participar: pide la palabra o usa el chat y silencialo al terminar de hablar
- Pide permiso antes de tomar registros de las personas presentes en este encuentro.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::: questions

- ¿Qué caracteriza a la Ciencia Abierta y qué beneficios puede aportar?
- ¿Qué barreras y preocupaciones pueden surgir al abrir procesos y productos de investigación?
- ¿Cómo orientan los principios FAIR la gestión y el intercambio responsable de los productos de investigación?

:::::::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::: objectives

Al finalizar este episodio, quienes participan podrán:

- Explicar qué es la Ciencia Abierta y relacionarla con la reproducibilidad, la colaboración y la participación.
- Reconocer barreras sociales, institucionales y de infraestructura desde una perspectiva situada.
- Analizar las preocupaciones frecuentes relacionadas con errores, datos sensibles, malinterpretaciones y apropiaciones.
- Identificar los componentes de los principios FAIR y su aplicación en datos, código y otros productos de investigación.

::::::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::: discussion

## Presentación en el chat

Para conocernos un poco, cuéntanos tu campo de trabajo y comenta en pocas palabras por qué te sumaste a esta formación.  

Tiempo estimado: 3 minutos.

::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Durante estos encuentros van a ir apareciendo ejercicios que nos ayudan a evaluar cómo viene el curso y recuperar la atención de quienes estén un poco cansados, algunas van a ser espontaneas, o pedidos de respuestas por chat, como esta, otras van a ser encuestas de zoom que son muy dinámicas y rápidas y por último también van a suceder algunas actividades en salas de grupo que siempre son muy valoradas. 

En la sala de grupo de hoy vamos a estar conversando acerca de las preocupaciones a la hora de abrir la ciencia, Estas salas van a tener una duración de 10 minutos y es muy importante que tengan en cuenta que la participación en las salas depende de la interacción que pueda tener cada uno de ustedes. Si lo prefieren, nos pueden avisar si tienen algún inconveniente para activar sus micrófonos, a fin de propiciar la división de salas de la manera más dinámica posible. Puede fallar, les pedimos que nos tengan paciencia este primer encuentro porque somos muchas personas, haremos lo mejor posible porque pasen una linda experiencia de intercambio y lo iremos mejorando encuentro a encuentro. 

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

# ¿Qué es la Ciencia Abierta?

## ¿Qué es la Ciencia Abierta?

> “El movimiento de Ciencia Abierta tiene como objetivo fomentar la difusión, el escrutinio y el reuso de los componentes de investigación para el bien de la ciencia y la sociedad”.
>
> — Leonelli, 2023

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Existen muchas definiciones de Ciencia Abierta, utilizadas por distintas organizaciones, pero todas comparten una idea central.

La Ciencia Abierta es un movimiento que tiene como objetivo fomentar la difusión, el escrutinio y el reuso de los componentes de investigación para el bien de la ciencia y la sociedad.

Incluye los principios y las prácticas que hacen que los productos y procesos de investigación estén disponibles para todas las personas por igual.
Por lo tanto, es una forma de pensar y hacer ciencia de manera inclusiva, diversa, equitativa y accesible.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Beneficios de la Ciencia Abierta

Comenzar a aplicar prácticas de Ciencia Abierta, aunque sea de a poco, puede aportar diversos beneficios:

- Aumenta la visibilidad y el impacto.
- Fomenta mejores prácticas de investigación.
- Favorece la colaboración.
- Ayuda a detectar y corregir errores rápidamente.
- Democratiza el acceso al conocimiento y promueve la participación ciudadana.
- Aumenta la transparencia del trabajo y su reproducibilidad.

<!-- 🟨🟨🟨 FIGURA PENDIENTE: cargar `beneficios-ciencia-abierta.jpg` en `episodes/fig/` 🟨🟨🟨 -->

![Ilustración sobre los beneficios de la Ciencia Abierta.](fig/beneficios-ciencia-abierta.jpg){alt='Personas colaboran alrededor de una estructura abierta y conectada que representa el intercambio de conocimientos y recursos.'}

*Fuente: The Turing Way Community & Scriberia (2022), [*Illustrations from The Turing Way*](https://doi.org/10.5281/zenodo.3332807), CC BY 4.0.*

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Una investigación publicada abiertamente tiene mayor visibilidad y potencial de impacto: es más fácil de encontrar, usar y citar.
También permite fomentar la colaboración y la participación en el proceso de investigación.

Por ejemplo, al documentar y publicar un plan de investigación al comienzo de un estudio, se puede obtener retroalimentación de colegas del área antes de que comience la recolección de datos.
Así podemos maximizar el uso de los recursos y evitar algunos sesgos desde el inicio del proceso.

Un buen Plan de Gestión de Datos y Software hace que nuestro proyecto sea más transparente y reproducible.
También nos ayudará a entender nuestro propio proceso en el futuro.
La documentación facilita la detección y corrección de errores, ya sea por nuestro equipo o por otras personas.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Reproducibilidad

La reproducibilidad consiste en obtener los mismos resultados utilizando:

- Los mismos datos de entrada.
- El mismo código o los mismos pasos de análisis.

<!-- 🟨🟨🟨 FIGURA PENDIENTE: cargar `reproducibilidad.png` en `episodes/fig/` 🟨🟨🟨 -->

![Ilustración sobre reproducibilidad.](fig/reproducibilidad.png){alt='Una persona sigue un recorrido que conecta datos, código y resultados documentados para reproducir un análisis.'}

*Fuente: The Turing Way Community & Scriberia (2022), [*Illustrations from The Turing Way*](https://doi.org/10.5281/zenodo.3332807), CC BY 4.0.*

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

La ciencia es más abierta cuando es transparente y reproducible, es decir, cuando otras personas pueden ver y verificar en detalle cómo se llevó a cabo la investigación.

Tradicionalmente, accedemos a una publicación que presenta el objetivo, la metodología y los resultados alcanzados, pero rara vez podemos reproducir dichos resultados a partir de la información disponible.

Muchas veces, los métodos se describen de forma informal o incompleta, hay poca precisión en los criterios utilizados para incluir o eliminar datos, o se presentan datos agrupados sin incluir las observaciones individuales.

Para que un proyecto sea reproducible, necesitamos hacer públicos productos como los datos sin procesar o intermedios, el software y el código de análisis, los materiales empleados y otros objetos de investigación que hayan influido en los resultados alcanzados.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Proceso, productos y resultados de investigación

<!-- 🟨🟨🟨 FIGURA PENDIENTE: cargar `proceso-productos-resultados-investigacion.png` en `episodes/fig/` 🟨🟨🟨 -->

![Proceso, productos y resultados de investigación.](fig/proceso-productos-resultados-investigacion.png){alt='Línea de tiempo de un proyecto de investigación que comienza con la ideación, continúa con la planificación, la recolección y exploración de datos, y finaliza con el reporte y la publicación. En cada etapa se producen objetos que pueden compartirse, como propuestas, planes, materiales de formación, planes de gestión, datos, código, archivos y publicaciones.'}

*Fuente: NASA Open Science.*

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Podemos pensar en un proyecto de investigación como un proceso que abarca desde la ideación de una propuesta hasta la publicación de sus resultados.

En los diferentes momentos, las personas que investigamos producimos distintos objetos que potencialmente pueden compartirse en abierto.
Abrir estos objetos representa abrir gran parte del proceso de investigación y no solamente sus resultados finales.

Dentro de todo este proceso hay matices posibles, porque no existe una única manera de hacer Ciencia Abierta.
Pensarla en nuestros propios contextos ayuda a implementarla en la práctica.
Más adelante retomaremos este punto con mayor detalle.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::


:::::::::::::::::::::::::::::::::::::::::::::::: challenge

## Ejercicio 2: ¿cuándo abrir un proyecto?

¿Cuándo deberíamos empezar a pensar cómo abrir un proyecto?

Seleccioná la opción correcta:

- Solo al final, al publicar.
- Durante el análisis de datos.
- Antes de recolectar datos.
- Desde la planificación.
- No lo sé.

Respondé la encuesta de Zoom.

Tiempo estimado: 3 minutos.

:::::::::::::::::::::::: solution

La respuesta correcta es **desde la planificación**. 

Si la apertura se considera recién al final, puede resultar difícil compartir algunos productos por falta de consentimiento, documentación o acuerdos.

Pensar la apertura desde la planificación no significa que todo deba abrirse, sino decidir de antemano qué se abrirá, cómo, cuándo y bajo qué condiciones. Como indica el principio: tan abierto como sea posible y tan cerrado como sea necesario.

::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## Barreras para las prácticas en Ciencia Abierta

Podemos reconocer tres tipos de barreras:

- Sociales.
- Institucionales.
- De infraestructura.

<!-- 🟨🟨🟨 FIGURA PENDIENTE: cargar `barreras-ciencia-abierta.jpg` en `episodes/fig/` 🟨🟨🟨 -->

![Ilustración sobre barreras para las prácticas en Ciencia Abierta.](fig/barreras-ciencia-abierta.jpg){alt='Una persona intenta avanzar por un recorrido con obstáculos, desniveles y barreras, como representación de las dificultades que pueden surgir al practicar la Ciencia Abierta.'}

*Fuente: The Turing Way Community & Scriberia (2022), [*Illustrations from The Turing Way*](https://doi.org/10.5281/zenodo.3332807), CC BY 4.0.*

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Cuando hablamos de Ciencia Abierta, no hablamos solamente de herramientas o de publicar abiertamente.
También hablamos de condiciones concretas que facilitan o dificultan estas prácticas.

Exploraremos tres tipos de barreras que aparecen con frecuencia: las sociales, las institucionales y las de infraestructura.
Separarlas y entenderlas según nuestros propios contextos nos ayuda a reconocer mejor dónde se encuentran los desafíos y qué tipo de respuestas requieren.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Barreras sociales

- La decisión de abrir el trabajo puede generar desacuerdos.
- La generación de acuerdos requiere tiempo y esfuerzo.
- Reglas claras para la interacción y el uso de los recursos.
- Pautas de convivencia y de uso de licencias.

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Las barreras sociales tienen que ver con cómo trabajamos con otras personas.
Abrir procesos, datos o materiales no siempre genera consenso automáticamente: muchas veces requiere conversaciones, acuerdos y tiempo.

Por eso, contar con reglas claras para la interacción, criterios compartidos y acuerdos sobre el uso de recursos y licencias puede facilitar la colaboración.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Barreras institucionales

- Apoyo insuficiente de las instituciones.
- Falta de recursos, presupuesto y tiempo.
- Poco reconocimiento en evaluaciones.
- Identificar la factibilidad y el alcance posible, y alentar a otras personas a apoyar los esfuerzos.

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

También hay barreras que dependen menos de las personas y más de las instituciones en las que trabajamos.
Muchas veces faltan tiempo, presupuesto, apoyo o reconocimiento para sostener prácticas de Ciencia Abierta.

En esos casos, puede ser útil identificar qué es viable en cada contexto, comenzar por objetivos alcanzables y sumar apoyos dentro de las instituciones para que esos esfuerzos no queden aislados.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Barreras de infraestructura

- Escasez de recursos materiales.
- La mayoría de los repositorios y las herramientas fueron desarrollados en otras regiones.
- Falta de financiamiento.
- Apoyo de la comunidad mediante ideas o infraestructura compartida.
- Trabajo colaborativo.

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Por último, están las barreras de infraestructura, que en América Latina conocemos bien.

No siempre contamos con recursos materiales, financiamiento o herramientas diseñadas para nuestros contextos e idiomas.
Frente a eso, el trabajo colaborativo, las infraestructuras compartidas y el apoyo entre comunidades son formas concretas de sostener prácticas abiertas de manera más realista y situada.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## ¿Qué pasa si…?

- **Errores:** ¿Qué pasa si mi trabajo tiene errores?
- **Apropiación:** ¿Qué pasa si alguien usa mi trabajo, se queda con el crédito o no me cita?
- **Malinterpretación:** ¿Qué pasa si mi trabajo se malinterpreta o se usa fuera de contexto?
- **Datos sensibles:** ¿Qué pasa si mis datos son demasiado sensibles para compartirlos?

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Además de las barreras que acabamos de mencionar, suelen aparecer preocupaciones muy concretas al momento de abrir un trabajo.

¿Qué pasa si hay errores?
¿Qué pasa si alguien se apropia de lo que hice?
¿Qué pasa si se malinterpreta?
¿Qué pasa si hay datos sensibles involucrados?

Son preocupaciones razonables.
A continuación, analizaremos cada una con mayor detalle.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Errores

**¿Y si abro mis materiales de investigación con errores?**

- Los errores son parte de la construcción de la ciencia.
- La evaluación por pares es un pilar del método científico.
- Mientras antes se conocen, antes se corrigen.
- ¡El error no es un fracaso!

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Las políticas de Ciencia Abierta apuntan a cambiar la percepción del error: dejar de considerarlo un fracaso y entenderlo como un paso en el proceso de descubrimiento que puede mejorarse con comentarios abiertos de la comunidad.

La revisión por pares es un pilar central de la construcción de la ciencia y un mecanismo mediante el cual otras personas ayudan a identificar y corregir errores.
Para que esto funcione, necesitamos ser más abiertos a encontrar, reconocer y corregir errores.

Abrir los errores también es una forma de construir ciencia.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Malinterpretación

**¿Y si mis resultados son malinterpretados?**

- La apertura ofrece más contexto para interpretar mejor.
- Puede suceder con o sin Ciencia Abierta.
- Abrir el plan de investigación y la gestión de productos y resultados ayuda a una mejor interpretación.

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Históricamente, muchas publicaciones fueron malinterpretadas.
También sabemos que todo lo que contribuya a mejorar el contexto de una investigación favorece una mejor interpretación.

Los instrumentos de gestión de la apertura, como el Plan de Gestión de Ciencia Abierta, el Plan de Gestión de Datos o cualquier documentación complementaria de los productos intermedios o finales, ayudan a evitar estas malas interpretaciones.

:::::::::::::::::::::::: caution

Abrir genera prácticas que no siempre están previstas y que implican más trabajo del que suele realizarse.
Es importante planificar la investigación considerando el tiempo que implica.

::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Datos sensibles

**¿Y si no puedo abrir mis datos por la sensibilidad que tienen?**

- Tratar los datos para minimizar el riesgo.
- Los datos sensibles son aquellos que pueden causar discriminación o estigmatización.
- Desidentificar y anonimizar, de ser posible, como mecanismo de resguardo.
- Es mejor no abrir si el riesgo es muy alto y está justificado.

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Los datos sensibles incluyen aquellos que pueden causar discriminación o estigmatización, incluso de manera potencial.

Cuando investigamos utilizando datos personales y sensibles, es clave tratarlos para evitar que la información pueda asociarse con una persona; por ejemplo, mediante la desidentificación y, si fuera posible, la anonimización total.

Compartí el enlace a la *Guía práctica para la protección de datos personales en salud* para que quienes participan puedan ampliar la información después del encuentro.

Cuidar los datos sensibles, en algunos contextos, implica no abrirlos.
Un ejemplo es el trabajo con datos de salud de poblaciones muy pequeñas, en las que resulta fácil identificar a grupos con alguna vulnerabilidad o enfermedad poco común.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

### Apropiación

**¿Y si abro mis materiales y se quedan con el crédito de mi trabajo?**

- Asegurar el crédito y facilitar la citación.
- Sucede con o sin Ciencia Abierta.
- Abrir pronto deja evidencia del trabajo en ese campo y ese tema.
- Mientras más abierto, y mejor abierto, más fácil de encontrar y de citar.
- ¡Podemos hacer muchas cosas para facilitar que nos citen!

:::::::::::::::::::::::::::::::::::::::::::::::: instructor

Antes de presentar esta última preocupación, consultá brevemente cómo va el grupo.

Las situaciones de apropiación ocurren independientemente de que los productos o resultados de investigación estén abiertos o no.
Sin embargo, cuando es evidente que se produce una apropiación del crédito, se pone en juego la reputación de quien utiliza los aportes sin reconocerlos debidamente.

Una forma de abordar estas prácticas poco éticas es procurar asegurar el crédito.
Abrir tempranamente, aun con errores, también permite dejar evidencia de que se está trabajando en un tema o campo determinado.
Deja constancia de los avances y de quiénes son sus autoras o autores.

Cuanto más abierto está un trabajo, más fácil es encontrarlo y citarlo, y más difícil es ocultar su origen o su autoría original.

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::


