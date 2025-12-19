Análisis de Evasión de Clientes (Churn Analysis)
 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el fenómeno de evasión de clientes (Churn) a partir de un conjunto de datos que contiene información demográfica, contractual y económica de clientes.
El análisis busca identificar patrones, relaciones y factores clave asociados al abandono del servicio, con el fin de generar insights accionables que ayuden a reducir la tasa de churn.

El trabajo fue desarrollado íntegramente en un Jupyter Notebook, utilizando Python y librerías estándar de análisis de datos.

 Objetivos del Análisis

Comprender la proporción total de clientes que abandonan y los que permanecen.

Analizar cómo variables categóricas (género, tipo de contrato, tipo de internet, método de pago) influyen en la evasión.

Estudiar la relación entre variables numéricas (gasto, tiempo de contrato, gasto diario) y el churn.

Identificar perfiles de clientes con mayor riesgo de abandono.

Proponer recomendaciones estratégicas basadas en datos.

 Limpieza y Tratamiento de Datos

Durante el preprocesamiento se realizaron las siguientes tareas:

Importación y exploración inicial del dataset.

Renombrado de columnas para mejorar legibilidad.

Eliminación de valores nulos o vacíos en variables clave.

Conversión de columnas numéricas almacenadas como texto (object) a float64.

Filtrado de registros con valores inválidos (por ejemplo, clientes con 0 meses de contrato).

Creación de variables derivadas, como el gasto diario por cliente.

Validación de duplicados en identificadores de clientes.

 Análisis Exploratorio de Datos (EDA)

El EDA incluyó análisis descriptivos y visualizaciones para comparar clientes que abandonaron vs. no abandonaron el servicio.

Principales análisis realizados:

Proporción total de churn.

Distribución del abandono según:

Género

Tipo de contrato

Tipo de internet (DSL / Fibra óptica)

Dependientes

Comparación de métricas numéricas:

Total gastado

Meses de contrato

Gasto diario promedio

Gráficos utilizados:

Barras

Gráficos comparativos


 Resultado clave:
El 26,5 % de los clientes abandonó el servicio, mientras que el 73,5 % permaneció activo.


Hallazgos relevantes:

El gasto diario presenta una correlación positiva con el churn.

La duración del contrato muestra una relación inversa con la evasión.

Un mayor nivel de vinculación con el servicio reduce la probabilidad de abandono.

 Conclusiones e Insights

Los clientes que abandonan presentan un gasto mensual y diario significativamente más alto.

El gasto diario promedio de los clientes que abandonan es 19,11, frente a 4,82 de quienes permanecen, casi 4 veces superior.

La evasión se concentra en clientes con fibra óptica, lo que podría indicar una brecha entre precio y calidad percibida.

Las variables económicas y contractuales resultan más determinantes que las demográficas.

 Recomendaciones Estratégicas

Revisar la política de precios para clientes con alto gasto mensual.

Implementar acciones de retención temprana para contratos de corta duración.

Evaluar la calidad y experiencia del servicio de fibra óptica.

Desarrollar estrategias de segmentación por riesgo de churn.

Monitorear métricas clave de evasión de manera continua.

🛠️ Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
