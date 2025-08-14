# proyecto_9_analisis_negocio

# SHOWZ: ANÁLISIS DE GASTOS DE MARKETING

## RESUMEN DEL PROYECTO
El proyecto se centra en un análisis de los datos de marketing de la empresa de venta de entradas de eventos, Showz. El objetivo es optimizar los gastos de marketing investigando cómo los clientes usan el servicio, cuándo compran, cuánto dinero aportan a la compañía y cuándo se recupera el costo de adquisición.

## OBJETIVO
Proporcionar al equipo de marketing de Showz recomendaciones fundamentadas para optimizar la inversión publicitaria, basándose en métricas clave de rentabilidad y eficiencia para maximizar el retorno de la inversión.

## METODOLOGÍA DE ANÁLISIS

### 1. DESCRIPCIÓN DE LOS DATOS
Se utilizó un conjunto de datos compuesto por tres tablas principales:

- **visits**: Registros de sesiones de los usuarios en el sitio web.
- **orders**: Datos de los pedidos de los clientes.
- **costs**: Estadísticas de gastos de marketing.

### 2. PREPROCESAMIENTO DE DATOS
Se importaron los datos de las tres tablas. Posteriormente, se optimizaron los tipos de datos de las columnas y se realizaron tareas de limpieza para asegurar la precisión y eficiencia del análisis. Las fechas y horas fueron convertidas al formato correcto para permitir el análisis temporal.

### 3. CÁLCULO DE MÉTRICAS Y ANÁLISIS DE DATOS
Se calcularon métricas clave para tres áreas del negocio, segmentadas por día, semana, mes, fuente de origen y dispositivo. Se incluyeron gráficos para visualizar cómo cambian estas métricas a lo largo del tiempo y entre distintas plataformas.

- **Análisis de Visitas**: Se determinaron el número de usuarios por día, semana y mes, el promedio de sesiones por día, la duración de cada sesión y la frecuencia de retorno de los usuarios.
- **Análisis de Ventas**: Se estudiaron cuándo los usuarios realizan su primera compra, el número de pedidos, el tamaño promedio de compra y el valor de vida del cliente (LTV).
- **Análisis de Marketing**: Se analizaron los gastos totales, el costo de adquisición de clientes (CAC) por fuente y la rentabilidad de la inversión (ROMI).

## CONCLUSIONES PRINCIPALES
El análisis de métricas revela una ineficiencia crítica en la asignación del presupuesto de marketing. La empresa invierte la mayor parte de su presupuesto en fuentes que no son rentables, lo que indica un desconocimiento del valor real de las inversiones.

## RECOMENDACIONES

### A. Reducir o Detener Inversión (Prioridad Máxima)
- **Fuente 3**: Reducir drásticamente la inversión o pausar la actividad. Es la principal fuente de pérdidas con un gasto de USD 141.321,63 y un ROMI consistentemente negativo de -61,43%.
- **Fuente 10, 4 y 5**: Revisar y reducir la inversión. A pesar de un CAC bajo, sus ROMIs negativos indican que los clientes no generan suficiente revenue.

### B. Mantener y Aumentar la Inversión
- **Fuente 1 y 2**: Mantener la inversión y explorar oportunidades para aumentarla. A pesar de su CAC alto, sus ROMIs positivos (49,24% y 9,61% respectivamente) demuestran que atraen clientes muy valiosos y rentables.
- **Fuente 9**: Mantener y considerar un ligero aumento. Su bajo CAC (USD 0,85) y ROMI positivo (4,38%) la convierten en un canal sólido y rentable.
- **Fuente 7**: Mantener y comprender su naturaleza. Con un costo de USD 0,00 y ROMI "infinito", es vital entender su mecanismo para asegurar que siga generando ingresos.

### C. Estrategia por Dispositivo
Reorientar el presupuesto: Priorizar la inversión hacia desktop y reevaluar la inversión en touch. Los dispositivos touch son significativamente menos rentables (-56,56% ROMI) que desktop (-10,21% ROMI).

## TECNOLOGÍAS UTILIZADAS
- **Python**: Lenguaje de programación principal.
- **Pandas**: Manipulación y análisis de datos.
- **NumPy**: Cálculos numéricos.
- **Matplotlib y Seaborn**: Visualización de datos para los informes y gráficos.
