# Análisis de Datos Biológicos con Machine Learning

## Descripción
Este proyecto se centra en el análisis de un conjunto de datos biológicos utilizando técnicas de machine learning supervisadas y no supervisadas. Se implementarán diversos métodos para el procesamiento de datos, reducción de dimensionalidad, clusterización, y aprendizaje supervisado, con el objetivo de explorar y comprender mejor los patrones subyacentes en los datos de expresión genética.

## Objetivos
- Implementar técnicas de aprendizaje supervisado y no supervisado para analizar datos de origen biológico.
- Preparar el entorno de trabajo con las herramientas adecuadas para el análisis de datos en Python.
- Depurar y procesar el conjunto de datos para su análisis.
- Aplicar métodos de reducción de dimensionalidad y clusterización.
- Implementar métodos de aprendizaje supervisado y evaluar su rendimiento.

## Estructura del Repositorio

- `DATOS/`: Carpeta que contiene los archivos de datos como `classes.csv`, `columnas_names.txt`, y `gene_expression.csv`.
- `VIDEOS MÉTODOS/`: Carpeta con presentación en vídeo de gráficos obtenidos en los estudio de ML no supervisados.
- `README.md`: Información general sobre el proyecto, estructura, y guía de inicio.
- `LICENSE`: Detalles de la licencia del proyecto.
- `index.html`: Carga el repositorio en formato GitHub pages, https://castimax.github.io/PROYECTO-GRUPO-4/ . Con los datos fundamentales del trabajo.

## SCRIPTS DE ANÁLISIS DE DATOS

- `comp_longitud.py`: Código en Python para comparar tamaños de archivos, y ayudar a montar el DataFrame.
- `estudio2.py`: Código en Python que ¨monta en DF¨ con los archivos de la carpeta `datos/` y realiza el análisis con Machine Learning, supervisado y no supervisado.


## DOCUMENTOS DE RESULTADOS EN MARDOWN Y EN HTML
- `EXPLICACION ML NO SUPERVISADO.md`: Explicación de los métodos utilizados, y análisis de resultados obtenidos.
- `EXPLICACION ML SUPERVISADO.md`: Explicación de los métodos utilizados, y análisis de resultados obtenidos.
- `Explicaci Métodos no supervisa.html`: Explicación de los métodos utilizados con los gráficos obtenidos en cada estudio, y análisis de resultados.
- `resultado anal de clusteres.html`: Explicación de los métodos Análisis de Clústeres usados, con los gráficos obtenidos.
- `analisis_modelos_supervisados_y_resultados.html`: Informe de los resultados obtenidos en estudio ML Supervisado.

## DOCUMENTOS DE CONCLUSIONES DEL ESTUDIO
- `CONCLUSIONES.html`: Conclusiones generales del trabajo.

## Configuración del Entorno
Se recomienda crear un entorno virtual de Python e instalar las dependencias necesarias listadas en `requirements.txt`.

```bash
python -m venv venv
source .venv/bin/activate
pip install -r requirements.txt
