📊 Análisis Comparativo de Tiendas
📝 Descripción

Este proyecto analiza las ventas de cuatro tiendas de un mismo grupo con el objetivo de proporcionar información estratégica para la toma de decisiones del señor Juan.

Se evaluaron cinco aspectos fundamentales:

Facturación total de cada tienda: identificar cuál tienda genera más ingresos.

Categorías más populares de cada tienda: conocer qué productos tienen mayor demanda.

Promedio de evaluación de los clientes: medir la satisfacción general.

Productos más y menos vendidos: determinar tendencias de venta y ajustar inventario.

Costo promedio de envío: evaluar eficiencia logística de cada tienda.

📂 Archivos de Datos

Los análisis se realizaron sobre los siguientes archivos CSV:

tienda_1.csv

tienda_2.csv

tienda_3.csv

tienda_4.csv

Cada archivo contiene información de:

Productos vendidos

Categorías

Clientes

Evaluaciones

Costos de envío

🛠 Tecnologías y Librerías

Python 3.x

Pandas: manipulación y análisis de datos

Matplotlib / Seaborn: visualización de resultados

⚙ Estructura del Código

Carga de datos
Los cuatro CSV se importan en variables: tienda, tienda2, tienda3, tienda4.

Análisis por tienda

Facturación total: precio_unitario * cantidad

Categorías más populares: agrupación por categoria y suma de cantidades

Promedio de evaluación de clientes: agrupación por id_cliente y cálculo de la media

Productos más y menos vendidos: agrupación por producto y ordenamiento de ventas

Costo promedio de envío: cálculo del promedio de la columna costo_envio

Ranking de rentabilidad
Comparación de facturación total de cada tienda para identificar la más y la menos rentable.

📈 Resultados Visuales
1. Facturación Total

Se genera un gráfico de barras mostrando facturación de cada tienda:

Tienda 1 ───── $X
Tienda 2 ───── $Y
Tienda 3 ───── $Z
Tienda 4 ───── $W

2. Categorías Más Populares

Tablas con top 5 categorías por tienda:

Tienda	Categoría	Cantidad Vendida
1	CatA	500
1	CatB	420
…	…	…
3. Promedio de Evaluación por Cliente

Tablas con promedio de puntuación:

Tienda	Cliente	Promedio Evaluación
1	C123	4.7
1	C456	4.5
4. Productos Más y Menos Vendidos

Top y bottom products por tienda:

Tienda	Producto Más Vendido	Cantidad	Producto Menos Vendido	Cantidad
1	ProdA	300	ProdB	2
5. Costo Promedio de Envío

Tablas o gráficos de costo promedio:

Tienda	Costo Promedio Envío
1	$15.50
🏆 Conclusiones

Identificar la tienda más rentable y la menos rentable según facturación total.

Determinar qué categorías y productos priorizar en cada tienda.

Analizar satisfacción del cliente mediante promedio de evaluaciones.

Evaluar eficiencia logística a través del costo promedio de envío.

Este informe permite a Juan tomar decisiones estratégicas fundamentadas sobre:

Optimización de inventario

Prioridad de tiendas más rentables

Mejoras en logística y servicio al cliente
