# Perú: Índice de Proximidad Física

## Description
Me baso en el trabajo «Characteristics of Workers in Low Work-From-Home and High Personal-Proximity Occupations» (Mongey & Weinberg, 2020) para elaborar un indicador de proximidad física por cada sector de la economía peruana. Uso Stata para realizar el ejercicio.

## Data
Son necesarias las siguientes bases de datos:
* `enaho01a-2018-500.dta`: microdatos de INEI, ENAHO Anual 2018, código de módulo: 5.
* `sumaria-2018.dta`: microdatos de INEI, ENAHO Anual 2018, código de módulo: 34.
* `INEI_ISCO_SOC.dta`: códigos de correspondencia entre clasificaciones internacionales de ocupaciones y códigos de INEI.

## Folders
* `data`: almacena toda la información fuente del ejercicio. Se requiere descomprimir carpeta en su interior.
* `resources`: almacena todos los resultados del ejercicio (tablas, imágenes, etc.).
* `scripts`: contiene todos los scripts necesarios para la ejecución del ejercicio.
* `temp`: almacena recursos temporales producto del ejercicio.
