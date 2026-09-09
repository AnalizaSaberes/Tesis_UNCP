# Tesis UNCP — Predicción probabilística de sequías

Repositorio reproducible asociado a la tesis:

**Predicción de sequías mediante modelos de cópulas y datos hidrometeorológicos en la Región Sur del Perú, 2024**

**Autor:** Virgilio Arriaga Gómez
**Universidad:** Universidad Nacional del Centro del Perú
**Programa:** Maestría en Gestión Sostenible de Cuencas Hidrográficas
**Año:** 2026

## Flujo computacional

El análisis está organizado en siete etapas:

1. **Regionalización hidroclimática**
   - 01_regionalizacion.ipynb

2. **Cálculo de nSPEI y extracción de eventos**
   - 02_eventos_nspei.ipynb

3. **Ajuste de distribuciones marginales**
   - 03_marginales_nspei3.ipynb

4. **Modelamiento de dependencia mediante cópulas**
   - 04_copulas_nspei3.ipynb

5. **Periodos de retorno conjuntos AND y OR**
   - 05_retornos_nspei3.ipynb

6. **Riesgo condicional**
   - 06_riesgo_condicional_nspei3.ipynb

7. **Simulación probabilística Monte Carlo**
   - 07_montecarlo_nspei3.ipynb

## Estructura del repositorio

Tesis_UNCP/
  01_datos/
  02_scripts/
  03_resultados/
  04_documentacion/
  README.md
  CITATION.cff
  LICENSE
  renv.lock
  .gitignore

Los notebooks utilizan rutas relativas para facilitar la portabilidad y reproducibilidad.

## Repositorio

https://github.com/AnalizaSaberes/Tesis_UNCP

## Alcance

La simulación y los modelos probabilísticos representan el régimen estadístico inferido de los datos históricos analizados. No constituyen un pronóstico fechado ni una proyección climática futura.
