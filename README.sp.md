[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)
# Dimensionador y calculador de precio de préstamos RTL

## Herramienta ligera de apoyo a la decisión para préstamos residenciales transitorios, para la estructuración de préstamos, fijación de precios, validación de elegibilidad y generación de cotizaciones precisas listas para el cliente

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Status](https://img.shields.io/badge/Version-Stable-brightgreen)

**Dimensione, valide y fije el precio de préstamos residenciales transitorios de manera consistente en minutos—sin instalación, sin programación y sin exponer la lógica de precios propietaria. Disponible como versión de navegador y como libro de trabajo de Excel.**

**Sin registro. Sin instalación. Gratis en su navegador.**

Pruebe la versión de navegador gratis. Si necesita la versión de Excel, puede comprarla con una garantía de devolución de dinero de 30 días, sin preguntas.
>
> 🌐 **Abrir en el navegador**  
> [*Versión HTML*](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> 📥 **Descargar Excel**  
> [*Descarga de Excel*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Qué le ayuda a seguir

- La elegibilidad del préstamo frente a los límites de apalancamiento de suscripción antes de emitir una cotización.
- El LTV, LTC, LTP y LTARV reales a través de diferentes estructuras de préstamos residenciales transitorios.
- Los requisitos de financiamiento del prestatario, el producto neto del financiamiento y el efectivo estimado requerido al cierre.
- La consistencia de precios a través de los niveles FICO, los niveles de apalancamiento y los supuestos de precios del prestamista.
- La protección del margen identificando préstamos fijados por debajo de los requisitos de spread internos.
- Condiciones de préstamo listas para el cliente generadas a partir de un único flujo de suscripción en lugar de cálculos ensamblados manualmente.

---

## Flujo de trabajo de inicio rápido

### 1. Configurar los supuestos de suscripción

Los usuarios administrativos definen los parámetros de préstamo una sola vez en la hoja dedicada Pricing & Assumptions. Estos incluyen límites de apalancamiento, cuadrículas de precios, comisiones de servicio, requisitos de spread, programas de préstamo y umbrales de suscripción. Estos ajustes normalmente requieren solo mantenimiento periódico en lugar de ajuste diario.

---

### 2. Ingresar un nuevo escenario de préstamo

Abra la hoja **Inputs** y complete la información solicitada.

La información típica incluye:

- Precio de compra
- Valor actual
- Presupuesto de rehabilitación
- Valor después de la reparación (ARV)
- Monto de préstamo solicitado
- Puntaje FICO del prestatario
- Experiencia del prestatario
- Activos líquidos
- Plazo del préstamo
- Tasa de interés del préstamo solicitada

Los menús desplegables y las reglas de validación reducen las entradas incorrectas, mientras que el formato condicional deshabilita automáticamente los campos que no son aplicables para el programa de préstamo seleccionado.

---

### 3. Revisar los resultados al instante

Cambie a la página Resumen de cotización.

Todos los cálculos de suscripción se actualizan automáticamente, incluyendo:

- Elegibilidad del préstamo
- Métricas de apalancamiento
- Validación de precios
- Efectivo al cierre
- Financiamiento neto
- Intereses prepagados
- Estimaciones de liquidación

No se requieren cálculos manuales ni hojas de precios separadas.

---

### 4. Repetir para cada nuevo préstamo

Cada préstamo adicional solo requiere reemplazar las entradas del prestatario.

No hay necesidad de reconstruir fórmulas, modificar cálculos ni rediseñar informes. El motor de precios sigue siendo reutilizable a través de escenarios de préstamos puente, préstamos Fix-and-Flip, rehabilitación mayor, rehabilitación menor y financiamiento de construcción.

**Establezca los parámetros de suscripción una sola vez. Ingrese el escenario del préstamo. Revise el precio. Genere la cotización. Repita cada vez que otro préstamo necesite ser evaluado.**

*   👉 [*Descarga la plantilla de Excel para usarla sin conexión*](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Por qué construí esto

La suscripción de préstamos residenciales transitorios a menudo parece sencilla porque los prestamistas experimentados ya conocen los principales ratios que quieren aprobar. En realidad, la mayoría de los errores de fijación de precios ocurren mucho antes de que un préstamo llegue a la revisión del comité.

El problema rara vez es calcular el LTV o el LTC individualmente. El problema es evaluar cada regla de suscripción simultáneamente mientras también se protege la rentabilidad del prestamista.

Un tramitador podría calcular un LTV aceptable pero pasar por alto que la tasa de interés del préstamo solicitada ya no satisface el requisito de spread mínimo. Otro originador puede cotizar una tasa atractiva que se ajusta a las expectativas del prestatario pero que, sin querer, fija el precio por debajo de la tasa de compra requerida del prestamista. Una tercera transacción puede satisfacer los requisitos de apalancamiento pero aun así requerir sustancialmente más efectivo del prestatario de lo esperado porque los intereses prepagados y las comisiones de servicio reducen el financiamiento disponible.

En lugar de confiar en múltiples hojas de cálculo desconectadas o verificar manualmente las directrices de suscripción una regla a la vez, quería un marco analítico reutilizable que evalúe juntas todas las restricciones principales de suscripción.

Por ejemplo:

**Antes**

- El LTV parece aceptable.
- El prestatario recibe una cotización verbal.
- La revisión de precios descubre más tarde un spread del prestamista insuficiente.
- La cotización debe ser revisada.
- La confianza del prestatario disminuye.
- El tiempo de procesamiento interno aumenta.

**Después**

El libro de trabajo evalúa el apalancamiento, los precios, la protección del spread, los costos de liquidación, los requisitos de liquidez y la elegibilidad juntos antes de emitir la cotización. El prestamista sabe inmediatamente si el escenario pasa, requiere una excepción o no debe proceder.

Este libro de trabajo no es simplemente una calculadora. Integra el razonamiento de suscripción en un proceso de apoyo a la decisión repetible que reduce la estructuración inconsistente de préstamos entre diferentes usuarios.

---

## Problemas comunes de préstamos RTL que esto resuelve

| Problema | Sin esta herramienta | Con esta herramienta |
|------------|-----------------|----------------|
| Préstamo aprobado usando un solo ratio de apalancamiento | Los límites importantes de suscripción pueden pasarse por alto hasta la revisión final | Todos los ratios de apalancamiento principales se evalúan simultáneamente antes de cotizar |
| Fijación de precios manual | Diferentes originadores cotizan tasas diferentes para prestatarios idénticos | El precio se genera de manera consistente usando reglas de precios centralizadas |
| Erosión oculta de la rentabilidad | Los préstamos parecen aceptables pero violan los requisitos de margen mínimo | La validación de spread señala inmediatamente la fijación de precios por debajo de los requisitos del prestamista |
| Requisito de efectivo del prestatario inesperado | Los costos de liquidación se descubren tarde en el cierre | El efectivo al cierre y el financiamiento neto se calculan durante la estructuración inicial |
| Excepciones de préstamo identificadas demasiado tarde | Múltiples revisiones retrasan la suscripción | Los escenarios de excepción se resaltan inmediatamente para la revisión gerencial |
| Lógica de precios interna expuesta | Los cálculos sensibles de tasa de compra se vuelven visibles para usuarios externos | Las hojas de precios internas permanecen protegidas en las versiones dirigidas a los originadores |

---

## Para quién es esto

Este libro de trabajo está diseñado para profesionales involucrados en préstamos residenciales transitorios, incluyendo:

- Prestamistas privados
- Prestamistas no bancarios
- Originadores de préstamos
- Tramitadores de préstamos
- Suscriptores
- Equipos de mercados de capitales
- Pequeñas sociedades de préstamo que buscan una fijación de precios de préstamos estandarizada
- Equipos de crédito que evalúan préstamos puente, de rehabilitación y de construcción

Es particularmente útil para organizaciones que necesitan un flujo de trabajo de suscripción ligero sin implementar un Loan Origination System (LOS) completo.

Esto **no** está destinado a reemplazar las plataformas de préstamo empresariales, el software de servicing ni los sistemas de gestión de cumplimiento.

No se requiere experiencia en hojas de cálculo. Abra la versión de navegador o el libro de Excel, ingrese la información del préstamo y comience a evaluar escenarios de préstamo de inmediato.

---

## Acerca de

Construyo herramientas analíticas ligeras para situaciones en las que demasiadas variables operativas deben considerarse al mismo tiempo. En lugar de reemplazar el software empresarial, estos libros de trabajo integran la toma de decisiones práctica en marcos reutilizables que ayudan a los equipos a alcanzar conclusiones consistentes con menos esfuerzo manual.

El **Dimensionador y calculador de precio de préstamos RTL** sigue esa filosofía reuniendo las reglas de suscripción, la lógica de precios, la validación de apalancamiento, los cálculos de liquidación y la generación de cotizaciones en un flujo de trabajo estructurado único. La pregunta central es siempre la misma: **¿Qué información necesita estar visible en un solo lugar para tomar la próxima decisión de préstamo con confianza?**
## Detalles técnicos

<details>
<summary><strong>Para revisores técnicos, practicantes de Excel y colaboradores</strong></summary>

---

## Arquitectura del libro de trabajo

El libro de trabajo sigue una arquitectura en capas que separa la interacción del usuario, las reglas de negocio, los cálculos analíticos y la presentación. Esto evita la modificación accidental de la lógica de precios mientras mantiene la operación diaria simple para los originadores de préstamos.

```text
                    USER LAYER
 ┌─────────────────────────────────────┐
 │          01_ReadMe                  │
 │ Documentation & Version Control     │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │          02_Inputs                  │
 │ Borrower & Loan Information         │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │ 03_Pricing_&_Assumptions            │
 │ Pricing Rules & Risk Parameters     │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │       04_Calc_Engine                │
 │ Underwriting & Pricing Logic        │
 └─────────────────────────────────────┘
                    │
                    ▼
 ┌─────────────────────────────────────┐
 │      05_Quote_Summary               │
 │ Client Ready Output                 │
 └─────────────────────────────────────┘
```

## Responsabilidades de las hojas

| Hoja | Propósito | Editable |
|------------|---------|----------|
| 01_ReadMe | Instrucciones, historial de versiones, documentación del administrador | Sí |
| 02_Inputs | Información del prestatario y condiciones de préstamo solicitadas | Sí |
| 03_Pricing_&_Assumptions | Cuadrículas de tasa de compra, reglas de apalancamiento, supuestos de precios | Solo administradores |
| 04_Calc_Engine | Cálculos de suscripción, motor de precios y validación | No |
| 05_Quote_Summary | Hoja de condiciones imprimible dirigida al cliente | No |

---

## Flujo de datos

```text
Borrower Inputs
        │
        ▼
Input Validation
        │
        ▼
Pricing Lookup
        │
        ▼
Leverage Calculations
        │
        ▼
Eligibility Validation
        │
        ▼
Settlement Calculations
        │
        ▼
Profitability Analysis
        │
        ▼
Quote Summary
```

Cada salida mostrada a los usuarios se origina en el motor de cálculo. Ningún valor se ingresa manualmente en la cotización final.

---

## Estrategia de seguridad

El libro de trabajo se compila intencionalmente en dos formatos de distribución.

| Versión | Usuarios previstos | Componentes protegidos |
|---------|----------------|----------------------|
| Versión interna | Directores, suscriptores, operaciones | Todas las hojas visibles con contraseña de administrador |
| Versión originador | Originadores de préstamos | Tablas de precios y motor de cálculo ocultos usando xlSheetVeryHidden |

Las medidas de protección adicionales incluyen:

- Protección de la estructura del libro de trabajo
- Fórmulas ocultas
- Celdas de cálculo bloqueadas
- Cuadrículas de precios protegidas
- Barra de fórmulas oculta (versión originador)
- Estructura de hoja protegida con contraseña

Este enfoque protege los precios propietarios del prestamista sin mantener dos libros de trabajo independientes.

---

## Tres trampas que atrapan incluso a los originadores de préstamos más experimentados

---

## Trampa 1 — Mirar solo el LTV

Muchos prestamistas se enfocan instintivamente en el préstamo-valor porque es la métrica de suscripción más familiar.

Lamentablemente, el préstamo transitorio rara vez se basa en un solo ratio de apalancamiento.

### Decisión incorrecta

Precio de compra

```
$400,000
```

Préstamo solicitado

```
$320,000
```

Valor actual

```
$420,000
```

LTV calculado

```
76.2%
```

El originador concluye:

> "El préstamo cumple con la política."

Sin embargo...

Presupuesto de rehabilitación

```
$160,000
```

Costo total del proyecto

```
$560,000
```

LTC real

```
57.1%
```

LTARV real

```
88%
```

El LTARV excede la política interna.

El préstamo en realidad está fuera de las directrices de préstamo.

### Enfoque correcto

Evalúe:

- LTV
- LTC
- LTARV
- LTP

antes de determinar la elegibilidad.

<details>

<summary>Referencia de fórmulas</summary>

```excel
Actual LTV
=IFERROR(LoanAmount/AsIsValue,0)

Actual LTC
=IFERROR(LoanAmount/(PurchasePrice+RehabBudget),0)

Actual LTARV
=IF(ARV=0,0,
IFERROR(LoanAmount/ARV,0))
```

</details>

Resultado:

El libro de trabajo evalúa automáticamente cada ratio de apalancamiento junto antes de asignar un estado Pass, Exception o Fail.

---

## Trampa 2 — Cotizar antes de verificar el margen

Un prestatario solicita una tasa atractiva.

El originador baja la tasa de interés del préstamo para seguir siendo competitivo.

Todo parece aceptable.

Más tarde...

El marketing secundario descubre que el spread del prestamista ha caído por debajo de los mínimos internos.

La cotización debe ser revisada.

### Decisión incorrecta

Tasa del prestatario

```
10.00%
```

Tasa de compra

```
8.20%
```

Spread

```
1.80%
```

Spread mínimo requerido

```
2.50%
```

La transacción en realidad está por debajo de los requisitos de rentabilidad del prestamista.

### Enfoque correcto

Cada cotización debe validar el precio antes de la presentación.

<details>

<summary>Referencia de fórmulas</summary>

```excel
Spread

=NoteRate-BuyRate

Spread Status

=IF(
Spread<MinimumSpread,
"Below Margin",
"Valid")
```

</details>

En lugar de descubrir el problema durante la revisión final, el libro de trabajo señala inmediatamente:

```
Below Margin
```

permitiendo corregir el precio antes de que el prestatario reciba una cotización.

---

## Trampa 3 — Subestimar el efectivo requerido al cierre

Muchos prestatarios evalúan solo el monto de préstamo solicitado.

Los costos de liquidación reducen el producto real.

Ignorar estas deducciones produce frecuentemente expectativas poco realistas del prestatario.

### Ejemplo

Préstamo solicitado

```
$450,000
```

Intereses provisionales

```
$6,250
```

Comisión de servicio

```
$2,250
```

Financiamiento neto

```
$441,500
```

Efectivo requerido

```
$468,000
```

Efectivo real al cierre

```
$26,500
```

Si la liquidez del prestatario es igual a solo

```
$18,000
```

el préstamo no puede cerrarse sin fondos adicionales.

### Enfoque correcto

Calcule el producto de liquidación en lugar de suponer que el monto bruto del préstamo es igual al financiamiento disponible.

<details>

<summary>Referencia de fórmulas</summary>

```excel
Net Funding

=LoanAmount
-ShortInterest
-ServiceFee

Cash To Close

=MAX(
0,
TotalProjectCost-
NetFunding)

Liquidity Shortfall

=MAX(
0,
CashToClose-
LiquidAssets)
```

</details>

El libro de trabajo identifica la escasez de liquidez antes de que se preparen los documentos de cierre.

---

## Escenario de ejemplo

Considere la siguiente transacción Fix-and-Flip.

| Partida | Valor |
|------|------:|
| Precio de compra | $300,000 |
| Presupuesto de rehabilitación | $70,000 |
| Valor actual | $310,000 |
| ARV | $465,000 |
| Préstamo solicitado | $340,000 |
| FICO | 726 |
| Experiencia | 6+ Projects |
| Tasa de interés del préstamo | 11.25% |
| Plazo del préstamo | 12 Months |

El motor de precios recupera la tasa de compra correspondiente según el nivel FICO del prestatario y el apalancamiento calculado.

El motor de cálculo determina entonces:

- LTV real
- LTC real
- LTP real
- LTARV real
- Spread
- Financiamiento neto
- Efectivo al cierre
- Ganancia estimada del prestamista

Suponga que las métricas resultantes son:

| Métrica | Resultado |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Elegibilidad | Exception Needed |

Aunque el precio sigue siendo rentable, el apalancamiento excede el umbral de LTV preferido.

En lugar de rechazar el préstamo de inmediato, el libro de trabajo lo clasifica como **Exception Needed**, permitiendo a la gerencia revisar factores compensatorios como la experiencia del prestatario, la liquidez o garantías adicionales.

Este flujo de trabajo estructurado crea un proceso de suscripción consistente donde el precio, el apalancamiento, la liquidación y la rentabilidad se evalúan juntos en lugar de forma independiente.

---

## Referencia de fórmulas

<details>

<summary>Cálculos de apalancamiento</summary>

| Cálculo | Fórmula |
|-------------|---------|
| LTV real | `Loan Amount ÷ As-Is Value` |
| LTC real | `Loan Amount ÷ (Purchase + Rehab)` |
| LTP real | `Loan Amount ÷ Purchase Price` |
| LTARV real | `Loan Amount ÷ ARV` |

</details>

<details>

<summary>Motor de precios</summary>

| Fórmula | Propósito |
|----------|----------|
| XLOOKUP | Recuperar la tasa de compra |
| INDEX + MATCH | Búsqueda de precios heredada |
| Spread | Tasa de interés del préstamo − Tasa de compra |
| Estado del spread | Validación del margen |

El precio siempre usa un comportamiento de búsqueda exacto con manejo de errores predeterminado para evitar salidas de precio inválidas.

</details>

<details>

<summary>Cálculos de liquidación</summary>

| Cálculo | Propósito |
|-------------|----------|
| Intereses provisionales | Intereses cobrados al cierre |
| Comisión de servicio | Comisión deducida a lo largo del plazo del préstamo |
| Financiamiento neto | Fondos disponibles para el prestatario |
| Efectivo al cierre | Contribución adicional del prestatario |
| Déficit de liquidez | Deficiencia de financiamiento |

</details>

<details>

<summary>Reglas de elegibilidad</summary>

El motor de suscripción evalúa:

- LTV máximo
- LTC máximo
- LTARV máximo
- Margen de precio
- Liquidez del prestatario

Resultados posibles:

- PASS
- EXCEPTION NEEDED
- FAIL

La elegibilidad general siempre refleja el resultado de suscripción más restrictivo.

</details>

## Reglas de validación

| Campo | Regla de validación | Comportamiento ante errores |
|------|-----------------|----------------|
| Loan Type | Solo menú desplegable | Rechazar valores inválidos |
| Purchase Price | Mayor que cero | Devolver cálculos en cero |
| As-Is Value | Mayor que cero | Evitar la división por cero |
| Rehab Budget | Cero para préstamos puente | Campo automáticamente en gris |
| ARV | Requerido para productos de rehabilitación | Mostrar N/A donde corresponda |
| Requested Loan | Moneda positiva | Rechazar valores negativos |
| FICO | 300–850 | Rechazar el puntaje inválido |
| Experience Tier | Solo menú desplegable | Evitar fallos de búsqueda |
| Loan Term | 12 / 18 / 24 meses | Rechazar otros valores |
| Short Interest Days | 0–30 | Rechazar la entrada inválida |
| Buy Rate Lookup | XLOOKUP con valor de reserva | "Check Risk Rules" |
| Division Operations | Envoltorio IFERROR | Devolver 0 en lugar de errores de Excel |
| Text Lookups | TRIM + UPPER | Evitar diferencias de espacios y mayúsculas |
| Margin Check | Comparar con el spread mínimo | Devolver "Below Margin" |
| Eligibility | Evaluar todos los indicadores de suscripción | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Otras herramientas de esta serie

El **Dimensionador y calculador de precio de préstamos RTL** es parte de una colección creciente de herramientas operativas ligeras de apoyo a la decisión construidas para profesionales que necesitan análisis confiables sin implementar software empresarial.

Cada herramienta sigue los mismos principios:

- Sin registro requerido
- Sin instalación requerida
- Disponible en ediciones para navegador y Excel
- Basada en fórmulas en lugar de dependiente de macros
- Construida para decisiones operativas repetibles en lugar de informes puntuales

| Herramienta | Propósito |
|------|---------|
| Construction Estimating System | Estandarizar la estimación de proyectos, ensamblajes, precios de oferta y seguimiento de costos. |
| Inventory Forecasting & Reorder Planner | Pronosticar la demanda de inventario, identificar el momento de reposición y monitorear el riesgo de stock. |
| Retail & Maquila Inventory Ledger | Rastrear el movimiento de inventario a nivel de pieza, producción, defectos y distribución. |
| Unified Personal & Business Budget Framework | Consolidar el flujo de caja personal y comercial en un solo modelo de planificación financiera. |
| Cross-Border VAT Compliance Dashboard | Monitorear las obligaciones de IVA en varios países y canales de venta. |
| Project Financial Control Dashboard | Comparar presupuesto, compromisos, facturas, facturación por avance y rentabilidad del proyecto. |
| Coffee Shop Operations Audit Toolkit | Evaluar el desempeño operativo de la cafetería mediante puntuación de auditoría estandarizada y análisis de KPI. |

---

## Aviso legal

Este libro de trabajo está destinado a ser una herramienta analítica de apoyo a la decisión.

No constituye:

- asesoramiento legal,
- asesoramiento de préstamo,
- aprobación de suscripción,
- orientación contable,
- certificación de cumplimiento normativo,
- recomendación de inversión.

Todas las decisiones de préstamo siguen sujetas a las políticas de suscripción de la institución de préstamo, las regulaciones aplicables, los requisitos de los inversores y la aprobación de crédito final.

Los usuarios son responsables de verificar todos los supuestos, parámetros de precio, calendarios de comisiones y reglas de suscripción antes de confiar en las salidas generadas.

---

## Agradecimientos

Este proyecto refleja las prácticas de suscripción comunes utilizadas en los préstamos residenciales transitorios, incluidos los préstamos puente, el financiamiento Fix-and-Flip, los préstamos de rehabilitación y los préstamos de construcción residencial.

Su arquitectura enfatiza la transparencia, la repetibilidad y la consistencia operativa para que las decisiones de precio puedan reproducirse, revisarse y auditarse en lugar de depender del conocimiento individual de hojas de cálculo.

---

**Apache License 2.0 © 2026**

Construido como parte de una colección más amplia de herramientas operativas ligeras de apoyo a la decisión para finanzas, construcción, gestión de inventario y operaciones comerciales.
