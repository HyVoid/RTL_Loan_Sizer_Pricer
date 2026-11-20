[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# RTL Loan Sizer & Pricer: calculadora gratuita de préstamos residenciales transitorios y plantilla Excel de suscripción para Fix-and-Flip
<img width="1245" height="1209" alt="image" src="https://github.com/user-attachments/assets/856c2ddf-16a5-4212-a162-b3e82ab67dcc" />


![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser Web App and Offline Excel Workbook](https://img.shields.io/badge/Platform-Browser%20%7C%20Excel-success)
![Category: RTL Underwriting and Loan Pricing Tool](https://img.shields.io/badge/Tool-Decision%20Support-orange)
![Release Status: Production Stable](https://img.shields.io/badge/Version-Stable-brightgreen)

**RTL Loan Sizer & Pricer** es una **calculadora de préstamos residenciales transitorios (RTL)** lista para usar, un **motor de precios para préstamos Fix-and-Flip** y una **plantilla Excel de suscripción hard money**. Úsela para dimensionar préstamos Bridge, Rehabilitación Ligera, Rehabilitación Profunda y Construcción desde cero, validar los límites de LTV, LTC, LTP y LTARV, verificar el spread de rendimiento del prestamista frente a su tasa de compra y calcular el Cash-to-Close del prestatario en menos de un minuto. Pruebe la herramienta de navegador gratis en línea sin registro, o compre una sola vez el libro de Excel sin conexión reutilizable con una garantía de devolución de dinero de 30 días sin preguntas.

> **Herramienta en línea gratuita (pruébela de inmediato en su navegador)**  
> [Lance la calculadora de préstamos RTL gratuita en el navegador (dimensionador instantáneo de préstamos Fix-and-Flip y Bridge)](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/)
>
> **Hoja de cálculo sin conexión reutilizable (compra única, garantía de devolución de dinero de 30 días)**  
> [Obtenga la plantilla Excel reutilizable y sin conexión de RTL Loan Sizer & Pricer en Theseus Workshop](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## Puntos críticos de la suscripción de préstamos residenciales transitorios y soluciones automatizadas

Las operaciones de crédito privado se estancan cuando los límites de apalancamiento, los ajustes de tasa por nivel crediticio y las deducciones al cierre se revisan en hojas de cálculo separadas. Esta herramienta de suscripción RTL asigna cada brecha de cálculo común directamente a resultados automatizados:

| Punto crítico del crédito hard money y RTL | Solución automatizada en este RTL Loan Sizer | Métricas y resultados clave de suscripción supervisados |
| :--- | :--- | :--- |
| **Cotizar operaciones no elegibles antes de la revisión crediticia** | Comprueba cada operación automáticamente contra los topes configurados de su programa antes de emitir una hoja de términos | Estado de elegibilidad Aprobado / Excepción / Rechazado en los programas Bridge, Rehabilitación y Construcción |
| **Calcular a mano solo una relación de apalancamiento** | Evalúa simultáneamente las cuatro restricciones de dimensionamiento de préstamos residenciales transitorios y vincula el préstamo al límite más estricto | **LTV** (Loan-to-Value), **LTC** (Loan-to-Cost), **LTP** (Loan-to-Purchase) y **LTARV** (Loan-to-After-Repair-Value) |
| **Sorpresas tardías en el Cash-to-Close del prestatario** | Deduce de antemano los puntos de originación, los intereses prepagados y las comisiones de servicio durante el dimensionamiento inicial de la operación | **Producto neto del financiamiento**, **Cash-to-Close** total, estructura de retención del presupuesto de rehabilitación y verificación de reserva de liquidez |
| **Tasas inconsistentes entre originadores de préstamos** | Extrae los ajustes de precios de una única matriz de tasas centralizada vinculada a los niveles de puntaje crediticio y de apalancamiento | **Precios por nivel FICO**, ajustes por experiencia del prestatario y salida estandarizada de la tasa nominal |
| **Erosión oculta del margen por debajo de la tasa de compra** | Señala de inmediato cualquier tasa nominal solicitada que caiga por debajo de su piso interno de spread de rendimiento | **Tasa de compra del prestamista**, **validación del spread mínimo** y estado de protección del margen neto |
| **Ensamblaje manual lento de cotizaciones en picos de volumen** | Consolida entradas, reglas de suscripción y cálculos de cierre en una vista formateada lista para el cliente | **Quote Summary** lista para enviar y desglose preliminar de los términos del préstamo |

---

## Guía de inicio rápido: dimensione y fije el precio de un préstamo Fix-and-Flip o Bridge en 4 pasos

Puede ejecutar un escenario de prueba ahora mismo en la [aplicación web gratuita RTL Loan Sizer](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) y luego trasladar su flujo diario de operaciones al libro de Excel sin conexión una vez que confirme que se ajusta a sus directrices de crédito.

### Paso 1. Configure sus reglas de suscripción y su cuadrícula de precios una sola vez

Configure sus parámetros de préstamo en la hoja de cálculo **Pricing & Assumptions**. Introduzca sus límites máximos de apalancamiento (LTV, LTC, LTP, LTARV), las cuadrículas de precios FICO, los puntos de originación, las comisiones de servicio, los requisitos mínimos de spread del prestamista y los programas de préstamo admitidos. Tras la configuración inicial, solo actualizará esta pestaña cuando su socio de capital o su comité de crédito cambie las directrices.

### Paso 2. Pegue los datos de la operación del prestatario y de la propiedad en Inputs

Abra la hoja de cálculo **Inputs** e introduzca los datos de la operación:

- Precio de compra y valor de la propiedad As-Is
- Presupuesto de rehabilitación / construcción y valor después de reparaciones (ARV)
- Monto del préstamo solicitado y plazo del préstamo
- Puntaje FICO del prestatario, experiencia previa en Fix-and-Flip y activos líquidos verificados
- Tasa nominal solicitada y programa de préstamo seleccionado (Bridge, Rehabilitación Ligera, Rehabilitación Profunda o Construcción)

Los menús desplegables integrados y la validación de datos bloquean las entradas no válidas. El formato condicional atenúa los campos que no aplican al programa de préstamo elegido.

### Paso 3. Lea los resultados automatizados de suscripción, precios y Cash-to-Close

Abra la hoja de cálculo **Quote Summary** para revisar el desglose completo de la operación en un solo lugar:

- Veredicto de elegibilidad del préstamo y alertas de excepción
- Métricas de apalancamiento vinculantes (LTV, LTC, LTP y LTARV)
- Validación de la tasa frente a la tasa de compra y las reglas de spread mínimo
- Intereses prepagados, estimaciones de liquidación, producto neto del financiamiento y Cash-to-Close del prestatario

### Paso 4. Cambie al libro de Excel sin conexión reutilizable para las operaciones del flujo diario

El dimensionamiento de préstamos residenciales transitorios implica una lógica de suscripción de múltiples capas, y sin embargo nunca necesita escribir una sola fórmula, depurar referencias de celda rotas ni arrastrar ecuaciones columna abajo con doble clic. Cada regla coincidente y fórmula de actualización automática viene preconstruida dentro de la plantilla de Excel.

Descargue el libro a su computadora, pegue las cifras de sus propias operaciones en las celdas de entrada y vea decisiones de suscripción claras en menos de un minuto. Incluso un principiante sin experiencia en modelado de hojas de cálculo obtiene de inmediato un análisis comercial estructurado, liberando horas de temporada alta para llamadas a corredores, negociaciones con prestatarios y cierres de operaciones.

**Por qué los equipos de crédito pasan de la prueba gratuita del navegador al libro de Excel sin conexión de pago:**

- **Compra única, reutilización ilimitada:** Pague una sola vez en lugar de pagar suscripciones mensuales recurrentes a SaaS para sistemas empresariales de originación de préstamos (LOS) o motores de precios en la nube. Reemplace las entradas y reutilice el mismo flujo fijo para cada operación Bridge, Fix-and-Flip, Rehabilitación y Construcción.
- **Privacidad de datos 100% local:** Guarde y ejecute el archivo sin conexión en su propia máquina. Los datos financieros sensibles de los prestatarios, las tasas de compra internas y los pisos de spread del prestamista nunca se alojan en servidores en la nube de terceros.
- **Garantía sin riesgo:** La versión de navegador es gratuita para probar en línea. El libro de Excel descargable es un producto de pago respaldado por una **garantía de devolución de dinero de 30 días sin preguntas**.

> **¿Listo para estandarizar su flujo de suscripción sin conexión?**  
> [Descargue la plantilla Excel reutilizable y sin conexión de RTL Loan Sizer & Pricer (compra única, garantía de devolución de dinero de 30 días)](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan)

---

## La lógica de negocio y la metodología: cómo la suscripción RTL automatizada evita puntos ciegos ocultos en las decisiones

La mayoría de los errores de precios en el crédito inmobiliario privado ocurren mucho antes de que el expediente del préstamo llegue al comité de crédito. Incluso los originadores experimentados cometen errores de cotización costosos cuando calculan las relaciones una por una en hojas desconectadas. Para los recién llegados al crédito hard money o al financiamiento Fix-and-Flip, cuatro puntos ciegos comerciales específicos terminan silenciosamente con operaciones o con el beneficio del prestamista.

### 1. El punto ciego de la relación única (por qué un LTV aprobado puede aun así fallar la suscripción)

**Hecho objetivo:** Un préstamo Fix-and-Flip que parece seguro con un LTV As-Is del 75% puede aun así incumplir un tope de LTC del 90% o un tope de LTARV del 70% cuando se incluye un presupuesto de rehabilitación grande.  
**Cómo lo resuelve este modelo:** El motor de dimensionamiento calcula LTV, LTC, LTP y LTARV en paralelo y aplica el monto de préstamo mínimo permitido entre las cuatro relaciones. Usted ve la restricción vinculante exacta antes de cotizar términos a un prestatario.

### 2. El punto ciego de tasa frente a spread (ganar la operación mientras se pierde el margen)

**Hecho objetivo:** Igualar la tasa nominal de un competidor para ganar a un prestatario a menudo empuja el préstamo por debajo de su tasa de compra interna o del spread de rendimiento mínimo después de aplicar los ajustes de precio por FICO y apalancamiento.  
**Cómo lo resuelve este modelo:** Cada tasa nominal cotizada se comprueba automáticamente contra su matriz centralizada de tasas de compra y el requisito de spread mínimo. Si una operación viola su piso de beneficio, la hoja la señala de inmediato para que pueda repreciarla o añadir puntos de originación antes de emitir una hoja de términos.

### 3. El punto ciego del Cash-to-Close (operaciones que mueren días antes del cierre)

**Hecho objetivo:** Los prestatarios primerizos y los procesadores junior suelen asumir que el enganche equivale al efectivo total necesario. Los intereses prepagados, las comisiones de originación, los cargos de servicio y las reglas de reserva de liquidez reducen el producto neto del financiamiento y aumentan el efectivo requerido al cierre.  
**Cómo lo resuelve este modelo:** El libro calcula el financiamiento neto del préstamo, las deducciones iniciales y el Cash-to-Close total del prestatario desde el primer día. Los prestatarios conocen de inmediato su requisito real de efectivo, lo que reduce las cancelaciones tardías.

### 4. El punto ciego de la fuga de precios (exposición de tasas de compra propietarias)

**Hecho objetivo:** Entregar una hoja de cálculo de precios sin bloquear a corredores externos o representantes junior expone sus tasas de compra mayoristas, sus costos de capital y sus reglas internas de margen.  
**Cómo lo resuelve este modelo:** Las tablas de precios y las fórmulas de spread residen en una pestaña de supuestos dedicada que puede bloquearse y ocultarse en las versiones orientadas al originador, manteniendo privada la economía sensible mientras se conserva la cotización de autoservicio rápida.

### Cambio real del flujo de trabajo: antes vs. después

**Antes (cotización manual)**
1. El originador comprueba el LTV As-Is en una calculadora rápida y envía una cotización verbal al prestatario.
2. La revisión de suscripción descubre más tarde un incumplimiento de LTARV y un spread insuficiente por debajo de la tasa de compra del prestamista.
3. El equipo revisa la cotización a la baja y aumenta el Cash-to-Close requerido del prestatario.
4. La confianza del prestatario cae, los retrasos en el cierre se acumulan y el personal interno pasa horas rehaciendo un expediente.

**Después (flujo de trabajo automatizado del RTL Loan Sizer)**
1. El originador introduce una sola vez los números de la propiedad, el presupuesto de rehabilitación y el FICO del prestatario.
2. El libro comprueba los topes de apalancamiento, el piso de spread, las deducciones de liquidación y las reservas de liquidez simultáneamente en segundos.
3. El equipo sabe de inmediato si la operación pasa sin problemas, requiere una excepción de la gerencia o debe rechazarse antes de enviar una cotización.

---

## Cotización manual hard money vs. RTL Loan Sizer automatizado: comparación operativa

| Cuello de botella del crédito residencial transitorio | Riesgo de hojas de cálculo improvisadas y cotización manual | Flujo de trabajo estandarizado del RTL Loan Sizer |
| :--- | :--- | :--- |
| **Dimensionamiento con una sola relación** | Aprobar solo con el LTV pasa por alto los topes de las directrices de LTC, LTP o LTARV hasta la revisión del comité de crédito | Evalúa LTV, LTC, LTP y LTARV simultáneamente y aplica el tope vinculante del préstamo antes de cotizar |
| **Consultas manuales de hojas de tasas** | Oficiales de crédito distintos cotizan tasas y puntos contradictorios para perfiles FICO y de apalancamiento idénticos | Extrae tasas y ajustes uniformes de una única cuadrícula de precios centralizada por FICO y apalancamiento |
| **Compresión de margen inadvertida** | Los préstamos pasan las comprobaciones de apalancamiento mientras se fijan en silencio por debajo de la tasa de compra interna y los pisos de spread de rendimiento | La validación de spread integrada señala de inmediato cualquier cotización por debajo de los requisitos mínimos de margen del prestamista |
| **Cash-to-Close inesperado del prestatario** | Los intereses prepagados, los puntos de originación y las deducciones de servicio aparecen tarde, cerca de la mesa de cierre | Calcula el producto neto del financiamiento, las deducciones de liquidación y el Cash-to-Close durante la estructuración inicial |
| **Descubrimiento tardío de excepciones de suscripción** | Las múltiples revisiones de la hoja de términos estancan el flujo de suscripción y frustran a los corredores | Resalta las excepciones de política de inmediato para una aprobación gerencial estructurada |
| **Lógica de precios mayorista expuesta** | Los libros manuales compartidos filtran tasas de compra internas y márgenes de beneficio a terceros | Separa los supuestos de precios protegidos de las hojas de entrada del originador y del resumen de cotización |

---

## Quién usa esta calculadora de préstamos RTL: casos de uso por rol para prestamistas privados, corredores y equipos hard money

Esta herramienta encaja en flujos de trabajo diarios específicos de la industria del crédito residencial transitorio, sin requerir habilidades de modelado en hojas de cálculo ni un despliegue pesado de software empresarial:

| Rol / puesto | Necesidad principal de búsqueda y flujo de trabajo | Cómo usan el RTL Loan Sizer & Pricer |
| :--- | :--- | :--- |
| **Prestamistas hard money y de dinero privado** | Hoja de cálculo de precios de préstamos hard money y motor de dimensionamiento de operaciones | Aplicar topes consistentes de LTV/LTC/LTARV y proteger el spread mínimo del prestamista en cada cotización |
| **Corredores hipotecarios y originadores de préstamos (LO)** | Generador de cotizaciones de préstamos Fix-and-Flip y herramienta de precalificación de prestatarios | Convertir números crudos de la propiedad y presupuestos de rehabilitación en hojas de términos claras para el prestatario en menos de un minuto |
| **Procesadores de préstamos y coordinadores de transacciones** | Calculadora de Cash-to-Close y financiamiento neto para préstamos Bridge | Verificar intereses prepagados, comisiones de servicio, liquidez del prestatario y producto neto antes de solicitar los documentos de cierre |
| **Analistas de crédito y suscriptores** | Verificador de elegibilidad de préstamos RTL y plantilla de detección de excepciones | Auditar los límites de apalancamiento de múltiples relaciones y señalar operaciones fuera de política antes de la revisión del comité de crédito |
| **Equipos de mercados de capital y mesa secundaria** | Validación de tasas de compra y modelo de spread de rendimiento del prestamista | Mantener cuadrículas de precios centralizadas y confirmar que el precio a nivel de préstamo supere los umbrales de venta secundaria |
| **Pequeñas firmas de crédito privado y fondos de deuda boutique** | Alternativa ligera al LOS en un libro de Excel | Estandarizar la suscripción Bridge, Rehabilitación Ligera, Rehabilitación Profunda y Construcción desde cero sin tarifas de SaaS empresariales |
| **Inversores inmobiliarios y house flippers** | Analizador de operaciones hard money apto para principiantes | Estimar el producto máximo del préstamo y el efectivo total requerido al cierre antes de presentar una solicitud de préstamo |

**Nota de alcance:** Este libro está construido específicamente para el dimensionamiento de préstamos de front-end, la validación de elegibilidad, las comprobaciones de precios y la generación de cotizaciones. El servicio del préstamo, la contabilidad de desembolso de partidas y la gestión del cumplimiento normativo permanecen en plataformas dedicadas de servicio y cumplimiento.

---

## Preguntas frecuentes (dimensionamiento RTL y plantilla Excel)

<details>
<summary><strong>¿Cuál es la diferencia entre LTV, LTC, LTP y LTARV en un préstamo residencial transitorio?</strong></summary>

- **LTV (Loan-to-Value):** Monto del préstamo dividido por el valor de tasación As-Is actual de la propiedad.
- **LTP (Loan-to-Purchase):** Desembolso inicial de adquisición dividido por el precio de compra contractual.
- **LTC (Loan-to-Cost):** Monto total del préstamo dividido por el costo total del proyecto (precio de compra más presupuesto de rehabilitación).
- **LTARV (Loan-to-After-Repair-Value):** Monto total del préstamo dividido por el valor después de reparaciones (ARV) proyectado una vez finalizadas las renovaciones.

Como los prestamistas hard money limitan las cuatro relaciones simultáneamente, el monto de préstamo resultante más bajo define su tamaño máximo de préstamo elegible.
</details>

<details>
<summary><strong>¿Necesito conocimientos avanzados de Excel para usar la plantilla sin conexión?</strong></summary>

No. Todas las cuadrículas de precios, las fórmulas de apalancamiento y las comprobaciones condicionales vienen preconfiguradas. Solo pega las entradas de la operación en las celdas designadas de la pestaña **Inputs** y lee los resultados en la pestaña **Quote Summary**.
</details>

<details>
<summary><strong>¿Cuál es la diferencia entre la versión gratuita de navegador y la versión de Excel de pago?</strong></summary>

La [calculadora de préstamos RTL gratuita en el navegador](https://hyvoid.github.io/RTL_Loan_Sizer_Pricer/) le permite probar la lógica de suscripción en línea de inmediato sin necesidad de cuenta. El [libro de Excel sin conexión de pago](https://www.theseusworkshop.com/l/okqdlp?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=residential-transitional-loan) le proporciona un archivo local permanente que puede personalizar con sus propias cuadrículas de precios, guardar por operación, reutilizar indefinidamente con un pago único (con garantía de devolución de dinero de 30 días) y mantener completamente fuera de los servidores en la nube de terceros.
</details>

---

## Acerca de Theseus Workshop

**Theseus Workshop** crea libros de análisis ligeros y reutilizables para decisiones de negocio y de crédito donde interactúan demasiadas variables financieras a la vez. Cada plantilla empaqueta lógica probada de suscripción y análisis comercial en un flujo de trabajo de Excel sin conexión limpio, para que los equipos pequeños y los operadores individuales alcancen decisiones consistentes y defendibles en minutos.

El **RTL Loan Sizer & Pricer** pone los límites de suscripción, las reglas de precios de la tasa de compra, la validación de apalancamiento, las deducciones de liquidación y las salidas de cotización para el cliente en una sola pantalla, de modo que siempre sepa si una operación funciona antes de comprometer capital.

¿Busca más modelos financieros de Excel sin conexión listos para usar, motores de precios y herramientas operativas de apoyo a la decisión?  
[Explore el catálogo completo de plantillas Excel de negocios y finanzas sin conexión en Theseus Workshop (theseusworkshop.com)](https://www.theseusworkshop.com)

## Detalles técnicos

<details>
<summary><strong>Para revisores técnicos, profesionales de Excel y colaboradores</strong></summary>

---

## Arquitectura del libro

El libro sigue una arquitectura en capas que separa la interacción del usuario, las reglas de negocio, los cálculos analíticos y la presentación. Esto evita modificaciones accidentales de la lógica de precios mientras mantiene la operación diaria simple para los originadores de préstamos.

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
| 02_Inputs | Información del prestatario y términos del préstamo solicitados | Sí |
| 03_Pricing_&_Assumptions | Cuadrículas de tasa de compra, reglas de apalancamiento, supuestos de precios | Solo administradores |
| 04_Calc_Engine | Cálculos de suscripción, motor de precios y validación | No |
| 05_Quote_Summary | Hoja de términos imprimible para el cliente | No |

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

Cada salida mostrada al usuario proviene del motor de cálculo. Ningún valor se introduce manualmente en la cotización final.

---

## Estrategia de seguridad

El libro se compila intencionalmente en dos formatos de distribución.

| Versión | Usuarios previstos | Componentes protegidos |
|---------|----------------|----------------------|
| Versión interna | Principales, suscriptores, operaciones | Todas las hojas visibles con contraseña de administrador |
| Versión del originador | Originadores de préstamos | Tablas de precios y motor de cálculo ocultos con xlSheetVeryHidden |

Las medidas de protección adicionales incluyen:

- Protección de la estructura del libro
- Fórmulas ocultas
- Celdas de cálculo bloqueadas
- Cuadrículas de precios protegidas
- Barra de fórmulas oculta (versión del originador)
- Estructura de hojas protegida por contraseña

Este enfoque protege los precios propietarios del prestamista sin mantener dos libros independientes.

---

## Tres trampas que atrapan incluso a los originadores de préstamos experimentados

---

## Trampa 1 — Mirar solo el LTV

Muchos prestamistas se centran instintivamente en el Loan-to-Value porque es la métrica de suscripción más familiar.

Desafortunadamente, el crédito transitorio rara vez depende de una sola relación de apalancamiento.

### Decisión incorrecta

Precio de compra

```
$400,000
```

Préstamo solicitado

```
$320,000
```

Valor As-Is

```
$420,000
```

LTV calculado

```
76.2%
```

El originador concluye:

> "El préstamo se ajusta a la política."

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

El préstamo en realidad está fuera de las directrices de crédito.

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

El libro evalúa automáticamente todas las relaciones de apalancamiento juntas antes de asignar un estado Aprobado, Excepción o Fallido.

---

## Trampa 2 — Cotizar antes de comprobar el margen

Un prestatario solicita una tasa atractiva.

El originador baja la tasa nominal para mantenerse competitivo.

Todo parece aceptable.

Más tarde...

El marketing secundario descubre que el spread del prestamista ha caído por debajo de los mínimos internos.

La cotización debe revisarse.

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

La operación en realidad está por debajo de los requisitos de rentabilidad del prestamista.

### Enfoque correcto

Cada cotización debe validar los precios antes de presentarse.

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

En lugar de descubrir el problema en la revisión final, el libro señala de inmediato:

```
Below Margin
```

lo que permite corregir el precio antes de que el prestatario reciba una cotización.

---

## Trampa 3 — Subestimar el efectivo requerido al cierre

Muchos prestatarios evalúan solo el monto del préstamo solicitado.

Los costos de liquidación reducen el producto real.

Ignorar estas deducciones con frecuencia produce expectativas poco realistas del prestatario.

### Ejemplo

Préstamo solicitado

```
$450,000
```

Interés corto (Short Interest)

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

Cash-to-Close real

```
$26,500
```

Si la liquidez del prestatario equivale solo a

```
$18,000
```

el préstamo no puede cerrar sin fondos adicionales.

### Enfoque correcto

Calcule el producto de liquidación en lugar de asumir que el monto bruto del préstamo equivale al financiamiento disponible.

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

El libro identifica la falta de liquidez antes de preparar los documentos de cierre.

---

## Escenario de ejemplo

Considere la siguiente operación Fix-and-Flip.

| Concepto | Valor |
|------|------:|
| Precio de compra | $300,000 |
| Presupuesto de rehabilitación | $70,000 |
| Valor As-Is | $310,000 |
| ARV | $465,000 |
| Préstamo solicitado | $340,000 |
| FICO | 726 |
| Experiencia | 6+ Proyectos |
| Tasa nominal | 11.25% |
| Plazo del préstamo | 12 Meses |

El motor de precios recupera la tasa de compra correspondiente según el nivel FICO del prestatario y el apalancamiento calculado.

El motor de cálculo determina entonces:

- LTV real
- LTC real
- LTP real
- LTARV real
- Spread
- Financiamiento neto
- Cash-to-Close
- Beneficio estimado del prestamista

Suponga que las métricas resultantes son:

| Métrica | Resultado |
|---------|-------:|
| LTV | 109.7% |
| LTC | 91.9% |
| LTARV | 73.1% |
| Spread | 3.10% |
| Elegibilidad | Excepción requerida |

Aunque los precios siguen siendo rentables, el apalancamiento excede el umbral preferido de LTV.

En lugar de rechazar el préstamo de inmediato, el libro lo clasifica como **Excepción requerida**, permitiendo que la gerencia revise factores compensatorios como la experiencia del prestatario, la liquidez o garantías adicionales.

Este flujo de trabajo estructurado crea un proceso de suscripción consistente donde los precios, el apalancamiento, la liquidación y la rentabilidad se evalúan juntas en lugar de forma independiente.

---

## Referencia de fórmulas

<details>

<summary>Cálculos de apalancamiento</summary>

| Cálculo | Fórmula |
|-------------|---------|
| LTV real | `Monto del préstamo ÷ Valor As-Is` |
| LTC real | `Monto del préstamo ÷ (Compra + Rehabilitación)` |
| LTP real | `Monto del préstamo ÷ Precio de compra` |
| LTARV real | `Monto del préstamo ÷ ARV` |

</details>

<details>

<summary>Motor de precios</summary>

| Fórmula | Propósito |
|----------|----------|
| XLOOKUP | Recuperar la tasa de compra |
| INDEX + MATCH | Consulta de precios heredada |
| Spread | Tasa nominal − Tasa de compra |
| Spread Status | Validación de margen |

Los precios siempre utilizan un comportamiento de búsqueda exacto con manejo de errores predeterminado para evitar salidas de precios no válidas.

</details>

<details>

<summary>Cálculos de liquidación</summary>

| Cálculo | Propósito |
|-------------|----------|
| Short Interest | Interés cobrado al cierre |
| Servicing Fee | Comisión deducida durante el plazo del préstamo |
| Net Funding | Fondos disponibles para el prestatario |
| Cash to Close | Aportación adicional del prestatario |
| Liquidity Shortfall | Déficit de financiamiento |

</details>

<details>

<summary>Reglas de elegibilidad</summary>

El motor de suscripción evalúa:

- LTV máximo
- LTC máximo
- LTARV máximo
- Margen de precios
- Liquidez del prestatario

Posibles resultados:

- PASS
- EXCEPTION NEEDED
- FAIL

La elegibilidad general siempre refleja el resultado de suscripción más restrictivo.

</details>

## Reglas de validación

| Campo | Regla de validación | Comportamiento ante errores |
|------|-----------------|----------------|
| Tipo de préstamo | Solo menú desplegable | Rechaza valores no válidos |
| Precio de compra | Mayor que cero | Devuelve cálculos en cero |
| Valor As-Is | Mayor que cero | Evita la división por cero |
| Presupuesto de rehabilitación | Cero para préstamos Bridge | Campo atenuado automáticamente |
| ARV | Requerido para productos de rehabilitación | Muestra N/A donde aplica |
| Préstamo solicitado | Moneda positiva | Rechaza valores negativos |
| FICO | 300–850 | Rechaza puntajes no válidos |
| Nivel de experiencia | Solo menú desplegable | Evita fallos de búsqueda |
| Plazo del préstamo | 12 / 18 / 24 meses | Rechaza otros valores |
| Días de interés corto | 0–30 | Rechaza entradas no válidas |
| Búsqueda de tasa de compra | XLOOKUP con valor alternativo | "Check Risk Rules" |
| Operaciones de división | Envoltura IFERROR | Devuelve 0 en lugar de errores de Excel |
| Búsquedas de texto | TRIM + UPPER | Evita discrepancias de espacios y mayúsculas |
| Comprobación de margen | Comparación con el spread mínimo | Devuelve "Below Margin" |
| Elegibilidad | Evalúa todas las alertas de suscripción | PASS / EXCEPTION NEEDED / FAIL |

</details>
---

## Otras herramientas de esta serie

El **RTL Loan Sizer / Pricer** forma parte de una colección creciente de herramientas ligeras de apoyo a la decisión operativa, creadas para profesionales que necesitan análisis confiables sin implementar software empresarial.

Cada herramienta sigue los mismos principios:

- **[rolling-cashflow-forecast](https://github.com/HyVoid/rolling-cashflow-forecast)** — ¿Por qué siempre falta efectivo? — Proyecte la liquidez futura bajo supuestos operativos y financieros cambiantes.
- **[Multi-Currency-Trade-Financial-Analyzer](https://github.com/HyVoid/Multi-Currency-Trade-Financial-Analyzer)** — ¿Qué flujos comerciales son realmente rentables tras los efectos cambiarios? — Mida la rentabilidad de operaciones multimoneda en entornos transfronterizos.
- **[Personal-Business-Dual-Track-Budget-Manager](https://github.com/HyVoid/Personal-Business-Dual-Track-Budget-Manager)** — ¿Dónde se mezclan o se malasignan el efectivo personal y el del negocio? — Separe los flujos de efectivo personal y comercial en presupuestos de seguimiento independientes.
- **[Multifamily-Value-Add-Acquisition-Model](https://github.com/HyVoid/Multifamily-Value-Add-Acquisition-Model)** — ¿Esta adquisición inmobiliaria sigue creando valor patrimonial tras los supuestos de renovación y operación? — Evalúe los rendimientos de adquisición multifamiliar bajo financiamiento de renovación y escenarios operativos.
- **[Real-Estate-Valuation-all-in-one-calculator](https://github.com/HyVoid/Real-Estate-Valuation-all-in-one-calculator)** — ¿Cuánto vale una propiedad bajo distintos métodos de valoración? — Calcule el valor de la propiedad mediante múltiples métodos de valoración con modelado de impuestos y gastos de capital.
- **[multi-entity-expense-allocation](https://github.com/HyVoid/multi-entity-expense-allocation)** — ¿Se asignan los costos compartidos de forma justa entre entidades, o algunos activos están sobrecargados mientras otros escapan de su exposición real de costos? — Distribuya facturas de proveedores entre múltiples entidades legales y activos operativos usando metodologías de asignación configurables.
- **[investment-pool-nav-excel-template](https://github.com/HyVoid/investment-pool-nav-excel-template)** — ¿Cuánto se le debe realmente a cada participante según el momento de su entrada y el valor actual del fondo? — Realice un seguimiento continuo de la propiedad en fondos de inversión mediante contabilidad de unidades basada en NAV.
- **[shopify-cash-flow-forecast-excel-toolkit](https://github.com/HyVoid/shopify-cash-flow-forecast-excel-toolkit)** — ¿Qué compromisos operativos crearán un problema de efectivo en las próximas doce semanas? — Conecte ventas de Shopify, transacciones bancarias, gasto publicitario y compras de inventario en un marco unificado de decisiones de flujo de efectivo.
- **[Revenue-Management-Decision-Engine](https://github.com/HyVoid/Revenue-Management-Decision-Engine)** — ¿Ha cambiado suficiente información significativa como para justificar un ajuste de precios? — Gobierne las recomendaciones de precios mediante barreras de protección configurables que eviten volatilidad innecesaria de ingresos.
- **[amazon-wbr-sqp-analytics-template](https://github.com/HyVoid/amazon-wbr-sqp-analytics-template)** — ¿Qué cambió realmente en el negocio este periodo y qué productos o palabras clave impulsaron el cambio? — Transforme las exportaciones de Amazon Seller Central SQP y Sellerboard en revisiones empresariales ejecutivas estandarizadas.
- **[food-manufacturing-cost-calculator-excel](https://github.com/HyVoid/food-manufacturing-cost-calculator-excel)** — ¿Qué productos son realmente rentables después de asignar todos los costos de fabricación y cuáles están destruyendo el margen? — Asigne mano de obra de fábrica, servicios, overhead y costos de materiales a cada SKU para una verdadera economía unitaria de fabricación.
- **[ecommerce-profit-calculator-excel](https://github.com/HyVoid/ecommerce-profit-calculator-excel)** — ¿Qué pedidos son realmente rentables tras todos los costos ocultos y dónde se está fugando dinero entre canales y monedas? — Reconstruya la rentabilidad real a nivel de pedido conciliando pagos de ventas, costos de envío, comisiones de pago y comisiones de marketplace en operaciones de comercio electrónico multicanal.
- **[construction-job-costing-excel-template](https://github.com/HyVoid/construction-job-costing-excel-template)** — ¿Qué proyectos de contratistas y clientes son realmente rentables tras todos los costos de obra? — Conecte estimación inicial, ejecución de obra y seguimiento de costos reales en un marco unificado de rentabilidad del contratista.
- **[Flora-Pastry-Coffee-Shop-Operating-Control-System](https://github.com/HyVoid/Flora-Pastry-Coffee-Shop-Operating-Control-System)** — ¿Es la tienda realmente rentable después de todos los costos de ingredientes, mano de obra y operación? — Conecte costeo de recetas, ventas, consumo de inventario y gastos operativos en un marco unificado de rentabilidad y flujo de efectivo.
- **[freight-forwarder-job-costing-excel](https://github.com/HyVoid/freight-forwarder-job-costing-excel)** — ¿Qué reservas de flete son realmente rentables después de todos los costos, comisiones y conversión de moneda? — Mida la rentabilidad de flete a nivel de reserva conciliando ingresos, COGS, comisiones bancarias y costos de contenedor en transacciones multimoneda.
- **[cross-entity-logistics-console](https://github.com/HyVoid/cross-entity-logistics-console)** — ¿Qué contenedores y clientes son realmente rentables en las operaciones aduaneras y de flota? — Consolide el despacho aduanero y la ejecución de flota en una vista única de rentabilidad a nivel de contenedor.
- **[family-loan-tracker-excel](https://github.com/HyVoid/family-loan-tracker-excel)** — ¿Cuánto se debe realmente hoy tras años de transferencias e intereses acumulados? — Concilie transferencias de fondos a largo plazo y acumulación de intereses en un saldo pendiente actual.
- **[3-statement-financial-model-excel](https://github.com/HyVoid/3-statement-financial-model-excel)** — ¿Cómo se verán nuestros estados financieros bajo distintos escenarios operativos y de financiamiento? — Proyecte estados financieros integrados vinculando ingresos, gastos, capital de trabajo y deuda en un modelo unificado.
- **[assisted-living-cost-allocation-excel](https://github.com/HyVoid/assisted-living-cost-allocation-excel)** — ¿Cuánto del margen reportado de cada edificio lo genera realmente ese edificio frente a la forma en que se asignaron los costos corporativos? — Asigne gastos compartidos entre unidades operativas preservando las transacciones de origen y conciliando los resultados unitarios con los totales de la empresa.
- **[real-estate-development-feasibility-excel](https://github.com/HyVoid/real-estate-development-feasibility-excel)** — ¿A qué precio máximo de adquisición de terreno este proyecto de desarrollo se convierte en una inversión bancable? — Evalúe oportunidades de desarrollo residencial filtrando comparables de terreno, estimando costos de construcción y calculando umbrales de beneficio sobre costo.
- **[uk-residential-costing-software](https://github.com/HyVoid/uk-residential-costing-software)** — ¿Alcanzará realmente este proyecto de construcción su margen objetivo una vez considerados la logística de obra, los factores de desperdicio y los cambios en tarifas de oficios? — Separe las cantidades físicas de construcción de las tarifas volátiles de oficios y los preliminares de obra para aplicar markups comerciales en cascada a través de presupuestos de licitación y cotizaciones a clientes.
- **[b2b-pricing-landed-cost-excel-model](https://github.com/HyVoid/b2b-pricing-landed-cost-excel-model)** — ¿Qué precios mayoristas y segmentos de clientes preservan realmente el margen una vez costados totalmente el flete, los aranceles, los plazos de pago y el tipo de cambio? — Calcule costos landed a nivel de SKU, costo de servicio y cascadas de precio de margen de bolsillo para simular la rentabilidad mayorista transfronteriza.
- **[custom-label-pricing-calculator](https://github.com/HyVoid/custom-label-pricing-calculator)** — ¿Cuánto deberíamos cobrar por un pedido de etiquetas personalizadas en cada nivel de cantidad para mantenernos competitivos y rentables? — Calcule precios paramétricos de etiquetas modelando costos de sustrato por pulgada cuadrada, cargos de configuración y descuentos por nivel de cantidad frente a referencias de la competencia.
- **[landed-cost-calculator-retail-deduction-excel](https://github.com/HyVoid/landed-cost-calculator-retail-deduction-excel)** — ¿Cuál es el margen neto real de cada SKU una vez contabilizados los costos landed reales y las deducciones de los minoristas? — Concilie los costos landed estimados del PO contra cargos reales de flete, aranceles, tipo de cambio y acarreo, auditando las deducciones de remesa de los minoristas para exponer el margen neto a nivel de SKU.
- **[saas-finance-mrr-burn-rate-excel](https://github.com/HyVoid/saas-finance-mrr-burn-rate-excel)** — ¿Podemos asumir los compromisos de contratación, marketing y proveedores de esta semana sin quedarnos sin efectivo antes del cierre contable? — Siga el ritmo de quema semanal de efectivo, la varianza del waterfall MRR/ARR, las métricas de retención y los costos de nómina contra el presupuesto antes del cierre de mes.
- **[startup-financial-model-excel](https://github.com/HyVoid/startup-financial-model-excel)** — ¿Se quedará sin efectivo nuestro plan de crecimiento antes de que la monetización de las cohortes lo alcance? — Proyecte la quema de efectivo plurianual, el runway, la economía unitaria y la dilución por levantamiento de capital a partir de supuestos bottom-up de cohortes y plantilla.
- **[shopify-pnl-reconciliation-excel](https://github.com/HyVoid/shopify-pnl-reconciliation-excel)** — ¿Es realmente rentable cada tienda Shopify una vez conciliados los costos reales a nivel de SKU, los gastos compartidos y los cargos bancarios? — Concilie las exportaciones de ventas multitienda de Shopify contra el COGS a nivel de SKU, el OPEX multimoneda asignado y los estados bancarios para producir un P&L mensual confiable.
- **[travel-agency-accounting-excel-template](https://github.com/HyVoid/travel-agency-accounting-excel-template)** — ¿Qué reservas de tours generan realmente beneficio neto y flujo de efectivo positivo tras los costos de proveedores y las cobranzas B2B? — Calcule costos de operación por reserva de tour, márgenes brutos, liquidación AR/AP y flujo de efectivo operativo en múltiples monedas.

| Herramienta | Propósito |
|------|---------|
| Sistema de estimación de construcción | Estandarizar la estimación de proyectos, ensamblajes, precios de licitación y seguimiento de costos. |
| Planificador de pronóstico y reposición de inventario | Pronosticar la demanda de inventario, identificar el momento de reposición y monitorear el riesgo de existencias. |
| Libro de inventario minorista y maquila | Registrar el movimiento de inventario por pieza, producción, defectos y distribución. |
| Marco de presupuesto unificado personal y comercial | Consolidar el flujo de efectivo personal y comercial en un solo modelo de planificación financiera. |
| Panel de cumplimiento de VAT transfronterizo | Monitorear las obligaciones de VAT en múltiples países y canales de venta. |
| Panel de control financiero de proyectos | Comparar presupuesto, compromisos, facturas, facturación por avance y rentabilidad del proyecto. |
| Kit de auditoría de operaciones de cafeterías | Evaluar el desempeño operativo de cafeterías mediante puntuaciones de auditoría estandarizadas y análisis de KPI. |

---

## Aviso legal

Este libro está concebido como una herramienta analítica de apoyo a la decisión.

No constituye **de ninguna manera**:

- asesoría legal,
- asesoría de crédito,
- aprobación de suscripción,
- guía contable,
- certificación de cumplimiento normativo,
- recomendación de inversión.

Todas las decisiones de préstamo quedan sujetas a las políticas de suscripción de la institución de crédito, las regulaciones aplicables, los requisitos de los inversionistas y la aprobación crediticia final.

Los usuarios son responsables de verificar todos los supuestos, parámetros de precios, tablas de comisiones y reglas de suscripción antes de confiar en los resultados generados.

---

## Agradecimientos

Este proyecto refleja prácticas de suscripción comunes en el crédito residencial transitorio, incluidos los préstamos Bridge, el financiamiento Fix-and-Flip, los préstamos de rehabilitación y el crédito de construcción residencial.

Su arquitectura enfatiza la transparencia, la repetibilidad y la consistencia operativa, de modo que las decisiones de precios puedan reproducirse, revisarse y auditarse en lugar de depender del conocimiento individual de hojas de cálculo.

---

**Apache License 2.0 © 2026**

Construido como parte de una colección más amplia de herramientas ligeras de apoyo a la decisión operativa para finanzas, construcción, gestión de inventario y operaciones de negocio.
