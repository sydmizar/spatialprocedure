# Procedimiento para la visualización de archivos SHP (información geoespacial) en Oracle Business Intelligence haciendo uso de R, MapBuilder, MapViewer, PyCharm y ODI.
Se detalla la programación R definida para el impacto de archivos SHP en bases de datos Oracle y sus actividades subsecuentes, con la finalidad de observar correctamente las visualizaciones de mapas en OBI y hacer uso de la información geoespacial para el calculo de intersecciones entre capas.

# Herramientas necesarias

- Si desea practicar el taller en vivo durante la sesión, por favor asegúrese de tener los siguientes paquetes de R pre-instalados en su sesión:

```r
library(rgeos) 
library(rgdal) 
```

- Asegúrese de tener QGIS Desktop instalado en su computadora, puede bajarlo aquí: https://qgis.org/en/site/forusers/download.html

- También, es necesario tener Oracle MapBuilder instalado en su computadora, puedo bajarlo aquí: http://www.oracle.com/technetwork/middleware/mapviewer/downloads/index.html

- Asegúrese de tener PyCharm Community instalado en su computadora (se realizar la codificación en R dentro del taller si da tiempo), puede bajarlo aquí: https://www.jetbrains.com/pycharm/download/
