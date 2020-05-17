# covid19-bigdata

**Desarrollado por:**  Santiago Arturo Zapata Chacón

En este proyecto se aplicó lo aprendido en el curso Tópicos especiales de Telemática acerca del tema bigdata sobre los datos de covid19 a nivel mundial y nacional. 

Puede ver el desarrollo del análisis en el siguiente enlace: [notebook](https://github.com/sazapatac1/covid19-bigdata/blob/master/covid_19.ipynb)


Se utilizo la herramienta de Google Colaboratory para realizar el notebook dónde se realizaron las siguientes fases:

 - Fuentes de datos
 - Ingesta y almacenamiento de datos
 - Procesamiento: Análisis exploratorio con Spark
 - Visualización básica de datos

Primero se importó lo necesario para realizar las fases anteriores:

**![](https://lh6.googleusercontent.com/1kkNuq_A0TQ1Lxcy5cT-gwxPrMYIMFy9p-6P3nJc92oC5lQKSnq7geMOhMzA4f7AtmTsrIEennp2nnGJ6KUW9WhkN08KDbnNvWACxbswzBw0sy487aT7crpKLQZSjaom2Z04HeER)**


## **Fuente de datos**

Nivel mundial (Confirmed, deaths, recovered):
https://data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases
Nivel Colombia:
[https://www.datos.gov.co/Salud-y-Protecci-n-Social/Casos-positivos-de-COVID-19-en-Colombia/gt2j-8ykr/data](https://www.datos.gov.co/Salud-y-Protecci-n-Social/Casos-positivos-de-COVID-19-en-Colombia/gt2j-8ykr/data)

## **Ingesta y Almacenamiento de datos**

Se subió los datasets a este repositorio [datasets](https://github.com/sazapatac1/covid19-bigdata/tree/master/datasets).
Luego en el notebook se descargan y se cargan con spark.

## **Procesamiento: Análisis exploratorio de datos con pyspark**

En la sección de Procesamiento: Análisis exploratorio de datos con pyspark del notebook se realiza ese primer vistazo a como los 
datos de los diferentes datasets están constituidos. Además, se realizan algunas consultas para responder preguntas especificas.

## **Visualización básica de datos**

En la sección de visualización básica de datos del notebook podemos observar los diferentes gráficos que responden preguntas especificas
tanto a nivel mundial, nacional y Mundo vs Colombia. Se utilizó la libreria de Matploblib para realizar dichos gráficos.
