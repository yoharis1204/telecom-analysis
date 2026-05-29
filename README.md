# telecom-analysis - Sprint 6

🎯 **Objetivo del proyecto**

El objetivo de este proyecto es analizar el comportamiento de los usuarios de ConnectaTel a partir de sus patrones de uso de llamadas y mensajes, con el fin de identificar segmentos de clientes, detectar comportamientos atípicos y generar insights que apoyen la toma de decisiones estratégicas en retención, fidelización y crecimiento de usuarios.

📁 **Datasets utilizados**

Se utilizaron los siguientes conjuntos de datos:

plans.csv: Catálogo de planes con sus precios y beneficios. 

users_latam.csv: Información de cada usuario (datos personales, plan, fecha de registro, churn). 

usage.csv: Actividad generada por los usuarios: llamadas, mensajes, duración, longitud. 

🔍 **Flujo del análisis**

El proyecto se desarrolló siguiendo el siguiente flujo estructurado:

**Carga y exploración de datos**

Se cargaron los datasets y se revisaron tipos de datos y estructura general para entender la información disponible.

**Identificación de problemas de calidad**

Se detectaron valores nulos, centinelas y fechas fuera de rango, generando una lista priorizada de problemas que podrían afectar el análisis.

**Limpieza de datos**

Se reemplazaron valores centinela, se corrigieron formatos de fecha y se aplicaron reglas para manejar valores faltantes.

**Estadística descriptiva (summary statistics)**

Se analizaron medidas como media, mediana y percentiles para entender el comportamiento típico y extremo de las variables.

**Visualización y detección de outliers**

Se utilizaron histogramas y boxplots para identificar sesgos, patrones de uso y valores atípicos.

**Segmentación de clientes**

Se crearon segmentos basados en edad y nivel de uso, y se analizaron sus proporciones mediante gráficos.

**Insights ejecutivos**

Se elaboraron conclusiones y recomendaciones orientadas a decisiones de negocio.

**Publicación del proyecto**

Se preparó el notebook y el README para su publicación en GitHub, garantizando reproducibilidad.


▶️ Cómo ejecutar el notebook

El notebook puede ejecutarse fácilmente en Google Colab, sin necesidad de instalar software adicional en el equipo. Para ello, siga estos pasos:

Acceda a Google Colab en el siguiente enlace: https://colab.research.google.com/

Seleccione la opción “File” → “Upload notebook”.

Cargue el archivo del proyecto en formato .ipynb.

Ejecute las celdas en orden, desde la carga de datos hasta la sección de conclusiones.


🔁 Guía de reproducción

Para reproducir el análisis:

Asegúrese de tener los datasets (plans, users_latam, usage) disponibles.

Ejecutar el notebook de forma secuencial sin omitir celdas.
Verificar la instalación de librerías (pandas, numpy, matplotlib, seaborn).
Mantener consistencia en los nombres de variables y columnas.
