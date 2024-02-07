# Identificacion de Tendencias de uso en CitiBike.
Este proyecto se centra en  comprender las tendencias de uso de las bicicletas compartidas en la ciudad. 
Se exploraran las horas pico de uso, los días con mayor actividad y el perfil demográfico de los usuarios para optimizar la disponibilidad y eficiencia del servicio.
En este proyecto, Se busca obtener:

  - Conexion de datos en Bigquery.
  - Limpieza de datos. 
  - Union de tablas, creacion de nuevas variables y generacion de tablas auxiliares.
  - Creacion de dashboard en Power BI:
    - Generacion de graficos basicos y avanzados.
    - Medidas de tendencia central.
    - Generacion de Histograma.
    - Mapas de calor.
    - Pivot Tables.
    
## Instrucciones de uso:
El archivo .pbi es el dashboard del proyecto, este podras abrirlo mediante la herramienta de Power BI.
Los datos originales podras encontrarlos en Google Cloud.


## Proceso de trabajo.
Siguiendo una lógica de pasos en secuencia, en este proyecto se aplicaron las siguientes fases:
  - Procesar y preparar la limpieza de datos.
  - Hacer un analisis exploratorio.
  - Aplicar tecnica de analisis.
  - Validacion de Hipotesis.
  - Resumir informacion en un dashboard.
  - Presentacion de resultados con las partes interesadas.


## Base de Datos.
Se trabajo con una base de datos con 3 tablas :
  - track_in_competition. Informacion de los streams y playlist de las plataformas de competencia.
  - track_in_spotify. Informacion de basica de las canciones en la plataforma.
  - track_technical_info. Informacion tecnica de las canciones en la plataforma.

## Herramientas utilizadas.
  - BigQuery (SQL)
  - Power BI.

    
 ## Imagenes de Resultados:
 ### Dashboard general.
 ![](https://github.com/ter2016/Proyecto-3-Hipotesis/blob/main/Imgs/D_Contexto.jpg)
 
 ![](https://github.com/ter2016/Proyecto-3-Hipotesis/blob/main/Imgs/D_Users.jpg)

 ![](https://github.com/ter2016/Proyecto-3-Hipotesis/blob/main/Imgs/D_Stations_usage.jpg)

 ![](https://github.com/ter2016/Proyecto-3-Hipotesis/blob/main/Imgs/D_Stations_capacity.jpg)


## Archivos y Links de acceso
  - Repositorio:
  - **PBI_Dashboard.pbix** https://comunidadxamarin-my.sharepoint.com/:f:/g/personal/tere_comunidadxamarin_onmicrosoft_com/ElwRcqsdzgRFmyKlFAN7SVUBZnMPPhTVtjhK6_yUmSawQA?e=Ei5ph1
    
  - Externo:
    **Datos Originales**  https://console.cloud.google.com/marketplace/product/city-of-new-york/nyc-citi-bike?project=data-sandbox-319716
