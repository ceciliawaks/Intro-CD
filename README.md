# Introducción a la Ciencia de Datos

**Autores:** Facundo Morini, Cecilia Waksman

**2026**

## Entrega 1 
Este repositorio contiene el primer informe de la materia **Introducción a la Ciencia de Datos**. El trabajo realiza un análisis exploratorio de un subconjunto del dataset **All the News 2.1 – Component One**, compuesto por artículos periodísticos publicados en distintos medios de prensa.

El objetivo principal del informe es estudiar la estructura de los datos, evaluar su calidad y construir visualizaciones que permitan identificar patrones relevantes en el contenido textual de los artículos.

### Archivos principales

- `informe_1.pdf`: informe final compilado en PDF.
- `informe_1.qmd`: código fuente del informe, escrito en Quarto (compila código y texto en formato latex a pdf) y utilizando Python.
- `requirements.txt`: listado de librerías necesarias para ejecutar el análisis y compilar el informe.

### Datos utilizados

Los datos provienen del dataset **All the News 2.1 – Component One**. En el informe se trabaja con un subconjunto de 30.213 artículos periodísticos y, luego de una primera exploración, el análisis se concentra en los cinco medios con mayor cantidad de artículos: Reuters, The New York Times, CNBC, The Hill y People.

### Contenido del informe

El informe incluye:

- una descripción general del dataset utilizado;
- análisis de valores faltantes y calidad de los datos;
- selección de los cinco medios con mayor cantidad de artículos;
- visualización de la cantidad de artículos por medio y su evolución mensual;
- limpieza y normalización del texto;
- análisis de palabras frecuentes mediante nubes de palabras;
- análisis de correspondencias entre medios y términos frecuentes;
- comparación del volumen total y promedio de palabras por medio;
- matriz y grafo dirigido de menciones cruzadas entre medios.

### Ejecución

Para instalar las dependencias necesarias:

```bash
pip install -r requirements.txt
