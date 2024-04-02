
# Contenido

## Tabla de contenidos
  - [1. Student Outcome Capítulo I: Introducción](#1-student-outcome-cap%C3%ADtulo-i-introducci%C3%B3n)
  - [2. Capítulo II: Requirements Elicitation & Analysis](#2-cap%C3%ADtulo-ii-requirements-elicitation--analysis)
  - [3. Capítulo III: Requirements Specification](#3-cap%C3%ADtulo-iii-requirements-specification)
  - [4. Capítulo IV: Product Design](#4-cap%C3%ADtulo-iv-product-design)
  - [5. Capítulo V: Product Implementation, Validation & Deployment](#5-cap%C3%ADtulo-v-product-implementation-validation--deployment)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliograf%C3%ADa)
- [Anexos](#anexos)

### 1. Student Outcome Capítulo I: Introducción

- 1.1. Startup Profile
  - 1.1.1. Descripción de la Startup
    - PhysioDesk/Ergonomic-Style es la implementación de un modelo de un asistente virtual que brinda soluciones ergonómicas y ejercicios para personas que ocupan gran parte del día en el computador. La iniciativa busca analizar el estilo de vida del usuario con el fin de brindar las herramientas indicadas para aliviar y/o prevenir lesiones fisiológicas mediante un entorno ergonómico. Así mismo, recomendar la correcta postura y herramientas ergonómicas adecuadas para el usuario en función a su rango económico.

| Integrante                         | Descripción del Perfil                                                                                          |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------|
|  |  |
| Erick Joaquin Palomino Santa Cruz | Curso el quinto ciclo de la carrera de Ingeneria de Software. Me gusta aprender cosas nuevas y trabajar grupalmente para lograr una meta. |
|    |  |
|                                   |                                                                                                                  |
|                                   |                                                                                                                  |



- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática

    #### ¿Cuál es el problema?
    El problema que pudimos identificar es que no todos los alumnos tiene la misma visibilidad desde todas los asientos del aula. Por lo que en ocasiones puede traerles porblemas para prestar atención o para entender de forma efectiva la clase. Además, este problema se ve intencificado en aquellos casos en el que el profesor no tiene un buen volumen de voz, viéndose perjudicados aquellos alumnos que se encuentran en los últimos asientos del aula.
    
    #### ¿Cuándo sucede el problema?
    Este problema toma lugar durante el dictado de clases presenciales. Es debido al tamaño del aula que no todos los alumnos tienen la misma visibilidad al momento de atender a sus clases.
    
    #### ¿Dónde sucede el problema?
    Como se mencionó con anterioridad, el problema ocurre dentro de las aulas de todas las instituciones educativas. Problema que se ve repotenciado en las aulas con mayor capacidad, puesto que el tamaño de la misma obliga a los alumnos a sentarse a una mayor distancia de la pizarra.
    
    #### ¿A quién se le presenta el problema? ¿Cuál es tu público objetivo?
    Dicho problema se le presenta a todos aquellos alumnos que tienen que llevar clases de forma presencial. Por lo que, nuestro público objetivo son estos mismo alumnos, además de los profesores y las mismas instituciones educativas. Los dos últimos también son considerados como público objetivo ya que se ven involucrados en el problema. Los profesores buscan que todos sus alumnos puedan entender de forma rápida y sencilla las clases que dictan, así como las instituciones buscan tener un mayor atractivo para aquellos futuros estudiantes.
    
    #### ¿Por qué sucede el problema? ¿Qué situación ocasiona el problema?
    La situación que ocasiona este problema es la dificultad de tener una única pantalla o pizarra donde se debe mostrar el contenido para toda la clase, por lo que termina habiendo problemas desde algunas perspectivas dentro del aula.
    
    #### ¿Cómo sucede el problema? ¿Cuáles son las precondiciones para que se presente el problema?
    Este problema sucede de forma involuntaria, se debe principalmente al diseño clásico de las aulas. Por lo mismo, es común ver este mismo problema replicado en una gran cantidad de instituciones educativas, véase universidades, colegios o institutos, a lo largo de nuestro país.
    Acerca de esto, Mónica Maldonado, Vícotor Sotomayor y Jorge Villagrasa, de la Universitat Politècnica de València mencionan que:
  
    > "El fenómeno de que los buenos estudiantes se encontrasen en las primeras filas, ocurría tanto si los propios estudiantes escogían sus asientos, como si, por el contrario, se les asignaba su localización de manera totalmente aleatoria" Maldonado et al. (2020).

    Lo que demuestra la relación directa de la ubicación del alumno y la calidad de aprendizaje que este mismo recibe, siendo distinto para cada alumno dentro del aula.
    
    #### ¿Cuánto impacto genera este problema? Representar datos estadísticos del segmento que tiene el problema.
    Dentro del mismo estudio mencionado anteriormente, se logró determinar que:
    
    > "Las notas son mucho más elevadas cuanto más hacia delante se sitúa el estudiante (con una diferencia de 2.4 puntos en actitud y 1.3 puntos en el examen final comparando la primera fila y la última)" Maldonado et al. (2020).

    Dicho que denota la disminución en las calificaciones tanto de actutud como de exámenes en aquellos alumnos que se encuentran más alejados de la pizarra.
    
  - 1.2.2. Lean UX Process.
    - 1.2.2.1. Lean UX Problem Statements.
      Nuestra solución de negocio surge a partir de una problemática que afecta a una gran cantidad de estudiantes, que es,la distancia que tienen dichos alumnos con respecto a la pizarra o al docente.
 
      Es esencial abordar este problema debido a que una de las principales causas de la disminución en el desempeño de los estudiantes, repercutiendo directamente en sus calificaciones finales. El desafío que buscamos enfrentar es poder aumentar la visibilidad de los alumnos, así como mejorar la comunicación entre estos y el profesor, proporcionando una herramienta útil tanto para el profesorado como para las diversas instituciones educativas.
      
    - 1.2.2.2. Lean UX Assumptions.
  
      **Bussines Outcomes:**
        * 1
    
      **Features:**
        * Inicio de sesión simple: NoteLive es una aplicación web accesible directamente desde un navegador, lo que elimina la necesidad de instalación de software adicional. Los usuarios pueden acceder fácilmente a la plataforma mediante un código único proporcionado por el profesor.
        * Interacción en Tiempo Real: Una vez que los alumnos ingresan al código de la sesión, pueden ver la presentación del profesor en tiempo real en sus dispositivos móviles. Esto les permite seguir el ritmo de la clase desde cualquier lugar en el aula.
        * Envío de Preguntas Anónimas: Los alumnos tienen la capacidad de enviar preguntas de forma anónima a través de la aplicación. Estas preguntas se vinculan automáticamente con la diapositiva relevante, lo que permite una referencia precisa durante la discusión posterior.
        * Destaque de Preguntas Relevantes: Para fomentar la participación y priorizar las preguntas más importantes, NoteLive incluye una función de "me gusta". Los alumnos pueden otorgar likes a las preguntas que consideren más relevantes, lo que las resalta en la pantalla para una fácil identificación por parte del profesor.
        * Integración con Presentaciones: Los profesores pueden vincular sus presentaciones de diapositivas a la plataforma, lo que permite una visualización sincronizada para todos los alumnos. Esto garantiza que todos los participantes estén en la misma página y facilita la discusión en tiempo real.
        * Exportación de Registro de Preguntas: Al finalizar la sesión, los alumnos tienen la opción de exportar un archivo detallado que contiene un registro de todas las preguntas formuladas durante la clase. Este archivo proporciona una valiosa herramienta de revisión para repasar el material discutido y las preguntas planteadas.
    
      **User Outcomes:**
        * 1
  
    - 1.2.2.3. Lean UX Hypothesis Statements.
    - 1.2.2.4. Lean UX Canvas.
- 1.3. Segmentos objetivo.
  
1. **Estudiantes Universitarios**:
   - Buscan herramientas que faciliten la interacción en el aula durante clases presenciales.
   - Valorizan la posibilidad de acceder a la plataforma sin necesidad de instalar software adicional.
   - Necesitan una forma de hacer preguntas de manera anónima para aclarar dudas sin temor a ser juzgados.
   - Quieren una plataforma que les permita seguir la presentación del profesor desde sus dispositivos móviles.
   
2. **Profesores y Educadores**:
   - Buscan una herramienta que facilite la interacción y participación de los alumnos durante las clases.
   - Valorizan la capacidad de integrar la plataforma con sus presentaciones de diapositivas.
   - Necesitan una forma de priorizar y responder a las preguntas más relevantes de los estudiantes.
   - Quieren una plataforma que les permita gestionar múltiples sesiones de manera eficiente.
   
3. **Instituciones Educativas y Empresas de Capacitación**:
   - Buscan una solución que facilite la interacción entre profesores y alumnos durante sesiones presenciales.
   - Valorizan la posibilidad de personalizar la plataforma según sus necesidades, incluyendo la opción de contar con cuentas premium para un mayor número de usuarios.
   - Necesitan una herramienta que garantice la seguridad y privacidad de los datos de los usuarios.
   - Quieren una plataforma que facilite la recopilación y revisión de preguntas formuladas durante las sesiones de clase.


### 2. Capítulo II: Requirements Elicitation & Analysis

- 2.1. Competidores.
   En el mercado de aplicaciones para la interacción en tiempo real durante sesiones de enseñanza, existen varios productos que compiten ofreciendo soluciones similares para profesores y alumnos. A continuación, se mencionan algunos de los competidores clave identificados:

	 **Zoom for Education:** Zoom for Education es una plataforma de videoconferencia popular, diseñada específicamente para entornos educativos. Ofrece herramientas como salas de reuniones virtuales, compartición de pantalla, pizarra virtual y chats en vivo. Además, cuenta con características de seguridad, como control de sala de espera y autenticación de usuarios, para proteger la privacidad de los estudiantes.
<p align="center">
  <img width="460" height="300" src="https://github.com/LiveLinORG/Informes/assets/48342953/b30438de-d761-481e-a966-28db3ebde976">
</p>
	**Google Classroom:** Google Classroom es una plataforma de gestión del aprendizaje que permite a los profesores crear clases virtuales, asignar tareas, evaluar el trabajo de los alumnos y facilitar la comunicación entre estudiantes y profesores. La integración con otras herramientas de Google, como Google Drive y Google Meet, proporciona una experiencia educativa integrada y colaborativa. Google Classroom también ofrece funciones de seguimiento del progreso del alumno y retroalimentación personalizada.
<p align="center">
  <img width="460" height="300" src="https://github.com/LiveLinORG/Informes/assets/48342953/5cb364ec-a8fe-462c-9083-d35603ce1342">
</p>
	**Microsoft Teams for Education:** Microsoft Teams es una plataforma de colaboración que ofrece herramientas para la comunicación en tiempo real, la colaboración en documentos y la organización de equipos. La versión para educación de Microsoft Teams incluye características específicas para la enseñanza, como asignaciones integradas, cuadernos de clase de OneNote y la capacidad de realizar reuniones virtuales con estudiantes y profesores. Microsoft Teams for Education también ofrece integración con otras herramientas de Microsoft, como Office 365 y SharePoint.
<p align="center">
  <img width="460" height="300" src="https://github.com/LiveLinORG/Informes/assets/48342953/143458cf-3ce5-4b14-9f7c-fcd5a849de97">
</p>	
	Estos competidores, al igual que NoteLive, se centran en ofrecer soluciones completas para la interacción en tiempo real durante clases, proporcionando una diversidad de herramientas y recursos para facilitar la comunicación, colaboración y aprendizaje entre profesores y alumnos. Cada plataforma presenta características únicas y ventajas competitivas, por lo que es esencial que los usuarios analicen sus necesidades y preferencias individuales al seleccionar la aplicación que más se ajuste a sus requerimientos.
- 2.2. Análisis competitivo.

  **Perfil de la Startup**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Origen           | Lima, Perú                            | San Jose, California, EE. UU.                         | Mountain View, California, EE. UU.                    | Redmond, Washington, EE. UU.                           |
| Descripción General | LiveLin es una Startup peruana que se especializa en ofrecer una plataforma de videoconferencia diseñada específicamente para entornos educativos. Su enfoque se centra en proporcionar herramientas intuitivas y eficientes para la interacción en tiempo real entre profesores y alumnos, facilitando la enseñanza remota y la colaboración en proyectos educativos. | Zoom es una reconocida empresa estadounidense que ofrece una plataforma de videoconferencia utilizada ampliamente en diversos ámbitos, incluida la educación. Su servicio se destaca por su facilidad de uso, calidad de audio y video, así como por sus funciones de colaboración en tiempo real. | Google Classroom es una plataforma educativa desarrollada por Google que permite a los profesores crear y administrar cursos en línea, así como asignar tareas y comunicarse con los estudiantes. Está integrada con otras herramientas de Google, como Google Drive y Google Docs, para facilitar el flujo de trabajo en el entorno educativo. | Microsoft Teams es una aplicación de colaboración en equipo desarrollada por Microsoft que ofrece funciones de chat, videoconferencia, intercambio de archivos y colaboración en tiempo real. Aunque su enfoque principal está en entornos empresariales, también se utiliza en instituciones educativas para facilitar la comunicación y la colaboración entre profesores y estudiantes. |
| Ventaja competitiva ¿Qué valor ofrece a los clientes? | LiveLin ofrece una solución integral para la enseñanza remota, con herramientas específicas para la interacción en tiempo real en entornos educativos. Su enfoque en la educación y su conjunto de características diseñadas para facilitar la enseñanza hacen que sea una opción atractiva para instituciones educativas y profesionales de la educación. | Zoom destaca por su facilidad de uso y calidad de audio y video, lo que lo convierte en una opción popular para la enseñanza remota y la colaboración en línea. Además, ofrece una amplia gama de funciones, como salas de reuniones virtuales, compartición de pantalla y grabación de sesiones, que añaden valor a la experiencia del usuario. | Google Classroom se beneficia de su integración con otras herramientas de Google, lo que facilita el flujo de trabajo para profesores y estudiantes que ya utilizan productos de Google en su vida diaria. Además, su enfoque en la simplicidad y la facilidad de uso lo hace atractivo para instituciones educativas de todos los niveles. | Microsoft Teams ofrece una plataforma completa de colaboración en equipo que incluye funciones de chat, videoconferencia y colaboración en tiempo real. Su integración con otras aplicaciones de Microsoft, como Office 365, proporciona una experiencia fluida para profesores y estudiantes que utilizan el ecosistema de Microsoft en sus actividades educativas. |

**Perfil de Marketing**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Mercado Objetivo | LiveLin está dirigido principalmente a instituciones educativas, profesores y estudiantes que buscan una solución integral para la enseñanza remota y la colaboración en proyectos educativos. | Zoom se dirige a una amplia variedad de usuarios, incluidos profesionales de negocios, equipos de trabajo remotos y educadores que necesitan herramientas de videoconferencia de alta calidad. | Google Classroom está orientado a profesores y estudiantes que desean gestionar cursos en línea, asignar tareas y colaborar en proyectos educativos utilizando las herramientas de Google. | Microsoft Teams se enfoca en entornos empresariales y educativos, ofreciendo una plataforma completa de colaboración en equipo que satisface las necesidades de comunicación y colaboración de profesores, estudiantes y equipos de trabajo. |
| Estrategias de Marketing | - Campañas de marketing dirigidas a instituciones educativas y profesionales de la educación. - Promoción en redes sociales y blogs educativos. - Colaboración con asociaciones educativas y organizaciones sin fines de lucro. | - Publicidad en línea y campañas de marketing dirigidas a profesionales y educadores. - Participación en conferencias y eventos de la industria. - Programas de afiliados y referencias para ampliar la base de usuarios. | - Integración con otras herramientas de Google para promover la adopción entre los usuarios existentes de Google. - Marketing de contenidos y tutoriales en línea para profesores y estudiantes. - Colaboración con instituciones educativas para la implementación y formación en Google Classroom. | - Promoción a través de la suite de productos de Microsoft, como Office 365 y Azure. - Eventos y conferencias educativas patrocinadas por Microsoft. - Colaboración con distribuidores y partners para la implementación y formación en Microsoft Teams. |

**Perfil del Producto**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Características y servicios | - Herramientas de videoconferencia diseñadas específicamente para entornos educativos. - Funciones de interacción en tiempo real entre profesores y estudiantes, como chat en vivo, compartición de pantalla y pizarra virtual. - Integración con plataformas de gestión de aprendizaje (LMS) para facilitar la administración de cursos y asignaciones. | - Videoconferencia de alta calidad con capacidad para hasta 1000 participantes en una sola reunión. - Funciones de colaboración en tiempo real, como compartición de pantalla, chat en vivo y grabación de sesiones. - Integración con aplicaciones de terceros y herramientas de productividad. | - Plataforma de gestión de cursos en línea que permite a los profesores crear y administrar clases virtuales, asignar tareas y evaluar el progreso de los estudiantes. - Integración con otras herramientas de Google, como Google Drive y Google Docs, para facilitar el flujo de trabajo. - Aplicación móvil para acceder a Google Classroom desde dispositivos móviles. | - Plataforma de colaboración en equipo que incluye funciones de chat, videoconferencia, intercambio de archivos y colaboración en tiempo real. - Integración con otras aplicaciones de Microsoft, como Office 365 y SharePoint. - Seguridad avanzada y cumplimiento de normativas para proteger los datos de los usuarios. |

**Análisis SWOT**

| Startup          | LiveLin                                            | Zoom                                                  | Google Classroom                                      | Microsoft Teams                                        |
|------------------|----------------------------------------------------|-------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|
| Fortalezas       | - Enfoque específico en el sector educativo. - Herramientas diseñadas para la enseñanza remota y la colaboración en proyectos educativos. - Integración con plataformas de gestión de aprendizaje (LMS) para una experiencia de usuario completa. | - Facilidad de uso y calidad de audio y video. - Capacidad para albergar grandes reuniones con hasta 1000 participantes. - Amplia gama de funciones de colaboración en tiempo real. | - Integración con otras herramientas de Google para un flujo de trabajo sin interrupciones. - Aplicación móvil para acceder a Google Classroom desde dispositivos móviles. - Popularidad y reconocimiento de la marca Google. | - Plataforma completa de colaboración en equipo con funciones de chat, videoconferencia y colaboración en tiempo real. - Integración con otras aplicaciones de Microsoft para una experiencia integrada. - Seguridad avanzada y cumplimiento de normativas para proteger los datos de los usuarios. |
| Debilidades      | - Poco reconocimiento de marca en comparación con competidores establecidos como Zoom y Google Classroom. - Limitaciones en la capacidad de participantes en las reuniones en comparación con Zoom. - Menor variedad de funciones en comparación con Microsoft Teams. | - Vulnerabilidades de seguridad y privacidad, como incidentes de "zoombombing". - Dependencia excesiva de la conexión a Internet para un rendimiento óptimo. - Falta de integración con otras herramientas educativas y plataformas de gestión de aprendizaje. | - Dependencia de la conectividad a Internet para el acceso y la funcionalidad. - Limitaciones en la capacidad de personalización y configuración en comparación con plataformas más avanzadas como Microsoft Teams. - Competencia directa con otras herramientas de productividad de Google, como Google Meet. | - Menor flexibilidad en la personalización y configuración en comparación con herramientas más avanzadas como Zoom y Microsoft Teams. - Menor integración con otras herramientas de productividad no relacionadas con Microsoft en comparación con Google Classroom. - Dependencia de la suscripción a Microsoft Office 365 para acceder a todas las funciones. |
| Oportunidades    | - Expansión del mercado educativo global con el aumento de la enseñanza remota y el aprendizaje en línea. - Colaboraciones estratégicas con instituciones educativas y organizaciones sin fines de lucro para promover la adopción de LiveLin. - Desarrollo y mejora continua de nuevas características y herramientas específicas para las necesidades educativas. | - Diversificación de servicios para abordar otras necesidades de comunicación y colaboración en línea, como reuniones virtuales sociales y eventos en línea. - Expansión internacional a nuevos mercados emergentes con una demanda creciente de herramientas de videoconferencia. - Integración con plataformas de gestión de aprendizaje (LMS) y sistemas de información educativa para una experiencia educativa más completa. | - Desarrollo de nuevas características y herramientas basadas en la retroalimentación de usuarios y educadores. - Expansión a mercados emergentes y regionales con una demanda creciente de soluciones educativas en línea. - Colaboración con desarrolladores de aplicaciones educativas y herramientas de aprendizaje para integraciones y asociaciones estratégicas. | - Expansión a nuevos sectores y mercados, como el sector empresarial y gubernamental, para su uso en la colaboración en equipo y la comunicación interna. - Integración con otras herramientas de productividad y sistemas empresariales para una experiencia de usuario más integrada. - Desarrollo de soluciones específicas para industrias verticales, como la atención médica y el sector público, para abordar necesidades específicas de colaboración y comunicación. |
| Amenazas         | - Competencia intensa de empresas establecidas en el mercado de videoconferencias, como Zoom y Google Meet. - Riesgos de seguridad y privacidad asociados con el almacenamiento y procesamiento de datos sensibles de estudiantes y profesores. - Cambios en las regulaciones y políticas gubernamentales que puedan afectar la operación y la expansión internacional de LiveLin. | - Competencia de otras plataformas de videoconferencia y colaboración en línea con una mayor cuota de mercado y reconocimiento de marca. - Amenazas de seguridad cibernética y violaciones de datos que pueden socavar la confianza del usuario en la plataforma. - Cambios en las preferencias y necesidades del usuario que pueden afectar la demanda de servicios de videoconferencia en línea. | - Competencia directa de otras plataformas educativas en línea, como Microsoft Teams y Canvas, que ofrecen funcionalidades similares y están integradas con otros servicios de productividad. - Cambios en las políticas y regulaciones gubernamentales que pueden afectar la recopilación y el procesamiento de datos de estudiantes y educadores en línea. - Dependencia de la infraestructura de Internet y la conectividad para el acceso y la funcionalidad de Google Classroom. | - Competencia de otras plataformas de colaboración en equipo y comunicación empresarial, como Slack y Cisco Webex Teams. - Amenazas de seguridad y riesgos de privacidad asociados con la comunicación y colaboración en línea en entornos empresariales y gubernamentales. - Cambios en las necesidades y preferencias del usuario que pueden afectar la demanda de herramientas de colaboración en equipo y comunicación interna. |
- 2.2. Análisis competitivo.
- 2.3. Estrategias y tácticas frente a competidores.
  ## Estrategias:

| Estrategia                           | Descripción                                                                                                                         |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Diferenciación del Producto          | Enfocarse en las características únicas de NoteLive para diferenciarse de otras plataformas en el mercado.                        |
| Enfoque en la Experiencia del Usuario| Priorizar la facilidad de uso y la experiencia del usuario para garantizar una experiencia satisfactoria durante las sesiones.       |
| Integración con Herramientas de Presentación | Mejorar la integración con herramientas de presentación populares para facilitar su adopción por parte de los usuarios.         |

## Tácticas:

| Táctica                                          | Descripción                                                                                                                            |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Ofrecer un Plan Gratuito Atractivo               | Mantener un plan gratuito con funcionalidades básicas para atraer a usuarios potenciales y darles la oportunidad de experimentar.     |
| Desarrollar y Promover Funcionalidades Exclusivas| Crear funcionalidades exclusivas para planes de pago y promover activamente estas características para captar usuarios dispuestos a pagar.|
| Crear Alianzas Estratégicas con Instituciones Educativas | Establecer alianzas con instituciones educativas para promover el uso de NoteLive en entornos académicos.                      |
| Realizar Campañas de Marketing Dirigidas        | Llevar a cabo campañas de marketing dirigidas a profesores y administradores educativos para destacar los beneficios de NoteLive.   |
| Mantenerse al Tanto de las Tendencias del Mercado| Permanecer atento a las tendencias del mercado y adaptar la plataforma para satisfacer las necesidades cambiantes de los usuarios.   |

- 2.4. Entrevistas.
  - 2.4.1. Diseño de entrevistas.
  
    ***Preguntas para Segmento 1: Estudiantes Universitarios***

    En relación al grupo de estudiantes universitarios a los que apuntamos:

	1. ¿Qué herramientas consideras más útiles para mejorar la interacción en el aula durante clases presenciales?
	2. ¿Prefieres plataformas que no requieran instalación de software adicional o estás dispuesto/a a hacerlo si ofrece más funcionalidades?
	3. ¿Qué características valoras más al hacer preguntas durante las clases, como la opción de anonimato o la facilidad de uso?
	4. ¿Qué aspectos te resultan más importantes al seguir la presentación del profesor desde dispositivos móviles?
	5. ¿Cómo crees que una plataforma podría ayudarte a mejorar tu experiencia de aprendizaje en el aula?
	6. ¿Qué funciones adicionales te gustaría que una plataforma ofreciera para facilitar la colaboración y el trabajo en equipo?
	7. ¿Cuál es tu opinión sobre la seguridad y privacidad de tus datos al utilizar plataformas en línea para la educación?
	8. ¿Has tenido alguna experiencia previa con plataformas similares? ¿Qué aspectos positivos y negativos destacarías?
	9. ¿Qué tan importante es para ti que una plataforma sea fácil de usar y tenga una interfaz intuitiva?
	10. ¿Qué crees que hace que una plataforma sea exitosa en el ámbito educativo?

    ***Preguntas para Segmento 2: Profesores y Educadores***

    Estas son algunas preguntas diseñadas para comprender mejor su perspectiva y experiencia en el ámbito educativo. 	 
    Agradecemos su tiempo y sus respuestas, ya que contribuirán al desarrollo de nuestro proyecto.

	1. ¿Qué características consideras más importantes al seleccionar una plataforma para utilizar en tus clases?
	2. ¿Cómo integrarías una plataforma en tus presentaciones de diapositivas o clases?
	3. ¿Qué herramientas te gustaría tener para priorizar y responder preguntas de los estudiantes durante las clases?
	4. ¿Cómo gestionas actualmente múltiples sesiones o cursos en línea?
	5. ¿Qué aspectos de una plataforma te facilitarían más tu trabajo como educador?
	6. ¿Qué desafíos enfrentas al interactuar con tus alumnos de manera remota o en línea?
	7. ¿Qué funciones adicionales te gustaría que una plataforma ofreciera para mejorar la participación y el compromiso de los estudiantes?
	8. ¿Cómo evalúas la efectividad de una plataforma en el proceso de enseñanza y aprendizaje?
	9. ¿Qué importancia le das a la personalización y adaptación de una plataforma a tus necesidades específicas como educador?
	10. ¿Qué consejos darías a otros educadores al seleccionar una plataforma para utilizar en sus clases?
  - 2.4.2. Registro de entrevistas.
  - 2.4.3. Análisis de entrevistas.
- 2.5. Needfinding.
  
#### Problemas Identificados:

1. **Dificultad para la Interacción en el Aula**:
   - Los estudiantes encuentran desafiante participar activamente en las clases presenciales debido a barreras de comunicación o miedo al juicio de sus pares.

2. **Limitaciones en la Participación de los Alumnos**:
   - Algunos alumnos pueden sentirse reacios a hacer preguntas o expresar dudas en público durante las clases, lo que puede afectar su comprensión del material.

3. **Falta de Sincronización en la Presentación de Diapositivas**:
   - La falta de sincronización entre la presentación del profesor y los dispositivos de los alumnos puede dificultar seguir el ritmo de la clase y afectar la comprensión del contenido.

4. **Desafíos en la Priorización de Preguntas Relevantes**:
   - Los profesores pueden enfrentar dificultades para identificar y responder a las preguntas más importantes de los alumnos debido a la falta de un sistema de priorización claro.

5. **Necesidad de Recursos de Revisión y Repaso**:
   - Los estudiantes pueden carecer de herramientas efectivas para revisar y repasar el material discutido en clase, lo que puede afectar su rendimiento académico.

#### Soluciones Propuestas:

1. **Facilitar la Interacción en el Aula**:
   - Proporcionar una plataforma que permita a los estudiantes participar activamente en la clase desde sus dispositivos móviles, eliminando barreras de comunicación.

2. **Fomentar la Participación de los Alumnos**:
   - Permitir a los estudiantes hacer preguntas de forma anónima para fomentar un entorno de aprendizaje inclusivo y sin miedo al juicio.

3. **Sincronización en Tiempo Real**:
   - Garantizar que la presentación del profesor esté sincronizada con los dispositivos de los estudiantes para facilitar el seguimiento del contenido de la clase.

4. **Priorización de Preguntas Relevantes**:
   - Implementar un sistema de votación o "me gusta" para que los estudiantes puedan destacar las preguntas más importantes, ayudando así a los profesores a priorizarlas y responderlas de manera efectiva.

5. **Recursos de Revisión y Repaso**:
   - Permitir a los estudiantes exportar un registro detallado de preguntas formuladas durante la clase para facilitar la revisión y repaso del material discutido.
- 2.6. User Personas.
- 2.7. User Task Matrix.
- 2.8. User Journey Mapping.
- 2.9. Empathy Mapping.
- 2.10. As-is Scenario Mapping.
- 2.11. Ubiquitous Language.
  ## Términos y Conceptos

1. **Sesión Presencial**:
   - Definición: Una reunión física entre profesores y alumnos donde se utiliza NoteLive para facilitar la interacción en tiempo real.
   - Ejemplo de Uso: "Hoy tendremos una sesión presencial de matemáticas utilizando NoteLive."

2. **Inicio de Sesión Simple**:
   - Definición: Proceso de acceso a la plataforma NoteLive sin requerir instalación de software adicional.
   - Ejemplo de Uso: "Gracias a la función de inicio de sesión simple, los usuarios pueden acceder a NoteLive con solo ingresar un código proporcionado por el profesor."

3. **Interacción en Tiempo Real**:
   - Definición: La capacidad de los alumnos para seguir la presentación del profesor en tiempo real desde sus dispositivos móviles durante una sesión presencial.
   - Ejemplo de Uso: "La interacción en tiempo real de NoteLive permite a los estudiantes seguir el ritmo de la clase desde cualquier lugar en el aula."

4. **Preguntas Anónimas**:
   - Definición: La capacidad de los alumnos para enviar preguntas de forma anónima a través de la aplicación.
   - Ejemplo de Uso: "Con la función de preguntas anónimas, los estudiantes pueden aclarar sus dudas sin temor a ser juzgados."

5. **Destaque de Preguntas Relevantes**:
   - Definición: La función que permite a los alumnos destacar preguntas importantes mediante la opción de "me gusta".
   - Ejemplo de Uso: "Los profesores pueden identificar las preguntas más relevantes gracias al destaque de preguntas implementado en NoteLive."

6. **Integración con Presentaciones**:
   - Definición: La capacidad de los profesores para vincular sus presentaciones de diapositivas a NoteLive para una visualización sincronizada.
   - Ejemplo de Uso: "La integración con presentaciones de NoteLive garantiza que todos los participantes estén en la misma página durante la clase."

7. **Exportación de Registro de Preguntas**:
   - Definición: La opción para que los alumnos exporten un archivo detallado que contiene un registro de todas las preguntas formuladas durante la sesión.
   - Ejemplo de Uso: "Al finalizar la sesión, los alumnos pueden exportar el registro de preguntas para su revisión y repaso posterior."

## Planes de Suscripción

- **Plan Gratuito**:
  - Límite de personas en la sesión: 30
  - Límite de tiempo: 40 min
  - Límite de diapositivas: 100
  - Sin opción de preguntas destacadas
  - Solo puede crear una sesión a la vez

- **Plan Premium**:
  - 1 cuenta premium
  - Límite de personas en la sesión: 100
  - Tiempo ilimitado
  - Diapositivas: 500
  - Preguntas destacadas con CSS
  - Múltiples sesiones

- **Plan Empresarial**:
  - Hasta 1000 cuentas
  - Límite de personas en la sesión: 200
  - Todas las ventajas del plan premium

### 3. Capítulo III: Requirements Specification

- 3.1. To-Be Scenario Mapping.
- 3.2. User Stories.
- 3.3. Impact Mapping.
- 3.4. Product Backlog.

|Historia De Usuario|Descripción|
|:----|:----|
|Inicio de Sesión Simple|Como usuario, quiero poder iniciar sesión de manera sencilla en NoteLive a través de un código único proporcionado por el profesor para acceder a la sesión.|
|Interacción en Tiempo Real|Como alumno, deseo ver la presentación del profesor en tiempo real en mi dispositivo móvil mientras estoy en clase para poder seguir el ritmo de la lección desde cualquier lugar en el aula.|
|Envío de Preguntas Anónimas|Como alumno, quiero tener la capacidad de enviar preguntas de forma anónima a través de la aplicación para poder participar en la discusión sin revelar mi identidad.|
|Destaque de Preguntas Relevantes|Como alumno, me gustaría poder destacar las preguntas que considere más relevantes utilizando la función de "me gusta" para que el profesor pueda identificarlas fácilmente y abordarlas durante la clase.|
|Integración con Presentaciones|Como profesor, quiero poder vincular mis presentaciones de diapositivas a NoteLive para que todos los alumnos puedan verlas sincronizadamente y facilitar la discusión en tiempo real durante la clase.|
|Exportación de Registro de Preguntas|Como alumno, quiero tener la opción de exportar un archivo detallado que contenga un registro de todas las preguntas formuladas durante la clase para poder revisarlas posteriormente y repasar el material discutido.|
|Navegación a la Página de Inicio|Como usuario, deseo poder navegar fácilmente a la página de inicio de NoteLive haciendo clic en el enlace correspondiente en la barra de navegación para acceder a información general sobre la aplicación.|
|Navegación a la Sección de Información|Como usuario, quiero poder acceder a la sección que explica qué es NoteLive haciendo clic en el enlace respectivo en la barra de navegación para obtener más detalles sobre su funcionamiento.|
|Navegación a la Sección de Usos|Como usuario, deseo poder explorar los diferentes usos de NoteLive haciendo clic en el enlace correspondiente en la barra de navegación para comprender cómo puede beneficiarme en mi contexto educativo.|
|Navegación a la Galería|Como usuario, me gustaría poder ver una galería de imágenes relacionadas con NoteLive haciendo clic en el enlace correspondiente en la barra de navegación para visualizar ejemplos de su aplicación en situaciones reales.|
|Navegación al Registro|Como usuario, quiero poder acceder a la página de registro de NoteLive haciendo clic en el enlace respectivo en la barra de navegación para crear una cuenta y comenzar a utilizar la plataforma.|
|Participación en Sesión Anónima|Como alumno, deseo poder participar en una sesión de NoteLive de manera anónima ingresando un código único proporcionado por el profesor para mantener mi privacidad durante la interacción en clase.|
|Acceso a Presentaciones Sincronizadas|Como alumno, quiero poder acceder a las presentaciones de diapositivas sincronizadas con la clase a través de NoteLive para asegurarme de que todos los participantes estén en la misma página y no perderme ningún contenido importante.|
|Recepción de Notificaciones|Como usuario, me gustaría recibir notificaciones de nuevas actualizaciones o anuncios importantes relacionados con NoteLive para mantenerme informado sobre cualquier cambio en la plataforma.|
|Personalización de Perfil|Como usuario, quiero poder personalizar mi perfil en NoteLive agregando una foto y ajustando mi configuración para adaptar la experiencia de uso a mis preferencias individuales.|
|Acceso a la Galería de Recursos|Como usuario, deseo poder acceder a una galería de recursos educativos dentro de NoteLive para encontrar material adicional que complemente mi aprendizaje durante la clase.|
|Función de Traducción Integrada|Como usuario, me gustaría tener la opción de utilizar una función de traducción integrada en NoteLive para traducir contenido en tiempo real a mi idioma preferido y facilitar la comprensión de la lección.|
|Compartir Enlaces de Sesión|Como profesor, quiero poder compartir enlaces de sesión personalizados con mis alumnos a través de NoteLive para facilitar su acceso a la plataforma y comenzar la clase sin problemas.|
|Control de Acceso a la Sesión|Como profesor, deseo tener la capacidad de controlar el acceso a la sesión de NoteLive mediante la generación y asignación de códigos únicos para garantizar la seguridad y la integridad de la clase.|
|Marcar Diapositivas Importantes|Como profesor, me gustaría poder marcar diapositivas importantes durante la presentación en NoteLive para resaltarlas y asegurarme de que los alumnos presten atención a los conceptos clave.|
|Evaluación de Participación|Como profesor, deseo tener la capacidad de evaluar la participación de los alumnos durante la clase en NoteLive mediante la revisión de las preguntas enviadas y los comentarios realizados para medir su compromiso con el material.|
|Asistencia Automatizada|Como profesor, quiero que NoteLive registre automáticamente la asistencia de los alumnos cuando accedan a la sesión para facilitar el seguimiento de su participación y puntualidad.|
|Acceso a Recursos Compartidos|Como alumno, me gustaría poder acceder a recursos compartidos por el profesor durante la clase a través de NoteLive para revisar el material posteriormente y reforzar mi aprendizaje.|
|Soporte para Diferentes Dispositivos|Como usuario, deseo que NoteLive sea compatible con una variedad de dispositivos y sistemas operativos para poder acceder a la plataforma desde cualquier dispositivo que tenga disponible.|
|Personalización de Temas|Como usuario, me gustaría poder personalizar el tema visual de NoteLive eligiendo entre diferentes opciones de color y diseño para adaptarlo a mis preferencias estéticas y mejorar la experiencia de uso.|
|Compartir Recursos con Otros Usuarios|Como profesor, quiero poder compartir recursos educativos con otros usuarios de NoteLive para promover la colaboración y el intercambio de conocimientos entre la comunidad de usuarios.|
|Informes de Desempeño del Alumno|Como profesor, deseo tener acceso a informes de desempeño individual de los alumnos en NoteLive para evaluar su progreso y ofrecer retroalimentación personalizada sobre su rendimiento académico.|
|Integración con Plataformas de Aprendizaje|Como usuario, me gustaría que NoteLive se integre con otras plataformas de aprendizaje en línea para facilitar la gestión de contenido y la comunicación con mis profesores y compañeros de clase.|
|Sincronización de Notas y Comentarios|Como usuario, quiero que mis notas y comentarios realizados en NoteLive se sincronicen automáticamente en todos mis dispositivos para poder acceder a ellos desde cualquier lugar y en cualquier momento.|
|Protección de Datos Personales|Como usuario, deseo que NoteLive garantice la protección de mis datos personales y la privacidad de mis interacciones en la plataforma mediante medidas de seguridad robustas y cumplimiento de regulaciones de privacidad.|
- Product Backlog de Landing Page:
| User Story                           | Descripción                                                                                                          |
|--------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Optimización de Responsividad        | Asegurarse de que el sitio web sea completamente responsive en diferentes dispositivos y tamaños de pantalla.      |
| Mejoras de Accesibilidad             | Garantizar que el sitio web sea accesible para usuarios con discapacidades, incluyendo la navegación por teclado y el uso de lectores de pantalla. |
| Validación de HTML y CSS             | Validar el código HTML y CSS para asegurar que cumple con los estándares y no contiene errores.                     |
| Optimización de Carga                | Optimizar el tiempo de carga del sitio web para mejorar la experiencia del usuario.                                |
| Añadir Interactividad                | Implementar interactividad en elementos como botones y enlaces para mejorar la usabilidad.                          |
| Mejoras de SEO                       | Optimizar el sitio web para mejorar su visibilidad en los motores de búsqueda.                                        |
| Refactorización de Clases y Selectores | Revisar y refactorizar las clases y selectores en el CSS para mejorar la legibilidad y mantenibilidad del código.  |
| Pruebas de Cross-Browser             | Realizar pruebas exhaustivas en diferentes navegadores para asegurar la compatibilidad y el rendimiento del sitio web.|
| Documentación                        | Documentar el código HTML y CSS para facilitar el mantenimiento futuro y la colaboración entre desarrolladores.     |
| Implementación de Funcionalidades Faltantes | Completar la implementación de características como el inicio de sesión, el registro de usuarios, y otras funciones necesarias para el funcionamiento completo del sitio web. |
| Seguridad                            | Implementar medidas de seguridad apropiadas para proteger el sitio web contra vulnerabilidades y ataques maliciosos.|
| Actualización de Contenido           | Actualizar el contenido del sitio web según sea necesario para mantenerlo relevante y preciso.                       |
| Gestión de Errores y Excepciones     | Implementar manejo de errores y excepciones para proporcionar una experiencia de usuario robusta y sin problemas.     |
| Integración de Diseño de Interfaces | Integrar el diseño de interfaces gráficas proporcionado por el equipo de diseño para asegurar coherencia visual en todo el sitio web. |
| Cabecera (Header)                    | La estructura de la cabecera está definida con secciones como el logo y los elementos de navegación.                  |
| Diseño Responsivo                    | El diseño del sitio web utiliza técnicas CSS Grid y Flexbox para garantizar una visualización adecuada en diferentes dispositivos y tamaños de pantalla. |
| Estilos de Navegación                | Se han aplicado estilos CSS para los elementos de navegación, incluyendo efectos de hover y sombras.                 |
| Contenedor Principal                 | El contenedor principal del sitio web se ha definido con una estructura de grid y secciones para organizar el contenido. |
| Sección de Aterrizaje (Landing)      | Se ha creado una sección de aterrizaje con un título, subtítulo, imágenes y un botón de inicio.                     |
| Estilos de Botón                     | Los botones tienen estilos CSS aplicados, incluyendo colores, sombras y efectos de hover.                           |
| Tarjetas de Notas (Note Live Cards)  | Se han definido tarjetas para mostrar información sobre las características de NoteLive, con diferentes estilos según el tamaño de la tarjeta. |
| Sección de Características Adicionales | Se ha creado una sección para mostrar las características de los diferentes planes de NoteLive, con estilos y colores específicos para cada plan. |
| Estilos de Testimonios de Usuarios   | Los testimonios de usuarios tienen estilos aplicados, incluyendo colores de fondo, tipografía y efectos de hover. |
| Sección de Recursos Educativos       | Se ha añadido una sección para mostrar recursos educativos relacionados con NoteLive.                                |
| Sección de Soporte y Contacto        | Se ha creado una sección para proporcionar información de contacto y soporte, con estilos aplicados para resaltar la información. |
| Sección de Integraciones y Compatibilidad | Se ha añadido una sección para destacar las integraciones y compatibilidad de NoteLive con otras plataformas.        |
| Sección de Actualizaciones y Novedades | Se ha incluido una sección para informar a los usuarios sobre las últimas actualizaciones y noticias relacionadas con NoteLive. |
| Estilos del Footer                   | El footer tiene estilos aplicados para el color de fondo, el color del texto y el espaciado interno.                |
| Consulta de Medios (Media Queries)   | Se han implementado consultas de medios para ajustar el diseño y los estilos en diferentes tamaños de pantalla.     |

  

### 4. Capítulo IV: Product Design

- 4.1. Style Guidelines.
  - 4.1.1. General Style Guidelines.
  - 4.1.2. Web Style Guidelines.
- 4.2. Information Architecture.
  - 4.2.1. Organization Systems.
  - 4.2.2. Labeling Systems.
  - 4.2.3. SEO Tags and Meta Tags.
  - 4.2.4. Searching Systems.
  - 4.2.5. Navigation Systems.
- 4.3. Landing Page UI Design.
  - 4.3.1. Landing Page Wireframe.
  - 4.3.2. Landing Page Mock-up.
- 4.4. Web Applications UX/UI Design.
  - 4.4.1. Web Applications Wireframes.
  - 4.4.2. Web Applications Wireflow Diagrams.
  - 4.4.3. Web Applications Mock-ups.
  - 4.4.4. Web Applications User Flow Diagrams.
  - 4.4.5. Web Applications Prototyping.
- 4.5. Domain-Driven Software Architecture.
  - 4.5.1. Software Architecture Context Diagram.
  - 4.5.2. Software Architecture Container Diagrams.
  - 4.5.3. Software Architecture Components Diagrams.
- 4.6. Software Object-Oriented Design.
  - 4.6.1. Class Diagrams.
  - 4.6.2. Class Dictionary.
- 4.7. Database Design.
  - 4.7.1. Database Diagram.

### 5. Capítulo V: Product Implementation, Validation & Deployment

- 5.1. Software Configuration Management.
  - 5.1.1. Software Development Environment Configuration.
  - 5.1.2. Source Code Management.
  - 5.1.3. Source Code Style Guide & Conventions.
  - 5.1.4. Software Deployment Configuration.
- 5.2. Landing Page, Services & Applications Implementation.
  - 5.2.1. Sprint n
    - 5.2.1.1. Sprint Planning.
    - 5.2.1.2. Sprint Backlog.
<table>
  <thead>
    <tr>
      <th>User Story</th>
      <th>Descripción</th>
      <th>Horas Estimadas</th>
      <th>Asignación</th>
      <th>Fecha Límite</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Mejoras de Accesibilidad</td>
      <td>Garantizar que el sitio web sea accesible para usuarios con discapacidades, incluyendo la navegación por teclado y el uso de lectores de pantalla.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>30 de marzo de 2024</td>
    </tr>
    <tr>
      <td>Validación de HTML y CSS</td>
      <td>Validar el código HTML y CSS para asegurar que cumple con los estándares y no contiene errores.</td>
      <td>6 horas</td>
      <td>[Por Asignar]</td>
      <td>31 de marzo de 2024</td>
    </tr>
    <tr>
      <td>Optimización de Carga</td>
      <td>Optimizar el tiempo de carga del sitio web para mejorar la experiencia del usuario.</td>
      <td>10 horas</td>
      <td>[Por Asignar]</td>
      <td>1 de abril de 2024</td>
    </tr>
    <tr>
      <td>Añadir Interactividad</td>
      <td>Implementar interactividad en elementos como botones y enlaces para mejorar la usabilidad.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>2 de abril de 2024</td>
    </tr>
    <tr>
      <td>Mejoras de SEO</td>
      <td>Optimizar el sitio web para mejorar su visibilidad en los motores de búsqueda.</td>
      <td>6 horas</td>
      <td>[Por Asignar]</td>
      <td>3 de abril de 2024</td>
    </tr>
    <tr>
      <td>Refactorización de Clases y Selectores</td>
      <td>Revisar y refactorizar las clases y selectores en el CSS para mejorar la legibilidad y mantenibilidad del código.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>4 de abril de 2024</td>
    </tr>
    <tr>
      <td>Pruebas de Cross-Browser</td>
      <td>Realizar pruebas exhaustivas en diferentes navegadores para asegurar la compatibilidad y el rendimiento del sitio web.</td>
      <td>12 horas</td>
      <td>[Por Asignar]</td>
      <td>5 de abril de 2024</td>
    </tr>
    <tr>
      <td>Documentación</td>
      <td>Documentar el código HTML y CSS para facilitar el mantenimiento futuro y la colaboración entre desarrolladores.</td>
      <td>6 horas</td>
      <td>[Por Asignar]</td>
      <td>6 de abril de 2024</td>
    </tr>
    <tr>
      <td>Implementación de Funcionalidades Faltantes</td>
      <td>Completar la implementación de características como el inicio de sesión, el registro de usuarios, y otras funciones necesarias para el funcionamiento completo del sitio web.</td>
      <td>14 horas</td>
      <td>[Por Asignar]</td>
      <td>7 de abril de 2024</td>
    </tr>
    <tr>
      <td>Seguridad</td>
      <td>Implementar medidas de seguridad apropiadas para proteger el sitio web contra vulnerabilidades y ataques maliciosos.</td>
      <td>10 horas</td>
      <td>[Por Asignar]</td>
      <td>8 de abril de 2024</td>
    </tr>
    <tr>
      <td>Actualización de Contenido</td>
      <td>Actualizar el contenido del sitio web según sea necesario para mantenerlo relevante y preciso.</td>
      <td>6 horas</td>
      <td>[Por Asignar]</td>
      <td>9 de abril de 2024</td>
    </tr>
    <tr>
      <td>Gestión de Errores y Excepciones</td>
      <td>Implementar manejo de errores y excepciones para proporcionar una experiencia de usuario robusta y sin problemas.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>7 de abril de 2024</td>
    </tr>
    <tr>
      <td>Integración de Diseño de Interfaces</td>
      <td>Integrar el diseño de interfaces gráficas proporcionado por el equipo de diseño para asegurar coherencia visual en todo el sitio web.</td>
      <td>10 horas</td>
      <td>[Por Asignar]</td>
      <td>1 de abril de 2024</td>
    </tr>
    <tr>
      <td>Cabecera (Header)</td>
      <td>La estructura de la cabecera está definida con secciones como el logo y los elementos de navegación.</td>
      <td>4 horas</td>
      <td>[Por Asignar]</td>
      <td>1 de abril de 2024</td>
    </tr>
    <tr>
      <td>Diseño Responsivo</td>
      <td>El diseño del sitio web utiliza técnicas CSS Grid y Flexbox para garantizar una visualización adecuada en diferentes dispositivos y tamaños de pantalla.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>3 de abril de 2024</td>
    </tr>
    <tr>
      <td>Estilos de Navegación</td>
      <td>Se han aplicado estilos CSS para los elementos de navegación, incluyendo efectos de hover y sombras.</td>
      <td>6 horas</td>
      <td>[Por Asignar]</td>
      <td>4 de abril de 2024</td>
    </tr>
    <tr>
      <td>Contenedor Principal</td>
      <td>El contenedor principal del sitio web se ha definido con una estructura de grid y secciones para organizar el contenido.</td>
      <td>6 horas</td>
      <td>[Por Asignar]</td>
      <td>5 de abril de 2024</td>
    </tr>
    <tr>
      <td>Sección de Aterrizaje (Landing)</td>
      <td>Se ha creado una sección de aterrizaje con un título, subtítulo, imágenes y un botón de inicio.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>6 de abril de 2024</td>
    </tr>
    <tr>
      <td>Estilos de Botón</td>
      <td>Los botones tienen estilos CSS aplicados, incluyendo colores, sombras y efectos de hover.</td>
      <td>4 horas</td>
      <td>[Por Asignar]</td>
      <td>7 de abril de 2024</td>
    </tr>
    <tr>
      <td>Tarjetas de Notas (Note Live Cards)</td>
      <td>Se han definido tarjetas de notas para mostrar información relevante de manera visualmente atractiva.</td>
      <td>8 horas</td>
      <td>[Por Asignar]</td>
      <td>5 de abril de 2024</td>
    </tr>
  </tbody>
</table>

---
- 5.2.1.3. Development Evidence for Sprint Review.
- 5.2.1.4. Testing Suite Evidence for Sprint Review.
- 5.2.1.5. Execution Evidence for Sprint Review.
- 5.2.1.6. Services Documentation Evidence for Sprint Review.
- 5.2.1.7. Software Deployment Evidence for Sprint Review.
- 5.2.1.8. Team Collaboration Insights during Sprint.    
    
- 5.3. Validation Interviews.
- 5.3.1. Diseño de Entrevistas.
- 5.3.2. Registro de Entrevistas.
- 5.3.3. Evaluaciones según heurísticas.
- 5.3.4. Video About-the-Product.

## Conclusiones

- Conclusiones y recomendaciones.
- Video About-the-Team.

## Bibliografía 
## Anexos
