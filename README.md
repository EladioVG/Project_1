# Análisis de Planes Prepago de Telecomunicaciones

## Objetivo del Proyecto

Determinar cuál de los planes prepago, **Surf** o **Ultimate**, genera mayores ingresos para la empresa con el fin de apoyar la toma de decisiones comerciales y la asignación eficiente del presupuesto publicitario.

## Contexto de Negocio

Se analizó una muestra de 500 clientes de una empresa de telecomunicaciones durante el año 2018. El estudio considera información sobre llamadas, mensajes SMS, consumo de datos móviles, plan contratado y comportamiento mensual de los usuarios.

## Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Metodología

* Carga y validación de datasets.
* Revisión y corrección de tipos de datos.
* Detección de valores faltantes, inconsistencias y duplicados.
* Limpieza y transformación de datos.
* Integración de múltiples tablas mediante `user_id`.
* Cálculo de consumo mensual por cliente.
* Estimación de ingresos por usuario según las condiciones de cada plan.
* Análisis exploratorio de datos (EDA).
* Comparación de métricas entre planes.
* Aplicación de pruebas estadísticas para validar hipótesis.

## Datasets Utilizados

* `megaline_calls.csv`
* `megaline_internet.csv`
* `megaline_messages.csv`
* `megaline_plans.csv`
* `megaline_users.csv`

## Preguntas de Negocio

* ¿Cuál de los planes genera mayores ingresos promedio?
* ¿Cómo difieren los patrones de consumo entre los usuarios de cada plan?
* ¿Existen diferencias estadísticamente significativas entre los ingresos de ambos planes?
* ¿Qué impacto tienen los cargos por excedentes en la rentabilidad de cada plan?

## Competencias Demostradas

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Integración de datos relacionales
* Análisis estadístico
* Pruebas de hipótesis
* Visualización de datos
* Storytelling con datos
* Pensamiento analítico
* Interpretación de métricas de negocio

## Resultados

El análisis realizado permite concluir que el servicio de telefonía e internet presenta una evolución positiva a lo largo del período analizado, reflejando una buena aceptación por parte de los usuarios. Asimismo, el estudio permitió identificar patrones relevantes mediante el análisis exploratorio, la visualización de datos y las pruebas estadísticas aplicadas.

Uno de los principales hallazgos es que la región NY-NJ concentra la mayor cantidad de clientes y, en consecuencia, genera la mayor parte de los ingresos de la empresa. Este comportamiento fue respaldado por el análisis estadístico realizado.

Respecto a los planes ofrecidos, se observa que Surf es el plan con mayor aceptación entre los usuarios, lo que se traduce en un mayor número de suscriptores y en una mayor recaudación total para la empresa. Por otro lado, el plan Ultimate cuenta con una menor cantidad de clientes, aunque sus usuarios realizan un pago promedio más alto.

Los resultados sugieren que el plan Surf representa una alternativa más atractiva para la mayoría de los clientes debido a su menor costo mensual. Aun cuando ofrece límites inferiores de minutos, mensajes e internet en comparación con Ultimate, el análisis indica que estos beneficios adicionales no son aprovechados por una parte importante de los usuarios, lo que podría explicar la mayor preferencia por el plan Surf.

En conjunto, las gráficas, el análisis exploratorio y las pruebas estadísticas respaldan la existencia de diferencias significativas en el comportamiento de los usuarios y en los ingresos generados por cada plan. Estos hallazgos pueden servir como base para futuras decisiones relacionadas con la estrategia comercial y la optimización de la oferta de planes de la empresa.

