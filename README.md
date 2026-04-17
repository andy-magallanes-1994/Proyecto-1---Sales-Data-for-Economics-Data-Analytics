# Proyecto-1---Sales-Data-for-Economics-Data-Analytics

# 📊 Análisis de Rentabilidad y Optimización de Precios mediante Machine Learning

Este proyecto desarrolla un ecosistema analítico completo para transformar datos transaccionales de ventas en estrategias accionables de rentabilidad. Utiliza técnicas avanzadas de **Machine Learning (Random Forest Regression)** para predecir el beneficio y simular escenarios de precios dinámicos.

## 🎯 Objetivos del Proyecto
*   **Maximizar la Rentabilidad:** Identificar los factores que más impactan en el margen de beneficio.
*   **Estrategia de Precios Dinámicos:** Simular el impacto de cambios en el precio unitario para encontrar el punto óptimo por segmento.
*   **Personalización de Ofertas:** Diseñar recomendaciones basadas en la sensibilidad al precio y demografía del cliente.

## 🛠️ Stack Tecnológico
*   **Lenguaje:** Python
*   **Bibliotecas Clave:** `Pandas`, `Scikit-Learn`, `Matplotlib`, `Seaborn`.
*   **Algoritmos:** RandomForestRegressor (R² Score: 0.96) vs. Linear Regression.
*   **Procesamiento:** Pipelines de transformación (OneHotEncoding, StandardScaler) y Feature Engineering.

## 📈 Hallazgos Clave (Insights)
1.  **Variable Crítica:** El `Unit Price` es el predictor #1 del beneficio, seguido por la ubicación geográfica (`Country_Germany`).
2.  **Segmentación:** Los clientes en Alemania muestran una menor sensibilidad al precio en comparación con el promedio global, permitiendo márgenes más agresivos.
3.  **Elasticidad del Beneficio:** La relación precio-beneficio es no lineal; subir precios sin una estrategia basada en datos puede resultar en la pérdida del punto óptimo de retorno.

## 🚀 Impacto de Negocio
El modelo permite pasar de una gestión de ventas reactiva a una **proactiva**, proporcionando:
*   **Precios Óptimos:** Recomendaciones específicas de incremento de precios de hasta un 30-40% en categorías como accesorios sin comprometer la estabilidad del beneficio predicho.
*   **Bundling Inteligente:** Creación de paquetes de productos para segmentos de alta sensibilidad (ej. Bikes) para aumentar el ticket promedio mediante financiamiento percibido.

---
*Proyecto desarrollado como parte de un análisis integral de Ciencia de Datos aplicado a la economía empresarial.*
