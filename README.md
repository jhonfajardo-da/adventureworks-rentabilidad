# adventureworks-rentabilidad
Análisis de rentabilidad por mercados internacionales usando SQL — ROI, KPIs y dashboards de desempeño

# Análisis de Rentabilidad por Mercados — AdventureWorks
> **SQL · JOINs · ETL · KPIs · Google Sheets**
> TripleTen Data Analytics Bootcamp — 2026

## Descripción
Análisis financiero de ventas, costos y ROI por mercado internacional para la empresa AdventureWorks. El objetivo fue identificar qué mercados generaban mayor rentabilidad real y optimizar la asignación del presupuesto de marketing.

---

## Problema de negocio
AdventureWorks invertía presupuesto de marketing basándose en volumen de ventas, sin considerar la rentabilidad real por territorio. Esto generaba inversión ineficiente en mercados con alto volumen pero bajo margen.

**Pregunta clave:** ¿Qué mercados internacionales tienen mayor ROI y merecen mayor inversión?

---

## Proceso

### 1. Extracción de datos (SQL)
- Consultas con múltiples JOINs entre tablas: ventas, productos, territorios, campañas
- Cálculo de ingresos brutos, costos totales, margen neto y ROI por país
- Filtrado por períodos de tiempo para análisis de tendencias

### 2. Transformación y limpieza (ETL)
- Normalización de datos de múltiples fuentes
- Eliminación de registros duplicados y valores nulos
- Creación de columnas calculadas: margen %, ROI %, costo por venta

### 3. Análisis y visualización
- Dashboard de KPIs en Google Sheets con métricas por territorio
- Segmentación de mercados por cuadrantes: alto/bajo volumen vs alta/baja rentabilidad
- Identificación de mercados prioritarios y mercados a revisar

---

## Resultados
- Identificados los **3 mercados con mayor ROI** para priorización de inversión
- Detectados **2 mercados con alto volumen pero margen negativo** que requerían revisión
- Entregué recomendaciones al director financiero que mejoraron la toma de decisiones sobre inversión en mercados internacionales

---

## Herramientas utilizadas

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)

`SQL` · `JOINs complejos` · `ETL` · `Análisis financiero` · `KPIs` · `Dashboards` · `Google Sheets`

---

## Archivos del repositorio
| Archivo | Descripción |
|---------|-------------|
| `Proyecto 3_ Análisis del desempeño financiero con SQL - Resumen ejecutivo` | Dashboard de KPIs por mercado |
| `Análisis del desempeño financiero de Adventure Works con SQL` | Informe de recomendaciones estratégicas |
| `Análisis del desempeño financiero de Adventure Works con SQL` | Capturas del dashboard |

---

*Desarrollado por [Jhon Fredy Fajardo Rodriguez](https://www.linkedin.com/in/jhon-fajardo-ingeniero-de-sistemas/) · Data Analyst Junior*
