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
