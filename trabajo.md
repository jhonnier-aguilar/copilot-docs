DISEÑO DE LA INFRAESTRUCTURA DE RED EN CENTRAL MOTOR EN LA CIUDAD DE BUCARAMANGA



JHONNIER ENRIQUE AGUILAR BARBOSA.
LAURA DANIELA PINZON LIZARAZO
PABLO ESNEIDER MOGOLLON FLOREZ






UNIVERSIDAD DE INVESTIGACIÓN Y DESARROLLO
FACULTAD INGENIERÍAS
PROGRAMA DE INGENIERÍA DE SISTEMAS
BUCARAMANGA, SANTANDER
2025
DISEÑO DE LA INFRAESTRUCTURA DE RED EN CENTRAL MOTOR EN LA CIUDAD DE BUCARAMANGA



JHONNIER ENRIQUE AGUILAR BARBOSA
LAURA DANIELA PINZON LIZARAZO
PABLO ESNEIDER MOGOLLON FLOREZ






UNIVERSIDAD DE INVESTIGACIÓN Y DESARROLLO
FACULTAD INGENIERÍAS
PROGRAMA DE INGENIERÍA DE SISTEMAS
BUCARAMANGA, SANTANDER
2025
DISEÑO DE LA INFRAESTRUCTURA DE RED EN CENTRAL MOTOR EN LA CIUDAD DE BUCARAMANGA

JHONNIER ENRIQUE AGUILAR BARBOSA
LAURA DANIELA PINZÓN LIZARAZO
PABLO ESNEIDER MOGOLLÓN FLÓREZ

Proyecto de grado presentado como requisito para optar al título de Ingeniera de Sistemas


Director
MSc Wilson Darío Alfonso Alvarado


Universidad De Investigación Y Desarrollo
Facultad Ingenierías
Programa De Ingeniería De Sistemas
Bucaramanga, Santander
2025
Dedicatoria
Jhonnier,


Laura,


Pablo,


Agradecimientos




Abstract
In the current context of the Colombian automotive sector, companies face the ongoing challenge of adapting to a dynamic and highly competitive environment, where agility, operational efficiency, and technological innovation are essential for sustainability and growth. The increasing demand from consumers for fast, reliable, and personalized solutions has accelerated digital transformation, compelling organizations to optimize processes, reduce response times, and ensure service continuity as key strategies to build trust and loyalty.
This project addresses the redesign and implementation of a robust and scalable network infrastructure for Central Motor S.A.S., a company with over 30 years of experience in the automotive industry in Bucaramanga. The initiative seeks not only to resolve operational inefficiencies that have impacted service quality but also to lay a solid technological foundation capable of integrating innovative solutions for future challenges.
Using a methodology based on simulation, technical analysis, and networking best practices, the proposed design ensures enhanced connectivity, security, and system availability. Moreover, this project supports the organizational mission of Central Motor by reinforcing its market positioning and commitment to employee and community development.
Academically, this work marks the culmination of the authors’ training in Systems Engineering, representing the integration of theoretical knowledge and practical skills to develop impactful technological solutions for the business environment.

Tabla de Contenido
1.	Problemática de investigación	16
1.1.	Descripción del problema	16
1.2.	Organigrama	18
1.2.1.	Administrativo	18
1.2.2.	Mercadeo	19
1.3.	Formulación de Problema	26
1.4.	Objetivos	27
1.4.1.	Objetivo General	27
1.4.2.	Objetivos Específicos	27
1.5.	Justificación	28
2.	Marco Referencial	30
2.1.	Marco Teórico	30
2.1.1.	Antecedentes de la Investigación	30
2.2.	Marco Conceptual	32
2.3.	Marco Normativo	38
2.4.	Marco Tecnológico	40
3.	Metodología	45
3.1.	Tipo de Investigación	45
3.2.	Metodología PPDIOO	47
3.2.1.	Planeación	48
3.2.1.1.	Evaluación de la Infraestructuras Existente.	49
3.2.1.2.	Aplicativos.	63
3.2.1.3.	Descripción Técnica del Estado de Dispositivos, Cableado y Servicios.	70
3.2.1.4.	Inventario con Versiones de Firmware y Antigüedad.	77
3.2.1.4.1.	Equipos de Cómputo.	77
3.2.1.4.2.	Equipos de Red.	79
3.2.1.5.	Identificación de Limitaciones Operativas y Estructurales.	82
3.2.1.6.	Informe de Riesgos y Vulnerabilidades.	83
3.2.1.6.1.	Diagrama Actualizado de la Topología Física y Lógica de la Red.	86
3.2.1.7.	Propuesta de Mejora, Orientadas a la Redundancia, Escalabilidad y Fortalecimiento de la Seguridad	93
3.2.1.7.1.	Diseño de la Infraestructura de Red en Central Motor.	93
3.2.2.	Preparación	96
3.2.2.1.	Definición de Requisitos Técnicos.	96
3.2.2.2.	Identificación de Objetivos de Escalabilidad de para la Nueva Infraestructura.	96
3.2.2.3.	Definición de Requerimientos de Protección de Datos y Accesos.	97
3.2.2.4.	Recopilación de Requisitos de Diseño Físico y Lógico de la Red.	97
3.2.2.5.	Entregables.	97
3.2.2.5.1.	Proyección de Crecimiento Futuro y Estrategias para Soportar Mayor Demanda.	97
3.2.2.5.2.	Descripción de los Equipos Necesarios de Red y Computo.	99
3.2.2.5.3.	Presupuesto de Implementación.	101
3.2.2.5.4.	Diagramas Preliminares de las Conexiones Lógicas de Red	102
3.2.2.6.	Identificación de Riesgos Potenciales y Estrategias para Mitigarlos.	107
3.2.2.6.1.	Matriz de Riesgo	107
3.2.2.6.2.	Lista de Verificación para la Mitigación de Riesgos Asociados al Cumplimiento de Requisitos	108
3.2.3.	Diseño	112
3.2.3.1.	Definición de herramienta de simulación a emplear para el proyecto.	112
3.2.3.2.	Validación de los Protocolos de Acceso y Autenticación.	112
3.2.3.3.	Desarrollo del Diseño Físico de la Red.	112
3.2.3.4.	Creación del Diseño Lógico.	113
3.2.3.5.	Entregables.	113
3.2.3.5.1.	Listado de Equipos con Implementación y Cambios de la Infraestructura Actual.	113
3.2.3.5.2.	Diagramas preliminares de las conexiones lógicas de la red.	118
3.2.3.5.3.	Diagrama que representa la configuración física	123
3.2.4.	Despliegue	126
3.2.4.1.	Ejecución de la Simulación de la Red Diseñada.	126
3.2.4.2.	Prueba de las Configuraciones de Seguridad Dentro de la Simulación.	126
3.2.4.3.	Entregables.	126
3.2.4.3.1.	Plano con la Disposición de Todos los Dispositivos de Red, Cableado y la Infraestructura Física.	126
3.2.5.	Operación	127
3.2.5.1.	Implementación del Ambiente de Pruebas.	127
3.2.5.2.	Entregables.	127
3.2.5.2.1.	Informe de las Configuraciones Aplicadas en el Entorno de Pruebas.	127
3.2.5.2.2.	Reporte de Resultados de las Pruebas Realizadas.	127
3.2.5.2.3.	Documento de Cambios Efectuados Durante las Pruebas.	127
3.2.6.	Optimización	128
4.	Conclusiones	129
5.	Recomendaciones	130
6.	Referencias	131


Lista de Ilustraciones
Ilustración 1	18
Ilustración 2	19
Ilustración 3	19
Ilustración 4	20
Ilustración 5	20
Ilustración 6	21
Ilustración 7	21
Ilustración 8	22
Ilustración 9	22
Ilustración 10	23
Ilustración 11	23
Ilustración 12	24
Ilustración 13	25
Ilustración 14	25
Ilustración 15	50
Ilustración 16	51
Ilustración 17	53
Ilustración 18	54
Ilustración 19	55
Ilustración 20	56
Ilustración 21	58
Ilustración 22	59
Ilustración 23	60
Ilustración 24	61
Ilustración 25	62
Ilustración 26	63
Ilustración 27	64
Ilustración 28	64
Ilustración 29	65
Ilustración 30	65
Ilustración 31	66
Ilustración 32	67
Ilustración 33	68
Ilustración 34	70
Ilustración 35	73
Ilustración 36	73
Ilustración 37	74
Ilustración 38	75
Ilustración 39	75
Ilustración 40	87
Ilustración 41	87
Ilustración 42	88
Ilustración 43	89
Ilustración 44	89
Ilustración 45	89
Ilustración 46	90
Ilustración 47	91
Ilustración 48	103
Ilustración 49	105
Ilustración 50	106
Ilustración 51	107
Ilustración 52	124
Ilustración 53	124
Ilustración 54	125
Ilustración 55	125



Lista de Tablas
Tabla 1	100
Tabla 2	101
Tabla 3	101
Tabla 4	109
Tabla 5	110
Tabla 6	114
Tabla 7	116
Tabla 8	117
Tabla 9	117
Tabla 10	118
Tabla 11	121
Tabla 12	122


Introducción
En el contexto actual del sector automotriz colombiano, las empresas enfrentan el desafío constante de adaptarse a un entorno dinámico y altamente competitivo, donde la agilidad, la eficiencia operativa y la innovación tecnológica son factores clave para la sostenibilidad y el crecimiento. La demanda creciente por parte de consumidores que buscan soluciones rápidas, confiables y personalizadas ha impulsado una transformación digital que obliga a las organizaciones a optimizar sus procesos, reducir los tiempos de respuesta y garantizar la continuidad del servicio como mecanismos fundamentales para generar confianza y fidelización.
El presente proyecto surge como respuesta a esta necesidad de transformación, abordando específicamente el rediseño e implementación de una infraestructura de red robusta y escalable para la empresa Central Motor S.A.S., una organización con más de 30 años de trayectoria en el sector automotriz de Bucaramanga. Este proceso busca no solo corregir deficiencias operativas que han impactado la calidad del servicio, sino también sentar las bases tecnológicas para afrontar los retos del futuro con una red más segura, eficiente y preparada para integrar soluciones innovadoras.
A través de un enfoque fundamentado en la simulación, análisis técnico y aplicación de buenas prácticas en redes, el proyecto propone un diseño que responde a las exigencias actuales del negocio, garantizando mayor conectividad, seguridad y disponibilidad. Además, esta iniciativa contribuye al cumplimiento de la misión organizacional de Central Motor, fortaleciendo su posicionamiento en el mercado y su compromiso con el desarrollo de sus colaboradores y de la comunidad.


1.Problemática de investigación
1.1.Descripción del problema
El sector automotriz colombiano actualmente exige agilidad para mantenerse en un entorno de constante cambio, donde los consumidores buscan soluciones rápidas y eficientes. Según un informe de la Asociación Nacional de Empresarios de Colombia (ANDI, 2023), las empresas del sector deben implementar estrategias de digitalización y optimización de procesos para adaptarse a las altas demandas del mercado y mejorar su eficiencia operativa (ANDI, 2023). Esto obliga a las empresas de este sector a optimizar sus procesos y reducir los tiempos de respuesta. La continuidad en el servicio, sin interrupciones ni demoras, es esencial para generar confianza y fidelizar a los clientes.
La tecnología, por otro lado, también nos permite ofrecer innovaciones que no son simplemente lo que más desean nuestros clientes, sino algo más. Un artículo de Forbes (Claps, 2023) amplía aún más este argumento discutiendo que las empresas que comienzan a adoptar nuevas tecnologías no solo mejoran en habilidades, sino que también comienzan a cumplir con las expectativas de sus clientes. Esto no solo mejorará la productividad, sino que además permitirá que nuestras empresas reajusten las áreas donde son necesarios cambios. Así, las empresas automotrices podrían hacer que estas innovaciones funcionen para ellas al demostrar el compromiso continuo con el cliente a través de la mejora continua y el refinamiento de la función de ventas y servicio. Un estudio de McKinsey & Company (McKinsey & Company, 2021) informa que, en el entorno altamente competitivo de hoy, las empresas que se centran no solo en el cliente, sino también en la personalización, tienen la capacidad de ofrecer satisfacción y lealtad a través de la recompensa y el logro, lo que sin duda conducirá al éxito.
Esa es la razón por la que se empleará a Central Motor S.A.S. para el diseño y despliegue de las nuevas máquinas de la red; dicha empresa tiene 30 años en el sector automotriz de Bucaramanga y, durante mucho tiempo, ha demostrado ser líder del mercado en la región. A lo largo de los años, el constante crecimiento de sede central hizo que la red fuera menos eficiente, lo que se reflejaba en problemas operativos como cortes de suministro y fallas de equipos y amenazaba la continuidad del negocio. Estos errores afectaron la estabilidad de la conexión, el rendimiento general de la red y, por lo tanto, la calidad de los servicios prestados a los clientes. Por lo tanto, es seguro decir que el principal objetivo del proyecto es aumentar la conectividad, la seguridad, la escalabilidad y el rendimiento, garantizar la difusión de redes flexibles y la preparación empresarial para desafíos actuales y futuros. 
Al implementar este proyecto, Central Motor apoya el alcanzar su misión de “Identificar las necesidades de nuestros clientes, satisfaciendo con excelentes productos y servicios; creando un ambiente que propicie el desarrollo integral de los colaboradores y optimizando los recursos para lograr un nivel de rentabilidad y crecimiento atractivo para los inversionistas, que nos ubique a la vanguardia del mercado y contribuya al desarrollo de nuestra comunidad” (Central, s/f), respaldándose en una red sólida y confiable para su constante crecimiento y éxito a largo plazo.


1.2.Organigrama
El organigrama de Central Motor representa la estructura jerárquica y funcional de la empresa, estableciendo la distribución de responsabilidades y las relaciones entre sus diferentes áreas. A través de este esquema, se visualiza la cadena de mando, permitiendo identificar los niveles de autoridad, los departamentos clave y la interacción entre ellos. Su diseño busca optimizar la eficiencia operativa, garantizar un flujo adecuado de comunicación y facilitar la toma de decisiones estratégicas dentro de la organización
1.2.1.Administrativo 
El Departamento de Contabilidad se encuentra estructurado bajo la dirección general de la Gerente General, quien lidera la organización a nivel estratégico. Bajo su supervisión, se articulan diversas áreas encabezadas por cargos de jefatura, entre los que se destacan: Asistente de Gerencia, Jurídico, Sistemas y Contabilidad. Dentro de esta estructura, el rol de supervisión recae principalmente en dos figuras: la Asistente de Gerencia y la Jefa de Contabilidad.
La Asistente de Gerencia tiene bajo su responsabilidad a dos personas encargadas del aseo general y a dos orientadores. Por otra parte, la Jefa de Contabilidad lidera y supervisa un equipo operativo compuesto por las áreas de nómina, tesorería, auxiliar contable, cartera (con dos personas asignadas), auditoría, caja, facturación de taller, facturación electrónica, así como dos personas responsables de la facturación de vehículos.
Ilustración 1
Departamento Administrativo Central Motor

1.2.2.Mercadeo
El Departamento de Mercadeo está conformado por una jefa la cual ocupa el cargo de directora de Mercadeo, seguido de dos diseñadores gráficos, una community manager y un diseñador audiovisual. Esta área se encuentra bajo la supervisión directa de la Gerente General.
Ilustración 2
Departamento Mercadeo Central Motor


1.2.3.Repuestos
El área de Repuestos está conformada por una jefatura que ocupa el cargo de Jefe de Repuestos, bajo cuya coordinación se encuentran dos asesores de mostrador, un auxiliar de bodega, un asesor de colisión y un asesor de taller. Esta área se encuentra bajo la supervisión directa de la Gerente General
Ilustración 3 
Departamento Repuestos Central Motor

1.2.4.Taller Kia
El área de taller de Kia se encuentra liderado por el jefe de taller, seguido por empleados que ocupan cargos como garantía de taller, un asesor de servicio, un callcenter de taller, cuatro técnicos que son especializados, cuatro técnicos de conocimientos básicos, un lavador y un recepcionista.
Ilustración 4 
Departamento Taller Kia Central Motor


1.2.5.Taller Hyundai -Derco

Esta área de taller abarca dos marcas, las cuales son Hyundai y Derco, se encuentra encabezado por un jefe de taller, de ahí se desglosa el cargo de garantía de taller, dos asesores de servicio, una persona de callcenter, cuatro técnicos especializados, cuatro técnicos de conocimiento básico y un lavador.
Ilustración 5 
Departamento Taller Hyundai - Derco Central Motor


1.2.6.Taller Ford
El departamento de taller Ford, se encuentra como jefe el gerente posventa, seguido de los cargos como callcenter de taller, experiencia al cliente, torre de control, dos personas en el cargo de garantía, un asesor de servicio y un jefe de taller que encabeza a los técnicos que son un total de 7 y un lavador de vehículos. 
Ilustración 6
Departamento Taller Ford Central Motor


1.2.7.Repuestos Ford
El área de repuestos Ford se encuentra liderada por la jefe de repuestos, quien tiene a cargo las personas de asesor de mostrador, auxiliar de bodega, asesor de colisión y un asesor de taller.
Ilustración 7 
Departamento Repuestos Ford Central Motor


1.2.8.Colisión
El departamento de colisión está encabezado por el jefe de colisión, quien se encarga de las personas tales como un analista de página, un latonero, un pintor, un técnico y un lavador. 
Ilustración 8 
Departamento Taller Colisión Central Motor


1.2.9.Logística
El departamento de logística se encuentra compuesto por la jefe de logística, quien tiene a cargo las personas de alistamiento, un lavador, y 7 alistadores
Ilustración 9 
Departamento Logística Central Motor



1.2.10.Comercial Usados

El departamento de Comercial Usados se encuentra compuesto por un gerente de Marca, seguido del área comercial que se encuentra divido en tres asesores comerciales.
Ilustración 10 
Departamento Comercial Usados Central Motor


1.2.11.Comercial Derco

El área comercial de Derco corresponde dos marcas que se divide en Suzuki y Citroën, el cual se encuentra liderado por el gerente de dicha marca, que sigue del personal de mercadeo quien lidera a los siete asesores comerciales en conjunto de una persona encargada del área financiera.
Ilustración 11 
Departamento Comercial Derco Central Motor


1.2.12.Comercial Hyundai

El área comercial de Hyundai, el cual se encuentra encabezado por el gerente de marca, le sigue el personal de mercadeo quien lidera a los cinco asesores comerciales en conjunto de una persona encargada del área financiera.
Ilustración 12
Departamento Comercial Hyundai Central Motor


1.2.13.Comercial Kia

El departamento de Comercial de Kia se encuentra compuesto principalmente por el gerente de Marca, seguido de la persona encargada de mercadeo quien es la encargada de liderar al equipo de doce (12) asesores comerciales, una persona encargada del área financiera y una persona que se encarga de la experiencia al cliente.

Ilustración 13 
Departamento Comercial Kia Central Motor


1.2.14.Comercial Ford

El área de Comercial de Ford se encuentra compuesto por el gerente de Marca, seguido de la persona encargada de mercadeo quien lidera al equipo de cinco (5) asesores comerciales y una persona encargada del área financiera.

Ilustración 14 
Departamento Comercial Ford Central Motor


1.3.Formulación de Problema
¿Cómo puede el diseño de una nueva infraestructura de red optimizar la gestión de la empresa Central Motor?


1.4.Objetivos
1.4.1.Objetivo General
Diseñar mediante una simulación, una infraestructura de red eficiente, segura y escalable para Central Motor en Bucaramanga, que proteja los datos y favorezca la continuidad operativa de la empresa.
1.4.2.Objetivos Específicos
Analizar la infraestructura de red actual de Central Motor, mediante la inspección de equipos, revisión de la red, su tráfico, rendimiento y seguridad actuales, para determinar su estado y los requerimientos necesarios para su mejora.
Establecer políticas de red enfocadas en la protección de datos, la optimización del tráfico, y la implementación de estándares de seguridad que aseguren la continuidad operativa de la empresa.
Diseñar una nueva propuesta de infraestructura de red, basada en los requerimientos identificados, para aportar eficiencia, seguridad, escalabilidad y rendimiento en distintos escenarios operativos. 
Realizar pruebas de la infraestructura simulada, definiendo escenarios específicos para verificar la seguridad y la calidad del servicio en la red propuesta.

1.5.Justificación
Los avances que se han realizado en el campo de redes, en el sector automotriz han sido críticos para la eficiencia, seguridad y flexibilidad de la industria. Es por eso que las redes confiables permiten a las empresas procesar grandes volúmenes de datos de los vehículos conectados y sus sistemas. Estos desarrollos no sólo mejoran la conectividad, sino que también, permiten la integración de tecnologías como mejoras actualizadas a los vehículos de manera oportuna y servicios de movilidad inteligente. Es la razón por la cual las empresas al implementar dichas mejoras en su infraestructura, pueden mejorar el rendimiento de la infraestructura crítica, como lo pueden ser los sistemas de seguridad, la gestión de datos, la productividad de los empleados y la experiencia del cliente.
También garantiza la estabilidad y continuidad del servicio, lo cual es importante para seguir siendo competitivo en una industria donde el tiempo de respuesta y la precisión son fundamentales	(dotmagazine, 2023). Según Stallings, W. (Stallings, 2014) la necesidad de una red robusta que soporte el tráfico de voz, datos, imágenes y video no se limita a un solo edificio u oficina; se ha convertido en un requisito fundamental para la comunicación empresarial integral.
Durante el desarrollo del proyecto, se recurrió a la simulación para ajustar y refinar elementos clave del diseño, con el fin de asegurar que la infraestructura respondiera adecuadamente a las necesidades de la organización y maximizara su rendimiento antes de proceder a una implementación física. Este enfoque permitió detectar problemas potenciales como cuellos de botella, puntos de falla o limitaciones de capacidad que, de no haberse identificado a tiempo, habrían comprometido la eficiencia y seguridad de la red en un entorno real.
El despliegue de una red sólida incrementó de manera significativa la eficiencia de los procesos internos, promoviendo un uso más efectivo de los recursos y fortaleciendo la competitividad en el mercado. Esta iniciativa también facilitó la adaptación a los desafíos tecnológicos contemporáneos, asegurando la continuidad de las operaciones en un entorno seguro y confiable. No solo se promovió el crecimiento empresarial, sino que también se fomenta un ambiente laboral propicio para el desarrollo del talento humano, generando beneficios tanto para la organización como para la comunidad.
Finalmente, la ejecución de este proyecto respondió a los requisitos académicos establecidos para la obtención del título de Ingenieros de Sistemas, constituyéndose como el proyecto de grado y consolidando la formación profesional de sus autores.

2.Marco Referencial
2.1.Marco Teórico
2.1.1.Antecedentes de la Investigación
En las comunicaciones e infraestructura de redes, la eficiencia, la disponibilidad y la escalabilidad son esenciales para el éxito de la operación. Varias empresas se han encontrado con problemas críticos en sus redes y han decidido implementar soluciones similares.
Por ejemplo, a nivel nacional, la empresa Camargo S.A.S, según el estudio de Ortiz, Camargo, y Monroy (Sánchez Ortiz et al., 2022), está empresa se enfoca en Outsourcing de contabilidad, que actualmente dispone de dos oficinas, que se encuentran ubicadas en Bogotá y Bucaramanga, identificó fallos en la eficiencia y seguridad de su red, lo que afectó la productividad y la integridad de los datos. La falta de redundancia y mantenimiento causaba interrupciones y dificultades en la gestión de información, por lo que optaron por actualizar su infraestructura, buscando mayor eficiencia operativa y seguridad.
De manera similar, el Banco Nacional en la ciudad de Bogotá, según el estudio de Plazas, Quintero y Ariza (Jara Plazas et al., 2014), tuvo que enfrentar problemas de disponibilidad y redundancia en su red LAN. Para garantizar una disponibilidad del 99,9%, implementaron una infraestructura robusta y redundante que mejoró el rendimiento de los servicios de datos y voz, asegurando una conectividad confiable y satisfaciendo los estándares de seguridad y operación. Hay que resaltar igualmente el rendimiento de los servicios de voz en una red, así como se hizo en este proyecto, ya que mejora significativamente la comunicación interna al integrar la voz con los datos, facilitando una colaboración más fluida entre los departamentos. Además, optimiza los costos operativos, eliminando la necesidad de líneas telefónicas tradicionales, ya que la voz viaja sobre IP (VoIP). Esto también ofrece una gran flexibilidad, permitiendo que los empleados puedan trabajar desde cualquier ubicación mientras acceden a los mismos servicios de voz que en la oficina.
En Estados Unidos, Databank (DataBank, 2022) implementó una infraestructura sólida de redundancia y conmutación por error. Este proyecto tenía como objetivo aumentar la tolerancia a fallas, minimizar el riesgo de fallas y mejorar la recuperación ante desastres. Al duplicar equipos críticos como enrutadores, conmutadores y enlaces de red, y usar protocolos avanzados como VRRP y HSRP, crearon una infraestructura que puede soportar fallas sin interrumpir el servicio.

2.2.Marco Conceptual
2.2.1.Infraestructura de TI: Es un conjunto de componentes tecnológicos físicos y lógicos que respaldan las actividades de una organización. Incluye hardware (servidores, equipos de red), software (sistemas operativos, aplicaciones), redes (cableadas e inalámbricas) y medidas de seguridad. Una infraestructura bien diseñada es esencial para la eficiencia operativa, las comunicaciones efectivas y la seguridad de los datos (Kurose & Ross, 2017; Stallings, 2014).
2.2.2.Infraestructura de Red: La infraestructura de red se refiere a la disposición física y lógica de los recursos tecnológicos que permiten la transmisión de datos (Forouzan, 2007). Incluye todos los componentes que facilitan la conectividad, desde cables y switches hasta routers y servidores.
2.2.3.Conectividad: La conectividad es fundamental en cualquier red para asegurar la transferencia de datos entre usuarios o sistemas conectados (Tanenbaum & Wetherall, 2011). Esto implica la capacidad de los dispositivos para comunicarse entre sí, lo cual es fundamental para el funcionamiento de cualquier sistema de red.
2.2.4.Escalabilidad: La escalabilidad es una característica clave en el diseño de redes modernas, asegurando que el sistema pueda manejar incrementos en la carga sin perder eficiencia (Kurose & Ross, 2017). Esto significa que la red puede expandirse para acomodar más usuarios y datos sin comprometer el rendimiento.
2.2.5.Seguridad de la Información: La seguridad de la información abarca todas las medidas destinadas a proteger los datos, garantizando su confidencialidad, integridad y disponibilidad (Stallings, 2014). Es crucial para prevenir accesos no autorizados y garantizar que la información sea accesible solo para quienes tienen permiso.
2.2.6.Medio de Red Cableada: "Las redes cableadas se basan en la transmisión de datos a través de cables de cobre o fibra óptica" (Olifer, 2006). Estas redes suelen ofrecer una mayor velocidad y estabilidad en comparación con las redes inalámbricas, aunque requieren instalación física.
2.2.7.Medio de Red Inalámbrica: "Las redes inalámbricas utilizan frecuencias de radio para conectar dispositivos sin la necesidad de cables físicos" (Gast, 2013). Son convenientes para la movilidad y el acceso a internet en áreas donde no se pueden instalar cables.
2.2.8.Protocolo de Comunicación: Los protocolos de comunicación son reglas y convenciones que determinan cómo se transmiten los datos en una red. Son esenciales para garantizar la interoperabilidad y la eficacia en la comunicación entre diferentes dispositivos y sistemas. (Kurose & Ross, 2016)
2.2.9.Cableado Estructurado: "El cableado estructurado facilita el diseño, la instalación y el mantenimiento de las redes modernas" (Siemon, 2014). Este enfoque sistemático mejora la organización del cableado, reduce la complejidad y permite la gestión eficiente de la infraestructura.
2.2.10.Ancho de Banda: "El ancho de banda de una red determina la capacidad de transmisión de datos y afecta directamente el rendimiento" (Kurose & Ross, 2016). Un mayor ancho de banda permite la transferencia de más datos simultáneamente, lo que mejora la velocidad y eficiencia de la red.
2.2.11.Dispositivos de Red: "Los dispositivos de red permiten la administración y el control del flujo de datos dentro de una red" (Stallings, 2017). Estos dispositivos, como routers y switches, son esenciales para dirigir el tráfico y asegurar una comunicación eficiente.
2.2.12.Switch: Para este proyecto se realiza un switch de capa 3, combina las funciones de un switch de Capa 2 con capacidades de enrutamiento de Capa 3, permitiendo la comunicación entre diferentes VLANs y subredes. Esta capacidad de encaminamiento interno mejora el rendimiento de la red al reducir la necesidad de un router externo para la comunicación intersubred. (Lammle, 2016)
2.2.13.Router: El Router es un dispositivo fundamental en redes que conecta diferentes segmentos de red y toma decisiones sobre el mejor camino para el tráfico de datos, operando a nivel de Capa 3 del modelo OSI. Los routers son esenciales para la comunicación en Internet, permitiendo la interconexión de redes locales y la navegación en la web. (Lammle, 2016)
2.2.14.QoS (Quality of Service): El QoS es crucial en redes que requieren priorización del tráfico, como aquellas que manejan aplicaciones críticas (Forouzan, 2007). Esto asegura que aplicaciones como la videoconferencia o la telefonía IP reciban el ancho de banda necesario para funcionar sin interrupciones.
2.2.15.Topología de Red: La topología de red define la disposición física o lógica de los nodos y conexiones en una red (Tanenbaum & Wetherall, 2011). Existen varias topologías, como estrella, anillo y malla, cada una con ventajas y desventajas según las necesidades de la red.
2.2.16.Virtualización de Red: La virtualización de red permite la creación de múltiples redes lógicas independientes dentro de una infraestructura física compartida (Howard, 2023). Esta técnica mejora la eficiencia y flexibilidad, permitiendo a las empresas utilizar sus recursos de manera más efectiva.
2.2.17.Ciberseguridad: La ciberseguridad implica la protección de sistemas y redes frente a amenazas que buscan comprometer la integridad de la información (Stallings, 2014). Esto incluye la implementación de firewalls, antivirus y políticas de acceso para proteger los datos críticos.
2.2.18.Planificación de Capacidad: La planificación de capacidad garantiza que las redes puedan escalar para cumplir con las demandas futuras sin perder rendimiento (Kurose & Ross, 2017). Implica evaluar el uso actual y proyectar necesidades futuras para asegurarse de que la infraestructura pueda soportar el crecimiento.
2.2.19.Redes de Área Local (LAN): Las LAN son redes que operan dentro de un área limitada, típicamente dentro de un edificio o campus (Forouzan, 2007). Son ideales para la interconexión de dispositivos en un entorno relativamente pequeño, ofreciendo alta velocidad de comunicación.
2.2.20.Red de Área Extendida (WAN): Las Redes de Área Amplia (WAN) son redes que cubren áreas geográficas extensas, interconectando múltiples LAN. Permiten la comunicación y transferencia de datos entre ubicaciones distantes (Stallings, 2014).
2.2.21.Modelo OSI (Open Systems Interconnection): El modelo OSI divide las funciones de red en siete capas para estandarizar y facilitar la interoperabilidad entre sistemas (AWS, s/f). Este modelo ayuda a comprender cómo se comunican los dispositivos en una red y a desarrollar protocolos de comunicación.
2.2.22.Simulación de Redes: La simulación de redes permite analizar el rendimiento y detectar posibles problemas antes de la implementación física (Tanenbaum & Wetherall, 2011). Esto ayuda a optimizar el diseño de la red y a identificar cuellos de botella o problemas de rendimiento antes de que ocurran en un entorno real.
2.2.23.Despliegue de Red: El despliegue de red involucra la instalación y configuración de los componentes para asegurar un rendimiento eficiente (González López et al., 2021). Este proceso es crítico para garantizar que todos los elementos de la infraestructura de red funcionen de manera conjunta y efectiva.
2.2.24.Latencia: La latencia de red se refiere al intervalo de tiempo que transcurre desde que se inicia el envío de datos desde un origen hasta que estos llegan a su destino a través de una red. Este retraso puede estar influenciado por diversos factores, como la distancia física entre los puntos de comunicación, la infraestructura de la red y otros elementos que afectan la velocidad de transmisión de los datos. (¿Qué es la latencia?, 2023)
2.2.25.Redundancia de Red: Es una estrategia de diseño que implica la incorporación de dispositivos, equipos y enlaces de comunicación adicionales dentro de una infraestructura de red. Su objetivo principal es garantizar la continuidad del servicio en caso de fallos en los componentes principales. (Redundancia de red, s/f)
2.2.26.Mantenimiento de Red: Es un proceso continuo y esencial para garantizar el rendimiento óptimo y confiable de las infraestructuras de telecomunicaciones. Este proceso abarca desde la planificación y diseño inicial hasta las medidas de seguridad y mantenimiento preventivo, asegurando que los sistemas de comunicación funcionen de manera eficiente y sin interrupciones. (Seguridad 360, 2023)
2.2.27.Servicio de voz: El servicio de voz, a menudo implementado a través de tecnologías VoIP, permite la comunicación de voz sobre redes de datos. Esto reduce costos y mejora la flexibilidad al permitir que los empleados se conecten desde diversas ubicaciones (Forouzan, 2007).
2.2.28.Servicio de Datos: El servicio de datos se refiere a la transmisión de información digital a través de redes. Un servicio de datos eficiente es fundamental para las operaciones comerciales, permitiendo el intercambio rápido y seguro de información. (Tanenbaum & Wetherall, 2011)
2.2.29.Servicios en la nube: El servicio en la nube permite el acceso a recursos y aplicaciones a través de Internet, eliminando la necesidad de infraestructura local. Este modelo ofrece escalabilidad, flexibilidad y eficiencia en costos para las empresas (Stallings, 2014).

2.3.Marco Normativo
Este marco proporciona un enfoque integral que busca mejorar la seguridad y la eficiencia de las infraestructuras tecnológicas, asegurando que se cumplan las normativas y se adopten mejores prácticas.
2.3.1.ISO/IEC 27001: Este estándar internacional establece los requisitos para un Sistema de Gestión de Seguridad de la Información (SGSI). Es fundamental para las organizaciones que buscan proteger su información y cumplir con regulaciones legales. En la industria automotriz, su aplicación ayuda a salvaguardar datos sensibles relacionados con la producción, distribución y servicios al cliente. La adopción de este estándar no solo mejora la seguridad, sino que también fortalece la confianza de los consumidores y socios comerciales (Valencia Duque, 2021).
2.3.2.Ley estatutaria 1581 de 2012: Esta ley regula la protección de datos personales en Colombia y es crucial para garantizar la privacidad y los derechos de los usuarios. Establece principios como el respeto a la intimidad y la protección de la información, obligando a las empresas a implementar medidas adecuadas para salvaguardar los datos de sus clientes. La conformidad con esta ley no solo evita sanciones, sino que también promueve una cultura de transparencia y responsabilidad en el manejo de la información personal (Ley 1581 de 2012 - Gestor Normativo, 2012).
2.3.3.RFCs: Los RFCs son documentos técnicos que establecen los estándares y protocolos utilizados en Internet, como TCP/IP. Son esenciales para la comunicación efectiva en redes, ya que definen cómo se deben transmitir los datos, garantizando interoperabilidad y estabilidad. La implementación de estos protocolos permite a las organizaciones asegurar que sus redes funcionen de manera eficiente y se mantengan actualizadas con las mejores prácticas de la industria (About RFCs, s/f).


2.4.Marco Tecnológico
Este marco está compuesto por una serie de estándares y protocolos que forman la base de la infraestructura de red. Estos son vitales para garantizar el funcionamiento eficiente y seguro de las redes locales y de área amplia.
2.4.1.IEEE 802.3: Este estándar define los protocolos para redes Ethernet, que son la columna vertebral de la mayoría de las redes locales. Permite la comunicación eficiente de datos a alta velocidad y es ampliamente utilizado en entornos empresariales. La especificación incluye aspectos técnicos como la topología de red, el cableado y las interfaces físicas, asegurando que los dispositivos puedan comunicarse de manera efectiva (Law, 2010).
2.4.2.IEEE 802.11: Este estándar especifica los protocolos para redes inalámbricas Wi-Fi, facilitando la conectividad sin cables en entornos domésticos y empresariales. Su implementación permite una mayor movilidad y flexibilidad, lo que es esencial en el mundo actual donde la conectividad constante es fundamental para la productividad (Kraemer, 2011).
2.4.3.IEEE 802.1Q: Este estándar define el protocolo VLAN (Virtual Local Área Network), que permite segmentar una red física en múltiples redes lógicas. Esta segmentación mejora la eficiencia y la seguridad al permitir un mejor control del tráfico de red, así como la separación de diferentes grupos de usuarios o aplicaciones dentro de la misma infraestructura (Farkas et al., 2013).
2.4.4.ISO/IEC 11801: Es una norma internacional que especifica sistemas de cableado estructurado de propósito general para telecomunicaciones, adecuados para una amplia gama de aplicaciones como telefonía analógica, ISDN, estándares de comunicación de datos, sistemas de control de edificios y automatización industrial. Esta norma abarca tanto el cableado de cobre balanceado como el de fibra óptica y fue diseñada para su implementación en entornos comerciales, que pueden consistir en uno o varios edificios dentro de un campus. (ISO, 2017)
2.4.5.Routers
2.4.5.1.Cisco ISR 4000 Series: La serie ISR 4000 ofrece enrutamiento de alto rendimiento y seguridad avanzada. Es ideal para empresas que requieren una solución robusta para el tráfico de datos, voz y vídeo. Soporta múltiples interfaces, VPNs, y QoS, además de ser escalable para adaptarse a diferentes tamaños de red. Comúnmente usado en redes empresariales y sucursales, ofreciendo conectividad segura y eficiente (Cisco, 2024a).
2.4.5.2.MikroTik RouterBOARD RB3011: Un router económico con un alto rendimiento, que incluye 10 puertos Gigabit Ethernet y soporte para enrutamiento y firewall avanzado. Es fácil de configurar y gestionar a través de RouterOS, ideal para pequeñas y medianas empresas. También es adecuado para redes de oficina o como solución de red para proveedores de servicios de Internet (ISP) (MikroTik, 2024).
2.4.5.3.TP-Link Archer AX6000: Un router de doble banda con tecnología Wi-Fi 6, ideal para hogares y pequeñas oficinas que requieren alta velocidad y conectividad simultánea. Ofrece un rendimiento de hasta 6000 Mbps y es compatible con múltiples dispositivos conectados al mismo tiempo. Es ideal para streaming de alta definición, juegos en línea y uso intensivo de internet (TP-Link, 2024).
2.4.5.4.RB1100AHx2: Es un router empresarial de alto rendimiento diseñado para aplicaciones de red intensivas en tráfico, instalado en un chasis 1U para montaje en rack. Equipado con un procesador dual core de 1066 MHz (P202ASSE2KFB) y 2 GB de RAM tipo SODIMM, este equipo ofrece una capacidad de procesamiento que alcanza hasta un millón de paquetes por segundo, lo cual lo hace ideal para entornos de misión crítica. Su arquitectura PPC y sistema operativo RouterOS con licencia nivel 6 permiten configuraciones avanzadas de ruteo, firewall y VPN (MikroTik, 2025).
2.4.5.5.Router Reyee RG-EG209GS: es una solución de conectividad integral orientada a entornos domésticos y profesionales que requieren alto rendimiento, administración remota y seguridad avanzada. Este dispositivo incorpora nueve puertos Ethernet Gigabit, permitiendo la conexión simultánea de múltiples dispositivos con alta velocidad y baja latencia. Destaca por su capacidad de balanceo de carga, lo que optimiza el uso de múltiples conexiones WAN, mejorando la estabilidad y disponibilidad del servicio de internet (Macrotics, 2025).
2.4.6.Switches
2.4.6.1.Cisco Catalyst 2960-X Series: Switches de acceso que ofrecen funciones avanzadas de seguridad, escalabilidad y gestión de red. Este soporta Power over Ethernet (PoE) y tiene una variedad de puertos para diferentes configuraciones de red. Igualmente es ideal para entornos empresariales donde se requiere una gestión centralizada y funciones de seguridad robustas (Cisco, 2024b).
2.4.6.2.Netgear GS724T: Un switch de 24 puertos Gigabit Ethernet que ofrece capacidades de gestión avanzadas y soporte para VLANs. Ofrece opciones de configuración flexibles y calidad de servicio (QoS) para priorizar el tráfico. Comúnmente utilizado en redes de pequeñas y medianas empresas para mejorar la conectividad y la gestión de tráfico. (Netgear, 2024)
2.4.6.3.Hewlett Packard Enterprise (HPE) Aruba 2530 Series: Switches de acceso que proporcionan una gestión simple y escalabilidad en redes empresariales.  Incluye características de seguridad, gestión de tráfico y Power over Ethernet (PoE).  Ideal para implementar en entornos de oficina donde se necesita una red confiable y de fácil gestión. (HPE, 2024)
2.4.6.4.TL-SG2428P Switch Smart Gigabit JetStream de 24 puertos PoE+ y 4 ranuras SFP: Un dispositivo de red gestionable diseñado para aplicaciones empresariales que requieren alto rendimiento, seguridad robusta y administración centralizada. Incorpora 24 puertos PoE+ Gigabit compatibles con los estándares IEEE 802.3af/at, ofreciendo una potencia total de hasta 250W, ideal para alimentar puntos de acceso, cámaras IP y teléfonos VoIP. Además, incluye 4 ranuras SFP Gigabit, permitiendo conexiones troncales de alta velocidad. (TP-Link, 2025)
2.4.7.GNS3 (Graphical Network Simulator-3): Es una plataforma de simulación de redes de código abierto que permite diseñar, probar y depurar redes complejas sin necesidad de hardware físico. Al admitir múltiples entornos de proveedores, imágenes de dispositivos virtuales y una amplia gama de hipervisores, GNS3 es ideal para la emulación de redes a gran escala, brindando flexibilidad y control a los usuarios. Aunque requiere que los usuarios suministren sus propias imágenes de Cisco, GNS3 se destaca por su comunidad activa y su compatibilidad con diversas tecnologías y plataformas, tanto de manera local como en la nube. (GNS3 Technologies, 2024)
2.4.8.Cisco Packet Tracer: Es una herramienta de simulación de redes desarrollada por Cisco que permite a los usuarios modelar redes complejas y probar su funcionamiento en un entorno virtual. Es ampliamente utilizado en el ámbito educativo y por profesionales de redes para diseñar, simular y analizar configuraciones de red de forma interactiva, brindando una experiencia práctica sin necesidad de equipos físicos. (Cisco, 2024c)
2.4.9.NetSim (Boson): Es un simulador de redes diseñado específicamente para ayudar a los estudiantes a prepararse para certificaciones como CCNA y CCNP. Este software proporciona entornos de laboratorio preconfigurados que permiten a los usuarios practicar configuraciones de red y resolución de problemas en un ambiente controlado. (Boson, 2024)
2.4.10.EDRAW: Edraw se presenta como una solución de diagramación multifuncional que facilita la creación de diagramas de flujo, mapas mentales y diseños de redes, con un enfoque en la precisión y la facilidad de uso. Sus plantillas y herramientas están diseñadas para ofrecer una experiencia visual intuitiva para los usuarios de diversas industrias, incluida la planificación de redes. (EdrawSoft, 2024)
2.4.11.Visio: Es una herramienta de diagramación que permite a los usuarios crear representaciones visuales detalladas de procesos y sistemas. Aunque no está exclusivamente enfocada en redes, Visio es utilizada frecuentemente para documentar topologías de red y diagramas de flujo. Su amplia variedad de plantillas y formas permite a los profesionales de TI diseñar diagramas precisos y claros, facilitando la planificación y presentación de infraestructuras complejas. (Microsoft, 2024)
2.4.12.Formulario de Google: Es una herramienta gratuita de Google que permite crear encuestas, cuestionarios y formularios de registro en línea. Los usuarios pueden personalizar sus formularios con diferentes tipos de preguntas, como opción múltiple, casillas de verificación, y preguntas de texto. La información recolectada se almacena automáticamente en Google Sheets, facilitando su análisis. (Google LLC, 2024)



3.Metodología
3.1.Tipo de Investigación
Para el proyecto de diseño de la infraestructura de red en Central Motor, se adoptó un enfoque de investigación cuantitativa, basado en una metodología descriptiva. Esta elección permitió medir de manera precisa y objetiva tanto el rendimiento como la seguridad de la red existente, utilizando para ello datos numéricos obtenidos a través de herramientas de monitoreo especializadas y análisis estadístico. A lo largo del proceso, se llevó a cabo un levantamiento detallado de todos los componentes de la infraestructura, identificando los dispositivos activos como switches, routers, puntos de acceso, firewalls y servidores, así como sus configuraciones y roles dentro de la red.
La observación sistemática del comportamiento de la red permitió caracterizar su funcionamiento bajo condiciones normales de operación, sin necesidad de intervenir en el sistema. Se recolectaron métricas esenciales como la latencia promedio, el uso del ancho de banda, la tasa de errores por interfaz, la disponibilidad del servicio y las medidas de seguridad implementadas. Esta información fue fundamental para elaborar un diagnóstico completo que evidenciara no solo el estado actual de la red, sino también sus limitaciones y potenciales áreas de mejora.
Los datos recopilados revelaron patrones de tráfico en horarios críticos, identificaron posibles cuellos de botella y permitieron evaluar la eficiencia del direccionamiento y la segmentación del tráfico. Asimismo, se evaluó el nivel de cumplimiento de las políticas de seguridad y se verificaron las configuraciones aplicadas en los distintos dispositivos. El análisis permitió generar un conjunto de recomendaciones técnicas orientadas a optimizar el rendimiento, aumentar la capacidad de respuesta del sistema y fortalecer la seguridad de la red
Todos los hallazgos fueron respaldados con documentación técnica, incluyendo diagramas actualizados de la red, informes generados por las herramientas utilizadas, capturas de configuración y representaciones gráficas de los principales indicadores. De esta manera, se garantizó que la investigación no solo respondiera a un enfoque metodológico riguroso, sino que además ofreciera una base sólida para futuras decisiones de mejora y expansión de la infraestructura tecnológica de la empresa.

3.2.Metodología PPDIOO
La metodología empleada para el diseño de la infraestructura de red en Central Motor se fundamentó en el enfoque PPDIOO de Cisco, un marco integral que permitió estructurar el proceso de manera eficaz y garantizar la fiabilidad de la red empresarial. Este enfoque, dividido en seis fases clave (Planificación, Preparación, Diseño, Despliegue, Operación y Optimización) para este proyecto.

3.2.1.Planeación
Durante la fase de Planeación, se llevó a cabo un análisis detallado del entorno empresarial en el cual se implementaría la nueva infraestructura de red. Esta etapa resultó crucial para comprender la misión y visión de Central Motor S.A.S., permitiendo alinear los objetivos tecnológicos del proyecto con las metas operativas y comerciales de la empresa. A través de este alineamiento estratégico, se definieron los requerimientos clave para priorizar la eficiencia, la seguridad y la escalabilidad de la red, factores esenciales para mantener la competitividad dentro del sector automotriz.
En paralelo, se realizó la recolección de datos sobre la infraestructura actual. Este proceso incluyó el levantamiento de información técnica sobre los dispositivos de red, cableado estructurado y la topología física y lógica de la red existente.
Asimismo, se desarrollaron entrevistas con personal clave con el fin de identificar problemas concretos relacionados con la conectividad, velocidad, caídas del sistema o fallos de seguridad. Para estructurar este proceso, se diseñaron formularios digitales que facilitaron la organización y el análisis de las respuestas obtenidas.
Posteriormente, se procedió con la revisión de la documentación técnica existente, incluyendo diagramas de red, manuales de configuración y reportes anteriores. Esta etapa permitió establecer una línea base del estado actual de la infraestructura y su modo de administración.
En cuanto a la evaluación de riesgos y vulnerabilidades, se aplicaron herramientas especializadas para identificar fallos potenciales en la red, verificar los protocolos utilizados y determinar el nivel de exposición ante amenazas internas y externas. Esto proporcionó una visión clara del estado de la seguridad y permitió priorizar medidas correctivas.
Finalmente, se efectuó un análisis exhaustivo de la topología de red y del equipamiento utilizado. Para esta tarea se emplearon herramientas de simulación y diseño de red que facilitaron la creación de un diagrama actualizado y preciso. Este análisis permitió detectar cuellos de botella, configuraciones obsoletas o puntos únicos de fallo.
Los entregables generados como resultado de esta metodología incluyeron:
3.2.1.1.Evaluación de la Infraestructuras Existente.
Recepción
El área evaluada cuenta con un total de 8 empleados, lo que influye directamente en la demanda de ancho de banda y en la estabilidad de la red. Con el objetivo de evaluar el desempeño de la red de datos, se realizó una prueba de velocidad utilizando la plataforma Fast.com. La medición se llevó a cabo desde un punto de red, empleando tanto una conexión cableada mediante Ethernet como una conexión inalámbrica (Wi-Fi), con el fin de analizar el rendimiento de cada medio de transmisión.
Para la conexión cableada, se utilizó un cable de categoría 5 (Cat 5) con conectores RJ45, siguiendo la norma TIA/EIA-568B para la correcta distribución de los pares trenzados. Este cableado estuvo dispuesto a través de ductos internos que canalizan las conexiones hasta el punto de acceso correspondiente, asegurando un entorno ordenado y protegido contra interferencias externas.
Resultados Ethernet:
Velocidad de descarga: 370 Mbps
Velocidad de subida: 160 Mbps
Latencia sin carga: 11 ms
Latencia con carga: 11 ms
Ilustración 15
Test de velocidad Ethernet: Área de Recepción

Las pruebas realizadas sobre la conexión Ethernet reflejan un desempeño óptimo en términos de velocidad, latencia y estabilidad. La velocidad de descarga alcanzó los 370 Mbps, lo que garantiza una transferencia de datos eficiente y sin interrupciones para aplicaciones de alto consumo de ancho de banda. La velocidad de subida de 160 Mbps permite la carga rápida de archivos, la sincronización en la nube y la transmisión en vivo sin degradación en el servicio. La latencia medida, tanto sin carga como bajo carga, se mantuvo estable en 11 ms, lo que indica una red con una infraestructura adecuada, libre de congestión y con un tiempo de respuesta ideal para aplicaciones críticas como gaming en línea, VoIP y videoconferencias. Estos resultados demuestran una conexión con un alto nivel de fiabilidad, sin signos de interferencias o pérdidas de rendimiento, lo que hace de Ethernet la opción más eficiente para entornos que requieren estabilidad y velocidad constante.
Resultados Wi-Fi:
Velocidad de descarga: 210 Mbps
Velocidad de subida: 110 Mbps
Latencia sin carga: 14 ms
Latencia con carga: 126 ms
Ilustración 16
Test de velocidad Wi-Fi: Área de Recepción

Por otro lado, la prueba realizada sobre la conexión Wi-Fi evidencia una reducción en el rendimiento, aunque dentro de valores aceptables para este tipo de tecnología. La velocidad de descarga alcanzó los 210 Mbps, suficiente para la mayoría de las actividades cotidianas, aunque por debajo de lo obtenido mediante cableado, lo que sugiere la posible presencia de interferencias, congestión en la red inalámbrica o limitaciones del hardware del dispositivo. La velocidad de subida se situó en 110 Mbps, permitiendo una carga de datos eficiente, pero con un margen de diferencia respecto a la conexión cableada que podría afectar tareas más exigentes como el trabajo remoto con múltiples transferencias simultáneas. La latencia sin carga se registró en 14 ms, lo que representa un leve aumento en comparación con Ethernet, pero dentro de parámetros manejables. Sin embargo, el mayor inconveniente se presentó en la latencia bajo carga, que ascendió a 126 ms, una variación considerable que podría impactar negativamente en aplicaciones que dependen de tiempos de respuesta bajos y constantes. Este comportamiento sugiere posibles problemas de saturación de la red Wi-Fi, interferencias en la señal o limitaciones del equipo de transmisión, lo que puede traducirse en fluctuaciones en el desempeño de la conexión.
Administración
El área analizada está conformada por un equipo de 21 empleados, lo que impacta directamente en el consumo de ancho de banda y en la estabilidad de la red. Con el propósito de evaluar el rendimiento de la infraestructura de conectividad, se llevó a cabo una prueba de velocidad utilizando la plataforma Fast.com. La medición se realizó desde un punto de acceso de red, utilizando tanto una conexión cableada a través de Ethernet como una conexión inalámbrica (Wi-Fi), permitiendo así comparar el comportamiento de ambos medios de transmisión.
Para la conexión mediante cable, se empleó un cable de categoría 5 (Cat 5) con conectores RJ45, cumpliendo con la norma TIA/EIA-568B para la correcta disposición de los pares trenzados. Este tendido se encuentra instalado a través de ductos estructurados que conducen las conexiones hasta los puntos de acceso designados, garantizando un entorno seguro y libre de interferencias que puedan afectar la calidad de la señal.
Resultados Ethernet:
Velocidad de descarga: 510 Mbps
Velocidad de subida: No registrada (posible bloqueo de tráfico en el test)
Latencia sin carga: 12 ms
Latencia con carga: 13 ms
Estos valores demuestran un excelente nivel de rendimiento y estabilidad en la conexión cableada, siendo significativamente superiores a los obtenidos mediante Wi-Fi. La latencia mínima y la alta velocidad de descarga reflejan que el backbone de red se encuentra en condiciones óptimas para soportar servicios críticos y tráfico intenso.
Ilustración 17
Test de velocidad Ethernet: Área de Administración

Resultados Wi-Fi:
●Velocidad de descarga: 44 Mbps
●Velocidad de subida: 50 Mbps
●Latencia sin carga: 17 ms
●Latencia con carga: 352 ms
A pesar de que la velocidad general es funcional para tareas cotidianas, la latencia con carga mostró un valor significativamente alto (352 ms), lo que puede generar retardos, eco o pérdida de calidad en servicios críticos como la telefonía IP. Esta diferencia se atribuye a factores como interferencias, saturación del espectro inalámbrico o distancia al punto de acceso.





Ilustración 18
Test de velocidad Wi-Fi: Área de Administración

Alistamiento
El área evaluada cuenta con 3 colaboradores, lo que incide directamente en la demanda de ancho de banda y en la estabilidad de la red. Para analizar el desempeño de la infraestructura de conectividad, se llevó a cabo una prueba de velocidad a través de la plataforma Fast.com. La medición se efectuó desde un punto de red, utilizando tanto una conexión alámbrica mediante Ethernet como una conexión inalámbrica (Wi-Fi), con el objetivo de comparar el rendimiento de ambas tecnologías.
En la conexión por cable, se utilizó un cable de categoría 5 (Cat 5) con conectores RJ45, siguiendo el estándar TIA/EIA-568B para la correcta distribución de los pares trenzados. Este sistema de cableado está organizado dentro de ductos estructurados que conducen las conexiones hasta los puntos de red correspondientes, asegurando una transmisión estable y minimizando posibles interferencias externas.
Resultados Ethernet:
Velocidad de descarga: 93 Mbps
Velocidad de subida: 80 Mbps
Latencia sin carga: 12 ms
Latencia con carga: 60 ms
Ilustración 19
Test de velocidad Ethernet: Área de Alistamiento

Estos valores reflejan un rendimiento estable y adecuado, dentro de los márgenes esperados para una red basada en cableado Categoría 5. La velocidad de descarga y carga es suficiente para operaciones empresariales comunes, incluyendo navegación, transferencias de archivos, uso de plataformas colaborativas y servicios en la nube. No obstante, el aumento moderado en la latencia bajo carga podría generar leves retrasos en aplicaciones sensibles si se presenta congestión en horarios pico.
Por otro lado, se efectuó una prueba de velocidad utilizando una conexión inalámbrica (Wi-Fi) desde un punto de red con buena recepción de señal, con el fin de evaluar el comportamiento de la red inalámbrica dentro de las instalaciones de Central Motor S.A.S. La prueba se realizó a través de la herramienta Fast.com, conectando un equipo cliente bajo condiciones normales de uso.
Resultados Wi-Fi:
Velocidad de descarga: 69 Mbps
Velocidad de subida: 400 Mbps
Latencia sin carga: 14 ms
Latencia con carga: 64 ms
Estos valores reflejan un buen desempeño de la red inalámbrica, especialmente en lo relacionado con la velocidad de subida, la cual fue superior a la media esperada, posiblemente debido al diseño de la red o a condiciones técnicas del proveedor. La latencia se mantuvo en rangos aceptables para la mayoría de los servicios empresariales, aunque el incremento bajo carga sugiere la necesidad de monitorear la saturación del canal Wi-Fi en horarios de alta demanda.
Ilustración 20
Test de velocidad Wi-Fi: Área de Alistamiento

Colisión
El departamento analizado cuenta con 6 empleados, lo que repercute en la utilización del ancho de banda y en la estabilidad de la red. Para evaluar el desempeño de la infraestructura de conectividad, se realizó una prueba de velocidad utilizando la plataforma Fast.com. La medición se llevó a cabo desde un punto de red, empleando tanto una conexión Ethernet por cable como una conexión inalámbrica (Wi-Fi), con el propósito de examinar el rendimiento de cada medio de transmisión.
Para la conexión cableada, se utilizó un cable de categoría 5 (Cat 5) con conectores RJ45, cumpliendo con la norma TIA/EIA-568B para la distribución adecuada de los pares trenzados. El cableado está instalado dentro de ductos de canalización, los cuales dirigen las conexiones hacia los puntos de red designados, asegurando un entorno ordenado y con protección contra interferencias electromagnéticas.
Resultados Ethernet:
Velocidad de descarga: 91 Mbps
Velocidad de subida: 87 Mbps
Latencia sin carga: 12 ms
Latencia con carga: 60 ms
Los datos reflejan un rendimiento estable y balanceado, con velocidades de descarga y subida muy próximas entre sí. La baja latencia, tanto en condiciones normales como bajo carga, indica que la red cableada cuenta con una infraestructura sólida y adecuada para soportar los servicios empresariales requeridos. Este resultado confirma la fiabilidad de la red física en puntos adicionales de acceso, validando su eficiencia para aplicaciones críticas de uso diario.





Ilustración 21
Test de velocidad Ethernet: Área de Colisión

Se realizó una medición de velocidad a través de conexión inalámbrica (Wi-Fi) desde una zona con menor intensidad de señal, con el fin de identificar posibles puntos críticos dentro de la infraestructura de red inalámbrica. La prueba fue ejecutada mediante Fast.com, bajo condiciones normales de operación.
Resultados Wi-Fi:
Velocidad de descarga: 7.7 Mbps
Velocidad de subida: 5.6 Mbps
Latencia sin carga: 15 ms
Latencia con carga: 291 ms
Estos valores evidencian un desempeño deficiente, tanto en velocidad como en latencia bajo carga. La significativa caída en la capacidad de subida y descarga, así como el aumento marcado en la latencia, indican problemas de cobertura, congestión del canal o interferencias electromagnéticas en la zona evaluada.
Este comportamiento puede afectar negativamente la experiencia del usuario y comprometer la estabilidad de servicios que dependen de una conexión en tiempo real.
Ilustración 22
Test de velocidad Wi-Fi: Área de Colisión

Posventa Ford
La sección evaluada está conformada por 30 empleados, cuya actividad depende del acceso estable a la red, lo que influye en el consumo de ancho de banda y en la calidad de la conexión. Para analizar el desempeño de la infraestructura de conectividad, se realizó una prueba de velocidad utilizando la plataforma Fast.com. La medición se efectuó desde un punto de red, utilizando tanto una conexión alámbrica a través de Ethernet como una conexión inalámbrica (Wi-Fi), con el objetivo de examinar el comportamiento de cada medio de transmisión.
En el caso de la conexión cableada, se utilizó un cable de categoría 5 (Cat 5) con conectores RJ45, cumpliendo con la norma TIA/EIA-568B para una correcta distribución de los pares trenzados. El cableado está organizado dentro de ductos de canalización, asegurando que las conexiones lleguen de manera eficiente a los puntos de red designados, minimizando interferencias y optimizando la estabilidad del enlace.
Resultados Ethernet:
Velocidad de descarga: 390 Mbps
Velocidad de subida: 170 Mbps
Latencia sin carga: 12 ms
Latencia con carga: 13 ms
Estos valores representan un desempeño excelente, confirmando que la red cableada de Central Motor es capaz de soportar altos niveles de tráfico con mínima latencia, incluso bajo carga. Esto valida la calidad del backbone y la infraestructura física, siendo adecuada para servicios críticos, tráfico empresarial intensivo y escenarios de alta demanda.
Ilustración 23
Test de velocidad Ethernet: Área de Postventa Ford

También se llevó a cabo una medición desde un punto de acceso inalámbrico en condiciones desfavorables, con el objetivo de evaluar el comportamiento de la red Wi-Fi en zonas con baja cobertura o posible interferencia:
Resultados Wi-Fi:
Velocidad de descarga: 6.6 Mbps
Velocidad de subida: 17 Mbps
Latencia sin carga: 17 ms
Latencia con carga: 838 ms
Este resultado evidencia un desempeño altamente deficiente en la red inalámbrica, con velocidades muy por debajo de los valores esperados y una latencia extrema al estar en carga. Dichas condiciones pueden provocar interrupciones, lentitud y pérdida de servicio, especialmente en aplicaciones sensibles como plataformas en línea, herramientas colaborativas y servicios en tiempo real.
Ilustración 24
Test de velocidad Wi-Fi: Área de Postventa Ford

Vitrina
El área de operaciones evaluada está conformada por 46 empleados, cuyo trabajo requiere un acceso estable a la red para garantizar un desempeño eficiente. Para analizar la calidad de la conectividad, se llevó a cabo una prueba de velocidad mediante la plataforma Fast.com. La medición se realizó desde un punto de red, utilizando tanto una conexión cableada por Ethernet como una conexión inalámbrica (Wi-Fi), con el propósito de examinar el rendimiento de cada tecnología.
Para la conexión por cable, se empleó un cable de categoría 5 (Cat 5) con conectores RJ45, siguiendo el estándar TIA/EIA-568B para la correcta disposición de los pares trenzados. La infraestructura de cableado está organizada dentro de ductos estructurados, asegurando una distribución eficiente de las conexiones y reduciendo la posibilidad de interferencias que puedan afectar la estabilidad de la red.
Resultados Ethernet:
Velocidad de descarga: 360 Mbps
Velocidad de subida: 170 Mbps
Latencia sin carga: 10 ms
Latencia con carga: 12 ms
Este resultado demuestra un nivel de rendimiento excelente, confirmando que la infraestructura de red cableada de Central Motor se encuentra en óptimas condiciones para soportar aplicaciones de alta demanda, servicios de tiempo real y operación continua. La estabilidad de la latencia incluso bajo carga ratifica la eficiencia del backbone y la baja congestión del canal.
Ilustración 25
Test de velocidad Ethernet: Área de Vitrina

Resultados Wi-Fi:
Velocidad de descarga: 130 Mbps
Velocidad de subida: 69 Mbps
Latencia sin carga: 17 ms
Latencia con carga: 170 ms
Si bien la velocidad de descarga es aceptable, el aumento de latencia bajo carga (170 ms) evidencia limitaciones de desempeño en la red inalámbrica, lo que puede generar afectaciones perceptibles en servicios que dependen de una respuesta en tiempo real. Este comportamiento podría atribuirse a congestión del canal, interferencias o limitaciones del punto de acceso.
Ilustración 26
Test de velocidad Wi-Fi: Área de Vitrina


3.2.1.2.Aplicativos.
DMS
Este software es utilizado para gestionar procesos clave como contabilidad, facturación de vehículos, facturación de taller y colisión, administración de órdenes de trabajo, gestión de roles, generación de informes gerenciales y ejecución de procesos de auditoría.
Se trata de una aplicación instalada localmente en los equipos asignados, con una distribución aproximada de 80 licencias activas. En el momento del análisis, no fue posible encontrar información explícita sobre el consumo específico de ancho de banda en la documentación oficial del aplicativo. No obstante, se realizó una prueba utilizando el Administrador de tareas de Windows, a través de la cual se evidenció un consumo estimado de 48.0 Kbps en envío y 88.0 Kbps en recepción. En cuanto a los requerimientos técnicos mínimos del sistema, se recomendó disponer de al menos 5 GB de espacio libre en disco y 4 GB de memoria RAM, con el fin de asegurar un desempeño óptimo de la aplicación.
Ilustración 27
Evidencia del aplicativo DMS

Ilustración 28
Evidencia consumo de datos aplicativo DMS

Cen Financiero
Este aplicativo se utiliza para la emisión y recepción de facturas electrónicas, permitiendo registrar eventos asociados a las facturas recibidas y mantener un control eficiente sobre las facturas emitidas.
Se trata de una solución en línea con un total de 10 licencias activas. Funciona a través de un navegador web y requiere conexión a internet para su operación. Actualmente, no se dispone de datos precisos sobre el consumo de ancho de banda asociado a su funcionamiento. Sin embargo, según el análisis de rendimiento de red realizado, se ha obtenido un consumo de 280 kbps para el envío de datos y 3.1 Mbps para la recepción.
Ilustración 29
Evidencia Cen Financiero

Ilustración 30
Evidencia consumo de red Cen Financiero

Dealer Tools
Es un aplicativo web desarrollado internamente por la empresa. Su principal funcionalidad es el control de los procesos relacionados con los vehículos que ingresan a taller y colisión, permitiendo el seguimiento detallado del estado de cada unidad.
Adicionalmente, el sistema permite la gestión de usuarios, administración de activos, control de aspectos contables y generación de informes operativos y gerenciales.
Al tratarse de una solución web, solo requiere acceso a internet y un navegador compatible para su utilización. No se cuenta con información específica sobre el consumo de ancho de banda, pero al realizar la revisión de rendimiento de red cuenta con un envío de datos de 24.0 Kbps y recepción de datos 104 Kbps. Debido a que es un desarrollo propio, no presenta restricciones en cuanto al número de licencias; sin embargo, actualmente es utilizado activamente por aproximadamente 45 empleados.
Ilustración 31
Evidencia Dealer Tools

Ilustración 32
Evidencia consumo de red Dealer Tools

3CX Phone
Se trata de un aplicativo instalado localmente en los equipos de cómputo, el cual requiere un mínimo de 10 GB de almacenamiento disponible y 4 GB de memoria RAM para garantizar un funcionamiento adecuado. Actualmente, este software es utilizado por tres usuarios.
Su funcionalidad principal es permitir la realización y recepción de llamadas. En cuanto al consumo de ancho de banda, se detalla lo siguiente:
RTP: 4.8 kbps
UDP: 3.2 kbps
IP: 8.0 kbps
Ethernet (sin QoS): 15.2 kbps
El overhead total estimado es de 31.2 kbps por llamada.
Ilustración 33
Evidencia 3CX

El análisis realizado sobre la infraestructura de red de Central Motor, mediante pruebas de rendimiento en distintas áreas funcionales y la evaluación de aplicativos operativos, permitió establecer un panorama claro del estado actual de la red, su eficiencia operativa y los retos a nivel de conectividad.
En primer lugar, las pruebas de velocidad realizadas mediante Fast.com, tanto en conexiones cableadas como inalámbricas, evidenciaron una tendencia general positiva en la infraestructura Ethernet, que mostró niveles estables de latencia y velocidades consistentes, incluso bajo carga. En casi todas las áreas evaluadas, el cableado de categoría 5 (Cat 5), a pesar de ser una tecnología estándar antigua, demostró mantener una capacidad de transmisión adecuada para las necesidades actuales, con velocidades de descarga superiores a los 300 Mbps en departamentos de alta demanda como Vitrina y Posventa Ford. La latencia mínima en estos entornos sugiere un backbone robusto y bien configurado.
En contraste, la conectividad Wi-Fi presentó variabilidad significativa, con zonas de buen rendimiento (por ejemplo, Alistamiento o Administración) y otras con claras deficiencias (como Colisión y Posventa Ford), donde se detectaron latencias superiores a los 800 ms bajo carga y velocidades de descarga menores a 10 Mbps. Estos resultados reflejan una infraestructura inalámbrica no homogénea, con problemas posiblemente relacionados como saturación del espectro, distancia a los puntos de acceso, limitaciones de cobertura o interferencias, capacidad limitada de los APs existentes. Estos problemas afectan directamente la experiencia del usuario y podrían representar un riesgo para servicios sensibles como telefonía IP o videollamadas corporativas.
En cuanto al análisis de aplicativos, se identificó una coexistencia entre soluciones instaladas localmente (como DMS y 3CX Phone) y plataformas web en la nube (como Cen Financiero y Dealer Tools). Aunque no todos los aplicativos cuentan con mediciones exactas de su consumo de ancho de banda, se logró establecer un rango estimado de uso gracias a las pruebas realizadas. En el caso de Dealer Tools mostró una carga baja sobre la red, con consumos que no superan los 0.1 Mbps por usuario. En el Cen Financiero representa una carga media, con descargas de hasta 3.1 Mbps por usuario. En el aplicativo 3CX Phone, aunque con muy bajo consumo por llamada (~31.2 Kbps), requiere baja latencia y estabilidad, lo que refuerza la necesidad de priorizar su tráfico mediante QoS o VLANs dedicadas. 
La carga acumulada de los aplicativos en uso, considerando hasta 80 licencias de DMS y 45 usuarios simultáneos de Dealer Tools, hace evidente que la red debe ser escalable y contar con mecanismos de priorización y segmentación para evitar la degradación del servicio.
Además, se observó que en la mayoría de los casos no se cuenta con mediciones continuas del uso de red, lo que impide un diagnóstico dinámico.
3.2.1.3.Descripción Técnica del Estado de Dispositivos, Cableado y Servicios.
Durante la inspección física de la infraestructura de red en Central Motor S.A.S., se llevó a cabo una evaluación detallada del estado de los dispositivos activos, el cableado estructurado y los elementos de conectividad asociados a la distribución general de datos. Si bien se comprobó la operatividad funcional básica de los equipos, el estado físico y organizacional de la red presenta múltiples deficiencias que requieren atención inmediata desde el punto de vista técnico, estético y operativo.
El rack principal, que actúa como núcleo de distribución para las diferentes zonas de la organización, se encuentra en condiciones de evidente desorden. Se identificó una alta concentración de cables de red sin etiquetas visibles que permitan trazar su origen o destino, lo cual complica la gestión y dificulta cualquier intervención técnica planificada o correctiva. Esta falta de organización no solo representa un obstáculo para el mantenimiento, sino que también implica un riesgo potencial en caso de fallos, debido a la imposibilidad de identificar rápidamente los puntos críticos. En este entorno, además, los cables se encuentran dispuestos sin canaletas adecuadas, con múltiples conexiones que sobresalen del gabinete, afectando tanto la ventilación de los equipos como la seguridad mecánica de las conexiones.
Ilustración 34
Rack principal Central Motor

El cableado presente en la mayoría de los puntos evaluados corresponde a categoría 5e, una tecnología aún vigente para muchas aplicaciones de red empresarial, pero que, en este caso particular, presenta signos claros de desgaste. Se encontraron múltiples pestañas de conectores RJ45 deterioradas o directamente rotas, lo cual impide asegurar adecuadamente las conexiones en los puertos de switches o patch panels. Esta situación no solo compromete la integridad del enlace, sino que puede ocasionar desconexiones intermitentes difíciles de diagnosticar, afectando directamente la estabilidad de servicios críticos como la telefonía IP, aplicaciones en la nube y transmisión de datos en tiempo real.
A simple vista, el gabinete presenta un alto grado de desorganización en la disposición del cableado horizontal, sin gestión adecuada de canalización ni uso de organizadores verticales u horizontales.
En los gabinetes denominados Citroën, y Hyundai, se observan múltiples cables de red (principalmente tipo UTP categoría 5e) de diferentes colores (azul, rojo, blanco y negro) entrelazados y dispuestos de forma caótica, lo cual dificulta cualquier intervención técnica segura. Esta acumulación de cables sin orden representa un obstáculo para la ventilación de los equipos activos, propiciando condiciones térmicas desfavorables que pueden afectar su desempeño y reducir su vida útil.
Además, se evidenció que varios de los cables no se encuentran conectados a los puertos de la cascada de switches según la topología definida previamente. Esto no solo dificulta la trazabilidad de las conexiones, sino que también puede implicar la existencia de enlaces fantasmas o conexiones obsoletas que continúan ocupando espacio y generando confusión en tareas de mantenimiento.
Otro punto crítico es la falta de rotulación en ambos extremos de los cables, lo que imposibilita identificar de manera rápida y confiable a qué punto de red corresponde cada conexión. En un entorno de red empresarial, esta deficiencia impacta negativamente en la capacidad de respuesta ante incidentes o necesidades de expansión.
Por último, se observan algunos conectores con sus pestañas deterioradas, lo cual compromete la estabilidad de la conexión física al switch. Estas condiciones son especialmente graves en un entorno que requiere alta disponibilidad de red, como lo es una zona de trabajo vehicular con sistemas de inventario, facturación y gestión centralizados.
Ilustración 35
Gabinete Citroën

Ilustración 36
Gabinete Hyundai

En el área de repuestos, se observó un caso puntual que afecta de forma negativa la presentación y seguridad de la red: uno de los switches de distribución se encuentra ubicado fuera del gabinete de red, sin protección estructural, apoyado sobre una superficie inadecuada. Esta condición expone al equipo a riesgos eléctricos, mecánicos y ambientales, además de proyectar una imagen desorganizada en un área visible del entorno de trabajo.
Ilustración 37
Gabinete Repuestos

El gabinete de comunicaciones ubicado en el sótano presenta un estado de desorganización considerable en la disposición del cableado estructurado. Aunque se identifican intentos parciales de agrupar los cables por color, no se observa una correcta canalización ni un uso adecuado de organizadores de cables, lo que genera una acumulación caótica que compromete la ventilación, dificulta las tareas de mantenimiento y eleva el riesgo de desconexiones accidentales.
Se encuentran cables tipo UTP categoría 5e, principalmente de color rojo y azul, enredados y sin rotulación visible, lo que impide la identificación clara de cada punto de red y dificulta enormemente el rastreo de fallos. Esta situación es crítica en redes de tamaño medio o superior, ya que afecta la eficiencia operativa del soporte técnico y aumenta los tiempos de respuesta ante incidentes.
Ilustración 38
Gabinete Sótano

Ilustración 39
Gabinete Colisión

El gabinete identificado como “GA – Alistamiento”, que también da soporte al área de colisión, presenta una infraestructura comprometida por varios factores críticos de diseño, organización y mantenimiento.
A simple vista, se observa una acumulación excesiva de cableado UTP categoría 5e, con predominancia de cables de color azul y rojo. El cableado se encuentra enredado, sin sistema de canalización y sin ninguna clase de rotulación visible en los extremos. Esta condición dificulta no solo las tareas de mantenimiento correctivo y preventivo, sino también incrementa significativamente el riesgo de errores en reconexiones o pruebas de conectividad.
Además, el espacio físico del gabinete es reducido y no parece adecuado para dar soporte de manera simultánea a dos áreas de trabajo distintas (Alistamiento y Colisión), lo cual genera una sobrecarga tanto física como lógica de la infraestructura. Esta sobreutilización incrementa el calor interno del gabinete y reduce la vida útil de los equipos activos.
La condición predominante en todos los puntos revisados es un nivel elevado de desorganización en el cableado estructurado, lo cual afecta directamente la gestión operativa de la red. En varios casos se observan cables sin identificación, conectores deteriorados y ausencia de una estructura clara de jerarquía entre los dispositivos activos (como switches y patch panels).
Asimismo, se constata una ocupación excesiva del espacio físico disponible en los gabinetes, sobre todo en aquellos que atienden más de una zona de trabajo, lo cual compromete tanto la ventilación como la accesibilidad para tareas de mantenimiento. La acumulación de conexiones en puntos únicos sin una cascada debidamente documentada contribuye a una gestión deficiente de la red.
Por otro lado, la falta de rotulación y la coexistencia de elementos de diferentes funciones (como switches de repuesto operando fuera de gabinete) suponen un riesgo operativo importante, tanto en términos de continuidad del servicio como de seguridad física del entorno técnico.
3.2.1.4.Inventario con Versiones de Firmware y Antigüedad.
3.2.1.4.1.Equipos de Cómputo.
Como parte del proceso de diagnóstico de infraestructura tecnológica en Central Motor S.A.S., se llevó a cabo un análisis detallado del inventario de equipos de cómputo disponibles en las distintas áreas operativas de la empresa. Este levantamiento incluyó variables técnicas fundamentales como el tipo de dispositivo, el sistema operativo instalado, la marca, la capacidad de almacenamiento, la memoria RAM, el tipo de conexión de red y la fecha de adquisición, con el propósito de determinar el estado actual del parque tecnológico y orientar posibles estrategias de renovación, estandarización y mejora.
El análisis evidenció una infraestructura variada, pero con una clara orientación hacia la modernización, destacando una predominancia de equipos All-in-One (AIO) y portátiles, los cuales representan la mayor parte de los dispositivos en operación. Esta distribución sugiere una infraestructura que combina espacios fijos con áreas de movilidad, aunque también implica una mayor dependencia de las redes inalámbricas, lo que se vincula directamente con el rendimiento de la red Wi-Fi analizado en paralelo.
En cuanto a la capacidad técnica, se observó una alta proporción de equipos con 8 GB de memoria RAM, y una cantidad considerable de dispositivos con 16 GB, lo cual es adecuado para las necesidades operativas actuales. No obstante, también se identificó un número significativo de estaciones con 4 GB o menos, que ya no cumplen con los requerimientos mínimos para ejecutar múltiples tareas o utilizar herramientas colaborativas en la nube con eficiencia. Estos equipos representan un foco de atención prioritario dentro de cualquier plan de actualización tecnológica. En relación con el almacenamiento, más de la mitad de los equipos están equipados con unidades M.2, que ofrecen altas velocidades de lectura y escritura. Sin embargo, todavía se identificaron varios dispositivos que utilizan discos mecánicos (HDD) o unidades de estado sólido tradicionales (SATA SSD), los cuales ofrecen un desempeño notablemente inferior frente a tecnologías actuales.
Respecto a los sistemas operativos, el análisis reveló una fragmentación relevante. Si bien una parte importante del parque ya se encuentra operando con Windows 11, existen numerosos equipos que aún funcionan con Windows 8 y Windows 7, versiones que ya no cuentan con soporte oficial por parte de Microsoft. Esta situación representa un riesgo tanto a nivel de seguridad informática como de compatibilidad de software, y plantea la necesidad urgente de una estrategia de homologación y estandarización hacia versiones modernas. También se identificaron equipos con Windows 10 y un caso con sistema macOS, lo que confirma la diversidad del entorno tecnológico.
En relación con las marcas, Lenovo se posiciona como el proveedor predominante, lo cual es favorable desde la perspectiva de soporte, compatibilidad de controladores y mantenimiento. Le siguen Dell y HP, con menor participación, además de algunos equipos ensamblados y unidades de otras marcas como Acer y Apple. Esta relativa homogeneidad permite optimizar las políticas de soporte técnico y facilitar la estandarización de imágenes y configuraciones. En cuanto a modelos, se destacan las familias ThinkCentre y ThinkPad de Lenovo, así como los modelos Vostro de Dell, evidenciando que gran parte de las adquisiciones recientes han estado orientadas a líneas empresariales con buenas capacidades de procesamiento.
A partir de estos hallazgos, se puede concluir que la infraestructura computacional de Central Motor S.A.S. se encuentra en un proceso de transición positiva hacia la actualización y estandarización, pero que aún persisten elementos críticos que requieren atención. La presencia de equipos obsoletos o con características técnicas limitadas puede afectar directamente la productividad y la experiencia del usuario, especialmente en áreas que dependen de aplicaciones en la nube, telefonía IP o herramientas colaborativas. Asimismo, se recomienda fortalecer los procesos de planificación tecnológica, definiendo un ciclo de vida claro para los equipos de cómputo, con esquemas de renovación cada 3 a 5 años, así como el monitoreo activo del estado de hardware y software mediante herramientas especializadas. [Ver anexo hojas de computo, listado de equipos]
3.2.1.4.2.Equipos de Red.
Central Motor S.A.S. cuenta con una infraestructura de red y video seguridad sólida, distribuida estratégicamente en sus diferentes áreas operativas y comerciales. El inventario levantado evidencia una importante inversión en equipos de videovigilancia, puntos de acceso inalámbrico, conmutación de red, telefonía IP, y dispositivos de control de acceso, lo que garantiza una cobertura integral tanto en aspectos de seguridad física como de conectividad.
El parque de videovigilancia está conformado mayoritariamente por cámaras HIKVISION de tipo domo y cámaras IP con tecnología Turbo HD y Dual Light, con capacidad de visión nocturna y compatibilidad con protocolos Onvif. Estas cámaras están instaladas en ubicaciones clave como accesos principales, vitrinas, áreas de servicio, salas administrativas, zonas de colisión, talleres, pasillos y exteriores. La uniformidad en la marca y especificaciones facilita la centralización de la administración de video, y su conexión a sistemas DVR HIKVISION de 32 canales permite consolidar las grabaciones de múltiples áreas, asegurando respaldo y trazabilidad de eventos. La antigüedad promedio de estos dispositivos se remonta a adquisiciones realizadas entre 2015 y 2017, por lo que, aunque aún funcionales, deben ser evaluadas a corto plazo para actualización o migración a estándares más actuales como cámaras IP con analítica incorporada y resolución superior.
Adicionalmente, se identifican elementos críticos como el firewall Sophos XG 125 y el router Mikrotik RB1100AHX2, que desempeñan un papel fundamental en el control del tráfico de red, filtrado de contenido, segmentación de servicios y protección frente a amenazas externas. Estos dispositivos están ubicados en el núcleo del sistema y han sido actualizados recientemente, con adquisiciones registradas en 2023 y 2018 respectivamente. Su integración con la estructura de red general proporciona una barrera robusta de ciberseguridad, que resulta clave en un entorno donde convergen datos administrativos, transacciones electrónicas y acceso remoto.
En cuanto a la conectividad inalámbrica, se evidencia una amplia cobertura gracias a la instalación de múltiples puntos de acceso RG-AP840-L con tecnología Wi-Fi 6, distribuidos tanto en vitrinas como en áreas de talleres, administración y zonas de uso general. Esta arquitectura asegura velocidades de transmisión adecuadas y estabilidad de conexión para los usuarios móviles, dispositivos portátiles y aplicaciones corporativas en la nube. Los APs están instalados desde 2015, y aunque su tecnología es avanzada, se sugiere una revisión de firmware y monitoreo continuo del rendimiento debido al crecimiento en la densidad de dispositivos conectados.
El componente de telefonía IP también está bien desarrollado, con la implementación de más de 80 teléfonos FANVIL X3G, distribuidos en todas las áreas, desde asesores comerciales y personal administrativo hasta bodegas, talleres y servicios. Esta solución unificada permite la comunicación eficiente entre departamentos, reduce costos asociados a llamadas tradicionales y puede integrarse con plataformas de gestión de clientes y atención al usuario. A pesar de ser una infraestructura funcional, su antigüedad (adquisiciones del año 2015) sugiere que se encuentran en el límite de su vida útil técnica, por lo que podría considerarse una renovación paulatina para incluir dispositivos con mejor calidad de audio, pantallas a color y capacidades de integración con software moderno.
Finalmente, se destacan los elementos de control de acceso, como lectores biométricos HIKVISION para huellas dactilares, instalados en zonas estratégicas como recepción y sótano. Estos dispositivos, aunque datan del año 2012, aún proporcionan funcionalidades básicas de control de ingreso, pero carecen de características modernas como autenticación multifactor, conectividad remota o integración con sistemas de videovigilancia. Se recomienda considerar su reemplazo por soluciones actualizadas que permitan una gestión centralizada, compatible con plataformas móviles y con mejores estándares de seguridad.
En conjunto, la infraestructura de red y seguridad electrónica de Central Motor presenta una base tecnológica sólida y funcional, pero con una carga importante de dispositivos que ya superan los 8 años de operación.
3.2.1.5.Identificación de Limitaciones Operativas y Estructurales.
Durante el proceso de diagnóstico de la red de datos en Central Motor S.A.S., se identificaron una serie de condiciones que limitan tanto el funcionamiento operativo como la estructura física de la infraestructura tecnológica. Estas limitaciones se evidencian al analizar aspectos técnicos como el cableado, los dispositivos activos, los gabinetes de red, el rendimiento de las conexiones, el estado de los equipos informáticos y la gestión organizacional de la seguridad de la información.
A nivel operativo, una de las principales restricciones se encuentra en la organización del cableado estructurado. En múltiples gabinetes, especialmente en el rack principal, se observaron cables sin identificación, conexiones desordenadas y ausencia de canalización interna. Este desorden afecta la trazabilidad de los puntos de red, la detección de fallos y la posibilidad de realizar mantenimientos o ampliaciones sin riesgo. En algunos casos, se hallaron cables categoría 5e con conectores dañados, lo que representa una afectación directa en la estabilidad de las conexiones físicas. 
Desde el punto de vista estructural, se identificó que varios gabinetes no cuentan con una adecuada disposición interna ni ventilación suficiente, y algunos dispositivos están apilados o mezclados sin jerarquía técnica. Asimismo, se constató una limitación física del espacio disponible en gabinetes como el del sótano, en donde la accesibilidad para intervención técnica es reducida, comprometiendo incluso la seguridad del personal.
Las pruebas de velocidad realizadas en diversas áreas reflejan un rendimiento heterogéneo entre las conexiones cableadas y las inalámbricas. Si bien algunas conexiones Ethernet alcanzaron valores óptimos, en otros sectores los resultados fueron inferiores a lo esperado para enlaces de categoría Gigabit. En el caso de las conexiones Wi-Fi, se observaron latencias elevadas bajo carga y velocidades de descarga inconsistentes, lo que apunta a limitaciones tanto en la cobertura como en la configuración actual de los puntos de acceso.
En cuanto al estado de los equipos de cómputo, se cuenta con una diversidad de dispositivos, algunos recientemente adquiridos y otros en evidente estado de obsolescencia. Esto genera un ecosistema operativo dispar, en el que los tiempos de respuesta y capacidad de procesamiento varían considerablemente entre áreas, lo cual afecta directamente la experiencia del usuario y el flujo operativo de las actividades diarias. Asimismo, el análisis del inventario de equipos de red reveló una infraestructura que no está estandarizada en su totalidad, con modelos y configuraciones distintas distribuidas sin una segmentación clara por áreas de servicio o criticidad funcional.
3.2.1.6.Informe de Riesgos y Vulnerabilidades.
Como parte del diagnóstico de seguridad de la red de datos en Central Motor S.A.S., se diseñó y aplicó un cuestionario a través de la herramienta Google Forms, con el objetivo de recopilar información clave sobre el estado actual de la infraestructura de red y las prácticas relacionadas con seguridad de la información. Este cuestionario fue respondido directamente por el jefe del área de sistemas, quien proporcionó datos sobre aspectos técnicos, normativos, organizacionales y operativos de la red de la empresa.
En el análisis de la infraestructura tecnológica y de seguridad, se identificaron diversos aspectos clave relacionados con la criticidad de los activos, la actualización de la infraestructura, la redundancia de los sistemas y la existencia de planes de recuperación ante desastres. En relación con la estructura actual de la red de datos, se indicó que está organizada bajo una topología en estrella, lo que facilita la identificación de fallos y el aislamiento de dispositivos problemáticos sin afectar a toda la red. Sin embargo, esta configuración implica una alta dependencia del nodo central, lo que representa un riesgo en caso de fallo de este componente.
Al abordar la criticidad de los activos tecnológicos, se preguntó si existía una clasificación formal de estos, y la respuesta fue negativa. Aunque se asignaron niveles de criticidad a algunos activos, la ausencia de una categorización oficial dificulta la priorización de medidas de seguridad y estrategias de recuperación. Dentro de los activos más críticos identificados para la continuidad operativa se encuentran los servidores físicos, servidores virtuales, firewall y el sistema ERP. Sin embargo, no se mencionaron otros elementos como el almacenamiento NAS/SAN y las plataformas en la nube, lo que podría derivar en una falta de medidas de seguridad adecuadas para ellos y, en consecuencia, un mayor riesgo de interrupciones.
Sobre la conectividad de la empresa, se determinó que el ancho de banda contratado con el proveedor de servicios de Internet es de 600 Mbps, lo que resulta adecuado para el tamaño de la empresa y sus necesidades operativas. No obstante, no se evidenció la existencia de enlaces redundantes o secundarios, lo cual representa una debilidad en términos de continuidad operativa. A pesar de que la empresa cuenta con los servicios de TIGO UNE y MEDIA COMMERCE como proveedores de Internet, lo que permitiría configurar esquemas de redundancia o balanceo de carga, no se mencionó la implementación de estos mecanismos.
En cuanto a las medidas de seguridad implementadas, se indicó que los servidores físicos, servidores virtuales, firewall, sistema ERP y sistema de facturación se consideran activos críticos, mientras que los switches y routers tienen un nivel de criticidad alto y el almacenamiento NAS/SAN, los equipos de usuarios y las plataformas en la nube tienen una criticidad media. Se confirmó la existencia de firewall y VPN como controles de seguridad, lo que representa un punto positivo en la defensa perimetral y en el acceso remoto seguro. Sin embargo, no se mencionaron controles adicionales como sistemas de detección de intrusiones (IDS/IPS), segmentación de red o autenticación reforzada, lo que puede representar vulnerabilidades no controladas.
Otro hallazgo relevante es la ausencia de políticas documentadas para la configuración de dispositivos de red, actualizaciones de software y aplicación de parches de seguridad, lo que representa un riesgo importante, ya que sin estándares formales no se puede garantizar que las configuraciones se mantengan actualizadas ni protegidas ante vulnerabilidades. A pesar de que la empresa realiza auditorías de la configuración de la red cada mes, lo cual es un indicador positivo de compromiso con la seguridad, la falta de una estrategia formal de actualización podría generar brechas en la infraestructura.
Sobre la gestión de riesgos, se identificó que la empresa no ha realizado un análisis formal para detectar vulnerabilidades en la red y los sistemas de información. Esta falta de evaluación limita la capacidad de la empresa para anticipar y gestionar amenazas que puedan afectar la disponibilidad, integridad o confidencialidad de los sistemas. Además, se determinó que no existe un plan de continuidad del negocio y recuperación ante desastres específico para la red de datos, lo que representa una vulnerabilidad crítica, ya que en caso de una interrupción grave del servicio no se cuenta con lineamientos formales para restablecer operaciones y proteger la información.
En relación con la gestión de la información, se identificó que sí existe una política de clasificación de datos y que se implementan controles de acceso basados en roles y responsabilidades, lo cual es positivo para la seguridad de la información. Sin embargo, se señaló que no se utilizan medidas de cifrado para proteger la información en tránsito y en reposo, lo que representa un riesgo considerable, ya que los datos pueden ser interceptados o comprometidos.
Respecto a las copias de seguridad, se indicó que estas se realizan todos los días y que se hacen pruebas periódicas, lo cual representa una fortaleza destacada en la gestión de la continuidad del negocio. No obstante, la empresa carece de un proceso formal para la gestión de incidentes de seguridad y la notificación de violaciones de datos, lo que podría dificultar la respuesta ante amenazas.
Sobre la cultura de seguridad dentro de la empresa, se mencionó que se envían mensajes informativos sobre buenas prácticas en seguridad de la información, pero no se realiza una capacitación formal ni sistemática, lo que puede generar una baja concienciación del personal sobre riesgos y amenazas cibernéticas. También se determinó que la empresa no cuenta con un Sistema de Gestión de Seguridad de la Información (SGSI) alineado con ISO 27001, lo que limita la capacidad de estructurar y mejorar continuamente su seguridad.
Finalmente, en cuanto a la visión de la empresa para la escalabilidad de su infraestructura tecnológica, se indicó que existe una estrategia definida y que se contempla la renovación tecnológica anual para evitar la obsolescencia. Este enfoque preventivo es positivo, aunque sería ideal que se ampliara para incluir componentes estratégicos a largo plazo.
3.2.1.6.1.Diagrama Actualizado de la Topología Física y Lógica de la Red.
Como parte del proceso de diagnóstico de la infraestructura de red de Central Motor S.A.S., se desarrolló un diagrama actualizado que representa tanto la topología física como la lógica de la red. Este diagrama incluye la distribución de los equipos de cómputo, impresoras, teléfonos IP y puntos de acceso (AP) inalámbricos, detallando su ubicación por área funcional y su interconexión con los diferentes switches y racks.
La representación física refleja cómo están dispuestos los dispositivos dentro de cada área de trabajo, permitiendo identificar claramente la densidad de conexiones y la cantidad de nodos conectados en cada gabinete. Por su parte, la topología lógica detalla la estructura de interconexión de los dispositivos activos, la relación entre los switches de acceso y distribución, y la forma en que los AP se enlazan con la red principal.
Ilustración 40
Diagrama topología física: Área de Postventa Ford piso 5


Ilustración 41
Diagrama topología física: Área de vitrina piso 3

Ilustración 42
Diagrama topología física: Área de colisión piso 6




Ilustración 43
Diagrama de topología física: Área de administración piso 4

Ilustración 44
Diagrama de topología física: Área de alistamiento piso 7

Ilustración 45
Diagrama de topología física: Área de Recepción piso 2.

Ilustración 46
Diagrama de topología física: Área de Sótano piso 1.

Durante el análisis del diagrama lógico, se identificó una problemática estructural relacionada con la gestión de los puntos de acceso inalámbricos. En varias zonas se evidenció que los AP no están conectados al switch más cercano de su misma área, sino que establecen conexión con AP ubicados en otras zonas físicas del edificio. Este comportamiento sugiere una distribución desorganizada de la red inalámbrica, posiblemente resultado de extensiones improvisadas o falta de planificación en la cascada de red. Esta configuración genera dependencia entre áreas no relacionadas, incrementa la complejidad en la gestión de la red, y podría ocasionar problemas de latencia, pérdida de señal o congestión en determinados tramos del backbone.
Adicionalmente, la forma en que están organizados los AP impacta directamente en la eficiencia del roaming inalámbrico, ya que la señal de un área puede depender de un punto de acceso remoto con mayor carga de usuarios, afectando la estabilidad de la conexión y degradando el servicio para los usuarios que se encuentren en movimiento o en zonas límite.
Ilustración 47
Diagrama de Topología Lógica

Para mejor claridad de la topología, cada zona contiene un número específico de equipos de cómputo conectados a la red, ya sea de forma directa o a través de dispositivos de interconexión como switches y access points. A continuación, se describen las áreas según su codificación por color:
En la zona de color amarillo claro, ubicada en la esquina superior izquierda de la imagen, se encuentran cuatro equipos de cómputo, cada uno con su respectivo Access Point (AP). 
La zona verde, situada en la parte central superior, corresponde al área de Colisión, en donde se encuentran conectados cuatro (4) equipos. 
En el sector rosado palo, ubicado en la parte superior derecha del esquema, se encuentra el área de Administración, conformada por veinte (20) equipos organizados jerárquicamente. 
La zona salmón claro, ubicada en la parte media central del diagrama, representa el área de Posventa Ford, en la cual se encuentran veintiséis (26) equipos conectados. 
El área más extensa del esquema está representada con el color naranja y corresponde a la Vitrina, donde se conectan cuarenta y cuatro (44) equipos.
En la parte inferior izquierda, dentro de la zona amarilla intensa, se encuentra el área del Sótano, que cuenta con catorce (14) equipos. 
Finalmente, la zona morada, ubicada en la parte inferior derecha, corresponde al área de Recepción, con ocho (8) equipos conectados.
3.2.1.7.Propuesta de Mejora, Orientadas a la Redundancia, Escalabilidad y Fortalecimiento de la Seguridad 
3.2.1.7.1.Diseño de la Infraestructura de Red en Central Motor.
Se llevará a cabo una simulación integral utilizando herramientas como GNS3. Esta simulación contempla el rediseño tanto lógico como físico de la red, enfocándose en la escalabilidad, el orden estructural, la seguridad y la continuidad operativa de los servicios tecnológicos de la organización.
En primer lugar, se presentará una nueva topología en la que se reorganizará completamente el cableado estructurado y la disposición de los dispositivos de interconexión. Cada área funcional (Administración, Colisión, Repuestos, Alistamiento, Comercial y Sótano) contará con switches de acceso dedicados, conectados directamente a un núcleo de distribución centralizado. Todos los puntos de acceso inalámbrico (AP) se conectarán al switch correspondiente de su misma área, eliminando enlaces cruzados que actualmente generan pérdida de control, dependencia de nodos ajenos y problemas de latencia.
En el diseño físico, se simulará el uso de cableado estructurado categoría 6 con etiquetado completo en ambos extremos, permitiendo una trazabilidad visual y técnica entre puntos de red, puertos y dispositivos conectados. Asimismo, se reservará espacio adicional en los gabinetes de comunicaciones y se incluirán switches adicionales para futuras expansiones sin afectar el rendimiento ni requerir una reconfiguración mayor.
Desde el plano lógico, se establecerá una segmentación de red mediante VLANs por área de trabajo, junto con una nomenclatura estandarizada, asignación de accesos por rol y políticas básicas de respaldo para dispositivos críticos. Esta estructura organizada permitirá mejorar la mantenibilidad, estabilidad y gobernabilidad de la red.
Adicionalmente, se desarrollará una simulación complementaria que incluirá un modelo de conectividad redundante, aprovechando los dos proveedores de internet actuales: TIGO UNE y Media Commerce. En este escenario, se configurará el firewall Sophos XG 125 para gestionar la conmutación automática ante fallos y balanceo de carga entre ambos enlaces, lo que garantizará la continuidad de la conectividad ante posibles caídas del proveedor principal.
Como medida adicional de continuidad operativa, se integrarán routers de respaldo en zonas críticas, los cuales permitirán mantener la operación local en caso de fallos en los switches principales o interrupciones hacia el núcleo de la red.
También se llevarán a cabo unos parámetros de las áreas críticas, incluyendo servidores, cámaras de seguridad y sistemas de gestión, con políticas de control de acceso por direcciones MAC, monitoreo de tráfico por grupo de trabajo, y mecanismos de aislamiento de servicios sensibles.
Dentro de esta simulación, se integrará también una propuesta para evaluar la escalabilidad de la infraestructura frente a la incorporación de una nueva marca, que implicará el ingreso de aproximadamente 20 nuevos colaboradores entre personal técnico, comercial y administrativo. Esta inclusión permitirá validar en tiempo real el impacto de crecimiento sobre el núcleo de red, la capacidad de los switches, el rendimiento del cableado estructurado, el manejo de nuevas VLANs y la adaptabilidad del diseño físico en términos de espacio, puntos de red y conectividad inalámbrica. La simulación ofrecerá un entorno controlado donde se podrá observar si la red es capaz de escalar de forma ordenada, sin generar cuellos de botella, conflictos de direccionamiento, ni degradación de los servicios actuales, asegurando así una infraestructura sostenible a largo plazo.

3.2.2.Preparación
Se desarrolló un plan detallado basado en los datos recopilados durante la fase de planificación. En esta etapa, se identificaron los requerimientos específicos de la red y de la infraestructura necesaria para su óptimo funcionamiento.
3.2.2.1.Definición de Requisitos Técnicos.
Se determinó la cantidad de hosts presentes en la infraestructura tecnológica, incluyendo servidores, computadores, impresoras y otros dispositivos esenciales, con el fin de establecer con precisión los elementos necesarios para soportar tanto las operaciones actuales como las proyectadas. Se definió el número de subredes requeridas, tomando como base la estructura organizacional por departamentos y funciones específicas. Así mismo, se especificó la cantidad y tipo de puntos de acceso inalámbrico (Access Point) necesarios para optimizar la cobertura y calidad de la conectividad. Finalmente, se verificó la necesidad de implementar dispositivos en los niveles Core, de distribución y acceso, dentro de una arquitectura de red jerárquica adecuada para soportar el crecimiento progresivo de la empresa.
3.2.2.2.Identificación de Objetivos de Escalabilidad de para la Nueva Infraestructura.
Se identificaron los objetivos de escalabilidad para asegurar que la nueva infraestructura tenga la capacidad de crecer y adaptarse eficientemente conforme evolucionen las necesidades operativas de la organización. Estos objetivos se centraron en garantizar un desempeño sostenido, flexibilidad en la ampliación de nodos y facilidad en la incorporación de nuevos servicios sin generar afectaciones en la red existente.
3.2.2.3.Definición de Requerimientos de Protección de Datos y Accesos.
Se establecieron los requerimientos necesarios para proteger los datos sensibles, así como los criterios para la gestión de accesos seguros a la infraestructura de red. Este proceso incluyó la definición de políticas de acceso por roles, autenticación reforzada, segmentación por VLAN y controles específicos que aseguran la confidencialidad, integridad y disponibilidad de la información crítica en tránsito y en reposo.
3.2.2.4.Recopilación de Requisitos de Diseño Físico y Lógico de la Red.
Se recopilaron los lineamientos para el diseño físico y lógico de la red. En cuanto al diseño físico, se contempló la distribución ordenada del cableado estructurado categoría 6, la ubicación estratégica de los dispositivos de red, y la inclusión de racks y canaletas para facilitar el mantenimiento y la expansión. En lo referente al diseño lógico, se definieron las configuraciones necesarias para soportar la segmentación de la red, asegurar la conectividad eficiente entre nodos, y aplicar medidas de seguridad lógica que respalden la operación diaria de cada una de las áreas de la empresa.
3.2.2.5.Entregables.
3.2.2.5.1.Proyección de Crecimiento Futuro y Estrategias para Soportar Mayor Demanda.
Con la implementación de una nueva marca, se proyecta un aumento previsto de 20 personas entre personal técnico, gerencia y equipo comercial. Esta proyección requiere adecuaciones significativas en la infraestructura tecnológica y física de la organización.
Actualmente, no se dispone del espacio físico suficiente para ubicar al nuevo personal. Por tal motivo, se proponen dos alternativas principales:
Construcción de un nuevo piso sobre la edificación existente, exclusivo para la operación de la nueva marca.
Reducción del espacio destinado a parqueaderos, aprovechando esa área para desarrollar nuevas oficinas administrativas y técnicas.
En Colombia, aunque no existe una norma única que defina los metros cuadrados por trabajador en oficina, entidades como el Ministerio de Trabajo, y el área de seguridad y salud en el trabajo, se recomienda:
Para espacios administrativos, cada trabajador debe contar con un mínimo de 3 x 2 m², considerando el mobiliario, la circulación y el cumplimiento de condiciones ergonómicas.
Para el área técnica, cada operario debe tener un espacio de 3 x 2 metros, adicional al área destinada a los vehículos con los que trabajará, cuya dimensión mínima es de 5.20 metros de largo por 2.40 a 2.50 metros de ancho.
Cada nuevo colaborador contará con su espacio individual y equipo asignado, según el perfil del cargo:
Administrativos y comerciales: estaciones de trabajo con equipos tipo AIO (All-in-One) o portátiles.
Técnicos: equipos portátiles resistentes o AIO según requerimiento de operación, con acceso a sistemas y software de diagnóstico en red.
Para poder realizar dicha implementación se necesitará:
Conectividad cableada (red estructurada) y puntos de Access Point.
Router, switches administrables, cámaras de vigilancia IP.
Segmentación de red mediante VLAN y respaldo eléctrico con UPS.
3.2.2.5.2.Descripción de los Equipos Necesarios de Red y Computo.
Se seleccionaron los equipos más adecuados para establecer una infraestructura de red eficiente, segura y escalable. El Patch Panel Cat 6 de 24 puertos es esencial para distribuir las conexiones de red de manera ordenada hacia los dispositivos. Este tipo de patch panel es ideal para facilitar la gestión de los cables y permitir la expansión en el futuro si fuera necesario. Además, el Rack de comunicaciones de 5U proporciona un espacio adecuado para alojar los dispositivos de red, como los switches, router y demás equipos, asegurando una instalación ordenada y accesible para su mantenimiento.
Los Access Points Ubiquiti UniFi U7-Pro WiFi7 son dispositivos de alto rendimiento, capaces de ofrecer conectividad inalámbrica de alta velocidad y estabilidad. Con su capacidad de triple banda y puerto 2.5G Ethernet, son ideales para asegurar una cobertura de red eficiente en toda la instalación, especialmente en entornos donde se requiere un alto volumen de tráfico inalámbrico. Para la gestión de la red, se seleccionó un Router Rg-eg209gs de 9 puertos, con capacidad Multi-WAN, lo que garantiza una conectividad robusta y redundante entre las diferentes redes. Este router es clave para garantizar la continuidad del servicio y gestionar el tráfico entre los dispositivos locales y el acceso a Internet.
Para la seguridad de la infraestructura, se optaron por Cámaras de seguridad Hikvision, que son una excelente opción para monitorear y asegurar las instalaciones. Las cámaras con resolución 720p son suficientes para una vigilancia básica y su diseño tipo bala las hace ideales para exteriores. Los Switches TL-SG2428P, con 24 puertos PoE+ y 4 ranuras SFP, son perfectos para conectar todos los dispositivos de la red y proporcionar alimentación a equipos como las cámaras de seguridad y teléfonos IP, todo a través del mismo cable de red, lo que reduce la cantidad de cables necesarios y mejora la eficiencia. Finalmente, se mantendrán los Teléfonos IP empresariales FANVIL X3G de Fanvil actualmente en uso, ya que se consideran adecuados para las necesidades de comunicación de la empresa. Estos teléfonos utilizan la tecnología VoIP, lo que permite una comunicación interna eficiente y de alta calidad, sin la necesidad de una infraestructura telefónica tradicional. Su desempeño ha sido satisfactorio y no requiere actualización en este momento, por lo que se continuará con su uso, asegurando la compatibilidad con la nueva infraestructura de red y manteniendo la eficiencia operativa sin la necesidad de inversión adicional en equipos de telefonía.
Tabla 1
Tabla de dispositivos de red.
Dispositivo de red	Descripción	Cantidad
Patch Panel	Patch Panel Cat 6 de 24 Puertos – Marca Infinite	1
Rack de comunicaciones	Rack de 5U - 29 cm de alto, 52 cm de ancho y 40 cm de profundidad	1
Access Point	Ubiquiti UniFi U7-Pro WiFi7, Triple banda con puerto 2.5G ethernet	3
Router	Rg-eg209gs Router 9 Puertos Multi-wan	1
Cámara	CAMARA SEGURIDAD HIKVISION BALA METALICA 3.6MM 720P	6
Switch	TL-SG2428P Switch Smart Gigabit JetStream de 24 puertos PoE+ y 4 ranuras SFP	2
Teléfono	Teléfono IP empresarial FANVIL X3G de Fanvil	12
Cable UTP	Categoría 6	350 metros

En cuanto a los equipos de cómputo, se ha decidido mantener y reutilizar los portátiles ThinkPad E14 Gen 5 y los All-in-One Neo 30a 22 Gen 3, ya que estos dispositivos han sido previamente empleados por la empresa y, tras el análisis técnico realizado, demostraron contar con buenas especificaciones, excelente rendimiento y resultados positivos en su uso operativo.

Tabla 2
Tabla de dispositivos de cómputo.
Dispositivo Computo	Descripción	Cantidad
Portátil	E14 Gen 5 (Type 21JK, 21JL) Laptops (ThinkPad) - Type 21JL	12
All In One	Neo 30a 22 Gen 3 Desktop (ThinkCentre) - Type 12B1)	8

3.2.2.5.3.Presupuesto de Implementación.
La siguiente tabla presenta el detalle del presupuesto estimado, permitiendo visualizar claramente la inversión requerida para llevar a cabo la implementación tecnológica proyectada.
El presupuesto total estimado para la implementación tecnológica asciende a $107.165.083,30 COP, incluyendo equipos de red, cómputo, mano de obra e imprevistos. Este valor refleja una inversión sólida y bien estructurada que busca garantizar la actualización, expansión y eficiencia de la infraestructura tecnológica.
Tabla 3
Tabla de presupuesto estimado, equipos de red.
Presupuesto
Conceptos	Cantidad	Valor Unitario	Valor Total
Dispositivos de red
Patch Panel	1	 $    241.900,00 	$ 241.900,00
Rack de comunicaciones	1	 $    205.000,00 	$ 205.000,00
Access Point	3	 $ 1.024.000,00 	$ 3.072.000,00
Router	1	 $    389.000,00 	$ 389.000,00
Cámara	6	 $      55.000,00 	$ 330.000,00
Switch	2	 $    976.000,00 	$ 1.952.000,00
Teléfono	12	 $    279.064,00 	$ 3.348.768,00
Cable UTP	350	 $        2.734,10 	$ 956.935,00
Total	$ 10.495.603,00
Dispositivos de computo
Portátil	12	$ 4.399.000	$ 52.788.000
All In One	8	$ 3.079.900	$ 24.639.200
Total	$ 77.427.200
Total, Compra	$ 87.922.803,00
Mano de obra (Puerto datos/Puerto Voz/Instalaciones)	 $               9.500.000,00 
Imprevistos (10%)	 $               9.742.280,30 
Total, Presupuesto	 $           107.165.083,30 

El presupuesto está alineado con los objetivos de escalabilidad, continuidad y eficiencia de la red y los servicios tecnológicos. Se trata de una inversión estratégica que combina adecuadamente infraestructura de red, tecnología de cómputo, instalación profesional y márgenes de seguridad financiera, posicionando a la empresa para afrontar con solidez sus necesidades actuales y futuras.
3.2.2.5.4.Diagramas Preliminares de las Conexiones Lógicas de Red
3.2.2.5.4.1.Diagrama Preliminares con implementación de escalabilidad
Para la demostración de la implementación preliminar del diseño de infraestructura de red en la empresa Central Motor, ubicada en Bucaramanga, se utilizó el software Packet Tracer. Esta herramienta permitió visualizar de manera adecuada el diseño propuesto, así como asignar los recursos de red según el área y la cantidad de equipos requeridos. 
Ilustración 48 
Evidencia Topología Packet Tracer con Implementación Escalable

En la parte superior de nuestra topología, representada en color naranja, se ubican todos los equipos críticos mencionados en la revisión inicial, los cuales fueron asignados a una VLAN dedicada para garantizar la segmentación y seguridad de esta zona. A continuación, encontramos el piso de colisión en color rosado con sus equipos predefinidos, incluyendo un área sin color asignado que corresponde a una implementación para escalabilidad de usuarios en esta zona.
El área de posventa (30 equipos), identificada en color salmón, opera bajo una única VLAN al no requerir subdivisión interna. En contraste, el área de administración presenta una segmentación detallada mediante múltiples VLANs debido al manejo de información confidencial: VLAN morado oscuro para Tesorería (3 equipos), rojo vino tinto para Nómina (1 equipo), salmón claro para Seguros (2 equipos), verde claro para Diseño (3 equipos), azul para Facturación Electrónica, verde vibrante para Contabilidad (2 equipos), azul cielo para Asistente de Gerencia (1 equipo), y amarillo pastel para unificar el acceso de portátiles en esta área.
En el siguiente nivel correspondiente a las vitrinas, implementamos una segmentación específica por marcas: verde menta para facturación de taller (1 equipo), amarillo pálido para portátiles Hyundai (8 equipos), rosado claro para portátiles Suzuki y Citroën (7 equipos), azul claro para facturación (2 equipos), morado oscuro para repuestos (2 equipos), verde fluorescente para área comercial Ford (8 equipos), morado claro para Kia (10 equipos), azul-morado para gerencia y mercadeo, marfil para 2 equipos segmentados, rosado palo para caja, y morado oscuro exclusivo para el gerente de usados. Además, incluimos un área sin color asignado para identificar más fácil el área que se va a identificar como propuesta de escalabilidad.
El área de recepción cuenta con una segmentación particular: color salmón para el access point de clientes, verde fluorescente para recepción de taller Ford (4 equipos), y azul agua marina para mantener unificados 4 equipos de esta zona.
Finalmente, en el sótano implementamos: azul oscuro para servicio Hyundai (2 equipos), violeta oscuro para taller Kia (2 equipos), rosado fucsia para control de access points de portátiles, verde oscuro para Derco (2 equipos), mostaza para repuestos (3 equipos), violeta para área de colisión (1 equipo), y un área sin color asignado para el futuro taller de nueva marca.
Ilustración 49 
Evidencia Topología GNS3 Implementación Escalable

Para optimizar el rendimiento de la red y reducir el consumo excesivo de recursos del aplicativo principal, se ha implementado una consolidación estratégica de las VLANs manteniendo la estructura de seguridad original. En este nuevo esquema, cada área conserva su VLAN asignada pero ahora se trabajará con equipos representativos: donde antes había múltiples dispositivos (por ejemplo, 10 equipos en un área), ahora solo uno funcionará como nodo de pruebas, debidamente identificado con color rojo para su fácil reconocimiento. Estos equipos clave, distribuidos en cada VLAN, permitirán validar la conectividad y el funcionamiento de cada segmento sin afectar la seguridad ni la segmentación lógica por departamentos.
El diseño mantiene todas las VLANs originales pero opera de manera más eficiente, reduciendo significativamente el consumo de recursos mientras preserva la capacidad de escalamiento y los protocolos de seguridad.
3.2.2.5.4.2.Diagrama Preliminares sin implementación de escalabilidad
Ilustración 50
Evidencia Topología Packet Tracer sin implementación de escalabilidad





Ilustración 51
Evidencia Topología GNS3 sin Implementación de Escalabilidad.

3.2.2.6.Identificación de Riesgos Potenciales y Estrategias para Mitigarlos.
3.2.2.6.1.Matriz de Riesgo
Se han identificado un total de 13 riesgos principales, los cuales han sido evaluados considerando su estado actual (vigente, reducido o controlado), los departamentos afectados y las acciones correctivas recomendadas. Entre los riesgos más críticos se encuentran los problemas en servidores, las fallas en los equipos de red, las caídas del servicio de Internet, los accesos no autorizados a los sistemas y la falta de respaldo de información. Estos riesgos representan una amenaza significativa para la continuidad operativa de la empresa, ya que pueden generar interrupciones en los servicios críticos, afectar la productividad, comprometer datos sensibles y aumentar la vulnerabilidad ante ataques cibernéticos.
Los problemas en los servidores han sido identificados como una de las amenazas más graves, ya que pueden provocar la interrupción de servicios esenciales y la pérdida de datos. Las fallas en los equipos de red también suponen un riesgo importante, pues afectan la conectividad y disponibilidad del servicio, generando dificultades en las operaciones diarias. De igual manera, las caídas del servicio de Internet pueden impactar procesos fundamentales, como el acceso a servicios en la nube y la comunicación con clientes y proveedores. Por otro lado, los accesos no autorizados a sistemas representan una vulnerabilidad crítica, ya que pueden comprometer información confidencial y generar incidentes de seguridad. Finalmente, la falta de respaldo de información incrementa significativamente el riesgo de pérdida de datos en caso de fallos técnicos o ataques informáticos.
Para la evaluación de los riesgos, se han considerado dos criterios principales: la probabilidad de ocurrencia y el impacto que tendrían en la organización. La probabilidad se ha clasificado en alta (A), media (M) y baja (B), mientras que el impacto se ha evaluado como alto (A), medio (M) y bajo (B). Con base en estos criterios, los riesgos han sido categorizados en diferentes niveles de prioridad: riesgos críticos (zona roja), riesgos moderados (zona amarilla) y riesgos bajos (zona verde). Los riesgos de prioridad alta requieren una intervención urgente, mientras que aquellos de prioridad media o baja pueden ser gestionados con estrategias de mitigación a mediano plazo.
3.2.2.6.2.Lista de Verificación para la Mitigación de Riesgos Asociados al Cumplimiento de Requisitos
A partir de la matriz de riesgos identificada, se analizaron los activos afectados, las causas probables (fallos técnicos, humanos o ciberataques) y los impactos esperados, para asociar cada riesgo con los controles pertinentes de la norma ISO/IEC 27001:2022 (específicamente su Anexo A). Este estándar internacional proporciona un marco claro para la gestión de riesgos relacionados con la seguridad de la información, que incluye confidencialidad, integridad y disponibilidad.
Se sigue el siguiente criterio:
Si el riesgo compromete la disponibilidad del servicio → se asocia a los controles de continuidad, infraestructura o soporte técnico (A.12, A.17).
Si compromete la confidencialidad o control de acceso → se asocia a los controles de acceso lógico (A.9).
Si compromete la red o los canales de comunicación → se asocia a los controles de seguridad en comunicaciones (A.13).
Si compromete la integridad de la información o la protección ante amenazas externas → se relaciona con controles de protección frente a malware, respaldos y respuesta a incidentes (A.10, A.12, A.16, A.18).
Tabla 4
Tabla de asociación de riesgos críticos con controles de la ISO/IEC 27001:2022.
#	Riesgo Identificado	Análisis del Impacto y Justificación Normativa	Control ISO/IEC 27001 Asociado
1	Problemas en servidores	Afecta la disponibilidad y recuperación de sistemas críticos	A.12.1.1 – Documentación operativa
A.17.1.2 – Implementación de medidas de continuidad
2	Fallas en equipos de red	Interrumpe la conectividad, afectando operaciones y servicios en red	A.13.1.1 – Protección de redes
3	Caídas del servicio de Internet	Impacta procesos en la nube y comunicación externa	A.13.1.3 – Separación en redes, continuidad del servicio
4	Accesos no autorizados a sistemas	Compromete la confidencialidad e integridad de los datos	A.9.2.1 – Gestión de cuentas de usuarios
5	Falta de respaldo de información	Aumenta el riesgo de pérdida de datos ante fallos o ataques	A.12.3.1 – Procedimientos de backup
6	Pérdida de datos por fallos técnicos	Riesgo crítico sin respaldo ni plan de recuperación	A.17.1.3 – Verificación de planes de continuidad
7	Vulnerabilidades ante ataques cibernéticos	Afecta la integridad, disponibilidad y confidencialidad	A.18.2.3 – Pruebas de sistemas de seguridad

Tabla 5
Lista de verificación para la mitigación de riesgos asociados al cumplimiento de requisitos ISO/IEC 270001:2022.
Ítem	Riesgo Asociado	Control ISO/IEC 27001	Pregunta de Verificación	Acción de Mitigación Propuesta
1	Problemas en servidores	A.12.1.1 / A.17.1.2	¿Existe un mantenimiento preventivo documentado para los servidores críticos?	Establecer cronograma y bitácora de mantenimiento técnico mensual.
2	Fallas en equipos de red	A.13.1.1	¿Se realizan revisiones periódicas a switches, routers y puntos de acceso?	Implementar rutina de diagnóstico y reemplazo de equipos obsoletos.
3	Caídas del servicio de Internet	A.13.1.3	¿Existe redundancia en el servicio de Internet o proveedor secundario?	Contratar ISP secundario y configurar failover automático.
4	Accesos no autorizados a sistemas	A.9.2.1	¿Se gestiona el ciclo de vida de cuentas de usuario y se controla el acceso por roles?	Implementar autenticación multifactor y auditoría de accesos.
5	Falta de respaldo de información	A.12.3.1	¿Se realizan backups automáticos y están verificados?	Automatizar copias de seguridad y almacenar en nube y local.
6	Pérdida de datos por fallos técnicos	A.17.1.3	¿Existe y se prueba un plan de recuperación ante desastres?	Elaborar y probar un DRP cada 6 meses.
7	Vulnerabilidades ante ataques cibernéticos	A.18.2.3	¿Se realizan análisis de vulnerabilidades o pruebas de penetración periódicamente?	Contratar auditoría de ciberseguridad anual.


3.2.3.Diseño
Durante la fase de diseño, se construyó una representación detallada de la solución de red a implementar. Se elaboraron diagramas físicos y lógicos en los que se especificaron los componentes de hardware y software utilizados. Además, se integraron planes de seguridad y políticas de gestión que regularían el funcionamiento de la red modernizada.
3.2.3.1.Definición de herramienta de simulación a emplear para el proyecto.
Para las simulaciones y validaciones del diseño de red, se evaluaron diversas herramientas de simulación. Finalmente, se seleccionó aquella que ofrecía mayor eficiencia tanto en la creación de topologías complejas como en configuraciones básicas. Esta herramienta permitió representar múltiples dispositivos y validar los protocolos y configuraciones necesarias para el entorno real.
3.2.3.2.Validación de los Protocolos de Acceso y Autenticación.
Se realizó una validación integral de los protocolos de acceso y autenticación que serían implementados. Esta revisión garantizó que las configuraciones aplicadas estuviesen alineadas con las mejores prácticas de seguridad. Se probó el funcionamiento de los controles de acceso en un entorno controlado, asegurando su efectividad ante distintos escenarios y tipos de usuario.
3.2.3.3.Desarrollo del Diseño Físico de la Red.
Se desarrolló el diseño físico de la red, definiendo la ubicación de servidores, switches, routers, puntos de acceso, cámaras, lectores biométricos, DVR, teléfonos IP y demás dispositivos. También se planificó y ejecutó el cableado estructurado, asegurando una distribución lógica y organizada. La infraestructura física fue documentada en planos detallados que permitieron un despliegue ordenado y conforme a estándares técnicos.
3.2.3.4.Creación del Diseño Lógico.
La arquitectura lógica fue diseñada con base en la segmentación por subredes, la definición de VLANs y la implementación de protocolos de enrutamiento. Se optimizó el rendimiento y la seguridad mediante la asignación eficiente de direcciones IP, la separación de dominios de broadcast y la identificación de zonas críticas. Todo este diseño fue previamente simulado, permitiendo detectar errores antes del despliegue definitivo.
3.2.3.5.Entregables.
3.2.3.5.1.Listado de Equipos con Implementación y Cambios de la Infraestructura Actual.
Como parte del proceso de modernización tecnológica de Central Motor, se ha definido la actualización y/o reemplazo de un total de 147 elementos de infraestructura, con el fin de mejorar el rendimiento, la seguridad y la estabilidad de los servicios tecnológicos. A esto se suman 26 nuevos elementos que harán parte de la propuesta de implementación, consolidando un entorno más robusto y eficiente.
Dentro de las actualizaciones más destacadas se encuentran los lectores biométricos, que se actualizarán al modelo HIKVISION DS-K1T804AF K1T804A Pro Series Fingerprint Terminal, una solución moderna que garantiza mayor precisión y seguridad en el control de accesos. Igualmente, se reemplazarán dos DVR existentes por un nuevo DVR de 4 megapíxeles, 32 canales TURBOHD, con capacidad para 16 canales IP, cuatro bahías de disco duro, 4 canales de audio y funciones avanzadas de video análisis, lo que fortalecerá considerablemente el sistema de videovigilancia.
En cuanto a las cámaras de seguridad, se realizará la migración de las cámaras domo Turbo de 2 MP al modelo ColorVu Hikvision DS-2CE70DF0T-PF de 1080P, las cuales ofrecen visión a color aún en condiciones de baja iluminación, mejorando la capacidad de monitoreo. Asimismo, las cámaras IP 2MP actuales serán reemplazadas por el modelo Hikvision DS-2CD1023G2-LI, una cámara tipo bala con infrarrojo de 30 metros y certificación IP67, ideal para exteriores.
En el área de conectividad, se actualizarán 20 puntos de acceso inalámbricos (AP) y cinco switches, lo que permitirá una mayor estabilidad en la red, mejorando la cobertura y velocidad de conexión para todos los usuarios. En cuanto a la telefonía, se renovarán 64 dispositivos, manteniendo el mismo modelo, pero en una versión más actualizada, asegurando compatibilidad con la infraestructura existente mientras se mejora el rendimiento.
Dentro de este proceso también se tiene presente la organización física de los racks de comunicaciones y el etiquetado estructurado de todos los elementos de red, lo cual facilitará las labores de mantenimiento, monitoreo, identificación de fallas y futuras ampliaciones. Esta práctica asegura una mejor gestión del cableado, reduce el riesgo de errores humanos y mejora el orden general del entorno técnico.
Tabla 6
Tabla de equipos actualizados.
Elemento	Modelo Actual	Modelo Nuevo o Actualización	Cantidad
Lectores de huella	Biométrico-HIKVISION-Lector de Proximidad MIFARE-3,000 Huellas-TCP-IP-150,000 Eventos - DSK1T804AMF	HIKVISION DS-K1T804AF K1T804A Pro Series Fingerprint Terminal	2
DVR	DVR 32 CANALES HIKVISION TURBO HD – 3MP – DS-7332HQHI-K4	DVR 4MP, 32 Canales TURBOHD, 16 IP, 4 Bahías, 4 Audio, Video análisis	2
Cámaras IP	Cámara IP 2MP Dual Light 30m PoE Onvif / DS-2CD1023G2-LIU	Cámara IP Hikvision DS-2CD1023G2-LI 2MP Bala IR 30m IP67	17
Cámaras TurboHD (Domo)	Cámara Domo Turbo 2MP A 1080p, Lente 2.8mm IR 20m Hikvision	Cámara Hikvision DS-2CE70DF0T-PF ColorVu 1080P Domo 2.8mm	36
Teléfonos	Mismo modelo, versión anterior	Misma línea de modelo, versión actualizada	64
Access Points (AP)	RG-AP840-L, Wi-Fi 6 Dual-Radio 5.378 Gbps Indoor AP	Ubiquiti UniFi U7-Pro WiFi7, Triple banda con puerto 2.5G ethernet	20
Switches	Switchs Capa 2 TRENDNET TEG-S24Dg 24 port Gigabit GREENnet Desktop Switch -Tl-sg1024d switch 24 puertos tp-link - TL-SG1048 - Gigabit Switch de 48 puertos	TL-SG2428P Switch Smart Gigabit JetStream de 24 puertos PoE+ y 4 ranuras SFP	5

El diagnóstico realizado evidenció la necesidad de reemplazar un total de 38 equipos de cómputo, los cuales presentan diversas deficiencias relacionadas con obsolescencia tecnológica, bajo rendimiento, incompatibilidad con software moderno y finalización de vida útil. Esta situación afecta directamente la productividad de los usuarios y dificulta la implementación de nuevas herramientas informáticas necesarias para el crecimiento y la operación eficiente de la organización. 
Entre los equipos identificados se encuentran 29 computadores All-in-One, 7 portátiles, 1 torre de escritorio y 1 MacBook, cuya antigüedad y especificaciones limitadas impiden cumplir con los requerimientos actuales. Muchos de ellos presentan procesadores desactualizados, almacenamiento mecánico (HDD), baja capacidad de memoria RAM y falta de soporte por parte de los fabricantes, lo cual incrementa el riesgo de fallos y vulnerabilidades de seguridad. El plan de renovación tecnológica propone el reemplazo de estos dispositivos por modelos actualizados y estandarizados, priorizando equipos con mayor rendimiento, eficiencia energética, compatibilidad con sistemas modernos y garantía vigente.
Este proceso de estandarización no solo facilitará el mantenimiento y gestión de los activos tecnológicos, sino que también permitirá mejorar el rendimiento de las operaciones, reducir el consumo energético y mitigar riesgos relacionados con fallas de hardware y brechas de seguridad.
Tabla 7
Tabla de modelos que serán actualizados.
Modelo Actual	Modelo Nuevo o Actualización	Cantidad
Aspire E5-575 (x2)	E14 Gen 5 (Type 21JK, 21JL) ThinkPad	2
C440 All-in-One (Type 6595)	Neo 30a 22 Gen 3 Desktop (ThinkCentre - Type 12B1)	1
C540 All-in-One (Type 6267)	Neo 30a 22 Gen 3 Desktop (ThinkCentre - Type 12B1)	1
E73z All-in-One (Type 10BD) (x16)	Neo 30a 22 Gen 3 Desktop (ThinkCentre - Type 12B1)	16
HP All-in-One 4488	M70q Gen 3 Desktop (ThinkCentre - Type 11T4)	1
HP Notebook 14-bp001la	E14 Gen 5 (Type 21JK, 21JL) ThinkPad	1
Laptop HP 240 G5 (x2)	Vostro 3400	2
MacBook Air 13.3	E14 Gen 5 (Type 21JK, 21JL) ThinkPad	1
V330-20ICB All-in-One (Type 10UL) (x5)	Neo 30a 22 Gen 3 Desktop (ThinkCentre - Type 12B1)	5
Vostro 260	M70q Gen 3 Desktop (ThinkCentre - Type 11T4)	1
Vostro 320 (x3)	M70q Gen 3 Desktop (ThinkCentre - Type 11T4)	3
Vostro 3460	Vostro 3400	1
XPS 13 L321X	Vostro 3400	1

De este modo, se obtuvo un presupuesto para las mejoras, excluyendo los costos asociados a la implementación de escalabilidad.
Tabla 8
Tabla de presupuesto estimado, equipos de cómputo (Excluyendo escalabilidad).
Presupuesto
Conceptos	Cantidad	Valor Unitario	Valor Total
Dispositivos de red
Lectores de huella	2	 $    567.899,24 	$ 1.135.798,48
DVR	2	 $ 3.090.948,84 	$ 6.181.897,68
Cámaras IP	17	 $    200.000,00 	$ 3.400.000,00
Cámaras TurboHD (Domo)	36	 $    105.000,00 	$ 3.780.000,00
Teléfonos	64	 $    279.064,00 	$ 17.860.096,00
Access Points (AP)	20	 $ 1.024.000,00 	$ 20.480.000,00
Switches	5	 $    976.000,00 	$ 4.880.000,00
Total	$ 57.717.792,16
Dispositivos de computo
Portátil E14	4	$ 4.399.000	$ 17.596.000
Portátil Vostro 3400	4	$ 2.000.000	$ 8.000.000
Tiny M70q	5	$ 4.149.990	$ 20.749.950
All In One Neo 30a 22	23	$ 3.079.900	$ 70.837.700
Total	$ 117.183.650
Total, Compra	$ 174.901.442,16
Mano de obra (Puerto datos/Puerto Voz/Instalaciones)	 $               2.750.000,00 
Imprevistos (10%)	 $             17.765.144,22 
Total, Presupuesto	 $           195.416.586,38 

Ahora, teniendo en cuenta que, si se llegará a realizar el objetivo de escalabilidad en conjunto de los cambios recomendado, el presupuesto sería el siguiente:
Tabla 9
Tabla de presupuesto estimado, equipos de cómputo (Incluyendo escalabilidad).
Presupuesto
Conceptos	Cantidad	Valor Unitario	Valor Total
Dispositivos de red
Lectores de huella	2	 $    567.899,24 	$ 1.135.798,48
DVR	2	 $ 3.090.948,84 	$ 6.181.897,68
Cámaras IP	17	 $    200.000,00 	$ 3.400.000,00
Cámaras TurboHD (Domo)	42	 $    105.000,00 	$ 4.410.000,00
Patch Panel	1	 $    241.900,00 	$ 241.900,00
Rack Comunicaciones	1	 $    205.000,00 	$ 205.000,00
Cable UTP	305	 $        2.734,10 	$ 833.900,50
Router	1	 $    389.000,00 	$ 389.000,00
Teléfonos	76	 $    279.064,00 	$ 21.208.864,00
Access Points (AP)	23	 $ 1.024.000,00 	$ 23.552.000,00
Switches	7	 $    976.000,00 	$ 6.832.000,00
Total	$ 68.390.360,66
Dispositivos de computo
Portátil E14	16	$ 4.399.000	$ 70.384.000
Portátil Vostro 3400	4	$ 2.000.000	$ 8.000.000
Tiny M70q	5	$ 4.149.990	$ 20.749.950
All In One Neo 30a 22	31	$ 3.079.900	$ 95.476.900
Total	$ 194.610.850
Total, Compra	$ 263.001.210,66
Mano de obra (Puerto datos/Puerto Voz/Instalaciones)	 $             12.250.000,00 
Imprevistos (10%)	 $             27.525.121,07 
Total, Presupuesto	 $           302.776.331,73 

3.2.3.5.2.Diagramas preliminares de las conexiones lógicas de la red.
Se elaboraron los diagramas preliminares de las conexiones lógicas de la red ylos flujos de comunicación entre los componentes clave. Estos diagramas representan la topología lógica de la red que se va a implementar para poder lograr el objetivo de una red escalable, segura y funcional.
Tabla 10
Tabla de distribución de conexiones lógicas de red.
Piso	Área	Subred IP	Máscara	Rango de Hosts	Broadcast	vlan
Sótano	Wifi	192.168.0.0	255.255.255.128	192.168.0.1 
- 192.168.0.126	192.168.0.127	10
Sótano	Kia	192.168.0.128	255.255.255.240	192.168.0.129 - 192.168.0.142	192.168.0.143	11
Sótano	Hyundai	192.168.0.144	255.255.255.248	192.168.0.145 - 192.168.0.150	192.168.0.151	12
Sótano	Derco	192.168.5.64	255.255.255.240	192.168.5.65 - 192.168.5.78	192.168.5.79	13
Sótano	Colisión	192.168.0.168	255.255.255.248	192.168.0.169 - 192.168.0.174	192.168.0.175	14
Sótano	Otros	192.168.0.176	255.255.255.240	192.168.0.177 - 192.168.0.190	192.168.0.191	15
2piso	Hyundai	192.168.1.0	255.255.255.224	192.168.1.1 
- 192.168.1.30	192.168.1.31	20
2piso	Suzuki	192.168.1.32	255.255.255.224	192.168.1.33 - 192.168.1.62	192.168.1.63	21
2piso	Kia	192.168.1.64	255.255.255.192	192.168.1.65 - 192.168.1.126	192.168.1.127	22
2piso	Derco	192.168.1.128	255.255.255.240	192.168.1.129 - 192.168.1.142	192.168.1.143	23
2piso	Repuestos	192.168.1.144	255.255.255.240	192.168.1.145 - 192.168.1.158	192.168.1.159	24
Edificio	Ford	192.168.5.0	255.255.255.192	192.168.5.1 
- 192.168.5.62	192.168.5.63	25
2piso	Seguro	192.168.1.224	255.255.255.240	192.168.1.225 - 192.168.1.238	192.168.1.239	26
2piso	Factura	192.168.1.240	255.255.255.240	192.168.1.241 - 192.168.1.254	192.168.1.255	27
2piso	Taller	192.168.2.0	255.255.255.248	192.168.2.1 
-
192.168.2.6	192.168.2.7	28
2piso	Caja	192.168.2.8	255.255.255.248	192.168.2.9 
- 192.168.2.14	192.168.2.15	29
1erpiso	Usado	192.168.2.16	255.255.255.248	192.168.2.17 - 192.168.2.22	192.168.2.23	30
3piso	Tesorería	192.168.5.80	255.255.255.240	192.168.5.81 - 192.168.5.94	192.168.5.95	40
3piso	Contabilidad	192.168.2.32	255.255.255.240	192.168.2.33 - 192.168.2.46	192.168.2.55	41
3piso	Nómina	192.168.2.56	255.255.255.248	192.168.2.57 - 192.168.2.62	192.168.2.63	42
3piso	Seguros	192.168.2.64	255.255.255.240	192.168.2.65 - 192.168.2.78	192.168.2.79	43
3piso	Diseño	192.168.2.80	255.255.255.240	192.168.2.81 - 192.168.2.94	192.168.2.95	44
3piso	Factura	192.168.2.96	255.255.255.248	192.168.2.97 - 192.168.2.102	192.168.2.103	45
3piso	Administración	192.168.5.96	255.255.255.240	192.168.5.97 - 192.168.5.110	192.168.5.111	46
3piso	Gerencia	192.168.2.112	255.255.255.240	192.168.2.113 - 192.168.2.124	192.168.2.135	47
Piso	Posventa	192.168.3.0	255.255.255.128	192.168.3.1 
- 192.168.3.126	192.168.3.127	50
Piso	Colisión	192.168.3.128	255.255.255.224	192.168.3.129 - 192.168.3.158	192.168.3.159	60
Piso	Alistamiento	192.168.3.160	255.255.255.240	192.168.3.161 - 192.168.3.174	192.168.3.175	70
Edificio	Telefonía ip	192.168.4.0	255.255.255.128	192.168.4.1 
- 192.168.4.126	192.168.4.127	80
Edificio	Red invitados	192.168.5.128	255.255.255.128	192.168.5.129 - 192.168.5.254	192.168.5.255	81

Tabla 11
Tabla de distribución de puertos de Switch.
SWITCH	RANGO PUERTO	AREA		SWITCH	RANGO PUERTO	AREA
SwitchColision	3-14	COLISIÓN		SwitchVitrinas4	14-18	REPUESTOS
SwitchColision	1--2	SWITCH		SwitchVitrinas4	8	SEGURO
SwitchColision	15-24	LIBRE		SwitchVitrinas4	9-13	FACTURA
SwitchPosventa2	5-16	POSVENTA		SwitchVitrinas4	5--7	CAJA
SwitchPosventa2	1--4	SWITCH		SwitchVitrinas4	1--3	SWITCH
SwitchPosventa2	17-24	LIBRE		SwitchVitrinas4	24	LIBRE
SwitchAdministracion	10-13	CONTABILIDAD		SwitchVitrinas4	4	USADO
SwitchAdministracion	4--5	ADMINISTRACIÓN		SwitchVitrinas3	1--3	SWITCH
SwitchAdministracion	6--9	GERENCIA		SwitchVitrinas3	16-24	LIBRE
SwitchAdministracion	1--3	SWITCH		SwitchVitrinas3	4-15	FORD
SwitchAdministracion	22-24	SWITCH		SwitchRecepcion	10-18	FORD
SwitchAdministracion	14-21	LIBRE		SwitchRecepcion	4--9	USADO
SwitchAdministracion2	5--7	TESORERÍA		SwitchRecepcion	19	RED INVITADOS
SwitchAdministracion2	8--10	NÓMINA		SwitchRecepcion	1--3	SWITCH
SwitchAdministracion2	11-14	SEGUROS		SwitchRecepcion	19-24	LIBRE
SwitchAdministracion2	15-19	DISEÑO		SwitchSotano	23-24	WIFI
SwitchAdministracion2	20-21	FACTURA		SwitchSotano	19-22	KIA
SwitchAdministracion2	1--3	SWITCH		SwitchSotano	15-18	HYUNDAI
SwitchAdministracion2	22-24	LIBRE		SwitchSotano	10-14	DERCO
SwitchVitrinas2	14-23	HYUNDAI		SwitchSotano	7--9	COLISIÓN
SwitchVitrinas2	8-13	SUZUKI		SwitchSotano	3--6	OTROS
SwitchVitrinas2	5--7	TALLER		SwitchSotano	1--2	SWITCH
SwitchVitrinas2	1--4	SWITCH		SwitchAlistamiento	4--8	ALISTAMIENTO
SwitchVitrinas2	24	LIBRE		SwitchAlistamiento	1--3	SWITCH
SwitchVitrinas	6--21	KIA		SwitchAlistamiento	9-24	LIBRE
SwitchVitrinas	1--5	SWITCH		SwitchPosventa	1--4	SWITCH
SwitchVitrinas	22-24	LIBRE		SwitchPosventa	20-24	LIBRE
SwitchVitrinas4	19-23	DERCO		SwitchPosventa	5-19	POSVENTA

Tabla 12
Tabla de IP asignadas por computador.
COMPUTADOR	IP FIJA		COMPUTADOR	IP FIJA
PC-Logistica	192.168.3.164		PC-Diseño	192.168.2.83
PC-ReptoColisión	192.168.3.130		PC-Diseñador	192.168.2.84
PC-Latoneria	192.168.3.131		PC-Fact.Electronica	192.168.2.98
PC-Laboratorio	192.168.3.132		AsesorFinancieroKia	192.168.1.66
PC-AnalistaPagina	192.168.3.133		FacturacionVehiculos2	192.168.1.242
PC-Técnicos	192.168.3.134		FacturacionVehiculos1	192.168.1.243
PC-MECAESP6	192.168.3.2		Caja	192.168.2.10
PC-MECAESP4	192.168.3.3		AsesorColisionFord	192.168.5.2
PC-Garantias	192.168.3.4		AsesorServicioFord1	192.168.5.3
PC-MECAESP5	192.168.3.5		AsesorServicioFord3	192.168.5.4
PC-Calidad	192.168.3.6		AsesorServicioFord2	192.168.5.5
PC-Experiencias	192.168.3.7		AsesorReptoMostrador	192.168.2.18
PC-ReptoColisiónFord	192.168.3.8		JefeRepuestosSas	192.168.1.146
PC-ReptoTaller	192.168.3.9		AsesorRepuestosSas	192.168.1.147
PC-MECAESP2	192.168.3.10		CallcenterDerco-Hyundai	192.168.0.146
PC-MECAESP3	192.168.3.11		AsesorServicioHyundai	192.168.0.147
PC-MECANICAESP1	192.168.3.12		AsesorServicioKia	192.168.0.130
PC-ALINEACION2	192.168.3.13		CallcenterKia	192.168.0.131
PC-MECANICA2	192.168.3.14		GarantiasDerco	192.168.5.66
PC-MECANICA1	192.168.3.15		AsesorServicioDerco	192.168.5.67
PC-ALINEACION 1	192.168.3.16		AsesorColisiónSas	192.168.0.170
PC-Callcenter	192.168.3.17		AsesorSotanoReptos	192.168.0.178
PC-Auxiliar	192.168.3.18		Clientes	192.168.0.179
FacturaciónTaller	192.168.2.2		AlineaciónSotano	192.168.0.180
PC-Cartera2	192.168.5.82		PC-AsisGerencia	192.168.2.114
PC-Cartera1	192.168.5.83		Equipo-Contadora	192.168.2.34
Equipo-Tesoreria	192.168.5.84		Equipo-AuxContable	192.168.2.35
PC-Nomina	192.168.2.58		Servidor	192.168.5.97
Equipo-AuxSeguros	192.168.2.66		AIO-GarantiasKia	192.168.1.67
Equipo-ContadoraSeguros	192.168.2.67		PC-Técnicos	192.168.3.134
PC-AudioVisual	192.168.2.82			


3.2.3.5.3.Diagrama que representa la configuración física
Como anteriormente se mencionó, los puestos que se van a asignar son en total 20 puestos distribuidos entre administración, técnicos tanto de taller posventa como de taller de colisión, también se podrá encontrar un área designada en la parte de vitrina para la parte comercial. A continuación, se evidencia los nuevos planos, siempre manteniendo el espacio de trabajo limitado para que cada usuario tenga el espacio adecuado de trabajo. Para mejor identificación se delimite el área marcada de color rojo.
Ilustración 52
Diagrama Físico ubicación Colisión Central Motor con implementación de escalabilidad

            

Ilustración 53 
Diagrama Físico ubicación Sótano Central Motor con implementación de escalabilidad

Ilustración 54 
Diagrama Físico ubicación Vitrina Central Motor con implementación de escalabilidad

Ilustración 55 
Diagrama Físico ubicación Administración Central Motor con implementación de escalabilidad


3.2.4.Despliegue 
Esta fase se centra en el modelo de simulación de la red según el diseño desarrollado en la fase anterior. Aquí se lleva a cabo la simulación en la herramienta, y se configuran todos los componentes necesarios para garantizar la funcionalidad de la red.
3.2.4.1.Ejecución de la Simulación de la Red Diseñada.
En esta fase, se deben realizar pruebas de las configuraciones de seguridad en un entorno simulado, asegurando que las medidas implementadas funcionan correctamente. Esto incluirá la configuración de medidas de seguridad y la realización de pruebas de penetración y auditoría de seguridad, evaluando la respuesta de la red ante posibles amenazas.
3.2.4.2.Prueba de las Configuraciones de Seguridad Dentro de la Simulación.
Se llevará a cabo una simulación completa de la red diseñada para evaluar su rendimiento, seguridad y escalabilidad. Esto implica la configuración de todos los dispositivos en el simulador y la ejecución de pruebas de carga y estrés en la red, con un análisis detallado del rendimiento, los tiempos de respuesta y la eficiencia de los protocolos de enrutamiento.
3.2.4.3.Entregables.
3.2.4.3.1.Plano con la Disposición de Todos los Dispositivos de Red, Cableado y la Infraestructura Física.
Reorganizar planos en Edraw con los puntos de red y cableados definidos en GNS3



3.2.5.Operación 
En esta fase, se estableció un entorno simulado para poder verificar la funcionalidad y las conexiones correspondientes de la nueva infraestructura antes de una posible implementación futura. El objetivo se enfocó en garantizar que todas las configuraciones de red, protocolos de seguridad y segmentaciones lógicas respondan correctamente a diferentes puntos para dar una red confiable. Se analizó mediante el aplicativo GNS3 para llevar a cabo las pruebas, considerando entornos complejos como VLANs y protocolos de enrutamiento.
3.2.5.1.Implementación del Ambiente de Pruebas. 
El entorno simulado por medio del aplicativo GNS3 y el aplicativo WireShark, es el idóneo para poder entregar un informe completo.
3.2.5.2.Entregables. 
3.2.5.2.1.Informe de las Configuraciones Aplicadas en el Entorno de Pruebas.

3.2.5.2.2. Reporte de Resultados de las Pruebas Realizadas.

3.2.5.2.3.Documento de Cambios Efectuados Durante las Pruebas.



3.2.6.Optimización
Con respecto a esta fase, no se realiza ya que el despliegue no será aplicado físicamente en la empresa, por lo que no se puede evaluar dicha optimización. 

4.Conclusiones


5.Recomendaciones


6.Referencias
About RFCs. (s/f). IETF. Recuperado el 4 de mayo de 2025, de https://www.ietf.org/process/rfcs/
ANDI. (2023). Informe de gestión ANDI 2023—2024. https://indd.adobe.com/view/535e8b86-7fb2-4521-ae2a-72813646c001
AWS. (s/f). ¿Qué es el modelo OSI? — Explicación de las 7 capas del modelo OSI — AWS. Amazon Web Services, Inc. Recuperado el 3 de mayo de 2025, de https://aws.amazon.com/es/what-is/osi-model/
Boson. (2024). Descripción general del bosón NetSim | NetSim Ayuda. https://help.boson.com/netsim/boson-netsim-overview
Central, M. (s/f). Sobre Nosotros. Central Motor Grupo Automotríz. Recuperado el 19 de abril de 2025, de https://centralmotor.com.co/sobre-nosotros/
Cisco. (2024a). Cisco 4000 Series Integrated Services Routers. Cisco. https://www.cisco.com/site/us/en/products/networking/sdwan-routers/4000-series-integrated-services-routers/index.html
Cisco. (2024b). Cisco Catalyst 2960-X Series Switches—Cisco. https://www.cisco.com/c/en/us/support/switches/catalyst-2960-x-series-switches/series.html
Cisco. (2024c). Cisco Packet Tracer. https://www.netacad.com/es/cisco-packet-tracer
Claps, S. M. (2023, marzo 31). Transformación digital: Desafíos y oportunidades para las empresas. Forbes México. https://forbes.com.mx/transformacion-digital-desafios-y-oportunidades-para-las-empresas/
DataBank. (2022). DataBank | Data Center Evolved. https://www.databank.com/
dotmagazine. (2023). How Connectivity is Redefining the Automotive Industry. Dotmagazine – Joining the Dots in the Internet Industry. https://www.dotmagazine.online/issues/the-edge/connectivity-redefining-automotive-industry
EdrawSoft. (2024). Guía del usuario de EdrawMax | Edraw. https://www.edrawsoft.com/es/guide/edrawmax/
Farkas, J., Fedyk, D., Finn, N., Gray, E., Johas Teener, M. D., Parsons, G., Saltsidis, P., & Thaler, P. (2013). IEEE 802.1Q. https://www.ieee802.org/802_tutorials/2013-03/8021-IETF-tutorial-final.pdf
Forouzan, B. A. (2007). Data Communucations and Networking. Mc Graw Hill. https://dpvipracollege.in/wp-content/uploads/2023/01/Data-Communications-and-Networking-By-Behrouz-A.Forouzan.pdf
GNS3 Technologies. (2024). Getting Started with GNS3 | GNS3 Documentation. https://mother.github.io/docs/
González López, É., Herrera Zapata, L. M., Murgueitio Cabrera, J., & Milena Ortiz Laverde, S. (Eds.). (2021). Las TIC y la sociedad digital: Doce años después de la ley. Tomo I & II: Ecosistema digital en sus distintos desarrollos y las tecnologías disruptivas (Primera edición). Universidad Externado de Colombia. https://bdigital.uexternado.edu.co/server/api/core/bitstreams/e3c2b366-7ab6-4246-b431-08b84f89c31a/content
Google LLC. (2024). Formularios de Google: Creador de formularios en línea. Google Workspace. https://workspace.google.com/intl/es-419/products/forms/
Howard. (2023, junio 16). Exploración de los distintos tipos de virtualización en la red del centro de datos | Comunidad FS. Knowledge. https://community.fs.com/es/article/exploring-different-types-of-virtualization-in-data-center-network.html
HPE. (2024). HPE Aruba Networking 2530 Switch Series. PSNow. https://www.hpe.com/psnow/doc/c04111414
ISO. (2017). ISO/IEC 11801. Information technology — Generic cabling for customer premises. https://www.iso.org/obp/ui/en/#iso:std:iso-iec:11801:-1:ed-1:v1:en
Jara Plazas, J., Quintero, J. E., & Ariza, P. A. (2014). PROYECTO PARA EL DISEÑO E IMPLEMENTACIÓN DE UNA RED LAN PARA EL BANCO NACIONAL. https://repository.usta.edu.co/server/api/core/bitstreams/16225375-6028-429a-8bc2-0f22901ae19e/content
Kraemer, B. (2011). IEEE 802.11. https://www.ieee802.org/misc-docs/GlobeCom2009/IEEE_802d11_Kraemer.pdf
Kurose, J. F., & Ross, K. W. (2017). Redes de computadoras. Pearson Educación.
Lammle, T. (2016). CCNA routing and switching complete: Study guide (Second edition). Sybex, a Wiley brand. https://digtvbg.com/files/LINUX/CCNA%20Routing%20and%20Switching%20Complete%20Study%20Guide.%20Exam%20100-105%2C%20Exam%20200-105%2C%20Exam%20200-125%20by%20Todd%20Lammle.pdf
Law, D. (2010). IEEE 802.3 Ethernet. IEEE. https://www.ieee802.org/misc-docs/GlobeCom2009/IEEE_802d3_Law.pdf
Ley 1581 de 2012—Gestor Normativo. (2012). https://www.funcionpublica.gov.co/eva/gestornormativo/norma.php?i=49981
Macrotics. (2025). Router Balanceador de Reyee con 9 Puertos Ethernet—Macrotics / Productos de Telecomunicaciones—Repetidor Wifi. https://www.macrotics.com/router-balanceador-de-reyee-con-9-puertos-ethernet/p
McKinsey & Company. (2021). Personalization & Customer Value Management. http://ceros.mckinsey.com/howitworks-desktop
Microsoft. (2024). Software de diagramación y creación de diagramas de flujo | Microsoft Visio. https://www.microsoft.com/es-co/microsoft-365/visio/flowchart-software
MikroTik. (2024). RB3011UiAS-RM | MikroTik. https://mikrotik.com/product/RB3011UiAS-RM
MikroTik. (2025). RB1100AHx2 | MikroTik. https://mikrotik.com/product/RB1100AHx2
Netgear. (2024). GS724Tv4: Switch Smart Gigabit Ethernet de 24 puertos con 2 puertos SFP. NETGEAR. https://www.netgear.com/es/support/product/gs724tv4/
¿Qué es la latencia? | IBM. (2023, agosto 15). https://www.ibm.com/mx-es/topics/latency
Redundancia de red. (s/f). Capterra. Recuperado el 3 de mayo de 2025, de https://www.capterra.es/glossary/628/network-redundancy?utm_source=chatgpt.com
Sánchez Ortiz, B. G., Camargo Redondo, G. A., & Benavides Monroy, Y. (2022). Diseño De Una Red De Telecomunicaciones Para La Empresa Martin Camargo. https://repository.ucc.edu.co/server/api/core/bitstreams/cbcfa5f1-46e8-4e54-a9e9-2a5296a0ed0e/content
Seguridad 360, R. R. (2023, junio 5). Guía completa de mantenimiento de redes de cableado: Tipos, consideraciones y medidas para optimizar la conectividad - Revista Seguridad 360. https://revistaseguridad360.com/noticias/mantenimiento-de-redes-guia/
Stallings, W. (2014). Data and computer communications (Tenth edition). Pearson. https://nibmehub.com/opac-service/pdf/read/Data%20and%20computer%20communications%20by%20Stallings-%20William-compressed.pdf
Tanenbaum, A. S., & Wetherall, D. J. (2011). Computer Networks (5a ed.). Pearson. https://csc-knu.github.io/sys-prog/books/Andrew%20S.%20Tanenbaum%20-%20Computer%20Networks.pdf
TP-Link. (2024). AX6000 Next-Gen Wi-Fi Router. https://www.tp-link.com/co/home-networking/wifi-router/archer-ax6000/
TP-Link. (2025). Switch Smart Gigabit JetStream de 24 puertos PoE+ y 4 ranuras SFP. https://www.tp-link.com/co/business-networking/omada-switch-access/tl-sg2428p/
Valencia Duque, F. J. (2021). Sistema de gestión de seguridad de la información basado en la familia de normas iso/iec 27000. https://fadmon.unal.edu.co/fileadmin/user_upload/extension/cursos/imagenes_cursos/digitales_septiembre/sistema_de_gestion_de_seguridad-1.pdf
