# Modelo Cuantitativo Simple

## 1. Objetivo

Cuantificar económicamente las alternativas definidas en el Paso 2 (decisin.md)
mediante un modelo estático de valor esperado.

Este modelo no incluye todavía dinámica temporal ni simulaciones avanzadas.

---

## 2. Supuestos económicos del caso (simulados y realistas)

Para este ejercicio se consideran los siguientes valores estimados:

- Valor económico del lote en proceso: USD 480.000
- Costo de mantenimiento preventivo (parada programada): USD 35.000
- Costo adicional por parada no planificada (logística, reinicio, horas extra): USD 60.000
- Costo reputacional estimado ante pérdida total del lote: USD 80.000

Costo total ante falla durante el ciclo:
480.000 + 60.000 + 80.000 = USD 620.000

---

## 3. Variable incierta

Se define la variable:

P = Probabilidad estimada de falla del componente durante el ciclo actual.

A efectos de este modelo simple, se utiliza una estimación inicial:

P = 8% (0.08)

Esta probabilidad surge de registros históricos y evaluación técnica preliminar.

---

## 4. Evaluación económica de alternativas

### Alternativa A1 — Interrupción preventiva

Costo cierto:
USD 35.000

Valor esperado:
-35.000

---

### Alternativa A2 — Continuar operación

Si NO ocurre falla:
Ganancia neta completa del lote.

Si ocurre falla:
Costo total estimado: USD 620.000

Valor esperado:

EV = (0.08 × -620.000) + (0.92 × 0)

EV = -49.600 USD

---

## 5. Comparación inicial

| Alternativa | Valor Esperado |
|-------------|---------------|
| A1 - Mantenimiento | -35.000 USD |
| A2 - Continuar | -49.600 USD |

Desde una perspectiva puramente económica y estática:

El mantenimiento preventivo presenta menor pérdida esperada.

---

## 6. Limitaciones del modelo

- No considera que la probabilidad de falla pueda aumentar con el tiempo
- No incorpora distribución de escenarios
- No evalúa umbrales dinámicos de intervención
- No incorpora sensibilidad de la probabilidad

Estos aspectos serán abordados en el siguiente paso (modelo_dinamico.md).
