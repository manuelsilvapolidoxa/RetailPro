RetailPro - Proyecto de Análisis de Datos
Descripción
RetailPro es un proyecto integral de análisis de datos desarrollado durante el curso de Data Analytics. El objetivo es transformar datos comerciales en información útil para la toma de decisiones mediante procesos de ETL, consultas SQL, modelado de datos, DAX y visualización en Power BI.

El proyecto permite analizar ventas, clientes, productos y categorías para identificar patrones de comportamiento, oportunidades de crecimiento y métricas clave de desempeño.

Objetivos del Proyecto
Analizar el comportamiento de las ventas.
Evaluar el rendimiento de productos y categorías.
Identificar tendencias temporales.
Construir dashboards ejecutivos para la toma de decisiones.
Aplicar buenas prácticas de modelado y documentación.
Tecnologías Utilizadas
PostgreSQL
SQL
Power BI Desktop
Power Query
DAX
GitHub
Inteligencia Artificial (ChatGPT / Copilot)
Estructura del Proyecto
RetailPro
│
├── SQL/
│   ├── consultas_analiticas.sql
│   ├── joins.sql
│   └── reportes.sql
│
├── PowerBI/
│   ├── Silva_Manuel_Checkpoint2.pbix
│   └── Dashboard_RetailPro.pbix
│
├── Documentacion/
│   ├── Checkpoint1.pdf
│   ├── Checkpoint2.pdf
│   └── IA_en_el_flujo_del_proyecto.pdf
│
└── README.md
Consultas Principales
Vista Base del Proyecto
Integra ventas, clientes, productos y categorías mediante INNER JOIN para generar una vista consolidada para el análisis.

Resumen Ejecutivo Mensual
Calcula:

Total facturado.
Cantidad de pedidos.
Ticket promedio.
Ranking de Productos
Genera un Top 5 de productos según facturación total.

Modelo Analítico
El modelo implementado en Power BI incluye:

Tabla de Hechos
Fact_Ventas
Tablas de Dimensión
Dim_Clientes
Dim_Productos
Dim_Categorias
Dim_Fechas
Medidas DAX
Total Ventas
Ventas Online
Ventas YTD
Ventas LY
% Crecimiento Anual
Cómo Ejecutar el Proyecto
SQL
Crear la base de datos RetailPro.
Importar las tablas de clientes, productos, categorías y ventas.
Ejecutar los scripts SQL incluidos en la carpeta correspondiente.
Power BI
Abrir el archivo .pbix.
Actualizar las fuentes de datos si es necesario.
Verificar relaciones y medidas DAX.
Explorar los dashboards y reportes.
Autor
Manuel Silva

Proyecto desarrollado como parte del programa de formación en Data Analytics.
