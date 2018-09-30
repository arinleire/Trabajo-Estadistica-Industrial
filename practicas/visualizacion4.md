# Estadística de Transporte de Viajeros
Se van a leer los viajeros transportados de una lista de diferentes tipos de transporte y se van a graficar en un gráfico de barras (bar chart) y en un gráfico de líneas (line chart).

Los datos provienen de la página web [Total de viajeros por tipo, medio de transporte (terrestre, aéreo y maritimo) y distancia](https://www.ine.es/jaxiT3/Tabla.htm?t=20239) donde se ha seleccionado lo siguiente:
- Todos los tipos de transporte en "Tipo de transporte"
- Viajeros transportados en "Viajeros y tasas"
- Periodo desde 2017M01 a 2017M12 en "Periodo"

*También se puede visualizar la tabla mediante [tabla.html](../geocoordenadas/tabla.html).

Se van a obtener con WebScraping mediante la función leertransporte() del [fichero JavaScript](../geocoordenadas/leertransporte.js)
Para ello, se ha abierto la consola (F12) y se ha pegado la definición de la función. 

Los datos obtenidos se guardan como JSON en un fichero de nombre [jasonprueba.js](../geocoordenadas/jasonprueba.js). Para poder usar directamente el array en una variable, se ha añadido por delante de dicho array el texto: "obj=".

Para visualizar los datos, se utiliza la librería de [Google Chart](https://developers.google.com/chart/). El resultado es el que se muestra en la página [visualizacion.html](../geocoordenadas/visualizacion.html).

