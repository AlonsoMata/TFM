# Entrega 1 - Propuesta inicial de ideas de producto

## Idea 1 - MixCheck Personal: una segunda opinión para cerrar una mezcla

### Problema que resuelve

Una de las partes que más me cuesta al producir música no es empezar una canción, sino saber cuándo una mezcla está realmente terminada. Después de escuchar el mismo tema durante horas, el oído se acostumbra. En ese punto me resulta difícil distinguir si, por ejemplo, la voz está demasiado alta, si hay más grave del que debería o si simplemente llevo tanto tiempo escuchándolo que ya lo percibo como normal.

Para salir de esa situación suelo comparar con canciones de referencia, mirar medidores y volver a escuchar la mezcla en distintos momentos. Funciona, pero es un proceso bastante manual y depende mucho de la experiencia de quien mezcla. Además, las herramientas que ya existen suelen dar valores técnicos por separado —loudness, espectro, dinámica, picos, etc.—, pero no necesariamente ayudan a interpretar qué merece la pena revisar.

MixCheck Personal partiría de una idea sencilla: cargar una mezcla, elegir una o varias referencias comparables y obtener una segunda opinión basada en datos. La herramienta buscaría diferencias claras en aspectos medibles del audio y las presentaría de una forma útil para tomar decisiones.

No quiero plantearlo como un sistema que diga si una mezcla es “buena” o “mala”, porque hay decisiones que son totalmente artísticas. Lo que me interesa es algo más concreto: que me avise de que hay un elemento que se aleja bastante de las referencias y que quizá conviene volver a escuchar con atención.

### Motivación para realizar el proyecto

Esta es probablemente la idea más personal de las tres porque parte directamente de mi experiencia produciendo y mezclando música. Me interesa especialmente ese momento final en el que ya has trabajado mucho sobre un tema y empiezas a perder objetividad.

Por eso me gustaría investigar si algunas de las comprobaciones que hago de forma manual se pueden convertir en un proceso más ordenado. No para sustituir el oído, sino justo para usar los datos cuando el oído ya está condicionado por haber escuchado demasiadas veces la misma canción.

También me parece una buena forma de unir dos áreas que normalmente trabajo por separado: producción musical y Data Science. Hay muchas variables que se pueden obtener de una señal de audio, pero el reto interesante para mí sería saber cuáles ayudan de verdad a tomar una decisión y cuáles son solo números que quedan bien en una pantalla.

En principio sería posible trabajar tanto con canciones propias como con material disponible públicamente. Más adelante habría que estudiar qué métricas y qué tipo de referencias son realmente útiles para que la comparación tenga sentido.

### A quién impacta

El perfil en el que pienso primero es bastante concreto: productores y artistas independientes que mezclan su propia música y que no siempre tienen a otra persona con experiencia para hacer una última revisión.

También podría ser útil para gente que está aprendiendo a mezclar, pequeños estudios o productores que quieren comparar distintas versiones de un tema sin depender únicamente de su percepción del momento.

### Por qué tiene valor

El valor estaría sobre todo en reducir dudas al final del proceso. Si la herramienta detecta que la mezcla se comporta de forma parecida a las referencias en casi todo, pero que existe una diferencia grande en una zona concreta del espectro o en la dinámica, el productor ya sabe dónde merece la pena centrar la escucha.

Eso puede ahorrar tiempo y, sobre todo, evitar parte de las correcciones hechas a ciegas. Para mí el producto tendría sentido si consiguiera convertir datos técnicos de audio en algo tan simple como: “antes de cerrar esta mezcla, vuelve a revisar esto”.

---

## Idea 2 - AeroDoc QA: apoyo a la revisión documental de software aeronáutico

### Problema que resuelve

En proyectos de software aeronáutico se genera mucha documentación a lo largo del ciclo de vida del software y una parte del trabajo de calidad consiste precisamente en revisarla. No basta con leer cada documento de forma aislada. Hay que comprobar que determinadas evidencias existen, que la información es coherente, que las referencias entre documentos tienen sentido y que no faltan elementos necesarios para continuar con el proceso.

El problema aparece cuando el volumen aumenta. Una incidencia pequeña puede estar escondida en muchas páginas o depender de información que se encuentra en otro documento. Esto obliga al revisor a saltar continuamente entre secciones, versiones y referencias. Es un trabajo en el que la experiencia humana es fundamental, pero también hay una parte repetitiva que consume bastante tiempo.

La idea de AeroDoc QA sería utilizar IA y análisis de texto como apoyo previo a esa revisión. El sistema no aprobaría ni rechazaría documentación. Su función sería localizar señales que merece la pena comprobar: apartados aparentemente incompletos, referencias sospechosas, posibles contradicciones o relaciones entre documentos que no parecen cuadrar.

En vez de sustituir una revisión, intentaría responder a una pregunta mucho más realista: “si tengo que revisar todo esto, ¿por dónde debería empezar a mirar?”.

### Motivación para realizar el proyecto

Esta idea sale directamente de mi experiencia profesional. Al trabajar con revisión documental relacionada con el ciclo de vida de software aeronáutico he visto que una parte importante del tiempo se va, precisamente, en localizar dónde está el posible problema antes de poder valorarlo.

Por otro lado, ya había trabajado anteriormente con IA aplicada a documentación técnica. Juntar ambas experiencias me hizo pensar que quizá el uso más interesante de la IA en este contexto no sea simplemente buscar información en documentos, sino ayudar a detectar qué partes necesitan una revisión más cuidadosa.

También me interesa mantener muy clara la frontera entre apoyo y decisión. En un contexto de software crítico no tendría sentido plantear que un modelo sustituya el criterio del personal de calidad. Sí me parece razonable estudiar si puede actuar como un filtro previo que haga la revisión más eficiente.

Hay además una limitación evidente que tendría que tenerse en cuenta desde el principio: la documentación real puede ser confidencial. Por eso el proyecto tendría que desarrollarse con documentación pública, anonimizada o preparada específicamente para el estudio. Eso condiciona la idea, pero no impide investigar el problema.

### A quién impacta

El usuario más directo sería una persona que trabaja en Quality Assurance o revisión de documentación técnica dentro de proyectos de software aeronáutico.

El enfoque también podría tener interés para equipos de desarrollo, verificación y validación, responsables de proyecto y, en general, organizaciones que trabajan con documentación técnica extensa y controles formales antes de avanzar de una fase a otra.

### Por qué tiene valor

En este caso el valor no estaría en “automatizar la calidad”, sino en utilizar mejor el tiempo de las personas que la garantizan.

Si un sistema consigue detectar con cierta fiabilidad qué documentos, apartados o referencias tienen más posibilidades de contener un problema, el revisor puede dedicar más atención a esos puntos y menos a comprobaciones mecánicas.

Además del posible ahorro de tiempo, también podría servir para hacer más homogéneas algunas revisiones repetitivas. El criterio final seguiría siendo humano, pero la búsqueda inicial de señales podría apoyarse en datos.

---

## Idea 3 - WorkflowRadar: descubrir qué tareas de tu ordenador merece la pena automatizar

### Problema que resuelve

Actualmente hay herramientas para automatizar casi cualquier cosa: scripts, plataformas no-code, asistentes con IA y, cada vez más, agentes capaces de ejecutar tareas. Sin embargo, antes de automatizar algo hay un paso que solemos dar por hecho: darse cuenta de que estamos repitiendo una tarea lo suficiente como para que merezca la pena automatizarla.

En el ordenador hacemos muchas rutinas pequeñas que acaban pasando desapercibidas. Abrir las mismas aplicaciones en un orden concreto, descargar un archivo y prepararlo siempre igual, mover información de un sitio a otro, repetir ciertos pasos cada semana... Ninguna de esas acciones parece especialmente grave por separado, pero juntas pueden ocupar bastante tiempo.

WorkflowRadar intentaría detectar esas rutinas a partir de datos básicos de uso del ordenador. La idea no sería empezar creando un agente que controle todo el equipo. La primera versión tendría un objetivo mucho más acotado: identificar secuencias repetidas, medir cuánto tiempo consumen y ordenar cuáles parecen mejores candidatas para ser automatizadas.

Por ejemplo, si una secuencia de varias aplicaciones y acciones aparece de forma muy parecida cuatro veces por semana, el sistema podría señalarla y estimar cuánto tiempo representa al mes. A partir de ahí sería el usuario quien decide si merece la pena automatizarla.

### Motivación para realizar el proyecto

Lo que me atrae de esta idea es que va un paso antes de la mayoría de herramientas de automatización. Hoy el problema muchas veces no es “cómo automatizo esto”, porque probablemente ya exista alguna forma de hacerlo. El problema es detectar qué parte de nuestro trabajo estamos repitiendo sin darle importancia.

En mi día a día utilizo el ordenador para cosas bastante diferentes: trabajo técnico, documentación, programación, estudio y música. Precisamente por cambiar tanto de herramientas me parece interesante estudiar si se pueden encontrar patrones repetidos sin tener que registrar el contenido de lo que estoy haciendo.

La idea también me interesa porque puede empezar siendo relativamente sencilla. Con frecuencia, duración y repetición de secuencias ya se podría construir una primera medida de “potencial de automatización”. Si el concepto funciona, en fases posteriores se podría investigar cómo recomendar una solución concreta para cada rutina detectada.

La privacidad sería una condición del producto, no un añadido posterior. El objetivo sería detectar patrones de uso sin guardar el contenido de documentos, mensajes o archivos personales.

### A quién impacta

El usuario sería cualquier persona que trabaje muchas horas con un ordenador, aunque creo que tendría más sentido en perfiles que cambian constantemente entre aplicaciones y repiten procesos digitales.

Por ejemplo, podría ser útil para analistas, desarrolladores, perfiles administrativos, estudiantes o pequeños equipos que saben que pierden tiempo en tareas repetitivas pero no tienen una visión clara de cuáles son las que más pesan.

### Por qué tiene valor

Me parece útil porque convierte una sensación bastante difusa —“pierdo tiempo haciendo siempre lo mismo”— en algo medible.

No todas las rutinas merecen una automatización. Algunas se hacen una vez al mes y otras cambian demasiado entre una ejecución y otra. Con datos de frecuencia, duración y similitud se podría priorizar cuáles tienen sentido y cuáles no.

El resultado sería una herramienta que no automatiza por automatizar, sino que ayuda a decidir dónde compensa invertir el esfuerzo. Solo con detectar y ordenar esas oportunidades ya habría un producto útil; automatizarlas podría ser una evolución posterior.

---

## Valoración inicial de las tres ideas

Las tres propuestas salen de contextos con los que tengo relación directa, pero cada una plantea un problema bastante distinto.

**MixCheck Personal** es la que más nace de una necesidad personal. Es una herramienta que yo mismo utilizaría al terminar una mezcla y tiene la ventaja de que el problema es fácil de probar con ejemplos reales.

**AeroDoc QA** es la más ligada a mi experiencia profesional. Creo que puede tener bastante valor porque el problema existe de forma clara, aunque también es la propuesta en la que habría que estudiar con más cuidado cómo conseguir documentación adecuada para desarrollar y evaluar el proyecto.

**WorkflowRadar** es la más experimental de las tres. Me gusta porque parte de una pregunta que no suelo ver planteada: antes de buscar cómo automatizar una tarea, ¿podemos detectar con datos qué tareas merece realmente la pena automatizar?

Todavía no tengo una idea definitiva. Para la siguiente fase me parecería importante comprobar qué datos podría conseguir en cada caso y hasta dónde se puede llegar con un alcance razonable antes de escoger una.
