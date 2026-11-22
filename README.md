# Cómo compilar EXP-01

Diapositivas de la exposición GA-SUM-02 (ISR-401, UTEQ): TraceCloud, gestión y trazabilidad de requisitos (tema 7, equipo AALM, caso Fabro Arriendos).

## Estructura

```
ISR401-AALM/
├── README.md
└── EXP-01/
    ├── Evidencias/
    │   └── TraceCloud-CAP-01.png a TraceCloud-CAP-05.png
    ├── main.tex
    ├── main.pdf
    └── referencias.bib
```

## Compilación

* Carpeta: `EXP-01/`
* Archivo principal: `EXP-01/main.tex`
* Compilador: pdfLaTeX (en Overleaf, menú Compiler → pdfLaTeX)
* Paquetes usados: beamer, inputenc, fontenc, lmodern, amssymb, amsmath, graphicx, tikz (bibliotecas arrows.meta, calc, positioning), babel (spanish). Beamer carga por sí mismo xcolor (colores) e hyperref (enlaces DOI y URL).
* Figuras: las capturas están en `EXP-01/Evidencias/` y deben quedar junto a `main.tex`.
* No usa BibTeX: la lista de referencias IEEE está escrita en las diapositivas finales y coincide con `referencias.bib`.

como primer paso al entrar a consola ejecutar el siguiente comando 

Ejemplo:
```cd C:\Users\GAMEMAX\OneDrive\Documentos\00_Git\ISR401-AALM\EXP-01```

esto permitirá que al compilar pueda detectar la carpeta y el archivo .tex donde se generara el pdf

En Overleaf: abrir el proyecto, seleccionar `EXP-01/main.tex` y pulsar Recompile.
Ejemplo en local, desde la raíz del repositorio:

```
cd C:\Users\GAMEMAX\OneDrive\Documentos\00_Git\ISR401-AALM\EXP-01
pdflatex main.tex
pdflatex main.tex
```

Se compila dos veces para que la numeración y los enlaces queden correctos. El resultado es `EXP-01/main.pdf`.

## Evidencias y datos personales

Las capturas de `Evidencias/` son del proyecto FabroArriendos creado en TraceCloud por el equipo. No se publican datos personales de terceros; esas evidencias están en la carpeta institucional privada compartida con el docente.

## Uso de IA

La declaración (herramienta, versión, propósito y verificación) está en la diapositiva de síntesis de `EXP-01/main.tex`.
