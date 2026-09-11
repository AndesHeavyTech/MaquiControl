# GRUPO-3

<p align="center">
  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/2c3d0613-f51e-47d7-bd82-439b78384731" />
</p>



<div align="center">

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

### FACULTAD DE INGENIERIA
### CARRERA DE INGENIERÍA DE SOFTWARE

<br>

# INFORME DE PROYECTO

## Nombre del proyecto
### ****

<br>

**Curso:**  
Desarrollo de Aplicaciones Open Source

**Sección:**  
7750

<br>

### Integrantes

| Integrante | Código |
|---|---|
| NICOLAS TANTALEAN GRANDA | U202410728 |
| WILMER SEBASTIAN GUTIERREZ LIZARBE| U202412044 |
| MATHIAS ALEJANDRO CASTILLO GUEVARA | U202410783 |
| CARLOS GABRIEL CESPEDES LEZCANO | U22416147 |

<br>

**Docente:**  
Efrain Ricardo Bautista Ubillus

<br>

**Ciclo:**  
[2026-2]

<br>

**Lima, Perú**  
**2026**
## Tabla de Contenidos

<details>
<summary><strong>Capítulo I: Introducción</strong></summary>

- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [What](#1211-what) · [Who](#1212-who) · [Where](#1213-where) · [When](#1214-when) · [Why](#1215-why) · [How](#1216-how) · [How Much](#1217-how-much)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [Problem Statements](#1221-lean-ux-problem-statements) · [Assumptions](#1222-lean-ux-assumptions) · [Hypothesis Statements](#1223-lean-ux-hypothesis-statements) · [Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

</details>

<details>
<summary><strong>Capítulo II: Requirements Elicitation & Analysis</strong></summary>

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
- [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)

</details>

<details>
<summary><strong>Capítulo III: Requirements Specification</strong></summary>

- [3.1. User Stories](#31-user-stories)
- [3.2. Impact Mapping](#32-impact-mapping)
- [3.3. Product Backlog](#33-product-backlog)

</details>

<details>
<summary><strong>Capítulo IV: Product Design</strong></summary>

- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Context Level Diagram](#462-software-architecture-context-level-diagram)
    - [4.6.3. Container Level Diagram](#463-software-architecture-container-level-diagram)
    - [4.6.4. Component Level Diagrams](#464-software-architecture-component-level-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)

</details>

<details>
<summary><strong>Capítulo V: Product Implementation, Validation & Deployment</strong></summary>

- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Style Guide & Conventions](#513-source-code-style-guide-conventions)
    - [5.1.4. Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services-applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
        - [Sprint Planning 1](#5211-sprint-planning-1)
        - [Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
        - [Sprint Backlog 1](#5213-sprint-backlog-1)
        - [Development Evidence](#5214-development-evidence-for-sprint-review)
        - [Execution Evidence](#5215-execution-evidence-for-sprint-review)
        - [Services Documentation Evidence](#5216-services-documentation-evidence-for-sprint-review)
        - [Deployment Evidence](#5217-software-deployment-evidence-for-sprint-review)
        - [Team Collaboration Insights](#5218-team-collaboration-insights-during-sprint)
- [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)

</details>

- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
    - [Anexo: Videos de Exposiciones](#anexo-videos-de-exposiciones)

</div>




# MaquiControl

## Registro de Versiones del Informe

## Project Report Collaboration Insights

## Contenido

## Student Outcome

# Capítulo I: Introducción

## 1.1 Startup Profile
Esta sección presenta el perfil de HeavyMach, la startup responsable del desarrollo de MaquiControl. Se describe su propósito, enfoque de negocio y propuesta de valor dentro del sector de alquiler y gestión de maquinaria pesada, así como los perfiles de los integrantes que participan en el desarrollo del proyecto.

### 1.1.1 Descripción de la Startup
HeavyMach tiene como objetivo transformar digitalmente la gestión, contratación y supervisión del alquiler de maquinaria pesada en las industrias de la construcción, minería e infraestructura, abarcando actividades desde la reserva de equipos y programación de mantenimientos hasta la emisión automatizada de comprobantes de pago. A través de su plataforma principal, HeavyMach permite a las empresas proveedoras y contratistas organizar de forma centralizada sus solicitudes de alquiler, asignar maquinaria y operadores de manera eficiente, y monitorear el estado operativo y financiero de sus flotas en tiempo real.

La solución busca resolver la falta de trazabilidad, la informalidad en la disponibilidad de equipos y los retrasos en los procesos administrativos en entornos donde las operaciones de obra deben adaptarse a cronogramas exigentes. Para ello, HeavyMach integra funcionalidades de catálogo dinámico con disponibilidad en tiempo real, programación de mantenimientos preventivos y correctivos, alertas automáticas de estado de máquina y emisión instantánea de facturación electrónica integrada a los estándares tributarios de SUNAT.

Una de las principales fortalezas del sistema es su capacidad para adaptarse a la realidad operativa del sector industrial: contempla la sincronización de datos entre personal de campo y administradores, la gestión transparente de valorizaciones por horas trabajadas, y dashboards especializados que reflejan el rendimiento de la flota y el cumplimiento de contratos en tiempo real. Esta solución aporta un valor diferencial tanto para los gestores de flota que planifican como para los contratistas que requieren equipos garantizados en obra.

**Misión:** Optimizar la comercialización, gestión operativa y trazabilidad tributaria del alquiler de maquinaria pesada mediante una plataforma inteligente, eficiente y adaptable a las necesidades del sector construcción e infraestructura.

**Visión:** HeavyMach aspira a convertirse en la plataforma tecnológica preferida por empresas de alquiler de maquinaria y contratistas en Latinoamérica, facilitando operaciones más eficientes, transparentes y formalizadas a través de la innovación digital aplicada al sector industrial.

### 1.1.2 Perfiles de integrantes del equipo
* **Wilmer Sebastián Gutiérrez Lizarbe**
    * **Código:** U202412044
    * **Carrera:** Ingeniería de Software (5.º ciclo)
    * **Perfil:** Estudiante de Ingeniería de Software con conocimientos en desarrollo web (HTML5, CSS3, JavaScript/TypeScript, Angular), arquitectura backend (Java, Spring Boot) y gestión de bases de datos relacionales y no relacionales. Aporta al equipo capacidad analítica para el diseño de arquitecturas distribuidas, integración de APIs RESTful y lógica de negocio orientada a procesos industriales.

*  **Carlos Gabriel Cespedes Lezcano**
    * **Codigo:** U202416147
    * **Carrea:** Ingeniería de Software (6.º ciclo)
    * **Perfil:** Estudiante de Ingeniería de Software con conocimientos en desarrollo web, incluyendo HTML, CSS y JavaScript, así como en los lenguajes de programación C++ y Python. Cuenta con nociones básicas sobre el consumo de APIs y el manejo de bases de datos, tanto relacionales como no relacionales.

* **Nicolas Tantalean Granda**
    * **Codigo:** U202410728
    * **Carrea:** Ingeniería de Software (5.º ciclo)
    * **Perfil:** Estudiante de Ingeniería de Software con conocimientos en desarrollo web, incluyendo HTML, CSS y JavaScript, así como en los lenguajes de programación C++ y Python. Aportare conocimientos al equipo sobre los lenguajes de programacion.

### 1.2 Solution Profile
Esta sección describe la problemática que MaquiControl busca resolver y la propuesta de solución planteada por HeavyMach. Se analizan las principales dificultades relacionadas con el alquiler, control y disponibilidad de maquinaria pesada, y se aplica el proceso Lean UX para definir las necesidades, supuestos e hipótesis que orientan el desarrollo del producto.

### 1.2.1 Antecedentes y problemática
En esta sección se presentan los antecedentes del sector de alquiler y gestión de maquinaria pesada, así como las principales dificultades que enfrentan los actores involucrados en este proceso. Se analizan problemas relacionados con la disponibilidad de equipos, la coordinación de alquileres, el seguimiento de mantenimientos, la comunicación entre proveedores y clientes, y la falta de información centralizada. A partir de estas limitaciones se establece la problemática que MaquiControl busca abordar mediante una solución digital orientada a mejorar la organización, trazabilidad y eficiencia de las operaciones.

##### 1.2.1.1. What

**¿Cuál es el problema?**

El problema se define como la ausencia de un recurso tecnológico centralizado capaz de organizar, planificar y supervisar el proceso de gestión, alquiler y mantenimiento de maquinaria pesada, así como la emisión de comprobantes de pago. Actualmente, la falta de un sistema digital unificado provoca **descoordinación**, **errores en la disponibilidad de equipos**, **pérdidas de tiempo por paradas no programadas**, **retrasos en la facturación electrónica** y **aumento de costos operativos** tanto para los proveedores de maquinaria como para las empresas contratistas. Esto genera impactos negativos en la eficiencia, la productividad de las obras y la liquidez de las PYMEs del sector.

##### 1.2.1.2. Who

**¿Quiénes están involucrados en el problema?**

Este problema involucra principalmente a **proveedores y gestores de flota de maquinaria pesada**, encargados de administrar el inventario, programar mantenimientos y asignar equipos; a **contratistas y jefes de obra**, responsables de la ejecución de proyectos de construcción o minería que requieren alquileres garantizados; a **técnicos de mantenimiento**, quienes registran las revisiones operativas de los equipos; y al **personal administrativo y contable**, que exige información exacta para la liquidación de horas máquina y la emisión de facturas electrónicas conformes a SUNAT. La falta de integración entre estos actores genera cuellos de botella que afectan directamente la continuidad de los proyectos.

##### 1.2.1.3. Where

**¿Dónde surge el problema?**

El problema surge en **obras de construcción, proyectos mineros, frentes de infraestructura y canteras** en todo el país, donde la ejecución de tareas requiere maquinaria en óptimas condiciones operativas. También se presenta en las **oficinas de control y centros administrativos de los proveedores**, donde la falta de visibilidad en tiempo real sobre la ubicación, estado técnico y disponibilidad de la flota limita la capacidad de respuesta ante imprevistos o solicitudes urgentes.

##### 1.2.1.4. When

**¿Cuándo se presenta el problema?**

El problema inicia desde la **búsqueda y reserva inicial de maquinaria**, cuando los contratistas no cuentan con información actualizada sobre la disponibilidad de equipos. Se intensifica durante la **ejecución en obra**, cuando ocurren averías imprevistas debido al descontrol en el historial de mantenimientos preventivos, y persiste hasta la etapa de **cierre del servicio y facturación**, donde se generan discrepancias en la liquidación de horas trabajadas y demoras en la emisión de comprobantes de pago.

##### 1.2.1.5. Why

**¿Por qué surge el problema?**

El problema se origina principalmente por la alta informalidad del sector y la continua dependencia de procesos manuales, tales como el registro de mantenimientos en papel, la coordinación de alquileres mediante mensajería informal y el cálculo manual de tarifas de alquiler. La ausencia de una solución SaaS integrada dificulta la comunicación fluida entre el personal operativo de obra y el área administrativa.

##### 1.2.1.6. How

**¿Cómo se utilizará el producto?**

La plataforma operará bajo un modelo distribuido accesible desde entornos web y móviles. Los clientes o contratistas navegarán por un catálogo interactivo con filtros por categoría, ubicación y precio para realizar reservas de maquinaria. Los proveedores gestionarán sus flotas, recibirán alertas automáticas para programar mantenimientos preventivos y monitorearán el estado de los contratos. Al finalizar el periodo de alquiler, la plataforma calculará automáticamente el monto correspondiente y generará la facturación electrónica integrada en cumplimiento con las normativas locales.

##### 1.2.1.7. How Much

**¿Cuál es la magnitud del problema?**

En el sector de la construcción e infraestructura, las averías no detectadas a tiempo por falta de mantenimiento representan pérdidas operativas de hasta un 25% en el tiempo de ejecución de una obra. Asimismo, las demoras administrativas y la falta de digitalización en el cobro y facturación electrónica afectan directamente la liquidez de más del 40% de las pequeñas y medianas empresas proveedoras de equipos.

### 1.2.2 Lean UX Process
En esta sección se aplica el proceso Lean UX para analizar la problemática desde una perspectiva centrada en los usuarios y en la validación temprana de supuestos. Se identifican los principales problemas, necesidades y comportamientos de los segmentos objetivo, y a partir de ellos se formulan assumptions e hypothesis statements que permiten orientar el desarrollo de MaquiControl. El resultado de este proceso se sintetiza en un Lean UX Canvas, que sirve como base para definir qué aspectos de la propuesta deben ser investigados y validados durante el proyecto.

#### 1.2.2.1 Lean UX Problem Statements
The current state of **heavy machinery rental and fleet management** has focused mainly on **manual rental agreements through messaging apps, paper-based maintenance logs, untracked equipment availability, and delayed manual electronic invoicing processes**.

What existing products/services fail to address is **an all-in-one digital platform that unifies real-time machinery catalog browsing, automated rental contract management, preventive maintenance control, and instant electronic invoicing compliant with local tax regulations**.

Our product/service will address this gap by **providing a distributed web platform that integrates real-time machinery availability tracking, service request workflows, automated fleet maintenance scheduling, and an integrated electronic invoicing module via RESTful APIs**.

Our initial focus will be **small and medium-sized construction contractors and heavy machinery rental companies in Peru**.

We'll know we are successful when we see **a 30% increase in rental booking conversions through the platform, a 25% reduction in machinery downtime due to scheduled maintenance alerts, and a 50% decrease in invoicing processing time during the first six months**.

#### 1.2.2.2 Lean UX Assumptions

**1. Business Assumptions:**
* Creemos que los proveedores de maquinaria pesada necesitan una plataforma digital centralizada para gestionar sus flotas y contratos, eliminando los registros manuales.
* Creemos que la monetización se alcanzará mediante cobro de suscripciones a proveedores de maquinaria y comisiones por transacción de alquiler realizada en la plataforma.
* Creemos que nuestros clientes iniciales serán empresas proveedoras de maquinaria de construcción y pequeñas empresas contratistas en Lima Metropolitana.
* Creemos que el valor diferenciador más importante es la integración inmediata del control de alquileres con la facturación electrónica automatizada.

**2. Business Outcome Assumptions:**
* Lograr la afiliación de al menos 15 empresas proveedoras de maquinaria pesada en los primeros 3 meses de lanzamiento.
* Reducir el tiempo promedio de contratación y emisión de facturas electrónicas de 3 días a menos de 15 minutos.
* Alcanzar una tasa de retención de clientes del 80% en el segundo trimestre de operación.

**3. User Assumptions:**
* **Clientes / Contratistas:** Necesitan alquilar maquinaria pesada garantizando disponibilidad inmediata, precios transparentes y equipos en buen estado técnico.
* **Proveedores de Maquinaria:** Buscan maximizar la tasa de ocupación de sus equipos, controlar los costos de mantenimiento y simplificar el cobro y la emisión de facturas electrónicas.
* **Técnicos de Mantenimiento:** Requieren registrar y recibir alertas de revisiones técnicas preventivas para evitar averías en obra.

**4. User Outcome and Benefit Assumptions:**
* Los contratistas podrán encontrar y alquilar maquinaria verificada en menos tiempo y sin intermediarios informales.
* Los proveedores reducirán los tiempos muertos de sus máquinas y tendrán visibilidad completa del estado financiero y operativo de su flota.
* Los contadores generarán facturas electrónicas sin errores de tipeo ni discrepancias con las horas máquina trabajadas.

**5. Feature Assumptions:**
* **Feature 1:** Catálogo interactivo de maquinaria pesada con filtros por tipo, ubicación, precio y disponibilidad en tiempo real.
* **Feature 2:** Módulo de gestión y reserva de contratos de alquiler con cálculo automático de tarifas por hora o día.
* **Feature 3:** Módulo de control de mantenimientos con programación de alertas preventivas y registro de historial técnico.
* **Feature 4:** Módulo de facturación electrónica integrado que genera comprobantes (facturas/boletas) en formato XML y PDF autorizados por SUNAT.
* **Feature 5:** Dashboard con métricas de rendimiento de flota, ingresos generados y próximos mantenimientos.

#### 1.2.2.3 Lean UX Hypothesis Statements
* **Hypothesis Statement 1:**
  We believe we will achieve **a 30% increase in successful machinery rentals** if **construction contractors** attain **quick identification and reservation of available equipment** with **a real-time interactive machinery catalog and search filters**.

* **Hypothesis Statement 2:**
  We believe we will achieve **a 40% reduction in booking transaction times** if **rental company managers** attain **streamlined contract creation and automated fee calculation** with **a digital rental contract management module**.

* **Hypothesis Statement 3:**
  We believe we will achieve **a 25% decrease in machinery breakdown incidents on site** if **fleet maintenance managers** attain **timely execution of technical revisions** with **an automated maintenance scheduling and alert system**.

* **Hypothesis Statement 4:**
  We believe we will achieve **a 50% reduction in administrative billing errors** if **accounting staff** attain **instant and compliant invoice generation linked to rental agreements** with **an integrated electronic invoicing module**.

* **Hypothesis Statement 5:**
  We believe we will achieve **an 85% user satisfaction rate among rental business owners** if **startup managers** attain **clear visibility into fleet productivity and monthly earnings** with **an analytics dashboard displaying real-time business KPIs**.

#### 1.2.2.4 Lean UX Canvas
![Lean UX Canvas](./assets/lean-ux-canvas.png)
*Ver el lienzo del Lean UX Canvas en [Canva](https://canva.link/k7s7r8rxw4h0cae).*

### 1.3 Segmentos objetivo

Para el desarrollo y validación de MaquiControl se han definido dos segmentos objetivo relacionados directamente con la contratación y gestión de maquinaria pesada. La selección considera tanto su relación con la problemática identificada como la posibilidad de acceder a representantes reales durante las etapas de investigación y validación del producto.

#### Segmento 1: Propietarios y administradores de pequeñas empresas de alquiler de maquinaria

- **Descripción del segmento:** Personas responsables de pequeñas empresas o negocios dedicados al alquiler de maquinaria y equipos para construcción. Administran la disponibilidad de sus equipos, coordinan reservas con clientes, realizan seguimiento de mantenimientos y controlan pagos y contratos.

- **Edad:** Aproximadamente entre 25 y 55 años.
- **Ubicación geográfica:** Principalmente Lima Metropolitana y otras ciudades con actividad de construcción.
- **Rol:** Propietarios, administradores, encargados de operaciones o responsables de alquiler.
- **Uso de tecnología:** Utilizan smartphones, WhatsApp, llamadas telefónicas, hojas de cálculo y otras herramientas básicas para coordinar alquileres y registrar información.
- **Necesidades principales:** Controlar la disponibilidad de la maquinaria, evitar cruces de reservas, registrar mantenimientos y centralizar la información de clientes y alquileres.

#### Segmento 2: Contratistas independientes y responsables de pequeñas obras de construcción

- **Descripción del segmento:** Personas que realizan o supervisan proyectos de construcción y que necesitan alquilar maquinaria o equipos durante determinadas etapas de una obra. Este grupo puede incluir contratistas independientes, maestros de obra, supervisores y pequeños empresarios del sector construcción.

- **Edad:** Aproximadamente entre 25 y 55 años.
- **Ubicación geográfica:** Lima Metropolitana y zonas urbanas con alta actividad de construcción.
- **Rol:** Contratistas independientes, maestros de obra, supervisores o responsables de pequeñas empresas constructoras.
- **Uso de tecnología:** Utilizan principalmente smartphones, WhatsApp, redes sociales y búsquedas en Internet para contactar proveedores y coordinar servicios.
- **Necesidades principales:** Encontrar maquinaria disponible rápidamente, conocer precios y características, coordinar fechas de alquiler y contar con información clara sobre el estado de su solicitud.
# Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores

### 2.1.1 Análisis competitivo

### Competitive Analysis Landscape

**¿Por qué llevar a cabo este análisis?**  
*¿De qué manera MaquiControl puede diferenciarse de las soluciones de alquiler de maquinaria pesada locales e internacionales mediante una plataforma SaaS integral que unifique la gestión operativa de flota, la programación preventiva de mantenimientos y la facturación electrónica instantánea compatible con SUNAT?*

| Sección | Criterio / Perfil | Su startup: **MaquiControl (HeavyMach)** | Competidor 1: **RentaFacil / Portales Locales** | Competidor 2: **EquipmentShare** | Competidor 3: **Gestión Manual / Excel** |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Perfil** | **Overview** | Plataforma SaaS integral para la gestión, reserva, mantenimiento preventivo y facturación electrónica de maquinaria pesada. | Portales web de directorio, anuncios clasificados y empresas tradicionales de alquiler local. | Plataforma internacional avanzada de telemetría, rastreo GPS y gestión de flota para construcción. | Control interno informal ejecutado en hojas de cálculo, cuadernos y mensajería instantánea. |
| **Perfil** | **Ventaja competitiva / ¿Qué valor ofrece a los clientes?** | Unificación en un solo flujo digital del alquiler, control técnico de mantenimiento y emisión automática de facturas SUNAT. Transparencia y eliminación de tiempos muertos. | Presencia local previa y red de contactos directos. Contacto rápido vía telefónica o WhatsApp para cotizaciones puntuales. | Telemetría IoT avanzada y alta escala internacional. Control preciso de activos mediante hardware especializado y sensores en tiempo real. | Cero costo directo de software e implementación inmediata. Flexibilidad absoluta en la anotación empírica de datos. |
| **Perfil de Marketing** | **Mercado objetivo** | PYMEs de alquiler de maquinaria y pequeños/medianos contratistas en Perú y Latinoamérica. | Empresas de construcción y contratistas independientes que buscan equipamiento urgente. | Grandes corporaciones de construcción, minería e infraestructura masiva en EE.UU./Global. | Maestros de obra, contratistas independientes y microproveedores informales. |
| **Perfil de Marketing** | **Estrategias de marketing** | Inbound marketing B2B, alianzas con gremios de construcción (CAPECO) y prueba gratuita SaaS. | Anuncios pagados en redes sociales, clasificados impresos/web y prospección telefónica. | Marketing corporativo B2B, eventos de la industria pesada y fuerza de ventas directa. | Recomendación boca a boca (*Word of Mouth*) y redes de contactos personales. |
| **Perfil de Producto** | **Productos & Servicios** | Catálogo interactivo, motor de reservas, alertas de mantenimiento y facturación XML/PDF. | Listado estático de equipos, formulario de contacto y cotización bajo solicitud. | Rastreo GPS, diagnóstico de motores, control de activos y portal de alquiler corporativo. | Planillas de Excel editables, cuadernos de campo y comprobantes en portal externo. |
| **Perfil de Producto** | **Precios & Costos** | Suscripción mensual/anual por tamaño de flota + comisión por transacción de alquiler. | Cotizaciones variables según negociación directa, volumen y duración del servicio. | Suscripción Enterprise de alto costo + tarifas corporativas de arrendamiento. | Sin costo de software (cubierto por licencias estándar de ofimática o papel). |
| **Perfil de Producto** | **Canales de distribución (Web y/o Móvil)** | Aplicación Web Progresiva (PWA) accesible desde navegadores web y dispositivos móviles. | Sitio web informativo, llamadas telefónicas directas y mensajería vía WhatsApp. | Plataforma web Enterprise y aplicación móvil nativa (iOS / Android). | Archivos locales de computadora, hojas impresas y carpetas físicas. |
| **Análisis SWOT** | **Fortalezas** | • Plataforma SaaS All-In-One (alquiler, mantenimiento, SUNAT).<br>• Interfaz responsiva intuitiva.<br>• Automatización de alertas preventivas. | • Posicionamiento de marca local.<br>• Confianza por relaciones comerciales previas. | • Tecnología IoT y telemetría de vanguardia.<br>• Respaldo de grandes capitales. | • Cero costo de software.<br>• Familiaridad total de uso. |
| **Análisis SWOT** | **Debilidades** | • Marca nueva en el mercado peruano.<br>• Dependencia de la adopción tecnológica inicial. | • Proceso de reserva estático y manual.<br>• Sin gestión interna de mantenimiento. | • Costos inaccesibles para PYMEs.<br>• Sin localización tributaria SUNAT. | • Alto riesgo de pérdida de datos y sobreventa.<br>• Sin alertas ni análisis en tiempo real. |
| **Análisis SWOT** | **Oportunidades** | • Exigencia de formalización SUNAT.<br>• Insatisfacción por averías imprevistas. | • Migración digital mediante alianzas. | • Captura de sector minero corporativo. | • Gran volumen de mercado por digitalizar. |
| **Análisis SWOT** | **Amenazas** | • Resistencia al cambio informal.<br>• Entrada de competidores globales. | • Pérdida de cuota ante plataformas en tiempo real. | • Barreras normativas en LATAM. | • Perpetuación de la informalidad. |

---

### 2.1.2 Estrategias y tácticas frente a competidores
A partir del análisis FODA cruzado, MaquiControl aplicará las siguientes estrategias y tácticas preliminares:

1. **Estrategia de Penetración de Mercado vs. Gestión Manual (Excel/WhatsApp):**
    * *Táctica:* Ofrecer una prueba gratuita (*Free Trial*) de 30 días acompañada de una plantilla de migración asistida, demostrando la reducción del 50% en tiempo administrativo y la eliminación de cruces de reservas desde la primera semana.
2. **Estrategia de Diferenciación vs. Portales Locales Tradicionales:**
    * *Táctica:* Promover la funcionalidad de **Catálogo Dinámico con Disponibilidad Garantizada en Tiempo Real** e integración instantánea con **Facturación Electrónica SUNAT**, posicionando a MaquiControl no solo como un directorio, sino como el sistema operativo del negocio de alquiler.
3. **Estrategia de Costo-Efectividad vs. Competidores Internacionales (EquipmentShare):**
    * *Táctica:* Comercializar una solución SaaS *cloud-native* sin necesidad de instalación de hardware costoso en etapas iniciales, ofreciendo planes de suscripción adaptados a la cantidad de máquinas de la PYME (desde 1 hasta 20 equipos).
4. **Estrategia de Mitigación de Amenazas Operativas:**
    * *Táctica:* Implementar un módulo de **Historial Técnico Certificado** que otorgue un "Sello de Mantenimiento al Día" a las máquinas registradas, incrementando la confianza de los contratistas y justificando tarifas de alquiler más competitivas.

## 2.2 Entrevistas
En esta sección se desarrolla el proceso de recolección de información mediante entrevistas dirigidas a representantes de los segmentos objetivo definidos para MaquiControl. El propósito es conocer sus experiencias, necesidades, problemas y comportamientos relacionados con el alquiler y gestión de maquinaria, de modo que los hallazgos obtenidos sirvan como base para el análisis de requerimientos y la posterior construcción de los User Personas y demás artefactos de Needfinding.

### 2.2.1 Diseño de entrevistas
Para la recolección de requerimientos se diseñaron guías de entrevista breves y estructuradas de 5 preguntas clave por segmento objetivo. Estas combinan datos demográficos/tecnológicos para el perfilamiento de arquetipos (*User Personas*) con preguntas profundas sobre la problemática operativa y de negocio.

### Segmento 1: Propietarios y administradores de empresas de alquiler de maquinaria

1. **¿Cuál es su nombre, edad, cargo, dispositivos y aplicaciones que utiliza a diario para administrar su negocio?** *(Complementaria)*
2. **¿Qué marcas o proveedores prefiere y qué fuentes consulta antes de tomar decisiones operativas?** *(Complementaria)*
3. **¿Cómo gestiona actualmente el inventario, la disponibilidad y los mantenimientos de su flota?** *(Principal)*
4. **¿Qué sucede cuando una máquina sufre una avería inesperada en obra y cómo gestiona las pérdidas?** *(Principal)*
5. **¿Cómo realiza la conciliación de horas trabajadas y la emisión de facturas electrónicas (SUNAT)?** *(Principal)*
6. **¿Cuáles son sus principales objetivos o prioridades dentro de su trabajo diario? (Complementaria)**
7. **¿Qué situaciones relacionadas con el alquiler o gestión de maquinaria le generan mayor frustración? (Complementaria)**
8. **¿Qué aplicaciones, páginas web o herramientas digitales utiliza con mayor frecuencia para trabajar y comunicarse? (Complementaria)**

### Segmento 2: Contratistas independientes y responsables de obras de construcción

1. **¿Cuál es su nombre, edad, cargo, nivel educativo y qué dispositivos/navegadores utiliza en obra?** *(Complementaria)*
2. **¿A través de qué canales o influencias del sector busca y contrata proveedores de maquinaria?** *(Complementaria)*
3. **¿Qué dificultades encuentra respecto a la transparencia de tarifas y la disponibilidad real de los equipos?** *(Principal)*
4. **¿Ha experimentado paradas de obra por fallas mecánicas en maquinaria alquilada? ¿Cómo afectó sus costos?** *(Principal)*
5. **¿Cómo valida el conteo de horas trabajadas y qué exige en una plataforma digital para reservar maquinaria?** *(Principal)*
6. **¿Cuáles son sus principales objetivos o prioridades dentro de su trabajo diario? (Complementaria)**
7. **¿Qué situaciones relacionadas con el alquiler o gestión de maquinaria le generan mayor frustración? (Complementaria)**
8. **¿Qué aplicaciones, páginas web o herramientas digitales utiliza con mayor frecuencia para trabajar y comunicarse? (Complementaria)**

### 2.2.2 Registro de entrevistas

### 2.2.3 Análisis de entrevistas

## 2.3 Needfinding

### 2.3.1 User Personas

### 2.3.2 User Task Matrix

### 2.3.3 User Journey Mapping

### 2.3.4 Empathy Mapping

## 2.4 Big Picture Event Storming

## 2.5 Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1 User Stories

## 3.2 Impact Mapping

## 3.3 Product Backlog

# Capítulo IV: Product Design

## 4.1 Style Guidelines

## 4.2 Information Architecture

## 4.3 Landing Page UI Design

## 4.4 Web Applications UX/UI Design

## 4.5 Web Applications Prototyping

## 4.6 Domain-Driven Software Architecture

## 4.7 Software Object-Oriented Design

## 4.8 Database Design

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management

## 5.2 Landing Page, Services & Applications Implementation

## 5.3 Validation Interviews

## 5.4 Video About-the-Product

# Conclusiones

# Bibliografía

# Anexos