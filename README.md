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
| xxxx          |  xxxxxx  |
|  xxxxxx       |  xxxxxxx |
|   x           | xxxxxx   |
| Vera Nuñez Nicolas Alejandro            | U202214869   |
|  xxxxxxxxxx   |  xxxxx  |

<div align="center"><h3>Abril 2026</h3></div><br>

</div>

---

### Registro de Versiones

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


































