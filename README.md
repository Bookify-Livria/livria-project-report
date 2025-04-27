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

- [CAPÍTULO 3: REQUIREMENTS SPECIFICATION](#capítulo-3-requirements-specification)
  * [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  * [3.2. User Stories](#32-user-stories)
  * [3.3. Impact Mapping](#33-impact-mapping)
  * [3.4. Product Backlog](#34-product-backlog)

- [CAPÍTULO 4: PRODUCT UX/UI DESIGN](#capítulo-4-product-uxui-design)
  * [4.1. Style Guidelines](#41-style-guidelines)
    + [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    + [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
  * [4.2. Information Architecture](#42-information-architecture)
    + [4.2.1. Organization Systems](#421-organization-systems)
    + [4.2.2. Labeling Systems](#422-labeling-systems)
    + [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    + [4.2.4 Searching Systems](#424-searching-systems)
    + [4.2.5. Navigation Systems](#425-navigation-systems)
  * [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    + [4.3.1. Landing Page Wireframes](#431-landing-page-wireframes)
    + [4.3.2. Landing Page Mock-Ups](#432-landing-page-mock-ups)
  * [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    + [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    + [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    + [4.4.3. Web Applications Mock-up](#443-web-applications-mock-up)
    + [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  * [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  * [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    + [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    + [4.6.2. Software Architecture Container Diagram](#462-software-architecture-container-diagram)
    + [4.6.3. Software Architecture Components Diagram](#463-software-architecture-components-diagram)
  * [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    + [4.7.1. Class Diagram](#471-class-diagram)
    + [4.7.2. Class Dictionary](#472-class-dictionary)
  * [4.8. Database Design](#48-database-design)
    + [4.8.1. Database Diagram](#481-database-diagram)

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

# CAPÍTULO 3: REQUIREMENTS SPECIFICATION
En esta sección se consolidan los requisitos del producto digital a partir del análisis detallado de la información obtenida durante las fases de investigación y mapeo de experiencia del usuario. El objetivo es traducir los hallazgos en especificaciones claras, priorizadas y alineadas con las necesidades reales de los usuarios y los objetivos del negocio. A través del To-Be Scenario Mapping, las User Stories, el Impact Map y el Product Backlog, se estructura una visión integral del producto que guía al equipo de desarrollo en la creación de soluciones funcionales, centradas en el usuario y técnicamente viables. Esta especificación sirve como base para la planificación, diseño e implementación del producto.

## 3.1. To-Be Scenario Mapping
En esta sección se presentan los To-Be Scenario Maps elaborados para cada uno de los User Personas, con el propósito de visualizar cómo debería ser la experiencia ideal del usuario una vez implementadas las mejoras propuestas. Estos mapas proyectan un recorrido optimizado, centrado en las necesidades, motivaciones y expectativas detectadas en fases anteriores del proceso de investigación. Al igual que en los escenarios actuales, cada mapa incluye las filas de Steps, Doing, Thinking y Feeling, permitiendo identificar de forma clara cómo cambiarán las percepciones, emociones y acciones del usuario en el futuro. Este ejercicio facilita la alineación del equipo en torno a una visión compartida y orienta el diseño de soluciones más empáticas y efectivas.

<p align="center">
  <img src="https://imgur.com/HoebMyL.png" alt="tobe1" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/AzMSw4g.png" alt="tobe2" width="500">
</p>

Para mejor visualización de los to-Be Scenarios de Livria, acceder al siguiente link: https://miro.com/app/board/uXjVI-wDlQU=/

## 3.2. User Stories
### 3.2.1. Requisitos
**Requisitos Funcionales**

| Código  | Requisito |
|---------|---------------|
| **Recomendaciones personalizadas** | |
| RFU-07 | Generación de recomendaciones según preferencias literarias |
| RFU-08 | Sección de recomendados |
| RFU-09 | Sistema de notificaciones para alertar sobre nuevas recomendaciones |
| RFU-10 | Interacción con recomendaciones |
| RFU-11 | Actualización dinámica de recomendaciones |
| **Búsqueda** | |
| RFU-12 | Barra de búsqueda principal |
| RFU-13 | Búsqueda por título, autor, género, editorial o palabra clave |
| RFU-14 | Filtrado y ordenamiento de resultados |
| RFU-15 | Resultados relevantes por coincidencia |
| RFU-16 | Historial de búsqueda del usuario |
| RFU-17 | Compatibilidad con errores tipográficos |
| **Comunidades** | |
| RFU-18 | Creación de comunidades |
| RFU-19 | Creación de publicaciones en comunidades |
| RFU-20 | Sugerencias de comunidades |
| RFU-21 | Unirse a comunidades |
| **Notificaciones** | |
| RFU-22 | Notificaciones instantáneas |
| RFU-23 | Configuración de notificaciones |
| **Suscripciones** | |
| RFU-24 | Suscripción inicial en el Plan Free |
| RFU-25 | Visualización de beneficios por tipo de suscripción |
| RFU-26 | Actualización al Plan Community |
| RFU-27 | Gestión de estado de suscripción |
| RFU-28 | Envío de recordatorios y confirmaciones de pago del Plan Community |
| RFU-29 | Reversión al Plan Free |
| **Perfil y preferencias de usuario** | |
| RFU-30 | Crear perfil |
| RFU-31 | Ajustes de privacidad |
| RFU-32 | Integración de aplicaciones de terceros |

**Requisitos No Funcionales**

| Código  | Requisito |
|---------|---------------|
| RNFU-01 | Soporte de crecimiento de usuarios |
| RNFU-02 | Tiempo de respuesta rápido |
| RNFU-03 | Disponibilidad 24/7 |
| RNFU-04 | Seguridad del usuario  |
| RNFU-05 | Interfaz amigable |
| RNFU-06 | Soporte multiplataforma |
| RNFU-07 | Internacionalización de idiomas (inglés-español) |

### 3.2.2. Historias de Usuario

| **User Story ID** | US01 |
|-------------------|------|
| **Epic ID**        | EP01 |
| **Title**          | Presentación de servicios de Livria |
| **Description**    | Como visitante, quiero ver información relevante sobre las funcionalidades principales que ofrece Livria, para conocer las característica únicas de la aplicación. |
| **Acceptance Criteria #1** | Dado que el visitante se encuentra en el inicio de la landing page<br>Y el visitante quiere ver las funcionalidad de Livria,<br>Cuando el visitante hace clic en “Ver Más +”<br>Entonces la página se desplaza hasta la sección “Servicios”. |
| **Acceptance Criteria #2** | Dado que el visitante se encuentra en cualquier otra sección de la landing page<br>Y el visitante quiere ir a la sección “Servicios”,<br>Cuando el visitante hace clic en el link “Servicios” del encabezado<br>Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria #3** | Dado que el visitante se encuentra en la landing page,<br>Cuando el visitante empieza a hacer scroll desde el inicio<br>Entonces la página le muestra la siguiente sección, es decir, la de “Servicios”. |

| **User Story ID** | US02 |
|-------------------|------|
| **Epic ID**        | EP01 |
| **Title**          | Acceso a la sección “Sobre Nosotros” desde la landing page |
| **Description**    | Como visitante, quiero acceder fácilmente a la sección “Sobre Nosotros”, para conocer la trayectoria de los creadores de Livria, comprender en qué consiste la plataforma y descubrir las funcionalidades que ofrece. |
| **Acceptance Criteria #1** | Dado que el visitante se encuentra en cualquier sección de la landing page<br>Y el visitante quiere ver información sobre los creadores de Livria,<br>Cuando el visitante hace clic en el link “Sobre Nosotros” del encabezado<br>Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria #2** | Dado que el visitante se encuentra en la landing page,<br>Cuando el visitante empieza a hacer scroll desde el inicio<br>Entonces la página le muestra las siguientes secciones hasta llegar a la de “Sobre Nosotros”. |

| **User Story ID** | US03 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Cambio de idioma en la Landing Page |
| **Description**    | Como visitante, quiero navegar por la plataforma en mi idioma preferido, para comprender fácilmente el contenido de presentación de Livria. |
| **Acceptance Criteria #1** | Dado que el visitante quiere cambiar el idioma de la landing page<br>Y la página se encuentra en inglés,<br>Cuando el visitante hace clic en “ES” del encabezado o en el link igual del pie de página<br>Entonces la página cambia de idioma al español. |
| **Acceptance Criteria #2** | Dado que el visitante quiere cambiar el idioma de la landing page<br>Y la página se encuentra en español,<br>Cuando el visitante hace clic en “EN” del encabezado o en el link igual del pie de página<br>Entonces la página cambia de idioma al inglés. |

| **User Story ID** | US04 |
|-------------------|------|
| **Epic ID**        | EP01 |
| **Title**          | Visualización de la sección “Home” en la landing page |
| **Description**    | Como visitante, quiero leer un resumen sobre qué es Livria en el inicio de la página, para entender rápidamente qué producto me ofrece. |
| **Acceptance Criteria #1** | Dado que el visitante quiere conocer más sobre Livria<br>Cuando el visitante entre a la landing page<br>Entonces la página muestra el inicio, es decir, “Home”<br>Y esta sección muestra un resumen de Livria y un carrusel de imágenes. |
| **Acceptance Criteria #2** | Dado que el visitante se encuentra en cualquier otra sección de la landing page<br>Y el visitante quiere ir a la sección de inicio,<br>Cuando el visitante hace clic en el link “Home” del encabezado<br>Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria #3** | Dado que el visitante se encuentra en cualquier otra sección de la landing page,<br>Cuando el visitante hace clic en el logo de Livria,<br>Entonces la página le muestra el inicio, es decir, “Home”. |

| **User Story ID** | US05 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Acceso a la sección “Contáctanos” desde la landing |
| **Description**    | Como visitante, quiero identificar fácilmente la sección “Contáctanos”, para poder establecer comunicación en caso de necesitar información adicional sobre la plataforma o tener interés en colaborar con el equipo de Livria. |
| **Acceptance Criteria #1** | Dado que el visitante se encuentra en cualquier sección de la landing page<br>Y el visitante quiere contactarse con el equipo de Livria,<br>Cuando el visitante hace clic en el link “Contáctanos” del encabezado<br>Entonces la página se desplaza hacia dicha sección de forma fluida. |
| **Acceptance Criteria #2** | Dado que el visitante se encuentra en la landing page,<br>Cuando el visitante empieza a hacer scroll desde el inicio<br>Entonces la página le muestra las siguientes secciones hasta llegar a la de “Contáctanos”. |

| **User Story ID** | US06 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Navegación simple entre secciones |
| **Description**    | Como visitante, quiero visualizar un encabezado con las secciones de la landing page, para navegar fácil y rápidamente entre ellas. |
| **Acceptance Criteria #1** | Dado que el visitante acaba de ingresar a la landing page,<br>Cuando la página cargue la pantalla inicial y el encabezado<br>Entonces el visitante puede identificar rápidamente cómo navegar por la página y cómo acceder a las secciones que le interesen. |
| **Acceptance Criteria #2** | Dado que el visitante se encuentra en la landing page de Livria,<br>Cuando el visitante hace clic en cualquiera de las opciones del encabezado<br>Entonces la página muestra dicha sección de manera fluida y sin contratiempos. |
| **Acceptance Criteria #3** | Dado que el visitante se desplaza en la página mediante el scroll,<br>Cuando el visitante navegue las distintas secciones<br>Entonces el encabezado permanece fijo y visible en la parte superior de la página<br>Y el encabezado permite cambiar de sección en cualquier momento sin necesidad de volver al inicio. |

| **User Story ID** | US07 |
|-------------------|------|
| **Epic ID**        | EP01 |
| **Title**          | Diseño atractivo de la landing page |
| **Description**    | Como visitante, quiero que la landing page sea visualmente atractiva, para sentirme interesado por Livria y motivado a usar la aplicación que ofrecen. |
| **Acceptance Criteria #1** | Dado que el visitante accede a la landing page de Livria,<br>Cuando la página cargue todos sus elementos<br>Entonces la página mostrará un diseño visual armonioso, imágenes llamativas, una paleta de colores atractiva y una tipografía clara. |
| **Acceptance Criteria #2** | Dado que el visitante se encuentra en la landing page de Livria<br>Cuando el visitante navegue a través de las secciones de la página<br>Entonces los elementos visuales seguirán la tipografía y la paleta de colores establecida, de modo que sea agradable a la vista. |

| **User Story ID** | US08 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Botón de acceso a la aplicación web |
| **Description**    | Como visitante, quiero tener un acceso directo a la aplicación de Livria, para empezar a utilizar la aplicación. |
| **Acceptance Criteria #1** | Dado que el visitante se encuentra en el inicio de la landing page,<br>Cuando el visitante hace clic en el botón “Ir a Livria”<br>Entonces la página lo redirecciona a la aplicación web de Livria. |

| **User Story ID** | US09 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Acceder a las redes sociales de Livria |
| **Description**    | Como visitante, quiero poder navegar a las redes sociales oficiales de Livria, para mantenerme informado sobre sus novedades y explorar contenido adicional. |
| **Acceptance Criteria #1** | Dado que el visitante se encuentra en el pie de página,<br>Cuando el usuario hace clic en uno de los íconos de redes sociales<br>Entonces se abre en una nueva pestaña la cuenta oficial de Livria en la red social seleccionada. |

| **User Story ID** | US10 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Redirección a las secciones |
| **Description**    | Como visitante, quiero visualizar un apartado en el pie de página con las secciones de la landing page, para retornar a cualquiera de ellas. |
| **Acceptance Criteria #1** | Dado que el visitante está en la parte inferior de la landing page,<br>Cuando el visitante hace clic en las opciones del apartado de “Navegación” del pie de página<br>Entonces la página se desliza automáticamente hacia la sección correspondiente. |
| **Acceptance Criteria #2** | Dado que el visitante ha hecho scroll por toda la página y desea volver al inicio,<br>Cuando el visitante hace clic en el enlace “Home” dentro del pie de página,<br>Entonces la página se desplaza automáticamente hacia la parte superior mostrando la sección de inicio. |

| **User Story ID** | US11 |
|-------------------|------|
| **Epic ID**        | EP02 |
| **Title**          | Formulario de contacto |
| **Description**    | Como visitante, quiero dejar mi información para que el equipo de Bookify - Livria me contacte para resolver una duda o trabajar con ellos. |
| **Acceptance Criteria #1** | Dado que el visitante desea realizar alguna consulta al equipo de Livria,<br>Cuando el visitante rellene los campos “Nombres y Apellidos”, “Correo electrónico”, “Número celular” y “Motivo de contacto”<br>Y el visitante acceda a compartir su información personal<br>Entonces el formulario enviará esta consulta al equipo de Livria. |
| **Acceptance Criteria #2** | Dado que el visitante desea trabajar con el equipo de Livria,<br>Cuando el visitante rellene todos los campos de información de contacto<br>Y el visitante adjunte el archivo de su CV<br>Y el visitante acceda a compartir su información personal<br>Entonces el formulario enviará la postulación al equipo de Livria. |
| **Acceptance Criteria #3** | Dado que el visitante desea realizar una consulta o postular para trabajo en Livria,<br>Cuando rellene los campos pero no seleccione la casilla de consentimiento del envío de información personal<br>Entonces el formulario no enviará la consulta o postulación al equipo de Livria<br>Y la página mostrará un popup señalando que marque la casilla. |
| **Acceptance Criteria #4** | Dado que el visitante desea realizar una consulta o postular para trabajo en Livria,<br>Cuando rellene solo algunos campos de información de contacto<br>Entonces el formulario no enviará la consulta o postulación al equipo de Livria<br>Y la página mostrará un popup señalando que rellene todos los campos. |

| **User Story ID** | US12 |
|-------------------|------|
| **Epic ID**        | EP03 |
| **Title**          | Recomendaciones según preferencias literarias |
| **Description**    | Como usuario, quiero recibir recomendaciones personalizadas basadas en mis preferencias literarias para poder descubrir nuevos libros y autores. |
| **Acceptance Criteria #1** | Dado que el usuario acaba de crear una cuenta en Livria,<br>Cuando el usuario ingrese a la sección de “Recomendaciones”<br>Entonces la plataforma mostrará las primeras recomendaciones aleatorias para el nuevo usuario. |
| **Acceptance Criteria #2** | Dado que el usuario ha realizado varias compras en Livria,<br>Cuando el usuario ingrese a la sección de “Recomendaciones”<br>Entonces la plataforma mostrará recomendaciones en base a las compras previas del usuario. |

| **User Story ID** | US13 |
|-------------------|------|
| **Epic ID**        | EP05 |
| **Title**          | Configuración de notificaciones |
| **Description**    | Como usuario, quiero tener la posibilidad de personalizar mis preferencias de notificación, para recibir únicamente la información que realmente me interesa y así mejorar mi experiencia dentro de la plataforma. |
| **Acceptance Criteria #1** | Dado que el usuario accede al menú de ajustes de su cuenta,<br>Cuando selecciona la opción de configuración de notificaciones,<br>Entonces podrá visualizar todas las categorías disponibles de notificaciones de la aplicación. |
| **Acceptance Criteria #2** | Dado que el usuario está dentro de la sección de configuración de notificaciones,<br>Cuando decide activar o desactivar alguna categoría específica,<br>Entonces la plataforma actualizará inmediatamente las preferencias según su elección, manteniéndolas activas hasta que el usuario decida modificarlas nuevamente o restablecer los valores predeterminados. |

| **User Story ID**         | US14 |
|--------------------------|------|
| **Epic ID**              | EP05 |
| **Title**                | Notificaciones instantáneas |
| **Description**          | Como usuario, quiero recibir notificaciones instantáneas en la aplicación, para mantenerme al tanto de mis pagos, descuentos únicos y recomendaciones otorgadas por el algoritmo de Livria. |
| **Acceptance Criteria #1** | Dado que el usuario ha marcado previamente un libro como favorito<br>Cuando el sistema genera una nueva recomendación basada en sus gustos<br>Entonces el usuario recibe una notificación con el título recomendado. |
| **Acceptance Criteria #2** | Dado que el usuario se encuentra navegando en la aplicación<br>Cuando el sistema lanza promociones especiales en determinados libros<br>Entonces el usuario recibe una notificación instantánea con los títulos que cuentan con descuento. |
| **Acceptance Criteria #3** | Dado que el usuario está activo en la plataforma<br>Cuando falten 7 días para la renovación automática de su suscripción mensual<br>Entonces el sistema enviará una notificación informando la fecha exacta del próximo cobro, indicando que la renovación se realizará de forma automática. |

| **User Story ID**         | US15 |
|--------------------------|------|
| **Epic ID**              | EP03 |
| **Title**                | Interacción con recomendaciones |
| **Description**          | Como usuario, quiero poder indicar si un libro me interesa o no, para personalizar mis futuras recomendaciones. |
| **Acceptance Criteria #1** | Dado que el usuario está explorando los libros<br>Cuando el usuario hace clic en el ícono del bookmark<br>Entonces el sistema registra el libro como preferencia positiva,<br>Y la plataforma muestra una confirmación visual<br>Y el algoritmo de recomendaciones se adapta a la selección. |
| **Acceptance Criteria #2** | Dado que el usuario está explorando los libros<br>Cuando el usuario hace clic en el ícono del negativo<br>Entonces el sistema registra el libro como preferencia negativa,<br>Y la plataforma muestra una confirmación visual<br>Y el algoritmo de recomendaciones se adapta a la selección. |

| **User Story ID**         | US16 |
|--------------------------|------|
| **Epic ID**              | EP04 |
| **Title**                | Registro e inicio de sesión |
| **Description**          | Como usuario, quiero poder registrarme e iniciar sesión con mis credenciales, para acceder a la plataforma y descubrir nuevos títulos de mi agrado. |
| **Acceptance Criteria #1** | Dado que el usuario abre la aplicación<br>Y selecciona la opción “Crear Cuenta”<br>Cuando completa correctamente los campos requeridos<br>Y confirma el registro<br>Entonces el sistema debe crear una cuenta nueva, iniciar sesión automáticamente y mostrar un mensaje de registro exitoso. |
| **Acceptance Criteria #2** | Dado que el usuario ya tiene una cuenta creada en Livria<br>Cuando introduce su usuario y contraseña en el formulario de inicio de sesión<br>Entonces el sistema debe autenticar sus credenciales y redirigirlo a su panel principal, donde podrá continuar con su experiencia de lectura. |

| **User Story ID**         | US17 |
|--------------------------|------|
| **Epic ID**              | EP03 |
| **Title**                | Sección de recomendaciones en la plataforma |
| **Description**          | Como usuario, quiero observar mis recomendaciones de manera ordenada y atractiva para poder elegir mi siguiente lectura. |
| **Acceptance Criteria #1** | Dado que el usuario está en la aplicación web de Livria,<br>Cuando el usuario quiere ver sus recomendaciones<br>Y el usuario accede a la sección de “Recomendaciones”<br>Entonces la plataforma muestra seis recomendaciones con una miniatura del libro, el título y una pequeña sinopsis. |
| **Acceptance Criteria #2** | Dado que el usuario se encuentra en la sección de “Recomendaciones”<br>Cuando el usuario hace clic en una de las recomendaciones<br>Entonces la plataforma lo dirige a la visualización completa del libro con más detalles y opciones. |

| **User Story ID**         | US18 |
|--------------------------|------|
| **Epic ID**              | EP03 |
| **Title**                | Actualización constante de recomendaciones |
| **Description**          | Como usuario, quiero obtener diferentes recomendaciones cada cierto tiempo para encontrar nuevas posibles lecturas que se adapten a mi gusto. |
| **Acceptance Criteria #1** | Dado que el usuario ha usado la aplicación web de Livria regularmente,<br>Cuando el usuario accede a la sección de “Recomendaciones” cada semana<br>Entonces la plataforma muestra seis nuevas sugerencias distintas a las vistas la semana anterior. |

| **User Story ID**         | US19 |
|--------------------------|------|
| **Epic ID**              | EP04 |
| **Title**                | Cierre de sesión |
| **Description**          | Como usuario, quiero poder cerrar sesión de mi cuenta cuando lo desee, para proteger mi información personal y asegurar la privacidad de mis datos al finalizar el uso de la plataforma. |
| **Acceptance Criteria #1** | Dado que el usuario ha iniciado sesión<br>Y se encuentra en la sección de configuración de su cuenta<br>Cuando selecciona la opción "Cerrar sesión"<br>Entonces el sistema debe cerrar su sesión activa de forma segura<br>Y redirigirlo automáticamente a la pantalla de inicio o login de Livria. |

| **User Story ID**         | US20 |
|--------------------------|------|
| **Epic ID**              | EP06 |
| **Title**                | Creación de publicaciones en comunidades |
| **Description**          | Como usuario, quiero poder crear y compartir publicaciones dentro de las comunidades temáticas de la plataforma, para interactuar con otros lectores a través de imágenes. |
| **Acceptance Criteria #1** | Dado que el usuario decide crear una nueva publicación dentro de una comunidad<br>Y opta por subir una imagen o ilustración<br>Cuando selecciona y carga el archivo desde su dispositivo<br>Entonces el sistema debe mostrar correctamente la imagen en la publicación, habilitando los comentarios por parte de otros usuarios. |
| **Acceptance Criteria #2** | Dado que el usuario desea compartir una publicación sin usar imágenes<br>Cuando ingresa un texto en el campo de publicación<br>Y lo envía<br>Entonces el sistema debe guardar y mostrar la publicación correspondiente. |

| **User Story ID**         | US21 |
|--------------------------|------|
| **Epic ID**              | EP06 |
| **Title**                | Gestión de comunidades |
| **Description**          | Como usuario, quiero poder crear y unirme a comunidades relacionadas con mis intereses literarios con el fin de conectar con distintos lectores o autores de títulos reconocidos. |
| **Acceptance Criteria #1** | Dado que el usuario se encuentra en la sección "Comunidades"<br>Cuando selecciona la opción "Crear comunidad"<br>Y completa el formulario con un nombre, descripción y categoría de la comunidad<br>Entonces el sistema debe registrar la nueva comunidad<br>Y mostrarla dentro del listado general de comunidades disponibles en Livria. |
| **Acceptance Criteria #2** | Dado que el usuario está explorando la lista de comunidades disponibles<br>Cuando ingresa al perfil de una comunidad de su interés<br>Y selecciona la opción "Unirse"<br>Entonces el sistema debe agregarlo como miembro de dicha comunidad<br>Y mostrarle una confirmación visual de su ingreso exitoso. |

| **User Story ID**         | US22 |
|--------------------------|------|
| **Epic ID**              | EP06 |
| **Title**                | Comentarios en publicaciones |
| **Description**          | Como usuario, quiero poder comentar en las publicaciones dentro de las comunidades literarias, para compartir opiniones, intercambiar ideas sobre libros y conectar con otros lectores. |
| **Acceptance Criteria #1** | Dado que el usuario se encuentra explorando una comunidad<br>Y visualiza una publicación donde desea comentar<br>Cuando selecciona la opción comentar<br>Entonces se despliega un cuadro de texto<br>Y el sistema debe publicar su comentario al enviarlo correctamente. |
| **Acceptance Criteria #2** | Dado que el usuario ha publicado un comentario en una publicación<br>Cuando presiona la opción eliminar junto a su comentario<br>Entonces el comentario debe de eliminarse de la publicación<br>Y el sistema debe confirmar que fue removido exitosamente. |
| **Acceptance Criteria #3** | Dado que el usuario está visualizando una publicación dentro de una comunidad<br>Y accede a la sección de comentarios<br>Cuando hace scroll en esa sección<br>Entonces debe poder leer los comentarios realizados por otros usuarios. |

| **User Story ID**         | US23 |
|--------------------------|------|
| **Epic ID**              | EP07 |
| **Title**                | Compra de libros digitales y físicos |
| **Description**          | Como usuario, quiero poder comprar libros digitales y físicos desde la plataforma para acceder a lecturas nuevas de manera inmediata o recibir ediciones impresas en mi domicilio. |
| **Acceptance Criteria #1** | Dado que el usuario está navegando por el catálogo de Livria<br>Cuando selecciona un libro digital y presiona “Comprar”<br>Y completa el proceso de pago<br>Entonces el sistema debe confirmar la compra<br>Y permitir la descarga inmediata del libro en su biblioteca digital. |
| **Acceptance Criteria #2** | Dado que el usuario está navegando por el catálogo<br>Cuando selecciona un libro físico y presiona “Comprar”<br>Y completa el proceso de pago y confirma su dirección de entrega<br>Entonces el sistema debe confirmar la compra<br>Y generar el pedido con estado “En proceso de envío”. |

| **User Story ID**         | US24 |
|--------------------------|------|
| **Epic ID**              | EP07 |
| **Title**                | Barra de búsqueda |
| **Description**          | Como usuario, quiero utilizar una barra de búsqueda para encontrar libros, autores y comunidades literarias de forma rápida y precisa, con el fin de acceder fácilmente a contenido de interés sin tener que navegar por toda la plataforma. |
| **Acceptance Criteria #1** | Dado que el usuario interactúa con la barra de búsqueda<br>Cuando escribe el nombre de un libro<br>Entonces el sistema debe mostrar una lista de resultados relacionados con el título ingresado, incluyendo portadas y disponibilidad. |
| **Acceptance Criteria #2** | Dado que el usuario desea encontrar obras de un autor en particular<br>Cuando ingresa el nombre del autor en la barra de búsqueda<br>Entonces el sistema debe mostrar un acceso al perfil del autor y una lista de sus libros disponibles en la plataforma. |
| **Acceptance Criteria #3** | Dado que el usuario está buscando una comunidad<br>Cuando introduce el nombre de una comunidad o una palabra clave relacionada<br>Entonces el sistema debe mostrar comunidades relevantes, incluyendo nombre, descripción y opción para unirse o seguirlas. |
| **Acceptance Criteria #4** | Dado que el usuario ingresa un término que no tiene coincidencias<br>Cuando el sistema no encuentra ningún libro, autor o comunidad con ese nombre<br>Entonces el sistema debe mostrar un mensaje indicando que no se encontraron resultados<br>Y sugerir nuevas opciones de lectura, autores o comunidades. |

| **User Story ID**         | US25 |
|--------------------------|------|
| **Epic ID**              | EP07 |
| **Title**                | Gestión del envío de libros físicos |
| **Description**          | Como usuario, quiero poder organizar y dar seguimiento al envío de mis libros físicos comprados, para saber cuándo y cómo recibiré mi pedido. |
| **Acceptance Criteria #1** | Dado que el usuario ha comprado un libro físico<br>Cuando accede a la sección de “Mis pedidos”<br>Entonces podrá ingresar la dirección de envío antes de que el pedido sea despachado. |
| **Acceptance Criteria #2** | Dado que el usuario ha comprado un libro físico<br>Y el pedido ya ha sido despachado<br>Cuando accede al detalle del pedido<br>Entonces podrá visualizar el número de seguimiento y el estado actual del envío. |
| **Acceptance Criteria #3** | Dado que el usuario ha recibido su libro físico<br>Cuando marca el pedido como recibido desde su historial de compras<br>Entonces el sistema debe actualizar el estado del pedido a “Entregado”<br>Y permitirle dejar una valoración sobre el proceso de compra. |

| **User Story ID**         | US26 |
|--------------------------|------|
| **Epic ID**              | EP07 |
| **Title**                | Proceso de pago |
| **Description**          | Como usuario, quiero poder pagar mis libros a través de Izipay, para asegurarme de que mi compra sea rápida y confiable mediante una única plataforma de pago. |
| **Acceptance Criteria #1** | Dado que el usuario ha añadido uno o más libros a su carrito de compras<br>Cuando selecciona la opción “Pagar con Izipay” y completa los datos solicitados<br>Entonces el sistema procesa el pago correctamente<br>Y muestra un mensaje de confirmación con el comprobante de la transacción. |
| **Acceptance Criteria #2** | Dado que el usuario intenta completar el pago mediante Izipay<br>Cuando ocurre un error<br>Entonces el sistema muestra un mensaje explicando el error<br>Y permite reintentar la operación. |

| **User Story ID**         | US27 |
|--------------------------|------|
| **Epic ID**              | EP03 |
| **Title**                | Valoración y reseña de libros |
| **Description**          | Como usuario, quiero poder valorar y dejar reseñas en los libros que he leído, para compartir mi opinión y ayudar a otros lectores en su elección. |
| **Acceptance Criteria #1** | Dado que el usuario ha finalizado la lectura de un libro<br>Cuando accede a la sección de valoraciones<br>Entonces puede calificar el libro con una puntuación de 1 a 5 estrellas<br>Y la valoración se actualiza en la ficha del libro. |
| **Acceptance Criteria #2** | Dado que el usuario desea dejar un comentario detallado<br>Cuando accede a la opción “Escribir reseña”<br>Entonces puede redactar y publicar su opinión sobre el contenido, estilo o experiencia de lectura. |

| **User Story ID**         | US28 |
|--------------------------|------|
| **Epic ID**              | EP04 |
| **Title**                | Actualización y gestión de suscripción |
| **Description**          | Como usuario, quiero poder actualizar mi plan de suscripción, recibir notificaciones sobre pagos y revertir cambios si me arrepiento, para tener un mayor control sobre mi experiencia en la plataforma. |
| **Acceptance Criteria #1** | Dado que el usuario tiene un plan gratuito<br>Cuando selecciona el plan “Community”<br>Y procede el pago, completando los datos requeridos<br>Entonces el sistema habilita el acceso al contenido comprado<br>Y el usuario recibe una notificación confirmando la transacción exitosa. |
| **Acceptance Criteria #2** | Dado que el usuario tiene una suscripción activa al Plan Community<br>Cuando se acerca la fecha de renovación (7 días antes)<br>Entonces el sistema envía un recordatorio por correo o notificación<br>Y una confirmación una vez que el pago se realiza exitosamente. |
| **Acceptance Criteria #3** | Dado que el usuario se encuentra suscrito a un plan de pago activo<br>Cuando decide cambiar al plan gratuito desde la sección de configuración de suscripción<br>Entonces el sistema revierte su suscripción al plan gratuito al finalizar el ciclo actual<br>Y le notifica que conservará los beneficios del plan actual hasta la fecha de renovación, momento en el cual se aplicará el plan gratuito automáticamente. |

| **User Story ID**         | US29 |
|--------------------------|------|
| **Epic ID**              | EP08 |
| **Title**                | Disponibilidad 24/7 |
| **Description**          | Como usuario, quiero que la plataforma esté disponible en cualquier momento del día, para acceder a mis libros, comunidades y funcionalidades sin importar el lugar o la hora. |
| **Acceptance Criteria #1** | Dado que el usuario desea acceder a la plataforma en cualquier momento<br>Cuando inicia sesión en Livria en cualquier horario<br>Entonces el sistema debe estar disponible<br>Y permitir el acceso sin restricciones. |
| **Acceptance Criteria #2** | Dado que el usuario está leyendo un libro digital<br>Cuando se conecte en horarios no habituales<br>Entonces la lectura debe funcionar sin ningún error. |

| **User Story ID**         | US30 |
|--------------------------|------|
| **Epic ID**              | EP04 |
| **Title**                | Seguridad del usuario |
| **Description**          | Como usuario, quiero que mi información personal y actividad en Livria estén protegidas, para sentirme seguro mientras navego, leo o realizo compras en la plataforma. |
| **Acceptance Criteria #1** | Dado que el usuario ha ingresado datos como nombre, correo y dirección<br>Cuando navega o interactúa dentro de la plataforma<br>Entonces el sistema debe garantizar que esta información no sea compartida ni filtrada a terceros sin consentimiento. |
| **Acceptance Criteria #2** | Dado que el usuario realiza una compra mediante Izipay<br>Cuando ingresa sus datos de pago<br>Entonces el sistema debe confirmar que la transacción es segura y privada. |

| **User Story ID**         | US31 |
|--------------------------|------|
| **Epic ID**              | EP08 |
| **Title**                | Interfaz amigable |
| **Description**          | Como usuario, quiero una interfaz intuitiva y fácil de usar, para navegar entre libros, comunidades y configuraciones sin complicaciones ni curvas de aprendizaje. |
| **Acceptance Criteria #1** | Dado que el usuario inicia sesión en la plataforma<br>Cuando desea acceder a las secciones principales como “Comunidad” o “Recomendaciones”<br>Entonces podrá hacerlo con pocos clics y sin confusión, gracias a una estructura organizada y un diseño intuitivo. |
| **Acceptance Criteria #2** | Dado que el usuario interactúa con la aplicación<br>Cuando el usuario visualiza la interfaz<br>Entonces los botones, textos e íconos deben tener buen contraste, tamaño adecuado<br>Y estar correctamente etiquetados para garantizar la accesibilidad. |

| **User Story ID**         | US32 |
|--------------------------|------|
| **Epic ID**              | EP08 |
| **Title**                | Soporte multiplataforma |
| **Description**          | Como usuario, quiero ingresar a Livria desde distintos dispositivos, para acceder a mis libros y comunidades desde cualquier lugar y sin perder mi progreso. |
| **Acceptance Criteria #1** | Dado que el usuario utiliza distintos dispositivos<br>Cuando accede a Livria desde cualquiera de ellos<br>Entonces la experiencia debe mantenerse fluida y funcional, sin errores de formato o limitaciones de funciones. |

| **User Story ID**         | US33 |
|--------------------------|------|
| **Epic ID**              | EP07 |
| **Title**                | Navegación principal por categorías editoriales |
| **Description**          | Como usuario, quiero acceder rápidamente a las categorías presentes en la barra superior de navegación para descubrir libros organizados según mis intereses personales. |
| **Acceptance Criteria #1** | Dado que el usuario se encuentra en la barra superior de navegación<br>Cuando hace clic en una categoría<br>Entonces se le redirige a una página que muestra únicamente libros correspondientes a esa categoría<br>Y se resalta visualmente para indicar que está activa. |

| **User Story ID**         | US34 |
|--------------------------|------|
| **Epic ID**              | EP07 |
| **Title**                | Filtro lateral por subcategorías y atributos del libro |
| **Description**          | Como usuario, quiero filtrar los libros según subcategorías, orden de precio o título, formato e idioma para encontrar más fácilmente el contenido que me interesa. |
| **Acceptance Criteria #1** | Dado que el usuario se encuentra en la vista de libros<br>Cuando selecciona una subcategoría<br>Entonces la lista de libros se actualiza mostrando solo los que pertenecen a esa subcategoría. |
| **Acceptance Criteria #2** | Dado que el usuario quiere ordenar los resultados<br>Cuando elige una opción como “Menor a mayor precio”<br>Entonces la lista se reordena automáticamente según esos criterios. |
| **Acceptance Criteria #3** | Dado que el usuario tiene una preferencia por el formato del libro<br>Cuando selecciona un formato específico<br>Entonces se muestran los libros que coincidan con las condiciones. |
| **Acceptance Criteria #4** | Dado que el usuario tiene una preferencia por el idioma<br>Cuando selecciona el idioma de su preferencia<br>Entonces se muestran los libros que coincidan con el idioma elegido. |
| **Acceptance Criteria #5** | Dado que el usuario ha aplicado filtros<br>Cuando presiona el botón “Borrar selección”<br>Entonces se eliminan todos los filtros activos<br>Y la lista vuelve a su estado inicial. |

### 3.2.3. Epicas

| **EPIC 01:** | Descubrimiento y comprensión de Livria |
|:------------:|:--------------------------------------|
| | Como visitante, quiero conocer fácilmente qué es Livria, qué ofrece y quiénes lo desarrollan, para evaluar si la plataforma es relevante para mí. |
| **User Story ID** | **Título** |
| US01 | Presentación de servicios de Livria |
| US02 | Acceso a la sección “Sobre Nosotros” |
| US04 | Visualización de la sección “Home” |
| US07 | Diseño atractivo de la landing page |

| **EPIC 02:** | Navegación e interacción accesible desde la landing page |
|:------------:|:---------------------------------------------------------|
| | Como visitante, quiero navegar de forma intuitiva por la landing page, cambiar el idioma a mi comodidad y tener acceso rápido a los recursos de contacto y redes, para explorar todo lo que Livria ofrece y establecer contacto directo si me interesa participar o colaborar. |
| **User Story ID** | **Título** |
| US03 | Cambio de idioma en la Landing Page |
| US05 | Acceso a la sección “Contáctanos” |
| US06 | Navegación simple entre secciones |
| US08 | Botón de acceso a la aplicación web |
| US09 | Acceder a las redes sociales de Livria |
| US10 | Redirección a las secciones desde el pie de página |
| US11 | Formulario de contacto |

| **EPIC 03:** | Personalización inteligente de la experiencia lectora |
|:------------:|:------------------------------------------------------|
| | Como usuario, quiero que Livria entienda mis gustos literarios y me ofrezca contenido relevante, actualizado y ajustado a mis preferencias, para que cada vez que entre encuentre algo nuevo y atractivo que realmente me interese. |
| **User Story ID** | **Título** |
| US12 | Recomendaciones según preferencias literarias |
| US15 | Interacción con recomendaciones |
| US17 | Sección de recomendaciones en la plataforma |
| US18 | Actualización constante de recomendaciones |
| US27 | Valoración y reseña de libros |

| **EPIC 04:** | Gestión de cuenta y seguridad del usuario |
|:------------:|:------------------------------------------|
| | Como usuario, quiero gestionar mi cuenta de forma segura y flexible, para tener el control de mi experiencia dentro de la plataforma y proteger mi información personal. |
| **User Story ID** | **Título** |
| US16 | Registro e inicio de sesión |
| US19 | Cierre de sesión |
| US28 | Actualización y gestión de suscripción |
| US30 | Seguridad del usuario |

| **EPIC 05:** | Notificaciones y comunicación con el usuario |
|:------------:|:---------------------------------------------|
| | Como usuario, quiero recibir notificaciones relevantes y configurables, para mantenerme informado de lo que realmente me importa dentro de Livria sin saturarme de mensajes innecesarios. |
| **User Story ID** | **Título** |
| US13 | Configuración de notificaciones |
| US14 | Notificaciones instantáneas |

| **EPIC 06:** | Interacción y construcción de comunidad |
|:------------:|:----------------------------------------|
| | Como usuario, quiero participar activamente en comunidades literarias temáticas, compartir contenido, comentar publicaciones y conocer a otros lectores que compartan mis intereses. |
| **User Story ID** | **Título** |
| US20 | Creación de publicaciones en comunidades |
| US21 | Gestión de comunidades |
| US22 | Comentarios en publicaciones |

| **EPIC 07:** | Compra y seguimiento de libros |
|:------------:|:-------------------------------|
| | Como usuario, quiero comprar libros digitales o físicos de manera sencilla y contar con herramientas para buscar títulos, autores y comunidades fácilmente, para adquirir lecturas de mi interés y navegar por el catálogo sin complicaciones. |
| **User Story ID** | **Título** |
| US23 | Compra de libros digitales y físicos |
| US24 | Barra de búsqueda |
| US25 | Gestión del envío de libros físicos |
| US26 | Proceso de pago |
| US33 | Navegación principal por categorías editoriales |
| US34 | Filtro lateral por subcategorías y atributos del libro |

| **EPIC 08:** | Accesibilidad y experiencia de uso multiplataforma |
|:------------:|:--------------------------------------------------|
| | Como usuario, quiero que la plataforma sea rápida, disponible siempre y con una interfaz intuitiva desde cualquier dispositivo, para disfrutar de una experiencia cómoda, fluida y sin interrupciones. |
| **User Story ID** | **Título** |
| US29 | Disponibilidad 24/7 |
| US31 | Interfaz amigable |
| US32 | Soporte multiplataforma |

## 3.3. Impact Mapping
El Impact Mapping de Livria es una herramienta visual que conecta el objetivo principal del negocio, aumentar en un 60% el número de usuarios que finalizan al menos un libro por mes, con los usuarios clave (estudiantes universitarios y lectores casuales), los impactos deseados en su comportamiento, las funcionalidades necesarias para lograr esos cambios y las historias de usuario que reflejan sus necesidades reales. Entre los impactos buscados están el uso preferente de Livria para buscar libros, la descarga o compra desde la app, y el descubrimiento frecuente de nuevas lecturas. Para lograrlo, se plantean funcionalidades como recomendaciones personalizadas, búsqueda avanzada, comparadores de precios y formatos, acceso digital directo, y comunidad con reseñas. Estas funcionalidades se traducen en historias de usuario que guían el desarrollo centrado en mejorar la experiencia de lectura y aumentar el compromiso con la plataforma.

<p align="center">
  <img src="https://imgur.com/ddUYr4v.png" alt="Im" width="500">
</p>

Link: https://drive.google.com/drive/folders/1zJEVEmTVXp3wqfTOmNEAVbZhEzfipoDu?usp=drive_link

## 3.4. Product Backlog

| # Orden | User Story ID | Descripción | Story Points (1/2/3/5) |
|:-------:|:-------------:|:------------|:----------------------:|
| 1 | US12 | Como usuario, quiero recibir recomendaciones personalizadas basadas en mis preferencias literarias para poder descubrir nuevos libros y autores. | 5 |
| 2 | US26 | Como usuario, quiero poder pagar mis libros a través de Izipay, para asegurarme de que mi compra sea rápida y confiable mediante una única plataforma de pago. | 5 |
| 3 | US20 | Como usuario, quiero poder crear y compartir publicaciones dentro de las comunidades temáticas de la plataforma, para interactuar con otros lectores a través de vídeos e imágenes. | 5 |
| 4 | US24 | Como usuario, quiero utilizar una barra de búsqueda para encontrar libros, autores y comunidades literarias de forma rápida y precisa, con el fin de acceder fácilmente a contenido de interés sin tener que navegar por toda la plataforma. | 5 |
| 5 | US21 | Como usuario, quiero poder crear y unirme a comunidades relacionadas con mis intereses literarios con el fin de conectar con distintos lectores o autores de títulos reconocidos. | 5 |
| 6 | US28 | Como usuario, quiero poder actualizar mi plan de suscripción, recibir notificaciones sobre pagos y revertir cambios si me arrepiento, para tener un mayor control sobre mi experiencia en la plataforma. | 5 |
| 7 | US23 | Como usuario, quiero poder comprar libros digitales y físicos desde la plataforma para acceder a lecturas nuevas de manera inmediata o recibir ediciones impresas en mi domicilio. | 5 |
| 8 | US14 | Como usuario, quiero recibir notificaciones instantáneas en la aplicación, para mantenerme al tanto de mis pagos, descuentos únicos y recomendaciones otorgadas por el algoritmo de Livria. | 3 |
| 9 | US15 | Como usuario, quiero poder indicar si un libro me interesa o no, para personalizar mis futuras recomendaciones. | 3 |
| 10 | US30 | Como usuario, quiero que mi información personal y actividad en Livria estén protegidas, para sentirme seguro mientras navego, leo o realizo compras en la plataforma. | 3 |
| 11 | US22 | Como usuario, quiero poder comentar en las publicaciones dentro de las comunidades literarias, para compartir opiniones, intercambiar ideas sobre libros y conectar con otros lectores. | 3 |
| 12 | US27 | Como usuario, quiero poder valorar y dejar reseñas en los libros que he leído, para compartir mi opinión y ayudar a otros lectores en su elección. | 3 |
| 13 | US18 | Como usuario, quiero obtener diferentes recomendaciones cada cierto tiempo para encontrar nuevas posibles lecturas que se adapten a mi gusto. | 3 |
| 14 | US17 | Como usuario, quiero observar mis recomendaciones de manera ordenada y atractiva para poder elegir mi siguiente lectura. | 3 |
| 15 | US31 | Como usuario, quiero una interfaz intuitiva y fácil de usar, para navegar entre libros, comunidades y configuraciones sin complicaciones ni curvas de aprendizaje. | 3 |
| 16 | US25 | Como usuario, quiero poder organizar y dar seguimiento al envío de mis libros físicos comprados, para saber cuándo y cómo recibiré mi pedido. | 3 |
| 17 | US32 | Como usuario, quiero ingresar a Livria desde distintos dispositivos, para acceder a mis libros y comunidades desde cualquier lugar y sin perder mi progreso. | 3 |
| 18 | US34 | Como usuario, quiero filtrar los libros según subcategorías, orden de precio o título, formato e idioma para encontrar más fácilmente el contenido que me interesa. | 3 |
| 19 | US05 | Como visitante, quiero identificar fácilmente la sección “Contáctanos”, para poder establecer comunicación en caso de necesitar información adicional sobre la plataforma o tener interés en colaborar con el equipo de Livria. | 2 |
| 20 | US19 | Como usuario, quiero poder cerrar sesión de mi cuenta cuando lo desee, para proteger mi información personal y asegurar la privacidad de mis datos al finalizar el uso de la plataforma. | 2 |
| 21 | US29 | Como usuario, quiero que la plataforma esté disponible en cualquier momento del día, para acceder a mis libros, comunidades y funcionalidades sin importar el lugar o la hora. | 2 |
| 22 | US16 | Como usuario, quiero poder registrarme e iniciar sesión con mis credenciales, para acceder a la plataforma y descubrir nuevos títulos de mi agrado. | 2 |
| 23 | US07 | Como visitante, quiero que la landing page sea visualmente atractiva, para sentirme interesado por Livria y motivado a usar la aplicación que ofrecen. | 2 |
| 24 | US03 | Como visitante, quiero navegar por la plataforma en mi idioma preferido, para comprender fácilmente el contenido de presentación de Livria. | 2 |
| 25 | US13 | Como usuario, quiero tener la posibilidad de personalizar mis preferencias de notificación, para recibir únicamente la información que realmente me interesa y así mejorar mi experiencia dentro de la plataforma. | 2 |
| 26 | US33 | Como usuario, quiero acceder rápidamente a las categorías presentes en la barra superior de navegación para descubrir libros organizados según mis intereses personales. | 2 |
| 27 | US11 | Como visitante, quiero dejar mi información para que el equipo de Bookify - Livria me contacte para resolver una duda o trabajar con ellos. | 2 |
| 28 | US08 | Como visitante, quiero tener un acceso directo a la aplicación de Livria, para empezar a utilizar la aplicación. | 1 |
| 29 | US10 | Como visitante, quiero visualizar un apartado en el pie de página con las secciones de la landing page, para retornar a cualquiera de ellas. | 1 |
| 30 | US09 | Como visitante, quiero poder navegar a las redes sociales oficiales de Livria, para mantenerme informado sobre sus novedades y explorar contenido adicional. | 1 |
| 31 | US06 | Como visitante, quiero visualizar un encabezado con las secciones de la landing page, para navegar fácil y rápidamente entre ellas. | 1 |
| 32 | US04 | Como visitante, quiero leer un resumen sobre qué es Livria en el inicio de la página, para entender rápidamente qué producto me ofrece. | 1 |
| 33 | US02 | Como visitante, quiero acceder fácilmente a la sección “Sobre Nosotros”, para conocer la trayectoria de los creadores de Livria, comprender en qué consiste la plataforma y descubrir las funcionalidades que ofrece. | 1 |
| 34 | US01 | Como visitante, quiero ver información relevante sobre las funcionalidades principales que ofrece Livria, para conocer las características únicas de la aplicación. | 1 |

# CAPÍTULO 4: PRODUCT UX/UI DESIGN
## 4.1. Style Guidelines
Livria es una plataforma web que busca transformar la forma en que las personas acceden a los libros y desarrollan su hábito lector. Combina la funcionalidad de una tienda virtual con herramientas interactivas que mejoran la comprensión lectora, brindando una experiencia accesible, atractiva y adaptada a los hábitos digitales. Además de facilitar la compra de libros físicos y digitales, Livria promueve una comunidad literaria activa, motivando a lectores de todas las edades a reconectarse con la lectura de manera significativa.

Esta sección presenta una guía estructurada que unifica todos los elementos visuales y de diseño utilizados en la plataforma Livria. Se organizan recursos gráficos como tipografías, paletas de colores y otros componentes visuales con el objetivo de mantener una identidad coherente que refleje el propósito de la marca: incentivar la lectura. Gracias a esta consistencia en el diseño, la navegación se vuelve más sencilla, lo que potencia una experiencia de usuario clara, funcional y alineada con los valores de la plataforma.

### 4.1.1. General Style Guidelines
El branding de Livria es el pilar fundamental de su identidad visual, diseñado para reflejar sus valores clave: fomento de la lectura, accesibilidad y construcción de comunidad. A través de una estética cálida, moderna y cercana, la marca busca capturar la esencia de la experiencia literaria digital, ofreciendo una presencia visual que sea tanto acogedora como inspiradora. 

El logotipo, la paleta de colores y la tipografía de Livria evocan tranquilidad, imaginación y conexión, elementos que representan la facilidad con la que los usuarios pueden descubrir, leer y compartir libros. El branding está alineado con el espíritu inclusivo y motivador de la plataforma, asegurando que lectores de todas las edades se sientan parte de una comunidad que valora la lectura como una experiencia enriquecedora y transformadora.

#### 4.1.1.1. Tipografía
La tipografía de Livria desempeña un papel esencial en la transmisión de su identidad, aportando calidez, claridad y cercanía en cada punto de contacto con el usuario. Se ha elegido una familia tipográfica que combina lo moderno con lo amigable, asegurando una lectura fluida y cómoda en distintos formatos y dispositivos.

<p align="center">
  <img src="https://imgur.com/7v6eGFP.png" alt="TipoTipoti" width="500">
</p>

**Tipografía del Logo y Títulos**

El logo de Livria es fundamental para la imagen del producto, por lo que se ha utilizado la tipografía Asap Condensed. Esta, con su estética limpia y moderna, transmite accesibilidad y dinamismo, cualidades esenciales para una plataforma que busca conectar emocionalmente con lectores jóvenes y adultos contemporáneos. Su diseño estilizado pero legible aporta una personalidad clara y versátil que se adapta perfectamente a entornos digitales, manteniendo una presencia fuerte sin resultar invasiva.

<p align="center">
  <img src="https://imgur.com/meys2KX.png" alt="TipoLoTi" width="500">
</p>

**Tipografía de Texto Regular**

Para el texto de la aplicación web se ha elegido la tipografía Alexandria con el objetivo de que permita la lectura cómoda y agradable, volviendo la experiencia de uso en placentera y continua. Se han definido diferentes pesos tipográficos — light, regular, medium y bold — para organizar de manera efectiva los distintos niveles de contenido, optimizando la jerarquía visual en la experiencia del usuario.

<p align="center">
  <img src="https://imgur.com/fOQ6jJT.png" alt="TipoTeRe" width="500">
</p>

#### 4.1.1.2. Colores
La elección de colores para la plataforma es fundamental para asegurar la placentera experiencia de usuario. Por ello, la paleta de colores de Livria ha sido cuidadosamente seleccionada para reflejar la esencia de la aplicación web: calidez, cercanía y motivación por la lectura.

<p align="center">
  <img src="https://imgur.com/g7uDwbu.png" alt="Colores" width="500">
</p>

**Paleta Principal**
* Anaranjado (#FF5C00): Este color vibrante representa la energía, la creatividad y la motivación que Livria busca despertar en sus usuarios. Es un tono cálido y estimulante que invita a la acción y al entusiasmo por la lectura.
* Ámbar (#FEB913): El ámbar complementa la vitalidad del anaranjado con una sensación de optimismo, luz y claridad. Es un color que simboliza el conocimiento y la inspiración, haciendo que el entorno visual sea más acogedor.
* Cian Suave (#A8DBDE): Este tono aporta equilibrio a la paleta, introduciendo una sensación de calma, frescura y apertura. Su suavidad invita a la concentración y al disfrute tranquilo de la lectura, generando armonía visual.

**Paleta Secundaria**
* Amarillo Claro (#FFD150): Utilizado para resaltar detalles importantes, este color transmite alegría, juventud y dinamismo. Aporta luminosidad sin ser invasivo, ideal para llamadas de atención sutiles.
* Azul Marino (#063A5D): Este tono profundo sugiere confianza, profesionalismo y estabilidad. Es perfecto para textos o elementos estructurales que requieran seriedad y contraste visual con los colores más cálidos.
* Gris Claro (#F4F5F7): Su neutralidad lo convierte en una base ideal que permite que los colores principales destaquen sin generar ruido visual. Transmite pulcritud y modernidad.
* Azul (#2364A0): Este azul intermedio ofrece un punto medio entre el dinamismo del marino y la frescura del cian. Representa exploración, profundidad y conexión, claves en la experiencia literaria digital que Livria propone.

#### 4.1.1.3. Espaciado
El espaciado en la interfaz web de Livria ha sido cuidadosamente estructurado para brindar una experiencia visual ordenada, respirable y armoniosa. Se ha definido una escala progresiva basada en múltiplos de 10 (10, 20, 40 y 60 píxeles), aplicada estratégicamente en márgenes y paddings para marcar jerarquías visuales, separar secciones y mejorar la legibilidad general. Esta lógica de espaciado aporta coherencia y claridad, sin perder flexibilidad: el contenido y los componentes mantienen una adaptabilidad fluida frente a distintos tamaños de pantalla, permitiendo que el diseño conserve su equilibrio estético tanto en resoluciones amplias como en visualizaciones más compactas. La consistencia en los espacios no solo refuerza el ritmo visual, sino que también guía de manera intuitiva la atención del usuario a lo largo de su recorrido por la web.

#### 4.1.1.4. Iconografía
Los íconos son elementos visuales sencillos que permiten identificar rápidamente funciones o acciones dentro de una plataforma, ya sea una app o un sitio web. Su presencia facilita la interacción del usuario, guiándose de forma clara y natural por la interfaz.

Incorporar íconos en nuestras plataformas resulta fundamental para optimizar la experiencia del usuario. No solo simplifican la navegación y hacen más claro el contenido, sino que también agilizan la interacción. Al ser símbolos reconocibles a nivel global, superan las barreras del idioma y permiten que cualquier persona comprenda con facilidad las opciones disponibles.

<p align="center">
  <img src="https://imgur.com/xs2S5yk.png" alt="Iconografia" width="500">
</p>

#### 4.1.1.5. Tono de Comunicación y Lenguaje Aplicado
El tono de Livria es cálido, motivador y accesible, diseñado para generar una conexión emocional con los usuarios. La plataforma busca acompañar al lector en su camino, ya sea que esté dando sus primeros pasos o retomando el hábito. Por ello, el tono se mantiene empático, cercano y alentador, transmitiendo confianza y entusiasmo por la lectura. También se adopta un estilo inspirador, que motive a explorar nuevas historias y sentirse parte de una comunidad literaria viva.

En cuanto al lenguaje, se utiliza un estilo claro y directo, evitando tecnicismos o estructuras complicadas, tanto en la versión de inglés como en la de español. Todo el contenido está pensado para ser fácilmente comprensible por personas de distintas edades y niveles de lectura. Además, cuando es apropiado, se recurre a una narrativa amigable o a ejemplos concretos, lo que facilita la identificación del usuario con los mensajes.

Este enfoque comunicativo busca crear una experiencia acogedora, inspiradora y auténtica, alineada con los valores de Livria: fomentar el hábito lector, promover la comprensión lectora y construir una comunidad conectada a través de los libros.

### 4.1.2. Web Style Guidelines
En la construcción del sistema visual de Livria se adoptó una línea gráfica coherente, limpia y moderna, orientada a la claridad, la accesibilidad y la personalidad de marca. La combinación tipográfica integra ASAP Condensed para los títulos, aportando dinamismo y carácter, mientras que fuentes como Alexandria en el sistema aportan legibilidad y un toque profesional. La jerarquización visual se refuerza mediante estilos diferenciados para subtítulos, acompañados de una paleta funcional aplicada con botones interactivos que responden a estados (normal, hover, seleccionado) y generan retroalimentación visual clara. El tratamiento de bordes suaves y sombras sutiles contribuye a una interfaz amigable, en la que los elementos tienen peso visual sin recargar la vista. Finalmente, el diseño de íconos responde a una estética lineal, accesible e intuitiva, que refuerza la identidad de la interfaz sin distraer la atención del usuario. Cada componente visual fue pensado no solo para armonizar entre sí, sino también para potenciar la experiencia digital de los lectores.

<p align="center">
  <img src="https://imgur.com/dVvbXK7.png" alt="WSG" width="500">
</p>

## 4.2. Information Architecture
La arquitectura de información de nuestra aplicación es fundamental para que el usuario pueda interactuar con esta de manera intuitiva y así retener su atención y facilitarle el acceso a la información que necesita.

## 4.2.1. Organization Systems
Para ilustrar las relaciones entre componentes de manera visual, se utilizará un diagrama organizado de manera jerárquica y en categorías, planteando sistemas de organización de información que contribuyan a una navegación más intuitiva para nuestros usuarios, lo que mejorará su experiencia de uso.

*Landing Page:*

<p align="center">
  <img src="https://imgur.com/Hw4O0Y1.png" alt="LP" width="500">
</p>

*Web Application:*

<p align="center">
  <img src="https://imgur.com/nxRTPNJ.png" alt="WA" width="500">
</p>

*Screen Organization:*

<p align="center">
  <img src="https://imgur.com/W6MtC8E.png" alt="SO" width="500">
</p>

### 4.2.2. Labeling Systems
La interfaz de Livria ha sido diseñada de manera eficiente y organizada, ofreciéndole al cliente una experiencia de uso dinámica que le permitirá encontrar una ruta rápida hacia la información que quiere consultar o las herramientas que quiere utilizar sin complicaciones. Para lograr esto, nuestro equipo ha propuesto un diseño que emplea etiquetas concisas y efectivas, favoreciendo una experiencia intuitiva. A continuación, se dará una descripción detallada de aquellas que se encuentran en nuestro proyecto:

*Landing Page*

<p align="center">
  <img src="https://imgur.com/vdcUI9f.png" alt="LPLP" width="500">
</p>

Antes de ingresar a la plataforma, el usuario se encontrará primero con el encabezado, en esta sección de la pantalla, encontrará las etiquetas “HOME”, “SERVICES”, “ABOUT US”, “CONTACT US”, “ES/EN”:

* HOME: Esta etiqueta provee un acceso rápido a la página principal de la Landing Page, el usuario puede acceder a esta fácilmente desde cualquier sección del sitio web.
* SERVICES: Esta etiqueta sirve como acceso directo a la página de “Servicios”, que contiene descripciones de los diferentes servicios que ofrece la plataforma.
* ABOUT US: Esta etiqueta sirve para brindar una ruta al usuario a la página de “Nosotros”, donde se encontrarán dos párrafos introductorios de la startup (Bookify) y el proyecto (Livria).
* CONTACT US: Esta etiqueta tiene la función de acceso directo a la página de “Contacto”, en la que se encontrará un formulario de contacto que el usuario puede utilizar para enviar comentarios o
* ES/EN: Esta etiqueta servirá para alternar la vista del sitio web, dando la opción al usuario de visualizarla en español (ES) o inglés (EN), dependiendo de sus necesidades.

*Homepage*

<p align="center">
  <img src="https://imgur.com/lOfOlU4.png" alt="HPHP" width="500">
</p>

Al ingresar a la plataforma, el usuario encontrará la interfaz propia de la aplicación, que mantiene el diseño y estilo general propuesto por el equipo, pero contiene etiquetas más relacionadas al funcionamiento del servicio. El encabezado de esta pantalla contiene las siguientes etiquetas:

* CARRITO: Utilizada para redirigir al usuario a la pantalla de “Carrito”, donde podrá observar la lista de productos que ha agregado a la lista de compra y efectuar la compra.
* TIENDA: Utilizada para redirigir al usuario a la pantalla de “Tienda”, donde podrá encontrar libros disponibles dentro de la aplicación, así como agregarlas a la lista de compra.
* NOTIFICACIONES: Esta etiqueta servirá para redirigir al usuario a la bandeja de notificaciones y sus opciones de configuración.
* CUENTA: Redirige al usuario a la pantalla de “Cuenta”, donde podrá consultar su información y acceder a los ajustes de cuenta dentro de la aplicación.
* EN/ES: Permite al usuario intercambiar el idioma de la interfaz entre Español (ES) e Inglés (EN), facilitando la lectura de los textos en pantalla.
* RECOMENDACIONES: Permite al usuario acceder a la pantalla de “Recomendaciones”, donde podrá recibir sugerencias de lectura en base a sus gustos.
* Etiquetas de categoría (LITERATURA - INFANTIL): Estas etiquetas permitirán al usuario realizar una búsqueda rápida en base a su contenido, facilitando el proceso de encontrar libros de diferentes categorías.
* EBOOKS Y AUDIOLIBROS: Redirige al usuario a la búsqueda de libros por tipo, facilitando la búsqueda de libros en formatos especiales.
* COMUNIDADES: Redirige al usuario a la interfaz de la función de “Comunidades”, una pantalla exclusiva para miembros con suscripción, con sus respectivas funcionalidades.

La elección de estos nombres para las etiquetas fue motivada por su uso frecuente dentro de diversas plataformas digitales, lo que ayudará al usuario a familiarizarse mucho más rápido con estas interfaces y le permitirá navegar por las diferentes pantallas de manera mucho más sencilla.

### 4.2.3. SEO Tags and Meta Tags

*Title:*

<title>Bookify - Livria</title>

En este meta tag, se define el título que tendrá el sitio web del proyecto. El equipo decidió usar el nombre de la startup seguido del nombre del producto para resaltar nuestra autoría sobre la idea, optando por una mayor simplicidad que facilite la lectura por parte del usuario.

*Meta tags:*

<meta charset="UTF-8”>

<meta name"viewport" content="width=device-width, initial-scale=1.0">

El equipo no realizó cambios sobre los meta tags incluídos por defecto dentro del archivo HTML, debido a que no fueron necesarios para el correcto funcionamiento de la página.

*Description:*

<meta name="description" content="Livria transforms how people access books and develop reading habits with interactive tools, a vibrant community, and access to physical and digital books.”>

El meta tag designado para la descripción del sitio web contiene un breve párrafo introductorio que resume los principales servicios que ofrece la aplicación, con el objetivo de informar rápidamente a los usuarios que no son familiares con su funcionamiento.

*Keywords:*

<meta name="keywords" content="Livria, books, reading, community, digital books, physical books, interactive tools”>

Los meta tags de “Keywords” tienen el propósito de optimizar la búsqueda del sitio web en navegadores al ampliar el número de términos que un usuario puede ingresar en la barra de búsqueda para localizarlo. En el caso de nuestro proyecto, se utilizaron términos relacionados al apartado de compra de libros y la función de comunidad.

*Author:*

<meta name="author" content="Bookify”>

Para el meta tag de “author”, el equipo decidió colocar el nombre de la startup para reflejar que su creación fue producto del esfuerzo colaborativo de los integrantes, además de resaltar nuestra autoría sobre el producto.

### 4.2.4. Searching Systems

En Livria, los Searching Systems fueron diseñados para simplificar la experiencia de búsqueda y mejorar la experiencia del usuario, ayudándolo a localizar los productos que quiere consultar rápidamente y de manera eficiente. Esto nos ayudará a evitar que los clientes se sientan abrumados o tengan problemas para encontrar libros de su interés.

<p align="center">
  <img src="https://imgur.com/zdCzLR9.png" alt="SS" width="500">
</p>

Dentro del encabezado la interfaz principal de la aplicación de Livria, el usuario encontrará una barra de búsqueda, la cual ejercerá el rol de principal herramienta de búsqueda de contenido. Esta barra le permitirá al usuario ingresar palabras clave y encontrar libros en base a distintos criterios, tales como el título del libro, su autor o el género literario al que pertenece.

La aplicación realizará la búsqueda en base a todos estos criterios y le ofrecerá al usuario los resultados más precisos que pudo encontrar.

<p align="center">
  <img src="https://imgur.com/EuBig5F.png" alt="SS2" width="500">
</p>

Además de la búsqueda manual, Livria ofrece diversas opciones de exploración dentro de la pantalla principal, ya que se podrán visualizar diferentes secciones dedicadas a categorías o géneros literarios específicos. Este sistema estará basado en algoritmos y servirá para ofrecerle al usuario una vista rápida y amplia del contenido de la aplicación.

### 4.2.5. Navigation Systems
Los Navigation Systems de Livria fueron diseñados para simplificar la navegación dentro de la aplicación y entre interfaces relacionadas, favoreciendo una interacción fluida, intuitiva y cómoda para nuestros usuarios. Nuestro proyecto logrará esto a través de la implementación de un menú de navegación en la parte superior de la interfaz.

<p align="center">
  <img src="https://imgur.com/LuHEyBQ.png" alt="NS1" width="500">
</p>

El menú de navegación ofrece diferentes opciones que ayudan al usuario a desplazarse entre secciones principales de la aplicación. Esta barra de navegación está presente en todo momento y en todas las diferentes pantallas de la interfaz. La combinación entre el espaciado, el lenguaje utilizado y la iconografía presente en cada elemento interactivo que la conforma garantiza una mayor comodidad de uso y facilidad de lectura para tanto usuario experimentados como principiantes.

<p align="center">
  <img src="https://imgur.com/u5T4cEY.png" alt="NS2" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/UCQfnFA.png" alt="NS3" width="500">
</p>

Dentro de la interfaz principal, la herramienta de navegación que usará el usuario será la interacción con elementos de la pantalla, como las imágenes designadas para libros y comunidades, que servirán como acceso directo a su información específica.

<p align="center">
  <img src="https://imgur.com/np0ilCs.png" alt="NS4" width="500">
</p>

Al final de la interfaz, el usuario podrá encontrar una sección de pie de página que contiene etiquetas con vínculos externos y herramientas de navegación propias de la página, que lo ayudarán a localizar información adicional sobre el servicio y acceder a otras pantallas.

Los Navigation Systems de nuestro proyecto ofrecen un recorrido intuitivo y eficiente que garantiza que los usuarios puedan explorar el contenido de la aplicación sin problemas ni frustraciones, agilizando su proceso de familiarización con la interfaz y optimizando la elaboración de rutas dentro de la misma.

## 4.3. Landing Page UI Design
La propuesta de UI para la landing page de Livria surge como una traducción visual clara y coherente de las decisiones tomadas durante el desarrollo de la arquitectura de información y el diseño centrado en el usuario. Desde el primer vistazo, se busca transmitir una identidad accesible, amigable y culturalmente cercana, alineada con los valores de promoción de la lectura y la comunidad lectora. La distribución de secciones —Home, Services, About Us y Contact Us— prioriza una navegación fluida e intuitiva, reforzada por una jerarquía visual limpia y componentes interactivos que guían la experiencia del visitante. La estética combina ilustraciones cálidas, tipografías legibles y un uso estratégico del color para generar confianza, despertar interés y dirigir la atención hacia los llamados a la acción. Esta UI no solo refleja las decisiones estructurales del proyecto, sino que también invita a los usuarios a conectar emocionalmente con el propósito de Livria desde el primer contacto.

### 4.3.1. Landing Page Wireframes

<p align="center">
  <img src="https://imgur.com/ukFHT37.png" alt="LPW1" width="500">
</p>

En primer lugar, se observa la pantalla de inicio de la Landing Page de Livria. Esta tiene una descripción sobre qué trata la aplicación web que se ofrece y un carrusel de imágenes relacionadas. Asimismo, tiene el header con los accesos a cada sección de la landing page

<p align="center">
  <img src="https://imgur.com/h9vfov1.png" alt="LPW2" width="500">
</p>

En la sección siguiente aparece la información sobre los servicios de Livria: Variedad de libros, Comunidad de libros, y Recomendaciones. Asimismo, cada tarjeta de información tiene su imagen correspondiente.

<p align="center">
  <img src="https://imgur.com/CBwjtos.png" alt="LPW3" width="500">
</p>

La sección que continúa es la de “Sobre Nosotros”, la cual muestra información sobre la startup, Bookify, y la aplicación web, Livria. Se visualiza texto importante sobre quiénes somos, así como el logo representativo de cada uno.

<p align="center">
  <img src="https://imgur.com/jEkCPal.png" alt="LPW4" width="500">
</p>

Luego, se llega a la última sección de la landing page, que es “Contáctanos”. En caso que el visitante desee comunicarse con el equipo de Bookify - Livria, puede dejar su información y motivo de contacto. Además, si desea formar parte de este equipo, puede dejar su CV y aplicar para un puesto disponible.

<p align="center">
  <img src="https://imgur.com/Za0rUPs.png" alt="LPW5" width="500">
</p>

A medida que el visitante hizo scroll en la página, se mostraron todas las secciones de la landing page, llegando hasta el pie de página. Este muestra los accesos a las secciones visualizadas anteriormente, así como enlaces a partes legales y de soporte de la plataforma.

### 4.3.2. Landing Page Mock-ups
Los mockups de la landing page de Livria muestran una mayor fidelización de la interfaz final del sitio, integrando los elementos visuales definidos en la guía de estilo. Esta representación busca validar la propuesta estética y funcional de los wireframes en una experiencia clara y atractiva para el usuario.

<p align="center">
  <img src="https://imgur.com/iJv6Hpo.png" alt="LDM1" width="500">
</p>

La pantalla de inicio del mockup de la Landing Page presenta el encabezado con las secciones principales de sitios y el bloque introductorio de la propuesta de Livria, ambos con los colores de la paleta. Incluye un carrusel visual con imágenes sobre lectura digital, comunidad lectora y la tienda física de Livria.

<p align="center">
  <img src="https://imgur.com/REM6Y3h.png" alt="LDM2" width="500">
</p>

La sección de “Servicios” presenta cada tarjeta de información con un color diferente, así como con una imagen respectiva sobre lo que describe la funcionalidad.

<p align="center">
  <img src="https://imgur.com/0v7jV47.png" alt="LDM3" width="500">
</p>

A esta sección, “Sobre Nosotros”, se le agrega color a los bloques que contienen los nombres de la startup y la aplicación, Bookify y Livria, respectivamente.

El mockup de la última sección de la landing page, la cual presenta el formulario de contacto, se visualiza con un color principal de la paleta.

<p align="center">
  <img src="https://imgur.com/SFutwZs.png" alt="LDM4" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/SFutwZs.png" alt="LDM5" width="500">
</p>

El mockup del pie de página muestra los accesos de Navegación, Legal y Soporte con el color azul, así como los logos de las redes sociales de Livria.

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes
Los wireframes de la aplicación web de Livria representan una primera aproximación estructural al diseño de la plataforma, enfocándose en la organización del contenido y la disposición de los elementos clave en cada pantalla. Esta etapa busca definir cómo interactuarán los usuarios con las principales funcionalidades del sistema sin distraer con aspectos estéticos aún no definidos. Al priorizar la usabilidad y claridad en esta fase inicial, los wireframes permiten optimizar la experiencia del usuario y sentar las bases para el desarrollo de un diseño visual coherente y funcional.

<p align="center">
  <img src="https://imgur.com/iFUtlsp.png" alt="WAW1" width="500">
</p>

En primer lugar se tiene a la pantalla de inicio de Livria, la cual muestra elementos principales de la aplicación. Se tiene el header, que posee los accesos a las diferentes secciones de Livria, así como la barra de búsqueda y los botones de cambio de idioma. Asimismo, hay un carrusel que muestra diferentes banners con información, siendo el principal el de “obtener el Plan Comunidad”. A partir de ello, aparecen las primeras sugerencias de las categorías parte del catálogo de Livria.

<p align="center">
  <img src="https://imgur.com/vozygBu.png" alt="WAW2" width="500">
</p>

A continuación, a medida que el usuario va haciendo scroll en la aplicación, le aparecen las siguientes sugerencias de las otras categorías del catálogo de Livria.

<p align="center">
  <img src="https://imgur.com/lvCXiNM.png" alt="WAW3" width="500">
</p>

A medida que el usuario hizo scroll en la aplicación de Livria y se mostraron los géneros literarios que se tiene, llegará al pie de página. Este es similar a aquel colocado en la landing page.

<p align="center">
  <img src="https://imgur.com/molD0z7.png" alt="WAW4" width="500">
</p>

El presente wireframe muestra la sección de “Recomendaciones” de Livria. En esta, aparecen 6 tarjetas con sugerencias que la aplicación brinda en base a los gustos del usuario. 

<p align="center">
  <img src="https://imgur.com/NHGbEPa.png" alt="WAW5" width="500">
</p>

El wireframe de la pantalla de un género literario muestra las obras del catálogo de Livria que se alinean a este criterio. En el área principal, se muestra una cuadrícula de libros disponibles, cada uno con su imagen de portada, nombre, autor y precio. A la derecha, un panel lateral ofrece opciones de filtrado por categoría, orden de visualización, formato e idioma, facilitando una experiencia de búsqueda personalizada y eficiente. Las pantallas de todos los géneros literarios que aparecen en el header siguen este mismo formato.

<p align="center">
  <img src="https://imgur.com/MCTgS5P.png" alt="WAW6" width="500">
</p>

Esta pantalla muestra los resultados de búsqueda para un término específico. En el centro, se despliegan las tarjetas con los libros relacionados al término buscado. Al costado derecho, se encuentra un panel de filtros que permite refinar los resultados por orden de visualización, formato e idioma.

<p align="center">
  <img src="https://imgur.com/FmM2VN5.png" alt="WAW7" width="500">
</p>

El wireframe de “Comunidades” muestra tarjetas con comunidades, mostrando la imagen de portada, el nombre de esta y el botón para ver más. Asimismo, da la opción de crear una nueva comunidad a través del botón grande de la izquierda o del botón pequeño de la esquina superior derecha.

<p align="center">
  <img src="https://imgur.com/m0U5v45.png" alt="WAW8" width="500">
</p>

Al haber seleccionado la opción de “Crear Comunidad”, mediante cualquiera de los botones, aparece un formulario sobreponiéndose a la pantalla anterior. Este pide rellenar información vital para la creación de la nueva comunidad, como lo es el nombre, la categoría y la descripción de la misma, así como una imagen representativa.

<p align="center">
  <img src="https://imgur.com/06n8XtG.png" alt="WAW9" width="500">
</p>

El wireframe de una comunidad en específico muestra cómo se vería al ingresar a una existente o al crear una nueva. Se colocan los detalles en la parte superior y se permite a los usuarios crear una publicación dentro de la comunidad, mostrando los posts a lo largo de la pantalla.

<p align="center">
  <img src="https://imgur.com/ntZj1Tm.png" alt="WAW10" width="500">
</p>

Al hacer clic en una de las publicaciones dentro de la comunidad, se sobrepone el recuadro con los detalles de la publicación y los comentarios respectivos que los usuarios hayan realizado.

<p align="center">
  <img src="https://imgur.com/hO3zCkb.png" alt="WAW11" width="500">
</p>

Por otro lado, se tiene el wireframe de la pantalla de un libro. Este muestra la portada y la sinopsis en la parte izquierda. En lo que resta de la pantalla, muestra detalles como el autor, el idioma, el precio. También se dan las opciones de agregar al carrito, de marcar como interés o desinterés, calificar la lectura con estrellas, y comentar sobre el libro.

<p align="center">
  <img src="https://imgur.com/MDHJu4O.png" alt="WAW12" width="500">
</p>

El wireframe del carrito de compras muestra el panel que se sobrepone a cualquier pantalla mostrando los elementos que se encuentran por comprar, así como el subtotal de la posible compra y un botón para finalizarla.

<p align="center">
  <img src="https://imgur.com/hRi6rCt.png" alt="WAW13" width="500">
</p>

La presente pantalla muestra el inicio del proceso de finalización de compra tras haber presionado el botón en el panel de carrito. Muestra el listado de libros añadidos al carrito, así como un panel con el resumen de costos de la compra.

<p align="center">
  <img src="https://imgur.com/Crr9luP.png" alt="WAW14" width="500">
</p>

Le sigue la pantalla de finalización de compra con el panel de identificación del cliente, donde rellena los campos con sus datos o aquellos de quien será responsable de recibir/recoger el pedido.

<p align="center">
  <img src="https://imgur.com/PrZjj5q.png" alt="WAW15" width="500">
</p>

La tercera pantalla de finalización de compra muestra el panel con los detalles de envío. Se puede seleccionar entre dos opciones: envío a domicilio o recojo en tienda.

<p align="center">
  <img src="https://imgur.com/sNRMaTo.png" alt="WAW16" width="500">
</p>

La última pantalla de finalización de compra muestra el panel que detalla cómo se realizará el pago a través de izipay en una ventana aparte. Asimismo, se pide que se acepten los términos y condiciones de Livria.

<p align="center">
  <img src="https://imgur.com/VKnVzlb.png" alt="WAW17" width="500">
</p>

Este wireframe representa una página de confirmación de compra en Livria. El cuerpo principal muestra un mensaje de agradecimiento por la compra donde también se indica el código de la compra. Al final, hay un botón centrado que permite regresar a la página de inicio.

<p align="center">
  <img src="https://imgur.com/mjrnOBT.png" alt="WAW18" width="500">
</p>

Este wireframe corresponde a la sección de "Cuenta" de Livria. El contenido principal está dividido en tres bloques: a la izquierda, un área con la foto de perfil, nombre de usuario y correo electrónico; en el centro, una sección de "Perfil" con un breve texto descriptivo y otra de "Mis Últimos Pedidos" mostrando el estado de las compras recientes; y a la derecha, un módulo de "Configuración" donde el usuario puede gestionar notificaciones, la visibilidad del perfil, y actualizar su contraseña.

### 4.4.2. Web Applications Wireflow Diagrams
**User Goal para Segmento 1: Estudiantes y jóvenes universitarios**

Como usuario, quiero visualizar recomendaciones personalizadas según mis preferencias de lectura y quiero determinar si una es de mi agrado o no.

*Task Flow:*

<p align="center">
  <img src="https://imgur.com/g9Amery.png" alt="TF1" width="500">
</p>

*Wireflow:*

<p align="center">
  <img src="https://imgur.com/PMR7dO4.png" alt="WF1" width="500">
</p>

Para poder interactuar con las recomendaciones que brinda Livria a cada usuario, se accede, en primer lugar, a esta sección a través del header de la aplicación web. Al presionar “Recomendaciones”, se le redirige al usuario al apartado en el que aparecen sus 6 recomendaciones. Al seleccionar una de ellas, aparece el detalle del libro recomendado. A este, se le puede marcar como interés o desinterés al seleccionar el ícono del bookmark o del negative, respectivamente.

Asimismo, para mejorar las recomendaciones que ofrece Livria, se pueden marcar otros libros. Para ello, desde el inicio de la aplicación —o desde cualquier otra sección— se puede acceder a un libro en específico y marcarle, así como a un libro recomendado, como interés o desinterés al seleccionar el ícono del bookmark o del negative, respectivamente. 

**User Goal para Segmento 2: Lectores casuales y aficionados a la lectura**

Como usuario, quiero conectar con otras personas que compartan mis gustos literarios y ver sus opiniones sobre esos temas en específico.

*Task Flow:*

<p align="center">
  <img src="https://imgur.com/933Tscs.png" alt="TF2" width="500">
</p>

*Wireflow:*

<p align="center">
  <img src="https://imgur.com/xYq6Kuq.png" alt="WF2" width="500">
</p>

Para interactuar con otros usuarios sobre temas específicos, se debe seguir una secuencia de pasos. En primer lugar, desde el inicio de Livria —o desde cualquier otra sección— se debe acceder al apartado de Comunidades al presionar su link en el header. Acto seguido, se mostrarán las variadas comunidades creadas en la aplicación. A partir de ello, el usuario puede elegir entre crear una nueva o unirse a una existente. De elegir la primera opción, deberá completar los campos de información requeridos y, cuando haya creado la comunidad, se le permitirá empezar a publicar sobre el tema elegido. En el caso contrario, podrá tanto crear una nueva publicación como comentar en una preexistente.

Para mejor visualización de los Wireflows de Livria, acceder al siguiente link: https://lucid.app/lucidchart/e1054595-89bd-4b48-922d-b00216bf8e74/edit?viewport_loc=-6918%2C-463%2C15406%2C7161%2C0_0&invitationId=inv_053ea8ae-d81b-4f9f-ba5d-43ab4e59bbba 

### 4.4.3. Web Applications Mock-up

<p align="center">
  <img src="https://imgur.com/DObt6nP.png" alt="WAM1" width="500">
</p>

Este mockup muestra la página inicial de la tienda Livria. En la parte superior se mantiene el encabezado con el logo, barra de búsqueda, accesos rápidos a carrito, tienda, notificaciones, cuenta, y el selector de idioma. Debajo, el menú de navegación ofrece varias categorías. El área principal tiene un banner promocionando el "Plan Comunidad", invitando a los usuarios a unirse para compartir opiniones. Abajo, aparece una sección de "Literatura" donde se muestran las tarjetas con libros destacados en forma de carrusel horizontal, con portadas visibles y sus títulos.

<p align="center">
  <img src="https://imgur.com/N3Z8t3P.png" alt="WAM2" width="500">
</p>

Al seguir haciendo scroll en la aplicación, le aparecen las siguientes sugerencias de las otras categorías del catálogo de Livria.

<p align="center">
  <img src="https://imgur.com/L1FS590.png" alt="WAM3" width="500">
</p>

A medida que el usuario hizo scroll en la aplicación de Livria y se mostraron los géneros literarios que se tiene, llegará al pie de página. Este es similar a aquel colocado en la landing page.

<p align="center">
  <img src="https://imgur.com/qmxRGpJ.png" alt="WAM4" width="500">
</p>

El mockup muestra la página de recomendaciones personalizadas de la tienda de libros Livria. La sección principal presenta libros sugeridos en forma de tarjetas con portada, título, autor y precio. Debajo, un aviso invita a los usuarios a marcar su interés usando íconos de bookmark o de negativo. Finalmente, el pie de página ofrece enlaces de navegación, información legal y soporte.

<p align="center">
  <img src="https://imgur.com/isFtOpL.png" alt="WAM5" width="500">
</p>

El mockup de la pantalla de un género literario en Livria presenta una cuadrícula de libros que coinciden con la temática seleccionada, mostrando para cada obra su portada, título, autor y precio. A la derecha, se incluye un panel lateral con filtros de búsqueda: por categoría, formato, idioma y orden de visualización. Este diseño busca ofrecer una navegación ágil y personalizada. Todas las pantallas de los géneros listados en el menú principal mantienen esta misma estructura visual.

<p align="center">
  <img src="https://imgur.com/FkyFT5d.png" alt="WAM6" width="500">
</p>

El mockup de la pantalla de resultados de búsqueda presenta una cuadrícula de tarjetas con los libros relacionados al término ingresado. A la derecha, un panel de filtros permite ajustar los resultados según el orden de visualización, el formato y el idioma, ofreciendo una experiencia de búsqueda más precisa.

<p align="center">
  <img src="https://imgur.com/tTiij84.png" alt="WAM7" width="500">
</p>

El mockup de la pantalla de "Comunidades" en Livria presenta una cuadrícula de tarjetas, cada una con la imagen de portada, el nombre de la comunidad y un botón para ver más detalles. Además, incluye un botón grande en la parte izquierda y otro pequeño en la esquina superior derecha que permiten crear una nueva comunidad de forma rápida y accesible.

<p align="center">
  <img src="https://imgur.com/dBz8b4B.png" alt="WAM8" width="500">
</p>

El mockup de la función “Crear Comunidad” muestra un formulario superpuesto sobre la pantalla anterior, activado al presionar cualquiera de los botones destinados a esta acción. El formulario solicita datos esenciales para configurar la nueva comunidad, como el nombre, la categoría, una breve descripción y una imagen representativa.

<p align="center">
  <img src="https://imgur.com/U5aOQiD.png" alt="WAM9" width="500">
</p>

El mockup de una comunidad específica en Livria representa la vista al ingresar a una ya existente o recién creada. En la parte superior se muestran los detalles principales de la comunidad, mientras que debajo se habilita un espacio para que los usuarios realicen nuevas publicaciones. Las publicaciones existentes se despliegan a lo largo de la pantalla.

<p align="center">
  <img src="https://imgur.com/TcSfhVl.png" alt="WAM10" width="500">
</p>

El mockup de una publicación dentro de una comunidad muestra un recuadro superpuesto al hacer clic sobre cualquier post. Este recuadro despliega los detalles completos de la publicación junto con los comentarios realizados por otros usuarios, permitiendo una interacción directa y enfocada sin abandonar la pantalla principal de la comunidad.

<p align="center">
  <img src="https://imgur.com/FQztwpi.png" alt="WAM11" width="500">
</p>

El mockup de la pantalla de un libro en Livria presenta, en la parte izquierda, la portada junto a la sinopsis de la obra. A la derecha, se despliegan detalles como el autor, idioma y precio, junto con botones para agregar al carrito, marcar como interés o desinterés, calificar con estrellas y dejar comentarios, facilitando la interacción y decisión de compra del usuario.

<p align="center">
  <img src="https://imgur.com/T7bHt6R.png" alt="WAM12" width="500">
</p>

El mockup del carrito de compras en Livria presenta un panel lateral superpuesto que puede desplegarse desde cualquier pantalla. En él se listan los productos añadidos, mostrando un resumen visual de cada uno, el subtotal de la compra y un botón destacado para finalizar la transacción.

<p align="center">
  <img src="https://imgur.com/F9FYiBP.png" alt="WAM13" width="500">
</p>

El mockup de la pantalla de inicio del proceso de compra en Livria se activa tras presionar el botón de finalizar en el carrito. En esta vista se muestra el listado completo de libros añadidos y, junto a ellos, un panel lateral con el resumen detallado de los costos totales de la compra.

<p align="center">
  <img src="https://imgur.com/F5mjfdR.png" alt="WAM14" width="500">
</p>

El mockup de la pantalla de finalización de compra en Livria incluye un panel destinado a la identificación del cliente. En esta etapa, el usuario debe completar un formulario con sus datos personales o los de la persona responsable de recibir o recoger el pedido, como parte del proceso previo al pago.

<p align="center">
  <img src="https://imgur.com/TUESiDm.png" alt="WAM15" width="500">
</p>

El mockup de la tercera pantalla del proceso de finalización de compra en Livria presenta un panel con las opciones de envío. El usuario puede elegir entre dos modalidades: envío a domicilio o recojo en tienda, adaptando así la entrega según su preferencia.

<p align="center">
  <img src="https://imgur.com/Cv36EFc.png" alt="WAM16" width="500">
</p>

El mockup de la última pantalla del proceso de finalización de compra en Livria muestra un panel con las instrucciones para realizar el pago mediante Izipay, el cual se completará en una ventana externa. Además, se solicita al usuario aceptar los términos y condiciones de Livria antes de finalizar la transacción.

<p align="center">
  <img src="https://imgur.com/H6Zj7GK.png" alt="WAM17" width="500">
</p>

El mockup muestra la pantalla final de confirmación de compra en Livria. En el centro se despliega un recuadro que agradece al usuario por su compra. Dentro del recuadro, aparece un texto confirmando que la compra fue exitosa, indicando que el usuario recibirá más información al correo registrado. También se muestra un código de compra para referencia. Debajo, hay un botón que invita al usuario volver a la página principal de la tienda.

<p align="center">
  <img src="https://imgur.com/vFeqfv9.png" alt="WAM18" width="500">
</p>

El mockup de la sección "Cuenta" en Livria organiza el contenido en tres bloques principales. A la izquierda, se muestra la foto de perfil, el nombre de usuario y el correo electrónico. En el centro, se encuentran dos apartados: "Perfil", con un breve texto descriptivo, y "Mis Últimos Pedidos", donde se visualiza el estado de las compras recientes. A la derecha, un módulo de "Configuración" permite al usuario gestionar las notificaciones, la visibilidad de su perfil y actualizar su contraseña.

### 4.4.4. Web Applications User Flow Diagrams

**Segmento 1: Estudiantes y jóvenes universitarios**

* Como usuario, quiero poder realizar la búsqueda de libros en base a diferentes criterios y obtener resultados relacionados.

<p align="center">
  <img src="https://imgur.com/HtJIFCt.png" alt="UF1" width="500">
</p>

* Como usuario, quiero poder navegar rápidamente entre categorías y géneros de libros.

<p align="center">
  <img src="https://imgur.com/sxKVRBc.png" alt="UF2" width="500">
</p>

**Segmento 2: Lectores casuales y aficionados a la lectura**

* Como usuario, quiero poder expresarme mediante mi perfil y tener la capacidad de editarlo en cualquier momento.

<p align="center">
  <img src="https://imgur.com/PMLCTCY.png" alt="UF3" width="500">
</p>

* Como usuario, quiero poder realizar compras desde la plataforma de manera segura y bien explicada.

<p align="center">
  <img src="https://imgur.com/yoVSe5b.png" alt="UF4" width="500">
</p>

## 4.5. Web Applications Prototyping
Con el objetivo de evaluar y perfeccionar la accesibilidad y la experiencia de usuario antes del desarrollo final, se elaboró un prototipo interactivo centrado en la navegación web. Este modelo funcional permite simular de forma integral el recorrido del usuario dentro del sitio, facilitando la exploración directa de sus secciones, elementos y flujos de interacción tal como se espera en su versión final online.

El prototipo fue diseñado siguiendo principios de arquitectura de la información clara, jerarquía visual lógica y diseño inclusivo, priorizando siempre la facilidad de uso. Se cuidó que cada componente respete estándares de usabilidad y coherencia visual, lo que favorece una navegación fluida e intuitiva.

A partir de maquetas de alta fidelidad y criterios de usabilidad previamente definidos, esta versión navegable actúa como una fiel representación de la futura interfaz web. Así, se convierte en una herramienta clave para validar decisiones de diseño, detectar posibles fricciones y garantizar una experiencia consistente y accesible desde el navegador.

Video explicativo: https://youtu.be/KXpBorl-CXY

Link al prototipo interactivo: https://www.figma.com/proto/eKCqZoU0IF7n3wNTA8kuZc/livria?page-id=192%3A596&node-id=255-816&p=f&viewport=-121%2C-24%2C0.12&t=bikOaC0wuxQpGsNk-1&scaling=min-zoom&content-scaling=fixed 

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram

<p align="center">
  <img src="https://imgur.com/bM6CYx4.png" alt="ContextD" width="500">
</p>

### 4.6.2. Software Architecture Container Diagram

<p align="center">
  <img src="https://imgur.com/LufYExk.png" alt="ContainerD" width="500">
</p>

### 4.6.3. Software Architecture Components Diagram

<p align="center">
  <img src="https://imgur.com/LufYExk.png" alt="ComponentsD" width="500">
</p>

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagram

<p align="center">
  <img src="https://imgur.com/LCfcMJU.png" alt="Class" width="500">
</p>

### 4.7.2. Class Dictionary
* USUARIO: Representa a cualquier persona registrada en la plataforma. Puede leer, comprar, valorar libros, interactuar en comunidades y gestionar su perfil.
* LIBRO: Entidad que contiene toda la información sobre los libros disponibles en Livria, incluyendo su autor, precio, formato y valoraciones.
* AUTOR: Representa a los escritores de los libros. Puede listar sus obras y está asociado a múltiples libros.
* VALORACION: Permite a los usuarios calificar y dejar una reseña sobre un libro. Está vinculada tanto al usuario como al libro.
* FAVORITO: Registra libros marcados como favoritos por un usuario. Facilita el acceso rápido a lecturas preferidas.
* COMENTARIO: Contiene los mensajes que un usuario deja en una publicación dentro de la comunidad.
* PUBLICACION: Representa una publicación dentro de la comunidad, creada por un usuario. Puede incluir texto y archivos multimedia.
* MULTIMEDIA: Asocia archivos multimedia (como imágenes o videos) a una publicación. Guarda información sobre el tipo y tamaño del archivo.
* COMUNIDAD: Agrupa a los usuarios según intereses comunes. Permite la interacción social a través de publicaciones.
* Notificacion: Mensajes enviados a los usuarios para informar sobre eventos importantes, actualizaciones o interacciones relevantes.
* PEDIDO: Registro de compra de libros. Contiene información del costo, fecha, estado y está asociado al usuario.
* DETALLE_PEDIDO: Elemento que desglosa cada libro dentro de un pedido, incluyendo cantidad y vínculo con el pedido y el usuario.
* ENTREGA: Representa el proceso de entrega de un pedido físico. Incluye información del repartidor, fecha y estado.
* REPARTIDOR: Persona encargada de realizar entregas. Tiene datos personales como nombre y teléfono.
* PAGO: Registra información sobre pagos realizados, como monto, fecha y usuario asociado.
* SUSCRIPCION: Vinculada al usuario, define el tipo de plan y sus beneficios. habilita funciones exclusivas.

## 4.8. Database Design
### 4.8.1. Database Diagram

<p align="center">
  <img src="https://imgur.com/qBScqXS.png" alt="Database" width="500">
</p>

URL: https://lucid.app/lucidchart/34ab5908-200e-4dc9-955d-49052617f49a/edit?viewport_loc=-384%2C-73%2C3906%2C1898%2CHWEp-vi-RSFO&invitationId=inv_881117db-e3c0-4cb4-b4b3-de363adf0664
