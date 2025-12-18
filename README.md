# Portafolio
Portafolio ciencia de datos para la economía

## **Predicción del Nivel de PIB utilizando Datos del Banco Mundial**

El objetivo de este proyecto es predecir el nivel de PIB de distintos países a partir de indicadores económicos, sociales y demográficos obtenidos del Banco Mundial.

El trabajo debe realizarse en tres etapas principales:

- Análisis descriptivo e imputación de datos

- Reducción de dimensionalidad con PCA

- Modelación mediante algoritmos de clasificación

### **Etapa 1: Análisis Descriptivo e Imputación de Datos**

**Revisión general del dataset**

- Identificar el número de países, años y variables disponibles.

- Número total de observaciones

- Porcentaje de datos faltantes por variable: En caso que la variable cuente con menos de un 15% de datos NA se recomienda imputar. En caso contrario, eliminar variable.

- Identificación de outliers relevantes


**Indicaciones**:

- Generar una tabla de estadísticas descriptivas: media, mediana, desviación estándar, máximo, mínimo.

- Mostrar la distribución del PIB (histograma o boxplot), ya que es la variable objetivo.

- Mapa con la distribución del PIB
  
###**Etapa 2:***

- Reduccion de dimensionalidad: Buscamos reducir el numero de variables de una base de datos, pero tratando de mantener toda la informacion relevante.
  
- Ecalar datos: Para aplicar PCA es necesario escalar los datos, para evitar que variables con valores grandes dominen el análisis.
  
- Mapa de calor de correlacion.
  
- Aplicacion de PCA: Buscamos reducir la dimensionalidad de un conjunto de datos y, al mismo tiempo, extraer las características más relevantes presentes en las variables numéricas originales.
  
