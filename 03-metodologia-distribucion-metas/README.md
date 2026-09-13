# Metodología de distribución de metas comerciales

> 🚧 Case study en construcción.

## Contexto / problema de negocio

Los objetivos comerciales mensuales (ingresos, envíos, kilos) de una empresa de logística internacional se repartían entre territorios de venta usando un proceso manual en Excel: pesos elegidos a criterio, revisión visual de valores atípicos, sin trazabilidad de los ajustes.

## Rol y alcance

Diseño y construcción de una metodología de reemplazo completa, documentada y auditable, para las tres métricas simultáneamente.

## Fuentes de datos y stack técnico

- Excel avanzado (sin macros): fórmulas, tablas dinámicas de apoyo
- Datos: histórico mensual de 17 meses por territorio

## Enfoque / metodología

- Normalización por día hábil para neutralizar diferencias de calendario entre meses
- Detección automática de valores atípicos con estadística robusta (mediana / MAD, umbral de z-score modificado)
- Backtesting de múltiples combinaciones de peso (año anterior vs. tendencia reciente) para elegir automáticamente la que mejor predice
- Bloque final con objetivos cerrados exactamente al total, columna de ajuste manual que exige justificación documentada, redistribución proporcional del resto, y alertas automáticas de desvío

## Resultado / impacto

Un proceso que antes dependía de revisión visual subjetiva pasó a ser reproducible, auditable, y con selección de método basada en evidencia (backtesting) en vez de intuición.

## Aprendizajes

*(pendiente)*
