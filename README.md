# Comprobador de PDF

Herramienta gratuita que revisa en el navegador algunos puntos básicos de accesibilidad de un PDF: etiquetas, idioma, título, texto alternativo, texto real frente a imágenes, encabezados, tablas, marcadores, formularios, orden de tabulación y restricciones de seguridad. Añade una lista de revisión manual.

El PDF no se sube a ningún servidor: se analiza en el navegador.

Web: https://jrebate.github.io/auto_pdf_accesible/

## Aviso

Es una herramienta orientativa. Que no se detecten errores en las comprobaciones automáticas no significa que el documento sea accesible ni que cumpla WCAG, EN 301 549, PDF/UA o cualquier ley. No es una auditoría ni una certificación.

## Librerías incluidas

- [pdf.js](https://github.com/mozilla/pdf.js) 4.10.38, licencia Apache 2.0 (`vendor/LICENSE-pdfjs.txt`).
- [pdf-lib](https://github.com/Hopding/pdf-lib) 1.17.1, licencia MIT (`vendor/LICENSE-pdf-lib.md`).
