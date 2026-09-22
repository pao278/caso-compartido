---
status: framed
segment: Cuentas Business Premium, sector tecnología, ≥100 licencias, ≥3 países, facturación >USD 100M (12.400 cuentas; 2,1M licencias). Equipos distribuidos, remotos o híbridos; reuniones convocadas y conducidas por Team Leads y mandos medios.
personas: valentina-ospina, rosa-elena-beltran, andres-villamizar
---

# Oportunidad: Colaboración en tiempo real durante las reuniones

Cuando una reunión de más de cinco personas necesita producir algo en conjunto (editar, priorizar, decidir), el grupo sale de Teams o deja el trabajo para después. Creemos que el Team Lead que la conduce paga ese costo durante la reunión (atención dispersa entre herramientas) y después (pasar a mano lo decidido); cuánto le cuesta está por validar. **Por qué ahora:** las señales del segmento están por encima del promedio de la base, el upgrade a Max está en 3,1% y CollabCon es en cinco meses.

> *Caso didáctico AFPM. Todas las cifras son ficticias y provienen del brief del caso; no representan datos reales de Microsoft.*

**Cómo llegó:** "Mejorar significativamente la colaboración y la interacción en tiempo real durante las reuniones y sesiones de trabajo, a través de herramientas colaborativas integradas". "Mejorar la colaboración" es un outcome y "a través de herramientas colaborativas integradas" es una solución: quedó aparcada en *Ideas candidatas*.

## Segmento y personas

- **Valentina Ospina (Team Lead) — sufre el problema directamente.** Hipótesis sintética de la persona: su tablero vive en Miro, varias personas lo abren en otra pestaña y pierden el hilo; la reunión se alargaría 15–20 min y dedicaría 30–40 min posteriores a pasar acuerdos a Jira y al correo. Estos tiempos no están comprobados.
- **Rosa Elena Beltrán (participante) — sufre la fragmentación de otra forma.** Hipótesis sintética: no sabe si debe abrir el enlace, pide acceso y se atrasa. Sirve para contrastar la creencia de que quien más sufre es quien conduce.
- **Andrés Villamizar (IT, comprador) — no sufre el problema en la reunión, pero lo paga.** Hipótesis sintética: herramientas duplicadas pagadas con tarjeta corporativa y datos fuera de su control. Pesa en la viabilidad porque decide compra y renovación.
- **Persona faltante:** participante experto que trabaja cómodo en Miro/FigJam (diseñador, PM facilitador), para quien el flujo externo podría funcionar bien. → Sugerencia: `/generate-personas` para cubrir el hueco.

## Signals

| Señal | Provenance | Fuente |
|---|---|---|
| 38% de las reuniones del segmento con más de 5 participantes comparten en el chat un enlace a Miro, Mural o FigJam; mientras dura, la actividad en Teams cae | unverified | Brief del ejercicio (segmento) |
| Whiteboard se abre en el 6% de las reuniones del segmento; en la mitad se cierra antes de 2 minutos | unverified | Brief del ejercicio (segmento) |
| 22% de los comentarios negativos post-reunión del segmento mencionan la colaboración en vivo ("terminamos en otra herramienta", "la pizarra es difícil de encontrar y nadie la usa", "pierdo tiempo pasando lo que decidimos a un documento después") | unverified | Brief del ejercicio (segmento) |
| 4.700 solicitudes en 12 meses; "colaboración durante reuniones" es la 3.ª categoría del portal de feedback | unverified | Brief del ejercicio (segmento) |
| "Colaboración" aparece en conversaciones sobre Max en renovaciones de cuentas grandes; sin registro de frecuencia | unverified | Ventas, vía brief del ejercicio (anecdótico) |
| Referencia de toda la base: 29% enlaces externos, Whiteboard 5%, 19% de quejas sobre colaboración | unverified | `product/overview.md` (toda la base, no el segmento) |
| Tiempos de Valentina (+15–20 min por reunión, 30–40 min posteriores) y confusión de Rosa con los enlaces | synthetic | `product/personas/` (hipotético) |

**Lectura de las señales (auditoría de evidencia):**
- **Contar.** Las cinco señales del segmento vienen de una sola fuente (el brief del ejercicio), aunque correspondan a cinco instrumentos distintos. No hay confirmación independiente.
- **Segmentar.** Las cifras del segmento no se mezclan con las de la base (38% se compara con 29%, no se suma). No sabemos si las 4.700 solicitudes son de cuentas únicas ni de qué rol.
- **Contradecir.** El 38% también se explica por un flujo externo que funciona. El cierre temprano de Whiteboard se explica igual por descubribilidad, por calidad o porque el material ya vive en otra herramienta. La caída de actividad en Teams es una correlación: no demuestra que el grupo pierda el hilo ni que la reunión se alargue.
- **Des-solucionar.** Las solicitudes más repetidas son soluciones ("editar un documento entre varios", "votar en vivo"); las necesidades de fondo son co-producir, decidir en grupo y mantener la atención del grupo.
- **Calibrar.** Respaldado: hay fricción visible en la colaboración dentro de las reuniones del segmento. Plausible: esa fricción cuesta tiempo al Team Lead y alarga las reuniones. No inferible todavía: que resolverla mueva el upgrade a Max.

## Business outcome

- **Principal: tasa de upgrade de Premium a Max en el segmento** (hoy 3,1% de las cuentas en 12 meses). Ingresos por licencia como consecuencia (USD 8 por usuario/mes).
- **Secundario: retención en la renovación**, vinculada a las creencias [product] [viability] del registro.
- No decide cómo se empaquetaría una futura solución.

## Constraints

- Presupuesto máximo: USD 5M.
- CollabCon tiene lugar en cinco meses (fecha exacta no confirmada). Es un dato de calendario, no un compromiso de que esta oportunidad produzca un feature.
- Decisión de seguir o no con el problema: 3 nov 2026 (seis semanas, decidido al enmarcar).
- Límites para cualquier solución: facilidad de uso, accesibilidad, compatibilidad con Microsoft 365, privacidad y seguridad corporativas, tiempo real, impacto mínimo en el rendimiento de la reunión.

## Beliefs

*Referencias a `product/overview.md`, registro único de creencias. El número es la posición en ese registro.*

**Registradas a nivel producto que esta oportunidad toca:**
- #1 [product] [value] Los Team Leads sacan la colaboración de Teams principalmente porque no descubren las funciones nativas.
- #2 [product] [value] El salto a herramientas externas es una fricción que quieren resolver, no un flujo que ya les funciona.
- #3 [product] [value] Quienes más sufren la fricción son los Team Leads que conducen, no los participantes.
- #4 [product] [viability] "El equipo ya usa otras herramientas" se refiere sobre todo a herramientas de colaboración en reuniones.
- #5 [product] [viability] Colaborar dentro de Teams reduce las bajas de plan y no renovaciones.

**Registradas por esta oportunidad** (umbrales = criterios propuestos de validación, provisionales):
- #6 [opportunity: colaboracion-tiempo-real-reuniones] [value] Los Team Leads del segmento que conducen reuniones de más de 5 personas pierden al menos 1 hora por semana entre el tiempo de reunión atribuible a salir de Teams y el registro posterior de lo decidido. *Criterio propuesto de validación:* si menos de la mitad de los Team Leads encuestados declara ese costo, el problema no es lo bastante grave para actuar.
- #7 [opportunity: colaboracion-tiempo-real-reuniones] [viability] La colaboración durante las reuniones es un motivo explícito de upgrade a Max en el segmento. *Criterio propuesto de validación:* aparece en al menos el 20% de las conversaciones de renovación donde se discute Max, y con más frecuencia en las cuentas con más reuniones grandes con enlaces externos; si no, la oportunidad no mueve el outcome principal.
- #8 [opportunity: colaboracion-tiempo-real-reuniones] [viability] Los compradores de IT del segmento consideran que concentrar la colaboración de las reuniones dentro de Microsoft 365 justifica pagar más (menos herramientas duplicadas, menos riesgo sobre los datos). *Criterio propuesto de validación:* si la mayoría de los entrevistados de IT no lo ve como razón de compra, la vía del upgrade se debilita.

**Prioridad propuesta (impacto × incertidumbre):** #7 → #6 → #1 → #2 → #3 → #8 → #4 → #5.

## Research agenda

| Creencia | Instrumento (de más barato a más caro) | Decisión que desbloquea | Para cuándo |
|---|---|---|---|
| #7, #4 | **Datos internos:** codificar notas de CRM de renovaciones del segmento (menciones de "colaboración" al discutir Max); cruzar historial de upgrade con frecuencia de enlaces externos por cuenta | Si la oportunidad sirve al upgrade (Max) o solo a la retención | 6 oct 2026 |
| #6, #3 | **Datos internos:** duración de reuniones con y sin enlace externo (correlación, no causa); 4.700 solicitudes y 22% de comentarios desglosados por cuentas únicas y por rol (conduce / participa) | Cuánto pesa el problema y para quién | 6 oct 2026 |
| #7, #8, #2 | **Secundaria** (`/research-market`): cómo empaquetan competidores y planes superiores la colaboración en reuniones; adopción de Miro/Mural/FigJam en empresas grandes | Si el mercado paga por resolver este problema dentro de la suite | 9 oct 2026 |
| #6, #2, #3 | **Encuesta** (`/design-survey`) a Team Leads y participantes del segmento: frecuencia, tiempo perdido, alternativa actual y satisfacción con ella; bloque de opt-in | Si el costo supera el criterio de #6 y si el flujo externo molesta o funciona | 27 oct 2026 |
| #1, #2, #8 | **Entrevistas** (`/design-interview`) con 8–10 Team Leads, 4 participantes y 3–4 responsables de IT, reclutados entre los opt-in; priorizando a quienes contradicen las creencias (p. ej., usuarios satisfechos con Miro) | El porqué de la salida (descubribilidad, calidad o material ya externo) y si IT lo ve como razón de compra | 3 nov 2026 |
| Todas | **Revisión de evidencia** | Pasar a `/clarify-idea`, priorizar sub-problema (durante vs. después de la reunión) o descartar | 3 nov 2026 |

## Candidate ideas (not evaluated)

- "Herramientas colaborativas integradas" (tal como llegó la asignación)
- Whiteboard nuevo o mejorado
- Integrar Miro, Mural o FigJam dentro de la reunión
- Coedición de documentos durante la llamada
- Votación o priorización en vivo
- Registro automático de decisiones y responsables
- Mejorar la descubribilidad de Whiteboard y de las notas de reunión
