# Analisis_Conecctatel-

   Este proyecto nace de la necesidad de transformar datos transaccionales y de uso en decisiones estratégicas. El objetivo principal es identificar patrones de    comportamiento, detectar anomalías y segmentar la base de clientes para optimizar la oferta comercial de la compañía.

   Mediante un proceso riguroso de ETL (Extracción, Transformación y Carga) y Análisis Exploratorio de Datos (EDA), este repositorio busca proporcionar una visión accionable sobre cómo interactúan los diferentes grupos de usuarios con el producto o servicio.

🎯 Objetivos Estratégicos

Identificación de Patrones: Descubrir tendencias de uso recurrentes que definan el "recorrido" del cliente.
Detección de Comportamientos Atípicos: Localizar irregularidades o anomalías que representen riesgos o nichos de oportunidad.
Segmentación de Clientes: Clasificar a los usuarios en grupos con necesidades diferenciadas para personalizar la experiencia.
Optimización Comercial: Generar insights que permitan ajustar la oferta y mejorar el Customer Experience (CX).

🛠️ Fases del Proyecto

Exploración y Limpieza: Auditoría de calidad de datos, manejo de valores nulos y normalización de variables.
Análisis Descriptivo: Creación de métricas clave y visualizaciones para entender el "qué" y el "cuándo" del comportamiento del usuario.     
Segmentación Avanzada:
Uso de técnicas analíticas para diferenciar grupos de usuarios (ej. Clústeres, RFM).    
Conclusiones y Recomendaciones: Traducción de hallazgos técnicos en estrategias de negocio medibles.

🧰 Stack Tecnológico
Lenguajes: Python (Pandas, NumPy, Scikit-learn) / R.
Visualización: Matplotlib, Seaborn o herramientas de BI.
Procesamiento: SQL para la extracción y manipulación de bases de datos.

💡 Impacto Esperado

La finalidad última de este análisis es convertir bases de datos complejas en una visión clara y confiable. Al entender las necesidades específicas de cada segmento, la empresa puede migrar de un modelo generalista a una estrategia centrada en el usuario, maximizando la retención y el valor del cliente.

⚠️ Problemas detectados en los datos Resumen Ejecutivo: Limpieza y análisis de datos (2022-2024)

Calidad y limpieza de datos: Se depuró la base de datos limitando el análisis al periodo 2022-2024, eliminando inconsistencias del año 2026.

Correcciones: Reemplazo de valores en age (mediana) y city (nulos).

Gestión de datos nulos: Se identificaron valores Missing At Random (MAR) en duracion y longitud. Al ser coherentes con el tipo de registro, se conservaron como nulos para evitar sesgos.

🔍 Segmentos por Edad

Usuario y planes

Edad: Distribución uniforme entre 18 y 80 años. La edad no influye en la elección del plan.

Preferencia: El Plan Básico es el más frecuente y contratado en todos los segmentos.

📊 Segmentos por Nivel de Uso Consumo

Distribución similar entre planes; usuarios premium presentan picos aislados de alta actividad.

Tendencia a consumo bajo/moderado con una "cola larga" de usuarios intensivos.

➡️ Esto sugiere que ...

El comportamiento de uso es estructuralmente idéntico entre planes, diferenciándose únicamente por el volumen de usuarios, donde el plan básico es el dominante.

Los datos están listos para modelos predictivos o análisis de valor por cliente.

💡 Recomendaciones Segmentación por uso, no por edad: Dado que la edad no discrimina la elección del plan. En su lugar, enfócarnos en segmentación por comportamiento: crea una oferta para esos usuarios que están en la cola derecha.

Si los usuarios premium se asemejan al básico pero con menor volumen, el plan premium podría no estar ofreciendo un diferenciador claro. Se recomienda analizar, si añadir beneficios específicos (como mayor prioridad de red o herramientas integradas).

Investigar a fondo a los usuarios extremos detectados en los histogramas. Entender quiénes son los que generan el volumen alto permitirá predecir picos de carga en el sistema.

Aunque la edad no influye, la ubicación geográfica o la infraestructura de la ciudad podría ser un factor determinante en la contratación del plan Premium.















