## **Descripción del trabajo**

Este proyecto se centra en el análisis del dataset accidents-1.csv con el objetivo de explorar patrones en los accidentes de tránsito. 
Se realizarán procesos de carga, transformación, análisis y visualización de datos mediante técnicas de procesamiento de datos en Python utilizando bibliotecas como pandas, numpy y matplotlib.

El trabajo está dividido en las siguientes fases:

**Fase 1.** Cargue de Datos: Importación del dataset y revisión de su estructura.

**Fase 2.** ETL (Extracción, Transformación y Carga): Limpieza y preprocesamiento de los datos para su análisis.

**Fase 3.** Análisis Exploratorio: Identificación de tendencias y patrones en los accidentes.

**Fase 4.** Visualización de Datos: Representación gráfica de los resultados obtenidos.

### **Instrucciones de ejecución:**
---------------------------------------------------------------------------------------------------------------

**Paso 1:** Abrir el cuaderno en Google Colab
Ir a Google Colab.
Cargar el archivo Guía3 (Grupo 12).ipynb desde tu ordenador o Google Drive.

**Paso 2:** Instalar las librerías necesarias
Ejecuta el siguiente comando en una celda para asegurarte de que todas las librerías necesarias estén instaladas:

        !pip install pandas numpy matplotlib seaborn

**Paso 3:** Importar las librerías
Asegúrate de que el cuaderno tenga las siguientes líneas para importar las librerías necesarias:

        import pandas as pd
        import numpy as np
        import matplotlib.pyplot as plt
        import seaborn as sns

**Paso 4:** Cargar el dataset
Sube el archivo accidents-1.csv a Google Colab y utiliza el siguiente código para cargarlo en un DataFrame:

        # Cargar el dataset
        file_path = "/content/accidents-1.csv"

        # Leer el archivo con el delimitador correcto (;)
        df = pd.read_csv(file_path, delimiter=";", low_memory=False)
        df.head()  # Visualiza las primeras filas

**Paso 5:** Ejecutar el análisis
Ejecuta las celdas del cuaderno en orden para completar las tareas de limpieza, transformación y análisis de datos.

Al final del análisis, se generarán gráficos y conclusiones basadas en los datos.
