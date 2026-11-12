# VetHuella Huila — Avance 2

## Inteligencia de Negocios 2026-B

**Proyecto:** Análisis de inasistencia veterinaria durante 2025.

### Objetivo

Construir un modelo estrella y un dashboard interactivo en Power BI para analizar las inasistencias a citas veterinarias.

### Desarrollo

Se implementó un modelo dimensional compuesto por una tabla de hechos (`Fact_Citas`) y cuatro dimensiones (`Dim_Servicio`, `Dim_Paciente`, `Dim_Canal` y `Dim_Fecha`).

Se desarrollaron medidas DAX para calcular el total de citas, las citas atendidas, las inasistencias, las cancelaciones, las reprogramaciones y la tasa de inasistencia.

### Resultados

- Total de citas: 1.500.
- Citas atendidas: 1.017.
- Citas no asistidas: 189.
- Citas canceladas: 172.
- Citas reprogramadas: 122.
- Tasa de inasistencia: 15,67 %.
- Validación de los totales: 0.

### Entregables

- Archivo Power BI con modelo estrella, medidas DAX y dashboard.
- Documentación técnica.
- Evidencias del desarrollo y funcionamiento del dashboard.
