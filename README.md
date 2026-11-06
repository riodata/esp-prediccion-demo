# Predicción de fallas en electrobombas sumergibles (ESP)

Demostración de Río Data Análisis: un modelo de machine learning que estima, con una ventana de tiempo, la probabilidad de falla de electrobombas sumergibles en pozos de petróleo y gas, y asigna cuadrillas a los equipos en riesgo.

**Ver la demostración:** https://riodata.github.io/esp-prediccion-demo/

## Contenido

La página presenta un recorrido en seis pasos:

1. **El problema** — componentes de una ESP y estimación de la producción diferida evitada.
2. **Las señales** — evolución de temperatura, corriente, vibración, caudal y presión de admisión en los días previos a una falla.
3. **El modelo** — etapas desde la adquisición de datos SCADA hasta la predicción.
4. **Calibración** — efecto del umbral de alerta sobre fallas anticipadas y falsas alarmas.
5. **Tablero operativo** — vista de sala de control con mapa, pronóstico y despacho de cuadrillas.
6. **Implementación** — etapas para llevar el sistema a una operación real.

## Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Recorrido didáctico |
| `tablero.html` | Tablero operativo (también embebido en el paso 5) |

Páginas estáticas, sin dependencias de compilación.

## Aviso

Todos los valores, equipos, ubicaciones y métricas son simulados con fines ilustrativos.

---

© Río Data Análisis · [riodataanalisis.com.ar](https://riodataanalisis.com.ar)
