# Capitulo V: Product Implementation, Validation & Deployment.
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

### Project Management

- **WhatsApp**: Aplicación de mensajería instantánea que fue utilizada para coordinar tareas del equipo, interca,biar ideas y brindar soporte continuo durante el desarrollo del proyecto.
- **Google Meet**: Herramienta de videoconferencias de Google empleada para mantener una comunicación verbal y directa, permitiendo la planificación colaborativa de actividades y la toma de decisiones en tiempo real.
- **Microsoft 365**: Servicio en la nube que integra herramientas clásicas como Word y Excel, ofreciendo acceso desde cualquier lugar y permitiendo la colaboración en tiempo real. Permitió la supervisión continua de los avances de los miembros.

### Requirements Management

- **UXPressia**: Herramienta utilizada para la elaboración de User Personas, User Journey Maps e Impact Maps, lo que permite comprender mejor las necesidades de los usuarios y definir funcionalidades centradas en ellos.
- **Zoom**: Aplicación de Google empleada para la toma de entrevistas a potenciales usuarios, facilitando la recopilación de información valiosa para la definición y validación de requisitos.

### Product UX/UI Design

- **Figma**: Plataforma colaborativa utilizada para el diseño de wireframes, wireflows, mockups y prototipos interactivos, garantizando una visión clara y alineada de la interfaz del producto.

### Software Development

- **Visual Studio Code**: Editor de código utilizado para la implementación de la Landing Page, gracias a sus extensiones y soporte para diversas tecnologías web.
- **Google Chrome**: Navegador utilizado para la ejecución de pruebas de visualización y funcionalidad de la landing page y el frontend, asegurando su correcto comportamiento en entornos reales.

### Software Deployment

- **Github Pages**: Servicio de hosting utilizado para el despliegue de la landing page del proyecto.

### Software Documentation

- **Structurizr**: Plataforma empleada para la creación de diagramas C4, permitiendo representar visualmente la arquitectura del software en distintos niveles de abstracción.
- **GitHub**: Plataforma utilizada para la gestión de repositorios de código y documentación del proyecto, incluyendo la landing page, el frontend, el backend y los documentos técnicos, facilitando el trabajo colaborativo y el control de versiones.
- **Vertabelo**: Herramienta especializada en el modelado de bases de datos, utilizada para diseñar diagramas entidad-relación (ERD), permitiendo estructurar de manera clara y eficiente la arquitectura de datos del sistema.
- **Trello**: Herramienta de gestión ágil utilizada para la organización del Product Backlog y Sprint Backlog, permitiendo priorizar tareas, hacer seguimiento del progreso y coordinar el trabajo del equipo de manera colaborativa.


### 5.1.2. Source Code Management.

El proyecto utiliza GitHub como repositorio para administrar y estructurar los avances. Implementamos el flujo de trabajo **Gitflow**, siguiendo la metodología propuesta por Vincent Driessen, para mantener versiones estables y trabajo colaborativo ordenado.

**Main branch:** Rama principal donde se almacena el código de producción estable.

**Develop branch:** Rama de integración donde se fusionan las nuevas funcionalidades desarrolladas.

**Chapter branches:** Ramas creadas a partir de `develop` para seccionar los avances del proyecto por capítulo. Cada chapter se trabaja de forma aislada para evitar conflictos.

**Conventional Commits:** Estándar aplicado en los mensajes de commit para mantener un historial de cambios claro, comprensible y trazable, mejorando además la automatización de flujos de despliegue.

### 5.1.3. Source Code Style Guide & Conventions.

**HTML:**

Seguimos las convenciones descritas en la guía oficial HTML Style Guide and Coding Conventions para fomentar una estructura limpia, semántica y predecible:

- Usar nombres de elementos en minúsculas.
- Cerrar todos los elementos HTML, incluso los que son opcionales.
- Usar nombres de atributos en minúsculas.
- Incluir siempre los atributos requeridos en elementos clave, especialmente en imágenes (alt) y formularios (name, id, etc.).
- Evitar líneas de código largas para mejorar la legibilidad.
- Utilizar sintaxis simplificada y estándar para hojas de estilo (link) y scripts externos (script).

**CSS:**

Aplicamos las siguientes convenciones para lograr un estilo consistente, ordenado y fácil de mantener:

- Usar minúsculas y guiones para los nombres de clases y selectores.
- Escribir un espacio después de los dos puntos y cerrar cada declaración con punto y coma.
- Agrupar reglas CSS relacionadas y separarlas con una línea en blanco para mejorar la claridad visual.
- Utilizar nombres de clases descriptivos, que reflejen la función o apariencia del elemento.
- Organizar el CSS por bloques lógicos o módulos.

**JavaScript:**

Definimos las siguientes convenciones para asegurar un código robusto, eficiente y comprensible:

- Declarar las variables al inicio del ámbito correspondiente, evitando la redeclaración innecesaria.
- Preferir el uso de const y let en lugar de var para controlar mejor el ámbito y la mutabilidad de las variables.
- Incluir comentarios descriptivos para explicar la funcionalidad de componentes, servicios, validaciones y lógica compleja.
- Mantener las funciones pequeñas y con una única responsabilidad.
- Aplicar principios de programación funcional y reactiva, así como patrones de diseño adecuados.

### 5.1.4. Software Deployment Configuration.

#### Entorno de Desarrollo

Tecnologías utilizadas:
- HTML5
- CSS3
- Javascript

#### Estrategia de Deployment

- Github Pages
- Repositorio principal en GitHub

Flujo Gitflow:

- main: rama principal de producción
- develop: rama de integración principal
- chapter-n*: desarrollo de los chapters sobre develop
- Pull Requests se realizan desde chapter-n hacia develop

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

<table border>
    <tr align="center">
        <td><strong>Sprint #</strong></td>
        <td><strong>Sprint 1</strong></td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Planning Background</strong></td>
    </tr>
    <tr align="center">
        <td>Date</td>
        <td>09/04/2026</td>
    </tr>
    <tr align="center">
        <td>Time</td>
        <td>15:00 PM</td>
    </tr>
    <tr align="center">
        <td>Location</td>
        <td>Meet</td>
    </tr>
    <tr align="center">
        <td>Prepared by</td>
        <td>Milenko Cayanchi</td>
    </tr>
    <tr align="center">
        <td>Attendess (to planning meeting)</td>
        <td>
          Milenko Rubén Cayanchi Avila - u202312566<br>
          Jose Gustavo Asto Jacome - u20241c630<br>
          Alberto Alejandro Ponce Perales - u202320684<br>
          Diego Fernando Herrera Enriquez - u202319027<br>
          Brayan Alexis Corvacho Damian - u20231a257
        </td>
    </tr>
    <tr align="center">
        <td>Sprint 0 Review Summary</td>
        <td>No hubo sprint previo</td>
    </tr>
    <tr align="center">
        <td>Sprint 0 Retrospective Summary</td>
        <td>No hubo sprint previo</td>
    </tr>
    <tr>
        <td colspan="2" align="center"><strong>Sprint Goal & User Stories</strong></td>
    </tr>
    <tr>
        <td align="center">Sprint 1 Goal</td>
        <td>Nuestro objetivo es comunicar la propuesta de valor de FullTank a clientes y proveedores potenciales
            mediante una página de destino funcional. Creemos que esto genera conocimiento de la marca e interés en
            la conversión entre las empresas que solicitan combustible y los proveedores. Esto se confirmará cuando 
            los visitantes puedan navegar por todas las secciones, cambiar de idioma y acceder al formulario de registro
            sin errores.
        </td>
    </tr>
    <tr align="center">
        <td>Sprint 1 Velocity</td>
        <td>17</td>
    </tr>
    <tr align="center">
        <td>Sum of Story Point</td>
        <td>17</td>
    </tr>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators.

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Team Member</th>
      <th>GitHub Username</th>
      <th>Landing Page</th>
      <th>Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Milenko Rubén Cayanchi Avila</td>
      <td>MaxghZZ</td>
      <td>L</td>
      <td>L</td>
    </tr>
    <tr>
      <td>Jose Gustavo Asto Jacome</td>
      <td>DhudsQ</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Diego Fernando Herrera Enriquez</td>
      <td>DerDFHE</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Alberto Alejandro Ponce Perales</td>
      <td>aponceperales</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Brayan Alexis Corvacho Damian</td>
      <td>BralexCD</td>
      <td>C</td>
      <td>C</td>
    </tr>
  </tbody>
</table>

#### 5.2.1.3. Sprint Backlog 1.

<table border>
    <tr align="center">
        <td colspan="2"><strong>Sprint #</strong></td>
        <td colspan="6"><strong>Sprint 1</strong></td>
    </tr>
    <tr align="center">
        <td colspan="2"><strong>User Story</strong></td>
        <td colspan="6"><strong>Work-Item / Task</strong></td>
    </tr>
    <tr align="center">
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Id</strong></td>
        <td><strong>Title</strong></td>
        <td><strong>Description</strong></td>
        <td><strong>Estimation (Hours)</strong></td>
        <td><strong>Assigned to</strong></td>
        <td><strong>Status (To do / In process / To review / Done)</strong></td>
    </tr>
    <tr align="center">
        <td>US-01</td>
        <td>Ver sección Home</td>
        <td>W-01</td>
        <td>Sección Home</td>
        <td>Como visitante (proveedor), quiero ver una sección de inicio que resuma el valor de FullTank para comprender rápidamente el objetivo del sistema</td>
        <td>5 horas</td>
        <td>Milenko</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-02</td>
        <td>Ver sección About Us</td>
        <td>W-02</td>
        <td>Sección About Us</td>
        <td>Como visitante de ambos segmentos, quiero conocer quiénes están detrás de FullTank para confiar en el sistema</td>
        <td>4 horas</td>
        <td>Alberto</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-03</td>
        <td>Ver sección How it Works?</td>
        <td>W-03</td>
        <td>Sección How it works?</td>
        <td>Como visitante de ambos segmentos, quiero entender cómo funciona FullTank paso a paso para evaluar si se ajusta a mis necesidades</td>
        <td>5 horas</td>
        <td>Jose</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-36</td>
        <td>Ver sección Benefits</td>
        <td>W-04</td>
        <td>Sección Beneficios</td>
        <td>Como visitante de ambos segmentos, quiero conocer las principales ventajas con las que puedo contar para evaluar la implementación de la plataforma</td>
        <td>4 horas</td>
        <td>Jose</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-37</td>
        <td>Ver sección Lo que Dicen Nuestros Clientes</td>
        <td>W-05</td>
        <td>Sección Testimonios</td>
        <td>Como visitante de ambos segmentos, quiero conocer los testimonios de los usuarios de FullTank para tener confianza en la plataforma y saber que otras empresas ya la están usando.</td>
        <td>6 horas</td>
        <td>Alberto</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-04</td>
        <td>Enviar mensaje de contacto</td>
        <td>W-06</td>
        <td>Contacto</td>
        <td>Como visitante de ambos segmentos, quiero enviar un mensaje desde Contact Us para solicitar más información</td>
        <td>5 horas</td>
        <td>Brayan</td>
        <td>In Process</td>
    </tr>
    <tr align="center">
        <td>US-38</td>
        <td>Ver sección Planes y Precios</td>
        <td>W-07</td>
        <td>Sección Planes y Precios</td>
        <td>Como visitante (ambos segmentos), quiero saber que planes se adecuan a mis necesidades para poder iniciar un proceso de registro o solicitud.</td>
        <td>6 horas</td>
        <td>Milenko</td>
        <td>Done</td>
    </tr>
    <tr align="center">
        <td>US-39</td>
        <td>Cambiar idioma</td>
        <td>W-08</td>
        <td>Idioma</td>
        <td>Como visitante de ambos segmentos, quiero poder cambiar entre inglés y español para entender la plataforma en mi idioma preferido</td>
        <td>8 horas</td>
        <td>Diego</td>
        <td>In Process</td>
    </tr>
</table>

#### 5.2.1.4. Development Evidence for Sprint Review.

Durante el Sprint 1, nuestro equipo culminó la implementación de la Landing Page de FullTank, cumpliendo con las User Stories priorizadas. Se trabajó en la maquetación de las secciones principales, implementación de estilos CSS, diseño responsive para diferentes dispositivos y subida de los cambios al repositorio grupal. Los commits fueron realizados en la rama main, cada uno agregando una sección de la Landing Page

<table border>
  <thead>
    <tr>
      <th>Repositorio</th>
      <th>Rama</th>
      <th>ID de Commit</th>
      <th>Mensaje de Commit</th>
      <th>Descripción del Commit</th>
      <th>Fecha de Commit</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>5596c00</td>
    <td>feat: add initial landing page structure for FullTank web platform</td>
    <td>-</td>
    <td>24/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>6c22e93</td>
    <td>feat: implement landing page interactivity including navigation, scroll effects, FAQ accordion, and animations</td>
    <td>-</td>
    <td>24/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>02df602</td>
    <td>feat: add styles for metrics, FAQ accordion, step cards, and responsive navbar components</td>
    <td>-</td>
    <td>24/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>25bd1bf</td>
    <td>feat: add styling for testimonials, pricing, FAQ, footer, about, and team sections</td>
    <td>-</td>
    <td>24/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>feat/about us</td>
    <td>0408f5d</td>
    <td>docs: improved the spelling</td>
    <td>-</td>
    <td>25/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>feat/about us</td>
    <td>389615f</td>
    <td>docs: added images file</td>
    <td>-</td>
    <td>25/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>771e406</td>
    <td>add team profiles and about-the-team video section</td>
    <td>-</td>
    <td>25/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>68e2115</td>
    <td>docs: fix landing page text</td>
    <td>-</td>
    <td>25/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>3ce5d9d</td>
    <td>feat(about the product): add stakeholder video for the future</td>
    <td>-</td>
    <td>26/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>d6c516c</td>
    <td>fix(english switched): everything is now translated to english</td>
    <td>-</td>
    <td>26/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>bc61806</td>
    <td>fix(responsive design):responsive design corrected</td>
    <td>-</td>
    <td>26/04/2026</td>
  </tr>
  <tr>
    <td>PrimeFuel/FullTank_LandingPage</td>
    <td>main</td>
    <td>bae9d2d</td>
    <td>fix(main.js): minor translation problems solved</td>
    <td>-</td>
    <td>26/04/2026</td>
  </tr>
</tbody>

</table>

#### 5.2.1.5. Execution Evidence for Sprint Review.

En el sprint 1 se diseñó el primer modelo de la landing page. Esta cuenta con diferentes secciones para acceso de los usuarios. Algunas evidencias son:
- **Home:** Presenta de manera rápida el propósito y valor de FullTank para captar la atención del visitante.
![Home](../assets/chapter-5/HomeLandingPage.png)

- **About Us:** Explica quiénes somos y nuestra misión para generar confianza.
![About Us 1](../assets/chapter-5/AboutUs1LandingPage.png)
![About Us 2](../assets/chapter-5/AboutUs2LandingPage2.png)
![About Us 3](../assets/chapter-5/AboutUs3LandingPage.png)

- **Benefits:** Explica los beneficios de implementar FullTank en el área logística de la empresa.
![Benefits](../assets/chapter-5/BenefitsLandingPage.png)

- **How it works?:** Describe de forma sencilla y visual el funcionamiento de FullTank paso a paso.
![How it works?](../assets/chapter-5/HowItWorksLandingPage.png)

- **Testimonials:** Muestra algunas de las empresas o usuarios que confían en FullTank como referencia de credibilidad.
![Testimonials](../assets/chapter-5/TestimonialsLandingPage.png)

- **Pricing:** Propone planes y precios que puedan acomodarse a las necesidades del usuario.
![Pricing](../assets/chapter-5/PricingLandingPage.png)

- **Contact Us:** Ofrece un formulario y datos de contacto directo para resolver dudas o solicitar soporte.
![Contact Us](../assets/chapter-5/ContactUsLandingPage.png)

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Durante el Sprint 1, el equipo se enfocó en el desarrollo del Landing Page de FullTank, por lo cual no se implementaron ni documentaron endpoints relacionados a Web Services. Los trabajos de desarrollo backend, integración de API y documentación con OpenAPI están planificados para Sprints posteriores.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

<p>
    <strong>Resumen:</strong><br>
    El despliegue inicial de la Landing Page de FullTank fue realizado exitosamente utilizando Vercel.
</p>

<h4>Detalles del Despliegue:</h4>

<ul>
  <li><strong>URL de la Landing Page:</strong> <a href="https://primefuel.github.io/FullTank_LandingPage/" target="_blank">https://primefuel.github.io/FullTank_LandingPage/</a></li>
  <li><strong>Repositorio:</strong> <a href="https://github.com/PrimeFuel/FullTank_LandingPage" target="_blank">https://github.com/PrimeFuel/FullTank_LandingPage</a></li>
</ul>

<h4>Evidencia:</h4>

![Deployment Visual Evidence of Analytics](../assets/chapter-5/Deploy1LandingPage.png)

![Deployment Visual Evidence of Analytics](../assets/chapter-5/Deploy2LandingPage.png)

#### 5.2.1.8. Team Collaboration Insights during Sprint. 

<p>
    <strong>Resumen:</strong><br>
    El equipo colaboró mediante GitHub y WhatsApp durante el Sprint. Las actividades principales se centraron en el desarrollo y despliegue de la Landing Page.
</p>

<h4>Evidencia de Colaboración:</h4>
<ul>
  <li>Captura de pantalla de commits en GitHub mostrando contribuciones del equipo.</li>
</ul>

<h4>Principales Herramientas de Comunicación:</h4>
<ul>
  <li>GitHub (control de versiones y manejo de issues)</li>
  <li>WhatsApp (comunicación diaria y aclaraciones rápidas)</li>
  <li>Google Meet (reuniones de planificación de sprint)</li>
</ul>

### 5.2.2. Sprint 2
#### 5.2.2.1.Sprint Planning 2

<table border="1" cellspacing="0" cellpadding="6">
  <tr>
    <td><strong>Sprint #</strong></td>
    <td><strong>Sprint 2</strong></td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Sprint Planning Background</strong></td>
  </tr>
  <tr>
    <td>Date</td>
    <td>04/05/2026</td>
  </tr>
  <tr>
    <td>Time</td>
    <td>15:00 PM</td>
  </tr>
  <tr>
    <td>Location</td>
    <td>Meet / Discord</td>
  </tr>
  <tr>
    <td>Prepared by</td>
    <td>Asto Jacome Jose Gustavo</td>
  </tr>
  <tr>
    <td>Attendees (to planning meeting)</td>
    <td>
      Asto Jacome Jose Gustavo (u20241c630)<br>
      Cayanchi Avila Milenko Rubén (u202312566)<br>
      Corvacho Damian Brayan Alexis (u20231a257)<br>
      Ponce Perales Alberto Alejandro (u202320684)<br>
      Herrera Enriquez Diego Fernando (u202319027)
    </td>
  </tr>
  <tr>
    <td>Sprint 1 Review Summary</td>
    <td>Se logró desplegar con éxito la Landing Page. Se estableció la arquitectura base del proyecto Angular con estructura por Bounded Contexts (DDD). El feedback fue positivo en cuanto a consistencia de estilos y organización del repositorio.</td>
  </tr>
  <tr>
    <td>Sprint 1 Retrospective Summary</td>
    <td>El equipo trabajó de forma coordinada. Se identificó la necesidad de definir convenciones claras de nomenclatura por módulo y de alinear el uso de Angular Signals y NgRx antes de avanzar con vistas operativas complejas.</td>
  </tr>
  <tr>
    <td colspan="2" align="center"><strong>Sprint Goal &amp; User Stories</strong></td>
  </tr>
  <tr>
    <td>Sprint 2 Goal</td>
    <td>
      Construir y estabilizar la Web Application (Frontend) funcional de FullTank en Angular 17, implementando los módulos operativos principales: inventario, pedidos (solicitudes y órdenes), logística (vehículos, conductores, despacho), dashboard del proveedor y reportes analíticos, conectados a una API fake (json-server) desplegada en Render para simular el flujo completo de negocio.<br><br>
      <em>El Sprint Goal se considerará cumplido cuando los usuarios puedan navegar fluidamente entre todos los módulos implementados y ejecutar simulaciones operativas desde la Web App desplegada.</em>
    </td>
  </tr>
  <tr>
    <td>Sprint 2 Velocity</td>
    <td>15</td>
  </tr>
  <tr>
    <td>Sum of Story Points</td>
    <td>55</td>
  </tr>
</table>

#### 5.2.2.2. Aspect Leaders and Collaborators.

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Team Member</th>
      <th>GitHub Username</th>
      <th>Landing Page</th>
      <th>Documentation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Milenko Rubén Cayanchi Avila</td>
      <td>MaxghZZ</td>
      <td>L</td>
      <td>L</td>
    </tr>
    <tr>
      <td>Jose Gustavo Asto Jacome</td>
      <td>DhudsQ</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Diego Fernando Herrera Enriquez</td>
      <td>DerDFHE</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Alberto Alejandro Ponce Perales</td>
      <td>aponceperales</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Brayan Alexis Corvacho Damian</td>
      <td>BralexCD</td>
      <td>C</td>
      <td>C</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.3.Sprint Backlog 2.

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th colspan="2"><strong>Sprint #</strong></th>
      <th colspan="6"><strong>Sprint 2</strong></th>
    </tr>
    <tr>
      <th colspan="2"><strong>User Story</strong></th>
      <th colspan="6"><strong>Work-Item / Task</strong></th>
    </tr>
    <tr>
      <th><strong>Id</strong></th>
      <th><strong>Title</strong></th>
      <th><strong>Id</strong></th>
      <th><strong>Title</strong></th>
      <th><strong>Description</strong></th>
      <th><strong>Estimation (Hours)</strong></th>
      <th><strong>Assigned to</strong></th>
      <th><strong>Status</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-47</td>
      <td>Ver Dashboard principal del proveedor</td>
      <td>W-01</td>
      <td>Dashboard Principal</td>
      <td>Implementación del dashboard con KPIs de combustible vendido, pedidos pendientes, gráfico de tendencia de ventas con filtro diario/semanal/mensual y navegación directa a módulos operativos.</td>
      <td>6</td>
      <td>Asto Jacome Jose Gustavo</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-46</td>
      <td>Gestionar inventario de combustibles</td>
      <td>W-02</td>
      <td>Módulo Inventory – CRUD de Productos</td>
      <td>CRUD completo de productos de combustible (fuel-product) con formulario de alta/edición y listado. Incluye assembler, API endpoint, store con Angular Signals y vistas product-form y product-inventory.</td>
      <td>6</td>
      <td>Cayanchi Avila Milenko Rubén</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-46</td>
      <td>Gestionar inventario de combustibles</td>
      <td>W-03</td>
      <td>Módulo Inventory – Lista de Stock</td>
      <td>Vista inventory-list que muestra el stock actual por tipo de combustible, con opciones de edición y eliminación de ítems de inventario.</td>
      <td>4</td>
      <td>Cayanchi Avila Milenko Rubén</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-10</td>
      <td>Ver pedidos pendientes</td>
      <td>W-04</td>
      <td>Módulo Ordering – Lista de Solicitudes</td>
      <td>Vista request-list con tabla paginada y ordenable de solicitudes pendientes. Incluye filtro por estado, búsqueda por código y chips de estado visual.</td>
      <td>5</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-05</td>
      <td>Registrar nuevo pedido</td>
      <td>W-05</td>
      <td>Módulo Ordering – Formulario de Solicitud</td>
      <td>Vista request-form con formulario reactivo para registrar una nueva solicitud de combustible. Incluye validación de campos obligatorios y envío al store.</td>
      <td>4</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-11</td>
      <td>Aprobar pedido</td>
      <td>W-06</td>
      <td>Acción Aprobar en request-list</td>
      <td>Implementación de la acción de aprobación de solicitudes desde la vista request-list, actualizando el estado a APPROVED en el store y en la API.</td>
      <td>3</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-42</td>
      <td>Rechazar pedido</td>
      <td>W-07</td>
      <td>Acción Rechazar en request-list</td>
      <td>Implementación del flujo de rechazo de solicitudes con actualización de estado a REJECTED en el store, incluyendo diálogo de confirmación.</td>
      <td>3</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-06</td>
      <td>Consultar estado del pedido</td>
      <td>W-08</td>
      <td>Módulo Ordering – Lista de Órdenes</td>
      <td>Vista order-list con tabla paginada y ordenable de órdenes. Muestra estado actualizado (CREATED, DISPATCHED, CLOSED) con chips visuales y navegación al detalle.</td>
      <td>4</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-43</td>
      <td>Ver detalle de pedido</td>
      <td>W-09</td>
      <td>Módulo Ordering – Detalle de Orden</td>
      <td>Vista order-detail con información completa de la orden: tipo de combustible, cantidad, estado, fechas y datos de asignación. Incluye restricción de acceso a órdenes ajenas.</td>
      <td>4</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-12</td>
      <td>Marcar pedido como despachado</td>
      <td>W-10</td>
      <td>Acción Despachar en order-list</td>
      <td>Acción de cambio de estado de orden a DISPATCHED desde la vista de listado de órdenes, con actualización en store y API.</td>
      <td>2</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-13</td>
      <td>Cerrar pedido</td>
      <td>W-11</td>
      <td>Acción Cerrar en order-list</td>
      <td>Acción de cierre de orden (CLOSED) desde la vista de listado, bloqueando modificaciones posteriores en el store.</td>
      <td>2</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-27</td>
      <td>Buscar pedido por código</td>
      <td>W-12</td>
      <td>Búsqueda por código en request-list</td>
      <td>Campo de búsqueda en la vista request-list que filtra en tiempo real por ID/código de solicitud usando MatInput y Angular Forms.</td>
      <td>2</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-28</td>
      <td>Filtrar pedidos por estado</td>
      <td>W-13</td>
      <td>Filtro por estado en request-list</td>
      <td>Filtrado de solicitudes por estado (PENDING_APPROVAL, APPROVED, REJECTED, CANCELLED) mediante MatChipSet en la vista request-list.</td>
      <td>2</td>
      <td>Ponce Perales Alberto Alejandro</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-44</td>
      <td>Gestionar vehículos de flota</td>
      <td>W-14</td>
      <td>Módulo Fulfillment – Vehículos CRUD</td>
      <td>Vistas vehicle-list y vehicle-form con CRUD completo de vehículos de flota. Incluye validación de placa duplicada y disponibilidad para asignación a pedidos.</td>
      <td>5</td>
      <td>Corvacho Damian Brayan Alexis</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-45</td>
      <td>Gestionar conductores</td>
      <td>W-15</td>
      <td>Módulo Fulfillment – Conductores CRUD</td>
      <td>Vistas driver-list y driver-form con CRUD completo de conductores. Incluye validación de DNI duplicado y control de disponibilidad operativa.</td>
      <td>5</td>
      <td>Corvacho Damian Brayan Alexis</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-22</td>
      <td>Validar disponibilidad de transporte</td>
      <td>W-16</td>
      <td>Módulo Fulfillment – Dispatch Dashboard</td>
      <td>Vista dispatch-dashboard que muestra la disponibilidad en tiempo real de vehículos y conductores, bloqueando selección de recursos con conflictos de agenda.</td>
      <td>4</td>
      <td>Corvacho Damian Brayan Alexis</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-49</td>
      <td>Asignar recursos a despacho</td>
      <td>W-17</td>
      <td>Asignación vehículo+conductor en Dispatch</td>
      <td>Implementación de la asignación conjunta de vehículo y conductor a un pedido aprobado en una sola operación desde dispatch-dashboard, con registro de la entidad delivery.</td>
      <td>4</td>
      <td>Corvacho Damian Brayan Alexis</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-34</td>
      <td>Ver gráfico de ventas (Proveedor)</td>
      <td>W-18</td>
      <td>Reporting – Gráfico de Ventas Mensuales</td>
      <td>Vista supplier-dashboard con gráfico de barras de ventas mensuales usando Chart.js, integrado al reporting store con datos de sales-metrics.</td>
      <td>4</td>
      <td>Asto Jacome Jose Gustavo</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-48</td>
      <td>Ver distribución de ventas por sector</td>
      <td>W-19</td>
      <td>Reporting – Distribución por Sector Industrial</td>
      <td>Sección dentro de supplier-dashboard que muestra la distribución porcentual de ventas por sector industrial (sector-distribution entity) con gráfico analítico.</td>
      <td>3</td>
      <td>Asto Jacome Jose Gustavo</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-31</td>
      <td>Ver listado de empresas</td>
      <td>W-20</td>
      <td>Reporting – Portafolio de Clientes</td>
      <td>Vista client-portfolio con listado interactivo de empresas solicitantes mostrando nombre, pedidos activos e historial total por empresa, usando client-portfolio entity.</td>
      <td>4</td>
      <td>Asto Jacome Jose Gustavo</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-32</td>
      <td>Ver detalles de empresa</td>
      <td>W-21</td>
      <td>Reporting – Detalle de empresa en Portafolio</td>
      <td>Detalle expandible de cada empresa dentro de client-portfolio que muestra historial de pedidos, cantidades y fechas. Mensaje informativo si no hay historial disponible.</td>
      <td>3</td>
      <td>Asto Jacome Jose Gustavo</td>
      <td>Done</td>
    </tr>
    <tr>
      <td>US-09</td>
      <td>Ver historial de pedidos</td>
      <td>W-22</td>
      <td>Historial en order-list (órdenes cerradas)</td>
      <td>Sección de órdenes cerradas en order-list que permite al solicitante consultar el historial con fecha, tipo y estado. Mensaje informativo si no hay pedidos previos.</td>
      <td>2</td>
      <td>Herrera Enriquez Diego Fernando</td>
      <td>Done</td>
    </tr>
  </tbody>
</table>

#### 5.2.2.4.Development Evidence for Sprint Review.

Durante el Sprint 2, el equipo se enfocó en el desarrollo del repositorio frontend del producto FullTank perteneciente a la startup PrimeFuel. La aplicación fue desarrollada utilizando Angular, Angular Material y TypeScript, siguiendo una arquitectura basada en Bounded Contexts y principios de DDD (Domain-Driven Design). Para el consumo de APIs se utilizó HttpClient conectado a un json-server como Fake API, mientras que para la visualización de métricas y reportes se implementaron gráficas utilizando Chart.js. Además, el proyecto incorporó soporte de internacionalización mediante @ngx-translate/core, utilizando archivos de traducción (en.json y es.json) para ofrecer soporte multilenguaje.

<table border> <thead> <tr> <th>Repositorio</th> <th>Rama</th> <th>ID de Commit</th> <th>Mensaje de Commit</th> </tr> </thead> <tbody> <tr> <td>PrimeFuel/frontend</td> <td>develop</td> <td>f815d0c</td> <td>feat(develop): added dashboard page</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>develop</td> <td>271c3e4</td> <td>feat(develop): solved hosting problems</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>develop</td> <td>36bc5a0</td> <td>feat(develop): changed endpoint into the environment one</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/inventory</td> <td>7a7b178</td> <td>feat(inventory): changed catalog to inventory</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/fulfillment</td> <td>97d1ecc</td> <td>feat(fulfillment): implement driver list and form presentation views</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/reporting</td> <td>133904a</td> <td>feat(reporting): connection json server and added statics</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/shared</td> <td>b720b65</td> <td>feat(shared): move notification button from menu to header</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/notification</td> <td>23248bf</td> <td>feat(notification): fix server db.json</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/notification</td> <td>ea54e2d</td> <td>feat(notification): add notification routes and list view</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/shared</td> <td>03fb1e3</td> <td>feat(shared): add button for clients and providers</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/i18n</td> <td>9e04917</td> <td>feat(i18n): add en and es translation files</td> </tr> <tr> <td>PrimeFuel/frontend</td> <td>feature/shared</td> <td>fa80d5d</td> <td>chore(environments): add development and production environment configuration</td> </tr> </tbody> </table>

#### 5.2.2.5.Execution Evidence for Sprint Review.

En este sprint se implementaron las siguientes pantallas y módulos clave:



#### 5.2.2.6.Services Documentation Evidence for Sprint Review.

Durante el Sprint 2 utilizamos un **json-server** expuesto en Render (`https://json-server-y51j.onrender.com`) para habilitar la simulación de todas las pantallas operativas sin depender del equipo backend en java. La implementación real del RESTful Web API con Spring Boot y documentación en Swagger será el objetivo principal de los próximos Sprints.

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.

Resumen:
Se logró el despliegue automático de la aplicación Frontend en la nube utilizando Firebase Hosting. El proyecto está configurado a través del archivo `firebase.json` en el workspace `full-tank-open`.

Detalles del Despliegue:
URL del Frontend App: 

![Frontend Firebase Deployment](../assets/chapter-5/firebase-deploy.png)


#### 5.2.2.8.Team Collaboration Insights during Sprint

<p>
    <strong>Resumen:</strong><br>
    La colaboración se estructuró dividiendo los componentes de Angular según los módulos del negocio:
    <b>Cayanchi Avila Milenko Rubén</b> estructuró las bases del proyecto, layout, router y configuración
    del store con Angular Signals; <b>Asto Jacome Jose Gustavo</b> lideró el módulo de dashboard del
    proveedor y los reportes analíticos (ventas, sector y portafolio de clientes); <b>Corvacho Damian
    Brayan Alexis</b> desarrolló el módulo de fulfillment, incluyendo la gestión de vehículos, conductores
    y el dispatch dashboard; <b>Ponce Perales Alberto Alejandro</b> lideró el módulo de ordering,
    implementando las vistas de solicitudes, órdenes y todas las acciones de estado; <b>Herrera Enriquez
    Diego Fernando</b> colaboró en la integración del historial de órdenes y el soporte transversal
    entre módulos.
</p>
<h4>Evidencia de Colaboración (GitHub Frontend):</h4>
<ul>
  <li>Captura de los Contribuidores del repositorio Frontend en GitHub.</li>
</ul>

![Frontend Contributors](../assets/chapter-5/frontend.png)

<br>

**Conclusiones**

Al finalizar el ciclo de desarrollo y validación de la solución FullTank, el equipo ha llegado a las siguientes conclusiones, contrastando los resultados obtenidos con los planteamientos iniciales del proceso Lean UX:

1. Validación de Problem Statements y Supuestos (Assumptions):

Inicialmente, se estableció como Problem Statement que las empresas que gestionan combustible enfrentan ineficiencias operativas debido a procesos manuales, falta de trazabilidad y poca visibilidad en la cadena de suministro. Tras las pruebas de validación, se confirmó que la digitalización del ciclo de pedidos, junto con el monitoreo en tiempo real, reduce significativamente los errores operativos y mejora la eficiencia logística.

Asimismo, se validó el supuesto de que los usuarios están dispuestos a adoptar soluciones digitales siempre que estas simplifiquen sus procesos y centralicen la información. Sin embargo, el supuesto de que los usuarios priorizaban únicamente el registro de pedidos fue refutado; las pruebas evidenciaron que existe una alta demanda por funcionalidades de seguimiento en tiempo real y notificaciones automáticas, lo que llevó a priorizar estas características dentro del sistema.

2. Contrastación de Hipótesis (Hypothesis Statements):

Hipótesis de Valor para Empresas:
Se planteó que "Si proporcionamos un dashboard centralizado, las empresas podrán optimizar la gestión de combustible y reducir errores en los pedidos". Los resultados de las pruebas de usabilidad confirmaron esta hipótesis, destacando que la visualización consolidada de pedidos, consumos y estados de entrega fue una de las funcionalidades más valoradas por los usuarios.

Hipótesis de Valor para Proveedores:
Se propuso que "Si los proveedores tienen visibilidad de las solicitudes en tiempo real, podrán mejorar sus tiempos de respuesta y coordinación logística". La validación confirmó esta hipótesis, ya que los usuarios destacaron la importancia de recibir notificaciones inmediatas y contar con información actualizada para la toma de decisiones.

No obstante, se identificó que ofrecer únicamente información resumida no es suficiente; los usuarios requieren actualizaciones constantes y trazabilidad detallada de cada pedido, lo que valida la necesidad de integrar monitoreo en tiempo real como una funcionalidad central y no opcional.

**Bibliografia**

- Adzic, G. (s.f.). Impact Mapping. Recuperado de https://www.impactmapping.org/
- Brandolini, A. (s.f.). Introducing EventStorming. Recuperado de https://www.eventstorming.com/
- CareerFoundry. (s.f.). What are User Flows in User Experience (UX) Design?. Recuperado de https://careerfoundry.com/en/blog/ux-design/what-are-user-flows/
- Cohn, M. (s.f.). User Stories. Mountain Goat Software. Recuperado de https://www.mountaingoatsoftware.com/agile/user-stories
- Cone, M. (s.f.). The Markdown Guide. Recuperado de https://www.markdownguide.org/
- Conventional Commits. (s.f.). Conventional Commits. Recuperado de https://www.conventionalcommits.org/
- Cucumber. (s.f.). Gherkin Reference. Recuperado de https://cucumber.io/docs/gherkin/reference/
- Driessen, V. (2010). A successful Git branching model. nvie.com. Recuperado de https://nvie.com/posts/a-successful-git-branching-model/
- DZone. (s.f.). Acceptance Criteria in Scrum: Explanation, Examples, and Template. Recuperado de https://dzone.com/articles/acceptance-criteria-in-software-explanation-exampl
- Evans, E. (2004). Domain-Driven Design: Tackling Complexity in the Heart of Software. Addison-Wesley Professional. Recuperado de https://www.oreilly.com/library/view/domain-driven-design-tackling/0321125215/
- Fowler, M. (2006). Ubiquitous Language. Recuperado de https://martinfowler.com/bliki/UbiquitousLanguage.html
- Google. (s.f.). Google HTML/CSS Style Guide. Recuperado de https://google.github.io/styleguide/htmlcssguide.html
- Google. (s.f.). Google JavaScript Style Guide. Recuperado de https://google.github.io/styleguide/jsguide.html
- Gothelf, J., & Seiden, J. (2021). Lean UX: Designing Great Products with Agile Teams (3rd ed.). O'Reilly Media. Recuperado de https://www.oreilly.com/library/view/lean-ux-2nd/9781491953594/
- HubSpot. (s.f.). Full List of Meta Tags, Why They Matter for SEO & How to Write Them. Recuperado de https://blog.hubspot.com/marketing/meta-tags
- IBM Design. (s.f.). Empathy Map. Enterprise Design Thinking. Recuperado de https://www.ibm.com/design/thinking/page/toolkit/activity/empathy-map
- IBM Design. (s.f.). As-is Scenario Map. Enterprise Design Thinking. Recuperado de https://www.ibm.com/design/thinking/page/toolkit/activity/as-is-scenario-map
- Martin, R. C. (2017). Clean Architecture: A Craftsman's Guide to Software Structure and Design. Prentice Hall. Recuperado de https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/
- Mendel, J. (s.f.). Seriously, what's your (startup's) problem?. Medium. Recuperado de https://medium.com/@jakemendel/seriously-whats-your-startup-s-problem-b3a884c54ab4
- Nielsen Norman Group. (1994). 10 Usability Heuristics for User Interface Design. Recuperado de https://www.nngroup.com/articles/ten-usability-heuristics/
- Nielsen Norman Group. (2016). The Four Dimensions of Tone of Voice. Recuperado de https://www.nngroup.com/articles/tone-of-voice-dimensions/
- Preston-Werner, T. (s.f.). Semantic Versioning 2.0.0. Recuperado de https://semver.org/
- Progressa Lean. (s.f.). 5W+2H - Técnica de análisis de problemas. Recuperado de https://www.progressalean.com/5w2h-tecnica-de-analisis-de-problemas/
- Refactoring.Guru. (s.f.). Design Patterns. Recuperado de https://refactoring.guru/es/design-patterns
- UXPressia. (s.f.). User vs. Buyer Persona: Differences and free template. Recuperado de https://uxpressia.com/blog/user-persona-vs-buyer-persona-difference
- Vernon, V. (2016). Domain-Driven Design Distilled. Addison-Wesley Professional. Recuperado de https://www.oreilly.com/library/view/domain-driven-design-distilled/9780134434964/
- Vernon, V. (s.f.). Domain-Driven Design Reference. Recuperado de https://domainlanguage.com/ddd/reference/

Anexos:

**Videos de Exposiciones:**
- **TB1:** [Enlace al video de la exposición del TB1 (Reemplazar con enlace real)](#)

Link del repositorio del informe: https://github.com/PrimeFuel/Prime_Fuel_Document

Link del repositorio de la Landing Page:
https://github.com/PrimeFuel/FullTank_LandingPage

Link del repositorio del fronted:
https://github.com/PrimeFuel/frontend

Link del repositorio del backend:
https://github.com/PrimeFuel/backend

Link de los repositorios de la organización: https://github.com/PrimeFuel


Link del figma: https://www.figma.com/design/ZMHB35H60u2eUhctevkVKc/Fullank-Completo?node-id=0-1&t=I3nr2x0tcAinM7gE-1

URL de la Landing Page: https://primefuel.github.io/FullTank_LandingPage/

