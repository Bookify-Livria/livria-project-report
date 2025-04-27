# Livria
<p align="center">  <img src="https://imgur.com/IFP8FSt.png" alt="logoupc" width="100"></p>

<p align="center">Universidad: Universidad Peruana de Ciencias Aplicadas (UPC)</p>
<p align="center">Carrera: Ingeniería de Software</p>
<p align="center">Ciclo: 05</p>
<p align="center">Sección 4388</p>
<p align="center">Profesor: Alex Humberto Sánchez Ponce</p>

<p align="center"><strong>Informe del Trabajo Final</strong></p>

<p align="center">Argomedo Camacho, Jhosep Jamil U20231D978</p>
<p align="center">Binda Arbañil, Marcelo Alejandro u202311157</p>
<p align="center">Borja Molina, Gabriel Sebastián U202310308</p>
<p align="center">Castillo Garay, Ainhoa Lucía U202311701</p>
<p align="center">Sulca Silva, Melisa Geraldine U202224602</p>

<p align="center">Abril 2025</p>

# Registro de versiones del informe
| **Versión**  | **Fecha**   | **Autor/es**                                                                                           | **Descripción**                                                                                                                |
|--------------|-------------|--------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| 1.0 (TB1)    | 25/04/25    | - Argomedo Camacho, Jhosep Jamil <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián <br> - Castillo Garay, Ainhoa Lucía <br> - Sulca Silva, Melisa Geraldine <br> | Capítulo I: Introducción <br> Capítulo II: Requirements Elicitation & Analysis <br> Capítulo III: Requirements Specification <br> Capítulo IV: Product Design <br> Capítulo V: Product Implementation, Validation & Deployment |

# Project Report Collaboration Insights

# Contenido
- [Livria](#livria)
  
- [Registro de versiones de informe](#registro-de-versiones-del-informe)

- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Contenido](#contenido)

- [Student Outcome](#student-outcome)

- [CAPÍTULO 1: INTRODUCCIÓN](#capítulo-1-introducción)
  * [1.1. Startup Profile](#11-startup-profile)
    + [1.1.1. Descripción del Startup](#111-descripción-del-startup)
    + [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)
    + [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    + [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

- [CAPÍTULO 2: REQUIREMENTS ELICITATION & ANALYSIS](#capítulo-2-requirements-elicitation--analysis)
  * [2.1. Competidores](#21-competidores)
    + [2.1.1. Análisis Competitivo](#211-análisis-competitivo)
    + [2.1.2. Estrategias y tácticas frente a los competidores](#212-estrategias-y-tácticas-frente-a-los-competidores)
  * [2.2. Entrevistas](#22-entrevistas)
    + [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    + [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    + [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  * [2.3. Needfinding](#23-needfinding)
    + [2.3.1. User Personas](#231-user-personas)
    + [2.3.2. User Task Matrix](#232-user-task-matrix)
    + [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    + [2.3.4. Empathy Mapping](#234-empathy-mapping)
    + [2.3.5. As-Is Scenario Mapping](#235-as-is-scenario-mapping)
  * [2.4 Ubiquitous Language](#24-ubiquitous-language)

# Student Outcome

ABET - EAC - Student Outcome 5
Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|:------------------------|:-------------------------|:-----------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | - Argomedo Camacho, Jhosep Jamil (TB1) <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián (TB1) <br> - Castillo Garay, Ainhoa Lucía (TB1) <br> - Sulca Silva, Melisa Geraldine (TB1) | El equipo de Livria ha demostrado una destacada capacidad para trabajar de manera colaborativa y ejercer un liderazgo compartido a lo largo del proyecto. Desde la definición del perfil de la startup hasta el diseño del producto, se aprecia una organización sólida y una distribución efectiva de roles, donde cada integrante aportó su conocimiento especializado. La implementación de metodologías como Lean UX y Domain-Driven Design, sumada a la planificación de la arquitectura de software y el diseño de la interfaz, refleja una visión alineada y un liderazgo distribuido a través de todas las etapas del proceso. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | - Argomedo Camacho, Jhosep Jamil (TB1) <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián (TB1) <br> - Castillo Garay, Ainhoa Lucía (TB1) <br> - Sulca Silva, Melisa Geraldine (TB1) | El desarrollo de Livria también resalta la creación de un entorno de trabajo cooperativo y abierto a la participación activa. El profundo trabajo de recopilación y análisis de requisitos, a través de entrevistas, técnicas de needfinding y la elaboración de user personas, evidencia un compromiso genuino por entender a los usuarios y responder a sus necesidades reales. La definición clara de los objetivos del producto y de los segmentos de usuarios objetivo muestra una planificación estratégica sólida. La organización de tareas se ve plasmada en la estructuración del documento, la construcción del Product Backlog y la preparación del primer sprint enfocado en el desarrollo de la landing page. El progreso alcanzado en la fase inicial de implementación reafirma la capacidad del equipo para convertir la planificación en resultados concretos. |
# CAPÍTULO 1: INTRODUCCIÓN
## 1.1. Startup Profile
### 1.1.1. Descripción del Startup
Bookify es una startup liderada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC) dedicada a impulsar la lectura y facilitar su acceso en entornos digitales. Con el objetivo de acercar la literatura a más personas, se ha desarrollado el proyecto Livria, una aplicación web innovadora que permite a los usuarios descubrir, adquirir y disfrutar de libros en diversos formatos: físicos, electrónicos y audiolibros. 
En Bookify, creemos que la lectura es fundamental para el aprendizaje, la cultura y el desarrollo del pensamiento crítico. No solo se trata de un hábito, sino de una elección. Por ello, a través de una experiencia intuitiva y personalizada, Livria busca convertirse en el punto de encuentro ideal entre lectores y su próxima gran historia.

Misión: Promover el hábito de la lectura y facilitar el acceso a la literatura mediante una plataforma digital intuitiva y accesible. Livria busca conectar a los lectores con una amplia selección de libros en diferentes formatos, brindando una experiencia personalizada que fomente el amor por la lectura y el conocimiento.

Visión: Convertirse en la plataforma líder en América Latina para la compra y disfrute de libros en formatos físico, digital y audiolibro. Aspiramos a revolucionar la forma en que las personas acceden a la literatura, creando una comunidad de lectores apasionados y fortaleciendo la cultura literaria en el mundo digital.
### 1.1.2. Perfiles de los integrantes del equipo

## 1.2. Solution Profile
Livria es una aplicación web diseñada para revolucionar la manera en que las personas adquieren y disfrutan de los libros. A través de una plataforma intuitiva y accesible, ofrece una amplia selección de títulos, permitiendo a los usuarios explorar y comprar sus lecturas favoritas de forma fácil y rápida. Con el objetivo de fomentar el hábito de la lectura y crear una comunidad de amantes de los libros, Livria facilita la conexión entre los lectores y el mundo literario en un entorno digital moderno.
### 1.2.1. Antecedentes y Problemática
De acuerdo con Lean Construction México, la metodología de las 5W’s y 2H’s permite estructurar y desarrollar un plan de acción o una estrategia detallada (Alvarez, 2020). En este contexto, esta herramienta resulta clave para comprender a fondo las necesidades de los usuarios. Por esta razón, se utilizó para recopilar información, la cual se presentará a continuación.
#### 1.2.1.1. What
#### 1.2.1.1.1. ¿Cuál es el problema?
Livria nace como respuesta a una problemática alarmante: la falta de hábito de lectura y los bajos niveles de comprensión lectora, especialmente en adolescentes y jóvenes. Según la Encuesta Nacional de Lectura de 2022 (Ministerio de Cultura), solo el 15.3 % de menores de 0 a 17 años lee con regularidad diaria y, peor aún, el 21.2 % no lee en absoluto. En adultos alfabetos de 18 a 64 años, a nivel nacional, existe un porcentaje mayor de no lectores, que asciende al 52.7% (Ministerio de Cultura, 2022), lo que evidencia un hábito lector frágil y poco sostenido.

A esto se suma la influencia de las redes sociales y el consumo de contenido breve e inmediato, que ha desplazado el interés por la lectura profunda y reflexiva. Un estudio realizado en una institución educativa pública del distrito de El Agustino en 2022 reveló que el 72.2 % de los estudiantes de secundaria se encuentran en un nivel bajo de comprensión lectora, y solo un 1.9 % alcanzó un nivel alto (Torres-Vega, 2025). Esta situación refleja una crisis silenciosa en el desarrollo educativo y cognitivo de las nuevas generaciones.

En este contexto, Livria se presenta como una solución innovadora que busca revertir esta tendencia preocupante. A través de una plataforma web moderna, accesible y atractiva, busca acercar los libros a los usuarios, fomentar el gusto por la lectura y construir una comunidad de lectores comprometidos, adaptada a los hábitos digitales de hoy.
#### 1.2.1.1.2. ¿Cuál es la relación con la persona en cuestión?
Para todo aquel que esté interesado en la lectura, Livria se presenta como una plataforma atractiva que elimina las barreras en el acceso a materiales adecuados, fomenta el hábito de la lectura y conecta a los jóvenes con libros en distintos formatos, adaptándose a sus costumbres digitales y promoviendo el interés por la lectura de manera dinámica y envolvente.
#### 1.2.1.2. When
#### 1.2.1.2.1. ¿Cuándo sucede el problema?
El problema de la baja tasa de lectura y comprensión lectora se agrava cuando los potenciales lectores enfrentan barreras de acceso a los materiales de lectura. 
Específicamente, esto ocurre cuando:
* Una persona intenta acceder a material de estudio o contenido literario que no está disponible en las principales plataformas
* Enfrenta dificultades con los procesos de compra o alquiler debido a largos tiempos de entrega
* Encuentra inconvenientes con los métodos de pago ofrecidos
* Necesita acceso inmediato a contenido pero debe esperar por cuestiones logísticas
* No encuentra un entorno motivador o una red de apoyo que lo incentive a continuar leyendo, lo que impide que la lectura se transforme en un hábito.

Estas barreras desincentivan el hábito lector y contribuyen directamente a las bajas estadísticas citadas en la Encuesta Nacional de Lectura, especialmente en un contexto donde lo digital e inmediato predomina.
#### 1.2.1.2.2. ¿Cuándo utiliza el cliente el servicio?
El cliente usará Livria precisamente cuando quiera o necesite acceder a material de lectura sin enfrentar estas barreras, permitiéndole desarrollar y mantener un hábito lector regular gracias a su sistema de entrega rápida para libros físicos y acceso instantáneo a materiales digitales.

Además, cuando el cliente desea compartir sus opiniones, descubrir nuevas lecturas recomendadas por personas con intereses similares o interactuar con otros lectores apasionados, utilizará la sección de comunidad. Este espacio impulsa la conexión social en torno a la lectura, creando un entorno motivador y enriquecedor para los usuarios.
#### 1.2.1.3. Where
#### 1.2.1.3.1. ¿Dónde está el cliente cuando usa el producto?
Debido a que Livria es una aplicación web, el usuario puede acceder al producto desde cualquier lugar. La plataforma está diseñada para ser accesible desde cualquier entorno con conexión a internet, de modo que los usuarios puedan disfrutar de sus funcionalidades sin importar en dónde estén.
#### 1.2.1.3.2. ¿Dónde surge el problema?
La problemática surge en los hogares y escuelas del Perú. Estos espacios son fundamentales para la formación de hábitos y habilidades lectoras, pero, en la actualidad, no se promueve activamente la lectura como una práctica cotidiana. La escasa presencia de libros, la ausencia de rutinas de lectura y el poco estímulo hacia el interés por los textos en estos espacios limitan el desarrollo del hábito lector.
#### 1.2.1.4. Who
#### 1.2.1.4.1. ¿Quiénes están involucrados?
Los principales involucrados en Livria son, en primer lugar, los amantes de la lectura, quienes buscan un espacio dinámico y accesible para descubrir, compartir y disfrutar de nuevos libros. Además, un grupo clave son aquellas personas, especialmente adolescentes y jóvenes, que desean mejorar su hábito lector o incluso dar sus primeros pasos en el mundo de la lectura.
#### 1.2.1.4.2. ¿A quiénes les sucede el problema?
El problema afecta principalmente a adolescentes y jóvenes, quienes enfrentan dificultades en la comprensión lectora y han perdido el interés por la lectura debido a la influencia de las redes sociales y el consumo de contenido breve e inmediato. Asimismo, afecta a adultos de diferente rango de edad, quienes muchas veces no cuentan con el tiempo, el hábito o el acceso a libros adecuados. En un sentido más amplio, el problema repercute en la sociedad en general, ya que la falta de lectura impide el desarrollo del pensamiento crítico, la educación y el acceso a la información, reduciendo las oportunidades de crecimiento personal y profesional.
#### 1.2.1.4.3. ¿Quién lo utilizará?
Livria será utilizada por una variedad de usuarios con necesidades y características específicas. En primer lugar, por adolescentes y jóvenes en busca de entretenimiento educativo, que desean una plataforma que haga la lectura más atractiva y relevante, con géneros y libros populares y recomendaciones personalizadas; así como aquellos con dificultades en comprensión lectora que buscan mejorar sus habilidades de lectura de manera accesible y adaptada a su ritmo. Por otro lado, adultos de diferentes edades que han dejado de leer por falta de tiempo o motivación, pero ahora desean retomar el hábito de la lectura con libros que se ajusten a sus intereses y disponibilidad de tiempo.
#### 1.2.1.5. Why
#### 1.2.1.5.1. ¿Cuál es la causa del problema?
Puesto que la problemática es la falta de hábito de lectura y los bajos niveles de comprensión lectora, se pueden identificar diversas causas que contribuyen a esta situación.

Una de las principales es la influencia de las redes sociales y el consumo de contenido digital breve. La exposición constante a videos cortos, memes y publicaciones rápidas ha modificado los hábitos de consumo de información, reduciendo la capacidad de concentración y la disposición a leer textos extensos. Esto ha generado que, especialmente entre adolescentes y jóvenes, la lectura se perciba como una actividad poco atractiva o demasiado exigente en comparación con el entretenimiento inmediato que ofrece el entorno digital. A medida que los jóvenes dedican mayor tiempo a las redes sociales, se incrementa el impacto negativo en su rendimiento académico (Mamami et al.,2024) y, por ende, se compromete su nivel de comprensión lectora. 

Otra causa significativa es la falta de estímulo lector en el hogar. Muchos niños y jóvenes crecen en contextos donde la lectura no forma parte de la rutina diaria, ya sea por la ausencia de libros en casa, el poco interés de los adultos responsables o la falta de tiempo para compartir momentos de lectura en familia. Esta falta de acompañamiento desde edades tempranas limita el desarrollo de un vínculo positivo con la lectura. Además, se suma el escaso acceso a libros atractivos y adecuados. La adquisición de ellos es, muchas veces, dificultosa por cuestiones económicas; el acceso a nuevas ediciones se convierte en un lujo (D’Adderio, 2020). La limitada oferta de títulos que conecten con los gustos, intereses y realidades de los jóvenes, junto con el elevado costo de muchos libros o su baja disponibilidad en espacios públicos como bibliotecas, hace que el hábito lector sea difícil de desarrollar y sostener en el tiempo.
#### 1.2.1.6. How
#### 1.2.1.6.1. ¿En qué condiciones los clientes utilizan nuestro producto?
Los clientes utilizan Livria en diversas condiciones, pero principalmente desde su entorno cotidiano, como su hogar, centro de estudio o lugar de trabajo, a través de dispositivos como celulares, tablets o computadoras. Dado que la plataforma es web, los usuarios pueden explorar o adquirir libros en sus momentos libres, durante viajes o tiempos de ocio. 

Además, muchos usuarios acceden a Livria cuando desean encontrar nuevas lecturas, mejorar su comprensión lectora, o simplemente reconectar con el hábito de leer. Estas condiciones provienen de intereses personales, necesidades académicas, o el deseo de aprovechar mejor su tiempo libre. En general, la plataforma se adapta al usuario, priorizando la comodidad, la accesibilidad y la personalización de la experiencia lectora.
#### 1.2.1.6.2. ¿Cómo nos conocieron los compradores?
Los compradores conocen Livria mediante diversas vías de marketing, tales como la promoción en redes sociales (TikTok, Instagram, etc.), donde se comparte contenido relevante sobre el producto y se realizan campañas publicitarias para atraer a posibles clientes interesados en la lectura. Asimismo, los compradores pueden descubrir la plataforma a través de cartelería publicitaria en locales relacionados con el mundo de la lectura, como las bibliotecas públicas o la tienda física de Livria.
#### 1.2.1.6.3. ¿Cómo prefieren los lectores acceder a nuestro contenido?
Los lectores prefieren acceder al contenido de Livria de manera rápida, sencilla y personalizada, a través de la aplicación web accesible desde sus dispositivos móviles o computadoras. Lo cual les permitirá realizar búsquedas y compras de libros desde cualquier lugar en que se encuentren. Además, prefieren el contenido de Livria por ser de acceso flexible, dinámico y conectado con sus hábitos digitales, donde leer se siente como una experiencia placentera y no como una obligación.
#### 1.2.1.6.4. ¿Qué llevó a la persona a llegar a esta situación?
Lo que llevó a la persona a llegar a esta situación —es decir, a perder el hábito de lectura o a tener poca comprensión de textos— es una combinación de factores personales y sociales que se han acumulado a lo largo del tiempo.

En muchos casos, la falta de estímulos adecuados desde la infancia, tanto en el hogar como en la escuela, impidió que la lectura se convirtiera en una actividad cotidiana o placentera. Muchos educadores afirman que los recursos que poseen son poco suficientes para desarrollar la motivación de lectura en sus estudiantes (Fabiana & Vega, 2022). Además, la poca disponibilidad de libros atractivos o económicamente accesibles han contribuido al alejamiento del mundo literario.

A esto se suma la influencia creciente del entorno digital, donde predominan contenidos breves, visuales y de consumo rápido, que reducen la capacidad de concentración y hacen que leer un libro parezca una tarea demandante o incluso aburrida. En algunos casos, también influyen falta de tiempo, desmotivación o desconocimiento sobre qué leer o cómo empezar.

Todo esto ha llevado a que muchas personas lleguen a la actualidad sin una conexión real con los libros, con niveles bajos de comprensión lectora y con la sensación de que leer es algo ajeno a sus intereses o estilo de vida.
#### 1.2.1.7. How Much
#### 1.2.1.7.1. Estadísticas que sustentan la problemática
Según los resultados de la Encuesta Nacional de Lectura de 2022 (Ministerio de Cultura), aunque el 78,8 % de niños y adolescentes de 0 a 17 años leyeron o fueron expuestos a la lectura de libros impresos o digitales, solo un 15,3 % lo hizo con frecuencia diaria, mientras que la mayoría (63,5 %) leyó con menor regularidad. Además, un 21,2 % no tuvo contacto con la lectura en absoluto, lo que evidencia una baja intensidad en las prácticas lectoras dentro de este grupo etario.

<p align="center">
  <img src="https://i.imgur.com/UdQNapX.png" alt="Organigrama" width="500">
</p>

Un estudio realizado en una institución educativa pública del distrito de El Agustino en 2022 reveló que el 72,2 % presenta un nivel bajo de comprensión lectora, el 25,9 % se encuentra en un nivel regular y solo el 1,9 % alcanza un nivel alto, lo que evidencia una preocupante deficiencia en esta habilidad (Torres–Vega, 2025).

<p align="center">
  <img src="https://imgur.com/U4MSMKk.png" alt="estudio" width="500">
</p>

Una investigación realizada en la Institución Educativa San Jerónimo-Asillo, en Perú, analizó la relación entre el uso de TikTok y el rendimiento académico de estudiantes de quinto grado. Los resultados muestran que el 74.8 % de los alumnos se encuentra en un nivel de rendimiento regular y el 25.2 % en un nivel alto (Mamani et al., 2024). La mayoría de quienes usan TikTok con frecuencia tienden a ubicarse en el grupo de rendimiento regular, lo que sugiere una posible relación entre el uso de esta red social y un menor desempeño académico.

<p align="center">
  <img src="https://imgur.com/bF0zSwe.png" alt="estudio2" width="500">
</p>

### 1.2.2. Lean Ux Process
El enfoque de Lean UX se basa en la colaboración para crear productos de alta calidad, priorizando la optimización de la experiencia del usuario y la satisfacción del cliente sobre la perfección del diseño. Esta metodología permite obtener mejores resultados al entender completamente la visión del negocio, brindando flexibilidad para integrar ideas y lograr soluciones efectivas. (Lean UX y Lean Startup: potencia experiencia y diseño de producto, 2023).
#### 1.2.2.1. Lean UX Problem Statements
Livria es una plataforma que combina la experiencia de una librería física con la comodidad de una tienda virtual. Más que un punto de venta, buscar fomentar el hábito de lectura, mejorar la comprensión lectora y construir una comunidad literaria adaptada a los hábitos digitales. Se ha identificado que la lectura enfrenta múltiples desafíos en la actualidad. La inmediatez del contenido en redes sociales, la falta de espacios que incentiven la lectura y la percepción de los libros como una obligación han reducido el interés por leer. Además, los lectores se enfrentan a una experiencia fragmentada, teniendo que alternar entre librerías físicas y digitales para descubrir, comprar y compartir libros, lo que dificulta la conexión con otros lectores y el acceso a contenido relevante. ¿Cómo podemos mejorar la experiencia literaria digital para facilitar la compra de libros, motivar el hábito lector, mejorar la comprensión lectora y conectar a los usuarios en una comunidad dinámica y accesible?
#### 1.2.2.2. Lean UX Assumptions
Features

* Algoritmos de recomendación de libros y autores.
* Comunidades de usuarios con inclinaciones literarias similares.
* Búsqueda avanzada
* Compra y venta de libros digitales y físicos
* Opciones de entrega flexibles según las necesidades del cliente
* Amplio catálogo de obras literarias

Business Outcomes

* Incentivar la lectura: El principal objetivo de Livria es promover el hábito de la lectura en las personas, ya sea con fines educativos, de entretenimiento o como una alternativa de pasatiempo saludable. Nuestra startup promueve el acceso a material de lectura de todo tipo de manera rápida y sencilla, ofreciendo al lector diferentes opciones, filtros de búsqueda y recomendaciones personalizadas, facilitando el proceso de encontrar un libro que se ajuste a sus intereses. Además, Livria incorpora una sección de comunidad, donde los usuarios pueden interactuar con otros lectores, compartir reseñas, participar en foros temáticos y descubrir lecturas recomendadas por personas con gustos similares.
* Generación de ingresos: Al habilitar la monetización a través del uso de la aplicación web y el modelo de negocio por suscripciones, nuestra startup podrá generar ganancias que pueden ser utilizadas para mejorar la calidad de nuestro servicio, expandir nuestra marca y ofrecer un catálogo más amplio de productos para nuestros usuarios. Estas mejoras garantizarán una mejor experiencia para los usuarios previos y captar nuevo público.
* Diferenciación en el mercado: La aplicación web de Livria ayudará a nuestra startup a destacarse en el mercado y llamar la atención de clientes objetivos gracias a sus funcionalidades y características únicas, como un algoritmo de recomendación de libros y descuentos personalizados, y especialmente, la sección de comunidad.
* Formación de asociaciones comerciales: Las características únicas del servicio de Livria permitirán el establecimiento de alianzas estratégicas con negocios de rubros similares o relacionados al nuestro, tales como imprentas, distribuidoras y editoriales.

User Benefits

* Acceso a una amplia variedad de libros impresos y digitales desde una sola plataforma, permitiendo explorar y adquirir lecturas de forma rápida y sencilla.
* Mejora de la comprensión lectora mediante herramientas interactivas como resúmenes, visuales explicativos y guías adaptadas al nivel de cada usuario.
* Recomendaciones personalizadas según intereses, nivel lector y hábitos de lectura, facilitando la conexión con libros significativos y motivadores.
* Espacios de interacción y comunidad donde los usuarios pueden compartir opiniones, participar en clubes de lectura y descubrir nuevas obras a través de otros lectores.
* Experiencia accesible desde cualquier dispositivo, pensada para adolescentes, jóvenes y adultos que buscan flexibilidad y comodidad al leer.
* Fomento del hábito lector mediante dinámicas motivacionales como recomendaciones y notificaciones personalizadas.
* Ahorro de tiempo y esfuerzo en la búsqueda de libros adecuados, al centralizar en una sola plataforma la selección, compra y gestión de lecturas.

¿Quién es el usuario?

El usuario de Livria es una persona interesada en la lectura, motivada por el deseo de descubrir nuevos libros y enriquecer su conocimiento. Estos usuarios valoran el acceso rápido a una amplia variedad de títulos, las recomendaciones personalizadas y la conexión con una comunidad que comparte su pasión por los libros.

¿Dónde encaja nuestro producto en su trabajo o vida?

Livria encaja en la vida de sus usuarios como una herramienta accesible y práctica que facilita el acceso a la lectura en cualquier momento y lugar. Se adapta a sus rutinas diarias, ya sea en tiempos de estudio, descanso o traslado, permitiéndoles descubrir nuevos libros, organizar sus lecturas y mantener el hábito lector como parte esencial de su día a día.

¿Qué problemas tiene nuestro producto y cómo se puede resolver?

Un desafío que podría enfrentar Livria es la competencia con otras plataformas de lectura digital, especialmente si su oferta de contenido o sus funcionalidades no resultan lo suficientemente atractivas para los usuarios. Este problema se puede resolver mejorando constantemente la experiencia del usuario, ampliando el catálogo con títulos actualizados y variados, y reforzando sus características distintivas, como el sistema de recomendaciones personalizadas, los filtros de búsqueda y las alianzas con editoriales para ofrecer contenido exclusivo.

¿Cuándo y cómo es usado nuestro producto?

Livria es utilizada principalmente durante momentos de ocio, estudio o relajación, cuando los usuarios deseen sumergirse en la lectura. La plataforma permite explorar títulos por género, autor o recomendaciones personalizadas, facilitando una experiencia lectora cómoda y adaptada a los intereses del usuario. Está diseñada para usarse en cualquier momento del día, ya sea desde la comodidad del hogar, durante trayectos en transporte público o en breves momentos de descanso, brindando acceso inmediato a una amplia variedad de lecturas desde cualquier dispositivo.

¿Qué características son importantes?

Las características más importantes son:

1. Algoritmo de recomendación: La principal característica diferenciadora de nuestra startup, ya que nuestra propuesta se basa en diseñar una aplicación web cuyas funciones estén orientadas al cliente y sus intereses, para que puedan encontrar obras que se ajusten a sus gustos o necesidades de una manera mucho más sencilla.
2. Oferta de un amplio repertorio de obras: Para competir en el mercado de las librerías, es necesario ofrecer bastante variedad de títulos de diferentes géneros, teniendo en cuenta su relevancia en el mercado y su importancia para los rubros específicos a los que queremos acatar, como podría ser el académico o el sector crítico.
3. Rápido acceso a libros digitales y físicos: Nuestra startup debe diferenciarse por sus facilidades de acceso y compra de libros tanto digitales como físicos, con entregas rápidas y procesos de pago prácticos que nos ayuden a resaltar entre las otras alternativas.
4. Descuentos y ofertas exclusivas para suscriptores: Para aumentar el valor de la suscripción de nuestros clientes y llamar más su atención, ofreceremos beneficios exclusivos que llamen la atención de los usuarios y les permitan adquirir más material de lectura.
5. Apartado de comunidad: Nuestra aplicación web ofrecerá un apartado dedicado a la formación de comunidades en los que lectores con intereses similares puedan interactuar y expresarse, para lograr fidelizarlos a la empresa y aumentar la diferenciación y valor del servicio respecto a su competencia.

¿Cómo debe verse nuestro producto y cómo comportarse?

Livria debe ser una plataforma amigable y cálida, que invite a nuestros clientes a sumergirse en el mundo de la lectura, tanto a lectores frecuentes como iniciantes. Para lograr esto, nuestro proyecto debe tomar un enfoque más cercano al cliente y más flexible en comparación a nuestros competidores. Su diseño debe ser visualmente atractivo y a la vez calmado, inspirando un ambiente de comodidad y estabilidad para el lector.

* Interfaz cálida e intuitiva: El diseño de las diversas pantallas de la plataforma debe ser agradable a la vista y cómodo de usar, permitiendo tanto a usuarios nuevos familiarizarse rápidamente con las diversas funcionalidades como a los usuarios experimentados navegar fácilmente hacia las secciones que quieren consultar.
* Navegación inteligente: La funcionalidad de búsqueda debe ofrecer facilidades al usuario para encontrar los productos que quiere adquirir, simplificando el proceso de búsqueda y mejorando su experiencia con la plataforma.
* Facilidad de uso: El usuario debe disponer de herramientas que faciliten la utilización del servicio, con accesos rápidos a las diferentes funciones que ofrece la plataforma y las pantallas a las que quiere acceder.

#### 1.2.2.3. Lean UX Hypothesis Statements
Creemos que, al facilitar el acceso a libros en formato físico, digital (ebooks) y audiolibro en nuestra app web Livria, aumentaremos la constancia lectora de nuestros usuarios y mejoraremos el hábito de lectura en comunidades con baja frecuencia de lectura. Sabremos que hemos tenido éxito, cuando veamos un aumento del 60% en el número de usuarios que terminan de completar al menos un libro por mes en cualquier tipo de formato utilizado.

Creemos que, al ofrecer recomendaciones personalizadas basados en los gustos, hábitos de lectura e intereses de nuestros clientes, mejoraremos la experiencia del nuestro usuario y fomentaremos que descubran diversos libros nuevos con la finalidad de aumentar la retención y participación en la aplicación web. Sabremos que hemos tenido éxito, cuando veamos que al menos un 80% de los usuarios interactúa con la sección de recomendaciones y registra libros sugeridos por la aplicación.

Creemos que, al diseñar una aplicación web accesible y funcional en múltiples dispositivos para nuestros clientes, permitirá una adopción más inclusiva en el hábito de la lectura. Sabremos que hemos tenido éxito, cuando veamos que un 70% de los usuarios activos, que acceden a la aplicación web desde diferentes plataformas, provienen de distintos contextos sociales y niveles educativos.

Creemos que, al integrar una sección de comunidad en nuestra aplicación web Livria, donde los usuarios puedan interactuar, compartir recomendaciones, participar en foros literarios y formar redes con otros lectores, incrementaremos la motivación y el compromiso con la lectura, especialmente en personas que actualmente no leen con frecuencia o abandonan libros antes de terminarlos. Sabremos que hemos tenido éxito cuando observemos que al menos el 65% de los usuarios activos participan en alguna actividad de la comunidad (comentarios, reseñas, debates, grupos de lectura, etc.) y que el 50% de ellos reporta haber terminado más libros gracias al incentivo de estas interacciones sociales.

#### 1.2.2.4. Lean UX Canvas

<p align="center">
  <img src="https://imgur.com/432D7hr.png" alt="canvas1" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/00fanZ9.png" alt="canvas2" width="500">
</p>

Link del Lean UX Canvas: https://docs.google.com/document/d/1IusijSIM7pGQxbRqBPXiQuV3y2nqFwOo/edit 

## 1.3. Segmentos Objetivo
Con el objetivo de atraer eficazmente a futuros usuarios y brindar un producto que responda de manera precisa a sus necesidades, se han identificado los siguientes dos segmentos objetivo.

**Segmento objetivo #1: Estudiantes y jóvenes universitarios**

Aquellas personas que necesitan acceder a material de lectura tanto académico como recreativo, buscando una plataforma digital que facilite sus estudios y fomente su hábito lector.

**Aspectos demográficos:**
* Sexo: Masculino y femenino
* Rango de edad: 14-25 años
* Nivel socioeconómico: clases B y C (media-alta y media)

**Aspectos geográficos:**
* Nacionalidad: Global, no específico
* Zona geográfica: Urbana

**Aspectos psicográficos:**
* Intereses: Educación, desarrollo personal, lectura digital y productividad.
* Estilo de vida: Estudiantes activos que equilibran estudios, ocio y vida social. Acostumbrados al uso de plataformas digitales para su aprendizaje y organización diaria.
* Actitudes: Motivados por el aprendizaje continuo, valoran el acceso rápido a información útil, y buscan herramientas que mejoren su rendimiento académico y personal. Son receptivos a la innovación digital y abiertos a nuevas formas de consumir contenido educativo.

**Segmento objetivo #2: Lectores casuales y aficionados a la lectura**

Personas que leen por placer y buscan una experiencia digital que les permita descubrir nuevos títulos, recibir recomendaciones personalizadas y acceder fácilmente a sus libros favoritos.
**Aspectos demográficos:**
* Sexo: Masculino y femenino
* Rango de edad: 24 años a 64
* Nivel socioeconómico: clases A, B y C (alta, media-alta y media)

**Aspectos geográficos:**
* Nacionalidad: Global, no específico
* Zona geográfica: Urbana

**Aspectos psicográficos:**
* Intereses: Lectura contemporánea y clásica, exploración cultural, apreciación del arte, lectura recreativa y el uso de la lectura como medio de relajación y crecimiento personal.
* Estilo de vida: Independientes o profesionales con interés en el desarrollo personal y enriquecer su tiempo libre con actividades intelectuales. Utilizan servicios digitales para entretenimiento y consumo cultural.
* Actitudes: Valoran la comodidad, la personalización y el acceso inmediato a contenido de calidad. Son personas curiosas y abiertas a nuevas experiencias literarias.

# CAPÍTULO 2: REQUIREMENTS ELICITATION & ANALYSIS
## 2.1. Competidores
En el ámbito de la venta y distribución de libros, tanto físicos como digitales, existen varias empresas que ofrecen servicios similares a Livria. A continuación, se presentan los principales competidores directos reconocidos:
* Crisol: Es una de las cadenas de librerías más conocidas en el país, con una fuerte presencia física y catálogo variado que incluye libros académicos, de ficción, infantiles y más. Crisol combina su plataforma web con tiendas físicas, lo que le permite llegar a un amplio público. Su enfoque está en la accesibilidad, la variedad editorial y el respaldo de grandes editoriales.
* Ibero Librerías: Reconocida por su amplia oferta de títulos especializados en el ámbito académico, técnico y profesional. Ibero ofrece tanto venta en línea como presencial, y es valorada por su servicio al cliente y por contar con títulos difíciles de conseguir en otras plataformas. Su propuesta está dirigida principalmente a estudiantes, docentes y profesionales.
* Communitas: Es una librería independiente enfocada en la promoción de la cultura y la literatura contemporánea. Se caracteriza por una curaduría cuidadosa de sus títulos y por su ambiente cercano a los lectores. Además de su tienda física, cuenta con una plataforma en línea desde donde se pueden adquirir libros físicos y digitales. Su principal diferenciador es la experiencia personalizada y el enfoque en la comunidad lectora.

### 2.1.1 Análisis Competitivo

**¿Por qué realizar este análisis?**

Realizar este análisis es crucial porque nos proporciona una visión clara del entorno competitivo en el que está incursionando nuestra startup. Nos permite detectar oportunidades y amenazas, así como identificar áreas en las que podemos distinguirnos de nuestros competidores y destacar en el mercado. También nos ayuda a reconocer nuestras fortalezas y debilidades respecto a la competencia, lo que nos ayudará a orientar una toma de decisiones estratégicas más efectiva.

|               |   Nombre  |    Livria    |       Crisol      |     Ibero Librerías    |       Communitas      |
|---------------|-----------|--------------|-------------------|------------------------|-----------------------|
|               |           |  <p align="center">  <img src="https://imgur.com/vcToSq3.png" alt="ac1" width="500"></p>            |      <p align="center">  <img src="https://imgur.com/jnyW86A.png" alt="ac2" width="500"></p>             |    <p align="center">  <img src="https://imgur.com/2c99R4t.png" alt="ac3" width="500"></p>                    |      <p align="center">  <img src="https://imgur.com/TBZLZTw.png" alt="ac4" width="500"></p>                 |
|   Perfil  |   Overview  |   Livria es una librería especializada emergente cuyo enfoque principal es brindar accesibilidad a diversos materiales de lectura para sus clientes, facilitando la búsqueda de obras de entretenimiento o educativas que se ajusten a los gustos e intereses del cliente.  |   Crisol es una de las cadenas de librerías más grandes y conocidas de Perú, se destaca por su amplia oferta de obras artísticas y educativas, además de su compromiso con la cultura y calidad. Cuenta con locales en puntos estratégicos del país  |  Ibero Librerías es una cadena de librerías muy popularizada en Perú, resalta por su especialización en ejemplares educativos, culturales y de ciencias sociales, con una selección variada de editoriales y autores emergentes.  |   Communitas es una librería cuyo enfoque se centra en libros que tratan temas complejos, filosóficos y modernos. Se destaca por ofrecer a sus clientes una experiencia más profunda y centrada en el pensamiento crítico, mediante un repertorio que invita al lector a reflexionar.  |
|           |   Ventaja competitiva ¿Qué valor ofrece a los clientes?  |   Cuenta con un enfoque en torno al cliente que permite acceso a diversas herramientas de búsqueda y métodos rápidos de acceso a contenido de lectura que se ajuste a los intereses y gustos de cada persona.  |   Posee un amplio inventario de obras de todos los géneros y cuenta con locales ubicados en puntos estratégicos del Perú, lo que amplía tanto el catálogo de productos a ofrecer como su accesibilidad.  |  Ofrece a sus clientes un amplio repertorio de obras educativas y culturales menos comerciales y más exigentes, proyectan una imagen de marca más especializada comparación de otras cadenas.  |   Presenta a sus clientes una curaduría enfocada en títulos que invitan al lector a la reflexión y el aprendizaje, apostando por una cuidadosa selección de títulos, optando por garantizar la calidad por encima de la rotación comercial.  |
|   Plan de marketing  |   Mercado objetivo  |   Jóvenes y adultos jóvenes que busquen empezar el hábito de la lectura o requieran acceso a obras escritas, lectores jóvenes y casuales.  |   Personas de todas las edades interesadas por las novelas y obras escritas de entretenimiento o educación. lectores casuales y escolares.  |  Jóvenes y adultos de todas las edades interesados en obras educativas o culturales, lectores frecuentes y profesionales.  |   Jóvenes y adultos jóvenes interesados en obras ideológicas y literatura alternativa, lectores jóvenes y críticos.  |
|           |   Estrategias de marketing  |   Descuentos semanales, publicidad digital, marketing de temporada  |   Descuentos frecuentes, marketing de temporada, publicidad digital, fuerte presencia en tiendas físicas  |  Publicidad digital, presencia en el medio cuidada y refinada, eventos y presentaciones  |   Eventos culturales, fuerte presencia en la comunidad lectora, colaboraciones con artistas y autores  |
|   Plan de producto  |   Productos y servicios  |  Libros digitales y físicos  |   Libros digitales y físicos, merchandising  |   Libros físicos  |   Libros físicos  |
|           |   Precios y costos  |   Descuentos semanales y de temporada, variedad de precios según el tipo de obra. Promedio: S/. 30 - 150 Suscripción: S/. 39.90  |   Descuentos frecuentes y de temporada, gran variedad de precios según el tipo de obra. Promedio: S/. 40 - 200 No cuenta con servicio de suscripción   |  Descuentos regulares y de temporada, poca diferencia de precios según el tipo de obra. Promedio: S/. 40 - 130 No cuenta con servicio de suscripción  |   Descuentos regulares, precios similares entre sí según el tipo de obra. Promedio: S/. 50 - 140 No cuenta con servicio de suscripción  |
|           |   Canales de distribución  |   Entrega a domicilio, compra en local, venta de productos digitales.  |   Entrega a domicilio, compra en local. |  Entrega a domicilio, compra en local.  |   Entrega a domicilio, compra en local.  |
|   Análisis FODA o SWOT  |   Fortalezas  |   Amplia cobertura a través de envíos a domicilio. Gran variedad de obras, tanto literarias como educativas. Imagen moderna y amigable para nuevos y antiguos lectores. Orientación en torno al cliente, buscando satisfacer sus necesidades y mejorar su experiencia.  |   Amplia cobertura local, tanto en tiendas físicas como en envíos a domicilios. Gran variedad de obras literarias y establecimiento en el mercado. Popularidad y relevante imagen de marca. Veinte años de experiencia en el mercado.  |   Curaduría especializada en títulos educativos y culturales de calidad. Imagen de marca especializada, profesional y más cercana con los lectores. Fidelización del público objetivo. Treinta años de experiencia en el mercado.  |   Curaduría selectiva y refinada, centrada en ideas y movimientos de alto peso en la sociedad. Fuerte imagen de marca y peso en el medio. Comunidad amplia y fuertemente establecida. Diez años de experiencia en el mercado.  |
|           |   Oportunidades  |   Posibilidad de captar un nuevo segmento del público (lectores iniciantes) con nuestra propuesta y diseño orientados al usuario. Posibilidad de fidelizar lectores con las características únicas de nuestro servicio y las funciones exclusivas de nuestra aplicación.  |   Posibilidad de expansión internacional en un futuro próximo, debido a su fuerte posicionamiento en el mercado nacional e imagen de marca. Posibilidad de establecer convenios estratégicos de exclusividad con editoriales emergentes.  |  Posibilidad de establecimiento de alianzas estratégicas con centros educativos superiores, debido a su fuerte enfoque en los temas educativos y culturales. Posibilidad de expandirse al entorno digital, ofreciendo material de lectura en este formato.  |   Posibilidad de expansión de la marca con ramas relacionadas, como organizadora de eventos o agencia artística, debido a su experiencia en estos rubros. Posibilidad de expandirse al entorno digital, ofreciendo material de lectura en este formato.  |
|           |   Debilidades  |   Escala pequeña para una incursión en el mercado: La principal debilidad de Livria es su pequeña escala respecto al resto de sus competidores, al no tener una imagen de marca establecida en la percepción del público, nuestro alcance se ve disminuído y la dificultad de una incursión en el mercado de las librerías será un reto difícil de afrontar.  |   Enfoque demasiado centrado en la variedad: La principal fortaleza de Crisol también puede ser considerada una debilidad, pues tener un catálogo tan amplio y diverso podría llegar a significar que algunos títulos más específicos de cada género no se encuentren disponibles, debido a su poca viabilidad comercial, llegando a ser un problema para lectores en busca de títulos poco conocidos.  |  Falta de venta de productos digitales: Ibero Librerías se diferencia por su especialización en material educativo y cultural, pero no ha incursionado al rubro de los libros digitales y productos relacionados a este medio, lo que puede representar una debilidad bastante prominente, debido a la existencia de alternativas más cómodas a los clásicos libros físicos, como los e-books o audiolibros.  |   Nicho específico y poco escalable: Communitas se destaca por su nicho como librería divulgadora de ideas profundas y discursos alternativos, pero esta característica es también una debilidad en el sentido comercial, ya que depende de un público pequeño y especializado, lo cual dificulta su crecimiento como marca, ya que no acata a la mayoría del público.  |
|           |   Amenazas |   Commit Id  |   La principal amenaza para Crisol es la aparición de un competidor más grande y con mayor alcance que cuente con una oferta similar y llegue a reemplazarlos, ya sea por tener precios más accesibles o mayor variedad de obras en su repertorio. |   Una de las amenazas más destacables para Ibero Librerías es la aparición de competidores con un rubro similar que ofrezcan más alternativas y un acceso más rápido a los libros solicitados por sus clientes, ya sea mediante una mayor cantidad de locales o la venta de libros digitales  |   Una amenaza considerable para Communitas es el acaparamiento de su nicho por una marca más grande y con mayor presupuesto, mediante la apropiación de su estilo y modelo de negocio, apelando a un mayor volumen de público y eventualmente ocupando su rubro en el mercado.  |


### 2.1.2. Estrategias y tácticas frente a los competidores
**Estrategias de diferenciación de producto**

*1. Implementación de funcionalidad de comunidad:*
* Fortaleza utilizada: Orientación en torno al cliente
* Oportunidad aprovechada: Posibilidad de fidelizar lectores
* Descripción: El apartado de comunidad nos permitirá captar y mantener la atención de grupos de lectores con intereses en común, ya que les ofrecerá un espacio en el que puedan compartir sus opiniones y gustos de una manera amigable. Esta funcionalidad también aportará más valor a la suscripción de cada usuario, ofreciendo acceso a aspectos exclusivos que pueden llamar la atención del cliente.

*2. Implementación de funcionalidad de recomendaciones:*
* Fortaleza utilizada: Orientación en torno al cliente
* Oportunidad aprovechada: Posibilidad de captar al segmento de lectores iniciantes.
* Descripción: La innovadora función de recomendaciones personalizadas nos permitirá acatar las necesidades de este tipo de clientes de una manera más efectiva, ya que toda persona que quiera empezar a formar el hábito de la lectura podrá utilizar este apartado de nuestro servicio para encontrar obras que estén alineadas con sus intereses y necesidades de una manera mucho más rápida, permitiéndoles adquirir un título de su interés dentro de nuestra misma aplicación.

**Estrategias de expansión de mercado**

*1. Expansión a mercados regionales:*
* Fortaleza utilizada: Amplia cobertura de servicio
* Oportunidad aprovechada: Posibilidad de fidelizar lectores
* Descripción: La creación de nuevas sedes en diferentes puntos estratégicos de la región nos permitirá aumentar el alcance de nuestra startup y nos brindará acceso a un público mucho más amplio cuando nuestra marca esté establecida y empecemos a generar suficientes ingresos para reinvertir en el proyecto.

*2. Alianzas con editoriales nacionales:*
* Fortaleza utilizada: Gran variedad de obras
* Oportunidad aprovechada: Posibilidad de fidelizar lectores
* Descripción: Establecer alianzas estratégicas con editoriales emergentes resultaría en una gran expansión al catálogo de obras que ofrecemos y la posibilidad de comercializar obras a precios mucho más competitivos, aumentando los beneficios de nuestros clientes y suscriptores.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
Es necesario ajustar las preguntas de las entrevistas a cada segmento para obtener la información más adecuada sobre las necesidades respectivas de los clientes de Livria. Cada entrevista inicia con preguntas generales como “¿Cuál es tu nombre?”, “¿Cuántos años tienes?”, etc.

**Segmento Objetivo #1: Estudiantes y jóvenes universitarios**
* ¿Con qué frecuencia lees material académico o de entretenimiento en formato digital?
* ¿Qué plataformas o aplicaciones usas actualmente para estudiar o leer?
* ¿Qué dificultades encuentras al buscar o acceder al material que necesitas para tus estudios?
* ¿Qué te gustaría que una aplicación de lectura te ofreciera para facilitar tu aprendizaje?
* ¿Te gustaría recibir recomendaciones de libros o materiales útiles? ¿Por qué?
* ¿Qué te motivaría a usar regularmente una plataforma de lectura digital?

**Segmento objetivo #2: Lectores casuales y aficionados a la lectura**
* ¿Con qué frecuencia lees libros por placer?
* ¿Qué tipo de libros te interesa leer?
* ¿Dónde sueles descubrir nuevos libros para leer? 
* ¿Usas alguna aplicación o plataforma digital para leer?Si no lo haces, ¿Por qué?
* ¿Qué aspectos valoras más en una app de lectura?
* ¿Te gustaría recibir recomendaciones basadas en tus intereses y hábitos de lectura?
* ¿Qué cosas te han decepcionado o frustrado al usar plataformas de lectura en el pasado?

### 2.2.2. Registro de entrevistas
**Segmento Objetivo #1: Estudiantes y jóvenes universitarios**
*Entrevistado N.º 1: Valentina Binda*
* Edad: 17
* Distrito: Surquillo

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/uHmEMXt.png" alt="e11" width="500">
</p>

* Link: [Segmento 1-1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/Ecaazhz5sYVCtHUhWWWMxO0BQp5C1mXAOTlS5YjoF9h7Pg?e=YE3T03)
* Instante en el que inicia: 0:12 min
* Duración: 1:47 min

Valentina Binda, una estudiante de 17 años, menciona que lee material académico en formato digital con frecuencia, ya que constantemente necesita estudiar y buscar información relevante. Utiliza principalmente la plataforma proporcionada por su universidad, la cual considera útil, aunque en ocasiones no le brinda toda la información que requiere. Le gustaría que una aplicación de lectura le ofreciera búsquedas más precisas y específicas, lo que facilitaría su proceso de estudio. También está interesada en recibir recomendaciones personalizadas de libros o materiales, ya que considera que acceder a información digital resulta más práctico que hacerlo de manera presencial. Valentina afirma que una plataforma de lectura digital la motivaría a informarse más y encontrar contenidos útiles con mayor facilidad.

*Entrevistado N.º 2: Emmanuel Andrades*
* Edad: 16
* Distrito: Miraflores

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/kjHyjUp.png" alt="e12" width="500">
</p>

* Link: [Segmento 1-2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/EYwCO9t9dp1KjqlpDZZISMkBCz_43zJ7q2o3VDdQYBpMBg?e=Fkd1qQ)
* Instante en el que inicia: 0:14 min
* Duración: 1:31 min

Emmanuel Andrades, un estudiante de 16 años, afirma que lee con frecuencia material académico en formato digital, ya que constantemente necesita informarse sobre diversos temas. Suele utilizar las plataformas que encuentra disponibles en la web, aunque señala que muchas veces no logra encontrar suficiente contenido para cumplir con sus tareas o trabajos escolares. Le gustaría que una aplicación de lectura le permitiera localizar con precisión el punto específico de información que necesita, lo que facilitaría su aprendizaje. Está a favor de recibir recomendaciones personalizadas de libros o materiales, ya que considera que le servirían de gran apoyo cuando necesita informarse sobre un tema en particular. Emmanuel concluye que, si los títulos de una plataforma le resultan interesantes, la utilizaría de manera regular.

*Entrevistado N.º 3: Sofia Pimentel*
* Edad: 14
* Distrito: Magdalena del Mar

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/BHYT8y3.png" alt="e13" width="500">
</p>

* Link: [Segmento 1-3](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/EeNmLb7eIZdBhme_kB-IvboBBaqHtLvRlKNq2Jq8krm0bA?e=ponlNs)
* Instante en el que inicia: 0:13 min
* Duración: 2:02 min

Sofía Pimentel, una estudiante de 14 años, menciona que lee frecuentemente material académico en formato digital porque considera que es necesario para alcanzar un mejor rendimiento escolar. Para investigar usa Google Académico y, cuando se trata de lectura recreativa, prefiere Crisol. Una de las principales dificultades que encuentra al buscar información es que Wikipedia aparece como primera opción en los resultados, lo cual considera poco útil para profundizar en los temas que le interesan. Le gustaría que una aplicación de lectura le brindara acceso a libros clave que enriquezcan su conocimiento académico. Aunque las recomendaciones de libros le parecen útiles, valora aún más las sugerencias de materiales educativos, ya que tienen un impacto directo en su aprendizaje. Finalmente, asegura que la motivaría a usar una plataforma digital si esta ofrece contenido relacionado con sus intereses y necesidades escolares.

*Entrevistado N.º 4: Wendy García*
* Edad: 25
* Distrito: Lince

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/I2oWJv0.png" alt="e14" width="500">
</p>

* Link: [Segmento 1-4.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/EfhBfftBqPBHvC78K1v4cp4BdX6No7mf_awt63P055rhiQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=vvA8Aj)
* Instante en el que inicia: 0:08 min
* Duración: 4:35 min

En la entrevista con Wendy García, se pudo destacar que ella habitualmente trata de ponerse metas de cantidad de páginas para leer cada día y así poder aumentar la cantidad de libros que lee por año. Nos indica que por temas académicos lee todos los días usando la biblioteca digital de su universidad como librería. Sin embargo, usa como segunda opción Google libros para encontrar libros que no tiene acceso en su universidad. Precisa que lo que le molesta al buscar el libro que desea, es que no aparezca en la primera opción aquel libro que anhela y tarda en encontrarlo. También, indica que considera un obstáculo que aparezca la información de algunos libros incompleta. Wendy recalca que le gustaría que existan distintos formatos de libros (digital y audiolibro) en una aplicación de lectura. Considera que el audiolibro es importante para no dejar de leer cuando esté haciendo otras actividades que le impida concentrarse visualmente y le motivaría esta opción ya que le permite continuar leyendo incluso si se llega a cansar visualmente. También, nos señala que le gustaría recibir recomendaciones de lecturas de su interés para poder aumentar su meta de libros leídos al año.

**Segmento objetivo #2: Lectores casuales y aficionados a la lectura**

*Entrevistado N.º 1: Roxana Arbañil*
* Edad: 50
* Distrito: Surquillo

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/y3QM8F4.png" alt="e21" width="500">
</p>

* Link: [Segmento 2-1](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/EVLoAw8UNb9IlErrqUo7A9YBh3KOP5BmXviuTeX3BL8qCA?e=VEQvsq)
* Instante en el que inicia: 0:10 min
* Duración: 2:45 min

La entrevistada, Roxana Arbañil, es una profesional de 50 años que trabaja en el área de gestión humana y se interesa especialmente por temas de psicología y comportamiento humano aplicados al entorno laboral. Aunque le gusta leer, lo hace de manera ocasional debido a la falta de tiempo, aproximadamente una vez cada dos meses. Prefiere los libros en formato físico y menciona que no utiliza plataformas digitales de lectura porque no ha tenido el acceso ni la orientación necesaria para hacerlo. Valora que una aplicación de lectura ofrezca variedad y filtros precisos que le permitan encontrar exactamente lo que desea leer, y estaría muy interesada en recibir recomendaciones personalizadas basadas en sus hábitos e intereses. En su experiencia pasada con plataformas digitales, se sintió frustrada por interfaces poco amigables y funciones limitadas que dificultan una lectura fluida.

*Entrevistado N.º 2: Jorge Binda*
* Edad: 48
* Distrito: Cercado de Lima

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/fNsSHeH.png" alt="e22" width="500">
</p>

* Link: [Segmento 2-2](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/EVtPmC4yz2BCh2g9Hh6N4tcBc3mvE5XIzzsoeMorDVmWQQ?e=xaj1aB)
* Instante en el que inicia: 0:12 min
* Duración: 1:56 min

Jorge Binda, ingeniero de sistemas de 48 años, menciona que lee por placer aproximadamente una vez al mes, aunque prefiere los audiolibros por su practicidad. Sus intereses abarcan la ciencia ficción, la acción y diversos géneros. Descubre nuevos títulos principalmente a través de audiolibros, utilizando Spotify como su plataforma principal, ya que le permite ahorrar tiempo y acceder al contenido de forma más eficiente. Valora especialmente la variedad de libros disponibles, y tiene una clara preferencia por aquellos narrados o escritos en español latino, ya que no se siente cómodo con el acento español peninsular. Además, considera muy útil recibir recomendaciones basadas en sus intereses, ya que esto le facilita significativamente la búsqueda de contenido que realmente le atraiga.

*Entrevistado N.º 3: Fiorella León*
* Edad: 24
* Distrito: Magdalena del Mar

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/16tns9x.png" alt="e23" width="500">
</p>

* Link: [Segmento 2-3.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/EZwCP4erymtFksBohx9zhmMBZR4wqr4Un-MfWb4EypzR-g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=9R43Jn)
* Instante en el que inicia: 0:07 min
* Duración: 3:56 min

En la entrevista con Fiorella podemos destacar que ella es aficionada a la lectura y lee regularmente. Además, ella busca leer un libro cada mes por placer. El género que le interesa más es el suspenso que contenga drama, pero también opta por leer libros de comedia combinado con romance. Adicionalmente, ella prefiere leer libros en plataformas digitales que físicas mediante las plataformas web de Wattpad y AO3. 

Suele consumir contenido de lectura gratuita y valora más el aspecto visual (el color de fondo o tipo de letras) e interactivo que contiene las lecturas (ej. Wattpad permite agregar música o una imagen de portada por capítulo). También, Fiorella señala que suele leer recomendaciones, puede ser en en distintas redes sociales o en las plataformas de lecturas anteriormente indicadas. Le resulta molesto la lentitud de carga de la lectura y el diseño anticuado de las plataformas de lectura digitales, recalca que se asemeja algunos a un libro físico y no le llama la atención.

*Entrevistado N.º 4: Nicole Azaña*
* Edad: 23
* Distrito: Ate

**Acerca de la entrevista:**

<p align="center">
  <img src="https://imgur.com/NiHPxY3.png" alt="e24" width="500">
</p>

* Link: [Segmento 2-4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311157_upc_edu_pe/EWGr6mTCco9BmLKqMirZAJMBFsqNlHWtNT0K0NPWQhYezg?e=YrfKQV)
* Instante en el que inicia: 0:14 min
* Duración: 3:24min

Nicole, una lectora casual, procura leer un libro cada dos semanas y se interesa principalmente por historias de romanticismo, comedia y libros informativos. Descubre nuevas lecturas a través de TikTok y otras fuentes en internet, y utiliza plataformas como Wattpad y Apple Books. Valora una buena ortografía, tamaño de letra legible, funciones como subrayado o toma de apuntes, y una experiencia libre de anuncios intrusivos. Está abierta a recibir recomendaciones basadas en sus intereses y hábitos de lectura, aunque ha tenido frustraciones con funciones que no guardan correctamente sus favoritos y con la presencia excesiva de publicidad en algunas plataformas.

### 2.2.3. Análisis de entrevistas
En base en las entrevistas recopiladas para cada segmento, se llevó a cabo un análisis, el cual destaca los principales hallazgos y las conclusiones derivadas.

**Segmento #1: Estudiantes y jóvenes universitarios**

*Hallazgos:*
* Los estudiantes utilizan constantemente plataformas digitales para acceder a material de estudio, lo que demuestra una fuerte necesidad de contar con herramientas prácticas y accesibles en su día a día académico.
* Muchos expresan frustración al no hallar la información exacta que necesitan o al encontrar resultados incompletos, lo que indica una oportunidad para mejorar los sistemas de búsqueda y organización del contenido.
* Los entrevistados valoran que una plataforma les sugiera libros o materiales adaptados a sus intereses y necesidades académicas, ya que esto agiliza su proceso de búsqueda y mejora su rendimiento.
* Algunos estudiantes muestran interés por opciones como audiolibros, que les permitirían seguir aprendiendo incluso en momentos donde no pueden leer, lo que resalta la importancia de ofrecer formatos alternativos.

*Conclusiones:*
* Los estudiantes y jóvenes universitarios muestran una alta predisposición al uso de plataformas digitales para la lectura académica, pero también revelan importantes carencias en las herramientas que actualmente utilizan.
* La falta de precisión en los motores de búsqueda, el acceso limitado a contenido completo y la ausencia de recomendaciones específicas generan frustración y pérdida de tiempo. Una aplicación que permita buscar con mayor exactitud, ofrezca contenido completo en distintos formatos y brinde recomendaciones personalizadas sería altamente valorada por este segmento. Además, la motivación de los estudiantes se ve reforzada por metas personales y el deseo de un acceso práctico al conocimiento. Livria tiene la oportunidad de posicionarse como una plataforma educativa de confianza si atiende a estas necesidades específicas.

Segmento objetivo #2: Lectores casuales y aficionados a la lectura

*Hallazgos:*
* Mientras algunos lectores aún prefieren el formato físico por costumbre o falta de familiaridad con lo digital, otros valoran mucho la practicidad de los audiolibros o la accesibilidad de plataformas digitales, especialmente si permiten una experiencia cómoda e inmersiva.
* Los entrevistados coinciden en que recibir recomendaciones personalizadas según sus intereses facilita y mejora su experiencia lectora, ya que les ayuda a descubrir contenido relevante sin perder tiempo.
* Las interfaces poco amigables, lentas o con diseño anticuado generan frustración y desmotivan el uso frecuente. En cambio, se valora mucho una experiencia visual atractiva, interactiva y fluida.
Algunos lectores no usan plataformas digitales simplemente por desconocimiento o falta de orientación. Esto indica que una plataforma con guía clara, onboarding accesible y diseño intuitivo podría atraer a nuevos usuarios de este segmento.

*Conclusiones:*
* Los lectores casuales y aficionados a la lectura muestran una variedad de preferencias en cuanto a formatos y temáticas, combinando el gusto por libros físicos, digitales y audiolibros según su estilo de vida. Aunque algunos disfrutan de la lectura por placer con regularidad, otros la realizan de forma esporádica debido a limitaciones de tiempo. 
* Las plataformas digitales son valoradas cuando ofrecen filtros detallados, recomendaciones personalizadas y una interfaz visualmente atractiva e intuitiva, pero pueden generar frustración cuando presentan un diseño anticuado, lentitud de carga o una experiencia de uso poco clara. Además, se evidencia que una parte del segmento, especialmente los adultos, no se involucra con plataformas digitales por falta de orientación o acceso adecuado. Por ello, una aplicación de lectura que combine personalización, múltiples formatos y acompañamiento tecnológico podría atender de forma efectiva las necesidades de este grupo, generando una experiencia más cómoda, eficiente y motivadora.

## 2.3. Needfinding
### 2.3.1. User Personas
**Segmento #1: Estudiantes y jóvenes universitarios**

<p align="center">
  <img src="https://imgur.com/xp59rDv.png" alt="up1" width="500">
</p>

Link: https://drive.google.com/drive/folders/1zJEVEmTVXp3wqfTOmNEAVbZhEzfipoDu?usp=sharing

**Segmento objetivo #2: Lectores casuales y aficionados a la lectura**

<p align="center">
  <img src="https://imgur.com/48W4F6z.png" alt="up2" width="500">
</p>

Link: https://drive.google.com/drive/folders/1zJEVEmTVXp3wqfTOmNEAVbZhEzfipoDu?usp=sharing

### 2.3.2. User Task Matrix

|   User Task Matrix  |   Yoel Ramírez  |              |   Lucia Carnero  |              |
|---------------------|-----------------|--------------|------------------|--------------|
|                     |   Frecuencia  |   Importancia   |   Frecuencia  |  Importancia   |
|   Buscar libros para estudio o interés personal  |   Con frecuencia  |   Alta  |  Con frecuencia  |   Alta  |
|   Usar el algoritmo de recomendación  |   Con frecuencia  |   Alta  |   A veces  |  Media  |
|   Unirse a comunidades con intereses similares  |   Con frecuencia  |   Alta  |   A veces  |  Media  |
|   Leer libros en formato digital  |   Con frecuencia  |   Alta  |   Con frecuencia  |  Alta  |
|   Guardar libros o marcar como “pendientes”  |   A veces  |   Media  |   A veces  |   Media  |
|   Compartir publicaciones en las comunidades  |   Rara vez  |   Baja  |   A veces  |  Media  |
|   Comentar las publicaciones  |   Rara vez  |   Baja  |   A veces  |  Media  |
|   Pedir libros con envío rápido  |   A veces  |   Media  |   A veces  |   Alta  |

### 2.3.3. User Journey Mapping
En esta sección se presenta el recorrido completo que experimenta cada uno de nuestros User Personas al interactuar con la plataforma, desde el primer contacto hasta la fidelización. A través de los User Journey Maps, se ilustran las etapas clave del proceso, incluyendo los puntos de contacto, emociones, expectativas y posibles fricciones a lo largo del camino. Este análisis nos permite comprender en profundidad las necesidades, motivaciones y desafíos de los usuarios, con el fin de optimizar su experiencia, mejorar la interfaz del producto y ofrecer soluciones más alineadas con sus objetivos y comportamientos.

**Segmento #1: Estudiantes y jóvenes universitarios**

*User Journey Map del Segmento 1*

<p align="center">
  <img src="https://imgur.com/qJqiiOl.png" alt="uj1" width="500">
</p>

**Segmento #2: Lectores casuales y aficionados a la lectura**

*User Journey Map del Segmento 2*

<p align="center">
  <img src="https://imgur.com/4J7ZzeK.png" alt="uj2" width="500">
</p>

Para mejor visualización de los User Journey Maps de Livria, acceder al siguiente link:
https://drive.google.com/drive/folders/1zJEVEmTVXp3wqfTOmNEAVbZhEzfipoDu?usp=drive_link 

### 2.3.4. Empathy Mapping
Para la elaboración de los Empathy Maps, el equipo siguió una metodología centrada en el usuario, basada en la recopilación de datos cualitativos obtenidos a través de entrevistas, encuestas, observación directa y análisis de comportamiento digital. Cada mapa fue diseñado teniendo en cuenta un User Persona específico, con el objetivo de capturar lo que el usuario piensa, siente, dice y hace en relación con la plataforma. Posteriormente, se identificaron los principales miedos, frustraciones, necesidades y motivaciones que influyen en su experiencia. Esta herramienta permitió generar una visión empática que guía la toma de decisiones de diseño y desarrollo, asegurando que cada funcionalidad responda realmente a las expectativas y preocupaciones del usuario.

**Segmento #1: Estudiantes y jóvenes universitarios**

*Empathy Map del Segmento 1*

<p align="center">
  <img src="https://imgur.com/1nY0bCw.png" alt="em1" width="500">
</p>

**Segmento #2: Lectores casuales y aficionados a la lectura**

*Empathy Map del Segmento 2*

<p align="center">
  <img src="https://imgur.com/9LLW5Dc.png" alt="em2" width="500">
</p>

Para mejor visualización de los Empathy Maps de Livria, acceder al siguiente link:
https://drive.google.com/drive/folders/1zJEVEmTVXp3wqfTOmNEAVbZhEzfipoDu?usp=drive_link

### 2.3.5. As-Is Scenario Mapping
En esta sección se presentan los As-Is Scenario Mapping, desarrollados para cada uno de los User Personas, con el fin de entender cómo interactúan actualmente con la plataforma o con soluciones similares. El objetivo es identificar puntos críticos, fricciones y oportunidades de mejora en la experiencia del usuario. 

Cada mapa incluye las filas correspondientes a Steps, Doing, Thinking y Feeling, permitiendo una visión estructurada de las acciones, pensamientos y emociones del usuario en cada etapa de su recorrido. Este análisis proporciona una base sólida para futuras iteraciones centradas en el usuario, asegurando que las decisiones de diseño y desarrollo respondan a sus necesidades reales.

<p align="center">
  <img src="https://imgur.com/wJdKztI.png" alt="asis1" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/cvvTEov.png" alt="asis2" width="500">
</p>

Para mejor visualización de los As-Is Scenarios de Livria, acceder al siguiente link: https://miro.com/app/board/uXjVI-wDlQU=/

## 2.4. Ubiquitous Language

| Término (Inglés)        | Definición |
|-------------------------|------------|
| **Casual reader**       | Persona que lee ocasionalmente por interés o entretenimiento, sin un hábito fijo de lectura. |
| **Amateur reader**      | Persona con un hábito de lectura más constante, que busca libros según sus intereses y disfruta compartir su experiencia lectora. |
| **Young university student** | Usuario que cursa estudios superiores y busca libros relacionados con sus trabajos o proyectos académicos o materias específicas. |
| **Recommendations**     | Sugerencias personalizadas de libros según el perfil, intereses, historial de lectura o área académica que busca el usuario. |
| **Reader community**    | Sección donde los usuarios interactúan, comparten opiniones, participan en retos y descubren libros en común. |
| **Search for books**    | Herramienta que permite encontrar libros mediante filtros avanzados como autor, editorial, género, formato y disponibilidad. |
| **Book formats**        | Tipos de presentación de un libro: digital (eBook), audiolibro o físico. |
| **Save books**          | Función que permite marcar libros para revisarlos después o recibir notificaciones sobre su disponibilidad. |
| **Join challenges**     | Participación en pequeñas dinámicas de lectura con metas y temas específicos, que fomentan la constancia y el disfrute de la lectura. |
| **Reviews**             | Comentarios, calificaciones y valoraciones que los usuarios de la comunidad dejan sobre libros que han leído, para guiar o recomendar a otros lectores. |
| **Audiobook**           | Un libro narrado en formato de audio, que permite a los usuarios escuchar el contenido en vez de leerlo. |
| **Digital books**       | Versión electrónica o digital de un libro que puede leerse desde múltiples dispositivos. |
| **Physical books**      | Libro impreso en papel, disponible para compra en formato tradicional. |
