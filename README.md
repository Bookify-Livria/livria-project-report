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
| 2.0 (TP)    | 15/05/25    | - Argomedo Camacho, Jhosep Jamil <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián <br> - Castillo Garay, Ainhoa Lucía <br> - Sulca Silva, Melisa Geraldine <br> | Correciones de la TB1 <br> Capítulo V: Product Implementation, Validation & Deployment <br> Frontend de Livria |
| 3.0 (TB2)    | 21/05/25    | - Argomedo Camacho, Jhosep Jamil <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián <br> - Castillo Garay, Ainhoa Lucía <br> - Sulca Silva, Melisa Geraldine <br> | Correciones del TP <br> Capítulo V: Product Implementation, Validation & Deployment <br> Backend de Livria |
| 4.0 (TF)    | 21/05/25    | - Argomedo Camacho, Jhosep Jamil <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián <br> - Castillo Garay, Ainhoa Lucía <br> - Sulca Silva, Melisa Geraldine <br> | Correciones del TB2 <br> Capítulo V: Product Implementation, Validation & Deployment <br> Integración del frontend con el backend <br> Implementación del bounded context IAM <br> Mejoras en el Backend de Livria |

# Project Report Collaboration Insights

Repositorio donde está el project report: https://github.com/Bookify-Livria/livria-project-report

Para la elaboración del informe, se utilizó Google Docs como plataforma de trabajo colaborativo, y posteriormente se migró el contenido al archivo README del repositorio principal. En esta entrega, el README ha sido actualizado para incluir los avances del Sprint 3 y los resultados de las entrevistas de validación de producto, las cuales fueron fundamentales para llevar a cabo las evaluaciones heurísticas.

<p align="center">
  <img src="https://imgur.com/sWRIMA3.png" alt="PRCI" width="500">
</p>

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

- [CAPÍTULO 5: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT](#capítulo-5-product-implementation-validation-&-deployment)
  * [5.1. Software Configuration Management](#51-software-configuration-management)
    + [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    + [5.1.2. Source Code Management](#512-source-code-management)
    + [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    + [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  * [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    + [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning](#5211-sprint-planning)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3 Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    + [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning](#5221-sprint-planning)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3 Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
    + [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning](#5231-sprint-planning)
      - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3 Sprint Backlog 3](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
    + [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1. Sprint Planning](#5241-sprint-planning)
      - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
      - [5.2.4.3 Sprint Backlog 4](#5243-sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
  * [5.3. Validation Interviews](#53-validation-interviews)
    + [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    + [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    + [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  * [5.4. Video About-the-Product](#54-video-about-the-product)

- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
  
- [Video About-the-Team](#video-about-the-team)
  
- [Bibliografía](#bibliografía)
  
- [Anexos](#anexos)

# Student Outcome

ABET - EAC - Student Outcome 5
Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

**TB1**

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|:------------------------|:-------------------------|:-----------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | - **Argomedo Camacho, Jhosep Jamil (TB1)**: <br> Desarrollo de la landing page, sección hero, sección de suscripción y barra de navegación. Desarrollo del informe (varios capítulos) <br> - **Binda Arbañil, Marcelo Alejandro**: <br> Desarrollo de la landing page, sección de servicios. Desarrollo del informe (varios capítulos) <br> - **Borja Molina, Gabriel Sebastián (TB1)**: <br> Desarrollo de la landing page, sección de “sobre nosotros”. Desarrollo del informe (varios capítulos) <br> - **Castillo Garay, Ainhoa Lucía (TB1)**: <br> Desarrollo de la landing page: revisión, resolución de problemas, y mejoramiento de diseño responsivo. Desarrollo del informe (varios capítulos) <br> - **Sulca Silva, Melisa Geraldine (TB1)**: <br> Desarrollo de la landing page: sección de contacto y pie de página. Desarrollo del informe (varios capítulos) <br>  | El equipo de Livria ha demostrado una destacada capacidad para trabajar de manera colaborativa y ejercer un liderazgo compartido a lo largo del proyecto. Desde la definición del perfil de la startup hasta el diseño del producto, se aprecia una organización sólida y una distribución efectiva de roles, donde cada integrante aportó su conocimiento especializado. La implementación de metodologías como Lean UX y Domain-Driven Design, sumada a la planificación de la arquitectura de software y el diseño de la interfaz, refleja una visión alineada y un liderazgo distribuido a través de todas las etapas del proceso. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | - Argomedo Camacho, Jhosep Jamil (TB1) <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián (TB1) <br> - Castillo Garay, Ainhoa Lucía (TB1) <br> - Sulca Silva, Melisa Geraldine (TB1) | El desarrollo de Livria también resalta la creación de un entorno de trabajo cooperativo y abierto a la participación activa. El profundo trabajo de recopilación y análisis de requisitos, a través de entrevistas, técnicas de needfinding y la elaboración de user personas, evidencia un compromiso genuino por entender a los usuarios y responder a sus necesidades reales. La definición clara de los objetivos del producto y de los segmentos de usuarios objetivo muestra una planificación estratégica sólida. La organización de tareas se ve plasmada en la estructuración del documento, la construcción del Product Backlog y la preparación del primer sprint enfocado en el desarrollo de la landing page. El progreso alcanzado en la fase inicial de implementación reafirma la capacidad del equipo para convertir la planificación en resultados concretos. |

**TP**

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|:------------------------|:-------------------------|:-----------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | - **Argomedo Camacho, Jhosep Jamil (TP)**: <br> Modificación y agregación de nueva vista en la landing page. Desarrollo de la lógica de vista de comunidades. Redacción del sprint 2  <br> - **Binda Arbañil, Marcelo Alejandro**: <br> Desarrollo e implementación de secciones de la aplicación web (Recomendaciones, Libros, comunidades y suscripción) <br> - **Borja Molina, Gabriel Sebastián (TP)**: <br> Desarrollo e implementación de secciones de la aplicación web (cuenta de usuario) <br> - **Castillo Garay, Ainhoa Lucía (TP)**: <br> Desarrollo e implementación de secciones de la aplicación web (Inicio, comunidades, carrito de compras, ordenes, notificaciones) <br> - **Sulca Silva, Melisa Geraldine (TP)**: Colaboración en diversas secciones (notificaciones, inicio y revisión de problemas). Redacción del sprint 2 <br>  | **Argomedo Camacho, Jhosep Jamil** <br> Demostró habilidades de liderazgo al coordinar las tareas del equipo durante el Sprint 2, fomentando una toma de decisiones colectiva para optimizar el flujo de trabajo en las funcionalidades de 'Comunidad'. <br> Participó activamente en la gestión del equipo, asegurando que cada integrante tuviera claridad sobre sus responsabilidades en las historias de usuario asignadas para el segundo sprint. <br> <br> **Binda Arbañil, Marcelo Alejandro** <br> Desempeñó un rol clave en la definición de prioridades del Sprint 2, guiando al equipo hacia el cumplimiento de los objetivos establecidos para las funcionalidades de 'Home y categorías'. <br> Mantuvo una comunicación constante con los miembros del equipo para alinear los esfuerzos hacia un propósito común, asegurando que las historias de usuario se implementaran correctamente. <br> <br> **Borja Molina, Gabriel Sebastián** <br> Contribuyó al liderazgo del equipo al proponer estrategias para mejorar la eficiencia en el desarrollo de las funcionalidades del Sprint 2, enfocadas en diferentes secciones, priorizando el registro, logueo y configuración de perfil. <br> Asumió responsabilidades adicionales para apoyar a sus compañeros en la implementación de funcionalidades críticas. <br> <br> **Castillo Garay, Ainhoa Lucía** <br> Se destacó como líder en la organización de tareas visuales y diseño para el Sprint 2, asegurando que los entregables cumplieran con los estándares de calidad en la interfaz de usuario. E implementando la sección de 'Home'. <br> Facilitó la integración de nuevas ideas en el proyecto mediante una comunicación abierta y efectiva con el equipo, promoviendo un diseño intuitivo y accesible. <br> <br> **Sulca Silva, Melisa Geraldine** <br> <br> Lideró iniciativas para optimizar la experiencia del usuario durante el Sprint 2, promoviendo soluciones innovadoras en el diseño de interfaces para las funcionalidades de notificaciones. <br> Colaboró en la definición de estrategias para mejorar la coordinación y colaboración dentro del equipo, asegurando que las metas del sprint fueran alcanzadas. |
**Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | - Argomedo Camacho, Jhosep Jamil (TP) <br> - Binda Arbañil, Marcelo Alejandro <br> - Borja Molina, Gabriel Sebastián (TP) <br> - Castillo Garay, Ainhoa Lucía (TP) <br> - Sulca Silva, Melisa Geraldine (TP) | **Argomedo Camacho, Jhosep Jamil** <br> Fomentó un ambiente inclusivo durante el Sprint 2, promoviendo la participación activa de todos los miembros del equipo en las decisiones del proyecto, especialmente en las funcionalidades de 'Comunidades'. <br> Contribuyó a la planificación de tareas, asegurando que los objetivos fueran alcanzados en cada sprint. <br> <br> **Binda Arbañil, Marcelo Alejandro** <br> Facilitó la colaboración efectiva al establecer metas claras y distribuir tareas de acuerdo a las fortalezas del equipo durante el Sprint 2, promoviendo el éxito en diferentes funcionalidades. <br> Participó en la creación de un entorno positivo y motivador que impulsó el rendimiento del equipo durante el segundo sprint, asegurando que las secciones principales sean implementadas de manera correcta. <br> <br> **Borja Molina, Gabriel Sebastián** <br> Apoyó a sus compañeros en la planificación y ejecución de tareas del Sprint 2, promoviendo un trabajo colaborativo y eficiente para las funcionalidades principalmente de registro. <br> Contribuyó a la creación de un entorno inclusivo mediante la integración de ideas diversas en el desarrollo del proyecto. <br> <br> **Castillo Garay, Ainhoa Lucía** <br> Facilitó la comunicación entre los miembros del equipo, asegurando que todos comprendieran los objetivos del Sprint 2 para las funcionalidades y secciones principales. <br> Ayudó en la organización de tareas y seguimiento de los avances para cumplir con los plazos establecidos durante el segundo sprint. <br> <br> **Sulca Silva, Melisa Geraldine** <br> Promovió un entorno de colaboración inclusiva al integrar nuevas perspectivas en el diseño de soluciones para las funcionalidades del Sprint 2. <br> Colaboró en la planificación de tareas para garantizar que los objetivos del proyecto fueran alcanzados de manera eficiente. |

**TB2**

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|:------------------------|:-------------------------|:-----------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | - **Argomedo Camacho, Jhosep Jamil (TB2)**: <br>   - Desarrollo e implementación de la base de datos <br>   - Interfaz de administrador (Dashboard) <br>   - Creación y gestión de servidor de base de datos (Azure) <br>   - Mejoramiento de la landing page <br> - **Binda Arbañil, Marcelo Alejandro (TB2)**: <br>   - Desarrollo e implementación de los bounded Context <br> - **Borja Molina, Gabriel Sebastián (TB2)**: <br>   - Desarrollo e implementación de los Bounded Context <br> - **Castillo Garay, Ainhoa Lucía (TB2)**: <br>   - Corrección del frontend <br>   - Desarrollo de nuevas funcionalidades <br> - **Sulca Silva, Melisa Geraldine (TB2)**: <br>   - Internalización de la interfaz de administrador (Dashboard) <br>   - Redacción del sprint 3 (informe) | **Argomedo Camacho, Jhosep Jamil** <br> Jhosep coordinó eficazmente las tareas técnicas, gestionando la base de datos y el dashboard. Su liderazgo fue clave para asegurar una integración exitosa entre las distintas partes del proyecto. <br> <br> **Binda Arbañil, Marcelo Alejandro** <br> Marcelo lideró la implementación de los bounded contexts, optimizando la estructura del proyecto y promoviendo un enfoque claro y organizado dentro del equipo. <br> <br> **Borja Molina, Gabriel Sebastián** <br> Gabriel desempeñó un papel clave en la implementación de bounded contexts, garantizando una distribución lógica de las tareas y una colaboración fluida entre los miembros del equipo. <br> <br> **Castillo Garay, Ainhoa Lucía** <br> Ainhoa lideró las mejoras del frontend, asegurando que las nuevas funcionalidades se integraran de forma coherente, y promovió la colaboración en las decisiones de diseño. <br> <br> **Sulca Silva, Melisa Geraldine** <br> Melisa destacó en la planificación y documentación del proyecto, asegurando que el equipo mantuviera una visión clara y coherente, mientras promovía un entorno inclusivo. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | - Argomedo Camacho, Jhosep Jamil (TB2) <br> - Binda Arbañil, Marcelo Alejandro (TB2) <br> - Borja Molina, Gabriel Sebastián (TB2) <br> - Castillo Garay, Ainhoa Lucía (TB2) <br> - Sulca Silva, Melisa Geraldine (TB2) | **Argomedo Camacho, Jhosep Jamil** <br> Jhosep facilitó un entorno inclusivo, distribuyendo tareas de manera equitativa y asegurando que todos comprendieran los objetivos del proyecto, lo que permitió un desarrollo fluido. <br> <br> **Binda Arbañil, Marcelo Alejandro** <br> Marcelo estableció metas claras y distribuyó tareas según las fortalezas del equipo, lo que permitió avanzar eficazmente en el desarrollo del proyecto y alcanzar los objetivos establecidos. <br> <br> **Borja Molina, Gabriel Sebastián** <br> Gabriel apoyó en la planificación de tareas y promovió un entorno colaborativo, asegurando que los objetivos del proyecto se alcanzaran sin dificultades, con un enfoque inclusivo. <br> <br> **Castillo Garay, Ainhoa Lucía** <br> Ainhoa contribuyó a la organización del trabajo, manteniendo una comunicación constante dentro del equipo y asegurando que todos los objetivos del proyecto fueran cumplidos eficientemente. <br> <br> **Sulca Silva, Melisa Geraldine** <br> Melisa promovió un entorno inclusivo, integrando perspectivas diversas y manteniendo una planificación clara, lo que permitió que el equipo avanzara hacia los objetivos de manera coordinada. |

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
|           |   Amenazas |   La amenaza más prominente para Livria es la acaparación de mercado por parte de competidores más grandes y con más poder capital, ya que, si estas empresas logran captar a nuestros clientes potenciales, será muy dificultoso llegar a establecernos en el mercado.  |   La principal amenaza para Crisol es la aparición de un competidor más grande y con mayor alcance que cuente con una oferta similar y llegue a reemplazarlos, ya sea por tener precios más accesibles o mayor variedad de obras en su repertorio. |   Una de las amenazas más destacables para Ibero Librerías es la aparición de competidores con un rubro similar que ofrezcan más alternativas y un acceso más rápido a los libros solicitados por sus clientes, ya sea mediante una mayor cantidad de locales o la venta de libros digitales  |   Una amenaza considerable para Communitas es el acaparamiento de su nicho por una marca más grande y con mayor presupuesto, mediante la apropiación de su estilo y modelo de negocio, apelando a un mayor volumen de público y eventualmente ocupando su rubro en el mercado.  |


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

---
### User Story: US35

| **User Story ID** | US35 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Obtener todos los libros |
| **Description** | Como administrador, quiero obtener todos los libros disponibles en la base de datos para realizar un seguimiento de los productos y gestionarlos eficientemente. |
| **Acceptance Criteria #1** | **Escenario 1: Ver todos los libros**<br>Dado que el administrador accede a la base de datos,<br>Cuando consulta los libros,<br>Entonces se muestra la lista completa de libros disponibles en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Filtro de libros por categoría**<br>Dado que hay muchos libros,<br>Y el administrador quiere filtrar los libros,<br>Cuando el administrador consulta con un filtro específico (categoría, autor o disponibilidad),<br>Entonces el sistema recupera y muestra solo los libros que coinciden con el filtro seleccionado. |

---
### User Story: US36

| **User Story ID** | US36 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Obtener detalles de un libro |
| **Description** | Como administrador, quiero ver los detalles completos de un libro en la base de datos para poder gestionarlo adecuadamente. |
| **Acceptance Criteria #1** | **Escenario 1: Ver detalles del libro**<br>Dado que el administrador consulta un libro específico,<br>Cuando lo selecciona,<br>Entonces se muestra toda la información relacionada con ese libro en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Ver disponibilidad**<br>Dado que el administrador ve los detalles,<br>Cuando consulta la sección de disponibilidad,<br>Entonces se muestra el estado actual del libro. |

---
### User Story: US37

| **User Story ID** | US37 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Crear una reseña de un libro |
| **Description** | Como administrador, quiero gestionar las reseñas que los usuarios crean para los libros, permitiendo que se guarden en la base de datos. |
| **Acceptance Criteria #1** | **Escenario 1: Crear una nueva reseña**<br>Dado que el administrador ha recibido una reseña de un usuario,<br>Cuando el sistema guarda la reseña en la base de datos automáticamente,<br>Entonces la reseña se asocia al libro correspondiente en la base de datos y es visible para los usuarios. |
| **Acceptance Criteria #2** | **Escenario 2: Validación automática de reseña**<br>Dado que el administrador supervisa las reseñas que se ingresan al sistema,<br>Cuando el sistema detecta que una reseña no cumple con los requisitos de formato o contenido,<br>Entonces el sistema notifica al administrador sobre el error para que el contenido no válido no sea publicado. |

---
### User Story: US38

| **User Story ID** | US38 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Obtener todas las reseñas de un libro |
| **Description** | Como administrador, quiero acceder a todas las reseñas de un libro para gestionarlas desde el backend. |
| **Acceptance Criteria #1** | **Escenario 1: Ver todas las reseñas**<br>Dado que el administrador consulta las reseñas de un libro,<br>Cuando las consulta,<br>Entonces se muestran todas las reseñas almacenadas en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Ordenar reseñas por fecha**<br>Dado que el administrador consulta las reseñas,<br>Cuando las ordena por fecha,<br>Entonces las reseñas se organizan de la más reciente a la más antigua. |

---
### User Story: US39

| **User Story ID** | US39 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Agregar un libro al carrito |
| **Description** | Como administrador, quiero gestionar la adición de libros al carrito de compra para realizar un seguimiento del proceso de compra. |
| **Acceptance Criteria #1** | **Escenario 1: Agregar libro al carrito**<br>Dado que el usuario agrega un libro,<br>Cuando se realiza la acción,<br>Entonces el libro se almacena en el carrito del usuario en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Confirmar adición al carrito**<br>Dado que el libro se ha agregado,<br>Cuando el usuario consulta su carrito,<br>Entonces el libro aparece correctamente con su cantidad y precio. |

---
### User Story: US40

| **User Story ID** | US40 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Gestión de un pedido |
| **Description** | Como administrador, quiero gestionar la creación de pedidos para que los usuarios puedan finalizar sus compras. |
| **Acceptance Criteria #1** | **Escenario 1: Crear un pedido**<br>Dado que un usuario ha agregado productos al carrito,<br>Cuando finaliza la compra,<br>Entonces se genera un pedido y se almacena en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Ver confirmación de pedido**<br>Dado que el pedido ha sido realizado,<br>Cuando se guarda,<br>Entonces el sistema muestra un mensaje de éxito y asigna un código de pedido único. |

---
### User Story: US41

| **User Story ID** | US41 |
|-------------------|------|
| **Epic ID** | EP09 |
| **Title** | Ver detalles de un pedido |
| **Description** | Como administrador, quiero poder ver los detalles de un pedido para gestionar el envío y los pagos. |
| **Acceptance Criteria #1** | **Escenario 1: Ver resumen del pedido**<br>Dado que el administrador consulta un pedido,<br>Cuando lo selecciona,<br>Entonces se muestran los detalles del pedido, como los libros comprados y el estado. |
| **Acceptance Criteria #2** | **Escenario 2: Ver estado de la entrega**<br>Dado que el administrador consulta un pedido,<br>Cuando observa su estado,<br>Entonces se muestra el estado actual del envío (en proceso, enviado, entregado). |

---
### User Story: US42

| **User Story ID** | US42 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Obtener todas las comunidades |
| **Description** | Como administrador, quiero acceder a la lista completa de comunidades para tener un control centralizado de las comunidades de la plataforma. |
| **Acceptance Criteria #1** | **Escenario 1: Ver todas las comunidades**<br>Dado que el administrador consulta las comunidades,<br>Cuando accede a ellas,<br>Entonces se muestra una lista completa de las comunidades en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Buscar comunidad específica**<br>Dado que el administrador desea encontrar una comunidad,<br>Cuando realiza la búsqueda,<br>Entonces se muestran los resultados correspondientes. |

---
### User Story: US43

| **User Story ID** | US43 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Gestión de creación de una comunidad |
| **Description** | Como administrador, quiero gestionar la creación automática de comunidades por parte de los usuarios y almacenarlas correctamente en la base de datos. |
| **Acceptance Criteria #1** | **Escenario 1: Registrar comunidad creada por el usuario**<br>Dado que un usuario ha creado una comunidad,<br>Cuando el usuario envía la información de la comunidad creada,<br>Entonces el sistema valida los datos y almacena esta información automáticamente en la base de datos, asignando un ID único a la comunidad. |
| **Acceptance Criteria #2** | **Escenario 2: Confirmación automática de creación de comunidad**<br>Dado que el sistema ha registrado correctamente una nueva comunidad creada por un usuario,<br>Cuando la comunidad es registrada en la base de datos,<br>Entonces el sistema genera una confirmación automática que es enviada al usuario que creó la comunidad. |

---
### User Story: US44

| **User Story ID** | US44 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Publicación en una comunidad |
| **Description** | Como administrador, quiero gestionar las publicaciones dentro de las comunidades para asegurarnos de que sean válidas y se guarden en la base de datos. |
| **Acceptance Criteria #1** | **Escenario 1: Crear publicación en comunidad**<br>Dado que un usuario ha creado una publicación dentro de una comunidad,<br>Cuando el sistema guarda la publicación en la base de datos,<br>Entonces la publicación se asocia correctamente a la comunidad y es visible para los miembros. |
| **Acceptance Criteria #2** | **Escenario 2: Verificación de contenido de publicación**<br>Dado que el sistema recibe una publicación de un usuario,<br>Cuando la publicación se envía al backend para ser procesada,<br>Entonces el administrador verifica que la publicación cumpla con las reglas y que no haya contenido vacío no permitido; si lo hay, se elimina la publicación después de unos minutos. |

---
### User Story: US45

| **User Story ID** | US45 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Obtener todos los usuarios |
| **Description** | Como administrador, quiero poder consultar todos los usuarios registrados para gestionar su acceso y actividad. |
| **Acceptance Criteria #1** | **Escenario 1: Ver lista de usuarios (clientes)**<br>Dado que el administrador accede a la lista de usuarios de tipo cliente,<br>Cuando consulta los datos,<br>Entonces se muestra la lista completa de usuarios. |
| **Acceptance Criteria #2** | **Escenario 2: Búsqueda de usuario (cliente)**<br>Dado que el administrador quiere buscar un usuario específico,<br>Cuando ingresa el nombre,<br>Entonces se muestran los resultados correspondientes. |

---
### User Story: US46

| **User Story ID** | US46 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Gestión de creación de un nuevo usuario |
| **Description** | Como administrador, quiero gestionar la creación de nuevos usuarios para que puedan acceder y participar en la plataforma. |
| **Acceptance Criteria #1** | **Escenario 1: Creación automática de un nuevo usuario**<br>Dado que un usuario se ha registrado a través del formulario de registro,<br>Cuando el usuario envía sus datos correctamente,<br>Entonces el sistema automáticamente registra al nuevo usuario en la base de datos y le asigna un ID único. |
| **Acceptance Criteria #2** | **Escenario 2: Validación automática de datos**<br>Dado que el usuario ha enviado un formulario con datos incompletos o inválidos,<br>Cuando el sistema detecta que faltan campos obligatorios o los datos no son válidos,<br>Entonces el sistema bloquea la creación del usuario, muestra un mensaje de error e indica los campos faltantes. |

---
### User Story: US47

| **User Story ID** | US47 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Eliminar un usuario |
| **Description** | Como administrador, quiero poder eliminar un usuario que ya no utilizará la plataforma, para mantener la base de datos actualizada. |
| **Acceptance Criteria #1** | **Escenario 1: Eliminar usuario**<br>Dado que el administrador selecciona un usuario para eliminar,<br>Cuando confirma,<br>Entonces el usuario es eliminado de la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Confirmación de eliminación**<br>Dado que el administrador ha confirmado la eliminación,<br>Cuando el sistema elimina el usuario de la base de datos,<br>Entonces se evidencia que ya no existe ese usuario en la base de datos. |

---
### User Story: US48

| **User Story ID** | US48 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Gestión de creación de una notificación |
| **Description** | Como administrador, quiero poder crear y enviar notificaciones a los usuarios para mantenerlos informados de actualizaciones importantes. |
| **Acceptance Criteria #1** | **Escenario 1: Notificación automática cuando un usuario agrega un libro al carrito de compras**<br>Dado que un usuario agrega un libro al carrito de compras,<br>Cuando el sistema registra esta acción,<br>Entonces automáticamente se crea una notificación para enviar al usuario informándole que el libro ha sido agregado al carrito. |
| **Acceptance Criteria #2** | **Escenario 2: Notificación automática cuando un usuario se une a una comunidad**<br>Dado que un usuario se une a una comunidad,<br>Cuando el sistema registra la acción de unión,<br>Entonces automáticamente se envía una notificación a todos los miembros de la comunidad informando sobre la nueva incorporación. |

---
### User Story: US49

| **User Story ID** | US49 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Gestión de asignación de favorito |
| **Description** | Como administrador, quiero poder ver los detalles de la lista de un usuario en particular y modificarla para mantener control sobre las relaciones entre clientes y favoritos. |
| **Acceptance Criteria #1** | **Escenario 1: Asignación de favorito desde vista de administrador**<br>Dado que el administrador selecciona un usuario al que agregar un favorito,<br>Cuando registre la id de un libro y confirme la acción,<br>Entonces automáticamente se creará una tabla de relación entre el usuario y el libro asignado como favorito. |
| **Acceptance Criteria #2** | **Escenario 2: Eliminación de favorito desde vista de administrador**<br>Dado que el administrador selecciona un usuario al que eliminar un favorito,<br>Cuando registre la id de un libro asignado previamente como favorito y confirme la acción,<br>Entonces automáticamente se eliminará una tabla de relación entre el usuario y el libro asignado como favorito. |
| **Acceptance Criteria #3** | **Escenario 3: Usuario asigna un favorito desde la plataforma**<br>Dado que un usuario se encuentra en la página individual de un libro,<br>Cuando realice la operación de asignación de favorito mediante el botón designado,<br>Entonces automáticamente se creará una tabla de relación entre el usuario y el libro asignado como favorito. |
| **Acceptance Criteria #4** | **Escenario 4: Usuario elimina un favorito desde la plataforma**<br>Dado que un usuario se encuentra en la página individual de un libro,<br>Cuando realice la operación de eliminación de favorito mediante el botón designado,<br>Entonces automáticamente se eliminará la tabla de relación entre el usuario y el libro asignado como favorito. |

---
### User Story: US50

| **User Story ID** | US50 |
|-------------------|------|
| **Epic ID** | EP10 |
| **Title** | Creación de recomendaciones en base a favoritos |
| **Description** | Como administrador, quiero poder generar de manera automática recomendaciones para cada usuario en base a sus libros favoritos para mejorar la experiencia del usuario. |
| **Acceptance Criteria #1** | **Escenario 1: Generación de recomendación**<br>Dado que el usuario ha asignado libros como favoritos previamente,<br>Cuando confirme la operación de generar recomendaciones,<br>Entonces automáticamente se recomendarán libros en base a los géneros de sus libros favoritos. |

---
### User Story: US51

| **User Story ID** | US51 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Acceso rápido a las secciones del sistema desde el Dashboard |
| **Description** | Como administrador, quiero tener acceso rápido a las principales secciones del sistema desde el home del dashboard, para poder acceder a la gestión libros, pedidos, inventarios, estadísticas y configuraciones de manera rápida. |
| **Acceptance Criteria #1** | **Escenario 1: Acceso a “Books” desde el Dashboard**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando el administrador hace clic en el botón de "Books" en la sección de “Quick Actions”,<br>Entonces el sistema redirige al administrador a la sección de libros. |
| **Acceptance Criteria #2** | **Escenario 2: Acceso a “Orders” desde el Dashboard**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando el administrador hace clic en el botón de "Orders" en la sección de “Quick Actions”,<br>Entonces el sistema redirige al administrador a la sección de pedidos. |
| **Acceptance Criteria #3** | **Escenario 3: Acceso a “Inventory” desde el Dashboard**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando el administrador hace clic en el botón de "Inventory" en la sección de “Quick Actions”,<br>Entonces el sistema redirige al administrador a la sección de inventarios. |
| **Acceptance Criteria #4** | **Escenario 4: Acceso a “Stadistics” desde el Dashboard**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando el administrador hace clic en el botón de "Statistics" en la sección de “Quick Actions”,<br>Entonces el sistema redirige al administrador a la sección de estadísticas. |
| **Acceptance Criteria #5** | **Escenario 5: Acceso a “Settings” desde el Dashboard**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando el administrador hace clic en el botón de "Settings" en la sección de “Quick Actions”,<br>Entonces el sistema redirige al administrador a la sección de configuraciones. |

---
### User Story: US52

| **User Story ID** | US52 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Visualización de estadísticas de libros en Books en la sección estadísticas |
| **Description** | Como administrador, quiero ver estadísticas relevantes sobre los libros en la sección estadísticas en Books, para poder tomar decisiones informadas sobre los libros más populares, más vendidos y otros datos clave del inventario. |
| **Acceptance Criteria #1** | **Escenario 1: Ver el total de libros y el total de géneros**<br>Dado que el administrador se encuentra en Books en la sección de estadísticas,<br>Cuando el administrador accede a esta sección,<br>Entonces se muestra el total de libros disponibles en el sistema y el total de géneros de libros registrados en la base de datos. |
| **Acceptance Criteria #2** | **Escenario 2: Ver el precio promedio de los libros**<br>Dado que el administrador se encuentra en Books en la sección de estadísticas,<br>Cuando el administrador consulta las estadísticas,<br>Entonces se muestra el precio promedio de todos los libros en el sistema. |
| **Acceptance Criteria #3** | **Escenario 3: Ver la cantidad de libros en stock**<br>Dado que el administrador se encuentra en Books en la sección de estadísticas,<br>Cuando el administrador consulta las estadísticas,<br>Entonces se muestra el número total de libros en stock, es decir, aquellos disponibles para la venta. |
| **Acceptance Criteria #4** | **Escenario 4: Ver el libro más visto y el libro más vendido**<br>Dado que el administrador se encuentra en Books en la sección de estadísticas,<br>Cuando el administrador consulta las estadísticas,<br>Entonces se muestra el libro más visto en la plataforma y el libro más vendido de la plataforma. |

---
### User Story: US53

| **User Story ID** | US53 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Búsqueda de libros en Books la sección "Book Collection" |
| **Description** | Como administrador, quiero poder buscar libros de la colección en Books en la sección "Book Collection", utilizando diversos filtros, para encontrar fácilmente el libro que me interesa saber su información. |
| **Acceptance Criteria #1** | **Escenario 1: Búsqueda por título o autor**<br>Dado que el usuario se encuentra en la sección "Book Collection",<br>Cuando el usuario ingresa un título o autor en el campo de búsqueda,<br>Entonces el sistema muestra los libros que coinciden con el título o autor ingresado. |
| **Acceptance Criteria #2** | **Escenario 2: Filtro por género e idioma**<br>Dado que el usuario se encuentra en la sección "Book Collection",<br>Cuando el usuario selecciona un género en el filtro o un idioma en el filtro,<br>Entonces el sistema muestra los libros que pertenecen a ese género específico o a ese idioma en específico. |
| **Acceptance Criteria #3** | **Escenario 3: Ordenamiento de libros**<br>Dado que el usuario se encuentra en la sección "Book Collection",<br>Cuando el usuario selecciona un criterio de ordenamiento (por ejemplo, precio, popularidad, fecha de publicación),<br>Entonces el sistema ordena los libros según el criterio seleccionado. |

---
### User Story: US54

| **User Story ID** | US54 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Visualización del precio y detalles completos del libro en la sección "Book Collection" |
| **Description** | Como administrador, quiero ver el precio de un libro y su información básica en la sección "Libro de Colección", y acceder a una ventana con más detalles completos del libro, para poder tomar decisiones informadas sobre la gestión de mis productos. |
| **Acceptance Criteria #1** | **Escenario 1: Ver el precio del libro**<br>Dado que el administrador está visualizando un libro en la sección "Book Collection",<br>Cuando el administrador consulta los detalles del libro,<br>Entonces el sistema muestra claramente el precio del libro. |
| **Acceptance Criteria #2** | **Escenario 2: Ver la información básica del libro**<br>Dado que el administrador está visualizando un libro en la sección "Book Collection",<br>Cuando el administrador consulta los detalles del libro,<br>Entonces el sistema muestra una breve descripción del libro, autor, género, idioma y otros datos clave como stock y reviews. |
| **Acceptance Criteria #3** | **Escenario 3: Botón "View" para acceder a más detalles del libro**<br>Dado que el administrador está visualizando un libro en la sección "Libro de Colección",<br>Cuando el administrador hace clic en el botón de "View",<br>Entonces el sistema muestra al administrador una ventana con información detallada sobre el libro, incluyendo la sinopsis, autor y datos relacionados con su precio de compra, de venta y de stock. |

---
### User Story: US55

| **User Story ID** | US55 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Visualización de estadísticas y análisis de órdenes en "Manage and Analyze All Livria Orders" |
| **Description** | Como administrador, quiero ver estadísticas clave sobre todas las órdenes en la sección "Manage and Analyze All Livria Orders”, para poder realizar un análisis completo y tomar decisiones informadas sobre las ventas. |
| **Acceptance Criteria #1** | **Escenario 1: Ver el total de órdenes y de ganancias**<br>Dado que el administrador se encuentra en la sección "Manage and Analyze All Livria Orders",<br>Cuando el administrador consulta las estadísticas,<br>Entonces el sistema muestra el total de órdenes realizadas en la plataforma y el total de ganancias generadas por todas las órdenes. |
| **Acceptance Criteria #2** | **Escenario 2: Ver órdenes pendientes y completas**<br>Dado que el administrador se encuentra en la sección "Manage and Analyze All Livria Orders",<br>Cuando el administrador consulta las estadísticas,<br>Entonces el sistema muestra el número total de órdenes pendientes de procesamiento o envío y el número total de órdenes completas que han sido procesadas y entregadas. |
| **Acceptance Criteria #3** | **Escenario 3: Ver el promedio del valor de las órdenes**<br>Dado que el administrador se encuentra en la sección "Manage and Analyze All Livria Orders",<br>Cuando el administrador consulta las estadísticas,<br>Entonces el sistema muestra el valor promedio de las órdenes realizadas en la plataforma. |
| **Acceptance Criteria #4** | **Escenario 4: Ver el libro más popular pedido**<br>Dado que el administrador se encuentra en la sección "Manage and Analyze All Livria Orders",<br>Cuando el administrador consulta las estadísticas,<br>Entonces el sistema muestra el libro más popular, basado en la cantidad de veces que ha sido solicitado en las órdenes. |

---
### User Story: US56

| **User Story ID** | US56 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Búsqueda y filtrado de órdenes en la sección "Order List" en Orders |
| **Description** | Como administrador, quiero poder buscar órdenes por ID de pedido o por el nombre del cliente, y poder filtrar de distintas formas, para encontrar fácilmente las órdenes que me interesan. |
| **Acceptance Criteria #1** | **Escenario 1: Buscar por ID de orden o por nombre del cliente**<br>Dado que el administrador se encuentra en la sección "Order List",<br>Cuando el administrador ingresa un ID de orden o el nombre del cliente en el campo de búsqueda,<br>Entonces el sistema muestra las órdenes que coinciden con ese ID o asociadas a ese cliente. |
| **Acceptance Criteria #2** | **Escenario 2: Filtrar por estado del pedido**<br>Dado que el administrador se encuentra en la sección "Order List",<br>Cuando el administrador selecciona un estado de pedido (pendiente, completado, cancelado, etc.),<br>Entonces el sistema muestra sólo las órdenes con el estado seleccionado. |
| **Acceptance Criteria #3** | **Escenario 3: Filtrar por fecha**<br>Dado que el administrador se encuentra en la sección "Order List",<br>Cuando el administrador selecciona un rango de fechas,<br>Entonces el sistema muestra sólo las órdenes que corresponden a ese rango de fechas. |
| **Acceptance Criteria #4** | **Escenario 4: Filtrar por ordenamiento**<br>Dado que el administrador se encuentra en la sección "Order List",<br>Cuando el administrador selecciona un criterio de ordenamiento (por ejemplo, por fecha, por total, por estado),<br>Entonces el sistema ordena las órdenes según el criterio seleccionado. |

---
### User Story: US57

| **User Story ID** | US57 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Visualización de la tabla con detalles de las órdenes en la sección "Order List" |
| **Description** | Como administrador, quiero que después de realizar una búsqueda o un filtro, el sistema me muestre una tabla con los detalles de las órdenes, incluyendo el código de orden, el cliente, el beneficiario, la fecha, el total, el estado, el ítem y las acciones disponibles, para gestionar las órdenes de manera eficiente. |
| **Acceptance Criteria #1** | **Escenario 1: Ver la tabla con detalles de las órdenes**<br>Dado que el administrador ha realizado la búsqueda o el filtrado de las órdenes,<br>Cuando se muestran los resultados,<br>Entonces el sistema muestra una tabla con diversos atributos relacionados comúnmente a una orden. |

---
### User Story: US58

| **User Story ID** | US58 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Búsqueda y filtrado en el "Book Collection" de Inventario |
| **Description** | Como administrador, quiero tener una barra de búsqueda y filtros en la sección "Book Collection" del inventario, para poder buscar fácilmente un libro específico dentro del inventario. |
| **Acceptance Criteria #1** | **Escenario 1: Barra de búsqueda**<br>Dado que el administrador está en la sección "Book Collection" del inventario,<br>Cuando el administrador ingresa un término en la barra de búsqueda,<br>Entonces el sistema muestra los libros que coinciden con el término de búsqueda. |
| **Acceptance Criteria #2** | **Escenario 2: Filtro por género o por lenguaje**<br>Dado que el administrador está en la sección "Book Collection" del inventario,<br>Cuando el administrador selecciona un género en el filtro o un lenguaje en el filtro,<br>Entonces el sistema muestra los libros que pertenecen a ese género específico o los libros disponibles en ese lenguaje. |
| **Acceptance Criteria #3** | **Escenario 3: Ordenamiento de libros**<br>Dado que el administrador está en la sección "Book Collection" del inventario,<br>Cuando el administrador selecciona un criterio de ordenamiento (por ejemplo, por precio, por stock, por fecha de publicación),<br>Entonces el sistema ordena los libros según el criterio seleccionado. |

---
### User Story: US59

| **User Story ID** | US59 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Visualización de la tabla de "Book Collection" en Inventario |
| **Description** | Como administrador, quiero ver una tabla en la sección "Book Collection" del inventario que contenga los detalles de cada libro, como su portada, título, autor, etc., para gestionar fácilmente el inventario de libros. |
| **Acceptance Criteria #1** | **Escenario 1: Ver la tabla con detalles del libro**<br>Dado que el administrador está en la sección "Book Collection" del inventario,<br>Cuando se muestran los libros,<br>Entonces el sistema presenta una tabla con los campos de Portada, título, autor, género, lenguaje, stock, precio de compra, cantidad y acción. |
| **Acceptance Criteria #2** | **Escenario 2: Añadir un libro a la colección**<br>Dado que el administrador está visualizando la tabla de "Book Collection" en el inventario,<br>Cuando hace clic en el botón "+" para un libro,<br>Entonces el sistema permite al administrador agregar el libro al inventario de la colección. |

---
### User Story: US60

| **User Story ID** | US60 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Gestión de la configuración del perfil en "Settings" |
| **Description** | Como administrador, quiero poder gestionar mi perfil desde la sección "Settings", para poder ver, actualizar mi información personal o cambiar mi contraseña si es necesario. |
| **Acceptance Criteria #1** | **Escenario 1: Ver información del perfil**<br>Dado que el administrador se encuentra en la sección "Settings",<br>Cuando el administrador accede a la pestaña "Profile Information",<br>Entonces se muestra la información del perfil actual del administrador, incluyendo su nombre, nombre de usuario, correo electrónico y un campo de contraseña. |
| **Acceptance Criteria #2** | **Escenario 2: Actualizar la información del perfil**<br>Dado que el administrador está en la sección "Settings",<br>Cuando el administrador realiza cambios en su nombre, nombre de usuario o correo electrónico,<br>Entonces el sistema permite al administrador guardar los cambios al hacer clic en "Save Changes". |
| **Acceptance Criteria #3** | **Escenario 3: Cambiar la contraseña**<br>Dado que el administrador está en la sección "Settings",<br>Cuando el administrador hace clic en "Change Password",<br>Entonces el sistema permite al administrador ingresar y actualizar su contraseña. |

---
### User Story: US61

| **User Story ID** | US61 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Gestión de la configuración de la aplicación en "Application Settings" |
| **Description** | Como administrador, quiero poder gestionar la configuración de la aplicación desde la sección "Application Settings", para poder activar o desactivar notificaciones, alertas por correo electrónico, autoguardado de cambios y cambiar la configuración de la cantidad de elementos por página. |
| **Acceptance Criteria #1** | **Escenario 1: Activar/desactivar notificaciones en la aplicación**<br>Dado que el administrador se encuentra en la sección "Application Settings",<br>Cuando el administrador marca o desmarca la opción "Receive notifications in the app",<br>Entonces el sistema habilita o deshabilita las notificaciones dentro de la aplicación según la elección del administrador. |
| **Acceptance Criteria #2** | **Escenario 2: Activar/desactivar alertas por correo electrónico**<br>Dado que el administrador se encuentra en la sección "Application Settings",<br>Cuando el administrador marca o desmarca la opción "Receive email alerts",<br>Entonces el sistema habilita o deshabilita las alertas por correo electrónico según la elección del administrador. |
| **Acceptance Criteria #3** | **Escenario 3: Activar/desactivar auto guardado de cambios**<br>Dado que el administrador se encuentra en la sección "Application Settings",<br>Cuando el administrador marca o desmarca la opción "Automatically save changes",<br>Entonces el sistema habilita o deshabilita el guardado automático de los cambios en la configuración de la aplicación. |
| **Acceptance Criteria #4** | **Escenario 4: Configurar el tamaño de página**<br>Dado que el administrador se encuentra en la sección "Application Settings",<br>Cuando el administrador ajusta el número de "Items per page" (por ejemplo, a 5, 10, 20, 50),<br>Entonces el sistema ajusta la cantidad de elementos que se muestran por página según la configuración seleccionada. |
| **Acceptance Criteria #5** | **Escenario 5: Guardar los cambios realizados en la configuración**<br>Dado que el administrador ha realizado cambios en las opciones de "Application Settings",<br>Cuando el administrador hace clic en "Save Changes",<br>Entonces el sistema guarda los cambios y los aplica inmediatamente a la configuración de la aplicación. |

---
### User Story: US62

| **User Story ID** | US62 |
|-------------------|------|
| **Epic ID** | EP11 |
| **Title** | Barra lateral de navegación en el dashboard del administrador |
| **Description** | Como administrador, quiero tener una barra lateral en el dashboard que contenga la información fundamental del dashboard, para poder navegar de forma rápida y eficiente a las diferentes áreas del sistema. |
| **Acceptance Criteria #1** | **Escenario 1: Ver título de la plataforma**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando mira la barra lateral,<br>Entonces el sistema muestra el título de la plataforma, "LIVRIA", en la parte superior. |
| **Acceptance Criteria #2** | **Escenario 2: Ver imagen de perfil y nombre del administrador**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando mira la barra lateral,<br>Entonces el sistema muestra la imagen de perfil del administrador y su nombre ("Super Administrador") debajo del título de la plataforma. |
| **Acceptance Criteria #3** | **Escenario 3: Ver secciones principales de navegación**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando mira la barra lateral,<br>Entonces el sistema muestra las secciones de Home, Books, Orders, Inventory y Stadistics. |
| **Acceptance Criteria #4** | **Escenario 4: Ver botón para cambiar el idioma**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando mira la barra lateral,<br>Entonces el sistema muestra un botón para cambiar el idioma entre "EN" (inglés) y "ES" (español). |
| **Acceptance Criteria #5** | **Escenario 5: Ver configuraciones y cerrar sesión**<br>Dado que el administrador se encuentra en el dashboard,<br>Cuando mira la barra lateral,<br>Entonces el sistema muestra un enlace a la sección "Settings" (configuraciones) y un botón para "Log out" (cerrar sesión). |

---
### User Story: US63

| **User Story ID** | US63 |
|-------------------|------|
| **Epic ID** | EP13 |
| **Title** | Registro de cuenta con control y seguridad. |
| **Description** | Como administrador, quiero registrarme en la plataforma mediante un formulario seguro, para crear una cuenta protegida y acceder posteriormente mediante autenticación segura. |
| **Acceptance Criteria** | **Escenario 1: Registro exitoso de administrador**<br>Dado que un administrador nuevo intenta registrarse en la plataforma,<br>Y proporciona un nombre de usuario, correo electrónico, contraseña y PIN de seguridad válidos,<br>Cuando envía el formulario de registro,<br>Entonces el sistema valida los datos proporcionados, crea una cuenta con rol de administrador y confirma el registro como exitoso. <br><br> **Escenario 2: Registro con datos existentes**<br>Dado que un administrador intenta registrarse en la plataforma,<br>Y proporciona un nombre de usuario o correo electrónico ya existente,<br>Cuando envía el formulario de registro,<br>Entonces el sistema rechaza el registro y retorna un mensaje de error indicando que el usuario o correo ya están registrados. |


---
### User Story: US64

| **User Story ID** | US64 |
|-------------------|------|
| **Epic ID** | EP13 |
| **Title** | Inicio de sesión con autenticación JWT. |
| **Description** | Como administrador, quiero iniciar sesión en la plataforma utilizando un sistema de autenticación basado en JWT, para acceder de manera segura a las funcionalidades administrativas. |
| **Acceptance Criteria** | **Escenario 1: Inicio de sesión exitoso**<br>Dado que un administrador registrado intenta iniciar sesión,<br>Y proporciona un nombre de usuario, contraseña y PIN válidos,<br>Cuando envía las credenciales,<br>Entonces el sistema valida las credenciales, genera un token JWT con el rol "Admin" y lo devuelve al usuario. <br><br> **Escenario 2: Inicio de sesión con credenciales inválidas**<br>Dado que un administrador intenta iniciar sesión,<br>Y proporciona un nombre de usuario o contraseña incorrectos,<br>Cuando envía las credenciales,<br>Entonces el sistema devuelve un error con un mensaje indicando que las credenciales son inválidas. |


---
### User Story: US65

| **User Story ID** | US65 |
|-------------------|------|
| **Epic ID** | EP13 |
| **Title** | Registro de usuario cliente |
| **Description** | Como usuario, quiero registrarme en la plataforma con un sistema seguro, para crear una cuenta y acceder a mis recursos personales como cliente. |
| **Acceptance Criteria** | **Escenario 1: Registro exitoso**<br>Dado que un usuario nuevo intenta registrarse,<br>Y proporciona un nombre de usuario y contraseña válidos,<br>Cuando envía el formulario de registro,<br>Entonces el sistema crea una cuenta de usuario y confirma como exitoso el registro. <br><br> **Escenario 2: Registro con información duplicada**<br>Dado que un usuario intenta registrarse,<br>Y proporciona un username y/o contraseña ya registrado,<br>Cuando envía el formulario de registro,<br>Entonces el sistema devuelve un error con un mensaje indicando que el username o la contraseña ya está en uso. |


---
### User Story: US66

| **User Story ID** | US66 |
|-------------------|------|
| **Epic ID** | EP13 |
| **Title** | Acceso seguro a la cuenta mediante JWT. |
| **Description** | Como usuario, quiero iniciar sesión en la plataforma utilizando autenticación JWT, para acceder de manera segura a mis recursos personales. |
| **Acceptance Criteria** | **Escenario 1: Inicio de sesión exitoso**<br>Dado que un usuario registrado intenta iniciar sesión,<br>Y proporciona un nombre de usuario y contraseña válidos,<br>Cuando envía las credenciales,<br>Entonces el sistema valida las credenciales, genera un token JWT con el rol "Cliente" y se lo devuelve. <br><br> **Escenario 2: Intento de acceso con credenciales inválidas**<br>Dado que un usuario intenta iniciar sesión,<br>Y proporciona un nombre de usuario o contraseña incorrectos,<br>Cuando envía las credenciales,<br>Entonces el sistema devuelve un error con un mensaje indicando que las credenciales son inválidas. |



### 3.2.3. Historias Técnicas

---
### Technical story: TS01

| **Technical story ID** | TS01 |
|-------------------|------|
| **Epic ID** | EP12 |
| **Title** | Configuración inicial de la base de datos MySQL. |
| **Description** | Como Developer, debo configurar la conexión segura entre el backend (.NET) y la base de datos MySQL, asegurando que las credenciales estén protegidas con variables de entorno. |
| **Acceptance Criteria** | **Escenario 1: Conexión exitosa a la base de datos**<br>Dado que el servidor backend está en ejecución,<br>Cuando se realiza una petición a cualquier endpoint que requiera datos,<br>Entonces la API debe responder con status 200 y los datos correctos,<br> Y la conexión debe usar SSL para encriptación.  |


---
### Technical story: TS02

| **Technical story ID** | TS02 |
|-------------------|------|
| **Epic ID** | EP12 |
| **Title** | Implementación de autenticación JWT. |
| **Description** | Como Developer, debo implementar autenticación basada en tokens JWT para proteger endpoints críticos (ej: gestión de usuarios, pedidos). |
| **Acceptance Criteria** | **Escenario 1: Acceso a endpoint protegido sin token**<br>Dado que un usuario no autenticado,<br>Cuando intenta acceder a /api/v1/orders,<br>Entonces la API debe responder con status 401 (Unauthorized). <br><br> **Escenario 2: Acceso con token válido**<br>Dado que un usuario con token JWT válido,<br>Cuando realiza una petición a /api/v1/orders,<br>Entonces la API debe responder con status 200 y los datos del pedido. |


---
### Technical story: TS03

| **Technical story ID** | TS03 |
|-------------------|------|
| **Epic ID** | EP12 |
| **Title** | Documentación de APIs con Swagger/OpenAPI |
| **Description** | Como Developer, debo generar documentación interactiva de los endpoints usando Swagger UI, incluyendo ejemplos de requests/responses y esquemas de datos. |
| **Acceptance Criteria** | **Escenario 1: Visualización de documentación**<br>Dado que un administrador accede a /swagger,<br>Cuando navega por los endpoints,<br>Entonces debe ver descripciones, parámetros y opciones para probar cada endpoint,<br> Y los esquemas de Books, Orders, Users deben estar correctamente definidos. |


---
### Technical story: TS04

| **Technical story ID** | TS04 |
|-------------------|------|
| **Epic ID** | EP12 |
| **Title** | Optimización de consultas SQL para carritos. |
| **Description** | Como Developer, debo optimizar las consultas SQL de las tablas cart_items y orders para reducir el tiempo de respuesta en un 30%. |
| **Acceptance Criteria** | **Escenario 1: Consulta de carrito con 100+ ítems**<br>Dado que un usuario con 150 libros en su carrito,<br>Cuando solicita su carrito (/api/v1/cart-items/users/{id}),<br>Entonces la respuesta debe demorar <500ms.<br>Y la consulta debe usar índices en `bookId` y `userClientId` |


---
### Technical story: TS05

| **Technical story ID** | TS05 |
|-------------------|------|
| **Epic ID** | EP12 |
| **Title** | Implementación de logs de errores. |
| **Description** | Como Developer, debo configurar un sistema de logging centralizado para registrar errores en la API (ej: fallos en consultas SQL, requests inválidos). |
| **Acceptance Criteria** | **Escenario 1: Error en consulta SQL**<br>Dado que un endpoint con error de sintaxis SQL,<br>Cuando se realiza una petición,<br>Entonces el sistema debe registrar el error en un archivo `logs/api_errors.log`<br> Y la API debe responder con status 500 y un mensaje genérico. |


---
### Technical story: TS06

| **Technical story ID** | TS06 |
|-------------------|------|
| **Epic ID** | EP12 |
| **Title** | Configuración de CORS para el frontend. |
| **Description** | Como Developer, debo habilitar CORS en el backend para permitir solicitudes solo desde los dominios autorizados (ej: https://livriabybookify.netlify.app/). |
| **Acceptance Criteria** | **Escenario 1: Petición desde dominio no autorizado**<br>Dado que un frontend en `malicious.com`,<br>Cuando intenta acceder a /api/v1/books,<br>Entonces la API debe responder con status 403 (Forbidden).<br><br> **Escenario 2: Petición desde livria.com**<br>Dado que el frontend oficial en `app.livria.com`,<br>Cuando realiza una petición GET a /api/v1/books,<br>Entonces la API debe responder con status 200. |


---
### Technical story: TS07

| **Technical story ID** | TS07 |
|-------------------|------|
| **Epic ID** | EP15 |
| **Title** | Creación del Endpoint RESTful para Registro de Administrador con Validación de Datos. |
| **Description** | Como Developer, debo crear el endpoint RESTful para el registro de un administrador, el cual recibirá un conjunto de datos como nombre de usuario, correo electrónico, contraseña y PIN de seguridad. Además, debe validar la existencia de los datos y generar un registro en la base de datos de forma segura. |
| **Acceptance Criteria** | **Escenario 1: Registro exitoso de administrador**<br>Dado que un administrador nuevo envía una solicitud POST a /register con los datos de nombre de usuario, correo electrónico, contraseña y PIN de seguridad válidos,<br>Cuando se valida que los datos no existen en la base de datos y son correctos,<br>Entonces la  API debe devolver un estado 201 (Creado)),<br> Y debe incluir en la respuesta un mensaje confirmando el registro exitoso y los detalles del nuevo administrador (sin contraseña ni PIN).<br><br> **Escenario 2: Registro con datos existentes**<br>Dado que un administrador intenta registrar un nombre de usuario o correo electrónico ya registrado<br>Cuando se envía la solicitud POST a /register con los datos mencionados,<br>Entonces la API debe devolver un estado 400 (Bad Request), <br> Y la respuesta debe contener un mensaje de error indicando que el nombre de usuario o correo electrónico ya están registrados. |


---
### Technical story: TS08

| **Technical story ID** | TS08 |
|-------------------|------|
| **Epic ID** | EP15 |
| **Title** | Configuración del endpoint de inicio de sesión (POST /login). |
| **Description** | Como Developer, debo crear el endpoint RESTful para el inicio de sesión de un usuario registrado, el cual recibirá las credenciales (nombre de usuario y contraseña) y devolverá un token JWT si son válidas. |
| **Acceptance Criteria** | **Escenario 1: Inicio de sesión exitoso**<br>Dado que un usuario registrado envía una solicitud POST a /login con un nombre de usuario y contraseña válidos,<br>Cuando se validan las credenciales contra la base de datos,<br>Entonces la API debe devolver un estado 200 (OK),<br>Y la respuesta debe incluir un token JWT con el rol "Cliente" que el usuario puede usar para acceder a recursos protegidos.<br><br> **Escenario 2: Intento de acceso con credenciales inválidas**<br>Dado que un usuario intenta iniciar sesión con un nombre de usuario o contraseña incorrectos,<br>Cuando se envía la solicitud POST a /login con credenciales incorrectas,<br>Entonces la  API debe devolver un estado 401 (Unauthorized),<br> Y la respuesta debe incluir un mensaje de error indicando que las credenciales son inválidas. |


---
### Technical story: TS09

| **Technical story ID** | TS09 |
|-------------------|------|
| **Epic ID** | EP15 |
| **Title** | Configuración de validación de entrada para el registro (validación de nombre de usuario y correo electrónico). |
| **Description** | Como Developer, debo asegurarme de que la API valida correctamente los datos proporcionados en el proceso de registro (nombre de usuario, correo electrónico, contraseña y PIN de seguridad), asegurando que el nombre de usuario y correo electrónico no existan previamente. |
| **Acceptance Criteria** | **Escenario 1: Validación de nombre de usuario y correo electrónico**<br>Dado que un administrador envía una solicitud POST a /register,<br>Cuando se valida que el nombre de usuario y correo electrónico no existan en la base de datos,<br>Entonces la API debe devolver un estado 400 (Bad Request),<br>Y el mensaje de error debe indicar que el nombre de usuario o correo electrónico ya existen en el sistema. |


---
### Technical story: TS10

| **Technical story ID** | TS10 |
|-------------------|------|
| **Epic ID** | EP15 |
| **Title** | Generación y Validación de Token JWT para Usuario Cliente. |
| **Description** | Como Developer, debo implementar la generación de un token JWT seguro para los usuarios que inician sesión con credenciales válidas, asegurando que el token tenga una fecha de expiración y un rol asociado. |
| **Acceptance Criteria** | **Escenario 1: Generación de token JWT**<br>Dado que un usuario ha iniciado sesión con credenciales válidas,<br>Cuando el sistema genera el token JWT,<br>Entonces el token debe incluir un campo "role" con el valor "Cliente",<br>Y el token debe tener una expiración de 1 hora<br>Y el token debe estar firmado de manera segura utilizando una clave privada. |


---
### Technical story: TS11

| **Technical story ID** | TS11 |
|-------------------|------|
| **Epic ID** | EP16 |
| **Title** | Autenticación de solicitudes con token JWT. |
| **Description** | Como Developer, debo garantizar que las solicitudes a endpoints protegidos requieran un token JWT válido en el encabezado de la solicitud para permitir el acceso. |
| **Acceptance Criteria** | **Escenario 1: Autenticación exitosa con token JWT válido**<br>Dado que un usuario ha iniciado sesión y tiene un token JWT válido,<br>Cuando se realiza una solicitud GET a un endpoint protegido (por ejemplo, /user/profile),<br>Entonces la API debe validar el token JWT,<br>Y la respuesta debe ser 200 (OK) si el token es válido y el usuario tiene acceso al recurso. <br><br> **Escenario 2: Acceso denegado con token JWT inválido**<br>Dado que un usuario intenta acceder a un endpoint protegido con un token JWT inválido,<br>Cuando se  envía la solicitud con el token inválido,<br>Entonces la API debe devolver un estado 401 (Unauthorized),<br>Y la respuesta debe contener un mensaje de error indicando que el token es inválido o ha expirado. |


---
### Technical story: TS12

| **Technical story ID** | TS12 |
|-------------------|------|
| **Epic ID** | EP16 |
| **Title** | Asignación de roles en el registro de clientes y administradores. |
| **Description** | Como desarrollador, quiero implementar la asignación de roles durante el registro de clientes y administradores, para garantizar que tengan los permisos adecuados según su tipo de cuenta. |
| **Acceptance Criteria** | **Escenario 1: Asignación de rol “Admin” al registrar un administrador**<br>Dado que un administrador se registra en la plataforma,<br>Cuando se crea la cuenta,<br>Entonces el sistema asigna el rol “Admin”. <br><br> **Escenario 2: Asignación de rol “Cliente” al registrar un usuario**<br>Dado que un cliente se registra en la plataforma,<br>Cuando se crea la cuenta,<br>Entonces el sistema asigna el rol “Cliente”. |


---
### Technical story: TS13

| **Technical story ID** | TS13 |
|-------------------|------|
| **Epic ID** | EP16 |
| **Title** | Middleware de control de acceso basado en roles JWT. |
| **Description** | Como desarrollador, quiero implementar un middleware que controle el acceso a los recursos basado en los roles incluidos en el token JWT, para restringir el acceso según el rol del usuario. |
| **Acceptance Criteria** | **Escenario 1: Acceso permitido a recurso con rol correcto**<br>Dado que un usuario con rol “Admin” envía una solicitud a un endpoint protegido por la política “AdminAccess”,<br>Cuando el middleware valida el token JWT,<br>Entonces el sistema permite el acceso al recurso. <br><br> **Escenario 2: Acceso denegado por rol incorrecto**<br>Dado que un usuario con rol “Client” envía una solicitud a un endpoint protegido por la política “AdminAccess”,<br>Cuando el middleware valida el token JWT,<br>Entonces el sistema devuelve un error HTTP 403 (forbidden). |


---
### Technical story: TS14

| **Technical story ID** | TS14 |
|-------------------|------|
| **Epic ID** | EP17 |
| **Title** | Integrar el backend con el frontend para la autenticación de usuarios. |
| **Description** | Como desarrollador, quiero integrar el frontend con el backend para gestionar la autenticación de usuarios mediante JWT, asegurando una experiencia de usuario fluida. |
| **Acceptance Criteria** | **Escenario 1: Autenticación exitosa desde el frontend**<br>Dado que un usuario envía credenciales válidas desde el frontend,<br>Cuando el frontend realiza una solicitud al endpoint de autenticación del backend,<br>Entonces el backend devuelve un token JWT, y el frontend lo almacena para solicitudes futuras.<br><br> **Escenario 2: Manejo de autenticación fallida**<br>Dado que un usuario envía credenciales inválidas desde el frontend,<br>Cuando frontend realiza una solicitud al endpoint de autenticación,<br>Entonces el backend devuelve un error HTTP 401, y el frontend muestra un mensaje de error al usuario. |


---
### Technical story: TS15

| **Technical story ID** | TS15 |
|-------------------|------|
| **Epic ID** | EP17 |
| **Title** | Manejar errores de autenticación en el frontend. |
| **Description** | Como desarrollador, quiero implementar el manejo de errores de autenticación en el frontend, para informar a los usuarios sobre problemas durante el inicio de sesión o el acceso a recursos. |
| **Acceptance Criteria** | **Escenario 1:  Mostrar error de credenciales inválidas**<br>Dado que el backend devuelve un error HTTP 401 (No autorizado) durante el inicio de sesión,<br>Cuando el frontend recibe la respuesta,<br>Entonces muestra un mensaje claro al usuario indicando que las credenciales son incorrectas. |


---
### Technical story: TS16

| **Technical story ID** | TS16 |
|-------------------|------|
| **Epic ID** | EP17 |
| **Title** | Asegurar la correcta sincronización de datos entre el frontend y el backend. |
| **Description** | Como desarrollador, quiero garantizar que los datos entre el frontend y el backend estén sincronizados, para evitar inconsistencias en la experiencia del usuario. |
| **Acceptance Criteria** | **Escenario 1: Sincronización de datos tras actualización**<br>Dado que un usuario actualiza datos en el frontend, por ejemplo, en su perfil,<br>Cuando el frontend  envía la solicitud al backend,<br>Entonces el backend actualiza los datos y devuelve una respuesta que el frontend refleja correctamente en la interfaz. <br><br> **Escenario 2: Manejo de errores de sincronización**<br>Dado que el frontend recibe la respuesta,<br>Cuando el frontend  envía la solicitud al backend,<br>Entonces muestra un mensaje de error al usuario y no actualiza los datos en la interfaz.|


---
### Technical story: TS17

| **Technical story ID** | TS17 |
|-------------------|------|
| **Epic ID** | EP17 |
| **Title** | Garantizar que la navegación entre el frontend y el backend sea segura. |
| **Description** | Como desarrollador, quiero asegurar que la comunicación entre el frontend y el backend sea segura, utilizando HTTPS y tokens JWT, para proteger los datos del usuario. |
| **Acceptance Criteria** | **Escenario 1: Comunicación segura con HTTPS**<br>Dado que el frontend realiza solicitudes al backend,<br>Cuando se envía una solicitud,<br>Entonces la solicitud se realiza a través de HTTPS, asegurando la encriptación de los datos.<br><br> **Escenario 2: Protección con token JWT**<br>Dado que el frontend envía una solicitud a un endpoint protegido,<br>Cuando incluye un token JWT válido en el encabezado,<br>Entonces el backend procesa la solicitud. De lo contrario, devuelve un error HTTP 401 (No autorizado). |


---
### Technical story: TS18

| **Technical story ID** | TS18 |
|-------------------|------|
| **Epic ID** | EP17 |
| **Title** | Optimizar la comunicación entre el frontend y el backend para la carga de datos. |
| **Description** | Como desarrollador, quiero optimizar las solicitudes entre el frontend y el backend, para reducir la latencia y mejorar la experiencia de carga de datos. |
| **Acceptance Criteria** | **Escenario 1: Carga eficiente de datos**<br>Dado que el frontend solicita una lista de recursos, por ejemplo, libros,<br>Cuando el backend devuelve los datos,<br>Entonces el frontend los procesa y muestra en menos de 2 segundos, asumiendo una conexión estable. |



### 3.2.4. Epicas

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

| **EPIC 09:** | Backend de gestión de libros, carrito de compra y pedidos |
|:------------:|:-------------------------------------------------------|
| | Como administrador, quiero gestionar eficientemente el backend de la plataforma, con funcionalidades de gestión de libros, carrito de compra y pedidos, para asegurarme de que la plataforma funcione de manera fluida y segura. |
| **User Story ID** | **Título** |
| US35 | Obtener todos los libros |
| US36 | Obtener detalles de un libro |
| US37 | Crear una reseña de un libro |
| US38 | Obtener todas las reseñas de un libro |
| US39 | Agregar un libro al carrito |
| US40 | Gestión de un pedido |
| US41 | Ver detalles de un pedido |

| **EPIC 10:** | Backend de gestión de comunidades, usuarios y notificaciones |
|:------------:|:-----------------------------------------------------------|
| | Como administrador, quiero gestionar eficientemente las comunidades, usuarios y notificaciones de la plataforma, asegurando que todo esté bien organizado y actualizado para mantener una operación fluida y eficaz. |
| **User Story ID** | **Título** |
| US42 | Obtener todas las comunidades |
| US43 | Gestión de creación de una comunidad |
| US44 | Publicación en una comunidad |
| US45 | Obtener todos los usuarios |
| US46 | Gestión de creación de un nuevo usuario |
| US47 | Eliminar un usuario |
| US48 | Gestión de creación de una notificación |
| US49 | Gestión de asignación de favorito |
| US50 | Creación de recomendaciones en base a favoritos |

| **EPIC 11:** | Gestión del dashboard del administrador |
|:------------:|:---------------------------------------|
| | Como administrador, quiero tener un dashboard con acceso rápido a las principales secciones del sistema, así como una barra lateral con la información básica del sistema, para navegar de manera eficiente entre las áreas clave del sistema, gestionar mi perfil, cambiar el idioma y cerrar sesión sin complicaciones. |
| **User Story ID** | **Título** |
| US51 | Acceso rápido a las secciones del sistema desde el Dashboard |
| US52 | Visualización de estadísticas de libros en Books en la sección estadísticas |
| US53 | Búsqueda y visualización de libros en Books la sección "Book Collection" |
| US54 | Visualización del precio y detalles completos del libro en la sección "Book Collection" |
| US55 | Visualización de estadísticas y análisis de órdenes en "Manage and Analyze All Livria Orders" |
| US56 | Búsqueda y filtrado de órdenes en la sección "Order List" en Orders |
| US57 | Visualización de la tabla con detalles de las órdenes en la sección "Order List" |
| US58 | Búsqueda y filtrado en el "Book Collection" de Inventario |
| US59 | Visualización de la tabla de "Book Collection" en Inventario |
| US60 | Gestión de la configuración del perfil en "Settings" |
| US61 | Gestión de la configuración de la aplicación en "Application Settings" |
| US62 | Barra lateral de navegación en el dashboard del administrador |

| **EPIC 12:** | Desarrollo del backend |
|:------------:|:---------------------------------------|
| | Como desarrollador, quiero implementar, configurar y optimizar aspectos del backend, para asegurar que el sistema sea seguro, eficiente y fácil de mantener. |
| **Technical story ID** | **Título** |
| TS01 | Configuración inicial de la base de datos MYSQL |
| TS02 | Implementación de autenticación JWT |
| TS03 | Documentación de APIs con Swagger/OpenAPI |
| TS04 | Optimización de consultas SQL para carritos |
| TS05 | Implementación de logs de errores |
| TS06 | Configuración de CORS para el frontend |

| **EPIC 13:** | Gestión de IAM con JWT para administradores |
|:------------:|:---------------------------------------|
| | Como administrador, quiero utilizar un sistema de autenticación y autorización basado en JWT para poder acceder de manera segura a las funcionalidades y recursos protegidos de la plataforma. |
| **User story ID** | **Título** |
| US63 | Registro de cuenta con seguridad JWT |
| US64 | Inicio de sesión con autenticación JWT |

| **EPIC 14:** | Gestión de inicio de sesión seguro |
|:------------:|:---------------------------------------|
| | Como usuario, quiero tener acceso a mi cuenta y recursos personales mediante autenticación segura con JWT, para iniciar sesión de manera segura. |
| **User story ID** | **Título** |
| US65 | Registro de usuario con generación de token JWT |
| US66 | Acceso seguro a la cuenta mediante JWT |

| **EPIC 15:** | Desarrollo del backend de la autenticación con JWT |
|:------------:|:---------------------------------------|
| | Como desarrollador, quiero implementar la lógica de autenticación con el token JWT en el backend para gestionar el inicio de sesión de nuestros usuarios. |
| **Technical story ID** | **Título** |
| TS07 | Creación del Endpoint RESTful para Registro de Administrador con Validación de Datos |
| TS08 | Configuración del endpoint de inicio de sesión (POST /login) |
| TS09 | Configuración de validación de entrada para el registro (validación de nombre de usuario y correo electrónico) |
| TS10 | Generación y Validación de Token JWT para Usuario Cliente |

| **EPIC 16:** | Desarrollo del Bounded Context de IAM |
|:------------:|:---------------------------------------|
| | Como desarrollador, quiero implementar el Identity and Access Management (IAM) en el backend para gestionar la autenticación, la autorización y los roles de los usuarios mediante JWT, asegurando que los usuarios tengan acceso a los recursos adecuados según su rol. |
| **Technical story ID** | **Título** |
| TS11 | Autenticación de solicitudes con token JWT |
| TS12 | Asignación de roles en el registro de clientes y administradores |
| TS13 | Middleware de control de acceso basado en roles JWT |

| **EPIC 17:** | Desarrollo de la integración del frontend con el backend |
|:------------:|:---------------------------------------|
| | Como desarrollador, quiero integrar el frontend con el backend para asegurar que las funcionalidades de la aplicación funcione de manera fluida y eficiente, permitiendo que los usuarios puedan interactuar sin problemas con los recursos y funcionalidades disponibles. |
| **Technical story ID** | **Título** |
| TS14 | Integrar el backend con el frontend para la autenticación de usuarios |
| TS15 | Manejar errores de autenticación en el frontend |
| TS16 | Asegurar la correcta sincronización de datos entre el frontend y el backend |
| TS17 | Garantizar que la navegación entre el frontend y el backend sea segura |
| TS18 | Optimizar la comunicación entre el frontend y el backend para la carga de datos |


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
| 8 | US37 | Como administrador, quiero gestionar las reseñas que los usuarios crean para los libros, permitiendo que se guarden en la base de datos. | 5 |
| 9 | US40 | Como administrador, quiero gestionar la creación de pedidos para que los usuarios puedan finalizar sus compras. | 5 |
| 10 | US44 | Como administrador, quiero gestionar las publicaciones dentro de las comunidades para asegurarnos de que sean válidas y se guarden en la base de datos. | 5 |
| 11 | US49 | Como administrador, quiero poder ver los detalles de la lista de un usuario en particular y modificarla para mantener control sobre las relaciones entre clientes y favoritos. | 5 |
| 12 | US50 | Como administrador, quiero poder generar de manera automática recomendaciones para cada usuario en base a sus libros favoritos para mejorar la experiencia del usuario. | 5 |
| 13 | US56 | Como administrador, quiero poder buscar órdenes por ID de pedido o por el nombre del cliente, y poder filtrar de distintas formas, para encontrar fácilmente las órdenes que me interesan. | 5 |
| 14 | US58 | Como administrador, quiero tener una barra de búsqueda y filtros en la sección "Book Collection" del inventario, para poder buscar fácilmente un libro específico dentro del inventario. | 5 |
| 15 | US60 | Como administrador, quiero poder gestionar mi perfil desde la sección "Settings", para poder ver, actualizar mi información personal o  cambiar mi contraseña si es necesario. | 5 |
| 16 | US14 | Como usuario, quiero recibir notificaciones instantáneas en la aplicación, para mantenerme al tanto de mis pagos, descuentos únicos y recomendaciones otorgadas por el algoritmo de Livria. | 3 |
| 17 | US15 | Como usuario, quiero poder indicar si un libro me interesa o no, para personalizar mis futuras recomendaciones. | 3 |
| 18 | US30 | Como usuario, quiero que mi información personal y actividad en Livria estén protegidas, para sentirme seguro mientras navego, leo o realizo compras en la plataforma. | 3 |
| 19 | US22 | Como usuario, quiero poder comentar en las publicaciones dentro de las comunidades literarias, para compartir opiniones, intercambiar ideas sobre libros y conectar con otros lectores. | 3 |
| 20 | US27 | Como usuario, quiero poder valorar y dejar reseñas en los libros que he leído, para compartir mi opinión y ayudar a otros lectores en su elección. | 3 |
| 21 | US18 | Como usuario, quiero obtener diferentes recomendaciones cada cierto tiempo para encontrar nuevas posibles lecturas que se adapten a mi gusto. | 3 |
| 22 | US17 | Como usuario, quiero observar mis recomendaciones de manera ordenada y atractiva para poder elegir mi siguiente lectura. | 3 |
| 23 | US31 | Como usuario, quiero una interfaz intuitiva y fácil de usar, para navegar entre libros, comunidades y configuraciones sin complicaciones ni curvas de aprendizaje. | 3 |
| 24 | US25 | Como usuario, quiero poder organizar y dar seguimiento al envío de mis libros físicos comprados, para saber cuándo y cómo recibiré mi pedido. | 3 |
| 25 | US32 | Como usuario, quiero ingresar a Livria desde distintos dispositivos, para acceder a mis libros y comunidades desde cualquier lugar y sin perder mi progreso. | 3 |
| 26 | US34 | Como usuario, quiero filtrar los libros según subcategorías, orden de precio o título, formato e idioma para encontrar más fácilmente el contenido que me interesa. | 3 |
| 27 | US35 | Como administrador, quiero obtener todos los libros disponibles en la base de datos para realizar un seguimiento de los productos y gestionarlos eficientemente. | 3 |
| 28 | US38 | Como administrador, quiero acceder a todas las reseñas de un libro para gestionarlas desde el backend. | 3 |
| 29 | US41 | Como administrador, quiero poder ver los detalles de un pedido para gestionar el envío y los pagos. | 3 |
| 30 | US43 | Como administrador, quiero gestionar la creación automática de comunidades por parte de los usuarios y almacenarlas correctamente en la base de datos. | 3 |
| 31 | US46 | Como administrador, quiero gestionar la creación de nuevos usuarios para que puedan acceder y participar en la plataforma. | 3 |
| 32 | US48 | Como administrador, quiero poder crear y enviar notificaciones a los usuarios para mantenerlos informados de actualizaciones importantes. | 3 |
| 33 | US51 | Como administrador, quiero tener acceso rápido a las principales secciones del sistema desde el home del dashboard, para poder acceder a la gestión libros, pedidos, inventarios, estadísticas y configuraciones de manera rápida. | 3 |
| 34 | US53 | Como administrador, quiero poder buscar libros de la colección en Books en la sección "Book Collection", utilizando diversos filtros, para encontrar fácilmente el libro que me interesa saber su información. | 3 |
| 35 | US55 | Como administrador, quiero ver estadísticas clave sobre todas las órdenes en la sección "Manage and Analyze All Livria Orders”, para poder realizar un análisis completo y tomar decisiones informadas sobre las ventas. | 3 |
| 36 | US57 | Como administrador, quiero que después de realizar una búsqueda o un filtro, el sistema me muestre una tabla con los detalles de las órdenes, incluyendo el código de orden, el cliente, el beneficiario, la fecha, el total, el estado, el ítem y las acciones disponibles, para gestionar las órdenes de manera eficiente. | 3 |
| 37 | US59 | Como administrador, quiero ver una tabla en la sección "Book Collection" del inventario que contenga los detalles de cada libro, como su portada, título, autor, etc. , para gestionar fácilmente el inventario de libros. | 3 |
| 38 | US61 | Como administrador, quiero poder gestionar la configuración de la aplicación desde la sección "Application Settings", para poder activar o desactivar notificaciones, alertas por correo electrónico, autoguardado de cambios y cambiar la configuración de la cantidad de elementos por página. | 3 |
| 39 | US63 | Como administrador, quiero registrarme en la plataforma mediante un formulario seguro, para crear una cuenta protegida y acceder posteriormente mediante autenticación segura. | 3 |
| 40 | US64 | Como administrador, quiero iniciar sesión en la plataforma utilizando un sistema de autenticación basado en JWT, para acceder de manera segura a las funcionalidades administrativas. | 3 |
| 41 | US66 | Como usuario, quiero iniciar sesión en la plataforma utilizando autenticación JWT, para acceder de manera segura a mis recursos personales. | 3 |
| 42 | US05 | Como visitante, quiero identificar fácilmente la sección “Contáctanos”, para poder establecer comunicación en caso de necesitar información adicional sobre la plataforma o tener interés en colaborar con el equipo de Livria. | 2 |
| 43 | US19 | Como usuario, quiero poder cerrar sesión de mi cuenta cuando lo desee, para proteger mi información personal y asegurar la privacidad de mis datos al finalizar el uso de la plataforma. | 2 |
| 44 | US29 | Como usuario, quiero que la plataforma esté disponible en cualquier momento del día, para acceder a mis libros, comunidades y funcionalidades sin importar el lugar o la hora. | 2 |
| 45 | US16 | Como usuario, quiero poder registrarme e iniciar sesión con mis credenciales, para acceder a la plataforma y descubrir nuevos títulos de mi agrado. | 2 |
| 46 | US07 | Como visitante, quiero que la landing page sea visualmente atractiva, para sentirme interesado por Livria y motivado a usar la aplicación que ofrecen. | 2 |
| 47 | US03 | Como visitante, quiero navegar por la plataforma en mi idioma preferido, para comprender fácilmente el contenido de presentación de Livria. | 2 |
| 48 | US13 | Como usuario, quiero tener la posibilidad de personalizar mis preferencias de notificación, para recibir únicamente la información que realmente me interesa y así mejorar mi experiencia dentro de la plataforma. | 2 |
| 49 | US33 | Como usuario, quiero acceder rápidamente a las categorías presentes en la barra superior de navegación para descubrir libros organizados según mis intereses personales. | 2 |
| 50 | US11 | Como visitante, quiero dejar mi información para que el equipo de Bookify - Livria me contacte para resolver una duda o trabajar con ellos. | 2 |
| 51 | US36 | Como administrador, quiero ver los detalles completos de un libro en la base de datos para poder gestionarlo adecuadamente. | 2 |
| 52 | US39 | Como administrador, quiero gestionar la adición de libros al carrito de compra para realizar un seguimiento del proceso de compra. | 2 |
| 53 | US42 | Como administrador, quiero acceder a la lista completa de comunidades para tener un control centralizado de las comunidades de la plataforma. | 2 |
| 54 | US45 | Como administrador, quiero poder consultar todos los usuarios registrados para gestionar su acceso y actividad. | 2 |
| 55 | US47 | Como administrador, quiero poder eliminar un usuario que ya no utilizará la plataforma, para mantener la base de datos actualizada. | 2 |
| 56 | US52 | Como administrador, quiero ver estadísticas relevantes sobre los libros en la sección estadísticas en Books, para poder tomar decisiones informadas sobre los libros más populares, más vendidos y otros datos clave del inventario. | 2 |
| 57 | US54 | Como administrador, quiero ver el precio de un libro y su información básica en la sección "Libro de Colección", y acceder a una ventana con más detalles completos del libro, para poder tomar decisiones informadas sobre la gestión de mis productos. | 2 |
| 58 | US62 | Como administrador, quiero tener una barra lateral en el dashboard que contenga la información fundamental de dashboard, para poder navegar de forma rápida y eficiente a las diferentes áreas del sistema. | 2 |
| 59 | US65 | Como usuario, quiero registrarme en la plataforma con un sistema seguro, para crear una cuenta y acceder a mis recursos personales como cliente. | 2 |
| 60 | US08 | Como visitante, quiero tener un acceso directo a la aplicación de Livria, para empezar a utilizar la aplicación. | 1 |
| 61 | US10 | Como visitante, quiero visualizar un apartado en el pie de página con las secciones de la landing page, para retornar a cualquiera de ellas. | 1 |
| 62 | US09 | Como visitante, quiero poder navegar a las redes sociales oficiales de Livria, para mantenerme informado sobre sus novedades y explorar contenido adicional. | 1 |
| 63 | US06 | Como visitante, quiero visualizar un encabezado con las secciones de la landing page, para navegar fácil y rápidamente entre ellas. | 1 |
| 64 | US04 | Como visitante, quiero leer un resumen sobre qué es Livria en el inicio de la página, para entender rápidamente qué producto me ofrece. | 1 |
| 65 | US02 | Como visitante, quiero acceder fácilmente a la sección “Sobre Nosotros”, para conocer la trayectoria de los creadores de Livria, comprender en qué consiste la plataforma y descubrir las funcionalidades que ofrece. | 1 |
| 66 | US01 | Como visitante, quiero ver información relevante sobre las funcionalidades principales que ofrece Livria, para conocer las características únicas de la aplicación. | 1 |

<br><br>

| # Orden | Technical Story ID | Descripción | Story Points (1/2/3/5) |
|:-------:|:-------------:|:------------|:----------------------:|
| 1 | TS01 | Como Developer, debo configurar la conexión segura entre el backend (.NET) y la base de datos MySQL, asegurando que las credenciales estén protegidas con variables de entorno. | 5 |
| 2 | TS02 | Como Developer, debo implementar autenticación basada en tokens JWT para proteger endpoints críticos (ej: gestión de usuarios, pedidos). | 5 |
| 3 | TS04 | omo Developer, debo optimizar las consultas SQL de las tablas cart_items y orders para reducir el tiempo de respuesta en un 30%. | 5 |
| 4 | TS07 | Como Developer, debo crear el endpoint RESTful para el registro de un administrador, el cual recibirá un conjunto de datos como nombre de usuario, correo electrónico, contraseña y PIN de seguridad. Además, debe validar la existencia de los datos y generar un registro en la base de datos de forma segura. | 5 |
| 5 | TS08 | Como Developer, debo crear el endpoint RESTful para el inicio de sesión de un usuario registrado, el cual recibirá las credenciales (nombre de usuario y contraseña) y devolverá un token JWT si son válidas. | 5 |
| 6 | TS10 | Como Developer, debo implementar la generación de un token JWT seguro para los usuarios que inician sesión con credenciales válidas, asegurando que el token tenga una fecha de expiración y un rol asociado. | 5 |
| 7 | TS11 | Como Developer, debo garantizar que las solicitudes a endpoints protegidos requieran un token JWT válido en el encabezado de la solicitud para permitir el acceso. | 5 |
| 8 | TS13 | Como desarrollador, quiero implementar un middleware que controle el acceso a los recursos basado en los roles incluidos en el token JWT, para restringir el acceso según el rol del usuario. | 5 |
| 9 | TS14 | Como desarrollador, quiero integrar el frontend con el backend para gestionar la autenticación de usuarios mediante JWT, asegurando una experiencia de usuario fluida. | 5 |
| 10 | TS17 | Como desarrollador, quiero asegurar que la comunicación entre el frontend y el backend sea segura, utilizando HTTPS y tokens JWT, para proteger los datos del usuario. | 5 |
| 11 | TS16 | Como desarrollador, quiero garantizar que los datos entre el frontend y el backend estén sincronizados, para evitar inconsistencias en la experiencia del usuario. | 5 |
| 12 | TS05 | Como Developer, debo configurar un sistema de logging centralizado para registrar errores en la API (ej: fallos en consultas SQL, requests inválidos). | 5 |
| 13 | TS09 | Como Developer, debo asegurarme de que la API valida correctamente los datos proporcionados en el proceso de registro (nombre de usuario, correo electrónico, contraseña y PIN de seguridad), asegurando que el nombre de usuario y correo electrónico no existan previamente. | 5 |
| 14 | TS03 | Como Developer, debo generar documentación interactiva de los endpoints usando Swagger UI, incluyendo ejemplos de requests/responses y esquemas de datos.| 5 |
| 15 | TS06 | Como Developer, debo habilitar CORS en el backend para permitir solicitudes solo desde los dominios autorizados (ej: https://livriabybookify.netlify.app/). | 5 |
| 16 | TS12 | Como desarrollador, quiero implementar la asignación de roles durante el registro de clientes y administradores, para garantizar que tengan los permisos adecuados según su tipo de cuenta. | 3 |
| 17 | TS15 | Como desarrollador, quiero implementar el manejo de errores de autenticación en el frontend, para informar a los usuarios sobre problemas durante el inicio de sesión o el acceso a recursos. | 3 |
| 18 | TS18 | Como desarrollador, quiero optimizar las solicitudes entre el frontend y el backend, para reducir la latencia y mejorar la experiencia de carga de datos. | 3 |


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

Video explicativo:

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

# CAPÍTULO 5: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
**1. Project Management**

*Descripción:*

La gestión de proyectos es fundamental en el desarrollo de software, ya que permite la organización y estructuración de las tareas necesarias para completar un proyecto. Las herramientas de gestión de proyectos permiten planificar, asignar y realizar un seguimiento de tareas, así como mejorar la colaboración en equipo y la comunicación.
Jira (SaaS):

Jira es una plataforma de gestión de proyectos ampliamente utilizada, especialmente en proyectos de desarrollo de software que siguen metodologías ágiles como Scrum o Kanban. Esta herramienta permite la planificación de sprints, seguimiento de tareas en tiempo real, y la creación de reportes de rendimiento, facilitando la organización y optimización del trabajo en equipo.

https://www.atlassian.com/es/software/jira

<p align="center">
  <img src="https://imgur.com/65HmGqZ.png" alt="Jira" width="250">
</p>

**2. Product UX/UI Design**

*Descripción:*

El diseño de interfaces de usuario (UI) y experiencia de usuario (UX) es esencial para crear aplicaciones y software intuitivos, estéticamente agradables y funcionales. Las herramientas de diseño UX/UI permiten la creación de prototipos visuales, wireframes y diseños interactivos, que pueden validarse con usuarios antes de la implementación.

Figma:

Figma es una herramienta de diseño colaborativo basada en la nube, ideal para la creación de prototipos de interfaces y diseños interactivos. Al estar en línea, permite la edición y revisión en tiempo real, facilitando la colaboración entre miembros del equipo desde cualquier lugar. Es especialmente útil en entornos ágiles donde el diseño y el desarrollo avanzan de manera simultánea.

https://www.figma.com/es-la/

<p align="center">
  <img src="https://imgur.com/Z8QXBFT.png" alt="Figma" width="250">
</p>

**3. Software Development**

*Descripción:*

El desarrollo de software requiere entornos y editores de código donde los desarrolladores puedan escribir, depurar y probar código. Los entornos de desarrollo integrados (IDE) y editores de texto enriquecidos ofrecen características como resaltar sintaxis, la integración de sistemas de control de versiones, y herramientas de depuración, optimizando la productividad del equipo de desarrollo.

Visual Studio Code (Desktop):

Visual Studio Code es un editor de código gratuito desarrollado por Microsoft, reconocido por su flexibilidad, extensibilidad y soporte de múltiples lenguajes de programación. Con una variedad de extensiones, VS Code permite personalizar el entorno de desarrollo para incluir características avanzadas como depuración, control de versiones, y colaboración en tiempo real a través de Live Share.

https://code.visualstudio.com/Download

<p align="center">
  <img src="https://imgur.com/0Vb6vB8.png" alt="VS" width="250">
</p>

**4. Version Control**

*Descripción:*

El control de versiones es un componente esencial en el desarrollo de software, ya que permite gestionar y realizar un seguimiento de los cambios en el código fuente. Facilita la colaboración entre desarrolladores, ya que cada miembro del equipo puede trabajar en una copia del código y posteriormente fusionar los cambios. Esto es especialmente importante en proyectos con múltiples colaboradores, evitando conflictos y manteniendo un historial completo de modificaciones.

*Git (CLI/GUI):*

Git es un sistema de control de versiones distribuido que permite gestionar el código localmente y compartirlo en repositorios remotos. Ofrece la posibilidad de crear ramas para trabajar en diferentes funcionalidades de manera simultánea, y posteriormente unirlas mediante operaciones como merge o rebase.

https://git-scm.com/downloads

<p align="center">
  <img src="https://imgur.com/FSlgo5Z.png" alt="GIT" width="250">
</p>

*GitHub:*

GitHub es una plataforma basada en la nube que utiliza Git para la gestión de repositorios y facilita la colaboración entre equipos de desarrollo. Además de su funcionalidad de control de versiones, GitHub ofrece herramientas adicionales para la revisión de código, seguimiento de problemas y proyectos, e integración continua.

https://github.com/

<p align="center">
  <img src="https://imgur.com/6OimTxR.png" alt="GITHUB" width="250">
</p>

### 5.1.2. Source Code Management
La gestión del código fuente es fundamental para el desarrollo colaborativo de cualquier proyecto de software. En esta sección, se establecerá un esquema claro de organización y control de versiones utilizando GitHub y el modelo de GitFlow. Esto garantizará una estructura organizada, controlada y accesible del código, con pautas para el seguimiento y manejo de cambios. Además, se definirán las convenciones para nombres de ramas, mensajes de commits, y se utilizará Semantic Versioning para las versiones del proyecto.

**1. Establecimiento de repositorios en GitHub:**

Para organizar el código y pruebas de manera eficiente, se crearán repositorios específicos en GitHub, cada uno con una función concreta en el desarrollo y control de calidad del proyecto:

**Repositorios Necesarios:**

*Landing Page:* Este repositorio estará destinado exclusivamente al desarrollo de la página de aterrizaje (Landing Page) de Livria. Contendrá todo el código relacionado con la interfaz inicial del proyecto, incluyendo los archivos HTML, CSS, JavaScript, imágenes y demás recursos Front-End que presenten de manera atractiva y funcional la propuesta de valor de la aplicación a los visitantes.

<p align="center">
  <img src="https://imgur.com/e0huRvR.png" alt="RN1" width="500">
</p>

*Informe acerca del proyecto:* Este repositorio servirá como almacenamiento y control de versiones del informe completo del proyecto Livria. Se incluirán documentos en formato .md, PDF finales, presentaciones y cualquier archivo relacionado con el proceso de documentación, planificación y análisis del proyecto. Permitirá mantener un seguimiento ordenado de los avances en la elaboración del informe.

<p align="center">
  <img src="https://imgur.com/8pRxW5p.png" alt="RN2" width="500">
</p>

*Aplicación web (livria):* Este repositorio contendrá todo el código fuente de la aplicación web Livria, tanto del Front-End como del Back-End. Incluirá estructuras de carpetas organizadas por componentes, rutas, controladores, servicios, así como archivos de configuración, dependencias, bases de datos y pruebas. Este repositorio será el núcleo técnico del desarrollo de la aplicación funcional.

<p align="center">
  <img src="https://imgur.com/pvaLAu7.png" alt="RN3" width="500">
</p>

**Enlaces:**

*Repositorio de la landing page:*

https://github.com/Bookify-Livria/livria.github.io

*Repositorio del informe:*

https://github.com/Bookify-Livria/livria-project-report

*Repositorio de la aplicación web:*

https://github.com/Bookify-Livria/livria-web-app 


**2. Workflow de control de versiones**

Para garantizar que el flujo de trabajo y la integración de cambios sean efectivos y organizados, se implementará el modelo GitFlow. Este modelo establece una estructura de ramas específica que facilita el desarrollo paralelo y la administración de versiones.

*Estructura de ramas en gitflow:*

| Nombre de la rama           | Descripción |
|------------------------------|-------------|
| **Main Branch** (`master`)   | Es la rama principal que contiene el código en estado de producción. Solo los cambios completamente probados y listos para ser liberados en producción se integrarán aquí. |
| **Develop Branch** (`develop`) | En esta rama se integran las funcionalidades en desarrollo. Sirve como base para el trabajo en curso antes de ser incorporado a la `master`. |
| **Feature Branches** (`feature/*`) | Para cada nueva funcionalidad o cambio importante, se debe crear una rama de funcionalidad derivada de `develop`. Esto permite que las funcionalidades se desarrollen de forma aislada. <br> **Ejemplo:** `feature/nueva-funcionalidad` |
| **Release Branches** (`release/*`) | Estas ramas se crean para preparar versiones próximas a lanzarse. Facilitan la corrección de errores menores y las pruebas antes de liberar la versión en `master`. <br> **Ejemplo:** `release/v1.0.0` |
| **Hotfix Branches** (`hotfix/*`) | Ramas utilizadas para aplicar correcciones urgentes en el código de producción. Se crean a partir de `master` y se integran de vuelta en `main` y `develop`. <br> **Ejemplo:** `hotfix/urgent-fix` |

*Convenciones para nombres de ramas*

* Feature Branches: feature/nombre-descriptivo

Nombres que describan claramente la funcionalidad o la tarea en desarrollo.

* Release Branches: release/x.y.z

Siguiendo el Semantic Versioning para indicar la versión en preparación.

* Hotfix Branches: hotfix/nombre-descriptivo

Nombres que describan el tipo de corrección realizada.

**3. Versionado semántico (Semantic Versioning)**

Para mantener un control claro y estructurado de las versiones liberadas, se emplea Semantic Versioning 2.0.0. Esta convención de nomenclatura consiste en tres números: Major.Minor.Patch:
* Major: Indica una versión con cambios que pueden ser incompatibles con versiones anteriores.
* Minor: Utilizado para nuevas funcionalidades que sean compatibles con versiones previas.
* Patch: Para modificaciones menores o correcciones de errores que no alteran la funcionalidad.
 
Ejemplo:

v1.0.0 – Primera versión estable lanzada al público

v1.1.0 – Nueva funcionalidad añadida

v1.1.1. – Pequeña corrección de errores

**4. Convenciones de commits (Conventional Commits)**

Para mantener claridad y consistencia en los mensajes de commit, se utilizará el estándar Conventional Commits. Este sistema ayuda a identificar fácilmente el tipo de cambio realizado en cada commit, lo cual facilita la revisión del historial de cambios y la integración continua. Cada mensaje de commit se estructurará con un tipo de cambio seguido de una breve descripción:

*Tipos de cambios y ejemplos:*
* feat: agregar barra de navegación a la página de inicio

Indica la implementación de una nueva funcionalidad.

* fix: corregir error de validación en formulario de contacto

Para resolver un error.

* docs: actualizar guía de instalación

Modificaciones en la documentación.

* style: mejorar el formato de los archivos CSS

Cambios de estilo que no afectan al código funcional.

* refactor: optimizar la lógica de la función de búsqueda

Cambios de código que no agregan funcionalidades nuevas ni corrigen errores.

* test: añadir pruebas unitarias para la función de autenticación

Añadir o modificar pruebas.

### 5.1.3. Source Code Style Guide & Conventions
Este capítulo establece las pautas y convenciones que el equipo de desarrollo adoptará para garantizar la coherencia y calidad del código en la aplicación Livria. Las convenciones cubrirán los lenguajes utilizados en el proyecto: HTML, CSS, JavaScript, y C#. Además, se seguirá una nomenclatura en inglés para todos los elementos del código, y se tomarán como referencia las mejores prácticas de las siguientes guías:

* HTML Style Guide and Coding Conventions
* Google HTML/CSS Style Guide
* Google JavaScript Style Guide
* MDN JavaScript Guidelines
* W3C JavaScript Style Guide
* C# Coding Conventions
* Microsoft ASP.NET Core Coding Guidelines

Para el desarrollo de la landing page, se han utilizado las tecnologías HTML, CSS y JavaScript para definir la estructura, el diseño y la funcionalidad de nuestra página. La organización y estandarización del código aseguran que el desarrollo sea consistente, fácil de mantener y comprensible para cualquier miembro del equipo que trabaje en el proyecto.

* HTML:

Define la estructura y el contenido de la página, asegurando una semántica adecuada y una jerarquía clara en los elementos para mejorar la accesibilidad y el SEO.

* CSS:

Controla el estilo visual, garantizando un diseño responsive y cohesivo mediante el uso de clases y selectores bien nombrados, evitando el uso de estilos en línea y manteniendo el código modular.

* JavaScript:

Proporciona la interacción y funcionalidad necesarias para mejorar la experiencia del usuario, utilizando funciones y variables descriptivas, y aplicando una estructura lógica que facilite el mantenimiento y escalabilidad.

La adopción de estas convenciones nos permite mantener una base de código ordenada, fácil de comprender y preparada para el crecimiento y la mejora continua del proyecto.

*Principios Generales*
* Todo el código debe estar documentado y usar nomenclatura en inglés.
* La indentación debe ser consistente en todos los archivos.
* El código debe ser fácil de leer y mantener.
* Se debe seguir el principio DRY (Don't Repeat Yourself).

**HTML**

*Convenciones de Formato*

* Utilizar 2 espacios para indentación.

<p align="center">
  <img src="https://imgur.com/LOTPA2i.png" alt="HTML1" width="500">
</p>

* Usar minúsculas para nombres de elementos y atributos.
* Usar comillas dobles para valores de atributos.
* Siempre cerrar todos los elementos HTML, incluso los elementos vacíos.
* Se deben utilizar etiquetas semánticas siempre que sea posible. Ejemplos incluyen: header, footer, main, section, article, nav, etc.
* Los atributos de los elementos HTML deben escribirse en minúsculas. Se deben usar guiones en lugar de mayúsculas o subrayados. Ejemplo: <div class="book-lis¨> en lugar de <div class="BookList¨>.

*Ejemplo general*

<p align="center">
  <img src="https://imgur.com/hnio7mD.png" alt="HTML2" width="500">
</p>

*Estructura del Documento*

* Incluir siempre el doctype HTML5 al comienzo del documento.
* Incluir los atributos lang y charset en el elemento HTML y head respectivamente.
* Cargar CSS en el head y JavaScript justo antes del cierre del /body salvo excepciones justificadas.

<p align="center">
  <img src="https://imgur.com/uuHIoMA.png" alt="HTML3" width="500">
</p>

**CSS**

*Convenciones de formato*

* Utilizar 2 espacios para indentación.
* Incluir un espacio antes de la llave de apertura.
* Colocar la llave de cierre en una nueva línea.
* Incluir un espacio después de los dos puntos de cada declaración.
* Terminar todas las declaraciones con punto y coma.
* Utilizar comillas dobles para valores de string.
* El orden de las propiedades CSS debe seguir un patrón lógico. Se recomienda el siguiente orden:
  * Layout: display, position, top, left, bottom, right, z-index
  * Box model: width, height, padding, margin, border
  * Typography: font-family, font-size, line-height, text-align
  * Color: color, background-color
  * Visual: box-shadow, border-radius, opacity

*Ejemplo general*

<p align="center">
  <img src="https://imgur.com/phx4goM.png" alt="CSS1" width="500">
</p>

Utilizar metodología BEM (Block, Element, Modifier) para nombrar clases.

* Block: .book-card
* Element: .book-card__title
* Modifier: .book-card--featured

Evitar uso excesivo de selectores anidados (no más de 3 niveles).

**JAVASCRIPT**

*Convenciones de formato*

* Utilizar 2 espacios para indentación.
* Usar punto y coma al final de cada declaración.
* Utilizar comillas simples para strings.
* Los nombres de archivos deben estar en kebab-case (ej. book-service.js).

*Ejemplo general*

<p align="center">
  <img src="https://imgur.com/1xfBKAB.png" alt="JS1" width="500">
</p>

*Convenciones de Nomenclatura*

* Variables y funciones: camelCase (bookTitle, getUserPreferences)
* Clases: PascalCase (BookRepository, UserAuthentication)
* Constantes: UPPER_SNAKE_CASE para constantes globales (MAX_RESULTS_PER_PAGE)
* Componentes: PascalCase (BookCard, SearchBar)
* Privados: Usar guión bajo prefijo (_privateMethod, _privateVariable)

*Buenas Prácticas*

* Preferir const sobre let. Usar let solo cuando sea necesario reasignar valores.
* Evitar el uso de var.
* Utilizar funciones de flecha para funciones anónimas en callbacks.
* Usar ES6+ features cuando sea posible (destructuring, spread operator, template literals).
* Preferir métodos de array funcionales (map, filter, reduce) sobre bucles tradicionales.

<p align="center">
  <img src="https://imgur.com/Y22TNJ4.png" alt="JS2" width="500">
</p>

**C#**

*Convenciones de formato*

* Utilizar 4 espacios para indentación.
* Las llaves deben estar en líneas separadas (estilo Allman).
* Usar un espacio entre las palabras clave de control y los paréntesis.
* Limitar la longitud de línea a 120 caracteres.

*Ejemplo general*

<p align="center">
  <img src="https://imgur.com/zAAdQI9.png" alt="c#" width="500">
</p>

*Convenciones de Nomenclatura*

* Interfaces: Prefijo "I" (IBookRepository)
* Clases: PascalCase (BookController, UserService)
* Métodos: PascalCase (GetBookById, UpdateUserProfile)
* Parámetros y variables locales: camelCase (bookId, currentUser)
* Propiedades: PascalCase (Title, Author)
* Campos privados: Prefijo guion bajo y camelCase (_bookRepository)
* Constantes: PascalCase (DefaultPageSize)
* Enums: PascalCase para nombre y miembros (BookCategory, BookCategory.Fiction)

*Buenas Prácticas*

* Usar directivas using para disponer correctamente de recursos.
* Preferir propiedades auto-implementadas cuando no se requiere lógica adicional.
* Utilizar modificadores de acceso explícitos (evitar implícitos).
* Preferir tipos por referencia inmutables cuando sea posible.
* Utilizar la palabra clave var cuando el tipo es evidente.
* Utilizar programación asíncrona con async/await para operaciones de I/O.
* Evitar excepciones para el flujo de control normal.

<p align="center">
  <img src="https://imgur.com/O5Z9AFE.png" alt="c#2" width="500">
</p>

### 5.1.4. Software Deployment Configuration
La Landing Page de nuestro proyecto está disponible públicamente para que los usuarios puedan acceder fácilmente a información relevante y ponerse en contacto con el equipo. A continuación, se detallan dos métodos para acceder al sitio.

**Opción 1: Acceso Directo a través de GitHub Pages**

La forma más sencilla de visualizar la Landing Page es a través de GitHub Pages. Simplemente haz clic en el siguiente enlace: 

https://bookify-livria.github.io/livria.github.io/ 

Este método es rápido y no requiere ninguna instalación ni configuración adicional.

**Opción 2: Despliegue Manual**

**1. Acceder al Repositorio en GitHub**

Dirígete al repositorio en GitHub en este enlace:

https://github.com/Bookify-Livria/livria.github.io 

<p align="center">
  <img src="https://imgur.com/8xC1Ze1.png" alt="op21" width="500">
</p>

**2. Descargar el Proyecto**

Haz clic en el botón verde “Code”.

Selecciona “Download ZIP” para descargar el proyecto en formato .zip.

<p align="center">
  <img src="https://imgur.com/jJCZmqj.png" alt="SDC1" width="500">
</p>

**3. Descomprimir el Archivo**

Localiza el archivo .zip que descargaste en tu computadora.

Haz clic derecho sobre el archivo y selecciona “Extraer todo” o usa un software de descompresión para descomprimirlo en una carpeta de tu elección.

<p align="center">
  <img src="https://imgur.com/pruPma0.png" alt="SDC2" width="500">
</p>

**4. Visualizar la Landing Page**

Navega hasta la carpeta donde descomprimimos el archivo.

Busca y abre el archivo index.html en tu navegador web favorito (Chrome, Firefox, Brave, etc.).

<p align="center">
  <img src="https://imgur.com/flp2TaP.png" alt="SDC2" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/RpvHkn9.png" alt="op42" width="500">
</p>

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning
El Sprint Planning es la reunión que da inicio al sprint y define qué se va a construir y cómo se logrará. Reúne al equipo Scrum para establecer un objetivo claro (Sprint Goal), seleccionar las historias de usuario más relevantes y descomponerlas en tareas concretas. Esta planificación asegura un enfoque común, organiza el trabajo de forma eficiente y alinea al equipo con la entrega de valor al usuario.

A continuación se mostrará la tabla del Sprint Planning:

| Sprint # | Sprint 1 |
|---------|-----------|
| **Sprint Planning Background** | |
| **Date** | 2025-04-07 |
| **Hour** | 02:40 PM |
| **Location** | Virtual |
| **Prepared By** | Ainhoa Lucía Castillo Garay, Marcelo Alejandro Indo Arbañil |
| **Attendees (to planning meeting)** | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Indo Arbañil / Gabriel Sebastián Borja Molina / Jhosep Jamil Argomedo Camacho / Melisa Geraldine Solis Suárez |
| **Sprint n - 1 Review Summary** | Durante el Sprint, se desarrollaron once historias de usuario enfocadas en la construcción de la landing page, lo que permitió ofrecer una vista inicial sólida de la plataforma. El equipo de desarrollo, conformado por Gabriel Borja, Jhosep Argomedo y Melisa Solís, destacó que la correcta asignación de Story Points y la claridad en las tareas permitió mantener un ritmo de trabajo constante. La diseñadora UX/UI, Ainhoa Castillo, señaló que la estructura modular facilitó la disposición visual del producto final. Marcelo Indo, expresó satisfacción general con los resultados, resaltando el alineamiento del diseño con los objetivos de marca y la buena experiencia de usuario. |
| **Sprint n - 1 Retrospective Summary** | Durante el Sprint, el equipo destacó como aciertos la buena organización de tareas, la correcta asignación de tiempos mediante Story Points y una comunicación fluida que permitió resolver bloqueos rápidamente. También se valoró el enfoque colaborativo al definir criterios de aceptación. Como oportunidad de mejora, se identificó la necesidad de ajustar mejor los tiempos estimados en tareas visibles y optimizar las reuniones de revisión para centrarse más en los aprendizajes y el feedback del product owner. |
| **Sprint Goal & User Stories** | |
| **Sprint Goal** | Our focus is on delivering a fully functional and visually engaging landing page that introduces Lirvia’s core services and enables intuitive navigation between key informational sections. We believe it delivers clarity and trust to potential users and collaborators by helping them understand what Lirvia offers and how to get in touch or access services. <br><br> This will be confirmed when the user can navigate the page easily, access all core sections like “Sobre Nosotros” and “Conctactenos”, switch languages, and engage with external links such as social media and privacy policy. |
| **Sprint Velocity** | 15 |
| **Sum of Story Points** | 15 |

#### 5.2.1.2. Aspect Leaders and Collaborators
Durante el desarrollo del Sprint, se han identificado distintos aspectos funcionales relacionados al diseño y construcción de la Landing Page de la aplicación web Livria. Con el objetivo de organizar el trabajo del equipo de manera eficiente, se ha elaborado una matriz de Liderazgo y Colaboración (LACX), donde se asigna a cada integrante el rol de líder (L) en uno de los aspectos clave del desarrollo, y el rol de colaborador (C) en otros aspectos.

Los aspectos definidos para este Sprint son:

1. Home de la landing page
2. Sección de servicios
3. Sección sobre nosotros
4. Sección de contacto y pie de página
5. Revisión general, mejoras y adaptación responsive

| Team Member (Last Name, First Name) | GitHub Username | Hero section | Services section | About us section | Contact and footer section | Review, Improvements, and responsive |
|-------------------------------------|-----------------|--------------|------------------|------------------|----------------------------|--------------------------------------|
| Castillo Garay, Ainhoa Lucía | noaa01100001 | C | C | C | C | L |
| Binda Arbañil, Marcelo Alejandro | MarceloHkd | C | L | C | C | C |
| Borja Molina, Gabriel Sebastián | borj410 | C | C | L | C | C |
| Argomedo Camacho, Jhosep Jamil | JhosepAC | L | C | C | C | C |
| Sulca Silva, Melisa Geraldine | MSS02204 | C | C | C | L | C |

#### 5.2.1.3. Sprint Backlog 1
Durante el Sprint 1, el objetivo principal fue construir la versión inicial de la landing page con un enfoque en claridad, accesibilidad y navegación fluida. Se buscó ofrecer una experiencia informativa que permita a los usuarios entender de inmediato el propósito de la plataforma, explorar las secciones clave como “Sobre Nosotros” y “Contáctanos”, y acceder fácilmente a la aplicación y sus redes sociales. Este primer paso fue clave para establecer una imagen sólida de Livria y captar el interés de nuevos usuarios desde el primer contacto.

|      Sprint #     |  Sprint #1 |                 |                        |                 |                                                           |
|-------------------|------------|-----------------|------------------------|-----------------|-----------------------------------------------------------|
|    1     | **Work-Item / Task** |                 |                        |                 |                                                           |
| **User Story ID** |   **Id**   | **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / InProcess / To-Review/Sprint# / Done)** |
| US01 | 1 | Redactar contenido atractivo sobre funcionalidades principales | 2 | Developer Team | Done |
|      | 2 | Diseñar e implementar sección de servicios en landing | 2 | Developer Team | Done |
| US02 | 1 | Maquetar y diseñar contenido de “Sobre Nosotros” | 1 | Developer Team | Done |
|      | 2 | Implementar navegación a “Sobre Nosotros” desde menú | 1 | Developer Team | Done |
| US03 | 1 | Implementar botón de cambio de idioma | 1 | Developer Team | Done |
|      | 2 | Integrar traducción automática del contenido | 2 | Developer Team | Done |
| US04 | 1 | Redactar descripción corta de Lirvia para la sección ‘Home’ | 1 | Developer Team | Done |
|      | 2 | Maquetar y aplicar diseño a sección principal | 1 | Developer Team | Done |
| US05 | 1 | Diseñar sección “Contáctanos” con campos básicos | 1 | Developer Team | Done |
|      | 2 | Programar funcionalidad de envío de mensaje | 3 | Developer Team | To-do |
| US06 | 1 | Implementar encabezado de navegación con links | 1 | Developer Team | Done |
|      | 2 | Probar navegación responsiva entre secciones | 1 | Developer Team | Done |
| US07 | 1 | Diseñar layout visual atractivo (colores, tipografía, imágenes) | 2 | Developer Team | Done |
|      | 2 | Adaptar diseño responsivo a distintos dispositivos | 2 | Developer Team | Done |
| US08 | 1 | Crear e insertar botón de acceso directo a la aplicación web | 1 | Developer Team | To-do |
| US09 | 1 | Insertar íconos y enlaces a redes sociales | 1 | Developer Team | Done |
| US10 | 1 | Diseñar footer con navegación rápida a secciones | 2 | Developer Team | Done |
| US11 | 1 | Crear formulario básico (nombre, email, mensaje) | 1 | Developer Team | Done |
|      | 2 | Integrar backend ligero para captura de datos | 2 | Developer Team | To-do |

#### 5.2.1.4. Development Evidence for Sprint Review
Esta sección presenta los principales avances en la implementación técnica del proyecto realizados durante el sprint, en función de los productos comprometidos: Landing Page, Aplicación Web y Servicios Web. Se detalla el progreso alcanzado a través de los repositorios utilizados por el equipo, identificando los commits relevantes que evidencian el desarrollo de funcionalidades, corrección de errores, mejoras en la interfaz y configuración de servicios. Esta evidencia permite evaluar el cumplimiento de los objetivos del sprint y facilita la retroalimentación en la reunión de revisión.

|   Repository  |   Branch  |   Commit Id  |   Commit Message  |   Commit Message Body  |   Commited on (Date)  |
|---------------|-----------|--------------|-------------------|------------------------|-----------------------|
|   JhosepAC/Bookify-Livria  |   feature/home-page  |   1c1c4d2  |   feat: implement initial Home section layout  |   ---  |   20/04/2025  |
|   MarceloHkd/Bookify-Livria  |   feature/home-page  |   4a23b17  |   feat: add services section to the home page  |   ---  |   22/04/2025  |
|   borj410/Bookify-Livria  |   feature/home-page  |   2c63a2c  |   feat: add about us section with content and layout  |   ---  |   22/04/2025  |
|   MSS02204/Bookify-Livria  |   feature/home-page  |   03a59a8  |   feat: add contact section and footer to the home page  |   ---  |   23/04/2025  |
|   noaa01100001/Bookify-Livria  |   feature/home-page  |   092342b  |   feat: fix bugs, update elements and responsive design  |   - Fixed taskbar positioning - Updated the header font and letter spacing - Updated title and content of the third service card - Added images in the services section - Improved responsive design in "About Us" and "Hero" section - Designed custom scrollbar style - Modified card design for services section  |   25/04/2025  |

#### 5.2.1.5. Execution Evidence for Sprint Review
Durante el Sprint 1, se desarrollaron once historias de usuario enfocadas en la construcción de la landing page de Livria, con énfasis en la navegación, el contenido visual y la estructura modular de las secciones “Sobre Nosotros”, “Contáctanos”, “Servicios”, “Home” y “Footer”.

El equipo cumplió con todos los entregables planeados excepto tres tareas que quedaron pendientes (formulario funcional, botón de app, y backend del formulario). Se logró un diseño responsive funcional, una experiencia de navegación fluida y alineación con los objetivos de la marca.

**Evidencia visual:**

A continuación, se presentan capturas de pantalla de las vistas implementadas en este Sprint:

1. Home Page (Hero Section)

*Desarrollado por: Jhosep Argomedo*

<p align="center">
  <img src="https://imgur.com/Q0nc0cT.png" alt="HPHS1" width="500">
</p>

2. Sección de servicios

*Desarrollado por: Marcelo Binda*

<p align="center">
  <img src="https://imgur.com/SJ5rtth.png" alt="SS1" width="500">
</p>

3. Sección Sobre Nosotros

*Desarrollado por Gabriel Borja*

<p align="center">
  <img src="https://imgur.com/XXAj4ya.png" alt="SN1" width="500">
</p>

4. Sección de Contacto y Footer

*Desarrollado por: Melisa Sulca*

<p align="center">
  <img src="https://imgur.com/oaXA9E2.png" alt="SCF1" width="500">
</p>

5. Correcciones de diseño/código y vista responsive general

*Desarrollado por: Ainhoa Castillo*

<p align="center">
  <img src="https://imgur.com/C63RF6H.png" alt="CORRE1" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/fkDsCUA.png" alt="CORRE2" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/0wvF7bt.png" alt="CORRE3" width="500">
</p>

**Video del Sprint Review:** https://youtu.be/bjdfFpCnZxo

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Durante este Sprint, el equipo de desarrollo enfocó sus esfuerzos en la construcción y diseño de la landing page.

Dado que el alcance de este Sprint se centró exclusivamente en el desarrollo de la interfaz web estática, no se ha implementado servicios web (API RESTful) ni se han generado endpoints que requieran documentación técnica con herramientas como OpenAPI.

La documentación de servicios web, incluyendo la definición de endpoints, métodos HTTP (GET, POST, PUT, DELETE), parámetros (parameters), respuestas (responses) y ejemplos de interacción (interaction examples), está prevista para Sprints posteriores. Cuando se avance con la implementación del backend y la lógica de servicios, se utilizará OpenAI (Swagger) para su documentación correspondiente, incluyendo con datos de ejemplo y evidencia visual del funcionamiento de los endpoints.

En futuras iteraciones, esta sección incluirá:

* Tabla de endpoints implementados.
* Métodos HTTP soportados por cada acción.
* Parámetros esperados y ejemplos de respuesta.
* Enlaces a la documentación desplegada con Swagger UI.
* Capturas de pantalla de la interacción con los endpoints.
* Referencia a los commits relacionados con la documentación técnica.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Durante este Sprint, el equipo llevó a cabo el proceso de despliegue inicial de la landing page del proyecto.

**Actividades realizadas:**

*1. Creación del repositorio en GitHub*

* Se creó un repositorio público bajo la organización del proyecto, alojado en: https://github.com/Bookify-Livria/livria.github.io 
* El nombre del repositorio está configurado específicamente para usar GitHub Pafes como medio de despliegue automático

*2. Configuración de GitHub Pages*

* Se configuró GitHub Pages directamente desde la pestaña pages del repositorio.
* Se seleccionó la rama main como fuente, y la carpeta raíz (/root) como origen de contenido.
* Esta configuración permite que el sitio esté disponible de forma pública en la siguiente URL: https://bookify-livria.github.io/livria.github.io/ 

<p align="center">
  <img src="https://imgur.com/isNoumJ.png" alt="FINAL1" width="500">
</p>

*3. Automatización del despliegue*

* GitHub Pages actualiza automáticamente el contenido del sitio web cada vez que se realiza un nuevo push a la rama main. Esto garantiza una integración continua entre los cambios de desarrollo y la versión desplegada. 

*4. Verificación de despliegue*

* Se realizaron pruebas visuales y funcionales para validar que la página se visualiza correctamente en distintos navegadores y dispositivos.

Durante este Sprint, no se realizó despliegue de Web Applications ni Web Services, ya que el desarrollo de backend e interfaces dinámicas está programado para Sprints posteriores. 

Sin embargo, este avance permite visibilizar el proyecto y facilitar futuras integraciones con frontend dinámico y servicios web.

#### 5.2.1.8. Team Collaboration Insights during Sprint
Durante este Sprint, el equipo se enfocó en la implementación de la landing page del proyecto Livria, abordando tareas como el diseño visual, estructura de contenido, maquetado HTML/CSS y funciones con JavaScript, así como la integración con GitHub Pages para su despliegue. Todos los miembros del equipo participaron activamente en la construcción de este primer producto.

**Actividades de implementación:**

* Se definió el diseño de la landing page desde Figma, permitiendo una planificación clara del contenido y la experiencia de usuario.
* Posteriormente, se desarrolló la estructura con HTML5 y se aplicaron estilos con CSS3.
* Asimismo, se añadieron funcionalidades con JavaScript.
* Se configuró el repositorio en GitHub, incluyendo ramas de desarrollo, documentación y recursos multimedia.
* Se realizaron revisiones entre miembros del equipo para asegurar la calidad visual semántica del código.

**Análitica de colaboración en GitHub:**

A continuación, se presenta evidencia visual de la participación de todos los integrantes del equipo a través de:

1. Historial de commits por miembro

*Desarrollados por: Jhosep Argomedo*

<p align="center">
  <img src="https://imgur.com/DhhGQc4.png" alt="FINAL2" width="500">
</p>

*Desarrollados por: Marcelo Binda*

<p align="center">
  <img src="https://imgur.com/arwwc2q.png" alt="FINAL3" width="500">
</p>

*Desarrollados por: Gabriel Borja*

<p align="center">
  <img src="https://imgur.com/CgF4jBM.png" alt="FINAL4" width="500">
</p>

*Desarrollados por: Ainhoa Castillo*

<p align="center">
  <img src="https://imgur.com/c6RSFRO.png" alt="FINAL5" width="500">
</p>

*Desarrollados por: Melisa Sulca*

<p align="center">
  <img src="https://imgur.com/8RvUxTN.png" alt="FINAL6" width="500">
</p>

2. Colaboradores activos en el repositorio

<p align="center">
  <img src="https://imgur.com/WUN2eOi.png" alt="FINAL7" width="500">
</p>

3. Histograma de contribuciones en el tiempo

<p align="center">
  <img src="https://imgur.com/Tqdgqf6.png" alt="FINAL8" width="500">
</p>

**Nota:** Marcelo Binda también ha participado en el desarrollo de la Landing Page, no obstante, por un problema de usuario el repositorio no lo ha considerado en las estadísticas. Pero, se puede ver su aporte en las anteriores evidencias (Historial de commits por miembro).

### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning
El Sprint Planning es la reunión que da inicio al sprint y define qué se va a construir y cómo se logrará. En esta reunión el equipo Scrum estableció tareas a cada integrante para desarrollar las siete historias relevantes seleccionadas para la aplicación web.

A continuación se mostrará la tabla del Sprint Planning:

| Sprint # | Sprint 2 |
|---------|-----------|
| **Sprint Planning Background** | |
| **Date** | 2025-04-29 |
| **Hour** | 05:30 PM |
| **Location** | Virtual |
| **Prepared By** | Ainhoa Lucía Castillo Garay, Marcelo Alejandro Indo Arbañil |
| **Attendees (to planning meeting)** | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Indo Arbañil / Gabriel Sebastián Borja Molina / Jhosep Jamil Argomedo Camacho / Melisa Geraldine Solis Suárez |
| **Sprint n - 2 Review Summary** | Durante el Sprint, se desarrollaron 18 historias de usuario enfocadas en el apartado de Frontend de la aplicación web, lo que nos permitió establecer una visión clara de las funcionalidades clave a desarrollar dentro de nuestra plataforma. El equipo de desarrollo, conformado por Gabriel Borja, destacó que la adecuada distribución de tareas permitió realizar una colaboración exitosa y mantener un ritmo de trabajo estable. La diseñadora UX/UI, Ainhoa Castillo, señaló que la elaboración de un diseño que integra estética y funcionalidad facilitó el proceso de implementación. El product owner, Marcelo Binda, expresó satisfacción general, destacando el moderno e intuitivo diseño de la interfaz, que invita al usuario a explorar el servicio y mejora su experiencia de interacción. |
| **Sprint n - 2 Retrospective Summary** | Durante el Sprint, el equipo destacó como aciertos la adecuada organización de tareas y la comunicación eficiente entre miembros del equipo de desarrollo. Se lograron avances significativos en el desarrollo de la aplicación web. Se completó el desarrollo de funcionalidades clave, tales como la visualización del catálogo a través de la pantalla principal, la implementación de la interfaz de compra y el sistema de registro e inicio de sesión. Para el siguiente sprint, se debe buscar lograr optimizar los procesos involucrados, realizar correcciones de errores menores e implementar el apartado de backend. |
| **Sprint Goal & User Stories** | |
| **Sprint Goal** | Our focus is on developing and implementing the core frontend functionalities of the web application, focusing on user interface design and initial user interaction flows such as catalog visualization, purchase interface, and login/registration screens. We believe it delivers a solid visual and functional foundation for the platform, allowing users to intuitively explore the service while setting the stage for backend integration in upcoming sprints. <br><br> This will be confirmed when users can navigate through the main interface, view the catalog, access the purchase section, and complete registration or login actions using the developed frontend components. |
| **Sprint Velocity** | 50 |
| **Sum of Story Points** | 48 |

#### 5.2.2.2. Aspect Leaders and Collaborators
Durante el desarrollo del Sprint 2, se han identificado distintos aspectos funcionales relacionados al diseño y construcción de la aplicación web de Livria. Con el objetivo de organizar el trabajo del equipo de manera eficiente, se ha elaborado una matriz de Liderazgo y Colaboración (LACX), donde se asigna a cada integrante el rol de líder (L) en uno de los aspectos clave del desarrollo, y el rol de colaborador (C) en otros aspectos.

Los aspectos definidos para este Sprint son:

1. Home de la aplicación web
2. Sección de recomendaciones
3. Secciones de libros
4. Sección de comunidad
5. Sección de cuenta de usuario
6. Sección de carrito
7. Sección de orden
8. Sección de suscripción
9. Sección de notificaciones
10. Revisión general y mejoras

| Team Member (Last Name, First Name) | GitHub Username | Home Page | Recommendations section | Books section | Community section | User account | Cart section | Order section | Suscription section | Notification section | Review and improvements |
|-------------------------------------|-----------------|--------------|------------------|------------------|----------------------------|--------------------------------------|------------------|------------------|------------------|------------------|------------------|
| Castillo Garay, Ainhoa Lucía | noaa01100001 | L | C | C | L | C | C | L | C | C | L |
| Binda Arbañil, Marcelo Alejandro | MarceloHkd | C | L | L | L | C | C | C | L | C | C |
| Borja Molina, Gabriel Sebastián | borj410 | C | C | C | C | L | C | C | C | C | C |
| Argomedo Camacho, Jhosep Jamil | JhosepAC | C | - | - | C | - | - | - | - | C | C |
| Sulca Silva, Melisa Geraldine | MSS02204 | C | - | - | - | - | - | - | - | L | C |

#### 5.2.2.3. Sprint Backlog 2
Durante el Sprint 2, nos enfocamos en la implementación de tareas para mejorar la experiencia del usuario en la app web. Además, se busca mejorar la interfaz de usuario, optimizar el proceso de compra de libros, permitir interacciones dentro de comunidades literarias y facilitar el proceso de pago. Las tareas incluyen la creación de interfaces intuitivas, el proceso de compra de un libro, y la implementación de funcionalidades para recomendaciones personalizadas y la valoración de libros. Al finalizar este sprint, se espera tener una plataforma funcional que permita a los usuarios navegar de manera eficiente, realizar compras y participar en comunidades literarias.

|      Sprint #     |  Sprint #2 |                 |                        |                 |                                                           |
|-------------------|------------|-----------------|------------------------|-----------------|-----------------------------------------------------------|
|    1     | **Work-Item / Task** |                 |                        |                 |                                                           |
| **User Story ID** |   **Id**   | **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / InProcess / To-Review/Sprint# / Done)** |
| US17 | 1 | Visualización de la pantalla de las recomendaciones personalizadas. | 3 | Developer Team | Done |
|      | 2 | Acceso al libro recomendado por la aplicación. | 3 | Developer Team | Done |
| US27 | 1 | Diseño de la funcionalidad para crear nuevas reseñas y realizar valoraciones. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad para que los usuarios puedan escribir reseñas de cualquier libro en la aplicación. | 2 | Developer Team | Done |
|      | 3 | Implementar la funcionalidad para que los usuarios puedan realizar valoraciones de cualquier libro. | 2 | Developer Team | To-do |
| US16 | 1 | Diseño del inicio de sesión y registro de un usuario. | 4 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad del registro de un nuevo usuario. | 3 | Developer Team | Done |
|      | 3 | Implementar la funcionalidad del inicio de sesión de un usuario registrado. | 3 | Developer Team | Done |
| US19 | 1 | Implementación de la funcionalidad de cierre de sesión. | 2 | Developer Team | Done |
| US28 | 1 | Diseño de la pantalla de suscripción al Plan Community. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de cambio de plan (actualización) al Plan Community. | 3 | Developer Team | Done |
|      | 3 | Diseño de la confirmación del pago del Plan Community. | 1 | Developer Team | Done |
|      | 4 | Implementar la funcionalidad de reversión al plan gratuito. | 3 | Developer Team | To-do |
| US30 | 1 | Darle a conocer al usuario que la transacción es segura y privada por medio de la aplicación. | 2 | Developer Team | Done |
| US14 | 1 | Diseño del apartado de notificaciones. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de confirmación de envío de notificaciones. | 3 | Developer Team | Done |
| US20 | 1 | Diseño del apartado de publicaciones en comunidades. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de creación de publicaciones. | 4 | Developer Team | Done |
| US21 | 1 | Diseño del apartado de comunidades. | 4 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de creación de comunidades. | 3 | Developer Team | Done |
|      | 3 | Implementar la funcionalidad de unirse a una comunidad existente. | 4 | Developer Team | To-do |
| US22 | 1 | Diseño de comentarios en las publicaciones | 2 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de creación de un nuevo comentario. | 3 | Developer Team | Done |
|      | 3 | Implementar la funcionalidad de eliminar un comentario existente. | 3 | Developer Team | Done |
| US23 | 1 | Diseño de carrito de compra. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de carrito de compra. | 4 | Developer Team | Done |
|      | 3 | Diseño de orden de compra de un libro digital. | 2 | Developer Team | Done |
|      | 4 | Diseño de orden de compra de un libro físico. | 2 | Developer Team | Done |
|      | 5 | Diseño del pedido de compra. | 3 | Developer Team | Done |
|      | 6 | Implementar la funcionalidad del pedido de compra. | 3 | Developer Team | Done |
| US24 | 1 | Diseño de la pantalla de búsqueda. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de búsqueda de libros específicos y autores. | 4 | Developer Team | Done |
|      | 3 | Implementar la funcionalidad de búsqueda sin coincidencias exactas. | 2 | Developer Team | Done |
| US25 | 1 | Diseño de la pantalla de gestión de envío de libros físicos. | 2 | Developer Team | Done |
|      | 2 | Diseño de la confirmación de entrega del libro en el perfil. | 1 | Developer Team | Done |
| US26 | 1 | Diseño de la pantalla de pago exitoso. | 2 | Developer Team | Done |
|      | 2 | Diseño de la pantalla de pago erróneo. | 3 | Developer Team | To-do |
| US33 | 1 | Diseño de la pantalla de filtrado de libro con respecto al género seleccionado. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad de filtrado de libro con respecto a la género seleccionado. | 4 | Developer Team | Done |
| US34 | 1 | Implementar la funcionalidad para filtrar libros según los criterios del usuario. | 3 | Developer Team | Done |
|      | 2 | Implementar la funcionalidad para filtrar libros con respecto al idioma seleccionado. | 2 | Developer Team | Done |
|      | 3 | Implementar la funcionalidad de borrado de filtros aplicados. | 2 | Developer Team | Done |
| US29 | 1 | Acceso sin interrupciones a la aplicación. | 1 | Developer Team | Done |
| US31 | 1 | Diseño general de la aplicación. | 3 | Developer Team | Done |
|      | 2 | Navegación clara y sencilla. | 3 | Developer Team | Done |



#### 5.2.2.4. Development Evidence for Sprint Review
En este capítulo se presenta el progreso alcanzado durante el Sprint 2 en el desarrollo de la aplicación web. A través de la colaboración del equipo y el enfoque ágil, hemos avanzado en la implementación de funcionalidades clave y mejoras de la interfaz de usuario. Este sprint ha permitido consolidar una base sólida para el desarrollo posterior y asegurar que se cumplen los objetivos establecidos.

|   Repository  |   Branch  |   Commit Id  |   Commit Message  |   Commit Message Body  |   Commited on (Date)  |
|---------------|-----------|--------------|-------------------|------------------------|-----------------------|
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   c6e6d79  |   docs: add initial README for Livria Web App  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app  |   feature/home-page  |   5633e05  |   feat: add toolbar, language-switcher and footer  |   ---  |   22/04/2025  |
|   https://github.com/Bookify-Livria/livria-web-app  |   feature/home-page  |   7192f1d  |   Merge pull request #1 from Bookify-Livria/feature/public-components  |   ---  |   22/04/2025  |
|   https://github.com/Bookify-Livria/livria-web-app  |   feature/home-page  |   be9381c  |   feat: Add Book-Card  |   ---  |   23/04/2025  |
|   https://github.com/Bookify-Livria/livria-web-app  |   feature/home-page  |   190addf  |   feat: Show Book-Card  |   ---  |   23/04/2025  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   f265946  |   feat: add book carousel  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   7f67b28  |   feat: create singular book view and created cart component  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   daec93d  |   feat: update general components  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   5ae1391  |   eat: update general components  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   5934510  |   Merge branch 'feature/books' of https://github.com/Bookify-Livria/livria-web-app into feature/books  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   1b54c31  |   feat: Update register and login  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   69586a9  |   fix: final improvements  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   a9298ae  |   Update shop.component.vue  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   d1fd39d  |   Merge pull request #2 from Bookify-Livria/hotfix/urgent-fix  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   efc6af4  |   Update shop.component.vue  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   a61f5c4  |   Merge pull request #3 from Bookify-Livria/hotfix/urgent-fix  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   538e6cb  |   Merge pull request #4 from Bookify-Livria/develop  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   be9381c  |   feat: Add: Book-Card  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   190addf  |   feat: Show: Book-Card  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   f265946  |   feat: add book carousel  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   64ed3e8  |   feat: create reviews per book  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   555e41c  |   feat: add images for every community  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   ac57ed9  |   feat: Create Card  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   0504e7e  |   feat: Create Order  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   5fd0218  |   feat: update cart drawer and toolbar component  |   ---  |   15/05/25  |
|   https://github.com/Bookify-Livria/livria-web-app   |   feature/home-page  |   11edefe  |   feat: update user components and implementation of notifications  |   ---  |   15/05/25  |


#### 5.2.2.5. Execution Evidence for Sprint Review
Durante el Sprint 2, se desarrollaron 17 historias de usuario centradas en la implementación de la aplicación web de Livria. Este sprint se enfocó en crear funcionalidades clave como la navegación entre libros, la integración de comunidades literarias, el proceso de compra y la personalización de recomendaciones de libros. Las historias incluyen tanto el diseño de interfaces de usuario como la implementación de funciones como la compra de libros, la creación de comunidades y la interacción con la sección de comentarios.

El equipo completó con éxito todas las tareas planificadas, excepto las valoraciones de libros y las recomendaciones personalizadas, que aún están pendientes. Además, se logró un diseño responsive para todas las secciones clave de la aplicación, con una experiencia de usuario fluida, funcional y alineada con los objetivos estratégicos de la plataforma.

**Evidencia visual:**

A continuación, se presentan capturas de pantalla de las vistas implementadas en este Sprint: 

*Interfaz de iniciar sesión*

<p align="center">
  <img src="https://imgur.com/0g176aR.png" alt="EE21" width="500">
</p>

*Interfaz de registro:*

<p align="center">
  <img src="https://imgur.com/xXrHzE8.png" alt="EE22" width="500">
</p>

*Interfaz principal (Home):*

<p align="center">
  <img src="https://imgur.com/24U8gSl.png" alt="EE23" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/H0pajZ8.png" alt="EE24" width="500">
</p>

*Sección de recomendaciones personalizadas:*

<p align="center">
  <img src="https://imgur.com/IxbPhvf.png" alt="EE25" width="500">
</p>

*Sección de categoría “literatura”:*

<p align="center">
  <img src="https://imgur.com/EUcx8TS.png" alt="EE26" width="500">
</p>

*Sección de categoría “no ficción”*

<p align="center">
  <img src="https://imgur.com/trTUaDd.png" alt="EE27" width="500">
</p>

*Sección de categoría “ficción”*

<p align="center">
  <img src="https://imgur.com/U9nlDPQ.png" alt="EE28" width="500">
</p>

*Sección de categoría “mangas y comics”*

<p align="center">
  <img src="https://imgur.com/xC0Oo1Q.png" alt="EE29" width="500">
</p>

*Sección de categoría “juvenil”*

<p align="center">
  <img src="https://imgur.com/jv3JN5e.png" alt="EE210" width="500">
</p>

*Sección de categoría “infantil”*

<p align="center">
  <img src="https://imgur.com/MtDtnLg.png" alt="EE211" width="500">
</p>

*Sección de categoría “ebooks y audiolibros”*

<p align="center">
  <img src="https://imgur.com/KJ5hdQH.png" alt="EE212" width="500">
</p>

*Interfaz de detalles de libros:*

<p align="center">
  <img src="https://imgur.com/mwQ7kLb.png" alt="EE213" width="500">
</p>

*Interfaz de tienda física:*

<p align="center">
  <img src="https://imgur.com/BIinlh9.png" alt="EE214" width="500">
</p>

*Interfaz de notificaciones:*

<p align="center">
  <img src="https://imgur.com/KiFPCTB.png" alt="EE215" width="500">
</p>

*Interfaz de cuenta:*

<p align="center">
  <img src="https://imgur.com/cfFHARq.png" alt="EE216" width="500">
</p>

*Interfaz de carro de compras:*

<p align="center">
  <img src="https://imgur.com/xfW0Qrw.png" alt="EE217" width="500">
</p>

*Interfaz de iniciar compras:*

<p align="center">
  <img src="https://imgur.com/zOIQTNE.png" alt="EE218" width="500">
</p>

*Interfaz de comunidades:*

<p align="center">
  <img src="https://imgur.com/XMmPE4v.png" alt="EE219" width="500">
</p>

*Interfaz de detalle comunidades:*

<p align="center">
  <img src="https://imgur.com/xvZst7H.png" alt="EE220" width="500">
</p>

Video del Sprint Review 2: https://youtu.be/D3Qu6SNdWEk

#### 5.2.2.6. Services Documentation Evidence for Sprint Review
Durante el Sprint 2, el desarrollo del frontend de Livria para las funcionalidades del catálogo de libros, carrito de compra, orden de compra, comunidades, notificaciones y suscripciones se implementó con la API fake. La API está localizada en la carpeta server y dentro se encuentra el archivo db.json, en el cual contiene toda la información de los datos utilizados. Además, estas fakes API logran simular una base de datos sin tenerla de verdad. 

|  Endpoint Simulado (Fake API)  |  Entidad Principal Gestionada  |  Operaciones CRUD Soportadas (Simuladas) vía JSON Server  |  Futuro Alcance con OpenAPI  |
|---------------|-----------|--------------|-------------------|
|  http://localhost:3000/books   |  Libros(Books)  |  GET, PUT (para reviews)  |   Documentación para obtener información de los libros, de los reviews, poder realizar una búsqueda de libros y poder recomendar libros personalizados.   |
|  http://localhost:3000/communities    |  Comunidades (Communities)  |  GET, PUT (para posts)  |  Documentación para obtener información de las comunidades, los posts y para la creación de las comunidades.    |
|  http://localhost:3000/notificaciones    |  Notificaciones (Notifications)  |  GET, POST, DELETE (por ID)  |   Documentación para gestionar las notificaciones cuando se inicia sesión, al momento de crear una orden, activar un plan de suscripción y recibir likes en tus respectivos posts.    |
|  http://localhost:3000/cart    |  Carrito de Compra (cart)  |  GET, POST, DELETE (por ID)  |   Documentación para gestionar los libros seleccionados para posible elección de compra.   |
|  http://localhost:3000/order   |  Orden de Compra (Order)  |  GET, POST(por ID)  |   Documentación para gestionar el proceso de compra como la confirmación de orden y la finalización de compra.   |
|  http://localhost:3000/users   |  Usuarios (Users)  |  GET, POST, PUT, DELETE (para Login, order)  |   Documentación para la información detallada de cada persona registrada en la aplicación web.   |
|  http://localhost:3000/userlogin   |  Inicio de sesión (Login)  |  GET, POST(por ID)  |   Documentación para obtener los datos de acceso del usuario.   |


URL de la API Simulada (Local): http://localhost:3000/

El uso de Axios y JSON Server logró gestionar las solicitudes HTTP hacia la fake API desde el código de frontend a través de la estructura de db.json y los endpoints simulados.

A continuación,  se mostrará el proceso de interacción del frontend de Livria con el endpoint simulado /books para obtener datos de los posts que realizan los usuarios en un determinado libro utilizando.

En las siguientes imágenes representa el resultado de acceder al endpoint http://localhost:3000/books en la página web con el json-server usando el db.json. Se visualiza la estructura JSON de “books”, en la que se incluye los “reviews”.

<p align="center">
  <img src="https://imgur.com/l8AnRDN.png" alt="SDE21" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/X2XuIa7.png" alt="SDE22" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/NzmCvXO.png" alt="SDE23" width="500">
</p>

* Acción: Obtener los datos de los libros, dentro se encuentra el detalle de los reviews
* Servicio Frontend Involucrado: BooksApiService
* Método del Servicio: getBooks(), updateBook(book)
* Verbo HTTP: GET, PUT
* Sintaxis de Llamada (URL usado por axios): http://localhost:3000/books 

**BookApiService realiza una solicitud GET y PUT**

<p align="center">
  <img src="https://i.imgur.com/dg6JXw1.png" alt="SDE24" width="500">
</p>

La documentación de los servicios implementados en la aplicación web Livria, durante el sprint 2, se enfocó principalmente en la API simulada utilizando el json-server y el archivo db.json. Esto representa una base inicial para, posteriormente, integrar servicios RESTful reales conectados a una base de datos en el siguiente sprint #3.  


#### 5.2.2.7. Software Deployment Evidence for Sprint Review
Para el despliegue de nuestra aplicación utilizamos Firebase como plataforma principal. Paralelamente, migramos nuestra API falsa (fake API) a Render, una herramienta que facilita la publicación de servicios backend simulados como json-server.

El primer paso fue subir el archivo db.json a un repositorio de GitHub, junto con la configuración necesaria para que Render pudiera utilizarlo correctamente.

Una vez listo el repositorio, accedimos a Render y creamos un nuevo Web Service, conectando el repositorio de GitHub previamente creado. Durante la configuración, seleccionamos una instancia del tipo gratuita (Free instance) y completamos los pasos requeridos para iniciar el despliegue.

Creación del Web Service en Render:

Después de unos minutos, Render marcó el servicio como "Live", indicando que la API estaba desplegada correctamente y disponible públicamente.

Despliegue exitoso del Web Service en Render:

Para verificar que todo funcionara como esperado, accedimos al enlace público proporcionado por Render y probamos los endpoints disponibles. Confirmada su operatividad, reemplazamos en nuestro proyecto las URLs locales de la API falsa por el nuevo enlace público de Render.

Este cambio permitió que nuestra aplicación pudiera acceder a los datos de manera remota y funcional en cualquier entorno.

Durante este Sprint, el equipo llevó a cabo el proceso de despliegue inicial de la aplicación Vue.js utilizando Firebase Hosting. Esto permite que el proyecto sea accesible públicamente en un entorno de producción.

Como primer paso hemos creado el proyecto en Firebase:

<p align="center">
  <img src="https://i.Imgur.com/HFKIGvM.png" alt="SDFS21" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/9O3iWoA.png" alt="SDFS22" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/91XdXGJ.png" alt="SDFS23" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/Drlaz7d.png" alt="SDFS24" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/gASc8sB.png" alt="SDFS25" width="500">
</p>

Una vez creado el proyecto en Firebase realizamos los siguientes pasos desde nuestro proyecto en WebStorm:

<p align="center">
  <img src="https://i.imgur.com/IcPpePc.png" alt="SDFS26" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/fapIm72.png" alt="SDFS27" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/g34WHla.png" alt="SDFS28" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/IhXGeht.png" alt="SDFS29" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/PX7zEzs.png" alt="SDFS210" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/PGrn4Fq.png" alt="SDFS211" width="500">
</p>

**Actividades realizadas:**

1. Instalación de Firebase CLI

Se instaló Firebase CLI globalmente en el entorno local para poder gestionar el despliegue.

*npm install -g firebase-tools*

2. Autenticación en Firebase

Se autenticó la cuenta de Firebase.

*firebase login*

3. Inicialización del Proyecto en Firebase

Se inicializó el proyecto Firebase en la raíz del proyecto Vue.js.

*firebase init*

Durante la inicialización, se configuró Firebase Hosting para que apunte al directorio dist/, que es la carpeta generada al realizar la construcción de producción de la aplicación Vue.js.

4. Construcción del Proyecto para Producción

Se generó la versión optimizada de producción de la aplicación Vue.js. 

*npm run build*

5. Despliegue en Firebase Hosting

Se desplegó la aplicación en Firebase Hosting.

*firebase deploy*



#### 5.2.2.8. Team Collaboration Insights during Sprint
Durante este Sprint, el equipo se centró en la implementación de las funcionalidades clave del frontend para la aplicación web de Livria, utilizando Vue.js como el marco principal de desarrollo. Se trabajó en la creación de interfaces de usuario intuitivas y en la integración de diversas funcionalidades, como la visualización del catálogo de libros, el proceso de compra y la interacción con comunidades literarias. Además, se desarrollaron pantallas esenciales para la experiencia de usuario, tales como la sección de recomendaciones personalizadas, el inicio de sesión y las notificaciones.

**Actividades de implementación:**

* El diseño de la interfaz de usuario fue realizado en Figma, lo que permitió una visión clara y precisa de los flujos de usuario.
* Utilizando Vue.js, se desarrollaron las estructuras dinámicas de la aplicación, con componentes reutilizables que gestionan el estado de la UI de manera eficiente.
* Se aplicaron Vue Router para la navegación entre las diferentes secciones de la plataforma y Vuex para la gestión del estado global de la aplicación, facilitando la integración de la interfaz con las funcionalidades backend.
* JavaScript fue utilizado para implementar interacciones y funcionalidades específicas como el registro de usuario, la compra de libros, la interacción con las comunidades literarias y las recomendaciones personalizadas.

**Análisis de colaboración en GitHub:**

A continuación, se muestra un resumen visual de la participación activa de los miembros del equipo a través de las contribuciones realizadas en el repositorio:

**Historial de commits:**

<p align="center">
  <img src="https://i.imgur.com/MN0MIBb.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/kbA7LKn.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/XOE0oXr.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/kl1bgYt.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/sv9iqcr.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/8XnkJyB.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/Pkd7jFs.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/LyGO2Ie.png" alt="SDFS211" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/4VOSaB5.png" alt="SDFS211" width="500">
</p>

**Colaboradores activos en el repositorio:**

<p align="center">
  <img src="https://i.imgur.com/wCVJ2NM.png" alt="SDFS211" width="500">
</p>

**Histograma de contribuciones en el tiempo:**

<p align="center">
  <img src="https://i.imgur.com/uGOLmUD.png" alt="SDFS211" width="500">
</p>

### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning
En esta reunión del **Sprint Planning** se va a construir el **backend** de nuestro proyecto Livria y realizar mejoras del **frontend** de nuestra aplicación. En esta reunión, el equipo Scrum estableció distintas tareas a cada integrante para desarrollar 28 historias de usuarios y 6 technical stories relevantes para la aplicación web.

A continuación, se mostrará la tabla del Sprint Planning 3:

| Sprint # | Sprint 3 |
|---|---|
| **Sprint Planning Background** | |
| **Date** | 2025-06-14 |
| **Time** | 05:20 PM |
| **Location** | Virtual |
| **Prepared By** | Ainhoa Lucía Castillo Garay, Marcelo Alejandro Binda Arbañil |
| **Attendees (to planning meeting)** | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Binda Arbañil / Gabriel Sebastián Borja Molina / Jhosep Jamil Argomedo Camacho / Melisa Geraldine Sulca Silva |
| **Sprint n - 3 Review Summary** | Durante el Sprint 3, se desarrollaron **28 historias de usuarios y 6 technical stories** centradas en el desarrollo del **backend** de la aplicación Livria. El trabajo realizado permitió consolidar la arquitectura de la **base de datos** y las funcionalidades clave del backend, como la gestión de productos, carritos de compra, comunidades y pedidos. Se implementaron los **endpoints RESTful** para las tablas principales, incluyendo libros, carritos de compra, pedidos y usuarios, lo que permitió una integración eficiente entre el frontend y el backend.<br><br>El equipo de programadores, conformado por **Joseph Argomedo**, se destacó en la **optimización de las consultas SQL** y en la mejora de la estructura de la base de datos, lo que resultó en una mayor eficiencia en la consulta de datos a la base de datos MySQL. Su contribución fue clave para asegurar que las operaciones de lectura y escritura se realizarán de manera rápida y fluida.<br><br>**Gabriel Borja** y **Melisa Sulca** trabajaron conjuntamente en la estructuración de las relaciones entre las tablas y en la correcta **normalización de la base de datos**, asegurando la integridad referencial y evitando problemas de duplicación de datos, lo cual facilita el mantenimiento y escalabilidad de la plataforma.<br><br>**Marcelo Binda** y **Ainhoa Castillo** contribuyeron significativamente en la implementación de las **APIs RESTful** para funcionalidades clave, como la gestión de carritos de compra, comunidades literarias, pedidos y notificaciones, garantizando que todas las interacciones fueran seguras y eficientes.<br><br>En cuanto a la **documentación de las APIs**, se utilizó **Swagger** para facilitar la visualización e interacción con los endpoints, lo que permitió al equipo desarrollar de manera más ágil y transparente. Además, la **documentación OpenAPI** se implementó para estandarizar los endpoints y facilitar futuras integraciones, asegurando que la aplicación esté lista para escalar y conectarse con otros servicios en el futuro. |
| **Sprint n - 3 Retrospective Summary** | Durante el Sprint 3, se estableció una base sólida del **backend** de la plataforma Livria. El equipo logró avanzar significativamente en la integración de los servicios clave. En cuanto a los avances están la **optimización de la base de datos**, donde las consultas SQL están optimizadas correctamente, mejorando notablemente el rendimiento del backend. El trabajo en equipo fue eficiente, permitiendo completar las tareas de backend de manera sincronizada. Mientras que la **estructuración de APIs** se logró implementar las APIs para el manejo de libros, carritos de compra y otros componentes clave. En la **documentación API**: La implementación de Swagger y la documentación OpenAPI facilitó tanto la integración como la prueba de los endpoints, mejorando la transparencia del proyecto. Para el siguiente sprint se debe realizar una **optimización continua de las consultas SQL** y la base de datos, realizar **correcciones de errores menores** si es que hay alguno detectado durante las pruebas del backend, realizar una **ampliación de la documentación de las APIs**, especialmente para los endpoints más complejos y realizar **revisión y mejora de la seguridad** en la API y la base de datos. |
| **Sprint Goal & User Stories** | |
| **Sprint Goal** | Our focus is on the development of the **backend infrastructure** for the Livria web app, particularly in implementing key **RESTful APIs**, optimizing database queries. This includes managing essential entities such as users, books, orders, cart items, communities, and reviews.<br><br>We believe it delivers a **robust backend system** capable of handling user interactions, processing orders, managing data efficiently, and providing essential API endpoints for the frontend. Additionally, the integration of **OpenAPI and Swagger** will ensure smooth documentation and facilitate future expansions.<br><br>This will be confirmed when all the user stories related to backend functionalities, such as authentication, cart management, community interactions, and order processing, are implemented and tested successfully. We will also verify the efficiency of the APIs and database queries, ensuring they meet performance benchmarks. |
| **Sprint Velocity** | 98 |
| **Sum of Story Points** | 94 |

#### 5.2.3.2. Aspect Leaders and Collaborators

Durante el Sprint 3, hemos identificado diversos aspectos funcionales relacionados con el desarrollo del **backend** de la aplicación web Livria, así como algunos ajustes en el frontend. Para organizar de manera eficiente las tareas del equipo, hemos creado una matriz de **Liderazgo y Colaboración (LACX)**. En esta matriz, a cada miembro se le asigna el rol de **líder (L)** en áreas clave del desarrollo del backend y ciertos ajustes del frontend, mientras que en otras áreas asumen el rol de **colaborador (C)**.

Los aspectos definidos para este Sprint son:

1.  Bounded Context de Commerce
2.  Bounded Context de Communities
3.  Bounded Context de Users
4.  Bounded Context de Notifications
5.  Corrección del Frontend
6.  Dashboard de administrador en el Frontend
7.  Desarrollo de la base de datos

| Team Member (Last Name, First Name) | GitHub Username | B. C. de Commerce | B. C. de Communities | B. C. de Users | B. C. de Notifications | Corrección del Frontend | Dashboard del administrador en el Frontend | Desarrollo de la base de datos |
|-------------------------------------|-----------------|-------------------|----------------------|----------------|------------------------|-------------------------|--------------------------------------------|-------------------------------|
| Castillo Garay, Ainhoa Lucía        | noaa01100001    | C                 | C                    | C              | C                      | L                       | C                                          | C                             |
| Binda Arbañil, Marcelo Alejandro    | MarceloHkd      | L                 | L                    | L              | L                      | C                       | C                                          | C                             |
| Borja Molina, Gabriel Sebastián     | borj410         | C                 | C                    | C              | C                      | C                       | C                                          | C                             |
| Argomedo Camacho, Jhosep Jamil      | JhosepAC        | C                 | C                    | C              | C                      | C                       | L                                          | L                             |
| Sulca Silva, Melisa Geraldine       | MSS02204        | C                 | C                    | C              | C                      | C                       | C                                          | C                             |

#### 5.2.3.3. Sprint Backlog 3

Durante el Sprint 3, el objetivo principal fue desarrollar la versión inicial del **backend** de la aplicación Livria, con un enfoque en eficiencia, seguridad y escalabilidad. El equipo trabajó en crear una infraestructura robusta que permitiera a los usuarios interactuar sin problemas con la plataforma, gestionando de manera eficaz aspectos clave como el registro e inicio de sesión de los usuarios, el manejo de productos de libros, la gestión de carritos de compra, y la interacción con las comunidades. Este primer paso fue fundamental para garantizar un rendimiento óptimo del backend y preparar el sistema para futuras expansiones y nuevas funcionalidades, asegurando una experiencia robusta desde el primer contacto con la aplicación.

| Sprint # | Sprint #3 | | | | |
|---|---|---|---|---|---|
| | **Work-Item / Task** | | | | |
| **User Story ID** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status (To-do / InProcess / To-Review / Sprint# / Done)** |
| **US35** | | **Obtener todos los libros** | | | | |
| | 1 | Consultar todos los libros disponibles | Realizar una consulta a la base de datos para recuperar todos los registros de libros de la tabla `books`. | 5 | Developer Team | Done |
| | 2 | Implementar filtro por campo de categoría | Crear consultas dinámicas que filtren los libros por campos específicos como `category`, `author` o `availability`. | 6 | Developer Team | Done |
| **US36** | | **Obtener detalles de un libro** | | | | |
| | 1 | Consultar detalles del libro | Crear una consulta SQL que recupere todos los campos de la tabla `books` para un libro específico identificado por su `id` del libro. | 4 | Developer Team | Done |
| | 2 | Consultar disponibilidad del libro | Crear una consulta para verificar el campo `availability` en la tabla `books` y retornar el estado actual. | 4 | Developer Team | Done |
| **US37** | | **Crear una reseña de un libro** | | | | |
| | 1 | Gestionar creación de reseñas | Implementar una funcionalidad que guarde reseñas de los usuarios en la tabla `reviews` asociando el `id` del libro y del usuario. | 6 | Developer Team | Done |
| | 2 | Validación de reseña antes de guardar | Validar con una consulta que los campos no estén vacíos y cumplan los requisitos establecidos. | 5 | Developer Team | In-Process |
| **US38** | | **Obtener todas las reseñas de un libro** | | | | |
| | 1 | Consultar todas las reseñas del libro | Crear una consulta SQL que recupere todas las reseñas de un libro específico desde la tabla `reviews`. | 5 | Developer Team | Done |
| **US39** | | **Agregar un libro al carrito** | | | | |
| | 1 | Agregar libro al carrito | Crear una nueva entrada en la tabla `cart_items` para asociar un `id` del libro y del usuario. | 5 | Developer Team | Done |
| | 2 | Confirmación de adición al carrito | Verificar que el libro haya sido agregado al carrito y actualizar el campo de cantidad en la tabla de `cart_items`. | 6 | Developer Team | Done |
| **US40** | | **Gestión de un pedido** | | | | |
| | 1 | Crear pedido | Crear una nueva entrada en la tabla `orders` con los detalles del carrito del usuario. | 6 | Developer Team | Done |
| **US41** | | **Ver detalles de un pedido** | | | | |
| | 1 | Consultar detalles de un pedido | Crear una consulta SQL que recupere los detalles del pedido desde la tabla `order_items` y `orders`. | 5 | Developer Team | Done |
| | 2 | Consultar estado de la entrega | Crear una consulta que verifique el estado del pedido en el campo de estado de la tabla `orders`. | 4 | Developer Team | Done |
| **US42** | | **Obtener todas las comunidades** | | | | |
| | 1 | Consultar todas las comunidades | Consultar la tabla `communities` y retornar todos los registros disponibles. | 5 | Developer Team | Done |
| | 2 | Buscar una comunidad específica | Implementar una búsqueda con un `Where` para encontrar comunidades específicas por nombre en la tabla `communities`. | 4 | Developer Team | Done |
| **US43** | | **Gestión de creación de una comunidad** | | | | |
| | 1 | Validación de creación de comunidad | Validar que los campos obligatorios (nombre, descripción) no estén vacíos antes de guardar la comunidad en la tabla `communities`. | 6 | Developer Team | Done |
| | 2 | Confirmación de creación de comunidad | Verificar que los datos se hayan guardado correctamente en la base de datos, asignando un `id` a la comunidad único. | 6 | Developer Team | Done |
| **US44** | | **Publicación en una comunidad** | | | | |
| | 1 | Crear publicación en una comunidad | Guardar la publicación del usuario en la tabla `posts` y asociarla con un `id` community. | 6 | Developer Team | Done |
| | 2 | Validación del contenido de publicación | Verificar que la publicación cumpla con las reglas y que no haya contenido vacío; si no cumple, eliminarla automáticamente. | 5 | Developer Team | To-do |
| **US45** | | **Obtener todos los usuarios** | | | | |
| | 1 | Consultar todos los usuarios | Obtener lista completa de usuarios registrados. | 5 | Developer Team | Done |
| | 2 | Buscar un usuario específico | Crear una consulta SQL que recupere todos los usuarios registrados desde las tablas `users`, `userclients` y `useradmins`. | 5 | Developer Team | Done |
| **US46** | | **Gestión de creación de un nuevo usuario** | | | | |
| | 1 | Crear nuevo usuario | Crear una nueva entrada en la tabla `userclients` cuando un nuevo usuario se registre. | 4 | Developer Team | Done |
| | 2 | Validación automática de datos | Validar que los campos del formulario de registro (nombre, email, contraseña) estén completos y sean válidos. | 6 | Developer Team | In-Process |
| **US47** | | **Eliminar un usuario** | | | | |
| | 1 | Eliminar un usuario | Crear una consulta SQL que elimine un usuario de la tabla `usersclients` con base en su `id` del `userclient`. | 5 | Developer Team | Done |
| | 2 | Confirmación de eliminación | Verificar que el usuario ha sido correctamente eliminado de la base de datos. | 5 | Developer Team | Done |
| **US48** | | **Gestión de creación de una notificación** | | | | |
| | 1 | Crear notificación de carrito agregado | Crear una notificación en la tabla `notifications` cuando un usuario agrega un libro al carrito. | 6 | Developer Team | Done |
| | 2 | Crear notificación de unión a comunidad | Crear una notificación en la tabla `notifications` cuando un usuario se une a una comunidad. | 4 | Developer Team | Done |
| **US49** | | **Gestión de asignación de favorito** | | | | |
| | 1 | Asignar favorito (administrador) | Agregar un favorito a un usuario desde la vista de administrador. | 6 | Developer Team | Done |
| | 2 | Eliminar favorito (administrador) | Eliminar un favorito de un usuario desde la vista de administrador. | 3 | Developer Team | Done |
| | 3 | Asignar favorito (cliente) | Agregar un favorito a un usuario desde la aplicación web. | 4 | Developer Team | Done |
| | 4 | Eliminar favorito (cliente) | Eliminar un favorito de un usuario desde la plataforma web. | 3 | Developer Team | Done |
| **US50** | | **Creación de recomendaciones en base a favoritos** | | | | |
| | 1 | Generación automática de recomendación | Generar recomendaciones en base a libros marcados como favoritos por un usuario. | 3 | Developer Team | Done |
| **US51** | | **Acceso rápido desde el Dashboard** | | | | |
| | 1 | Acceso rápido a secciones | Implementar navegación rápida desde el dashboard a las principales secciones. | 5 | Developer Team | Done |
| **US52** | | **Estadísticas en Books** | | | | |
| | 1 | Total libros y géneros | Mostrar conteo total de libros y géneros. | 3 | Developer Team | Done |
| | 2 | Precio promedio | Mostrar precio promedio de libros. | 2 | Developer Team | In-Process |
| | 3 | Libros en stock | Mostrar cantidad total de libros en stock. | 2 | Developer Team | Done |
| | 4 | Libro más visto y vendido | Mostrar estadísticas de libro más visto y más vendido. | 3 | Developer Team | In-Process |
| **US53** | | **Búsqueda en Book Collection** | | | | |
| | 1 | Búsqueda por título o autor | Implementar campo de búsqueda por título o autor. | 3 | Developer Team | Done |
| | 2 | Filtros por género e idioma | Agregar filtros de género e idioma. | 3 | Developer Team | Done |
| | 3 | Ordenamiento | Ordenar libros por criterio. | 3 | Developer Team | Done |
| **US54** | | **Visualización de detalles del libro** | | | | |
| | 1 | Precio e info básica | Mostrar precio, descripción, autor, etc. | 3 | Developer Team | Done |
| | 2 | Ver más detalles | Mostrar ventana modal con detalles completos del libro. | 3 | Developer Team | Done |
| **US55** | | **Estadísticas de órdenes** | | | | |
| | 1 | Total órdenes y ganancias | Mostrar número total de órdenes y ganancias. | 3 | Developer Team | Done |
| | 2 | Órdenes pendientes y completas | Mostrar estadísticas de estado de órdenes. | 2 | Developer Team | Done |
| | 3 | Promedio valor de órdenes | Mostrar el valor promedio de las órdenes. | 2 | Developer Team | In-Process |
| | 4 | Libro más popular pedido | Mostrar el libro más ordenado. | 2 | Developer Team | In-Process |
| **US56** | | **Búsqueda y filtro en Order List** | | | | |
| | 1 | Búsqueda por ID o nombre | Implementar campo de búsqueda. | 3 | Developer Team | Done |
| | 2 | Filtro por estado | Filtrar por estado del pedido. | 2 | Developer Team | Done |
| | 3 | Filtro por fecha | Implementar filtro por rango de fechas. | 2 | Developer Team | Done |
| | 4 | Ordenamiento | Ordenar órdenes por criterio. | 2 | Developer Team | Done |
| **US57** | | **Tabla de órdenes** | | | | |
| | 1 | Tabla con detalles de órdenes | Mostrar tabla con columnas: código, cliente, ítems, total, etc. | 3 | Developer Team | Done |
| **US58** | | **Filtros en Inventario** | | | | |
| | 1 | Barra de búsqueda | Búsqueda por término. | 2 | Developer Team | Done |
| | 2 | Filtro por género/lenguaje | Filtros de género y lenguaje. | 2 | Developer Team | Done |
| | 3 | Ordenamiento | Ordenar libros por stock, precio, etc. | 2 | Developer Team | Done |
| **US59** | | **Tabla de libros en inventario** | | | | |
| | 1 | Tabla de libros | Mostrar tabla con campos clave (portada, autor, etc.). | 3 | Developer Team | Done |
| | 2 | Aumentar stock de libro | Botón para aumentar stock del libro en el inventario. | 2 | Developer Team | Done |
| **US60** | | **Configuración de perfil** | | | | |
| | 1 | Ver info perfil | Mostrar información actual del usuario. | 2 | Developer Team | Done |
| | 2 | Editar info | Editar y guardar nombre, usuario, correo. | 2 | Developer Team | Done |
| | 3 | Cambiar contraseña | Permitir actualización de contraseña. | 2 | Developer Team | Done |
| **US61** | | **Configuración aplicación** | | | | |
| | 1 | Notificaciones app | Activar/desactivar notificaciones in-app. | 2 | Developer Team | Done |
| | 2 | Alertas email | Activar/desactivar alertas por correo. | 2 | Developer Team | Done |
| | 3 | Auto guardado | Activar/desactivar auto save. | 2 | Developer Team | Done |
| | 4 | Items por página | Configurar cantidad de elementos por página. | 2 | Developer Team | Done |
| | 5 | Guardar cambios | Botón para guardar configuración. | 1 | Developer Team | Done |
| **US62** | | **Barra lateral navegación** | | | | |
| | 1 | Mostrar título plataforma | Mostrar "LIVRIA". | 1 | Developer Team | Done |
| | 2 | Foto y nombre del admin | Mostrar imagen + “Super Administrador”. | 1 | Developer Team | Done |
| | 3 | Secciones principales | Mostrar links: Home, Books, etc. | 2 | Developer Team | Done |
| | 4 | Cambiar idioma | Botón para cambiar entre EN/ES. | 2 | Developer Team | Done |
| | 5 | Settings y logout | Enlace a settings + botón cerrar sesión. | 1 | Developer Team | Done |
| **TS01** | | **Configuración inicial de la base de datos MySQL** | | | | |
| | 1 | Configuración de conexión con base de datos MySQL | Configurar la conexión entre el backend (.NET) y la base de datos MySQL, protegiendo las credenciales con variables de entorno. | 6 | Developer Team | Done |
| | 2 | Implementación de conexión segura con SSL | Asegurarse de que la conexión entre el backend y la base de datos MySQL utilice SSL para encriptar los datos. | 5 | Developer Team | Done |
| **TS02** | | **Implementación de autenticación JWT** | | | | |
| | 1 | Protección de endpoints con autenticación JWT | Crear la lógica para validar el token JWT en los endpoints protegidos, como /api/v1/orders. | 6 | Developer Team | Done |
| | 2 | Validación de acceso sin token | Asegurarse de que la API devuelva un estado 401 cuando se intente acceder a un endpoint protegido sin un token válido. | 4 | Developer Team | Done |
| **TS03** | | **Documentación de APIs con Swagger/OpenAPI** | | | | |
| | 1 | Configuración de Swagger para documentación de API | Configurar Swagger/OpenAPI para que genere una documentación interactiva de los endpoints, mostrando ejemplos y esquemas de datos. | 5 | Developer Team | Done |
| | 2 | Definición de esquemas en Swagger | Incluir los esquemas para las entidades Books, Orders, y Users en la documentación generada por Swagger. | 4 | Developer Team | Done |
| **TS04** | | **Optimización de consultas SQL para carritos** | | | | |
| | 1 | Optimización de consulta SQL para carrito de 100+ ítems | Optimizar la consulta de los carritos con más de 100 ítems para reducir el tiempo de respuesta en un 30%. | 6 | Developer Team | Done |
| | 2 | Implementación de índices en bookId y userClientId | Crear índices en las columnas bookId y userClientId para mejorar el rendimiento de las consultas del carrito. | 4 | Developer Team | Done |
| **TS05** | | **Implementación de logs de errores** | | | | |
| | 1 | Configuración de logging para errores de SQL | Configurar un sistema de logging centralizado para registrar errores de SQL en el archivo logs/api_errors.log. | 5 | Developer Team | Done |
| | 2 | Manejo de errores con respuesta genérica | Asegurarse de que la API devuelva un estado 500 y un mensaje genérico cuando ocurra un error de SQL y se registre en los logs. | 4 | Developer Team | Done |
| **TS06** | | **Configuración de CORS para el frontend** | | | | |
| | 1 | Implementación de CORS para frontend autorizado | Configurar CORS para que solo el dominio https://livriabybookify.netlify.app/ pueda hacer solicitudes al backend. | 5 | Developer Team | Done |
| | 2 | Manejo de peticiones de dominio no autorizado | Asegurarse de que las solicitudes de dominios no autorizados, como malicious.com , reciban una respuesta 403. | 4 | Developer Team | Done |


#### 5.2.3.4. Development Evidence for Sprint Review

En este capítulo se detalla el progreso logrado durante el **Sprint 3** en el desarrollo del **backend** de la aplicación web. Gracias a la colaboración continua del equipo y al enfoque ágil, hemos avanzado en la implementación de funcionalidades clave en el backend, así como en las correcciones realizadas en el frontend. Este sprint ha sido fundamental para consolidar la infraestructura del backend, asegurando que todas las funcionalidades de gestión de datos, pedidos, usuarios y notificaciones estén bien integradas y optimizadas, lo que sienta las bases para el desarrollo de las siguientes fases del proyecto.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| https://github.com/Bookify-Livria/livria.github.io | master | d5bf72b | feat: add link to web application | --- | 18/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 13f3250 | feat: admin preview pages and inheritance in Users classes | --- | 17/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | dc93622 | fix: duplicate folders | --- | 17/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 42b1f1c | feat: admin validation access page | --- | 17/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | a8cb685 | Merge branch 'feat/admin' into develop | --- | 17/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feat/admin | 7ce211e | feat: update admin components | --- | 17/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/books | 6663fdf | feat: stars in individual review | --- | 18/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 59c2b78 | Merge branch 'develop' into feature/books | --- | 18/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 4a715b0 | feat: form validations | --- | 18/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 4a748f7 | feat: design modifications | --- | 18/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feat/admin | 75d0bffc | feat: added order status | --- | 19/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feat/admin | 1a828e5 | feat: PUT method for admin and design improvements | --- | 19/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/books | 434bd0d | feat: recommendations and book markings | --- | 19/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feat/admin | 509b4a9 | feat: Inventory management components | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feat/admin | 129997d | feat: upgrade in books management and addition of inventory components | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-web-app.git | feat/admin | cbfec1f7 | feat: update in admin orders view | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | main | 15ef27f | Initial commit | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/users | 15ef27f | feat: Add Users Bounded Context | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/community | b743855 | feat: Add Community Bounded Context | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/commerce | f683592 | feat: Add Commerce Bounded Context | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/data-annotations | 7e68f3a | feat: Add validation, data annotations localization and Shared validation | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/recommendations | 7ac229e | feat: Add validation, data annotations localization and Shared validation | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/commerce | ab8144e | Fix: Commerce Bounded Context | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/data-annotations | e07aaac | feat: Add user bounded context validation | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | feature/notifications | 8120432 | feat: Update notifications | --- | 20/06/25 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | c5904ce | feat: LIVRIA TB2 | --- | 20/06/25 |

#### 5.2.3.5. Execution Evidence for Sprint Review

Durante el Sprint 3, se desarrollaron múltiples historias de usuario centradas principalmente en la implementación del **backend** de la aplicación web de Livria, con especial enfoque en la gestión de productos, usuarios, comunidades, pedidos y notificaciones. Este sprint se centró en la mejora de la infraestructura y la integración de funcionalidades críticas, como la gestión de libros, carritos de compra, comunidades literarias, y la implementación de un sistema robusto de notificaciones.

Además, se implementó la **documentación y prueba de las APIs** a través de **OpenAPI y Swagger**, lo que permite tener una visión clara y accesible de todos los endpoints disponibles en el backend, facilitando la interacción y desarrollo de nuevas funcionalidades.

El equipo completó varias tareas clave, como la implementación de las funcionalidades para obtener y crear libros, gestionar carritos y pedidos, así como la gestión de comunidades y la integración de funcionalidades de notificaciones. A lo largo de este sprint, se hicieron ajustes en la base de datos (**db.json**) para mejorar la estructura de usuarios y se corrigieron aspectos en el frontend de la sección de administración.

#### Avances realizados:

**Commerce:**
* **Books:** Implementación de funcionalidades para obtener todos los libros (**GetAll**) y obtener detalles de un libro específico (**GetById**) y actualizar el stock de un libro.
* **Reviews:** Implementación de la funcionalidad de crear reseñas de libros (**GetAll, GetById, Create**).
* **CartItems:** Implementación de la funcionalidad para gestionar el carrito de compras (**GetAll, Update, Delete, Post**).
* **Orders:** Implementación de la creación de pedidos (**Create**) y la visualización de detalles de un pedido (**GetAll, GetById**).
* **Recommendations:** Implementación de la creación de recomendaciones del catálogo de libros para los usuarios (**GetAll**).

**Communities:**
* **Communities:** Implementación de funcionalidades para obtener todas las comunidades (**GetAll**), obtener detalles de una comunidad (**GetById**), y crear nuevas comunidades (**Create**).
* **Post:** Implementación de funcionalidades para obtener publicaciones (**GetAll**), obtener detalles de una publicación (**GetById**), y crear nuevas publicaciones (**Create**).

**Users:**
* **UserClients:** Gestión de clientes, con la capacidad de obtener todos los clientes (**GetAll**), obtener detalles de un cliente (**GetById**), y realizar operaciones de creación (**Create**), eliminación, eliminar clientes (**Delete**) y actualización de clientes (**Update**).
* **UserAdmins:** Funcionalidad para gestionar administradores, con la capacidad de obtener todos los administradores (**GetAll**) y realizar actualizaciones de datos (**Update**).

**Notification:**
* Implementación de funcionalidades para gestionar notificaciones, con la capacidad de obtener todas las notificaciones (**GetAll**), obtener detalles de una notificación específica (**GetById**), crear notificaciones (**Create**) y ocultar notificaciones (**Patch**).

#### Contribuciones del equipo:

Se implementaron las funcionalidades relacionadas con los bounded contexts anteriormente mencionados, se realizó la **corrección de la fake API (db.json)** para usuarios, y completó la **corrección y mejoras en el frontend de la sección de administración**. Se trabajó en la implementación de **DataAnnotations**, validaciones y la **internacionalización** de la aplicación, se realizó la sección del **administrador en el frontend** y se realizó la **corrección de errores y mejoras en el diseño frontend**, especialmente para la sección de administración.

#### Evidencia visual:

A continuación, se presentan capturas de pantalla de las vistas implementadas en este Sprint:

**Sección Home del dashboard del administrador:**

<p align="center">
  <img src="https://imgur.com/50Mzjh3.png" alt="bruh1" width="500">
</p>

**Sección Books del dashboard del administrador:**

<p align="center">
  <img src="https://imgur.com/SNyZiBq.png" alt="bruh2" width="500">
</p>

**Sección Orders del dashboard del administrador:**

<p align="center">
  <img src="https://imgur.com/AifaHr7.png" alt="bruh3" width="500">
</p>

**Sección Settings del dashboard del administrador:**

<p align="center">
  <img src="https://imgur.com/Jqh4AIQ.png" alt="bruh4" width="500">
</p>

**Backend de los bounded context de Livria:**
<p align="center">
  <img src="https://i.imgur.com/orIqhjD.png" alt="bruh5" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/5g3qwJF.png" alt="bruh6" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/wAeXqdE.png" alt="bruh7" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/mNNqjlv.png" alt="bruh7" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/qDWmLYf.png" alt="bruh8" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/CGdtVLQ.png" alt="bruh9" width="500">
</p>

**Video Sprint Review 3**

*Frontend*
https://drive.google.com/file/d/1PfDVySKwf-HpYugEF7xXwTlmyMUvm0ul/view?usp=sharing

*Backend*
https://drive.google.com/file/d/1Kk48d_cboV3UpPt4qyteE4DP60uIiPLs/view?usp=sharing

---
#### 5.2.3.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 3, el enfoque se centró en la implementación del **backend real** para la aplicación web de Livria, reemplazando la API fake utilizada en el Sprint 2 con servicios backend funcionales. Ahora, el sistema está conectado a una base de datos real y las operaciones CRUD para gestionar libros, carritos, pedidos, usuarios, comunidades, notificaciones y otras entidades están completamente implementadas y operativas.

En lugar de utilizar una API simulada, ahora se está trabajando con una **API RESTful real** construida con **.NET y conectada a MySQL**. A continuación, se detallan los endpoints de la nueva API, los métodos implementados y la documentación correspondiente:

| Endpoint | Acción | Verbo HTTP | Sintaxis de llamada | Parámetros | Ejemplo de Request | Ejemplo de Response | Explicación |
|---|---|---|---|---|---|---|---|
| `/api/v1/books` | Obtener los datos de todos los libros. | `GET` | `GET /api/v1/books` | Ninguno | `http://localhost:5119/api/v1/books` | `{"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 49,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []}` | Esta solicitud GET obtiene los datos de todos los libros disponibles. Muestra una lista completa de los libros registrados en el sistema. |
| `/api/v1/books` | Crear un nuevo libro. | `POST` | `GET /api/v1/books` | Ninguno | `{"title": "XD","description": "string","author": "string","salePrice": 4,"stock": 20,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english"}` | `{"id": 3,"title": "XD","description": "string","author": "string","salePrice": 4,"stock": 20,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []}` | Esta solicitud POST crea un nuevo libro en el sistema. Permite registrar un libro con su título, descripción, autor, precio, stock, imagen de portada, género y idioma. |
| `/api/v1/books/{id}` | Obtener los datos de un libro en específico. | `GET` | `GET /api/v1/books/{id}` | `id: Integer` | `http://localhost:5119/api/v1/books/1` | `{"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 50,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []}` | Esta solicitud GET obtiene los datos de un libro en específico, utilizando su ID. Muestra los detalles del libro solicitado. |
| `/api/vi/books/{bookId}/stock` | Actualizar el stock de un libro. | `PUT` | `PUT /api/vi/books/{bookId}/stock` | `bookId: Integer`, `stock: Integer` | `{"newStock": 50}` | `{"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 50,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []}` | Esta solicitud PUT actualiza el stock disponible de un libro específico, usando su ID. Permite modificar la cantidad de libros en existencia. |
| `/api/v1/cart-items` | Crear un nuevo ítem en el carrito. | `POST` | `POST /api/v1/cart-items` | Ninguno | `{"bookId": 1,"quantity": 1,"userClientId": 2}` | `{"id": 2,"book": {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 50,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []},"quantity": 1}` | Esta solicitud POST crea un nuevo ítem en el carrito de un usuario. Permite añadir un libro con una cantidad específica al carrito de un cliente. |
| `/api/v1/cart-items/{id}/users/{userClientId}` | Actualizar la cantidad de libros de un ítem de un carrito existente. | `PUT` | `PUT /api/v1/cart-items/{id}/users/{userClientId}` | `id: Integer`, `userClientId: Integer` | `{"newQuantity": 2}` | `{"id": 1,"book": {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 50,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []},"quantity": 2,"userClientId": 2}` | Esta solicitud PUT actualiza la cantidad de un libro en un ítem de carrito específico. Permite modificar la cantidad de un libro ya existente en el carrito de un usuario. |
| `/api/v1/cart-items/{id}/users/{userClientId}` | Eliminar un item de un carrito de un UserClient previamente creado. | `DELETE` | `DELETE /api/v1/cart-items/{id}/users/{userClientId}` | `id: Integer`, `userClientId: Integer` | `Id: 1`, `userClientId: 1` | `CartItem eliminado exitosamente.` | Esta solicitud DELETE elimina un ítem específico del carrito de un usuario. Borra un libro determinado del carrito de compras. |
| `/api/v1/cart-items/{id}` | Obtener los datos de un libro perteneciente a un carrito en especificado. | `GET` | `GET /api/v1/cart-items/{id}` | `id: Integer` | `http://localhost:5119/api/v1/cart-items/3` | `{"id": 3,"book": {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 49,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []},"quantity": 3,"userClientId": 2}` | Esta solicitud GET obtiene los datos de un libro perteneciente a un carrito en específico, utilizando el ID del ítem del carrito. Muestra los detalles del libro y la cantidad en el carrito. |
| `/api/v1/cart-items/users/{userClientId}` | Obtener los datos del carrito del usuario en específico. | `GET` | `GET /api/v1/cart-items/users/{userClientId}` | `userClientId: Integer` | `http://localhost:5119/api/v1/cart-items/users/2` | `{"id": 3,"book": {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 49,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []},"quantity": 3,"userClientId": 2}` | Esta solicitud GET obtiene todos los ítems del carrito de un usuario específico. Muestra los libros y sus cantidades en el carrito de ese usuario. |
| `/api/v1/communities` | Crear una nueva comunidad. | `POST` | `POST /api/v1/communities` | Ninguno | `{"name": "string","description": "string","type": "string","image": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","banner": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg"}` | `{"id": 1,"name": "string","description": "string","type": "string","image": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","banner": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","posts": []}` | Esta solicitud POST crea una nueva comunidad en el sistema. Permite registrar una comunidad con su nombre, descripción, tipo, imagen y banner. |
| `/api/v1/communities` | Obtener los datos de todas las comunidades. | `GET` | `GET /api/v1/communities` | Ninguno | `http://localhost:5119/api/v1/communities` | `{"id": 1,"name": "string","description": "string","type": "string","image": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","banner": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","posts": [{"id": 1,"communityId": 1,"userId": 2,"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","createdAt": "2025-06-21T05:40:19.554941"}]}` | Esta solicitud GET obtiene los datos de todas las comunidades existentes. Muestra una lista de comunidades con sus detalles. |
| `/api/v1/communities/{id}` | Obtener los datos de una comunidad en específico. | `GET` | `GET /api/v1/communities/{id}` | `id: Integer` | `Id: 1` | `{"id": 1,"name": "string","description": "string","type": "string","image": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","banner": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","posts": [{"id": 1,"communityId": 1,"userId": 2,"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","createdAt": "2025-06-21T05:40:19.554941"}]}` | Esta solicitud GET obtiene los datos de una comunidad en específico, utilizando su ID. Muestra los detalles de la comunidad buscada. |
| `/api/v1/communities/join` | Unirse a una comunidad existente. | `POST` | `POST /api/v1/communities/join` | `id: Integer` | `{"userClientId": 2,"communityId": 1}` | `{"userClientId": 2,"communityId": 1,"joinedDate": "2025-06-21T05:38:02.722597Z"}` | Esta solicitud POST permite a un usuario unirse a una comunidad existente. Asocia un usuario a una comunidad específica. |
| `/api/v1/reviews` | Crear una nueva review. | `POST` | `POST /api/v1/reviews` | Ninguno | `{"bookId": 1,"userClientId": 2,"content": "string","stars": 4}` | `{"id": 1,"bookId": 1,"username": "string","content": "string","stars": 4}` | Esta solicitud POST crea una nueva reseña en el sistema. Permite añadir una reseña con calificación y contenido para un libro y un usuario. |
| `/api/v1/reviews` | Obtener los datos de todas las reseñas. | `GET` | `GET /api/v1/reviews` | Ninguno | `http://localhost:5119/api/v1/reviews` | `{"id": 1,"bookId": 1,"username": "string","content": "string","stars": 4}` | Esta solicitud GET obtiene los datos de todas las reseñas. Muestra una lista completa de todas las reseñas en el sistema. |
| `/api/v1/reviews/{id}` | Obtener los datos de una reseña en específico. | `GET` | `GET /api/v1/reviews/{id}` | `id: Integer` | `Id: 1` | `{"id": 1,"bookId": 1,"username": "string","content": "string","stars": 4}` | Esta solicitud GET obtiene los datos de una reseña en específico, usando su ID.Muestra los detalles de la reseña buscada. |
| `/api/v1/reviews/book/{bookId}` | Obtener todas las reseñas para un libro específico. | `GET` | `GET /api/v1/reviews/book/{bookId}` | `bookId: Integer` | `BookId: 1` | `{"id": 1,"bookId": 1,"username": "string","content": "string","stars": 4}` | Esta solicitud GET obtiene todas las reseñas para un libro específico. Muestra una lista de todas las reseñas asociadas a un libro dado. |
| `/api/v1/userAdmin` | Obtener los datos del usuario administrador | `GET` | `GET /api/v1/userAdmin` | Ninguno | `http://localhost:5119/api/v1/useradmins` | `{"adminAccess": true,"securityPin": "0000","id": 1,"display": "Super Administrador","username": "admin_default","email": "admin@livria.com"}` | Esta solicitud GET obtiene los datos del usuario administrador. Muestra la información del usuario con privilegios de administrador. |
| `/api/v1/userAdmin/{id}` | Actualizar los datos de UserAdmin | `PUT` | `PUT /api/v1/userAdmin/{id}` | `ud: Integer` | `Id: 1` | `{"display": "string","username": "string","email": "string","password": "string","adminAccess": true,"securityPin": "string"}` | Esta solicitud PUT actualiza los datos de un usuario administrador. Permite modificar la información del usuario con privilegios de administrador. |
| `/api/v1/userClients` | Añadir nuevo cliente | `POST` | `POST /api/v1/userClients` | Ninguno | `{"display": "XDDDDDDDD","username": "CDSF","email": "string@gmail.com","password": "string","icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string"}` | `{"icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string","orders": [],"subscription": "freeplan","id": 4,"display": "XDDDDDDDD","username": "CDSF","email": "string@gmail.com"}` | Este POST request crea un nuevo cliente en el sistema. Incluye información de visualización, un correo electrónico, una URL de ícono y una suscripción predeterminada 'freeplan'. |
| `/api/v1/userClients` | Obtener los datos de todos los clientes | `GET` | `GET /api/v1/userClients` | Ninguno | `http://localhost:5119/api/v1/userclients` | `{"icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string","orders": [{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "delivered","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}],"subscription": "communityplan","id": 2,"display": "string","username": "string","email": "user@example.com"}` | Esta solicitud GET obtiene los datos de todos los clientes registrados. Devuelve una lista de objetos cliente con sus detalles. |
| `/api/v1/userClients/{id}` | Obtener los datos de un usuario en específico | `GET` | `GET /api/v1/userClients/{id}` | `id: Integer` | `Id: 2` | `{"icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string","orders": [],"subscription": "freeplan","id": 2,"display": "string","username": "string","email": "string@gmail.com"}` | Esta solicitud GET obtiene los datos de un usuario específico, utilizando su ID. Muestra los detalles completos del cliente buscado. |
| `/api/v1/userClients/{id}` | Actualizar los datos de un UserClient existente | `PUT` | `PUT /api/v1/userClients/{id}` | `id: Integer` | `Id: 1` | `{"display": "string","username": "string","email": "user@example.com","password": "string","icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string","subscription": "freeplan"}` | Esta solicitud PUT actualiza los datos de un cliente existente, utilizando su ID. Permite modificar campos como display, username, password, icon, phrase y subscription. |
| `/api/v1/userClients/{id}` | Eliminar un UserClient previamente creado | `DELETE` | `DELETE /api/v1/userClients/{id}` | `id: Integer` | `Id: 3` | `userClient eliminado exitosamente.` | Esta solicitud DELETE elimina un cliente previamente creado del sistema, usando su ID. Borra por completo el registro del cliente. |
| `/api/v1/userClients/{id}/subscription` | Actualizar el plan de suscripción de un cliente de usuario | `PUT` | `PUT /api/v1/userClients/{id}/suscription` | `id: Integer` | `Id: 4` | `{"icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string","orders": [],"subscription": "communityplan","id": 4,"display": "XDDDDDDDD","username": "CDSF","email": "string@gmail.com"}` | Esta solicitud PUT actualiza la suscripción de un cliente específico, dado su ID. Permite cambiar la suscripción entre 'freeplan' y 'communityplan'. |
| `/api/v1/userClients/{id}/favorites/{bookId}` | Agregar un libro existente como favorito | `POST` | `POST /api/v1/userClients/{id}/favorites/{bookId}` | `id: Integer`, `bookId: Integer` | `userClientId: 1`, `BookId: 1` | `{"icon": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","phrase": "string","orders": [{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "delivered","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}],"subscription": "communityplan","id": 2,"display": "string","username": "string","email": "user@example.com"}` | Esta solicitud POST agrega un libro existente como favorito a un usuario. Permite añadir un libro a la lista de favoritos de un cliente. |
| `/api/v1/userClients/{id}/favorites/{bookId}` | Eliminar un libro favorito de un UserClient previamente creado | `DELETE` | `DELETE /api/v1/userClients/{id}/favorites/{bookId}` | `id: Integer`, `bookId: Integer` | `Id: 2` | `favorito eliminado exitosamente.` | Esta solicitud DELETE elimina un libro de la lista de favoritos de un usuario. Permite quitar un libro de los favoritos de un cliente. |
| `/api/v1/userClients/{userClientId}/favorites` | Obtener los datos de los favoritos que le pertenecen a un usuario en específico | `GET` | `GET /api/v1/userClients/{userClientId}/favorites` | `id: Integer` | `http://localhost:5119/api/v1/userclients/2/favorites` | `{"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 49,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []}` | Esta solicitud GET obtiene los libros favoritos de un usuario específico. Muestra la lista de libros marcados como favoritos por el usuario. |
| `/api/v1/notifications/user/{userClientId}` | Obtener las notificaciones activas de un usuario | `GET` | `GET /api/v1/notifications/user/{userClientId}` | `id: Integer` | `userClientId: 2` | `[{"id": 4,"userClientId": 2,"createdAt": "2025-06-21T05:39:05.365242","type": 2,"title": "Order Received","content": "Thanks for your order! It's being processed.","isRead": false,"isHidden": false}]` | Esta solicitud GET obtiene las notificaciones activas de un usuario específico. Muestra las notificaciones que no han sido ocultadas para ese usuario. |
| `/api/v1/notifications/{id}` | Obtener los datos de una notificación en específicos | `GET` | `GET /api/v1/notifications/{id}` | `id: Integer` | `Id: 1` | `{"id": 1,"userClientId": 2,"createdAt": "2025-06-21T05:29:40.197533","type": 0,"title": "Welcome to Livria!","content": "We're thrilled to have you here.","isRead": false,"isHidden": true}` | Esta solicitud GET obtiene los datos de una notificación en específico, utilizando su ID. Muestra los detalles de la notificación buscada. |
| `/api/v1/notifications/hide-all` | Ocultar todas las notificaciones de un usuario | `PATCH` | `PATCH /api/v1/notifications/hide-all` | `userClientId: Integer` | `{"userClientId": 2}` | `content-language: es-ESdate: Sat,21 Jun 2025 07:14:07 GMTserver: Kestrel` | Esta solicitud PATCH oculta todas las notificaciones activas de un usuario. Marca las notificaciones como ocultas (eliminación lógica) sin borrarlas físicamente. |
| `/api/v1/orders` | Crear una nueva orden | `POST` | `POST /api/v1/orders` | Ninguno | `{"userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shippingDetails": {"address": "string","city": "string","district": "string","reference": "string"},"cartItemIds": [2]}` | `{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.2790128Z","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}` | Esta solicitud POST crea una nueva orden en el sistema. Permite registrar una compra con detalles del cliente, envío y los ítems comprados. |
| `/api/v1/orders/{id}` | Obtener los datos de un orden en específico | `GET` | `GET /api/v1/orders/{id}` | `id: Integer` | `Id: 1` | `{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}` | Esta solicitud GET obtiene los datos de una orden en específico, usando su ID. Muestra los detalles de la orden buscada. |
| `/api/v1/orders/code/{code}` | Obtener los datos de una orden en específico por medio de su código | `GET` | `GET /api/v1/orders/code/{code}` | `code: String` | `code: 292W4X` | `{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}` | Esta solicitud GET obtiene los datos de una orden específica por medio de su código. Muestra los detalles de la orden que coincida con el código. |
| `/api/v1/orders/users/{userClientId}` | Obtener los datos de las órdenes de un usuario cliente en específico. | `GET` | `GET /api/v1/orders/users/{userClientId}` | `userClientId: Integer` | `userClientId: 2` | `[{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "delivered","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}]` | Esta solicitud GET obtiene todas las órdenes de un usuario cliente específico, usando su ID. Muestra una lista de todas las compras realizadas por ese usuario. |
| `/api/v1/orders/{orderId}/status` | Actualizar el estado de una orden | `PUT` | `PUT /api/v1/orders/{orderId}/status` | `status: string` | `{"status": "in progress"}` | `{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "in progress","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": [{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}]}` | Esta solicitud PUT actualiza el estado de una orden, usando su ID. Permite cambiar el estado de una orden entre 'pending', 'in progress' o 'delivered'. |
| `/api/v1/posts/community/{communityId}` | Crear una nueva publicación de una comunidad existente | `POST` | `POST /api/v1/posts/community/{communityId}` | `communityId: integer` | `{"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg"}` | `{"id": 1,"communityId": 1,"userId": 2,"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","createdAt": "2025-06-21T05:40:19.5549411Z"}` | Esta solicitud POST crea una nueva publicación en una comunidad existente, dado el ID de la comunidad. Permite añadir contenido a una comunidad específica. |
| `/api/v1/posts/{id}` | Obtener los datos de una publicación en específico | `GET` | `GET /api/v1/posts/{id}` | `id: Integer` | `Id: 1` | `{"id": 1,"communityId": 1,"userId": 2,"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","createdAt": "2025-06-21T05:40:19.554941"}` | Esta solicitud GET obtiene los datos de una publicación específica, usando su ID. Muestra los detalles de la publicación buscada. |
| `/api/v1/posts` | Obtener los datos de todas las publicaciones | `GET` | `GET /api/v1/posts` | Ninguno | `http://localhost:5119/api/v1/posts` | `[{"id": 1,"communityId": 1,"userId": 2,"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","createdAt": "2025-06-21T05:40:19.554941"}]` | Esta solicitud GET obtiene los datos de todas las publicaciones existentes. Muestra una lista completa de todas las publicaciones en el sistema. |
| `/api/v1/posts/community/{communityId}` | Obtener todas las publicaciones para una comunidad específica | `GET` | `GET /api/v1/posts/community/{communityId}` | `communityId: Integer` | `communityId: 1` | `{"id": 1,"communityId": 1,"userId": 2,"username": "string","content": "string","img": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","createdAt": "2025-06-21T05:40:19.554941"}` | Esta solicitud GET obtiene todas las publicaciones para una comunidad específica, usando el ID de la comunidad. Muestra una lista de las publicaciones asociadas a esa comunidad. |
| `/api/v1/recommendations/users/{userClientId}` | Obtener las recomendaciones de libros que le pertenecen a un usuario en específico | `GET` | `GET /api/v1/recommendations/users/{userClientId}` | `userClientId: Integer` | `userClientId: 2` | `{"userClientId": 2,"recommendedBooks": [{"id": 2,"title": "XDDDDD","description": "string","author": "string","salePrice": 4,"stock": 20,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []},{"id": 3,"title": "XD","description": "string","author": "string","salePrice": 4,"stock": 20,"cover": "https://i.kinja-img.com/image/upload/c_fit,q_60,w_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": []}]}` | Esta solicitud GET obtiene las recomendaciones de libros que le pertenecen a un usuario específico. Muestra una lista de libros recomendados para el usuario. |

**Capturas:**

<p align="center">
  <img src="https://i.imgur.com/dlZ579h.png" alt="full1" width="500">
</p>

Este POST request crea un nuevo cliente en el sistema. Incluye información de visualización, un correo electrónico, una URL de ícono y una suscripción predeterminada 'freeplan'.

<p align="center">
  <img src="https://i.imgur.com/x3T94SU.png" alt="full2" width="500">
</p>

Esta solicitud GET obtiene los datos de todos los clientes registrados. Devuelve una lista de objetos cliente con sus detalles.

<p align="center">
  <img src="https://i.imgur.com/oBe6pyg.png" alt="full3" width="500">
</p>

Esta solicitud GET obtiene los datos de un usuario específico, utilizando su ID. Muestra los detalles completos del cliente buscado.

<p align="center">
  <img src="https://imgur.com/d1HSXAG.png" alt="full4" width="500">
</p>

Esta solicitud PUT actualiza los datos de un cliente existente, utilizando su ID. Permite modificar campos como display, username, password, icon, phrase y subscription.

<p align="center">
  <img src="https://i.imgur.com/hgeUVYy.png" alt="full5" width="500">
</p>

Esta solicitud DELETE elimina un cliente previamente creado del sistema, usando su ID. Borra por completo el registro del cliente.

<p align="center">
  <img src="https://i.imgur.com/iRJ52bU.png" alt="full6" width="500">
</p>

Esta solicitud PUT actualiza la suscripción de un cliente específico, dado su ID. Permite cambiar la suscripción entre 'freeplan' y 'communityplan'.

<p align="center">
  <img src="https://i.imgur.com/EII0Imi.png" alt="full7" width="500">
</p>

Esta solicitud POST crea un nuevo libro en el sistema. Permite registrar un libro con su título, descripción, autor, precio, stock, imagen de portada, género y idioma.

<p align="center">
  <img src="https://i.imgur.com/AaiAb4V.png" alt="full8" width="500">
</p>

Esta solicitud GET obtiene los datos de todos los libros disponibles. Muestra una lista completa de los libros registrados en el sistema.

<p align="center">
  <img src="https://i.imgur.com/TL49BEu.png" alt="full9" width="500">
</p>

Esta solicitud GET obtiene los datos de un libro en específico, utilizando su ID. Muestra los detalles del libro solicitado.

<p align="center">
  <img src="https://i.imgur.com/bAB6tPG.png" alt="full10" width="500">
</p>

Esta solicitud PUT actualiza el stock disponible de un libro específico, usando su ID. Permite modificar la cantidad de libros en existencia.

<p align="center">
  <img src="https://i.imgur.com/vDtyD46.png" alt="full11" width="500">
</p>

Esta solicitud POST crea un nuevo ítem en el carrito de un usuario. Permite añadir un libro con una cantidad específica al carrito de un cliente.

<p align="center">
  <img src="https://i.imgur.com/DhGYLO5.png" alt="full12" width="500">
</p>

Esta solicitud PUT actualiza la cantidad de un libro en un ítem de carrito específico. Permite modificar la cantidad de un libro ya existente en el carrito de un usuario.

<p align="center">
  <img src="https://i.imgur.com/APFjJ2z.png" alt="full13" width="500">
</p>

Esta solicitud DELETE elimina un ítem específico del carrito de un usuario. Borra un libro determinado del carrito de compras.

<p align="center">
  <img src="https://i.imgur.com/DRh4Uy6.png" alt="full14" width="500">
</p>

Esta solicitud GET obtiene los datos de un libro perteneciente a un carrito en específico, utilizando el ID del ítem del carrito. Muestra los detalles del libro y la cantidad en el carrito.

<p align="center">
  <img src="https://i.imgur.com/OU3G46S.png" alt="full15" width="500">
</p>

Esta solicitud GET obtiene todos los ítems del carrito de un usuario específico. Muestra los libros y sus cantidades en el carrito de ese usuario.

<p align="center">
  <img src="https://i.imgur.com/5E7XqP4.png" alt="full16" width="500">
</p>

Esta solicitud POST crea una nueva comunidad en el sistema. Permite registrar una comunidad con su nombre, descripción, tipo, imagen y banner.

<p align="center">
  <img src="https://i.imgur.com/zW5ISIJ.png" alt="full17" width="500">
</p>

Esta solicitud GET obtiene los datos de todas las comunidades existentes. Muestra una lista de comunidades con sus detalles.

<p align="center">
  <img src="https://i.imgur.com/u4BAZQ6.png" alt="full18" width="500">
</p>

Esta solicitud GET obtiene los datos de una comunidad en específico, utilizando su ID. Muestra los detalles de la comunidad buscada.

<p align="center">
  <img src="https://i.imgur.com/MRYQlc6.png" alt="full19" width="500">
</p>

Esta solicitud POST permite a un usuario unirse a una comunidad existente. Asocia un usuario a una comunidad específica.

<p align="center">
  <img src="https://i.imgur.com/XUhu6tI.png" alt="full20" width="500">
</p>

Esta solicitud GET obtiene las notificaciones activas de un usuario específico. Muestra las notificaciones que no han sido ocultadas para ese usuario.

<p align="center">
  <img src="https://i.imgur.com/eAzLWeI.png" alt="full21" width="500">
</p>

Esta solicitud GET obtiene los datos de una notificación en específico, utilizando su ID. Muestra los detalles de la notificación buscada.

<p align="center">
  <img src="https://i.imgur.com/9oZ3gvF.png" alt="full22" width="500">
</p>

Esta solicitud PATCH oculta todas las notificaciones activas de un usuario. Marca las notificaciones como ocultas (eliminación lógica) sin borrarlas físicamente.

<p align="center">
  <img src="https://imgur.com/JEB5TDV.png" alt="full23" width="500">
</p>

Esta solicitud POST crea una nueva orden en el sistema. Permite registrar una compra con detalles del cliente, envío y los ítems comprados.

<p align="center">
  <img src="https://i.imgur.com/grxBCqC.png" alt="full24" width="500">
</p>

Esta solicitud GET obtiene los datos de una orden en específico, usando su ID. Muestra los detalles de la orden buscada.

<p align="center">
  <img src="https://i.imgur.com/OVoTg8s.png" alt="full25" width="500">
</p>

Esta solicitud GET obtiene los datos de una orden específica por medio de su código. Muestra los detalles de la orden que coincida con el código.

<p align="center">
  <img src="https://i.imgur.com/PYroDqD.png" alt="full26" width="500">
</p>

Esta solicitud GET obtiene todas las órdenes de un usuario cliente específico, usando su ID. Muestra una lista de todas las compras realizadas por ese usuario.

<p align="center">
  <img src="https://i.imgur.com/Y8QMdNE.png" alt="full27" width="500">
</p>

Esta solicitud PUT actualiza el estado de una orden, usando su ID. Permite cambiar el estado de una orden entre 'pending', 'in progress' o 'delivered'.

<p align="center">
  <img src="https://i.imgur.com/Nnq1Zl0.png" alt="full28" width="500">
</p>

Esta solicitud POST crea una nueva publicación en una comunidad existente, dado el ID de la comunidad. Permite añadir contenido a una comunidad específica.

<p align="center">
  <img src="https://i.imgur.com/RHMoC0z.png" alt="full29" width="500">
</p>

Esta solicitud GET obtiene los datos de una publicación específica, usando su ID. Muestra los detalles de la publicación buscada.

<p align="center">
  <img src="https://i.imgur.com/nEdQR3q.png" alt="full30" width="500">
</p>

Esta solicitud GET obtiene los datos de todas las publicaciones existentes. Muestra una lista completa de todas las publicaciones en el sistema.

<p align="center">
  <img src="https://i.imgur.com/rG7RgU5.png" alt="full31" width="500">
</p>

Esta solicitud GET obtiene todas las publicaciones para una comunidad específica, usando el ID de la comunidad. Muestra una lista de las publicaciones asociadas a esa comunidad.

<p align="center">
  <img src="https://i.imgur.com/R7e2tza.png" alt="full32" width="500">
</p>

Esta solicitud POST agrega un libro existente como favorito a un usuario. Permite añadir un libro a la lista de favoritos de un cliente.

<p align="center">
  <img src="https://i.imgur.com/vJYwjQF.png" alt="full33" width="500">
</p>

Esta solicitud DELETE elimina un libro de la lista de favoritos de un usuario. Permite quitar un libro de los favoritos de un cliente.

<p align="center">
  <img src="https://i.imgur.com/fCyYN6r.png" alt="full34" width="500">
</p>

Esta solicitud GET obtiene los libros favoritos de un usuario específico. Muestra la lista de libros marcados como favoritos por el usuario.

<p align="center">
  <img src="https://i.imgur.com/ZXUokY0.png" alt="full35" width="500">
</p>

Esta solicitud GET obtiene las recomendaciones de libros que le pertenecen a un usuario específico. Muestra una lista de libros recomendados para el usuario.

<p align="center">
  <img src="https://i.imgur.com/xN5uuIE.png" alt="full36" width="500">
</p>

Esta solicitud POST crea una nueva reseña en el sistema. Permite añadir una reseña con calificación y contenido para un libro y un usuario.

<p align="center">
  <img src="https://i.imgur.com/o0oiTlh.png" alt="full37" width="500">
</p>

Esta solicitud GET obtiene los datos de todas las reseñas. Muestra una lista completa de todas las reseñas en el sistema.

<p align="center">
  <img src="https://i.imgur.com/9xLOPYS.png" alt="full38" width="500">
</p>

Esta solicitud GET obtiene los datos de una reseña en específico, usando su ID. Muestra los detalles de la reseña buscada.

<p align="center">
  <img src="https://i.imgur.com/pRpVLGj.png" alt="full39" width="500">
</p>

Esta solicitud GET obtiene todas las reseñas para un libro específico. Muestra una lista de todas las reseñas asociadas a un libro dado.

<p align="center">
  <img src="https://i.imgur.com/wxZACo7.png" alt="full40" width="500">
</p>

Esta solicitud GET obtiene los datos del usuario administrador. Muestra la información del usuario con privilegios de administrador.

<p align="center">
  <img src="https://i.imgur.com/hgsTEeV.png" alt="full41" width="500">
</p>

Esta solicitud PUT actualiza los datos de un usuario administrador. Permite modificar la información del usuario con privilegios de administrador.

#### 1. Libros (Books)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de todos los libros.
    * `GET`: Obtener los datos de un libro en específico por Id.
    * `POST`: Crear un nuevo libro.
    * `PUT`: Actualizar el stock de un libro.
* **Descripción:** Proporciona funcionalidades para obtener información sobre los libros, agregar reseñas, y obtener detalles de libros específicos.

#### 2. Reseñas de los libros (Reviews)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de todas las reseñas.
    * `GET`: Obtener los datos de una reseña en específico.
    * `GET`: Obtener todas las reseñas para un libro específico.
    * `POST`: Crear una nueva reseña.
* **Descripción:** Permite gestionar las reseñas de libros, permitiendo que los usuarios puedan crear y consultar comentarios sobre los libros disponibles en la plataforma.

#### 3. Comunidades (Communities)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de todas las comunidades.
    * `GET`: Obtener los datos de una comunidad en específico por id.
    * `POST`: Crear una nueva comunidad.
    * `POST`: Unirse a una comunidad existente.
* **Descripción:** Permite gestionar las comunidades literarias, crear nuevas comunidades y realizar publicaciones dentro de ellas.

#### 4. Publicaciones en comunidades (Posts)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de una publicación en específico.
    * `GET`: Obtener los datos de todas las publicaciones.
    * `GET`: Obtener todas las publicaciones para una comunidad específica.
    * `POST`: Crear una nueva publicación en una comunidad existente.
* **Descripción:** Gestiona las publicaciones dentro de las comunidades literarias, permitiendo a los usuarios compartir contenido y participar activamente en discusiones dentro de sus comunidades literarias favoritas.

#### 5. Notificaciones (Notifications)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener las notificaciones activas de un usuario.
    * `GET`: Obtener los datos de una notificación en específico.
    * `POST`: Crear una nueva notificación.
    * `PATCH`: Ocultar todas las notificaciones de un usuario.
* **Descripción:** Permite la gestión de notificaciones, incluyendo la notificación de acciones de usuario, como la creación de órdenes o actualizaciones de suscripciones.

#### 6. Carrito de Compra (CartItems)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de un libro perteneciente a un carrito en específico.
    * `GET`: Obtener los datos del carrito del usuario especificado.
    * `POST`: Crear un nuevo ítem en el carrito.
    * `PUT`: Actualizar la cantidad de libros de un ítem de un carrito existente.
    * `DELETE`: Eliminar un ítem de un carrito de un UserClient previamente creado.
* **Descripción:** Permite gestionar los productos seleccionados para compra, actualizar cantidades y realizar eliminaciones.

#### 7. Orden de Compra (Orders)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de una orden en específico.
    * `GET`: Obtener los datos de una orden en específico por medio de su código.
    * `GET`: Obtener los datos de las órdenes de un usuario cliente en específico.
    * `POST`: Crear una nueva orden.
    * `PUT`: Actualiza el estado de una orden.
* **Descripción:** Gestiona el proceso de compra, incluyendo la creación de órdenes y la obtención de detalles sobre pedidos específicos.

#### 8. Usuario Administrador (UserAdmins)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos del usuario administrador.
    * `PUT`: Actualizar los datos del UserAdmin.
* **Descripción:** Permite gestionar la información de los usuarios administradores, incluyendo detalle de registro y actualización.

#### 9. Usuarios (UserClients)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de todos los clientes.
    * `GET`: Obtener los datos de un usuario en específico.
    * `GET`: Obtener los datos de los favoritos que le pertenecen a un usuario en específico.
    * `POST`: Añadir nuevo cliente.
    * `POST`: Agregar un libro existente como favorito.
    * `PUT`: Actualizar los datos de UserClient existente.
    * `PUT`: Actualizar el plan de suscripción de un cliente de usuario.
    * `DELETE`: Eliminar un usuario cliente de la plataforma.
    * `DELETE`: Eliminar un libro favorito de un UserCliente previamente creado.
* **Descripción:** Permite gestionar la información de los usuarios clientes, incluyendo detalle de registro y actualización.

#### 10. Recomendaciones (Recommendations)
* **Operaciones CRUD soportadas:**
    * `GET`: Obtener los datos de las recomendaciones que le pertenecen a un usuario en específico.
* **Descripción:** Permite obtener una lista de libros recomendados para un usuario según sus preferencias y su historial de actividad. La solicitud de recomendaciones se realiza mediante el `userClientId`, que identifica al usuario dentro de la plataforma de Livria.

La documentación de la API ha sido integrada utilizando OpenAPI y Swagger. Estos permiten a los desarrolladores acceder a una interfaz interactiva para explorar y probar los endpoints de la API. Además, Swagger proporciona una visión detallada de todos los endpoints disponibles, los métodos soportados, los parámetros requeridos y las respuestas esperadas, facilitando así la integración de nuevos servicios y la extensión de la API.

En nuestro proyecto, a través de la interfaz Swagger, nos permite visualizar y probar los endpoints para gestionar libros, carritos de compra, pedidos, usuarios, comunidades y notificaciones. Esto proporciona una herramienta útil y mejora la eficiencia en el desarrollo de nuevas funcionalidades.


#### 5.2.3.7. Software Deployment Evidence for Sprint Review
Durante este Sprint 3, el equipo se centró en el desarrollo y despliegue de las funcionalidades backend para la aplicación web de Livria. A continuación, se detallan los pasos realizados para asegurar que el backend estuviera correctamente implementado y desplegado en el entorno de producción.

#### Actividades de Despliegue:

1.  **Desarrollo de la API Backend:**
    * La API RESTful fue desarrollada utilizando **.NET** como el marco principal de trabajo y **MySQL** como sistema de gestión de bases de datos. La API permite la gestión de entidades clave como libros, carritos de compra, pedidos, usuarios, comunidades y notificaciones.

2.  **Despliegue en el Entorno de Desarrollo:**
    * Se utilizó **Swagger** para documentar la API y proporcionar una interfaz interactiva que permite explorar y probar todos los endpoints.

3.  **Despliegue en el Entorno de Producción:**
    * La API fue desplegada en el entorno de producción, y se configuraron las instancias necesarias en el servidor para asegurar la disponibilidad continua.
    * **MySQL** fue configurado en el servidor de producción para manejar moderados volúmenes de datos, y se optimizó la base de datos para garantizar un rendimiento eficiente.

4.  **Configuración y Gestión de la Base de Datos:**
    * La base de datos fue migrada a **MySQL**, y se implementaron todas las relaciones necesarias entre las tablas para garantizar la integridad de los datos.
    * Se realizaron pruebas de rendimiento en las consultas de la base de datos para asegurarse de que las operaciones de lectura y escritura fueran rápidas y escalables.

<p align="center">
  <img src="https://imgur.com/yYQRizP.png" alt="confi1" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/FazSUmG.png" alt="confi2" width="500">
</p>

#### 5. Deployment en Azure

Para realizar la publicación del proyecto en Azure se siguieron los pasos a continuación:

* **Instalar el plugin de Azure en Rider:**

<p align="center">
  <img src="https://imgur.com/Kn1sgYI.png" alt="confi3" width="500">
</p>

* **Acceder a la cuenta de Azure a utilizar mediante Sign-In para conectarlo con Rider:**

<p align="center">
  <img src="https://imgur.com/3JhSeyL.png" alt="confi4" width="500">
</p>

* **Antes de continuar, asegurarse de que Swagger esté habilitado para producción. Para ello, contar con las siguientes líneas de código en Program.cs:**

<p align="center">
  <img src="https://imgur.com/Ok945Jw.png" alt="confi5" width="500">
</p>

* **Dar click derecho en el proyecto y seleccionar la opción de Publish (Publicar). Seguidamente, elegir la opción de Azure:**

<p align="center">
  <img src="https://imgur.com/heZSBPQ.png" alt="confi6" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/0gZSPV4.png" alt="confi7" width="500">
</p>

* **A continuación, configuramos la publicación del proyecto. Se debe crear una nueva Web App y seleccionar la opción de More settings. Ahí, se debe seleccionar un Resource Group en Azure existente o crear uno nuevo:**

<p align="center">
  <img src="https://imgur.com/uy8opZC.png" alt="confi8" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/wgBHr5H.png" alt="confi9" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/WiHTSAu.png" alt="confi10" width="500">
</p>

* **Tras haber seleccionado las opciones de Ok y de Run en las ventanas anteriores, el proyecto empezará con el deployment. Al finalizar, mostrará el link de conexión:**

<p align="center">
  <img src="https://imgur.com/LVrzjD9.png" alt="confi11" width="500">
</p>

* **Al hacer click en este link, nos llevará a la aplicación web deployada. Inicialmente, saldrá que la página web no se encuentra. Para ello, colocar “/swagger/index.html” al final de la URL y aparecerá la pestaña de Swagger con nuestros endpoints:**

<p align="center">
  <img src="https://imgur.com/qP4cNJd.png" alt="confi12" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/neGM8Qg.png" alt="confi13" width="500">
</p>

<p align="center">
  <img src="https://imgur.com/fFt36E5.png" alt="confi14" width="500">
</p>

#### 5.2.3.8. Team Collaboration Insights during Sprint

Durante este Sprint 3, el equipo se centró en la implementación de las funcionalidades clave del **backend** para la aplicación web de Livria. Utilizando **.NET** como marco principal de desarrollo y **MySQL** como sistema de gestión de bases de datos, se lograron avances significativos en la gestión de datos, incluyendo la creación de **APIs RESTful** para operaciones CRUD esenciales como la gestión de libros, carritos de compra, pedidos, usuarios, comunidades, y notificaciones. Además, se integró la documentación de la API a través de **OpenAPI y Swagger**, lo que facilita la comprensión, prueba y uso de los endpoints para los desarrolladores.

#### Actividades de implementación:

* **Estructura del Backend:** Se implementaron los endpoints necesarios para gestionar las entidades clave de la aplicación. Las APIs fueron desarrolladas usando .NET y se conectaron a una base de datos MySQL para almacenar y gestionar los datos de libros, carritos, pedidos, usuarios, comunidades, notificaciones y recomendar libros.
* **Operaciones CRUD:** Las funcionalidades básicas de Create, Read, Update, y Delete fueron implementadas para cada entidad, asegurando que el sistema pudiera manejar de manera eficiente los datos del catálogo de libros, la información del usuario, las publicaciones en las comunidades, los pedidos de compra, etc.
* **Documentación con OpenAPI y Swagger:** Se implementó la documentación interactiva de la API utilizando OpenAPI y Swagger, permitiendo a los desarrolladores explorar los endpoints de manera visual y probar cada uno de ellos directamente desde la interfaz. Swagger facilita la interacción con los endpoints de la API, garantizando que las funcionalidades sean fáciles de integrar y probar en el entorno de desarrollo.
* **Base de Datos MySQL:** La base de datos fue diseñada con relaciones bien estructuradas entre las tablas, lo que permite una gestión eficiente y escalable de los datos. Las operaciones de lectura y escritura fueron optimizadas para asegurar un rendimiento adecuado incluso con moderados volúmenes de datos.
* **Mejoras en el Frontend:** Se realizaron correcciones y mejoras en el frontend, específicamente en la sección de usuarios. Se corrigieron algunos errores de diseño y se optimizó la experiencia de usuario en la plataforma, asegurando una navegación más fluida y visualmente atractiva.
* **Dashboard para Administradores:** Se incorporó una nueva sección de Dashboard en el frontend dedicada exclusivamente a los administradores. Esta sección permite gestionar los libros, ver estadísticas de ventas y supervisar las operaciones clave de la plataforma, lo que facilita la administración del sistema de forma centralizada.

#### Analítica de colaboración en GitHub:

##### Repositorio livria-web-app
* Historial de commits:

  <p align="center">
  <img src="https://imgur.com/zMNAKvd.png" alt="confi15" width="500">
  </p>

* Colaboradores activos en el repositorio:

  <p align="center">
  <img src="https://imgur.com/deWOqo2.png" alt="confi16" width="500">
  </p>
  
* Histograma de contribuciones en el tiempo:
  
  <p align="center">
  <img src="https://imgur.com/scsgZbe.png" alt="confi17" width="500">
  </p>
  
##### Repositorio livria-backend
* Historial de commits:

  <p align="center">
  <img src="https://imgur.com/MPGqeMr.png" alt="confi18" width="500">
  </p>
  
* Colaboradores activos en el repositorio:

  <p align="center">
  <img src="https://imgur.com/FYXgufk.png" alt="confi19" width="500">
  </p>
  
* Histograma de contribuciones en el tiempo:

  <p align="center">
  <img src="https://imgur.com/cY3fNhY.png" alt="confi20" width="500">
  </p>

##### Repositorio livria-db-scripts
* Historial de commits:

  <p align="center">
  <img src="https://imgur.com/AAPXo2D.png" alt="confi21" width="500">
  </p>
  
* Colaboradores activos en el repositorio:

  <p align="center">
  <img src="https://imgur.com/pwJDUK7.png" alt="confi22" width="500">
  </p>
  
* Histograma de contribuciones en el tiempo: 

  <p align="center">
  <img src="https://imgur.com/rlJhzYZ.png" alt="confi23" width="500">
  </p>
  
##### Repositorio livria.github.io
* Historial de commits:

  <p align="center">
  <img src="https://imgur.com/E2nr6Xz.png" alt="confi24" width="500">
  </p>
  
* Colaboradores activos en el repositorio:

  <p align="center">
  <img src="https://imgur.com/H4diLGH.png" alt="confi25" width="500">
  </p>
  
* Histograma de contribuciones en el tiempo:

  <p align="center">
  <img src="https://imgur.com/bWuN3Qd.png" alt="confi26" width="500">
  </p>


### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning

En esta reunión del Sprint Planning se va a integrar el frontend con el backend, se añadirá el bounded context de Identity and Access Management (IAM) usando el token Json Web Token (JWT) y se mejorará funcionalidades de los endpoints del backend. En esta reunión el equipo Scrum estableció diversas actividades a cada integrante para desarrollar 4 User Stories y 12 Technical Stories relevantes para la aplicación web.

A continuación, se mostrará la tabla del Sprint Planning 4:

| Sprint # | Sprint 4 |
|---|---|
| **Sprint Planning Background** | |
| **Date** | 2025-07-04 |
| **Time** | 07:30 PM |
| **Location** | Virtual |
| **Prepared By** | Ainhoa Lucía Castillo Garay, Marcelo Alejandro Binda Arbañil |
| **Attendees (to planning meeting)** | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Binda Arbañil / Gabriel Sebastián Borja Molina / Jhosep Jamil Argomedo Camacho / Melisa Geraldine Sulca Silva |
| **Sprint n - 4 Review Summary** | Durante el Sprint 4, se desarrollaron 6 historias de usuarios y 12 technical stories enfocado principalmente en la implementación de autenticación y autorización para administradores y usuarios, utilizando JWT (JSON Web Token), el desarrollo del bounded context de Gestión de Identidad y Acceso (IAM), mejoras en el backend, así como en la integración y optimización del frontend y backend de la plataforma Livria. <br><br> El equipo de programadores, conformado por Marcelo Binda y Gabriel Borja se destacó en la optimización de la lógica de autenticación y manejo de sesiones con JWT, asegurando que el sistema validará los tokens de manera eficiente, mejorando la velocidad de las interacciones entre el frontend y el backend. <br><br> Jhosep Argomedo y Melisa Sulca trabajaron de manera colaborativa en la implementación del control de roles y permisos dentro del backend, garantizando que cada usuario tuviera acceso solo a los recursos adecuados, según su rol (administrador o usuario), lo que optimizó la seguridad y la autorización dentro de la plataforma. <br><br> Ainhoa Castillo desempeñó un papel crucial en la integración del frontend con el backend, asegurándose de que las funcionalidades de inicio de sesión y manejo de sesiones se realizarán sin contratiempos, permitiendo una experiencia fluida para los usuarios al interactuar con la aplicación. También trabajaron en la sincronización correcta de los datos entre ambas partes y en la implementación de las medidas de seguridad necesarias para proteger los datos de los usuarios. |
| **Sprint n - 4 Retrospective Summary** | Durante el Sprint 4, se prevé un alto enfoque en la integración entre el frontend y backend, y gestión de identidad y acceso. <br><br> Los aspectos que se destacarán durante este sprint incluyen la implementación segura de JWT, la cual es asegurarse de que los tokens sean generados y gestionados de manera eficiente y segura. También, la autenticación y autorización en backend que consiste en la implementación de endpoints de autenticación que se integrarán con el sistema de backend y se gestionan las rutas para manejar tokens JWT. Además,se agregará la integración fluida entre frontend y backend, en la cual se garantizará que la comunicación entre el frontend y el backend sea estable y funcional, utilizando el mecanismo de autenticación basado en JWT para todas las solicitudes seguras. |
| **Sprint Goal & User Stories** | |
| **Sprint Goal** | **Our focus is** on implementing Identity and Access Management (IAM) with JSON Web Tokens (JWT) for secure authentication and authorization in the Livria web app. We will also focus on integrating the frontend with the backend to ensure seamless communication and secure user interactions across the platform. <br><br> **We believe it delivers** a robust security framework for user authentication, ensuring that only authorized users can access protected resources. Additionally, the integration of JWT with the frontend and backend will enable secure communication and efficient access management. <br><br> **This will be confirmed when** all user authentication endpoints are secured with JWT, the frontend properly sends and receives JWT tokens, and successful integration between the frontend and backend is verified. We will also verify that the system is secure, protected against common vulnerabilities. |
| **Sprint Velocity** | 93 |
| **Sum of Story Points** | 89 |


#### 5.2.4.2. Aspect Leaders and Collaborators

Durante el Sprint 4, se ha avanzado significativamente en la implementación de la autenticación y autorización de usuarios mediante JWT, mejoras en el backend, así como en la integración del frontend con el backend de la aplicación Livria. Para organizar de manera eficiente las tareas del equipo, se ha creado una matriz de Liderazgo y Colaboración (LACX), donde se asignan responsabilidades específicas a cada miembro del equipo. Algunos integrantes asumieron el rol de líder (L) y otros desempeñaron el rol de colaborador (C).

Los aspectos definidos para este Sprint son:

1.  Bounded Context de Gestión de Identidad y Acceso (IAM)
2.  Implementación del token JWT
3.  Mejoras en el backend
4.  Integración del frontend con el backend
5.  Finalización de la landing page

| Team Member (Last Name, First Name) | GitHub Username | B. C. de Gestión de Identidad y Acceso (IAM) | Implementación del token JWT | Mejoras en el backend | Integración del frontend con el backend | Finalización de la landing page |
|-------------------------------------|-----------------|----------------------------------------------|------------------------------|-----------------------|-----------------------------------------|---------------------------------|
| Castillo Garay, Ainhoa Lucía        | noaa01100001    | C                 | C                    | C              | L                      | C                       |
| Binda Arbañil, Marcelo Alejandro    | MarceloHkd      | L                 | C                    | L              | C                      | C                       |
| Borja Molina, Gabriel Sebastián     | borj410         | C                 | L                    | C              | C                      | C                       |
| Argomedo Camacho, Jhosep Jamil      | JhosepAC        | C                 | C                    | C              | C                      | L                       |
| Sulca Silva, Melisa Geraldine       | MSS02204        | C                 | C                    | C              | C                      | C                       |


#### 5.2.4.3. Sprint Backlog 4

Durante el Sprint 4, el objetivo principal fue consolidar la integración entre el frontend y el backend de la aplicación Livria, con un enfoque en la autenticación segura, la gestión de acceso, la sincronización eficiente de datos y mejoras en el backend. El equipo trabajó en la implementación del bounded context de IAM (Identity and Access Management), lo que permitió establecer un sistema de gestión de identidad para los usuarios, asegurando que tanto administradores como clientes pudieran interactuar con la plataforma de manera segura mediante tokens JWT.


<table class="c12">
<tr class="c5">
<td class="c3" colspan="1" rowspan="1"><p>Sprint #</p></td>
<td class="c16" colspan="7" rowspan="1"><p>Sprint 4</p></td>
</tr>
<tr class="c5">
<td class="c13" colspan="2" rowspan="1"><p>User Story</p></td>
<td class="c17" colspan="6" rowspan="1"><p>Work Item/Task</p></td>
</tr>
<tr class="c11">
<td class="c3" colspan="1" rowspan="1"><p>Id</p></td>
<td class="c8" colspan="1" rowspan="1"><p>Title</p></td>
<td class="c10" colspan="1" rowspan="1"><p>Id</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Title</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Description</p></td>
<td class="c6" colspan="1" rowspan="1"><p>Estimation (Hours)</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Assigned To</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Status (To-do / InProcess / ToReview / Done)</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>US63</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Registro de cuenta con control y seguridad.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Registro de administrador.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar el registro correcto de datos y creación de cuenta de administrador.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Validación de datos de registro.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Validar que los datos del administrador (nombre de usuario, correo, contraseña, PIN) sean correctos.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>US64</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Inicio de sesión con autenticación JWT.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Inicio de sesión del administrador con autenticación.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar el inicio de sesión que genere el token JWT al validar las credenciales.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Manejo de credenciales inválidas.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Asegurarse de que el sistema devuelva un error 401 si las credenciales son incorrectas.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>In-Process</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>US65</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Registro de usuario cliente.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Registro de cliente.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Crear el registro datos y creación de cuenta de cliente.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Validación de usuario cliente.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Validar que el nombre de usuario y contraseña del cliente no existan ya en la base de datos.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="1"><p>US66</p></td>
<td class="c8" colspan="1" rowspan="1"><p>Acceso seguro a la cuenta mediante JWT.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Acceso a la cuenta con token.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar la validación del token JWT para el acceso a recursos del cliente.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS07</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Creación del Endpoint RESTful para Registro de Administrador.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Implementación del endpoint de registro.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Crear el endpoint /register para registrar un administrador con validación de nombre de usuario, correo, contraseña y PIN.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Validación de datos durante el registro.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Validar que el nombre de usuario y el correo electrónico no existan previamente en la base de datos antes de crear el administrador.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS08</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Configuración del endpoint de inicio de sesión (POST /login).</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Implementación del endpoint de inicio de sesión.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Crear el endpoint /login para permitir que los usuarios inicien sesión con nombre de usuario y contraseña y obtengan un token JWT.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Manejo de credenciales inválidas.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Asegurarse de que el sistema devuelva un estado 401 y un mensaje de error si las credenciales son inválidas.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="1"><p>TS09</p></td>
<td class="c8" colspan="1" rowspan="1"><p>Configuración de validación de entrada para el registro.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Validación de nombre de usuario y correo electrónico.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Validar que el nombre de usuario y el correo electrónico no existan en la base de datos al realizar el registro de un administrador.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS10</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Generación y Validación de Token JWT para Usuario Cliente.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Implementación de generación de token JWT.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar la lógica para generar un token JWT con un campo "role" como "Cliente", con una espiración de 1 hora.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Validación del token JWT para acceso a recursos.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Validar que el token JWT generado sea correcto y permita el acceso a recursos protegidos.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS11</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Autenticación de solicitudes con token JWT.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Implementación de protección con token JWT.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar la lógica para que los endpoints protegidos validen el token JWT en las solicitudes.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Respuesta de error para token inválido.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Asegurarse de que la API devuelva un estado 401 y un mensaje claro cuando el token JWT sea inválido o haya expirado.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS12</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Asignación de roles en el registro de clientes y administradores.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Asignación de rol "Admin" al registrar un administrador.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar la lógica de asignación de rol al crear un nuevo administrador en la base de datos, asegurando que el rol "Admin" sea asignado correctamente y guardado en el campo de rol del registro.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Asignación de rol "Cliente" al registrar un cliente.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar la lógica de asignación de rol al crear un nuevo usuario en la base de datos, asegurando que el rol "Cliente" sea asignado correctamente y guardado en el campo de rol del registro.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS13</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Middleware de control de acceso basado en roles JWT.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Middleware de control de acceso basado en el rol "Admin".</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Desarrollar un middleware que valide el token JWT y asegure que solo los usuarios con el rol "Admin" puedan acceder a ciertos endpoints protegidos. El middleware debe comprobar el campo role del JWT y, si el valor no es "Admin", devolver un error.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Middleware de control de acceso basado en el rol "Cliente".</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Desarrollar un middleware que valide el token JWT y asegure que solo los usuarios con el rol "Cliente" puedan acceder a ciertos endpoints protegidos. El middleware debe comprobar el campo role del JWT y, si el valor no es "Cliente", devolver error.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS14</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Integrar el backend con el frontend para la autenticación de usuarios.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Flujo de autenticación.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar el flujo de autenticación en el frontend, enviando credenciales y recibiendo el token JWT desde el backend.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Almacenamiento y manejo del token JWT.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Almacenar el token JWT recibido en el frontend y utilizarlo en solicitudes futuras.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>In-Process</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS15</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Manejar errores de autenticación en el frontend.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Manejo de error de credenciales inválidas en el frontend.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Mostrar un mensaje claro en el frontend cuando el backend devuelva un error 401 por credenciales inválidas.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>In-Process</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Manejo de error de token expirado en el frontend.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Mostrar un mensaje de error claro en el frontend cuando el backend devuelva un error 401 debido a un token expirado.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>4</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>In-Process</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS16</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Asegurar la correcta sincronización de datos entre el frontend y el backend.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Sincronización de datos entre frontend y backend.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Asegurar que el frontend reciba los datos correctos del backend y que cualquier actualización se refleje inmediatamente.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Validación de datos sincronizados.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Verificar que los datos enviados desde el frontend sean correctamente procesados y actualizados en el backend.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="2"><p>TS17</p></td>
<td class="c8" colspan="1" rowspan="2"><p>Garantizar que la navegación entre el frontend y el backend sea segura.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Implementación de HTTPS para comunicaciones seguras.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Configurar el backend para el uso de HTTPS para todas las comunicaciones entre el frontend y el backend.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Protección de datos con JWT.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Asegurar que todas las solicitudes con datos sensibles sean protegidas mediante un token JWT válido, transmitido de forma segura.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>6</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Done</p></td>
</tr>
<tr class="c5">
<td class="c3" colspan="1" rowspan="3"><p>TS18</p></td>
<td class="c8" colspan="1" rowspan="3"><p>Optimizar la comunicación entre el frontend y el backend para la carga de datos.</p></td>
<td class="c10" colspan="1" rowspan="1"><p>1</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Optimización de las solicitudes para la carga de datos.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Reducir la latencia de las solicitudes entre el frontend y el backend para una carga más rápida de los datos.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>In-Process</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>2</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Implementación de carga diferida para datos.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Implementar una técnica de carga diferida (lazy loading) para mejorar la experiencia del usuario y optimizar el rendimiento.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>To-Do</p></td>
</tr>
<tr class="c5">
<td class="c10" colspan="1" rowspan="1"><p>3</p></td>
<td class="c9" colspan="1" rowspan="1"><p>Monitorización de la comunicación.</p></td>
<td class="c7" colspan="1" rowspan="1"><p>Establecer un sistema para monitorear y optimizar la eficiencia de la comunicación entre el frontend y el backend.</p></td>
<td class="c6" colspan="1" rowspan="1"><p>5</p></td>
<td class="c4" colspan="1" rowspan="1"><p>Developer Team</p></td>
<td class="c4" colspan="1" rowspan="1"><p>To-Do</p></td>
</tr></table>


#### 5.2.4.4. Development Evidence for Sprint Review

En este capítulo se detalla el progreso logrado durante el Sprint 4 en las mejoras y la sección añadida del bounded context IAM al backend de la plataforma Livria y la integración del frontend con el backend de la aplicación web. Con el trabajo colaborativo del equipo y siguiendo un enfoque ágil, se logró implementar un sistema robusto de gestión de identidad y acceso (IAM), que permite la autenticación y autorización seguras de los usuarios, diferenciando entre administradores y clientes a través de tokens JWT.
Se completó con éxito la integración del frontend con el backend, lo que asegura que la información se gestione correctamente y se refleje de manera dinámica en la interfaz de usuario. Este avance ha optimizado la experiencia del usuario, permitiendo un registro e inicio de sesión seguro, además de garantizar la correcta sincronización entre los datos almacenados en la base de datos y las vistas en el frontend.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| https://github.com/Bookify-Livria/livria-backend.git | develop | 74b389c | feat: "Replace 'display' with 'username' in ReviewCommandService.cs" | ----------- | 05/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 1fdb637 | feat: update Controller authorization | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 0cc01e2f | Update UserClientsController.cs | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 4a02384 | feat: add IAM bounded context, authorization configuration, role management and authentication endpoints | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | d0bb3db | feat: ADD CAPITAL IN LIVRIA | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 8722c44 | Merge branch 'develop' of https://github.com/Bookify-Livria/livria-backend into develop | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 2483d9f | feat: Add "fiction" | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 0e76d75 | feat: Update Program.cs | ----------- | 01/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | aae6a7e | feat: update deployment configuration | ----------- | 01/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | c48dc26 | feat: update appsettings and add CORS Policy | ----------- | 01/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 450e3da | Merge branch 'develop' of https://github.com/Bookify-Livria/livria-backend into develop | ----------- | 01/07/2025 |
| https://github.com/Bookify-Livria/livria-backend.git | develop | 8dee7bd | feat: update LIVRIA | ------------- | 01/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/user-components | 5c84579 | feat: User Authentications using JWT | ----------- | 04/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/user-components | 0f6dd27 | Pull latest changes into the Users branch | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/user-components | 2cd0996 | feat: modifying the assembler and api service for Reviews | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/user-components | d16261d | feat: Change in community.type and proper connection to the backend database | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/user-components | 0f3cf4e | feat: modifying the assembler and api service for Posts | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/user-components | 5dd12e9 | Merge branch 'develop' into feature/communities | ----------- | 30/06/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/communities | 5dd12e9 | Merge branch 'develop' into feature/communities | ----------- | 30/06/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/communities | 0f3cf4e | feat: modifying the assembler and api service for Posts | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/communities | d16261d | feat: Change in community.type and proper connection to the backend database | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/books | 5dd12e9 | Merge branch 'develop' into feature/communities | ----------- | 30/06/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/books | 0f3cf4e | feat: modifying the assembler and api service for Posts | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/books | d16261d | feat: Change in community.type and proper connection to the backend database | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/books | 2cd0996 | feat: modifying the assembler and api service for Reviews | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 5dd12e9 | Merge branch 'develop' into feature/communities | ----------- | 30/06/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 0f3cf4e | feat: modifying the assembler and api service for Posts | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | d16261d | feat: Change in community.type and proper connection to the backend database | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 2cd0996 | feat: modifying the assembler and api service for Reviews | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 0f6dd27 | Pull latest changes into the Users branch | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 5c84579 | feat: User Authentications using JWT | ----------- | 04/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | d5d290b | feat: User Conection to database | ----------- | 04/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 9e46c43 | feat: GET and POST methods for Review and Post | ----------- | 05/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | feature/additionals | 76e5418 | feat: Books conection to database and fix of books display by genre | ----------- | 05/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 5dd12e9 | Merge branch 'develop' into feature/communities | ----------- | 30/06/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 0f3cf4e | feat: modifying the assembler and api service for Posts | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | d16261d | feat: Change in community.type and proper connection to the backend database | ----------- | 02/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 2cd0996 | feat: modifying the assembler and api service for Reviews | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 0f6dd27 | Pull latest changes into the Users branch | ----------- | 03/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 5c84579 | feat: User Authentications using JWT | ----------- | 04/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | d5d290b | feat: User Conection to database | ----------- | 04/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 9e46c43 | feat: GET and POST methods for Review and Post | ----------- | 05/07/2025 |
| https://github.com/Bookify-Livria/livria-web-app.git | develop | 76e5418 | feat: Books conection to database and fix of books display by genre | ----------- | 05/07/2025 |
| https://github.com/Bookify-Livria/livria.github.io  | master |  |  | ----------- | 06/07/2025 |


#### 5.2.4.5. Execution Evidence for Sprint Review

Durante el Sprint 4, el equipo se enfocó en la integración y desarrollo del bounded context de IAM (Identity and Access Management) dentro del backend de Livria y mejoras a algunas funcionalidades. Este nuevo módulo permitió robustecer la gestión de autenticación y autorización de usuarios, diferenciando claramente los flujos de acceso para administradores y clientes.

Se implementaron controladores REST específicos para el manejo de registro y autenticación. Además, se desarrollaron los correspondientes command y servicios para procesar las solicitudes de autenticación y generación de tokens JWT, asegurando así la protección y gestión segura de las sesiones de usuario.

El equipo también avanzó en la definición de modelos de dominio, comandos y repositorios relacionados con la identidad, permitiendo una arquitectura más modular y escalable. Se realizaron pruebas de integración para validar los nuevos endpoints y se documentaron las rutas y respuestas esperadas, facilitando la colaboración entre los distintos equipos de desarrollo.

En cuanto a la integración del frontend con el backend, se trabajó estrechamente para asegurar que el sistema funcionara de manera fluida en ambos lados. El equipo de frontend implementó los flujos de inicio de sesión, gestión de sesiones y control de acceso a información de la aplicación, conectándose correctamente con los endpoints del backend para obtener y validar los datos. 


#### Avances realizados:

**IAM:**
* **Identity:** Implementación de funcionalidades para la gestión de la autenticación y autorización de usuarios, con la capacidad de registrar nuevos usuarios en la plataforma (**POST**), iniciar sesión como administrador (**POST**) e iniciar sesión como cliente (**POST**).

#### Contribuciones del equipo:

Se realizaron mejoras en el backend y se desarrollaron funcionalidades relacionadas con el bounded context de IAM en el backend, consolidando un sistema robusto para la autenticación y autorización de usuarios. Además, se integró correctamente el frontend con el backend de la aplicación. Se trabajó en la implementación de la autenticación con JWT, utilizando tokens JWT para validar el acceso de administradores y clientes a los recursos protegidos. Los usuarios pueden ahora iniciar sesión, obtener tokens seguros y acceder a su información personal de manera segura. También, se realizaron pruebas de integración para garantizar que el frontend y el backend estuvieran correctamente sincronizados.

#### Evidencia visual:

A continuación, se presentan capturas de pantalla de las vistas implementadas en este Sprint:


**Backend de los bounded context de Livria:**

<p align="center">
  <img src="https://i.imgur.com/tCAKjri.png" alt="bruh5" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/B0YOSYP.png" alt="bruh6" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/bVHFROV.png" alt="bruh7" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/jVgViCQ.png" alt="bruh7" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/mq8RHkZ.png" alt="bruh8" width="500">
</p>



**Video Sprint Review 4**




#### 5.2.4.6. Services Documentation Evidence for Sprint Review

Durante el Sprint 4, el enfoque se centró en la implementación y fortalecimiento del bounded context de IAM (Identity and Access Management) dentro del backend de la aplicación web de Livria. Este nuevo módulo permitió la integración de un sistema de autenticación y autorización para los usuarios, diferenciando claramente los flujos de acceso entre administradores y clientes. Además, se consolidó el sistema de gestión de roles y la protección de las rutas mediante el uso de tokens JWT.
A diferencia del Sprint 3, en el cual se implementaron funcionalidades en distintos bounded contexts con una API RESTful conectada a una base de datos real (MySQL), el Sprint 4 incorporó de manera eficaz la lógica de gestión de identidad dentro de la aplicación, asegurando que las sesiones de los usuarios sean protegidas adecuadamente.


| Endpoint | Acción | Verbo HTTP | Sintaxis de llamada | Parámetros | Ejemplo de Request | Ejemplo de Response | Explicación |
|---|---|---|---|---|---|---|---|
| `/api/v1/authentication/register` | Crear un registro de un usuario. | `POST` | `POST /api/v1/authentication/register` | Ninguno | `{"username": "rodrigo", "password": "contrasea", "confirmPassword": "contrasea", "display": "Rodrigo", "email": "rodrigo.bolomo@example.com", "icon": "https://example.com/icon.png", "phrase": "¡la vida!"}` | `{"message": "Registration successful."}` | Esta solicitud POST crea un nuevo registro de un usuario de la plataforma. Permite registrar un usuario proporcionando información como el username, password, confirmPassword, display, email, icon y phrase. |
| `/api/v1/authentication/sign-in/admin` | Iniciar sesión como administrador. | `POST` | `POST /api/v1/authentication/sign-in/admin` | Ninguno | `{"username": "admin_default", "password": "0000", "securityPin": "0000"}` | `{"identityId": 1, "userId": 1, "username": "admin_default", "success": true, "message": "Login successful.", "token": "eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE3NTIzNTkzOTksImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL3NpZCI6IjEiLCJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy93cy8yMDA1LzA1L2lkZW50aXR5L2NsYWltcy9uYW1lIjoiYWRtaW5fZGVmYXVsdCIsImh0dHA6Ly9zY2hlbWFzLm1pY3Jvc29mdC5jb20vd3MvMjAwOC8wNi9pZGVudGl0eS9jbGFpbXMvcm9sZSI6IkFkbWluIiwiaWF0IjoxNzUxNzU0NTk5LCJuYmYiOjE3NTE3NTQ1OTl9.mGcSdBaMrrP7-DEZTf8gjy5I82pm7Ts9bSfHYKVgypo"}` | Esta solicitud POST permite iniciar sesión como administrador en la plataforma. El administrador ingresa con su username, password y securityPin. |
| `/api/v1/authentication/sign-in/client` | Iniciar sesion como cliente. | `POST` | `POST /api/v1/authentication/sign-in/client` | Ninguno | `{"username": "rodrigo", "password": "contrasea"}` | `{"identityId": 7, "userId": 7, "username": "rodrigo", "success": true, "message": "Login successful.", "token": "eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE3NTIzNTk0ODQsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL3NpZCI6IjciLCJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy93cy8yMDA1LzA1L2lkZW50aXR5L2NsYWltcy9uYW1lIjoicm9kcmlnbyIsImh0dHA6Ly9zY2hlbWFzLm1pY3Jvc29mdC5jb20vd3MvMjAwOC8wNi9pZGVudGl0eS9jbGFpbXMvcm9sZSI6IlVzZXJDbGllbnQiLCJpYXQiOjE3NTE3NTQ2ODQsIm5iZiI6MTc1MTc1NDY4NH0.0VhD4A-bCEMh-X0ItAKe1utt5HKBO-j5jbnQn2MVk4E"}` | Esta solicitud POST permite iniciar sesión como cliente en la plataforma. El cliente ingresa con su username y password. |

**Capturas:**

<p align="center">
  <img src="https://i.imgur.com/fXx6jLF.png" alt="full38" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/50D901M.png" alt="full38" width="500">
</p>

Esta solicitud POST recupera los datos de un usuario recién registrado en el sistema, guarda su información y envía un mensaje confirmando el registro exitoso.

<p align="center">
  <img src="https://i.imgur.com/2bkcPmm.png" alt="full38" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/N1uaeZX.png" alt="full38" width="500">
</p>

Esta solicitud POST auténtica al administrador con las credenciales proporcionadas, valida el inicio de sesión y devuelve un token de acceso junto con un mensaje de autenticación exitosa.

<p align="center">
  <img src="https://i.imgur.com/mupEhMS.png" alt="full38" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/n5lIlyq.png" alt="full38" width="500">
</p>

Esta solicitud POST auténtica al cliente con las credenciales proporcionadas, valida el inicio de sesión y devuelve un token de acceso junto con un mensaje de autenticación exitosa.

#### 5.2.4.7. Software Deployment Evidence for Sprint Review

Durante este Sprint 4, el equipo se centró en el despliegue del frontend conectado al backend de la aplicación web de Livria. Este sprint incluyó la integración completa de ambos componentes, asegurando que el frontend pudiera interactuar correctamente con el backend, permitiendo que las funcionalidades de la plataforma funcionen de manera fluida.
Se implementó la autenticación de usuarios, incluyendo el registro e inicio de sesión seguro con JWT, tanto para administradores como para clientes. El sistema ahora maneja las solicitudes de inicio de sesión de manera efectiva, generando los tokens correspondientes para asegurar las sesiones de los usuarios.

#### Actividades de Despliegue:



#### 5.2.4.8. Team Collaboration Insights during Sprint

Durante este Sprint 4, el equipo se centró en la integración completa del frontend con el backend de la aplicación web de Livria, asegurando que la plataforma funcione de manera fluida y sincronizada. Utilizando .NET para el backend y una base de datos MySQL, se mejoró el backend, se implementó el registro e inicio de sesión de usuarios clientes y administradores, ahora asegurados mediante el uso de tokens JWT.

#### Actividades de implementación:

* **Estructura del Backend:** Se implementó los endpoints requeridos para gestionar la entidad Identity añadida en este sprint. Las APIs se desarrollaron en .NET y se conectaron a la base de datos MySQL.
* **Operaciones CRUD:** La funcionalidad básica de Create fue implementada para la entidad Identity, asegurando que el sistema maneje de manera correcta los datos del registro de usuario y el inicio de sesión del cliente y del administrador. 
* **Integración del frontend con el backend:** Con la integración de ambos, se aseguró que las interacciones del usuario se actualizarán en tiempo real a través de los datos almacenados en la base de datos. Esto permite que la plataforma proporcione una experiencia dinámica, fluida, segura y sin errores de datos de los usuarios.
* **Desarrollo del bounded context de Gestión de identidad y acceso (IAM):** Se añadió un sistema de gestión de identidad que controla los flujos de acceso, roles y permisos dentro de la plataforma Livria, usando JWT para asegurar que los usuarios puedan acceder solamente a los recursos adecuados según su rol, administrador o cliente.
* **Implementación del token JWT:** Se agregó el token Json Web token para la autenticación y autorización de los usuarios, ya que este asegura que la sesión de los usuarios funcione correctamente y permite que el acceso a los recursos de la plataforma sea controlado.
* **Mejoras en el backend:** Se mejoró las funcionalidades de las tipos de comunidades (communities), en ocultar las notificaciones (notifications),  en el stock de los libros (books), en el estado de la orden (order) y en la suscripción del cliente en la plataforma (userClients).


#### Analítica de colaboración en GitHub:

##### Repositorio livria-web-app

* Historial de commits:

  <p align="center">
  <img src="https://i.imgur.com/KRXSgIs.png" alt="confi24" width="500">
  </p>

* Colaboradores activos en el repositorio:

  <p align="center">
  <img src="https://i.imgur.com/Wre4F3p.png" alt="confi24" width="500">
  </p>

* Histograma de contribuciones en el tiempo:

  <p align="center">
  <img src="https://i.imgur.com/xx97V4q.png" alt="confi24" width="500">
  </p>

##### Repositorio livria-backend
* Historial de commits:

  <p align="center">
  <img src="https://i.imgur.com/aWoK6YM.png" alt="confi24" width="500">
  </p>

* Colaboradores activos en el repositorio:

  <p align="center">
  <img src="https://imgur.com/FYXgufk.png" alt="confi19" width="500">
  </p>
  
* Histograma de contribuciones en el tiempo:

  <p align="center">
  <img src="https://i.imgur.com/FY5G4mQ.png" alt="confi24" width="500">
  </p>
  
  
## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

**User flows utilizados:**

* **Segmento 1: Estudiantes y jóvenes universitarios**
    * Como usuario, quiero poder realizar la búsqueda de libros en base a diferentes criterios y obtener resultados relacionados.
    * Como usuario, quiero poder navegar rápidamente entre categorías y géneros de libros.

* **Segmento 2: Lectores casuales y aficionados a la lectura**
    * Como usuario, quiero poder expresarme mediante mi perfil y tener la capacidad de editarlo en cualquier momento.
    * Como usuario, quiero poder realizar compras desde la plataforma de manera segura y bien explicada.

**Preguntas:**

##### Segmento Objetivo #1: Estudiantes y jóvenes universitarios

**Perfil del entrevistado:**
* ¿Cuál es tu nombre y a qué te dedicas actualmente?
* ¿Qué herramientas o aplicaciones usas actualmente para estudiar o leer libros digitales académicos?

**Tras mostrar la Landing Page:**
* ¿Qué entendiste que ofrece Livria?
* ¿Crees que esta plataforma está pensada para alguien como tú, que estudia?
* ¿Qué mejorarías en la página para hacerla más atractiva o útil para estudiantes como tú?

**Tras la demostración de la aplicación web:**
* ¿Qué impresión general te dio la plataforma Livria?
* ¿Te parece útil para tu gestión diaria de lecturas académicas?
* ¿Fue fácil de usar y entender cómo funciona la plataforma?
* ¿Te gustaría que la aplicación tuviera alguna funcionalidad adicional para tus estudios, para facilitar la organización de tus lecturas o tareas?

**Cierre:**
* ¿Qué es lo que más te gustó de Livria?
* ¿Usarías esta herramienta regularmente para tus estudios? ¿Por qué?

##### Segmento Objetivo #2: Lectores casuales y aficionados a la lectura

**Perfil del entrevistado:**
* ¿Cuál es tu nombre y qué tipo de lectura disfrutas?
* ¿Qué plataformas o aplicaciones usas para leer libros digitales o descubrir nuevos títulos?

**Tras mostrar la Landing Page:**
* ¿Qué entendiste que ofrece Livria?
* ¿Crees que esta aplicación sería adecuada para alguien como tú, que disfruta leer libros por placer?
* ¿Qué mejorarías en la página para que te resulte más atractiva y útil como lector casual?

**Tras la demostración de la aplicación web:**
* ¿Qué impresión general te dio la plataforma Livria?
* ¿Te parece que la plataforma es adecuada para la lectura de libros de entretenimiento y ficción?
* ¿Fue fácil navegar y encontrar libros que te interesaran en la aplicación?
* ¿Cómo calificarías la experiencia de recibir recomendaciones personalizadas según tus gustos literarios?
* ¿Te gustaría que la aplicación incluya más funciones sociales, como comentarios o foros de discusión sobre libros?

**Cierre:**
* ¿Qué es lo que más te gustó de la plataforma?
* ¿Volverías a usar Livria para encontrar nuevos libros? ¿Por qué?

### 5.3.2. Registro de Entrevistas

#### Segmento objetivo #1: Estudiantes y jóvenes universitarios

##### Entrevistado #1: Joaquin Cuentas
* Edad: 22
* Distrito: San Miguel

  <p align="center">
  <img src="https://imgur.com/UYoVtxe.png" alt="ent1" width="500">
  </p>

Link: [Validación de entrevista Segmento #1 Joaquin Cuentas.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/ER_Rc3KXonBIjFT_HoFH4YMBuL8ZB7b84LXsGFZ2-oq9cQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=2gcRXT)

Joaquin Cuentas, quien es un estudiante universitario, nos comenta que suele leer libros académicos digitalmente a través de google académico o PDF de revistas académicas. Él entiende que Livria  no solo se dedica a la venta de libros digitales y físicos, sino que también ofrece una plataforma única para que los usuarios compartan sus intereses de manera efectiva. Sin embargo, considera que sería útil ampliar las categorías de textos académicos disponibles y que mejoremos el color de la barra de búsqueda para mayor visibilidad, ya que considera que no se aprecia de la mejor manera. Lo que realmente le impresionó de Livria fue la sección de comunidades, ya que no solo se trata de un espacio para comprar libros, sino también para que los usuarios interactúen y compartan intereses en diversas disciplinas académicas. 
Joaquín también considera que la organización de las opciones en la plataforma es intuitiva y llamativa, lo que le resulta muy útil para su gestión diaria. Si él pudiera añadir una funcionalidad, sugeriría incorporar una sección de edición de PDFs en la que los usuarios pudieran resaltar puntos importantes, agregar resúmenes y realizar anotaciones en los textos.  Además, le gustaría que las comunidades se organizaran por carreras universitarias, permitiendo a los estudiantes conectarse con otros de su misma área de estudio. 
En resumen, Joaquín destaca especialmente la sección de comunidades, ya que le permite conocer a personas con intereses y pasiones similares, lo que añade un valor único a la plataforma.

##### Entrevistado #2: Ernesto Rodas
* Edad: 19
* Distrito: San Isidro

  <p align="center">
  <img src="https://imgur.com/EzIUtja.png" alt="ent2" width="500">
  </p>

Link: [Validación de entrevista Segmento #1 Ernesto Rodas.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/Ec3OJQvjWFdAvfsNkzKUid0BAFYJ-GqIM1RQzoR0WuthPQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=b1rtGM)

Ernesto Rodas, un estudiante universitario, menciona que no posee el hábito de leer mucho libros académicos en aplicaciones o apps webs, sino que usa más los repositorios de las universidades para realizar tareas de su carrera. Él entiende que Livria ofrece un acceso abierto a cualquier tipo de público, permitiéndole leer lo que desee, ya que la plataforma cuenta con diversas categorías, lo que considera innovador. 
Destaca que la landing page si es concisa y precisa, explicando claramente lo que la plataforma ofrece de manera efectiva. Sobre la interfaz, la describe como simple y accesible, pensada para todo tipo de público. Asimismo, él afirma que sí lo usaría para estudiar, ya que la considera práctica. Además, sugiere que la sección académica  podría mejorarse y que sería beneficioso tener más libros digitales en esa categoría. A Ernesto, le sorprendió la calidad de la plataforma, destaca que está bien hecha la interfaz del proceso de pago, dice que es muy realista. Lo que valora positivamente son las funcionalidades de las comunidades, los comentarios, los comentarios que se encuentran en cada libro y el botón de cambio de idioma. 
Para su gestión de lecturas académicas, Ernesto considera que los filtros y la barra de búsqueda son herramientas muy útiles, ya que le ahorran tiempo al facilitar la búsqueda de contenido. En general, describe la plataforma como interactiva y didáctica, destacando que todo está al alcance de la mano, desde la búsqueda de libros hasta el proceso de pago y las comunidades. Él nos sugiere agregar secciones relacionadas con programación e inteligencia artificial dentro de las categorías disponibles. En resumen, lo que más le gustó de Livria fue que toda la información está fácilmente accesible, y la landing page explica muy bien las funciones que ofrece la plataforma. Él usaría la aplicación porque le permite ahorrar tiempo, haciendo que la búsqueda de lo que necesita sea más rápida y sencilla.

##### Entrevistado #3: Wendy García 
* Edad: 25
* Distrito: Lince

  <p align="center">
  <img src="https://imgur.com/wZXkz90.png" alt="ent3" width="500">
  </p>

Link: [Validación de entrevista Segmento #1 Wendy Garcia.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/EdzYjY04ldtKqWTMmU9mRNwBIKyDejfwcKrxyL97GZhJIw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=FGxVb2)

Wendy Garcia, quien es una estudiante universitaria, nos comenta que suele leer ebooks y en Google Académico. Ella entiende que Livria posee diversas categorías de libros, incluyendo formatos digitales, físicos y audiolibros. Wendy, considera que esta plataforma está diseñada para personas como ella, ya que es dinámica y práctica. Sin embargo, menciona que mejoraría las sinopsis de los libros, ya que las actuales son demasiado breves. Ella sugiere que estas sinopsis deberían ser más detalladas y que se incluyan etiquetas en los libros para facilitar la identificación de su contenido y público objetivo. La impresión general que le dejó la plataforma es positiva, destacando su dinamismo y el buen uso de la paleta de colores. Lo que más le impresionó fue la posibilidad de cambiar el idioma de la plataforma con tan solo un click, lo que consideró una función muy conveniente. 
Asimismo, ella nos menciona que le parece una herramienta útil para su gestión diaria de lecturas académicas, especialmente porque la sección de comunidades le permite compartir intereses con otros usuarios, intercambiar opiniones sobre libros académicos, resúmenes y perspectivas personales. Le gustaría que la plataforma ofreciera resúmenes de libros como funcionalidad adicional para poder decidir si desea leerlos o no. También, destaca que la interacción con la plataforma es fácil y fluida, y le encanta la sección de comunidades, pues la considera un espacio donde se pueden compartir ideas y experiencias. Además, valora la disposición de las categorías en la barra superior, lo que hace que navegar por la plataforma sea más dinámico y práctico. En la sección de cuenta, le agrada poder consultar las órdenes que ha realizado. 
En resumen, si usaría la aplicación, debido a que le encanta lo dinámica que es. Además, le encantó la sección de la comunidad y la opción disponible de audiolibros.

#### Segmento objetivo #2: Lectores casuales y aficionados a la lectura

##### Entrevistado #1: Andree Cardenas 
* Edad: 24
* Distrito: San Miguel 

  <p align="center">
  <img src="https://imgur.com/xTdyQ6W.png" alt="ent4" width="500">
  </p>
  
Link: [Validación de entrevista Segmento #2 Andree Cardenas.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/EdTSIQLzmMNNhHPaz4jZ7YsBJLpqkVhFw74deOAjV6-q8w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=QtMn9K)

Andree Cardenas nos señala que disfruta principalmente lecturas de ciencia ficción, así como también un poco de romance, suspenso y drama. Él suele usar cualquier página web para mangas, pero más Webtoon. Andree entiende que Livria ofrece un catálogo de libros, adecuado para un público diverso. Él considera que la plataforma es cómoda y atractiva, destaca su diseño. Le resulta tan cautivador que le motivaría a comprar libros en la plataforma.  Una sugerencia que señala es que, en el proceso de comprar un libro,  encuentres reseñas con fotos de otros usuarios sobre su experiencia de compra, así como la posibilidad de valorar tanto el libro como el servicio de envío. 
La impresión general que le dio la plataforma fue muy positiva, la detalla como simple, llamativa y acogedora. Asimismo, considera que Livria si es ideal para leer, ya que es intuitiva y bien organizada, con las categorías bien dispuestas. Destaca que la comunidad es muy buena, ya que puedes entablar conversaciones con otros usuarios sobre temas en común. Además, destaca la posibilidad de crear nuevas comunidades dentro de Livria.  Le encanta la opción de recomendaciones personalizadas y considera que eso gratifica la experiencia en el uso de la plataforma. 
En resumen, Andree se siente muy satisfecho con el diseño y el orden de la plataforma.  Menciona que esta ofrece que contiene un diseño cómodo y señala que si utilizaría Livria, debido a que lo considera fascinante y menciona que brinda una experiencia cómoda y amigable para el usuario.

##### Entrevistado #2: Fiorella Gomez 
* Edad: 24
* Distrito: Magdalena del mar

  <p align="center">
  <img src="https://imgur.com/NNDHH3c.png" alt="ent5" width="500">
  </p>
  
Link: [Validación de entrevista Segmento #2 Fiorella Gomez Leon.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/ER7z6G8S8P9HpQtAhg4Lk68BxlS9N59iyoOLx_qcYtHQ1Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=tOdjrF)

Fiorella Gomez, una aficionada a la lectura, nos comenta que disfruta de la lectura que contiene el drama y romance, aunque también suele leer comedia. Menciona que las plataformas que utiliza para leer de manera digital son Wattpad y AO3.  Ella entiende que Livria ofrece una amplia variedad de libros en distintas categorías,  lo que la hace atractiva para todo tipo de público. Además, considera que la plataforma sería útil para ella, principalmente por la diversidad de contenido y la sección de comunidad. Sin embargo,  sugiere mejorar la visibilidad de la opción de cerrar la sesión, debido a que es necesario entrar a la sección de cuenta del usuario para poder cerrarla. También, propone que la sección de notificaciones esté en un lugar diferente, ya que la encuentra algo confusa al estar al lado de otras opciones. 
En general, Livria le causó una buena impresión, ya que es fácil de usar y el registro es sencillo, y, también, agrega que le agradan los comentarios en cada libro, debido a que estos le ayudan a decidir si desea leer un título o no. Fiorella menciona que  fue fácil encontrar los libros que le gustan, debido a que están bien organizados por categorías. Además, valora la opción de recibir recomendaciones personalizadas, ya que le permite descubrir libros que podrían interesarle. A su vez, sugiere que los usuarios puedan agregar fotos de cómo les llegó su pedido, para que otros puedan conocer la calidad del envío. Asimismo, le gustaría que en cada párrafo de la lectura, se pueda comentar para que haya más interacción entre los usuarios. 
Lo que más le gustó a Fiorella fue la facilidad del registro (sencillo y rápido). En resumen, utilizará Livria debido a la variedad de categorías de libros disponibles.

##### Entrevistado #3: Manuel Tumi
* Edad: 26
* Distrito: Surco

  <p align="center">
  <img src="https://imgur.com/1fYMPez.png" alt="ent6" width="500">
  </p>
  
Link: [Validación de Entrevista Segmento #2 Manuel Tumi.mp4](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202224602_upc_edu_pe/EfcRiMRM-1xBtOkM4J2jfUgBpPHh5Uf7ilWbNDo6x1pX8w?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=HgXkO8)

Manuel Tumi, un aficionado a la lectura, nos señala que lo más lee son mangas y manhwas, aunque en el pasado solía leer más ficción, pero lo ha dejado de lado. Suele buscar cualquier página web de mangas o manhwas y se queda con la que ofrezca la mejor traducción del manga o manhwa o poseea menos anuncios. Manuel entendió que Livria está más enfocada en la compra de libros, pero cree que es adecuada para leer allí, debido a que las comunidades pueden guiarte a descubrir nuevos libros para leer. Una de las sugerencias de Manuel es mejorar la interfaz de la plataforma, señalando que algunas secciones, como la de detalles del libro, se ven un poco vacías. Propone que  la sinopsis de los libros se ubique en el lado derecho para equilibrar visualmente la página. A pesar de esto, le sorprendió la calidad de la plataforma, destacando la sección de las comunidades, que él considera una idea innovadora. Para él, es una excelente oportunidad para compartir gustos con otros usuarios y explorar nuevas categorías de libros. 
Manuel considera que el enfoque de la plataforma es que te interese la lectura más que solo que compres sus productos. Añade que la sección de ebooks y audiolibros es algo interesante, y sugiere que sería genial incluir una opción para leer los libros en formato PDF o en un modo que simule las páginas de un libro físico (ambas caras). También, le gustaría que haya una funcionalidad como bookmarks, que le permita señalar la página donde se quedó, de modo que la plataforma lo lleve directamente allí la próxima vez que ingrese.   Asimismo, dice que fue intuitivo la plataforma y y que la barra de búsqueda y el filtro le ayudan a encontrar fácilmente los libros que le interesan. Sin embargo, sugiere cambiar el color de la barra de búsqueda, ya que actualmente no se aprecia claramente. También valora mucho las recomendaciones personalizadas, ya que le ayudan a decidir qué libro leer, ya que suele demorarse en escoger uno. Señala que aprecia los comentarios de otros usuarios, ya que le sirven para tomar una decisión informada sobre qué libros leer. Manuel también sugeriría la creación de un foro global para interactuar con usuarios activos en ese momento, lo que enriquecería la experiencia de la comunidad. 
En resumen, lo que más le gustó a Manuel fue la sección de comunidades, ya que no solo permite comentar, sino que también genera una sensación de conexión con personas que comparten sus mismos gustos y opiniones. Finalmente, señala que utilizaría Livria debido a su simplicidad y facilidad de uso, lo que hace que la plataforma sea muy amigable para el usuario.

### 5.3.3. Evaluaciones según heurísticas

#### UX Heuristics & Principles Evaluation

**CARRERA**: Ingeniería de Software
**CURSO**: Aplicaciones Web
**SECCIÓN**: 4388
**PROFESORES**: Alex Humberto Sánchez Ponce
**AUDITOR**: LIVRIA
**CLIENTE(S)**:
* Joaquin Cuentas
* Ernesto Rodas
* Wendy Garcia
* Andree Cardenas
* Fiorella Gomez
* Manuel Tumi

**SITE O APP A EVALUAR**: Livria

**TAREAS A EVALUAR**:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
* Búsqueda de libros
* Uso de filtros en el catálogo de libros
* Procesos de pago
* Gestión de cuentas de usuario
* Navegación entre las categorías de libros
* Opciones de personalización del perfil de usuario
* Sección de tienda de Livria
* Sección de recomendaciones personalizadas
* Sección de comunidades
* Notificaciones
* Dashboard del administrador
* Sección del detalle de libro específico

No están incluidas en esta versión de la evaluación las siguientes tareas:
* Agregar a favoritos un libro en específico
* Algoritmo de recomendaciones en base a libros favoritos
* Mejora de diseño en la sección de dashboard del administrador
* Mejora en la estadística del dashboard del administrador

**ESCALA DE SEVERIDAD**:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

| Nivel | Descripción                                                                                                                                      |
| :---- | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| 1     | **Problema superficial**: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2     | **Problema menor**: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| 3     | **Problema mayor**: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| 4     | **Problema muy grave**: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

#### TABLA RESUMEN:

| # | Problema                                                                                        | Escala de severidad | Heurística/Principio violada(o)       |
| :- | :---------------------------------------------------------------------------------------------- | :------------------ | :------------------------------------ |
| 1 | La sinopsis de los libros son demasiados breves, lo que no permite al usuario tener suficiente información para decidir si leer el libro. | 2                   | Proveer retroalimentación de manera adecuada. |
| 2 | La interfaz de la sección de detalles de los libros está un poco vacía causando una mala distribución visual. | 1                   | Diseño visual y minimalismo           |
| 3 | El proceso de cierre de sesión no es claro, ya que dirigirse a la cuenta del usuario para intentar cerrar sesión. | 1                   | Control y libertad del usuario        |
| 4 | La barra de búsqueda tiene un color que no es fácilmente visible, lo que podría afectar la accesibilidad. | 1                   | Diseño visual y accesibilidad         |

#### PROBLEMA #1:
* **Severidad**: 2
* **Heurística violada**: Proveer retroalimentación de manera adecuada
* **Problema**: Las sinopsis de los libros son demasiado breves y no proporcionan suficiente información al usuario sobre el contenido del libro. Esto dificulta la toma de decisiones para aquellos que no están familiarizados con el título.

**Figura**

  <p align="center">
  <img src="https://imgur.com/ggrO20o.png" alt="fig1" width="500">
  </p>

*Nota. Elaboración propia.*

**Recomendación**:
Ampliar la longitud de las sinopsis para dar más detalles sobre el libro, lo que permitiría a los usuarios tomar decisiones más informadas.

#### PROBLEMA #2:
* **Severidad**: 1
* **Heurística violada**: Diseño visual y minimalismo
* **Problema**: La interfaz de la sección de detalles de los libros está un poco vacía en el lado derecho causando que la página se vea algo desordenada y poco atractiva visualmente.

**Figura**

  <p align="center">
  <img src="https://imgur.com/5v0eyLw.png" alt="fig2" width="500">
  </p>
  
*Nota. Elaboración propia.*

**Recomendación**:
Añadir más contenido visual y texto en el lado derecho de la sección de detalles del libro. Como al costado del precio, poner la sinopsis y que en el lado izquierdo solo vaya la imagen del libro.

#### PROBLEMA #3:
* **Severidad**: 1
* **Heurística violada**: Control y libertad del usuario
* **Problema**: El proceso de cierre de sesión no es claro, ya que los usuarios deben ir a la cuenta del usuario para cerrar la sesión, lo cual no es ideal.

**Figura**

  <p align="center">
  <img src="https://imgur.com/DchnNTO.png" alt="fig3" width="500">
  </p>

  <p align="center">
  <img src="https://imgur.com/9eDQfml.png" alt="fig4" width="500">
  </p>

  
*Nota. Elaboración propia.*

**Recomendación**:
Colocar una opción más visible para cerrar sesión en el menú principal o en un lugar más intuitivo de la interfaz.

#### PROBLEMA #4:
* **Severidad**: 1
* **Heurística violada**: Diseño visual y accesibilidad
* **Problema**: El color de la barra de búsqueda no es fácilmente visible, lo que podría afectar la accesibilidad para usuarios con dificultades visuales.

**Figura**

  <p align="center">
  <img src="https://imgur.com/KJIDZQG.png" alt="fig5" width="500">
  </p>
  
*Nota. Elaboración propia.*

**Recomendación**:
Ajustar el contraste de la barra de búsqueda para que sea más accesible y visible para todos los usuarios, especialmente para aquellos con dificultades visuales.

## 5.4. Video About-the-Product

Link del video: [VideoAbout-the-Product](https://drive.google.com/file/d/1U1pLQrU2ldrs_Q6LWjTs4EhoLLXARXQD/view?usp=sharing)

# CONCLUSIONES Y RECOMENDACIONES

*TB1*

**Conclusiones**

1.	Problem Statements y Validación

El problema central identificado–la baja tasa de lectura y comprensión lectora en adolescentes y jóvenes– fue validado mediante entrevistas y estudios citados (como la Encuesta Nacional de Lectura 2022). Los usuarios confirmaron barreras como falta de acceso a libros atractivos, dificultades en la búsqueda de material y la competencia con redes sociales. 
Nuestra solución propuesta (Livria) aborda estas barreras al integrar un catálogo diversos, recomendaciones personalizadas, y especialmente, una comunidad lectora. 

2.	Assumptions vs. Realidad

Features asumidos:
Las recomendaciones personalizadas y la sección de comunidad fueron validadas como prioritarias por los usuarios, especialmente por estudiantes y lectores casuales. 
La preferencia por múltiples formatos (físico, digital, audiolibros) se confirmó, destacando la necesidad de accesibilidad inmediata.

3.	Diseño centrado en el usuario

A través del enfoque de Lean UX, Livria prioriza en todo momento la experiencia y necesidades del usuario final. Desde la investigación inicial, que incluyó entrevistas y análisis de necesidades, hasta el diseño de la interfaz, se garantizaron soluciones que respondieron de manera precisa a las expectativas de los lectores.

**Recomendaciones:**

1.	Integración de métricas de seguimiento

Durante las fases iniciales de lanzamiento, se debe integrar un sistema de medición de métricas de uso que permita validar continuamente los indicadores de éxito planteados (lectura de un libro por mes, interacción en comunidad, diversificación de accesos multiplataforma). 

2.	Consolidación de Roadmap de Producto

En el Roadmap de Livria, se deben definir los siguientes hitos inmediatos:

1.	Fase 2: Desarrollo Backend y documentación de API RESTful con OpenAPI (Swagger).
2.	Fase 3: Integración de algoritmos de recomendación y motor de comunidad.

*TP*

**Conclusiones**

1. Avance integral en el Frontend en la experiencia de usuario.

En este avance, el equipo logró desarrollar con éxito las funcionalidades claves del frontend, incluyendo la visualización del catálogo de libros, la gestión del carrito de compra, las órdenes de compra, comunidades literarias, notificaciones y sistemas de suscripción. La integración de Vite+Vue permitió crear una interfaz intuitiva y fluida, lo que ayuda a alinear con los objetivos estratégicos y centrarse en mejorar la interacción del usuario con la plataforma.

2. Uso efectivo de herramientas y APIs Simuladas(fake API) para asegurar la calidad del desarrollo

Se utilizó una fake API basada en json-server y el archivo db.json para simular operaciones CRUD en distintas entidades creadas, durante el desarrollo del código, lo que permitió un desarrollo ágil y controlado del frontend sin tener que depender de un backend (base de datos) real. Los servicios implementados, como por ejemplo, BookApiService, facilitaron la gestión de datos y la integración con la interfaz de usuario (UI), lo que forma las bases para una transición fluida a servicios RESTful reales en los próximos sprints.

3. Planificación y Retos para futuros avances

Se realizó una planificación efectiva y una ejecución colaborativa del equipo, con la distribución de tareas claras entre los integrantes del equipo para cubrir los aspectos funcionales de la aplicación web Livria. Sin embargo, algunas funcionalidades, como la de inventario por parte de un usuario administrativo quedaron pendientes, lo que quiere decir que debemos priorizar este punto para el próximo sprint y mejorar la interfaz del usuario asegurando que todas las secciones sean responsive. 

4. Despliegue en Firebase hosting: 

El proyecto fue desplegado correctamente en Firebase Hosting, lo que hizo que el entorno de producción estuviera disponible para pruebas de usuarios reales. La implementación inicial utilizando Firebase como hosting ofrece una infraestructura confiable para el manejo de la aplicación web en producción.

5. Enfoque en la calidad  y mejora continua

El equipo mostró compromiso al asegurarse de lograr la calidad del producto al momento de implementar pruebas y revisiones constantemente durante el desarrollo del sprint 2. La utilización de metodologías ágiles facilitó la rápida identificación y corrección de errores, así como el envío de feedback interno entre los integrantes del equipo. Este enfoque asegura que la aplicación web Livria cumpla los requisitos funcionales y ofrezca una experiencia de usuario buena y confiable, lo que permite prepararnos para futuras interacciones con funcionalidades más complejas y con un backend ya integrado a la aplicación. 

**Recomendaciones:**

1. Optimización del Backend y Transición a API RESTful Real:

Aunque se ha utilizado una API simulada con JSON Server para pruebas iniciales, se recomienda migrar a una API RESTful real que se conecte a una base de datos real. Esto proporcionará un entorno más robusto y escalable, permitiendo el manejo de datos de manera más eficiente. La documentación de la API con OpenAPI (Swagger) debe ser priorizada en el siguiente sprint para garantizar que las integraciones futuras sean fluidas.

2. Escalabilidad del Catálogo de Libros:

Dado que el catálogo de libros es uno de los pilares de Livria, debemos asegurarnos de que el sistema sea capaz de escalar a medida que aumenten el número de libros, usuarios y recomendaciones. En futuras fases, se implementarán características como la carga dinámica de contenido (lazy loading) para mantener la velocidad de carga de la página en niveles óptimos, incluso a medida que el catálogo crezca.

3. Integración de la Funcionalidad de Búsqueda Avanzada:

Sabemos que el motor de búsqueda es fundamental en una plataforma con un catálogo extenso de libros. Por lo tanto, nos debemos asegurar de que la búsqueda permita a los usuarios encontrar libros no solo por nombre o autor, sino también por criterios más específicos como género, idioma y rango de precio. También debemos garantizar que la búsqueda sin coincidencias exactas sea robusta y brinde alternativas relevantes, lo cual es esencial para mejorar la experiencia del usuario y asegurar que encuentren lo que buscan.

4. Accesibilidad y Multiplataforma

Es fundamental que Livria sea accesible en una amplia variedad de dispositivos, como smartphones, tablets y desktops. Iremos mejorando la optimización para diferentes tamaños de pantalla. La accesibilidad debe ser una prioridad, por lo que deberíamos incluir funciones como la compatibilidad con lectores de pantalla y opciones de personalización del contraste y tamaño de texto. Esto garantizará una experiencia inclusiva para todos los usuarios, sin importar sus necesidades.

5. Nueva Interfaz para el Usuario Administrador

Para el siguiente entregable, desarrollaremos una interfaz de administración más intuitiva y eficiente. Esta nueva interfaz debe permitir una gestión centralizada del catálogo de libros, usuarios y transacciones. Además, será completamente responsiva y ofreceremos una experiencia de usuario fluida tanto en dispositivos móviles como de escritorio. Esto permitirá a los administradores gestionar la plataforma de forma más ágil y optimizada.

*TB2*

**Conclusiones**

1. Avances significativos en el desarrollo del backend

El equipo logró implementar las funcionalidades clave del backend de la plataforma Livria, como la gestión de productos, usuarios, carritos de compra, recomendaciones, comunidades y notificaciones, utilizando .NET y MySQL. Además, la implementación de APIs RESTful para estas entidades fue exitosa, lo que proporcionó la infraestructura necesaria para que el frontend pudiera interactuar de manera eficiente con el backend. La integración de OpenAPI y Swagger permitió una documentación clara y accesible de los endpoints, facilitando las pruebas y futuras expansiones de la plataforma.

2. Mejoras en la experiencia de usuario del frontend

A pesar de que el enfoque principal fue el backend, se realizaron correcciones y mejoras en el frontend, especialmente en la sección de administración, optimizando la experiencia de usuario y la funcionalidad de la plataforma. Se agregó un dashboard para administradores, permitiendo la gestión eficiente de libros, pedidos y estadísticas, lo que centraliza las operaciones y mejora la administración de la plataforma. Además, se modificó la sección de usuarios también.

3. Evaluación de usabilidad y áreas de mejora para Livria

Las entrevistas de validación de nuestra plataforma nos indica que los usuarios entrevistados perciben a Livria como una plataforma intuitiva y atractiva, con una buena variedad de libros y funcionalidades, destacando la sección de comunidades. Sin embargo, existen áreas clave que los entrevistados sugieren que le demos atención, como la mejora en la visualización de la sinopsis de libros, la distribución visual en la sección de detalles del libro seleccionado y la accesibilidad de la barra de búsqueda, lo que podría mejorar significativamente la experiencia del usuario.  

**Recomendaciones**

1. Optimización continua del rendimiento del backend

Si bien el rendimiento de la base de datos y las consultas SQL fueron optimizadas durante este sprint, se recomienda continuar con el monitoreo y la mejora continua de la base de datos para garantizar un rendimiento óptimo, especialmente cuando la plataforma crezca y maneje más datos. Esto incluirá la optimización de las consultas más complejas y la implementación de índices adecuados para asegurar tiempos de respuesta rápidos.

2. Ampliación de la documentación y la seguridad

Aunque la documentación de la API se realizó a través de Swagger y OpenAPI, es fundamental continuar ampliando la documentación para los endpoints más complejos, especialmente para aquellos que interactúan con funcionalidades avanzadas. Además, se debe revisar la seguridad tanto del backend como del sistema de autenticación de usuarios para garantizar que la plataforma sea resistente a vulnerabilidades y esté lista para enfrentar posibles riesgos en un entorno de producción.

3. Sugerencias para mejorar la experiencia del usuario en Livria

Se recomienda realizar modificaciones en el frontend en la próxima entrega, enfocados en mejorar la visibilidad de elementos clave como la sinopsis y la barra de búsqueda, así como ofrecer opciones más intuitivas para cerrar sesión y mejorar la organización visual de las secciones de detalles del libro. Esto contribuye a una experiencia más fluida y accesible para los usuarios.  

*TF*

**Conclusiones**

1. Implementación del sistema de autenticación y autorización con JWT

Se consolidó un sistema robusto de autenticación y autorización utilizando tokens JWT, lo que mejoró significativamente la seguridad de la plataforma. La integración de IAM (Identity and Access Management) permitió diferenciar y gestionar adecuadamente los flujos de acceso para administradores y clientes, brindando a cada tipo de usuario un control adecuado sobre los recursos de la aplicación. Con esta implementación, los usuarios ahora pueden iniciar sesión de manera segura, lo que garantiza que solo aquellos con los permisos adecuados accedan a las funcionalidades protegidas.


2. Despliegue completo y funcionamiento del frontend con el backend

La integración del frontend con el backend fue completada, asegurando que todas las funcionalidades de la aplicación web Livria estuvieran operativas y sincronizadas. Tras la implementación de la autenticación segura y el manejo de tokens JWT, el frontend fue correctamente vinculado al backend, lo que permitió que los usuarios pudieran interactuar con la aplicación de manera fluida. El proyecto fue desplegado exitosamente, lo que permitió que la plataforma estuviera disponible en un entorno de producción para pruebas de usuarios reales. El despliegue proporcionó una infraestructura confiable para garantizar el correcto funcionamiento de la aplicación web en un entorno real. 


**Recomendaciones**

1. Revisión en la infraestructura y escalabilidad del backend

Se logró mejorar la infraestructura del backend, enfocándose en la escalabilidad y optimización de recursos. Sin embargo, a medida que Livria crece y el número de usuarios, productos y transacciones aumenta, se debe garantizar que el backend pueda manejar una mayor carga sin comprometer el rendimiento. Para ello, es esencial continuar con el uso de estrategias de escalabilidad, como la implementación de microservicios o el uso de caches en las consultas más pesadas. El sistema de base de datos debe ser monitoreado y ajustado para asegurarse de que los tiempos de respuesta sigan siendo rápidos incluso con una mayor cantidad de datos.


2. Seguir mejorando la experiencia de nuestros usuarios

Es fundamental que Livria continúe enfocándose en mejorar constantemente la experiencia de usuario para garantizar que los usuarios disfruten de una plataforma fluida, intuitiva y agradable. Para ello, se recomienda optimizar la navegación para asegurar que los usuarios puedan encontrar lo que buscan de manera rápida y eficiente. Además, realizar pruebas de usabilidad constante con usuarios reales, permitirá identificar puntos débiles en la experiencia y actuar rápidamente para solucionarlos.

# VIDEO ABOUT-THE-TEAM

Link del video: [VideoAbout-the-Team]()

# BIBLIOGRAFÍA 
Alvarez, A. (2020, 5 de agosto). 5W2H: Qué significa, para qué sirve, cómo aplicarla y algunos ejemplos. LeanConstructionMexico. https://www.leanconstructionmexico.com.mx/post/5w2h-qu%C3%A9-significa-para-qu%C3%A9-sirve-c%C3%B3mo-aplicarla-y-algunos-ejemplos
Fabiana, E., & Vega, J. (2022). La motivación en el aprendizaje de la lectura en los estudiantes. Revista EDUCARE - UPEL-IPB - Segunda Nueva Etapa 2.0, 26(Extraordinario), 476–493. https://doi.org/10.46498/reduipb.v26iExtraordinario.1641
Mamani, B., Chata, L., & Choque, D. (2024). Efecto del uso de Tik Tok en el rendimiento académico de estudiantes de 5to grado . Revista Tribunal, 4(9), 161-175. https://doi.org/10.59659/revistatribunal.v4i9.71 
Ministerio de Cultura. (2022, febrero). Encuesta Nacional de Lectura 2022 Informe de Lectores y no lectores. https://perulee.pe/sites/default/files/ENL%202022%20-%20Informe%20de%20lectores%20y%20no%20lectores.pdf 
Torres-Vega, E. (2025). Comprensión lectora en estudiantes de secundaria en Perú. Horizontes. Revista De Investigación En Ciencias De La Educación, 9(36), 177–187. https://doi.org/10.33996/revistahorizontes.v9i36.909 

# ANEXOS

Diagrama C4: https://drive.google.com/file/d/14LIW0V4P1bBFikrUViIq4owWTtexcsCh/view?usp=sharing

Link de la landing page: https://bookify-livria.github.io/livria.github.io/

Link de la aplicación web: https://livria.netlify.app/

Link del backend: https://app-250621192653.azurewebsites.net/swagger/index.html

