# PowerBI_TablasCalendario
# Proyecto 6 – Tablas Calendario en Power BI 📅📊

Este repositorio contiene la **creación y aplicación de una tabla calendario** dentro de un modelo de datos en Power BI. Las tablas calendario son fundamentales para realizar análisis temporales sólidos, como comparaciones año a año, segmentaciones por mes, trimestre o semana, y otras métricas de inteligencia temporal.

---

## 📌 Objetivo del proyecto

El propósito principal de este proyecto es:

- Crear una **tabla calendario dinámica** en Power BI usando DAX.
- Comprender su importancia en el modelado de datos.
- Aprender a relacionarla correctamente con tablas de hechos.
- Implementar análisis y segmentaciones temporales en los informes.

---

## 🧾 Detalles del dataset

El proyecto se basa en un conjunto de datos de ventas simplificado, el cual contiene campos como:

- Fecha de venta
- Producto
- Categoría
- Importe de la venta

A partir de ese conjunto, se crea una **tabla calendario personalizada** con campos útiles como:

- Fecha
- Año
- Mes
- Trimestre
- Día de la semana
- Semana del año
- Nombre del mes

---

## 📊 Visualizaciones incluidas

El dashboard incluye visualizaciones para mostrar cómo utilizar correctamente la tabla calendario:

- Ventas por mes y año
- Segmentación por trimestre
- Comparaciones año a año
- Gráfico de líneas con tendencia de ventas mensuales
- Uso de slicers temporales (filtros por fechas)

---

## 🧠 Funciones DAX destacadas

- `CALENDAR()`
- `ADDCOLUMNS()`
- `FORMAT()`
- `WEEKNUM()`
- `YEAR()`, `MONTH()`, `DAY()`
- `RELATED()`, `USERELATIONSHIP()`

---

## 📁 Estructura del repositorio

PowerBI_TablasCalendario/
│

├─ Data/

│ └─ Tickets+Data.xlsx
│

├─ Powerbi/

│ └─ Tabla Calendario.pbix
│

├─ dax/

│ └─ Dim+Calendar+DAX.txt

│ └─ Dim+Calendar+M.txt 

│
└─ README.md
