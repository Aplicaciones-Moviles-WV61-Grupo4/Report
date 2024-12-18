# COURSE PROJECT

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Aplicaciones para Dispositivos Móviles - WV61</strong><br>
    <strong>Profesor: Jorge Luis Mayta Guillermo</strong><br>
    <br>INFORME DEL TRABAJO FINAL
</p>
<p align="center">
    <strong>Startup: Aerios</strong><br>
    <strong>Producto: NestHub </strong>
</p>
<div>
    <h3 align="center">Team Members:</h3>
    </div>
<div>
     <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Cancho Corilla, Angel Antonio</td>
            <td>U201721995</td>
        </tr>
        <tr>
            <td>Gamio Upiachihua, Brenda Lucía</td>
            <td>U202120344</td>
        </tr>
        <tr>
            <td>Carpio Cornejo, Miguel Ángel</td>
            <td>U20221c360</td>
        </tr>       
    </table>
</div>
<p align="center">
    <strong> Setiembre 2024</strong>
</p>
<br>

# Contenido

## Tabla de contenidos

### [Capítulo I: Presentación](#capítulo-i-presentación)

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

### [Capítulo II: Needfinding](#capítulo-ii-needfinding)

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
- [2.4. Requirements specification](#24-requirements-specification)
  - [2.4.1. To-Be Scenario Mapping](#241-to-be-scenario-mapping)
  - [2.4.2. User Stories](#242-user-stories)
  - [2.4.3. Impact Mapping](#243-impact-mapping)
  - [2.4.4. Product Backlog](#244-product-backlog)

### [Capítulo III: Arquitectura](#capítulo-iii-arquitectura)

- [3.1. Product Design](#31-product-design)
  - [3.1.1. Style Guidelines](#311-style-guidelines)
    - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
  - [3.1.2. Information Architecture](#312-information-architecture)
    - [3.1.2.1. Organization Systems](#3121-organization-systems)
    - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
    - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
    - [3.1.2.4. Searching Systems](#3124-searching-systems)
    - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
  - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
    - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
    - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
  - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
    - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
    - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
    - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
    - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
    - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
- [3.2. Architecture Overview](#32-architecture-overview)
  - [3.2.1. Domain-Driven Software Architecture](#321-domain-driven-software-architecture)
    - [3.2.1.1. Software Architecture Context Level Diagram](#3211-software-architecture-context-level-diagram)
    - [3.2.1.2. Software Architecture Container Level Diagram](#3212-software-architecture-container-level-diagram)
    - [3.2.1.3. Software Architecture Components Diagram](#3213-software-architecture-components-diagram)
  - [3.2.2. Software Object-Oriented Design](#322-software-object-oriented-design)
    - [3.2.2.1. Class Diagrams](#3221-class-diagrams)
    - [3.2.2.2. Class Dictionary](#3222-class-dictionary)
    - [3.2.2.3. Database Design](#3223-database-design)
    - [3.2.2.4. Database Diagram](#3224-database-diagram)

### [Capítulo IV: Backend Product Implementation & Validation](#capítulo-iv-backend-product-implementation--validation)

- [COURSE PROJECT](#course-project)
- [Contenido](#contenido)
  - [Tabla de contenidos](#tabla-de-contenidos)
    - [Capítulo I: Presentación](#capítulo-i-presentación)
    - [Capítulo II: Needfinding](#capítulo-ii-needfinding)
    - [Capítulo III: Arquitectura](#capítulo-iii-arquitectura)
    - [Capítulo IV: Backend Product Implementation \& Validation](#capítulo-iv-backend-product-implementation--validation)
    - [Capítulo V: Product Implementation \& Validation](#capítulo-v-product-implementation--validation)
    - [Conclusiones](#conclusiones)
    - [Glosario](#glosario)
    - [Bibliografía](#bibliografía)
    - [Anexos](#anexos)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Objetivo Smart](#objetivo-smart)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Description de la StartUp](#111-description-de-la-startup)
    - [When](#when)
    - [Where](#where)
    - [Why](#why)
    - [How](#how)
    - [How much](#how-much)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Requirements specifications](#24-requirements-specifications)
    - [2.4.1. To-Be Scenario Mapping](#241-to-be-scenario-mapping)
    - [2.4.2. User Stories](#242-user-stories)
    - [2.4.3. Impact Mapping](#243-impact-mapping)
    - [2.4.4. Product Backlog](#244-product-backlog)
  - [3.1. Product Design](#31-product-design)
    - [3.1.1. Style Guidelines.](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
      - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
      - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      - [3.1.4.2. Mobile Applications Wireflow Diagram](#3142-mobile-applications-wireflow-diagram)
      - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      - [3.1.4.4. Mobile Applications User Flow Diagram](#3144-mobile-applications-user-flow-diagram)
      - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
  - [3.2. Architecture Overview](#32-architecture-overview)
    - [3.2.1. Domain-Driven Software Architecture](#321-domain-driven-software-architecture)
      - [3.2.1.1. Software Architecture Context Level Diagram](#3211-software-architecture-context-level-diagram)
      - [3.2.1.2. Software Architecture Container Level Diagram](#3212-software-architecture-container-level-diagram)
      - [3.2.1.3. Software Architecture Components Diagram](#3213-software-architecture-components-diagram)
    - [3.2.2. Software Object-Oriented Design](#322-software-object-oriented-design)
      - [3.2.2.1. Class Diagrams](#3221-class-diagrams)
      - [3.2.2.2. Class Dictionary](#3222-class-dictionary)
      - [3.2.2.3. Database Design](#3223-database-design)
      - [3.2.2.4. Database Diagram](#3224-database-diagram)
- [Capítulo IV: Backend Product Implementation \& Validation](#capítulo-iv-backend-product-implementation--validation-1)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide \& Conventions](#413-source-code-style-guide--conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Software Development \& Implementation](#42-software-development--implementation)
    - [4.2.1. Sprint 1](#421-sprint-1)
      - [4.2.1.1. Sprint Planning 1](#4211-sprint-planning-1)
      - [4.2.1.2. Sprint Backlog 1](#4212-sprint-backlog-1)
      - [4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)
      - [4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)
      - [4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)
      - [4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)
      - [4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)
      - [4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)
    - [4.2.2. Sprint 2](#422-sprint-2)
      - [4.2.2.1. Sprint Planning 2](#4221-sprint-planning-2)
      - [4.2.2.2. Sprint Backlog 2](#4222-sprint-backlog-2)
      - [4.2.2.3. Development Evidence for Sprint Review](#4223-development-evidence-for-sprint-review)
      - [4.2.2.4. Testing Suite Evidence for Sprint Review](#4224-testing-suite-evidence-for-sprint-review)
      - [4.2.2.5. Execution Evidence for Sprint Review](#4225-execution-evidence-for-sprint-review)
      - [4.2.2.6. Services Documentation Evidence for Sprint Review](#4226-services-documentation-evidence-for-sprint-review)
      - [4.2.2.7. Software Deployment Evidence for Sprint Review](#4227-software-deployment-evidence-for-sprint-review)
      - [4.2.2.8. Team Collaboration Insights during Sprint](#4228-team-collaboration-insights-during-sprint)
    - [4.2.3. Sprint 3](#423-sprint-3)
      - [4.2.3.1. Sprint Planning 3](#4231-sprint-planning-3)
      - [4.2.3.2. Sprint Backlog 3](#4232-sprint-backlog-3)
      - [4.2.3.3. Development Evidence for Sprint Review](#4233-development-evidence-for-sprint-review)
      - [4.2.3.4. Testing Suite Evidence for Sprint Review](#4234-testing-suite-evidence-for-sprint-review)
      - [4.2.3.5. Execution Evidence for Sprint Review](#4235-execution-evidence-for-sprint-review)
      - [4.2.3.6. Services Documentation Evidence for Sprint Review](#4236-services-documentation-evidence-for-sprint-review)
      - [4.2.3.7. Software Deployment Evidence for Sprint Review](#4237-software-deployment-evidence-for-sprint-review)
      - [4.2.3.8. Team Collaboration Insights during Sprint](#4238-team-collaboration-insights-during-sprint)
    - [4.2.4. Sprint 4](#424-sprint-4)
      - [4.2.4.1. Sprint Planning 4](#4241-sprint-planning-4)
      - [4.2.4.2. Sprint Backlog 4](#4242-sprint-backlog-4)
      - [4.2.4.3. Development Evidence for Sprint Review](#4243-development-evidence-for-sprint-review)
      - [4.2.4.4. Testing Suite Evidence for Sprint Review](#4244-testing-suite-evidence-for-sprint-review)
      - [4.2.4.5. Execution Evidence for Sprint Review](#4245-execution-evidence-for-sprint-review)
      - [4.2.4.6. Services Documentation Evidence for Sprint Review](#4246-services-documentation-evidence-for-sprint-review)
      - [4.2.4.7. Software Deployment Evidence for Sprint Review](#4247-software-deployment-evidence-for-sprint-review)
      - [4.2.4.8. Team Collaboration Insights during Sprint](#4248-team-collaboration-insights-during-sprint)
  - [4.3 Validation Interviews](#43-validation-interviews)
    - [4.3.1 Registro de preguntas](#431-registro-de-preguntas)
    - [4.3.2 Registro de entrevistas](#432-registro-de-entrevistas)
    - [4.3.3 Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)
  - [4.3 Video About the team](#43-video-about-the-team)
  - [Conclusiones](#conclusiones-1)
  - [bibliografía](#bibliografía-1)
  - [Anexos](#anexos-1)

### [Capítulo V: Product Implementation & Validation](#capítulo-v-product-implementation--validation)

- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page & Mobile Application Implementation](#52-landing-page--mobile-application-implementation)
  - [5.2.1. Sprint n](#521-sprint-n)
    - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
    - [5.2.1.2. Sprint Backlog n](#5212-sprint-backlog-n)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)

### [Conclusiones](#conclusiones)

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video App Validation](#video-app-validation)
- [Video About the product](#video-about-the-product)
- [Video About the team](#video-about-the-team)

### [Glosario](#glosario)

### [Bibliografía](#bibliografía)

### [Anexos](#anexos)

---

# Project Report Collaboration Insights

TB1: Las tareas asignadas para la entrega TB1 se han completado y están documentadas en el siguiente repositorio de Github perteneciente a la organización del equipo: [Repositorio Github](https://github.com/Aplicaciones-Moviles-WV61-Grupo4/Report).

**User goal: Visualización de perfil**

# Student Outcome

ABET – EAC - Student Outcome 7: *La capacidad de adquirir y aplicar nuevos conocimientos según sea
necesario, utilizando estrategias deaprendizaje apropiadas.*

<table >
        <tr>
            <th style="text-align:center;">Criterio específico</th>
            <th style="text-align:center;">Acciones realizadas</th>
            <th style="text-align:center;">Conclusiones</th>
        </tr>
        <tr>
            <td align = "left"> Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de ingeniería de software.</td>
            <td align = "left">
            Cancho Corilla, Angel Antonio:<br>
                Se llevaron a cabo reuniones tanto presenciales como virtuales para seleccionar la problemática a tratar. Durante estas reuniones, se establecieron horarios específicos, se programaron encuentros futuros y se asignaron responsabilidades.<br>
            <br>Carpio Cornejo, Miguel Ángel<br>
                Se realizaron sesiones de brainstorming y análisis crítico para identificar posibles soluciones innovadoras a la problemática seleccionada. Estas sesiones permitieron una mayor colaboración entre los miembros del equipo, promoviendo la creatividad y la generación de ideas. Además, se crearon documentos     detallados con las estrategias y pasos a seguir para asegurar una implementación efectiva del proyecto. <br>
            <br>Gamio Upiachihua, Brenda Lucía:<br>
            Para la primera entrega, se comenzó coordinando, planificando y definiendo el alcance de nuestra propuesta. Esto proporciona una base más sólida para la definición y ejecución técnica del proyecto.<br>
	    <br>TB3:<br>
	  	Cancho Corilla, Angel Antonio:<br>
		    He actualizado el backend del proyecto, mejorando su funcionalidad y rendimiento. Además, he agregado nuevas funcionalidades en la aplicación Flutter, optimizando la experiencia del usuario y asegurando que el frontend se comunique de manera efectiva con el backend para ofrecer un servicio más robusto y eficiente.<br><br>
		    Gamio Upiachihua, Brenda Lucía:<br>
		    He mejorado mis conocimientos en desarrollo de aplicaciones móviles al optimizar la navegación de la app, lo que mejora la experiencia del usuario. También he actualizado los reportes para que reflejen con precisión los datos del proyecto. Estas acciones refuerzan mis habilidades técnicas y contribuyen al avance de mi proyecto en soluciones de ingeniería de software.<br>
            <br>Carpio Cornejo, Miguel: <br>
            He actulizado el backend para poder así desplegarlo con sus respectivas configuras previas. Además he actualizado el reporte mostrando el avance del proyecto como grupo.<br>
            <br>TF:<br>
	  	    Cancho Corilla, Angel Antonio:<br>
		    Actualicé mis conocimientos en integración de APIs y optimización de rendimiento, aplicando mejores prácticas para garantizar la sincronización entre el backend y la aplicación, mejorando la eficiencia en el consumo de datos y la experiencia del usuario.
            <br>
            <br>Carpio Cornejo, Miguel: <br><br>
            <br>Carpio Cornejo, Miguel:<br> Se llevaron a cabo sesiones de brainstorming y análisis crítico para identificar soluciones innovadoras a la problemática planteada. Estas actividades permitieron no solo la generación de ideas creativas, sino también una planificación estratégica que define los pasos a seguir. Asimismo, se realizaron actualizaciones en el backend del proyecto, ajustándolo para su despliegue con configuraciones óptimas. Estas acciones reflejan un enfoque metódico y colaborativo, esencial para garantizar la efectividad del proyecto. <br><br>
            Gamio Upiachihua, Brenda Lucía:<br> 
		    Me actualicé en diseño centrado en el usuario y evaluación heurística, mejorando la UI/UX de la aplicación. Además, dirigí los sprints del proyecto, fortaleciendo mis habilidades en gestión ágil de proyectos y optimización de la usabilidad.
            </td>
            <td>Se destaca la importancia de mantener actualizados los conocimientos y conceptos necesarios para el desarrollo profesional, especialmente en el área de soluciones de software. Un enfoque metodológico y colaborativo, como se menciona en las conclusiones, representa una práctica eficaz para el desarrollo de proyectos en este sector, garantizando el uso de las mejores prácticas y herramientas disponibles para cumplir con los objetivos establecidos.</td>           
        </tr>  
        <tr>
            <td align = "left"> Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de tecnologías de ingeniería de software.</td>
            <td align = "left">
            Cancho Corilla, Angel Antonio:<br>
                En el proceso de entrega, se llevó a cabo una investigación y consulta sobre la problemática abordada, con el objetivo de recopilar y organizar la información relevante de manera estructurada y coherente.<br>
            <br>Carpio Cornejo, Miguel Ángel<br>
                Durante la fase de desarrollo, se implementó un enfoque iterativo, realizando pruebas periódicas y evaluaciones del progreso del proyecto. Esto permitió identificar y corregir posibles fallos en etapas tempranas, asegurando la calidad y efectividad de la solución propuesta. Además, se promovió la retroalimentación constante entre los miembros del equipo, lo que contribuyó a un proceso de desarrollo más colaborativo y eficiente. <br>
            <br>Gamio Upiachihua, Brenda Lucía:<br>
            Nos basamos en proyectos anteriores para aplicar la mejora continua y evitar errores del pasado, con el objetivo de lograr un proyecto superior a los anteriores y ejecutarlo de manera más fluida.
		<br><br>
  		TB3:<br>
		    Cancho Corilla, Angel Antonio:<br>
		     He trabajado en el frontend utilizando Flutter y Dart, añadiendo funcionalidades que interactúan directamente con el backend. Esto mejora la experiencia del usuario y refuerza mi comprensión sobre la integración de sistemas. Reconozco que el aprendizaje continuo es fundamental para adaptarse a los cambios en la ingeniería de software, asegurando un desarrollo profesional sólido y eficaz.<br>
		    <br>Gamio Upiachihua, Brenda Lucía:<br>
		    He reconocido la importancia del aprendizaje continuo al mejorar la navegación y actualizar reportes en la aplicación móvil. Estas acciones optimizan la funcionalidad del proyecto y amplían mis habilidades, asegurando que permanezca competente en el campo de la ingeniería de software.<br>
            <br> Carpio Cornejo, Miguel: <br>
            Consultó foros, videos, documentación para mantenerse actualizado y así implementar lo aprendido a la hora de hacer despliegues utilizando tecnlogías actuales y competentes. Reconoció la importancia de dicho aprendizaje para mejorar la calidad de software.<br>
            <br>TF:<br>
	  	    Cancho Corilla, Angel Antonio:<br>
		    Reconozco la importancia del aprendizaje continuo para mejorar mis habilidades en integración de APIs y optimización de rendimiento. Esto me permitió aplicar soluciones eficaces en el proyecto, actualizando constantemente mis conocimientos en tecnologías móviles y asegurando que la aplicación fuera eficiente y funcional.
            <br>
            <br>Carpio Cornejo, Miguel:<br>Durante el desarrollo del proyecto, se implementó un enfoque iterativo que incluyó pruebas constantes y retroalimentación del equipo. Esta dinámica no solo ayudó a mejorar la calidad del software, sino que también potenció el aprendizaje continuo. Además, se invirtió tiempo en consultar foros, videos y documentación técnica, integrando conocimientos actuales en las implementaciones del proyecto. Este proceso destaca la importancia del aprendizaje constante como un pilar en la mejora de las competencias profesionales y en la entrega de soluciones efectivas en ingeniería de software. <br><br>
            Gamio Upiachihua, Brenda Lucía:<br> 
		    El aprendizaje constante sobre UI/UX y evaluación heurística me permitió mejorar la experiencia de usuario en la aplicación. Además, a través de la gestión ágil de proyectos, pude aplicar lo aprendido en metodologías como Scrum, mejorando tanto mis habilidades técnicas como mi capacidad para dirigir equipos de trabajo.
            </td>
            <td>Se enfatiza la relevancia del aprendizaje continuo en el desarrollo profesional y en los proyectos de soluciones de software. La investigación constante, la adopción de herramientas actualizadas y el análisis de experiencias previas reflejan un compromiso con el aprendizaje permanente, lo cual es crucial para mejorar continuamente el desempeño y la calidad de los proyectos.</td>  
        </tr>  

</table >

# Objetivo Smart

<img src="assets/smart-goals.png" alt="SMART">

# Capítulo I: Introducción

## 1.1. StartUp Profile

En esta sección se describirá la descripción de la Startup y el caso de negocio.

### 1.1.1. Description de la StartUp

Aerios es una startup tecnológica fundada en 2024 con el objetivo de revolucionar la industria de los alquileres para eventos. Nuestra plataforma, diseñada por un equipo de jóvenes ingenieros de software, ofrece una amplia gama de funcionalidades, como: búsqueda avanzada, reservas en línea, gestión de pagos, calificaciones y reseñas.

- **¿Cuál es el problema?** <br>
  Organizar un evento, ya que esto implica una ardua tarea al momento de buscar el espacio ideal. La falta de una plataforma unificada dificulta la conexión entre propietarios y organizadores, generando retrasos y frustración en el proceso.

### When

- **¿Cuándo ocurre el problema** <br>
  Tanto propietarios como organizadores de eventos se enfrentan constantemente al desafío de conectar sus necesidades. Ya sea para eventos planificados con meses de anticipación o para aquellos que requieren una solución inmediata, la búsqueda de espacios adecuados es una necesidad recurrente.

- **¿Cuándo utiliza el cliente el producto?** <br>
  Desde la planificación de grandes eventos con meses de anticipación hasta la búsqueda de última hora de un lugar para una reunión pequeña, la necesidad de encontrar el espacio adecuado es constante y diversa.

### Where

- **¿Dónde está el usuario cuando usa el producto?** <br>
  El usuario estaría principalmente en el aplicativo móvil.

- **¿Dónde surge el problema?** <br>
  La principal problemática radica en la complejidad de hallar y reservar espacios que cumplan con los requisitos de un evento, tanto si se planea con anticipación como si se necesita una solución inmediata. Además de poder encontrar un espacio que se ajuste al presupuesto, la capacidad y las características requeridas para un evento específico puede ser una tarea desafiante.

### Why

- **¿Por qué ocurre este problema?** <br>
  La carencia de una plataforma única que conecte a quienes ofrecen espacios para eventos con quienes los buscan genera una serie de inconvenientes. La búsqueda se vuelve engorrosa, lo que a menudo conduce a la frustración de ambas partes y a la pérdida de oportunidades de negocio.

### How

- **¿Cómo prefieren los clientes acceder a nuestro servicio?** <br>
  Los usuarios prefieren acceder al producto a través de un aplicativo móvil por lo conveniente que es usar un app desde su celular, en vez de usar un navegador web.

- **¿Cómo serían las condiciones en la que los usuarios usarían nuestro producto?** <br>
  En NestHub, organizadores de eventos, ya sean sociales o corporativos, encuentran el espacio perfecto para sus celebraciones. Al mismo tiempo, propietarios de espacios pueden conectar con una amplia audiencia y rentabilizar sus instalaciones.

### How much

Nuestros planes de suscripción en NestHub ofrecen una gama de beneficios adicionales para aquellos que buscan una experiencia más completa y pueden adaptarse a las necesidades de cada usuario. Desde opciones gratuitas hasta planes premium con beneficios adicionales, encontrarás el plan perfecto para tu presupuesto y requerimientos.

### 1.2.2. Lean UX Process

En esta seccióm, utilizaremos el enfoque Lean UX para diseñar nuestro producto de software y asegurarnos de que se ajuste a nuestra estrategia de negocio. Al priorizar las necesidades de nuestros usuarios, podremos desarrollar una solución que genere valor y contribuya al éxito de nuestra empresa.

#### 1.2.2.1. Lean UX Problem Statements

1. **Problema:**

- Los organizadores de eventos enfrentan dificultades para encontrar y reservar espacios adecuados para sus eventos de forma eficiente, ya que no existe una plataforma centralizada que reúna todas las opciones disponibles y facilite este proceso.

- Los propietarios de espacios tienen dificultades para conectar con organizadores de eventos interesados en sus instalaciones debido a la falta de visibilidad y herramientas adecuadas para la gestión de reservas.

2. **Declaración del problema:** La falta de una plataforma unificada genera frustración y retrasos para ambos grupos de usuarios, lo que lleva a una experiencia negativa y la pérdida de oportunidades de negocio.
3. **Solución propuesta:** Una plataforma que facilite la búsqueda, comparación, reserva y pago de espacios para eventos en un solo lugar, reduciendo el tiempo y el esfuerzo necesario para ambas partes.

#### 1.2.2.2. Lean UX Assumptions

1. **Business Assumptions:**

- La búsqueda de espacios para eventos es un proceso frustante y consume mucho tiempo.

- La falta de unificación en las opciones de búsqueda y reserva impide a los organizaciones de eventos encontrar opciones adecuadas rápidamente.

2. **Users Assumptions:**

- Los organizadores de eventos prefieren utilizar una aplicación móvil para buscar y reservar espacios, debido a la conveniencia de tener acceso instantáneo desde sus dispositivos.

- Los propietarios de espacios desean aumentar la visibilidad de sus instalaciones y optimizar la gestión de reservas a través de herramientas digitales.

3. **Outcome Assumptions:**

- Al ofrecer una plataforma que centralice las opciones de búsqueda y reserva de espacios para eventos, tanto organizadores como propietarios experimentarán una mejora en la eficiencia del proceso.

- Una aplicación móvil que incluya búsqueda avanzada, gestión de pagos, calificaciones y reseñas atraerá tanto a organizadores como a propietarios de espacios.

#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que al ofrecer una plataforma unificada de búsqueda y reserva de espacios, reduciremos el tiempo de búsqueda para los organizadores de eventos en un 50% durante los primeros tres meses.

- Creemos que al implementar una aplicación móvil con funciones avanzadas (búsqueda avanzada, gestión de pagos, calificaciones y reseñas), aumentaremos el uso de la plataforma por parte de organizadores de eventos en un 30% durante los primeros seis meses.

- Creemos que los organizadores de eventos que actualmente utilizan métodos tradicionales (boca a boca, sitios web individuales, etc.) preferirán nuestra plataforma para sus futuras búsquedas y reservas, ya que será más conveniente y eficiente.

- Creemos que los propietarios de espacios que desean maximizar sus ingresos y la ocupación de sus instalaciones se suscribirán a nuestros planes premium para obtener una mayor visibilidad y herramientas avanzadas.

#### 1.2.2.4. Lean UX Canvas

<p align = "center"><img width="800" alt="Lean Ux Canvas (v2)" src="assets/LeanUX_canvas_v5[1].png"></p>

<p align = "center"><em> Fuente: Elaboración propia. </em></p>

# 1.3. Segmentos Objetivo

En esta sección, identificamos los segmentos específicos de clientes a los que NestHub se dirige, considerando características demográficas, comportamientos y necesidades comunes.

- **Organizadores de Eventos:** <br>
  Se trata de personas que planifican eventos sociales, como bodas, cumpleaños, reuniones familiares, entre otros, así como individuos que organizan eventos de forma regular, ya sean sociales o corporativos.

  - **Características:** Buscan espacios que se ajusten a sus necesidades particulares, tales como capacidad, ubicación, y servicios disponibles. Además, realizan múltiples reservas a lo largo del año.
  - **Necesidades:** Requieren una plataforma que facilite la búsqueda y reserva de espacios, con acceso a información detallada sobre instalaciones y servicios, así como programas de fidelización, descuentos por reservas frecuentes y acceso prioritario a espacios exclusivos.

- **Propiedades de Espacios para eventos:** <br>
  Incluye a personas o empresas que poseen espacios adecuados para eventos, como salones de banquetes, jardines, locales comerciales, entre otros.

  - **Características:** Cuentan con una variedad de espacios con diferentes capacidades y atributos.
  - **Necesidades:** Buscan una promoción eficaz de sus espacios, una gestión eficiente de las reservas y acceso a herramientas para administrar sus listados y la planificación de eventos.

  # Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Hemos realizado una investigación de mercado y descubrimos tres plataformas que ofrecen funciones similares a las de nuestra aplicación que conectan a los propietarios de espacios con los organizadores de eventos. Estos incluyen:

1. **Airbnb:**
Es una plataforma en línea que, desde su fundación en 2008, ha revolucionado la industria hotelera ofreciendo una alternativa a los hoteles convencionales. En más de 191 países, los usuarios pueden alquilar alojamientos a corto plazo, desde habitaciones individuales hasta casas completas. Facilita la comunicación entre los propietarios que desean alquilar sus propiedades y los visitantes que buscan alojamiento temporal.
<div style="text-align: center;">
                <img src="assets/images/logos/logo-airbnb.png" alt="Airbnb" style="max-width: 400px; width: 25%;">
</div>

2. **Vrbo:**
Es una plataforma en línea creada en 1995 que permite a los propietarios alquilar viviendas directamente. El nombre significa "Alquileres de vacaciones por propietario". Es uno de los principales sitios web para alquileres vacacionales en todo el mundo, y los usuarios pueden buscar y reservar casas, apartamentos, cabañas y villas en una variedad de lugares. Esto les da la oportunidad de elegir opciones que se ajusten a sus necesidades y preferencias.
<div style="text-align: center;">
                <img src="assets/images/logos/logo-vrbo.png" alt="Vrbo" style="max-width: 400px; width: 25%;">
</div>

3. **Booking:**
Es una plataforma donde los usuarios pueden reservar hoteles, hostales, apartamentos y otros tipos de alojamiento en todo el mundo. Además, tiene la opción de reservar vuelos, coches y actividades turísticas. Una de las principales plataformas en línea para reservar alojamientos es Booking.com, que tiene una amplia gama de opciones para viajeros de todo tipo. Los usuarios pueden buscar alojamientos según sus preferencias y presupuesto, y a través de la plataforma pueden realizar reservas de manera rápida y conveniente.
<div style="text-align: center;">
                <img src="assets/images/logos/logo-booking.png" alt="Booking" style="max-width: 400px; width: 25%;">
</div>

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se realizó con la finalidad de poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de estos.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        NestHub
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/logos/logo-NestHub3.png" alt="NestHub" width="60px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
      Airbnb
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/logos/logo-airbnb.png" alt="Airbnb" width="60px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      Vrbo
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/logos/logo-vrbo.png" alt="Vrbo" width="60px">
            </div>
        </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Booking
        <div style="text-align: center; margin-top: 10px;">
                <img src="assets/images/logos/logo-booking.png" alt="Booking" width="60px">
        </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Es una plataforma en línea que permite el alquiler de una variedad de espacios para eventos, incluidos salones de eventos, casas y alojamientos temporales. Con una interfaz fácil de usar, conecta a los propietarios con los organizadores y ofrece una solución económica para satisfacer las necesidades de ambos.</td>
    <td colspan="1" valign="top">La plataforma en línea que conecta anfitriones y huéspedes en todo el mundo ha revolucionado el alquiler de alojamientos a corto plazo. Desde habitaciones individuales hasta casas completas, hay una amplia gama de opciones de alojamiento disponibles.</td>
    <td colspan="1" valign="top">Plataforma en línea que permite a los usuarios buscar y reservar viviendas directamente a través de los propietarios Adaptándose a las necesidades y preferencias de los viajeros, ofrece una variedad de opciones de alojamiento, como casas, apartamentos, cabañas y villas, en varios destinos.</td>
    <td colspan="1" valign="top">Booking.com es una plataforma de reservas líder en todo el mundo para alojamiento y actividades turísticas. Ofrece una amplia gama de opciones, desde hoteles hasta apartamentos, y facilita la búsqueda y reserva según las preferencias y presupuesto del usuario.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Tiene una amplia gama de espacios para eventos y una plataforma fácil de usar para gestionar las reservas, lo que lo convierte en una solución completa para la planificación de eventos. NestHub simplifica el proceso de planificación de eventos para organizadores y propietarios de espacios con características como registro gratuito de espacios, búsqueda avanzada y servicio al cliente dedicado.</td>
    <td colspan="1" valign="top">Ofrece una amplia gama de alojamientos en todo el mundo, desde habitaciones individuales hasta casas completas, junto con experiencias locales únicas organizadas por anfitriones. Como resultado, los viajeros pueden personalizar su experiencia y sumergirse en la cultura local.</td>
    <td colspan="1" valign="top">Se especializa en alquileres vacacionales directamente a través de propietarios, lo que permite a los viajeros disfrutar de una experiencia más genuina y única. Vrbo ofrece una amplia gama de alojamientos vacacionales para todos los gustos y presupuestos.</td>
    <td colspan="1" valign="top">Destaca por su amplia gama de alojamiento y servicios, que incluye hoteles, vuelos, alquiler de automóviles y actividades turísticas. La plataforma fácil de usar permite a los usuarios encontrar y reservar alojamiento de manera rápida y sencilla, brindando a los viajeros una solución completa.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Dirigido a organizadores de eventos adultos de 18 años en adelante que buscan espacios para eventos sociales, corporativos o especiales, como bodas, conferencias y fiestas de empresa, entre otros. Además, atrae a empresas y organizaciones que buscan espacios para reuniones profesionales y corporativas dirigidas a adultos.</td>
    <td colspan="1" valign="top">Se enfoca en los viajeros adultos de 18 años en adelante y ofrece una amplia gama de opciones de alojamiento en todo el mundo, desde habitaciones individuales hasta casas completas, para satisfacer las necesidades y preferencias de cada viajero. Además, está dirigido a grupos de amigos, parejas y familias adultas que buscan opciones de alojamiento que cumplan con sus necesidades y presupuestos durante sus vacaciones o escapadas.</td>
    <td colspan="1" valign="top">Se dirige a familias y grupos de amigos de 18 años en adelante que buscan alquilar casas, villas o cabañas para vacaciones o escapadas grupales. Además, atrae a parejas y grupos de amigos adultos que buscan alquilar alojamientos vacacionales para eventos especiales como bodas, reuniones familiares o cumpleaños.</td>
    <td colspan="1" valign="top">Se dirige a viajeros adultos de 18 años en adelante y ofrece una amplia gama de opciones de alojamiento para satisfacer diversas necesidades y preferencias durante sus viajes. Se dirige también a personas que viajan por negocios, parejas en escapadas románticas, grupos de amigos en vacaciones y familias que buscan opciones de alojamiento convenientes y cómodas.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">Para brindar a los organizadores de eventos soluciones completas, NestHub se destaca mediante el marketing de contenidos, la participación en eventos de la industria y la colaboración con proveedores de servicios de eventos.</td>
    <td colspan="1" valign="top">Para publicitar destinos y experiencias únicos, Airbnb trabaja con influencers y campañas publicitarias en redes sociales. Además, utiliza programas de referidos para atraer a más usuarios.</td>
    <td colspan="1" valign="top">Vrbo se enfoca en ofrecer contenido educativo en su sitio web, trabajar con agencias de viajes y ofrecer ofertas exclusivas para que familias y grupos de amigos reserven a través de su plataforma.</td>
    <td colspan="1" valign="top">Para atraer tráfico y aumentar la lealtad del cliente a través de una experiencia personalizada, Booking.com utiliza estrategias de SEO y SEM, así como programas de fidelización.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Aplicación móvil que conecta a organizadores de eventos con propietarios de diferentes espacios, como salones de eventos, jardines y locales comerciales, que buscan alquilarlos para eventos sociales, corporativos o especiales. Proporciona una variedad de herramientas y servicios que ayudan a encontrar, reservar y administrar espacios para eventos.</td>
    <td colspan="1" valign="top">Plataforma en línea que permite a los usuarios alquilar una variedad de alojamientos a corto plazo en todo el mundo, desde habitaciones individuales hasta casas completas. Además de brindar alojamiento, Airbnb también ofrece experiencias locales personalizadas, como excursiones, recorridos gastronómicos y clases de cocina.</td>
    <td colspan="1" valign="top">Plataforma para alquilar viviendas directamente a través de los propietarios Para sus vacaciones o escapadas en todo el mundo, los usuarios pueden encontrar y reservar una amplia gama de propiedades, que van desde casas y apartamentos hasta cabañas y villas.</td>
    <td colspan="1" valign="top">La plataforma en línea permite a los usuarios reservar una variedad de tipos de alojamiento, incluidos hoteles, hostales, apartamentos y otros en todo el mundo. Para completar la experiencia de viaje del usuario, Booking.com le permite reservar vuelos, alquilar autos y actividades turísticas.</td>
  </tr>
  <tr>
      <td colspan="2">Precios & Costos</td>
      <td colspan="1" valign="top">Los precios de NestHub varían dependiendo del lugar, el tamaño de la propiedad, servicios, y el tiempo de uso.</td>
      <td colspan="1" valign="top">El costo promedio puede variar significativamente dependiendo de varios factores, como la ubicación, el tipo de alojamiento, la época del año y la demanda local.</td>
      <td colspan="1" valign="top">Los precios en VRBO pueden variar significativamente dependiendo de la ubicación, el tamaño de la propiedad, las comodidades ofrecidas y la temporada del año.</td>
      <td colspan="1" valign="top">Los precios pueden variar significativamente según la ubicación, la temporada, la demanda y el tipo de alojamiento.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Redes sociales y aplicación móvil donde los usuarios pueden poner en renta su espacio o alquilar un espacio para eventos.</td>
    <td colspan="1" valign="top">Sitio web de Airbnb, aplicación móvil de Airbnb, socios afiliados y asociaciones, redes sociales y marketing digital.</td>
    <td colspan="1" valign="top">Principalmente su sitio web y su aplicación móvil, así como acuerdos de distribución con otros sitios web de viajes o agencias de viajes en línea.</td>
    <td colspan="1" valign="top">Sitio web de Booking.com, aplicación móvil de Booking, agencias de viajes en línea, alianzas con compañías de viajes, afiliados y asociados.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Solución completa para la planificación de eventos.</td>
    <td colspan="1" valign="top">Gran comunidad de anfitriones y usuarios.</td>
    <td colspan="1" valign="top">Variedad de alojamientos en todo el mundo.</td>
    <td colspan="1" valign="top">Interfaz fácil de usar y experiencia intuitiva del usuario.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Dependencia de la disponibilidad de espacios para eventos.</td>
    <td colspan="1" valign="top">Dependencia de la reputación y opiniones de los usuarios.</td>
    <td colspan="1" valign="top">Posible saturación del mercado de alquiler vacacional.</td>
    <td colspan="1" valign="top">Competencia intensa con otras plataformas de alquiler de alojamiento.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">Expansión a nuevos mercados y nichos de eventos.</td>
    <td colspan="1" valign="top">Desarrollo de nuevas características y servicios para mejorar la experiencia del usuario.</td>
    <td colspan="1" valign="top">Alianzas estratégicas con proveedores de servicios de eventos.</td>
    <td colspan="1" valign="top">Aprovechamiento de la tendencia creciente del turismo y los viajes.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Cambios en la regulación de alquileres vacacionales y eventos.</td>
    <td colspan="1" valign="top">Posible disminución de la demanda de viajes debido a crisis económicas o sanitarias.</td>
    <td colspan="1" valign="top">Innovaciones tecnológicas que podrían ser adoptadas por competidores.</td>
    <td colspan="1" valign="top">Posible pérdida de confianza del usuario debido a problemas de seguridad o calidad del servicio.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

- **Diferenciación de la plataforma:** Vamos a identificar y destacar las ventajas de NestHub que la diferencian de otras plataformas de alquiler de espacios para eventos. Esto podría incluir herramientas innovadoras para la gestión de reservas, una interfaz fácil de usar que simplifica la búsqueda y la reserva de espacios, y características adicionales como la personalización de eventos y la integración de servicios de catering o entretenimiento.

- **Comunidad activa:** En la plataforma de NestHub, trabajaremos para fomentar una comunidad activa de propietarios de espacios, organizadores de eventos y clientes. Ofreceremos espacios donde las personas puedan compartir sus experiencias, recomendar lugares y eventos y interactuar entre sí. Esto aumentará la participación de los usuarios y la lealtad a la plataforma.

- **Marketing dirigido:** Para llegar a nuestro público objetivo, utilizaremos estrategias de marketing digital enfocadas. Esto podría incluir la promoción de la plataforma mediante publicidad en redes sociales dirigida a organizadores de eventos y propietarios de espacios, colaboraciones con organizadores de eventos locales e influyentes en el sector, y participación en ferias comerciales y eventos relevantes.

- **Monetización creativa:** Para diversificar nuestras fuentes de ingresos y brindar a nuestros usuarios opciones adaptables, investigaremos varios modelos de monetización. Podríamos ofrecer a los propietarios de espacios servicios premium, como herramientas de gestión de reservas avanzadas o promociones destacadas en sus listados, además de las tarifas estándar por el uso de la plataforma. Además, podríamos considerar incluir servicios adicionales, como la organización de catering o servicios de entretenimiento, por un precio adicional. Los patrocinios de eventos y la publicidad no intrusiva también podrían ser oportunidades de monetización a considerar.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se han definido una cierta cantidad de preguntas para nuestros segmentos objetivos, con la finalidad de obtener información cualitativa como opiniones o descripciones. Esta información nos será de gran ayuda en el desarrollo de nuestra solución.

**Preguntas generales:**

1. ¿Cuál es tu nombre?
2. ¿Qué edad tienes?
3. ¿Dónde vives actualmente?
4. ¿A qué te dedicas?

**Preguntas Segmento 1: Propietarios**

1. ¿Qué desafíos enfrenta actualmente al promocionar y gestionar reservas para su espacio?
2. ¿Qué tipo de propiedades suele alquilar o publicitar? (apartamentos, casas, locales comerciales, terrenos, etc.)
3. De tener experiencia en alquilar su propiedad, ¿cómo ha realizado los pagos de los centros en alquiler?
4. ¿Cómo promociona su espacio para atraer a potenciales clientes? ¿Qué estrategias de marketing ha encontrado más efectivas?
5. ¿Qué te parece más importante al alquilar una propiedad: la facilidad de uso de la plataforma, la seguridad de las transacciones, la diversidad de opciones disponibles, u otros aspectos?
6. ¿Cuáles son las principales características que busca en una plataforma de alquiler de espacios para eventos?
7. ¿Qué incentivos o beneficios podrían motivar a utilizar una plataforma de alquiler de espacios de manera más frecuente?
8. ¿Ha tenido alguna experiencia previa con plataformas similares de alquiler de espacios para eventos?¿Qué aspectos le gustaron?
9. ¿Estarías dispuesto(a) a pagar una tarifa por utilizar una aplicación que te ayude a publicitar o alquilar tu propiedad de manera más eficiente?
10. ¿Qué sugerencias o mejoras tendrías para una aplicación de este tipo que aún no estén disponibles en otras plataformas similares?

**Preguntas Segmento 2: Organizadores**

1. ¿Qué tipo de propiedades alquila regularmente para sus reuniones?
2. ¿Alguna vez has necesitado un lugar de encuentro o festivo de emergencia?
3. ¿Qué tipo de información te gustaría que viniera en las características del local/propiedad? (ej. licencias de eventos, capacidad máxima de gente, etc.)
4. Organizando eventos, ¿alguna vez tuvo un problema grave con las políticas de cancelación?
5. ¿Eres promotor de algún tipo de evento recurrente?
6. ¿Cada cuanto recurres a alquilar lugares o a usarlos?
7. ¿Ves necesario una plataforma como NestHub?
8. ¿De qué maneras ves útil NestHub y cada cuanto lo utilizamos?
9. ¿Hay alguna otra consideración o solicitud especial que crea que deba adicionarse para hacer un mejor servicio?
10. ¿Qué tan importante es para ti la flexibilidad de horarios al momento de reservar un espacio para tu evento?

### 2.2.2. Registro de entrevistas

**Entrevista 1:**

Nombres: Miguel Ángel

Apellidos: Alvizuri

Edad: 24

Lugar de residencia: Chorrillos, Lima

Entrevistador: Miguel Carpio Cornejo

Evidencia de la entrevista: <img src="assets/entrevista1-miguel.png">
[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c360_upc_edu_pe/Ef5cabeHfFBLqiaOZrxatsIByBMU0CnLw_F7hNGOMQR9SQ?e=Smle5l)

Resumen de la entrevista:

Miguel Alvizuri enfrenta varios desafíos al promocionar y gestionar reservas para sus espacios. La competencia es fuerte y es crucial coordinar y confirmar reservas sin errores para mantener una buena reputación. Suele alquilar salones de eventos y casas de campo, ideales para bodas, fiestas y eventos corporativos.

En cuanto a los pagos, prefiere utilizar transferencias bancarias o plataformas de pago en línea por su seguridad y comodidad. Para atraer a potenciales clientes, utiliza redes sociales, anuncios en Google, y colaboraciones con organizadores de eventos. Las estrategias más efectivas han sido las redes sociales por su capacidad de mostrar imágenes atractivas y recibir retroalimentación directa.

Considera que la seguridad de las transacciones es fundamental, seguida de la facilidad de uso de la plataforma. Busca características como seguridad, facilidad de uso, buen soporte al cliente, y visibilidad en motores de búsqueda y redes sociales en una plataforma de alquiler de espacios. Incentivos como descuentos en comisiones y programas de fidelidad podrían motivarlo a usar la plataforma más frecuentemente.

Ha tenido experiencias previas con plataformas como Airbnb, valorando su facilidad de uso, visibilidad, y seguridad en las transacciones. Estaría dispuesto a pagar una tarifa por una aplicación que mejore la publicidad y gestión de sus propiedades. Sugiere mejoras como integraciones avanzadas con redes sociales, herramientas de análisis de mercado, opciones de personalización de anuncios y soporte técnico 24/7.

**Entrevista 3:**

Nombres: Erick Ernesto

Apellidos: Guerrero

Edad: 20

Lugar de residencia: Chorrillos, Lima

Entrevistador: Brenda Gamio Upiachihua

Evidencia de la entrevista: <img src="assets/entrevista2-erick.png">
[Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120344_upc_edu_pe/Eeakt8f2BWJKqJu8D5wSkyABHCwtA6nc5b7KAq-3Fyp-gw?e=08LWD2&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

Resumen de la entrevista:

Erick Guerrero es un joven trabajador de 20 años que suele hacer reuniones casuales con su grupo de amigos. Si bien no es el que suele organizar eventos grandes como quinciañeros o coferencias en su trabajo, si se encarga de organizar y encontrar las locales en dónde divertirse con sus amigos.

Lo que más le importa saber sobre el local de que va estar utilizando, es la condición del espacio en donde estará. Cómo se encuentran las tuverías y desagüe para evitar poner en peligro a él y sus amigos. Cómo de seguro es la casa debido a antigüedad, etc.

Por último, menciona que estos servicios de alquiler de centros para eventos, suelen ser a través de organizadores. Esto implica transladarse hasta dónde está el organizador y el local, gastanto dinero en pasajes, gasolina. También que requiere esfuerzo y tiempo. Sin embargo, que un servicio web que facilite todo este proceso le parece una idea muy buena.

### 2.2.3. Análisis de entrevistas

Las entrevistas ofrecen una visión detallada y matizada sobre las expectativas y requisitos de los distintos actores involucrados en el ámbito de las apps móviles para el alquiler de locales destinados a eventos. Tanto los propietarios, los organizadores de eventos, como los usuarios finales resaltan la importancia de contar con sistemas que garanticen la seguridad en las transacciones financieras, la claridad en los acuerdos contractuales y una comunicación fluida y eficaz. La facilidad de uso y la intuitividad de la interfaz se identifican como características clave para una experiencia positiva para todos los participantes, mientras que la disponibilidad de una amplia gama de opciones de espacios para eventos resulta esencial para satisfacer diversas necesidades y preferencias. Además, se observa que algunos usuarios están dispuestos a pagar por servicios premium que ofrezcan beneficios adicionales, como una mayor visibilidad de sus espacios dentro de la app.

Los propietarios de espacios para eventos tienen preocupaciones y necesidades particulares al utilizar apps móviles de alquiler. Para ellos, es fundamental la seguridad en las transacciones financieras y la integridad de los contratos. También valoran la posibilidad de promocionar efectivamente sus propiedades, buscando una app que les permita llegar a un público amplio y relevante. La comunicación clara y fluida con los organizadores de eventos es crucial para evitar malentendidos y conflictos. Por último, algunos propietarios están dispuestos a invertir en servicios premium que les otorguen ventajas adicionales, como una mayor visibilidad de sus espacios en la app. En resumen, los propietarios buscan apps que les ofrezcan seguridad, visibilidad, comunicación eficiente y opciones para maximizar el rendimiento de sus espacios para eventos.

Los organizadores de eventos también presentan necesidades específicas al utilizar apps móviles para alquilar locales. Para ellos, la facilidad para encontrar y reservar espacios adecuados es primordial, especialmente en situaciones de emergencia o cambios de última hora. Valoran la transparencia en los contratos y la comunicación efectiva con los propietarios para evitar malentendidos y asegurar una experiencia sin inconvenientes. Asimismo, buscan apps que ofrezcan una amplia variedad de opciones de espacios para eventos que se adapten a sus necesidades específicas y horarios. La disponibilidad de herramientas avanzadas de búsqueda y filtrado es igualmente importante para localizar el lugar ideal. En resumen, los organizadores de eventos buscan apps que les proporcionen facilidad de uso, transparencia en los procesos, comunicación eficiente y una amplia gama de opciones de espacios para eventos.

## 2.3. Needfinding

### 2.3.1. User Personas

**Segmento propietario:**

<img src="assets/userpersona-maria.png" alt="Segmento objetivo propietario">

**Segmento organizador:**

<img src="assets/userpersona-eduardo.png" alt="Segmento objetivo organizador">

### 2.3.2. User Task Matrix

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <td></td>
        <td colspan=2>
            <b>User Persona</b>
        </td>
    </tr>
    <tr>
        <td></td>
        <td colspan=2>
            <b>María Pérez</b> </br>Propietaria de un local para eventos
        </td>
    </tr>
    <tr>
        <td>
            <b>Task</b>
        </td>
        <td>
            <b>Frequency</b>
        </td>
        <td>
            <b>Importance</b>
        </td>
    </tr>
    <tr>
        <td>
            Organizar eventos y administrar reservas
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Promocionar la ubicación a través de canales de marketing como las redes sociales
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Mantener el lugar limpio y bien mantenido
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Comunicarse de manera efectiva con clientes y proveedores
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Explorar nuevas oportunidades de crecimiento y negocios
        </td>
        <td>
            Medium
        </td>
        <td>
            Medium
        </td>
    </tr>
</table>

</br></br>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <td></td>
        <td colspan=2>
            <b>User Persona</b>
        </td>
    </tr>
    <tr>
        <td></td>
        <td colspan=2>
            <b>Eduardo Robles</b> </br>Organizador de Eventos
        </td>
    </tr>
    <tr>
        <td>
            <b>Task</b>
        </td>
        <td>
            <b>Frequency</b>
        </td>
        <td>
            <b>Importance</b>
        </td>
    </tr>
    <tr>
        <td>
            Buscar y reservar espacios para eventos
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Contactar a los dueños de los espacios
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            La diversidad de los tipos de espacios disponibles debe ser buscada.
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Reservar espacios para diferentes tipos de eventos
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Estar dispuesto a pagar por una experiencia de plataforma mejorada
        </td>
        <td>
            Medium
        </td>
        <td>
            Medium
        </td>
    </tr>
    <tr>
        <td>
            Utilizar una plataforma que es simple de usar y fácil de entender
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
</table>

### 2.3.3. User Journey Mapping

**Segmento propietario:**

<img src="assets/journeymap-segment1.png" alt="Segmento objetivo propietario">

**Segmento organizador:**

<img src="assets/journeymap-segment2.png" alt="Segmento objetivo organizador">

### 2.3.4. Empathy Mapping

**Segmento propietario:**

<img src="assets/empathymap-maria.png" alt="Segmento objetivo propietario">

**Segmento organizador:**

<img src="assets/empathymap-eduardo.png" alt="Segmento objetivo organizador">

### 2.3.5. As-is Scenario Mapping

**Segmento propietario:**

<img src="assets/as-is-scenario/as-is-scenario-propietario.jpg" alt="Segmento objetivo propietario">

**Segmento organizador:**

<img src="assets/as-is-scenario/as-is-scenario-organizador.jpg" alt="Segmento objetivo organizador">

## 2.4. Requirements specifications

### 2.4.1. To-Be Scenario Mapping

**Propietario de Espacio para Eventos**
![toBePropietario](/assets/to-be-scenario/Tobe_Scenario_Mapping_Propietario_png.png)

**Usuario para Búsqueda de Espacio para Eventos**
![tobeUsuario](/assets/to-be-scenario/Tobe_Scenario_Mapping_Usuario_png.png)

### 2.4.2. User Stories

<table> <thead> <tr> <th>Epic / Story ID</th> <th>Título</th> <th>Descripción</th> <th>Criterios de Aceptación</th> <th>Relacionado con (Epic ID)</th> </tr> </thead> <tbody> <tr> <td>US01</td> <td>Visualización de Información Clave</td> <td>Como visitante de la landing page, quiero ver una presentación clara de los beneficios de NestHub, para entender rápidamente cómo la plataforma me puede ayudar a alquilar o encontrar espacios para eventos.</td> <td> <h5>Escenario 01: Presentación de los Beneficios de Forma Destacada</h5> Dado que un visitante accede a la landing page de NestHub. Cuando la página se carga completamente y el usuario ve la sección principal. Entonces los beneficios clave de la plataforma se muestran de manera destacada con textos claros y elementos visuales atractivos, captando la atención del usuario. </td> <td>EP01</td> </tr> <tr> <td>US02</td> <td>Explorar Espacios Populares</td> <td>Como usuario, quiero ver los espacios más populares y mejor calificados destacados en la landing page, para conocer las opciones más recomendadas sin tener que buscarlas.</td> <td> <h5>Escenario 01: Visualización de Espacios Populares en la Landing Page</h5> Dado que un usuario accede a la landing page de NestHub. Cuando el usuario revisa la sección principal de la página. Entonces se muestran los espacios más populares y mejor calificados en una sección destacada con imágenes, calificaciones y una breve descripción, para que el usuario pueda ver rápidamente las opciones más recomendadas. </td> <td>EP01</td> </tr> <tr> <td>US03</td> <td>Acceso Rápido a Registro e Inicio de Sesión</td> <td>Como nuevo usuario, quiero encontrar botones de registro e inicio de sesión fácilmente accesibles en la landing page, para empezar a usar la plataforma rápidamente.</td> <td> <h5>Escenario 01: Visualización de Botones de Registro e Inicio de Sesión</h5> Dado que un usuario accede a la landing page de NestHub. Cuando la página se carga completamente y el usuario revisa la parte superior de la página. Entonces se muestran de forma destacada y accesible los botones de "Registrarse" e "Iniciar Sesión" en la barra de navegación o en una sección visible, permitiendo al usuario acceder rápidamente a las opciones para crear una cuenta o iniciar sesión. </td> <td>EP01</td> </tr> <tr> <td>US04</td> <td>Visualización de Variedad de Locales</td> <td>Como usuario que busca alquilar un espacio para eventos, quiero ver una sección destacada en la landing page que muestre la variedad de locales disponibles, para tener una idea clara de las diferentes opciones que ofrece la plataforma y encontrar el tipo de espacio que mejor se adapte a mis necesidades.</td> <td> <h5>Escenario 01: Presentación de la Variedad de Locales en la Landing Page</h5> Dado que un usuario accede a la landing page de NestHub. Cuando el usuario desplaza la página hacia la sección de "Variedad". Entonces se muestra una sección con información destacada sobre la amplia variedad de locales disponibles, incluyendo diferentes tipos de espacios como salones, terrazas, jardines, y más, acompañados de imágenes representativas y descripciones breves que resaltan la diversidad. </td> <td>EP01</td> </tr> <tr> <td>US05</td> <td>Registro de Propietario</td> <td>Como propietario de un espacio para eventos, quiero poder registrarme fácilmente en NestHub para ofrecer mi espacio en alquiler y llegar a más clientes potenciales.</td> <td> <h5>Escenario 01: Registro exitoso</h5> Dado que un propietario desea registrar su espacio en NestHub. Cuando el propietario completa el formulario de registro con la información requerida. Entonces el propietario recibe una confirmación de registro y puede acceder a su cuenta. <h5>Escenario 02: Validación de datos</h5> Dado que un propietario completa el formulario de registro en NestHub. Cuando el propietario envía el formulario. Entonces los datos proporcionados se validan para garantizar la precisión y la autenticidad. </td> <td>EP02</td> </tr> <tr> <td>US06</td> <td>Búsqueda y Filtrado de Espacios</td> <td>Como organizador de eventos, quiero poder buscar y filtrar fácilmente espacios disponibles en NestHub para encontrar el lugar perfecto para mi evento, según mis criterios específicos.</td> <td> <h5>Escenario 01: Búsqueda por ubicación</h5> Dado que un organizador busca un espacio para eventos en una ubicación específica. Cuando el organizador ingresa la ubicación deseada en el campo de búsqueda. Entonces se muestran los espacios disponibles en esa ubicación. <h5>Escenario 02: Filtrado por capacidad</h5> Dado que un organizador desea un espacio con capacidad para un número específico de personas. Cuando el organizador aplica un filtro de capacidad en la búsqueda. Entonces se muestran solo los espacios que cumplen con ese criterio. </td> <td>EP03</td> </tr> <tr> <td>US07</td> <td>Reservas de Espacios</td> <td>Como organizador de eventos, quiero poder reservar un espacio para mi evento en NestHub para garantizar su disponibilidad en la fecha deseada.</td> <td> <h5>Escenario 01: Proceso de Reserva</h5> Dado que un organizador ha encontrado el espacio ideal en NestHub. Cuando el organizador selecciona el espacio y la fecha deseada. Entonces se muestra un formulario de reserva para completar los detalles del evento. <h5>Escenario 02: Confirmación de Reserva</h5> Dado que un organizador ha completado el formulario de reserva en NestHub. Cuando el organizador envía la solicitud de reserva. Entonces recibe una confirmación de reserva y los detalles se actualizan en su cuenta. </td> <td>EP03</td> </tr> <tr> <td>US08</td> <td>Calificaciones y Comentarios sobre Espacios</td> <td>Como organizador de eventos, quiero poder ver las calificaciones y comentarios de otros usuarios sobre los espacios en NestHub para tomar una decisión informada al seleccionar un espacio para mi evento.</td> <td> <h5>Escenario 01: Visualización de Calificaciones</h5> Dado que un organizador está revisando las opciones de espacios en NestHub. Cuando el organizador selecciona un espacio en particular. Entonces se muestran las calificaciones y comentarios de otros usuarios sobre ese espacio. <h5>Escenario 02: Aporte de Comentarios</h5> Dado que un organizador ha utilizado un espacio reservado a través de NestHub. Cuando el evento ha concluido. Entonces el organizador puede dejar un comentario y una calificación sobre su experiencia en ese espacio. </td> <td>EP04</td> </tr> <tr> <td>US09</td> <td>Comunicación Directa con Propietarios</td> <td>Como organizador de eventos en NestHub, quiero poder comunicarme directamente con los propietarios de los espacios para aclarar dudas, coordinar detalles y resolver cualquier problema de manera rápida y efectiva.</td> <td> <h5>Escenario 01: Mensajería Instantánea</h5> Dado que un organizador ha reservado un espacio en NestHub. Cuando necesita comunicarse con el propietario del espacio. Entonces puede enviar mensajes directos a través de la plataforma para obtener respuestas rápidas y resolver cualquier problema. <h5>Escenario 02: Gestión de Consultas</h5> Dado que un organizador tiene preguntas o solicitudes específicas sobre un espacio en NestHub. Cuando envía un mensaje al propietario. Entonces recibe una respuesta oportuna y personalizada para abordar sus inquietudes. </td> <td>EP05</td> </tr> <tr> <td>EP10/US01</td> <td>Acceder a EndPoints</td> <td>Como desarrollador, quiero tener acceso a los endpoints de la aplicación para poder interactuar con ella.</td> <td> <h5>Escenario 01: Solicitud Correcta a la API</h5> Dado que el desarrollador hace uso del endpoint para interactuar con la aplicación. Cuando se realiza la solicitud al API. Entonces el API devuelve un response con toda la data solicitada. </td> <td>EP10</td> </tr> <tr> <td>EP10/US08</td> <td>Creación de Persistencia para la Entidad Local</td> <td>Como desarrollador, quiero realizar la persistencia de la información para la entidad Local.</td> <td> <h5>Escenario 01: Registro de Datos del Local</h5> Dado que se recibe la data del exterior. Y esta se valida correctamente. Entonces esta data se registra en la tabla de datos de la entidad Local en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US09</td> <td>Creación de Persistencia para la Entidad Reserva</td> <td>Como desarrollador, quiero realizar la persistencia de la información para la entidad Reserva.</td> <td> <h5>Escenario 01: Registro de Datos de Reserva</h5> Dado que se recibe la data del exterior. Y esta se valida correctamente. Entonces esta data se registra en la tabla de datos de la entidad Reserva en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US10</td> <td>Creación de Persistencia para la Entidad Usuario</td> <td>Como desarrollador, quiero realizar la persistencia de la información para la entidad Usuario.</td> <td> <h5>Escenario 01: Registro de Datos de Usuario</h5> Dado que se recibe la data del exterior. Y esta se valida correctamente. Entonces esta data se registra en la tabla de datos de la entidad Usuario en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US12</td> <td>Actualización de Entidad Local</td> <td>Como desarrollador, quiero implementar la lógica para actualizar la información de un Local.</td> <td> <h5>Escenario 01: Actualización Correcta</h5> Dado que se recibe la data del exterior. Y esta se valida correctamente. Entonces esta data se actualiza en la tabla de datos de la entidad Local en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US13</td> <td>Actualización de Entidad Reserva</td> <td>Como desarrollador, quiero implementar la lógica para actualizar la información de una Reserva.</td> <td> <h5>Escenario 01: Actualización Correcta</h5> Dado que se recibe la data del exterior. Y esta se valida correctamente. Entonces esta data se actualiza en la tabla de datos de la entidad Reserva en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US14</td> <td>Actualización de Entidad Usuario</td> <td>Como desarrollador, quiero implementar la lógica para actualizar la información de un Usuario.</td> <td> <h5>Escenario 01: Actualización Correcta</h5> Dado que se recibe la data del exterior. Y esta se valida correctamente. Entonces esta data se actualiza en la tabla de datos de la entidad Usuario en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US15</td> <td>Eliminación de Entidad Local</td> <td>Como desarrollador, quiero implementar la lógica para eliminar la información de un Local.</td> <td> <h5>Escenario 01: Eliminación Correcta</h5> Dado que se recibe una solicitud de eliminación. Entonces se elimina el registro correspondiente de la tabla de datos de la entidad Local en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US16</td> <td>Eliminación de Entidad Reserva</td> <td>Como desarrollador, quiero implementar la lógica para eliminar la información de una Reserva.</td> <td> <h5>Escenario 01: Eliminación Correcta</h5> Dado que se recibe una solicitud de eliminación. Entonces se elimina el registro correspondiente de la tabla de datos de la entidad Reserva en la base de datos. </td> <td>EP10</td> </tr> <tr> <td>EP10/US17</td> <td>Eliminación de Entidad Usuario</td> <td>Como desarrollador, quiero implementar la lógica para eliminar la información de un Usuario.</td> <td> <h5>Escenario 01: Eliminación Correcta</h5> Dado que se recibe una solicitud de eliminación. Entonces se elimina el registro correspondiente de la tabla de datos de la entidad Usuario en la base de datos. </td> <td>EP10</td> </tr> </tbody> </table>

### 2.4.3. Impact Mapping

**Propietario de Espacio para Eventos**
![ImpactMapPropietario](/assets/impact-mapping/Impact_map_propietario.png)

**Usuario para Búsqueda de Espacio para Eventos**
![ImpactMapUsuario](/assets/impact-mapping/Impact_map_usuario.png)

### 2.4.4. Product Backlog

Utilizamos la escala de Fibonacci para la estimación de los Story Points

<table>
    <thead>
        <tr>
            <th>User Story Id</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Story Points (1/2/3/5)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>US01</td>
            <td>Visualización de Información Clave</td>
            <td>Como visitante de la landing page, quiero ver una presentación clara de los beneficios de NestHub, para entender rápidamente cómo la plataforma me puede ayudar a alquilar o encontrar espacios para eventos.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>US02</td>
            <td>Explorar Espacios Populares</td>
            <td>Como usuario, quiero ver los espacios más populares y mejor calificados destacados en la landing page, para conocer las opciones más recomendadas sin tener que buscarlas.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>US03</td>
            <td>Acceso Rápido a Registro e Inicio de Sesión</td>
            <td>Como nuevo usuario, quiero encontrar botones de registro e inicio de sesión fácilmente accesibles en la landing page, para empezar a usar la plataforma rápidamente.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>US04</td>
            <td>Visualización de Variedad de Locales</td>
            <td>Como usuario que busca alquilar un espacio para eventos, quiero ver una sección destacada en la landing page que muestre la variedad de locales disponibles, para tener una idea clara de las diferentes opciones que ofrece la plataforma y encontrar el tipo de espacio que mejor se adapte a mis necesidades.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>US05</td>
            <td>Registro de Propietario</td>
            <td>Como propietario de un espacio para eventos, quiero poder registrarme fácilmente en NestHub para ofrecer mi espacio en alquiler y llegar a más clientes potenciales.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>US06</td>
            <td>Registro de Espacio Sencillo</td>
            <td>Como propietario de un espacio para eventos en NestHub, quiero poder registrar mi espacio de manera rápida y sencilla para comenzar a recibir solicitudes de reserva lo antes posible.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>US07</td>
            <td>Búsqueda y Filtrado de Espacios</td>
            <td>Como organizador de eventos, quiero poder buscar y filtrar fácilmente espacios disponibles en NestHub para encontrar el lugar perfecto para mi evento, según mis criterios específicos.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>US08</td>
            <td>Reservas de Espacios</td>
            <td>Como organizador de eventos, quiero poder reservar un espacio para mi evento en NestHub para garantizar su disponibilidad en la fecha deseada.</td>
            <td>5</td>
        </tr>
        <tr>
            <td>US09</td>
            <td>Calificaciones y Comentarios sobre Espacios</td>
            <td>Como organizador de eventos, quiero poder ver las calificaciones y comentarios de otros usuarios sobre los espacios en NestHub para tomar una decisión informada al seleccionar un espacio para mi evento.</td>
            <td>3</td>
        </tr>
        <tr>
            <td>US10</td>
            <td>Calidad de Servicio Garantizada</td>
            <td>Como organizador de eventos en NestHub, quiero tener la certeza de que los espacios disponibles cumplen con altos estándares de calidad y seguridad para garantizar una experiencia positiva para mis invitados.</td>
            <td>2</td>
        </tr>
        <tr>
            <td>US11</td>
            <td>Comunicación Directa con Propietarios</td>
            <td>Como organizador de eventos en NestHub, quiero poder comunicarme directamente con los propietarios de los espacios para aclarar dudas, coordinar detalles y resolver cualquier problema de manera rápida y efectiva.</td>
            <td>5</td>
        </tr>
    </tbody>
</table>

## 3.1. Product Design

### 3.1.1. Style Guidelines.

Un Style Guideline es un conjunto de directrices y estándares que establecen la forma correcta de redactar, diseñar o presentar documentos, contenido web, software y otros tipos de trabajos creativos. A continuación, se presentan las especificaciones de los parámetros aplicados en la estructura del proyecto.

#### 3.1.1.1. General Style Guidelines

**Descripción general:** Queremos captar la atención del usuario desde el inicio, diseñando una presentación del producto que genere una conexión instantánea y fácil de identificar.

**Descripción de la marca:** NestHub es una startup tecnológica fundada en 2024 por un grupo de estudiantes de Ingeniería de Software. Nuestra empresa se enfoca en facilitar el proceso de alquiler de espacios para eventos, ofreciendo una plataforma innovadora y accesible tanto para propietarios como para organizadores.

**Misión:** Nuestra misión es hacer que el alquiler de espacios para eventos sea sencillo y eficiente mediante una plataforma intuitiva que conecte rápidamente a propietarios y organizadores de manera conveniente.

**Visión:** Aspiramos a ser la plataforma líder a nivel global en el alquiler de espacios para eventos, promoviendo la eficiencia y la satisfacción de nuestros usuarios.

**Nombre de la marca:** Debido a que el startup se centra en el alquiler y la promoción de espacios para eventos, se decidió nombrarla “NestHu” para reflejar su propósito de forma clara y directa.

<img src="assets/images/logos/logo-nesthub3.png" alt="NestHub" width="250px">

**Tipografía:** El equipo seleccionó el siguiente tamaño para la fuente:

<img src="assets/product-design/tipografia.png" alt="tipografia">

Y se realizaron las siguientes modificaciones:

<img src="assets/product-design/tipografia2.png" alt="tipografia">

**Colores:** La paleta de colores seleccionada incluye:

<img src="assets/product-design/color.png" alt="colors">

<img src="assets/product-design/color2.png" alt="colors">

### 3.1.2. Information Architecture

#### 3.1.2.1. Organization Systems

**Menú principal**

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Tarifas</td>
            <td>La página presenta planes de suscripción que ofrecen beneficios específicos a diferentes precios, adecuados para cualquier tipo de presupuesto.</td>
        </tr>
        <tr>
            <td>Log In</td>
            <td>La página permite a los usuarios iniciar sesión en su cuenta. Si no tienen una cuenta, también hay una sección para registrarse gratuitamente en el servicio web.</td>
        </tr>
        <tr>
            <td>Publicar centro</td>
            <td>Primero, la página solicitará que inicies sesión para identificar al usuario que desea publicar su propiedad. Después, se mostrará una ventana donde podrás ingresar todos los datos y características de la propiedad.</td>
        </tr>
        <tr>
            <td>Alquilar centro</td>
            <td>Primero, la página solicitará que inicies sesión para identificar al usuario que desea publicar su propiedad. Después, se mostrará una ventana donde podrás ingresar todos los datos y características de la propiedad.</td>
        </tr>
        <tr>
            <td>Alquilar centro</td>
            <td>La página mostrará inicialmente los centros ya publicados disponibles para alquiler. Además, incluye una barra de búsqueda con filtros para encontrar los centros más adecuados de manera rápida y eficiente.</td>
        </tr>
        <tr>
            <td>Barra de búsqueda</td>
            <td>En la misma página principal se muestra una barra para poder buscar centros a través de distritos.</td>
        </tr>
        <tr>
            <td>Lista de ciudades destacadas</td>
            <td>La página principal te mostrará toda una lista de las ciudades más populares que el público ha alquilado para sus eventos.</td>
        </tr>
    </tbody>
</table>

**Página de Tarifas**

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Lista de planes de suscripción</td>
            <td>La página mostrará todos los planes que ofrece el servicio.</td>
        </tr>
        <tr>
            <td>Detalles de planes</td>
            <td>La página mostrará los detalles de todos los planes que ofrece el servicio.</td>
        </tr>
    </tbody>
</table>

**Página de Log In**

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Registro y autenticación</td>
            <td>La página de inicio puede ofrecer una visión general del servicio y resaltar sus características principales.</td>
        </tr>
    </tbody>
</table>

**Página de Publicar centro**

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Paso 1</td>
            <td>La página mostrará todos los detalles que se deben poner sobre el centro que el propietario quiere alquilar.</td>
        </tr>
        <tr>
            <td>Paso 2</td>
            <td>La página muestra las características que se deben agregar para el anuncio de la propiedad a alquilar sea como el propietario quiera que se vea.</td>
        </tr>
        <tr>
            <td>Paso 3</td>
            <td>La página mostrará los planes para mantener su anuncio en alquiler y el usuario decidirá qué plan usará.</td>
        </tr>
    </tbody>
</table>

**Página de Alquilar centro**

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Filtros de búsqueda</td>
            <td>Permite a los usuarios ajustar los resultados de búsqueda según ubicación, tipo de servicio, calificaciones, entre otros criterios.</td>
        </tr>
        <tr>
            <td>Lista de propiedades</td>
            <td>Presenta los resultados de la búsqueda con un resumen de la información de cada centro técnico.</td>
        </tr>
        <tr>
            <td>Detalles de propiedades</td>
            <td>Al seleccionar un centro técnico, se muestra información detallada, así como calificaciones y comentarios.</td>
        </tr>
        <tr>
            <td>Comentarios y calificaciones</td>
            <td>Ofrece a los usuarios la posibilidad de añadir comentarios y calificaciones sobre el servicio.</td>
        </tr>
    </tbody>
</table>

**Página de favoritos:** Muestra los centros en alquiler marcados como favoritos por el usuario.

**Otras páginas y funciones**

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Perfil de usuario</td>
            <td>Permite a los usuarios gestionar su perfil y la información personal.</td>
        </tr>
        <tr>
            <td>Configuraciones</td>
            <td>Permite a los usuarios y técnicos configurar sus preferencias.</td>
        </tr>
        <tr>
            <td>Pagina acerca de nosotros</td>
            <td>Información sobre la empresa o la aplicación.</td>
        </tr>
        <tr>
            <td>Ayuda y soporte</td>
            <td>Recursos de ayuda, preguntas frecuentes y opciones de asistencia.</td>
        </tr>
    </tbody>
</table>

**Barra de navegación:** Una barra de navegación intuitiva y uniforme en la parte superior de cada página facilita el acceso a las secciones principales de la aplicación.
**Diseño adaptativo:** La aplicación debe ser fácil de usar en dispositivos de escritorio y móviles, ajustando la interfaz según el tamaño de la pantalla.

#### 3.1.2.2. Labelling Systems

Para los sistemas de etiquetado, hemos decidido organizar el contenido mediante encabezados que agrupan las secciones accesibles. De este modo, el usuario puede identificar fácilmente dónde hacer clic para acceder a cada sección.

<table>
    <thead>
        <tr>
            <th>Topico</th>
            <th>Definición</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Lugares</td>
            <td>Sección principal que mostrará los centros más populares y mejor calificados tan pronto como el usuario acceda al enlace.</td>
        </tr>
        <tr>
            <td>Publica</td>
            <td>En esta sección, proporcionaremos a los usuarios la información necesaria que deben ingresar sobre su propiedad para que pueda ser publicada.</td>
        </tr>
        <tr>
            <td>Variedad</td>
            <td>Aquí, el usuario podrá seleccionar el tipo de espacio que desea para su evento.</td>
        </tr>
        <tr>
            <td>Premium</td>
            <td>En esta sección, se mostrarán los planes y tarifas disponibles que ofrecemos.</td>
        </tr>
        <tr>
            <td>Iniciar Sesión</td>
            <td>Los clientes podrán iniciar sesión en su cuenta desde aquí, y si no tienen una cuenta, también podrán registrarse desde esta sección.</td>
        </tr>
        <tr>
            <td>Registrarse</td>
            <td>Los clientes podrán registrarse como nuevos usuarios desde aquí; si ya tienen una cuenta, también podrán iniciar sesión desde esta sección.</td>
        </tr>
        <tr>
            <td>Barra de búsqueda</td>
            <td>En esta sección, el usuario podrá buscar centros para eventos de acuerdo con sus preferencias.</td>
        </tr>
    </tbody>
</table>

#### 3.1.2.3. SEO Tags and Meta Tags

Las meta etiquetas permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web pueden leerlas. Estas etiquetas facilitan el análisis de archivos HTML y apoyan el mantenimiento del contenido, además de influir en el posicionamiento de la página en los motores de búsqueda.<br>

**Título**
<br>Las meta etiquetas permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las interpretan. Facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido, además de afectar el posicionamiento en los motores de búsqueda.<br>
`<title>Register your processes with NestHub</title>`

**Codificación de caracteres**
<br>Se ha optado por utilizar utf-8 debido a su eficiencia en el uso de memoria. Es más eficiente en términos de memoria para caracteres del BMP (Plano Multilingüe Básico), que abarca la mayoría de los caracteres comunes.<br>
`<meta charset="utf-8">`

**Descripción**
<br>Esta meta etiqueta proporciona un resumen del contenido de la página web, ofreciendo una breve descripción de lo que los usuarios encontrarán en ella.<br>
`<meta name="description" content="NestHub is a web application focused on publishing and renting centers for events"/>`

**Palabras clave**
<br>En esta meta etiqueta se incluyen las palabras clave relacionadas con el tema o contenido de la página web.<br>
`<meta name="keywords" content="publish, rent, management, application, announcements, centers"/>`

**Autor y derechos de autor**
<br>Se utiliza para registrar la información del autor de la página web y los derechos de autor.<br>
`<meta name="author" content="NestHub"/>`
`<meta name="copyright" content="Copyright NestHub team"/>`

#### 3.1.2.4. Searching Systems

<td>El motor de búsqueda es esencial para que los usuarios encuentren rápidamente información específica.</td>
<br><br>

**Características principales**

- _Búsqueda por ubicación:_ <td>Los usuarios podrán buscar centros para eventos cercanos a su ubicación actual o especificar una ubicación deseada.</td>
- _Búsqueda por características:_ <td>Los usuarios podrán buscar centros que cumplan con características específicas, como piscina, parrilla, que acepten mascotas o que cuenten con vigilancia.</td>
- _Filtros avanzados:_ <td>Se ofrecerán filtros para refinar la búsqueda, como calificaciones, precios y disponibilidad.</td>
- _Resultados relevantes:_ <td>El sistema de búsqueda presentará resultados relevantes y los organizará según la ubicación y otros criterios.</td>

#### 3.1.2.5. Navigation Systems

El Sistema de Navegación es la estructura que facilita a los usuarios moverse de manera eficiente entre las diferentes secciones y páginas de la aplicación.<br><br>

**Estructura de navegación:** El Sistema de Navegación incluirá las siguientes secciones principales en la barra de navegación:

- Lugares
- Publica
- Variedad
- Premium
- Iniciar sesión
- Registrarse

Después, la vista del usuario se dirigirá a la opción "Alquilar centro" y, finalmente, accederá a un panel con ciudades destacadas.

### 3.1.3. Landing Page UI Design

#### 3.1.3.1. Landing Page Wireframe

<img src="assets/mock-ups/Landing Page Wireframe (Mobile Web Browser).png">

### 3.1.4. Mobile Applications UX/UI Design

#### 3.1.4.1. Mobile Applications Wireframes

<img src="assets/wireframes/Frame 8Mobile App wireframes.png">

#### 3.1.4.2. Mobile Applications Wireflow Diagram

**User goal: Registro de usuario en la aplicación.**
<img src="assets/wireflow/inicio sesion.png">

**User goal: Búsqueda y filtrado de espacios.**
<img src="assets/wireflow/buscado.png">

**User goal: Calificaciones y comentarios sobre espacios.**
<img src="assets/wireflow/calificaciones.png">

**User goal: Comunicación directa con propietarios.**
<img src="assets/wireflow/comunicacion.png">

**User goal: Registro de espacio sencillo.**
<img src="assets/wireflow/registro.png">

#### 3.1.4.3. Mobile Applications Mock-ups

<img src="assets/mock-ups/Mobile app - Mock upsMobile App wireframes.png">

<img src="assets/mock-ups/Sign up.png">
<img src="assets/mock-ups/Sign in.png">
<img src="assets/mock-ups/Home.png">
<img src="assets/mock-ups/House display.png">
<img src="assets/mock-ups/Confirmation and payment.png">
<img src="assets/mock-ups/Messages.png">
<img src="assets/mock-ups/Notification.png">
<img src="assets/mock-ups/Perfil.png">
<img src="assets/mock-ups/Publish step1.png">
<img src="assets/mock-ups/Publish- step1 describe.png">
<img src="assets/mock-ups/Publish- step1.png">
<img src="assets/mock-ups/Publish- step1-1.png">
<img src="assets/mock-ups/Publish step2.png">
<img src="assets/mock-ups/Publish- step2-2.png">
<img src="assets/mock-ups/Publish- step2.png">
<img src="assets/mock-ups/Publish- step2-1.png">
<img src="assets/mock-ups/Publish step3.png">
<img src="assets/mock-ups/Publish- step3-1.png">
<img src="assets/mock-ups/Publish- step3.png">

#### 3.1.4.4. Mobile Applications User Flow Diagram

<img src="assets/userflow/userflow 3.png">

Explicación del flujo: El proceso comienza con el usuario accediendo a la aplicación desplegada. Luego, se le presentará un formulario en pantalla donde deberá ingresar su correo electrónico y contraseña para iniciar sesión. Si los datos son válidos, el sistema lo redirigirá a la página principal del aplicativo. En caso contrario, permanecerá en la página de inicio de sesión y se le pedirá que vuelva a ingresar sus credenciales.

<img src="assets/userflow/userflow 4.png">

**User goal: Visualización de perfil**

Explicación del flujo: En la aplicación, siempre se mostrará una barra de navegación en la parte inferior. Cuando el usuario haga clic en "perfil", que están ubicados en el extremo inferior derecho de la barra de navegación, podrá acceder a su perfil de usuario y operaciones que puede hacer.

<img src="assets/userflow/userflow 2.png">

<img src="assets/userflow/userflow1.png">

#### 3.1.4.5. Mobile Applications Prototyping

<img src="assets/prototype.png">

## 3.2. Architecture Overview

### 3.2.1. Domain-Driven Software Architecture

A continuación se visualizarán los diagramas C4.

#### 3.2.1.1. Software Architecture Context Level Diagram

Se puede visualizar el diagrama de contexto que representa un panorama general de la comunicación entre nuestros segmentos objetivo y la aplicación.

![contextDiagram](assets/c4/context_diagram.png)

#### 3.2.1.2. Software Architecture Container Level Diagram

En este diagrama se puede apreciar el funcionamiento que tendrá la aplicación y las relaciones con los bounded context correspondientes, se busca organizarlos de tal forma que no generen dependencias fuertes que perjudiquen migraciones a future.

![containerDiagram](assets/c4/containerDiagramA.png)

#### 3.2.1.3. Software Architecture Components Diagram

En este diagrama se presenta de forma detallada las conexiones entre controllers, services y repositories de las entidades que contiene el bounded context.

<p style="text-align: center;"><strong>User Context</strong></p>

![componentDiagram](assets/c4/component-1.png)

<p style="text-align: center;"><strong>Subscription Context</strong></p>

![componentDiagram](assets/c4/component-2.png)

<p style="text-align: center;"><strong>Space Context</strong></p>

![componentDiagram](assets/c4/component-3.png)

<p style="text-align: center;"><strong>CreateReservation Context</strong></p>

![componentDiagram](assets/c4/component-4.png)

<p style="text-align: center;"><strong>Reservations Context</strong></p>

![componentDiagram](assets/c4/component-5.png)

### 3.2.2. Software Object-Oriented Design

#### 3.2.2.1. Class Diagrams

![diagramClass](assets/c4/AlquilaFacilDiagram.png)

#### 3.2.2.2. Class Dictionary

<table style="text-aling:center">
    <thead>
        <tr>
            <th>Clase</th>
            <th>Descripción</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td> 
            <img src="assets/c4/userC.png" alt="userClass" height="200" width="200">
            </td>
            <td>Es la clase padre de las clases Organizer y Owner, es la encargada de almacenas los datos del usuario</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/ownerC.png" alt ="ownerC" height="120">
            </td>
            <td>La clase Owner hereda de la clase User. Representa a los propietarios de los espacios que pueden ser alquilados para eventos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/organizerC.png" alt ="organizerC" height="120">
            </td>
            <td>La clase Organizer hereda de la clase User. Representa a los organizadores de eventos que buscan y reservan espacios para sus eventos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/reservationC.png" alt ="reservationC" height="200" width="200">
            </td>
            <td>Gestiona las reservas realizadas por organizadores para espacios de eventos específicos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/eventSpaceC.png" alt ="eventSpaceC" height="200" width="200">
            </td>
            <td>Representa los espacios físicos disponibles para alquiler. Proporciona información detallada sobre el espacio, como ubicación, capacidad y características.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/paymentsC.png" alt ="paymentsC" height="200" width="200">
            </td>
            <td>Representa los pagos asociados a las reservas de espacios de evento. Registra información sobre el monto, la fecha y el estado de los pagos realizados.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/c4/subscriptionC.png" alt ="subscriptionC" height="200" width="200">
            </td>
            <td>Representa las suscripciones de los propietarios a planes de servicio que ofrecen beneficios adicionales.</td>
        </tr>
    </body>
</table>

#### 3.2.2.3. Database Design

1. Users

Esta entidad representa a los usuarios de la plataforma, que pueden ser organizadores de eventos (quienes buscan alquilar un espacio para realizar eventos) o propietarios de locales (quienes ofrecen sus espacios en alquiler). La tabla almacena información esencial de los usuarios, como sus credenciales y datos de contacto. Es clave para administrar tanto a los usuarios que alquilan locales como a aquellos que los ofrecen.

3. Profiles

Descripción: Contiene la información de perfil de cada usuario, incluyendo datos como su biografía, imagen de perfil y ubicación. Los organizadores de eventos pueden usar sus perfiles para mostrar su experiencia y los tipos de eventos que organizan, mientras que los propietarios pueden incluir detalles sobre sus propiedades y su trayectoria ofreciendo locales.

4. Locals

Representa los locales o propiedades que los propietarios pueden listar en la plataforma para ser alquilados por los organizadores de eventos. Estos locales pueden ser espacios como salones de eventos, casas de campo, auditorios, entre otros. La entidad permite a los propietarios describir sus propiedades, indicando el tamaño, ubicación, capacidad, comodidades y precios, para que los organizadores de eventos encuentren el lugar adecuado para sus necesidades.

6. Local_Categories

Clasifica los locales en diferentes categorías según su tipo o función. Las categorías pueden incluir opciones como salón de eventos, casa de campo, auditorio, jardín para eventos, entre otras. Esto facilita a los organizadores de eventos buscar y filtrar espacios en función del tipo de evento que desean organizar.

8. Invoices

Descripción: Registra las transacciones financieras que ocurren en la plataforma, tanto para los propietarios que alquilan sus locales como para los organizadores de eventos que pagan por el uso de los espacios. Cada vez que se realiza una transacción, se genera una factura que detalla el monto y el estado del pago.

10. Plans

Representa los diferentes planes de suscripción que la plataforma puede ofrecer, tanto a los propietarios de locales como a los organizadores de eventos. Los propietarios podrían suscribirse a planes que les permitan destacar sus locales o acceder a servicios adicionales, mientras que los organizadores pueden obtener beneficios como descuentos o acceso prioritario a locales mediante la suscripción a estos planes.

12. Subscriptions

Almacena la información de las suscripciones de los propietarios y organizadores de eventos a los distintos planes disponibles. Lleva el control de las fechas de inicio y finalización de la suscripción, el estado (activa, expirada) y los beneficios asociados a cada plan.

#### 3.2.2.4. Database Diagram

![dataBaseDiagram](assets/c4/db-alquilaf.jpg)

# Capítulo IV: Backend Product Implementation & Validation

## 4.1. Software Configuration Management

### 4.1.1. Software Development Environment Configuration

A continuación se presenta un resumen de las herramientas utilizadas en el proyecto, que permiten al equipo avanzar en cada aspecto del trabajo:

- Rider: IDE que utilizamos para el desarrollo backend en .NET y C#.
- GitHub: Repositorio en la nube para colaboración en proyectos.
- Swagger: Herramienta para documentar y probar las APIs desarrolladas en el backend.
- MySQL Workbench: Herramienta gráfica para administrar la base de datos MySQL, utilizada para modelar, consultar y gestionar la base de datos del backend.

### 4.1.2. Source Code Management

Trabajamos con dos ramas principales:

- Main: La rama principal utilizada para publicar nuestras versiones oficiales.
- Default: Rama por defecto que utilizamos para consolidar los desarrollos generales del proyecto.
- feature/Locals: Rama dedicada al desarrollo de las funcionalidades relacionadas con la gestión de locales.
- feature/contacts: Rama enfocada en la implementación de las funcionalidades relacionadas con la gestión de contactos.
- feature/profiles: Rama destinada al desarrollo e integración de las funcionalidades de perfiles de usuarios.

### 4.1.3. Source Code Style Guide & Conventions

Para realizar nuestro proyecto, hemos utilizado:

- Tecnologías: Utilizamos lenguajes y tecnologías como C# y ASP.NET Core para el desarrollo del backend de nuestra aplicación.
- Herramientas: Optamos por herramientas recomendadas y ampliamente utilizadas en el desarrollo backend, como Rider para el entorno de desarrollo integrado (IDE) y Workbench para la gestión de bases de datos.

### 4.1.4. Software Deployment Configuration

A continuación, explicamos el proceso de implementación del backend en GitHub:

- Primero, creamos un repositorio remoto en GitHub para alojar el código del backend.
- Inicializamos el repositorio localmente en nuestro entorno de desarrollo con el comando git init.
- Luego, conectamos el repositorio local al repositorio remoto de GitHub utilizando el comando git remote add origin [URL].
- Subimos los archivos y cambios al repositorio remoto con git push -u origin main (o la rama en la que estemos trabajando).
- Configuramos las herramientas de integración continua y cualquier ajuste necesario para asegurar el despliegue automático y el correcto funcionamiento del backend.
- Finalmente, verificamos que el despliegue del backend se haya realizado exitosamente y que la aplicación funcione según lo esperado.

## 4.2. Software Development & Implementation

### 4.2.1. Sprint 1

#### 4.2.1.1. Sprint Planning 1

<table style="text-align: center;">
    <tbody>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 1</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td colspan="1">Date</td>
            <td colspan="1">05/09/2024</td>
        </tr>
        <tr>
            <td colspan="1">Location</td>
            <td colspan="1">Microsoft Teams (Reuniones Virtuales)</td>
        </tr>
        <tr>
            <td colspan="1">Prepared By</td>
            <td colspan="1">Brenda Gamio</td>
        </tr>
        <tr>
            <td colspan="1">Attendees (to planning meeting)</td>
            <td colspan="1">- Brenda Gamio<br>
                - Angel Cancho<br>
                - Miguel Carpio<br></td>
        </tr>
        <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 1 Goal</td>
            <td colspan="1">Avanzar en la implementación de los endpoints del backend.</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 1 Velocity</td>
            <td colspan="1">No se puede calcular ya que la implementación de los endpoints del backend no tiene backlog items o story points.</td>
        </tr>
        <tr>
            <td colspan="1">Sum of Story Points</td>
            <td colspan="1">No se puede calcular ya que la implementación de los endpoints del backend no tiene story points.</td>
        </tr>
        <tr>
            <td colspan="1">Backend Progress</td>
            <td colspan="1">Avance del 30% en la implementación de los endpoints del backend.</td>
        </tr>
    </tbody>
</table>

#### 4.2.1.2. Sprint Backlog 1

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 3</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td>EP10/US01</td>
			<td>Acceder a EndPoints</td>
			<td>Como desarrollador, quiero tener acceso a los endpoints de la aplicación para poder interactuar con ella.</td>
			<td>6</td>
			<td>All team members</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>EP10/US02</td>
			<td>Registrar Subscripciones</td>
			<td>Como developer, quiero contar con un endpoint para poder registrar las subscripciones que tienen los usuarios.</td>
			<td>2</td>
			<td>Brenda Gamio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US04</td>
			<td>Registrar Perfiles</td>
			<td>Como developer, quiero contar con un endpoint para poder registrar a los perfiles.</td>
			<td>2</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US05</td>
			<td>Registrar Contactos</td>
			<td>Como developer, quiero contar con un endpoint para poder registrar los contactos.</td>
			<td>2</td>
			<td>Miguel Carpio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US07</td>
			<td>Creación de persistencia de la entidad Subscription</td>
			<td>Como developer, quiero realizar la persistencia de la información para la entidad Subscription.</td>
			<td>2</td>
			<td>Brenda Gamio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US08</td>
			<td>Creación de persistencia de la entidad Perfil</td>
			<td>Como developer, quiero implementar la persistencia de la información de la entidad Perfil para asegurar que los datos de los perfiles se almacenen de manera segura y estén disponibles cuando sea necesario.</td>
			<td>2</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US09</td>
			<td>Creación de persistencia de la entidad Contacto</td>
			<td>Como developer quiero hacer persistir la información de la entidad Contacto para tener registrado.</td>
			<td>2</td>
			<td>Miguel Carpio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US11</td>
			<td>Creación de resource de la entidad Subscription</td>
			<td>Como developer quiero devolver un resource de la información de la entidad Subscription para realizar consultas.</td>
			<td>2</td>
			<td>Brenda Gamio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US12</td>
			<td>Creación de resource de la entidad Perfil</td>
			<td>Como developer quiero devolver un resource de la información de la entidad Perfil para realizar consultas.</td>
			<td>2</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US13</td>
			<td>Creación de resource de la entidad Contacto</td>
			<td>Como developer quiero devolver un resource de la información de la entidad Contacto para realizar consultas.</td>
			<td>2</td>
			<td>Miguel Carpio</td>
			<td>Done</td>
		</tr>        
    </tbody>
</table>

#### 4.2.1.3. Development Evidence for Sprint Review

| Repository | Branch | Commit ID                                | Commit Message                        | Commit Message Body             | Commited on (Date) |
| ---------- | ------ | ---------------------------------------- | ------------------------------------- | ------------------------------- | ------------------ |
| Backend    | main   | 5d3eede7981780e5bc96fa4067df4ff3f1472a85 | chore: initial commit                 | Initial setup                   | 14/09/2024         |
| Backend    | main   | 2200e6526ebdde4d400fcf5bab5720882cdb4596 | chore: added shared folder            | Added shared folder             | 14/09/2024         |
| Backend    | main   | 7f30747276c3a935a9564e79489b82ae0ce7d645 | feat: add contacts service            | Added contacts service          | 14/09/2024         |
| Backend    | main   | 798e808dfbc0c51da7f8a724727a1475ba356c8f | feat: added bounded context for local | Added bounded context for local | 14/09/2024         |
| Backend    | main   | c99c0683833aa5d576b9d939610afca73f7c96c4 | feat: added profiles bounded context  | Added profiles bounded context  | 14/09/2024         |

#### 4.2.1.4. Testing Suite Evidence for Sprint Review

Esta sección ha sido omitida porque aún no contamos con el conocimiento necesario para llevar a cabo pruebas automatizadas, las cuales están previstas para el próximo sprint.

#### 4.2.1.5. Execution Evidence for Sprint Review

![bd](assets/bd.png)
![swagger](assets/swagger-contact.png)
![swagger](assets/swagger-local.png)
![swagger](assets/swgger-profile.png)

#### 4.2.1.6. Services Documentation Evidence for Sprint Review

| Nombre del Endpoint       | Acciones Implementadas | Sintaxis de Llamada                                      | Especificación de Parámetros                         | Ejemplo de Llamada                                                                                                                                                                                                                                                                           | Explicación del Response                                                                                                                  |
| ------------------------- | ---------------------- | -------------------------------------------------------- | ---------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| profiles-api.service.json | GET                    | (Not used)                                               | Ya que es un GET, los parámetros que se piden son id | `fetch('src/app/profiles/services/profiles-api.service.json')`<br>`.then(response => response.json())`<br>`.then(data => {`<br>`this.profiles = data;`<br>`});`                                                                                                                              | En este caso, se está devolviendo el valor de todos los objetos "profiles" alojados en el json con el nombre 'profiles-api.service.json'. |
| contact-api.service.json  | GET                    | `axios.get("src/app/services/contact-api.service.json")` | Ya que es un GET, los parámetros que se piden son id | `fetchContacts() {`<br>`axios.get("src/app/services/contact-api.service.json")`<br>`.then(response => {`<br>`console.log(response.data);`<br>`this.contacts = response.data.contacts;`<br>`})`<br>`.catch(error => {`<br>`console.error('Error fetching contacts:', error);`<br>`});`<br>`}` | En este caso, se está devolviendo el valor de todos los objetos "contacts" alojados en el json con el nombre 'contact-api.service.json'.  |
| local-api.service.json    | GET                    | `fetch('src/app/local/services/local-api.service.json')` | Ya que es un GET, los parámetros que se piden son id | `fetch('src/app/local/services/local-api.service.json')`<br>`.then(response => response.json())`<br>`.then(data => {`<br>`this.localData = data;`<br>`});`                                                                                                                                   | En este caso, se está devolviendo el valor de todos los objetos "local" alojados en el json con el nombre 'local-api.service.json'.       |

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

Hasta la fecha, aún no hemos realizado el despliegue de la aplicación. La evidencia de despliegue se proporcionará en la próxima entrega, correspondiente a la finalización del próximo sprint.

#### 4.2.1.8. Team Collaboration Insights during Sprint

![swagger](assets/insight-1.png)
![swagger](assets/insight-2.png)

### 4.2.2. Sprint 2

#### 4.2.2.1. Sprint Planning 2

<table style="text-align: center;">
    <tbody>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 2</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td colspan="1">Date</td>
            <td colspan="1">19/09/2024</td>
        </tr>
        <tr>
            <td colspan="1">Location</td>
            <td colspan="1">Discord (Reuniones Virtuales)</td>
        </tr>
        <tr>
            <td colspan="1">Prepared By</td>
            <td colspan="1">Brenda Gamio</td>
        </tr>
        <tr>
            <td colspan="1">Attendees (to planning meeting)</td>
            <td colspan="1">- Brenda Gamio<br>
                - Angel Cancho<br>
                - Miguel Carpio<br></td>
        </tr>
        <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 2 Goal</td>
            <td colspan="1">Terminar el backend y comenzar el desarrollo movile de nuestra app.</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 2 Velocity</td>
            <td colspan="1">6</td>
        </tr>
        <tr>
            <td colspan="1">Sum of Story Points</td>
            <td colspan="1">19</td>
        </tr>
        <tr>
            <td colspan="1">Movile app development Progress</td>
            <td colspan="1">Avance del 30% en el desarollo de la app móvil.</td>
        </tr>
    </tbody>
</table>

#### 4.2.2.2. Sprint Backlog 2

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 2</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td>US01</td>
			<td>Visualización de Información Clave</td>
			<td>Como visitante de la landing page, quiero ver una presentación clara de los beneficios de NestHub, para entender rápidamente cómo la plataforma me puede ayudar a alquilar o encontrar espacios para eventos.</td>
			<td>3</td>
			<td>Brenda Gamio</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>US02</td>
			<td>Explorar Espacios Populares</td>
			<td>Como usuario, quiero ver los espacios más populares y mejor calificados destacados en la landing page, para conocer las opciones más recomendadas sin tener que buscarlas.</td>
			<td>3</td>
			<td>Brenda Gamio</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>US03</td>
			<td>Acceso Rápido a Registro e Inicio de Sesión</td>
			<td>Como nuevo usuario, quiero encontrar botones de registro e inicio de sesión fácilmente accesibles en la landing page, para empezar a usar la plataforma rápidamente.</td>
			<td>2</td>
			<td>Miguel Carpio</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>US08</td>
			<td>Reservas de Espacios</td>
			<td>Como organizador de eventos, quiero poder reservar un espacio para mi evento en NestHub para garantizar su disponibilidad en la fecha deseada.</td>
			<td>5</td>
			<td>Brenda Gamio</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>US09</td>
			<td>Calificaciones y Comentarios sobre Espacios</td>
			<td>Como organizador de eventos, quiero poder ver las calificaciones y comentarios de otros usuarios sobre los espacios en NestHub para tomar una decisión informada al seleccionar un espacio para mi evento.</td>
			<td>3</td>
			<td>Brenda Gamio</td>
			<td>In-Progress</td>
		</tr>
		<tr>
			<td>EP10/US14</td>
			<td>Creación de persistencia de la entidad Payment</td>
			<td>Como developer, quiero implementar la persistencia de la información de la entidad Payment para asegurar que los datos de los pagos se almacenen de manera segura y estén disponibles cuando sea necesario.</td>
			<td>2</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US15</td>
			<td>Creación de persistencia de la entidad Reservations</td>
			<td>Como developer quiero hacer persistir la información de la entidad Reservation para tener registrado.</td>
			<td>2</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>EP10/US16</td>
			<td>Creación de resource de la entidad Reviews</td>
			<td>Como developer quiero devolver un resource de la información de la entidad Reviews para realizar consultas.</td>
			<td>2</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>    
    </tbody>
</table>

#### 4.2.2.3. Development Evidence for Sprint Review

| Repository   | Branch | Commit ID                                | Commit Message        | Commit Message Body | Commited on (Date) |
| ------------ | ------ | ---------------------------------------- | --------------------- | ------------------- | ------------------ |
| NestHub      | master | 755dbc9e22aa04dc07a587f1da1c934083f4b8d2 | chore: initial commit | -                   | 27/09/2024         |
| NestHub      | master | c27e75cab5150eed99ad2b80f511eea6f4b96d60 | feat: Add auth login  | -                   | 28/09/2024         |
| NestHub      | master | 7ef9e3459929f2ce6b8f248a8b8079e40ef1567b | feat: add screens     | -                   | 28/09/2024         |
| Landing-Page | main   | 2d0bba33a51687c6a9258711e869f1201fc5fe58 | Initial commit        | -                   | 28/09/2024         |
| Landing-Page | main   | 3aaae9e79383104ed724ac2c08ddb2da94e68da6 | feat: add landing     | -                   | 28/09/2024         |

#### 4.2.2.4. Testing Suite Evidence for Sprint Review

<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Landing-Page</td>
    <td>main</td>
    <td>Brenda Gamio</td>
    <td>despliegue de la landing page</td>
    <td>28/09/2024</td>
    <td>https://nesthublandingpage.web.app/</td>
  </tr>
</table>

#### 4.2.2.5. Execution Evidence for Sprint Review

![landing-page1](assets/landing1.png)
![landing-page2](assets/landing2.png)
![landing-page3](assets/landing3.png)
![landing-page4](assets/landing4.png)

#### 4.2.2.6. Services Documentation Evidence for Sprint Review

Durante el segundo sprint, se ha creado el landing page y se ha finalizado el desarollo del backend, sin que se haya hecho uso de web services para su funcionamiento.

#### 4.2.2.7. Software Deployment Evidence for Sprint Review

Para el presente sprint, se ha desarrollado el landing page. Para el desarrollo del landing page se ha utilizado las siguientes herramientas:

- Git: Herramienta de gestión de versiones que facilitó la colaboración en equipo durante la creación del landing page. Git es un sistema que permite a los programadores registrar y seguir los cambios realizados en el código fuente de un proyecto. Con Git, podemos crear ramas para trabajar en diferentes partes del código sin interferir con el trabajo de los demás, integrar los cambios cuando estén listos y revertirlos si es necesario.

- GitFlow: Método de trabajo que contribuyó al seguimiento del progreso individual de cada miembro del equipo en la creación del landing page. GitFlow es un modelo de flujo de trabajo con ramificaciones en Git que establece una estructura estándar para organizar las diferentes versiones y características del código. Con GitFlow, podemos mantener una rama principal (master o main) con el código más estable y seguro, una rama de desarrollo (develop) con el código en proceso, y varias ramas auxiliares (feature, release, hotfix) que se utilizan para desarrollar nuevas funcionalidades, preparar lanzamientos y solucionar errores urgentes, respectivamente.

- GitHub: Plataforma que facilitó la colaboración en equipo para almacenar las versiones de nuestro proyecto. GitHub es un servicio web que utiliza Git para alojar repositorios remotos y fomentar la colaboración entre programadores. Con GitHub, podemos cargar nuestro código en la nube, compartirlo con otros usuarios, recibir comentarios y sugerencias, hacer seguimiento de tareas y problemas, y acceder a una amplia gama de proyectos de código abierto.

- Firebase: Servicio que nos permitió publicar nuestro landing page directamente desde nuestro repositorio de GitHub.

https://nesthublandingpage.web.app/

#### 4.2.2.8. Team Collaboration Insights during Sprint

![swagger](assets/insight-1.png)
![swagger](assets/insight-2.png)

--

### 4.2.3. Sprint 3

#### 4.2.3.1. Sprint Planning 3

<table style="text-align: center;">
    <tbody>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 3</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td colspan="1">Date</td>
            <td colspan="1">20/10/2024</td>
        </tr>
        <tr>
            <td colspan="1">Location</td>
            <td colspan="1">Discord (Reuniones Virtuales)</td>
        </tr>
        <tr>
            <td colspan="1">Prepared By</td>
            <td colspan="1">Brenda Gamio</td>
        </tr>
        <tr>
            <td colspan="1">Attendees (to planning meeting)</td>
            <td colspan="1">- Brenda Gamio<br>
                - Angel Cancho<br>
                - Miguel Carpio<br></td>
        </tr>
        <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 3 Goal</td>
            <td colspan="1">Deployar el backend y avanzar el desarrollo movile de nuestra app.</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 3 Velocity</td>
            <td colspan="1">5</td>
        </tr>
        <tr>
            <td colspan="1">Sum of Story Points</td>
            <td colspan="1">11</td>
        </tr>
        <tr>
            <td colspan="1">Movile app development Progress</td>
            <td colspan="1">Deployar el backend.</td>
        </tr>
    </tbody>
</table>

#### 4.2.3.2. Sprint Backlog 3

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 3</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td>US04</td>
			<td>Visualización de Variedad de Locales</td>
			<td>Como usuario que busca alquilar un espacio para eventos, quiero ver una sección destacada en la landing page que muestre la variedad de locales disponibles, para tener una idea clara de las diferentes opciones que ofrece la plataforma y encontrar el tipo de espacio que mejor se adapte a mis necesidades.</td>
			<td>3</td>
			<td>Angel Cancho</td>
			<td>In-Process</td>
		</tr>
		<tr>
			<td>US05</td>
			<td>Registro de Propietario</td>
			<td>Como propietario de un espacio para eventos, quiero poder registrarme fácilmente en NestHub para ofrecer mi espacio en alquiler y llegar a más clientes potenciales.</td>
			<td>3</td>
			<td>Brenda Gamio</td>
			<td>In-Process</td>
		</tr>
        <tr>
			<td>US06</td>
			<td>Búsqueda y Filtrado de Espacios</td>
			<td>Como organizador de eventos, quiero poder buscar y filtrar fácilmente espacios disponibles en NestHub para encontrar el lugar perfecto para mi evento, según mis criterios específicos.</td>
			<td>3</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>US07</td>
			<td>Reservas de Espacios</td>
			<td>Como organizador de eventos, quiero poder reservar un espacio para mi evento en NestHub para garantizar su disponibilidad en la fecha deseada.</td>
			<td>2</td>
			<td>Miguel Carpio</td>
			<td>In-Process</td>
		</tr>  
    </tbody>
</table>

#### 4.2.3.3. Development Evidence for Sprint Review

| Repository | Branch | Commit ID                                | Commit Message                  | Commit Message Body | Commited on (Date) |
| ---------- | ------ | ---------------------------------------- | ------------------------------- | ------------------- | ------------------ |
| NestHubApp | main   | dea17c403b7db350a2c39d64649995b52631addd | chore                           | -                   | 25/10/2024         |
| NestHubApp | main   | 4d0be2afa0c44a382b46329b88074991ade91bbd | feat: added publishing steps    | -                   | 25/10/2024         |
| NestHubApp | main   | 4d1b4b402584e62c81db02a36ea52a88d461905f | feat: added user profile screen | -                   | 25/10/2024         |
| NestHubApp | main   | 4c506ec6ffe22441ec75a942479433bad847f8d9 | feat: added messages screen     | -                   | 26/10/2024         |

#### 4.2.3.4. Testing Suite Evidence for Sprint Review

<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Backend</td>
    <td>main</td>
    <td>Miguel Carpio</td>
    <td>despliegue del backend</td>
    <td>26/10/2024</td>
    <td>https://nesthubplatform-0a5eeee622eb.herokuapp.com/</td>
  </tr>
</table>

#### 4.2.3.5. Execution Evidence for Sprint Review

![web-app](assets/evidences/1.jpg)
![web-app](assets/evidences/2.jpg)
![web-app](assets/evidences/3.jpg)
![web-app](assets/evidences/4.jpg)
![web-app](assets/evidences/5.jpg)
![web-app](assets/evidences/6.jpg)
![web-app](assets/evidences/7.jpg)
![web-app](assets/evidences/8.jpg)
![web-app](assets/evidences/9.jpg)
![web-app](assets/evidences/10.jpg)
![web-app](assets/evidences/11.jpg)
![web-app](assets/evidences/12.jpg)
![web-app](assets/evidences/13.jpg)
![web-app](assets/evidences/14.jpg)
![web-app](assets/evidences/15.jpg)
![web-app](assets/evidences/16.jpg)
![web-app](assets/evidences/17.jpg)
![web-app](assets/evidences/18.jpg)
![web-app](assets/evidences/19.jpg)
![web-app](assets/evidences/20.jpg)

#### 4.2.3.6. Services Documentation Evidence for Sprint Review

Durante el tercer sprint, se ha finalizado el desarollo del backend, utilizando heroku y aws para la base de datos.

#### 4.2.3.7. Software Deployment Evidence for Sprint Review

![backend-deploy](assets/evidences/HerokuOverview.png)
![backend-deploy](assets/evidences/HerokuAppSwagger.png)
https://nesthubplatform-0a5eeee622eb.herokuapp.com/

![db-deploy](assets/evidences/AwsDbDeploy.png)
![db-deploy](assets/evidences/AwsDbDeployConfig.png)

#### 4.2.3.8. Team Collaboration Insights during Sprint

![network](assets/sprint3-insight-1.png)
![network](assets/sprint3-insight-2.png)
![network](assets/sprint3-insight-3.png)

--

### 4.2.4. Sprint 4

#### 4.2.4.1. Sprint Planning 4

<table style="text-align: center;">
    <tbody>
        <tr>
            <td colspan="1">Sprint #</td>
            <td colspan="1">Sprint 4</td>
        </tr>
        <tr>
            <td colspan="2">Sprint Planning Background</td>
        </tr>
        <tr>
            <td colspan="1">Date</td>
            <td colspan="1">05/11/2024</td>
        </tr>
        <tr>
            <td colspan="1">Location</td>
            <td colspan="1">Discord (Reuniones Virtuales)</td>
        </tr>
        <tr>
            <td colspan="1">Prepared By</td>
            <td colspan="1">Brenda Gamio</td>
        </tr>
        <tr>
            <td colspan="1">Attendees (to planning meeting)</td>
            <td colspan="1">- Brenda Gamio<br>
                - Angel Cancho<br>
                - Miguel Carpio<br></td>
        </tr>
        <tr>
            <td colspan="2">Sprint Goal & User Stories</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 4 Goal</td>
            <td colspan="1">Terminar detalles del aplicativo.</td>
        </tr>
        <tr>
            <td colspan="1">Sprint 4 Velocity</td>
            <td colspan="1">5</td>
        </tr>
        <tr>
            <td colspan="1">Sum of Story Points</td>
            <td colspan="1">15</td>
        </tr>
        <tr>
            <td colspan="1">Movile app development Progress</td>
            <td colspan="1">Terminar detalles del aplicativo.</td>
        </tr>
    </tbody>
</table>

#### 4.2.4.2. Sprint Backlog 4

<table>
	<tbody>
		<tr>
			<td>Sprint #</td>
			<td colspan="7">Sprint 4</td>
		</tr>
		<tr>
			<td colspan="2">User Story</td>
			<td colspan="6">Work - Item / Task</td>
		</tr>
		<tr>
			<td>Id</td>
			<td>Title</td>
			<td>Description</td>
			<td>Estimation (Hours)</td>
			<td>Assigned To</td>
			<td>Status (To-do / In-Process / To-Review / Done)</td>
		</tr>
		<tr>
			<td>US03</td>
			<td>Acceso Rápido a Registro e Inicio de Sesión</td>
			<td>Como nuevo usuario, quiero encontrar botones de registro e inicio de sesión fácilmente accesibles en la landing page, para empezar a usar la plataforma rápidamente.</td>
			<td>5</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>US05</td>
			<td>Registro de Propietario</td>
			<td>Como propietario de un espacio para eventos, quiero poder registrarme fácilmente en NestHub para ofrecer mi espacio en alquiler y llegar a más clientes potenciales.</td>
			<td>3</td>
			<td>Brenda Gamio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>US07</td>
			<td>Reservas de Espacios</td>
			<td>Como organizador de eventos, quiero poder reservar un espacio para mi evento en NestHub para garantizar su disponibilidad en la fecha deseada.</td>
			<td>2</td>
			<td>Miguel Carpio</td>
			<td>Done</td>
		</tr>
		<tr>
			<td>US08</td>
			<td>Calificaciones y Comentarios sobre Espacios</td>
			<td>Como organizador de eventos, quiero poder ver las calificaciones y comentarios de otros usuarios sobre los espacios en NestHub para tomar una decisión informada al seleccionar un espacio para mi evento.</td>
			<td>5</td>
			<td>Angel Cancho</td>
			<td>Done</td>
		</tr>   
    </tbody>
</table>

#### 4.2.4.3. Development Evidence for Sprint Review

| Repository | Branch | Commit ID                                | Commit Message                  | Commit Message Body | Commited on (Date) |
| ---------- | ------ | ---------------------------------------- | ------------------------------- | ------------------- | ------------------ |
| NestHubApp | main   | 2b150c13f837daac5471a40edccf57c4a8cf0117 | feat: updated favorite local             | -                   | 22/11/2024         |
| NestHubApp | main   | 4ae1e18c672fdaec0373ae6906630b95cdf862ef | feat: implement login screen with validation and user authentication | -                   | 21/11/2024         |
| NestHubApp | master   | 4d1b4b402584e62c81db02a36ea52a88d461905f | Add reservation page | -                   | 23/11/2024         |
| NestHubApp | master   | 1f06edbac302d6efd9c070ac32ebdb7d148fa346 | feat: added personal data settings     | -                   | 23/11/2024         |

#### 4.2.4.4. Testing Suite Evidence for Sprint Review

<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Backend</td>
    <td>main</td>
    <td>Miguel Carpio</td>
    <td>despliegue del backend</td>
    <td>26/10/2024</td>
    <td>https://nesthubplatform-0a5eeee622eb.herokuapp.com/</td>
  </tr>
</table>

#### 4.2.4.5. Execution Evidence for Sprint Review

![web-app](assets/evidences/1.jpg)
![web-app](assets/evidences/2.jpg)
![web-app](assets/sprint%204%20-%20evidences/fav1.png)
![web-app](assets/sprint%204%20-%20evidences/fav2.png)
![web-app](assets/sprint%204%20-%20evidences/info.png)
![web-app](assets/sprint%204%20-%20evidences/info2.png)
![web-app](assets/sprint%204%20-%20evidences/info3.png)
![web-app](assets/sprint%204%20-%20evidences/payments.png)
![web-app](assets/sprint%204%20-%20evidences/card-input1.png)
![web-app](assets/sprint%204%20-%20evidences/card-input2.png)
![web-app](assets/sprint%204%20-%20evidences/security1.png)
![web-app](assets/sprint%204%20-%20evidences/security2.png)
![web-app](assets/sprint%204%20-%20evidences/accessibility.png)
![web-app](assets/sprint%204%20-%20evidences/shared%20data%20settings.png)
![web-app](assets/sprint%204%20-%20evidences/shared%20data.png)


#### 4.2.4.6. Services Documentation Evidence for Sprint Review

Durante el cuarto sprint, se ha realizado el desarollo del aplicativo móvil, utilizando la api y nuestra base de datos.

#### 4.2.4.7. Software Deployment Evidence for Sprint Review

![backend-deploy](assets/evidences/HerokuOverview.png)
![backend-deploy](assets/evidences/HerokuAppSwagger.png)
https://nesthubplatform-0a5eeee622eb.herokuapp.com/

![db-deploy](assets/evidences/AwsDbDeploy.png)
![db-deploy](assets/evidences/AwsDbDeployConfig.png)

#### 4.2.4.8. Team Collaboration Insights during Sprint

![network](assets/sprint4-insight-1.png)
![network](assets/sprint4-insight-2.png)
![network](assets/sprint4-insight-3.png)

## 4.3 Validation Interviews

### 4.3.1 Registro de preguntas

1. **¿Cuál fue tu primera impresión al abrir la aplicación o visitar la página de destino?**
2. **¿Pudiste entender rápidamente el propósito de la app o la información ofrecida en la landing page?**
3. **¿Cómo describirías tu experiencia al navegar por la app?**
4. **¿Hubo algo que te resultó confuso o poco claro? ¿Qué mejorarías para hacerlo más intuitivo?**
5. **¿Qué función o sección te pareció más útil o destacable? ¿Por qué?**
6. **¿Pudiste completar las acciones que esperabas hacer de manera fácil?**
7. **¿Te pareció que el diseño visual es atractivo y fácil de entender? ¿Qué cambios harías?**
8. **¿Notaste algún error o problema mientras usabas la app o navegabas por la página de destino?**
9. **¿Sientes que hay algo que falta o alguna característica que sería útil añadir?**
10. **En una escala del 1 al 10, ¿cuánto recomendarías esta app o página de destino a un amigo? ¿Qué mejorarías para que esa puntuación fuera más alta?**

### 4.3.2 Registro de entrevistas

**Entrevista 1:**

Nombre: Miguel ángel

Apellidos: Alvizuri Yucra

Edad: 20

Lugar de residencia: Chorrillos

Entrevistador: Miguel Carpio

Evidencia de la entrevista:

![entrevista 1](assets/evidences/ValidationInterview_MiguelC.png)

[Link de entrevisa](https://youtu.be/XTL40Z4jQNg)

**Entrevista 2:**

Nombre: Andrés Julián

Apellidos: Collazos Castro

Edad: 19

Lugar de residencia: La Perla

Entrevistador: Brenda Gamio

Evidencia de la entrevista:
![entrevista 2](assets/validation-interiew1.png)
[Link de entrevisa](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201721995_upc_edu_pe/EZ_cpKrgumtCo8VMVXQkjkgBIIcBZKf0ebap3ERUnCyygA?e=pOfhgJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Entrevista 3:**

Nombre: Bryan Alexander

Apellidos: Navarro Remon

Edad: 23

Lugar de residencia: Breña

Entrevistador: Angel Cancho

Evidencia de la entrevista:

![entrevista 3](assets/evidences/interview.png)

[Link de entrevisa](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201721995_upc_edu_pe/EYbgfzhhBTxCrRedG8leDswBY-lB-pKxIm2KRXXNnXtNFg?e=xh6HOq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

### 4.3.3 Evaluaciones según heurísticas

**Tareas a evaluar**<br>
1.	Mobile Application<br>
- Inicio de sesión de usuario existente<br>
- Acciones de retroceso dentro de la aplicación<br>
- Opciones de cancelar o salir del registro de espcaios<br>
- Elementos de la interfaz de usuario consistentes<br>
- Pestañas de navegación dentro de la aplicación<br>
- Botones interactivo y de uso intuitivo<br>
- Búsqueda por filtros<br>
- Navegación y orientación dentro de la aplicación<br>

**No están incluidas en esta versión de la evaluación las siguientes tareas**<br>
- Otro inicio de sesión aparte desde registrarse<br>
- Política de privacidad y condiciones de uso<br><br>

**Escala de severidad:**

| Nivel | Descripción |
|-------|-------------|
| 1     | Problema superficial: puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo para la siguiente entrega. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| 4     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
<br>

**Mobile application**
<br>
Tabla resumen:

| # | Problema | Escala de severidad | Heurística/Principio violada |
|---|----------|---------------------|------------------------------|
| 1 | Funcionalidades indisponibles relacionados a la modificación o personalización de perfil, además de eliminar cuenta de usuario. | 3 | Usability - Flexibilidad y eficiencia de uso / Usability – Prevenir errores |
| 2 | La página de Mensajes no muestra funcionalidad para poder contactar al propietario de un establecimiento. | 4 | Usability - Visibilidad del estado del sistema |
| 3 | Incapacidad para modificar o eliminar la información de los espacios previamente registrados. | 4 | Usability-Prevención de errores |

**PROBLEMA #01**: Funcionalidades indisponibles relacionados a la modificación o personalización de perfil, además de eliminar cuenta de usuario.<br>
Escala de severidad: 03<br>
Principio violdado: <br>
Usability - Flexibilidad y eficiencia de uso<br>
Usability - Prevenir errores<br>

Descripción del problema: El problema identificado se refiere a la falta de funcionalidades disponibles en la aplicación que permitan a los usuarios modificar o personalizar sus perfiles de usuario, así como la eliminación de sus cuentas. Esta carencia afecta la flexibilidad y la eficiencia de uso, ya que los usuarios no tienen la capacidad de gestionar sus perfiles de manera efectiva y no cuentan con opciones para corregir errores o deshacer acciones. Además, la aplicación no cumple con la heurística de "Flexibilidad y eficiencia de uso", ya que no proporciona estas funciones esenciales.<br>

<img src="assets/heuristics/perfil.png">
<br>
<br>

**Recomendación:** 
Para resolver el problema, se sugiere integrar de manera eficiente y accesible estas características clave en la interfaz. Además, es fundamental implementar salvaguardias de datos y confirmaciones al eliminar cuentas, con el objetivo de prevenir eliminaciones accidentales.<br>

**PROBLEMA #02**: La página de Mensajes no muestra funcionalidad para poder contactar al propietario de un establecimiento.<br>
Escala de severidad: 03<br>
Principio violado: Information Arquitecture <br><br>
Descripción del problema: El problema identificado radica en la imposibilidad de encontrar información precisa sobre las funcionalidades ofrecidas por cada plan de suscripción en el aplicativo. Esto se debe a una deficiente organización y presentación de la información, lo que dificulta que los usuarios accedan de manera efectiva a los detalles de cada plan y tomen decisiones informadas. La falta de claridad en la arquitectura de la información obstaculiza la navegación de los usuarios y puede resultar en una experiencia frustrante y confusa al intentar seleccionar el plan de suscripción adecuado.<br>

<img src="assets/heuristics/messages.png">
<br>
<br>

**Recomendación:** 
Asegurarse de que el formulario de contacto funcione correctamente y que los usuarios reciban retroalimentación después de enviar su mensaje, como un mensaje de confirmación o un redireccionamiento a una página de agradecimiento.<br>

**PROBLEMA #03**: Incapacidad para modificar o eliminar la información de los espacios previamente registrados.<br>
Escala de severidad: 04<br>
Principio violado: Usability – Prevención de errores <br><br>
Descripción del problema: El problema identificado se refiere a la incapacidad de modificar o eliminar la información de los espacios previamente registrados en la aplicación. Los usuarios no tienen la opción de corregir errores, actualizar datos obsoletos o eliminar registros no deseados, lo que puede resultar en información inexacta y desactualizada en la aplicación. Esta limitación afecta la usabilidad y la capacidad de los usuarios para mantener registros precisos y completos de los espacios ya registrados.<br>


**Recomendación:** 
Implementa una funcionalidad que permita a los usuarios editar la información de los espacios registrados. Esto les permitirá corregir errores, actualizar datos obsoletos y mantener registros precisos.<br>

## 4.3 Video About the team

![entrevista 3](assets/evidences/video_team.png)

[Link del video](https://upcedupe-my.sharepoint.com/personal/u201721995_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu201721995%5Fupc%5Fedu%5Fpe%2FDocuments%2F2024%2D11%2D10%2D20%2D59%2D14%5FgKqBdlHC%2Emkv&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6670c700%2D2cf9%2D4380%2D8060%2D1bf3dff1283e)

## [Conclusiones](#conclusiones)

## [bibliografía](#bibliografía)

Airbnb | Alojamientos para vacaciones, cabañas, casas en la playa y más. (s. f.). Airbnb. https://www.airbnb.com.pe/

Vrbo. (s. f.). https://www.vrbo.com/es-es/

Booking.com: The largest selection of hotels, homes, and vacation rentals. (s. f.). Booking.com. https://www.booking.com/

Instituto Nacional de Estadística e Informática - INEI. (s. f.). Plataforma del Estado Peruano. https://www.gob.pe/inei/

## [Anexos](#anexos)
