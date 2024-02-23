# Análisis de la evolución de la pandemia de COVID-19

Este proyecto se centra en el análisis de la evolución de la pandemia de COVID-19 utilizando datos actualizados disponibles públicamente. El objetivo principal es representar gráficamente la evolución de la pandemia a nivel mundial, con un enfoque particular en algunos países seleccionados, como España, Francia, Alemania, Italia, Canadá, Japón, Reino Unido y Estados Unidos.

**Datos**

Los datos utilizados en este análisis son accesibles a través del siguiente enlace: https://covid.ourworldindata.org/data/owid-covid-data.csv .

Se importan y se filtran para incluir únicamente los datos de los países seleccionados para el análisis.

**Herramientas utilizadas**

· R: Se utiliza como lenguaje principal de programación para el análisis y la visualización de datos.

· Librerías R:

        ggplot2: Para la generación de gráficos.
        
        tidyverse: Incluyendo dplyr y otras herramientas para manipulación y limpieza de datos.
        
        plotly: Para crear gráficos interactivos a partir de ggplot2.
        
        readr: Para la importación de datos desde archivos CSV.

**Configuración**

El código proporcionado incluye una sección de configuración inicial que establece algunas opciones generales y carga las librerías necesarias para el análisis. También se importan y filtran los datos para su posterior visualización. Por úlitmo, encontramos un gráfico estático y otro interactivo.

**Visualización**

Se generan gráficos para representar la evolución de la pandemia de COVID-19 en los países seleccionados. Se incluyen gráficos estáticos y también gráficos interactivos que permiten explorar los datos de manera dinámica.
