<div align="center" style="margin-top: -5px;">


## Universidad Peruana de Ciencias Aplicadas

<img src="assets/UPC_logo_transparente.png"
     alt="Logo UPC"
     style="width: 28%; height: auto; margin-bottom: -40px;">
  



### INFORME DE TRABAJO FINAL 

**Arquitecturas De Software Emergentes – NRC: 11821**

**Carrera de Ingeniería de Software** 


**Docente: Christian Luis De Los Rios Fernandez** 

**Nombre del startup: TechProtection** 

**Nombre del producto: GeoEntry**


| Integrante                              | Código       |
|-----------------------------------------|--------------|
| Agama Espinoza, Eric Fabrizio       |  U202213358  |
|  López Huamán, Rodrigo Adrián        |  U202212338  |
|   Salon Puerta, Merly            | U20201b772   |
| Vera Nuñez, Nicolas Alejandro            | U202214869   |
|  Salvador Rodríguez, Rodrigo Jesús   |  U202213646   |

<div align="center"><h3>Abril 2026</h3></div><br>

</div>

---

### Registro de Versiones

<section class="version-section">
  <h2>Historial de Versiones</h2>

  <table>
    <thead>
      <tr>
        <th>Versión</th>
        <th>Fecha</th>
        <th>Autor</th>
        <th>Descripción de la modificación</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1.1</td>
        <td>18/04/2026</td>
        <td>TechProtection</td>
        <td>Capítulo I</td>
      </tr>
      <tr>
        <td>1.2</td>
        <td>19/04/2026</td>
        <td>TechProtection</td>
        <td>Capítulo II</td>
      </tr>
      <tr>
        <td>1.3</td>
        <td>22/04/2026</td>
        <td>TechProtection</td>
        <td>Capítulo III</td>
      </tr>
      <tr>
        <td>1.4</td>
        <td>24/04/2026</td>
        <td>TechProtection</td>
        <td>Capítulo IV</td>
      </tr>
    </tbody>
  </table>
</section>

### Report Collaboration Insights

### Contenido
Tabla de contenidos


### Student Outcome 

### Capítulo I: Introducción

#### 1.1 Startup Profile

#### 1.1.1. Descripción de la Startup

La startup TechProtection surge con el objetivo de transformar la interacción entre las personas y sus espacios mediante el uso de tecnologías emergentes como el Internet de las Cosas (IoT) y la Inteligencia Artificial (IA). En un contexto donde los sistemas de automatización del hogar aún presentan altos niveles de fragmentación y requieren intervención manual constante, TechProtection propone una solución integral, inteligente y adaptativa.

El producto principal, GeoEntry, es un sistema de automatización inteligente que permite gestionar dispositivos del hogar como cerraduras electrónicas, sistemas de iluminación y climatización de manera automática y personalizada. A través del uso de dispositivos basados en ESP32 y sensores, el sistema detecta la proximidad del usuario y ejecuta acciones en tiempo real.

A diferencia de soluciones tradicionales, GeoEntry incorpora algoritmos de aprendizaje que analizan patrones de comportamiento del usuario, permitiendo anticipar sus necesidades y automatizar acciones sin intervención manual. De esta manera, el sistema no solo reacciona, sino que aprende y se adapta continuamente, optimizando la experiencia del usuario y promoviendo la eficiencia energética.

La propuesta de valor de TechProtection se centra en ofrecer un entorno inteligente capaz de adaptarse dinámicamente a los hábitos del usuario, brindando comodidad, seguridad y control en un solo ecosistema integrado.

Misión:
Desarrollar soluciones inteligentes basadas en IoT e Inteligencia Artificial que automaticen y optimicen la interacción de las personas con sus espacios, mejorando su calidad de vida.

Visión:
 Convertirse en una startup líder en soluciones de automatización inteligente en Latinoamérica, destacando por su innovación, adaptabilidad y enfoque centrado en el usuario.

#### 1.1.2. Perfiles de integrantes del equipo

<section class="team-section">
  <h2>Miembros</h2>

  <table>
    <thead>
      <tr>
        <th>Miembros</th>
        <th>Código estudiante</th>
        <th>Carrera</th>
        <th>Descripción</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Eric Agama Espinoza</td>
        <td>u202213358</td>
        <td>Ingeniería de Software</td>
        <td></td>
      </tr>
      <tr>
        <td>Merly Salon Puerta</td>
        <td>u20201b772</td>
        <td>Ingeniería de Software</td>
        <td>
          Mi nombre es Merly Salon, estudiante de Ingeniería de Software. Me considero una persona entusiasta.
          Pienso que todo lo que nos proponemos, se puede lograr con esfuerzo, constancia y disciplina.
          Lo que más me gusta de la ingeniería de software es que puedes crear soluciones tecnológicas
          que impacten positivamente en la sociedad.
        </td>
      </tr>
      <tr>
        <td>Nicolas Alejandro Vera Nuñez</td>
        <td>u202214869</td>
        <td>Ingeniería de Software</td>
        <td>
          Mi nombre es Nicolas Vera, estudiante de Ingeniería de Software, tengo 22 años y me considero
          una persona disciplinada y enfocada en alcanzar mis objetivos. En el área de Ingeniería de Software,
          me interesa el desarrollo de aplicaciones, el diseño de soluciones tecnológicas y el aprendizaje
          continuo de nuevas herramientas y metodologías, lo que me permite fortalecer mis habilidades y
          crecer profesionalmente en este campo.
        </td>
      </tr>
    </tbody>
  </table>
</section>

#### 1.2. Solution Profile

#### 1.2.1 Antecedentes y problemática

En la actualidad, el crecimiento de los hogares inteligentes ha generado un incremento en el uso de dispositivos conectados como luces, cerraduras electrónicas, sensores y sistemas de climatización. Sin embargo, a pesar de estos avances tecnológicos, persisten problemas importantes que limitan su adopción y efectividad.
Uno de los principales problemas es la fragmentación del ecosistema, donde los dispositivos funcionan de manera independiente y requieren múltiples aplicaciones para su control. Esto genera una experiencia poco fluida y aumenta la complejidad para el usuario.
Además, los sistemas actuales dependen en gran medida de la interacción manual, ya sea mediante aplicaciones móviles o comandos de voz, lo que reduce la comodidad y eficiencia que debería caracterizar a un hogar inteligente.
Otro problema relevante es la falta de inteligencia adaptativa, ya que la mayoría de los sistemas no aprenden del comportamiento del usuario ni anticipan sus necesidades, limitándose a ejecutar acciones preconfiguradas.

Como consecuencia, los usuarios enfrentan:
- Procesos repetitivos y poco eficientes
- Falta de personalización real
- Bajo aprovechamiento del potencial de automatización
- Consumo energético innecesario

Frente a este contexto, surge la necesidad de desarrollar una solución que no solo automatice tareas, sino que sea capaz de aprender, predecir y adaptarse al comportamiento del usuario, integrando múltiples dispositivos en un sistema único e inteligente.

#### 1.2. Lean UX Process.


#### 1.2.2.1.      Lean UX Problem Statements.

El propósito de GeoEntry es ofrecer una experiencia de automatización inteligente que reduzca la intervención manual del usuario y optimice la gestión del hogar mediante el uso de IoT e Inteligencia Artificial.

El problema actual radica en que los sistemas de domótica existentes presentan fragmentación, baja integración y ausencia de aprendizaje adaptativo, lo que obliga a los usuarios a configurar manualmente sus dispositivos y limita la personalización de la experiencia.

¿Cómo podríamos desarrollar un sistema de automatización del hogar que integre múltiples dispositivos y sea capaz de aprender del comportamiento del usuario para anticipar sus necesidades sin intervención manual?


#### 1.2.2.2. Lean UX Assumptions.

Business Assumptions

- Creemos que los usuarios valoran la automatización inteligente que reduzca la interacción manual.
- Creemos que la integración de múltiples dispositivos en una sola plataforma mejora la experiencia del usuario.
- Creemos que la incorporación de Inteligencia Artificial generará un valor diferencial frente a soluciones tradicionales.
- Creemos que los usuarios estarán dispuestos a invertir en soluciones que mejoren su comodidad, seguridad y eficiencia energética.
- Creemos que el modelo de negocio puede basarse en venta de hardware + servicios inteligentes.

User Assumptions
- Los usuarios desean simplificar la gestión de sus dispositivos inteligentes.
- Los usuarios prefieren sistemas automáticos en lugar de control manual constante.
- Los usuarios valoran la personalización basada en sus hábitos.
- Los usuarios tienen preocupaciones sobre complejidad, seguridad y compatibilidad.

Feature Assumptions
- El sistema debe detectar la proximidad del usuario.
- Debe automatizar dispositivos en tiempo real.
- Debe aprender patrones de comportamiento.
- Debe permitir personalización de escenarios.
- Debe ser fácil de configurar y usar. 


#### 1.2.2.3. Lean UX Hypothesis Statements.

**Hypothesis Statement 1:**

Creemos que los usuarios interesados en hogares inteligentes (jóvenes profesionales, familias tecnológicas o personas con rutinas definidas) estarán dispuestos a adoptar GeoEntry para automatizar su hogar mediante la integración de dispositivos IoT y detección de proximidad en tiempo real.

Sabremos que hemos tenido éxito
 Cuando al menos el 70% de los usuarios registrados configuren y utilicen al menos una automatización basada en proximidad dentro de los primeros 30 días de uso.


**Hypothesis Statement 2:**

Creemos que la incorporación de Inteligencia Artificial en GeoEntry permitirá a los usuarios reducir la necesidad de interacción manual, al automatizar acciones basadas en el aprendizaje de sus hábitos y patrones de comportamiento.

Sabremos que hemos tenido éxito
 Cuando al menos el 60% de las acciones ejecutadas por el sistema se realicen de forma automática sin intervención directa del usuario durante el primer mes de uso.


**Hypothesis Statement 3:**

Creemos que los usuarios valorarán la personalización inteligente del sistema, basada en el análisis de sus horarios y preferencias, lo que mejorará su experiencia dentro del hogar.

Sabremos que hemos tenido éxito
 Cuando al menos el 65% de los usuarios interactúen semanalmente con las configuraciones o recomendaciones del sistema para ajustar sus automatizaciones.

**Hypothesis Statement 4:**

Creemos que una interfaz intuitiva y fácil de usar facilitará la adopción de GeoEntry, incluso en usuarios sin experiencia previa en domótica.

Sabremos que hemos tenido éxito
 Cuando al menos el 85% de los usuarios completen correctamente la configuración inicial del sistema y el índice de abandono en la primera semana sea menor al 15%.


#### 1.2.2.4. Lean UX Canvas.

#### 1.3. Segmentos objetivo.

El sistema GeoEntry está dirigido a usuarios que buscan mejorar la gestión de sus espacios mediante automatización inteligente basada en IoT e Inteligencia Artificial. Se identifican dos segmentos principales:

#### 1.3.1. Usuarios residenciales

Este segmento incluye a jóvenes profesionales y familias con interés en hogares inteligentes. Son usuarios que valoran la comodidad, la seguridad y la eficiencia energética, pero que actualmente enfrentan problemas como la fragmentación de dispositivos y la necesidad de interacción manual constante.

GeoEntry les permite integrar y automatizar sus dispositivos en una sola plataforma, incorporando inteligencia artificial para aprender de sus hábitos y anticipar acciones, mejorando así su experiencia diaria.


#### 1.3.2. Negocios

Este segmento está conformado por negocios como hoteles boutique, coworking y espacios de bienestar, que buscan mejorar la experiencia de sus clientes mediante automatización.

GeoEntry les permite optimizar procesos como el acceso, la iluminación y la climatización, además de ofrecer personalización basada en el comportamiento del usuario, generando valor agregado y diferenciación en el mercado.


### Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores
### 2.1.1 Análisis competitivo

Se realiza este análisis con el propósito de comprender el alcance de la solución propuesta y su posicionamiento frente a alternativas existentes, así como evaluar cómo la integración de tecnologías como IoT e Inteligencia Artificial en GeoEntry aporta valor diferencial en la automatización del hogar y en la optimización de la experiencia del usuario.

<h2>Análisis del Panorama Competitivo</h1>

<h2>Tabla Comparativa</h2>

<table class="competitive-analysis-table">
  <thead>
    <tr>
      <th colspan="2">Nombre de los Startups o Empresas</th>
      <th>GeoEntry</th>
      <th>Google Nest</th>
      <th>Samsung SmartThings</th>
      <th>Control4 (Snap One)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" class="category-header">Perfil</td>
      <td>Overview</td>
      <td>GeoEntry utiliza sensores IoT que detectan cuando una persona ingresa a un espacio y activa automáticamente configuraciones personalizadas de iluminación, temperatura y seguridad. Intuitiva y fácil de instalar.</td>
      <td>Plataforma consolidada con dispositivos propios y compatibilidad con muchos productos de terceros. Usa aprendizaje automático para adaptarse a los hábitos del usuario.</td>
      <td>Ecosistema abierto y compatible con múltiples marcas. Su hub centraliza el control de dispositivos conectados y permite automatizaciones basadas en ubicación.</td>
      <td>Sistema profesional de alta gama con instalación profesional. Ofrece soluciones totalmente personalizadas para hogares de lujo y empresas con necesidades complejas.</td>
    </tr>
    <tr>
      <td>Ventaja competitiva<br>¿Qué valor ofrece a los clientes?</td>
      <td>Experiencia inmersiva completa al entrar al espacio sin necesidad de comandos. Solución modular y escalable que no requiere cambiar toda la infraestructura existente. Equilibrio entre facilidad de uso y personalización avanzada.</td>
      <td>Integración perfecta con el ecosistema Google, excelente reconocimiento de patrones y aprendizaje del comportamiento del usuario. Actualizaciones constantes y soporte a largo plazo.</td>
      <td>Gran compatibilidad con dispositivos de diferentes fabricantes. Precio más accesible y opciones de automatización basadas en la ubicación del usuario a través del smartphone.</td>
      <td>Soluciones completamente personalizadas de alto nivel con soporte profesional. Experiencia premium para clientes dispuestos a invertir en sistemas sofisticados.</td>
    </tr>
    <tr>
      <td rowspan="2" class="category-header">Perfil de Marketing</td>
      <td>Mercado objetivo</td>
      <td>Hogares de clase media-alta interesados en domótica y negocios pequeños-medianos (hoteles boutique, oficinas modernas, spas, estudios de yoga, coworkings) que buscan diferenciarse con experiencias personalizadas.</td>
      <td>Propietarios de viviendas con cierto poder adquisitivo, familias interesadas en seguridad y comodidad, usuarios ya integrados en el ecosistema Google.</td>
      <td>Propietarios e inquilinos con presupuesto más ajustado, usuarios que valoran la flexibilidad y quieren centralizar dispositivos de diferentes marcas.</td>
      <td>Propietarios de viviendas de lujo, hotelería premium, salas de conferencias corporativas y negocios exclusivos.</td>
    </tr>
    <tr>
      <td>Estrategias de marketing</td>
      <td>Contenido educativo, alianzas con diseñadores de interiores y arquitectos, demostraciones experienciales en showrooms de smart homes y ferias tecnológicas.</td>
      <td>Publicidad masiva, presencia en tiendas como Best Buy, promoción cruzada con otros productos Google, programa Works with Nest para desarrolladores.</td>
      <td>Partnerships con múltiples fabricantes, precio competitivo, comunidad activa de usuarios que comparten automatizaciones.</td>
      <td>Marketing exclusivo, presencia en ferias de construcción de lujo, alianzas con constructores y diseñadores de élite.</td>
    </tr>
    <tr>
      <td rowspan="3" class="category-header">Perfil de Producto</td>
      <td>Productos & Servicios</td>
      <td>Hardware: sensores de presencia, hub central, accesorios de conexión. Software: app móvil para configuración, plataforma cloud, APIs para integración. Servicios: asesoría de instalación, mantenimiento y actualizaciones.</td>
      <td>Línea completa de dispositivos smart home, servicio de almacenamiento en la nube Nest Aware, soporte técnico, actualizaciones regulares de software.</td>
      <td>Hub SmartThings, sensores variados, app móvil, plataforma cloud, marketplace de aplicaciones y servicios, comunidad para compartir automatizaciones.</td>
      <td>Sistema Control4 completo con componentes propios, servicios de diseño e instalación profesional, mantenimiento premium, actualizaciones y personalizaciones exclusivas.</td>
    </tr>
    <tr>
      <td>Precios & Costos</td>
      <td>Kit básico hogar: $249 (hub + 2 sensores). Kit negocio: $599 (hub + 5 sensores + software analítico). Sensores adicionales: $49/unidad. Suscripción opcional: $5.99/mes (análisis avanzado y backup).</td>
      <td>Termostato Nest: $249. Cámara Nest: $199-299. Timbre Nest: $229. Suscripción Nest Aware: $6-12/mes. Sin costos de instalación profesional obligatoria.</td>
      <td>Hub: $99. Sensores entre $20-60. Sin costos de suscripción obligatoria. Compatible con dispositivos económicos de diferentes marcas. </td>
      <td>Sistemas desde $5,000 hasta $50,000+ dependiendo de la complejidad. Instalación profesional obligatoria ($1,000+). Suscripción anual de mantenimiento recomendada.</td>
    </tr>
    <tr>
      <td>Canales de distribución(Web y/o Móvil)</td>
      <td>Web propia con e-commerce, Amazon, tiendas especializadas en smart home, alianzas con integradores de domótica, app móvil (iOS/Android) y aplicación web para gestión.</td>
      <td>Google Store, Amazon, Best Buy, Home Depot, instaladores autorizados. Control mediante app Nest/Google Home (iOS/Android).</td>
      <td>Tienda online propia, Amazon, Best Buy, Walmart. Control mediante app SmartThings (iOS/Android). </td>
      <td>Exclusivamente a través de distribuidores e instaladores autorizados. Venta consultiva con demostración previa. Control mediante app Control4 (iOS/Android) y paneles táctiles instalados.</td>
    </tr>
    <tr>
      <td rowspan="4" class="category-header">Análisis SWOT</td>
      <td>Fortalezas</td>
      <td> 1. Experiencia inmersiva "manos libres" sin necesidad de comandos. <br>2. Sistema modular y escalable. <br>3. Equilibrio entre facilidad de uso y personalización. <br>4. Compatible con múltiples ecosistemas existentes. <br>5. Precio competitivo para el valor ofrecido.</td>
      <td>1. Marca reconocida y respaldo de Google. <br>2. Productos de alta calidad y diseño atractivo. <br>3. Fuerte integración con asistentes virtuales. <br>4. Constantes actualizaciones y mejoras. <br>5. Amplia red de distribución.</td>
      <td>1. Gran compatibilidad con diferentes marcas. <br>2. Comunidad activa de usuarios. <br>3. Precios accesibles. <br>4. Plataforma abierta para desarrolladores. <br>5. Respaldo de Samsung.</td>
      <td>1. Calidad premium. <br>2. Personalización total. <br>3. Soluciones a medida para hogares y negocios. <br>4. Servicio completo (diseño, instalación, mantenimiento). <br>5. Experiencia en proyectos complejos.</td>
    </tr>
    <tr>
      <td>Debilidades</td>
      <td>1. Marca nueva sin reconocimiento en el mercado. <br>2. Red de distribución limitada. <br>3. Dependencia de fabricantes de dispositivos para integraciones. <br>4.  Equipo más pequeño que las grandes corporaciones.</td>
      <td>1. Precios elevados. <br>2.  Ecosistema cerrado que prioriza productos Google. <br>3. Necesidad de conexión a internet constante. <br>4.  Preocupaciones de privacidad por recopilación de datos.</td>
      <td>1. Experiencia de usuario menos pulida. <br>2.  Algunas automatizaciones requieren conocimientos técnicos. <br>3.  Menor reconocimiento de marca que Google. <br>4.  Soporte técnico limitado. </td>
      <td>1. Precios muy elevados. <br>2.  Instalación profesional obligatoria. <br>3. Dependencia del instalador para cambios. <br>- Menor flexibilidad para actualizaciones DIY <br>- Curva de aprendizaje pronunciada.</td>
    </tr>
    <tr>
      <td>Oportunidades</td>
      <td>1. Crecimiento del mercado de smart home y IoT. <br>2.  Aumento de conciencia sobre eficiencia energética <br>3.  Interés creciente en experiencias personalizadas <br>4.  Potencial para expandirse al sector hotelero y hospitalidad.</td>
      <td>1. Expansión del ecosistema Google Home. <br>2.  Integración con nuevos electrodomésticos inteligentes <br>3.  Alianzas con constructoras para instalaciones en nuevas viviendas <br>4.  Desarrollo de IA más avanzada.</td>
      <td>1. Crecimiento del mercado de dispositivos compatibles. <br>2.  Potencial para convertirse en el estándar de interoperabilidad <br>3.  Expansión internacional <br>4.  Nuevos acuerdos con fabricantes. </td>
      <td>1. Aumento de construcciones de lujo. <br>2.  Crecimiento del segmento de hoteles boutique <br>3.  Expansión a oficinas corporativas premium <br>4. Internacionalización a mercados emergentes de lujo.</td>
    </tr>
    <tr>
      <td>Amenazas</td>
      <td>1. Entrada de grandes tecnológicas al mismo nicho. <br>2.  Cambios en estándares de conectividad. <br>3. Preocupaciones sobre privacidad y seguridad. <br>4. Recesión económica que afecte el gasto en tecnología.</td>
      <td>1. Competencia creciente de Amazon y Apple. <br>2. Regulaciones de privacidad más estrictas. <br>3. Saturación del mercado premium. <br>4. Vulnerabilidades de seguridad.</td>
      <td>1. Posible consolidación del mercado. <br>2.  Competencia de soluciones propietarias más integradas. <br>3.  Cambios en la estrategia de Samsung. <br>4.  Problemas de compatibilidad con actualizaciones de terceros. </td>
      <td>1. Soluciones DIY cada vez más sofisticadas. <br>2.  Disminución en la demanda de instalaciones profesionales. <br>3.  Competencia de sistemas modulares más accesibles. <br>4. Cambios generacionales en preferencias de consumo.</td>
    </tr>
  </tbody>
</table>

### 2.1.2 Estrategias y tácticas frente a competidores

| Competidores | ¿Qué se puede hacer para ganarle a la competencia? |
| --- | --- |
| Competidor 1: Google Nest | - Ofrecer una experiencia "manos libres" completamente automática, sin necesidad de comandos manuales. <br> - Posicionarse como la opción con mejor relación valor-precio en el segmento medio-alto, superando la oferta de Nest en accesibilidad y facilidad de uso. <br> - Desarrollar soluciones modulares que permitan a los usuarios comenzar con una inversión más baja y escalar gradualmente. <br> - Establecer alianzas estratégicas con arquitectos, diseñadores de interiores y constructoras para aumentar la visibilidad y el alcance en proyectos de viviendas inteligentes. |
| Competidor 2: SmartThings (Samsung) |  - Simplificar la instalación y gestión para hacerla accesible a usuarios menos técnicos, ofreciendo una experiencia intuitiva y sin fricciones. <br> - Mejorar la integración con dispositivos existentes para que los usuarios no necesiten reemplazar toda su infraestructura de hogar inteligente. <br> - Enfocar más en la personalización para negocios, como hoteles boutique y espacios comerciales, agregando valor a esos segmentos con características específicas. <br> - Fomentar una comunidad activa de usuarios que compartan configuraciones personalizadas y escenas para aumentar el valor de la plataforma a medida que crece. |
| Competidor 3: Control4 (Snap One) |  - Proporcionar una opción más accesible, enfocándose en la facilidad de uso y la reducción de la necesidad de instalación profesional obligatoria. <br> - Ofrecer precios más competitivos en comparación con Control4, haciendo que la tecnología avanzada sea más accesible para un público más amplio. <br> - Desarrollar un sistema modular que permita a los usuarios comenzar con una inversión pequeña y aumentar la escala a medida que se familiarizan con el sistema. <br> - Desarrollar propiedad intelectual alrededor de sus algoritmos de detección y personalización para proteger la tecnología y mantener una ventaja competitiva.|

## 2.2 Entrevistas

En la presente sección del informe se desarrollará el diseño, registro y análisis de las entrevistas dirigidas a los segmentos objetivo previamente identificados, con el fin de validar la pertinencia de la solución tecnológica propuesta.

### 2.2.1 Diseño de entrevistas

Se han identificado los siguientes segmentos:
  - Usuarios residenciales con tecnología inteligente en el hogar.
  - Negocios interesados en implementar experiencias de bienvenida automatizadas.
<br>

Antes de llevar a cabo las entrevistas, se consideró necesario realizar un análisis preliminar orientado a comprender el contexto de uso de tecnologías de automatización, así como las principales limitaciones y expectativas de los usuarios frente a este tipo de soluciones.<br>
Este enfoque permitió estructurar adecuadamente el proceso de levantamiento de información, facilitando la formulación de preguntas alineadas con los componentes clave de GeoEntry, tales como la automatización basada en proximidad, la integración de dispositivos IoT y el uso de Inteligencia Artificial para el aprendizaje de patrones de comportamiento.<br>
En ese sentido, se elaboraron preguntas específicas para cada segmento con el propósito de identificar necesidades, problemáticas y percepciones relacionadas con el control de accesos, la personalización de entornos y la eficiencia en la gestión energética, aspectos fundamentales que la solución GeoEntry busca optimizar.<br>

#### Segmento: Hogares inteligentes (usuarios residenciales)
#### Principales:
1. **Introducción al Contexto**: ¿Podría describir qué tecnologías inteligentes tiene actualmente en su hogar y cómo las utiliza en su día a día?
2. **Experiencia Actual**: ¿Cómo es su experiencia al llegar a casa? ¿Qué acciones debe realizar manualmente que le gustaría automatizar?
3. **Desafíos y Frustraciones**: ¿Cuáles son los mayores inconvenientes o frustraciones que experimenta con la tecnología existente en su hogar?
4. **Prioridades y Valores**: ¿Qué aspectos valora más en su hogar: la comodidad, la seguridad, la eficiencia energética o la personalización del ambiente?
5. **Experiencias Previas**: ¿Ha intentado implementar algún sistema de automatización anteriormente? ¿Cuál fue su experiencia?
6. **Interacción Preferida**: ¿Prefiere controlar sus dispositivos mediante comandos de voz, aplicaciones móviles, o le gustaría que funcionaran automáticamente sin intervención?
7. **Preocupaciones**: ¿Qué preocupaciones tiene respecto a implementar más tecnologías inteligentes en su hogar (privacidad, complejidad, costo, etc.)?
8. **Disposición a Invertir**: ¿Qué presupuesto consideraría razonable para implementar un sistema que automatice su experiencia al llegar a casa?
9. **Expectativas de Resultados**: ¿Cómo imagina que sería la experiencia ideal al llegar a su hogar si pudiera personalizarla completamente?
10. **Decisión de Compra**: ¿Qué factores serían determinantes para que usted decidiera invertir en un nuevo sistema de automatización para su hogar?

<br>

#### Segmento: Negocios que buscan experiencias de bienvenida automatizadas
#### Principales:
1. **Contexto del Negocio**: ¿Podría describir su negocio y cómo es actualmente la experiencia de sus clientes o empleados al ingresar a su establecimiento?
2. **Objetivos de Experiencia**: ¿Qué tipo de primera impresión o experiencia de bienvenida le gustaría crear para las personas que ingresan a su establecimiento?
3. **Desafíos Actuales**: ¿Qué problemas o limitaciones enfrenta actualmente para ofrecer una experiencia de bienvenida personalizada y consistente?
4. **Tecnología Existente**: ¿Qué tecnologías o sistemas de automatización utiliza actualmente en su negocio? ¿Cuáles han sido sus resultados?
5. **Diferenciación Competitiva**: ¿Cómo cree que una experiencia de bienvenida automatizada podría ayudarle a diferenciarse de sus competidores?
6. **Impacto en Clientes**: ¿Qué tipo de comentarios o retroalimentación ha recibido de sus clientes respecto a la experiencia de entrada a su establecimiento?
7. **Expectativas de ROI**: ¿Qué retorno de inversión esperaría de implementar un sistema de bienvenida automatizado en términos de satisfacción del cliente, eficiencia operativa o ahorro energético?
8. **Presupuesto y Recursos**: ¿Qué presupuesto consideraría razonable para implementar una solución de este tipo? ¿Cuenta con personal que podría gestionar esta tecnología?
9. **Personalización y Control**: ¿Qué nivel de personalización y control necesitaría sobre las experiencias automatizadas para diferentes tipos de clientes o momentos del día?
10. **Factores de Decisión**: ¿Qué aspectos serían determinantes para que usted decidiera implementar una solución de bienvenida automatizada en su negocio (facilidad de uso, escalabilidad, compatibilidad con sistemas existentes, etc.)?

<br>

### 2.2.2 Registro de entrevistas
A continuación se presentan los resúmenes de las entrevistas realizadas a representantes de nuestros dos segmentos objetivo.<br>

#### Segmento 1: Hogares inteligentes (usuarios residenciales)

| Entrevista 1 | Alejandro Barturen |
|------------------|----------------------|
| Edad         | 21 años              |
| Distrito     | San Miguel          |
| <img src="assets/entrevistado1.png"/>  | - Resumen: <br> Cuenta con un ecosistema básico de hogar inteligente (luces y termostato inteligentes, cerradura inteligente). Busca principalmente automatizar el proceso de llegada a casa, eliminando la necesidad de buscar llaves, encender luces manualmente y ajustar la temperatura. Su principal frustración es la fragmentación de los sistemas que requieren múltiples aplicaciones. Valora la comodidad como prioridad principal, seguida de la eficiencia energética. Ha experimentado con automatizaciones básicas mediante IFTTT, pero las abandonó por la dificultad de adaptarlas a horarios variables. Prefiere soluciones que funcionen automáticamente según su ubicación y horarios, sin necesidad de comandos o aplicaciones. Expresa preocupaciones sobre privacidad y obsolescencia tecnológica. Dispuesto a invertir entre $500-700 inicialmente en un sistema que realmente funcione. Los factores determinantes para su decisión incluyen facilidad de instalación, compatibilidad con dispositivos existentes, confiabilidad y buen soporte técnico.|
| URL | [Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212191_upc_edu_pe/EWaFGrpWV4xApxird8jnfNIBsRNl3LYrlh1bVEhv8_Q5Mg?e=9x7JxC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
<br>

| Entrevista 2 |  Steven Liu Li |
|------------------|----------------------|
| Edad         | 24 años              |
| Distrito     | San Miguel          |
| <img src="assets/entrevistado2.png"/>  | - Resumen: <br> Posee un sistema más orientado a la seguridad (cámaras conectadas, enchufes inteligentes y cortinas automáticas). Desea automatizar la desactivación del sistema de alarma, el encendido de luces y ajuste de temperatura al llegar a casa. Su principal frustración es la falta de integración entre dispositivos de diferentes marcas. Prioriza la seguridad sobre la comodidad, con especial interés en el monitoreo remoto. Ha expandido gradualmente su sistema mediante prueba y error. Prefiere una combinación de automatización basada en ubicación y control manual desde el teléfono. Sus principales preocupaciones incluyen la seguridad informática de los dispositivos y la resiliencia del sistema ante fallas eléctricas. Considera una inversión de $800-1000 para un sistema integral. Valora especialmente la seguridad informática, compatibilidad con dispositivos existentes y un buen soporte técnico.|
| URL | [Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212191_upc_edu_pe/EchLT4C3VYFEh-IPtMOirHgBedGcVkTbePxXf29lP59Dhg?e=5IuhUW&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
<br>

| Entrevista 3 |  Harold Mayta |
|------------------|----------------------|
| Edad         | 21 años              |
| Distrito     | Lince          |
| <img src="assets/entrevistado3.png"/>  | - Resumen: <br> Principiante en domótica con experiencia limitada a bombillas y parlantes inteligentes. Busca simplificar su rutina de llegada a casa, especialmente cuando tiene las manos ocupadas. Su principal desafío es no saber por dónde empezar ante las abrumadoras opciones del mercado. Valora la simplicidad y buena relación calidad-precio sobre características avanzadas. Ha encontrado complicada la configuración de rutinas automatizadas. Prefiere un equilibrio entre funciones automáticas y comandos de voz simples. Le preocupa principalmente la complejidad de instalación y configuración, así como la potencial obsolescencia. Dispuesto a realizar una inversión inicial modesta de $300-400 como prueba. Los factores decisivos incluyen facilidad de instalación y configuración, escalabilidad, y buen soporte para principiantes. |
| URL | [Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212191_upc_edu_pe/Ef1mZmoe1IhPqK2f1KDjgCcBLt2oHTY96O9FZXKflCoC6Q?e=ivDzYC&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
<br>

#### Segmento 2: Negocios que buscan experiencias de bienvenida automatizadas

| Entrevista 4 |  Jose Cuevas Vera |
|------------------|----------------------|
| Negocio         | Hotel boutique (15 habitaciones)              |
| Cargo     | Dueño y Gestor          |
| <img src="assets/entrevistado4.png"/>  | - Resumen: <br> Gestiona un hotel boutique donde la experiencia de llegada es tradicional, con check-in manual y llaves físicas. Desea crear una experiencia más personalizada con ajustes automáticos de ambiente y notificaciones para el personal con información relevante sobre cada huésped. Su principal desafío es la inconsistencia en la experiencia según el personal en turno. Cuenta con sistemas digitales de gestión hotelera, cerraduras con tarjeta y sonido centralizado, pero sin integración entre ellos. Ve en la automatización un diferenciador importante en su segmento de mercado. Los clientes han sugerido mejorar la eficiencia del check-in y personalización. Espera como retorno aumento en valoraciones positivas, mayor fidelización y ahorro energético. Dispuesto a invertir entre $5,000-8,000, con personal técnico básico para gestionar el sistema. Necesita flexibilidad para personalizar la experiencia según distintos perfiles de huéspedes. Los factores determinantes incluyen facilidad de integración con sistemas existentes, simplicidad de uso para el personal y buen soporte técnico. |
| URL | [Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212191_upc_edu_pe/EYDUf-6A7vtLoOxfVTENShABHeXudaaxe8F-KvkZjX5-Ew?e=EKU2Lq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
<br>

| Entrevista 5 |  Nicolas Alejandro Vera |
|------------------|----------------------|
| Negocio         | Estudio de yoga y bienestar             |
| Cargo     | Dueño y Administrador          |
| <img src="assets/entrevistado5.png"/>  | - Resumen: <br> Dirige un estudio de yoga con tres salas diferentes donde el registro es manual y los ajustes de ambiente se realizan manualmente entre clases. Busca crear un ambiente más fluido donde los clientes frecuentes sean reconocidos automáticamente y dirigidos a salas ya configuradas según el tipo de clase. Su principal desafío es la transición entre clases y el registro de asistencia sin interrumpir la tranquilidad del espacio. Dispone de un sistema básico de reservas online y controles independientes no automatizados para iluminación y sonido. Ve la automatización como un diferenciador para posicionarse como estudio premium. Ha recibido algunas quejas sobre tiempos de espera en registro y configuraciones inadecuadas de salas. Espera mejorar la retención de clientes y reducir la carga administrativa. Con un presupuesto de $3,000-5,000 como pequeño negocio, necesita una solución intuitiva con buen soporte. Requiere poder configurar ambientaciones predefinidas para diferentes tipos de clases. Valora especialmente la simplicidad de uso, confiabilidad incluso sin internet, y estética discreta de los dispositivos. |
| URL | [Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212191_upc_edu_pe/EeXl6Ym9kc5LlgI_SfIKWI0BDc9sPoTI2daCDkESI1Gluw?e=69lcaK&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
<br>

| Entrevista 6 |  Erick Cavero |
|------------------|----------------------|
| Negocio         | Espacio de coworking             |
| Cargo     | Administrador          |
| <img src="assets/entrevistado6.png"/>  | - Resumen: <br> Administra un espacio de coworking con acceso mediante tarjetas RFID pero sin automatización interna. Desea implementar reconocimiento automático de miembros con indicaciones de espacios disponibles según preferencias y configuración automática de áreas de trabajo reservadas. Enfrenta desafíos en la gestión de ocupación en tiempo real y en la recepción de visitantes para reuniones. Cuenta con sistemas de control de acceso, reserva de salas y termostatos programables, pero funcionan independientemente. El mercado competitivo de coworking hace que la experiencia tecnológica avanzada sea un importante diferenciador, especialmente para su clientela de profesionales tecnológicos. Los miembros han sugerido mejorar la fluidez del proceso desde la entrada hasta instalarse a trabajar. Espera mejorar las tasas de renovación, poder cobrar un premium por la experiencia, y optimizar la utilización del espacio. Con un presupuesto considerable de $10,000-15,000 dada la escala del negocio, y soporte técnico a tiempo parcial. Necesita alto nivel de personalización por miembro, tipo de espacio y horario. Prioriza la escalabilidad del sistema, robustez para múltiples usuarios, integración con sistemas existentes y capacidades analíticas. |
| URL | [Link de la entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202212191_upc_edu_pe/EZPAAJNQre9Jhpd3GScHJQkBGMWWwFLWYQu7LjusuwP-5A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=KPHLt2)            |
<br>

### 2.2.3 Análisis de entrevistas

## 2.3 Needfinding
### 2.3.1 User Personas

### 2.3.2 User Task Matrix

### 2.3.3 Empathy Mapping

### 2.3.4 As-is Scenario Mapping

## 2.4 Ubiquitous Language


























