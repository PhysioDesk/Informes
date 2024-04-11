
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
    
  	**Organización visual del contenido** <br><br>
   
	1. Jerárquica (Visual Hierarchy):<br><br>
  	- La organización jerárquica se aplicará en las páginas principales del sitio web, donde se destacan las secciones principales y subsecciones de manera visualmente clara para orientar a los usuarios.
  	- Por ejemplo, en la página de inicio, se presentarán los apartados principales como "Servicios", "Acerca de Nosotros" y "Contacto" de manera prominente, seguidos de las subsecciones relevantes.<br><br>
 
	2. Secuencial (Step-by-Step to Accomplish):<br><br>
  	- Este sistema de organización se utilizará en secciones que guían al usuario a través de un proceso paso a paso para lograr un objetivo específico, como el registro o la solicitud de servicios.
	- Por ejemplo, en la sección de registro de usuarios, se presentarán pasos secuenciales para completar el proceso, como ingresar información personal, seleccionar preferencias y confirmar la cuenta. <br><br>

	 **Esquemas de Categorización de Contenido:** <br><br>
	
	1. Alfabético:<br><br>
	- La categorización alfabética se aplicará en secciones como un directorio de recursos o un catálogo de productos, donde el contenido se puede clasificar fácilmente por orden alfabético.
	- Por ejemplo, en la sección de "Productos Ergonómicos", los artículos se organizan alfabéticamente por título para facilitar la búsqueda de los usuarios.<br><br>

	2. Por Tópicos:<br><br>
	- Este esquema se utilizará para agrupar contenido relacionado bajo categorías o temas específicos, facilitando la navegación del usuario hacia información relevante.
	- Por ejemplo, en la sección de "Productos Ergonómicos", los artículos se categorizan por temas como "Salud Postural" y "Ejercicios Ergonómicos"<br><br>

  - 4.2.2. Labeling Systems.
 
	- Etiquetas de Menú: Utiliza etiquetas descriptivas y breves para los elementos del menú principal, como "Inicio", "Servicios", "Blog", "Recursos", "Contacto", etc. Estas etiquetas deben reflejar claramente el contenido o la función de cada sección.

	- Etiquetas de Categoría: Si la información se organiza en categorías o secciones específicas, utiliza etiquetas que indiquen claramente el tema o el tipo de contenido que se encuentra en cada sección. Por ejemplo, "Lesiones Comunes", "Ejercicios Recomendados", "Artículos de Compra", etc.

	- Etiquetas de Acción: Cuando se presentan opciones de acción para los usuarios, como botones o enlaces, utiliza etiquetas que describan claramente la acción que realizarán al hacer clic en ellas. Por ejemplo, "Registrarse", "Iniciar Sesión", "Agendar Cita", "Descargar Recurso", etc.

	- Etiquetas de Navegación: Enlaces internos dentro del contenido o elementos de navegación como botones de "Siguiente" o "Anterior" deben tener etiquetas claras que indiquen la acción que realizarán. Por ejemplo, "Siguiente Paso", "Volver al Inicio", etc.

	- Etiquetas de Formulario: Para campos de entrada en formularios, utiliza etiquetas claras que indiquen qué información se espera que ingrese el usuario. Por ejemplo, "Nombre", "Correo Electrónico", "Contraseña", "Especialidad", etc.<br><br>

  - 4.2.3. SEO Tags and Meta Tags.
 
	**Landing Page:**
	
	- Title: PhysioDesk - Plataforma de Fisioterapia en Línea | Mejora tu Salud Hoy.
	- Meta Description: Con PhysioDesk, accede a fisioterapeutas calificados desde cualquier lugar. Programa citas, sigue tu progreso y mejora tu bienestar de forma remota.
	- Keywords: fisioterapia en línea, rehabilitación virtual, fisioterapeuta en línea, terapia física remota, consulta con fisioterapeutas.
	- Author: PhysioDesk Team
	
	**Web Application:**
	
	- Title: PhysioDesk - Tu Compañero en la Recuperación | Plataforma de Fisioterapia en Línea.
	- Meta Description: PhysioDesk te ofrece una experiencia completa de fisioterapia en línea. Programa citas, accede a ejercicios personalizados y mejora tu salud desde casa.
	- Keywords: plataforma de fisioterapia, aplicación de rehabilitación, seguimiento de ejercicios, terapia virtual, consulta con especialistas en fisioterapia.
	- Author: PhysioDesk Team. <br><br>

  - 4.2.4. Searching Systems.
 
	En PhysioDesk, se proporcionarán diversos medios de ayuda para que los usuarios encuentren fácilmente la información que están buscando dentro del producto digital. Estos medios están diseñados para evitar que los usuarios se sientan perdidos entre el volumen de información y garantizar una experiencia de búsqueda eficiente y satisfactoria. Las opciones de búsqueda y los filtros disponibles para los usuarios variarán según el contexto y la sección de la aplicación. Aquí se detallan algunas de las características principales:
	
	- Barra de búsqueda principal: En la página de inicio y en otras secciones clave de la aplicación, los usuarios encontrarán una barra de búsqueda prominente. Esta barra les permitirá realizar búsquedas rápidas y directas utilizando palabras clave y frases relevantes.
	
	- Filtros de búsqueda avanzada: Después de realizar una búsqueda, los usuarios tendrán la opción de aplicar filtros avanzados para refinar los resultados según sus necesidades específicas. Estos filtros podrán incluir categorías como tipo de contenido (artículos, ejercicios, productos).
	
	- Resultados de búsqueda destacados: Después de realizar una búsqueda, los resultados se presentarán de manera clara y organizada, con los elementos más relevantes y útiles destacados de manera prominente. Esto ayudará a los usuarios a identificar rápidamente la información que están buscando y a tomar decisiones informadas.<br><br>

  - 4.2.5. Navigation Systems.
 
	En PhysioDesk, los usuarios podrán navegar fácilmente por el Landing Page y la aplicación web para encontrar la información y las funciones que necesitan. Esto se logrará a través de las siguientes acciones y técnicas:
	
	- Barra de búsqueda prominente: En el Landing Page y en la aplicación, los usuarios encontrarán una barra de búsqueda fácilmente accesible en la parte superior de la página. Esta barra permitirá a los usuarios buscar términos específicos relacionados con fisioterapia, ejercicios, consejos de salud y más.
	
	- Filtros de búsqueda avanzada: En la sección de búsqueda de la aplicación, los usuarios tendrán la opción de aplicar filtros avanzados para refinar sus resultados. Estos filtros podrán incluir categorías como tipo de servicio (fisioterapia en línea, ejercicios de rehabilitación, etc.), especialidad del fisioterapeuta, disponibilidad de citas y más.
	
	- Sugerencias de búsqueda instantánea: Cuando los usuarios comiencen a escribir en la barra de búsqueda, recibirán sugerencias instantáneas basadas en términos populares y relevantes. Esto ayudará a los usuarios a encontrar rápidamente contenido relacionado sin necesidad de escribir la consulta completa.
	
	- Navegación intuitiva: Tanto en el Landing Page como en la aplicación, se seguirán principios de diseño de navegación intuitiva. Los usuarios podrán desplazarse fácilmente por las diferentes secciones utilizando un menú claro y etiquetado, así como botones de navegación y enlaces prominentes.<br><br>
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
