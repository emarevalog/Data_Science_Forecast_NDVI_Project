## Título: Machine Learning y Eco-hidrología: Pronóstico de la Actividad Vegetal en el Bosque Tropical Seco del Cañón del Río Cauca
### Autores:
- Eileen Melissa Arévalo [@emarevalog](https://github.com/emarevalog)
- Pablo Uribe Uribe [@Blouri](https://github.com/Blouri)
### Grupo: 8


## Exploración de Datos - Análisis de Variables Climáticas
Este conjunto de códigos en Google Colab realiza una exploración exhaustiva de datos climáticos utilizando diversas técnicas de visualización y análisis estadístico. El código utiliza el lenguaje de programación Python y las bibliotecas populares como Pandas, Matplotlib, Seaborn y SciPy.

### Contenido del Repositorio
- Exploracion_de_Datos.ipynb: Este es el cuaderno de Google Colab que contiene todo el código para la exploración de datos.

- Datos.csv: El conjunto de datos utilizado en el análisis. Este archivo debe mantenerse en la misma carpeta que el cuaderno de Google Colab.

### Instrucciones de Uso
Abre el cuaderno de Google Colab, Exploracion_de_Datos.ipynb, en tu entorno de Google Colab.

Ejecuta cada celda secuencialmente para cargar los datos y realizar análisis.

Examina los histogramas, diagramas de cajas, gráficos de dispersión y la matriz de correlación para comprender las distribuciones y relaciones entre las variables climáticas.

### Descripción del Conjunto de Datos
El conjunto de datos contiene información climática mensual con las siguientes variables. NDVI fue obtenida por procesamiento de imágenes del satélite MODIS, las demás provienen del modelo Soil-Water Balance (SWB)  :

- Mes (1 al 12)
- NDVI
- Precipitación(mm)
- Evapotranspiración (mm) 
- Intercepción (mm)
- Evapotranspiración (mm)
- Humedad_Suelo (mm)
- Recarga (mm)

### Visualizaciones Incluidas

Histogramas: Muestra la distribución de cada variable junto con la curva de mejor ajuste y la línea vertical para la media.

Diagramas de Cajas: Proporciona una representación visual de la distribución estadística, mostrando la mediana, cuartiles y valores atípicos.

Gráficos de Dispersión: Presenta la relación entre el NDVI_Sat y otras variables climáticas.

Matriz de Correlación: Representa la fuerza y dirección de las relaciones lineales entre las variables.

### Requisitos

-Las bibliotecas de Python utilizadas en el cuaderno deben estar instaladas. Puedes instalarlas utilizando
```bash
  !pip install nombre_de_la_libreria
```
