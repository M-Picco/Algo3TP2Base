# Diagramas

En esta carpeta se ubican los distintos diagramas que muestran la estructura e interacciones del proyecto

## PlantUML

Los diagramas de ejemplo están hechos con una herramienta llamada PlantUML, la cual permite especificar los diagramas a través de un DSL (Domain Specific Language)

Pueden encontrar la documentación en [plantuml.com](https://plantuml.com/).

## Instalación

### Requisitos

Para generar los diagramas de clase el software depende de GraphViz, el cual pueden descargarlo desde la [página del mismo](https://www.graphviz.org/download/)

### Linea de comando

Pueden descargar el archivo `jar` desde la [página de descargas](https://plantuml.com/starting) de PlantUml. Tal como menciona la página, se ejecuta de la siguiente forma:

```shell script
java -jar plantuml.jar {archivo}
```

### IntelliJ

IntelliJ cuenta con un plugin para la visualización y desarrollo de los diagramas. Pueden encontrarlo en el marketplace de Plugins de IntelliJ (`File -> Settings -> Plugins -> Marketplace`) o [aquí](https://plugins.jetbrains.com/plugin/7017-plantuml-integration)

### Eclipse

Eclipse también cuenta con un plugin. Pueden encontrar instrucciones para instalación y uso [aquí](https://plantuml.com/eclipse)