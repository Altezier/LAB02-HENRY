# LAB02-HENRY
PROYECTO INDIVIDUAL Nº2 :: Mercado bursátil
BY: Gian Pier, Pacheco Mateo

### **Temática**
Se simulara una situación en donde una empresa que busca invertir en el mercado bursátil  solicita analizarlo en detalle. Considerando que la empresa no conoce esta área financiera, se solicita una explicación de qué ha sucedido en este mercado en los últimos años (considerando impactos positivos y negativos a partir del año 2000), recomendaciones de inversión (ya sea enfocada en empresas o rubros de éstas) y otra información complementaria.
Considerando la cantidad de empresas existentes en el mercado bursátil, se le pide limitar el análisis a las empresas pertenecientes al índice SP500 (Standard & Poor's 500 Index).

Fuente de datos:

Para este trabajo se utilizará la API de yahoo finance, la cual posee su librería https://pypi.org/project/yfinance/ y pagina oficial https://finance.yahoo.com/
Como tambien el indice para extraer los indices por empresa como alguna otra informacion relevante en:
-[Lista índice SP500](https://www.google.com/url?q=https://en.wikipedia.org/wiki/List_of_S%2526P_500_companies&sa=D&source=docs&ust=1676566032938438&usg=AOvVaw3J6gZYtEH8xJABTCf0pYqO)


> En este apartado describire un poco el proyecto y los files.
:red_circle: **MENU:** :red_circle:
* **datasets/** - datasets que utilice en el proyecto.
* **EDA** - Análisis exploratorio de los datos referente a S&P500( indice = ^GSPC)
* **EDAP** - Análisis exploratorio de los datos referente a un sector de empresesas del rubro de energia dentro del indice S&P500.
* **POWER BI** - Dashboards referentes al analisis exploratorio del indice S&P500 y recomendaciones de inversion.
* **POWER BI** - Dashboards referentes al analisis exploratorio del indice S&P500 y recomendaciones de inversion.
* **requirements.txt** - librerias.

### **Herramientas utilizadas**
-   **[Python](https://www.python.org/)**: lenguaje de programación utilizado, que brinda acceso a librerías apropiadas para realizar la tarea encomendada de manera eficaz y eficiente.
-   **[Pandas](https://pandas.pydata.org/):** librería que nos permite el acceso a los archivos csv provistos, su conversión en dataframes, la transformación de los datos y la posterior exportación de los mismos en un único archivo, el cual luego será utilizado por la API para disponibilizar los datos.
-   **[Pandasql](https://pypi.org/project/pandasql/):** librería que nos permite efectuar consultas con lenguaje SQL sobre Dataframes de Pandas.
-   **[Power BI]([https://www.python.org/](https://powerbi.microsoft.com/es-es/))**: Power BI es una plataforma unificada y escalable de inteligencia empresarial (BI) con funciones de autoservicio apta para grandes empresas. Conéctese a los datos, visualícelos e incorpore sin problemas objetos visuales en las aplicaciones que usa todos los días.
