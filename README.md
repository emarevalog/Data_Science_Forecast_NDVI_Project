## Título: Machine Learning y Eco-hidrología: Pronóstico de la Actividad Vegetal en el Bosque Tropical Seco del Cañón del Río Cauca
### Autores:
- Eileen Melissa Arévalo [@emarevalog](https://github.com/emarevalog)
- Pablo Uribe Uribe [@Blouri](https://github.com/Blouri)
### Grupo: 8


## Exploración y Preprocesamiento de Datos
Este conjunto de códigos realiza la exploración y preprocesamiento de datos utilizando Python en un entorno de Google Colab. El código realiza diversas tareas, desde la carga de datos hasta la estandarización y guardado en un archivo CSV.

### Contenido del Repositorio
- Exploracion_de_Datos.ipynb: Este es el cuaderno de Google Colab que contiene todo el código para la exploración de datos.

- Datos.csv: El conjunto de datos crudos que se utilizará en el análisis

### Instrucciones de Uso
Abre el cuaderno de Google Colab, Exploracion_de_Datos.ipynb, en tu entorno de Google Colab.

Para cargar los datos ve al archivo [Enlace a Datos.csv](https://github.com/emarevalog/Machine_learning_project/blob/main/Datos.csv) y copia la ruta de los datos crudos y pegala en pathfile

Ejecuta cada celda secuencialmente para cargar los datos y realizar análisis.

Examina los histogramas, diagramas de cajas, gráficos de dispersión, gráficos de líneas y la matriz de correlación para comprender las distribuciones y relaciones entre las variables climáticas.

### Descripción del Conjunto de Datos
El conjunto de datos contiene información climática mensual con las siguientes variables. NDVI fue obtenida por procesamiento de imágenes del satélite MODIS, las demás provienen del modelo Soil-Water Balance (SWB)  :

- Mes (1 al 12)
- NDVI
- Precipitación(ml)
- Evapotranspiración (ml) 
- Intercepción (ml)
- Evapotranspiración (ml)
- Humedad_Suelo (ml)
- Recarga (ml)

### Visualizaciones Incluidas

Histogramas: Muestra la distribución de cada variable junto con la curva de mejor ajuste y la línea vertical para la media.

Diagramas de Cajas: Proporciona una representación visual de la distribución estadística, mostrando la mediana, cuartiles y valores atípicos.

Gráficos de Dispersión: Presenta la relación entre el NDVI_Sat y otras variables climáticas.

Gráficos de líneas: Muestra cómo las variables evolucionan a lo largo del año, permiten identificar patrones y tendencias.

Matriz de Correlación: Representa la fuerza y dirección de las relaciones lineales entre las variables.

### Requisitos

-Las bibliotecas de Python utilizadas en el cuaderno deben estar instaladas. Puedes instalarlas utilizando
```bash
  !pip install nombre_de_la_libreria
```
