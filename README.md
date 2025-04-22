# Trabajo Final - Regresión Avanzada

Este repositorio contiene el trabajo final para la materia de Regresión Avanzada, centrado en el análisis de datos del telescopio Kepler para la detección de exoplanetas.

## Contenido

- `RA2024_TP_Final_Nicolau.Rmd`: Documento principal en R Markdown con el análisis y resultados.
- `RA2024_TP_Final_Nicolau.html`: Versión renderizada del análisis en formato HTML.
- `Nicolau - Regresion Avanzada - Trabajo Final.pdf`: Informe final en formato PDF.
- `keplerexoplanets.csv`, `keplerfiltered.csv`, `keplerdataestimated.csv`: Conjuntos de datos utilizados en el análisis.
- `keplerdatadictionary.csv`: Diccionario de datos que describe las variables utilizadas.
- `TPfinalDic2024 - Consigna.pdf`: Enunciado original del trabajo final.
- `referencias.yaml`: Archivo con las referencias bibliográficas utilizadas.
- `renv.lock`, `renv/`: Archivos de configuración del entorno R para reproducibilidad.

## Requisitos

- R (versión recomendada: 4.3 o superior)
- Paquetes de R: `tidyverse`, `caret`, `ggplot2`, entre otros.
- RStudio para una mejor experiencia de desarrollo.

## Reproducción del Análisis

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/georgsmeinung/ra-tp-final.git
   ```
2. Abrir el proyecto en RStudio (`TP Final Codigo Fuente.Rproj`).
3. Restaurar el entorno con `renv`:
   ```R
   renv::restore()
   ```
4. Ejecutar el archivo `RA2024_TP_Final_Nicolau.Rmd` para reproducir el análisis.

## Licencia

Este proyecto se distribuye bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

## Contacto

Para consultas o sugerencias, por favor contacta a [georgsmeinung](https://github.com/georgsmeinung).
