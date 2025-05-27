# 🛒 Análisis de embudo y test A/A/B en e-commerce

Proyecto centrado en estudiar el comportamiento del usuario dentro de una app de alimentos, evaluando su progresión a través del embudo de conversión y midiendo el impacto de un rediseño de interfaz.

## 🎯 Objetivo
Identificar etapas de abandono en el embudo de compra y validar, mediante test A/A/B, si un cambio visual afecta el comportamiento del usuario.

## 📊 Herramientas utilizadas
- Python (Pandas, Seaborn)
- Estadística: pruebas U de Mann-Whitney
- Visualización de embudos
- Análisis de cohortes

## 🔎 Análisis realizado
- Limpieza y segmentación por grupos experimentales (ExpId)
- Cálculo de tasas de conversión en cada paso del embudo
- Comparación de grupos A/A y A/B
- Aplicación de ajuste de significancia para evitar falsos positivos

## 🧠 Hallazgos
- La mayor pérdida ocurre al pasar del producto al carrito
- No hay impacto negativo del rediseño en la tasa de conversión
- Se validó la estabilidad de los grupos de control
