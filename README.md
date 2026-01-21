# Model-Fitness-An-lisis-de-Retenci-n-con-Machine-Learning
Clasificación Binaria (Churn) y Segmentación (Clustering K-Means)

##🏋️ Contexto del Proyecto
La cadena de gimnasios Model Fitness se enfrenta al reto de la pérdida de clientes (churn). Este proyecto utiliza datos analíticos para predecir la probabilidad de cancelación para el próximo mes y segmentar a los usuarios en grupos específicos, permitiendo diseñar estrategias de retención basadas en evidencia científica de datos.

##📊 Objetivos Estratégicos
Predicción de Churn: Entrenamiento de modelos de Regresión Logística y Random Forest para predecir la marcha de usuarios.

Segmentación de Clientes: Identificación de clústeres de usuarios mediante aprendizaje no supervisado (K-Means).

Factores de Retención: Análisis de variables críticas como la duración del contrato y la participación en actividades grupales.

##🛠️ Stack Tecnológico
Lenguaje: Python.

Librerías de ML: Scikit-learn (Logistic Regression, Random Forest, K-Means).

Análisis & Visualización: Pandas, Matplotlib, Seaborn (Mapas de calor y Dendrogramas).

##📈 Hallazgos Clave
Precisión del Modelo: Comparativa de modelos donde Random Forest/Regresión Logística permitieron identificar el riesgo de cancelación con métricas de Exactitud, Precisión y Recall.

Dendrograma y Clústeres: Se determinó un número óptimo de 5 clústeres para segmentar a los clientes según su comportamiento.

Perfil de Riesgo: Los usuarios con contratos mensuales y nula asistencia a clases grupales tienen la tasa de abandono más alta.

##🚀 Estrategias Recomendadas
Fomento de la Comunidad: Incentivar las sesiones grupales para los grupos con alta probabilidad de pérdida.

Incentivos de Contrato: Ofrecer promociones para migrar a clientes de contratos de 1 mes a planes de 6 o 12 meses.

Alertas Tempranas: Implementar el modelo de predicción para detectar bajas en la frecuencia de visitas semanal antes de que ocurra la cancelación definitiva.
