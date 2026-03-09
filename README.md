# **Telecom X: Análisis de Evasión de Clientes (Churn) 🚀**

Este proyecto forma parte del Challenge de Ciencia de Datos del programa Oracle Next Education (ONE). El objetivo principal es identificar los factores críticos que influyen en la pérdida de clientes de una empresa de telecomunicaciones y proponer estrategias basadas en datos para mejorar la retención.

📌 **Escenario del Proyecto**
Telecom X enfrenta una alta tasa de cancelaciones. Como analista de datos, mi misión fue procesar un dataset complejo en formato JSON, realizar una limpieza profunda (ETL) y ejecutar un Análisis Exploratorio de Datos (EDA) para extraer "insights" estratégicos.

🛠️ **Tecnologías Utilizadas**
Lenguaje: Python 3.x

Entorno: Google Colab

Librerías principales:

Pandas: Manipulación y limpieza de datos.

Seaborn & Matplotlib: Visualización de datos estadística.

Requests & JSON: Consumo de datos desde API/GitHub.

⚙️ Proceso de Desarrollo (ETL)
1. Extracción (Extract)
Los datos se obtuvieron directamente de una fuente remota en formato JSON. Se utilizó la técnica de aplanamiento (flattening) para convertir estructuras anidadas en un DataFrame bidimensional listo para el análisis.

2. Transformación (Transform)
Limpieza: Manejo de valores nulos y duplicados.

Casting: Conversión de tipos de datos (strings a floats para cargos mensuales).

Ingeniería de Características: Creación de la métrica Cuentas_Diarias para entender el impacto económico por día en el usuario.

Estandarización: Renombrado de columnas para mejorar la legibilidad y compatibilidad con herramientas de visualización.

3. Análisis y Carga (Analysis & Load)
Se generaron visualizaciones clave para responder preguntas de negocio:

¿Cómo influye el tipo de contrato en la evasión?

¿Hay una relación entre los cargos mensuales elevados y el Churn?

¿Qué perfil de cliente es más propenso a retirarse?

📊 Hallazgos Principales (Insights)
El "Efecto Contrato": Los clientes con contratos mes a mes representan el mayor riesgo de fuga.

Umbral de Precio: Los clientes que abandonan suelen tener cargos mensuales significativamente superiores a la media de los clientes leales.

Oportunidad en Pagos: Existe una correlación positiva entre la retención y los métodos de pago automáticos.

🚀 Conclusiones y Recomendaciones
Fomentar la lealtad: Incentivar la migración de contratos mensuales a anuales mediante beneficios exclusivos.

Revisión de Precios: Monitorear a los usuarios con facturación alta para ofrecerles planes personalizados antes de que decidan cancelar.

Optimización de Facturación: Reducir la fricción en los pagos promoviendo el débito automático.

📁 Estructura del Repositorio
telecomx_churn_analysis.ipynb: Notebook principal con todo el código y análisis.

TelecomX_Data.json: (Opcional, si lo descargaste) Dataset original.

README.md: Documentación del proyecto.

👤 Autor
Jean Christian Rodriguez Cespedes
https://www.linkedin.com/in/jean-christian-rodriguez-cespedes/
