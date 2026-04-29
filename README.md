<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC" width="200"/>
</p>

<h1 align="center">Universidad Peruana de Ciencias Aplicadas</h1>
<h2 align="center">Facultad de Ingeniería</h2>
<h3 align="center">Carrera de Ingeniería de Software</h3>
<h3 align="center">Ciclo 2026-10</h3>

---

**Código y Nombre del Curso:** 1ASI0732 – Diseño de Experimentos de Ingeniería de Software

**NRC:** 12278

**Nombre del Profesor:** Julio Manuel Noriega Melendez

---

# Informe de Trabajo Final

**Nombre del Startup:** Defontes

**Nombre del Producto:** Livria

---

## Relación de Integrantes

| Código | Apellidos y Nombres |
|--------|---------------------|
| u202310877 | Alva Abanto, Luis Andrés |
| u202311157 | Binda Arbañil, Marcelo Alejandro |
| u202311701 | Castillo Garay, Ainhoa Lucía |
| u202312287 | Martel Andrade, Cassius Estefano |
| u20201F855 | Nakamurakare Teruya, Alex Tomio |
| u202312504 | Yalán Zhang, Angie Christina |

---

**Mes y Año:** Abril 2026

---

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
| 1.0 | 24-04-2026 | Todos | Creación del informe. Inclusión de Capítulos I, II, III, IV y V (Sprint 1). |

---


## Project Report Collaboration Insights

El desarrollo del proyecto se llevó a cabo mediante una estrategia de colaboración multi-repositorio, permitiendo una gestión especializada tanto para el informe técnico como para los diversos componentes del software (Landing Page, Aplicación Móvil y API). Los miembros del equipo mantuvieron una participación activa y equitativa en todos los entornos, utilizando GitHub como eje central para la integración de versiones, el seguimiento de commits y la documentación detallada de cada avance, asegurando así la trazabilidad y coherencia entre el desarrollo técnico y el reporte académico.

URL del repositorio del Project Report en GitHub:
[https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-report](https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-report)

[Descripción de cómo se han desarrollado las actividades de elaboración del informe. Incluir capturas de analíticos de colaboración y commits en GitHub realizados por los miembros del equipo.]

---

## Contenido

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Product Backlog](#33-product-backlog)
  - [3.4. Impact Mapping](#34-impact-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
  - [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Relational/Non-Relational Database Diagram](#481-relationalnon-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Product Implementation & Deployment](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Native-Mobile Application Evidence](#523-implemented-native-mobile-application-evidence)
    - [5.2.4. Implemented RESTful API and/or Serverless Backend Evidence](#524-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.5. RESTful API documentation](#525-restful-api-documentation)
    - [5.2.6. Team Collaboration Insights](#526-team-collaboration-insights)
  - [5.3. Video About-the-Product](#53-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 4**
**Criterio:** La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 4.

| Criterio Específico | Acciones Realizadas | Conclusiones |
|---|---|---|
| 4.c.1 **Reconoce la responsabilidad ética y profesinal en situaciones de ingeniería de software** | **Luis Andres Alva Abanto** <br> **TB1** <br><br> **Marcelo Alejandro Binda Arbañil** <br> **TB1** <br><br> **Ainhoa Lucía Castillo Garay** <br> **TB1** <br><br> **Cassius Estefano Martel Andrade** <br> **TB1** <br><br> **Alex Tomio Nakamurakare Teruya** <br> **TB1** <br><br> **Angie Christina Yalán Zhang** <br> **TB1** | **TB1** <br> |
| 4.c.2 **Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales** | **Luis Andres Alva Abanto** <br> **TB1** <br><br> **Marcelo Alejandro Binda Arbañil** <br> **TB1** <br><br> **Ainhoa Lucía Castillo Garay** <br> **TB1** <br><br> **Cassius Estefano Martel Andrade** <br> **TB1** <br><br> **Alex Tomio Nakamurakare Teruya** <br> **TB1** <br><br> **Angie Christina Yalán Zhang** <br> **TB1** | **TB1** <br> |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Defontes es una startup liderada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC) dedicada a impulsar la lectura y facilitar su acceso en entornos digitales. Con el objetivo de acercar la literatura a más personas, se ha desarrollado el proyecto Livria, una aplicación móvil innovadora que permite a los usuarios descubrir, adquirir y disfrutar de libros en diversos formatos: físicos, electrónicos y audiolibros. 

En Defontes, creemos que la lectura es fundamental para el aprendizaje, la cultura y el desarrollo del pensamiento crítico. No solo se trata de un hábito, sino de una elección. Por ello, a través de una experiencia intuitiva y personalizada, Livria busca convertirse en el punto de encuentro ideal entre lectores y su próxima gran historia.

Misión: Promover el hábito de la lectura y facilitar el acceso a la literatura mediante una plataforma digital intuitiva y accesible. Livria busca conectar a los lectores con una amplia selección de libros en diferentes formatos, brindando una experiencia personalizada que fomente el amor por la lectura y el conocimiento.

Visión: Convertirse en la plataforma líder en América Latina para la compra y disfrute de libros en formatos físico, digital y audiolibro. Aspiramos a revolucionar la forma en que las personas acceden a la literatura, creando una comunidad de lectores apasionados y fortaleciendo la cultura literaria en el mundo digital.

### 1.1.2. Perfiles de integrantes del equipo

| Nombre | Código | Carrera | Descripción |
|---|---|---|---|
| Alva Abanto, Luis Andres <p align="center"> <img src="https://imgur.com/j4tnSmM.png" alt="luis"> </p> | U202310877 | Ingeniería de Software | Mi nombre es Luis Andrés Alva Abanto, tengo 20 años y estudio ingeniería de software. |
| Binda Arbañil, Marcelo Alejandro <p align="center"> <img src="https://imgur.com/9XWdym2.jpg" alt="luis"> </p> | U202311157 | Ingeniería de Software | Mi nombre es Marcelo Binda y soy estudiante de séptimo ciclo de la carrera de Ingeniería de Software. Me defino como un profesional proactivo y orientado a resultados, con una capacidad natural para el trabajo colaborativo y la resolución de problemas complejos. Me caracteriza mi alto sentido de la responsabilidad y un compromiso inquebrantable con la calidad técnica en cada proyecto que emprendo. Busco siempre la eficiencia en el código y la excelencia en la experiencia del usuario, manteniendo una comunicación fluida y constante con mi equipo de trabajo. |
| Castillo Garay, Ainhoa Lucía <p align="center"> <img src="https://imgur.com/2UE04dl.jpg" alt="luis"> </p> | U202311701 | Ingeniería de Software | Mi nombre es Ainhoa Castillo y estoy cursando mi séptimo ciclo en la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC). Me considero una persona activa y responsable. Me gusta trabajar en un ambiente tranquilo y divertido, pero siempre eficaz. Me gusta programar y resolver problemas mediante soluciones creativas. |
| Martel Andrade, Cassius Estefano <p align="center"> <img src="https://imgur.com/DNdObuQ.jpg" alt="luis"> </p> | U202312287 | Ingeniería de Software | Mi nombre es Cassius Martel y soy estudiante de séptimo de la carrera de Ingeniería de Software. Me caracterizo por ser líder nato que siempre busca sacar lo mejor de cada uno de sus compañeros de equipo, así como por ser sumamente responsable y atento con los requerimientos de cada proyecto en el que me involucro. Tengo conocimientos técnicos en lenguajes y diversos frameworks de desarrollo Frontend, bases de datos y metodologías ágiles. |
| Nakamurakare Teruya, Alex Tomio <p align="center"> <img src="https://imgur.com/Z8IWHJL.jpg" alt="luis"> </p> | U20201f855 | Ingeniería de Software | Mi nombre es Tomio Nakamurakare, estudiante de séptimo ciclo de la carrera de Ingeniería de Software. Me defino como un profesional en formación con una fuerte inclinación hacia el aprendizaje continuo y la aplicación práctica de nuevas tecnologías. Poseo una mentalidad orientada a la resolución de problemas complejos, viendo en los retos técnicos una oportunidad para fortalecer mi pensamiento crítico. Mi enfoque de trabajo se caracteriza por la persistencia y la resiliencia, cualidades que me permiten afrontar y superar las dificultades inherentes al desarrollo de software. |
| Yalán Zhang, Angie Christina <p align="center"> <img src="https://imgur.com/37xqvzq.png" alt="angie"> </p> | U202311157 | Ingeniería de Software | Mi nombre es Angie Yalán. Soy estudiante de la carrera Ingeniería de Software y tengo 20 años. Me considero una persona proactiva que le gustan nuevas experiencias y aprender cosas diferentes. Sigo en el proceso de mejora en cuanto a la programación y cuento con toda la iniciativa para ser cada día mejor en ello.|

## 1.2. Solution Profile

Livria es una aplicación móvil diseñada para revolucionar la manera en que las personas adquieren y disfrutan de los libros. A través de una plataforma intuitiva y accesible, ofrece una amplia selección de títulos, permitiendo a los usuarios explorar y comprar sus lecturas favoritas de forma fácil y rápida. Con el objetivo de fomentar el hábito de la lectura y crear una comunidad de amantes de los libros, Livria facilita la conexión entre los lectores y el mundo literario en un entorno digital moderno.

### 1.2.1. Antecedentes y problemática

De acuerdo con Lean Construction México, la metodología de las 5W’s y 2H’s permite estructurar y desarrollar un plan de acción o una estrategia detallada (Alvarez, 2020). En este contexto, esta herramienta resulta clave para comprender a fondo las necesidades de los usuarios. Por esta razón, se utilizó para recopilar información, la cual se presentará a continuación.

#### 1.2.1.1. What

##### ¿Cuál es el problema?

Livria nace como respuesta a una problemática alarmante: la falta de hábito de lectura y los bajos niveles de comprensión lectora, especialmente en adolescentes y jóvenes. Según la Encuesta Nacional de Lectura de 2022 (Ministerio de Cultura), solo el 15.3 % de menores de 0 a 17 años lee con regularidad diaria y, peor aún, el 21.2 % no lee en absoluto. En adultos alfabetos de 18 a 64 años, a nivel nacional, existe un porcentaje mayor de no lectores, que asciende al 52.7% (Ministerio de Cultura, 2022), lo que evidencia un hábito lector frágil y poco sostenido.

A esto se suma la influencia de las redes sociales y el consumo de contenido breve e inmediato, que ha desplazado el interés por la lectura profunda y reflexiva. Un estudio realizado en una institución educativa pública del distrito de El Agustino en 2022 reveló que el 72.2 % de los estudiantes de secundaria se encuentran en un nivel bajo de comprensión lectora, y solo un 1.9 % alcanzó un nivel alto (Torres-Vega, 2025). Esta situación refleja una crisis silenciosa en el desarrollo educativo y cognitivo de las nuevas generaciones.

En este contexto, Livria se presenta como una solución innovadora que busca revertir esta tendencia preocupante. A través de una plataforma móvil moderna, accesible y atractiva, busca acercar los libros a los usuarios, fomentar el gusto por la lectura y construir una comunidad de lectores comprometidos, adaptada a los hábitos digitales de hoy.

##### ¿Cuál es la relación con la persona en cuestión?

Para todo aquel que esté interesado en la lectura, Livria se presenta como una plataforma atractiva que elimina las barreras en el acceso a materiales adecuados, fomenta el hábito de la lectura y conecta a los jóvenes con libros en distintos formatos, adaptándose a sus costumbres digitales y promoviendo el interés por la lectura de manera dinámica y envolvente.

#### 1.2.1.2. When

##### ¿Cuándo sucede el problema?

El problema de la baja tasa de lectura y comprensión lectora se agrava cuando los potenciales lectores enfrentan barreras de acceso a los materiales de lectura. 

Específicamente, esto ocurre cuando:

* Una persona intenta acceder a material de estudio o contenido literario que no está disponible en las principales plataformas
* Enfrenta dificultades con los procesos de compra o alquiler debido a largos tiempos de entrega
* Encuentra inconvenientes con los métodos de pago ofrecidos
* Necesita acceso inmediato a contenido pero debe esperar por cuestiones logísticas
* No encuentra un entorno motivador o una red de apoyo que lo incentive a continuar leyendo, lo que impide que la lectura se transforme en un hábito.

Estas barreras desincentivan el hábito lector y contribuyen directamente a las bajas estadísticas citadas en la Encuesta Nacional de Lectura, especialmente en un contexto donde lo digital e inmediato predomina.

##### ¿Cuándo utiliza el cliente el servicio?

El cliente usará Livria precisamente cuando quiera o necesite acceder a material de lectura sin enfrentar estas barreras, permitiéndole desarrollar y mantener un hábito lector regular gracias a su sistema de entrega rápida para libros físicos y acceso instantáneo a materiales digitales.
Además, cuando el cliente desea compartir sus opiniones, descubrir nuevas lecturas recomendadas por personas con intereses similares o interactuar con otros lectores apasionados, utilizará la sección de comunidad. Este espacio impulsa la conexión social en torno a la lectura, creando un entorno motivador y enriquecedor para los usuarios.

#### 1.2.1.3. Where

##### ¿Dónde está el cliente cuando usa el producto?

Livria está diseñada como una aplicación accesible tanto en versión IOS como Android, lo que permite a los usuarios disfrutar de sus funcionalidades desde cualquier lugar con conexión a internet. De este modo, pueden acceder a la plataforma ya sea desde sus computadoras o dispositivos móviles, facilitando la lectura y el acceso a libros en cualquier momento y contexto.

##### ¿Dónde surge el problema?

La problemática surge en los hogares y escuelas del Perú. Estos espacios son fundamentales para la formación de hábitos y habilidades lectoras, pero, en la actualidad, no se promueve activamente la lectura como una práctica cotidiana. La escasa presencia de libros, la ausencia de rutinas de lectura y el poco estímulo hacia el interés por los textos en estos espacios limitan el desarrollo del hábito lector.

#### 1.2.1.4. Who

##### ¿Quiénes están involucrados?

Los principales involucrados en Livria son, en primer lugar, los amantes de la lectura, quienes buscan un espacio dinámico y accesible para descubrir, compartir y disfrutar de nuevos libros. Además, un grupo clave son aquellas personas, especialmente adolescentes y jóvenes, que desean mejorar su hábito lector o incluso dar sus primeros pasos en el mundo de la lectura.

##### ¿A quiénes les sucede el problema?

El problema afecta principalmente a adolescentes y jóvenes, quienes enfrentan dificultades en la comprensión lectora y han perdido el interés por la lectura debido a la influencia de las redes sociales y el consumo de contenido breve e inmediato. Asimismo, afecta a adultos de diferente rango de edad, quienes muchas veces no cuentan con el tiempo, el hábito o el acceso a libros adecuados. En un sentido más amplio, el problema repercute en la sociedad en general, ya que la falta de lectura impide el desarrollo del pensamiento crítico, la educación y el acceso a la información, reduciendo las oportunidades de crecimiento personal y profesional.

##### ¿Quién lo utilizará?

Livria será utilizada por una variedad de usuarios con necesidades y características específicas. En primer lugar, por adolescentes y jóvenes en busca de entretenimiento educativo, que desean una plataforma que haga la lectura más atractiva y relevante, con géneros y libros populares y recomendaciones personalizadas; así como aquellos con dificultades en comprensión lectora que buscan mejorar sus habilidades de lectura de manera accesible y adaptada a su ritmo. Por otro lado, adultos de diferentes edades que han dejado de leer por falta de tiempo o motivación, pero ahora desean retomar el hábito de la lectura con libros que se ajusten a sus intereses y disponibilidad de tiempo.

#### 1.2.1.5. Why

##### ¿Cuál es la causa del problema?

Puesto que la problemática es la falta de hábito de lectura y los bajos niveles de comprensión lectora, se pueden identificar diversas causas que contribuyen a esta situación.

Una de las principales es la influencia de las redes sociales y el consumo de contenido digital breve. La exposición constante a videos cortos, memes y publicaciones rápidas ha modificado los hábitos de consumo de información, reduciendo la capacidad de concentración y la disposición a leer textos extensos. Esto ha generado que, especialmente entre adolescentes y jóvenes, la lectura se perciba como una actividad poco atractiva o demasiado exigente en comparación con el entretenimiento inmediato que ofrece el entorno digital. A medida que los jóvenes dedican mayor tiempo a las redes sociales, se incrementa el impacto negativo en su rendimiento académico (Mamami et al.,2024) y, por ende, se compromete su nivel de comprensión lectora. 

Otra causa significativa es la falta de estímulo lector en el hogar. Muchos niños y jóvenes crecen en contextos donde la lectura no forma parte de la rutina diaria, ya sea por la ausencia de libros en casa, el poco interés de los adultos responsables o la falta de tiempo para compartir momentos de lectura en familia. Esta falta de acompañamiento desde edades tempranas limita el desarrollo de un vínculo positivo con la lectura. Además, se suma el escaso acceso a libros atractivos y adecuados. La adquisición de ellos es, muchas veces, dificultosa por cuestiones económicas; el acceso a nuevas ediciones se convierte en un lujo (D’Adderio, 2020). La limitada oferta de títulos que conecten con los gustos, intereses y realidades de los jóvenes, junto con el elevado costo de muchos libros o su baja disponibilidad en espacios públicos como bibliotecas, hace que el hábito lector sea difícil de desarrollar y sostener en el tiempo.

#### 1.2.1.6. How

##### ¿En qué condiciones los clientes utilizan nuestro producto?

Los clientes utilizan Livria en diversas condiciones, principalmente desde su entorno cotidiano, como el hogar, el centro de estudios o el lugar de trabajo, a través de dispositivos como celulares, tablets o computadoras. Gracias a su disponibilidad en diferentes sistemas operativos, los usuarios pueden explorar o adquirir libros en sus momentos libres, durante viajes o en tiempos de ocio.

Además, muchos acceden a Livria cuando desean descubrir nuevas lecturas, mejorar su comprensión lectora o simplemente reconectar con el hábito de leer. Estas condiciones responden a intereses personales, necesidades académicas o al deseo de aprovechar mejor el tiempo libre. En general, la plataforma se adapta al usuario, priorizando la comodidad, la accesibilidad y la personalización de la experiencia lectora.

##### ¿Cómo nos conocieron los compradores?

Los compradores conocen Livria mediante diversas vías de marketing, tales como la promoción en redes sociales (TikTok, Instagram, etc.), donde se comparte contenido relevante sobre el producto y se realizan campañas publicitarias para atraer a posibles clientes interesados en la lectura. Asimismo, los compradores pueden descubrir la plataforma a través de cartelería publicitaria en locales relacionados con el mundo de la lectura, como las bibliotecas públicas o la tienda física de Livria.

##### ¿Cómo prefieren los lectores acceder a nuestro contenido?

Los lectores prefieren acceder al contenido de Livria de manera rápida, sencilla y personalizada en cualquier dispositivo móvil de Android o IOS. Esta flexibilidad les permite realizar búsquedas y compras de libros desde cualquier lugar en el que se encuentren. Asimismo, valoran la propuesta de Livria por ofrecer un acceso dinámico y adaptado a sus hábitos digitales, donde la lectura se vive como una experiencia placentera y motivadora, más que como una obligación.

##### ¿Qué llevó a la persona a llegar a esta situación?

Lo que llevó a la persona a llegar a esta situación —es decir, a perder el hábito de lectura o a tener poca comprensión de textos— es una combinación de factores personales y sociales que se han acumulado a lo largo del tiempo.

En muchos casos, la falta de estímulos adecuados desde la infancia, tanto en el hogar como en la escuela, impidió que la lectura se convirtiera en una actividad cotidiana o placentera. Muchos educadores afirman que los recursos que poseen son poco suficientes para desarrollar la motivación de lectura en sus estudiantes (Fabiana & Vega, 2022). Además, la poca disponibilidad de libros atractivos o económicamente accesibles han contribuido al alejamiento del mundo literario.

A esto se suma la influencia creciente del entorno digital, donde predominan contenidos breves, visuales y de consumo rápido, que reducen la capacidad de concentración y hacen que leer un libro parezca una tarea demandante o incluso aburrida. En algunos casos, también influyen falta de tiempo, desmotivación o desconocimiento sobre qué leer o cómo empezar.

Todo esto ha llevado a que muchas personas lleguen a la actualidad sin una conexión real con los libros, con niveles bajos de comprensión lectora y con la sensación de que leer es algo ajeno a sus intereses o estilo de vida.

#### 1.2.1.7. How much

##### 1.2.1.7.1 Estadísticas que sustentan la problemática

Según los resultados de la Encuesta Nacional de Lectura de 2022 (Ministerio de Cultura), aunque el 78,8 % de niños y adolescentes de 0 a 17 años leyeron o fueron expuestos a la lectura de libros impresos o digitales, solo un 15,3 % lo hizo con frecuencia diaria, mientras que la mayoría (63,5 %) leyó con menor regularidad. Además, un 21,2 % no tuvo contacto con la lectura en absoluto, lo que evidencia una baja intensidad en las prácticas lectoras dentro de este grupo etario.

<p align="center">
  <img src="https://i.imgur.com/7MnGt7n.png" alt="12171">
</p>

https://imgur.com/8X2WQca.jpg
https://imgur.com/7MnGt7n.jpg
https://i.imgur.com/7MnGt7n.png
Nota. Adaptado de Encuesta Nacional de Lectura 2022. Informe de lectores y no lectores, por Ministerio de Cultura, 2022 (https://perulee.pe/sites/default/files/ENL%202022%20-%20Informe%20de%20lectores%20y%20no%20lectores.pdf)

Un estudio realizado en una institución educativa pública del distrito de El Agustino en 2022 reveló que el 72,2 % presenta un nivel bajo de comprensión lectora, el 25,9 % se encuentra en un nivel regular y solo el 1,9 % alcanza un nivel alto, lo que evidencia una preocupante deficiencia en esta habilidad (Torres–Vega, 2025).

<p align="center">
  <img src="https://imgur.com/R74IWKZ.jpg" alt="121712">
</p>
Nota. Adaptado de Comprensión lectora en estudiantes de secundaria en Perú, por Torres-Vega, 2025 (https://doi.org/10.33996/revistahorizontes.v9i36.909)

Una investigación realizada en la Institución Educativa San Jerónimo-Asillo, en Perú, analizó la relación entre el uso de TikTok y el rendimiento académico de estudiantes de quinto grado. Los resultados muestran que el 74.8 % de los alumnos se encuentra en un nivel de rendimiento regular y el 25.2 % en un nivel alto (Mamani et al., 2024). La mayoría de quienes usan TikTok con frecuencia tienden a ubicarse en el grupo de rendimiento regular, lo que sugiere una posible relación entre el uso de esta red social y un menor desempeño académico.

<p align="center">
  <img src="https://imgur.com/DY6cqya.jpg" alt="121713">
</p>
Nota. Adaptado de Efecto del uso de Tik Tok en el rendimiento académico de estudiantes de 5to grado, por Mamani et al, 2024 (https://doi.org/10.59659/revistatribunal.v4i9.71)

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

Nuestro servicio busca ofrecer un entorno digital literario que unifique la experiencia de compra, descubrimiento y conexión social de los lectores. A través de este entorno, los usuarios pueden transformar la lectura de una obligación a un placer, acceder a contenidos de interés y participar en una comunidad.

Hemos observado un factor crítico que afecta el cumplimiento de estos objetivos, y es la ausencia de un entorno digital que integre la compra, el descubrimiento y la conexión social. Hoy en día, la lectura profunda se enfrenta a un declive acelerado, y la experiencia del lector está fragmentada entre lo físico y lo virtual, lo cual impide la interacción fluida y el acceso a contenidos relevantes.

¿Cómo podemos diseñar un ecosistema literario digital unificado que motive el hábito lector, mejore la comprensión de los usuarios, facilite la compra de libros y fortalezca la conexión entre lectores en una comunidad accesible y atractiva?

#### 1.2.2.2. Lean UX Assumptions

##### Features
* Algoritmos de recomendación de libros y autores.
* Comunidades de usuarios con inclinaciones literarias similares.
* Búsqueda avanzada
* Compra y venta de libros en diferentes formatos
* Opciones de entrega flexibles según las necesidades del cliente
* Amplio catálogo de obras literarias

##### Business Outcomes
Incentivar la lectura: El principal objetivo de Livria es promover el hábito de la lectura en las personas, ya sea con fines educativos, de entretenimiento o como una alternativa de pasatiempo saludable. Nuestra startup promueve el acceso a material de lectura de todo tipo de manera rápida y sencilla, ofreciendo al lector diferentes opciones, filtros de búsqueda y recomendaciones personalizadas, facilitando el proceso de encontrar un libro que se ajuste a sus intereses. Además, Livria incorpora una sección de comunidad, donde los usuarios pueden interactuar con otros lectores, compartir reseñas, participar en foros temáticos y descubrir lecturas recomendadas por personas con gustos similares.

Generación de ingresos: Al habilitar la monetización a través del uso de la aplicación móvil y el modelo de negocio por suscripciones, nuestra startup podrá generar ganancias que pueden ser utilizadas para mejorar la calidad de nuestro servicio, expandir nuestra marca y ofrecer un catálogo más amplio de productos para nuestros usuarios. Estas mejoras garantizarán una mejor experiencia para los usuarios previos y captar nuevo público.

Livria generará ingresos principalmente mediante la venta de libros físicos y digitales a través de la aplicación móvil. Adicionalmente, se ofrece un plan de suscripción mensual para la comunidad. Esta combinación permite garantizar la sostenibilidad del negocio, mejorar continuamente la plataforma y ampliar el catálogo de productos y servicios para los usuarios.

Diferenciación en el mercado: La aplicación móvil de Livria permitirá que nuestra startup se destaque en el mercado gracias a funcionalidades únicas, como algoritmos de recomendación de libros y la sección de comunidad. Estas características crean una experiencia de lectura digital diferenciada que atrae a lectores interesados en descubrir, compartir y conectar con otros usuarios.

Formación de asociaciones comerciales: Las características únicas del servicio de Livria permitirán el establecimiento de alianzas estratégicas con negocios de rubros similares o relacionados al nuestro, tales como imprentas, distribuidoras y editoriales.

##### User Benefits
* Acceso a una amplia variedad de libros impresos y digitales desde una sola plataforma, permitiendo explorar y adquirir lecturas de forma rápida y sencilla.
* Recomendaciones personalizadas según intereses, facilitando la conexión con libros significativos y motivadores.
* Espacios de interacción y comunidad donde los usuarios pueden compartir opiniones, participar en clubes de lectura y descubrir nuevas obras a través de otros lectores.
* Experiencia accesible desde cualquier dispositivo, pensada para adolescentes, jóvenes y adultos que buscan flexibilidad y comodidad al leer.
* Fomento del hábito lector mediante notificaciones personalizadas.
* Ahorro de tiempo y esfuerzo en la búsqueda de libros adecuados, al centralizar en una sola plataforma la selección, compra y gestión de lecturas.

#### 1.2.2.3. Lean UX Hypothesis Statements

Creemos que, al ofrecer recomendaciones de libros altamente personalizadas y dinámicas, para los nuevos usuarios de la plataforma, obtendremos una mejora significativa en la experiencia de descubrimiento de contenido nuevo y aumentará su retención. Sabremos que hemos tenido éxito, cuando veamos que los usuarios interactúan frecuentemente con el contenido sugerido y compran los libros recomendados.

Creemos que, al integrar una sección de comunidad vibrante donde se pueda interactuar, compartir y formar grupos de lectura, para personas que buscan motivación y compromiso social, obtendremos un incremento en el descubrimiento de libros y la participación activa en la aplicación. Sabremos que hemos tenido éxito, cuando veamos un crecimiento en la generación de contenido social (comentarios, publicaciones y reseñas) y en la creación de comunidades de Livria.

Creemos que, al integrar y facilitar el acceso a libros en múltiples formatos (físico, E-book, audiolibro), para usuarios con baja frecuencia de lectura, obtendremos un aumento en la constancia y el compromiso con la lectura. Sabremos que hemos tenido éxito, cuando veamos que las ventas de los diferentes formatos aumentan significativamente.

Creemos que, al implementar la publicación de reseñas y calificación con estrellas en cada libro, para los usuarios que han leído diferentes obras literarias y para los usuarios interesados en leerlas, obtendremos una mayor confianza en el catálogo y un crecimiento en interacciones sociales. Sabremos que hemos tenido éxito, cuando veamos un incremento de calificaciones en los libros y de ventas en aquellos que tienen mayor cantidad de reseñas.

#### 1.2.2.4. Lean UX Canvas

<p align="center">
  <img src="https://imgur.com/x1hEKKV.jpg" alt="12231">
</p>

<p align="center">
  <img src="https://imgur.com/iiE6SOn.jpg" alt="122312">
</p>

Link del Lean UX Canvas: https://docs.google.com/document/d/1J1PJ1gn62fnoB0Saa-rrgXwppnVQFzs8/edit?usp=sharing&ouid=112054289490328588638&rtpof=true&sd=true

## 1.3. Segmentos objetivo

Con el objetivo de atraer eficazmente a futuros usuarios y brindar un producto que responda de manera precisa a sus necesidades, se han identificado los siguientes dos segmentos objetivo.

Con el objetivo de atraer eficazmente a futuros usuarios y brindar un producto que responda de manera precisa a sus necesidades, se han identificado los siguientes dos segmentos objetivo.

**Segmento objetivo \#1: Lectores en Desarrollo**

Este segmento incluye tanto a personas que ya tienen afinidad por la lectura, como a aquellas que buscan incorporar este hábito en su vida diaria, con fines recreativos y educativos. Son individuos que desean encontrar plataformas digitales que faciliten el acceso a material variado, atractivo y adaptado a sus intereses. Este grupo busca principalmente plataformas de compra de libros que sean cómodas, intuitivas y que los ayuden a encontrar títulos en base a sus preferencias y objetivos de lectura.

**Aspectos demográficos:**

* Sexo: Masculino y femenino  
* Rango de edad: 16 a 64 años  
* Nivel socioeconómico: clases A, B y C (alta, media-alta y media), con acceso frecuente a dispositivos móviles e internet

**Aspectos geográficos:**

* Nacionalidad: Global, no limitado a un país específico  
* Zona geográfica: Urbana

**Aspectos psicográficos:**

* Intereses: Lectura contemporánea y clásica, exploración cultural, apreciación artística, entretenimiento y desarrollo personal a través de la lectura  
* Estilo de vida: Personas independientes o profesionales que valoran el crecimiento personal y buscan enriquecer su tiempo libre con actividades intelectuales y culturales. Utilizan servicios digitales para entretenimiento y consumo literario  
* Actitudes: Valoran la comodidad, la personalización y el acceso inmediato a contenido de calidad. Son curiosos, abiertos a nuevas experiencias literarias y disfrutan descubrir autores y tendencias

Las estadísticas respaldan que este segmento constituye un público relevante: según la Encuesta Nacional de Lectura 2022, el 47,3 % de la población alfabeta de 18 a 64 años leyó libros en el último año, siendo la lectura más frecuente en mujeres (51,5 %) que en hombres (43,2 %) y concentrándose principalmente en áreas urbanas (50,3 % frente al 29,8 % en zonas rurales) (Ministerio de Cultura del Perú & Instituto Nacional de Estadística e Informática, 2023). Además, el 36,3 % de estos lectores prefirió libros de literatura, mientras que un 68,5 % eligió sus lecturas por el tema y un 23,3 % por recomendación de amigos o familiares, lo que muestra el interés en explorar nuevas obras y recibir orientación en sus elecciones de lectura. Estos datos evidencian que este grupo tiene motivación e interés en acceder a contenido literario, lo que lo convierte en un segmento estratégico para Livria.

**Segmento objetivo \#2: Lectores Comunitarios**

Este segmento incluye a jóvenes y adultos que buscan no solo leer, sino también intercambiar opiniones, descubrir nuevos títulos y conectarse con otros lectores mediante comunidades literarias, ya sean en línea o presenciales. Son personas motivadas por la socialización, el desarrollo personal y el aprendizaje continuo, que valoran espacios donde puedan discutir libros, recibir recomendaciones y participar en actividades grupales relacionadas con la lectura. Este grupo aprovecha plataformas digitales para conectar con otros lectores y formar parte de comunidades activas, fomentando así la constancia lectora y la interacción social en torno a la lectura.

**Aspectos demográficos:**

* Sexo: Masculino y femenino  
* Rango de edad: 16-40 años  
* Nivel socioeconómico: Clases A, B y C (alta, media-alta y media), con acceso a dispositivos móviles e internet.

**Aspectos geográficos:**

* Nacionalidad: Global, no específico  
* Zona geográfica: Urbana

**Aspectos psicográficos:**

* Intereses: Desarrollo personal, lectura digital, entretenimiento, educación y productividad  
* Estilo de vida: Jóvenes y adultos que utilizan plataformas digitales para informarse, aprender y entretenerse. Buscan mejorar sus hábitos, ampliar sus conocimientos y disfrutar de la lectura en entornos digitales  
* Actitudes: Motivados por el crecimiento personal, valoran la comodidad de acceder a información y contenido desde cualquier lugar, y están abiertos a probar nuevas herramientas digitales que faciliten su aprendizaje y fomenten su hábito lector

Los Millennials y la Generación Z muestran un creciente interés en comunidades lectoras, participando en clubes de lectura presenciales y virtuales que fomentan la interacción social y el hábito lector (Allen, 2024). Plataformas como TikTok (\#BookTok), Instagram y Facebook permiten a los jóvenes compartir reseñas y recomendaciones, creando redes que incentivan la lectura. Según Statista (2024), alrededor del 30 % de los jóvenes lectores descubren su club de lectura a través de redes sociales, evidenciando que la conexión digital es clave para este segmento, lo que lo convierte en un público estratégico para Livria.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En el sector de la venta y distribución de libros a través de dispositivos móviles, existen varias empresas que ofrecen aplicaciones móviles o versiones optimizadas para smartphones. Los principales competidores directos son:

* Crisol: Crisol cuenta con una aplicación móvil que complementa su red de librerías físicas y su portal web. A través de la app, los usuarios pueden explorar su variado catálogo de libros académicos, de ficción, infantiles y más. Su fortaleza principal radica en la accesibilidad al combinar experiencia digital y física, respaldada por grandes editoriales. No obstante, su aplicación móvil se percibe como una extensión de su web, con oportunidades de mejora en personalización, usabilidad y comunidad lectora.
* Ibero Librerías: Ibero ofrece su catálogo a través de su plataforma digital, principalmente orientada a estudiantes, docentes y profesionales. Aunque dispone de un sistema de compra en línea, su presencia en aplicaciones móviles es limitada, lo que restringe la experiencia de los usuarios que buscan inmediatez en dispositivos móviles. Su fortaleza está en los títulos especializados, pero carece de funcionalidades móviles como recomendaciones personalizadas, interacción social o accesibilidad mejorada.
* Communitas: Communitas es una librería independiente que apuesta por una experiencia cercana y personalizada con la comunidad lectora. Su enfoque principal está en la curaduría de títulos y la promoción cultural. Si bien dispone de venta en línea, su presencia en aplicaciones móviles es reducida, lo que limita la experiencia de interacción digital desde un smartphone. Esto abre un espacio para apps que combinen curaduría, personalización y comunidad lectora en un formato más interactivo y móvil-friendly.

### 2.1.1. Análisis competitivo

¿Por qué realizar este análisis?  
Este análisis es clave porque nos brinda una visión clara del panorama competitivo en el ecosistema móvil. Permite detectar oportunidades de diferenciación a partir de la experiencia en aplicaciones móviles, así como identificar fortalezas y debilidades en cuanto a usabilidad, accesibilidad y valor agregado en dispositivos móviles. Nos ayuda a reconocer en qué aspectos podemos superar a la competencia y ofrecer una experiencia única, fluida y adaptada al usuario móvil.

| Aspecto | **Livria** | **Crisol** | **Ibero Librerías** | **Communitas** |
|---------|------------|------------|----------------------|----------------|
| **Logo** | <div align="center"><img src="https://imgur.com/oHI5UEa.jpg" height="100"/></div> | <div align="center"><img src="https://imgur.com/cp7XfPx.jpg" height="100"/></div> | <div align="center"><img src="https://imgur.com/U7qSPil.jpg" height="100"/></div> | <div align="center"><img src="https://imgur.com/zAP7Dvf.jpg" height="100"/></div> |
| **Overview** | Livria es una librería especializada emergente cuyo enfoque principal es brindar accesibilidad a diversos materiales de lectura para sus clientes, facilitando la búsqueda de obras de entretenimiento o educativas que se ajusten a los gustos e intereses del cliente. | Crisol es una de las cadenas de librerías más grandes y conocidas de Perú, se destaca por su amplia oferta de obras artísticas y educativas, además de su compromiso con la cultura y calidad. Cuenta con locales en puntos estratégicos del país. | Ibero Librerías es una cadena de librerías muy popularizada en Perú, resalta por su especialización en ejemplares educativos, culturales y de ciencias sociales, con una selección variada de editoriales y autores emergentes. | Communitas es una librería cuyo enfoque se centra en libros que tratan temas complejos, filosóficos y modernos. Se destaca por ofrecer a sus clientes una experiencia más profunda y centrada en el pensamiento crítico, mediante un repertorio que invita al lector a reflexionar. |
| **Ventaja competitiva** | Combina un enfoque centrado en el cliente con herramientas de búsqueda rápidas y personalizadas, además de espacios de interacción que permiten a los usuarios compartir intereses y conectar con otros lectores. | Posee un amplio inventario de obras de todos los géneros y cuenta con locales ubicados en puntos estratégicos del Perú, lo que amplía tanto el catálogo de productos a ofrecer como su accesibilidad. | Ofrece un amplio repertorio de obras educativas y culturales menos comerciales y más exigentes, proyectando una imagen de marca más especializada en comparación con otras cadenas. | Presenta una curaduría enfocada en títulos que invitan al lector a la reflexión y el aprendizaje, apostando por una selección cuidadosa de títulos, priorizando la calidad sobre la rotación comercial. |
| **Mercado objetivo** | Jóvenes y adultos jóvenes que busquen empezar el hábito de la lectura y buscan comodidad, personalización y conexión social. | Personas de todas las edades interesadas en novelas y obras educativas o de entretenimiento. Lectores casuales y escolares. | Jóvenes y adultos de todas las edades interesados en obras educativas o culturales, lectores frecuentes y profesionales. | Jóvenes y adultos jóvenes interesados en obras ideológicas y literatura alternativa, lectores críticos. |
| **Estrategias de marketing** | Descuentos semanales, publicidad digital, marketing de temporada. | Descuentos frecuentes, marketing de temporada, publicidad digital, fuerte presencia en tiendas físicas. | Publicidad digital, presencia cuidada y refinada, eventos y presentaciones. | Eventos culturales, fuerte presencia en la comunidad lectora, colaboraciones con artistas y autores. |
| **Productos y servicios** | Libros físicos y digitales, suscripción (Community Plan), comunidades, publicaciones y reseñas. | Libros digitales y físicos, merchandising. | Libros físicos. | Libros físicos. |
| **Precios y costos** | Descuentos semanales y de temporada. <br> Promedio: S/. 30 – 90 <br> Suscripción: S/. 39.90 | Descuentos frecuentes y de temporada. <br> Promedio: S/. 40 – 200 <br> No cuenta con servicio de suscripción | Descuentos regulares y de temporada. <br> Promedio: S/. 40 – 130 <br> No cuenta con servicio de suscripción | Descuentos regulares. <br> Promedio: S/. 50 – 140 <br> No cuenta con servicio de suscripción |
| **Canales de distribución** | Entrega a domicilio, compra en local, venta digital (app móvil). | Entrega a domicilio, compra en local (app web y móvil). | Entrega a domicilio, compra en local (web responsive). | Entrega a domicilio, compra en local (web básica). |
| **Fortalezas** | Diseño UX Nativo y Centralizado: A diferencia de Ibero o Communitas, que dependen de webs responsivas, Livria ofrece una app móvil fluida y optimizada. Nuestra velocidad de implementación de funciones como el lector de e-books integrado es superior, brindando una experiencia de uso más cohesiva y profesional.<br><br>Ecosistema Social Integrado: Mientras Crisol es netamente transaccional, nosotros integramos una comunidad activa. Nuestra capacidad para generar interacción directa (foros y reseñas) dentro de la app nos da una ventaja competitiva en retención de usuarios que la competencia tradicional no posee. | - Amplia cobertura local (tiendas físicas y envíos).<br>- Gran variedad de obras.<br>- Popularidad y marca establecida.<br>- Veinte años de experiencia en el mercado. | - Curaduría especializada en títulos educativos y culturales.<br>- Imagen profesional y cercana.<br>- Fidelización del público objetivo.<br>- Treinta años de experiencia en el mercado. | - Curaduría selectiva y refinada.<br>- Imagen de marca fuerte.<br>- Comunidad establecida.<br>- Diez años de experiencia. |
| **Oportunidades** | Liderazgo en Formatos Digitales: Existe un vacío en la oferta de audiolibros y e-books en Ibero y **Communitas. Livria puede capturar este nicho joven mediante una distribución digital inmediata, superando la lentitud logística de la competencia física.<br><br>Modelo de Suscripción Inexistente en el Sector: Ningún competidor directo ofrece un "Community Plan". Implementar este modelo nos permite fidelizar clientes de forma recurrente, creando una barrera de salida que las librerías tradicionales no pueden replicar fácilmente. | - Posibilidad de expansión internacional.<br>- Convenios estratégicos con editoriales emergentes. | - Alianzas con centros educativos.<br>- Expansión al entorno digital con libros electrónicos. | - Expansión de marca en eventos o como agencia artística.<br>- Expansión al entorno digital con libros electrónicos. |
| **Debilidades** | Penetración de Mercado Inicial: Al ser una startup liderada por estudiantes, carecemos del posicionamiento de marca de 20 años que tiene **Crisol**. Esto nos pone en desventaja en términos de confianza masiva del consumidor frente a sus locales físicos establecidos.<br><br>Economía de Escala Limitada: Nuestra capacidad de negociación con grandes editoriales es menor comparada con Ibero, lo que dificulta igualar ciertos precios de preventa o acceder a ediciones exclusivas de alto volumen en el corto plazo. | - Enfoque demasiado amplio en catálogo (riesgo de falta de títulos específicos). | - Falta de venta de libros digitales (dependencia de lo físico). | - Nicho pequeño y especializado, poco escalable comercialmente. |
| **Amenazas** | Actualización Tecnológica de Grandes Cadenas:** El mayor capital de Crisol representa un riesgo si deciden modernizar su app para copiar nuestro modelo de comunidad. Su presupuesto publicitario podría eclipsar nuestra visibilidad si igualan nuestras funciones.<br><br>Guerra de Precios: Competidores consolidados podrían aplicar descuentos agresivos que Livria, por su escala, no podría sostener, captando así a nuestro segmento objetivo más sensible al precio. | - Aparición de un competidor con mayor alcance y precios más accesibles. | - Competidores similares con más locales o venta digital. | - Acaparamiento de su nicho por marcas grandes con más presupuesto. |

### 2.1.2. Estrategias y tácticas frente a competidores

#### **Estrategias de diferenciación de producto**

**#1 Implementación de ecosistema social y de comunidad:**
* **Fortaleza utilizada:** Enfoque en la conexión social (Comunidad).
* **Oportunidad aprovechada:** Modelo de suscripción inexistente en el sector (Community Plan).
* **Descripción:** A diferencia del modelo puramente transaccional de Crisol, Livria transformará la compra de un libro en una experiencia social persistente. Implementaremos foros de discusión moderados y grupos de lectura vinculados al "Community Plan". Esta táctica genera una barrera de salida emocional y social, ya que los usuarios no solo compran un producto, sino que mantienen una identidad y reputación dentro de la plataforma que no pueden trasladar a una librería convencional.

**#2 Sistema de recomendaciones hiper-personalizadas:**
* **Fortaleza utilizada:** Diseño UX Nativo y personalizado.
* **Oportunidad aprovechada:** Vacío en el acompañamiento a "Lectores en Desarrollo".
* **Descripción:** Mientras los competidores ofrecen catálogos genéricos, Livria utilizará algoritmos de recomendación basados en el comportamiento del usuario dentro de la app. Esta táctica está diseñada para captar al segmento que se siente abrumado en tiendas grandes como Ibero, facilitando el descubrimiento de títulos de forma intuitiva. Al reducir la "fatiga de decisión", aumentamos la tasa de conversión y posicionamos nuestra UX como superior a las plataformas web responsivas de la competencia.

#### **Estrategias de expansión de mercado**

**#1 Liderazgo en formatos de consumo digital inmediato:**
* **Debilidad de la competencia:** Dependencia del stock físico y lentitud logística en Ibero y Communitas.
* **Fortaleza utilizada:** Imagen moderna y agilidad tecnológica.
* **Oportunidad aprovechada:** Liderazgo en el nicho de E-books y Audiolibros.
* **Descripción:** Livria se posicionará como la alternativa "Digital First" mediante la integración nativa de un reproductor de audiolibros y lector de e-books. Esta táctica ataca directamente la debilidad de los competidores tradicionales que no ofrecen una solución móvil integral, permitiendo capturar al usuario que busca gratificación instantánea y eliminando los tiempos de espera de los envíos físicos.

**#2 Programa de Alianzas con Editoriales Independientes:**
* **Debilidad abordada:** Economía de escala limitada frente a grandes cadenas como Crisol.
* **Fortaleza utilizada:** Orientación centrada en el cliente y autores emergentes.
* **Oportunidad aprovechada:** Captación de nichos de literatura alternativa y crítica.
* **Descripción:** Para mitigar la ventaja de volumen de las grandes cadenas, Livria establecerá convenios exclusivos con editoriales emergentes. La táctica consiste en ofrecer una vitrina digital más atractiva y una curaduría especializada que la que ofrecen las grandes tiendas, convirtiéndonos en el canal preferido para títulos que los competidores suelen ignorar por no ser "best-sellers" masivos.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

Las entrevistas se adaptan a cada segmento con el fin de obtener información relevante para comprender sus necesidades y expectativas. Para iniciar, se plantean preguntas generales que permiten recoger datos demográficos básicos y sentar las bases para la construcción de arquetipos.

**Preguntas generales:**

* ¿Cuál es tu nombre?
* ¿Cuántos años tienes?
* ¿Cuál es tu distrito de residencia?
* ¿Cuál es tu estado civil?
* ¿A qué te dedicas?

***Segmento Objetivo #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Preguntas principales**

* ¿Con qué frecuencia lees actualmente y qué tipo de libros sueles preferir?
* ¿Qué factores influyen más en tu elección de libros (tema, autor, recomendaciones, reseñas, precio)?
* ¿Qué tan cómodo/a te resulta acceder a libros en formato físico versus digital?
* ¿Qué obstáculos encuentras actualmente para mantener o ampliar tu hábito de lectura?
* ¿Qué características valoras más en una plataforma digital de compra o lectura de libros?

**Preguntas complementarias**

* ¿Qué dispositivos usas más frecuentemente para leer (celular, tablet, laptop, lector digital)?
* ¿Cuánto influyen tus amigos, familiares o redes sociales en tu elección de lecturas?
* ¿Qué esperas de una experiencia digital de lectura (comodidad, personalización, rapidez, variedad)?
* ¿Has usado antes plataformas digitales de lectura? Si es así, ¿qué te gustó y qué no?

***Segmento objetivo #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores***

**Preguntas principales**

* ¿Qué tan importante es para ti compartir tus lecturas u opiniones con otros?
* ¿Participas en comunidades o clubes de lectura, ya sean físicos o virtuales? Si es así, ¿cómo es tu experiencia?
* ¿Qué plataformas digitales utilizas para descubrir libros o compartir reseñas (ej. TikTok, Instagram, Goodreads)?
* ¿Qué valor agregado te motiva a unirte a una comunidad lectora (descubrir títulos, interacción social, aprendizaje)?
* ¿Qué características debería tener una aplicación o plataforma para motivarte a interactuar con otros lectores?

**Preguntas complementarias**

* ¿Prefieres las recomendaciones de personas cercanas, de comunidades online o de algoritmos automatizados?
* ¿Qué te desmotiva o frustra en las comunidades literarias en las que has participado?
* ¿Qué tan importante es para ti que una plataforma combine lectura con interacción social?
* ¿Has comprado libros o decidido lecturas por sugerencia de un club o comunidad online?

### 2.2.2. Registro de entrevistas

***Segmento #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Entrevistado N.º 1: Valentina Binda**

* Edad: 18
* Distrito: Surquillo
* Estado civil: Soltero
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/QN0La0c.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 0:01
* Duración: 3:09

Valentina, una estudiante de 18 años, soltera y residente en el distrito de Surquillo, se identifica como una lectora motivada por la conexión emocional. Actualmente, lee con poca frecuencia, principalmente por falta de tiempo.

Su género favorito es el terror, ya que le gustan los libros que la mantienen "enganchada", con una trama que la sumerge por completo. A la hora de elegir sus lecturas, se deja influir por las reseñas y el autor, lo que demuestra que valora las opiniones de otros lectores y la trayectoria del escritor.

Valentina se siente más cómoda con los libros físicos, pues considera que los formatos digitales son difíciles de conseguir. A pesar de esto, si tuviera que leer en un dispositivo, usaría su tablet o su computadora.

El principal obstáculo que encuentra es la falta de tiempo, ya que sus responsabilidades académicas y personales le restan horas de lectura. Su experiencia con plataformas de lectura es limitada, habiendo utilizado solo una en el pasado, pero valora que estas ofrezcan una amplia variedad de títulos y una experiencia de lectura fluida.

***Segmento #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Entrevistado N.º 2: Emmanuel Andrades**

* Edad: 16
* Distrito: Miraflores
* Estado civil: Soltero
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/ow2WB78.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 3:09
* Duración: 3:01

Emmanuel, un estudiante de 20 años que reside en el distrito de Miraflores, se define como soltero y con un perfil de lector selectivo y enfocado en el entretenimiento. Su hábito de lectura es esporádico, impulsado principalmente por recomendaciones directas de su círculo de amigos, quienes son lectores ávidos.

El género que más le atrae es el de terror, buscando una conexión con la trama y la intriga que lo mantenga enganchado. Para él, el factor más influyente en la elección de un libro no es el autor ni las reseñas, sino el tema en sí y las recomendaciones de sus allegados.

En cuanto a formatos y tecnología, Emmanuel prefiere la lectura digital porque le resulta más cómoda y accesible. Considera que las plataformas digitales agilizan la búsqueda y el proceso de compra, en contraste con la experiencia de buscar un libro físico. Su principal dispositivo de lectura es una tablet, ya que la considera más cómoda que un celular o una laptop.

A pesar de su preferencia por lo digital, su experiencia con plataformas de lectura es limitada, habiendo usado solo una cuando era niño. Valora en una plataforma la rapidez y la amplia variedad de títulos disponibles. A diferencia de otros lectores, Emmanuel no encuentra grandes obstáculos para mantener su hábito de lectura, más allá de la falta de tiempo. La mayor parte de su tiempo libre está dedicado a sus estudios, lo cual deja menos espacio para la lectura.

**Entrevistado N.º 3: Jorge Binda**

* Edad: 49
* Distrito: Surquillo
* Estado civil: Divorciado
* Ocupación: Ingeniero de sistemas

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/pFD4v3B.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 6:11
* Duración: 3:48

Jorge, un trabajador de 49 años, divorciado y residente en el distrito de Surquillo, es un lector con perfil dual. Por un lado, tiene un interés práctico por el aprendizaje y el desarrollo personal. Por otro lado, disfruta del entretenimiento, especialmente con libros de terror, ya que le permiten desconectarse y sumergirse en una historia.

Su hábito de lectura es actualmente esporádico, leyendo un libro cada dos meses, a diferencia de su juventud, cuando lo hacía con mayor frecuencia. A la hora de elegir sus lecturas, se deja influir por dos factores principales: el autor y las reseñas de otros lectores, lo que sugiere que valora tanto la reputación del escritor como la validación social de la obra.

Respecto a los formatos, Jorge se siente cómodo con los libros físicos y los digitales, pero tiene una clara preferencia por los físicos, ya que le permiten una lectura más enfocada y libre de distracciones. Considera que al leer en su celular, su dispositivo habitual, las notificaciones y el acceso a otras aplicaciones lo convierten en una actividad más superficial.

El principal obstáculo que encuentra es la falta de tiempo, ya que sus responsabilidades laborales y personales reducen su disponibilidad para leer. Su única experiencia con plataformas digitales es a través de Spotify, donde escucha audiolibros. Le ha gustado esta experiencia porque le permite realizar otras actividades, como sus quehaceres o sus trayectos, mientras se concentra en el contenido del libro.

**Entrevistado N.º 4: Juan Fukusaki**

* Edad: 21 años
* Distrito de residencia: Pueblo Libre
* Estado civil: Soltero
* Ocupación: Cocinero

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/tz9ujx5.jpg" alt="12231">
</p>


* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 10:00
* Duración: 4:55

Juan Fukusaki, un joven cocinero de 21 años, presenta un perfil de lector con motivaciones duales. Por un lado, su interés es pragmático y profesional, evidente en su preferencia por libros de cocina que le ayudan a perfeccionar su oficio. Por otro, mantiene un interés por el entretenimiento y la evasión, disfrutando de la fantasía y la aventura medieval en su tiempo libre.

Su hábito de lectura es actualmente esporádico, un cambio drástico en comparación con su etapa escolar y el inicio de la pandemia. El principal obstáculo que enfrenta es la falta de tiempo, ya que su trabajo le exige mucho y el cansancio lo lleva a preferir ver series de televisión, una actividad que ha reemplazado la lectura nocturna.

En cuanto a la elección de sus lecturas, Juan no se deja llevar por el autor ni por las reseñas en línea. Su decisión se basa principalmente en el tema del libro y, de manera crucial, en las recomendaciones personales de su círculo de amigos. Esto sugiere que confía más en la validación social directa que en la opinión de extraños.

Respecto a la tecnología y los formatos, Juan se siente cómodo con los libros físicos, ya que vive cerca de librerías. Su experiencia con plataformas digitales es limitada, habiendo utilizado una sola vez una aplicación de lectura. A pesar de su inexperiencia, tiene expectativas claras: valora que una plataforma sea fácil de usar y que cuente con una gran variedad de títulos, incluyendo temas específicos como la gastronomía. La principal frustración que encontró en su única experiencia digital fue, precisamente, la falta de oferta en el nicho que le interesaba en ese momento. Los dispositivos que utiliza para consumir contenido son su celular cuando está fuera de casa y su laptop en un entorno más relajado.

***Segmento objetivo #2: Lectores casuales y aficionados a la lectura***

**Entrevistado N.º 1: Roxana Arbañil**

* Edad: 50
* Distrito: Surquillo
* Estado civil: Divorciada
* Ocupación: Asistente de desarrollo organizacional en la subgerencia de gestión humana del Perú

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/gCau8K5.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 14:55
* Duración: 4:23

Roxana Katty Arbañil, de 50 años, divorciada y residente en el distrito de Surquillo, es una lectora que valora profundamente la interacción social en torno a la lectura. Para ella, compartir opiniones y recomendaciones con otros lectores es fundamental, ya que enriquece su experiencia y le permite descubrir nuevas historias y perspectivas.

Ella es una participante activa en comunidades virtuales con un grupo de amigos, donde intercambian ideas y se pasan libros. También utiliza Instagram para seguir comunidades literarias y booktubers que le ayudan a descubrir nuevos títulos y a mantenerse al tanto de las tendencias literarias. Las recomendaciones de personas cercanas y de las comunidades online son sus principales fuentes de inspiración.

Roxana valora que una comunidad lectora le permita aprender y la mantenga motivada. El simple hecho de tener un grupo con el cual comentar lo que lee la impulsa a leer más. Para ella, una plataforma ideal debe ser amigable, práctica y fácil de usar, con funciones que le permitan compartir sus opiniones y recibir recomendaciones de manera sencilla.

Aunque se siente cómoda con las herramientas digitales, ha experimentado frustración en algunas comunidades online donde se comparten opiniones de manera superficial o sin profundizar en el contenido. Considera que la calidad de la conversación es crucial. La posibilidad de comprar libros o decidir sus próximas lecturas por sugerencia de una comunidad es un valor agregado importante para ella, ya que le ahorra tiempo y le asegura que la recomendación proviene de un grupo con intereses similares.

**Entrevistado N.º 2: Sofia Pimentel**

* Edad: 16
* Distrito: Magdalena del Mar
* Estado civil: Soltera
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/drReFnp.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 19:18
* Duración: 3:08

Sofía Pimentel, una estudiante de 16 años, soltera y residente en el distrito de Magdalena del Mar, es una lectora social para quien el acto de leer no es una actividad solitaria. Para ella, es muy importante compartir sus lecturas y opiniones con otros, ya que esto le permite conectarse con personas que tienen intereses similares.

Sofía participa en comunidades de lectura, lo que la motiva a leer más y a conocer personas con gustos parecidos a los suyos. Para ella, es fundamental poder escuchar diferentes puntos de vista para entender en profundidad lo que lee.

La principal motivación de Sofía para unirse a una comunidad de lectura es la interacción social. En su experiencia, valora que estas comunidades sean abiertas y le permitan expresarse libremente. Por otro lado, le desmotiva cuando las comunidades se vuelven cerradas y no permiten que los miembros compartan sus opiniones.

Para Sofía, la plataforma ideal debe ser fácil de usar, rápida y, sobre todo, debe tener un espacio dedicado para recomendar libros y permitir la interacción entre lectores. Ella prefiere las recomendaciones de personas cercanas o de comunidades online con las que se identifica, ya que le generan mayor confianza.

**Entrevistado N.º 3: Nicole Azaña**

* Edad: 24
* Distrito: Ate
* Estado civil: Soltera
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/Vfa4w8u.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 22:27
* Duración: 4:58

Nicole Azaña, de 24 años, soltera y residente en el distrito de Ate, es una lectora que valora el intercambio de opiniones. Para ella, compartir sus lecturas y reseñas con otros es muy importante, ya que le permite conocer diferentes puntos de vista.

Nicole participa en comunidades virtuales, específicamente en grupos de Facebook, donde ha descubierto libros interesantes y se guía por las reseñas que otros usuarios le dan. También utiliza Wattpad y la aplicación de libros de Apple para leer, además de la plataforma digital de su universidad, que le otorga acceso a una gran variedad de títulos.

Su motivación principal para unirse a estas comunidades es la interacción social y el aprendizaje. Para ella es fundamental la conectividad y la calidad de los comentarios en una plataforma ideal de una librería con comunidades. Prefiere las recomendaciones de personas cercanas ya que tiene confianza en sus opiniones. Le gusta saber las opiniones de todos para entender mejor lo que lee.

Su principal frustración con las comunidades online es cuando la conversación es superficial y no profundiza en la discusión del libro. Para ella, una plataforma ideal debería ser amigable, práctica y fácil de usar, combinando lectura con interacción social de forma fluida.

**Entrevistado N.º 4: Fabrizzio Gionti**

* Edad: 21 años
* Distrito de residencia: Callao
* Estado civil: Soltero
* Ocupación: Estudiante

Acerca de la entrevista:

<p align="center">
  <img src="https://imgur.com/RSSwukT.jpg" alt="12231">
</p>

* Link: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f855_upc_edu_pe/EWZiS1n_89FKgISqOVCjVmUB9Kn699X3OkaJF1K_yNxkpQ?e=6ctcJp>
* Instante en el que inicia: 27:26
* Duración: 5:06

Fabricio Yonti, un estudiante de 21 años del Callao, se presenta como un lector para quien compartir es un pilar fundamental de su experiencia. Para él, compartir sus lecturas no solo es un gusto personal, sino también una forma de motivar a otros a leer y de crear un espacio para conversar sobre intereses comunes.

A pesar de no haber participado en comunidades formales de lectura, su experiencia en el colegio con un club de lectores, donde se intercambiaban libros y se discutían las lecturas del año, le dejó una impresión muy positiva. Su principal motivación para unirse a una comunidad es la interacción social y el valor de compartir conocimientos.

Respecto a la tecnología, Fabricio no utiliza plataformas específicas para reseñas o comunidades literarias. En cambio, su proceso de descubrimiento de libros se inicia en Google, donde busca títulos de su interés y explora diversos enlaces para obtener información. Aunque no usa estas plataformas, su preferencia para obtener recomendaciones es clara: prefiere la opinión de comunidades online antes que las de personas cercanas o algoritmos automatizados, lo que demuestra su apertura a interactuar con desconocidos con intereses similares.

Una plataforma ideal para Fabricio debería tener un buscador inteligente capaz de recomendarle libros basados en sus intereses, evitando el spam o la publicidad excesiva de títulos que no le interesan, un aspecto que le resulta frustrante. Valora que una plataforma combine la lectura con la interacción social, ya que considera que esta combinación amplía su conocimiento de forma significativa. Finalmente, revela que sí ha comprado libros basándose en las sugerencias de una comunidad en línea, específicamente un grupo en Discord, lo que refuerza su confianza en las recomendaciones de este tipo de espacios virtuales.

### 2.2.3. Análisis de entrevistas

En base en las entrevistas recopiladas para cada segmento, se llevó a cabo un análisis, el cual destaca los principales hallazgos y las conclusiones derivadas.

***Segmento objetivo #1: Personas que desean desarrollar y expandir el hábito de la lectura***

**Hallazgos:**

| Característica | Hallazgos | Porcentaje |
| :---- | :---- | :---- |
| Hábito de Lectura | Es esporádico o poco frecuente, a diferencia de su etapa escolar o juventud. | 100% |
| Obstáculo Principal | La falta de tiempo debido a responsabilidades académicas y laborales. | 100% |
| Motivación | La búsqueda de entretenimiento, para "engancharse" en una historia. | 100% |
| Género Preferido | El terror es el género más popular. | 75% |
| Intereses Adicionales | Lectura con fines profesionales o de desarrollo personal  | 50% |
| Factores de Elección | Basan su decisión en recomendaciones o reseñas. | 100% |
| Influencia de Amigos | Confían en las recomendaciones de su círculo cercano. | 50% |
| Influencia de Reseñas | Se guían por la reputación del autor y las reseñas en línea. | 50% |
| Preferencia de Formato | Prefieren los libros físicos por la experiencia táctil y la ausencia de distracciones. | 75% |
| Experiencia Digital | Tienen una experiencia limitada o nula con plataformas digitales. | 100% |
| Expectativas Digitales | Valoran que las plataformas ofrezcan una amplia variedad de títulos. | 100% |

| Insights | Respaldo |
| :---- | :---- |
| La Lectura debe competir con el Ocio Rápido. El principal obstáculo, 100% falta de tiempo, significa que la lectura es una actividad desplazada por el entretenimiento pasivo. Necesitan ser "enganchados" rápidamente. | Se menciona ver series sobre leer. Buscan entretenimiento y trama que sumerja, como géneros de terror y fantasía. |
| Confianza sobre la Exploración. Aunque tienen experiencia digital limitada, confían más en las recomendaciones validadas por otros que en una búsqueda propia. | 100% se basa en recomendaciones o reseñas. 50% confía en amigos. |
| La Comodidad de lo Físico es la Amenaza Digital. El formato físico se valora porque elimina distracciones. Lo digital es útil solo si supera el proceso de compra o búsqueda. | 75% prefiere el formato físico por la ausencia de distracciones. 100% valora la variedad y rapidez en lo digital. |

**Conclusiones:**

Los lectores de este segmento integran la lectura en su vida de forma esporádica para satisfacer una necesidad específica, ya sea de entretenimiento o de aprendizaje. El obstáculo principal para ellos es la falta de tiempo, lo que los lleva a buscar soluciones convenientes y eficientes. Aunque algunos prefieren los libros físicos, no se oponen a lo digital, valorando la practicidad de los audiolibros o la accesibilidad que ofrecen las plataformas digitales cuando la experiencia es cómoda.

Para que una aplicación como Livria sea atractiva para este segmento, debe enfocarse en ofrecer una experiencia sin fricciones. Es crucial que la plataforma facilite la búsqueda y el descubrimiento de libros con un sistema de recomendaciones robusto, que no solo sugiera títulos populares, sino que también tenga una gran variedad en nichos específicos, como la gastronomía o el marketing. Además, es fundamental que la interfaz sea intuitiva y fácil de usar, ya que muchos tienen una experiencia limitada o nula con plataformas digitales.

***Segmento objetivo #2: Personas interesadas en compartir intereses literarios e interactuar con otros lectores***

**Hallazgos:**

| Característica | Hallazgos | Porcentaje |
| :---- | :---- | :---- |
| Importancia de Compartir | Compartir opiniones y lecturas es fundamental. Lo ven como una forma de enriquecer su experiencia y conocer nuevos puntos de vista. | 100% |
| Participación en Comunidades | Participan activamente en comunidades de lectura, ya sea en grupos de amigos, Facebook, Instagram o Discord. | 100% |
| Uso de Plataformas Digitales | El 75% (Roxana, Sofía y Nicole) utiliza plataformas como Instagram, TikTok y Facebook para descubrir libros y conectar. El otro 25% utiliza Google y Discord (Fabricio). | 75% \- 25% |
| Valor Agregado | La principal motivación para unirse a una comunidad es la interacción social. | 100% |
| Punto de Dolor | La principal frustración es la falta de calidad en la conversación o cuando las comunidades son cerradas y no permiten la libre expresión de ideas. | 100% |
| Preferencia de Recomendaciones | Todos prefieren las recomendaciones de personas cercanas o de comunidades online con las que se sienten identificados, ya que les genera confianza. | 100% |
| Plataforma Ideal | Una plataforma ideal debe ser amigable, práctica, fácil de usar y rápida. Roxana, Sofía y Nicole también destacan la importancia de un espacio para recomendar libros y una interacción de calidad. | 100% |
| Obstáculo Principal | La falta de tiempo debido a responsabilidades, mencionada por el 50% de los entrevistados (Roxana y Sofía), limita su frecuencia de lectura. | 50% |

| Insights | Respaldo |
| :---- | :---- |
| El Valor está en la Calidad del Debate, no en la Cantidad de Miembros. La frustración principal no es la dificultad técnica, sino la superficialidad de la conversación en las plataformas existentes. | 100% menciona que la falta de calidad en la conversación o el ambiente cerrado es su principal punto de dolor. |
| El acto de compartir es un motor de lectura y descubrimiento, no una actividad posterior. | 100% encuentra fundamental compartir opiniones. |
| La Confianza en la Recomendación impulsa la Compra | 100% prefiere recomendaciones de personas cercanas o comunidades online identificadas. |

**Conclusiones:**

Los entrevistados de este segmento se definen como "Lectores Sociales", que ven la lectura como una actividad compartida. Su principal motor no es simplemente la lectura, sino la experiencia de compartir y conectar que esta genera. Para ellos, el acto de leer no es una actividad solitaria, sino una oportunidad para debatir, aprender y conocer a personas con intereses similares.

Las plataformas digitales tienen un gran potencial para este segmento si logran crear un ecosistema social robusto y de calidad. Los hallazgos muestran que una solución exitosa debe priorizar la interacción genuina y profunda, ofreciendo un diseño que facilite la conversación y la conexión entre usuarios. El éxito no se medirá solo por el catálogo de libros, sino por la calidad de la comunidad y la fluidez de la experiencia social que ofrezca.

## 2.3. Needfinding

### 2.3.1. User Personas

En esta sección, se presentan las fichas de User Persona, un artefacto clave para visualizar y comprender a nuestros usuarios a un nivel más profundo. Su elaboración se basa en el análisis de las entrevistas realizadas a los dos segmentos de lectores identificados. Se han tomado en cuenta características esenciales como la falta de tiempo para leer, la importancia de las recomendaciones de personas cercanas, la preferencia por formatos digitales o audiolibros que ofrecen conveniencia, y la búsqueda de una experiencia fluida y sin distracciones. Estos perfiles nos permiten humanizar los datos recolectados y guiarán el diseño de Livria para asegurar que sus funcionalidades resuelvan las necesidades y puntos de dolor de sus futuros usuarios de manera efectiva.

**Segmento objetivo \#1: Lectores en Desarrollo**
<p align="center">
  <img src="https://imgur.com/OiQmVr3.jpg" alt="12231">
</p>

**Segmento objetivo \#2: Lectores Comunitarios**
<p align="center">
  <img src="https://imgur.com/4fsp9KP.jpg" alt="12231">
</p>

### 2.3.2. User Task Matrix

| Tarea                                                     | Yoel Ramírez |              | Lucia Carnero |              |
|-----------------------------------------------------------|--------------|--------------|---------------|--------------|
|                                                           | Frecuencia   | Importancia  | Frecuencia    | Importancia  |
| Buscar libros para estudio o interés personal             | Con frecuencia | Alta        | Con frecuencia | Alta         |
| Usar el algoritmo de recomendación                        | Con frecuencia | Alta        | A veces        | Media        |
| Unirse a comunidades con intereses similares              | A veces        | Media       | Con frecuencia | Alta         |
| Leer libros en formato digital                            | Con frecuencia | Alta        | Con frecuencia | Alta         |
| Guardar libros o marcar como “pendientes”                 | A veces        | Media       | Con frecuencia | Media        |
| Buscar comunidades                                        | A veces        | Baja        | Con frecuencia | Alta         |
| Compartir publicaciones en las comunidades                | Rara vez       | Baja        | Con frecuencia | Alta         |
| Comentar las publicaciones                                | Rara vez       | Baja        | Con frecuencia | Alta         |
| Pedir libros con envío rápido                             | A veces        | Media       | A veces        | Alta         |
| Publicar y consultar reseñas de libros                    | Con frecuencia | Media       | Con frecuencia | Alta         |
| Realizar búsquedas de libros con filtros                  | Con frecuencia | Alta        | Con frecuencia | Media        |
| Asignar libros como favoritos                              | Con frecuencia | Media       | Con frecuencia | Alta         |

### 2.3.3. User Journey Mapping

En esta sección se presentan los User Journey Maps, diseñados para visualizar y comprender el recorrido de nuestros usuarios en su estado actual, sin la existencia de Livria. Estos diagramas ilustran el "end-to-end journey" de cada uno de los arquetipos de User Persona elaborados, abarcando desde el momento en que un usuario siente la necesidad de leer, hasta el cierre de su experiencia.

A través de estos mapas, se identifican las etapas cruciales del proceso, las acciones que realizan los usuarios, sus pensamientos, emociones y, lo más importante, los puntos de dolor y las oportunidades que la situación actual presenta. Al vincular cada mapa con su User Persona correspondiente, se busca evidenciar de manera clara cómo las frustraciones de cada arquetipo, como la dificultad para encontrar libros relevantes, la falta de tiempo o la desconexión social, son el motor para la creación de Livria. Estos recorridos As-Is nos servirán de base para diseñar una experiencia futura (To-Be) que sea fluida, atractiva y que resuelva de manera efectiva las necesidades de nuestros usuarios.

**Segmento objetivo \#1: Lectores en Desarrollo**
*User Journey Map del Segmento 1*

<p align="center">
  <img src="https://imgur.com/RZ4Ylha.jpg" alt="12231">
</p>

**Segmento objetivo \#2: Lectores Comunitarios**
*User Journey Map del Segmento 2*

<p align="center">
  <img src="https://imgur.com/Fue9yto.jpg" alt="12231">
</p>

Para mejor visualización de los User Journey Maps de Livria, acceder al siguiente link:
https://drive.google.com/drive/folders/14E_HWaeTiKD7pzQmV_kdxLkU8VU8cxag?usp=sharing

### 2.3.4. Empathy Mapping

Para la elaboración de los Empathy Maps, el equipo siguió una metodología centrada en el usuario, basada en la recopilación de datos cualitativos obtenidos a través de entrevistas, encuestas, observación directa y análisis de comportamiento digital. Cada mapa fue diseñado teniendo en cuenta un User Persona específico, con el objetivo de capturar lo que el usuario piensa, siente, dice y hace en relación con la plataforma. Posteriormente, se identificaron los principales miedos, frustraciones, necesidades y motivaciones que influyen en su experiencia. Esta herramienta permitió generar una visión empática que guía la toma de decisiones de diseño y desarrollo, asegurando que cada funcionalidad responda realmente a las expectativas y preocupaciones del usuario.

**Segmento objetivo \#1: Lectores en Desarrollo**

*Empathy Map del Segmento 1*

<p align="center">
  <img src="https://imgur.com/KEwYBZO.jpg" alt="12231">
</p>

**Segmento objetivo \#2: Lectores Comunitarios**

*Empathy Map del Segmento 2*

<p align="center">
  <img src="https://imgur.com/LhuwaSw.jpg" alt="12231">
</p>

### 2.3.5. As-is Scenario Mapping

**Segmento objetivo \#1: Lectores en Desarrollo**
<p align="center">
  <img src="https://imgur.com/5hXADbH.jpg" alt="As-is Segmento 1">
</p>


**Segmento objetivo \#2: Lectores Comunitarios**
<p align="center">
  <img src="https://imgur.com/zJC6wCh.jpg" alt="As-is Segmento 2">
</p>

## 2.4. Ubiquitous Language

| Término (Inglés)           | Definición   |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Casual reader              | Persona que lee ocasionalmente por interés o  entretenimiento, sin una hábito fijo de lectura.  |
| Amateur reader             | Persona con un hábito de lectura más constante, que busca libros según sus intereses y disfruta compartir su experiencia lectora.  |
| Young university student   | Usuario que cursa estudios superiores y busca libros relacionados con sus trabajos o proyectos académicos o materias específicas. |
| Recommendations            | Sugerencias personalizadas de libros según el perfil, intereses, historial de lectura o área académica que busca el usuario.  |
| Reader community           | Sección donde los usuarios interactúan, comparten opiniones, participan en retos y descubren libros en común.   |
| Search for books           | Herramienta que permite encontrar libros mediante filtros avanzados como autor, editorial, género, formato y disponibilidad. |
| Book formats               | Tipos de presentación de un libro:  digital(eBook), audiolibro o físico.  |
| Save books                 | Función que permite marcar libros para revisarlos después o recibir notificaciones sobre su disponibilidad. |
| Reviews                    | Comentarios, calificaciones y valoraciones que los usuarios de la comunidad dejan sobre libros que han leído, para guiar o recomendar a otros lectores. |
| Audiobook                  | Un libro narrado en formato de audio, que permite a los usuarios escuchar el contenido en vez de leerlo. |
| Digital books              | Versión electrónica o digital de un libro que puede leerse desde múltiples dispositivos. |
| Physical books             | Libro impreso en papel, disponible para compra en formato tradicional.|

---

# Capítulo III: Requirements Specification

En esta sección se consolidan los requisitos del producto digital a partir del análisis detallado de la información obtenida durante las fases de investigación y mapeo de experiencia del usuario. El objetivo es traducir los hallazgos en especificaciones claras, priorizadas y alineadas con las necesidades reales de los usuarios y los objetivos del negocio. Mediante el uso To-be Scenario Mapping, User Stories, el Impact Map y el Product Backlog, se organiza una visión completa del producto que orienta al equipo de desarrollo en la construcción de soluciones útiles, centradas en el usuario y técnicamente factibles. Esta especificación constituye el punto de partida para la planificación, el diseño y la implementación del producto.

## 3.1. To-Be Scenario Mapping

**Segmento objetivo \#1: Lectores en Desarrollo**
<p align="center">
  <img src="https://imgur.com/SjlSkw1.jpg" alt="To-Be Segmento 1">
</p>


**Segmento objetivo \#2: Lectores Comunitarios**
<p align="center">
  <img src="https://imgur.com/7FY3Hdd.jpg" alt="To-Be Segmento 2">
</p>

## 3.2. User Stories

Las User Stories permiten traducir la visión del producto en necesidades concretas de los lectores y de la comunidad que se busca construir. Cada historia refleja, desde la perspectiva del usuario, las funcionalidades que harán posible explorar, adquirir y disfrutar libros dentro de la plataforma. De esta manera, se transforman los objetivos de Livria en requisitos claros y accionables para el equipo de desarrollo. Estas historias no solo sirven como una guía práctica para priorizar y organizar el trabajo en el Product Backlog, sino que también garantizan que cada funcionalidad esté alineada con la propuesta de valor de Livria.

| Campo | Valor |
|---|---|
| **Story ID** | US01 |
| **User** | Visitante de Landing Page |
| **Priority** | 1 – Must Have |
| **Epic** | EP01: Landing Page |
| **Title** | Presentar Servicios de Livria |
| **Description** | Como visitante, quiero ver información relevante sobre las funcionalidades principales que ofrece Livria, para conocer las características únicas de la aplicación. |
| **Acceptance Criteria – Escenario 1: Presentación de servicios** 
Dado que el visitante accede a la landing page, **Cuando** requiere entender las funcionalidades principales que ofrece Livria, **Entonces** el sistema debe mostrar una sección que describa claramente los servicios ofrecidos. |
| **Acceptance Criteria – Escenario 2: Accesibilidad a información de servicios** 
Dado que el visitante se encuentra navegando en la landing page, **Cuando** desea acceder a la información sobre los servicios de Livria, **Entonces** el sistema debe permitir llegar a dicha información desde cualquier sección de la página. |
| **Acceptance Criteria – Escenario 3: Contenido mínimo de la sección de servicios** 
Dado que el sistema presenta la sección de servicios, **Cuando** el visitante revisa dicha sección, **Entonces** esta debe incluir como mínimo una descripción de las funcionalidades principales y su valor diferencial. |

| Campo | Valor |
|---|---|
| **Story ID** | US02 |
| **User** | Visitante de Landing Page |
| **Priority** | 2 – Should Have |
| **Epic** | EP01: Landing Page |
| **Title** | Acceder a la sección “Sobre Nosotros” desde la landing page |
| **Description** | Como visitante, quiero acceder fácilmente a la sección “Sobre Nosotros”, para conocer la trayectoria de los creadores de Livria, comprender en qué consiste la plataforma y descubrir las funcionalidades que ofrece. |
| **Acceptance Criteria – Escenario 1: Disponibilidad de sección “Sobre Nosotros”** 
Dado que el visitante accede a la landing page, **Cuando** busca conocer información sobre Livria y sus creadores, **Entonces** el sistema debe mostrar una sección que describa el propósito, origen y propuesta de valor de la plataforma. |
| **Acceptance Criteria – Escenario 2: Accesibilidad a la sección “Sobre Nosotros”** 
Dado que el visitante se encuentra navegando en la landing page, **Cuando** desea acceder a la sección “Sobre Nosotros”, **Entonces** el sistema debe permitir llegar a dicha sección desde cualquier parte de la página. |

| Campo | Valor |
|---|---|
| **Story ID** | US03 |
| **User** | Visitante de Landing Page |
| **Priority** | 2 – Should Have |
| **Epic** | EP01: Landing Page |
| **Title** | Cambiar de idioma en la Landing Page |
| **Description** | Como visitante, quiero navegar por la plataforma en mi idioma preferido, para comprender fácilmente el contenido de presentación de Livria. |
| **Acceptance Criteria – Escenario 1: Activación del idioma español** 
Dado que el sistema está presentando el contenido en inglés, **Cuando** el sistema recibe la solicitud del usuario para cambiar el idioma a español (ES), **Entonces** el sistema debe cargar y mostrar todo el contenido localizado en español. |
| **Acceptance Criteria – Escenario 2: Activación del idioma inglés** 
Dado que el sistema está presentando el contenido en español, **Cuando** el sistema recibe la solicitud del usuario para cambiar el idioma a inglés (EN), **Entonces** el sistema debe cargar y mostrar todo el contenido localizado en inglés. |

| Campo | Valor |
|---|---|
| **Story ID** | US04 |
| **User** | Visitante de Landing Page |
| **Priority** | 2 – Should Have |
| **Epic** | EP01: Landing Page |
| **Title** | Visualizar la sección “Home” en la landing page |
| **Description** | Como visitante, quiero leer un resumen sobre qué es Livria en el inicio de la página, para entender rápidamente qué producto me ofrece |
| **Acceptance Criteria – Escenario 1: Presentación inicial del contenido de Livria** 
Dado que el visitante accede a la plataforma por primera vez, **Cuando** el sistema carga la Landing Page, **Entonces** el sistema debe presentar el punto de entrada principal de la información, **Y** esta sección debe contener el resumen informativo sobre la oferta de Livria. |
| **Acceptance Criteria – Escenario 2: Retorno al punto de entrada principal** 
Dado que el visitante se encuentra en cualquier otra sección de la Landing Page, **Cuando** el sistema recibe la solicitud de navegación hacia el inicio, **Entonces** el sistema debe presentar el contenido del inicio de forma inmediata. |

| Campo | Valor |
|---|---|
| **Story ID** | US05 |
| **User** | Visitante de Landing Page |
| **Priority** | 2 – Should Have |
| **Epic** | EP01: Landing Page |
| **Title** | Acceder a la sección “Contáctanos” desde la landing page |
| **Description** | Como visitante, quiero identificar fácilmente la sección “Contáctanos”, para poder establecer comunicación en caso de necesitar información adicional sobre la plataforma o tener interés en colaborar con el equipo de Livria. |
| **Acceptance Criteria – Escenario 1: Disponibilidad de la sección de contacto** 
Dado que el visitante se encuentra navegando la plataforma, **Cuando** el sistema carga la Landing Page, **Entonces** la sección "Contáctanos" debe estar disponible para la visualización del usuario, **Y** esta sección debe contener la información necesaria para establecer comunicación con el equipo de Livria. |
| **Acceptance Criteria – Escenario 2: Acceso directo a la sección de contacto** 
Dado que el visitante se encuentra en cualquier otra sección de la Landing Page, **Cuando** el sistema recibe la solicitud de navegación hacia la sección "Contáctanos", **Entonces** el sistema debe presentar dicha sección para su interacción inmediata. |

| Campo | Valor |
|---|---|
| **Story ID** | US06 |
| **User** | Visitante de Landing Page |
| **Priority** | 1 – Must Have |
| **Epic** | EP01: Landing Page |
| **Title** | Navegar de manera simple entre secciones en la Landing Page |
| **Description** | Como visitante, quiero visualizar un encabezado con las secciones de la landing page, para navegar fácil y rápidamente entre ellas. |
| **Acceptance Criteria – Escenario 1: Disponibilidad inmediata del punto de navegación** 
Dado que el visitante accede a la Landing Page, **Cuando** el sistema carga la pantalla inicial, **Entonces** el sistema debe presentar el componente de navegación principal, **Y** este componente debe identificar claramente las secciones disponibles para el usuario. |
| **Acceptance Criteria – Escenario 2: Acceso a las secciones desde la navegación principal** 
Dado que el visitante se encuentra en la Landing Page, **Cuando** el sistema recibe una solicitud de navegación hacia una sección específica, **Entonces** el sistema debe presentar dicha sección sin interrupciones. |
| **Acceptance Criteria – Escenario 3: Permanencia del componente de navegación** 
Dado que el visitante se encuentra navegando a través de las distintas secciones, **Cuando** el contenido de la página es desplazado, **Entonces** el componente de navegación principal debe permanecer visible y fijo, **Y** debe permitir la transición a otras secciones en cualquier momento. |

| Campo | Valor |
|---|---|
| **Story ID** | US07 |
| **User** | Visitante de Landing Page |
| **Priority** | 1 – Must Have |
| **Epic** | EP01: Landing Page |
| **Title** | Ver un diseño atractivo de la landing page |
| **Description** | Como visitante, quiero que la landing page sea visualmente atractiva, para sentirme interesado por Livria y motivado a usar la aplicación que ofrecen. |
| **Acceptance Criteria – Escenario 1: Cumplimiento de los estándares de marca en la carga inicial** 
Dado que el visitante accede a la Landing Page de Livria, **Cuando** el sistema carga todos los elementos de la página, **Entonces** el diseño presentado debe adherirse a la paleta de colores oficial de Livria, **Y** el sistema debe aplicar la tipografía y los estilos de texto definidos en la guía de diseño. |
| **Acceptance Criteria – Escenario 2: Consistencia visual en la navegación** 
Dado que el visitante se encuentra navegando la Landing Page, **Cuando** el sistema presenta el contenido de las distintas secciones, **Entonces** todos los elementos visuales presentados (imágenes, textos y componentes) deben mantener la consistencia de la paleta de colores y la tipografía establecida en los estándares de diseño. |

| Campo | Valor |
|---|---|
| **Story ID** | US08 |
| **User** | Visitante de Landing Page |
| **Priority** | 2 – Should Have |
| **Epic** | EP01: Landing Page |
| **Title** | Redirigir a la descarga de la aplicación móvil |
| **Description** | Como visitante, quiero tener un acceso directo a la tienda para descargar Livria, para empezar a utilizar la aplicación. |
| **Acceptance Criteria – Escenario 1: Inicio de la descarga de la aplicación móvil** 
Dado que el visitante accede al sistema con intención de descargar la aplicación, **Cuando** el sistema recibe la solicitud de descarga, **Entonces** el sistema debe identificar la plataforma del visitante (iOS o Android), **Y** debe iniciar la redirección hacia la tienda de aplicaciones correspondiente para la descarga de Livria. |

| Campo | Valor |
|---|---|
| **Story ID** | US09 |
| **User** | Visitante de Landing Page |
| **Priority** | 3 – Could Have |
| **Epic** | EP01: Landing Page |
| **Title** | Acceder a las redes sociales de Livria |
| **Description** | Como visitante, quiero poder navegar a las redes sociales oficiales de Livria, para mantenerme informado sobre sus novedades y explorar contenido adicional. |
| **Acceptance Criteria – Escenario 1: Redirección a la red social oficial** 
Dado que el sistema presenta las opciones de redes sociales de Livria, **Cuando** el sistema recibe la solicitud del visitante para acceder a una red social específica, **Entonces** el sistema debe abrir el perfil oficial de Livria en la red social seleccionada, **Y** la navegación debe ocurrir en una ventana externa a la plataforma. |

| Campo | Valor |
|---|---|
| **Story ID** | US10 |
| **User** | Visitante de Landing Page |
| **Priority** | 3 – Could Have |
| **Epic** | EP01: Landing Page |
| **Title** | Navegar en el footer de la Landing Page |
| **Description** | Como visitante, quiero visualizar un apartado en el pie de página con las secciones de la landing page, para retornar a cualquiera de ellas. |
| **Acceptance Criteria – Escenario 1: Navegación de retorno desde el pie de página** 
Dado que el sistema presenta la sección de pie de página al usuario, **Cuando** el sistema recibe la solicitud de navegación hacia una sección diferente de la Landing Page, **Entonces** el sistema debe presentar el contenido de la sección solicitada. |
| **Acceptance Criteria – Escenario 2: Retorno rápido al punto de entrada principal** 
Dado que el visitante se encuentra en el pie de página, **Cuando** el sistema recibe la solicitud de navegación hacia el inicio, **Entonces** el sistema debe presentar la sección de inicio inmediatamente. |

| Campo | Valor |
|---|---|
| **Story ID** | US11 |
| **User** | Visitante de Landing Page |
| **Priority** | 3 – Could Have |
| **Epic** | EP01: Landing Page |
| **Title** | Enviar un mensaje al equipo de Livria |
| **Description** | Como visitante, quiero dejar mi información para que el equipo de Bookify - Livria me contacte para resolver una duda o trabajar con ellos. |
| **Acceptance Criteria – Escenario 1: Envío exitoso de consulta** 
Dado que el visitante proporciona la información de contacto requerida, **Cuando** el sistema recibe el consentimiento para el uso de la información, **Entonces** el sistema debe validar los campos requeridos, **Y** debe enviar la consulta al canal de comunicación interna del equipo de Livria. |
| **Acceptance Criteria – Escenario 2: Envío exitoso de postulación laboral** 
Dado que el visitante proporciona la información de contacto requerida y adjunta el archivo de su CV, **Cuando** el sistema recibe el consentimiento para el uso de la información, **Entonces** el sistema debe validar los campos requeridos y el formato del archivo adjunto, **Y** debe enviar la postulación al canal de comunicación interna del equipo de Livria. |
| **Acceptance Criteria – Escenario 3: Rechazo por falta de consentimiento** 
Dado que el visitante intenta enviar la información al equipo de Livria, **Cuando** el sistema no detecta el consentimiento para el envío y procesamiento de la información personal, **Entonces** el sistema debe rechazar el envío del formulario, **Y** debe notificar al visitante la obligatoriedad del consentimiento. |
| **Acceptance Criteria – Escenario 4: Rechazo por información incompleta** 
Dado que el sistema recibe una solicitud de envío del formulario, **Cuando** el sistema detecta que faltan datos en campos marcados como obligatorios, **Entonces** el sistema debe rechazar el envío, **Y** debe señalar al visitante qué campos deben ser completados. |

| Campo | Valor |
|---|---|
| **Story ID** | US12 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP02: Personalización de la experiencia lectora |
| **Title** | Interactuar con recomendaciones según preferencias literarias |
| **Description** | Como lector, quiero recibir recomendaciones personalizadas basadas en mis preferencias literarias para poder descubrir nuevos libros y autores. |
| **Acceptance Criteria – Escenario 1: Generación de recomendaciones iniciales** 
Dado que el usuario accede a la sección de recomendaciones por primera vez, **Cuando** el sistema identifica la falta de datos de preferencia del usuario, **Entonces** el sistema debe generar un conjunto de recomendaciones iniciales basadas en criterios genéricos o aleatorios. |
| **Acceptance Criteria – Escenario 2: Registro de preferencia positiva** 
Dado que el sistema presenta una recomendación de libro al usuario, **Cuando** el sistema recibe la indicación del usuario de interés en el libro, **Entonces** el sistema debe registrar el libro como una preferencia positiva, **Y** el algoritmo de recomendación debe actualizar la calificación de los criterios literarios asociados a ese libro para futuras sugerencias. |
| **Acceptance Criteria – Escenario 3: Registro de preferencia negativa** 
Dado que el sistema presenta una recomendación de libro al usuario, **Cuando** el sistema recibe la indicación del usuario de desinterés en el libro, **Entonces** el sistema debe registrar el libro como una preferencia negativa (ocultar), **Y** el algoritmo de recomendación debe reducir la calificación de los criterios literarios asociados a ese libro para futuras sugerencias. |


| Campo | Valor |
|---|---|
| **Story ID** | US13 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP04: Gestión de cuenta y seguridad de usuario |
| **Title** | Registrar un usuario e iniciar sesión |
| **Description** | Como lector, quiero poder registrarme e iniciar sesión con mis credenciales, para acceder a la plataforma y descubrir nuevos títulos de mi agrado. |
| **Acceptance Criteria – Escenario 1: Creación y autenticación de una cuenta nueva** 
Dado que el sistema recibe una solicitud de registro con información válida y única, **Cuando** el sistema procesa la creación de la nueva cuenta y confirma la aceptación de los términos, **Entonces** el sistema debe almacenar las credenciales de forma segura, **Y** debe autenticar automáticamente al nuevo lector, permitiendo el acceso a la plataforma. |
| **Acceptance Criteria – Escenario 2: Autenticación exitosa de un lector registrado** 
Dado que el lector proporciona credenciales (usuario y contraseña) a la sección de ingreso, **Cuando** el sistema verifica la validez de las credenciales, **Entonces** el sistema debe otorgar acceso al lector, **Y** debe redirigirlo a la sección de contenido principal de la plataforma. |

| Campo | Valor |
|---|---|
| **Story ID** | US14 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP02: Personalización de la experiencia lectora |
| **Title** | Visualizar recomendaciones en la plataforma |
| **Description** | Como lector, quiero observar mis recomendaciones de manera ordenada y atractiva para poder elegir mi siguiente lectura. |
| **Acceptance Criteria – Escenario 1: Presentación y actualización de recomendaciones** 
Dado que el lector accede a la sección de recomendaciones, **Cuando** el sistema procesa la solicitud de recomendación, **Entonces** el sistema debe presentar un conjunto de libros recomendados con información esencial (imagen y título), **Y** el sistema debe poder generar y presentar un nuevo conjunto de recomendaciones cuando se solicite. |
| **Acceptance Criteria – Escenario 2: Acceso directo a los detalles del libro** 
Dado que el sistema presenta las recomendaciones de libros, **Cuando** el sistema recibe una solicitud de acceso a una recomendación específica, **Entonces** el sistema debe presentar la vista completa de los detalles de ese libro con toda su información y opciones disponibles. |

| Campo | Valor |
|---|---|
| **Story ID** | US15 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP04: Gestión de cuenta y seguridad de usuario |
| **Title** | Cerrar sesión |
| **Description** | Como lector, quiero poder cerrar sesión de mi cuenta cuando lo desee, para proteger mi información personal y asegurar la privacidad de mis datos al finalizar el uso de la plataforma. |
| **Acceptance Criteria – Escenario 1: Terminación exitosa de la sesión activa** 
Dado que el lector tiene una sesión activa en el sistema, **Cuando** el sistema recibe la solicitud de cierre de sesión, **Entonces** el sistema debe invalidar la sesión actual de forma segura, **Y** debe eliminar todos los datos de autenticación del dispositivo, **Y** debe presentar la pantalla de ingreso o registro (login) como punto de entrada de la aplicación. |

| Campo | Valor |
|---|---|
| **Story ID** | US16 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP05: Comunidades |
| **Title** | Crear publicaciones en comunidades |
| **Description** | Como lector, quiero poder crear y compartir publicaciones dentro de las comunidades temáticas de la plataforma, para interactuar con otros lectores a través de imágenes. |
| **Acceptance Criteria – Escenario 1: Creación de publicación con contenido gráfico** 
Dado que el lector tiene una sesión activa en una comunidad, **Cuando** el sistema recibe el envío de una publicación que incluye un archivo de imagen, **Entonces** el sistema debe almacenar el contenido de la imagen de forma segura, **Y** debe registrar la publicación como disponible para la visualización y comentarios por parte de otros miembros de la comunidad. |
| **Acceptance Criteria – Escenario 2: Creación de publicación con solo contenido textual** 
Dado que el lector desea compartir una publicación, **Cuando** el sistema recibe el envío de la publicación con solo contenido de texto, **Entonces** el sistema debe registrar y hacer visible la publicación en la comunidad, **Y** debe mostrar correctamente el contenido textual dentro del feed de la comunidad. |

| Campo | Valor |
|---|---|
| **Story ID** | US17 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP05: Comunidades |
| **Title** | Gestionar comunidades |
| **Description** | Como lector, quiero poder crear y unirse a comunidades relacionadas con mis intereses literarios, para conectar con distintos lectores o autores de títulos reconocidos. |
| **Acceptance Criteria – Escenario 1: Creación y registro de una nueva comunidad** 
Dado que el lector proporciona información requerida para la comunidad, **Cuando** el sistema recibe la solicitud de creación de la comunidad, **Entonces** el sistema debe validar y registrar la nueva comunidad, **Y** debe incluirla entre las comunidades disponibles en la plataforma. |
| **Acceptance Criteria – Escenario 2: Asignación de membresía a una comunidad** 
Dado que el lector accede a una comunidad existente, **Cuando** el sistema recibe la solicitud del lector para unirse, **Entonces** el sistema debe registrar al lector como miembro activo de esa comunidad, **Y** debe otorgar al lector acceso a la creación y visualización de contenido dentro de la misma. |

| Campo | Valor |
|---|---|
| **Story ID** | US18 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP06: Compra de libros |
| **Title** | Comprar libros digitales y físicos |
| **Description** | Como lector, quiero poder comprar libros digitales y físicos desde la plataforma para acceder a lecturas nuevas de manera inmediata o recibir ediciones impresas en mi domicilio. |
| **Acceptance Criteria – Escenario 2: Proceso de compra y gestión de libros** 
Dado que el lector tiene ítems en su carrito de compras, **Cuando** el usuario selecciona el botón "Completar compra" **Entonces** el sistema debe procesar y registrar la compra de los ítems seleccionados, **Y** debe confirmar la transacción de pago de manera exitosa.  |

| Campo | Valor |
|---|---|
| **Story ID** | US19 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP06: Compra de libros |
| **Title** | Buscar libros y contenido en la aplicación |
| **Description** | Como lector, quiero utilizar una barra de búsqueda para encontrar libros, autores y comunidades literarias de forma rápida y precisa, para así acceder fácilmente a contenido de interés sin tener que navegar por toda la plataforma. |
| **Acceptance Criteria – Escenario 1: Búsqueda por título o contenido de libro** 
Dado que el lector inicia una consulta de búsqueda, **Cuando** el sistema recibe términos relacionados con el título o contenido de un libro, **Entonces** el sistema debe presentar una lista de resultados que contengan información esencial del libro (título, autor e imagen). |
| **Acceptance Criteria – Escenario 2: Búsqueda por autor específico** 
Dado que el lector desea encontrar obras de un autor en particular, **Cuando** el sistema recibe el nombre de dicho autor en la consulta de búsqueda, **Entonces** el sistema debe mostrar todos los libros de catálogo pertenecientes a ese autor. |

| Campo | Valor |
|---|---|
| **Story ID** | US20 |
| **User** | Usuario de Livria |
| **Priority** | 2 – Should Have |
| **Epic** | EP06: Compra de libros |
| **Title** | Gestionar pago de libros |
| **Description** | Como lector, quiero poder pagar mis libros mediante transacción bancaria, para asegurarme de que mi compra sea rápida y confiable. |
| **Acceptance Criteria – Escenario 1: Procesamiento y confirmación de pago exitoso** 
Dado que el lector ha completado los pasos iniciales de ingreso de información para la compra, **Cuando** el lector selecciona continuar con el proceso de pago, **Entonces** el sistema debe mostrar el número de cuenta interbancaria de Livria para realizar la transferencia, **Y** debe indicar las instrucciones necesarias para completar el pago. |
| **Acceptance Criteria – Escenario 2: Envío de comprobante y validación de pago** 
Dado que el lector ha realizado la transferencia bancaria correspondiente, **Cuando** el lector adjunta la captura del comprobante de pago en la plataforma, **Entonces** el sistema debe registrar el comprobante y asociarlo a la orden de compra, **Y** debe mostrar el mensaje “Pago en verificación. Te llegará un correo con la confirmación”, Y debe mantener la orden en estado pendiente de validación. |

| Campo | Valor |
|---|---|
| **Story ID** | US21 |
| **User** | Usuario de Livria |
| **Priority** | 3 – Could Have |
| **Epic** | EP02: Personalización de la experiencia lectora |
| **Title** | Valorar y dejar reseña de libros |
| **Description** | Como lector, quiero poder valorar y dejar reseñas en los libros que he leído, para compartir mi opinión y ayudar a otros lectores en su elección. |
| **Acceptance Criteria – Escenario 1: Registro de la puntuación de un libro** 
Dado que el lector ha finalizado la lectura de un libro, **Cuando** el sistema recibe una calificación numérica para ese libro (entre 1 y 5), **Entonces** el sistema debe registrar la valoración, **Y** debe actualizar la puntuación promedio general en la ficha de detalles del libro. |
| **Acceptance Criteria – Escenario 2: Envío y publicación de una reseña** 
Dado que el lector desea proporcionar una opinión detallada del libro, **Cuando** el sistema recibe el contenido textual de la reseña, **Entonces** el sistema debe registrar la reseña vinculándola al libro y al lector, **Y** debe hacer que la reseña esté disponible para la visualización pública en la sección de opiniones del libro. |

| Campo | Valor |
|---|---|
| **Story ID** | US22 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP04: Gestión de cuenta y seguridad de usuario |
| **Title** | Gestionar plan de suscripción |
| **Description** | Como lector, quiero poder actualizar mi plan de suscripción, y revertir cambios si me arrepiento, para tener un mayor control sobre mi experiencia en la plataforma. |
| **Acceptance Criteria – Escenario 1: Actualización exitosa a un plan de pago** 
Dado que el lector tiene un plan de suscripción gratuito, **Cuando** el lector adjunta el comprobante de pago para la actualización al nuevo plan, **Entonces** el sistema debe registrar el comprobante y asociarlo a la solicitud de actualización, **Y** debe actualizar el estado de la suscripción del lector a *Activa* una vez validado el pago, **Y** debe habilitar el acceso a las funcionalidades premium (Comunidades).|
| **Acceptance Criteria – Escenario 2: Reversión a la suscripción gratuita** 
Dado que el lector tiene un plan de pago activo, **Cuando** el sistema recibe la solicitud del lector para cambiar al plan gratuito, **Entonces** el sistema debe revertir inmediatamente el estado de la suscripción a *Gratuita*, **Y** debe restringir el acceso a las funcionalidades premium. |

| Campo | Valor |
|---|---|
| **Story ID** | US23 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP07: Accesibilidad y experiencia de uso multiplataforma |
| **Title** | Acceder a la plataforma en cualquier momento |
| **Description** | Como lector, quiero que la plataforma esté disponible en cualquier momento del día, para acceder a mis libros, comunidades y funcionalidades sin importar el lugar o la hora. |
| **Acceptance Criteria – Escenario 1: Disponibilidad y acceso ininterrumpido** 
Dado que el lector intenta acceder al sistema, **Cuando** la solicitud de acceso ocurre en cualquier momento del día (24/7) y desde cualquier ubicación geográfica, **Entonces** el servidor debe responder y permitir la conexión al sistema, **Y** todas las funcionalidades principales deben estar operativas y accesibles sin interrupción. |

| Campo | Valor |
|---|---|
| **Story ID** | US24 |
| **User** | Usuario de Livria |
| **Priority** | 1 – Must Have |
| **Epic** | EP07: Accesibilidad y experiencia de uso multiplataforma |
| **Title** | Navegar la aplicación de forma fácil e intuitiva |
| **Description** | Como lector, quiero una interfaz intuitiva y fácil de usar, para navegar entre libros, comunidades y configuraciones sin complicaciones ni curvas de aprendizaje. |
| **Acceptance Criteria – Escenario 1: Acceso directo a secciones principales** 
Dado que el lector ha iniciado sesión en la plataforma, **Cuando** el sistema presenta el punto de navegación principal, **Entonces** el lector debe poder acceder a las secciones clave (Home, Comunidades, Perfil) utilizando la estructura de navegación de nivel superior. |
| **Acceptance Criteria – Escenario 2: Filtrado y presentación de contenido por categoría** 
Dado que el lector solicita navegar por una categoría específica, **Cuando** el sistema recibe la solicitud de filtrado por esa categoría, **Entonces** el sistema debe presentar únicamente los libros que concuerdan con la categoría seleccionada. |
| **Acceptance Criteria – Escenario 3: Cumplimiento de estándares de accesibilidad visual** 
Dado que el lector interactúa con la plataforma, **Cuando** el sistema presenta cualquier elemento visual (texto, iconos, botones), **Entonces** el contraste de color debe cumplir con el estándar WCAG AA mínimo, **Y** el tamaño del texto debe ser legible en la configuración predeterminada para garantizar la usabilidad. |

| Campo | Valor |
|---|---|
| **Story ID** | US25 |
| **User** | Usuario de Livria |
| **Priority** | 2 – Should Have |
| **Epic** | EP07: Accesibilidad y experiencia de uso multiplataforma |
| **Title** | Usar la aplicación en diferentes dispositivos |
| **Description** | Como lector, quiero ingresar a Livria desde distintos dispositivos, para acceder a mis libros y comunidades desde cualquier lugar y sin perder mi progreso. |
| **Acceptance Criteria – Escenario 1: Portabilidad y consistencia entre plataformas** 
Dado que el lector accede a la plataforma desde diferentes sistemas operativos (Android, iOS), **Cuando** el sistema presenta el contenido y las funcionalidades, **Entonces** la plataforma debe ser completamente funcional y adaptable a la resolución de cualquier dispositivo compatible, **Y** todos los datos del lector (biblioteca, progreso, suscripción) deben estar sincronizados y accesibles de forma consistente. |

| Campo | Valor |
|---|---|
| **Story ID** | US26 |
| **User** | Usuario de Livria |
| **Priority** | 3 – Could Have |
| **Epic** | EP06: Compra de libros |
| **Title** | Filtrar por atributos del libro |
| **Description** | Como lector, quiero filtrar los libros según subcategorías, orden de precio o título, formato e idioma para encontrar más fácilmente el contenido que me interesa. |
| **Acceptance Criteria – Escenario 1: Aplicación de ordenamiento por criterios** 
Dado que el lector está visualizando un listado de libros, **Cuando** el sistema recibe la solicitud de ordenamiento por un criterio específico (ej: precio ascendente o título), **Entonces** el sistema debe presentar la lista de libros reordenada según el criterio seleccionado. |
| **Acceptance Criteria – Escenario 2: Aplicación de filtro por atributo** 
Dado que el lector desea refinar la búsqueda, **Cuando** el sistema recibe la selección de un atributo de filtro (ej: idioma o formato), **Entonces** el sistema debe mostrar únicamente los libros que coincidan con el atributo seleccionado. |
| **Acceptance Criteria – Escenario 3: Restablecimiento de filtros y orden** 
Dado que el lector ha aplicado uno o más filtros y criterios de orden, **Cuando** el sistema recibe la solicitud de restablecer la selección de filtros, **Entonces** el sistema debe eliminar todos los filtros y criterios de orden activos, **Y** debe mostrar la lista de libros en su estado predeterminado inicial. |

| Campo | Valor |
|---|---|
| **Story ID** | TS01 |
| **User** | Developer |
| **Priority** | 1 – Must Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Acceder rápido a las secciones del sistema desde la pantalla principal |
| **Description** | Como developer, quiero tener acceso rápido a las principales secciones del sistema, para poder acceder a la gestión libros, pedidos, inventarios, estadísticas y configuraciones de manera rápida. |
| **Acceptance Criteria – Escenario 1: Acceso a la gestión de libros** 
Dado que el desarrollador está autenticado y en el la pantalla principal de la app, **Cuando** el sistema recibe la solicitud de navegación a la sección de libros, **Entonces** el sistema debe presentar la vista de gestión y catálogo de libros. |
| **Acceptance Criteria – Escenario 2: Acceso a la gestión de pedidos** 
Dado que el desarrollador está autenticado y en la pantalla principal de la app, **Cuando** el sistema recibe la solicitud de navegación a la sección de pedidos, **Entonces** el sistema debe presentar la vista de seguimiento y gestión de órdenes. |
| **Acceptance Criteria – Escenario 3: Acceso a la gestión de inventario** 
Dado que el desarrollador está autenticado y en la pantalla principal de la app, **Cuando** el sistema recibe la solicitud de navegación a la sección de inventarios, **Entonces** el sistema debe presentar la vista de control de stock y almacén. |
| **Acceptance Criteria – Escenario 4: Acceso a las estadísticas** 
Dado que el desarrollador está autenticado y en la pantalla principal de la app, **Cuando** el sistema recibe la solicitud de navegación a la sección de estadísticas, **Entonces** el sistema debe presentar la vista de métricas y rendimiento del sistema. |
| **Acceptance Criteria – Escenario 5: Acceso a la configuración** 
Dado que el desarrollador está autenticado y en la pantalla principal de la app, **Cuando** el sistema recibe la solicitud de navegación a la sección de configuraciones, **Entonces** el sistema debe presentar la vista de ajustes globales del sistema. |

| Campo | Valor |
|---|---|
| **Story ID** | TS02 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Visualizar estadísticas de libros |
| **Description** | Como developer, quiero ver estadísticas relevantes sobre los libros, para poder tomar decisiones informadas sobre los libros más populares, más vendidos y otros datos clave del inventario. |
| **Acceptance Criteria – Escenario 1: Presentación de métricas de catálogo** 
Dado que el desarrollador está en la sección de gestión de libros, **Cuando** el sistema procesa la solicitud de visualización de estadísticas, **Entonces** el sistema debe calcular y mostrar el número total de libros registrados, **Y** debe mostrar el número total de géneros distintos registrados en el sistema. |
| **Acceptance Criteria – Escenario 2: Presentación de métricas financieras** 
Dado que el desarrollador requiere datos financieros agregados, **Cuando** el sistema procesa las estadísticas, **Entonces** el sistema debe calcular y mostrar el precio promedio de venta de todos los libros del catálogo. |
| **Acceptance Criteria – Escenario 3: Presentación de métricas de inventario** 
Dado que el desarrollador necesita información sobre el stock, **Cuando** el sistema procesa las estadísticas, **Entonces** el sistema debe calcular y mostrar el número total de unidades de libros disponibles para la venta (en stock). |

| Campo | Valor |
|---|---|
| **Story ID** | TS03 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Buscar libros como administrador |
| **Description** | Como developer, quiero poder buscar libros de la colección utilizando diversos filtros, para encontrar fácilmente uno o más libros en específico. |
| **Acceptance Criteria – Escenario 1: Búsqueda por término específico (título o autor)** 
Dado que el desarrollador está en la sección de gestión de libros, **Cuando** el sistema recibe una consulta de búsqueda que incluye términos de título o autor, **Entonces** el sistema debe presentar una lista de resultados que coincidan con los términos ingresados. |
| **Acceptance Criteria – Escenario 2: Aplicación de filtros por categoría y atributo** 
Dado que el desarrollador refina la búsqueda, **Cuando** el sistema recibe la selección de un filtro por género o por idioma, **Entonces** el sistema debe limitar y presentar la lista de libros que cumplen con ambos criterios. |
| **Acceptance Criteria – Escenario 3: Ordenamiento de los resultados del catálogo** 
Dado que el desarrollador requiere una visualización organizada, **Cuando** el sistema recibe la selección de un criterio de ordenamiento (ej: por precio o por fecha de publicación), **Entonces** el sistema debe reordenar la lista de libros según el criterio seleccionado. |

| Campo | Valor |
|---|---|
| **Story ID** | TS04 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Visualizar detalles completos de un libro |
| **Description** | Como developer, quiero ver la información completa de un libro, para poder tomar decisiones informadas sobre la gestión de mis productos. |
| **Acceptance Criteria – Escenario 1: Presentación de la información esencial del libro** 
Dado que el desarrollador está en la sección de gestión de libros, **Cuando** el sistema presenta el listado de la colección, **Entonces** el sistema debe mostrar la información esencial de cada libro. |
| **Acceptance Criteria – Escenario 2: Acceso a la vista de detalles de gestión** 
Dado que el desarrollador solicita acceder a la información extendida de un libro, **Cuando** el sistema recibe la solicitud para la vista de detalles, **Entonces** el sistema debe presentar la información completa del producto, incluyendo la sinopsis y los costos financieros (precio de compra y de venta). |

| Campo | Valor |
|---|---|
| **Story ID** | TS05 |
| **User** | Developer |
| **Priority** | 3 – Could Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Visualizar estadísticas y análisis de órdenes |
| **Description** | Como developer, quiero ver estadísticas clave sobre todas las órdenes, para poder realizar un análisis completo y tomar decisiones informadas sobre las ventas. |
| **Acceptance Criteria – Escenario 1: Presentación de métricas financieras de alto nivel** 
Dado que el desarrollador está en la sección de gestión de órdenes, **Cuando** el sistema procesa la solicitud de estadísticas, **Entonces** el sistema debe calcular y mostrar el número total de órdenes registradas en la plataforma, **Y** debe calcular y mostrar el valor total de las ganancias generadas por esas órdenes. |
| **Acceptance Criteria – Escenario 2: Presentación de métricas de estado de órdenes** 
Dado que el desarrollador requiere un resumen del flujo de trabajo, **Cuando** el sistema procesa las estadísticas, **Entonces** el sistema debe calcular y mostrar el número total de órdenes que están pendientes (en espera de procesamiento o envío), **Y** debe calcular y mostrar el número total de órdenes que han sido marcadas como completadas. |
| **Acceptance Criteria – Escenario 3: Presentación de métricas de valor promedio** 
Dado que el desarrollador necesita analizar el comportamiento del cliente, **Cuando** el sistema procesa las estadísticas, **Entonces** el sistema debe calcular y mostrar el valor promedio de las órdenes realizadas en la plataforma. |

| Campo | Valor |
|---|---|
| **Story ID** | TS06 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Buscar y filtrar de órdenes |
| **Description** | Como developer, quiero poder buscar órdenes por ID de pedido o por el nombre del cliente, y poder filtrar de distintas formas, para encontrar fácilmente las órdenes que me interesan. |
| **Acceptance Criteria – Escenario 1: Búsqueda por identificador o por cliente** 
Dado que el desarrollador está en la sección de gestión de órdenes, **Cuando** el sistema recibe una consulta de búsqueda que incluye un ID de pedido o el nombre de un cliente, **Entonces** el sistema debe presentar las órdenes que coinciden con el identificador o que están asociadas al cliente ingresado. |
| **Acceptance Criteria – Escenario 2: Visualización de estado vacío** 
Dado que el desarrollador (o administrador) realiza una búsqueda de órdenes, Cuando el sistema no encuentra ningún registro que coincida con los criterios ingresados (o la base de datos está vacía), Entonces el sistema debe mostrar un mensaje claro indicando que no se encontraron órdenes. |

| Campo | Valor |
|---|---|
| **Story ID** | TS07 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Visualizar una tabla con detalles de las órdenes |
| **Description** | Como developer, quiero que el sistema me muestre una tabla con detalles generales de las órdenes, para gestionar las órdenes de manera eficiente. |
| **Acceptance Criteria – Escenario 1: Presentación estructurada de los detalles de las órdenes** 
Dado que el desarrollador está en la sección de gestión de órdenes, **Cuando** el sistema carga la vista de listado de órdenes, **Entonces** el sistema debe presentar la información de cada orden de manera estructurada, **Y** la estructura debe incluir todos los atributos esenciales de cada orden para la gestión (ej: ID de la orden, fecha, cliente asociado, valor total y estado). |

| Campo | Valor |
|---|---|
| **Story ID** | TS08 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Buscar y filtrar libros en el Inventario |
| **Description** | Como developer, quiero tener una barra de búsqueda y filtros en la sección "Book Collection" del inventario, para poder buscar fácilmente un libro específico dentro del inventario. |
| **Acceptance Criteria – Escenario 1: Búsqueda por término dentro del inventario** 
Dado que el desarrollador está en la sección de gestión de inventario, **Cuando** el sistema recibe una consulta de búsqueda, **Entonces** el sistema debe presentar únicamente los libros del inventario que coinciden con el término ingresado. |
| **Acceptance Criteria – Escenario 2: Aplicación de filtro por categoría y atributo** 
Dado que el desarrollador refina la búsqueda, **Cuando** el sistema recibe la selección de un filtro por género o por idioma, **Entonces** el sistema debe mostrar la lista de libros que cumplen con el criterio seleccionado. |

| Campo | Valor |
|---|---|
| **Story ID** | TS09 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Visualizar libros en el inventario |
| **Description** | Como developer, quiero ver una tabla que contenga los detalles de cada libro, como su portada, título, autor, etc., para gestionar fácilmente el inventario de libros. |
| **Acceptance Criteria – Escenario 1: Presentación estructurada de los detalles de inventario** 
Dado que el desarrollador está en la sección de gestión de inventario, **Cuando** el sistema carga la vista del inventario, **Entonces** el sistema debe presentar de forma estructurada los detalles de cada libro, incluyendo el título, autor, género, idioma, stock actual y el precio de compra. |
| **Acceptance Criteria – Escenario 2: Procesamiento de aumento de stock** 
Dado que el desarrollador solicita aumentar las unidades disponibles de un libro, **Cuando** el sistema recibe la cantidad de nuevas unidades a agregar, **Entonces** el sistema debe validar que la cantidad sea un número entero positivo, **Y** debe calcular el costo total de la adquisición (precio de compra * cantidad), **Y** debe actualizar el stock del libro con la nueva cantidad. |

| Campo | Valor |
|---|---|
| **Story ID** | TS10 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Añadir un libro al inventario |
| **Description** | Como developer, quiero agregar un libro nuevo al inventario de Livria, para ampliar el catálogo y aumentar las ventas. |
| **Acceptance Criteria – Escenario 1: Disponibilidad de la función de registro de libro** 
Dado que el desarrollador está en la sección de gestión de inventario, **Cuando** el sistema recibe la solicitud de registro de un nuevo producto, **Entonces** el sistema debe presentar la interfaz para la entrada de toda la información requerida del libro. |
| **Acceptance Criteria – Escenario 2: Procesamiento y registro exitoso de un nuevo libro** 
Dado que el desarrollador proporciona toda la información esencial del libro (título, género, stock inicial, precios, etc.), **Cuando** el sistema recibe la solicitud de alta del nuevo libro, **Entonces** el sistema debe validar la integridad y unicidad de la información, **Y** debe registrar el nuevo libro en la base de datos, **Y** debe reflejar el nuevo producto en el listado visible de la colección del inventario. |

| Campo | Valor |
|---|---|
| **Story ID** | TS11 |
| **User** | Developer |
| **Priority** | 2 – Should Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Visualizar estadísticas de negocio |
| **Description** | Como developer, quiero ver gráficos sobre la gestión del capital y de las ventas para poder manejar mejor las compras de nuevos libros y supervisar las ventas. |
| **Acceptance Criteria – Escenario 1: Identificación de libros con mayor disponibilidad** | **Dado que** el desarrollador está en la sección de gestión de inventario, **Cuando** el sistema procesa los niveles de existencias, **Entonces** el sistema debe identificar y presentar una lista de los libros que poseen el mayor volumen de unidades en stock físico. |
| **Acceptance Criteria – Escenario 2: Análisis de la distribución de inventario por género** | **Dado que** el desarrollador requiere supervisar la variedad del catálogo, **Cuando** el sistema procesa los datos del almacén, **Entonces** el sistema debe mostrar la distribución cuantitativa (número de ejemplares) de todo el inventario agrupada por cada género literario. |
| **Acceptance Criteria – Escenario 3: Identificación de géneros con mayor impacto financiero** | **Dado que** el desarrollador necesita analizar el rendimiento por categorías, **Cuando** el sistema procesa los datos de ventas históricas, **Entonces** el sistema debe clasificar y mostrar los géneros literarios que han generado el mayor volumen de ingresos económicos totales. |

| Campo | Valor |
|---|---|
| **Story ID** | TS12 |
| **User** | Developer |
| **Priority** | 1 – Must Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Gestionar la configuración del perfil |
| **Description** | Como developer, quiero poder gestionar mi perfil desde una sección de configuración, para poder ver, actualizar mi información personal o cambiar mi contraseña si es necesario. |
| **Acceptance Criteria – Escenario 1: Presentación de la información de la cuenta** 
Dado que el desarrollador accede a la sección de configuración del perfil, **Cuando** el sistema carga la vista, **Entonces** el sistema debe presentar la información personal actual del administrador, incluyendo nombre, nombre de usuario y correo electrónico. |
| **Acceptance Criteria – Escenario 2: Actualización de datos de perfil** 
Dado que el desarrollador modifica la información de su nombre, nombre de usuario o correo electrónico, **Cuando** el sistema recibe la solicitud de guardar los cambios, **Entonces** el sistema debe validar los nuevos datos, **Y** debe actualizar la información del perfil del administrador en la base de datos. |

| Campo | Valor |
|---|---|
| **Story ID** | TS13 |
| **User** | Developer |
| **Priority** | 1 – Must Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Gestionar la configuración de la aplicación |
| **Description** | Como developer, quiero gestionar la configuración de la aplicación desde una sección de configuración, para poder activar o desactivar notificaciones, alertas por correo electrónico, autoguardado de cambios y cambiar la configuración de la cantidad de elementos por página. |
| **Acceptance Criteria – Escenario 1: Control de notificaciones internas** 
Dado que el desarrollador está en la sección de configuración, **Cuando** el sistema recibe la solicitud de cambiar el estado de las notificaciones dentro de la aplicación, **Entonces** el sistema debe almacenar y aplicar el nuevo estado (habilitado/deshabilitado) para todas las notificaciones internas. |
| **Acceptance Criteria – Escenario 2: Control de alertas por correo electrónico** 
Dado que el desarrollador está en la sección de configuración, **Cuando** el sistema recibe la solicitud de cambiar el estado de las alertas enviadas por correo electrónico, **Entonces** el sistema debe almacenar y aplicar el nuevo estado para todas las comunicaciones externas por email. |
| **Acceptance Criteria – Escenario 3: Control de la función de autoguardado** 
Dado que el desarrollador modifica la configuración de guardado automático, **Cuando** el sistema recibe el nuevo estado (activo/inactivo), **Entonces** el sistema debe habilitar o deshabilitar el guardado automático de los cambios en la configuración del administrador. |

| Campo | Valor |
|---|---|
| **Story ID** | TS14 |
| **User** | Developer |
| **Priority** | 1 – Must Have |
| **Epic** | EP08: Vista de administrador |
| **Title** | Registrar una cuenta con control y seguridad. |
| **Description** | Como developer, quiero ingresar a la vista de administrador para poder gestionar operaciones de Livria como el inventario y las ventas. |
| **Acceptance Criteria – Escenario 1: Autenticación exitosa y acceso al panel de administración** 
Dado que el desarrollador proporciona credenciales válidas y con rol de administrador, **Cuando** el sistema recibe la solicitud de ingreso, **Entonces** el sistema debe verificar y autenticar las credenciales correctamente, **Y** debe otorgar acceso al desarrollador a la vista principal del panel de administración. |
| **Acceptance Criteria – Escenario 2: Rechazo por credenciales no válidas** 
Dado que el desarrollador intenta autenticarse, **Cuando** el sistema recibe credenciales que no coinciden con ningún registro de administrador activo, **Entonces** el sistema debe denegar el acceso, **Y** debe notificar que las credenciales son incorrectas. |

| Campo | Valor |
|---|---|
| **Story ID** | SS01 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** | Prototipar el Algoritmo de Recomendación |
| **Description** | Como equipo de desarrollo, quiero investigar y prototipar un algoritmo de recomendación de libros, para que podamos validar la viabilidad técnica y determinar el mejor enfoque para ofrecer sugerencias personalizadas a los usuarios. |
| **Acceptance Criteria – Escenario 1: Investigación de tipos de algoritmos** 
Dado que el equipo de desarrollo necesita entender los diferentes tipos de algoritmos de recomendación, **Cuando** el desarrollador investiga sobre el filtrado colaborativo, basado en contenido y los enfoques híbridos, **Entonces** el desarrollador documenta en un informe compartido los pros y contras de cada modelo para el contexto de Livria. |
| **Acceptance Criteria – Escenario 2: Investigación de tipos de algoritmos** 
Dado que el equipo de desarrollo debe seleccionar la mejor herramienta para el desarrollo, **Cuando** el desarrollador compara bibliotecas de código abierto (como Apache Mahout) con servicios de IA de terceros (como Google Cloud AI Platform), **Entonces** el desarrollador propone una solución recomendada basada en costos, escalabilidad y curva de aprendizaje. |
| **Acceptance Criteria – Escenario 3: Investigación de tipos de algoritmos** 
Dado que el equipo de desarrollo necesita validar el concepto, **Cuando** el desarrollador construye un prototipo simple que toma datos de prueba (ej. calificaciones de usuarios) y genera recomendaciones, **Entonces** el prototipo es funcional y se añade el código de demostración al informe final. |
| **Acceptance Criteria – Escenario 4: Investigación de tipos de algoritmos** 
Dado que el algoritmo requiere datos para funcionar, **Cuando** el desarrollador identifica qué datos de usuario son esenciales para el sistema, **Entonces** el desarrollador lista estos campos para su inclusión en la base de datos del proyecto. |

| Campo | Valor |
|---|---|
| **Story ID** | SS02 |
| **User** | Equipo de desarrollo |
| **Priority** | 2 – Should Have |
| **Epic** | E09: Investigación y Prototipado |
| **Title** | Investigar la Estructura de Comunidades |
| **Description** | Como equipo de desarrollo, quiero investigar las tecnologías y la arquitectura para la sección de comunidad de Livria, para que podamos asegurar un sistema escalable y seguro que gestione las publicaciones y comentarios. |
| **Acceptance Criteria – Escenario 1: Evaluación de arquitecturas de comunidad** 
Dado que la comunidad es una funcionalidad central de Livria, **Cuando** el desarrollador investiga y evalúa diferentes soluciones (ej. APIs REST propias, Firebase Firestore o plataformas de terceros), **Entonces** el desarrollador propone una arquitectura clara que detalle cómo se manejará el contenido generado por los usuarios. |
| **Acceptance Criteria – Escenario 2: Identificación de cuellos de botella** 
Dado que el sistema debe manejar un alto volumen de interacciones, **Cuando** el desarrollador identifica los posibles cuellos de botella de rendimiento y escalabilidad (ej. carga de múltiples reseñas en una página), **Entonces** el desarrollador propone posibles soluciones de optimización, como la paginación o el almacenamiento en caché. |

## 3.3. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
|---------|---------------|--------|-------------|--------------------------|
| 1 | SS02 | Investigación de Estructura de Comunidades | Como equipo de desarrollo, quiero investigar las tecnologías y arquitectura de comunidades, para asegurar un sistema escalable y seguro. | 3 |
| 2 | SS01 | Prototipado de Algoritmo de Recomendación | Como equipo de desarrollo, quiero prototipar un algoritmo de recomendación, para validar su viabilidad técnica. | 5 |
| 6 | US18 | Comprar libros digitales y físicos | Como lector, quiero comprar libros digitales y físicos, para acceder a contenido inmediato o recibir libros en casa. | 8 |
| 7 | US14 | Visualizar recomendaciones en la plataforma | Como lector, quiero ver recomendaciones organizadas, para elegir mi próxima lectura. | 2 |
| 8 | US12 | Interactuar con recomendaciones | Como lector, quiero recibir recomendaciones personalizadas, para descubrir nuevos libros. | 3 |
| 9 | US19 | Buscar libros y contenido | Como lector, quiero buscar libros y autores fácilmente, para acceder rápido al contenido. | 2 |
| 10 | US01 | Presentación de servicios de Livria | Como visitante, quiero ver información de los servicios, para conocer la plataforma. | 1 |
| 11 | US17 | Gestión de comunidades | Como lector, quiero crear y unirme a comunidades, para interactuar con otros lectores. | 5 |
| 12 | US20 | Gestionar pago de libros | Como lector, quiero pagar mediante transferencia, para asegurar una compra confiable. | 3 |
| 14 | US16 | Crear publicaciones en comunidades | Como lector, quiero compartir publicaciones, para expresar ideas y contenido. | 2 |
| 15 | US13 | Registro e inicio de sesión | Como lector, quiero registrarme e iniciar sesión, para acceder a la plataforma. | 3 |
| 17 | US22 | Gestionar plan de suscripción | Como lector, quiero gestionar mi suscripción, para controlar mi experiencia. | 3 |
| 19 | US07 | Diseño atractivo de Landing Page | Como visitante, quiero una página atractiva, para sentir interés en usar Livria. | 1 |
| 20 | US21 | Valoración y reseñas de libros | Como lector, quiero valorar libros, para compartir opiniones. | 3 |
| 21 | US15 | Cierre de sesión | Como lector, quiero cerrar sesión, para proteger mi información. | 1 |
| 22 | US26 | Filtro por atributos del libro | Como lector, quiero filtrar libros, para encontrar contenido relevante. | 2 |
| 23 | US06 | Navegación simple en Landing Page | Como visitante, quiero navegar fácilmente, para explorar la página. | 1 |
| 24 | TS10 | Añadir libro al inventario | Como developer, quiero añadir libros, para ampliar el catálogo. | 3 |
| 25 | TS03 | Búsqueda de libros (admin) | Como developer, quiero buscar libros, para gestionarlos fácilmente. | 1 |
| 26 | TS09 | Visualizar inventario | Como developer, quiero ver el inventario, para gestionar libros. | 1 |
| 27 | TS04 | Ver detalles de libros | Como developer, quiero ver información completa, para tomar decisiones. | 1 |
| 28 | TS01 | Acceso rápido a secciones | Como developer, quiero acceder rápido a módulos, para gestionar el sistema. | 1 |
| 29 | TS02 | Estadísticas de libros | Como developer, quiero ver estadísticas, para tomar decisiones informadas. | 2 |
| 30 | TS05 | Estadísticas de órdenes | Como developer, quiero analizar órdenes, para evaluar ventas. | 3 |
| 31 | TS08 | Filtrado de libros en inventario | Como developer, quiero filtrar libros, para encontrarlos fácilmente. | 2 |
| 32 | TS06 | Buscar y filtrar de órdenes | Como developer, quiero buscar órdenes, para gestionarlas. | 2 |
| 33 | TS07 | Visualizar una tabla con detalles de las órdenes | Como developer, quiero ver órdenes en tabla, para analizarlas. | 1 |
| 34 | TS11 | Visualizar estadísticas de negocio | Como developer, quiero ver métricas, para mejorar decisiones. | 2 |
| 35 | US25 | Uso en múltiples dispositivos | Como lector, quiero usar la app en distintos dispositivos, para acceder desde cualquier lugar. | 5 |
| 36 | TS12 | Configuración de perfil | Como developer, quiero gestionar mi perfil, para actualizar datos. | 2 |
| 37 | TS13 | Configuración de aplicación | Como developer, quiero configurar la app, para personalizar su funcionamiento. | 2 |
| 38 | US23 | Acceso en cualquier momento | Como lector, quiero acceder 24/7, para usar la plataforma sin restricciones. | 2 |
| 39 | US24 | Navegación intuitiva | Como lector, quiero una interfaz fácil, para usar la app sin complicaciones. | 3 |
| 40 | US08 | Descargar app móvil | Como visitante, quiero descargar la app, para comenzar a usarla. | 1 |
| 41 | US03 | Cambio de idioma | Como visitante, quiero cambiar idioma, para entender mejor el contenido. | 2 |
| 42 | US05 | Sección Contáctanos | Como visitante, quiero contactar al equipo, para resolver dudas. | 1 |
| 43 | US02 | Sección Sobre Nosotros | Como visitante, quiero conocer la empresa, para entender su propósito. | 1 |
| 44 | US04 | Sección Home | Como visitante, quiero ver resumen inicial, para entender la plataforma. | 1 |
| 45 | US09 | Redes sociales | Como visitante, quiero acceder a redes, para ver contenido adicional. | 1 |
| 46 | US11 | Formulario de contacto | Como visitante, quiero enviar mensajes, para comunicarme con el equipo. | 2 |
| 47 | US10 | Footer de Landing Page | Como visitante, quiero usar el footer, para navegar rápidamente. | 1 |
| 48 | TS14 | Registro seguro administrador | Como developer, quiero acceder al panel admin, para gestionar el sistema. | 3 |

Evidencias de la implementación del Product Backlog en Jira:

<p align="center">
  <img src="https://imgur.com/XY8Yqyw.jpg" alt="12231">
</p>
<p align="center">
  <img src="https://imgur.com/rzug1N7.jpg" alt="12231">
</p>

## 3.4. Impact Mapping

**Business Goal 1: Aumentar el crecimiento inicial y adopción de Livria**

Objetivo SMART: Alcanzar 50,000 descargas de la aplicación en los primeros seis meses posteriores al lanzamiento oficial, para establecer una base de usuarios sólida que valide la demanda del mercado y el modelo de negocio.

<p align="center">
  <img src="https://imgur.com/meN3bY8.jpg" alt="12231">
</p>

**Business Goal 2: Fomento de compra de libros**

Objetivo SMART: Lograr que el 25% de los usuarios activos mensuales realicen al menos una compra de libro en un periodo de 3 meses, para generar un flujo de ingresos constante que asegure la rentabilidad de la operación.

<p align="center">
  <img src="https://imgur.com/BfE5rBc.jpg" alt="12231">
</p>

**Business Goal 3: Construcción de la comunidad de Livria**

Objetivo SMART: Conseguir que el 30% de los usuarios activos participen en al menos una actividad de la comunidad en los primeros 6 meses, para validar que la plataforma está logrando su objetivo de conectar a los lectores.

<p align="center">
  <img src="https://imgur.com/t87vZOy.jpg" alt="12231">
</p>

---

# Capítulo IV: Product Design

## 4.1. Style Guidelines

Livria busca transformar la manera en que los lectores encuentran nuevas lecturas y en que los aficionados desarrollan el hábito lector. Para ello, funciona como una tienda virtual con recursos interactivos que brindan una experiencia atractiva y accesible para todas las personas. Además de facilitar la compra de libros físicos y digitales, Livria promueve una comunidad literaria activa, motivando a lectores de todas las edades a reconectarse con la lectura de manera significativa.

Esta sección presenta una Guía de Estilo integral y estructurada, diseñada para unificar todos los elementos visuales y de diseño que componen la plataforma Livria. El propósito es establecer una identidad de marca coherente que refleje su misión: transformar el acceso a los libros e incentivar el hábito lector en la era digital. Al organizar meticulosamente recursos gráficos clave como tipografías, paletas de colores y otros componentes visuales, la plataforma garantiza una consistencia en el diseño. Esto no solo simplifica la navegación y potencia una experiencia de usuario clara y funcional, sino que también refuerza los valores de Livria como un espacio moderno, accesible y atractivo para la comunidad literaria.

### 4.1.1. General Style Guidelines

El diseño de Livria se sustenta en una Guía de Estilo integral y estructurada, cuya finalidad es proyectar una identidad de marca coherente que refleje nuestros valores de fomento de la lectura y accesibilidad digital. Esta sección define los pilares visuales y comunicacionales de la plataforma, abordando desde el Branding, con su estética cálida, moderna y cercana, hasta la selección de Tipografía y Paleta de Colores, y las directrices de Spacing. 

Todas estas decisiones de diseño se basan en el principio de claridad funcional y cohesión, garantizando que cada interacción sea intuitiva y esté alineada con el espíritu inclusivo y transformador de Livria.

**Branding y Logotipo**

El Branding de Livria busca reflejar sus valores fundamentales: el fomento de la lectura, la accesibilidad y la construcción de comunidad, proyectando una estética cálida, moderna y cercana. El Logotipo se compone de un ícono gráfico y el nombre "LIVRIA". El ícono representa tres libros apilados en colores vibrantes de la paleta principal (Anaranjado, Ámbar y Azul), simbolizando la diversidad del catálogo y el espíritu dinámico de la plataforma. La sencillez y claridad del logo aseguran su versatilidad y reconocimiento en cualquier contexto digital, reforzando la imagen de Livria como un portal moderno y acogedor para los lectores.

<p align="center">
  <img src="https://i.imgur.com/KmTiPgz.png" alt="12171">
</p>


**Paleta de Colores (Colors)**

La paleta de colores de Livria se ha seleccionado estratégicamente para inspirar confianza, energía y serenidad. Se divide en colores principales, utilizados para acciones clave y elementos estructurales, y colores secundarios, para fondos neutros y acentos sutiles:

* Paleta Principal:  
  * Anaranjado (`#FF5C00`, RGB 255, 92, 0): Color primario de acción, usado para Call-to-Action (CTA) y elementos que requieren máxima atención, representando energía y entusiasmo.  
  * Ámbar (`#FEB913`, RGB 254, 185, 19): Acento secundario que aporta calidez y optimismo, ideal para destacar beneficios o información relevante.  
  * Azul (`#2364A0`, RGB 35, 100, 160): Color estructural que transmite confianza y estabilidad, utilizado para barras de navegación y fondos que requieren solidez.  
* Paleta Secundaria:  
  * Amarillo Claro (`#FFD150`, RGB 255, 209, 80).  
  * Azul Marino (`#063A5D`, RGB 6, 58, 93): Usado para el texto principal y asegurar una alta legibilidad.  
  * Gris Claro (`#F4F5F7`, RGB 244, 245, 247): Utilizado para fondos neutros y un diseño limpio.  
  * Cian Suave (`#A8DBDE`, RGB 168, 219, 222).

<p align="center">
  <img src="https://i.imgur.com/7MnGt7n.png" alt="12171">
</p>

**Tipografía (Typography)**

La selección tipográfica prioriza la legibilidad y la claridad jerárquica en todos los dispositivos.

* Para Logo y Títulos: Se utiliza la fuente Asap Condensed. Su estilo proporciona una estructura visual fuerte e impactante, ideal para encabezados y títulos de alto nivel, alineándose con el dinamismo del branding.  
* Para Texto Regular (Cuerpo): Se emplea la familia tipográfica Alexandria en sus cuatro pesos (Light, Regular, Medium y Bold). Esta elección garantiza una excelente legibilidad en bloques de texto largos y permite una jerarquía de información sutil pero efectiva mediante variaciones de peso.

<p align="center">
  <img src="https://i.imgur.com/3lb5HZb.png" alt="12171">
</p>

**Iconografía (Iconography)**

La iconografía de Livria está diseñada para ser simple, clara y escalable, facilitando la comprensión de las funcionalidades de forma rápida y visual.

* Estilo: Los iconos son de línea delgada (outline), lo que mantiene el diseño moderno y limpio.  
* Tamaño Sugerido: Se establece un tamaño original de 24 píxeles para asegurar la nitidez y el correcto espaciado en la interfaz.  
* Propósito: El set incluye íconos comunes de e-commerce (carrito, ubicación, pago), gestión (configuración, editar, eliminar) y comunidad (corazón/like, comentario, compartir), garantizando una cobertura completa de las interacciones del usuario en Livria.

**Espaciado (Spacing)**

Aunque no se proporciona una escala de espaciado explícita, los principios de diseño de Livria se rigen por la modularidad y la consistencia para asegurar una interfaz organizada y funcional:

* Principio de Base: Se sugiere el uso de una escala de 8 puntos (8px, 16px, 24px, 32px, etc.) para definir márgenes, paddings y separación entre componentes. Esto garantiza que todos los elementos de la interfaz se alineen de manera armónica, independientemente del dispositivo.  
* Legibilidad y Agrupación: El espaciado se utiliza para agrupar visualmente elementos relacionados (como los campos de un formulario o los detalles de una reseña) y para asegurar un espacio adecuado en torno al texto y a los elementos interactivos, mejorando la experiencia táctil y de lectura.

**Tono de Comunicación y Lenguaje Aplicado**

El Tono de Comunicación de Livria es fundamental para establecer una conexión emocional y duradera con los usuarios. Se define como Cálido, Motivador y Accesible, buscando ser un acompañante empático y cercano para el lector, independientemente de su experiencia. Se utiliza un estilo Entusiasta y Alentador para inyectar emoción en la exploración de historias, mientras que la Cercanía se mantiene para generar confianza. La plataforma siempre promueve un ambiente Inspirador, motivando a los usuarios a sentirse parte de una comunidad literaria viva y activa.

En cuanto al Lenguaje Aplicado, se prioriza la Claridad y la Comprensión Directa, evitando tecnicismos o estructuras gramaticales complejas, lo que garantiza que el contenido sea accesible para usuarios de todas las edades y niveles de lectura. El estilo se mantiene Amigable (Casual), y se recurre a una narrativa accesible o ejemplos concretos cuando es apropiado, facilitando la identificación del usuario con los mensajes. Este enfoque comunicativo está diseñado para crear una experiencia acogedora, inspiradora y auténtica, alineada con los valores de Livria: fomentar el hábito lector y construir una comunidad conectada a través de los libros.

## 4.2. Information Architecture

La arquitectura de información es fundamental para plantear la manera en que se organizarán los diferentes componentes de Livria, de modo que el usuario pueda interactuar y adaptarse a ellos de manera intuitiva. La buena organización de la información se debe priorizar para retener la atención del usuario e incentivar el uso constante de la aplicación.

### 4.2.1. Organization Systems

Los diagramas presentados a continuación están organizados de manera jerárquica y en categorías para ilustrar las relaciones entre los componentes de manera visual. Estos sistemas de organización de información contribuyen a una navegación más intuitiva para los usuarios, lo que mejorará su experiencia de uso.

**Landing Page**

<p align="center">
  <img src="https://i.imgur.com/8HVgxyz.jpeg" alt="12171">
</p>

**Admin Mobile Application**

<p align="center">
  <img src="https://i.imgur.com/OLJoj7k.jpeg" alt="12171">
</p>

**Client Mobile Application**

<p align="center">
  <img src="https://i.imgur.com/OLJoj7k.jpeg" alt="12171">
</p>


**Screen Organization**

<p align="center">
  <img src="https://i.imgur.com/odIUF9H.jpeg" alt="12171">
</p>

### 4.2.2. Labeling Systems

La interfaz de Livria ha sido diseñada de manera eficiente y organizada, ofreciéndole al cliente una experiencia de uso dinámica que le permitirá encontrar una ruta rápida hacia la información que quiere consultar o las herramientas que quiere utilizar sin complicaciones. Para lograr esto, nuestro equipo ha propuesto un diseño que emplea etiquetas concisas y efectivas, favoreciendo una experiencia intuitiva. A continuación, se dará una descripción detallada de aquellas que se encuentran en nuestro proyecto.

**Landing Page**

<p align="center">
  <img src="https://i.imgur.com/oliE50k.png" alt="12171">
</p>

Al ingresar a la plataforma, el usuario se encontrará primero con el encabezado, en esta sección de la pantalla, encontrará las etiquetas “HOME”, “SERVICES”, “ABOUT US”, “CONTACT US”, “ES/EN”:

* HOME: Esta etiqueta provee un acceso rápido a la página principal de la Landing Page, el usuario puede acceder a esta fácilmente desde cualquier sección del sitio web.  
* SERVICES: Esta etiqueta sirve como acceso directo a la página de “Servicios”, que contiene descripciones de los diferentes servicios que ofrece la plataforma.  
* ABOUT US: Esta etiqueta sirve para brindar una ruta al usuario a la página de “Nosotros”, donde se encontrarán dos párrafos introductorios de la startup (Bookify) y el proyecto (Livria).  
* CONTACT US: Esta etiqueta tiene la función de acceso directo a la página de “Contacto”, en la que se encontrará un formulario de contacto que el usuario puede utilizar para enviar comentarios o  
* ES/EN: Esta etiqueta servirá para alternar la vista del sitio web, dando la opción al usuario de visualizarla en español (ES) o inglés (EN), dependiendo de sus necesidades.

**Admin Mobile Application**

Para la aplicación de Administrador se tiene dos barras de menú con sus labels respectivos que permiten al usuario navegar fácilmente entre las secciones.

<p align="center">
  <img src="https://i.imgur.com/36Gumf1.png" alt="12171">
</p>

El encabezado es la primera barra de menú de la aplicación de administración, la cual funciona como un Panel de Control de Estado y Navegación Rápida. Visualmente, utiliza el color Azul Marino para transmitir profesionalismo y seguridad. Se compone de tres elementos críticos para la gestión:

* LOGO: Ubicado a la izquierda, representa la identidad de Livria Management y sirve como punto de acceso rápido a la pantalla de Home.  
* MÉTRICA FINANCIERA: En el centro se muestra la métrica Capital (o un indicador financiero principal). Este valor se presenta resaltado en color Ámbar (\#FEB913), garantizando que el administrador tenga visibilidad inmediata sobre la salud económica del negocio en cualquier momento.  
* CONFIGURACIÓN: El ícono de engranaje (Settings) a la derecha proporciona un acceso directo a las opciones de configuración del sistema y del perfil del administrador.

<p align="center">
  <img src="https://i.imgur.com/yHJDrGL.png" alt="12171">
</p>

Este menú inferior sirve como el principal Sistema de Etiquetado y Navegación Global para la aplicación de administración, permitiendo al usuario acceder directamente a las áreas críticas de gestión sin importar en qué parte del sistema se encuentre.

El sistema de etiquetado utiliza una combinación de iconos visuales de línea delgada y texto claro para representar las funciones operativas:

* HOME: Representado por el ícono de una casa, etiqueta la pantalla de inicio o dashboard de gestión, que sirve como punto central de información.  
* BOOKS: Etiqueta el módulo de Gestión de Catálogo, permitiendo al administrador ver y modificar los títulos disponibles.  
* ORDERS: Representado por el ícono de carrito de compras, etiqueta la sección de Gestión de Pedidos, crucial para rastrear y actualizar el estado de las transacciones de los clientes.  
* INVENTORY: Representado por el ícono de un portapapeles, etiqueta el módulo de Gestión de Stock/Inventario, permitiendo el control de las existencias físicas y el reabastecimiento.  
* STATS: Etiqueta el módulo de Estadísticas/Analíticas, proporcionando métricas de rendimiento y datos de ventas.

**Client Mobile Application**

Al igual que en la aplicación de administrador, en las pantallas de cliente se pueden observar dos barras de menú que sirven como sistemas de etiquetado y de navegación. 

<p align="center">
  <img src="https://i.imgur.com/M4R83Kb.png" alt="12171">
</p>

La barra de menú superior de la aplicación para el Usuario Cliente funciona como un centro de navegación crítica y herramientas de descubrimiento. Utiliza el color Azul Marino en su fondo y Anaranjado (\#FF5C00) para la marca Livria, lo que proporciona un contraste vibrante y distintivo. Se compone de elementos clave de izquierda a derecha:

* LOGO: El logo de Livria se ubica a la izquierda, funcionando como un ancla visual y un acceso rápido a la pantalla de Home o inicio.  
* BÚSQUEDA (Lupa): El ícono de lupa permite al usuario acceder rápidamente a la función de búsqueda directa en el catálogo.  
* RECOMENDACIONES (Foco): El ícono de marcador de libro proporciona acceso instantáneo a la sección de las recomendaciones personalizadas para el usuario.  
* TIENDA (Location Pin): El ícono de pin de ubicación dirige al usuario a la pantalla de Store, donde puede encontrar la dirección física de la librería.  
* CARRITO (Shopping Cart): El ícono de carrito de compras es el call-to-action más importante de la barra, ya que permite al usuario ver y gestionar inmediatamente los artículos seleccionados y proceder a la compra.

<p align="center">
  <img src="https://i.imgur.com/OfRj9i2.png" alt="12171">
</p>

La barra de menú inferior es el Sistema de Navegación Global principal de la aplicación, diseñada para el acceso rápido y constante a las secciones clave. Se presenta en un tono oscuro de Azul Marino para estabilidad y contraste. Este menú utiliza iconografía de línea delgada con texto claro debajo, garantizando la usabilidad táctil:

* HOME: El ícono de casa funciona como el punto central de navegación.  
* CATEGORIES: El ícono de tres líneas horizontales (hamburguesa) dirige a la lista de categorías y géneros.  
* COMMUNITIES: El ícono de personas enfoca al usuario en el aspecto social y de interacción de la plataforma.  
* NOTIFICATIONS: El ícono de campana alerta al usuario de mensajes y novedades.  
* PROFILE: El ícono de persona da acceso al centro de gestión de la cuenta, settings y la información personal del usuario.

Este diseño asegura que todas las áreas fundamentales de la experiencia (descubrimiento, socialización y gestión personal) estén siempre visibles y sean accesibles con un solo toque, optimizando el flujo de navegación.

### 4.2.3. SEO Tags and Meta Tags

**Landing Page**

*Title*

<p align="center">
  <img src="https://i.imgur.com/ew2WMaj.png" alt="12171">
</p>

En este meta tag, se define el título que tendrá el sitio web del proyecto. El equipo decidió usar el nombre de la startup seguido del nombre del producto para resaltar nuestra autoría sobre la idea, optando por una mayor simplicidad que facilite la lectura por parte del usuario.

*Meta tags*

<p align="center">
  <img src="https://i.imgur.com/ccw5CEp.png" alt="12171">
</p>

El equipo no realizó cambios sobre los meta tags incluídos por defecto dentro del archivo HTML, debido a que no fueron necesarios para el correcto funcionamiento de la página.

*Description*

<p align="center">
  <img src="https://i.imgur.com/NNoNOAS.png" alt="12171">
</p>

El meta tag designado para la descripción del sitio web contiene un breve párrafo introductorio que resume los principales servicios que ofrece la aplicación, con el objetivo de informar rápidamente a los usuarios que no son familiares con su funcionamiento.

*Keywords*

<p align="center">
  <img src="https://i.imgur.com/8i09h1y.png" alt="12171">
</p>

Los meta tags de “Keywords” tienen el propósito de optimizar la búsqueda del sitio web en navegadores al ampliar el número de términos que un usuario puede ingresar en la barra de búsqueda para localizarlo. En el caso de nuestro proyecto, se utilizaron términos relacionados al apartado de compra de libros y la función de comunidad.

*Author*

<p align="center">
  <img src="https://i.imgur.com/nn35LiF.png" alt="12171">
</p>

El meta tag de autor está presente para identificar a los autores del contenido de la Landing Page.

**Admin Mobile App**

*ASO (App Store Optimizaton) elements:*

<p align="center">
  <img src="https://i.imgur.com/J9W9v8o.png" alt="12171">
</p>

La optimización para tiendas de aplicaciones (ASO) de tu aplicación, basándose únicamente en el AndroidManifest.xml que proporcionaste, se centra en los siguientes elementos visibles:

*Título de la Aplicación (App Title/Name)*

Este está definido por el atributo android:label tanto en la etiqueta <application> como en la <activity> principal. En ambos casos, el valor es "Adminlivria". Este es el nombre que los usuarios verán bajo el icono de la aplicación en la pantalla de inicio y en la tienda de aplicaciones. Un título efectivo debe ser memorable y reflejar la función de la aplicación, y "Adminlivria" sugiere un enfoque en administración o gestión.

*Ícono de la aplicación (App Icon)*

El atributo android:icon especifica el recurso **@mipmap/ic_launcher** y android:roundIcon especifica **@mipmap/ic_launcher_round**. Aunque no se muestra el diseño real, este es un elemento crucial de ASO ya que es la primera impresión visual de la aplicación.

### 4.2.4. Searching Systems

En Livria, los Searching Systems fueron diseñados para simplificar la experiencia de búsqueda y mejorar la experiencia del usuario, ayudándolo a localizar los productos que quiere consultar rápidamente y de manera eficiente. Esto nos ayudará a evitar que los clientes se sientan abrumados o tengan problemas para encontrar libros de su interés.

**Admin Mobile Application**

<p align="center">
  <img src="https://i.imgur.com/jEQcGM9.png" alt="12171">
</p>

La tarjeta de Book Collection no solo contiene el título de la sección, sino posee, también, una barra de búsqueda que permite encontrar un libro por su nombre. Además, al hacer clic en el ícono de Filtros, se pueden aplicar ciertos criterios para realizar una búsqueda más acertada.  
Esta tarjeta se encuentra en las pantallas de Book Management y de Inventory para facilitar al administrador la búsqueda de libros en el catálogo de Livria.

<p align="center">
  <img src="https://i.imgur.com/nCX3CG8.png" alt="12171">
</p>

La tarjeta de Orders es casi idéntica a la de Book Collection, pues poseen su respectivo título, la barra de búsqueda y el método de filtrado. La principal diferencia es que la actual tarjeta encuentra órdenes a través de su ID o por el nombre del comprador.

**Client Mobile Application**

<p align="center">
  <img src="https://i.imgur.com/VqADQtC.png" alt="12171">
</p>

La pantalla de búsqueda de Livria está diseñada para ofrecer una experiencia de descubrimiento de catálogo rápida y directa al usuario. Su diseño conciso se enfoca en la eficiencia y la relevancia de los resultados. Posee los siguientes elementos clave:

* Activación de la Búsqueda: El sistema se inicia con un campo de texto claro y prominente etiquetado como "Search by Title or Author" (Buscar por Título o Autor), lo que dirige al usuario a introducir su consulta de forma explícita.  
* Mecanismo de Resultados: Al ingresar un término, el sistema procesa y presenta los RESULTS (Resultados) en formato de tarjeta visual. Cada tarjeta contiene la carátula, el título, el autor y el precio del libro, permitiendo una rápida identificación visual del contenido.  
* Refinamiento de Criterios (Filtros): El sistema incluye un ícono de filtros (representado por barras verticales de diferentes alturas) en la esquina superior derecha de la sección de resultados. Esta funcionalidad es crucial, ya que permite al usuario refinar los resultados obtenidos por la consulta inicial (título o autor) aplicando criterios adicionales, como se ve en el flujo de búsqueda.  
* Integración con Descubrimiento: La selección de cualquiera de los resultados conduce a la Vista Individual del Libro, integrando el sistema de búsqueda directamente con el proceso de evaluación y compra.

En esencia, este sistema es una herramienta de búsqueda de alta fidelidad que soporta tanto la entrada directa de consulta como el refinamiento posterior de los resultados.

<p align="center">
  <img src="https://i.imgur.com/wGss9Py.png" alt="12171">
</p>

La Pantalla de Categorías funciona como un sistema de búsqueda estructurada y de exploración del catálogo, dirigido a los usuarios que desean descubrir contenido por género o tema en lugar de buscar un título específico.

* Exploración Estructurada: El sistema presenta una lista jerárquica de categorías principales (LITERATURE, NON-FICTION, MANGA & COMICS, etc.). El etiquetado claro de las categorías permite al usuario refinar su búsqueda por áreas de interés con un solo toque.  
* Activación de la Búsqueda: La interacción principal es la selección de una categoría, pues el usuario es redirigido a la Vista de Categoría Seleccionada.  
* Resultados y Refinamiento por Categoría: Esta vista muestra todos los libros pertenecientes a la categoría seleccionada. Es crucial notar que esta pantalla incluye el ícono de filtros (barras verticales). Esto permite al usuario refinar los resultados dentro de la categoría por criterios adicionales, completando así el proceso de búsqueda por exploración.

### 4.2.5. Navigation Systems

El diseño de la navegación de Livria se basa en una arquitectura de información clara, utilizando patrones móviles probados para garantizar que tanto los lectores como el personal administrativo puedan acceder a sus flujos de trabajo clave de manera eficiente. Este enfoque dual es crucial para dar soporte a los diferentes *Bounded Contexts* definidos en el sistema.

* Navegación Persistente: La Barra de Pestañas Inferior (Bottom Tabs)

<p align="center">
  <img src="https://i.imgur.com/WiU41Qg.png" alt="12171">
</p>

Este sistema constituye el eje de navegación global de la aplicación para el usuario lector. La Barra de Pestañas Inferior implementa un patrón de Navegación Persistente que asegura el acceso rápido y constante a los módulos de negocio fundamentales, sin que el usuario pierda su contexto actual. Esta barra es esencial para las funcionalidades principales de la aplicación, permitiendo a los usuarios cambiar entre estas secciones de alto nivel de forma instantánea. Su naturaleza constante en la base de la pantalla mejora la eficiencia y la descubribilidad de los módulos centrales de Livria, alineándose directamente con las metas de interacción social y exploración de contenido.

* Navegación Contextual: La Barra Superior (Top Bar)

<p align="center">
  <img src="https://i.imgur.com/KhhqoBO.png" alt="12171">
</p>

La barra superior actúa como un complemento funcional y contextual de la navegación principal, enfocándose en acciones secundarias pero esenciales y en el acceso a la sesión. La Barra Superior complementa la navegación inferior, sirviendo como un portal para funcionalidades contextuales o universales. Ofrece acceso directo a Recomendaciones, al Carrito, etc. Su implementación minimiza el desorden en la barra inferior, reservándola solo para los módulos de más alta prioridad, mientras centraliza las acciones de usuario y compra.

* Navegación Jerárquica y Gestual: El Retorno al Contexto

<p align="center">
  <img src="https://i.imgur.com/W81M9n7.png" alt="12171">
</p>

Este sistema garantiza la fluidez del usuario al moverse de una vista general a una específica y viceversa, utilizando tanto la jerarquía visual como la interacción gestual moderna. Se complementa con la Navegación Gestual de Retorno, permitiendo al usuario deslizar lateralmente de izquierda a derecha para deshacer la última acción de navegación y regresar inmediatamente a la pantalla anterior dentro de la pila. Por ejemplo, al salir de una publicación en Comunidades, el deslizamiento regresa al feed comunitario. Este mecanismo no solo es intuitivo y rápido, sino que también aligera la dependencia del botón físico o de la flecha de retroceso del sistema operativo, mejorando la experiencia de usuario y la percepción de fluidez.

* Navegación Específica: La Funcionalidad de Búsqueda

<p align="center">
  <img src="https://i.imgur.com/UTBcxqJ.png" alt="12171">
</p>

La búsqueda es la ruta más directa para que el usuario acceda a la información deseada, actuando como un atajo crucial a través de los diversos Bounded Contexts. La Navegación por Búsqueda es un sistema crucial y transversal que permite a los usuarios saltar directamente a contenido específico de su interés, evitando la navegación secuencial. Al proveer resultados en tiempo real y categorizados, la búsqueda se convierte en la herramienta de navegación más eficiente para la exploración intencionada, optimizando el tiempo del usuario y reduciendo la fricción para la adquisición de libros.

## 4.3. Landing Page UI Design

La propuesta de diseño para la interfaz de usuario (UI) de la Landing Page de Livria es la culminación visual de la arquitectura de información y el diseño centrado en el usuario. Desde el primer impacto, esta interfaz está diseñada para proyectar una identidad accesible, amigable y culturalmente cercana, alineada con el valor fundamental de promover la lectura y la comunidad. La estructura se organiza en secciones clave —Home, Services, About Us y Contact Us— que garantizan una navegación fluida e intuitiva. Estéticamente, el diseño emplea una jerarquía visual limpia, ilustraciones cálidas, tipografías legibles y un uso estratégico de la paleta de colores para despertar el interés, generar confianza e impulsar al visitante a interactuar con los llamados a la acción, asegurando que la primera impresión sea tanto funcional como emocionalmente atractiva.

### 4.3.1. Landing Page Wireframe

En primer lugar, se observa la pantalla de inicio de la Landing Page de Livria. Esta tiene una descripción sobre qué trata la aplicación móvil que se ofrece y un carrusel de imágenes relacionadas. Asimismo, tiene el header con los accesos a cada sección de la landing page.

<p align="center">
  <img src="https://i.imgur.com/2WHRUgm.png" alt="12171">
</p>

En la sección siguiente aparece la información sobre los servicios de Livria: Variedad de libros, Comunidad de libros, y Recomendaciones. Asimismo, cada tarjeta de información tiene su imagen correspondiente.

<p align="center">
  <img src="https://i.imgur.com/M32uH0X.png" alt="12171">
</p>

La sección que continúa es la de “Sobre Nosotros”, la cual muestra información sobre la startup, Bookify, y la aplicación, Livria. Se visualiza texto importante sobre quiénes somos, así como el logo representativo de cada uno.

<p align="center">
  <img src="https://i.imgur.com/QBeEGEs.png" alt="12171">
</p>

Luego, se llega a la última sección de la landing page, que es “Contáctanos”. En caso que el visitante desee comunicarse con el equipo de Bookify \- Livria, puede dejar su información y motivo de contacto. Además, si desea formar parte de este equipo, puede dejar su CV y aplicar para un puesto disponible.

<p align="center">
  <img src="https://i.imgur.com/gH7FYhn.png" alt="12171">
</p>

A medida que el visitante hizo scroll en la página, se mostraron todas las secciones de la landing page, llegando hasta el pie de página. Este muestra los accesos a las secciones visualizadas anteriormente, así como enlaces a partes legales y de soporte de la plataforma.

<p align="center">
  <img src="https://i.imgur.com/VERprTk.png" alt="12171">
</p>

### 4.3.2. Landing Page Mock-up

Los mockups de la landing page de Livria muestran una mayor fidelización de la interfaz final del sitio, integrando los elementos visuales definidos en la guía de estilo. Esta representación busca validar la propuesta estética y funcional de los wireframes en una experiencia clara y atractiva para el usuario.

La pantalla de inicio del mockup de la landing page presenta el encabezado con las secciones principales del sitio y el bloque introductorio de la propuesta de Livria, ambos con los colores de la paleta. Incluye un carrusel visual con imágenes sobre lectura digital, comunidad lectora y la tienda física de Livria.

<p align="center">
  <img src="https://i.imgur.com/rqNL6wN.png" alt="12171">
</p>

La sección de “Servicios” presenta cada tarjeta de información con un color diferente, así como con una imagen respectiva sobre lo que describe la funcionalidad.

<p align="center">
  <img src="https://i.imgur.com/zl55fT7.png" alt="12171">
</p>

A esta sección, “Sobre Nosotros”, se le agrega color a los bloques que contienen los nombres de la startup y la aplicación, Defontes y Livria, respectivamente.

<p align="center">
  <img src="https://i.imgur.com/97eORXD.png" alt="12171">
</p>

El mockup de la última sección de la landing page, la cual presenta el formulario de contacto, se visualiza con un color principal de la paleta.

<p align="center">
  <img src="https://i.imgur.com/k4kMo0x.png" alt="12171">
</p>

El mockup del pie de página muestra los accesos de Navegación, Legal y Soporte con el color azul, así como los logos de las redes sociales de Livria.

<p align="center">
  <img src="https://i.imgur.com/ScJXwUf.png" alt="12171">
</p>

## 4.4. Mobile Applications UX/UI Design

El diseño UX/UI de las aplicaciones móviles de Livria (tanto para el Usuario Cliente como para el Administrador) se ha abordado bajo la premisa de accesibilidad, rendimiento y optimización táctil. El objetivo principal es trasladar la experiencia de lectura y comunidad a un entorno móvil de forma fluida y nativa, respetando los patrones de diseño de cada sistema operativo. Se ha priorizado la simplicidad en la navegación y la claridad de la información, utilizando grandes zonas de toque, una tipografía legible y un contraste adecuado. Esto asegura que el usuario pueda interactuar con el catálogo, la comunidad y las funcionalidades administrativas de manera eficiente.

### 4.4.1. Mobile Applications Wireframes

Los wireframes de las aplicaciones móviles de Livria (tanto para la versión de cliente como la de administrador) representan la columna vertebral estructural del diseño, priorizando la usabilidad táctil y la eficiencia de navegación en pantallas pequeñas. Esta etapa se enfoca en definir la organización jerárquica del contenido y la disposición óptima de los elementos clave dentro de los patrones de diseño móvil. Al concentrarse únicamente en la estructura y el flujo de tareas sin la distracción de elementos visuales, los wireframes permiten optimizar la experiencia de usuario en movimiento y asegurar que las funcionalidades críticas del sistema sean accesibles y fluidas para el lector y el administrador.

##### **Pantallas de Loggeo** 

La pantalla de Log In es el punto de entrada inicial a la plataforma Livria y está diseñada para gestionar el acceso de todos los tipos de usuarios. Presenta un formulario centralizado para la autenticación estándar con campos para Username y Password, culminando con el botón 'LOG IN'. Debajo de la sección de acceso principal, la pantalla ofrece opciones secundarias vitales: un botón 'REGISTER' que redirige a los nuevos usuarios a la creación de cuenta, y un botón 'ADMIN' que permite a los administradores iniciar sesión con sus credenciales por defecto. Esta disposición asegura que tanto los usuarios regulares como el personal de gestión puedan acceder a sus respectivos flows desde una única interfaz, manteniendo la usabilidad y la seguridad como prioridad.

<p align="center">
  <img src="https://i.imgur.com/5ll4vZV.png" alt="12171">
</p>

La primera pantalla de Register está diseñada para facilitar la incorporación de nuevos usuarios a la plataforma Livria. La interfaz se centra en un formulario claro y conciso que solicita la información esencial para la creación de una cuenta: Email, Password y Confirm Password. El proceso de registro incorpora un paso de cumplimiento legal mediante un checkbox que exige al usuario confirmar que ha leído y acepta la Privacy Policy y los Terms and Conditions de Livria. La acción se consolida con el botón 'CONTINUE'. Adicionalmente, la pantalla mantiene la usabilidad al ofrecer opciones de navegación alternativas, permitiendo a los usuarios ya registrados volver a la pantalla de 'SIGN IN' o a los administradores iniciar sesión mediante el botón 'ADMIN'.

<p align="center">
  <img src="https://i.imgur.com/ZOAwpNh.png" alt="12171">
</p>

La segunda pantalla de Register está dedicada a la personalización del perfil del nuevo usuario, siguiendo el registro inicial de credenciales. El formulario solicita al usuario definir su identidad dentro de la plataforma con campos como Nickname, Username (nombre de usuario único) y la Phrase (una frase o bio de perfil). Adicionalmente, el usuario tiene la opción de personalizar su perfil subiendo una Profile Picture mediante opciones para tomar una foto o seleccionar una de la galería. El proceso de creación de la cuenta se completa con el botón 'REGISTER'. Al igual que en el paso anterior, la pantalla mantiene la usabilidad ofreciendo rutas de escape para usuarios que ya tienen una cuenta ('SIGN IN') o para la autenticación de administradores ('ADMIN').

<p align="center">
  <img src="https://i.imgur.com/28SgVMC.png" alt="12171">
</p>

Por último, la pantalla de Admin Sign In es la interfaz dedicada a la autenticación del personal de gestión de Livria, priorizando la seguridad mediante un proceso de acceso de triple factor. El formulario requiere que el administrador ingrese un Username y Password estándar, pero añade un campo adicional de Security Pin para una verificación de identidad más robusta. El acceso al dashboard se otorga al pulsar el botón 'SIGN IN'. La interfaz también mantiene opciones de navegación para la usabilidad, ofreciendo el botón 'GO BACK' para regresar a la pantalla de inicio de sesión de cliente si se ha accedido por error, y el botón 'ADMIN' que funge como un doble check para confirmar la intención de iniciar sesión como administrador.

<p align="center">
  <img src="https://i.imgur.com/pKOwG9S.png" alt="12171">
</p>

##### **Pantallas de Administrador** 

En primer lugar, la pantalla de Home del Administrador está diseñada como un dashboard de gestión centralizado que prioriza la eficiencia y el acceso rápido a las tareas críticas. Se presenta una interfaz limpia y jerárquica que inmediatamente proporciona una bienvenida personalizada al administrador. En la parte superior se muestra información esencial de negocio, como el Capital actual, que es una métrica clave. El cuerpo de la pantalla está dominado por la sección Quick Actions, que agrupa las funcionalidades principales de manera accesible: Manage Books, Manage Orders, Inventory y Statistics. Finalmente, la sección System Information ofrece datos de soporte, como la versión del sistema y el último inicio de sesión.

<p align="center">
  <img src="https://i.imgur.com/Ps0Yryq.png" alt="12171">
</p>

La pantalla de Books del Administrador combina visualización de métricas y gestión del catálogo. En la parte superior, bajo el título Statistics, se presenta un resumen ejecutivo con tarjetas que muestran datos clave como Total Books, Total Genres, Average Price, Books in Stock y Most Reviewed, proporcionando al administrador una visión rápida del rendimiento del catálogo. La sección inferior, Book Collection, es el corazón de la gestión. Aquí, el administrador puede buscar títulos específicos mediante una barra de búsqueda y ver el listado completo de libros organizado en un formato de tarjeta (card) conciso. Cada tarjeta muestra la portada, el título y el precio, e incluye un botón 'VIEW' que permite acceder a la información detallada del libro, facilitando la navegación rápida y la gestión eficiente del inventario.

<p align="center">
  <img src="https://i.imgur.com/lyz2nul.png" alt="12171">
</p>

Consecutivamente, la pantalla de Detalle del Libro del Administrador, ofrece una vista exhaustiva de la información individual de cada título, accesible mediante el botón "VIEW" desde la pantalla anterior. En la parte superior, se muestra el título completo del libro, junto con etiquetas descriptivas como "JUVENILE" y "EN INGLÉS", que categorizan el contenido. La portada del libro ocupa un lugar central, seguida de los datos financieros clave: el Purchase Price (precio de compra) y el Sale Price (precio de venta), métricas esenciales para la gestión de inventario y la estrategia de precios. Finalmente, la sección Synopsis proporciona un resumen detallado del contenido del libro, lo que permite al administrador obtener una comprensión profunda del producto sin necesidad de fuentes externas. Esta pantalla consolida toda la información relevante para la gestión de cada título.

<p align="center">
  <img src="https://i.imgur.com/6OEO7L5.png" alt="12171">
</p>

La primera pantalla de Orders del Administrador es el centro de control para la gestión y el análisis de las transacciones de Livria. Al igual que otras secciones, comienza con un panel de métricas clave que incluye Total Orders, Total Revenue, Average Order Value, Pending Orders y Completed Orders, proporcionando una visión inmediata del rendimiento financiero y operativo. La sección principal, ORDERS, permite al administrador buscar pedidos mediante un Order ID o el Customer Name. Debajo de la búsqueda, la información se presenta en un formato de tabla concisa, que resume el ORDER CODE, el CUSTOMER, la DATE, el TOTAL de la compra y el STATUS actual (entre "Pending", “In Progress” y “Delivered”). Esta estructura está optimizada para la trazabilidad y el monitoreo eficiente del ciclo de vida de cada pedido.

<p align="center">
  <img src="https://i.imgur.com/bWH9UvG.png" alt="12171">
</p>

La segunda pantalla de Orders, accesible al seleccionar un pedido de la tabla, ofrece una vista detallada de la transacción, organizada en secciones claras para una gestión eficiente. La sección ORDER DETAILS proporciona un resumen del pedido con el Order Code, la Order Date y el Order Status ("Pending" en el ejemplo), junto con el Order Value. A continuación, la sección CUSTOMER INFORMATION presenta datos esenciales del cliente, incluyendo Customer Name, Customer Email, y la información del destinatario (Recipient Name y Recipient Phone). Finalmente, la sección ORDER ITEMS desglosa los productos adquiridos en un formato de tarjeta visual, mostrando cada libro con su título, un breve resumen y precio, e incluye una opción 'VIEW' para verificar la información del ítem. Esta estructura facilita el proceso de verificación y el servicio al cliente, complementado por una sección para UPDATE STATUS que permite avanzar el pedido en su ciclo de vida.

<p align="center">
  <img src="https://i.imgur.com/UAmHp1d.png" alt="12171">
</p>

La primera vista de la sección Inventory del Administrador se centra en la función de agregar nuevos títulos al catálogo de Livria, bajo el título Add to Inventory. Esta pantalla está organizada en un formulario que captura la información esencial de cada libro de manera estructurada. El administrador debe completar campos como Title, Author, Description, y seleccionar el Genre y el Language a través de dropdowns. Adicionalmente, la interfaz permite subir la Cover Image y definir el Stock inicial mediante un selector de cantidad. La navegación se facilita con pestañas superiores que permiten alternar entre esta función (ADD A BOOK) y la visualización del inventario existente (VIEW INVENTORY), garantizando un flujo de trabajo claro para la gestión de existencias.

<p align="center">
  <img src="https://i.imgur.com/XGE8gFq.png" alt="12171">
</p>

La segunda vista de la sección Inventory, accesible mediante la pestaña VIEW INVENTORY, transforma la interfaz en una herramienta de gestión de existencias. La pantalla presenta la Book Collection en un formato de lista de tarjetas, similar a la vista de "Books", pero con un enfoque en la disponibilidad. El administrador puede buscar títulos específicos y, lo más importante, observar el Stock actual (mostrado como 'Stock: 0' en el ejemplo) debajo de cada título. Esta funcionalidad está diseñada para permitir al administrador reaccionar rápidamente a la escasez de existencias, ya que cada tarjeta incluye un prominente botón 'ADD STOCK'. Este botón dirige a una tercera pantalla de libro individual al que se quiere aumentar el stock.

<p align="center">
  <img src="https://i.imgur.com/Bvw1byy.png" alt="12171">
</p>

La tercera y última pantalla de Inventory se enfoca exclusivamente en el proceso de reabastecimiento de existencias para un título específico, siendo accesible al seleccionar 'ADD STOCK' en la vista de inventario. En la parte superior, se muestra la información de identificación del libro, incluyendo el título, las etiquetas de clasificación, los precios (Purchase Price y Sale Price) y el CURRENT STOCK disponible. La función principal reside en la sección de acción, donde el administrador selecciona la QUANTITY a añadir mediante un dropdown y visualiza el TOTAL TO PAY asociado a esa compra de inventario. El proceso se finaliza con el botón 'CONTINUE', lo que indica la transición al flujo de compra o registro de existencias. Esta pantalla consolida la verificación del estado actual del stock con la acción de reabastecimiento, optimizando la gestión de inventario.

<p align="center">
  <img src="https://i.imgur.com/n8IrULn.png" alt="12171">
</p>

La pantalla de Statistics del Administrador es un dashboard analítico que ofrece una visualización de las métricas clave para la toma de decisiones, pues consolida la información de ventas y finanzas, transformando datos en insights visuales para que el administrador pueda monitorear la salud operativa y estratégica de Livria.. Se estructura en tres secciones:

* TOP THREE BEST SELLING BOOKS: Destaca visualmente los tres títulos con mejor rendimiento de ventas mediante tarjetas que muestran la portada y el número de unidades vendidas, permitiendo identificar rápidamente los productos más exitosos.  
* REVENUE ACCORDING THE GENRES: Presenta un gráfico de pastel que desglosa los ingresos totales de Livria según el género literario. Este gráfico es crucial para analizar qué segmentos del catálogo están generando mayor rentabilidad.  
* CAPITAL FLOW AND OPERATIONS: Muestra la dinámica financiera de la plataforma a través de un gráfico de líneas que compara variables clave como las Ganancias por Órdenes y el Costo de Venta (Libros) a lo largo del tiempo.

<p align="center">
  <img src="https://i.imgur.com/MXRwiD4.png" alt="12171">
</p>

La primera vista de la pantalla de Settings del Administrador se enfoca en la gestión del perfil y las preferencias del sistema. La interfaz se presenta de manera clara, con una bienvenida personalizada al administrador. La funcionalidad principal se divide mediante pestañas: PROFILE y APPLICATION. La sección PROFILE INFORMATION muestra un formulario para la modificación de datos sensibles, incluyendo Name, Username, Email y Security Pin. Los campos están diseñados para una edición rápida. En la parte inferior, se encuentran botones clave para la seguridad y la persistencia de los cambios: un botón 'LOG OUT' para cerrar la sesión y un botón 'SAVE CHANGES' para actualizar los datos del perfil, garantizando que el administrador mantenga el control sobre su información y credenciales.

<p align="center">
  <img src="https://i.imgur.com/dBRUNCl.png" alt="12171">
</p>

La segunda vista de la sección Settings del Administrador, accesible mediante la pestaña APPLICATION, se dedica a la gestión de las preferencias del sistema y la comunicación. Esta pantalla permite al administrador configurar el flujo de notificaciones y alertas que recibe. Se presentan toggles binarios de 'YES' / 'NO' para tres opciones clave: Notifications (recibir notificaciones dentro de la aplicación), Email Alerts (recibir alertas a través del correo electrónico), y una configuración para Email (probablemente referida a la automaticidad o guardado de cambios en la configuración de email). Esta interfaz asegura que el administrador pueda personalizar su experiencia y su nivel de exposición a las comunicaciones del sistema. Al igual que en la vista de perfil, incluye los botones 'LOG OUT' y 'SAVE CHANGES' para aplicar las modificaciones o cerrar la sesión.

<p align="center">
  <img src="https://i.imgur.com/pp8KqT0.png" alt="12171">
</p>

##### **Pantallas de Cliente** 

En primer lugar se tiene a la pantalla de inicio de Livria, la cual muestra elementos principales de la aplicación. Se tiene el header, que posee los accesos a las secciones de Búsqueda, Recomendaciones, Tienda, y al Carrito de Compras. Asimismo, hay un carrusel que muestra diferentes banners con información, siendo el principal el de “obtener el Plan Comunidad”. A partir de ello, aparecen las primeras sugerencias de las categorías parte del catálogo de Livria. Finalmente, se encuentra el menú de navegación entre las principales secciones de Livria. 

<p align="center">
  <img src="https://i.imgur.com/0oxdHi4.png" alt="12171">
</p>

La pantalla de Recommendations es el feed personalizado del Usuario Cliente, diseñado para fomentar el descubrimiento de nuevos títulos. La interfaz saluda al usuario con un mensaje amigable y explica que las sugerencias se basan en sus preferencias. El contenido principal presenta los libros recomendados en un formato de tarjetas visuales concisas que muestran la portada, el título, el autor y el precio. El diseño prioriza la acción y la interacción inmediata, permitiendo al usuario marcar su interés con íconos de marcador o eliminar la sugerencia con íconos negativos, lo que refina el algoritmo. Finalmente, la pantalla incluye un botón 'REFRESH' para generar una nueva tanda de recomendaciones, asegurando una experiencia de navegación dinámica y continuamente adaptada a los gustos del lector.

<p align="center">
  <img src="https://i.imgur.com/xeS5EPO.png" alt="12171">
</p>

La pantalla de Categories es una herramienta de navegación esencial diseñada para facilitar la exploración y el descubrimiento del catálogo de libros por parte del Usuario Cliente. Presenta una interfaz limpia y estructurada, organizada como una lista jerárquica bajo el título SEARCH BY CATEGORY. La pantalla enumera las principales clasificaciones de contenido, incluyendo géneros tradicionales como LITERATURE, NON-FICTION y FICTION, junto con segmentos específicos como MANGAS & COMICS, JUVENILE y CHILDREN. Adicionalmente, se destaca una categoría para formatos digitales, E-BOOKS AND AUDIOBOOKS. El diseño prioriza la claridad y la sencillez, permitiendo al usuario navegar rápidamente a través de grandes colecciones de libros y refinar su búsqueda con un solo toque, optimizando el flujo de descubrimiento.

<p align="center">
  <img src="https://i.imgur.com/v4b4j3C.png" alt="12171">
</p>

La pantalla de Category View se presenta al Usuario Cliente después de seleccionar un género o categoría específica desde la pantalla de categorías. Su función principal es mostrar el subconjunto del catálogo que pertenece a esa clasificación. La interfaz organiza los libros en un formato de tarjeta visual de fácil escaneo, donde cada card muestra la portada, el título, el autor y el precio. Además, la pantalla incluye un ícono de filtros/ordenamiento en la esquina superior derecha, lo que permite al usuario refinar aún más los resultados dentro de la categoría seleccionada. Este diseño asegura una transición fluida desde la exploración general a una vista detallada y manejable de los libros relevantes.

<p align="center">
  <img src="https://i.imgur.com/84y4AVX.png" alt="12171">
</p>

La pantalla de Search es la herramienta de exploración directa del Usuario Cliente. Presenta un campo de búsqueda prominente titulado SEARCH BY TITLE OR AUTHOR, que permite al usuario ingresar términos específicos para localizar libros. Debajo de la barra de entrada, los RESULTS se muestran en un formato de tarjeta concisa y visualmente atractivo. Cada tarjeta ofrece una vista previa con la portada, el título, una breve descripción y el precio del libro. La interfaz está optimizada para el refinamiento de la búsqueda, ya que incluye un ícono de filtros/ordenamiento en la sección de resultados. Esto garantiza que el usuario no solo pueda encontrar libros rápidamente, sino también manipular los resultados para optimizar su descubrimiento y su experiencia de compra.

<p align="center">
  <img src="https://i.imgur.com/W7JemgL.png" alt="12171">
</p>

La pantalla de Single Book View es el punto focal para la interacción del Usuario Cliente con un título específico, consolidando la información de compra y reseña. En la parte superior, se muestra de manera prominente el título del libro y etiquetas descriptivas como "JUVENILE" y "EN INGLÉS". El diseño se centra en la portada del libro y en las acciones de interacción clave: el usuario puede marcar el libro con iconos de negativo (no interesado) y marcador (interesado). La zona de compra incluye el precio, un selector de cantidad y el botón 'ADD TO CART'. Debajo de la acción de compra, la sección Synopsis proporciona un resumen detallado del contenido. Finalmente, continúa con el apartado de REVIEWS.

<p align="center">
  <img src="https://i.imgur.com/ks12piQ.png" alt="12171">
</p>

La pantalla de Communities es el punto central para la interacción social del Usuario Cliente, diseñada para fomentar la participación y la creación de grupos de lectura. La interfaz principal muestra un listado de comunidades existentes en un formato de tarjeta visual, donde cada card presenta el nombre de la comunidad y un espacio para su ícono o imagen representativa. La pantalla incluye una barra de búsqueda en la parte superior, permitiendo al usuario buscar comunidades por título. De manera destacada, la acción clave de la sección, 'CREATE +', se encuentra en la esquina superior derecha, facilitando a los usuarios crear y expandir la red de comunidades, reforzando el pilar de construcción de comunidad de Livria.

<p align="center">
  <img src="https://i.imgur.com/bV0CpDQ.png" alt="12171">
</p>

La pantalla de Community View es la interfaz dedicada a la interacción dentro de una comunidad específica, sirviendo como un feed social. En la parte superior, se muestra el par de imágenes representativas (banner y profile picture) de la comunidad con su nombre y una breve descripción, junto con un botón 'JOIN +' que permite al Usuario Cliente unirse al grupo. El foco de la pantalla es la creación y visualización de contenido social. Los usuarios pueden ingresar sus pensamientos en un campo de texto, agregar imágenes y publicar su contenido con el botón 'POST'. Debajo de la zona de publicación, se despliega un feed de las publicaciones existentes, donde cada tarjeta muestra el username del autor y el contenido publicado. Este diseño fomenta activamente la discusión, la compartición de contenido y la construcción de lazos entre los miembros de la comunidad.

<p align="center">
  <img src="https://i.imgur.com/GfGRek9.png" alt="12171">
</p>

La pantalla de Cart es la interfaz dedicada a la gestión de las compras del Usuario Cliente. Presenta un diseño simple y enfocado en la conversión, con un botón 'EMPTY CART' en la parte superior para vaciar rápidamente la cesta. El contenido principal muestra los artículos agregados en un formato de tarjeta conciso, donde cada libro se visualiza junto a un selector de cantidad y un ícono de eliminar para la gestión individual. En la parte inferior de la pantalla, se presenta un resumen financiero con el Subtotal de la compra. Finalmente, el botón 'COMPLETE MY PURCHASE' actúa como el llamado a la acción principal, dirigiendo al usuario al flujo de pago y finalización de la transacción.

<p align="center">
  <img src="https://i.imgur.com/kfNTt0W.png" alt="12171">
</p>

La pantalla de Notifications es la central de mensajes y alertas para el Usuario Cliente. Su diseño es directo y funcional, con el objetivo de gestionar las comunicaciones del sistema. La interfaz incluye un botón 'EMPTY LIST' en la parte superior, que permite al usuario limpiar rápidamente su historial de notificaciones. El contenido se presenta como un listado de tarjetas de mensaje (como "Welcome to Livria!"), donde cada una contiene la alerta o información relevante. Cada notificación incluye la opción de eliminar el mensaje de forma individual, permitiendo al usuario gestionar su bandeja de entrada de manera eficiente y mantener solo las alertas pendientes o relevantes.

<p align="center">
  <img src="https://i.imgur.com/3yO3Sl7.png" alt="12171">
</p>

La pantalla de Store está diseñada para proporcionar al Usuario Cliente información sobre la ubicación física de Livria. Bajo el título OUR STORE y una invitación a visitar la tienda, la interfaz se centra en la geolocalización. La sección principal está dominada por una visualización de mapa que muestra la ubicación exacta de la tienda. Debajo del mapa, el ADDRESS se presenta de forma clara y detallada. Esta pantalla cumple la función de conectar la experiencia de compra en línea con la posibilidad de una visita física, ofreciendo una herramienta de localización directa para el cliente.

<p align="center">
  <img src="https://i.imgur.com/vttBUSF.png" alt="12171">
</p>

La pantalla Submit Order marca el inicio del flujo de pago para el Usuario Cliente, siendo el primer paso tras hacer clic en 'COMPLETE MY PURCHASE' desde el carrito. El título SUBMIT ORDER establece claramente el objetivo de la pantalla. La interfaz está organizada en una barra de progreso visual que guía al usuario a través de los pasos de la compra: Carrito, Información del Cliente, Dirección de Envío y Pago. La vista actual se centra en el PURCHASE SUMMARY, mostrando un resumen financiero conciso que incluye la cantidad de ítems y el Total a pagar. Para mantener el foco y permitir la revisión, un botón 'VIEW ITEMS' permite al usuario verificar los productos. La transición al siguiente paso del proceso se realiza mediante el botón 'CONTINUE'.

<p align="center">
  <img src="https://i.imgur.com/WCI21Mw.png" alt="12171">
</p>

El segundo paso del flujo Submit Order se enfoca en la recolección de los datos del destinatario para la entrega, indicando un progreso claro en la barra superior. La sección principal, RECIPIENT INFORMATION, solicita al Usuario Cliente información esencial para el envío, incluyendo Name, Last Name, Phone Number y Email. Estos campos de formulario son críticos para asegurar que el pedido sea entregado a la persona correcta y que se pueda establecer una comunicación efectiva durante el proceso de delivery. La interfaz mantiene la opción 'VIEW ITEMS' para una revisión rápida de los productos y permite al usuario avanzar al siguiente paso del proceso de compra mediante el botón 'CONTINUE'.

<p align="center">
  <img src="https://i.imgur.com/pwLYYgI.png" alt="12171">
</p>

El tercer y penúltimo paso del flujo Submit Order se enfoca en la selección del método de entrega para el Usuario Cliente. La interfaz guía al usuario mediante dos opciones claras: 'PICK UP IN STORE' (recoger en tienda) y 'HOME DELIVERY' (entrega a domicilio). Al seleccionar 'PICK UP IN STORE', se informa al usuario que la recogida estará disponible a partir de tres días hábiles después de la confirmación del pedido y se proporciona un enlace (click here) para obtener más detalles sobre la ubicación física de la tienda. Esta pantalla asegura que el cliente elija el método de entrega más conveniente antes de avanzar a la fase final del pago, manteniendo la opción 'VIEW ITEMS' para la revisión del carrito y utilizando el botón 'CONTINUE' para proceder.

<p align="center">
  <img src="https://i.imgur.com/sL7JRwG.png" alt="12171">
</p>

La última pantalla del flujo Submit Order se enfoca en los detalles de pago y la confirmación de términos legales antes de completar la compra. La sección PAYMENT DETAILS informa al Usuario Cliente que todos los pagos se procesan a través de Izipay y que la aceptación de los términos redirigirá al usuario a la página de Izipay para realizar el pago. Este paso incluye dos checkboxes obligatorios para el cumplimiento legal: el primero requiere la autorización para el procesamiento de datos personales de acuerdo con la Privacy Policy y Terms and Conditions, y el segundo es opcional para autorizar el procesamiento de datos con fines de promoción comercial. El botón 'CONTINUE' finaliza el flujo en la plataforma, llevando al usuario al sistema de pago externo para completar la transacción.

<p align="center">
  <img src="https://i.imgur.com/Q3I0MFR.png" alt="12171">
</p>

La pantalla de Profile es el centro de gestión de la identidad y las preferencias para el Usuario Cliente. La parte superior muestra la información de la cuenta del usuario, incluyendo el nombre de perfil, username, email, y una breve biografía o frase. Se presenta información clave sobre el estatus de la cuenta mediante pestañas para SUBSCRIPTION y Community Plan. La funcionalidad de gestión principal se organiza en tres pestañas: SETTINGS, MY ORDERS y EDIT BIO. El apartado de SETTINGS permite al usuario configurar sus preferencias de notificación y privacidad mediante toggles; MY ORDERS permite ver las anteriores compras del usuario; y EDIT BIO permite cambiar la información del usuario. Finalmente, la pantalla incluye acciones críticas para el control total de la cuenta: 'DELETE ACCOUNT' y 'LOG OUT', asegurando que el cliente pueda gestionar su privacidad y acceso de forma segura.

<p align="center">
  <img src="https://i.imgur.com/eC3Mkv3.png" alt="12171">
</p>

### 4.4.2. Mobile Applications Wireflow Diagrams

**User Goal para Segmento 1: Lectores en Desarrollo**

Como usuario, quiero visualizar recomendaciones personalizadas según mis preferencias de lectura y quiero determinar si una es de mi agrado o no.

Task Flow:

<p align="center">
  <img src="https://i.imgur.com/At7uFMF.png" alt="12171">
</p>

Wireflow:

<p align="center">
  <img src="https://i.imgur.com/hSyeHP0.jpeg" alt="12171">
</p>

Para poder interactuar con las recomendaciones que brinda Livria a cada usuario, se accede, en primer lugar, a esta sección a través del header de la aplicación móvil. Al presionar el ícono del foco, que vendría a ser “Recomendaciones”, se le redirige al usuario al apartado en el que aparecen sus 6 recomendaciones. Al seleccionar una de ellas, aparece el detalle del libro recomendado. A este, se le puede marcar como interés o desinterés al seleccionar el ícono del bookmark o del negative, respectivamente.

Asimismo, para mejorar las recomendaciones que ofrece Livria, se pueden marcar otros libros. Para ello, desde el inicio de la aplicación —o desde cualquier otra sección— se puede acceder a un libro en específico y marcarle, así como a un libro recomendado, como interés o desinterés al seleccionar el ícono del bookmark o del negative, respectivamente.

**User Goal para Segmento 2: Lectores casuales y aficionados a la lectura**

Como usuario, quiero conectar con otras personas que compartan mis gustos literarios y ver sus opiniones sobre esos temas en específico.

Task Flow:

<p align="center">
  <img src="https://i.imgur.com/xyMBDgg.png" alt="12171">
</p>

Wireflow:

<p align="center">
  <img src="https://i.imgur.com/hPl9I9L.jpeg" alt="12171">
</p>

Para interactuar con otros usuarios sobre temas específicos, se debe seguir una secuencia de pasos. En primer lugar, desde el inicio de Livria —o desde cualquier otra sección— se debe acceder al apartado de Comunidades al presionar su link en el menú inferior. Acto seguido, se mostrarán las variadas comunidades creadas en la aplicación. A partir de ello, el usuario puede elegir entre crear una nueva o unirse a una existente. De elegir la primera opción, deberá completar los campos de información requeridos y, cuando haya creado la comunidad, aparecerá con la información proporcionada. En función a eso, se le permitirá empezar a publicar sobre el tema elegido, así como a los demás usuarios que se unan. En el caso contrario, que se unan a una comunidad existente, se podrá tanto crear una nueva publicación como comentar en una preexistente.

### 4.4.3. Mobile Applications Mock-ups

La etapa de Mockups representa la traducción fiel de la estructura definida en los wireframes a una propuesta visual de alta fidelidad. Utilizando los Style Guidelines de Livria —que incluye la paleta de colores, tipografías y branding—, esta sección ilustra el look and feel final de la plataforma. El objetivo es mostrar al detalle cómo se aplicarán los elementos visuales para generar una interfaz coherente, atractiva y funcional. Los mockups no solo respetan la jerarquía y el flujo de navegación establecidos, sino que también garantizan que la experiencia de usuario (UX) sea intuitiva y esté completamente alineada con el tono cálido y motivador de la marca.

##### **Pantallas de Loggeo**

La pantalla de Log In utiliza una paleta de colores cálida para crear una bienvenida acogedora. El formulario de acceso principal se destaca en un recuadro de color Ámbar (#FEB913), que transmite optimismo, y el botón principal 'LOG IN' utiliza una variación de este color para incentivar la acción. El logo de Livria se exhibe prominentemente en la parte superior. La zona inferior, que contiene las opciones 'REGISTER' y 'ADMIN' (para el acceso de gestión), utiliza el color Cian Suave para diferenciar claramente las rutas secundarias del login principal del cliente. El uso de la tipografía Asap Condensed para el título refuerza la claridad y el dinamismo del branding.

<p align="center">
  <img src="https://i.imgur.com/zxcJUZp.png" alt="12171">
</p>

El primer paso de Registro mantiene la estética cálida y cercana con el fondo Ámbar, utilizando el color Anaranjado (#FF5C00) para el título 'REGISTER' y el botón 'CONTINUE', lo que canaliza la energía hacia la finalización del proceso. La interfaz se enfoca en la recolección de Email y la definición de Password con campos de texto limpios. Visualmente, se destaca la casilla de aceptación de la Privacy Policy y Terms and Conditions, asegurando que el cumplimiento legal sea un paso claro e ineludible. Las opciones secundarias de 'SIGN IN' y 'ADMIN' mantienen el contraste con el Cian Suave en la parte inferior.

<p align="center">
  <img src="https://i.imgur.com/Kbmshqs.png" alt="12171">
</p>

El segundo mockup de Registro se centra en la personalización del perfil, continuando con la paleta ámbar y anaranjada para el foco de acción. Los campos solicitan información personal de la cuenta (Nickname, Username y Phrase) y proporcionan íconos claros para la carga de la Profile Picture (cámara/galería), utilizando la iconografía de línea delgada. El botón 'REGISTER' finaliza el proceso con el color de acción anaranjado. Este diseño, a través de la calidez del color y la tipografía Asap Condensed, refuerza el tono acogedor y motivador de Livria, animando al nuevo usuario a completar su identidad en la comunidad.

<p align="center">
  <img src="https://i.imgur.com/B65Xijt.png" alt="12171">
</p>

La pantalla de Admin Sign In utiliza la misma estructura, pero puede diferenciarse sutilmente en el color del recuadro principal (un amarillo ligeramente más pálido en este mockup, aunque aún cercano al Ámbar). El énfasis visual se pone en la seguridad, requiriendo tres campos de autenticación: Username, Password y el Security Pin. El botón 'SIGN IN' es prominente y utiliza el color de acción. Las opciones secundarias 'GO BACK' y 'ADMIN' reafirman que esta es una ruta de acceso especializada. La aplicación del branding es limpia y directa, priorizando la funcionalidad y la seguridad de acceso a los desarrolladores encargados de la supervisión y administración de la aplicación.

<p align="center">
  <img src="https://i.imgur.com/hpE6HzU.png" alt="12171">
</p>

##### **Pantallas de Administrador**

En primer lugar, la pantalla de Home del Administrador traduce la estructura del wireframe a un dashboard visualmente limpio y profesional, utilizando la paleta de colores de Livria para la jerarquía y el branding. El fondo principal utiliza el color Azul Marino para la barra superior e inferior, transmitiendo estabilidad, mientras que el contenido se presenta en un contenedor de color claro. El título de bienvenida ("Welcome to the Library Management System") utiliza el color Anaranjado (#FF5C00) para ser más llamativo. La sección Quick Actions utiliza iconos de línea clara y botones con el fondo blanco para contrastar con el color de acción, permitiendo un acceso rápido a las funcionalidades clave como Manage Books, Manage Orders e Statistics. Finalmente, la sección System Information utiliza un fondo Ámbar (#FEB913) para diferenciar la información de soporte, manteniendo un diseño enfocado en la eficiencia operativa.

<p align="center">
  <img src="https://i.imgur.com/syXwaub.png" alt="12171">
</p>

La pantalla de Books utiliza una combinación de colores contrastantes para destacar la información crucial. La barra superior y la navegación inferior emplean el Azul Marino, transmitiendo profesionalismo. El título principal, "Livria Management", está en color Anaranjado (#FF5C00), guiando la vista del administrador. Las métricas clave (Total Books, Total Genres) se presentan en tarjetas blancas y limpias, facilitando la lectura rápida. La Book Collection utiliza un fondo blanco, con el título "BOOK COLLECTION" en Ámbar (#FEB913) para diferenciar la sección de catálogo. Cada tarjeta de libro ahora muestra la portada real y el botón 'VIEW' es de color Azul (#2364A0), enfatizando la acción de visualización.

<p align="center">
  <img src="https://i.imgur.com/5J8rXNO.png" alt="12171">
</p>

El mockup de Detalle del Libro se enfoca en presentar la información del título de forma clara. El título del libro (PERCY JACKSON AND THE BATTLE OF THE LABYRINTH) se muestra en color Anaranjado. Los metadatos (JUVENILE, en INGLÉS) y el nombre del autor (RICK RIORDAN) utilizan el color Azul Marino para mantener la legibilidad contra el fondo. Los datos financieros se jerarquizan por color: el PURCHASE PRICE (Precio de Compra) se etiqueta en Anaranjado y el SALE PRICE (Precio de Venta) en Amarillo Claro (#FFD150), destacando la diferencia de valor. La sinopsis se presenta en un recuadro limpio con texto Alexandria Regular, manteniendo la atención en el contenido.

<p align="center">
  <img src="https://i.imgur.com/5XQORm3.png" alt="12171">
</p>

En la pantalla de Orders, el color Anaranjado se usa para el título principal ("Order Management") y para el encabezado de la sección "ORDERS". Las métricas clave son inmediatamente visibles, con los números de Capital en un Ámbar brillante en la barra superior. En la tabla de pedidos, los datos importantes como el ORDER CODE se resaltan en un tono más claro de Azul Marino para facilitar el escaneo. El contraste entre el texto en Azul Marino y el fondo blanco garantiza la alta legibilidad de los datos en tiempo real de los pedidos (código, cliente, estado).

<p align="center">
  <img src="https://i.imgur.com/GdN4fuA.png" alt="12171">
</p>

El mockup de Order Details utiliza el color para guiar la lectura a través de las secciones de información. El Ámbar destaca los títulos de sección ("ORDER DETAILS", "CUSTOMER INFORMATION", "ORDER ITEMS"). Dentro de las secciones, la información clave utiliza un degradado de colores: las etiquetas críticas (como ORDER CODE y CUSTOMER NAME) se presentan en Anaranjado, mientras que los campos menos críticos (como ORDER STATUS y CUSTOMER EMAIL) usan un Cian Suave. Esto ayuda al administrador a priorizar visualmente la información. Los artículos pedidos se muestran con sus portadas reales para una identificación rápida.

<p align="center">
  <img src="https://i.imgur.com/IWxiSdN.png" alt="12171">
</p>

La función ADD A BOOK en la gestión de inventario utiliza el Ámbar para el fondo del formulario, proporcionando un ambiente visual acogedor para el proceso de ingreso de datos. El título "ADD TO INVENTORY" y el título principal "Livria Management" utilizan el Anaranjado. Los input fields utilizan un Cian Suave muy pálido para el fondo, diferenciándose del blanco, y el botón de acción 'ADD BOOK' emplea el color Ámbar. Las pestañas superiores diferencian la acción principal (ADD A BOOK) en Azul oscuro, del estado pasivo de VIEW INVENTORY.

<p align="center">
  <img src="https://i.imgur.com/1kAEuEd.png" alt="12171">
</p>

La pestaña VIEW INVENTORY muestra la colección de libros con un enfoque en el Stock actual, resaltando la acción de reabastecimiento. El título "BOOK COLLECTION" está en Ámbar. La interfaz presenta portadas de libros reales y un indicador de stock en color Azul Marino. El botón de acción clave, 'ADD STOCK', utiliza el Azul (\#2364A0) para impulsar la acción de reabastecimiento en cada tarjeta, contrastando con el fondo blanco de la colección.

<p align="center">
  <img src="https://i.imgur.com/uUhIwdi.png" alt="12171">
</p>

La pantalla de Add Stock Details utiliza el Anaranjado para el título del libro y el Azul Marino para los metadatos y la información de stock. Los campos clave de la gestión financiera (PURCHASE PRICE y SALE PRICE) se resaltan en Anaranjado y Amarillo Claro, respectivamente. La sección de acción (QUANTITY y TOTAL TO PAY) utiliza un fondo Ámbar para atraer la atención, y el botón 'CONTINUE' usa un Cian Suave, cerrando el ciclo de la gestión de existencias de manera clara y visualmente distinta.

<p align="center">
  <img src="https://i.imgur.com/sRC4Q5q.png" alt="12171">
</p>

La pantalla de Statistics es un dashboard analítico y visual. El color Anaranjado se utiliza para títulos de alto nivel ("Management and Statistics") y el Ámbar para subtítulos de sección ("TOP THREE BEST SELLING BOOKS", "REVENUE ACCORDING THE GENRES"). Esto jerarquiza los datos. Los libros más vendidos se presentan con portadas reales en tarjetas con un sombreado suave para destacarse. Los gráficos utilizan la paleta de colores de Livria (literatura en Rojo/Anaranjado, mangas/comics en Azul y juvenil en Amarillo Claro) para una interpretación intuitiva de los datos de rendimiento.

<p align="center">
  <img src="https://i.imgur.com/G4pS9OD.png" alt="12171">
</p>

En la pestaña PROFILE, el diseño es limpio y utiliza el contraste de color para la acción. El Anaranjado destaca el título principal ("Settings"). Los campos del formulario (Name, Username, Email, Security Pin) utilizan un relleno de color Cian Suave para que sean fácilmente editables y visibles. El botón 'LOG OUT' usa el color de acción Anaranjado para asegurar que la acción sea prominente y el botón 'SAVE CHANGES' utiliza el color Cian Suave como acción secundaria de confirmación.

<p align="center">
  <img src="https://i.imgur.com/aL9rnQ1.png" alt="12171">
</p>

La pestaña APPLICATION utiliza el mismo patrón de color para la seguridad y la acción. El título de la sección "APP SETTINGS" se resalta en Anaranjado. Los toggles de configuración (Notifications, Email Alerts) utilizan el Ámbar (\#FEB913) y el color Gris Claro para las opciones 'YES' y 'NO', proporcionando una retroalimentación visual inmediata sobre el estado de la configuración. Los botones 'LOG OUT' (en Anaranjado) y 'SAVE CHANGES' (en Cian Suave) mantienen la coherencia visual con la sección de perfil.

<p align="center">
  <img src="https://i.imgur.com/nlnektH.png" alt="12171">
</p>

##### **Pantallas de Cliente** 

La pantalla de Home es el punto de entrada visualmente más rico, diseñada para ser acogedora. La cabecera superior utiliza los colores de la marca. Una sección destacada de carrusel (COMMUNITY PLAN) utiliza una imagen de fondo cálida (librería) y un call-to-action ('GET IT HERE') en Ámbar (\#FEB913) para fomentar la participación social. La lista de libros se organiza por categorías (LITERATURE, NON-FICTION, FICTION, MANGAS & COMICS), donde los títulos de las secciones utilizan los colores vibrantes de la paleta (Anaranjado, Amarillo Claro, Azul) para una jerarquía visual clara y atractiva. Las portadas de los libros reales y los precios visibles completan la experiencia de navegación.

<p align="center">
  <img src="https://i.imgur.com/10SBKTm.png" alt="12171">
</p>

La pantalla de Recommendations for You utiliza el color Anaranjado (\#FF5C00) para el título principal, capturando la atención sobre el contenido personalizado. El texto introductorio utiliza la tipografía Alexandria para una lectura amigable. La lista de libros recomendados se muestra en un diseño de tarjeta, con portadas reales de títulos como 1984 y Harry Potter, lo que refuerza la conexión emocional. El botón 'REFRESH' al final de la lista utiliza un color Cian Suave (\#A8DBDE) como un call-to-action secundario que sugiere la recarga de contenido.

<p align="center">
  <img src="https://i.imgur.com/1lXlFdu.png" alt="12171">
</p>

La pantalla de Categories facilita la navegación del catálogo con una lista limpia y organizada. El título de la sección superior, 'SEARCH BY CATEGORY', utiliza un Cian Suave para orientar al usuario. Cada categoría principal (LITERATURE, NON-FICTION, MANGAS & COMICS) se distingue con un color vibrante de la paleta principal (Anaranjado, Amarillo Claro, Azul) para una rápida identificación visual y un diseño dinámico. El uso de íconos de flecha hacia la derecha (' \> ') en el color principal de la categoría indica claramente la navegabilidad.

<p align="center">
  <img src="https://i.imgur.com/jzpNQXs.png" alt="12171">
</p>

La vista de una categoría específica, como LITERATURE, mantiene el título de la sección en su color distintivo (Anaranjado). El listado de libros utiliza un diseño de rejilla de tarjetas con información mínima (portada, título, autor y precio) para una navegación eficiente. El ícono de Filtro en la esquina superior derecha utiliza una combinación de colores de la marca para mantener la coherencia y llamar la atención sobre la funcionalidad de refinamiento de búsqueda.

<p align="center">
  <img src="https://i.imgur.com/GDgf0Tq.png" alt="12171">
</p>

La pantalla de Search está diseñada para ser la herramienta de precisión del usuario. La barra de búsqueda, central y destacada, está enmarcada por el color Ámbar (\#FEB913), que dirige la atención inmediatamente a la acción de entrada. El título 'SEARCH BY TITLE OR AUTHOR' en Cian Suave (\#A8DBDE) proporciona una guía clara sobre los términos de búsqueda esperados. Los resultados (RESULTS) se presentan de manera limpia, con portadas de libros reales y el color Anaranjado (\#FF5C00) destacando los nombres de la sección. El ícono de Filtro en la esquina superior derecha utiliza una combinación de colores de la marca, asegurando que el usuario pueda refinar los resultados obtenidos (función clave para optimizar la compra) con una acción visualmente accesible.

<p align="center">
  <img src="https://i.imgur.com/SbfSNFP.png" alt="12171">
</p>

Esta vista transforma el libro seleccionado en un producto digital altamente atractivo, utilizando el color Anaranjado (\#FF5C00) para el título principal, lo que le otorga la máxima prominencia visual. Los metadatos críticos como el autor y las etiquetas de género (JUVENILE, en INGLÉS) utilizan el contraste del Azul Marino para mantener la legibilidad. El precio (S/ 49.00) se enfatiza en Anaranjado, ubicándose junto al botón de acción clave 'ADD TO CART', que emplea el color Cian Suave (\#A8DBDE) para ser distintivo e incentivar la conversión. La Sinopsis está en un recuadro limpio con tipografía Alexandria Regular, facilitando una inmersión textual antes de la compra.

<p align="center">
  <img src="https://i.imgur.com/4l994W4.png" alt="12171">
</p>

A continuación, la sección REVIEWS está diseñada para fomentar la participación comunitaria. El título se destaca en Anaranjado. El sistema de calificación utiliza estrellas que se iluminan con el color Ámbar (\#FEB913), el color de la marca asociado a la calidad, incentivando al usuario a calificar positivamente. El botón de confirmación 'POST REVIEW' se presenta en Cian Suave (\#A8DBDE) para ser una acción secundaria, manteniendo la jerarquía visual de la página. Las reseñas existentes muestran avatares de usuario y resaltan las calificaciones con el color Ámbar, creando prueba social para otros lectores.

<p align="center">
  <img src="https://i.imgur.com/GwNsdHs.png" alt="12171">
</p>

La pantalla de Communities es el centro neurálgico para el segmento de Lectores Comunitarios. El título principal en Anaranjado (\#FF5C00) atrae la vista. El call-to-action más importante, 'CREATE \+', se distingue en Cian Suave (\#A8DBDE), proporcionando un contraste sutil que anima a la creación de nuevos grupos de lectura. La presentación visual en mosaico con imágenes de portadas reales y nombres de comunidades temáticas (como horror o Wonderland) refuerza la diversidad de intereses literarios y motiva la exploración activa del usuario.

<p align="center">
  <img src="https://i.imgur.com/DwP3I2Y.png" alt="12171">
</p>

Esta interfaz de una Comunidad en singular prioriza la interacción social dinámica. El botón 'JOIN \+' utiliza el Cian Suave (\#A8DBDE), contrastando con el fondo para facilitar la incorporación a la comunidad. El encabezado de la comunidad usa el Azul Marino. El área de publicación de contenido es funcional y visible, con íconos de Línea de 24 píxeles para las opciones de cámara/galería, y el botón 'POST' en Cian Suave. El feed utiliza un diseño limpio para mostrar las publicaciones del usuario (imágenes de cómics de Batman) y sus interacciones, promoviendo el compromiso continuo dentro del grupo.

<p align="center">
  <img src="https://i.imgur.com/wL2S9Sy.png" alt="12171">
</p>

La pantalla de Cart está diseñada para ser la etapa final de conversión, transmitiendo confianza y claridad financiera. Utiliza un fondo oscuro de Azul Marino en la parte inferior para la estabilidad. El título 'CART' en Anaranjado (\#FF5C00) atrae la atención. La lista de artículos utiliza tarjetas blancas y limpias, con el precio del libro en Anaranjado para enfocar la vista en el costo. El botón 'COMPLETE MY PURCHASE' en la barra inferior es el call-to-action más prominente, utilizando el color Cian Suave (\#A8DBDE) para ser ineludible y guiar al usuario a la finalización segura de la transacción.

<p align="center">
  <img src="https://i.imgur.com/m3v2kF2.png" alt="12171">
</p>

La pantalla de Notifications mantiene una estética simple para asegurar que las alertas sean el foco principal. El título utiliza el color Anaranjado (\#FF5C00) para captar la atención. El botón 'EMPTY LIST' se ubica en la parte superior derecha, utilizando un color Cian Suave (\#A8DBDE) para ser funcional pero no intrusivo. Cada notificación se presenta en una tarjeta blanca y limpia, con el mensaje en color Azul Marino para maximizar la legibilidad. La opción de eliminar cada notificación individualmente se representa con un ícono de línea delgada en la parte derecha de la tarjeta, optimizando la gestión de la bandeja de entrada.

<p align="center">
  <img src="https://i.imgur.com/pjS4JtJ.png" alt="12171">
</p>

La pantalla de Store está diseñada para ofrecer una conexión clara entre la plataforma digital y la ubicación física. El título principal ("OUR STORE") y la frase de bienvenida utilizan el color Anaranjado. La interfaz presenta un fragmento de mapa visualmente realista con el pin de ubicación en la paleta de la marca. La dirección se muestra de forma clara con tipografía legible, y la sección de información se destaca con un color Ámbar (\#FEB913) en el encabezado, lo que asegura que los datos de contacto y localización sean inmediatamente visibles y confiables para el cliente.

<p align="center">
  <img src="https://i.imgur.com/YbzPB65.png" alt="12171">
</p>

El inicio del flujo de pago se presenta con una clara barra de progreso visual que utiliza el color Cian Suave (#A8DBDE) para indicar el paso actual ('CART') y los pasos pendientes. El título "SUBMIT ORDER" está en Anaranjado. La sección PURCHASE SUMMARY utiliza el color Ámbar para resaltar el Total de la compra, atrayendo la mirada del usuario al costo final. El botón 'CONTINUE', clave para avanzar en la transacción, se presenta en Cian Suave, manteniendo el foco en la usabilidad.

<p align="center">
  <img src="https://i.imgur.com/phOusi7.png" alt="12171">
</p>

El segundo paso, RECIPIENT INFORMATION, mantiene la barra de progreso y resalta el paso actual. Los campos de formulario (Name, Last Name, Phone Number, Email) utilizan el color Azul Marino para el texto, garantizando la legibilidad de los datos que el usuario ingresa. El diseño de los campos es limpio y minimalista para evitar fricciones. La acción de 'CONTINUE' utiliza el Cian Suave, asegurando una transición fluida hacia la siguiente fase de la compra.

<p align="center">
  <img src="https://i.imgur.com/tpMKJDl.png" alt="12171">
</p>

En el tercer paso, la selección del método de entrega se simplifica mediante tarjetas claras y visuales. Las opciones 'PICK UP IN STORE' y 'HOME DELIVERY' utilizan el Cian Suave para sus íconos y texto, lo que las hace fácilmente seleccionables. La información adicional sobre la recogida en tienda (días hábiles) usa un texto Ámbar para notificar al cliente sobre los detalles clave de la logística. El botón 'CONTINUE' en Cian Suave reafirma la progresión del proceso de checkout.

<p align="center">
  <img src="https://i.imgur.com/Va1nmuA.png" alt="12171">
</p>

El paso final, PAYMENT DETAILS, mantiene un diseño enfocado en la seguridad y el consentimiento legal. La información sobre la pasarela de pago Izipay utiliza el color Azul Marino para transmitir confianza. Las casillas de verificación para la Privacy Policy y Terms and Conditions son obligatorias y visualmente claras, utilizando el color Anaranjado para las etiquetas. El botón 'CONTINUE', que inicia la redirección al sistema de pago, utiliza el color Cian Suave para una finalización de compra que es a la vez intuitiva y legalmente informada.

<p align="center">
  <img src="https://i.imgur.com/S5EtAzq.png" alt="12171">
</p>

La pantalla de Profile es el centro de control personal, diseñada para ofrecer la máxima flexibilidad al cliente. La información de la cuenta (nickname, username, email) utiliza el color Anaranjado para los títulos de las secciones. La funcionalidad se organiza en pestañas (SETTINGS, MY ORDERS, EDIT BIO), utilizando un degradado de color para indicar la pestaña activa. La sección de configuración (SETTINGS) utiliza toggles en Ámbar (#FEB913) para la personalización de notificaciones. Los botones de acción de alto impacto ('DELETE ACCOUNT' y 'LOG OUT') usan el Anaranjado y Cian Suave respectivamente, diferenciando las acciones de seguridad permanente de las acciones de cierre de sesión.

<p align="center">
  <img src="https://i.imgur.com/r8r4lYv.png" alt="12171">
</p>

### 4.4.4. Mobile Applications User Flow Diagrams

**Segmento 1: Lectores en Desarrollo**

<p align="left"><i>Búsqueda Personalizada</i></p>
* Como usuario, quiero poder realizar la búsqueda de libros en base a diferentes criterios y obtener resultados relacionados.
<br>
<p align="center">
  <img src="https://i.imgur.com/BD9GXo6.jpeg" alt="12171">
</p>

El flujo de Búsqueda Personalizada comienza en la Pantalla de Inicio, donde el usuario pulsa el ícono de búsqueda (lupa) en la esquina superior. Esto lo lleva a la Pantalla de Búsqueda inicial, que solicita ingresar un título o autor en el campo de texto. Una vez que el usuario ingresa un término de búsqueda, la aplicación muestra una Pantalla de Búsqueda con una lista de Resultados relacionados. Desde esta pantalla, el usuario tiene la opción de Filtrar los resultados (mediante el ícono de filtro) o puede seleccionar un libro de la lista para ver más detalles. Al seleccionarlo, el flujo concluye con la Visualización del resultado seleccionado en la Pantalla de Libro, donde se muestra información completa como la portada, el autor, precio, un resumen, y reseñas, permitiendo al usuario decidir si desea añadirlo al carrito.
<br>

<p align="left"><i>Búsqueda por Categorías</i></p>
* Como usuario, quiero poder realizar una búsqueda amplia de libros entre los diferentes géneros literarios.
<br>
<p align="center">
  <img src="https://i.imgur.com/weS07Si.jpeg" alt="12171">
</p>

El flujo de Búsqueda por Categorías en la aplicación LIVRIA permite a los usuarios realizar una exploración amplia de géneros literarios. El proceso inicia en la Pantalla de Inicio, donde el usuario puede ver un resumen de las categorías disponibles. Para acceder a la lista completa, el usuario selecciona el ícono de Categorías, lo que lo lleva a la Visualización de la pantalla de Categorías. En esta Pantalla de Categorías, se presenta un listado organizado de todos los géneros, tales como Literatura, No Ficción, Ficción, Mangas & Cómics, Juvenil, Infantil, y E-books & Audiolibros. El usuario debe Seleccionar una categoría a buscar. Tras la selección, el flujo culmina con la Visualización de la categoría seleccionada en la Pantalla de una Categoría, donde se presenta un listado completo de los libros que pertenecen a ese género específico, permitiendo una exploración amplia dentro del tema elegido.
<br>

<p align="left"><i>Recomendaciones Personalizadas</i></p>
* Como usuario, quiero poder marcar interés en diferentes libros y visualizar recomendaciones basadas en mis gustos literarios.
<br>
<p align="center">
  <img src="https://i.imgur.com/VFKV41o.jpeg" alt="12171">
</p>

El flujo comienza en la Pantalla de Inicio, desde la cuál accede a la Pantalla de Búsqueda para encontrar un título en específico. Al interactuar con cada libro, el usuario proporciona feedback directo al sistema: el Feedback Positivo (usando el 'Marcador') le indica al algoritmo que debe priorizar ese tipo de contenido. Por otro lado, el Feedback Negativo ('No Me Gusta/Negativo') instruye al Algoritmo de Recomendación para reducir la frecuencia de ese contenido, asegurando que las futuras sugerencias se alineen más estrechamente con los intereses del usuario. Esta interacción funciona con cualquier libro, sea uno buscado específicamente por el usuario o no. Desde la Pantalla de Recomendaciones, el usuario recibe un listado inicial de sugerencias y tiene la opción de repetir el ciclo tocando el botón 'REFRESH' para solicitar un nuevo conjunto de libros.

<br><br>

**Segmento 2: Lectores Comunitarios**

<p align="left"><i>Comunidades Temáticas</i></p>
* Como usuario, quiero poder unirme a comunidades temáticas, crear publicaciones y conectar con otros lectores con intereses literarios similares.
<br>
<p align="center">
  <img src="https://i.imgur.com/fyGaQSF.jpeg" alt="12171">
</p>

El flujo permite al usuario, desde la Pantalla de Comunidades, elegir entre Crear una nueva comunidad o Ingresar a una existente. Tras ingresar los datos requeridos, estos se mostraran en su pantalla personalizada, ante la cual se podrá empezar con la publicación de pensamientos y/o imágenes. Contrariamente, si ingresa a una comunidad existente (la Vista de Comunidad Única), debe seleccionar 'JOIN +' para unirse al grupo. Una vez dentro de la vista comunitaria, el usuario puede cumplir su objetivo central de socialización al Crear una Publicación (añadiendo texto y/o imágenes). Finalmente, al publicar su contenido, el flujo culmina en la Visualización de la publicación hecha, confirmando que el usuario ha compartido activamente sus opiniones e iniciado la interacción con otros lectores en el grupo temático.
<br>

<p align="left"><i>Personalización del Perfil</i></p>
* Como usuario, quiero poder personalizar ciertos aspectos de mi perfil.
<br>
<p align="center">
  <img src="https://i.imgur.com/iM458EJ.jpeg" alt="12171">
</p>

El flujo de personalización se inicia en el Registro. Esto lleva al usuario a las pantallas con formularios, donde puede personalizar su Profile Picture, Nickname, Username y la Phrase de perfil. Una vez que el usuario ingresa su personalidad literaria deseada, confirma los cambios con el botón 'REGISTER'. El flujo lo lleva a la pantalla de Inicio, desde la cual puede acceder a la pantalla de Perfil mediante el menú inferior. La información ingresada previamente ahora se muestra en el perfil y a la comunidad de lectores, cumpliendo el objetivo de proyectar su identidad literaria.

## 4.5. Mobile Applications Prototyping

Con el objetivo de evaluar y perfeccionar la accesibilidad y la experiencia de usuario (UX) antes del desarrollo final, se elaboró un prototipo interactivo a partir de los mockups de alta fidelidad, centrado exclusivamente en la navegación móvil.  
Este modelo funcional simula de forma integral el recorrido del usuario dentro de la aplicación, permitiendo explorar directamente sus secciones, elementos y flujos de interacción tal como se verá en un dispositivo móvil. 

El prototipo fue diseñado siguiendo principios de arquitectura de la información clara, jerarquía visual lógica y diseño inclusivo. Se priorizó la facilidad de uso, asegurando que cada componente respete los estándares de usabilidad táctil y coherencia visual para una navegación fluida e intuitiva en la pantalla del smartphone. Esta versión navegable actúa como una fiel representación de la futura interfaz de la aplicación, siendo clave para validar decisiones de diseño y garantizar una experiencia consistente y accesible.

Video explicativo: [https://drive.google.com/file/d/1zC7zEfy8xk2KNJ6Z2aCdW8eQRqIzGSus/view?usp=sharing](https://drive.google.com/file/d/1zC7zEfy8xk2KNJ6Z2aCdW8eQRqIzGSus/view?usp=sharing)

Link al prototipo interactivo: [https://www.figma.com/proto/eKCqZoU0IF7n3wNTA8kuZc/livria?page-id=923%3A589\&node-id=923-591\&p=f\&viewport=263%2C65%2C0.18\&t=ykEtTTogjnebX157-1\&scaling=scale-down\&content-scaling=fixed](https://www.figma.com/proto/eKCqZoU0IF7n3wNTA8kuZc/livria?page-id=923%3A589&node-id=923-591&p=f&viewport=263%2C65%2C0.18&t=ykEtTTogjnebX157-1&scaling=scale-down&content-scaling=fixed)

## 4.6. Domain-Driven Software Architecture

### Strategic-Level Domain-Driven Design

En esta sección se introduce el proceso de Domain-Driven Design a nivel estratégico para Livria. Este enfoque nos ha permitido conceptualizar el sistema a partir de la lógica del negocio, con el fin de modelar una arquitectura de microservicios coherente. Para ello se identificaron los subconjuntos del sistema con límites claros y naturales, conocidos como Bounded Contexts. Las herramientas utilizadas para este propósito son el EventStorming, que nos permitió visualizar el flujo de eventos del negocio, y el Bounded Context Canvas, una herramienta para definir formalmente cada contexto y sus relaciones, garantizando así una base sólida para el desarrollo.

## Event Storming

Event Storming es una técnica que consiste en la realización de una especie de taller facilitado en el que los integrantes del equipo identifican eventos clave del negocio y los requisitos para su funcionamiento, a lo largo de diferentes pasos que deben ser realizados colaborativamente.

Esta herramienta nos permite elaborar una arquitectura de aplicación más robusta, estructurada y acorde con el enfoque del Domain-Driven Design (DDD), además de visualizar posibles flujos de usuario y estructuras de código a utilizar. En nuestro caso, por motivos de mejor visualización y facilidad, se utilizó la plataforma Miro para la realización de los diferentes pasos de manera colaborativa.

●	Step 1: Unstructured Exploration

<p align="center">
  <img src="https://imgur.com/391o69b.jpg" alt="12231">
</p>

El primer paso del Event Storming, Unstructured Exploration (Exploración No Estructurada), consiste en escribir en post-its los eventos propios del negocio que cada miembro del equipo pueda detectar, generando una lluvia de ideas masiva con el objetivo de identificar la mayor cantidad de eventos de dominio posibles, estimar la complejidad del proyecto y permitir que se forme una base de conocimiento compartido entre los participantes.

●	Step 2: Timelines

<p align="center">
  <img src="https://imgur.com/cmderHR.jpg" alt="12231">
</p>

El segundo paso del Event Storming, Timelines (Líneas de tiempo), consiste en organizar los post-its escritos en el paso anterior de izquierda a derecha a través de flechas y en orden cronológico, pudiendo seguir diferentes flujos según los eventos de dominio involucrados. El objetivo es organizar todos los eventos de dominio identificados de una manera más comprensible y clara para todos los miembros del equipo, ilustrando cómo es la secuencia en la que suceden.

●	Step 3: Pain Points

<p align="center">
  <img src="https://imgur.com/Y0RnyN5.jpg" alt="12231">
</p>

El tercer paso, Pain Points (Puntos de Dolor), consiste en identificar problemas y áreas de mejora dentro del flujo de eventos de dominio. Esto se realiza con el objetivo de visibilizar puntos críticos en los que concentrar esfuerzos de desarrollo y oportunidades de optimización a futuro para aumentar el impacto de la solución.

●	Step 4: Pivotal Points

<p align="center">
  <img src="https://imgur.com/tmbX4f9.jpg" alt="12231">
</p>

El cuarto paso, Pivotal Points (Puntos Pivotes), consiste en identificar las causas y consecuencias de los eventos de dominio identificados, analizando cómo y por qué suceden. El objetivo es tener un mayor entendimiento de lo que sucede “antes” de un evento de dominio y descubrir reglas de dominio previamente no identificadas.
En nuestro caso, utilizamos post-its en forma de rombo para señalizar los Pain Points detectados.

●	Step 5: Commands

<p align="center">
  <img src="https://imgur.com/leGXzSJ.jpg" alt="12231">
</p>

El quinto paso, Commands (Comandos), se trata de identificar las intenciones y solicitudes que dan paso a los eventos de dominio, esto permite detectar las causas presentes justo antes de que se desencadene un evento determinado.

●	Step 6: Policies

<p align="center">
  <img src="https://imgur.com/eQkhJBL.jpg" alt="12231">
</p>

El sexto paso, Policies (Políticas), permite al equipo identificar la lógica reactiva del negocio, es decir, lo que ocurre de forma automática inmediatamente después de un evento de dominio. Este paso es muy importante para modelar el comportamiento autónomo y la automatización presente dentro de la aplicación.

●	Step 7: Read Models

<p align="center">
  <img src="https://imgur.com/i7ubvEL.jpg" alt="12231">
</p>

El séptimo paso, Read Models (Modelos de Lectura), consiste en realizar una revisión de todo el modelo y señalar los datos o información dentro del dominio, que están al alcance del usuario en determinado momento. Realizar este paso nos permite visualizar de una mejor manera cómo diseñar las vistas de usuario y tener en consideración la información a mostrar en diferentes etapas del flujo de uso.

●	Step 8: External Systems

<p align="center">
  <img src="https://imgur.com/yiwBoz0.jpg" alt="12231">
</p>

Durante el octavo paso del Event Storming, External Systems (Sistemas Externos), el equipo debe identificar y colocar los componentes que no forman parte de la aplicación, usualmente dependencias externas y APIs pertenecientes a servicios de terceros. Este paso nos permite tener una visión más clara del funcionamiento de nuestra aplicación, permitiéndonos diseñar una arquitectura incluso más robusta, al identificar partes del sistema que interactúan con servicios que están fuera del control del equipo.

### Candidate Context Discovery

Tras la sesión de Event Storming para modelar el dominio de negocio, el equipo se enfocó en el proceso de Candidate Context Discovery con el objetivo de identificar los bounded contexts preliminares. Para ello, aplicamos una combinación de técnicas, utilizando look-for-pivotal-events para hallar eventos de dominio clave que indican cambios de estado significativos, start-with-simple para crear modelos con propósito y descomponer el timeline en pasos secuenciales, y start-with-value para priorizar los contextos que representan el core domain del negocio.

En primera instancia, a partir del Event Storming, se delimitaron los bounded contexts identificando los flujos de negocio clave de la plataforma. Este proceso permitió agrupar comandos, eventos y vistas relacionados para crear modelos de dominio cohesionados y bien definidos. Los contextos que emergieron de este análisis inicial, centrados en funcionalidades como las reseñas, la gestión de comunidades, el proceso de compra y el inventario, son el resultado de aplicar técnicas de descubrimiento que buscan aislar las partes más valiosas y críticas del negocio.

<p align="center">
  <img src="https://i.imgur.com/KHhTA1v.png" alt="12231">
</p>

El Bounded Context de Search se centra en el comando principal "Buscar Libro". Esta acción es crucial porque inicia la interacción más frecuente y valiosa para el Usuario de Livria, facilitando el acceso a los productos del negocio. Por esta razón, la funcionalidad ha sido identificada como un dominio de soporte fundamental para el negocio. La cohesión de este comando y todas las funcionalidades asociadas como filtros, ordenación y sugerencia, justifican la delimitación de un Bounded Context independiente.

<p align="center">
  <img src="https://i.imgur.com/cXKfOp7.png" alt="12231">
</p>

El Bounded Context de Book se centra en el evento de "Vista de información de un libro". Esta acción es crucial porque representa la interacción con el producto principal del negocio: el libro.
Por esta razón, la funcionalidad se ha identificado como un dominio central para el negocio. La cohesión de este evento y todas las funcionalidades asociadas, como ver reseñas, publicar una nueva, y marcar un libro como favorito o para no recomendar, justifican la delimitación de un Bounded Context independiente.

<p align="center">
  <img src="https://imgur.com/ckPfuaz.jpg" alt="12231">
</p>

El Bounded Context de Profile se centra en el comando principal de "Crear cuenta" e "Iniciar sesión". Estas acciones son cruciales porque habilitan la interacción del usuario con la plataforma, siendo la puerta de entrada a todas las demás funcionalidades.
Por esta razón, la funcionalidad se ha identificado como un dominio de soporte fundamental para el negocio. La cohesión de estas acciones y todas las funcionalidades asociadas, como modificar el perfil y validar credenciales, justifican la delimitación de un Bounded Context independiente.

<p align="center">
  <img src="https://i.imgur.com/Ile7A86.png" alt="12231">
</p>

El Bounded Context de Communities se centra en el comando de "Crear comunidad". Esta acción es fundamental para el negocio, ya que fomenta la interacción social y aumenta la retención de usuarios, generando un valor significativo para la plataforma.

La funcionalidad se identifica como un dominio central debido a que toda la lógica crucial para la interacción de la comunidad, desde la asignación de roles y permisos hasta la publicación de contenido, la moderación y las notificaciones, se agrupan de manera coherente. Esta cohesión justifica la delimitación de un contexto independiente, asegurando que todas las funcionalidades relacionadas con los grupos se gestionen de forma autónoma.

<p align="center">
  <img src="https://i.imgur.com/o5GXjC1.png" alt="12231">
</p>

El Bounded Context de Cart se centra en el comando de "Agregar libro a carrito de compra". Esta acción es fundamental, ya que inicia un flujo de valor que monetiza el catálogo y gestiona la interacción directa del cliente con los productos.

Esta funcionalidad se identifica como un dominio central porque la lógica de la compra, la integración con la pasarela de pagos y la gestión de la transacción son críticas para el negocio. La cohesión de estas accione, desde la eliminación de ítems hasta la suscripción a planes, justifican su delimitación en un contexto independiente, asegurando que todo el proceso de compra se gestione de forma coherente y segura.

<p align="center">
  <img src="https://imgur.com/9xbekUP.jpg" alt="12231">
</p>

El Bounded Context de Stock se centra en los comandos de "Agregar" y "Eliminar libros del inventario". Estas acciones, ejecutadas por un administrador, son fundamentales para el negocio, ya que aseguran la disponibilidad de productos para la venta y mantienen la información de inventario actualizada.

Esta funcionalidad se identifica como un dominio central porque el stock es crítico para la operación del negocio. La cohesión de las acciones relacionadas con la gestión de existencias y los metadatos de los libros justifica la delimitación de un contexto independiente, lo que permite que esta lógica de negocio se maneje de forma centralizada y eficiente.

<p align="center">
  <img src="https://i.imgur.com/oUpmZue.png" alt="12231">
</p>

El Bounded Context de Orders se centra en los comandos de "Buscar pedidos por ID" y "Buscar pedidos por cliente". Estas acciones, ejecutadas por administradores, son cruciales porque permiten la trazabilidad y la auditoría de ventas.

Este dominio se identifica como un subdominio de soporte, ya que proporciona las herramientas necesarias para que el equipo de administración monitoree y gestione el flujo de capital y la actividad de los clientes. La cohesión de estas funcionalidades de búsqueda y visualización justifica la delimitación de un contexto independiente, asegurando que las herramientas de gestión interna operen de manera eficiente y autónoma.

<p align="center">
  <img src="https://i.imgur.com/rfyprh1.png" alt="12231">
</p>

El Bounded Context de Recommendations se centra en la "Funcionalidad de recomendaciones". Esta acción es fundamental para el negocio, ya que personaliza la experiencia del usuario y promueve el descubrimiento de nuevos productos.

Esta funcionalidad se identifica como un dominio central porque un sistema de recomendaciones de calidad es una ventaja competitiva clave para la plataforma. La cohesión de las acciones relacionadas con la generación de recomendaciones, basada en favoritos y exclusiones, y su posterior visualización, justifica la delimitación de un contexto independiente, lo que permite el desarrollo y la mejora de algoritmos de forma autónoma.

### Domain Message Flows Modelling

En esta sección se modelan los Domain Message Flows para representar cómo los bounded contexts de Livria colaboran en la resolución de los casos de negocio. Para ello se utiliza la técnica de Domain Storytelling, que permite narrar e ilustrar los flujos de mensajes entre actores y contextos, mediante diagramas elaborados que evidencian dichas interacciones en escenarios clave del sistema.

**Escenario 1: Compra de libro del catálogo de Livria**

<p align="center">
  <img src="https://imgur.com/v2pgFZF.jpg" alt="12231">
</p>

Este diagrama ilustra el flujo que sigue el usuario para completar la compra de un libro en Livria. Una vez agregado el libro al carrito, se genera un evento que confirma al usuario que el producto ha sido añadido con éxito. Al acceder al carrito, el usuario puede visualizar los artículos seleccionados y, al hacer clic en “Realizar pago”, el sistema valida la disponibilidad de los libros antes de redirigirlos a la pantalla de pago. Cuando el usuario selecciona la opción “Pagar”, el sistema valida sus credenciales a través de Izipay. Tras la confirmación, se dispara el evento de Pago exitoso, se actualiza el stock correspondiente y, finalmente, se emite el comprobante de compra.

**Escenario 2: Creación de una publicación dentro de una comunidad existente**

<p align="center">
  <img src="https://imgur.com/nn7Z0GO.jpg" alt="12231">
</p>

Este diagrama representa el flujo para la creación de una publicación dentro de una comunidad en Livria. El proceso inicia cuando el usuario accede a una comunidad específica, momento en el que el sistema lo redirige y despliega la pantalla correspondiente, pudiendo unirse a la comunidad si no lo ha hecho ya. Desde allí, el usuario puede crear una nueva publicación proporcionando una descripción y una imagen; al enviarla, se genera un evento que confirma su creación exitosa y, de forma inmediata, se activa una política de moderación automatizada en el contexto de la comunidad. Además, el diagrama refleja un flujo secundario que permite al usuario navegar desde la comunidad hacia su perfil, donde se le muestra tanto su información personal como la lista de comunidades a las que pertenece.

**Escenario 3: Vista de libros recomendados**

<p align="center">
  <img src="https://imgur.com/asKrnyt.jpg" alt="12231">
</p>

Este diagrama de flujo describe el proceso de visualización de libros recomendados en Livria. La secuencia comienza cuando el usuario selecciona un libro de su interés y es redirigido a la pantalla de detalle, donde puede consultar su título, descripción y autor, además de contar con la opción de marcarlo como “favorito”. Al hacerlo, el sistema muestra una notificación que confirma que el libro ha sido agregado a sus favoritos, acción que impacta directamente en su perfil. Posteriormente, al acceder a la sección de recomendaciones, el sistema despliega una lista personalizada de libros sugeridos en función de sus preferencias, sobre la cual se aplica una política de moderación automática para garantizar la calidad del contenido presentado.

**Escenario 4: Agregar stock a un nuevo libro**

<p align="center">
  <img src="https://imgur.com/vbHGRsk.jpg" alt="12231">
</p>

Este diagrama ilustra el flujo que sigue un administrador para agregar stock a un libro nuevo en el sistema de Livria. El proceso comienza cuando el administrador registra un libro en el inventario, ingresando datos como título, autor y género, tras lo cual se ejecuta una política de validación de duplicados para garantizar que el libro no exista previamente. Si la validación es exitosa, se genera un evento que confirma la creación del libro. Luego, el administrador localiza el libro recién creado mediante una búsqueda y accede a su vista de datos iniciales, desde donde ejecuta el comando para añadir stock. Finalmente, esta acción desencadena una política que confirma la actualización del inventario y una notificación visual que informa al administrador que la operación se ha completado satisfactoriamente.

#### 2.5.1.3.	Bounded Context Canvases

En esta sección se presentan los candidate bounded contexts identificados para el dominio de Livria. Su elaboración se desarrolló mediante un proceso iterativo que incluyó la definición de cada contexto, la captura del lenguaje ubicuo, el análisis de reglas de negocio, capacidades y dependencias, así como la crítica de diseño. Este abordaje permitió establecer límites claros y responsabilidades bien delimitadas, asegurando la independencia y escalabilidad de cada contexto y, al mismo tiempo, la coherencia integral del sistema.

Cabe señalar que algunos de estos bounded contexts no presentan comunicación de salida, ya que representan pasos finales dentro del flujo de la aplicación. Sin embargo, todos ellos fueron considerados y empleados en el modelado, puesto que resultan esenciales para completar el ciclo de negocio de Livria y garantizar la trazabilidad de los procesos.

**Search Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/7QbOrF2.png" alt="12231">
</p>

**Book Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/2X3oKV8.png" alt="12231">
</p>

**Recommendations Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/eSkMtRm.png" alt="12231">
</p>

**Cart Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/mudi4P5.png" alt="12231">
</p>

**Profile Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/H9rtCYw.png" alt="12231">
</p>

**Orders Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/ZDfePga.png" alt="12231">
</p>

**Stock Bounded Context:**

<p align="center">
  <img src="https://imgur.com/U1HWDiu.jpg" alt="12231">
</p>

**Communities Bounded Context:**

<p align="center">
  <img src="https://i.imgur.com/cCMrxi5.png" alt="12231">
</p>



### 4.6.1. Software Architecture Context Diagram

El Diagrama de Contexto es el primer nivel de abstracción del Modelo C4. Su propósito es definir el sistema a construir, en este caso Livria, y su interacción con los usuarios y otros sistemas externos. Este diagrama nos ofrece una vista de alto nivel que ayuda a entender el rol de Livria en su entorno sin profundizar en su estructura interna, lo que lo hace ideal para comunicárselo a las partes interesadas, tanto técnicas como no técnicas.

<p align="center">
  <img src="https://imgur.com/eZyBU79.jpg" alt="12231">
</p>

El diagrama de contexto de Livria ilustra los principales actores y sistemas externos con los que interactúa la aplicación. Se identifican dos tipos de usuarios: el Administrador de Livria, responsable de la supervisión y gestión de la plataforma, y el Usuario Cliente, que utiliza la aplicación para explorar, comprar libros y participar en la comunidad.
En el ámbito de los sistemas externos, Livria se integra con servicios de terceros especializados para delegar funcionalidades específicas. Se utiliza Izipay para procesar los pagos de manera segura, permitiendo a los usuarios realizar transacciones sin que Livria tenga que gestionar directamente la lógica financiera. Para la autenticación y validación de cuentas, la plataforma se apoya en Gmail, que gestiona el envío de correos electrónicos de verificación. La comunicación entre todos estos componentes se establece a través del protocolo HTTPS, lo que garantiza la seguridad e integridad de la información transferida.

### 4.6.2. Software Architecture Container Diagrams

El Diagrama de Contenedores es el segundo nivel del Modelo C4. Este diagrama descompone el sistema de Livria en contenedores, que son unidades de despliegue y ejecución (como aplicaciones web, bases de datos o servicios de microservicios). Su objetivo es mostrar la arquitectura interna de Livria, especificando los roles y las interacciones entre los diferentes contenedores, lo cual es útil para los desarrolladores.

<p align="center">
  <img src="https://imgur.com/9MsTQ7m.jpg" alt="12231">
</p>

El diagrama de contenedores de Livria detalla la arquitectura de la aplicación, Livria Software System, que se ha diseñado con un enfoque de aplicación web única (SPA) y aplicaciones móviles separadas para los usuarios y los administradores. En el centro del sistema se encuentra el Livria API, un contenedor que expone todas las funcionalidades y servicios de la aplicación. Esta API se comunica con el Web Application y las Single Page Applications (tanto para el usuario como para el administrador) a través de llamadas JSON/HTTPS. Para la persistencia de datos, la API se conecta a una Base de datos (MySQL) donde se almacenan todos los registros del negocio. Además, las aplicaciones móviles –nativa y cross-platform, respectivamente– el administrador (Admin Mobile Application) y para el usuario (User Mobile Application) se comunican directamente con el Livria API. El sistema también mantiene sus interacciones con los servicios externos de Izipay y Gmail, que se detallaron en el diagrama de contexto.

### 4.6.3. Software Architecture Components Diagrams

#### 4.6.3.1. Bounded Context: Search

<p align="center">
  <img src="https://imgur.com/sln3W2x.jpg" alt="12231">
</p>

Este diagrama representa la arquitectura simplificada del Bounded Context de Search para una plataforma de libros, utilizando un enfoque de Arquitectura Limpia y Domain-Driven Design. Muestra cómo un Usuario interactúa con la Búsqueda API para buscar libros y ver su historial. La API orquesta internamente el flujo de trabajo: el BusquedaController recibe las peticiones y las delega a los Handlers de la Capa de Aplicación. Estos handlers, a su vez, usan el Motor de Búsqueda y el Repositorio para ejecutar la lógica de negocio y acceder a los datos de la Base de Datos. La arquitectura está diseñada para mantener una clara separación de responsabilidades y una baja dependencia entre las capas.

#### 4.6.3.2. Bounded Context: Book

<p align="center">
  <img src="https://imgur.com/ndohIaH.jpg" alt="12231">
</p>

Este diagrama detalla la arquitectura para el Bounded Context de Libro. La Libro API actúa como la puerta de entrada, manejando las peticiones de un Usuario para crear, obtener o gestionar libros y reseñas. La lógica de negocio está segregada en la Capa de Aplicación y la Capa de Dominio, asegurando que el código de negocio sea independiente de la tecnología. 


#### 4.6.3.3. Bounded Context: Recommendations

<p align="center">
  <img src="https://imgur.com/H2UiVZS.jpg" alt="12231">
</p>

La Recomendaciones API gestiona las solicitudes de un Usuario para obtener sugerencias de libros. Internamente, un RecomendacionController delega las peticiones a los Handlers de la Capa de Aplicación, quienes utilizan el AlgoritmoRecomendacion (un servicio de dominio) para generar las sugerencias. Este algoritmo accede a los datos de usuario y libros a través del IRecomendacionRepository, que se comunica con la base de datos MySQL.

#### 4.6.3.4. Bounded Context: Cart

<p align="center">
  <img src="https://imgur.com/P5UHQTD.jpg" alt="12231">
</p>

La Carrito API gestiona todas las interacciones de un Usuario con su carrito de compras. Internamente, el CarritoController delega las operaciones a los Handlers de la Capa de Aplicación, los cuales son responsables de orquestar la lógica para agregar, eliminar o confirmar ítems. Estas acciones se llevan a cabo utilizando el ICarritoRepository, que define las operaciones de persistencia. 

#### 4.6.3.5. Bounded Context: Profile

<p align="center">
  <img src="https://imgur.com/HEAN5BG.jpg" alt="12231">
</p>

El servicio expone una API que permite al Usuario ver y actualizar sus datos. Las peticiones son recibidas por el PerfilController y delegadas a los Handlers de la Capa de Aplicación, los cuales encapsulan la lógica para cada operación. Estos Handlers utilizan el IPerfilRepository para interactuar con la base de datos MySQL

#### 4.6.3.6. Bounded Context: Orders

<p align="center">
  <img src="https://imgur.com/E9RXaSG.jpg" alt="12231">
</p>

La API permite al Administrador ver los pedidos. El OrdenController en la Capa de Interfaz delega las operaciones a los Handlers de la Capa de Aplicación. Estos Handlers utilizan el IOrdenRepository para interactuar con la base de datos MySQL a través de Entity Framework Core, gestionando la persistencia de las órdenes.

#### 4.6.3.7. Bounded Context: Stock

<p align="center">
  <img src="https://imgur.com/EmLGzAn.jpg" alt="12231">
</p>

La API permite al Administrador consultar y actualizar el stock de libros. El flujo de trabajo es gestionado por los Handlers en la Capa de Aplicación, quienes encapsulan la lógica para cada tipo de movimiento de inventario. Estos Handlers se comunican con el IStockRepository para interactuar con la base de datos MySQL a través de Entity Framework Core, asegurando que el estado del inventario se mantenga consistente y que la lógica del dominio esté aislada de la infraestructura.

#### 4.6.3.8. Bounded Context: Communities

<p align="center">
  <img src="https://imgur.com/cOUSoVD.jpg" alt="12231">
</p>

Utilizando una API, el servicio permite al Usuario crear, unirse y participar en comunidades. Las peticiones son gestionadas por el ComunidadController y delegadas a los Handlers de la Capa de Aplicación. Estos Handlers utilizan el IComunidadRepository para interactuar con la base de datos MySQL a través de Entity Framework Core.

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

#### 4.7.1.1. Bounded Context: Search

<p align="center">
  <img src="https://imgur.com/2gFHXt6.jpg" alt="12231">
</p>

Este diagrama de clases UML detalla la capa de dominio del contexto Búsqueda. La clase BusquedaActiva, como la raíz del agregado, asegura la coherencia de una sesión de búsqueda. Se compone de una ConsultaBusqueda (la entidad de la búsqueda en sí), una lista de FiltroBusqueda (un objeto de valor inmutable) y una lista de ResultadoBusqueda. El MotorBusqueda es un servicio de dominio que encapsula la lógica de búsqueda, mientras que la interfaz IBusquedaRepository define el contrato para la persistencia, manteniendo el dominio desacoplado de la implementación de la base de datos.

#### 4.7.1.2. Bounded Context: Book

<p align="center">
  <img src="https://imgur.com/TDyWhTD.jpg" alt="12231">
</p>

Este diagrama de clases UML detalla la capa de dominio del contexto Libro. El agregado LibroAggregate es la raíz del contexto, encapsulando y garantizando la consistencia de una Libro y sus Reseñas asociadas. Las entidades Libro y Reseña tienen relaciones de composición con el agregado, lo que significa que no pueden existir fuera de él. El Libro también se compone de objetos de valor inmutables como Autor, Titulo y Descripcion, que aseguran la validez de los datos. Además, el ReseñaService es un servicio de dominio que encapsula la lógica de negocio, como la validación de reseñas. Las interfaces de los repositorios, ILibroRepository e IReseñaRepository, definen los contratos para la persistencia, manteniendo el dominio desacoplado de la infraestructura.

#### 4.7.1.3. Bounded Context: Recommendations

<p align="center">
  <img src="https://imgur.com/8r7DsdW.jpg" alt="12231">
</p>

Este diagrama de clases UML detalla la capa de dominio del contexto de Recomendaciones. La clase RecomendacionAggregate, como la raíz del agregado, orquesta la lógica de negocio central. Se compone de una Recomendacion (una entidad que representa la sugerencia generada), y se basa en el HistorialLectura del usuario y sus PreferenciasUsuario. Las relaciones de asociación indican que el agregado utiliza estas clases para su funcionamiento, pero no las posee de manera exclusiva. El AlgoritmoRecomendacion es un servicio de dominio que encapsula la lógica compleja para generar las recomendaciones, utilizando la interfaz IRecomendacionRepository para acceder a los datos persistidos.

#### 4.7.1.4. Bounded Context: Cart

<p align="center">
  <img src="https://imgur.com/1EeF5nd.jpg" alt="12231">
</p>

Este diagrama de clases UML muestra el diseño de la capa de dominio para el contexto de Carrito. El CarritoAggregate es la raíz del agregado, asegurando que las operaciones sobre el Carrito y sus ItemCarrito sean consistentes. Las flechas de composición indican que la vida de los ItemCarrito y del Carrito está ligada a la del CarritoAggregate. La interfaz ICarritoRepository define el contrato para la persistencia, permitiendo que la lógica del dominio, encapsulada en el agregado, interactúe con la base de datos de manera abstracta y desacoplada. Este diseño separa claramente el comportamiento del negocio de los detalles de la infraestructura.

#### 4.7.1.5. Bounded Context: Profile

<p align="center">
  <img src="https://imgur.com/pXcvDwa.jpg" alt="12231">
</p>

Este diagrama de clases UML muestra la estructura de la capa de dominio del contexto Perfil. El PerfilAggregate actúa como la raíz del agregado, garantizando la consistencia de las operaciones sobre un Perfil y sus Preferencias. La relación de composición indica que tanto la entidad Perfil como el objeto de valor Preferencias son partes esenciales del agregado y no pueden existir de forma independiente. La interfaz IPerfilRepository define el contrato para las operaciones de persistencia, manteniendo el dominio desacoplado de los detalles de la base de datos. Este diseño permite que toda la lógica de negocio relacionada con la gestión del perfil esté encapsulada y protegida dentro del agregado.

#### 4.7.1.6. Bounded Context: Orders

<p align="center">
  <img src="https://imgur.com/djGlbY0.jpg" alt="12231">
</p>

Este diagrama de clases UML muestra la estructura de la capa de dominio del contexto de Órdenes. El OrdenAggregate es la raíz principal que asegura la integridad de una compra. Está compuesto por una entidad Orden y una lista de ItemOrden, que son objetos de valor inmutables que capturan el estado del libro en el momento de la compra. La relación de composición indica que los ItemOrden y la Orden no pueden existir sin el OrdenAggregate. Por último, la interfaz IOrdenRepository define el contrato de persistencia para el agregado, permitiendo que la lógica del negocio se mantenga independiente de la tecnología de la base de datos.

#### 4.7.1.7. Bounded Context: Stock

<p align="center">
  <img src="https://imgur.com/0E2vCv1.jpg" alt="12231">
</p>

Este diagrama de clases UML muestra la estructura del Domain Layer para el contexto Stock. La clase StockAggregate actúa como la raíz del agregado, asegurando que las operaciones sobre el Inventario y sus MovimientoStock sean consistentes. La composición indica que tanto la entidad Inventario como los objetos de valor MovimientoStock son partes fundamentales del agregado. El Inventario encapsula el estado actual del stock, mientras que los MovimientoStock registran las variaciones de forma inmutable. La interfaz IStockRepository define el contrato de persistencia, manteniendo la lógica de negocio, encapsulada en el agregado, independiente de los detalles de la base de datos. Este diseño garantiza la integridad del inventario al centralizar su gestión en una única unidad transaccional.

#### 4.7.1.8. Bounded Context: Communities

<p align="center">
  <img src="https://imgur.com/lwMyIFY.jpg" alt="12231">
</p>

Este diagrama de clases UML detalla la estructura del Domain Layer del contexto de Comunidades. El ComunidadAggregate es la raíz del agregado, asegurando la consistencia de una Comunidad, sus Miembros y Publicaciones. La relación de composición indica que las entidades Comunidad, Miembro y Publicacion no pueden existir de forma independiente. Cada Publicacion puede tener múltiples Comentarios, que se modelan como objetos de valor inmutables. La interfaz IComunidadRepository define el contrato para la persistencia, permitiendo que la lógica del negocio, encapsulada en el agregado, interactúe con la base de datos de manera abstracta y desacoplada.

### 4.7.2. Class Dictionary

#### 4.7.2.1. Bounded Context: Search

##### Domain Layer

**ConsultaBusqueda (Entity):** Representa la búsqueda iniciada por un usuario, es parte del agregado BusquedaActiva.
* Atributos: idConsulta, textoBusqueda, fechaHora, usuarioId.
* Métodos: validarConsulta(), registrarHistorial().

**FiltroBusqueda (ValueObject):** Representa criterios inmutables de filtrado, se asocia a ConsultaBusqueda.
* Atributos: categoria, rangoPrecio, idioma, disponibilidad.
* Métodos: aplicarAFiltros(resultados).

**ResultadoBusqueda (Entity):** Representa un libro encontrado como resultado, hace referencia a la entidad Libro del contexto Libro.
* Atributos: libroId, titulo, autor, coincidenciaRelevancia.
* Métodos: calcularRelevancia().

**BusquedaActiva (Aggregate):** Agrupa la consulta, filtros y resultados de una sesión de búsqueda. Además, orquesta las entidades del contexto.
* Atributos: consulta, listaFiltros, listaResultados.
* Métodos: ejecutarBusqueda(), limpiarResultados().

**MotorBusqueda (DomainService):** Ejecuta la lógica de búsqueda (indexación, coincidencia, ranking). Opera sobre BusquedaActiva, accede a datos de libros.
* Métodos: buscar(consulta, filtros).

**BusquedaRepository (Repository):** Define operaciones para guardar y recuperar búsquedas previas. Implementación en Infrastructure Layer.
* Métodos: guardar(busqueda), obtenerPorUsuario(usuarioId).

##### Interface Layer

BusquedaController (Controller): Gestiona las peticiones HTTP del usuario para realizar búsquedas. Llama a Application Layer (CommandHandlers).
●	Métodos: buscarLibros(request), verHistorial(usuarioId).

##### Application Layer

EjecutarBusquedaHandler (Command Handler): Maneja el comando de ejecutar una nueva búsqueda. Invoca a MotorBusqueda y guarda resultados en BusquedaRepository.
* Métodos: handle(ejecutarBusquedaCommand).

VerHistorialBusquedaHandler (Command Handler): Maneja el comando para recuperar búsquedas pasadas. Accede a BusquedaRepository.
* Métodos: handle(verHistorialCommand).

NuevaBusquedaRegistradaHandler (Event Handler): Reacciona al evento de nueva búsqueda registrada.
* Métodos: onNuevaBusqueda(event).

##### Infrastructure Layer

BusquedaRepositoryImpl (Repository Impl):  Implementa la persistencia de búsquedas y la interfaz BusquedaRepository.
* Métodos: guardar(busqueda), obtenerPorUsuario(usuarioId).


#### 4.7.2.2. Bounded Context: Book

##### Domain Layer

**Libro (Entity):** Representa un libro dentro del sistema. Puede recibir reseñas y ser marcado como favorito por los usuarios.
* Atributos: id, titulo, autor, descripcion, fechaPublicacion.
* Métodos: agregarReseña(reseña), calcularPromedioReseñas(), marcarFavorito(usuarioId).

**Reseña (Entity):** Representa una reseña asociada a un libro, creada por un usuario.
* Atributos: id, usuarioId, contenido, puntuacion, fecha.
* Métodos: editarContenido(nuevoContenido), editarPuntuacion(nuevaPuntuacion).

**Autor (ValueObject):** Representa al autor del libro como un valor inmutable.
* Atributos: nombre, biografia.
* Métodos: validarNombre().

**Titulo (ValueObject):** Representa el título del libro, asegurando su validez.
* Atributos: valor.
* Métodos: validarNoVacio().

**Descripcion (ValueObject):** Representa la descripción del libro con una longitud controlada.
* Atributos: texto.
* Métodos: validarLongitudMaxima().

**LibroAggregate (Aggregate):** Agrupa un libro con sus reseñas, garantizando consistencia en las operaciones.
* Atributos: libro, listaReseñas.
* Métodos: validarReseñaUnica(usuarioId), agregarReseñaValidada(reseña).

**ReseñaService (DomainService):** Gestiona reglas de negocio relacionadas a reseñas.
* Métodos: validarReseñaDuplicada(libroId, usuarioId), calcularPromedioLibro(libroId).

**LibroRepository (Repository):** Define operaciones de persistencia para libros.
* Métodos: guardar(libro), buscarPorId(id), buscarPorTitulo(titulo).

**ReseñaRepository (Repository):** Define operaciones de persistencia para reseñas.
* Métodos: guardar(reseña), buscarPorLibro(libroId), eliminar(reseñaId).

##### Interface Layer

**LibroController (Controller):** Gestiona las peticiones HTTP relacionadas con libros.
* Métodos: crearLibro(request), obtenerLibro(id), listarLibrosPorTitulo(titulo).

ReseñaController (Controller): Gestiona las operaciones sobre reseñas de libros.
* Métodos: agregarReseña(libroId, request), editarReseña(reseñaId, request), eliminarReseña(reseñaId).


##### Application Layer

**CrearLibroHandler (Command Handler):** Maneja el comando de crear un nuevo libro.
* Métodos: handle(crearLibroCommand).

**AgregarReseñaHandler (Command Handler):** Maneja el comando de agregar una reseña a un libro.
* Métodos: handle(agregarReseñaCommand).

**EditarReseñaHandler (Command Handler):** Maneja el comando para modificar una reseña existente.
* Métodos: handle(editarReseñaCommand).

**ReseñaAgregadaHandler (Event Handler):** Reacciona al evento de reseña agregada.
* Métodos: onReseñaAgregada(event).

##### Infrastructure Layer

**LibroRepositoryImpl (Repository Impl):** Implementa la persistencia de libros y la interfaz LibroRepository.
* Métodos: guardar(libro), buscarPorId(id), buscarPorTitulo(titulo).

**ReseñaRepositoryImpl (Repository Impl):** Implementa la persistencia de reseñas y la interfaz ReseñaRepository.
* Métodos: guardar(reseña), buscarPorLibro(libroId), eliminar(reseñaId).

#### 4.7.2.3. Bounded Context: Recommendations

##### Domain Layer

**Recomendacion (Entity):** Representa una recomendación generada para un usuario, basada en su historial o preferencias.
* Atributos: id, usuarioId, listaLibros, fechaGeneracion.
* Métodos: actualizarListaLibros(nuevaLista), marcarComoVista().

**AlgoritmoRecomendacion (DomainService):** Encapsula la lógica de generación de recomendaciones.
* Métodos: generar(usuarioId), reentrenarModelo().

**PreferenciasUsuario (ValueObject):** Representa las preferencias inmutables del usuario que influyen en las recomendaciones.
* Atributos: generosFavoritos, autoresFavoritos, rangoPrecio, idioma.
* Métodos: validarPreferencias().

**HistorialLectura (Entity):** Representa el conjunto de libros consumidos por el usuario.
* Atributos: usuarioId, listaLibrosLeidos.
* Métodos: registrarLectura(libroId), obtenerLibrosRecientes().

**RecomendacionAggregate (Aggregate):** Agrupa la recomendación, el historial y las preferencias para generar sugerencias consistentes.
* Atributos: recomendacion, historialLectura, preferenciasUsuario.
* Métodos: generarRecomendacion(), validarRecomendacion().

**RecomendacionRepository (Repository):** Define operaciones de persistencia para las recomendaciones.
* Métodos: guardar(recomendacion), obtenerPorUsuario(usuarioId).

##### Interface Layer

**RecomendacionController (Controller):** Gestiona las peticiones HTTP relacionadas con recomendaciones.
* Métodos: obtenerRecomendaciones(usuarioId), refrescarRecomendaciones(usuarioId).

##### Application Layer

**GenerarRecomendacionHandler (Command Handler):** Maneja el comando de generar una nueva recomendación para un usuario.
* Métodos: handle(generarRecomendacionCommand).

**ActualizarRecomendacionHandler (Command Handler):** Maneja el comando de actualizar la lista de recomendaciones de un usuario.
* Métodos: handle(actualizarRecomendacionCommand).

**RecomendacionGeneradaHandler (Event Handler):** Reacciona al evento de recomendación generada.
* Métodos: onRecomendacionGenerada(event).

##### Infrastructure Layer

**RecomendacionRepositoryImpl (Repository Impl):** Implementa la persistencia de recomendaciones y la interfaz RecomendacionRepository.
* Métodos: guardar(recomendacion), obtenerPorUsuario(usuarioId).

#### 4.7.2.4. Bounded Context: Cart

##### Domain Layer

**Carrito (Entity):** Representa el carrito de un usuario, donde se almacenan los libros seleccionados para compra.
*	Atributos: idCarrito, usuarioId, listaItems, fechaCreacion.
*	Métodos: agregarItem(item), eliminarItem(itemId), vaciarCarrito(), calcularTotal().

**ItemCarrito (Entity):** Representa un libro específico dentro del carrito con su cantidad.
*	Atributos: libroId, cantidad, precioUnitario.
*	Métodos: actualizarCantidad(nuevaCantidad), calcularSubtotal().

**CarritoAggregate (Aggregate):** Agrupa el carrito y sus ítems para mantener consistencia en las operaciones.
*	Atributos: carrito, listaItems.
*	Métodos: confirmarCarrito(), validarStock().

**CarritoRepository (Repository):** Define operaciones de persistencia sobre los carritos.
*	Métodos: guardar(carrito), obtenerPorUsuario(usuarioId), eliminar(carritoId).

##### Interface Layer

**CarritoController (Controller):** Gestiona las peticiones HTTP relacionadas con el carrito.
*	Métodos: verCarrito(usuarioId), agregarLibro(request), eliminarLibro(request), vaciar(usuarioId), confirmarCompra(usuarioId).

##### Application Layer

**AgregarItemCarritoHandler (Command Handler):** Maneja el comando para agregar un libro al carrito.
*	Métodos: handle(agregarItemCarritoCommand).

**EliminarItemCarritoHandler (Command Handler):** Maneja el comando para eliminar un libro del carrito.
*	Métodos: handle(eliminarItemCarritoCommand).

**ConfirmarCarritoHandler (Command Handler):** Maneja el comando de confirmar un carrito antes de generar una orden.
*	Métodos: handle(confirmarCarritoCommand).

**CarritoConfirmadoHandler (Event Handler):** Reacciona al evento de carrito confirmado (ej. generar una orden en el contexto Órdenes).
*	Métodos: onCarritoConfirmado(event).

##### Infrastructure Layer

**CarritoRepositoryImpl (Repository Impl):** Implementa la persistencia de carritos y la interfaz CarritoRepository.
*	Métodos: guardar(carrito), obtenerPorUsuario(usuarioId), eliminar(carritoId).

#### 4.7.2.5. Bounded Context: Profile

##### Domain Layer

**Perfil (Entity):** Representa la información personal de un usuario en Livria.
* Atributos: perfilId, usuarioId, nombre, fotoPerfil, frase, preferencias.
* Métodos: actualizarDatos(datos), actualizarFoto(nuevaFoto), actualizarFrase(nuevaFrase).

**Preferencias (ValueObject):** Define las configuraciones y gustos literarios de un usuario.
* Atributos: generosFavoritos, idiomaPreferido, notificaciones.
* Métodos: actualizarPreferencias(nuevasPreferencias).

**PerfilAggregate (Aggregate):** Agrupa al perfil y sus preferencias, asegurando consistencia en las actualizaciones.
* Atributos: perfil, preferencias.
* Métodos: personalizarPerfil(), validarDatos().

**PerfilRepository (Repository):** Define operaciones de persistencia de perfiles.
* Métodos: guardar(perfil), obtenerPorUsuario(usuarioId), eliminar(perfilId).

##### Interface Layer

**PerfilController (Controller):** Gestiona las peticiones HTTP relacionadas con el perfil.
* Métodos: verPerfil(usuarioId), actualizarPerfil(request), actualizarFoto(request), actualizarFrase(request).

##### Application Layer

**ActualizarPerfilHandler (Command Handler):** Maneja el comando de actualización de datos del perfil.
* Métodos: handle(actualizarPerfilCommand).

**ActualizarFotoHandler (Command Handler):** Maneja el comando de actualización de foto.
* Métodos: handle(actualizarFotoCommand).

**ActualizarFraseHandler (Command Handler):** Maneja el comando de actualización de frase en el perfil.
* Métodos: handle(actualizarFraseCommand).

**PerfilActualizadoHandler (Event Handler):** Reacciona al evento de perfil actualizado.
* Métodos: onPerfilActualizado(event).

##### Infrastructure Layer

**PerfilRepositoryImpl (Repository Impl):** Implementa la persistencia de perfiles y la interfaz PerfilRepository.
* Métodos: guardar(perfil), obtenerPorUsuario(usuarioId), eliminar(perfilId).

#### 4.7.2.6. Bounded Context: Orders

##### Domain Layer

**Orden (Entity):** Representa una compra realizada por un usuario.
* Atributos: ordenId, usuarioId, fecha, estado, total, listaItems.
* Métodos: calcularTotal(), cambiarEstado(nuevoEstado).

**ItemOrden (ValueObject):** Representa un libro dentro de una orden, con su cantidad y precio en el momento de la compra.
* Atributos: libroId, titulo, cantidad, precioUnitario.
* Métodos: calcularSubtotal().

**OrdenAggregate (Aggregate):** Agrupa la orden y sus ítems, asegurando la consistencia en el flujo de compra.
* Atributos: orden, listaItems.
* Métodos: agregarItem(item), eliminarItem(libroId), confirmarOrden().

**OrdenRepository (Repository):** Define operaciones de persistencia de órdenes.
* Métodos: guardar(orden), obtenerPorId(ordenId), obtenerPorUsuario(usuarioId).

##### Interface Layer

**OrdenController (Controller):** Gestiona las peticiones HTTP relacionadas con las órdenes.
* Métodos: verOrden(ordenId), verOrdenesPorUsuario(usuarioId), crearOrden(request), actualizarEstado(request).

##### Application Layer

**CrearOrdenHandler (Command Handler):** Maneja el comando para crear una nueva orden.
* Métodos: handle(crearOrdenCommand).

**ActualizarEstadoOrdenHandler (Command Handler):** Maneja el comando de cambio de estado de una orden.
* Métodos: handle(actualizarEstadoOrdenCommand).

**OrdenCreadaHandler (Event Handler):** Reacciona al evento de orden creada.
* Métodos: onOrdenCreada(event).

**OrdenActualizadaHandler (Event Handler):** Reacciona al evento de cambio de estado en la orden.
* Métodos: onOrdenActualizada(event).

##### Infrastructure Layer

**OrdenRepositoryImpl (Repository Impl):** Implementa la persistencia de órdenes y la interfaz OrdenRepository.
* Métodos: guardar(orden), obtenerPorId(ordenId), obtenerPorUsuario(usuarioId).

#### 4.7.2.7. Bounded Context: Stock

##### Domain Layer

**Inventario (Entity):** Representa el estado del inventario de un libro.
* Atributos: inventarioId, libroId, cantidadDisponible, ultimaActualizacion.
* Métodos: aumentarStock(cantidad), disminuirStock(cantidad), verificarDisponibilidad(cantidad).

**MovimientoStock (ValueObject):** Representa una variación puntual en el stock (entrada o salida).
* Atributos: tipoMovimiento (entrada/salida), cantidad, fechaHora.
* Métodos: esEntrada(), esSalida().

**StockAggregate (Aggregate):** Agrupa el inventario y los movimientos de stock, asegurando consistencia en las actualizaciones.
* Atributos: inventario, listaMovimientos.
* Métodos: registrarEntrada(cantidad), registrarSalida(cantidad).

**StockRepository (Repository):** Define operaciones de persistencia del inventario.
* Métodos: guardar(inventario), obtenerPorLibro(libroId), registrarMovimiento(movimiento).

##### Interface Layer

**StockController (Controller):** Gestiona las peticiones HTTP relacionadas con el inventario.
* Métodos: verStock(libroId), actualizarStock(request), registrarEntrada(request), registrarSalida(request).

##### Application Layer

**ActualizarStockHandler (Command Handler):** Maneja el comando de modificar las existencias de un libro.
* Métodos: handle(actualizarStockCommand).

**RegistrarEntradaHandler (Command Handler):** Maneja el comando de registrar una nueva entrada de inventario.
* Métodos: handle(registrarEntradaCommand).

**RegistrarSalidaHandler (Command Handler):** Maneja el comando de registrar una salida de inventario.
* Métodos: handle(registrarSalidaCommand).

**StockActualizadoHandler (Event Handler):** Reacciona al evento de stock actualizado.
* Métodos: onStockActualizado(event).

##### Infrastructure Layer

**StockRepositoryImpl (Repository Impl):** Implementa la persistencia de inventarios y la interfaz StockRepository.
* Métodos: guardar(inventario), obtenerPorLibro(libroId), registrarMovimiento(movimiento).

#### 4.7.2.8. Bounded Context: Communities

##### Domain Layer

**Comunidad (Entity):** Representa una comunidad dentro de la plataforma.
* Atributos: comunidadId, nombre, descripcion, politicaVisibilidad, fechaCreacion, creadorId.
* Métodos: cambiarNombre(nuevoNombre), cambiarDescripcion(nuevaDescripcion), actualizarPolitica(visibilidad).

**Miembro (Entity):** Representa a un usuario dentro de una comunidad.
* Atributos: comunidadId, usuarioId.

**Publicacion (Entity):** Representa una publicación dentro de una comunidad.
* Atributos: publicacionId, comunidadId, autorId, contenido, fechaHora.
* Métodos: editarContenido(nuevoContenido), eliminarPublicacion().

**Comentario (ValueObject):** Representa un comentario asociado a una publicación.
* Atributos: comentarioId, autorId, contenido, fechaHora.
* Métodos: esValido().

**ComunidadAggregate (Aggregate):** Agrupa comunidad, miembros y publicaciones para mantener consistencia en interacciones.
* Atributos: comunidad, listaMiembros, listaPublicaciones.
* Métodos: agregarMiembro(usuarioId, rol), removerMiembro(usuarioId), crearPublicacion(contenido).

**ComunidadRepository (Repository):** Define operaciones de persistencia sobre comunidades y sus interacciones.
* Métodos: guardar(comunidad), obtenerPorId(comunidadId), obtenerPorUsuario(usuarioId).

##### Interface Layer

**ComunidadController (Controller):** Gestiona las peticiones HTTP relacionadas con comunidades.
* Métodos: crearComunidad(request), verComunidad(comunidadId), unirseComunidad(usuarioId, comunidadId), publicar(comunidadId, request).

##### Application Layer

**CrearComunidadHandler (Command Handler):** Maneja el comando de creación de una nueva comunidad.
* Métodos: handle(crearComunidadCommand).

**UnirseComunidadHandler (Command Handler):** Maneja el comando de adhesión de un usuario a una comunidad.
* Métodos: handle(unirseComunidadCommand).

**PublicarHandler (Command Handler):** Maneja el comando de crear una nueva publicación en una comunidad.
* Métodos: handle(publicarCommand).

**NuevaPublicacionHandler (Event Handler):** Reacciona al evento de publicación creada (ej. notificar a miembros).
* Métodos: onNuevaPublicacion(event).

##### Infrastructure Layer

**ComunidadRepositoryImpl (Repository Impl):** Implementa la persistencia de comunidades y la interfaz ComunidadRepository.
* Métodos: guardar(comunidad), obtenerPorId(comunidadId), obtenerPorUsuario(usuarioId).

## 4.8. Database Design

### 4.8.1. Relational/Non-Relational Database Diagram

#### 4.8.1.1. Bounded Context: Search

<p align="center">
  <img src="https://imgur.com/LILcKls.jpg" alt="12231">
</p>

Debido a la funcionalidad específica del bounded context de Search, no es necesario incluir una tabla representativa dentro de la base de datos, ya que este se basa en un algoritmo que emplea la información de la entidad “Book" para mostrar resultados relacionados a una consulta escrita por el usuario en determinado momento. En este caso, la función de búsqueda realiza comparaciones con información como el título y autor para encontrar resultados asociados, facilitando la exploración del amplio catálogo de Livria y el descubrimiento de material relevante para el usuario.


#### 4.8.1.2. Bounded Context: Book

<p align="center">
  <img src="https://imgur.com/itCc0rF.jpg" alt="12231">
</p>

El diseño de la base de datos para el bounded context de Book se basa en la separación de sus entidades centrales libro y reseña. Esta división estratégica en las tablas Book y Review asegura que cada entidad tenga su propia responsabilidad, lo que refuerza la cohesión del dominio.

La tabla Book es el corazón de este contexto. Su importancia radica en que actúa como el agregado principal y se relaciona con múltiples tablas, como UserFavoriteBooks, UserBannedBooks, y CartItem, demostrando su papel central en el ecosistema de la aplicación. Por otro lado, la tabla Review tiene un rol más específico. Se relaciona solo con las tablas UserClient y Book, lo que refleja su naturaleza simple pero vital. Una reseña solo puede ser escrita por un único usuario y está ligada a un solo libro, lo que se representa con una relación de uno a muchos, manteniendo la integridad y la coherencia de los datos.

#### 4.8.1.3. Bounded Context: Recommendations

<p align="center">
  <img src="https://imgur.com/1DtnCPm.jpg" alt="12231">
</p>

Para el bounded context de Recomendaciones, existe una tabla designada en la base de datos que actúa como intermediario entre las tablas Book y UserClient. Sin embargo, la funcionalidad de este bounded context se basa en un algoritmo que obtiene información de tablas ya existentes para procesar posibles títulos de interés para un usuario en específico. Este algoritmo utiliza la información del detalle de todos los libros, un historial de compra y visualizaciones del usuario, una lista de libros marcados como “Favoritos” y “No recomendar” y la información de un usuario individual, obtenida a través de su identificador único.

Los atributos de la entidad “Recommendation” son tres: una foreign key de una tabla UserClient, una lista de identificadores de libros (foreign keys de tablas Book) y un identificador único (id) debido a las propiedades del gestor de base de datos. El uso del identificador único de esta entidad no es requerido para el funcionamiento de la aplicación, por lo que fue omitido durante el diseño del diagrama de base de datos.

#### 4.8.1.4. Bounded Context: Cart

<p align="center">
  <img src="https://imgur.com/F72xCNp.jpg" alt="12231">
</p>

El diseño de la base de datos para el bounded context de Cart se basa en la división de sus entidades centrales el carrito y los artículos dentro del carrito. Esta segmentación en las tablas Cart y CartItem es fundamental para reflejar la lógica de negocio de la compra. La tabla Cart actúa como el contenedor principal que representa el carrito de un usuario, mientras que la tabla CartItem almacena los libros específicos y sus detalles de compra. Esta separación es clave para mantener la cohesión del dominio, permitiendo una gestión eficiente y autónoma del proceso de compra.

La relación entre las tablas Cart y CartItem es de uno a muchos. Un carrito de compras puede contener múltiples artículos, pero cada artículo pertenece a un único carrito. Esta relación es crucial para reflejar con precisión la cantidad de libros agregados a un carrito de compra específico.

#### 4.8.1.5. Bounded Context: Profile

<p align="center">
  <img src="https://imgur.com/evVrQGi.jpg" alt="12231">
</p>

El diseño de la base de datos para el bounded context de Profile se basa en la separación de las entidades UserClient y Preferences. La tabla UserClient encapsula el perfil público del usuario, mientras que la tabla Preferences funciona como un value object, conteniendo atributos que, aunque son cruciales, no requieren una identidad propia. Esta segmentación es fundamental para la cohesión del dominio, asegurando que la información de perfil y las preferencias de configuración se gestionen de manera eficiente y autónoma.

La tabla UserClient es fundamental para el negocio, ya que representa la identidad del usuario y actúa como el centro de diversas funcionalidades clave. Su rol es crucial al interactuar con tablas como Order, Cart y la tabla intermedia de Comunidades, lo que demuestra su participación en los flujos de negocio más importantes de la plataforma. La relación de uno a uno con la tabla Preferences se ha diseñado intencionalmente, ya que Preferences funciona como un value object que encapsula la configuración personal del usuario sin requerir una identidad propia.

#### 4.8.1.6. Bounded Context: Orders

<p align="center">
  <img src="https://imgur.com/4pJf81f.jpg" alt="12231">
</p>

El diseño de la base de datos para el bounded context de Órdenes se fundamenta en la distinción clara entre la orden en sí y los artículos que la componen. Esta segmentación en las tablas Order y OrderItem es esencial para modelar la naturaleza inmutable de una transacción finalizada. La tabla Order actúa como un agregado raíz que encapsula la información de la compra completa, mientras que OrderItem almacena los detalles específicos de cada libro adquirido. Esta separación asegura la cohesión del dominio y la integridad de los datos de la transacción.

La tabla Order mantiene una relación de uno a muchos con la tabla OrderItem. Esta conexión es fundamental, ya que una orden puede contener uno o varios artículos, pero cada artículo pertenece a una sola orden. Por otro lado, la decisión de no relacionar directamente Order con Cart se alinea con una arquitectura orientada a eventos. El Carrito es una entidad temporal y mutable que representa una intención de compra. Una vez que se confirma la transacción, la orden se convierte en una entidad inmutable y permanente. Así, la orden se crea a partir del contenido del carrito, pero no depende de su existencia posterior. Este enfoque asegura la cohesión de cada dominio y evita dependencias innecesarias, lo que hace que el sistema sea más robusto y fácil de mantener.

#### 4.8.1.7. Bounded Context: Stock

<p align="center">
  <img src="https://imgur.com/Xa6HYxx.jpg" alt="12231">
</p>

El bounded context de Stock no presenta tablas dentro de la base de datos debido a su funcionamiento específico, que utiliza la información contenida en tablas ya existentes, como Book y Order, para mostrar datos relevantes dentro de la vista de administrador tras una verificación exitosa (inicio de sesión de administrador). En el caso de esta funcionalidad, se muestran datos como la cantidad de libros en el inventario (atributo “stock” de la tabla Book) en una lista que permite una visualización rápida de sus detalles (atributos “title”, “cover” y “price”), lo que facilita el uso de la vista del administrador y optimiza los procesos de análisis de inventario.

#### 4.8.1.8. Bounded Context: Communities

<p align="center">
  <img src="https://imgur.com/4dhzi4m.jpg" alt="12231">
</p>

El diseño de base de datos para el bounded context de Communities se basa en la segmentación de sus entidades clave en las tablas Community, UserCommunity, Post y Comment. Esta separación es crucial para la cohesión del dominio, ya que permite que cada entidad sea gestionada de manera autónoma, reflejando la complejidad del aspecto social del negocio de Livria. La tabla UserCommunity actúa como una tabla intermedia que resuelve la relación de muchos a muchos entre usuarios y comunidades, mientras que Post y Comment se relacionan con sus respectivos agregados y usuarios a través de claves foráneas, garantizando que el ecosistema social opere con integridad y eficiencia.

---

# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

#### Project Management

Jira:  
    Jira Software, una herramienta de gestión de proyectos ágiles desarrollada por Atlassian, fue seleccionada como herramienta de gestión de proyecto por su excelente compatibilidad con metodologías como Scrum o Kanban. Su propósito central es facilitar la planificación, organización y el seguimiento colaborativo del trabajo, ofreciendo funcionalidades esenciales como la gestión del backlog, la planificación detallada de sprints y el monitoreo del progreso en tiempo real mediante tableros personalizables. Para el proyecto de Livria, la utilidad de Jira es clave al permitir modelar el flujo de trabajo ágil, utilizándose específicamente para la gestión de Sprints y el manejo exhaustivo de las Historias de Usuario (User Stories) de la aplicación móvil, asegurando que el desarrollo de la aplicación móvil y sus funcionalidades se alinee consistentemente con los objetivos del producto y facilite la optimización continua del trabajo en equipo.  
     
    [https://www.atlassian.com/es/software/jira](https://www.atlassian.com/es/software/jira)
<p align="center">
  <img src="https://i.imgur.com/hL6B3qm.png" alt="12171">
</p>

#### Product UX/UI Design

Figma  
    Para el diseño de la Experiencia de Usuario (UX) y la Interfaz de Usuario (UI), se ha seleccionado Figma, una poderosa herramienta de diseño colaborativo que opera completamente en línea. Su propósito principal es permitir la creación, diseño y prototipado interactivo de las interfaces, facilitando una colaboración fluida y en tiempo real entre diseñadores y desarrolladores. Figma es altamente eficiente en entornos ágiles porque mantiene la fuente de verdad del diseño centralizada. En el desarrollo de Livria, la utilidad de Figma se centrará en elaborar la arquitectura de la información y los mockups de alta fidelidad para la aplicación móvil. Esto asegura que la estética, usabilidad y accesibilidad del producto final se definan antes de la codificación, reduciendo retrabajos y garantizando una experiencia de usuario coherente.

    [https://www.figma.com/](https://www.figma.com/)
<p align="center">
  <img src="https://i.imgur.com/Qm8PVh7.png" alt="12171">
</p>

#### Software Development

Android Studio  
    Para el desarrollo del frontend de la aplicación móvil de Livria, se utilizará Android Studio, el Entorno de Desarrollo Integrado (IDE) oficial proporcionado por Google, diseñado para la creación de aplicaciones nativas de Android. Su propósito es ofrecer a los desarrolladores un conjunto de herramientas completo que incluye un sistema de compilación flexible (Gradle), un emulador avanzado de dispositivos Android (AVD), potentes herramientas de debugging y plantillas de código para acelerar el desarrollo. En este proyecto, Android Studio será la plataforma principal para construir la interfaz de usuario, tanto para vistas de administrador como de usuarios de tipo cliente, asegurando la optimización y el rendimiento en el ecosistema Android.

    [https://developer.android.com/studio?hl=es-419](https://developer.android.com/studio?hl=es-419)
<p align="center">
  <img src="https://i.imgur.com/p9S4yaj.png" alt="12171">
</p>

 Rider  
    Complementando el frontend, el Backend del proyecto será desarrollado y gestionado utilizando Rider, el IDE multiplataforma de JetBrains orientado a proyectos .NET y web. Rider es la herramienta escogida por su compatibilidad con ASP.NET Core y sus sólidas funcionalidades de integración con bases de datos, lo que lo hace ideal para construir una API robusta y escalable. Su utilidad en Livria radica en el desarrollo de la lógica de negocio central, la gestión de la autenticación de usuarios y el manejo de los endpoints que conectarán la aplicación Android con la base de datos propia del proyecto, garantizando un desarrollo eficiente y con un alto nivel de refactorización de código.  
     
    [https://www.jetbrains.com/rider/](https://www.jetbrains.com/rider/)
<p align="center">
  <img src="https://i.imgur.com/1vjtPzR.png" alt="12171">
</p>

#### Software Deployment 

 Firebase  
    Para el soporte de la infraestructura de la aplicación móvil, se utilizará Firebase, una plataforma de desarrollo de aplicaciones móviles y web respaldada por Google. Aunque el backend principal está desarrollado en Rider, Firebase proporciona un ecosistema de servicios clave para la aplicación Android. Su propósito principal es ofrecer herramientas de monitoreo de rendimiento y estabilidad (Crashlytics), servicios de mensajería push (FCM), y configuraciones dinámicas (Remote Config). En Livria, la utilidad de Firebase garantizará que el rendimiento de las funciones críticas, como las transacciones de la tienda y las interacciones de la comunidad, pueda ser supervisado y gestionado de manera eficiente tras el lanzamiento.  
    
    [https://firebase.google.com/?hl=es-419](https://firebase.google.com/?hl=es-419)
<p align="center">
  <img src="https://i.imgur.com/DlRwQDc.png" alt="12171">
</p>

  Google Play Console:
    El proceso final de publicación y distribución de la aplicación móvil de Livria se llevará a cabo a través de Google Play Console. Esta es la plataforma oficial de Google para que los desarrolladores gestionen, publiquen y actualicen sus aplicaciones en la Google Play Store. Su propósito es funcionar como el canal de deployment directo al usuario final, proporcionando herramientas esenciales para la gestión de lanzamientos, pruebas beta, precios y la recopilación de métricas de instalación. La Console será fundamental para que el equipo logre una distribución controlada de las versiones de la aplicación, asegurando que las funcionalidades desarrolladas lleguen a los usuarios de Android de manera segura y gestionada.  
     
    [https://developer.android.com/distribute/console?hl=es-419](https://developer.android.com/distribute/console?hl=es-419) 
<p align="center">
  <img src="https://i.imgur.com/j3ISZ5H.png" alt="12171">
</p>

### 5.1.2. Source Code Management

La gestión del código fuente es fundamental para el desarrollo colaborativo de cualquier proyecto de software. En esta sección, el equipo establece el esquema de organización y control de versiones que aplicará para el seguimiento de modificaciones, utilizando GitHub como plataforma y sistema. Para ello, se empleará el modelo GitFlow y se definirán convenciones claras para nombres de ramas y mensajes de commits, además de usar Semantic Versioning para las versiones del proyecto. Esto garantizará una estructura organizada y accesible del código.

1. **Repositorios en Github:**

Para optimizar la organización del código y las pruebas, se implementarán repositorios específicos en GitHub. Cada uno cumplirá una función definida dentro del desarrollo y control de calidad del proyecto, garantizando una gestión estructurada y eficiente del ciclo de trabajo.

**Landing Page**

Este repositorio estará dedicado exclusivamente al desarrollo de la Landing Page de Livria. Incluirá todo el código y los recursos asociados a la interfaz inicial del proyecto, como archivos HTML, CSS, JavaScript, imágenes y demás elementos Front-End, orientados a ofrecer una presentación atractiva, funcional y coherente con la propuesta de valor de la aplicación para los visitantes.

<p align="center">
  <img src="https://imgur.com/7EMIS6x.png" alt="Landing Page Repository">
</p>

**Report**

Este repositorio estará destinado al almacenamiento y control de versiones del informe completo del proyecto Livria. Contendrá los documentos en formato .md vinculados al proceso de documentación, planificación y análisis del proyecto, permitiendo mantener un seguimiento estructurado y actualizado de los avances en la elaboración del informe.

<p align="center">
  <img src="https://imgur.com/wWLcukh.png" alt="Report Repository">
</p>

**Livria Admin**

Este repositorio contiene el código fuente y la arquitectura de la aplicación móvil nativa desarrollada en Kotlin para la gestión administrativa. Está diseñado específicamente para que los dueños de librerías y administradores puedan supervisar el inventario, analizar las estadísticas de ventas en tiempo real y gestionar el estado de las órdenes de manera eficiente, ofreciendo una interfaz robusta y optimizada para dispositivos Android.

<p align="center">
  <img src="https://imgur.com/GkGfge7.png" alt="Admin Repository">
</p>

**Livria User**

Este repositorio está dedicado al desarrollo de la aplicación móvil orientada al cliente final. A través de esta interfaz nativa, los usuarios pueden explorar el catálogo de libros, gestionar sus perfiles personales y realizar compras. El enfoque principal es proporcionar una experiencia de usuario fluida y atractiva que facilite el acceso a la lectura y la interacción con los servicios de Livria.

<p align="center">
  <img src="https://imgur.com/wS7S8Su.png" alt="User Repository">
</p>

**Livria Web Services**

Este repositorio centraliza el desarrollo del backend del ecosistema Livria, implementado mediante una RESTful API construida con .NET Core. Incluye la lógica de negocio, la gestión de la base de datos y los servicios necesarios para garantizar la persistencia de datos y la comunicación fluida entre todas las aplicaciones del proyecto (Admin y User), siguiendo principios de arquitectura limpia y escalabilidad.

<p align="center">
  <img src="https://imgur.com/zS5beSY.png" alt="Web Services Repository">
</p>

**Enlaces:** 

**Repositorio de la Landing Page:**

[**https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-landing-page**](https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-landing-page)

**Repositorio del informe:**

[**https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-report**](https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-report)

**Repositorio de la aplicación móvil para Administradores:**

[**https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-admin**](https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-admin)

**Repositorio de la aplicación móvil para Usuarios:**

[**https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-user**](https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-user)


**Repositorio de los Web Services:**

[**https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-web-services**](https://github.com/upc-pre-202610-1asi0732-12278-defontes/livria-web-services)


2. **Workflow de control de versiones:**

Para asegurar un flujo de trabajo eficiente y una integración organizada de los cambios, se adoptará el modelo GitFlow. Este enfoque define una estructura de ramas clara y jerarquizada, que facilita el desarrollo paralelo, el control de versiones y la colaboración ordenada entre los miembros del equipo.

**Estructura de ramas en GitFlow:**

| Nombre de la rama | Descripción |
| ----- | ----- |
| Main Branch (*main*) | Es la rama principal que contiene el código estable y listo para producción. Solo se integrarán en ella los cambios completamente probados, verificados y aprobados, garantizando que el entorno de producción mantenga la máxima estabilidad y calidad del software. |
| Develop Branch (*develop*) | En esta rama se integran todas las funcionalidades en desarrollo, sirviendo como la base principal de trabajo antes de que los cambios sean fusionados con la rama main. Actúa como un entorno de integración continua donde se validan y consolidan las nuevas implementaciones. |
| Feature Branches (*feature/\**) | Para cada nueva funcionalidad o cambio significativo, se debe crear una rama de tipo feature derivada de la rama develop. Este enfoque permite que el desarrollo se realice de forma aislada y controlada, evitando interferencias con el código principal y facilitando la integración posterior. **Ejemplo de nomenclatura:** feature/nueva-funcionalidad |

**Convenciones para nombres de ramas**

* **Feature Branches:** *feature/nombre-descriptivo*

  Nombres que describan claramente la funcionalidad o la tarea en desarrollo.

**Convenciones de commits (Conventional Commits)**

Para mantener la claridad y consistencia en los mensajes de commit, se adoptará el estándar Conventional Commits.

Este sistema permite identificar fácilmente el tipo de cambio realizado en cada commit, facilitando la revisión del historial, la automatización de versiones y la integración continua.

Cada mensaje de commit deberá estructurarse con un tipo de cambio seguido de una breve descripción del ajuste realizado.

**Tipos de cambios y ejemplos:**

* **feat:** *agregar footer*

  Indica la implementación de una nueva característica o componente en el proyecto.

### 5.1.3. Source Code Style Guide & Conventions

Este capítulo establece las pautas y convenciones que el equipo de desarrollo adoptará para garantizar la coherencia, legibilidad y calidad del código en la aplicación Livria. Las convenciones abordarán los lenguajes utilizados en el proyecto: HTML, CSS, JavaScript y Kotlin. Asimismo, se emplea una nomenclatura en inglés para todos los elementos del código, tomando como referencia las mejores prácticas y guías de estilo reconocidas:

* **HTML Style Guide and Coding Conventions**  
* **Google HTML/CSS Style Guide**  
* **Google JavaScript Style Guide**  
* **MDN JavaScript Guidelines**  
* **W3C JavaScript Style Guide**  
* **Kotlin Coding Conventions (JetBrains)**  
* **Android Developers Kotlin Style Guide**

Para el desarrollo de la Landing Page de *Livria* se emplearon las tecnologías HTML, CSS y JavaScript, responsables de definir la estructura, el diseño y la funcionalidad del sitio. La correcta organización y estandarización del código garantizan un desarrollo consistente, mantenible y comprensible para cualquier miembro del equipo.

**HTML:**  
Define la estructura y el contenido de la página, asegurando una semántica adecuada y una jerarquía clara de elementos que favorece la accesibilidad y el posicionamiento SEO.

**CSS:**  
Controla el estilo visual de la interfaz, garantizando un diseño responsive y coherente mediante el uso de clases y sectores bien definidos. Se evita el uso de estilos en línea, priorizando un enfoque modular y reutilizable.

**JavaScript:**  
Aporta la interactividad y funcionalidad dinámica necesarias para optimizar la experiencia del usuario, empleando funciones y variables descriptivas junto con una estructura lógica y escalable que facilite el mantenimiento.

La adopción de estas convenciones permite mantener una base de código limpia, legible y preparada para la evolución continua del proyecto.

Principios Generales

* Todo el código debe estar documentado y utilizar nomenclatura en inglés.  
* La indentación debe ser consistente en todos los archivos.  
* El código debe ser fácil de leer, comprender y mantener.  
* Se debe aplicar el principio DRY (Don’t Repeat Yourself) para evitar redundancias y mejorar la eficiencia.

**HTML:**

**Convenciones de Formato**

* Utilizar 2 espacios para indentación.

\<div class\="book"\>

    \<h3\>Title\</h3\>

    \<p\>Genre\</p\>

\</div\> 

* Utilizar minúsculas para los nombres de elementos y atributos.  
* Emplear comillas dobles (") para los valores de los atributos.  
* Cerrar siempre todos los elementos HTML, incluso aquellos que son vacíos.  
* Usar etiquetas semánticas siempre que sea posible, para mejorar la estructura y accesibilidad del documento.  
   Ejemplos: \<header\>, \<footer\>, \<main\>, \<section\>, \<article\>, \<nav\>, entre otras.  
* Los atributos deben escribirse en minúsculas y, en caso de nombres compuestos, utilizar guiones (-) en lugar de mayúsculas o guiones bajos.  
   Ejemplo correcto:  
   \<div class="book-list"\>\</div\>  
*  Ejemplo incorrecto:  
   \<div class="BookList"\>\</div\>

**Estructura del Documento:**

Incluir siempre el DOCTYPE de HTML5 al inicio del documento:

 \<\!DOCTYPE html\>

Definir los atributos lang en el elemento \<html\> y charset dentro del \<head\>, para garantizar la correcta interpretación del idioma y codificación del contenido.

 \<html lang="es"\>

\<head\>

    \<meta charset="UTF-8"\>

\</head\>

Cargar las hojas de estilo (CSS) dentro del elemento \<head\> y los scripts de JavaScript justo antes del cierre de \</body\>, salvo en casos debidamente justificados donde sea necesario modificar este orden (por ejemplo, scripts críticos para el renderizado).

**CSS:**

Convenciones de Formato

* Utilizar 2 espacios para la indentación.  
* Incluir un espacio antes de la llave de apertura {.  
* Colocar la llave de cierre } en una nueva línea.  
* Incluir un espacio después de los dos puntos (:) en cada declaración.  
* Finalizar todas las declaraciones con punto y coma (;).  
* Utilizar comillas dobles (") para los valores de tipo *string*.  
* Mantener un orden lógico y consistente de las propiedades CSS. Se recomienda el siguiente orden:

   **1\. Layout:**  
   display, position, top, left, bottom, right, z-index  
   **2\. Box Model:**  
   width, height, padding, margin, border  
   **3\. Tipografía:**  
   font-family, font-size, line-height, text-align  
   **4\. Color:**  
   color, background-color  
   **5\. Visuales:**  
   box-shadow, border-radius, opacity

**Ejemplo general:**

book-card {

    display: flex;

    margin-bottom: 20px;

    border-radius: 4px;

    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);

}

**Convenciones de nomenclatura:**

* Block: Representa un componente independiente.  
   Ejemplo:   .book-card  
* Element: Representa una parte interna del bloque que cumple una función específica.  
   Ejemplo:   .book-card\_\_title  
* Modifier: Indica una variación o estado diferente del bloque o elemento.  
   Ejemplo:   .book-card--featured

**Buenas prácticas adicionales:**

* Evitar el uso excesivo de selectores anidados. Se recomienda no superar los tres niveles de profundidad.  
   Ejemplo:  .book-card\_\_title span { ... }

**JAVASCRIPT**

**Convenciones de formato**

* Utilizar 2 espacios para la indentación.  
* Incluir punto y coma (;) al final de cada declaración.  
* Utilizar comillas simples (') para los valores de tipo string.  
* Nombrar los archivos en kebab-case, es decir, con minúsculas y guiones medios para separar palabras.

**Ejemplo general:**

const getBookDetails \= function(bookId) {

    return fetch(\`/api/books/${bookId}\`)

      .then(response \=\> response.json())

      .catch(error \=\> {

        console.error('Error fetching book details:', error);

        return null;

      });

};

##### 

**Convenciones de Nomenclatura**

* **Variables y funciones:** Usar camelCase.  
   Ejemplo: `bookTitle`, `getUserPreferences`  
* **Clases:** Usar PascalCase.  
   Ejemplo: `BookRepository`, `UserAuthentication`  
* **Constantes globales:** Usar UPPER\_SNAKE\_CASE.  
   Ejemplo: `MAX_RESULTS_PER_PAGE`  
* **Componentes (en entornos de UI o frameworks):** Usar PascalCase.  
   Ejemplo: `BookCard`, `SearchBar`  
* **Propiedades o métodos privados:** Usar guion bajo (`_`) como prefijo.  
   Ejemplo: `_privateMethod`, `_privateVariable`

**Buenas Prácticas**

* Preferir `const` sobre `let`; usar `let` solo cuando el valor debe reasignarse.  
* Evitar el uso de `var` en cualquier contexto.  
* Utilizar funciones flecha (`=>`) para funciones anónimas o *callbacks*.  
* Emplear las características modernas de ES6+, como *destructuring*, *spread operator* y *template literals*.  
* Preferir los métodos funcionales de arrays (`map`, `filter`, `reduce`) en lugar de bucles tradicionales.

*// Good*

const filteredBooks \= books.filter(book \=\> book.inStock);

*// Avoid*

const filteredBooks \= \[\];

for (let i \= 0; i \< books.length; i\++) {

  if (books\[i\].inStock) {

    filteredBooks.push(books\[i\]);

  }

}

##### 

**KOTLIN**

**Convenciones de formato:**

* Utilizar 4 espacios para la indentación (estándar oficial de Kotlin).  
* Dejar un espacio antes y después de los operadores (=, \+, \-, \==, etc.).  
* Colocar una sola instrucción por línea.  
* Incluir una línea en blanco entre las declaraciones de funciones, clases o bloques lógicos.  
* Usar llaves {} incluso en sentencias de una sola línea (por ejemplo, en if o when), para mejorar la claridad.

package com.livria.app.ui

class BookCard(

    val title: String,

    val author: String,

    val isFeatured: Boolean \= false

) {

    fun displayInfo() {

        if (isFeatured) {

            println("🌟 Featured Book: $title by $author")

        } else {

            println("Book: $title by $author")

        }

    }

    fun calculateDiscount(price: Double): Double {

        val discountRate \= if (isFeatured) 0.15 else 0.05

        return price \- (price \* discountRate)

    }

}

##### 

* **Clases y Objetos:** Usar PascalCase.

* **Funciones y Variables:** Usar camelCase, comenzando con minúscula.

* **Constantes y Valores Inmutables (companion objects o globales):** Usar UPPER\_SNAKE\_CASE.

**Buenas Prácticas**

* Usar val en lugar de var siempre que sea posible, para favorecer la inmutabilidad y evitar efectos secundarios.  
* Evitar valores nulos; aprovechar el sistema de seguridad de nulabilidad de Kotlin usando tipos no nulos y el operador seguro ?. cuando sea necesario.  
* Preferir funciones de extensión para agregar comportamiento a clases existentes sin modificarlas.  
* Usar expresiones concisas y aprovechar las funciones lambda para simplificar el código.  
* Evitar el uso innecesario de \!\! (operador de aserción nula), ya que puede provocar excepciones en el tiempo de ejecución.  
  Organizar el código por paquetes según su responsabilidad (por ejemplo: ui, data, domain, utils).

**FLUTTER (DART)**

**Convenciones de Formato**

* Utilizar 2 espacios para la indentación.
* Utilizar comas finales (trailing commas) en argumentos de funciones y constructores de Widgets para facilitar el formateo automático y la lectura.
* Colocar la llave de apertura `{` en la misma línea que la declaración.
* Limitar las líneas a un máximo de 80 caracteres para mejorar la legibilidad en pantallas divididas.

**Ejemplo general:**

```dart
class BookListScreen extends StatelessWidget {
  const BookListScreen({super.key, required this.books});

  final List<Book> books;

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text('Livria Catalog'),
      ),
      body: ListView.builder(
        itemCount: books.length,
        itemBuilder: (context, index) {
          return BookTile(book: books[index]);
        },
      ),
    );
  }
}
```

**Convenciones de Nomenclatura**

* **Clases y Mixins:** Usar PascalCase.
  Ejemplo: `OrderService`, `UserWidget`.
* **Variables, Funciones y Parámetros:** Usar camelCase.
  Ejemplo: `calculateTotal`, `isAvailable`.
* **Archivos y Directorios:** Usar snake_case.
  Ejemplo: `main_screen.dart`, `order_repository_impl.dart`.
* **Extensiones:** Usar PascalCase.
  Ejemplo: `StringExtensions`.
* **Constantes:** Usar camelCase.
  Ejemplo: `maxItemsCount`.

**Buenas Prácticas**

* Utilizar `const` en los constructores de Widgets siempre que sea posible para optimizar el rendimiento del renderizado.
* Preferir el uso de `final` para variables que no serán reasignadas después de su inicialización.
* Evitar el uso de "Magic Numbers"; definir constantes con nombres descriptivos.
* Dividir Widgets grandes en sub-widgets más pequeños y reutilizables para mantener el principio de responsabilidad única.
* Utilizar el operador de nulidad de Dart (`?`, `??`, `?.`) para manejar de forma segura los valores nulos.

---

**C# (.NET)**

**Convenciones de Formato**

* Utilizar 4 espacios para la indentación (estándar de Visual Studio).
* Utilizar llaves en una nueva línea (Estilo Allman) para clases, métodos y bloques de control.
* Incluir una línea en blanco entre métodos y propiedades.
* Utilizar una sola instrucción por línea.

**Ejemplo general:**

```csharp
namespace Livria.Api.Services
{
    public class OrderService : IOrderService
    {
        private readonly IOrderRepository _orderRepository;

        public OrderService(IOrderRepository orderRepository)
        {
            _orderRepository = orderRepository;
        }

        public async Task<OrderResponse> ProcessOrderAsync(OrderRequest request)
        {
            if (request == null)
            {
                throw new ArgumentNullException(nameof(request));
            }

            var order = await _orderRepository.AddAsync(request.ToEntity());
            return OrderResponse.FromEntity(order);
        }
    }
}
```

**Convenciones de Nomenclatura**

* **Clases, Métodos y Propiedades Públicas:** Usar PascalCase.
  Ejemplo: `GetOrders`, `CustomerRepository`.
* **Interfaces:** Usar PascalCase con el prefijo "I".
  Ejemplo: `IBookService`, `IRepository`.
* **Variables Locales y Parámetros:** Usar camelCase.
  Ejemplo: `orderId`, `totalPrice`.
* **Campos Privados (Private Fields):** Usar camelCase con prefijo de guion bajo (`_`).
  Ejemplo: `_dbContext`, `_isInitialized`.
* **Constantes:** Usar PascalCase (recomendado por Microsoft) o UPPER_SNAKE_CASE en configuraciones específicas.

**Buenas Prácticas**

* Utilizar `async` y `await` para todas las operaciones de entrada/salida (I/O) para evitar el bloqueo de hilos.
* Preferir el uso de `var` cuando el tipo de la variable sea evidente en el lado derecho de la asignación.
* Aplicar Inyección de Dependencias para desacoplar componentes y facilitar las pruebas unitarias.
* Utilizar LINQ para operaciones de consulta y manipulación de colecciones de forma declarativa.
* Manejar excepciones de forma específica, evitando bloques `catch (Exception e)` genéricos a menos que sea para logging en el nivel superior.
* Seguir los principios SOLID para garantizar una arquitectura robusta y escalable.

### 5.1.4. Software Deployment Configuration

La estrategia de despliegue de Livria implementa una arquitectura basada en la nube que maximiza la eficiencia operativa, la escalabilidad y la distribución multicanal de sus productos digitales. Esta configuración es híbrida, utilizando Microsoft Azure para los Web Services críticos y plataformas especializadas (GitHub Pages y Firebase) para la distribución de *front-end* y aplicaciones móviles, como se ilustra en el Deployment Diagram adjunto.

<p align="center">
  <img src="https://i.imgur.com/y2xbTsR.jpeg" alt="12171">
</p>

Despliegue de la Aplicación Móvil (Android)

El proceso de despliegue de la aplicación Android se divide en dos fases distintas, utilizando Firebase App Distribution para la gestión de pruebas internas antes de la publicación final.

<p align="center">
  <img src="https://i.imgur.com/ywQ4TDr.png" alt="12171">
</p>

| Componente | Plataformas | Beneficios Clave |
| :---- | :---- | :---- |
| Mobile App | Firebase App Distribution (Pruebas) y Google Play Store (Producción). | Agilidad de Pruebas: Distribución rápida a QA y testers. Alcance: Acceso al mercado global de Android. |

Pasos del Proceso de Despliegue

1. Integración Continua (CI): El código fuente de la aplicación (Kotlin/Compose) se versiona y prueba automáticamente en la pipeline de CI.  
2. Generación de Artefacto: Tras el éxito de las pruebas, se genera el archivo Android App Bundle (.aab).  
3. Distribución Continua (CD): El .aab es cargado automáticamente a Firebase App Distribution, lo que notifica a los testers para que descarguen la versión de prueba de forma instantánea.  
4. Conexión a Backend: El Dispositivo Android accede a los servicios de negocio mediante HTTPS (protocolo seguro) a la API alojada en Azure App Service.  
5. Publicación Final: Una vez que la versión es estable, el .aab se sube manualmente a Google Play Console para su revisión y lanzamiento al público general.

Despliegue de Web Services (Backend / API REST)

El backend aloja toda la lógica de negocio central, siendo el componente más crítico del sistema. Su despliegue se gestiona completamente en el ecosistema Microsoft Azure.

<p align="center">
  <img src="https://i.imgur.com/dPOznbM.png" alt="12171">
</p>

| Componente | Servicios Azure | Beneficios Clave |
| :---- | :---- | :---- |
| Web Services | Azure App Service y Azure SQL Database. | Escalabilidad: Azure App Service gestiona picos de tráfico. Seguridad: Aislamiento de la DB. |

Pasos del Proceso de Despliegue

1. Integración Continua (CI): Se ejecutan pruebas unitarias y de integración sobre el código del backend (API REST).  
2. Generación de Artefacto: Los archivos compilados del backend se empaquetan en un artefacto de despliegue.  
3. Despliegue Continuo (CD): La pipeline automatizada realiza el despliegue al Azure App Service. Este servicio actúa como el punto de exposición de la API, encargándose del balanceo de carga y la disponibilidad.  
4. Configuración de Persistencia: El App Service se configura para conectarse a Azure SQL Database utilizando un Protocolo SQL seguro. Esta base de datos es el único nodo que almacena los datos transaccionales, y no tiene exposición directa a Internet por motivos de seguridad.

Despliegue de la Aplicación Web (Landing Page)

El *Landing Page* es una aplicación estática y de *marketing*. Su despliegue debe ser ágil y de bajo costo.

<p align="center">
  <img src="https://i.imgur.com/ohiYqxj.png" alt="12171">
</p>

| Componente | Plataforma | Beneficios Clave |
| :---- | :---- | :---- |
| Web Browser (Landing Page) | GitHub Pages. | Bajo Costo y Mantenimiento: Despliegue gratuito sin necesidad de gestión de servidores. Rapidez: Publicación directa desde el repositorio. |

Pasos del Proceso de Despliegue

1. Alojamiento en Repositorio: El código fuente (HTML, CSS, JS) se almacena en el repositorio GitHub.  
2. Publicación Automática: Se configura una branch o una GitHub Action específica.  
3. Acceso Público: Cada push a la rama de publicación desencadena la actualización del sitio web, alojado en GitHub Pages. El usuario accede a este contenido directamente desde su Navegador Web vía HTTPS (protocolo seguro).

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs

#### 5.2.1.1 Sprint  1

##### Sprint Planning 1

| Sprint \# | Sprint 1 |
| :---- | :---- |
| **Sprint Planning Background** |  |
| Date | 05/10/2025 |
| Time | 3:30 PM |
| Location | Virtual |
| Prepared by | Ainhoa Lucía Castillo Garay, Cassius Estefano Martel Andrade |
| Attendees (to planning meeting) | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Binda Arbañil / Cassius Estefano Martel Andrade / Alex Tomio Nakamurakare Teruya / Gabriel Sebastián Borja Molina |
| **Sprint Goal & User Stories** |  |
| Sprint 1 Goal | Our focus is on delivering the foundational components of the Livria platform: a complete, visually engaging and interactive Landing Page, a functional core API service (backend) with Swagger documentation, and an initial mobile user experience preview (frontend) featuring an interactive prototype with core screens. We believe it delivers a strong foundation of clarity and trust to potential users and collaborators by clearly articulating Livria's purpose, demonstrating its core backend capabilities, and providing an early visualization of the mobile experience. This will be confirmed when an internal user can successfully navigate through all sections of the landing page like “About Us” and “Contact Us”, access the Swagger documentation to review all specified endpoints, and interact with the simulated user flows on the frontend mobile screens. |
| Sprint 1 Velocity | 45 |
| Sum of Story Points | 40 |

##### Sprint Backlog 1

| Sprint n | Sprint 1 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **User Story** | **Work-Item / Task** | | | | | | |
| **User Story ID** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** | |
| **US01: Presentar Servicios de Livria** | | | | | | | |
| | 1 | Diseño UI de Sección Servicios – Wireframe | Crear el wireframe inicial de la sección de Servicios considerando disposición y jerarquía visual. | 1 | Developer Team | Done |
| | 2 | Diseño UI de Sección Servicios – Versión Visual | Diseñar la versión final con estilos, colores e iconografía para presentar los servicios. | 1 | Developer Team | Done |
| | 3 | Desarrollo Componentes UI de Servicios | Implementar los componentes visuales reutilizables para mostrar los servicios en la Landing Page. | 1.5 | Developer Team | Done |
| | 4 | Integración de Contenido | Incorporar los textos descriptivos finales y asegurar correcta visualización responsiva. | 0.5 | Developer Team | Done |
| **US02: Acceder a la sección “Sobre Nosotros”** | | | | | | | |
| | 1 | Diseño de la Sección "Sobre Nosotros" | Definir la estructura y organización del contenido que mostrará la información del equipo y misión. | 1 | Developer Team | Done |
| | 2 | Maquetación de la Sección "Sobre Nosotros" | Implementar la estructura visual de la sección respetando el diseño aprobado. | 1.5 | Developer Team | Done |
| | 3 | Integración de Assets | Incorporar imágenes o ilustraciones aprobadas que complementen el contenido de la sección. | 0.5 | Developer Team | Done |
| **US03: Cambiar de idioma en la Landing Page** | | | | | | | |
| | 1 | Configuración de Internacionalización | Configurar el sistema de internacionalización para permitir múltiples idiomas en la Landing Page. | 1.5 | Developer Team | Done |
| | 2 | Estructura de Archivos de Traducción | Crear la estructura base para los archivos de traducción con claves organizadas. | 1 | Developer Team | Done |
| | 3 | Contenido de Traducción ES/EN | Redactar e insertar los textos de la Landing Page en español e inglés. | 2.5 | Developer Team | Done |
| | 4 | Implementación del Selector de Idioma | Implementar el componente que permite cambiar el idioma desde el header. | 2 | Developer Team | Done |
| | 5 | Aplicación del Cambio de Idioma | Asegurar que todos los textos cambien correctamente al idioma seleccionado. | 1 | Developer Team | Done |
| **US04: Visualizar la sección “Home” en la landing page** | | | | | | | |
| | 1 | Diseño de la Hero Section | Definir el contenido, estructura y elementos visuales de la sección principal. | 1 | Developer Team | Done |
| | 2 | Implementación de la Hero Section | Desarrollar la sección principal con su mensaje clave y CTA. | 2 | Developer Team | Done |
| | 3 | Navegación al Home | Configurar el logo y el enlace del menú para retornar al inicio con desplazamiento fluido. | 1 | Developer Team | Done |
| **US05: Acceder a la sección “Contáctanos”** | | | | | | | |
| | 1 | Maquetación del Formulario | Crear la estructura visual con campos: nombre, correo y mensaje. | 2 | Developer Team | Done |
| | 2 | Validación y Lógica de Envío (Frontend) | Implementar validaciones básicas de campos y manejo del envío del formulario. | 2 | Developer Team | Done |
| **US06: Navegar de manera simple entre secciones** | | | | | | | |
| | 1 | Estructura Base del Navbar | Crear la estructura del navbar con enlaces ancla a secciones. | 2 | Developer Team | Done |
| | 2 | Comportamiento Sticky y Scroll Suave | Implementar navbar fijo y desplazamiento suave hacia secciones. | 2 | Developer Team | Done |
| | 3 | Versión Mobile del Navbar | Adaptar el menú para mobile e incluir menú hamburguesa. | 2 | Developer Team | Done |
| | 4 | Accesibilidad y Pruebas UX | Asegurar correcto tabbing, contraste y testear navegación. | 1 | Developer Team | Done |
| **US07: Ver un diseño atractivo de la landing page** | | | | | | | |
| | 1 | Definición de Tema Global | Configurar variables globales (colores, tipografías, tamaños) para la UI. | 2 | Developer Team | Done |
| | 2 | Estilos de Componentes Base | Aplicar el tema a componentes principales (botones, títulos, secciones). | 2 | Developer Team | Done |
| | 3 | Ajustes de UX/UI y Microinteracciones | Refinar espaciados, contraste y animaciones sutiles según el diseño. | 2 | Developer Team | Done |
| **US08: Redirigir a la descarga de la aplicación móvil** | | | | | | | |
| | 1 | Diseño e Implementación de Botones de Descarga | Crear e integrar los botones App Store y Google Play siguiendo sus guías oficiales. | 1.5 | Developer Team | Done |
| | 2 | Configuración de Enlaces a Tiendas | Añadir las URLs oficiales de descarga a cada botón. | 0.5 | Developer Team | Done |
| | 3 | Validación y Comprobación de Redirecciones | Probar que ambos botones redirigen correctamente en dispositivos web y móviles. | 0.5 | Developer Team | Done |
| **US09: Acceder a las redes sociales de Livria** | | | | | | | |
| | 1 | UI de Íconos Sociales | Diseñar y maquetar el conjunto de íconos de redes sociales acorde a la identidad visual. | 0.5 | Developer Team | Done |
| | 2 | Implementación del Componente Social Links | Crear el componente e insertar los íconos en el footer u ubicación definida. | 0.5 | Developer Team | Done |
| | 3 | Integración de Enlaces a Redes | Configurar los enlaces a las redes sociales oficiales de Livria. | 0.5 | Developer Team | Done |
| **US10: Navegar en el footer de la Landing Page** | | | | | | | |
| | 1 | Maquetación del Footer | Estructurar el layout del pie de página con secciones definidas (links, info legal, contacto). | 1 | Developer Team | Done |
| | 2 | Mapa de Sitio Secundario | Añadir y organizar los enlaces de navegación dentro del footer. | 0.5 | Developer Team | Done |
| | 3 | Ajustes de Estilos y Responsive Footer | Aplicar estilos y asegurar correcta visualización en dispositivos móviles. | 0.5 | Developer Team | Done |
| **US11: Enviar un mensaje al equipo de Livria** | | | | | | | |
| | 1 | Endpoint de Contacto (Backend) | Crear un endpoint para recibir datos del formulario y procesar el mensaje (ej. enviar email). | 3 | Developer Team | Done |
| | 2 | Lógica de Procesamiento del Mensaje | Implementar validaciones y el envío del correo o almacenamiento temporal. | 1 | Developer Team | Done |
| | 3 | Integración Frontend-Backend | Conectar el formulario de la Landing Page con el endpoint, manejando estados de carga y error. | 1.5 | Developer Team | Done |
| | 4 | Mensajes de Confirmación/Feedback | Mostrar al usuario notificaciones de éxito o error después del envío. | 0.5 | Developer Team | Done |
| **TS15: Registrar una cuenta con control y seguridad (Admin)**| | | | | | | |
| | 1 | Modelo de Usuario Admin | Definir el esquema de base de datos para usuarios con rol administrador y campos de seguridad. | 1.5 | Developer Team | Done |
| | 2 | Reglas de Seguridad del Modelo | Añadir validaciones, hashing de contraseña y restricciones de acceso. | 0.5 | Developer Team | Done |
| | 3 | Endpoint de Login Admin | Implementar la API de autenticación segura para administradores. | 2.5 | Developer Team | Done |
| | 4 | Gestión de Sesiones / JWT | Configurar expiración, refresh tokens o sesión segura según el método elegido. | 1.5 | Developer Team | Done |
| | 5 | Interfaz de Login Admin | Desarrollar la pantalla de inicio de sesión exclusiva para el área administrativa. | 2.5 | Developer Team | Done |
| | 6 | Validaciones y Feedback UI | Agregar manejo de errores, mensajes de credenciales inválidas y estados de carga. | 0.5 | Developer Team | Done |
| **TS01: Acceder rápido a las secciones del sistema (Dashboard)**| | | | | | | |
| | 1 | Layout Principal Admin | Crear la estructura base del dashboard (Sidebar + área de contenido principal). | 3 | Developer Team | Done |
| | 2 | Estilos y Responsividad del Layout | Ajustar el diseño para que el layout funcione correctamente en distintas resoluciones. | 2 | Developer Team | Done |
| | 3 | Routing de Administración | Configurar las rutas privadas que requieren autenticación de administrador. | 1.5 | Developer Team | Done |
| | 4 | Protección de Rutas con Guardia | Validar sesión/rol antes de permitir acceso a rutas administrativas. | 0.5 | Developer Team | Done |
| **TS12: Gestionar la configuración del perfil (Admin)** | | | | | | | |
| | 1 | Vista de Perfil Admin | Crear la pantalla para visualizar los datos del administrador actual. | 2 | Developer Team | Done |
| | 2 | Formulario de Edición de Perfil | Implementar formulario para modificar datos básicos (nombre, email, etc.). | 1.5 | Developer Team | Done |
| | 3 | Endpoint de Actualización Perfil | API para permitir al administrador cambiar sus datos básicos. | 1.5 | Developer Team | Done |
| **TS13: Gestionar la configuración de la aplicación (Admin)** | | | | | | | |
| | 1 | Vista de Settings Globales | Crear la interfaz con toggles/inputs para las configuraciones globales (ej. notificaciones). | 3 | Developer Team | Done |
| | 2 | Lógica de Settings en Frontend | Conectar los toggles/inputs con el estado y validaciones de la app. | 1 | Developer Team | Done |
| | 3 | Persistencia de Configuración | Implementar el guardado de estas preferencias en base de datos o local storage según corresponda. | 3 | Developer Team | Done |
| **TS10: Añadir un libro al inventario (Admin)** | | | | | | | |
| | 1 | Modelo de Datos Libro | Definir el esquema completo de la base de datos para los libros (título, autor, precio, stock, etc.). | 3 | Developer Team | Done |
| | 2 | Formulario de Creación de Libro (UI) | Desarrollar la interfaz para ingresar los datos de un nuevo libro. | 3 | Developer Team | Done |
| | 3 | Validaciones del Formulario | Agregar validaciones de campos obligatorios y formatos (ej: precio numérico). | 2 | Developer Team | Done |
| | 4 | Endpoint de Creación (API) | Implementar la lógica de backend para validar y guardar un nuevo libro en la BD. | 4 | Developer Team | Done |
| **TS09: Visualizar libros en el inventario (Admin)** | | | | | | | |
| | 1 | Tabla de Inventario UI | Crear el componente de tabla para listar los libros con sus datos principales. | 2.5 | Developer Team | Done |
| | 2 | Endpoint de Listado (API) | API para obtener la lista paginada de libros desde la base de datos. | 3 | Developer Team | Done |
| **TS04: Visualizar detalles completos de un libro (Admin)** | | | | | | | |
| | 1 | Vista de Detalle de Libro | Crear la pantalla que muestra toda la información extendida de un libro seleccionado. | 2 | Developer Team | Done |
| | 2 | Sección de Información Adicional | Incluir en la vista datos complementarios (descripción, categoría, reseñas, etc.). | 1 | Developer Team | Done |
| | 3 | Navegación a Detalle | Configurar la tabla de inventario para navegar a esta vista al seleccionar un libro. | 1 | Developer Team | Done |
| **TS08: Buscar y filtrar libros en el Inventario (Admin)** | | | | | | | |
| | 1 | Componentes de Filtro UI | Implementar barras de búsqueda y dropdowns de filtro en la vista de inventario. | 2 | Developer Team | Done |
| | 2 | Integración de Filtros Frontend | Conectar los componentes UI con el listado aplicando filtros y búsqueda en tiempo real. | 1.5 | Developer Team | Done |
| | 3 | Lógica de Filtrado (Backend) | Actualizar el endpoint de listado para aceptar parámetros de búsqueda y filtrado. | 2 | Developer Team | Done |
| **TS07: Visualizar una tabla con detalles de las órdenes (Admin)**| | | | | | | |
| | 1 | Modelo de Datos Orden | Definir el esquema básico para las órdenes de compra en la base de datos. | 1.5 | Developer Team | Done |
| | 2 | Endpoint de Listado de Órdenes | Implementar la API para obtener el listado de órdenes desde la BD. | 1.5 | Developer Team | Done |
| | 3 | Tabla de Órdenes UI | Crear la vista para listar las órdenes recibidas con sus datos principales. | 2 | Developer Team | Done |
| **TS06: Buscar y filtrar de órdenes (Admin)** | | | | | | | |
| | 1 | Filtros de Órdenes UI | Añadir campos de búsqueda y filtros de estado en la vista de órdenes. | 1.5 | Developer Team | Done |
| | 2 | Lógica de Filtrado UI | Implementar la lógica para aplicar filtros y actualizar la tabla desde el frontend. | 1.5 | Developer Team | Done |
| | 3 | API de Órdenes con Filtros | Implementar endpoint para obtener y filtrar órdenes por criterios (ID, cliente, estado). | 2 | Developer Team | Done |
| **TS02: Visualizar estadísticas de libros (Admin)** | | | | | | | |
| | 1 | Endpoint de Stats Libros | Crear consultas a BD para obtener conteos totales, stock total, etc. | 2 | Developer Team | Done |
| | 2 | Lógica de Cálculo de Stats | Procesar los datos obtenidos para devolver métricas listas para mostrar. | 1 | Developer Team | Done |
| | 3 | Widgets de Estadísticas UI | Crear componentes visuales (tarjetas numéricas) para mostrar estos datos en el Dashboard. | 2 | Developer Team | Done |
| **TS05: Visualizar estadísticas y análisis de órdenes (Admin)** | | | | | | | |
| | 1 | Endpoint de Stats Órdenes | Crear consultas a BD para obtener total de ventas, ingresos, órdenes pendientes. | 2 | Developer Team | Done |
| | 2 | Lógica de Cálculo de Stats Órdenes | Procesar los datos para obtener métricas listas para presentar. | 1 | Developer Team | Done |
| | 3 | Integración en Dashboard | Añadir estos widgets de estadísticas a la vista principal del Dashboard. | 1 | Developer Team | Done |
| **TS11: Visualizar estadísticas de negocio (Admin)** | | | | | | | |
| | 1 | Endpoint de Análisis Negocio | Consultas para obtener "Top vendidos", ganancias por género, etc. | 2.5 | Developer Team | Done |
| | 2 | Lógica de Análisis de Datos | Procesar y estructurar los datos analíticos para visualización. | 1.5 | Developer Team | Done |
| | 3 | Gráficos UI | Implementar librería de gráficos para visualizar estos datos. | 1 | Developer Team | Done |

#### 5.2.1.1 Sprint  2

##### Sprint Planning 2

| Sprint \# | Sprint 2 |
| :---- | :---- |
| **Sprint Planning Background** |  |
| Date | 30/10/2025 |
| Time | 1:30 PM |
| Location | Virtual |
| Prepared by | Gabriel Sebastián Borja Molina, Marcelo Alejandro Binda Arbañil, Cassius Estefano Martel Andrade |
| Attendees (to planning meeting) | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Binda Arbañil / Cassius Estefano Martel Andrade / Alex Tomio Nakamurakare Teruya / Gabriel Sebastián Borja Molina |
| **Sprint Goal & User Stories** |  |
| Sprint 2 Goal | Our primary objective for Sprint 2 is to deliver the core user lifecycle and social interaction features of the Livria application. This involves implementing secure authentication flows (register/login/logout), enabling content discovery through personalized recommendations, advanced search, and filtering, and launching the foundational 'Communities' features. The success of this Sprint will be validated when a user can successfully create an account, log in, find books matching their interests, join literary communities, and create posts within them. This establishes the functional base for user retention and engagement. |
| Sprint 2 Velocity | 30 |
| Sum of Story Points | 28 |

##### Sprint Backlog 2

| Sprint n | Sprint 2 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **User Story** | **Work-Item / Task** | | | | | | |
| **User Story ID** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** | |
| **US15: Registrar un usuario e iniciar sesión** | | | | | | | |
| | 1 | Diseño UI Pantallas Auth | Crear las vistas de Registro e Inicio de Sesión siguiendo las guías de diseño. | 1.5 | Developer Team | Done |
| | 2 | Validaciones UI de Formularios | Implementar validación de campos en cliente (email, contraseñas, errores). | 1.5 | Developer Team | Done |
| | 3 | Endpoint de Registro de Usuario | Implementar la API para crear nuevas cuentas de lector con validación de datos. | 2 | Developer Team | Done |
| | 4 | Endpoint de Autenticación (Login) | Implementar la API que valida credenciales y devuelve tokens de sesión seguros (JWT). | 2 | Developer Team | Done |
| | 5 | Integración Auth en Frontend | Conectar los formularios con los endpoints y gestionar estado de sesión. | 2 | Developer Team | Done |
| **US17: Cerrar sesión** | | | | | | | |
| | 1 | Lógica de Logout (Frontend) | Implementar la función que elimina el token de sesión y redirige al usuario al inicio. | 0.5 | Developer Team | Done |
| | 2 | Limpieza de Estado Local | Asegurar que se limpien datos del usuario almacenados (storage, cache, context). | 0.5 | Developer Team | Done |
| | 3 | Endpoint de Invalidación de Sesión | (Opcional según arquitectura) API para invalidar el token actual en el servidor. | 1 | Developer Team | Done |
| **US16: Visualizar recomendaciones en la plataforma** | | | | | | | |
| | 1 | Diseño UI Sección Recomendaciones | Crear el componente visual (carrusel/grilla) para mostrar los libros recomendados en el Home. | 2 | Developer Team | Done |
| | 2 | Adaptación Responsive del Componente | Ajustar el componente de recomendaciones para móviles, tablet y desktop. | 1 | Developer Team | Done |
| | 3 | Endpoint de Recomendaciones Iniciales | Implementar API que devuelve un conjunto de libros populares o aleatorios para usuarios nuevos. | 2 | Developer Team | Done |
| | 4 | Vista de Detalle de Libro | Crear la pantalla pública con la info del libro, precio y botón de compra. | 2 | Developer Team | Done |
| | 5 | Integración de Recomendaciones con Detalle | Conectar la sección de recomendaciones con la vista de detalle del libro seleccionado. | 1 | Developer Team | Done |
| **US12: Interactuar con recomendaciones** | | | | | | | |
| | 1 | Componentes de Interacción UI | Añadir botones de "Me interesa" / "No me interesa" en las tarjetas de libros. | 1 | Developer Team | Done |
| | 2 | Feedback Visual de Interacción | Mostrar cambio visual inmediato al usuario cuando marca un libro como "Me interesa" o "No me interesa". | 1 | Developer Team | Done |
| | 3 | Endpoint de Registro de Preferencias | API para recibir y guardar la interacción del usuario con un libro específico. | 1 | Developer Team | Done |
| | 4 | Lógica Básica de Recomendación | Actualizar el endpoint de recomendaciones para filtrar libros marcados como "No me interesa". | 2 | Developer Team | Done |
| | 5 | Integración Frontend-Backend | Conectar los botones de interacción con el endpoint para que la acción tenga efecto real. | 2 | Developer Team | Done |
| **US19: Gestionar comunidades** | | | | | | | |
| | 1 | Diseño UI Lista de Comunidades | Crear la vista principal donde el usuario puede explorar y buscar comunidades existentes. | 2 | Developer Team | Done |
| | 2 | Endpoint de Listado de Comunidades | API para obtener las comunidades disponibles, con soporte básico de paginación. | 1 | Developer Team | Done |
| | 3 | Botón "Unirse a Comunidad" | Crear el componente visual para unirse a una comunidad desde la lista. | 3 | Developer Team | Done |
| | 4 | Endpoint de Unión a Comunidad | Implementar API que registre la membresía del usuario en la comunidad seleccionada. | 5 | Developer Team | Done |
| | 5 | Lógica de Actualización UI | Refrescar la lista y estado del usuario tras unirse a una comunidad. | 3 | Developer Team | Done |
| | 6 | Formulario de Creación de Comunidad | UI y lógica para que los usuarios puedan proponer/crear nuevas comunidades temáticas. | 2 | Developer Team | Done |
| **US18: Crear publicaciones en comunidades** | | | | | | | |
| | 1 | Diseño UI Muro de Comunidad | Crear la vista del feed de publicaciones dentro de una comunidad específica. | 1 | Developer Team | Done |
| | 2 | Componente de Creación de Post | UI para escribir texto y, opcionalmente, adjuntar una imagen. | 1 | Developer Team | Done |
| | 3 | Validaciones Frontend | Asegurar que el texto y la imagen cumplan con los límites y formatos permitidos antes de enviar. | 1 | Developer Team | Done |
| | 4 | Endpoint de Publicaciones | API para guardar nuevas publicaciones (texto + manejo de archivo de imagen) en la base de datos. | 1 | Developer Team | Done |
| | 5 | Integración Frontend-Backend | Conectar el formulario de creación de post con el endpoint y refrescar el feed tras publicación. | 1 | Developer Team | Done |
| **US29: Filtrar por atributos del libro** | | | | | | | |
| | 1 | UI de Filtros y Ordenamiento | Implementar componentes visuales (dropdowns, chips) para seleccionar género, precio, idioma, etc. | 1 | Developer Team | Done |
| | 2 | Validación de Selección de Filtros | Asegurar que las opciones seleccionadas sean válidas antes de enviar la consulta al backend. | 0.5 | Developer Team | Done |
| | 3 | Optimización de Endpoint de Catálogo | Actualizar la API de listado de libros para aceptar múltiples parámetros de filtrado y orden. | 0.5 | Developer Team | Done |
| **US22: Buscar libros y contenido en la aplicación** | | | | | | | |
| | 1 | Componente de Barra de Búsqueda | Implementar el input de búsqueda global en el encabezado de la aplicación. | 1 | Developer Team | Done |
| | 2 | Validaciones y Sugerencias | Añadir validación de entradas y mostrar sugerencias/autocompletado según términos parciales. | 1 | Developer Team | Done |
| | 3 | Endpoint de Búsqueda Global | Crear API que acepte un término y busque coincidencias en Títulos de Libros y Nombres de Autores. | 3 | Developer Team | Done |
| | 4 | Paginación y Ordenamiento | Mejorar el endpoint para soportar paginación y orden de resultados. | 1 | Developer Team | Done |
| | 5 | Página de Resultados de Búsqueda | Crear la vista para mostrar los libros que coinciden con la búsqueda del usuario. | 2 | Developer Team | Done |

#### 5.2.1.1 Sprint  3

##### Sprint Planning 3

| Sprint \# | Sprint 3 |
| :---- | :---- |
| **Sprint Planning Background** |  |
| Date | 05/11/2025 |
| Time | 3:30 PM |
| Location | Virtual |
| Prepared by | Gabriel Sebastián Borja Molina, Marcelo Alejandro Binda Arbañil, Cassius Estefano Martel Andrade |
| Attendees (to planning meeting) | Ainhoa Lucía Castillo Garay / Marcelo Alejandro Binda Arbañil / Cassius Estefano Martel Andrade / Alex Tomio Nakamurakare Teruya / Gabriel Sebastián Borja Molina |
| **Sprint Goal & User Stories** |  |
| Sprint 3 Goal | Our primary objective for Sprint 3 is to implement the monetization and user engagement layers of the Livria application. This involves integrating a secure payment gateway for book purchases and subscription management, enabling deeper social interaction through comments and reviews, and establishing a proactive communication channel via instant notifications. The success of this Sprint will be validated when a user can successfully purchase a book, subscribe to a premium plan, comment on community posts, review books, and receive real-time alerts on their device. |
| Sprint 3 Velocity | 30 |
| Sum of Story Points | 27 |

##### Sprint Backlog 3

| Sprint n | Sprint 3 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **User Story** | **Work-Item / Task** | | | | | | |
| **User Story ID** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** | |
| **US21: Comprar libros digitales y físicos** | | | | | | | |
| | 1 | Lógica de Procesamiento de Orden | Conectar la confirmación de pago con la creación definitiva de la orden y reducción de stock. | 2 | Developer Team | Done |
| | 2 | Validaciones y Estado de Orden | Implementar validaciones de datos de la orden y actualización de estado en backend. | 1 | Developer Team | Done |
| **US25: Gestionar plan de suscripción** | | | | | | | |
| | 1 | UI Selección de Planes | Crear la vista para comparar y seleccionar planes de suscripción (Gratuito vs Premium). | 1.5 | Developer Team | Done |
| | 2 | Validaciones de Selección de Plan | Asegurar que el usuario solo pueda elegir un plan activo a la vez y mostrar mensajes de error si corresponde. | 0.5 | Developer Team | Done |
| | 3 | Backend de Suscripciones | Implementar la lógica de facturación recurrente (vía pasarela de pago) y actualización de rol de usuario. | 3 | Developer Team | Done |
| | 4 | Control de Acceso Premium | Actualizar los "guards" de navegación para restringir/permitir acceso a Comunidades según el plan. | 1 | Developer Team | Done |
| | 5 | Notificaciones de Cambio de Plan | Enviar correo o notificación al usuario cuando se actualice su suscripción. | 1 | Developer Team | Done |
| **US24: Valorar y dejar reseña de libros** | | | | | | | |
| | 1 | UI Selector de Estrellas | Implementar el componente visual para seleccionar 1-5 estrellas en la ficha del libro. | 2 | Developer Team | Done |
| | 2 | UI Campo de Texto para Reseña | Añadir el campo de texto para que el usuario escriba su reseña del libro. | 1 | Developer Team | Done |
| | 3 | Endpoint de Guardado de Valoración | Crear el endpoint para registrar la valoración del usuario y asociarla al libro. | 2 | Developer Team | Done |
| | 4 | Endpoint de Guardado de Reseña | Crear el endpoint para registrar la reseña escrita por el usuario. | 1 | Developer Team | Done |
| | 5 | Cálculo de Rating Promedio | Implementar la lógica backend para actualizar el rating promedio del libro tras cada nueva valoración. | 2 | Developer Team | Done |
| | 6 | Integración Frontend-Backend | Conectar el UI con los endpoints de valoración y reseña, mostrando feedback inmediato al usuario. | 1 | Developer Team | Done |
| **US14: Recibir notificaciones instantáneas** | | | | | | | |
| | 1 | Configuración Servicio Push | Instalar y configurar el servicio de notificaciones push (ej. Firebase FCM) en backend. | 4 | Developer Team | Done |
| | 2 | Integración Cliente Push | Integrar el servicio de notificaciones en la app web/móvil para recibir eventos. | 4 | Developer Team | Done |
| | 3 | Triggers de Eventos Stock | Implementar backend para notificar cambios de stock de libros favoritos del usuario. | 2.5 | Developer Team | Done |
| | 4 | Triggers de Eventos Comunidad | Implementar backend para notificar actividad en comunidades que el usuario sigue. | 2.5 | Developer Team | Done |
| | 5 | Vista de Historial de Notificaciones | Crear UI para que el usuario vea todas las notificaciones recibidas. | 3 | Developer Team | Done |
| | 6 | Integración Frontend-Backend | Conectar la UI con el backend para mostrar notificaciones en tiempo real. | 2 | Developer Team | Done |
| **US13: Configurar notificaciones** | | | | | | | |
| | 1 | Diseño UI Preferencias | Crear la interfaz con toggles para activar/desactivar tipos de notificaciones. | 1.5 | Developer Team | Done |
| | 2 | Implementación Frontend | Programar la lógica de toggles y la interacción con la API. | 1.5 | Developer Team | Done |
| | 3 | Endpoint de Preferencias | Crear API para guardar la configuración de notificaciones del usuario. | 1 | Developer Team | Done |
| | 4 | Validación de Configuración | Asegurar que los cambios del usuario se respeten al enviar notificaciones. | 1 | Developer Team | Done |

### 5.2.2. Implemented Landing Page Evidence

<p align="center">
  <img src="https://imgur.com/mCjimWS.png" alt="Landing Page Evidence">
</p>

Se ha llevado a cabo la implementación integral de la Landing Page, diseñada como el punto de contacto principal para los usuarios interesados en el ecosistema de Livria. El sitio cuenta con una estructura semántica y navegable que incluye las secciones de Home (vista principal), Servicios (propuesta de valor), About Us (misión y equipo) y Contacto. La página ha sido optimizada para ofrecer una experiencia responsiva y coherente con las guías de estilo del proyecto, facilitando la conversión de visitantes en usuarios de la plataforma. Se puede acceder a la versión desplegada del sitio a través del siguiente enlace:

Link de la Landing Page ya desplegada: https://upc-pre-202610-1asi0732-12278-defontes.github.io/livria-landing-page/

### 5.2.3. Implemented Native-Mobile Application Evidence



### 5.2.4. Implemented RESTful API and/or Serverless Backend Evidence



### 5.2.5. RESTful API documentation

| Endpoint | Acción | Verbo HTTP | Sintaxis de llamada | Parámetros | Ejemplo de request | Respuesta |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| /api/v1/authentication/register | Crear un registro de un usuario. | POST | /api/v1/authentication/register | Ninguno | {"username": "happy\_vlan", "password": "nativagestion", "confirmPassword": "nativagestion", "display": "Happy Villain", "email": "happy.villain@example.com", "icon": "https://example.com/icon.png", "phrase": "¡VLAN Feliz\!"} | {"message": "Registration successful."} |
| /api/v1/authentication/sign-in/admin | Iniciar sesión como administrador. | POST | /api/v1/authentication/sign-in/admin | Ninguno | {"username": "admin\_default", "password": "0000", "securityPin": "0000"} | {"identityId": 1, "userId": 1, "username": "admin\_default", "success": true, "message": "Login successful.", "token": "eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE3NTIzNTkzOTksImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL3NpZCI6IjEiLCJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy93cy8yMDA1LzA1L2lkZW50aXR5L2NsYWltcy9uYW1lIjoiYWRtaW5fZGVmYXVsdCIsImh0dHA6Ly9zY2hlbWFzLm1pY3Jvc29mdC5jb20vd3MvMjAwOC8wNi9pZGVudGl0eS9jbGFpbXMvcm9sZSI6IkFkbWluIiwiaWF0IjoxNzUxNzU0NTk5LCJuYmYiOjE3NTE3NTQ1OTl9.mGcSdBaMrrP7-DEZTf8gjy5I82pm7Ts9bSfHYKVgypo"} |
| /api/v1/authentication/sign-in/client | Iniciar sesion como cliente. | POST | /api/v1/authentication/sign-in/client | Ninguno | {"username": "rodrigo", "password": "contrasea"} | {"identityId": 7, "userId": 7, "username": "rodrigo", "success": true, "message": "Login successful.", "token": "eyJhbGciOiJodHRwOi8vd3d3LnczLm9yZy8yMDAxLzA0L3htbGRzaWctbW9yZSNobWFjLXNoYTI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE3NTIzNTk0ODQsImh0dHA6Ly9zY2hlbWFzLnhtbHNvYXAub3JnL3dzLzIwMDUvMDUvaWRlbnRpdHkvY2xhaW1zL3NpZCI6IjciLCJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy93cy8yMDA1LzA1L2lkZW50aXR5L2NsYWltcy9uYW1lIjoicm9kcmlnbyIsImh0dHA6Ly9zY2hlbWFzLm1pY3Jvc29mdC5jb20vd3MvMjAwOC8wNi9pZGVudGl0eS9jbGFpbXMvcm9sZSI6IlVzZXJDbGllbnQiLCJpYXQiOjE3NTE3NTQ2ODQsIm5iZiI6MTc1MTc1NDY4NH0.0VhD4A-bCEMh-X0ItAKe1utt5HKBO-j5jbnQn2MVk4E"} |
| /api/v1/books | Obtener los datos de todos los libros. | GET | /api/v1/books | Ninguno | \- | {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 49,"cover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": \[\]} |
| /api/v1/books | Crear un nuevo libro. | POST | /api/v1/books | Ninguno | {"title": "Millonario","description": "Jugador","author": "Persona","salePrice": 4,"stock": 20,"cover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english"} | {"id": 3,"title": "XD","description": "string","author": "string","salePrice": 4,"stock": 20,"cover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": \[\]}  |
| /api/v1/books/{id} | Obtener los datos de un libro en específico. | GET | /api/v1/books/{id} | id: Integer | /api/v1/books/1 | {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 50,"cover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": \[\]} |
| /api/vi/books/{bookId}/stock | Actualizar el stock de un libro. | PUT | /api/vi/books/{bookId}/stock | bookId: Integer, stock: Integer | {"newStock": 50} | {"id": 1,"title": "string","description": "string","author": "string","salePrice": 4,"stock": 50,"cover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","genre": "noficcion","language": "english","reviews": \[\]} |
| /api/v1/orders | Crear una nueva orden. | POST | /api/v1/orders | Ninguno | {"userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shippingDetails": {"address": "string","city": "string","district": "string","reference": "string"},"cartItemIds": \[2\]} | {"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.2790128Z","items": \[{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}\]} |
| /api/v1/orders/{id} | Obtener los datos de un orden en específico. | GET | /api/v1/orders/{id} | id: Integer | /api/v1/orders/1 | {"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": \[{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}\]} |
| /api/v1/orders/code/{code} | Obtener los datos de una orden en específico por medio de su código. | GET | /api/v1/orders/code/{code} | code: String | /api/v1/orders/code/292W4X | {"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "pending","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": \[{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}\]} |
| /api/v1/orders/users/{userClientId} | Obtener los datos de las órdenes de un usuario cliente en específico. | GET | /api/v1/orders/users/{userClientId} | userClientId: Integer | /api/v1/orders/users/2 | \[{"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "delivered","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": \[{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}\]}\] |
| /api/v1/orders/{orderId}/status | Actualizar el estado de una orden. | PUT | /api/v1/orders/{orderId}/status | status: string | {"status": "in progress"} | {"id": 1,"code": "292W4X","userClientId": 2,"userEmail": "string@gmail.com","userPhone": "123123123","userFullName": "string","recipientName": "string","status": "in progress","isDelivery": true,"shipping": {"address": "string","city": "string","district": "string","reference": "string"},"total": 4,"date": "2025-06-21T05:39:05.279012","items": \[{"id": 1,"bookId": 1,"bookTitle": "string","bookAuthor": "string","bookPrice": 4,"bookCover": "https://i.kinja-img.com/image/upload/c\_fit,q\_60,w\_645/3403984c00db62389e225eac46008f21.jpg","quantity": 1,"itemTotal": 4}\]} |
| /api/v1/communities | Crea una nueva comunidad en el sistema. | POST | /api/v1/communities | Ninguno (cuerpo JSON) | {"name": "Club de Lectura Fantasía Épica", "description": "Un espacio para debatir sobre Tolkien, Brandon Sanderson y las mejores sagas de fantasía.", "type": 1, "image": "https://livria-assets.com/icons/fantasia-epic-icon.png", "banner": "https://livria-assets.com/banners/epic-banner.jpg"} | **Code 201 (Created)** <br> {"id": 12, "name": "Club de Lectura Fantasía Épica", "description": "Un espacio para debatir sobre Tolkien, Brandon Sanderson y las mejores sagas de fantasía.", "type": 1, "image": "https://livria-assets.com/icons/fantasia-epic-icon.png", "banner": "https://livria-assets.com/banners/epic-banner.jpg"} |
| /api/v1/communities | Obtener los datos de todas las comunidades. | GET | /api/v1/communities | Ninguno | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/communities' | **Code 200 (OK)** <br> [ { "id": 0, "name": "Evil HQ", "description": "We're all evil in here :)", "type": 0, "image": "https://...", "banner": "https://..." }, { "id": 2, "name": "Wonderland", "description": "A very strange and mad place for all travelers, a truly wonderland...", "type": 0, "image": "https://d23.com/app/uploads/2015/07/alice-in-wonderland.jpg", "banner": "https://www.thomaskinkade.com/cdn/shop/collections/alice_10ec166fb-007c-4236-95f2-62dadd22ac8c.jpg?v=1689619943&width=800" } ] |
| /api/v1/communities/{id} | Obtener los datos de una comunidad en específico. | GET | /api/v1/communities/1 | id: Integer (path) | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/communities/1' | **Code 200 (OK)** <br> { "id": 0, "name": "Evil HQ", "description": "We're all evil in here :)", "type": 1, "image": "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQifg0iQO..." } |
| /api/v1/communities/join | El userclient puede unirse a una comunidad existente. | POST | /api/v1/communities/join | Ninguno (cuerpo JSON) | {"userClientId": 37, "communityId": 12} | **Code 201 (Created)** <br> {"userClientId": 37, "communityId": 12, "joinedDate": "2025-11-14T03:48:34.370354Z"} |
| /api/v1/communities/{communityId}/members/{userId} | Permite a un usuario salir de una comunidad específica. | DELETE | /api/v1/communities/1/members/37 | communityId: Integer (path), userId: Integer (path) | curl -X 'DELETE' 'https://livriagod.azurewebsites.net/api/v1/communities/1/members/37' | **Code 204 (No Content)** <br> (No hay cuerpo de respuesta) |
| /api/v1/authentication/register | Registrar un nuevo usuario en el sistema. | POST | /api/v1/authentication/register | Ninguno (cuerpo JSON) | {"username": "cassius_dev", "password": "P@ssword123!", "confirmPassword": "P@ssword123!", "display": "Cassius", "email": "cassius.dev@livria.com", "icon": "https://livria-assets.com/avatars/default.png", "phrase": "Amante de la ciencia ficción."} | **Code 201 (Created)** <br> {"message": "Registration successful."} |
| /api/v1/authentication/sign-in/client | Inicia sesión para un usuario cliente. | POST | /api/v1/authentication/sign-in/client | Ninguno (cuerpo JSON) | {"username": "cassius_dev", "password": "P@ssword123!"} | **Code 200 (OK)** <br> {"identityId": 10, "userId": 95, "username": "cassius_dev", "success": true, "message": "Login successful.", "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c"} |
| /api/v1/posts/communities/{communityId} | Crear una nueva publicación en una comunidad existente. | POST | /api/v1/posts/communities/1 | communityId: Integer (path) | {"username": "cassius_dev", "content": "¡Acabo de terminar 'Dune' y es increíble! ¿Alguien más es fan de la saga?", "img": "https://livria-assets.com/posts/dune-cover.png"} | **Code 201 (Created)** <br> {"id": 1, "communityId": 1, "userId": 37, "username": "cassius_dev", "content": "¡Acabo de terminar 'Dune' y es increíble! ¿Alguien más es fan de la saga?", "img": "https://livria-assets.com/posts/dune-cover.png", "createdAt": "2025-11-14T03:45:43.0797309Z"} |
| /api/v1/posts/{id} | Obtener los datos de una publicación en específico. | GET | /api/v1/posts/1 | id: Integer (path) | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/posts/1' | **Code 200 (OK)** <br> {"id": 1, "communityId": 1, "userId": 35, "username": "happyvillain", "content": "primer post malvado de la comnidad :)", "img": "", "createdAt": "2025-11-08T21:33:30.52679S"} |
| /api/v1/posts/community/{communityId} | Obtener todas las publicaciones para una comunidad específica. | GET | /api/v1/posts/community/1 | communityId: Integer (path) | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/posts/community/1' | **Code 200 (OK)** <br> [ { "id": 1, "communityId": 1, "userId": 35, "username": "happyvillain", "content": "primer post malvado de la comnidad :)", "img": "", "createdAt": "2025-11-08T21:33:30.52679S" }, { "id": 2, "communityId": 1, "userId": 35, "username": "happyvillain", "content": "segundo post malvado de la comnidad :)", "img": "", "createdAt": "2025-11-08T22:11:58.24796S" } ] |
| /api/v1/recommendations/users/{userClientId} | Obtener los datos de las recomendaciones que le pertenecen a un usuario en específico. | GET | /api/v1/recommendations/users/35 | userClientId: Integer (path) | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/recommendations/users/35' | **Code 200 (OK)** <br> {"userClientId": 35, "recommendedBooks": []} |
| /api/v1/reviews | Crear una nueva review en el sistema. | POST | /api/v1/reviews | Ninguno (cuerpo JSON) | {"bookId": 1, "userClientId": 37, "content": "¡Este libro es increíble, me cambió la vida!", "stars": 5} | **Code 201 (Created)** <br> {"id": 8, "bookId": 1, "username": "cassius_dev", "content": "¡Este libro es increíble, me cambió la vida!", "stars": 5} |}
| /api/v1/reviews/{id} | Obtener los datos de una reseña en específico. | GET | /api/v1/reviews/1 | id: Integer (path) | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/reviews/1' | **Code 200 (OK)** <br> {"id": 1, "bookId": 1, "username": "jabberwocky", "content": "c'est sublime comme tous les univers", "stars": 5} |
| /api/v1/reviews/book/{bookId} | Obtener todas las reseñas para un libro específico. | GET | /api/v1/reviews/book/1 | bookId: Integer (path) | curl -X 'GET' 'https://livriagod.azurewebsites.net/api/v1/reviews/book/1' | **Code 200 (OK)** <br> [ { "id": 1, "bookId": 1, "username": "jabberwocky", "content": "c'est sublime comme tous les univers", "stars": 5 }, { "id": 5, "bookId": 1, "username": "happyvillain", "content": "increible", "stars": 4 }, { "id": 6, "bookId": 1, "username": "tiktok_user", "content": "Gran manga.", "stars": 5 } ] |
| /api/v1/communities/{communityId}/members/{userId}/is-member | Verificar la membresía de un usuario en una comunidad. | GET | /api/v1/communities/1/members/3/is-member | communityId: Integer (path), userId: Integer (path) | curl -X 'GET' 'https://lililivria.azurewebsites.net/api/v1/communities/1/members/3/is-member' | **Code 200 (OK)** <br> { "isMember": false } |
| /api/v1/userclients/{userClientId}/exclusions/{bookId} | Agregar un libro existente a la lista de exclusión. | POST | /api/v1/userclients/3/exclusions/1 | userClientId: Integer (path), bookId: Integer (path) | curl -X 'POST' 'https://lililivria.azurewebsites.net/api/v1/userclients/3/exclusions/1' | **Code 200 (OK)** <br> { "icon": "data:image/jpeg;base64,/9j/4QBqRXhpZgAATU0AKg...", "id": 3, "display": "ksedudu_gamepluplu", "username": "ksedudu", "email": "ksedudu@gmail.com", "phrase": "soy ksedo xdxdxxd", "subscription": "communityplan" } |
| /api/v1/userclients/{userClientId}/exclusions | Obtener los datos de los libros excluidos de un usuario. | GET | /api/v1/userclients/3/exclusions | userClientId: Integer (path) | curl -X 'GET' 'https://lililivria.azurewebsites.net/api/v1/userclients/3/exclusions' | **Code 200 (OK)** <br> [ { "id": 1, "title": "Cien años de soledad", "author": "Gabriel García Márquez", "salePrice": 49.55, "stock": 11, "cover": "https://i.imgur.com/4Bv3Eq5.jpeg", "genre": "literature" } ] |
| /api/v1/userclients/{userClientId}/exclusions/{bookId} | Eliminar un libro de la lista de exclusión de un UserClient. | DELETE | /api/v1/userclients/3/exclusions/1 | userClientId: Integer (path), bookId: Integer (path) | curl -X 'DELETE' 'https://lililivria.azurewebsites.net/api/v1/userclients/3/exclusions/1' | **Code 200 (OK)** <br> { "icon": "data:image/jpeg;base64/...", "id": 3, "display": "ksedudu_gamepluplu", "username": "ksedudu", "email": "ksedudu@gmail.com", "phrase": "soy ksedo xdxdxxd", "subscription": "communityplan" } |

**/api/v1/authentication/register:**
<p align="center">
  <img src="https://i.imgur.com/36KKSwv.png" alt="12171">
</p>

Esta solicitud POST inicia una nueva sesión como usuario administrador, con acceso a la vista de gestión de librería. Para lograr esto, utiliza las credenciales de administrador cargadas por defecto al sistema y devuelve un JSON Web Token (JWT).

**/api/v1/authentication/sign-in/client:**

<p align="center">
  <img src="https://i.imgur.com/sBkG9fM.png" alt="12171">
</p>

Esta solicitud POST auténtica al cliente con las credenciales de usuario de tipo cliente proporcionadas. Valida la sesión y devuelve un JSON Web Token (JWT) para la autenticación.

**/api/v1/books:**

<p align="center">
  <img src="https://i.imgur.com/zElCiAA.png" alt="12171">
</p>

Esta solicitud POST crea un nuevo libro en el sistema. Permite registrar un libro con su título, descripción, autor, precio, stock, imagen de portada, género e idioma.

<p align="center">
  <img src="https://i.imgur.com/x5oByk6.png" alt="12171">
</p>

Esta solicitud GET obtiene los datos de todos los libros disponibles. Muestra una lista completa de los libros registrados en el sistema.

**/api/v1/books/{id}:**

<p align="center">
  <img src="https://i.imgur.com/Y9B0aDg.png" alt="12171">
</p>

Esta solicitud GET obtiene los datos de un libro en específico, utilizando su ID. Muestra los detalles del libro solicitado.

**/api/vi/books/{bookId}/stock:**

<p align="center">
  <img src="https://i.imgur.com/CCV93QN.png" alt="12171">
</p>

Esta solicitud PUT actualiza el stock disponible de un libro específico, usando su ID. Permite modificar la cantidad de libros en existencia.

**/api/v1/orders:**

<p align="center">
  <img src="https://i.imgur.com/dc8v46S.png" alt="12171">
</p>

Esta solicitud POST crea una nueva orden en el sistema. Permite registrar una compra con detalles del cliente, envío y los ítems comprados.

**/api/v1/orders/{id}:**

<p align="center">
  <img src="https://i.imgur.com/dc8v46S.png" alt="12171">
</p>

Esta solicitud GET obtiene los datos de una orden en específico, usando su ID. Muestra los detalles de la orden buscada.

**/api/v1/orders/code/{code}:**

<p align="center">
  <img src="https://i.imgur.com/WRcdUZX.png" alt="12171">
</p>

Esta solicitud GET obtiene los datos de una orden específica por medio de su código. Muestra los detalles de la orden que coincida con el código.

**/api/v1/orders/users/{userClientId}:**  

<p align="center">
  <img src="https://i.imgur.com/h5dYSqv.png" alt="12171">
</p>

Esta solicitud GET obtiene todas las órdenes de un usuario cliente específico, usando su ID. Muestra una lista de todas las compras realizadas por ese usuario.

**/api/v1/orders/{orderId}/status:**

<p align="center">
  <img src="https://i.imgur.com/stgPl8L.png" alt="12171">
</p>

Esta solicitud PUT actualiza el estado de una orden, usando su ID. Permite cambiar el estado de una orden entre 'pending', 'in progress' o 'delivered'.

**POST /api/v1/communities**
<p align="center">
  <img src="https://github.com/user-attachments/assets/77a544af-6a0c-4a0a-a888-207111c8dedc" alt="12171">
</p>

Crea una nueva comunidad en el sistema. Recibe en el cuerpo de la petición el nombre, descripción, tipo, imagen y banner. Devuelve la comunidad recién creada con su ID.

**GET /api/v1/communities**
<p align="center">
  <img src="https://github.com/user-attachments/assets/d9603e8f-a1fa-4395-b755-5c5a1088b5b8" alt="12171">
</p>

Obtiene una lista de todas las comunidades registradas en el sistema. Devuelve un arreglo de objetos de comunidad.

**GET /api/v1/communities/{id}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/045a1695-ef2e-4a9c-ae51-70e2cf4909d8" alt="12171">
</p>

Obtiene los datos de una comunidad específica usando su ID como parámetro en la URL. Devuelve el objeto de la comunidad solicitada.

**POST /api/v1/communities/join**
<p align="center">
  <img src="https://github.com/user-attachments/assets/54389499-bc58-483c-9380-cd83455bdb70" alt="12171">
</p>

Permite que un userClientId se una a una communityId. Recibe ambos IDs en el cuerpo de la petición y devuelve un objeto confirmando la unión y la fecha.

**DELETE /api/v1/communities/{communityId}/members/{userId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/1e21822f-f796-49cd-8ef5-6c4b687aadb6" alt="12171">
</p>

Permite a un usuario salir de una comunidad. Utiliza tanto el communityId como el userId en la URL para identificar y eliminar la membresía.

**POST /api/v1/authentication/register**
<p align="center">
  <img src="https://github.com/user-attachments/assets/82048fa0-1693-45cc-91e7-154b2edf7e15" alt="12171">
</p>

Registra un nuevo usuario cliente en el sistema. Recibe todos los datos del formulario (username, password, email, display, etc.) en el cuerpo de la petición.

**POST /api/v1/authentication/sign-in/client**
<p align="center">
  <img src="https://github.com/user-attachments/assets/d112c7cf-5d77-4c87-b669-9aa720a5a207" alt="12171">
</p>

Inicia sesión para un usuario cliente. Recibe username y password, y si tiene éxito, devuelve un objeto con el userId, username y el token (JWT) de sesión.

**POST /api/v1/posts/communities/{communityId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/49096c07-0922-4f23-a357-7358152856cc" alt="12171">
</p>

Crea una nueva publicación (post) dentro de una comunidad específica. El communityId se pasa en la URL, y el contenido (username, content, img) se envía en el cuerpo.

**GET /api/v1/posts/{id}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/0797064c-0420-40eb-8c61-8fdecfbfbe91" alt="12171">
</p>

Obtiene los datos de una publicación (post) específica usando su ID en la URL.

**GET /api/v1/posts/community/{communityId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/7b1e58d6-5960-4796-8858-b1ec5dbfb84e" alt="12171">
</p>

Obtiene una lista de todas las publicaciones asociadas a un communityId específico, pasado en la URL.

**GET /api/v1/recommendations/users/{userClientId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/d82454e0-a0d0-430a-9fc9-e5b323d58a9c" alt="12171">
</p>

Obtiene las recomendaciones de libros personalizadas para un usuario específico, identificado por su userClientId en la URL.

**POST /api/v1/reviews**
<p align="center">
  <img src="https://github.com/user-attachments/assets/a3d94f32-3a76-4ec6-a7f7-dd850c029e73" alt="12171">
</p>

Crea una nueva reseña (review) en el sistema. Recibe el bookId, userClientId, el content (texto) y las stars (estrellas) en el cuerpo de la petición.

**GET /api/v1/reviews/{id}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/76cd139a-854c-4014-810c-aa44b15967b7" alt="12171">
</p>

Obtiene los datos de una reseña específica usando su ID en la URL.

**GET /api/v1/reviews/book/{bookId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/13e81ac8-1d17-4f05-b1bc-9e7f18e019bd" alt="12171">
</p>

Obtiene una lista de todas las reseñas asociadas a un libro específico, identificado por su bookId en la URL.

**POST /api/v1/communities/{communityId}/members/{userId}/is-member**
<p align="center">
  <img src="https://github.com/user-attachments/assets/5b9821f0-e248-438b-b433-833d798dc8b3" alt="12171">
</p>

Comprueba si un usuario específico es miembro activo de una comunidad determinada.

**POST /api/v1/userclients/{userClientId}/exclusions/{bookId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/e4c2bc70-5922-4ee8-8839-1d3f8ca0843c" alt="12171">
</p>

Añade un libro a la lista de exclusión del usuario para que no aparezca en sus recomendaciones.

**GET /api/v1/userclients/{userClientId}/exclusions**
<p align="center">
  <img src="https://github.com/user-attachments/assets/99c2d228-974e-414b-89f5-02ef67471577" alt="12171">
</p>

Recupera el listado completo de todos los libros que el usuario ha decidido excluir.

**DELETE /api/v1/userclients/{userClientId}/exclusions/{bookId}**
<p align="center">
  <img src="https://github.com/user-attachments/assets/26c15ae7-7ff8-401b-8b1e-1123b8d5dfc6" alt="12171">
</p>


Remueve un libro específico de la lista de exclusión del usuario, permitiendo que vuelva a ser recomendado.


### 5.2.6. Team Collaboration Insights

#### Sprint 1

Durante este Sprint, el equipo se centró en la implementación y despliegue de las principales funcionalidades del proyecto Livria, abordando tanto el frontend web, como el backend y la aplicación móvil. Se desarrolló la Landing Page utilizando HTML, CSS y JavaScript, asegurando una interfaz visual atractiva y responsiva acorde con el diseño definido. Esta fue desplegada en GitHub Pages, garantizando su disponibilidad pública y un flujo de navegación fluido.

En paralelo, se implementó el backend en C#, diseñando e integrando endpoints para la gestión de libros, inventario, pedidos y usuarios. Este servicio fue desplegado en Microsoft Azure, permitiendo la conexión estable con los distintos módulos del sistema y asegurando la persistencia de los datos.

Finalmente, se desarrolló la aplicación móvil en Android Studio utilizando Kotlin, enfocada en la vista del administrador de Livria. Esta aplicación permite la gestión directa de los recursos del sistema, ofreciendo pantallas funcionales y una experiencia de uso coherente con la plataforma web.
Actividades de implementación:

* La Landing Page fue construida conforme a los diseños de Figma, aplicando estilos y flujos de navegación definidos previamente.
* El backend en C# integró controladores y servicios RESTful conectados a la base de datos, optimizados para las operaciones del sistema.
* La aplicación móvil implementó pantallas clave para la administración de libros, inventario y órdenes, garantizando una comunicación efectiva con el backend desplegado en Azure.

Visualización de commits:

<p align="center">
  <img src="https://i.imgur.com/1erqp0c.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/skz9UVG.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/rchRhxY.png" alt="12171">
</p>

#### Sprint 2

Durante este Sprint, el equipo concentró todos sus esfuerzos en la implementación y despliegue de la aplicación móvil dirigida al usuario final (lector), utilizando el framework Flutter dentro del entorno Android Studio. El enfoque principal fue la construcción de una interfaz de usuario fiel a los diseños y la arquitectura del cliente, asegurando una navegación fluida y una experiencia nativa consistente.

Dado que la infraestructura del servidor ya se encontraba operativa, el trabajo técnico se focalizó en la integración desde el cliente, desarrollando la capa de datos y repositorios en la aplicación móvil para consumir los servicios RESTful existentes. Esto permitió validar los flujos de autenticación y obtención de datos sin necesidad de realizar modificaciones en el código fuente del backend.

Actividades de implementación:

* La aplicación móvil de usuario fue desarrollada en Flutter, implementando la lógica de negocio en el cliente y las pantallas de Autenticación (Login/Registro), Inicio, Búsqueda y Comunidades conforme a los prototipos de Figma.
* Se desarrolló la capa de infraestructura en la aplicación móvil para gestionar la comunicación HTTP, el manejo de errores y el almacenamiento seguro de tokens (JWT) recibidos del backend.
* Se validó la integración de los servicios mediante pruebas de conexión desde el aplicativo Android, garantizando que la visualización de libros, comunidades y perfiles de usuario respondiera correctamente a la data existente.

Visualización de commits:

<p align="center">
  <img src="https://i.imgur.com/JzpufE4.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/plbWVA5.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/LjeyLl1.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/0Y4Qt3w.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/ajnLREa.png" alt="12171">
</p>

<p align="center">
  <img src="https://i.imgur.com/kQOxqPW.png" alt="12171">
</p>

#### Sprint 3

Durante este Sprint, el equipo orientó sus esfuerzos a la consolidación de la aplicación móvil (Flutter/Android Studio) como una plataforma transaccional completa y personalizada. El enfoque principal fue la implementación de los flujos de comercio electrónico (Carrito de Compras, Órdenes) y la gestión integral del perfil de usuario, asegurando que la arquitectura soportara operaciones complejas de estado y persistencia de datos de manera fluida.

En el ámbito técnico, el trabajo se focalizó en la integración de lógica de negocio avanzada en el cliente y la conexión con servicios externos y actualizados del backend. Se desarrolló la gestión de estados globales para el manejo de stock y compras, además de incorporar herramientas de geolocalización y aseguramiento de calidad (Testing) para validar la robustez del sistema antes de la entrega final.

Actividades de implementación:

* La aplicación móvil integró los módulos de E-commerce y Suscripciones, implementando las pantallas de Carrito de Compras, Pasarela de Pagos, Historial de Órdenes y Edición de Perfil, completando el ciclo de vida comercial del usuario.
* Se desarrollaron funcionalidades de infraestructura avanzada, incluyendo la integración con Google Maps para la gestión de direcciones, un sistema de notificaciones y la optimización del algoritmo de recomendaciones con lógica de exclusión y favoritos (bookmarks).
* Se incorporó una fase rigurosa de calidad mediante la implementación de pruebas unitarias y de integración, garantizando que tanto la lógica de negocio (cálculos de carrito, stock) como la navegación entre módulos funcionaran correctamente bajo distintos escenarios de uso.

Visualización de commits:

<p align="center">
  <img src="https://imgur.com/7S4tqD6.png" alt="12171031">
</p>

<p align="center">
  <img src="https://imgur.com/hxTkrCu.png" alt="12171031">
</p>

<p align="center">
  <img src="https://imgur.com/aDaJCVz.png" alt="12171031">
</p>

<p align="center">
  <img src="https://imgur.com/JssVcP1.png" alt="12171031">
</p>

<p align="center">
  <img src="https://imgur.com/AwtJY2V.png" alt="12171031">
</p>

## 5.3. Video About-the-Product

---

# Conclusiones

1. El proceso Lean UX constituye una herramienta clave para orientar estratégicamente el negocio, ya que permite validar tempranamente hipótesis y explorar diferentes enfoques antes de comprometer recursos de desarrollo. Gracias a este proceso, fue posible identificar con claridad los segmentos de usuarios más relevantes y las oportunidades de valor que guiarán el diseño del producto.

2. La etapa de needfinding resulta fundamental en la construcción de un producto centrado en el usuario, dado que proporciona información directa sobre sus necesidades, expectativas y motivaciones. Este proceso asegura que las decisiones de diseño y desarrollo respondan a problemas reales, incrementando la probabilidad de adopción y satisfacción del usuario final.

3. La aplicación de Domain-Driven Design (DDD) favorece la definición temprana de bounded contexts y clases esenciales del dominio, lo cual aporta claridad conceptual y una arquitectura más limpia. Este enfoque permite separar responsabilidades de manera ordenada, reducir la complejidad técnica y facilitar la escalabilidad del sistema en el largo plazo.

4. El desarrollo completo de los wireframes, wireflows y mockups tanto para la Landing Page como para las pantallas móviles asegura que la implementación del Frontend se realizará con una guía visual clara y centrada en el usuario. Este proceso minimiza las ambigüedades en la fase de desarrollo y garantiza la consistencia visual y funcional.

5. La aplicación de una metodología ágil y la realización estructurada del Sprint 1 (incluyendo el Sprint Backlog detallado, la evidencia de desarrollo y las pruebas) demuestran un progreso tangible y medible en la construcción del producto. Esto asegura la transparencia del proceso y el alineamiento del equipo.

6. El desglose detallado de las User Stories en tareas específicas dentro del Sprint Backlog ha permitido cuantificar la carga de trabajo del equipo con alta precisión. Esta granularidad es clave para realizar una planificación realista de la capacidad del Sprint, asegurar la distribución equitativa de responsabilidades y minimizar la incertidumbre durante la fase de desarrollo.

7. La implementación del proyecto móvil en Flutter demostró que la aplicación del Domain-Driven Design (DDD) a nivel táctico facilitó la separación de las responsabilidades del sistema. La clara segregación de capas (Dominio, Infraestructura, Presentación) permitió que la lógica de negocio fuera completamente independiente de los detalles tecnológicos (APIs, Base de Datos, UI), resultando en un código más mantenible, testeable y desacoplado.


8. El equipo logró la integración funcional de los componentes críticos para el ciclo de vida del usuario (Login, Registro y Logout). Esto implicó la conexión de la lógica del frontend (Flutter) con el backend desplegado en Azure, asegurando la persistencia del estado de la sesión (JWT/SharedPreferences) y validando la arquitectura de la solución.

9. La implementación de validaciones en tiempo real (como el control de stock en el carrito y la lógica de suscripciones) y el manejo eficiente de la conversión de imágenes (Base64) reforzaron la integridad de los datos entre el cliente y el servidor. Estas prácticas no solo previenen errores en el backend, sino que mejoran la experiencia del usuario al proporcionar retroalimentación inmediata y evitar estados inconsistentes en la aplicación.

# Recomendaciones

1. Es aconsejable adoptar Material Design como marco de referencia para el diseño de la interfaz, dado que proporciona consistencia visual, buenas prácticas de usabilidad y un sistema estandarizado de componentes. Esto contribuirá a que la experiencia del usuario sea más intuitiva, atractiva y alineada con tendencias actuales en aplicaciones modernas.

2. Es crucial establecer un proceso obligatorio de revisión de código (utilizando herramientas como GitHub Pull Requests). Esto debe realizarse por al menos un miembro del equipo diferente al autor antes de la fusión con la rama principal. Esta práctica no solo mejora la calidad del código y reduce los errores, sino que también facilita la transferencia de conocimiento y asegura la adherencia a las convenciones de estilo.

3. Se aconseja utilizar las herramientas de Project Management para mantener un gráfico de trabajo pendiente visible y actualizado diariamente. Esta métrica visual ayuda al equipo a monitorear su ritmo de progreso, detectar a tiempo si el Sprint está en riesgo de no completarse y facilita la toma de decisiones basadas en datos durante la Sprint Review.

4. La anticipación en la definición de Style Guidelines es un acierto estratégico que facilitará la unidad de marca y la velocidad de desarrollo en sprints futuros, al proporcionar un sistema de diseño reutilizable.

5. Es aconsejable implementar patrones de Optimistic UI en la gestión de estados, especialmente para interacciones frecuentes como "Agregar al carrito" o "Unirse a una comunidad". Al actualizar visualmente el estado de la interfaz de manera inmediata, se mejora la percepción de velocidad y fluidez de la aplicación, siempre manteniendo un mecanismo de reversión (rollback) en caso de que la petición falle.

# Bibliografía

Alaminkarno. (2024, enero 8). *DDD (Domain-Driven Design) in Flutter – Too much or just right?* DEV Community. [https://dev.to/alaminkarno/ddd-domain-driven-design-in-flutter-too-much-or-just-right-d1g](https://dev.to/alaminkarno/ddd-domain-driven-design-in-flutter-too-much-or-just-right-d1g)

Allen, C. (2024). *The impact of book clubs on millennials: Best way to instill a love of reading*. Recuperado de [https://catherineallenblog.com/the-impact-of-book-clubs-on-millennials-best-way-to-instill-a-love-of-reading](https://catherineallenblog.com/the-impact-of-book-clubs-on-millennials-best-way-to-instill-a-love-of-reading)

Alvarez, A. (2020, 5 de agosto). 5W2H: Qué significa, para qué sirve, cómo aplicarla y algunos ejemplos. LeanConstructionMexico. [https://www.leanconstructionmexico.com.mx/post/5w2h-qué-significa-para-qué-sirve-cómo-aplicarla-y-algunos-ejemplos](https://www.leanconstructionmexico.com.mx/post/5w2h-qu%C3%A9-significa-para-qu%C3%A9-sirve-c%C3%B3mo-aplicarla-y-algunos-ejemplos)

Dart Packages. (s. f.). *pub.dev*. [https://pub.dev](https://pub.dev)

Fabiana, E., & Vega, J. (2022). La motivación en el aprendizaje de la lectura en los estudiantes. Revista EDUCARE \- UPEL-IPB \- Segunda Nueva Etapa 2.0, 26(Extraordinario), 476–493. [https://doi.org/10.46498/reduipb.v26iExtraordinario.1641](https://doi.org/10.46498/reduipb.v26iExtraordinario.1641) 

Flutter Dev. (s. f.). *Flutter documentation*. [https://docs.flutter.dev](https://docs.flutter.dev)

Google Fonts. (s. f.). *Alexandria*. [https://fonts.google.com/specimen/Alexandria](https://fonts.google.com/specimen/Alexandria)

Google Fonts. (s. f.). *Asap Condensed*. [https://fonts.google.com/specimen/Asap+Condensed](https://fonts.google.com/specimen/Asap+Condensed)

Google Maps. (s. f.). *Google Maps Platform*. [https://developers.google.com/maps](https://developers.google.com/maps)

Mamani, B., Chata, L., & Choque, D. (2024). Efecto del uso de Tik Tok en el rendimiento académico de estudiantes de 5to grado . Revista Tribunal, 4(9), 161-175. [https://doi.org/10.59659/revistatribunal.v4i9.71](https://doi.org/10.59659/revistatribunal.v4i9.71)

Ministerio de Cultura del Perú & Instituto Nacional de Estadística e Informática. (2023). *Encuesta Nacional de Lectura 2022: Informe de lectores y no lectores*. Recuperado de [https://perulee.pe/sites/default/files/ENL%202022%20-%20Informe%20de%20lectores%20y%20no%20lectores.pdf](https://perulee.pe/sites/default/files/ENL%202022%20-%20Informe%20de%20lectores%20y%20no%20lectores.pdf?utm_source=chatgpt.com)

Statista. (2024). *Hablemos de los clubes de lectura y por qué esta tendencia va en aumento*. Recuperado de [https://globaltag.mx/uncategorized/leer-esta-de-moda-hablemos-de-los-clubes-de-lectura-y-por-que-esta-tendencia-va-en-aumento/](https://globaltag.mx/uncategorized/leer-esta-de-moda-hablemos-de-los-clubes-de-lectura-y-por-que-esta-tendencia-va-en-aumento/?utm_source=chatgpt.com)

Stripe. (s. f.). *Stripe*. [https://stripe.com](https://stripe.com)

Torres-Vega, E. (2025). Comprensión lectora en estudiantes de secundaria en Perú. Horizontes. Revista De Investigación En Ciencias De La Educación, 9(36), 177–187. [https://doi.org/10.33996/revistahorizontes.v9i36.909](https://doi.org/10.33996/revistahorizontes.v9i36.909)

# Anexos
