# Datos utilizados en la tesis

## Base consolidada de entrada

Archivo:

raw/Base_Datos_Final_ETo_Pivot.csv

Esta base constituye la entrada consolidada utilizada por el flujo computacional reproducible de la investigación.

## Cobertura

- Periodo: enero de 1970 a diciembre de 2023
- Resolucion temporal: mensual
- Estaciones meteorologicas: 28
- Meses por estacion: 648
- Registros estacion-mes: 18144
- Variables: 12
- Duplicados ESTACION-FECHA: 0
- Campos vacios en la base consolidada: 0

## Variables

| Variable | Descripcion |
| --- | --- |
| FECHA | Fecha correspondiente al registro mensual |
| ESTACION | Nombre de la estacion meteorologica |
| LATITUD | Latitud de la estacion |
| LONGITUD | Longitud de la estacion |
| ALTITUD | Altitud de la estacion |
| HR101 | Humedad relativa |
| PT101 | Precipitacion |
| TM101 | Temperatura media |
| VTMED | Velocidad media del viento |
| ETo_dia | Evapotranspiracion de referencia diaria |
| DIAS_EN_MES | Numero de dias del mes |
| ETo_mensual | Evapotranspiracion de referencia mensual |

## Uso dentro del flujo reproducible

La base es utilizada directamente por:

- 02_scripts/01_regionalizacion/01_regionalizacion.ipynb
- 02_scripts/02_eventos/02_eventos_nspei.ipynb

Los archivos derivados posteriores deben obtenerse ejecutando secuencialmente los notebooks del repositorio.

## Integridad del archivo

SHA-256:

90EEAC3F551887BCE511881511FB06731494020A8DF8E48AE7A6906FCFA1D265

Esta carpeta representa la entrada del pipeline reproducible. La procedencia institucional, unidades originales, control de calidad y procedimientos de procesamiento deben interpretarse de acuerdo con la metodologia y los anexos de la tesis.
