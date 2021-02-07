![portada](https://github.com/EmilioOcelotl/tres-estudios-abiertos/blob/main/img/tres.png)

# Tres Estudios Abiertos

> Si somos esclavos de la tecnologı́a, es precisamente porque hay todo un conjunto de artefactos de nuestra existencia cotidiana que tenemos por especı́ficamente “técnicos” y que consideramos eternamente como simples cajas negras de las cuales serı́amos sus inocentes usuarios. Comprender cómo funciona cualquiera de los aparatos que nos rodean conlleva a un incremento de potencia inmediato, permitiéndonos actuar sobre aquello que por consiguiente no se nos aparece ya como un medio ambiente, sino como un mundo agenciado de una cierta manera y sobre el cual podemos intervenir. (Comité-invisible, 2014, p. 133)

Este repositorio busca exponer un mapa que permita visualizar el panorama y delimitar posibles rutas. 

Se relaciona con otros repositorios para establecer una red de códigos, documentaciones y bitácoras. 

Obras y actividades relacionadas con el proyecto:

- [THREE.studies](https://github.com/EmilioOcelotl/THREE.studies)
- [Diálogo IV](https://github.com/EmilioOcelotl/dialogoIV) @ Coloquio Salvador Contreras. Artes Sonoras y Creación Musical en México: Siglo XXI
- [Anti](https://github.com/EmilioOcelotl/Anti) (Posible nueva instancia del proyecto, revisar viabilidad e integrar) 
- Artículo 

[Calendario](https://github.com/EmilioOcelotl/tres-estudios-abiertos/tree/main/calendario)

## Objetivos Principales 

- Desarrollar un sistema de sintesis granular visual y sonoro en el navegador.
- Expandir el proyecto a partir de tres capas de complejidad: Uso de frameworks dedicados, exploración de bajo nivel y desarrollo.

## Objetivos Secundarios

- Implementar el sistema en obras. Detonador de la relación entre práctica y reflexión escrita de cara a la tesis. 
- Utilizar una serie de instrucciones personalizadas como interfaz textual que puedan mediar entre niveles y que discutan con el contexto cultural en el que se enmarcan. 
- Realizar reflexiones a manera de documentación, teniendo como eje de vinculación conceptos tecno-sociales y estéticos. 
- Aportar módulos de desarrollo tecnólogico que puedar ser de utilidad para otros proyectos. 
- Estrategias de colaboración y creación a distancia, por medio de la computadora y e instrumentos acústicos. 
- Comparar críticamente el desarrollo tecnológico y la tecnología existente. 
- Documentar los desarrollos y resultados secundarios realizados en colectivo. 

## Resumen

El presente estudio se enfoca en el desarrollo y puesta en marcha de un sistema personalizado para el procesamiento de música e imagen en tiempo real desde el navegador. Aprovecha el potencial de los lenguajes de programación y de las interfaces de texto al vuelo como posibilidad tecnológica y poética. 

De manera secundaria estudiar el rol de la triada instrumento, interpretación y composición con la implementación de un prototipo audio visual que se ejecute como audio/imagen en vivo  y que sirva como partitura en situación de concierto. En términos estéticos el prototipo tendrá como eje la experimentación espacial y temporal. 

Finalmente, a manera de propuesta para la exploración de estas piezas, indaga en las posibilidades creativas y sociales de movimientos que problematizan el conocimiento y la codificación en un contexto creativo como el buen vivir/ buen conocer, DIY (Hazlo tú mismo), DIWO (Hazlo con otros) y la distribución y decentralización en la web. 

[Presentaciones y versiones anteriores](https://github.com/EmilioOcelotl/tres-estudios-abiertos/blob/main/anteriores/README.md)

[Antecedentes](https://github.com/EmilioOcelotl/tres-estudios-abiertos/blob/main/antecedentes/README.md)

![open](https://github.com/EmilioOcelotl/tres-estudios-abiertos/blob/main/img/open.png)

## Introducción

Tres estudios abiertos es un proyecto que se desenvuelve en discusión con la práctica musical.En específico hace referencia a la música por computadora, a la interpretación musical y al uso de interfaces de texto basasadas en lenguajes de programación orentados al audio.

El proyecto de investigación toma en cuenta a los lenguajes de programación orientados a música e imagen como un proceso histórico delimitado por factores sociales, políticos y económicos. La conformación de estas plantaformas ha planteado momentos en los cuales es posible observar giros en la orientación de estas plataformas.

## Música e imagen en el navegador

TEA considera al uso del navegador y de piezas audiovisuales en la web como uno de estos giros. En este sentido, el proyecto explorará las restricciones pero también los ofrecimientos de las tecnologías utilizadas para generar audio e imagen desde el navegador en un contexto web. Es importante señalar que el contexto de la pandemia de 2020 también ha marcado fuertemente el perfil de esta investigación. 

El proyecto se encuentra en un estado inicial y plantea dos momentos específicos: el primero busca ser un primer acercamiento al uso de [WebGL](https://www.khronos.org/webgl/), [Web Audio API](https://developer.mozilla.org/es/docs/Web_Audio_API) (motores de audio y video) y [JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript) vía [three.js](https://threejs.org/). El segundo momento busca explorar las posibilidades en un nivel de programación inferior. Para resolver este último punto la investigación parte de dos plataformas: [WebGL](https://get.webgl.org/) y [WebAssembly](https://webassembly.org/).

El sistema propuesto será un granulador de audio e imagen. El procesamiento de señales de audio y de objetos visuales generados en un entorno 3d tendrán correspondencia y las piezas generadas transformarán simultáneamente al flujo de sonido e imagen. Nota: Clasificación y espectro pueden ser relevantes en el contexto de la reconstrucción. 

La presente propuesta busca aportar elementos abstractos que puedan ser implementadas en el contexto específico de la realización de piezas audiovisuales que coincidan o aporten elementos a otros desarrollos complejos y extensos que sobrepasen los tiempos de esta investigación. El colectivo PiranhaLab puede ser uno de los interlocutores tecno-estéticos colectivos que permitan enriquecer el proyecto de manera diferenciada. Relevancia de los proyectos paralelos. 

## Procesamiento, flujos e interpretación 

Si bien el sistema inicialmente plantea el procesamiento de señales desde el navegador como motor de audio, también plantea la interacción con flujos de audio de fuentes no sintéticos. Idealmente este sistema podría funcionar para procesar la señal de audio de un flujo de audio generado por instrumentistas presencialmente o a distancia. El objeto práctico del prototipo es construir un sistema interactivo en la web que reduzca curvas de instalación y que permita la participación de intérpretes musicales y ejecutantes de la computadora.

El proyecto busca plantear la interacción entre intérpretes musicales, ejecutantes de la computadora y sistema interactivo a través de un proceso de retroalimentación e interacción a través de la percepción  visual(a través de la imagen pero también a través de la lectura de código) y sonora. En este sentido el flujo de audio e imagen es por sí misma la electrónica en vivo de la pieza y al mismo tiempo es una partitura audiovisual sugerida.

El objetivo del proyecto es que la entrada del flujo por parte del intérprete no sea solamente musical o sonora, sino también visual. El uso de cámaras de profundidad podría problematizar la distinción mental / corporal en la música por computadora y en la música por computadora que interactúa con intérpretes musicales. De este punto se pueden extender discusiones sobre la Música por computadora, la interpretación musical, el gesto el cuerpo. Relevante en este sentido:  [Sobre cómo emborrachar a un ordenador](http://users.sussex.ac.uk/~thm21/thor/pdfs/Magnusson_EmborracharUnOrdenador.pdf).

El proyecto busca establecer flujos de audio, imagen e información. Esto se implementará con: [Jack](https://jackaudio.org/) y [Jacktrip](https://ccrma.stanford.edu/software/jacktrip/). Más recientemente: [SonoBus](https://github.com/essej/sonobus) 

## Código como interfaz 

Además de los agentes que interpretan y alimentan con flujos de audio / video al sistema interactivo, el sistema contempla ejecutentes de computadora. Para la realización de esta función el proyecto busca explorar las posibilidades de las interfaces textuales para el control y la transformación de audio e imagen. El ejecutante de la computadora idealmente puede ser un ejecutante al vuelo o *live coder*. La función de este ejecutante consiste en explorar y sacarle sonido a un sistema que por una parte ya está delimitado y es fijo y que por el otro, permite la exploración al vuelo por medio del mismo código que lo ejecuta. La interfaz de audio partira de dialéctos personalizados basados en lenguajes de programación amplios como Javascript o LISP y buscar ser, además de una interfaz eficaz, un recurso poético que permita delimitar las piezas a partir de lo textual. 

La distinción entre intérpretes y ejecutantes de computadora son los extremos de un continuo. Las personas involucradas en la interpretación podrían controlar flujos de audio provenientes de una señal acústica y manipular la señal en este espacio. De hecho el mismo compositor puede ser ejecutante y la idea es que los ejecutantes puedan aportar desde la perspectiva de la composición. Incluso el flujo de la pieza podrá estar delimitado por el mismo sistema. Este último punto ofrecerá una discusión referente a la reconfiguración de la triada composición, intepretación e instrumento. 

La generación de una interfaz de texto basada en código tiene como objetivo principal practicar y reflexionar en torno a la expresividad visual/musical a través de estas interfaces. La generación de capas superiores de código en el contexto permiten expresar una idea con pocos elementos o instrucciones. El presente proyecto se adscribe a la perspectiva del live coding y busca sortear los problemas que surgen en las interpretaciones en situación de concierto con código de programación. El presente proyecto apunta a la descentralización y des-estandarización de las interfaces de alto nivel. 

## Vetas reflexivas 

Esto último apunta a los aspectos reflexivos de la investigación que tienen como punto de partida los estudios del software y el giro de los nuevos medios propuesto por Lev Manovich. Adicionalmente atienden a la problematización de la interfaz, a las decisiones de diseño de software previamente tomadas y a la personalización, distribución y decentralización en el diseño y producción de software. Estas decisiones apuntan hacia la problematización de la centralidad del diseñ del software en términos políticos y prácticos:

> Con las herramientas comerciales disponibles para la interpretación con una laptop como Ableton Live o Radial, las sospechas existentes con respecto a las interfaces fijas y a las decisiones de su diseño provocan un giro hacia el lenguaje de programación personalizable. ¿Por qué no explorar la cualidad de interfaz del lenguaje mismo como una nueva herramienta performática, en marcado contraste con interfaces de usuario que resultan bastante convencionales? (Collins et al., 2003, p. 322)

El proyecto se implementará en software libre y de código abierto. Pretende aprovecharlo como restricción y como ofrecimiento, de acuerdo a las ideas de la Interacción Humano Máquina y al giro que esto puede tener desde la perspectiva del código (Thor Magnusson). La propuesta busca problematizar al software desde la perspectiva del trabajo:

> El argumento de esta sección ha considerado al trabajo en estos términos maquínicos, para ver más allá de la retórica emancipatoria del software libre y tener un entendimiento más detallado del trabajo y la agencia a través de una pluralidad de movimientos sociales, de la auto-organización de los trabajadores, de las culturas del codeo y de la habilidad para escribir, compilar y ejecutar código en modos inesperados. (Cox y McLean, 2013, p. 57)

Finalmente el proyecto busca plantear formas de colaboración teniendo en cuenta un ciclo de interacción entre inérprete, compositor, desarrollador y software:

> discutimos que el software musical introduce tres tipos de interacción que no son cubiertos por el paradigma acústico: el software actúa como un medio distinto y nuevo para la interacción entre personas, el desarrollo de software en contextos creativos implica un nuevo y distinto ciclo de interacción entre el desarrollador y el software, y los elementos del software pueden interactuar entre ellos en formas musicalmente significantes.(Bown et al., 2009, p. 188)

La presente investigación busca relacionar conceptos y práctica artística en varios niveles. Tomamos en cuenta el planteamiento teórico de la síntesis granular y en específico, tendremos en consideración la noción de escalas de tiempo de Curtis Roads como herramienta conceptual de acercamiento-alejamiento del proceso. La observación microscópica nos permitirá hablar del sonido en términos tecnológicos y la macroscópica en términos sociales. La realización de las piezas sucederá en el continuo intermedio.

Del lado macroscópico hablaremos de formas de organización decentralizadas como las redes par a par conceptos y formas de organización que toman en cuenta el conocimiento y lo tecnológico para plantear un motivo constante en la realización de piezas y que pueden ser un motivo para problematizar no solamente la práctica musical y el desarrollo de tecnología musical: 

> “El buen vivir *sumak kawsay*, demanda, en esta globalidad de conocimiento, de un *sumak yachay*, un buen conocer, de los saberes (nuevos y viejos). Es por tanto necesario desarrollar el buen conocer, aquel que beneficia a todos, que crea un entorno rico y fértil para la vida cultural, social, económica, política. En definitiva, crear una matriz productiva basada en conocimiento común y abierto”(Platohedro et al., 2019, p. 31).

[Ideas sueltas](https://github.com/EmilioOcelotl/tres-estudios-abiertos/blob/main/sueltas/README.md)

## Referencias

- Bown, O., Eldridge, A., y Mccormack, J. (2009). Understanding interaction in contemporary digital music: From instruments to behavioural objects. Org. Sound, 14(2):188–196.

- Collins, N. (2006). Towards Autonomous Agents for Live Computer Music: Realtime Machine Listening and Interactive Music Systems. Tesis doctoral, University of Cambridge.

- Collins, N., McLean, A., Rohruber, J., y Ward, A. (2003). Live coding techniques for laptop performance. Organised Sound, 8(3).

- Comité-invisible (2014). [A nuestros amigos](http://mexico.indymedia.org/IMG/pdf/a_nuestros_amigos_-_comite_invisible.pdf).

- Cox, G. y McLean, A. (2013). Speaking Code. Coding as Aesthetic and Political Expression. The MIT Press.

- Latour, B. (2001). La esperanza de Pandora. Ensayos sobre la realidad de los estudios de la ciencia. Gedisa, Barcelona.

- López-Cano, R. y San Cristóbal Opazo, U. (2014). Investigación artística en música. Problemas, métodos, experiencias y modelos. Fonca-Esmuc, Barcelona.

- Magnusson, T. (2010). Designing constraints: Composing and performing with digital musical systems. Computer Music Journal, 34(4):62–73.

- Manovich, L. (2001). The Language of New Media. Leonardo (Series) (Cambridge, Mass.). MIT Press.

- Platohedro, Correa, A., Alvarez, L. M., Fleischmann, L., Rodrı́guez, Y., Rueda, D., Jaramillo, J. A., Correa, C., y Narváez, O. (2019). Platohedro. [Multiversos](https://platohedro.org/multiversos/). Cráneo Invertido, Medellı́n, Colombia.

- Rowe, R. (1993). [Interactive music systems](https://wp.nyu.edu/robert_rowe/text/interactive-music-systems-1993/).

- Welch, C. (2010). Programming machines and people: Techniques for live improvisation with electronics. Leonardo Music Journal, -:25–28.