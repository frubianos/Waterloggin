# Waterloggin
Water logging assesment, hazard maps, risk maps.
# 🌧️ Waterloggin

### Urban Waterlogging Spatial Assessment and Visualisation Tool

**Python | GIS | H3 | Spatial Analysis | Climate Monitoring | Open Source**

## 📌 Descripción / Overview

**Waterloggin** es una herramienta de código abierto desarrollada en Python para el análisis espacial y temporal de eventos de encharcamiento urbano (*urban waterlogging*).

Integra técnicas de análisis geoespacial, indexación hexagonal H3, ponderación de infraestructura vial y visualización interactiva para identificar patrones de concentración de eventos, evaluar su distribución temporal y generar indicadores de priorización territorial.

La herramienta también permite incorporar información de anomalías de precipitación procedente de estaciones meteorológicas, complementando el análisis de los eventos con información climática.

Waterloggin busca proporcionar una metodología reproducible y adaptable a diferentes ciudades, como apoyo a la gestión del drenaje urbano, la planificación territorial y la toma de decisiones.

## ⚙️ Principales funcionalidades

- **Análisis espacial:** identificación de concentraciones de eventos mediante índices hexagonales H3.
- **Priorización territorial:** construcción de indicadores ponderados según la frecuencia de eventos y la jerarquía vial.
- **Análisis temporal:** evaluación de la distribución mensual y trimestral de los encharcamientos.
- **Seguimiento climático:** integración de anomalías de precipitación por estación meteorológica.
- **Visualización interactiva:** generación de mapas y dashboards HTML mediante Folium y Plotly.
- **Reproducibilidad:** estructura metodológica orientada a facilitar su aplicación en diferentes contextos urbanos.

## 🛠️ Tecnologías utilizadas

- Python
- GeoPandas
- Pandas y NumPy
- H3 — Uber Hexagonal Hierarchical Spatial Index
- Folium y Leaflet
- Plotly
- Shapely

## 🌎 Aplicabilidad

Waterloggin se desarrolla con el propósito de facilitar el análisis espacial de encharcamientos en distintas ciudades.

Su implementación inicial utiliza información georreferenciada de eventos registrados en Bogotá, Colombia. La generalización de los parámetros y datos de entrada para otras ciudades forma parte del desarrollo del proyecto.

## 📊 Estado del proyecto

**Versión inicial en desarrollo.**

El proyecto cuenta con funcionalidades de procesamiento espacial, análisis temporal y generación de mapas y dashboards interactivos. Se encuentra abierto a mejoras, validaciones metodológicas y contribuciones de la comunidad.

## 👨‍💻 Autor

**Fabio Rubiano Sánchez**

Ingeniero Civil | Magíster en Recursos Hidráulicos y Medio Ambiente | Especialista en Análisis Espacial | Doctorando en Geografía

Universidad Nacional de Colombia

## 📄 Licencia

Este proyecto se distribuye bajo la licencia **GNU General Public License v3.0 (GPL-3.0)**.

Se invita a investigador@s, profesionales y desarrollador@s a contribuir a su evolución, proponer mejoras metodológicas y reportar posibles errores.

**Waterloggin — Spatial analysis for better urban water management.**
