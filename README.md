
# Reporte de Prediccion de Evasion de Clientes - Telecom X (Parte 2)

## Descripcion del Proyecto
Este proyecto aborda la fase de modelado predictivo para identificar clientes con alta probabilidad de cancelar sus servicios (Churn) en Telecom X.

## Estructura del Trabajo
1. Preparacion de Datos: Codificacion y normalizacion.
2. Division de Datos: Entrenamiento y prueba (70/30).
3. Entrenamiento: Regresion Logistica y Random Forest.
4. Evaluacion: Analisis de metricas de clasificacion.
5. Importancia de Variables: Identificacion de factores criticos.

## Tecnologias Utilizadas
* Python, Pandas, Scikit-Learn, Matplotlib y Seaborn.

## Resultados de los Modelos
* Regresion Logistica: Mejor desempeño con 79.8% de exactitud y mejor capacidad de deteccion (Recall).
* Random Forest: Mostro alta capacidad pero con señales de sobreajuste (overfitting).

## Analisis de Importancia de Variables
Los factores clave identificados son la antiguedad del cliente, el monto de los cargos mensuales y el uso del servicio de Fibra Optica.

## Conclusiones y Estrategia
Se recomienda focalizar los esfuerzos de retencion en los clientes durante su primer año de servicio y promover metodos de pago automaticos para reducir la friccion detectada en los pagos manuales.
"""

    f.write(readme_content.strip())

print("Archivo README_ML.md creado exitosamente.")
