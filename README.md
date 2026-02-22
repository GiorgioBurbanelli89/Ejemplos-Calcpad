# Ejemplos Calcpad

Coleccion de ejemplos y bibliotecas de macros para [Calcpad](https://calcpad.eu/).

## Estructura

```
Examples/
  Plot svg/        - Graficos SVG con biblioteca de macros
```

## Examples/Plot svg

- **plot_lib.cpd** - Biblioteca de macros reutilizable para generar graficos SVG
  - `plot$` - Grafico de una funcion con rango automatico
  - `plot2$` - Grafico de dos funciones con leyenda
  - `plot_begin$` / `plot_add$` / `plot_end$` - Patron builder para graficos multi-curva
  - Macros de etiquetas, ejes, leyendas y utilidades

- **dmf_calcpad.cpd** - Factor de Magnificacion Dinamica (7 curvas de amortiguamiento)
  - Requiere `plot_lib.cpd` en el mismo directorio

## Requisitos

- [Calcpad](https://calcpad.eu/) Desktop o Calcpad.Cli
