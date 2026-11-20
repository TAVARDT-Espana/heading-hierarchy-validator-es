# Analizador de Etiquetas de Encabezado H1-H6 y Jerarquia Web

[![Analizador Etiquetas Encabezado](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/es/analizador-etiquetas-encabezado/)
[![Jurisdiccion](https://img.shields.io/badge/Jurisdiccion-Espana-00C853.svg)](https://ag.tavardt.com/es/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de arquitectura de encabezados HTML5, consistencia semantica y accesibilidad para lectores de pantalla.

Desarrollado y mantenido por el equipo de arquitectura semantica de **[TAVARDT Espana](https://ag.tavardt.com/es/)**.

---

## Capacidades del Analizador de Encabezados H1-H6

* **Verificacion de H1 Unico**: Comprobacion estricta de una sola etiqueta `<h1>` representativa del contenido.
* **Deteccion de Saltos de Nivel**: Identificacion de incoherencias jerarquicas (ejemplo `<h2>` seguido de `<h4>`) que afectan a la accesibilidad.
* **Control de Longitud y Contenido**: Deteccion de encabezados vacios o con sobrecarga de palabras clave.
* **Esquema Semantico Completo**: Mapeo visual estructurado del arbol jerarquico del documento.
* **Indice de Coherencia de Titulos**: Calificacion cuantitativa de 0 a 100 con detalle de alertas W3C WCAG.

---

## Instalacion y Ejecucion

Compatible con Python 3.8 o superior sin dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/heading-hierarchy-validator-es.git
cd heading-hierarchy-validator-es
python heading_hierarchy_validator.py https://empresa.es
```

Salida estructurada en JSON:

```bash
python heading_hierarchy_validator.py https://empresa.es --json
```

---

## Plataforma Web Oficial

Para realizar auditorias visuales interactivas:

* **[Analizador de Etiquetas de Encabezado Oficial](https://tools.tavardt.com/es/analizador-etiquetas-encabezado/)**
* **[Portal Corporativo TAVARDT Espana](https://ag.tavardt.com/es/)**

---

## Asistencia Tecnica y Consultoria

Para optimizacion semantica conforme a Directrices W3C WCAG y Estandares Europeos de Accesibilidad, consulte a **[TAVARDT Espana](https://ag.tavardt.com/es/contacto/)**.
