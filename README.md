# Mapa de Escalada — Sierra de la Vigilancia

Proyecto de cartografía y croquis de escalada de la **Sierra de la Vigilancia**.

---

## Mapas disponibles

| Archivo | Descripción |
|---|---|
| [export/mapa_pdf_v0.5.pdf](export/mapa_pdf_v0.5.pdf) | Mapa para ver desde el celu |
| [export/addon_guia_v0.5.pdf](export/addon_guia_v0.5.pdf) | página complementaria para imprimir y agregar a la guía|
| [export/picadas_y_sectores.gpx](export/picadas_y_sectores.gpx) | Archivo GPX con picadas y sectores para GPS y apps |
|https://www.google.com/maps/d/u/1/edit?mid=1LyoCFQeLItQdF1Ji7sYadOqtvXdG-5U&usp=sharing| Mapa interactivo en Google Maps |

---

## Estructura del proyecto

El repositorio contiene:

- Proyecto **QGIS** con senderos, sectores, capas vectoriales y datos CSV
  
- Croquis de **vías** en Inkscape con fotos de referencia

```md
qgis/               → proyecto QGIS (2026Vigi.qgz), capas vectoriales (.shp),
│                     datos de terreno (SRTM), CSVs de sectores y lugares
│                     y curvas de nivel (.gpkg)
inkscape/           → croquis de vías (XCF/SVG) y fotos de referencia
export/             → PDFs finales
```

---

## Aportar información

Este es un proyecto abierto.  
Si encontrás **errores, nuevas vías, senderos o cambios en el equipamiento**, podés abrir un **Issue** en GitHub

---

## Aviso

La información puede contener errores u omisiones.  
El estado de las vías y equipamientos puede cambiar con el tiempo.  
Escalar implica riesgos; cada persona es responsable de evaluar las condiciones y su propia seguridad.
