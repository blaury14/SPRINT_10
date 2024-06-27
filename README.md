# SPRINT 10: Análisis del Mercado de Restaurantes para Innovación con Robots

## Descripción del Proyecto

En este proyecto, realizamos un análisis exhaustivo del mercado de restaurantes en Los Ángeles para identificar oportunidades estratégicas para introducir robots en la industria. Este análisis incluye la identificación de los tipos de establecimientos, su distribución, tamaños y ubicaciones, así como recomendaciones basadas en los datos obtenidos.

## Objetivos del Proyecto

- Identificar las proporciones de diferentes tipos de establecimientos en Los Ángeles.
- Analizar la distribución geográfica de estos establecimientos.
- Evaluar el tamaño de los establecimientos en términos de capacidad de asientos.
- Proveer recomendaciones estratégicas para la ubicación y tamaño óptimos para introducir robots en restaurantes.

## Pasos Realizados en el Proyecto

### Paso 1: Descarga y Preparación de los Datos

- **Archivos de Datos:**
  - `/datasets/rest_data.csv`: Datos sobre los establecimientos de comida en Los Ángeles.

- **Preparación de Datos:**
  - Cargamos los datos en DataFrames de pandas.
  - Revisamos y optimizamos los tipos de datos.
  - Filtramos y limpiamos los datos para análisis posteriores.

### Paso 2: Análisis de Tipos de Establecimientos

- **Métricas Calculadas:**
  - Proporción de diferentes tipos de establecimientos (restaurantes, cafés, pizzerías, etc.).
  - Generación de gráficos de barras y torta para visualizar las proporciones.

- **Resultados:**
  - Los restaurantes constituyen el tipo de establecimiento más común, seguido por cafés y pizzerías.

### Paso 3: Análisis de la Distribución Geográfica

- **Métricas Calculadas:**
  - Identificación de las principales calles con mayor concentración de establecimientos.
  - Análisis de la distribución geográfica y visualización en gráficos de barras.

- **Resultados:**
  - W Sunset Blvd y W Pico Blvd son las calles con la mayor concentración de establecimientos.

### Paso 4: Análisis del Tamaño de los Establecimientos

- **Métricas Calculadas:**
  - Número de asientos en diferentes establecimientos.
  - Medianas y rangos intercuartílicos (IQR) para el tamaño de los establecimientos.

- **Resultados:**
  - La mayoría de los establecimientos tienen menos de 50 asientos. Wilshire Blvd muestra una mayor dispersión en el tamaño de los restaurantes.

### Paso 5: Proporciones de Establecimientos que Pertenecen a una Cadena

- **Métricas Calculadas:**
  - Proporción de establecimientos que son parte de una cadena versus independientes.
  - Visualización en gráficos de torta.

- **Resultados:**
  - Un análisis de las proporciones mostró que una gran parte de los establecimientos son independientes, con una menor proporción de cadenas.

### Conclusiones y Recomendaciones

- **Ubicación Estratégica:**
  - W Sunset Blvd y W Pico Blvd son buenas opciones debido a la alta concentración de restaurantes.
  - Wilshire Blvd es una alternativa debido a la diversidad en el tamaño de los establecimientos.
  
- **Tamaño del Establecimiento:**
  - Un establecimiento de tamaño mediano podría ser ideal, especialmente si se ofrece una propuesta única como un café atendido por robots.
  
- **Desarrollo de Cadena:**
  - La expansión como una cadena de restaurantes podría ser viable comenzando con un establecimiento exitoso en una calle popular.

## Presentación

- [Descargar Presentación Aquí](https://drive.google.com/file/d/1H6WiAk2HO-Q2jD9t0Z8LZiKYcnN4X2IA/view?usp=sharing)

## Contribución

Si deseas contribuir a este proyecto, realiza un fork del repositorio y crea una pull request con tus mejoras. Asegúrate de que tu código sigue los lineamientos del proyecto y está bien comentado.

## Licencia

Este proyecto está bajo la licencia MIT. Para más detalles, consulta el archivo LICENSE.
