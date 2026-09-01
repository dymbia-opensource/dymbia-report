# Universidad Peruana de Ciencias Aplicadas
<p align="center">
  <img src="assets/img/upc-logo.png" alt="UPC Logo" width="200"/>
</p>

**FACULTAD DE INGENIERÍA**  
**CARRERA DE INGENIERÍA DE SOFTWARE**  

**CURSO:** 1ASI0729 - Desarrollo de Aplicaciones Open Source  
**SECCIÓN:** [CÓDIGO DE SECCIÓN]  
**PROFESOR:** [NOMBRE DEL DOCENTE]  
**CICLO ACADÉMICO:** 2026-20  

---

# INFORME DE TRABAJO FINAL
**STARTUP:** Dymbia  
**PRODUCTO:** Dymbia - SaaS de Agricultura de Precisión (Café y Tubérculos)  

### **RELACIÓN DE INTEGRANTES:**
| Código       | Apellidos y Nombres                             | Carrera |
|:-------------|:------------------------------------------------| :--- |
| U202315120   | Duarte Ruffner, Drago Derick                    | Ingeniería de Software |
| U20241E057   | Sanca Condori, Miguel                           | Ingeniería de Software |
| U202...      | [Apellidos, Nombres Integrante 3]               | Ingeniería de Software |
| U202...      | [Apellidos, Nombres Integrante 4]               | Ingeniería de Software |
| U202...      | [Apellidos, Nombres Integrante 5]               | Ingeniería de Software |

**FECHA DE ENTREGA:** [FECHA]  

---

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :--- | :--- | :--- | :--- |
| **1.0** | YYYY-MM-DD | [Nombre del Integrante] | Versión inicial del informe: Carátula, Capítulo I (Startup Profile, Problemática 5W/2H, Lean UX) y Capítulo II (Competidores). |
| **1.1** | YYYY-MM-DD | [Nombre del Integrante] | Incorporación de entrevistas de Needfinding, User Personas, User Task Matrix y Journey Maps en el Capítulo II. |
| **1.2** | YYYY-MM-DD | [Nombre del Integrante] | Redacción de User Stories en Gherkin (inglés), Impact Mapping y Product Backlog en Capítulo III. |
| **1.3** | YYYY-MM-DD | [Nombre del Integrante] | Adición de Style Guidelines, Arquitectura de Información y Wireframes/Mockups en Capítulo IV. |
| **1.4** | YYYY-MM-DD | [Nombre del Integrante] | Incorporación de EventStorming, Diagramas C4 (Context, Container, Component) y UML en Capítulo IV. |
| **1.5** | YYYY-MM-DD | [Nombre del Integrante] | Documentación del Sprint 1 (Capítulo V), evidencias de despliegue del Landing Page y revisión general para AV1. |

---

## Project Report Collaboration Insights

* **Organización de GitHub:** [https://github.com/[nombre-organizacion]](https://github.com/[nombre-organizacion])
* **Repositorio del Informe (`project-report`):** [https://github.com/[nombre-organizacion]/project-report](https://github.com/[nombre-organizacion]/project-report)

### Estrategia de Ramas en GitFlow
El equipo adoptó el flujo de trabajo **GitFlow** estricto:
* `main`: Rama de producción con versiones estables de cada entrega.
* `develop`: Rama de integración de trabajo colaborativo.
* `feature/...`: Ramas granulares por capítulo o sección creadas por cada miembro del equipo.
* `release-...`: Ramas preparatorias para hitos del curso (`release-av1`, `release-tb1`, `release-av2`, `release-tb2`).

*(Añadir aquí capturas de los gráficos de commits, clones y red de ramas de GitHub para cada entrega).*

---

## Student Outcome - ABET Student Outcome 3

> **ABET – EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.

| Criterio Específico | Acciones Realizadas | Conclusiones |
| :--- | :--- | :--- |
| **3.c1. Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **[Apellido, Nombre 1]:**<br>• *AV1:* Presenté ante cámara la introducción del modelo de negocio de Dymbia y la sustentación del problema agrícola.<br>• *TB1:* Expuse la demostración navegable del Landing Page ante el docente.<br><br>**[Apellido, Nombre 2]:**<br>• *AV1:* Expliqué los resultados de las entrevistas de Needfinding con agricultores y agrónomos.<br>• *TB1:* Sustenté los componentes de la arquitectura en Spring Boot. | **AV1:** El equipo logró transmitir de manera fluida y técnica la propuesta de valor de Dymbia adaptando el tono según la audiencia (docente y usuarios agrícolas).<br><br>**TB1:** Se demostró dominio de la arquitectura distribuida durante las preguntas síncronas. |
| **3.c2. Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **[Apellido, Nombre 1]:**<br>• *AV1:* Redacté el Problem Statement bajo el estándar Lean UX en inglés y las historias de usuario.<br>• *TB1:* Elaboré la documentación del Sprint Backlog 1.<br><br>**[Apellido, Nombre 2]:**<br>• *AV1:* Documenté el análisis competitivo frente a OneSoil y Agromonitoring.<br>• *TB1:* Redacté los contratos de la API OpenAPI/Swagger. | **AV1:** La documentación técnica redactada en Markdown mantiene un estándar formal y consistente sin errores de traducción.<br><br>**TB1:** La especificación de endpoints en Swagger facilita la integración transparente entre Angular y Spring Boot. |

---

## Tabla de Contenidos

1. [Capítulo I: Introducción](#capítulo-i-introducción)
   1. [1.1. Startup Profile](#11-startup-profile)
      1. [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      2. [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   2. [1.2. Solution Profile](#12-solution-profile)
      1. [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      2. [1.2.2. Lean UX Process](#122-lean-ux-process)
         1. [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
         2. [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
         3. [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
         4. [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
   3. [1.3. Segmentos objetivo](#13-segmentos-objetivo)
2. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
   1. [2.1. Competidores](#21-competidores)
      1. [2.1.1. Análisis competitivo](#211-análisis-competitivo)
      2. [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
   2. [2.2. Entrevistas](#22-entrevistas)
      1. [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      2. [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
      3. [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
   3. [2.3. Needfinding](#23-needfinding)
      1. [2.3.1. User Personas](#231-user-personas)
      2. [2.3.2. User Task Matrix](#232-user-task-matrix)
      3. [2.3.3. User Journey Mapping](#233-user-journey-mapping)
      4. [2.3.4. Empathy Mapping](#234-empathy-mapping)
   4. [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
   5. [2.5. Ubiquitous Language](#25-ubiquitous-language)
3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
   1. [3.1. User Stories](#31-user-stories)
   2. [3.2. Impact Mapping](#32-impact-mapping)
   3. [3.3. Product Backlog](#33-product-backlog)
4. [Capítulo IV: Product Design](#capítulo-iv-product-design)
   1. [4.1. Style Guidelines](#41-style-guidelines)
      1. [4.1.1. General Style Guidelines](#411-general-style-guidelines)
      2. [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
   2. [4.2. Information Architecture](#42-information-architecture)
      1. [4.2.1. Organization Systems](#421-organization-systems)
      2. [4.2.2. Labeling Systems](#422-labeling-systems)
      3. [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      4. [4.2.4. Searching Systems](#424-searching-systems)
      5. [4.2.5. Navigation Systems](#425-navigation-systems)
   3. [4.3. Landing Page UI Design](#43-landing-page-ui-design)
      1. [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
      2. [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
   4. [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
      1. [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
      2. [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
      3. [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
      4. [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
   5. [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
   6. [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
      1. [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
      2. [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
      3. [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
      4. [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
   7. [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
      1. [4.7.1. Class Diagrams](#471-class-diagrams)
   8. [4.8. Database Design](#48-database-design)
      1. [4.8.1. Database Diagrams](#481-database-diagrams)
5. [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
   1. [5.1. Software Configuration Management](#51-software-configuration-management)
      1. [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
      2. [5.1.2. Source Code Management](#512-source-code-management)
      3. [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
      4. [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
   2. [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
      1. [5.2.1. Sprint 1](#521-sprint-1)
      2. [5.2.2. Sprint 2](#522-sprint-2)
      3. [5.2.3. Sprint 3](#523-sprint-3)
   3. [5.3. Validation Interviews](#53-validation-interviews)
      1. [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
      2. [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
      3. [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
   4. [5.4. Video About-the-Product](#54-video-about-the-product)
6. [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
   1. [Conclusiones](#conclusiones)
   2. [Recomendaciones](#recomendaciones)
   3. [Video About-the-Team](#video-about-the-team)
7. [Bibliografía](#bibliografía)
8. [Anexos](#anexos)
* **Anexo A: Videos de Exposiciones**
* **Anexo B: Participant Performance Reports**