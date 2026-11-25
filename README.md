# Analizador de Etiquetas de Encabezado H1-H6 y Jerarquia Web

[![Analizador Etiquetas Encabezado](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/es/analizador-etiquetas-encabezado/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Auditoria de arquitectura de encabezados HTML5, consistencia semantica y accesibilidad para lectores de pantalla.

***

## Capacidades del Analizador de Encabezados H1-H6

* **Verificacion de H1 Unico**: Comprobacion estricta de una sola etiqueta `<h1>` representativa del contenido.
* **Deteccion de Saltos de Nivel**: Identificacion de incoherencias jerarquicas (ejemplo `<h2>` seguido de `<h4>`) que afectan a la accesibilidad.
* **Control de Longitud y Contenido**: Deteccion de encabezados vacios o con sobrecarga de palabras clave.
* **Esquema Semantico Completo**: Mapeo visual estructurado del arbol jerarquico del documento.
* **Indice de Coherencia de Titulos**: Calificacion cuantitativa de 0 a 100 con detalle de alertas W3C WCAG.

***

## Instalacion y Ejecucion

Compatible con Python 3.8 o superior sin dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/heading-hierarchy-validator-es.git
cd heading-hierarchy-validator-es
python heading_hierarchy_validator.py https://empresa.es
```

Salida estructurada en JSON:

```bash
python heading_hierarchy_validator.py https://empresa.es -json
```

***

## Asistencia Tecnica y Consultoria

Para optimizacion semantica conforme a Directrices W3C WCAG y Estandares Europeos de Accesibilidad, consulte a **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/es/
* **Suite de Diagnósticos:** https://tools.tavardt.com/es/
* **Contacto Técnico:** https://ag.tavardt.com/es/contacto/

***

### Licencia
Distribuido bajo la Licencia MIT.

***

© 2026 TAVARDT. Todos los derechos reservados.
