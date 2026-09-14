# Investigación 1 — Temas emergentes de ciberseguridad

Esqueleto modular para la investigación grupal de **CE-1115 Seguridad de la
Información** (Semestre II, 2026). El enunciado solicita un informe tipo
`summary paper` de máximo cinco páginas, en dos columnas, un PDF separado para
el atributo Investigación (IN), una presentación y una demo o ejemplo práctico.

**Tema seleccionado:** Tema 3 — Criptografía post-cuántica.

## Estructura

- [`informe/main.tex`](informe/main.tex): informe principal en formato IEEEtran
  (`conference`, dos columnas, A4).
- [`informe/secciones/`](informe/secciones/): una sección por archivo `.tex`,
  incluida la matriz de revisión.
- [`informe/referencias.bib`](informe/referencias.bib): bibliografía BibTeX
  inicial con entradas de ejemplo para reemplazar.
- [`atributo-in/main.tex`](atributo-in/main.tex): PDF independiente del
  atributo IN, con portada propia y bloques IN1–IN5 separados.
- [`presentacion/main.tex`](presentacion/main.tex): esqueleto de diapositivas
  Beamer para la exposición de al menos 15 minutos.
- [`demo/`](demo/): plan, código, evidencia y resultados de la demo. El
  contenido debe ejecutarse únicamente en un entorno propio y autorizado.
- [`docs/formato-ieee.md`](docs/formato-ieee.md): decisiones de formato y
  enlaces oficiales consultados.

## Compilación

Desde cada carpeta:

```bash
latexmk -pdf main.tex
```

Para limpiar archivos auxiliares:

```bash
latexmk -C
```


## Entrega y seguridad

El informe debe contener al menos cinco fuentes válidas, de las cuales dos sean
académicas, además de la matriz con referencia, problema, método, datos o
entorno, hallazgo y limitación. La demo no debe atacar terceros, utilizar datos
personales reales ni salir del entorno autorizado. Consulten el PDF del
enunciado incluido en la raíz para la rúbrica completa y la fecha de entrega.
