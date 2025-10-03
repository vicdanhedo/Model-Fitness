Proyecto: Predicción de Cancelación de Clientes – Model Fitness
Resumen del Proyecto

Se desarrolló un modelo analítico para predecir la probabilidad de cancelación de clientes de la cadena de gimnasios Model Fitness. El proyecto también incluye segmentación de clientes mediante clustering para identificar perfiles típicos y analizar los factores que más impactan la pérdida de usuarios.

Contexto de Negocio

La empresa enfrenta un desafío común en la industria del fitness: la pérdida de clientes. No siempre es evidente cuándo un cliente se ha ido, y la cancelación temprana puede afectar los ingresos y la planificación de recursos. Este proyecto permite identificar clientes en riesgo y generar estrategias de retención basadas en datos.

Metodología y Enfoque

Recolección de Datos: obtención de información sobre clientes, registros de visitas, compras y estado de la membresía.

Análisis Exploratorio de Datos (EDA): limpieza de datos, detección de valores ausentes, análisis de medias y desviaciones, histogramas y matriz de correlación.

Modelado Predictivo:

División de los datos en entrenamiento y validación.

Entrenamiento de modelos de clasificación binaria: regresión logística y Random Forest.

Evaluación mediante exactitud, precisión y recall.

Segmentación de Clientes (Clustering):

Estandarización de características.

Análisis jerárquico para estimar número de clústeres.

Entrenamiento de modelo K-means con n=5 clústeres.

Interpretación de perfiles y cálculo de tasa de cancelación por clúster.

Conclusiones y Recomendaciones: análisis de factores que impactan la pérdida de clientes y elaboración de estrategias de retención.

Tecnologías Utilizadas

Python, Pandas, Scikit-learn, Matplotlib, Seaborn

Resultados y Valor de Negocio

Se identificaron patrones clave de cancelación según frecuencia de visitas, antigüedad y tipo de contrato.

Modelos predictivos confiables que permiten anticipar clientes en riesgo de pérdida.

Segmentación de clientes en 5 perfiles, cada uno con características distintas y diferentes tasas de cancelación.

Insights útiles para diseñar campañas de retención y priorizar la atención a clientes vulnerables.

Impacto Comercial

Optimización de la estrategia de retención mediante comunicación personalizada y promociones específicas.

Posibilidad de reducir la tasa de cancelación y aumentar la fidelidad de los clientes.

Mejora en la planificación de recursos y estrategias de marketing basadas en datos objetivos.
