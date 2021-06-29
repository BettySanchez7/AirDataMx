# Análisis de la calidad de aire en la Ciudad de México y zonas aledañas.

  

https://analisiscalidadaire.herokuapp.com/


La contaminación atmosférica consiste en la presencia de materias o formas de energía en el aire que pueden suponer un riesgo, daño o molestia de diferente gravedad para los seres vivos.

Este tipo de contaminación no solo representa un gran problema en el medioambiente sino que también en la salud de la sociedad y al mismo tiempo tiene grandes repercusiones en la economía pues reduce la productividad laboral siendo así que de acuerdo al Banco Mundial, cada año la contaminación del aire le cuesta a la economía mundial más de US$ 5 billones en costos de asistencia social y US$ 225 mil millones en ingresos perdidos. Estos son solo algunos de sus efectos pues la contaminación del aire afecta a miles de personas en diferentes sectores.


Siendo conscientes de este problema, desde el año de 1986, se monitorea de forma periódica la calidad del aire en la Zona Metropolitana del Valle de México por medio del Sistema de Monitoreo Atmosférico (SIMAT) y la RAMA (Red Automática de Monitoreo Atmosférico), realizando mediciones de la concentración de los contaminantes criterio cada hora.

## Descripción del proyecto:

Para el desarrollo de este proyecto se trabajó con las bases de datos del IMECA (Índice Metropolitano de la Calidad del Aire) la cual resume la información de las 34 estaciones de monitoreo existentes en cinco zonas representativas del Valle de México: Noroeste, Noreste, Centro, Suroeste, Sureste.

Cada uno de estos archivos incluye información sobre la fecha y hora de medición, así como las mediciones para cada zona y contaminante criterio. Elegimos trabajar con los datos de los años 2005-2020 porque consideramos que es un buen rango para analizar y observar cambios en el tiempo es decir se trabajó con series temporales.

OBJETIVO:

Analizar los datos disponibles para entender la problemática de la contaminación del aire en el Valle de México, y hacer que esta información sea más accesible, para luego proponer posibles soluciones. Después del análisis de datos disponibles se busca poder hacer predicciones, las predicciones son una herramienta muy útil en la toma de decisiones por lo que entender el problema y poder saber cómo estará la calidad de aire en un futuro puede ayudar en primera instancia a las personas que habiten el lugar de monitorio pero cómo se mencionó anteriormente este problema afecta a diferentes sectores por lo que no solo es útil hablando de la salud humana.


## Contenido del proyecto:  

● [Introducción e Identificación del problema ](https://github.com/BettySanchez7/Proyecto_AnalisisDatosConPython/blob/main/docs/Introduccion.md)
  

● [FASE 1 DEL PROYECTO (recolección, limpieza y transformación de datos)](https://github.com/BettySanchez7/Analisis_Calidad_AireCDMX_Python)

  

● [FASE 2 ANALISIS Y VISUALIZACIÓN DE DATOS](https://github.com/BettySanchez7/AirDataMx/tree/main/docs/MODULO4)

  

● FASE 3 IMPLEMENTACIÓN DE MACHINE LEARNING

La principal característica de los datos recolectados para este trabajo es que se constituye de datos temporales por lo que buscar un modelo que se adecue a esta característica es de importancia. El modelo de **regresión lineal** es el apropiado para realizar pronósticos cuando la tendencia es lineal pues su objetivo se basa en la comprensión de la naturaleza probabilística del modelo de regresión de tal manera que se pueda hacer un estimado del valor de una variable en función de una o más variables.

[DOCUMENTACIÓN]()

  

[NOTEBOOKS DEL PROYECTO](https://github.com/BettySanchez7/AirDataMx/tree/main/Notebooks/MODULO5)

[PRESENTACIÓN DEL PROYECTO]()

  

[DASHBOARD DEL PROYECTO CON STREAMLIT](https://analisiscalidadaire.herokuapp.com/)

  
  

### COLABORADORES DEL PROYECTO

  

- Maria Beatriz Sanchez Díaz

- Leonardo Zurita Martínez

- Jesús Ramseths Echeverría Rivera

- Daniel Alberto Ramos López (FASE 2- FASE 3)