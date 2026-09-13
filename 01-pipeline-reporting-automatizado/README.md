# Pipeline de reporting comercial automatizado

> 🚧 Case study en construcción.

## Contexto / problema de negocio

Un equipo de ventas con una cartera fija de clientes necesitaba un reporte comercial consistente y actualizado (contactabilidad, pipeline, ofertas, oportunidades ganadas/perdidas) sin depender de armado manual en cada corte.

## Rol y alcance

Diseño y desarrollo end-to-end del pipeline: ingesta de datos, lógica de negocio, y generación automática de todos los entregables.

## Fuentes de datos y stack técnico

- Python (pandas) para el ETL
- Fuentes: exportaciones de CRM (maestro de targets, oportunidades, actividades) en Excel
- Salidas generadas automáticamente: PowerPoint ejecutivo, dashboard HTML interactivo, imágenes PNG/SVG, reportes Excel

## Enfoque / metodología

- Métricas acotadas estrictamente al universo de clientes con objetivo asignado
- Regla híbrida de contactabilidad combinando dos fuentes de actividad
- Matching en tres niveles (ID de cliente → cliente vía oportunidad → nombre) con normalización de texto y fallback difuso para resolver inconsistencias entre fuentes
- Reglas de negocio explícitas para clasificar cuentas "sin gestionar"

## Resultado / impacto

Reporte ejecutivo que antes tomaba armado manual pasó a generarse en un solo paso, con métricas consistentes entre todos los formatos de salida.

## Aprendizajes

*(pendiente)*
