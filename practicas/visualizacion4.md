# Estudio de transporte
Se van a leer las coordenadas de una lista de poblaciones y se van a graficar en un gráfico de dispersión o XY (Scatter Chart).

Los datos provienen de la hoja [Estadística de Transporte de Viajeros](https://www.ine.es/jaxiT3/Tabla.htm?t=20239) donde se ha seleccionado lo siguiente: 
- Todos los tipos de transporte en "Tipo de transporte"
- Viajeros transportados en "Viajeros y tasas"
- Desde 2017M12 a 2017M01 en "Periodo"
*Tambien se pueden visualizar los datos mediante la [tabla.html](../geocoordenadas/tabla.html)

Se van a obtener con WebScraping mediante la función leerPoblaciones() del [fichero JavaScript](../geocoordenadas/leerPoblaciones.js) los datos necesarios.

Los datos obtenidos se guardan como JSON en un fichero de nombre [jasonprueba.js](../geocoordenadas/jasonprueba.js). Para poder usar directamente el array en una variable,le hemos añadido por delante de dicho array el texto: "obj=".

Para visualizar los datos, se utiliza la librería de [Google Chart](https://developers.google.com/chart/). El resultado es el que se muestra en la página [visualizacion.html](../geocoordenadas/visualizacion.html)
