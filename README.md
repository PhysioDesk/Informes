
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
     
    
      **User Outcomes:**
        ##### Para los Usuarios:
        - Proporcionar a los usuarios una amplia gama de consejos y herramientas ergonómicas.
        - Ayudar a los usuarios a planificar las sesiones y reservarlas para una experiencia personalizada.
        - Facilitar la interacción de los clientes con los fisioterapeutas y proporcionar una orientación personalizada para que disfruten de su experiencia.

        ##### Para las Empresas de inmuebles ergonómicos:
        - Permitir a las empresas llegar a un público más amplio y aumentar sus ingresos a través de las compras por medio de los usuarios.
        - Facilitar el envío de los productos y la comunicación de los clientes, lo que les permite ofrecer un servicio selección de alta calidad.

    - 1.2.2.3. Lean UX Hypothesis Statements.
    - 1.2.2.4. Lean UX Canvas.
- 1.3. Segmentos objetivo.
  
  #### Segmento objetivo 1: Trabajadores Individuales
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

  #### Segmento objetivo 2: Empresas y Corporaciones
  **Aspectos demográficos:**
	- **Sexo:** Ambos sexos.
	- **Edades:** Adultos jóvenes y adultos de mediana edad (18-45 años).
	- **Nivel socioeconómico:** Diverso, desde bajo a alto.

  **Aspectos geográficos:**
	- **Nacionalidad:** Sin restricciones, pero enfocado en áreas con una alta densidad de empresas y trabajadores de oficina.
	- **Zona geográfica en la que viven:** Principalmente áreas urbanas y suburbanas.

  **Aspectos psicográficos:**
	- Empresas interesadas en mejorar la salud y el bienestar de sus empleados.
	- Empresas que valoran la productividad y el rendimiento laboral de sus empleados.
	- Empresas dispuestas a invertir en soluciones ergonómicas para mejorar el entorno laboral y reducir el ausentismo por enfermedad.


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

	#### Para el segmento de empresas:

	1. ¿Qué iniciativas o programas tienen actualmente en su empresa para promover la salud y el bienestar de los empleados en el entorno laboral?
	2. ¿Qué desafíos enfrentan al implementar soluciones ergonómicas y de salud en el lugar de trabajo?
	3. ¿Qué criterios consideran al evaluar nuevas tecnologías o plataformas diseñadas para mejorar la salud de los empleados?
	4. ¿Cómo medirían el éxito o la efectividad de una plataforma como PhysioDesk en su empresa?
	5. ¿Qué aspectos de la cultura empresarial consideran más importantes para fomentar la adopción de herramientas de salud y bienestar entre los empleados?
	6. ¿Cuál es su nivel de interés en invertir en tecnologías o programas que mejoren la salud y el bienestar de sus empleados?
	7. ¿Qué tipo de funciones o características esperarían encontrar en una plataforma diseñada para mejorar la salud en el lugar de trabajo?
	8. ¿Qué preocupaciones tendrían en cuanto a la privacidad y seguridad de los datos de los empleados al utilizar una plataforma como PhysioDesk?
	9. ¿Qué recursos o apoyo interno estarían disponibles para implementar y promover el uso de una plataforma de salud en la empresa?
	10. ¿Cómo creen que una plataforma como PhysioDesk podría contribuir a la productividad y satisfacción general de los empleados en su empresa?

  
  - 2.4.2. Registro de entrevistas.
  - 2.4.3. Análisis de entrevistas.
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
- 2.9. Empathy Mapping.
- 2.10. As-is Scenario Mapping.
- 2.11. Ubiquitous Language.
  ## Términos y Conceptos



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

Para organizar nuestro proyecto y sus modificaciones, hemos seguido lo propuesto por Vincent Dreissen: un modelo de Git de branching permite gestionar ramas de un proyecto, asi como facilitar el flujo de trabajo. Partimos con una main branch o rama master, y junto a ella, una develop branch. A partir de la rama master, surgen las Hotfix branches, que nos permiten solucionar problemas criticos directamente de la rama master. También creamos Feature branches para los cambios que hicimos a lo largo del proyecto. Estos se unen a la develop Branch. 

Para las releases, hemos aplicado Semantic Versioning para nombrarlas, siguiendo las enumeraciones que plantea (1.0.0, 1.0.1, 1.1.0), así como los Conventional Commits, para nombrar los commits que hacemos en el proyecto, usando terminos como: "feat", "docs", etc. 

URL del repositorio de Github del Landing Page:


  - 5.1.3. Source Code Style Guide & Conventions.
    
Configuración del Código HTML:

 -  Para definir el tipo de documento, se utiliza la etiqueta <!DOCTYPE html>.
 - La cabecera del código se establece entre las etiquetas <head> y </head>
 - Mientras, que el cuerpo del documento HTML se define utilizando las  etiquetas <body> y </body>
 - Es preferible poner los atributos en minúsculas. Los valores de los atributos se deben colocar entre comillas, evitando espacios innecesarios, como en <link rel="stylesheet" href="css/estilos.css">.

Precauciones Importantes:

 - Es mejor no omitir la etiqueta <body>, ya que su omisión puede causar errores en navegadores antiguos.
 - Se incluye la etiqueta <html> para evitar problemas de funcionamiento de XML.

Convenciones de CSS:

 - Para líneas cortas de CSS, se siguen las pautas de escritura en una sola línea, por ejemplo: 
p.intro {font-family: Arial; font-size: 12px;}.
 - Para reglas de estilo más largas, se formatean con una regla por línea para mejorar la legibilidad, como:

  body {
    background-color: blue;
    font-family: "Arial Black", Helvetica, sans-serif;
    font-size: 18px;
    color: white;
}



  - 5.1.4. Software Deployment Configuration.
Para desplegar la landing page es necesario contar con una serie de requisitos, entre ellos, es necesario contar con una cuenta personal, una organización y un repositorio al cual cargar los documentos. A partir de lo anterior, es posible comenzar el despliegue de la landing page. A continuación se enuncian los pasos a seguir:

Crear una carpeta llamada "docs" para alojar el Landing Page.
Asegurarse de que los archivos sigan las nomenclaturas "index.html", "style.css", "funcionalities.js" y una carpeta llamada "img" que contenga las imágenes.
Cargar los archivos al repositorio mediante un commit.
Dirigirse a Settings > Pages y seleccionar el branch correspondiente, en nuestro caso es el "main".
Especificar la carpeta "docs" como la fuente de la página.
Esperar a que GitHub realice las comprobaciones necesarias. Una vez culminado el proceso, se obtendrá un enlace que llevará al Landing Page desplegado

![image](https://github.com/PhysioDesk/Informes/assets/129527802/4bda1c94-7479-4072-a733-94a495e8fc0e)


- 5.2. Landing Page, Services & Applications Implementation.
  - 5.2.1. Sprint n
    - 5.2.1.1. Sprint Planning.
    Un Sprint se trata de un plazo fijo y corto de tiempo en el que el equipo se centra en desarrollar el objetio final del proyecto, también llamado "Product Goal" .
Nuestro primer sprint, aun sin los Review Summary ni Retrospective Summary, se centra en cumplir el objetivo de desarrollar nuestra Landing Page.

| Sprint #  | Sprint 1  |
| ------------ | ------------ |
| **Sprint Planning Background**  |
|  Date  | 2024-04-05  |
| Time  |  11:04 PM |
| Location  | Google Meeting |
| Prepared  by  | Erick Palomino, Giacomo Zoppi |
| Attendees  | Erick Palomino, Giacomo Zoppi, Anthony Guerrero, Juan Ramos, Gianfranco   |
| **Sprint Goal And User Stories**   |
| Sprint n Goal | Elaborar una Landing page que resulte atrayente, útil y apropiada para nuestro proyecto |
| Spring n Velocity | 19  puntos |
| Sum of Story Points |   19 puntos|


- 5.2.1.2. Sprint Backlog
Para nuestro primer Sprint Bakclog, el equipo se centró principalmente en la elaboración de nuestra landing page. Siendo este el foco principal, nos dedicamos
a determinas metas mas pequeñas y alguans funcionalidades que queriamos implementarlas, basandonos en nuestras user sotires. Es así, que las dividimos en
tareas mas maneajables y organizables y las asignamos a cada uno de los miembros. Hicimos uso de Trello para la elaboración de esta actividad.

![trellocaptura](https://github.com/PhysioDesk/Informes/assets/129527802/110bdb99-8f2a-43bd-bff5-20a23c0d9151)


| Sprint #  | Sprint 1  |------------|------------|------------|------------|------------|------------
| ------------ | ------------ |------------|------------|------------|------------|------------|------------
| User Story |------------|------------|------------|------------|------------|------------|------------
|  Id  | Title  |TaskId |Title|Description|Estimation(Hours)|Assigned To|Status(To do/ In Process/Done)
| US02  | Agregar herramienta ergonómica al carrito de compra |  UT01|Funcionalidad "Carrito de Compras" | Añadir la funcionalidad de Carrito de Compras |1 | Juan Ramos|Done
| US03  | Ver detalle de la herramienta ergonómica |UT02 |Desplegar Texto|Añadir botón para ver mas información|1 | ------------| To do
| US04  |Filtrar herramientas ergonómicas|UT03 |Barra de navegación|Permitir a los usuarios interactuar con la barra de navegación |2 |------------ |------------
| US04  |Filtrar herramientas ergonómicas|UT04 |Filtros de Busqueda|Permitir a los usuarios interactuar con filtros de busqueda|2 |------------ ||------------
| US22 | Registrar en la aplicación |UT05 |Ingreso de datos| Permitir a los usuarios ingresar datos  | 1|------------ |------------ 
| US08 |Acceder a un entorno fácil de usar para la cita|UT06| Creación de un entorno agil y amigable |Creación de un entorno agil y amigable |1 |Giacomo Zoppi|Done
| US011|Calificar al fisioterapeuta |UT07 |Sección Terapeutas|Añadir sección Terapeutas | 1|------------ |------------ 
| US011|Calificar al fisioterapeuta |UT08 |Calificación|Añadir calificación a Terapeutas | 1|------------ |------------ 

- 5.2.1.3. Development Evidence for Sprint Review.
  Como hemos ido desarrollando el landing page

| Repository  | Branch  | Commit Id |Commit Message|Commit Message Body|Commited on (Date)|
| ------------  | ------------  | ------------ | ------------ |------------|------------|
|   |main|825a7c9|feat: Added first draft of Landing Page|Added first draft of Landing Page incluiding main menu.|11/04/24|
|   |main|94af9ee|feat: Added images|Added images|12/04/24|
|   |main|35f4891|Update index.html|Update index..html|12/04/24|
|   |main|2ada6fb|Update style.css|Updated style.css|12/04/24|
|   |main|98df8fa|Create funcionalities.js|Created funcionalities.js|13/04/24|
|   |main|7e24545|Create js.js|Create js.js.|13/04/24|
|   |main|da39ea0|feat: typos|feat:typos|13/04/24|



- 5.2.1.4. Testing Suite Evidence for Sprint Review.

 |Repository|Branch|Commit ID|Commit Message|Commit Message <br> Body|Commited<br>On (Date)|  
|----------|------|---------|--------------|-------------------|------------------|
|erickpalomino1923|Main|d92ec96|Add Feature|Add Feature 1,2 |14/04/2024| 
||Main|2f7e60d|Add Feature|Add Feature |14/04/2024|

 ```gherkin
  Feature: VISIT-001: Acceso a la sección de Inicio
  Como visitante
  Quiero ser redirigido automáticamente a la sección de Inicio al ingresar al sitio web
  Para obtener una visión general rápida de la aplicación

  Scenario: Acceso a la sección de Inicio
    Given que un visitante accede a la página de inicio
    When ingresa al sitio web
    Then debe ser redirigido automáticamente a la sección de Inicio

Feature: VISIT-001: Navegación por la página de Inicio
  Como visitante
  Quiero poder desplazarme hacia abajo en la página de Inicio y acceder fácilmente a otras secciones importantes de la aplicación
  Para obtener más información sobre los servicios ofrecidos y la sección de contacto

  Scenario: Navegación por la página de Inicio
    Given que un visitante está en la sección de Inicio
    When desplaza hacia abajo la página
    Then debe poder ver enlaces o botones que le permitan acceder a otras secciones importantes de la aplicación, como los servicios ofrecidos y la sección de contacto

Feature: VISIT-002: Acceso a la sección de Servicios
  Como visitante
  Quiero encontrar un enlace claro que me dirija a la sección de Servicios
  Para obtener información detallada sobre los servicios ofrecidos por la aplicación

  Scenario: Acceso a la sección de Servicios
    Given que un visitante interesado en los servicios accede al sitio web
    When ingresa al sitio
    Then debe encontrar un enlace claro que lo dirija a la sección de Servicios

Feature: VISIT-002: Reserva de cita con fisioterapeuta
  Como visitante
  Quiero poder reservar una cita con un fisioterapeuta desde la sección de Servicios
  Para obtener atención personalizada

  Scenario: Reserva de cita con fisioterapeuta
    Given que un visitante está en la sección de Servicios
    When desea programar una cita con un fisioterapeuta
    Then debe poder encontrar un enlace o botón que lo redirija a la página de reserva de citas

Feature: VISIT-003: Acceso a la sección de Testimonios
  Como visitante
  Quiero encontrar un enlace claro que me dirija a la sección de Testimonios
  Para leer experiencias de usuarios anteriores

  Scenario: Lectura de testimonios de usuarios anteriores
    Given que un visitante interesado en la aplicación accede al sitio web
    When ingresa al sitio
    Then debe encontrar un enlace claro que lo dirija a la sección de Testimonios

Feature: VISIT-004: Acceso a la sección de Contacto
  Como visitante
  Quiero encontrar un enlace claro que me dirija a la sección de Contacto
  Para obtener información de contacto y poder comunicarme con el equipo de soporte si es necesario

  Scenario: Acceso a la sección de Contacto
    Given que un visitante interesado en obtener más información sobre la aplicación accede al sitio web
    When ingresa al sitio
    Then debe encontrar un enlace claro que lo dirija a la sección de Contacto

Feature: VISIT-004: Envío de mensaje al equipo de soporte
  Como visitante
  Quiero poder completar un formulario de contacto en la sección de Contacto con mi nombre, dirección de correo electrónico y mensaje
  Para enviar consultas al equipo de soporte

  Scenario: Envío de mensaje al equipo de soporte
    Given que un visitante está en la sección de Contacto
    When decide enviar un mensaje al equipo de soporte
    Then debe poder completar un formulario de contacto con su nombre, dirección de correo electrónico y mensaje

Feature: VISIT-005: Acceso a la sección de Colaboradores
  Como fisioterapeuta interesado en colaborar con la aplicación
  Quiero encontrar un enlace claro que me dirija a la sección de Colaboradores
  Para obtener información sobre cómo puedo unirme a la plataforma

  Scenario: Acceso a la sección de Colaboradores
    Given que un fisioterapeuta interesado en colaborar con la aplicación accede al sitio web
    When ingresa al sitio
    Then debe encontrar un enlace claro que lo dirija a la sección de Colaboradores

Feature: VISIT-005: Información sobre cómo unirse a la plataforma
  Como fisioterapeuta interesado en colaborar con la aplicación
  Quiero encontrar información sobre cómo unirme a la plataforma
  Para poder colaborar con la aplicación y ofrecer mis servicios a los usuarios

  Scenario: Información sobre cómo unirse a la plataforma
    Given que un fisioterapeuta está en la sección de Colaboradores
    When encuentra información sobre cómo unirse a la plataforma
    Then debe poder seguir un enlace o completar un formulario de registro

Feature: VISIT-006: Acceso a la sección de Beneficios para Profesionales
  Como fisioterapeuta interesado en asociarse con la aplicación
  Quiero encontrar un enlace claro que me dirija a la sección de Beneficios para Profesionales
  Para conocer los beneficios de colaborar con la aplicación

  Scenario: Acceso a la sección de Beneficios para Profesionales
    Given que un fisioterapeuta interesado en asociarse con la aplicación accede al sitio web
    When ingresa al sitio
    Then debe encontrar un enlace claro que lo dirija a la sección de Beneficios para Profesionales

Feature: VISIT-006: Información sobre los beneficios de asociarse con la aplicación
  Como fisioterapeuta interesado en asociarse con la aplicación
  Quiero encontrar información sobre los beneficios de colaborar con la aplicación
  Para tomar una decisión informada sobre mi colaboración

  Scenario: Información sobre los beneficios de asociarse con la aplicación
    Given que un fisioterapeuta está en la sección de Beneficios para Profesionales
    When lee sobre los beneficios de colaborar con la aplicación
    Then debe poder encontrar testimonios de otros fisioterapeutas que han tenido éxito al asociarse con la plataforma


```

- 5.2.1.5. Execution Evidence for Sprint Review.
  	1. Sección Inicial: Aquí presentamos nuestro proyecto y los productos ergonomicos.
     ![image](https://github.com/PhysioDesk/Informes/assets/129527802/3cfe16e5-0611-46d1-91cc-6e836d431c26)
     	2. Sección Sesiones virtuales: Presentación de lo que seria la funcionalidad de contratar terapeutas
  	      ![image](https://github.com/PhysioDesk/Informes/assets/129527802/b7c220d6-2604-44f4-8ece-c2eed7ed38fa)
  	3. Sección productos ergonomicos: Sección centrada en la visualización de productos ergonomicos
  	  ![image](https://github.com/PhysioDesk/Informes/assets/129527802/ae9a0e81-16d7-4197-988c-f96c2aafc34b)
	4. Sección About Us: Sección que explica nuestra historia y nuestro propósito.
	![image](https://github.com/PhysioDesk/Informes/assets/129527802/04b00e97-2edb-4a38-9e46-782f2a6b1e05)
	5. Sección Our Services: Sección que explica los servicios que otorgamos
	![image](https://github.com/PhysioDesk/Informes/assets/129527802/8fe865e3-94d5-4d16-8591-7e0c54049d6d)
	6. Sección Contact Us: Sección que permite a los usuarios contactar con nosotros
	![image](https://github.com/PhysioDesk/Informes/assets/129527802/92b2626c-5c79-4b7f-b7b0-d563b1d03bd5)
	7. Seccion Our Testimonals: Sección que permite visualizar testimonios de usuarios.
 	![image](https://github.com/PhysioDesk/Informes/assets/129527802/90dc9712-322c-4e07-84b7-9e698f32ebb5) 	 
     
- 5.2.1.6. Services Documentation Evidence for Sprint Review.
   Para la elaboración de este sprint no fueron contemplados el desarrollo de un Web Service así como los Services Documentation Evidence.
- 5.2.1.7. Software Deployment Evidence for Sprint Review.
En esta entrega del sprint 1, logramos implementar una Landing Page funcional. 
  	![image](https://github.com/PhysioDesk/Informes/assets/129527802/3cfe16e5-0611-46d1-91cc-6e836d431c26)
  	![image](https://github.com/PhysioDesk/Informes/assets/129527802/b7c220d6-2604-44f4-8ece-c2eed7ed38fa)
  	![image](https://github.com/PhysioDesk/Informes/assets/129527802/ae9a0e81-16d7-4197-988c-f96c2aafc34b)
	![image](https://github.com/PhysioDesk/Informes/assets/129527802/04b00e97-2edb-4a38-9e46-782f2a6b1e05)
	![image](https://github.com/PhysioDesk/Informes/assets/129527802/8fe865e3-94d5-4d16-8591-7e0c54049d6d)
	![image](https://github.com/PhysioDesk/Informes/assets/129527802/92b2626c-5c79-4b7f-b7b0-d563b1d03bd5)
 	![image](https://github.com/PhysioDesk/Informes/assets/129527802/90dc9712-322c-4e07-84b7-9e698f32ebb5)
  	Link del Landing Page: https://github.com/PhysioDesk/Frontend.git  
- 5.2.1.8. Team Collaboration Insights during Sprint.
  
| Integrante                         | Actividad                                                                                          |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------|
| Gianfranco Luna Morales| Diseño y estructura de la landing page |
| Erick Joaquin Palomino Santa Cruz | Implementación de funcionalidades |
| Anthony Jeandet Guerrero Castillo | Diseño y estructura de la landing page |
| Juan Pablo Ramos Mendoza | Creación de Typos |
| Giacomo Zoppi Rodriguez | Implementación de la sección header de la landing page |    
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
