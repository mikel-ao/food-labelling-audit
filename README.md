# FoodFacts Project

## Estructura del Proyecto

```text
foodfacts/
├── notebooks/       # Notebooks .ipynb (Preprocesado, Limpieza, Análisis)
├── data/            # Archivos .csv
│   ├── raw/         # Datos originales (FAO, OpenFoodFacts original)
│   └── processed/   # Datos limpios (foods_cleaned_2026.csv)
├── images/          # Gráficos y visualizaciones generadas
└── README.md

# Hipótesis planteadas

### 1. Los productos con etiqueta 'Bio/Organic' no tienen un mejor perfil nutricional que sus equivalentes convencionales

### 2. Los productos con etiqueta 'Bio/Organic' son más procesados y tienen mayor impacto ambiental que sus equivalentes convencionales

### 3. Las marcas blancas tienen un perfil nutricional significativamente mejor que las grandes multinacionales en categorías de conveniencia (Ready-to-eat)

### 4. Los productos de la categoria "Plant-based alternatives" tienen peor perfil nutricional y más sal que los productos cárnicos naturales debido a la necesidad de mejorar su palatabilidad

### 5. El impuesto del azucar de Reino Unido funciona, resultando en menor contenido de azucar que España y Francia en las categorias "bebidas" y "snacks"

### 6. España tiene menor ratio de grasas saturadas que el resto de paises debido al uso de aceites vegetales locales

### 7. El Nutri-Score es un algoritmo cuestionable que premia la baja densidad calórica, pero no penaliza el procesamiento industrial

## Bonus cruzando con datos de producción/importación de la FAO

### 8. Los países con mayor producción de aceites vegetales insaturados tienen productos procesados con un ratio de grasas saturadas notablemente inferior al de países importadores de aceite de palma

### 9. Los países con mayor producción de proteína animal tienen alternativas vegetales más procesadas al intentar imitar texturas cárnicas complejas

### 10. Los países con mayor producción de avena presentan una categoría "cereal_bread" con mayor contenido en fibra debido a la disponibilidad local y menor precio que el trigo o el maíz. 
