# Predicción de Desechos de Comida en Locales Comerciales

## Trabajo Final Integrador
Diplomatura en Ciencia de Datos y Análisis Avanzado

El proyecto tiene como objetivo predecir la cantidad de desperdicio alimentario y detectar la ocurrencia de desperdicio en locales comerciales mediante técnicas de Machine Learning.

---

## Resultados principales

El modelo Random Forest fue seleccionado como modelo final para la predicción de desperdicio alimentario debido a su mejor desempeño frente a los demás modelos evaluados.

### Métricas del modelo final (conjunto de prueba)

| Métrica | Valor |
|----------|----------|
| R² | 0.88 |
| RMSE | 5.96 |
| MAE | 1.51 |

### Modelo de clasificación

La Regresión Logística mostró una elevada capacidad para detectar la ocurrencia de desperdicio:

| Métrica | Valor |
|----------|----------|
| Accuracy | 0.952 |
| F1 Score | 0.958 |
| ROC AUC | 0.984 |

### Hallazgos principales

- Random Forest fue el modelo con mejor desempeño para la predicción de cantidades desperdiciadas.
- La Regresión Logística mostró una alta capacidad para detectar casos con desperdicio.
- Purchase_Quantity concentró aproximadamente el 80 % de la importancia del modelo.
- Daily_Demand y Storage_Temperature también mostraron una influencia significativa.
- Una mejor planificación de compras e inventario podría contribuir a reducir el desperdicio alimentario y generar beneficios económicos para los comercios.
## Dataset utilizado

Dataset sintético basado en escenarios reales de inventario y ventas de:

- Restaurantes
- Cafeterías
- Supermercados
- Cloud Kitchens

Características:

- 8.000 registros
- 16 variables
- Año 2025
- Fuente: Kaggle

---

## Metodología

El proyecto siguió una metodología inspirada en CRISP-DM:

1. Comprensión del problema de negocio.
2. Exploración y análisis de datos (EDA).
3. Preparación y limpieza de datos.
4. Entrenamiento y comparación de modelos.
5. Evaluación y selección del modelo final.
6. Interpretación de resultados e impacto en el negocio.

---

## Modelos evaluados

- Regresión Lineal
- Random Forest
- Regresión Logística

---

## Estructura del repositorio
```text
TP-Final-Grupo55
├── README.md
├── Entrega_final_grupo55.ipynb
├── food_waste_dataset.csv
└── GRUPO_55-PREDICCIÓN DE DESECHOS DE COMIDA EN LOCALES COMERCIALES.pdf
```

## Ejecución

### Google Colab

1. Abrir `Entrega_final_grupo55.ipynb`.
2. Seleccionar **Entorno de ejecución → Ejecutar todo**.
3. El dataset se descarga automáticamente desde GitHub.
