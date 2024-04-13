
# Contenido

## Tabla de contenidos
  - [0. Student Outcome](#0)
  - [1. Capítulo I: Introducción](#1-student-outcome-cap%C3%ADtulo-i-introducci%C3%B3n)
  - [2. Capítulo II: Requirements Elicitation & Analysis](#2-cap%C3%ADtulo-ii-requirements-elicitation--analysis)
  - [3. Capítulo III: Requirements Specification](#3-cap%C3%ADtulo-iii-requirements-specification)
  - [4. Capítulo IV: Product Design](#4-cap%C3%ADtulo-iv-product-design)
  - [5. Capítulo V: Product Implementation, Validation & Deployment](#5-cap%C3%ADtulo-v-product-implementation-validation--deployment)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliograf%C3%ADa)
- [Anexos](#anexos)

### 0. Student Outcome
Criterio específico | Acciones Realizadas | Conclusiones
------------------- | ------------------- | ------------
Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería. | Content Cell | Content Cell
Comunica en forma escrita ideas y/o resultados con objetividad apúblico de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería | Content Cell | Content Cell

### 1. Capítulo I: Introducción

- 1.1. Startup Profile
  - 1.1.1. Descripción de la Startup
    - PhysioDesk/Ergonomic-Style es la implementación de un modelo de un asistente virtual que brinda soluciones ergonómicas y ejercicios para personas que ocupan gran parte del día en el computador. La iniciativa busca analizar el estilo de vida del usuario con el fin de brindar las herramientas indicadas para aliviar y/o prevenir lesiones fisiológicas mediante un entorno ergonómico. Así mismo, recomendar la correcta postura y herramientas ergonómicas adecuadas para el usuario en función a su rango económico.

| Integrante                         | Descripción del Perfil                                                                                          |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------|
|  |  |
| Erick Joaquin Palomino Santa Cruz | Curso el quinto ciclo de la carrera de Ingeneria de Software. Me gusta aprender cosas nuevas y trabajar grupalmente para lograr una meta. |
| Anthony Jeandet Guerrero Castillo | Estudiante del sexto ciclo de Ingeniería de Software. Desde pequeño me ha gustado el mundo de la tecnología. Soy basante colaborativo. |
| Juan Pablo Ramos Mendoza | Me encuentro en el quinto ciclo de Ingeniería de Software. Al momento de trabajar en equipos trato de mantener el orden y recordar a los miembros las divisiones del trabajo, además de apoyar en cualquier parte que se requiera. |
| Giacomo Zoppi Rodriguez | Me encuentro estudiando para ser un Ingeniero de Software. Me destaco en el analisis de información, asi como actividades de creatividad e innovacion|                                                                                                                 |



- 1.2. Solution Profile
  - 1.2.1. Antecedentes y problemática

     #### ¿Cuál es el problema?
    El problema es la generación de lesiones fisiológicas causadas por falta de ergonomía en el entorno laboral. 
    
    #### ¿Cuándo sucede el problema?
    Sucede de manera continua a lo largo del día tras la exposición prolongada del uso del computador.
    #### ¿Dónde sucede el problema?
    Sucede dentro del hogar o centros laborales o en cualquier lugar donde se realicen actividades laborales que requieran.
    
    #### ¿A quién se le presenta el problema? ¿Cuál es tu público objetivo?
    A las personas, mayormente jóvenes de 21 a 30 años de edad.
    Incluye empleados de oficina y estudiantes de educación remota.
    
    #### ¿Por qué sucede el problema? ¿Qué situación ocasiona el problema?
    El problema sucede debido a la falta de un espacio ergonómico, asi como estar frente al computador por largas jornadas, sin estar informado de la correcta postura al sentarse.


    #### ¿Cómo sucede el problema? ¿Cuáles son las precondiciones para que se presente el problema?
    Comienzan a manifestarse por medio de una  exposición prolongada a condiciones ergonómicamente deficientes, esto incluye malas posturas, realizar movimientos repetitivos durante largos periodos de tiempo, como abusar del uso del celular, sobrecargar la posición del cuello, etc
    
    #### ¿Cuánto impacto genera este problema? Representar datos estadísticos del segmento que tiene el problema.
    Dentro del mismo estudio mencionado anteriormente, se logró determinar que:
    Según la Administración de Seguridad y Salud Ocupacional (OSHA) de EE. UU., las lesiones musculoesqueléticas  relacionadas con el trabajo, como el síndrome del túnel carpiano y el dolor lumbar, representan aproximadamente un tercio de todas las lesiones registradas en el lugar de trabajo.

    La OSHA también informa que los trabajadores que pasan muchas horas frente al computador tienen un mayor riesgo de desarrollar lesiones musculoesqueléticas debido a una mala ergonomía, como el uso incorrecto de la silla, la posición inadecuada del teclado y el ratón, y la falta de descansos regulares.

    Un estudio de la Asociación Internacional de Ergonomía y Salud Ocupacional encontró que el dolor musculoesquelético  relacionado con el trabajo es una de las principales causas de discapacidad laboral en todo el mundo, lo que resulta en costos significativos para los empleadores y la sociedad en general.
    
  - 1.2.2. Lean UX Process.
     Debido a la pandemia, se formalizaron las clases y trabajos remotos para ayudar a continuar con el desarrollo de los ciudadanos, sin embargo, diversas empresas, institutos y universidades optaron por normalizar el aprendizaje y las labores de manera virtual, por lo que las horas frente al computador aumentaron radicalmente. Esto genera diversos problemas, como la mala postura corporal, lo cual genera lesiones fisiológicas, las cuales de no ser tratadas pueden generar lesiones o atrofias permanentes. 


      Según la International Ergonomics Association (IEA), el problema radica en la falta de información de un correcto ambiente laboral ergonómico. Ya que las personas no toman en cuenta su postura en sus horas laborales o de estudio, por lo que genera dolencias en el sistema locomotor que agrupa los huesos, músculos, nervios y articulaciones. Las lesiones más comunes identificadas son la cervicalgia, “codo del programador”, dorsalgia, artritis, lumbalgia, tortícolis, tendinitis, túnel del carpo o carpiano, hombro doloroso y cifosis. 

      Se realizó un estudio en la Dirección Regional de Salud Tacna en el año 2022, en la cual se evaluaron a 45 trabajadores administrativos con modalidad de trabajo remoto, se utilizaron una herramienta de medición de la vértebra cervical y un 100% de los evaluados presentaron síndrome de dolor cervical. Se encontró un nivel leve del 61.4% y un 6.8% moderado. Por lo que se concluye que se debe crear conciencia y capacitación de un ambiente laboral para prevenir las lesiones fisiológicas.  

      Nuestra tarea es encontrar una solución integral que aborde estas preocupaciones y mejore el estilo de vida de los usuarios. Nuestras interrogantes serían: ¿Cómo podemos garantizar que las personas tengan acceso fácil a una variedad de recursos, reciban información clara sobre la correcta forma de sentarse  y disfruten de una experiencia de soporte,  rehabilitación y altamente personalizada? ¿Cómo podemos simplificar el proceso y brindar orientación a los clientes para que tengan una experiencia excepcional en el tratamiento?

      
    - 1.2.2.2. Lean UX Assumptions.
  
      **Bussines Outcomes:**
        - Evaluar la efectividad de los ejercicios fisioterapéuticos mediante sesiones diarias programadas.
        - Recomendar la correcta postura y herramientas ergonómicas adecuadas para el usuario en función a su rango económico.
        - Desarrollar un sistema de seguimiento por medio de recopilación de datos con el fin de optimizar y personalizar los ejercicios adecuados según la lesión.
        - Diseñar una plataforma interactiva donde el usuario pueda, mediante una imagen 3D del cuerpo humano, señalar la ubicación de su lesión.

      **Features:**
	- Asistente Virtual Ergonómico: Un asistente virtual que proporciona recomendaciones personalizadas sobre ergonomía y ejercicios para mejorar la postura y prevenir lesiones fisiológicas causadas por el uso prolongado del computador.

	- Análisis de Estilo de Vida: Funcionalidad que analiza el estilo de vida del usuario, incluyendo sus hábitos de trabajo y descanso, para ofrecer recomendaciones específicas y adaptadas a sus necesidades individuales.

	- Recomendaciones de Postura y Herramientas Ergonómicas: Recomendaciones sobre la postura adecuada al sentarse frente al computador, así como sugerencias para la adquisición de herramientas ergonómicas según el presupuesto del usuario.

	- Entorno Ergonómico Personalizado: Herramientas para personalizar el entorno de trabajo del usuario, incluyendo ajustes de silla, monitor, teclado y ratón, para asegurar una postura óptima durante las horas de trabajo.

	- Recordatorios y Notificaciones: Funcionalidad de recordatorios y notificaciones para recordar al usuario tomar descansos regulares, realizar ejercicios de estiramiento y ajustar su postura durante las largas sesiones frente al computador.

	- Seguimiento y Registro de Progreso: Capacidad para realizar un seguimiento y registrar el progreso del usuario en la mejora de su postura y la prevención de lesiones fisiológicas, proporcionando retroalimentación y motivación adicional.

	- Biblioteca de Ejercicios Ergonómicos: Acceso a una biblioteca de ejercicios ergonómicos recomendados por profesionales de la salud, con instrucciones paso a paso y videos demostrativos para una correcta ejecución.

	- Chat en Vivo con Expertos: Posibilidad de comunicarse con expertos en ergonomía a través de un chat en vivo integrado en la plataforma, para recibir asesoramiento personalizado y respuestas a preguntas específicas sobre salud y postura.
     
    
      **User Outcomes:**
        ##### Para los Usuarios:
        - Proporcionar a los usuarios una amplia gama de consejos y herramientas ergonómicas.
        - Ayudar a los usuarios a planificar las sesiones y reservarlas para una experiencia personalizada.
        - Facilitar la interacción de los clientes con los fisioterapeutas y proporcionar una orientación personalizada para que disfruten de su experiencia.

        ##### Para las Empresas de inmuebles ergonómicos:
        - Permitir a las empresas llegar a un público más amplio y aumentar sus ingresos a través de las compras por medio de los usuarios.
        - Facilitar el envío de los productos y la comunicación de los clientes, lo que les permite ofrecer un servicio selección de alta calidad.

    - 1.2.2.3. Lean UX Hypothesis Statements.
      
	- Creemos que al ofrecer recomendaciones personalizadas de ergonomía y ejercicios a través de un asistente virtual, los usuarios mejorarán su postura y reducirán el riesgo de lesiones fisiológicas.
	Sabremos esto cuando observemos una disminución en las quejas de dolor relacionadas con el trabajo y una mayor adherencia a las recomendaciones ergonómicas.

	- Creemos que al proporcionar herramientas para ajustar el entorno de trabajo del usuario, como la silla y el monitor, podremos mejorar la postura y la comodidad durante las horas de trabajo.
	Sabremos esto cuando notemos una mejora en la ergonomía del espacio de trabajo y una disminución en las molestias físicas reportadas por los usuarios.

	- Creemos que al enviar recordatorios y notificaciones para tomar descansos regulares y realizar ejercicios de estiramiento, los usuarios desarrollarán hábitos más saludables frente al computador.
	Sabremos esto cuando veamos un aumento en la frecuencia de los descansos tomados por los usuarios y una reducción en la fatiga y el malestar asociados con el trabajo prolongado.

	- Creemos que al ofrecer acceso a una biblioteca de ejercicios ergonómicos, los usuarios mejorarán su conocimiento sobre cómo cuidar su salud postural.
	Sabremos esto cuando observemos un aumento en la participación de los usuarios con la biblioteca de ejercicios y una mayor autoeficacia percibida en el manejo de su bienestar físico.

	- Creemos que al facilitar el acceso a expertos en ergonomía a través de un chat en vivo integrado, los usuarios recibirán orientación personalizada y respuestas a sus preguntas específicas sobre salud y postura.
	Sabremos esto cuando notemos una mayor interacción de los usuarios con el chat en vivo y una mejora en su comprensión de los principios ergonómicos aplicados a su situación individual.

    - 1.2.2.4. Lean UX Canvas.
- 1.3. Segmentos objetivo.
  
  #### Segmento objetivo 1: Usuarios 
  **Aspectos demográficos:**
	- **Sexo:** Ambos sexos.
	- **Edades:** Adultos jóvenes y adultos de mediana edad (18-45 años).
	- **Nivel socioeconómico:** Medio a medio-alto.
   
  **Aspectos geográficos:**
  	- **Nacionalidad:** Sin restricciones, pero principalmente dirigido a países con una alta tasa de uso de computadoras en el trabajo.
	- **Zona geográfica en la que viven:** Principalmente áreas urbanas y suburbanas.
   
  **Aspectos psicográficos:**
	- Personas que trabajan en entornos de oficina o desde casa.
	- Personas preocupadas por su salud y bienestar.
	- Individuos interesados en la prevención de lesiones relacionadas con el trabajo.

  #### Segmento objetivo 2: Profesionales de Ergonomia
  **Aspectos demográficos:**
	- **Sexo:** Ambos sexos.
	- **Edades:** Adultos jóvenes y adultos de mediana edad (25-45 años).
	- **Nivel socioeconómico:** Diverso, desde medio a alto.

  **Aspectos geográficos:**
	- **Nacionalidad:** Sin restricciones, pero enfocado en áreas urbanas y suburbanas con una alta concentración de profesionales.
	- **Zona geográfica en la que viven:** Principalmente áreas urbanas y suburbanas, donde se encuentran oficinas y centros de trabajo.

  **Aspectos psicográficos:**
	- Profesionales comprometidos con su salud y bienestar laboral.
	- Individuos que valoran la eficiencia y el rendimiento en su trabajo.
	- Profesionales que buscan mejorar su calidad de vida en el entorno laboral.
	- Aquellos dispuestos a invertir en soluciones ergonómicas para aumentar su comodidad y productividad en el trabajo.


### 2. Capítulo II: Requirements Elicitation & Analysis

- 2.1. Competidores.
  
	Para PhysioDesk, una plataforma especializada en soluciones ergonómicas y ejercicios terapéuticos para individuos que pasan largas horas frente al ordenador, los competidores podrían incluir:

	1. **ErgoPlus:** Una empresa que ofrece software de evaluación ergonómica y soluciones de mobiliario diseñadas para mejorar la postura y prevenir lesiones relacionadas con la ergonomía en entornos de trabajo.

	2. **MyFitnessPal:** Una popular aplicación de salud y fitness que incluye ejercicios específicos para mejorar la postura, fortalecer músculos y reducir el riesgo de lesiones, adaptados para personas que trabajan en oficinas.

	3. **Herman Miller:** Una empresa reconocida por proporcionar soluciones ergonómicas para entornos de oficina, incluyendo software, accesorios y mobiliario diseñado para mejorar la salud y el bienestar de los trabajadores.

	4. **PhysioAdvisor:** Una aplicación de fisioterapia que ofrece ejercicios terapéuticos y recomendaciones para mejorar la postura y tratar lesiones relacionadas con el trabajo de oficina.

	Estas empresas representan algunos de los competidores existentes en el mercado de aplicaciones ergonómicas y de salud, compitiendo por la preferencia de usuarios comprometidos con su salud y bienestar mientras trabajan en entornos informáticos.

- 2.2. Analisis Competitivo

### Perfil de la Startup

| Competidor | PhysioDesk | ErgoPlus | MyFitnessPal | PhysioAdvisor |
|------------|------------|----------|--------------|---------------|
| Origen     | Perú | Estados Unidos | Estados Unidos | Australia |
| Descripción General | PhysioDesk es una plataforma especializada en soluciones ergonómicas y ejercicios terapéuticos para individuos que pasan largas horas frente al ordenador. Su enfoque se centra en proporcionar herramientas efectivas para mejorar la postura y prevenir lesiones relacionadas con la ergonomía. | ErgoPlus ofrece software de evaluación ergonómica y soluciones de mobiliario diseñadas para mejorar la postura y prevenir lesiones relacionadas con la ergonomía en entornos de trabajo. | MyFitnessPal es una popular aplicación de salud y fitness que incluye ejercicios específicos para mejorar la postura, fortalecer músculos y reducir el riesgo de lesiones, adaptados para personas que trabajan en oficinas. | PhysioAdvisor es una aplicación de fisioterapia que ofrece ejercicios terapéuticos y recomendaciones para mejorar la postura y tratar lesiones relacionadas con el trabajo de oficina. |
| Ventaja competitiva ¿Qué valor ofrece a los clientes? | PhysioDesk ofrece una solución integral para mejorar la salud y bienestar de los trabajadores de oficina mediante ejercicios ergonómicos y terapéuticos adaptados a sus necesidades. Su enfoque especializado y herramientas efectivas lo hacen una opción atractiva para individuos preocupados por su salud en el entorno laboral. | ErgoPlus destaca por ofrecer soluciones ergonómicas personalizadas y software de evaluación para mejorar la postura y prevenir lesiones en el lugar de trabajo. Su enfoque en la ergonomía y la prevención de lesiones lo convierte en una opción popular para empresas preocupadas por el bienestar de sus empleados. | MyFitnessPal ofrece una amplia gama de ejercicios y herramientas de salud adaptadas para individuos que desean mejorar su bienestar físico, incluyendo opciones específicas para mejorar la postura y reducir el riesgo de lesiones relacionadas con el trabajo de oficina. | PhysioAdvisor proporciona una variedad de ejercicios terapéuticos y recomendaciones para mejorar la postura y tratar lesiones relacionadas con el trabajo de oficina, adaptados para las necesidades individuales de los usuarios. Su enfoque en la fisioterapia lo hace una opción valiosa para quienes buscan tratamientos efectivos y personalizados. |

### Perfil de Marketing

| Competidor | PhysioDesk | ErgoPlus | MyFitnessPal | PhysioAdvisor |
|------------|------------|----------|--------------|---------------|
| Mercado Objetivo | PhysioDesk se dirige a trabajadores de oficina y empresas que buscan soluciones ergonómicas efectivas para mejorar la salud y el bienestar en el entorno laboral. | ErgoPlus está orientado a empresas y profesionales preocupados por la ergonomía en el lugar de trabajo, ofreciendo soluciones personalizadas para mejorar la postura y prevenir lesiones. | MyFitnessPal se enfoca en individuos interesados en mejorar su salud y bienestar físico, incluyendo aquellos que trabajan en oficinas y buscan opciones específicas para mejorar la postura y reducir el riesgo de lesiones. | PhysioAdvisor está dirigido a personas que buscan tratamientos terapéuticos y ejercicios para mejorar la postura y tratar lesiones relacionadas con el trabajo de oficina, ofreciendo opciones personalizadas para sus necesidades específicas. |
| Estrategias de Marketing | - Campañas de marketing dirigidas a empresas y trabajadores de oficina, resaltando los beneficios de utilizar PhysioDesk para mejorar la salud y el bienestar en el entorno laboral. - Promoción en redes sociales y blogs especializados en ergonomía y salud en el trabajo. - Colaboración con empresas y organizaciones para la implementación de programas de salud y bienestar en el lugar de trabajo. | - Publicidad dirigida a empresas y profesionales preocupados por la ergonomía en el lugar de trabajo, destacando las soluciones personalizadas y software de evaluación de ErgoPlus. - Participación en ferias y eventos de salud y seguridad laboral para promover la marca y sus servicios. - Programas de afiliados y referencias para ampliar la base de clientes. | - Estrategias de marketing enfocadas en la salud y el bienestar, destacando los beneficios de utilizar MyFitnessPal para mejorar la postura y reducir el riesgo de lesiones. - Publicidad en plataformas digitales y redes sociales dirigida a usuarios interesados en fitness y salud en el trabajo. - Colaboración con expertos en salud y fitness para crear contenido relevante y educativo. | - Promoción de PhysioAdvisor como una solución efectiva para mejorar la postura y tratar lesiones relacionadas con el trabajo de oficina, a través de campañas de marketing dirigidas a individuos preocupados por su salud y bienestar. - Publicidad en plataformas digitales y redes sociales especializadas en fisioterapia y salud en el trabajo. - Colaboración con fisioterapeutas y profesionales de la salud para respaldar la efectividad de los tratamientos y ejercicios ofrecidos por PhysioAdvisor. |

### Perfil del Producto

| Competidor | PhysioDesk | ErgoPlus | MyFitnessPal | PhysioAdvisor |
|------------|------------|----------|--------------|---------------|
| Características y servicios | - Ejercicios ergonómicos y terapéuticos diseñados para mejorar la postura y prevenir lesiones relacionadas con el trabajo de oficina. - Herramientas de seguimiento y análisis para evaluar el progreso y la efectividad de los ejercicios. - Integración con dispositivos y accesorios ergonómicos para una experiencia completa. | - Software de evaluación ergonómica para identificar riesgos y áreas de mejora en el entorno de trabajo. - Soluciones de mobiliario diseñadas para mejorar la postura y prevenir lesiones musculoesqueléticas. - Servicios de consultoría y capacitación para implementar programas de ergonomía en empresas. | - Amplia variedad de ejercicios y rutinas de fitness adaptadas para mejorar la postura y reducir el riesgo de lesiones relacionadas con el trabajo. - Herramientas de seguimiento de la actividad física y la nutrición para un enfoque integral en la salud y el bienestar. - Comunidad en línea para compartir experiencias y consejos de fitness. | - Ejercicios terapéuticos y recomendaciones para mejorar la postura y tratar lesiones musculoesqueléticas relacionadas con el trabajo de oficina. - Información detallada sobre técnicas de fisioterapia y prevención de lesiones. - Asesoramiento personalizado de fisioterapeutas y expertos en salud ocupacional. |

### Análisis SWOT

| Competidor | PhysioDesk | ErgoPlus | MyFitnessPal | PhysioAdvisor |
|------------|------------|----------|--------------|---------------|
| Fortalezas | - Enfoque especializado en soluciones ergonómicas y terapéuticas para el entorno laboral. - Herramientas efectivas y personalizadas para mejorar la postura y prevenir lesiones. - Integración con dispositivos y accesorios ergonómicos para una experiencia completa. | - Amplia experiencia en soluciones ergonómicas para empresas. - Software de evaluación ergonómica y soluciones de mobiliario diseñadas para mejorar la postura y prevenir lesiones musculoesqueléticas. - Servicios de consultoría y capacitación para implementar programas de ergonomía en empresas. | - Amplia variedad de ejercicios y herramientas de seguimiento de la actividad física para mejorar la salud y el bienestar. - Comunidad en línea para compartir experiencias y consejos de fitness. - Popularidad y reconocimiento de la marca MyFitnessPal. | - Enfoque especializado en fisioterapia y tratamiento de lesiones musculoesqueléticas relacionadas con el trabajo de oficina. - Información detallada y asesoramiento personalizado de fisioterapeutas y expertos en salud ocupacional. - Credibilidad y confianza de los usuarios en la efectividad de los tratamientos ofrecidos por PhysioAdvisor. |
| Debilidades | - Menor reconocimiento de marca en comparación con competidores establecidos en el mercado de salud y bienestar. - Limitaciones en la capacidad de alcance y promoción en comparación con competidores más grandes. | - Dependencia de la demanda de soluciones ergonómicas por parte de empresas y profesionales de la salud ocupacional. - Limitaciones en la capacidad de promoción y alcance en comparación con competidores con mayor reconocimiento de marca. | - Vulnerabilidad a cambios en las preferencias del usuario y la competencia en el mercado de salud y bienestar. - Dependencia de la suscripción de usuarios para la generación de ingresos. - Competencia directa con otras aplicaciones de fitness y salud en el mercado. | - Dependencia de la demanda de tratamientos terapéuticos y fisioterapia relacionados con el trabajo de oficina. - Limitaciones en la capacidad de promoción y alcance en comparación con competidores más grandes. - Competencia directa con otras aplicaciones y servicios de fisioterapia en el mercado. |
| Oportunidades | - Aumento de la conciencia sobre la importancia de la salud y el bienestar en el entorno laboral. - Expansión del mercado de salud y bienestar con el crecimiento de la fuerza laboral remota. - Colaboraciones estratégicas con empresas y profesionales de la salud ocupacional para promover la adopción de PhysioDesk. | - Crecimiento del mercado de salud ocupacional y ergonomía en empresas preocupadas por el bienestar de sus empleados. - Expansión internacional a nuevos mercados emergentes con una demanda creciente de soluciones ergonómicas. - Desarrollo de nuevas características y soluciones para abordar las necesidades cambiantes del mercado. | - Expansión del mercado de fitness y salud con el aumento de la conciencia sobre la importancia de la actividad física y la nutrición. - Colaboraciones estratégicas con empresas de tecnología y dispositivos para integrar MyFitnessPal en productos y servicios existentes. - Desarrollo y mejora continua de nuevas características y herramientas para mantener la relevancia en el mercado. | - Aumento de la demanda de tratamientos terapéuticos y fisioterapia en el entorno laboral. - Colaboraciones con empresas y profesionales de la salud para la promoción y adopción de PhysioAdvisor. - Desarrollo de nuevas características y servicios para abordar las necesidades cambiantes del mercado de salud ocupacional. |
| Amenazas | - Competencia intensa de empresas establecidas en el mercado de salud y bienestar. - Riesgos de seguridad y privacidad asociados con el almacenamiento y procesamiento de datos de usuarios. - Cambios en las regulaciones y políticas gubernamentales que pueden afectar la operación y la expansión internacional de PhysioDesk. | - Competencia de otras empresas de ergonomía y soluciones de salud ocupacional con mayor reconocimiento de marca y recursos financieros. - Vulnerabilidades de seguridad y riesgos de privacidad asociados con el almacenamiento y procesamiento de datos de clientes. - Cambios en las regulaciones y políticas gubernamentales que pueden afectar la industria de la salud ocupacional y ergonomía. | - Competencia de otras aplicaciones de fitness y salud en el mercado, que pueden ofrecer características similares y una experiencia de usuario comparable. - Amenazas de seguridad cibernética y violaciones de datos que pueden socavar la confianza del usuario en la plataforma. - Cambios en las preferencias y necesidades del usuario que pueden afectar la demanda de servicios de fitness y salud en línea. | - Competencia de otras aplicaciones y servicios de fisioterapia en el mercado, que pueden ofrecer tratamientos similares y una experiencia de usuario comparable. - Amenazas de seguridad cibernética y violaciones de datos que pueden socavar la confianza del usuario en la plataforma. - Cambios en las preferencias y necesidades del usuario que pueden afectar la demanda de servicios de fisioterapia en línea. |

- 2.3. Estrategias y tácticas frente a competidores.
  
## Estrategias:

| Estrategia                           | Descripción                                                                                                                         |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|
| Enfoque en Soluciones Ergonómicas   | Centrarse en proporcionar soluciones ergonómicas efectivas para mejorar la salud y el bienestar de los trabajadores de oficina.      |
| Personalización de Servicios        | Ofrecer servicios personalizados adaptados a las necesidades específicas de cada cliente para maximizar su efectividad y satisfacción.|
| Colaboración con Profesionales de la Salud | Establecer asociaciones con fisioterapeutas y expertos en salud ocupacional para respaldar la efectividad de los servicios ofrecidos.|
	
 ## Tácticas:

| Táctica                                          | Descripción                                                                                                                            |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| Desarrollar Programas de Ejercicios Personalizados | Crear programas de ejercicios personalizados según las necesidades individuales de los usuarios para obtener mejores resultados.   |
| Ofrecer Consultas Virtuales con Expertos         | Proporcionar la opción de consultas virtuales con fisioterapeutas y profesionales de la salud para obtener asesoramiento personalizado. |
| Colaborar con Empresas para Programas de Bienestar| Establecer colaboraciones con empresas para implementar programas de bienestar en el lugar de trabajo, incluyendo el uso de PhysioDesk.|
| Promoción en Eventos de Salud y Bienestar        | Participar en eventos de salud y bienestar para promover los servicios de PhysioDesk y aumentar su visibilidad en el mercado.           |
| Crear Contenido Educativo y de Sensibilización   | Desarrollar contenido educativo sobre ergonomía y salud en el trabajo para sensibilizar a los usuarios sobre la importancia del cuidado corporal. |

  
- 2.4. Entrevistas.
  - 2.4.1. Diseño de entrevistas.
  	#### Para el segmento de usuarios:

	1. ¿Cuáles son los principales problemas de salud relacionados con el trabajo de oficina que enfrentas en tu día a día?
	2. ¿Qué tipo de soluciones o herramientas has utilizado previamente para mejorar tu postura y prevenir lesiones relacionadas con la ergonomía?
	3. ¿Qué aspectos consideras más importantes al elegir una plataforma o aplicación para mejorar tu salud y bienestar en el entorno laboral?
	4. ¿Qué tipo de ejercicios o rutinas de fitness te resultan más efectivos para contrarrestar los efectos negativos de pasar largas horas frente al ordenador?
	5. ¿Cuál es tu nivel de interés en utilizar tecnología como PhysioDesk para mejorar tu salud en el trabajo?
	6. ¿Qué características o funcionalidades esperarías encontrar en una plataforma diseñada para mejorar la salud y bienestar en el entorno laboral?
	7. ¿Has experimentado algún beneficio tangible al utilizar herramientas o aplicaciones para mejorar tu postura y salud en el trabajo?
	8. ¿Qué obstáculos crees que podrían impedirte utilizar una plataforma como PhysioDesk de manera regular?
	9. ¿Qué tan importante es para ti recibir recomendaciones personalizadas y seguimiento de tu progreso al utilizar una plataforma de salud en el trabajo?
	10. ¿Cómo crees que una plataforma como PhysioDesk podría integrarse mejor en tu rutina diaria de trabajo?

	#### Para el segmento profesional:

	1. ¿Qué desafíos enfrenta habitualmente al tratar con problemas de salud relacionados con la postura y la ergonomía en su práctica?
	2. ¿Qué herramientas o recursos utiliza actualmente para evaluar y abordar los problemas ergonómicos de sus pacientes?
	3. ¿Qué características considera más importantes al evaluar una plataforma o herramienta digital para su práctica profesional?
	4. ¿Cómo cree que una plataforma como PhysioDesk podría beneficiar su trabajo diario y mejorar los resultados del tratamiento para sus pacientes?
	5. ¿Cuál es su opinión sobre la integración de tecnología en la práctica de la fisioterapia y la promoción de la salud ergonómica?
	6. ¿Qué funciones específicas le gustaría ver en una plataforma diseñada para profesionales de la salud, como PhysioDesk?
	7. ¿Cómo se asegura de mantenerse actualizado sobre las últimas investigaciones y avances en el campo de la ergonomía y la fisioterapia?
	8. ¿Cuál es su enfoque para capacitar a sus pacientes en prácticas ergonómicas y promover la salud postural fuera del entorno clínico?
	9. ¿Cómo evalúa el éxito del tratamiento ergonómico en sus pacientes y qué métricas utiliza para medirlo?
	1¿Qué desafíos anticipa al adoptar una nueva plataforma o herramienta digital en su práctica profesional, y cómo planea superarlos?

  
  - 2.4.2. Registro de entrevistas.

	- Usuarios:
      	- Entrevista #1:
  	![Imagen de WhatsApp 2024-04-13 a las 02 05 38_3c2aa5f7](https://github.com/PhysioDesk/Informes/assets/127764958/9cd6d5ed-cbbf-4f2c-922f-941c9d9ab121)
	Entrevistado: Maria Lucia Paez<br>
 	Entrevistador: Erick Joaquin Palomino Santa Cruz<br>
  	Duracion: 05:19<br>
   	Link: https://youtu.be/7mP6-3dtAM8?si=7I2ffvJz830Z_dSs <br>
    	Resumen: La entrevista enfatiza la importancia de una plataforma de salud con una interfaz atractiva y fácil de usar, así como la atención personalizada. Se menciona la integración de PhysioDesk en la rutina diaria para mejorar la postura.

	- Profesional:
		- Entrevista #2:
		![image](https://github.com/PhysioDesk/Informes/assets/89022078/71b761e7-b69e-48a3-9c8d-659a11d83578)
		Entrevistado: Kevin Quintana Cauti<br>
		Entrevistador: Anthony Jeandet Guerrero Castillo<br>
		Duracion: 07:37<br>
		Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202010054_upc_edu_pe/ERP_ICuU7vFOo6UU5kwRIT4BgZ2Y3powGDwu2qtq7wSHpg?e=HSbS7l&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D <br>
		Resumen: La entrevista resalta los métodos que utilizan a día de hoy los fisioterapeutas para tratar con sus clientes. Se puede destacar que la tecnología llega para mejorar los aspectos críticos del mercado, facilitando la comunicación entre profesional y cliente, mediante una aplicación web, donde el fisioterapeuta podrá brindar sus servicios. Todo ello mejorará la organización de tiempos y ayudará a llegar a más clientes.

- 2.4.3. Análisis de entrevistas.
  	## Entrevista 1: Maria Lucia Paez Cairo
  	- En la entrevista, Maria Lucia Paez discute los problemas de salud relacionados con el trabajo de oficina, como el dolor en las articulaciones y la zona lumbar. No ha utilizado herramientas específicas, pero realiza ejercicios para mejorar su postura. Destaca la importancia de una plataforma de salud que se adapte al usuario y proteja la privacidad. Muestra interés en tecnologías como Seiko Desk y valora la atención personalizada en las plataformas de salud. Ve la integración de PhysioDesk en su rutina diaria como la adquisición de un hábito para mejorar su postura.
 
	## Entrevista 2: Kevin Quintana Cauti
	- El fisioterapeuta identificó desafíos comunes en la falta de conciencia sobre la postura y la dificultad para cambiar hábitos. Utiliza evaluaciones físicas y herramientas de medición para abordar estos problemas. Valora la accesibilidad y personalización en plataformas digitales como PhysioDesk, que simplificarían la gestión de datos y mejorarían la participación del paciente. Cree en el poder de la tecnología para mejorar la fisioterapia y enfatiza la importancia de mantenerse actualizado. Utiliza demostraciones prácticas y recursos digitales para educar a los pacientes. Evalúa el éxito del tratamiento por la mejora de síntomas y la reducción de lesiones relacionadas con la ergonomía. Planea superar desafíos en la adopción de nuevas plataformas mediante planificación y colaboración con proveedores confiables.
- 2.5. Needfinding.

	# User Personas.
  	Con el propósito de profundizar en nuestra comprensión de nuestro público objetivo, hemos analizado la información recopilada de entrevistas previas. A partir de este análisis, hemos creado un "User Persona" para cada segmento objetivo, una representación ficticia de un usuario típico dentro de nuestro segmento. Este perfil detallado incluye información sobre la personalidad, historia, motivaciones, objetivos y desafíos del usuario. Esta herramienta será invaluable para nuestro equipo, ya que nos permitirá establecer una conexión más sólida con el cliente ideal de nuestro producto, lo que a su vez nos ayudará a desarrollar mejoras que satisfagan de manera óptima las necesidades de nuestros usuarios.

	### Para el segmento Usuarios
  ![Imagen de WhatsApp 2024-04-03 a las 23 09 43_ff0742ff](https://github.com/PhysioDesk/Informes/assets/127764958/9dbf4033-db47-4f9a-add9-e9225702b446)

	### Para el segmento Empresa
  ![Carlos Rivera](https://github.com/PhysioDesk/Informes/assets/127764958/044a5c69-9378-4082-a8ca-d7e611a131fc)


- 2.7. User Task Matrix.
### Bruno Moises   
| Actividades                                                 | Frecuencia    | Importancia |
|-------------------------------------------------------------|---------------|-------------|
| Realizar ejercicios ergonómicos y terapéuticos             | Diariamente   | Alta        |
| Seguir programas de ejercicios personalizados              | Regularmente | Alta        |
| Utilizar herramientas de seguimiento y análisis del progreso | Regularmente | Media       |
| Integrar dispositivos ergonómicos en la rutina de trabajo  | A veces       | Alta        |
| Participar en sesiones de consulta y capacitación           | A veces       | Media       |
| Compartir experiencias y consejos en la comunidad en línea  | A veces       | Baja        |

  ### Carlos Zapata
| Actividades                                                 | Frecuencia    | Importancia |
|-------------------------------------------------------------|---------------|-------------|
| Evaluar riesgos ergonómicos en el entorno de trabajo        | Regularmente | Alta        |
| Implementar soluciones ergonómicas personalizadas           | Regularmente | Alta        |
| Utilizar software de evaluación ergonómica                  | Diariamente   | Alta        |
| Capacitar al personal en prácticas ergonómicas              | A veces       | Media       |
| Participar en programas de bienestar en el lugar de trabajo | A veces       | Alta        |
| Promover la cultura de la ergonomía en la empresa           | A veces       | Alta        |

- 2.8. User Journey Mapping.
  	### Segmento Usuario
  	![Imagen de WhatsApp 2024-04-05 a las 23 29 42_88b954a1](https://github.com/PhysioDesk/Informes/assets/127764958/c5043a5c-a075-45d1-aa29-9f6917ba8497)

 	### Segmento Profesional
  	![Imagen de WhatsApp 2024-04-05 a las 23 36 36_f7fe5a61](https://github.com/PhysioDesk/Informes/assets/127764958/366f487e-368b-46ca-9f7d-c3f00f7ffeea)

- 2.9. Empathy Mapping.
  	### Segmento Usuario
  	![Empathy map Usuario](https://github.com/PhysioDesk/Informes/assets/127764958/813dff6d-4f06-4ed7-9fcc-efe4addb213b)

 	### Segmento Profesional
  	![Imagen de WhatsApp 2024-04-06 a las 01 09 50_9aba3370](https://github.com/PhysioDesk/Informes/assets/127764958/f9c4c366-46cd-4285-ae3c-d3517b7fcae3)

- 2.10. As-is Scenario Mapping.
  	### Segmento Usuario
  	![Imagen de WhatsApp 2024-04-06 a las 01 22 47_0b14448b](https://github.com/PhysioDesk/Informes/assets/127764958/fc8c80d6-0ec9-45cb-834d-934a33a3fe22)

 	### Segmento Profesional
  	![Imagen de WhatsApp 2024-04-06 a las 08 56 04_deebcd1f](https://github.com/PhysioDesk/Informes/assets/127764958/0173bf4b-94b5-4e78-b85b-6651e8c36796)

- 2.11. Ubiquitous Language.
  ### Términos y Conceptos
  
 	 1. **PhysioDesk**: El nombre del proyecto en sí mismo, que se refiere a la plataforma y al asistente virtual diseñado para proporcionar soluciones ergonómicas y ejercicios para usuarios que pasan mucho tiempo frente al computador.

	2. **Asistente Virtual**: El componente de software de PhysioDesk que interactúa con los usuarios, recopila datos, ofrece recomendaciones ergonómicas y proporciona asistencia personalizada para mejorar la salud y el bienestar en el entorno laboral.

	3. **Usuario**: Cualquier persona que utilice PhysioDesk para recibir recomendaciones ergonómicas y realizar ejercicios para mejorar su salud y bienestar mientras trabaja frente al computador.

	4. **Soluciones Ergonómicas**: Las recomendaciones, consejos y sugerencias proporcionadas por PhysioDesk para mejorar la postura, configuración del lugar de trabajo y hábitos de trabajo del usuario con el fin de prevenir lesiones y mejorar el bienestar.

	5. **Ejercicios Ergonómicos**: Rutinas de ejercicios diseñadas para aliviar la tensión muscular, mejorar la flexibilidad y promover una postura saludable mientras se trabaja frente al computador.

	6. **Configuración del Lugar de Trabajo**: La disposición física y ergonómica de los elementos del entorno laboral, como la altura del monitor, la posición del teclado y la silla, que pueden influir en la comodidad y la salud del usuario.

	7. **Pausas Activas**: Breves interrupciones en el trabajo para realizar ejercicios de estiramiento, movimientos y respiración diseñados para reducir la fatiga y mejorar la concentración.

	8. **Productos Ergonómicos**: Herramientas, dispositivos y accesorios diseñados para mejorar la ergonomía y la comodidad en el entorno laboral, como sillas de oficina ajustables, soportes para monitor y teclados ergonómicos.



### 3. Capítulo III: Requirements Specification

- 3.1. To-Be Scenario Mapping.
- 3.2. User Stories.
- 3.3. Impact Mapping.
- 3.4. Product Backlog.


  

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
  	[UxPressia](http://uxpressia.com/w/pFiiX ) :Para la elaboración de los User persona, User Task Matrix e Impact Map. 
	Miro/LucidChart: Elboración de As-Is y To-Be, Wireflows, User Flows y los diagramas de UML. 
	[Vertabelo](https://my.vertabelo.com/drive ): Elaboración de los 
	[Figma](https://www.figma.com ): Elaboración de Wireframes, Mock-ups y Prototypes
	HTML, CSS3 y Javascript para la elaboración del Landing Page
	[Visual Studio Code:](https://code.visualstudio.com/download) Para la elaboración del Landing Page 
	[Github](https://github.com): Se utilizará para el control y almacenamiento de nuestro codigo, junto a GitFlow
	[M editor.md](https://pandao.github.io/editor.md/en.html#H2%20header): Para la edición de archivos tipo .md o Markdown. 
	[Trello](https://trello.com/es ): Para la división y organización de Tasks. 
	[Microsoft 365](https://www.microsoft.com/es-es/microsoft-365/try?culture=es-es&country=es): Para la elaboración del Keynote y la presentación de nuestro proyecto en Power Point. 
	[Zoom(64 bits)](https://zoom.us/client/latest/ZoomRooms.exe?archType=x64 ) : Para la elaboración de las entrevistas de nuestro proyecto. 
	[Google Meets:](https://meet.google.com "Google Meets:") Para la organización y las reuniones virtuales de grupo.


  - 5.1.2. Source Code Management.
  
Según la obra de Vinven Dreissen, el modelo de Git de branching permite gestionar ramas de un proyecto, asi como facilitar el flujo de trabajo. Partimos con una main branch o rama principal y seguimos con una branch: AAAAA. Hacer una x cada feature

Respecto, a las Release branches y Hotfix branches, incluimos las siguientes convenciones: 

Usamos nombres como AAAA, aplicando Semanting Versioning para nombrar nuestras Releases y Conventional Commits para los textos de mensajes en nuestros commits. 




Link del Landing Page: 
  - 5.1.3. Source Code Style Guide & Conventions.
Aquí el equipo explica e indica las referencias que adoptará para nombrar elementos
y programar en los lenguajes que se utilizan en la solución (en este caso HTML, CSS,
JavaScript, TypeScript, Java, así como Gherkin para los archivos .feature). Para todos
los lenguajes debe aplicar la nomenclatura en inglés. Adicionalmente, adopte
convenciones estándares para coding (Vea “HTML Style Guide and Coding
Conventions”, “Google HTML/CSS Style Guide”, “Gherkin Conventions for Readable
Specifications”, “Angular coding style guide”, “Google Java Style Guide”, “Google
TypeScript Style Guide” y “Spring Boot Features” en la sección de Referencias).
  - 5.1.4. Software Deployment Configuration.
como se despliega el landing page, a partir de los repositorios de codigo fuente. 

- 5.2. Landing Page, Services & Applications Implementation.
  - 5.2.1. Sprint n
    - 5.2.1.1. Sprint Planning.
    - 5.2.1.2. Sprint Backlog.


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
