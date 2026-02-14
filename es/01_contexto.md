# Contexto del problema

## Descripción general

La empresa opera un activo industrial crítico utilizado en un proceso de producción continuo.
El proceso tiene una duración prolongada y no admite interrupciones sin generar pérdidas económicas relevantes.

El activo presenta un comportamiento típico de sistemas industriales complejos:
- opera correctamente la mayor parte del tiempo,
- muestra degradación progresiva de componentes clave,
- y puede fallar de forma no determinística durante la operación.

Cuando el activo falla durante un ciclo productivo, el proceso en curso se pierde por completo y la operación debe detenerse de manera no planificada.

---

## Características operativas del sistema

- Proceso continuo de larga duración  
- Ciclos productivos de entre **48 y 96 horas**
- Interrupciones no planificadas generan:
  - pérdida total del producto en proceso,
  - costos de recuperación,
  - impacto en compromisos de entrega
- La información sobre el estado real del activo es parcial e incompleta

---

## Contexto organizacional

La empresa cuenta con áreas de:
- Operaciones
- Mantenimiento
- Calidad / Compliance

Estas áreas suelen tener objetivos parcialmente en conflicto:
- Operaciones prioriza continuidad y cumplimiento del plan
- Mantenimiento prioriza reducción de riesgo técnico
- Calidad prioriza evitar eventos críticos y no conformidades

La decisión debe tomarse bajo presión de tiempo, con información incompleta y con consecuencias relevantes para el negocio.

---

## Naturaleza del problema

El problema no es técnico, sino **decisional bajo incertidumbre**.

No existe certeza sobre si el activo fallará o no durante el ciclo en curso.
Sin embargo, existen antecedentes históricos y señales indirectas que permiten estimar el riesgo.

La empresa debe decidir cómo balancear:
- continuidad operativa,
- riesgo de falla,
- impacto económico,
- y tolerancia al riesgo.

Este tipo de decisiones se repite en múltiples industrias y contextos operativos.
