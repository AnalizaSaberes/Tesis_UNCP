# Documentacion de reproducibilidad

Esta carpeta contiene archivos complementarios para verificar la trazabilidad y el entorno computacional del analisis.

## Archivos incluidos

### Manifiestos

- manifiesto_regionalizacion.csv
- manifiesto_nspei_eventos.csv
- manifiesto_marginales_nspei3.csv
- manifiesto_copulas_nspei3.csv

### Informacion de sesion de R

- sessionInfo_regionalizacion.txt
- sessionInfo_nspei_eventos.txt
- sessionInfo_marginales_nspei3.txt
- sessionInfo_copulas_nspei3.txt

## Entorno reproducible

En la raiz del repositorio se incluyen:

- renv.lock
- .Rprofile
- renv/activate.R

El archivo renv.lock registra R 4.5.2 y 215 paquetes.

Para restaurar las versiones de los paquetes puede utilizarse en R:

renv::restore()

Los notebooks correspondientes a periodos de retorno, riesgo condicional y Monte Carlo forman parte del flujo reproducible disponible en 02_scripts.
