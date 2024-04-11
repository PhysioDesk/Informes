
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

	### Segmento Usuarios
	![image](https://github.com/PhysioDesk/Informes/assets/89022078/5104680a-188e-464b-a7c1-77c80dee1a93)

	### Segmento Profesional
	![image](https://github.com/PhysioDesk/Informes/assets/89022078/3f7e968c-0b6c-456d-ad27-ba83878fc880)

	Link para visualizar el To-Be Scenario Mapping en Miro: https://miro.com/welcomeonboard/ZnZpOEtKc0tXcFUwTkN3OXlRQ0drN09JUHFPR29YZ3VVWjBlNTlVTWVEc0tnbkNxekxkczJIaGpHekE3ek8ycnwzMDc0NDU3MzQ3Njk4ODc5OTg5fDI=?share_link_id=155036395771

- 3.2. User Stories.

| Epic / StoryId | Título  | Descripción   | Criterios de aceptación | Relacionado con (Epic ID) |
| --- | --- | --- | --- | ---- |
| USER-001 | Recibir recomendaciones para la correcta postura. | Como   usuario, quiero recibir recomendaciones sobre una correcta postura, para tratar o prevenir algún dolor muscular.| Escenario 1:<br>El usuario recibe recomendaciones personalizadas de la app sobre sus malestares.<br><br>Criterio 1: <br>Dado que el usuario ha registrado previamente sus malestares.<br>Cuando el usuario navega por la aplicación web.<br>Entonces un consejo orientado a su malestar se entrega al usuario de manera que sea fácilmente visible y accesible.<br><br>Escenario 2:<br>El usuario recibe recomendaciones generales de la app.<br><br>Criterio 2:<br>Dado que el usuario no ha registrado previamente malestares.<br>Cuando el usuario navega por la aplicación web<br>Entonces un consejo general  se entrega al usuario de manera que sea fácilmente visible y accesible.| EP-001 |
| USER-002 | Agregar herramienta ergonómica al carrito de compra y proceder el pago. | Como usuario, quiero poder agregar las herramientas ergonómicas seleccionadas a un carrito de compras y proceder al pago de manera segura, para completar fácilmente mi compra. | Escenario 1:<br>Agregar al carrito de compras.<br><br>Criterio 1:<br>Dado que el usuario ha seleccionado una herramienta ergonómica para comprar.<br>Cuando el usuario agrega la herramienta seleccionada al carrito de compras.<br>Entonces la herramienta ergonómica se añade al carrito de compras del usuario correctamente.<br><br>Escenario 2: <br>Proceso de pago<br><br>Criterio 2:<br>Dado que el usuario ha agregado herramientas ergonómicas al carrito y desea proceder al pago.<br>Cuando el usuario selecciona la opción de pagar.<br>Entonces el usuario es redirigido a una página segura de pago donde puede ingresar la información de pago de forma segura. | EP-001 |
| USER-003 | Ver detalle de la herramienta ergonómica | Como usuario, quiero ver una lista clara y detallada de las características de cada herramienta ergonómica, incluyendo descripción, precio y disponibilidad, para tomar decisiones de compra informadas. | Escenario 1: <br>Visualización detallada.<br><br>Criterio 1:<br>Dado que el usuario está en la página de detalles de una herramienta ergonómica.<br>Cuando el usuario visualiza la información de la herramienta.<br>Entonces se muestra una descripción clara y detallada de las características de la herramienta, incluyendo la descripción, el precio y la disponibilidad.<br><br>Criterio 2:<br>Dado que el usuario está en la página de detalles de una herramienta ergonómica.<br>Cuando el usuario verifica la disponibilidad del producto.<br>Entonces se muestra claramente si la herramienta está disponible para su compra y entrega inmediata. | EP-001 |
| USER-004 | Filtrar herramientas ergonómicas | Como usuario, quiero filtrar las opciones disponibles de herramientas ergonómicas, para que la búsqueda sea más sencilla y encuentre el adecuado de acuerdo a mi disponibilidad económica. | Escenario 1: <br>Filtrado por precio<br><br>Criterio 1:<br>Dado que el usuario está en la página de herramientas ergonómicas.<br>Cuando el usuario establece un rango de precios utilizando el filtro de precio.<br>Entonces la página se actualiza y muestra solo las herramientas ergonómicas que se encuentran dentro del rango de precios especificado por el usuario. | EP-001 |
| USER-005 | Ver detalle de la compra | Como usuario, quiero recibir una confirmación clara y detallada de mi compra, incluyendo información sobre los productos adquiridos y el total de la compra, para tener una referencia de la transacción realizada. | Escenario 1: <br>Confirmación de compra<br><br>Criterio  1:<br>Dado que el usuario ha completado el proceso de compra de herramientas ergonómicas.<br>Cuando se confirma la transacción.<br>Entonces se muestra una confirmación clara y detallada de la compra, incluyendo un resumen de los productos adquiridos y el total de la compra.<br><br>Criterio  2:<br>Dado que el usuario ha completado la compra de herramientas ergonómicas.<br>Cuando la transacción se ha confirmado con éxito.<br>Entonces el usuario recibe un correo electrónico de confirmación de la compra en la dirección de correo electrónico proporcionada durante el proceso de pago. | EP-001 |
| USER-006 | Visualizar los horarios de atención de cada fisioterapeuta | Como usuario, quiero visualizar los horarios disponibles de cada fisioterapeuta, para conocer cuál se acomoda a mis tiempos libres. | Escenario 1: <br>Visualización de la lista de fisioterapeutas.<br><br>Criterio 1:<br>Dado que el usuario accede a la sección de fisioterapeutas en la aplicación,<br>Cuando se carga la página,<br>Entonces se muestra una lista de fisioterapeutas disponibles, incluyendo su nombre, especialidad y disponibilidad de horarios.<br><br>Escenario 2:<br>Visualización de horarios de atención detallados<br><br>Criterio 2:<br>Dado que el usuario selecciona un fisioterapeuta de la lista,<br>Cuando accede a los detalles del fisioterapeuta,<br>Entonces se muestran claramente los días y horarios en los que el fisioterapeuta está disponible para atender citas, así como su ubicación y contacto. | EP-002 |
| USER-007 | Reservar cita con fisioterapeuta | Como usuario, quiero reservar una cita con un fisioterapeuta, con el fin de que me brinde asesoramiento y tratamiento para mis malestares. | Escenario 1: <br>Selección de fecha y hora disponibles<br><br>Criterio 1:<br>Dado que el usuario está visualizando los horarios de atención de un fisioterapeuta,<br>Cuando selecciona una fecha y hora para su cita,<br>Entonces la aplicación muestra claramente los horarios disponibles del fisioterapeuta y permite al usuario elegir una opción que se ajuste a su disponibilidad.<br><br>Escenario 2: <br>Confirmación de reserva de cita<br><br>Criterio 2:<br>Dado que el usuario ha seleccionado una fecha y hora para su cita,<br>Cuando confirma la reserva de su cita,<br>Entonces la aplicación muestra un resumen de la cita propuesta y solicita la confirmación del usuario antes de proceder.<br><br>Criterio 3:<br>Dado que el usuario confirma la reserva de su cita,<br>Cuando se procesa la confirmación,<br>Entonces la aplicación registra la cita en el sistema y notifica al usuario sobre la confirmación junto con los detalles de la cita. | EP-002 |
| USER-008 | Acceder a un entorno fácil de usar para la cita. | Como usuario, quiero acceder a un entorno de cita intuitivo y fácil de usar en la aplicación, para poder participar plenamente en la consulta y acceder a las funciones necesarias de manera clara y rápida. | Escenario 1: <br>Visualización clara de opciones de la cita<br><br>Criterio 1:<br><br>Dado que el usuario accede al entorno de la cita en la aplicación,<br>Cuando se carga el entorno de la cita,<br>Entonces el usuario encuentra una interfaz clara con opciones visibles para iniciar la videollamada y acceder al chat. | EP-002 |
| USER-009 | Grabación automática de la cita. | Como usuario, quiero que la sesión de mi cita se graba automáticamente en cuanto comience la consulta en el entorno de la cita, para poder revisar posteriormente para un seguimiento efectivo del tratamiento y repasar las recomendaciones proporcionadas durante la consulta. | Escenario 1: <br>Inicio de la grabación de la sesión<br><br>Criterio 1:<br>Dado que el usuario está participando en una consulta a través del entorno de la cita,<br>Cuando el usuario inicia la consulta en una plataforma sencilla de manejar,<br>Entonces la grabación de la sesión se activa automáticamente sin necesidad de intervención por parte del usuario. | EP-002 |
| USER-010 | Acceder a las grabaciones. | Como usuario, quiero acceder fácilmente a las grabaciones de mis sesiones de citas anteriores, para poder revisarlas en cualquier momento y asegurarse de seguir correctamente las instrucciones y recomendaciones proporcionadas durante la consulta. | Escenario 1: <br>Acceso a las grabaciones anteriores<br><br>Criterio 1:<br>Dado que la consulta ha finalizado,<br>Cuando el usuario desea acceder a la grabación de la sesión anterior,<br>Entonces la aplicación proporciona un acceso claro y fácil a las grabaciones anteriores, permitiendo al usuario revisarlas en cualquier momento para un seguimiento efectivo del tratamiento. | EP-002 |
| USER-011 | Calificar al fisioterapeuta. | Como usuario, quiero calificar al fisioterapeuta cada vez que se lleva a cabo una cita, para expresarme sobre cómo me siento con el servicio. | Escenario 1:<br>Calificación satisfactoria del fisioterapeuta<br><br>Criterio 1:<br>Dado que se ha completado una cita con un fisioterapeuta,<br>Cuando la cita finaliza,<br>Entonces el usuario tiene acceso a la funcionalidad para calificar al fisioterapeuta.<br><br>Criterio 2:<br>Dado que el usuario tiene acceso a la funcionalidad de calificación del fisioterapeuta,<br>Cuando el usuario elige calificar al fisioterapeuta,<br>Entonces se presenta al usuario una interfaz clara para proporcionar una calificación, que puede ser en forma de estrellas, puntaje numérico o comentarios escritos. | EP-002 |
| USER-012 | Configurar notificaciones de cita. | Como usuario, quiero configurar las notificaciones de recordatorio para mis citas, para recibir recordatorios antes de cada cita programada. | Escenario 1: <br>Configuración de notificaciones y establecer tiempo de anticipación<br><br>Criterio 1:<br>Dado que el usuario se ha registrado en la aplicación,<br>Cuando accede a la configuración de notificaciones desde la aplicación,<br>Entonces puede habilitar o deshabilitar las notificaciones de recordatorio para citas.<br><br>Criterio 2:<br>Dado que el usuario se ha registrado en la aplicación,<br>Cuando accede a la configuración de notificaciones desde la aplicación,<br>Entonces puede establecer el tiempo de anticipación deseado para las notificaciones de recordatorio de citas. | EP-002 |
| USER-013 | Generar notificaciones de cita. | Como usuario, quiero recibir automáticamente notificaciones antes de la hora programada para cada cita, para recordarme sobre las próximas citas. | Escenario 1: <br>El usuario recibe automáticamente las notificaciones<br><br>Criterio 1:<br>Dado que el usuario está registrado en la aplicación y ha configurado las notificaciones de cita,<br>Cuando se acerca la hora programada de una cita,<br>Entonces la aplicación genera automáticamente una notificación de recordatorio basada en el tiempo de anticipación configurado. | EP-002 |
| USER-014 | Interactuar con las notificaciones de cita. | Como usuario, quiero poder interactuar con las notificaciones de recordatorio de cita, para acceder rápidamente a los detalles de la cita o confirmar/cancelar la cita desde la notificación. | Escenario 1:<br>El usuario interactúa con la notificación fuera de la aplicación.<br><br>Criterio 1:<br>Dado que el usuario recibe una notificación de recordatorio de cita,<br>Cuando interactúa con la notificación en su dispositivo,<br>Entonces puede abrir la aplicación y acceder a los detalles de la cita.<br><br>Escenario 2: <br>Confirmar o cancelar la cita desde la notificación<br><br>Criterio 2:<br>Dado que el usuario recibe una notificación de recordatorio de cita,<br>Cuando interactúa con la notificación en su dispositivo,<br>Entonces puede confirmar o cancelar la cita directamente sin necesidad de abrir la aplicación. | EP-002 |
| FISIO-001 | Registrar detalles de cada sesión de tratamiento. | Como fisioterapeuta, quiero registrar detalles de cada sesión de tratamiento, para llevar un registro preciso del progreso del paciente. | Escenario 1:<br>El fisioterapeuta registra la sesión de tratamiento.<br><br>Criterio 1:<br>Dado que el fisioterapeuta está tratando a un paciente,<br>Cuando finaliza una sesión de tratamiento,<br>Entonces debe poder registrar la fecha, duración, tipo de tratamiento y ejercicios realizados para esa sesión. | EP-003 |
| FISIO-002 | Analizar el progreso del paciente. | Como fisioterapeuta, quiero analizar el progreso del paciente, para evaluar su evolución y ajustar el plan de tratamiento según sea el malestar. | Escenario 1:<br>El fisioterapeuta visualiza el progreso del paciente.<br><br>Criterio 1:<br>Dado que el fisioterapeuta está evaluando el progreso de un paciente,<br>Cuando accede al perfil del paciente,<br>Entonces debe poder ver gráficos o tablas que muestren su evolución en términos de movilidad, fuerza, flexibilidad, dolor y otras métricas relevantes.<br><br>Escenario 2:<br>El fisioterapeuta identifica tendencias.<br><br>Criterio 2:<br>Dado que el fisioterapeuta está analizando el progreso del paciente,<br>Cuando revisa los datos de progreso,<br>Entonces debe poder identificar tendencias, mejoras o áreas que necesiten más atención para ajustar el plan de tratamiento. | EP-003 |
| FISIO-003 | Generar informes. | Como fisioterapeuta, quiero generar informes de progreso para comunicar la evolución del paciente de manera efectiva. | Escenario1: <br>El fisioterapeuta genera informes personalizados<br><br>Criterio 1:<br>Dado que el fisioterapeuta necesita comunicar el progreso del paciente,<br>Cuando accede al perfil del paciente,<br>Entonces debe poder generar informes personalizados que incluyan gráficos, tablas u otros datos visuales. | EP-003 |
| USER-017 | Pagar con diversos medios de pago para acceder a la versión premium de la app | Como usuario interesado en acceder a la versión premium de la aplicación, quiero poder realizar el pago utilizando diferentes métodos de pago para mayor conveniencia y accesibilidad. | Escenario 1: <br>Selección del método de pago<br><br>Criterio 1:<br>Dado que un usuario está interesado en la versión premium de la aplicación,<br>Cuando accede a la pantalla de suscripción premium,<br>Entonces debe poder seleccionar entre diferentes opciones de pago, como tarjeta de crédito, débito, PayPal, u otros métodos de pago populares.<br><br>Escenario 2: <br>Ingreso de detalles de pago<br><br>Criterio 2:<br>Dado que se ha seleccionado un método de pago para la suscripción premium,<br>Cuando se ingresan los detalles de pago requeridos,<br>Entonces la aplicación debe validar la información ingresada y procesar el pago de forma segura y confiable. <br><br>Escenario 3: <br>Confirmación de la transacción<br><br>Criterio 3:<br>Dado que el pago se ha procesado correctamente,<br>Cuando se confirma la transacción,<br>Entonces la aplicación debe otorgar al usuario acceso inmediato a la versión premium de la aplicación, desbloqueando todas las funcionalidades y beneficios asociados.<br><br>Escenario 4: <br>Confirmación de la finalización del pago<br><br>Criterio 4:<br>Dado que el usuario ha realizado el pago,<br>Cuando se le redirige de vuelta a la aplicación desde el proceso de pago,<br>Entonces la aplicación debe mostrar una confirmación clara de que el pago se ha realizado. | EP-004 |
| FISIO-004 | Creación de planes de ejercicios de movimiento | Como fisioterapeuta, quiero poder crear planes de ejercicios de movimiento personalizados para mis usuarios, con el fin de ayudarles a mejorar su malestar y promover una recuperación efectiva. | Escenario 1: <br>Creación de un nuevo plan de ejercicios<br><br>Criterio 1:<br>Dado que un fisioterapeuta utiliza la aplicación,<br>Cuando accede a la función de creación de planes de ejercicios,<br>Entonces debe poder crear un nuevo plan de ejercicios personalizado para un usuario específico.<br><br>Escenario 2: <br>Selección de ejercicios para el plan<br><br>Criterio 2:<br>Dado que se está creando un plan de ejercicios para un usuario,<br>Cuando se seleccionan los ejercicios adecuados para abordar su malestar específico y mejorar su movilidad y flexibilidad,<br>Entonces se deben poder agregar estos ejercicios al plan con instrucciones claras sobre cómo realizar cada ejercicio correctamente.<br><br>Escenario 3: <br>Guardado del plan de ejercicios<br><br>Criterio 3:<br>Dado que se ha creado un plan de ejercicios para un usuario,<br>Cuando se guarda el plan,<br>Entonces este debe quedar asociado al perfil del usuario para que pueda acceder a él en cualquier momento. | EP-006 |
| FISIO-005 | Afiliar cuenta de ahorros para recibir pagos. | Como fisioterapeuta, quiero poder afiliar mi cuenta de ahorros, para recibir pagos por los servicios prestados a través de la aplicación. | Escenario 1: <br>Acceso a la función de afiliación de cuenta de ahorros.<br><br>Criterio 1:<br>Dado que un fisioterapeuta utiliza la aplicación,<br>Cuando accede a la sección de configuración del perfil,<br>Entonces debe encontrar una opción clara para afiliar la cuenta de ahorros y recibir pagos.<br><br>Criterio 2:<br>Dado que se accede a la función de afiliación de cuenta de ahorros,<br>Cuando se ingresan los detalles de la cuenta bancaria, incluyendo el número de cuenta y los detalles de identificación requeridos,<br>Entonces la aplicación debe validar la información ingresada y mostrar una confirmación de que la afiliación se ha completado con éxito.<br><br>Escenario 2: <br>Verificación y gestión de la cuenta afiliada<br><br>Criterio 3:<br>Dado que se ha afiliado la cuenta de ahorros para recibir pagos,<br>Cuando se accede a la sección de configuración del perfil,<br>Entonces se debe poder ver los detalles de la cuenta bancaria afiliada, incluyendo el número de cuenta y los datos asociados. | EP-007 |
| USER-018 | Registrar dolores musculares. | Como usuario de la aplicación, quiero poder registrar mis malestares musculoesqueléticos utilizando una imagen interactiva, para poder identificar y documentar con precisión las áreas afectadas de mi cuerpo. | Escenario 1: <br>Presentación de la imagen 3D interactiva.<br><br>Criterio 1:<br>Dado que el usuario accede a la función de registro de malestares,<br>Cuando se le presenta una imagen interactiva de un cuerpo humano,<br>Entonces el usuario debe poder interactuar con la imagen y seleccionar las áreas de su cuerpo donde experimentan malestares.<br><br>Escenario 2: <br>Selección y confirmación de área del cuerpo<br><br>Criterio 2:<br>Dado que el usuario ha interactuado con la imagen interactiva y seleccionado un área de su cuerpo donde experimentan malestares,<br>Cuando confirma la selección,<br>Entonces la aplicación debe registrar el malestar asociado a esa área específica y almacenarlo para futura referencia. | EP-007 |
| FISIO-006 | Registrar horario disponible por parte del fisioterapeuta. | Como fisioterapeuta quiero poder registrar mis horarios disponibles para sesiones de terapia, para que los usuarios puedan reservar citas conmigo según mi disponibilidad. | Escenario 1: <br>Acceso a la función de gestión de horarios<br><br>Criterio 1:<br>Dado que el fisioterapeuta accede a la función de gestión de horarios,<br>Cuando ingresa a su perfil de usuario,<br>Entonces debe tener la opción de registrar sus horarios disponibles para sesiones de terapia.<br><br>Escenario 2: <br>Registro de horarios disponibles.<br><br>Criterio 2:<br>Dado que el fisioterapeuta ha accedido a la función de gestión de horarios,<br>Cuando selecciona un día y un rango horario para la sesión de terapia,<br>Y confirma la disponibilidad,<br>Entonces la aplicación debe registrar estos horarios como disponibles para reservar por parte de los usuarios.<br><br>Escenario 3: <br>Visualización de horarios disponibles para los usuarios<br><br>Criterio 3:<br>Dado que el fisioterapeuta ha registrado sus horarios disponibles,<br>Cuando un usuario busca citas disponibles,<br>Entonces la aplicación debe mostrar los horarios registrados por el fisioterapeuta como opciones para reservar sesiones de terapia. | EP-007 |
| USER-019 | Acceder al plan de ejercicios. | Como usuario de la aplicación, quiero poder acceder al plan de ejercicios recomendado por mi fisioterapeuta, para poder realizarlos y mejorar mi condición física. | Escenario 1: <br>Visualización del plan de ejercicios<br><br>Criterio 1:<br>Dado que el usuario accede a la sección de planes de ejercicios en la aplicación,<br>Cuando selecciona el plan recomendado por su fisioterapeuta,<br>Entonces la aplicación debe mostrar el plan de ejercicios completo con todos los detalles y ejercicios recomendados.<br><br>Escenario 2: <br>Acceso a la descripción de los ejercicios<br><br>Criterio 2:<br>Dado que el usuario está visualizando el plan de ejercicios recomendado por su fisioterapeuta,<br>Cuando selecciona un ejercicio específico del plan,<br>Entonces la aplicación debe mostrar una descripción detallada del ejercicio, incluyendo instrucciones sobre cómo realizarlo correctamente. | EP-006 |
| USER-020 | Marcar ejercicios como completados. | Como usuario de la aplicación, quiero poder marcar los ejercicios del plan como completados, para llevar un registro de mi progreso y seguimiento de mis sesiones de ejercicio. | Escenario 1: <br>Marcado de un ejercicio como completado<br><br>Criterio 1:<br>Dado que el usuario está visualizando un ejercicio específico del plan de ejercicios,<br>Cuando completa el ejercicio,<br>Entonces la aplicación debe proporcionar una opción clara para marcar el ejercicio como completado.<br><br>Escenario 2: <br>Confirmación del ejercicio marcado<br><br>Criterio 2:<br>Dado que el usuario ha marcado un ejercicio como completado,<br>Cuando confirma la acción,<br>Entonces la aplicación debe registrar el ejercicio como completado y actualizar el estado del ejercicio en el plan de ejercicios. | EP-006 |
| USER-021 | Recibir recordatorio de ejercicios. | Como usuario de la aplicación, quiero recibir una notificación cuando falte una hora para realizar un ejercicio recomendado por mi fisioterapeuta, para recordarme la hora de realizar la actividad y mantenerme en mi rutina de ejercicios. | Escenario 1: <br>Recepción de la notificación.<br><br>Criterio 1:<br>Dado que ha pasado una hora desde que se programó un ejercicio recomendado por el fisioterapeuta,<br>Cuando falte una hora para que se lleve a cabo,<br>Entonces la aplicación debe enviar una notificación al usuario para recordarle que debe realizar el ejercicio.<br><br>Escenario 2:<br>Interacción con la notificación<br><br>Criterio 2:<br>Dado que el usuario recibe la notificación de recordatorio de ejercicio,<br>Cuando toca la notificación,<br>Entonces la aplicación debe abrir la pantalla correspondiente al ejercicio recomendado para que el usuario pueda acceder rápidamente a los detalles y realizar la actividad. | EP-004 |
| USER-022 | Registrarse en la aplicación. | Como usuario interesado en mejorar su postura y bienestar general, quiero poder registrarme en la aplicación de manera sencilla e intuitiva, para acceder a todas las funcionalidades y servicios disponibles de manera rápida. | Escenario 1: <br>Registro exitoso<br><br>Criterio 1:<br>Dado que el usuario abre la aplicación por primera vez<br>Cuando el usuario selecciona la opción de registro<br>Entonces el usuario debería ver un formulario para completar sus datos personales<br><br>Criterio 2:<br>Dado que el usuario ingresa su nombre, dirección de correo electrónico y contraseña<br>Cuando envía el formulario de registro<br>Entonces el usuario debería recibir una confirmación de registro exitoso y ser redirigido a la página de inicio de sesión<br><br>Escenario 2: <br>Registro fallido<br><br>Criterio 3:<br>Dado que el usuario está completando el formulario de registro<br>Cuando el usuario ingresa una dirección de correo electrónico inválida<br>Entonces el usuario debería ver un mensaje de error indicando que la dirección de correo electrónico es inválida y no debería poder enviar el formulario hasta que corrija el error<br><br>Criterio 4:<br>Dado que el usuario está completando el formulario de registro<br>Cuando el usuario ingresa una contraseña débil (menos de 8 caracteres)<br>Entonces el usuario debería ver un mensaje de error indicando que la contraseña es débil y no debería poder enviar el formulario hasta que corrija el error. | EP-008 |
| FISIO-007 | Enviar solicitud de incorporación como fisioterapeuta | Como fisioterapeuta interesado en colaborar con la aplicación, quiero poder enviar una solicitud de incorporación desde el landing page para iniciar el proceso de registro. | Escenario 1:<br>Solicitud exitosa<br><br>Criterio 1:<br>Dado que el fisioterapeuta encuentra la sección destinada a colaboradores y accede al formulario<br>Cuando completa todos los campos requeridos en el formulario de solicitud<br>Entonces debería ver un mensaje de confirmación en pantalla indicando que su solicitud ha sido enviada correctamente.<br><br>Escenario 2:<br>Campos incompletos en el formulario<br><br>Criterio 2:<br>Dado que el fisioterapeuta encuentra la sección destinada a colaboradores y accede al formulario<br>Cuando intenta enviar la solicitud con campos obligatorios incompletos en el formulario<br>Entonces no debería poder enviar la solicitud y debería recibir mensajes de error indicando los campos que faltan por completar. | EP-008 |
| VISIT-001 | Sección de inicio del Landing Page. | Como visitante, quiero una sección de "Inicio" que me brinde una visión general de la aplicación y sus características principales, para entender rápidamente de qué se trata y cómo puede beneficiarme como usuario. | Escenario 1: <br>Acceso a la sección de "Inicio"<br><br>Criterio 1: <br>Dado que un visitante accede a la página de inicio, cuando ingresa al sitio web, entonces debe ser redirigido automáticamente a la sección de "Inicio".<br><br>Criterio 2: <br>Dado que un visitante está en la sección de "Inicio", cuando observa la página, entonces debe ver una breve descripción de la aplicación y sus características principales.<br><br>Escenario 2: <br>Navegación por la página de "Inicio"<br><br>Criterio 3: <br>Dado que un visitante está en la sección de "Inicio", cuando desplaza hacia abajo la página, entonces debe poder ver enlaces o botones que le permitan acceder a otras secciones importantes de la aplicación, como los servicios ofrecidos y la sección de contacto. | EP-005 |
| VISIT-002 | Sección de servicios del Landing Page. | Como visitante, quiero una sección de "Servicios" donde pueda encontrar información detallada sobre los diferentes servicios ofrecidos por la aplicación, incluyendo ejercicios recomendados, seguimiento de progreso y citas con fisioterapeutas, para comprender cómo puede ayudarme a mejorar mi salud y bienestar. | Escenario 1: <br>Acceso a la sección de "Servicios"<br><br>Criterio 1: <br>Dado que un visitante interesado en los servicios ofrecidos por la aplicación accede al sitio web, cuando ingresa al sitio, entonces debe encontrar un enlace claro que lo dirija a la sección de "Servicios" <br><br>Criterio 2: <br>Dado que un visitante está en la sección de "Servicios", cuando selecciona un servicio específico, entonces debe poder acceder a información adicional y detalles sobre ese servicio <br><br>Escenario 2: <br>Reserva de cita con fisioterapeuta.<br><br>Criterio 3: <br>Dado que un visitante está en la sección de "Servicios", cuando desea programar una cita con un fisioterapeuta, entonces debe poder encontrar un enlace o botón que lo redirija a la página de reserva de citas. | EP-005 | 
| VISIT-003 | Sección de testimonios del Landing Page. | Como visitante, quiero una sección de "Testimonios" donde pueda leer experiencias de usuarios anteriores y sus resultados, para tener confianza en la efectividad de la aplicación y sentirme motivado a utilizarla. | Escenario 1: <br>Lectura de testimonios de usuarios anteriores.<br><br>Criterio 1: <br>Dado que un visitante interesado en la aplicación accede al sitio web, cuando ingresa al sitio, entonces debe encontrar un enlace claro que lo dirija a la sección de "Testimonios".<br><br>Criterio 2: <br>Dado que un visitante está en la sección de "Testimonios", cuando lee un testimonio específico, entonces debe poder ver detalles sobre el usuario y su experiencia con la aplicación. | EP-005 |
| VISIT-004 | Sección de contacto del Landing Page. | Como visitante, quiero una sección de "Contacto" con información de contacto clara y un formulario de contacto, para poder comunicarme con el equipo de soporte si tengo alguna pregunta o necesito asistencia. | Escenario 1: <br>Acceso a la sección de "Contacto"<br><br>Criterio 1: <br>Dado que un visitante interesado en obtener más información sobre la aplicación accede al sitio web, cuando ingresa al sitio, entonces debe encontrar un enlace claro que lo dirija a la sección de "Contacto".<br><br>Criterio 2:<br>Dado que un visitante está en la sección de "Contacto", cuando decide enviar un mensaje al equipo de soporte, entonces debe poder completar un formulario de contacto con su nombre, dirección de correo electrónico y mensaje. | EP-005 |
| VISIT-005 | Sección de colaboradores del Landing Page. | Como visitante del segmento fisioterapeuta interesado en colaborar con la aplicación, quiero una sección de "Colaboradores" donde pueda obtener información sobre cómo puedo unirme a la plataforma y ofrecer mis servicios a los usuarios, para ampliar mi base de clientes y llegar a más personas necesitadas de atención física. | Escenario 1: <br>Acceso a la sección de "Colaboradores"<br><br>Criterio 1: <br>Dado que un fisioterapeuta interesado en colaborar con la aplicación accede al sitio web, cuando ingresa al sitio, entonces debe encontrar un enlace claro que lo dirija a la sección de "Colaboradores".<br><br>Criterio 2:<br>Dado que un fisioterapeuta está en la sección de "Colaboradores", cuando encuentra información sobre cómo unirse a la plataforma, entonces debe poder seguir un enlace o completar un formulario de registro. | EP-005 |
| VISIT-006 | Sección de beneficios para profesionales del Landing Page | Como visitante del segmento fisioterapeuta, quiero una sección de "Beneficios para Profesionales" donde pueda conocer los beneficios de asociarse con la aplicación, como la posibilidad de llegar a nuevos clientes, gestionar citas de manera eficiente y acceder a herramientas de seguimiento del progreso del paciente, para tomar una decisión informada sobre mi colaboración. | Escenario 1: <br>Acceso a la sección de "Beneficios para Profesionales"<br><br>Criterio 1: <br>Dado que un fisioterapeuta interesado en asociarse con la aplicación accede al sitio web, cuando ingresa al sitio, entonces debe encontrar un enlace claro que lo dirija a la sección de "Beneficios para Profesionales".<br><br>Criterio 2: <br>Dado que un fisioterapeuta está en la sección de "Beneficios para Profesionales", cuando lee sobre los beneficios de colaborar con la aplicación, entonces debe poder encontrar testimonios de otros fisioterapeutas que han tenido éxito al asociarse con la plataforma. | EP-005 |
| DVLOP-001 | Crear Endpoint para Registro de Usuario | Como desarrollador, quiero crear un endpoint POST para permitir el registro de nuevos usuarios en la plataforma PhysioDesk, para que los usuarios puedan crear cuentas y acceder a la funcionalidad completa. | Escenario 1:<br> Crear un nuevo usuario. <br><br> Criterio 1: <br>Dado que el usuario proporciona información válida de registro <br>Cuando se envía una solicitud POST al endpoint /api/register con los datos del usuario <br>Entonces se debe crear una nueva cuenta de usuario en la base de datos<br>Y se debe devolver un código de estado 201 (Created) junto con un mensaje de éxito | EP-008 |
| DVLOP-002 | Implementar Autenticación de Usuario | Como desarrollador, quiero agregar autenticación basada en tokens JWT para proteger los endpoints sensibles de la API, para garantizar la seguridad de los datos del usuario y restringir el acceso no autorizado. | Escenario 1: <br>Iniciar sesión con credenciales válidas. <br><br>Criterio1: <br>Dado que el usuario proporciona credenciales válidas (correo electrónico y contraseña)<br>Cuando se envía una solicitud POST al endpoint /api/login con las credenciales<br>Entonces se debe generar un token JWT válido y devolverlo en la respuesta<br>Y se debe devolver un código de estado 200 (OK) junto con un mensaje de éxito. <br><br> Escenario2: <br>Manejar credenciales inválidas.<br><br>Criterio 2:<br>Dado que el usuario proporciona credenciales inválidas<br>Cuando se envía una solicitud POST al endpoint /api/login con credenciales incorrectas<br>Entonces se debe devolver un código de estado 401 (No autorizado) junto con un mensaje de error. | EP-007 |
| DVLOP-003 | Integrar Sistema de Citas | Como desarrollador, quiero integrar un sistema de gestión de citas para permitir que los usuarios reserven citas con fisioterapeutas, para facilitar la planificación y organización de las consultas. | Escenario 1: <br>Reservar una cita <br><br>Criterio 1: <br>Dado que el usuario envía una solicitud POST al endpoint /api/appointments para reservar una cita<br>Cuando la solicitud contiene los detalles de la cita y está dentro del horario disponible del fisioterapeuta<br>Entonces se debe registrar la cita en el sistema<br>Y se debe devolver un código de estado 201 (Creado) junto con un mensaje de éxito<br><br>Escenario 2: <br>Manejar horarios no disponibles. <br><br>Criterio 2:<br>Dado que el usuario intenta reservar una cita en un horario no disponible<br>Cuando se envía una solicitud POST al endpoint /api/appointments<br>Entonces se debe devolver un código de estado 400 (Solicitud incorrecta) junto con un mensaje de error. | EP-002 |
| DVLOP-004 | Crear Endpoint para Consulta de Productos Ergonómicos | Como desarrollador, quiero implementar un endpoint GET para permitir a los usuarios consultar productos ergonómicos disponibles en la plataforma, para que los usuarios puedan ver y buscar productos fácilmente. | Escenario 1: <br>Consultar productos disponibles. <br><br>Criterio 1: <br>Dado que el usuario envía una solicitud GET al endpoint /api/products<br>Cuando la solicitud es válida y contiene parámetros de búsqueda opcionales<br>Entcones se deben devolver los productos disponibles según los parámetros de búsqueda<br>Y se debe devolver un código de estado 200 (OK) junto con la lista de productos. <br><br>Escenario 2: <br>Manejar solicitudes inválidas. <br><br>Criterio 2: <br>Dado que el usuario envía una solicitud GET inválida al endpoint /api/products<br>Cuando la solicitud no contiene parámetros válidos<br>Entonces se debe devolver un código de estado 400 (Bad Request) junto con un mensaje de error. | EP-001 |
| EP-001 | Gestión de Recomendaciones y Compra de Productos Ergonómicos | | | |
| EP-002 | Gestión de Citas con Fisioterapeutas | | | |
| EP-003 | Seguimiento y Evaluación del Progreso del Paciente | | | |
| EP-004 | Mejoras en la Experiencia de Usuario y Pagos | | | |
| EP-005 | Interacción y Navegación en el Landing Page | | | |
| EP-006 | Gestión de Planes de Ejercicios | | | |
| EP-007 | Gestión de Usuarios y Fisioterapeutas | | | |
| EP-008 | Gestión de Registros de Usarios y Fisioterapeutas | | | |
  
- 3.3. Impact Mapping.

 	### Segmento Usuarios
  	![image](https://github.com/PhysioDesk/Informes/assets/89022078/adf3ed17-4305-452d-bf25-2121ebe0ee71)

	### Segmento Profesional
	![image](https://github.com/PhysioDesk/Informes/assets/89022078/1cd3908d-c5e6-4126-b987-1b7d041c42e5)

	Link para visualizar el Impact Map de ambos segmentos en UXPressia: https://uxpressia.com/w/2nIbe/i/yEYYu

- 3.4. Product Backlog.

| # Orden | User Story Id | Título | Descripción | Story Points (1 / 2 / 3) |
| --- | --- | --- | --- | --- |
| 1 | VISIT-001 | Sección de inicio del Landing Page | Como visitante, quiero una sección de "Inicio" que me brinde una visión general de la aplicación y sus características principales, para entender rápidamente de qué se trata y cómo puede beneficiarme como usuario. | 1 |
| 2 | VISIT-002 | Sección de servicios del Landing Page | Como visitante, quiero una sección de "Servicios" donde pueda encontrar información detallada sobre los diferentes servicios ofrecidos por la aplicación, incluyendo ejercicios recomendados, seguimiento de progreso y citas con fisioterapeutas, para comprender cómo puede ayudarme a mejorar mi salud y bienestar. | 1 |
| 3 | VISIT-003 | Sección de testimonios del Landing Page | Como visitante, quiero una sección de "Testimonios" donde pueda leer experiencias de usuarios anteriores y sus resultados, para tener confianza en la efectividad de la aplicación y sentirme motivado a utilizarla. | 1 |
| 4 | VISIT-004 | Sección de contacto del Landing Page | Como visitante, quiero una sección de "Contacto" con información de contacto clara y un formulario de contacto, para poder comunicarme con el equipo de soporte si tengo alguna pregunta o necesito asistencia. | 1 |
| 5 | VISIT-005 | Sección de colaboradores del Landing Page | Como visitante del segmento fisioterapeuta interesado en colaborar con la aplicación, quiero una sección de "Colaboradores" donde pueda obtener información sobre cómo puedo unirme a la plataforma y ofrecer mis servicios a los usuarios, para ampliar mi base de clientes y llegar a más personas necesitadas de atención física. | 1 |
| 6 | VISIT-006 | Sección de beneficios para profesionales del Landing Page | Como visitante del segmento fisioterapeuta, quiero una sección de "Beneficios para Profesionales" donde pueda conocer los beneficios de asociarse con la aplicación, como la posibilidad de llegar a nuevos clientes, gestionar citas de manera eficiente y acceder a herramientas de seguimiento del progreso del paciente, para tomar una decisión informada sobre mi colaboración. | 1 |
| 7 | USER-018 | Registrar dolores musculares | Como usuario de la aplicación, quiero poder registrar mis malestares musculoesqueléticos utilizando una imagen interactiva, para poder identificar y documentar con precisión las áreas afectadas de mi cuerpo. | 3 |
| 8 | USER-001 | Recibir recomendaciones para la correcta postura | Como usuario, quiero recibir recomendaciones sobre una correcta postura, para tratar o prevenir algún dolor muscular. | 3 |
| 9 | DVLOP-003 | Integrar Sistema de Citas | Como desarrollador, quiero integrar un sistema de gestión de citas para permitir que los usuarios reserven citas con fisioterapeutas, para facilitar la planificación y organización de las consultas. | 3 |
| 10 | USER-013 | Generar notificaciones de cita | Como usuario, quiero recibir automáticamente notificaciones antes de la hora programada para cada cita, para recordarme sobre las próximas citas. | 3 |
| 11 | USER-007 | Reservar cita con fisioterapeuta | Como usuario, quiero reservar una cita con un fisioterapeuta, con el fin de que me brinde asesoramiento y tratamiento para mis malestares. | 3 |
| 12 | USER-008 | Acceder a un entorno fácil de usar para la cita. | Como usuario, quiero acceder a un entorno de cita intuitivo y fácil de usar en la aplicación, para poder participar plenamente en la consulta y acceder a las funciones necesarias de manera clara y rápida. | 2 |
| 13 | FISIO-004 | Creación de planes de ejercicios de movimiento | Como fisioterapeuta, quiero poder crear planes de ejercicios de movimiento personalizados para mis usuarios, con el fin de ayudarles a mejorar su malestar y promover una recuperación efectiva. | 3 |
| 14 | USER-019 | Acceder al plan de ejercicios | Como usuario de la aplicación, quiero poder acceder al plan de ejercicios recomendado por mi fisioterapeuta, para poder realizarlos y mejorar mi condición física. | 1 |
| 15 | DVLOP-004 | Crear Endpoint para Consulta de Productos Ergonómicos | Como desarrollador, quiero implementar un endpoint GET para permitir a los usuarios consultar productos ergonómicos disponibles en la plataforma, para que los usuarios puedan ver y buscar productos fácilmente. | 2 |
| 16 | USER-002 | Agregar herramienta ergonómica al carrito de compra y proceder el pago | Como usuario, quiero poder agregar las herramientas ergonómicas seleccionadas a un carrito de compras y proceder al pago de manera segura, para completar fácilmente mi compra. | 3 |
| 17 | USER-004 | Filtrar herramientas ergonómicas | Como usuario, quiero filtrar las opciones disponibles de herramientas ergonómicas, para que la búsqueda sea más sencilla y encuentre el adecuado de acuerdo a mi disponibilidad económica. | 3 |
| 18 | USER-021 | Recibir recordatorio de ejercicios | Como usuario de la aplicación, quiero recibir una notificación cuando falte una hora para realizar un ejercicio recomendado por mi fisioterapeuta, para recordarme la hora de realizar la actividad y mantenerme en mi rutina de ejercicios. | 3 |
| 19 | USER-014 | Interactuar con las notificaciones de cita | Como usuario, quiero poder interactuar con las notificaciones de recordatorio de cita, para acceder rápidamente a los detalles de la cita o confirmar/cancelar la cita desde la notificación. | 3 |
| 20 | FISIO-002 | Analizar el progreso del paciente | Como fisioterapeuta, quiero analizar el progreso del paciente, para evaluar su evolución y ajustar el plan de tratamiento según sea el malestar. | 3 |
| 21 | FISIO-003 | Generar informes | Como fisioterapeuta, quiero generar informes de progreso para comunicar la evolución del paciente de manera efectiva. | 3 |
| 22 | USER-017 | Pagar con diversos medios de pago para acceder a la versión premium de la app | Como usuario interesado en acceder a la versión premium de la aplicación, quiero poder realizar el pago utilizando diferentes métodos de pago para mayor conveniencia y accesibilidad. | 3 |
| 23 | USER-003 | Ver detalle de la herramienta ergonómica | Como usuario, quiero ver una lista clara y detallada de las características de cada herramienta ergonómica, incluyendo descripción, precio y disponibilidad, para tomar decisiones de compra informadas. | 2 |
| 24 | USER-005 | Ver detalle de la compra | Como usuario, quiero recibir una confirmación clara y detallada de mi compra, incluyendo información sobre los productos adquiridos y el total de la compra, para tener una referencia de la transacción realizada. | 2 |
| 25 | USER-009 | Grabación automática de la cita | Como usuario, quiero que la sesión de mi cita se graba automáticamente en cuanto comience la consulta en el entorno de la cita, para poder revisar posteriormente para un seguimiento efectivo del tratamiento y repasar las recomendaciones proporcionadas durante la consulta. | 2 |
| 26 | USER-012 | Configurar notificaciones de cita | Como usuario, quiero configurar las notificaciones de recordatorio para mis citas, para recibir recordatorios antes de cada cita programada. | 2 |
| 27 | FISIO-001 | Registrar detalles de cada sesión de tratamiento | Como fisioterapeuta, quiero registrar detalles de cada sesión de tratamiento, para llevar un registro preciso del progreso del paciente. | 2 |
| 28 | FISIO-005 | Afiliar cuenta de ahorros para recibir pagos | Como fisioterapeuta, quiero poder afiliar mi cuenta de ahorros, para recibir pagos por los servicios prestados a través de la aplicación. | 2 |
| 29 | FISIO-006 | Registrar horario disponible por parte del fisioterapeuta | Como fisioterapeuta quiero poder registrar mis horarios disponibles para sesiones de terapia, para que los usuarios puedan reservar citas conmigo según mi disponibilidad. | 2 |
| 30 | USER-020 | Marcar ejercicios como completados | Como usuario de la aplicación, quiero poder marcar los ejercicios del plan como completados, para llevar un registro de mi progreso y seguimiento de mis sesiones de ejercicio. | 1 |
| 31 | USER-011 | Calificar al fisioterapeuta | Como usuario, quiero calificar al fisioterapeuta cada vez que se lleva a cabo una cita, para expresarme sobre cómo me siento con el servicio. | 1 |
| 32 | USER-010 | Acceder a las grabaciones | Como usuario, quiero acceder fácilmente a las grabaciones de mis sesiones de citas anteriores, para poder revisarlas en cualquier momento y asegurarse de seguir correctamente las instrucciones y recomendaciones proporcionadas durante la consulta. | 1 |
| 33 | USER-006 | Visualizar los horarios de atención de cada fisioterapeuta | Como usuario, quiero visualizar los horarios disponibles de cada fisioterapeuta, para conocer cuál se acomoda a mis tiempos libres. | 1 |
| 34 | FISIO-007 | Enviar solicitud de incorporación como fisioterapeuta | Como fisioterapeuta interesado en colaborar con la aplicación, quiero poder enviar una solicitud de incorporación desde el landing page para iniciar el proceso de registro. | 2 |
| 35 | DVLOP-001 | Crear Endpoint para Registro de Usuario | Como desarrollador, quiero crear un endpoint POST para permitir el registro de nuevos usuarios en la plataforma PhysioDesk, para que los usuarios puedan crear cuentas y acceder a la funcionalidad completa. | 2 |
| 36 | USER-022 | Registrarse en la aplicación | Como usuario interesado en mejorar su postura y bienestar general, quiero poder registrarme en la aplicación de manera sencilla e intuitiva, para acceder a todas las funcionalidades y servicios disponibles de manera rápida. | 2 |
| 37 | DVLOP-002 | Implementar Autenticación de Usuario | Como desarrollador, quiero agregar autenticación basada en tokens JWT para proteger los endpoints sensibles de la API, para garantizar la seguridad de los datos del usuario y restringir el acceso no autorizado. | 3 |

Link para visualizar el Product Backlog en Pivotal Tracker: https://www.pivotaltracker.com/n/projects/2700540
  

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
