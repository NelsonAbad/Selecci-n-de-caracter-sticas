# Selección de Características - Vino Tinto

El objetivo es generar un **modelo de regresión lineal múltiple** que contenga solamente las variables seleccionadas mediante un **proceso de selección hacia adelante (forward selection)** y un **proceso de eliminación hacia atrás (backward elimination)**, para predecir la calidad de vinos tintos.

Se trabajó con la base de datos **“A1.4 Vino Tinto.csv”**, que contiene **1,599 observaciones** con **11 variables predictoras** y una variable de salida (calidad). Los datos provienen del [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality) y fueron originalmente reportados en una publicación científica para la revista *Decision Support Systems*.

### Variables de la base de datos:

- **acidezFija**: Gramos de ácido tartárico por decímetro cúbico.  
- **acidezVolatil**: Gramos de ácido acético por decímetro cúbico.  
- **acidoCitrico**: Gramos de ácido cítrico por decímetro cúbico.  
- **azucarResidual**: Gramos de azúcar por decímetro cúbico.  
- **cloruros**: Gramos de cloruro de sodio por decímetro cúbico.  
- **dioxidoAzufreLibre**: Miligramos de dióxido de azufre libre por decímetro cúbico.  
- **dioxidoAzufreTotal**: Miligramos de dióxido de azufre total por decímetro cúbico.  
- **densidad**: Medida en gramos por centímetro cúbico.  
- **pH**: Nivel de pH del vino.  
- **sulfatos**: Gramos de sulfato de potasio por decímetro cúbico.  
- **alcohol**: Volumen porcentual de alcohol en el vino.  
- **calidad**: Mediana de la calidad otorgada por al menos tres catadores (escala de 0 a 10). *(Variable objetivo)*

El objetivo principal de la actividad fue implementar la metodología de selección hacia adelante y hacia atras para identificar el conjunto óptimo de variables predictoras en un modelo de regresión lineal, evaluando su desempeño mediante la métrica R² y utilizando validación cruzada.

[Base de datos](https://github.com/NelsonAbad/Selecci-n-de-caracter-sticas/blob/2904537b32df93a0f226d932f8678373847e9a83/A1.4%20Vino%20Tinto.csv)

[Reporte en .ipynb](https://github.com/NelsonAbad/Selecci-n-de-caracter-sticas/blob/2904537b32df93a0f226d932f8678373847e9a83/A1.4%20Selecci%C3%B3n%20de%20caracter%C3%ADsticas.ipynb)

[Reporte en HTML](A1.4%20Selecci%C3%B3n%20de%20caracter%C3%ADsticas.html)
