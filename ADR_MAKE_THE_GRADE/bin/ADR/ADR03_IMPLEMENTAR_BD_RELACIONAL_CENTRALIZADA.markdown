# Titulo
Implementar una base de datos relacional PostgresSQL centralizada 
# Estado
Propuesto

# Contexto 
La base de datos centralizada en el sistema de evaluación estandarizado va a jugar un papel crucial en la gestión de la información de los estudiantes, los datos de las pruebas y los resultados. Por ello es necesario priorizar la recuperación eficiente de datos, la integridad de los datos, las instituciones educativas puedan garantizar la confiabilidad del sistema y proteger la confidencialidad de los datos de los estudiantes. 

# Desición 
Se propone una base de datos relacional PostgresSQL centralizada para almacenar y administrar la información de los usuarios.

# Consecuencias
La decisión de utilizar una base de datos relacional PostgresSQL centralizada tiene las siguientes implicaciones: 

1. Diseñar el esquema de base de datos para almacenar toda la información requerida en un modelo relacional, considerando la normalización y la indexación para optimizar la recuperación de datos. 

2. Implementar mecanismos eficientes de almacenamiento y recuperación de datos, teniendo en cuenta factores como el rendimiento de las consultas y partición de datos. 

3. Recuperación y respaldo de datos: Establecer procedimientos regulares de respaldo y recuperación de datos para garantizar la disponibilidad de los datos y protegerlos contra posibles pérdidas de datos. Realizar copias de seguridad completas, copias de seguridad incrementales y almacenamiento externo. 

4. Seguridad: PostgresSql tiene medidas de seguridad robustas que nos permitien cumplir con los requisitos de seguridad.  

5. Escalabilidad: PostgresSql almacena grandes cantidades de datos con facilidad, permite tambien la fragmentación de la base de datos. 

6. Integración: Garantiza una integración perfecta entre la capa de aplicación y la base de datos, implementando las APIs adecuadas o las capas de acceso a datos para facilitar la manipulación y recuperación de datos. 

7. Mantenibilidad: Establecer procedimientos de mantenimiento de la base de datos, optimización de los índices. 

 




