# Evidencias — Avance 2: Modelo estrella y dashboard

**Proyecto:** VetHuella Huila — Análisis de inasistencia veterinaria (2025)

Este paquete organiza capturas compartidas durante la construcción del Avance 2 en Power BI. Las imágenes son originales, sin alteraciones; los nombres describen su propósito.

## Índice de evidencias

| Archivo | Descripción |
|---|---|
| `01_Modelo_y_Relaciones/01_Relaciones_Activas.png` | Ventana de administracion de relaciones; muestra las tres relaciones iniciales activas. |
| `01_Modelo_y_Relaciones/02_Modelo_Estrella_Cuatro_Dimensiones.png` | Modelo con Fact_Citas, Dim_Servicio, Dim_Paciente, Dim_Canal y Dim_Fecha. |
| `02_Medidas_y_Validacion/03_Medida_DAX_Tasa_Inasistencia.png` | Formula DAX de la tasa de inasistencia, con DIVIDE. |
| `02_Medidas_y_Validacion/04_Medida_DAX_Total_Citas.png` | Formula DAX de Total Citas con COUNTROWS. |
| `02_Medidas_y_Validacion/05_Validacion_Indicadores_1500.png` | Tarjetas de indicadores y validacion previa del total. |
| `03_Construccion_Dashboard/07_Grafico_Inasistencias_Servicio.png` | Grafico de inasistencias por servicio en construccion. |
| `03_Construccion_Dashboard/08_Dashboard_Con_Filtros.png` | Dashboard con segmentadores y cuatro visualizaciones. |
| `03_Construccion_Dashboard/09_Diseno_Modelo_Visual.png` | Organizacion de elementos del dashboard durante el proceso. |
| `04_Dashboard_Final/10_Dashboard_Indicadores_y_Graficos.png` | Dashboard reorganizado con KPI y graficos. |
| `04_Dashboard_Final/11_Dashboard_Con_Titulo_Completo.png` | Dashboard con titulo completo y etiquetas mejoradas. |
| `04_Dashboard_Final/12_Dashboard_Final_Orden_Cronologico.png` | Version final compartida; 1500 citas, 1017 atendidas, 189 no asistidas, tasa 15,67%, validacion 0 y meses ordenados. |

## Comprobación visible en la captura final

- Total de citas: **1.500**.
- Citas atendidas: **1.017**.
- Citas no asistidas: **189**.
- Canceladas: **172**; reprogramadas: **122**.
- Tasa de inasistencia: **15,67 %** = 189 / (1017 + 189) × 100.
- Validación del total: **0** = 1500 − (1017 + 189 + 172 + 122).

## Alcance y observaciones

- La evidencia del modelo muestra visualmente las cuatro dimensiones y las relaciones con la tabla de hechos.
- Las capturas de construcción muestran estados intermedios y no deben confundirse con la versión final.
- La interactividad de los segmentadores no puede demostrarse con una única captura estática. Para demostrarla, se recomienda añadir una captura con un filtro seleccionado y los KPI actualizados.
- Las capturas no reemplazan el archivo original `.pbix` ni una revisión funcional del modelo.
