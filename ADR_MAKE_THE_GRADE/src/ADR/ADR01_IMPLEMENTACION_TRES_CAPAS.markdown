# Titulo
Arquitectura Web de tres capas para un sistema de evaluación estandarizado escalable.

# Estado
Propuesto

# Contexto 
Se tiene la necesidad de diseñar un sistema de evaluación estandarizado escalable que pueda manejar una gran cantidad de usuarios y garantizar un rendimiento eficiente. El sistema requiere una arquitectura web. Entre las consideraciones que se tomarón en cuenta están: 

1. Disponibilidad: El sistema debe adaptarse a un gran volumen de usuarios y manejar actividades simultáneas, optimizando el rendimiento para ofrecer una experiencia de usuario fluida y receptiva.

2. Escalabilidad: Implementar la capa de presentación, aplicación y datos para separar las necesidades y facilitar la escalabilidad. 

4. Accesibilidad: El sistema estará basado en la web para garantizar la accesibilidad entre dispositivos y plataformas. 

5. Modularidad: la arquitectura de tres capas nos permite el desarrollo y mantenimiento independientes de cada capa, lo que facilita la modularidad y la reutilización del código. 

6. Seguridad: debe incorporar medidas de seguridad adecuadas para proteger los datos confidenciales de los usuarios. 

# Desición
Adoptar una arquitectura basada en web de tres capas para el sistema escalable de evaluación estandarizada. 

# Consecuencias
La decisión de adoptar una arquitectura basada en web de tres niveles para el sistema tiene las siguientes implicaciones: 

1. Capa de FrontEnd: Desarrollar una interfaz web (React) que sea fácil de usar, que permita a cada uno de los usuarios interactuar con el sistema, implementando mecanismos de autentificación seguros para controlar los accesos a la información confidencial de los usuarios. 

2. Capa de BackEnd: Desarrollar la capa lógica de negocio (SprintBoot) para desplegarla sobre un servidor de aplicaciones Wildfly, Esta capa será la encargada del procesamiento de solicitudes de prueba, la consolidación de resultados, la generación de informes y la calificación manual.  Garantizando la protección de la información por medio de autentificación SSO (KeyCloack) que firme los tokens de cada servicio antes de darnos una respuesta

3. Capa de Base Datos: Elaborar un esquema de base de datos (PostgreSQL) escalable y eficiente para almacenar información de los estudiantes, datos de pruebas y resultados.  Implementando adecuadas formas de indexación y partición para respaldar la recuperación de datos rápidos y confiables. 

4. Escalabilidad y rendimiento: Implementar medidas de balanceo de carga, almacenamiento en caché y la optimización de la base de datos para soportar grandes cargas de usuarios simultáneos.  Se realizará pruebas de carga y medición de la capacidad de respuesta para garantizar que el sistema pueda escalar con el tiempo de manera efectiva. 

5. Seguridad: Incorporar medidas de seguridad en cada capa para proteger los datos de los usuarios implementando cifrado, controles de acceso y prácticas de codificación segura para minimizar los riesgos de seguridad. 

6. Modularidad y reutilización de código: Desarrollar componentes modulares que se puedan probar y mantener de forma independiente.  Buscando la reutilización de código para reducir los tiempos de mantenimiento. 





