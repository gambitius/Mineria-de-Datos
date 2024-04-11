# Solemne 1

En este archivo se explorarán y transformarán datos relacionados con el COVID-19 proporcionados por un conjunto de datos públicos disponibles en BigQuery API. 

El primer análisis de datos realizados fue mediante BigQuery en donde se consultó un conjunto de datos proporcionados por la Universidad de Oxford. Mediante este análisis fue posible en una primera instancia ver la estructura en que se encuentra organizada esta tabla de datos, poder visibilizar esta tabla y realizar consultas de acuerdo a variables que se consideraron relevantes como lo puede ser la cantidad de casos confirmados y la cantidad de muertes debido al COVID-19.

El segundo análisis correspondió al acceso de una API pública, realizando consulta a dos APIS, una correspondiente a un traker de COVID-19 en Sri Lanka, y la otra llamada "HTTP API for Latest Covid-19 Data". Para el primer conjunto de datos fue posible obtener el contenido de la url e imprimirlo en  nuestra consola, mientras que para el segundo conjunto de datos, además de realizar este procedimiento, se logró hacer una consulta SQL luego de cargar los datos como un DataFrame.

Luego de realizar los análisis con BigQuery y la API, el objetivo es realizar 5 visualizaciones de gráficos diferentes utilizando los datos proporcionados por la base de datos, para ello se decidió utilizar la obtención de datos de BigQuery. Los 5 tipos de gráficos que se utilizarán corrsponderán a un gráfico lineal, circular, de burbujas, de pirámide y de barras.
