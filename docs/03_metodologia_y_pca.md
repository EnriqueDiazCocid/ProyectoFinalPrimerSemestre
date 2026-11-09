# Fase 2 — Protocolo de replicación

Registrar decisiones del artículo **antes** de ajustar parámetros para aproximarse a los resultados publicados.

| Decisión | Lo que dice el artículo | Implementación y evidencia | Divergencia justificada |
|---|---|---|---|
| Variables numéricas incluidas | PENDIENTE | PENDIENTE | PENDIENTE |
| Valores faltantes | PENDIENTE | PENDIENTE | PENDIENTE |
| Centrado/escalado | PENDIENTE | PENDIENTE | PENDIENTE |
| Covarianza/correlación | PENDIENTE | PENDIENTE | PENDIENTE |
| Componentes retenidos | PENDIENTE | PENDIENTE | PENDIENTE |
| Solver, versión y semilla | PENDIENTE | PENDIENTE | PENDIENTE |
| Validación, particiones y métricas | PENDIENTE | PENDIENTE | PENDIENTE |
| Modelo posterior a PCA (si aplica) | PENDIENTE | PENDIENTE | PENDIENTE |

**Precauciones:** una salida de PCA puede invertir el signo de sus componentes sin cambiar el subespacio; las *loadings* publicadas pueden tener distinta normalización de los vectores de `components_`. Compare convenciones antes de concluir que existe un error. Si PCA precede a clasificación/predicción, ajustar el escalado y PCA solo con los datos de entrenamiento para evitar fuga de información.

El método original tiene prioridad sobre el ejemplo sintético de esta plantilla.
