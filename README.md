# 🚗 ETL_PARKING - Sistema de Parqueo Inteligente

Este proyecto implementa un sistema completo de Business Intelligence para gestionar y analizar datos de parqueo de vehículos en un lugar específico de Bogotá.

Incluye modelado de datos, carga mediante ETL (SSIS) y visualización con Power BI.

---

## 🧩 Tecnologías utilizadas

- **SQL Server** – Base de datos relacional, multidimensional (Cubo Olap) y generación de datos
- **SSIS (SQL Server Integration Services)** – Proceso ETL desde archivos y otras fuentes
- **Power BI** – Dashboard interactivo para análisis de datos, tablero de control
- **T-SQL** – Scripts y procedimientos almacenados

---

## 📌 ¿Qué hace este proyecto?

1. Crea dos modelos de datos:
   - `PARKING_MR.sql`: Modelo relacional
   - `PARKING_DW.sql`: Data Warehouse (modelo multidimensional)
2. Usa un paquete SSIS (`Package.dtsx`) para hacer el proceso ETL:
   - Extracción de datos generados aleatoriamente
   - Transformación y limpieza
   - Carga en el Data Warehouse
3. Presenta un dashboard Power BI (`v2_ETL.pbix`) con visualización de:
   - Tiempo promedio de parqueo
   - Montos generados
   - Horas pico
   - Distribución de tipos de vehículo

---

## 📂 Estructura del repositorio

```bash
├── PARKING_MR.sql         # Script para crear el modelo relacional
├── PARKING_DW.sql         # Script para crear el Data Warehouse
├── Package.dtsx           # Paquete SSIS con el proceso ETL
├── V2_ETL.sln             # Solución de Visual Studio del proyecto ETL
├── v2_ETL.pbix            # Dashboard en Power BI
└── README.md              # Este archivo


