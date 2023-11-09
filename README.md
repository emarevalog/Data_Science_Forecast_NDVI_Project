>#Título: Machine Learning y Eco-hidrología: Pronóstico de la Actividad Vegetal en el Bosque Tropical Seco del Cañón del Río Cauca
>#Autores: Eileen Melissa Arévalo @emarevalog / Pablo Uribe Uribe @Blouri
>#Grupo: 8


>##Exploración de Datos - Análisis de Variables Climáticas
>Este conjunto de códigos en Google Colab realiza una exploración exhaustiva de datos climáticos utilizando diversas técnicas de visualización y análisis estadístico. El código utiliza el lenguaje de programación Python y las bibliotecas populares como Pandas, >Matplotlib, Seaborn y SciPy.

###Contenido del Repositorio
Exploracion_de_Datos.ipynb: Este es el cuaderno de Google Colab que contiene todo el código para la exploración de datos.

datos.csv: El conjunto de datos utilizado en el análisis. Este archivo debe mantenerse en la misma carpeta que el cuaderno de Google Colab.

Instrucciones de Uso
Abre el cuaderno de Google Colab, Exploracion_de_Datos.ipynb, en tu entorno de Google Colab.

Ejecuta cada celda secuencialmente para cargar los datos y realizar análisis.

Examina los histogramas, diagramas de cajas, gráficos de dispersión y la matriz de correlación para comprender las distribuciones y relaciones entre las variables climáticas.

Descripción del Conjunto de Datos
El conjunto de datos contiene información climática mensual con las siguientes variables:

Mes
NDVI_Sat
Precipitación_Modelo_Swb
Evapotranspiración_Actual_Modelo_Swb
Intercepción_Modelo_Swb
Evapotranspiración_Potencial_Modelo_Swb
Humedad_Del_Suelo_Modelo_Swb
Recarga_Modelo_Swb
Ml (columna sin valores)

##Visualizaciones Incluidas

Histogramas: Muestra la distribución de cada variable junto con la curva de mejor ajuste y la línea vertical para la media.

Diagramas de Cajas: Proporciona una representación visual de la distribución estadística, mostrando la mediana, cuartiles y valores atípicos.

Gráficos de Dispersión: Presenta la relación entre el NDVI_Sat y otras variables climáticas.

Matriz de Correlación: Representa la fuerza y dirección de las relaciones lineales entre las variables.

Requisitos
Se requiere acceso a internet para cargar el conjunto de datos desde un enlace de GitHub.

Las bibliotecas de Python utilizadas en el cuaderno deben estar instaladas. Puedes instalarlas utilizando !pip install nombre_de_la_libreria en una celda de código.

Contribuciones
¡Las contribuciones son bienvenidas! Si encuentras formas de mejorar el análisis, optimizar el código o agregar visualizaciones adicionales, no dudes en enviar una solicitud de extracción.
