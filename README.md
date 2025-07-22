# Challenge-Telecom-X-Latam_ ONE- Oracle Next Education AluraLatam 

Análisis de Clientes que NO permanecen en el servicio de TelecomX LATAM

Este proyecto tiene como objetivo la practica de ETL en Pandas mediante el analizis de los factores que influyen en la el motivo por el cual los clientes de una empresa NO permanecen en el servicio (churn) en una empresa de telecomunicaciones ficticia, TelecomX LATAM. A través de la limpieza, exploración y visualización de los datos, se identifican patrones relevantes y se proponen recomendaciones estratégicas para reducir la fuga de clientes.

Objetivo: 

Identificar qué variables están más asociadas a la no permanencia de los clientes en el servicio, con el fin de apoyar la toma de decisiones que mejoren la retención, bienvenida y el nivel de compromiso del cliente.

Estructura del Proyecto:

La realización de este Proyecto fue en GoogleColab y se utilizaron como base los siguientes archivos, proporcinados por Alura Latam y descargados del siguiente enlace:

TelecomTelecomX_diccionario.md
TelecomX_LATAM.ipynb
TelecomX_Data.json
https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_Data.json

Los cuales al ser trabajados se convirtieron en estos archivos finales:
•	Challenge_TelecomX_LATAM.ipynb: Notebook principal con todo el análisis.
•	README.md.

Limpieza y Tratamiento de Datos:
•	Importación del dataset en formato JSON.
•	Normalización y renombrado de columnas para mayor claridad.
•	Conversión de variables categóricas y binarias.
•	Revisión de valores nulos y duplicados.
•	Creación de nuevas variables como número de servicios contratados y cuenta diaria promedio.

Análisis Exploratorio:
Se realizaron diversos cruces y visualizaciones para responder preguntas clave, como:
•	¿Cuál es la proporción de clientes que se mantienen vs. los que no?
•	¿Influyen la edad, el género o el tipo de contrato en la evasión?
•	¿Cuántos servicios contratan los clientes que abandonan?
•	¿Existe relación entre la forma de pago y la permanencia?
•	¿Cómo se relacionan los cargos mensuales y totales con la evasión?

Análisis de Correlación:
Se utilizó la matriz de correlación de variables numéricas para identificar posibles relaciones que ayuden a predecir la no permanencia, destacando la cantidad de servicios contratados y la cuenta diaria como factores clave.

Conclusiones y Recomendaciones:
•	El tipo de contrato “mes a mes” tiene mayor tasa de evasión.
•	Los clientes con menos servicios contratados tienden a abandonar más fácilmente.
•	El uso de ciertos medios de pago, como cheque electrónico, se relaciona con una mayor fuga.
•	Se recomienda mejorar el proceso de bienvenida y acompañamiento del cliente y desarrollar acciones para aumentar el compromiso mediante servicios adicionales.

Requisitos:

•	Python 3.10+
•	Bibliotecas:
o	pandas
o	plotly express

Autor:
Este proyecto fue realizado como parte de un desafío de ciencia de datos, con un enfoque práctico y analítico sobre el comportamiento de los clientes

