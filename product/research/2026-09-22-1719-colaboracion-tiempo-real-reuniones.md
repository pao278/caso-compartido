---
source: secondary
method: web
date: 2026-09-22
question: ¿Cómo empaqueta y cobra el mercado la colaboración en reuniones (P1)? ¿Qué ofrecen Miro, Mural, FigJam y alternativas, y por qué las eligen frente a las nativas (P2)? ¿Qué tan adoptadas están en grandes empresas y pesa la consolidación como argumento de compra de TI (P3)? ¿Qué evidencia hay del costo de la fragmentación y del registro posterior, y cómo lo cambia la IA de reuniones (P4)?
opportunity: colaboracion-tiempo-real-reuniones
---

# Research: Colaboración en tiempo real durante las reuniones de Microsoft Teams

> **Dos mundos que este informe no mezcla.**
> - **Mercado real:** productos, precios y estudios con fuente externa y fecha de consulta (22-sep-2026).
> - **Caso AFPM:** el plan "Max", los USD 8 de upgrade, el 3,1% de upgrade del segmento, el 38% de enlaces externos y todas las cifras de `overview.md` y del brief son **ficticios**. No existe un plan "Max" de Microsoft 365.
>
> **Etiquetas de procedencia:**
> - `[verificado: URL — 2026-09-22]` para lo encontrado en fuentes web.
> - `[conocimiento del modelo — verificar]` para lo que viene de mi entrenamiento.
> - `[ficticio — caso AFPM]` para las cifras del ejercicio.
> - "desconocido" cuando no hubo fuente.
>
> **Tipo de fuente**, marcado en cada hallazgo:
> - **(E)** estudio publicado
> - **(P)** afirmación comercial o documentación del proveedor
> - **(Pr)** prensa o análisis de terceros
> - **(O)** opinión de usuarios, no representativa

## Resumen: los tres hallazgos que cambian decisiones

1. **En el mercado real, el problema de "después de la reunión" ya se está resolviendo con IA, y de forma cada vez más barata.**
   - Microsoft (Copilot con Facilitator, Teams Premium), Zoom (AI Companion sin costo adicional) y Google (Gemini "Take notes for me") ya capturan decisiones y próximos pasos.
   - La diferenciación se está moviendo de "tomar notas" a "ejecutar acciones".
   - Implicación para la oportunidad: el sub-problema de *durante* la reunión (co-producir, priorizar, decidir en grupo) está menos cubierto que el de *después* (pasar a mano lo decidido). Esto pesa en la decisión del 3-nov sobre qué sub-problema priorizar.
2. **Hay causas documentadas de la salida a herramientas externas distintas de la descubribilidad.** No se ha demostrado cuál predomina en el segmento, así que la creencia #1 queda no concluyente.
   - Whiteboard no ofrece en reunión las funciones de facilitación que Miro, Mural, FigJam y Lucidspark sí traen (timer, votación, modo privado).
   - Whiteboard y las notas colaborativas tienen límites documentados con participantes externos.
   - Microsoft está retirando la app independiente de Whiteboard.
   - Los problemas de descubribilidad que aparecen en foros se explican sobre todo por configuración del administrador o por la licencia.
3. **El dolor de TI con el gasto SaaS está bien documentado. La evidencia de que TI *pague más* por consolidar, no.**
   - Los informes del sector (patrocinados por vendedores de gestión de SaaS) muestran gasto fuera de TI y licencias sin uso.
   - Eso sostiene un argumento de **sustituir y ahorrar**, no de **pagar un sobreprecio**.
   - Las empresas siguen usando herramientas que se solapan con Microsoft 365.
   - La evidencia no permite determinar si TI pagaría un sobreprecio por una solución que aporte valor, ni si los clientes harían el upgrade. Las creencias #8 y #7 quedan no concluyentes.

---

## P1. Empaquetado y precio de la colaboración en reuniones

**Patrón real:** en todas las suites, la *colaboración básica* entra en el plan base y la *inteligencia de reunión con IA* va en un nivel superior o en un complemento.

- **En el plan base:** pizarra y notas colaborativas.
- **En nivel superior o complemento:** recap, notas automáticas, facilitación con IA.
- **Tendencia 2025–2026:** integrar la IA en el plan base y subir el precio de lista.

| Suite | Plan / complemento | Precio de lista (USD/usuario/mes, EE. UU.) | Colaboración en reunión que incluye | Fuente |
|---|---|---|---|---|
| Microsoft | M365 Business Basic | 7,00 (anual) | Reuniones de Teams, Copilot Chat. Loop y Whiteboard no aparecen en la ficha comercial | (P) [verificado: [compare-all business](https://www.microsoft.com/en-us/microsoft-365/business/compare-all-microsoft-365-business-products) — 2026-09-22] |
| Microsoft | Business Standard / Premium | 14,00 / 22,00 (sin Copilot) | Teams y Loop | (P) Standard: [verificado: [Business Standard](https://www.microsoft.com/en-us/microsoft-365/business/microsoft-365-business-standard-with-copilot) — 2026-09-22]. Premium 22: (Pr) [verificado: [universal.cloud](https://universal.cloud/en/blog/article/microsoft-365-prijsverhoging-juli-2026/) — 2026-09-22] |
| Microsoft | Business Standard / Premium **with Copilot** (SKU desde el 1-jul-2026) | 23,50 / 32,00 (anual) | Lo anterior más Copilot en Teams | (P) [verificado: [compare-all business](https://www.microsoft.com/en-us/microsoft-365/business/compare-all-microsoft-365-business-products) — 2026-09-22] |
| Microsoft | M365 E3 / E5 | 39 / 60 (anual) | Teams, Loop, Copilot Chat | (P) [verificado: [enterprise plans](https://www.microsoft.com/en-us/microsoft-365/enterprise/microsoft365-plans-and-pricing) — 2026-09-22] |
| Microsoft | Complemento **Teams Premium** | 10,00 | Intelligent recap, notas con IA, traducción en vivo, protección de reuniones | (P) [verificado: [Teams Premium](https://www.microsoft.com/en-us/microsoft-teams/premium) — 2026-09-22] |
| Microsoft | Complemento **Microsoft 365 Copilot** | 30,00 (anual) | Agente **Facilitator**: notas colaborativas en vivo, decisiones, acciones, agenda con temporizador | (P) [verificado: [Copilot enterprise](https://www.microsoft.com/en-us/microsoft-365/copilot/enterprise); [Facilitator — Learn](https://learn.microsoft.com/en-us/microsoftteams/facilitator-teams) — 2026-09-22] |
| Microsoft | Microsoft 365 Copilot Business (pymes) | 21,00 | "Capturing meeting notes" | (P) [verificado: [blog Microsoft, 2-dic-2025](https://www.microsoft.com/en-us/copilot/blog/2025/12/02/microsoft-365-copilot-business-the-future-of-work-for-small-businesses/) — 2026-09-22] |
| Google | Workspace Starter / Standard / Plus | 7 / 14 / 22 (anual) | Meet. "Take notes for me" desde Standard. **Sin pizarra nativa**: Jamboard cerró el 31-dic-2024 y Google remite a FigJam, Lucidspark y Miro | Precios: (Pr) [verificado: [cloudwards](https://www.cloudwards.net/google-workspace-plans-and-pricing/) — 2026-09-22]. Funciones: (P) [verificado: [soporte Google](https://support.google.com/docs/answer/13952129); [Workspace Updates, sep-2023](https://workspaceupdates.googleblog.com/2023/09/the-next-phase-of-digital-whiteboarding-for-google-workspace.html) — 2026-09-22] |
| Zoom | Workplace Pro / Business | ~14,16 / ~18,33 (anual) | Zoom Whiteboard (3 pizarras en Pro, ilimitadas en Business). AI Companion **sin costo adicional** en planes de pago | Precios: (Pr) [verificado: [meetgeek](https://meetgeek.ai/blog/zoom-price-plans) — 2026-09-22]. AI Companion: (P) [verificado: [Zoom AI Companion 2.0](https://news.zoom.com/zoom-introduces-ai-companion-2-0/) — 2026-09-22] |
| Zoom | ZoomMate (capa agéntica) | 16,67 (anual) | Capacidades agénticas y créditos de IA | (P) [verificado: [zoom.us/pricing/aic](https://zoom.us/pricing/aic) — 2026-09-22] |
| Cisco Webex | Free / Enterprise | 0 / a medida. Planes intermedios: **desconocido** | Pizarra en Free. AI Assistant "incluido" en Enterprise | (P) [verificado: [pricing.webex.com](https://pricing.webex.com/) — 2026-09-22] |
| Slack | Business+ | 15 (anual) | Notas de huddle con IA en un canvas | (P) [verificado: [Slack, jun-2025](https://slack.com/blog/news/june-2025-pricing-and-packaging-announcement) — 2026-09-22] |

**Hallazgos**

- **Con que el organizador tenga licencia, todo el equipo interno recibe el resultado del Facilitator.** Microsoft lo documenta así (P): "A Microsoft Copilot license is required to add Facilitator to a meeting…; however, any meeting participant (excluding external participants) can see all real-time updates in Chat and Notes" [verificado: [soporte Microsoft](https://support.microsoft.com/en-us/teams/copilot/facilitator-in-microsoft-teams-meetings) — 2026-09-22, comprobado directamente]. Es relevante para la #7: el valor puede comprarse **por puesto del Team Lead**, no por toda la cuenta.
- **Precios de lista 2026 y separación de Teams:**
  - Microsoft subió los precios de lista el 1-jul-2026. Por ejemplo, Business Standard pasó de 12,50 a 14 y E3 de 36 a 39. Las cifras previas vienen de un partner (Pr) [verificado: [blog Microsoft, 4-dic-2025](https://www.microsoft.com/en-us/copilot/blog/2025/12/04/advancing-microsoft-365-new-capabilities-and-pricing-update/) — 2026-09-22].
  - Teams se vende también por separado de la suite, con una diferencia mínima de precio comprometida ante la Comisión Europea durante 7 años (P) [verificado: [blog Microsoft, 12-sep-2025](https://www.microsoft.com/en-us/microsoft-365/blog/2025/09/12/evolving-our-productivity-offerings-to-resolve-european-competition-concerns-about-teams/) — 2026-09-22].
- **Google también integró la IA subiendo el precio.** Metió Gemini en los planes y subió Business Standard de 12 a 14 en 2025 (Pr) [verificado: [9to5google, 15-ene-2025](https://9to5google.com/2025/01/15/google-workspace-gemini-price-increase/) — 2026-09-22].
- **Análogo real del "Max" ficticio:** es Teams Premium (10 USD) o Copilot (21–30 USD) como capa de pago encima de Business Premium. Ninguno cuesta 8 USD ni se llama "Max". La comparación sirve para ver **cómo** se empaqueta, no para validar la cifra ficticia.

**Qué prueba y qué no**

- **Prueba:** los proveedores creen que la inteligencia de reunión se puede cobrar.
- **No prueba:**
  - que los clientes del segmento paguen por ella;
  - cuántos puestos de Teams Premium se venden (desconocido).
- **Único dato de adopción:** 20 M de puestos pagados de Copilot, ≈4% de los puestos comerciales de M365, según la prensa sobre la llamada de resultados del 29-abr-2026 (Pr sobre P) [verificado: [No Jitter](https://www.nojitter.com/ai-automation/microsoft-365-copilot-hits-20-million-paid-seats) — 2026-09-22]. Es adopción de Copilot en general, no de sus funciones de reunión.
- **Posible señal en contra (interpretación, no dato):** que la IA se esté integrando en los planes base encaja también con que el complemento separado no se vendió como se esperaba.

---

## P2. Miro, Mural, FigJam y alternativas: qué ofrecen y por qué las eligen

| Herramienta | Para quién (según el proveedor) | Funciones para reuniones | Integración con Teams | Precio (fecha) | Fuente |
|---|---|---|---|---|---|
| **Miro** | Facilitadores, estrategia, *design sprints*. Dice tener "100M+ usuarios, 250.000 empresas" (P) | Timer y votación (desde Starter), modo privado, Talktrack, encuestas (Business o superior) | App oficial: pestaña, **panel lateral y Share to Stage**. Solo lectura en móvil. **Los invitados no pueden usar apps en reuniones de Teams** | Free (3 tableros), Starter USD 8, Business USD 20 (anual, por miembro), Enterprise a medida (mínimo 30) — 22-sep-2026 | (P) [verificado: [miro.com/pricing](https://miro.com/pricing/); [ayuda Miro–Teams](https://help.miro.com/hc/en-us/articles/4411292563602-Microsoft-Teams-app-Calendar-user-guide-) — 2026-09-22] |
| **Mural** | Enterprise: I+D, consultoría, PI Planning | Timer, votación anónima, *Summon*, modo privado **en todos los planes** | App oficial. Lienzo en reuniones y pestañas. Detalle de panel lateral e invitados: **desconocido** | Free, Team+ USD 9,99, Business USD 17,99 (anual), Enterprise a medida — 22-sep-2026 | (P) [verificado: [mural.co/pricing](https://www.mural.co/pricing); [Mural para Teams](https://www.mural.co/partners/microsoft/teams) — 2026-09-22] |
| **FigJam** | Equipos de producto y diseño | Timer, votación, *spotlight*, resúmenes con IA. *Open sessions* sin cuenta (en planes de pago) | App oficial: **panel lateral y Share to Stage**. FigJam se puede editar en Teams | Asiento Collab ~USD 3–5 **según fuente terciaria (jul-2025)**. El precio oficial no se pudo leer | (P) [verificado: [ayuda Figma–Teams](https://help.figma.com/hc/en-us/articles/7405452518423-Figma-and-Microsoft-Teams)]. Precio: (Pr) [verificado: [UserJot](https://userjot.com/blog/figma-pricing-2025-plans-seats-costs-explained) — 2026-09-22] |
| **Lucidspark** | TI, ingeniería, PMO, *agile* | Timer, votación, modo privado. *Breakout boards* en Enterprise | App oficial: **panel lateral y Share to Stage**. Requiere iniciar sesión | Team ~USD 9, **según Capterra (fecha desconocida)** | (P) [verificado: [ayuda Lucid–Teams](https://help.lucid.co/hc/en-us/articles/15997078015124-Integrate-Lucid-with-Microsoft-Teams)]; (Pr) [verificado: [Capterra](https://www.capterra.com/p/211643/LucidSpark/pricing/) — 2026-09-22] |
| **MS Whiteboard** | Organizaciones M365 | Dibujo, notas, plantillas, cursores. Copilot agrupa y resume ideas. **La ayuda de reuniones no menciona timer ni votación** | Nativa, desde "Compartir" | Incluido en M365; varía según la licencia del *tenant* | (P) [verificado: [Whiteboard en Teams](https://support.microsoft.com/en-us/whiteboard/use-whiteboard-in-a-teams-meeting) — 2026-09-22] |
| **Loop / notas colaborativas** | Usuarios M365 | Agenda, notas y tareas co-editables | Nativa. Solo en reuniones programadas. **Invitados y externos sin acceso** | Incluido (licencias exactas: desconocido) | (P) [verificado: [Q&A Microsoft](https://learn.microsoft.com/en-us/answers/questions/4417987/teams-meeting-notes-unable-to-be-seen-by-external) — 2026-09-22] |
| Confluence / Notion | Documentación | Notas de reunión (Confluence). Notion **no investigado** | App oficial de Confluence en Teams | No investigado | (P) [verificado: [Atlassian](https://support.atlassian.com/confluence-cloud/docs/use-microsoft-teams-and-confluence-together/) — 2026-09-22] |

**Estado de la oferta nativa (P, fuente espejo):**

- Microsoft retira la app independiente de Whiteboard y las pizarras *legacy*. Desde el 16-oct-2026, Whiteboard se usará dentro de Teams, en la web o desde OneDrive.
- Fuente: Message Center MC1441775 y MC1469557, consultados en un espejo de terceros [verificado: [mc.merill.net MC1441775](https://mc.merill.net/message/MC1441775); [MC1469557](https://mc.merill.net/message/MC1469557) — 2026-09-22]. Las fechas han cambiado entre versiones; hay que confirmarlas en el Message Center oficial.

**Por qué eligen herramientas externas, según el tipo de evidencia**

- **(E) Estudios:** **no encontré ningún estudio independiente** que mida por qué los equipos eligen Miro o FigJam frente a Whiteboard o Loop. Es una brecha de evidencia, no una respuesta.
  - El *Market Guide* de Gartner (oct-2025) describe el mercado de colaboración visual como "maduro". Solo lo pude consultar a través de un resumen de Lucid, que es parte interesada [verificado: [blog Lucid](https://lucid.co/blog/takeaways-gartner-market-guide-for-visual-collaboration) — 2026-09-22].
- **(P) Proveedores:** afirmaciones de amplitud ("250+ integraciones", "20.000+ reseñas" en Miro). No prueban preferencia.
- **(Pr) Comparativas de terceros:** Collab365 (mar–ago 2026) recomienda Miro para facilitación profunda, colaboración entre organizaciones o un tablero "long-lived", y Whiteboard cuando el tablero "revolves around a Teams meeting" [verificado: [collab365](https://collab365.com/blog/microsoft-whiteboard-vs-miro-which-wins-for-collaboration) — 2026-09-22]. Collab365 vende cursos, así que su independencia es limitada.
- **(O) Opiniones de usuarios. No son representativas:** hay autoselección y la muestra de Whiteboard es pequeña.
  - G2: Miro 4,6 (13.503 reseñas) frente a Whiteboard 4,0 (52) [verificado: [G2](https://www.g2.com/compare/microsoft-whiteboard-vs-miro) — 2026-09-22].
  - Capterra: 4,7 (1.705) frente a 4,4 (158) [verificado: [Capterra](https://www.capterra.com/compare/128955-203470/Miro-vs-Microsoft-Whiteboard) — 2026-09-22].
  - Quejas repetidas sobre Whiteboard: faltan funciones, necesita cuenta Microsoft y es difícil que todos miren la misma zona del tablero. En Microsoft Q&A, una respuesta sugiere exportar a PDF y seguir en Miro o Figma para trabajar con invitados [verificado: [Q&A](https://learn.microsoft.com/en-us/answers/questions/1803142/using-whiteboard-while-working-with-guests-in-a-te) — 2026-09-22].
- **(P) Límites con externos (documentación oficial):**
  - En Whiteboard, los externos colaboran solo durante la reunión, no se crea enlace para compartir y los anónimos requieren una política del administrador [verificado: [Learn, 23-jun-2025](https://learn.microsoft.com/en-us/microsoft-365/whiteboard/manage-sharing-organizations?view=o365-worldwide) — 2026-09-22].
  - Las apps externas tampoco resuelven del todo a los invitados *dentro* de Teams. Donde ganan es *fuera* de Teams: enlace directo u *open sessions* de FigJam.

**Cómo se reparte la evidencia entre las explicaciones de la salida** (síntesis mía, no medición):

| Explicación | Peso de la evidencia |
|---|---|
| Calidad y funciones de facilitación | Más señales (documentación y opiniones) |
| Colaboración con externos | Respaldo documental oficial |
| El material ya vive en la herramienta externa | Solo un argumento de terceros |
| Descubribilidad | Señales débiles, ligadas a configuración y licencia |

---

## P3. Adopción empresarial y el argumento de compra de TI

| Herramienta | Cifra | Tipo | Fecha | Fuente |
|---|---|---|---|---|
| Miro | "100M+ usuarios en 250.000 organizaciones" | (P) | consultado 2026-09 | [verificado: [miro.com/about](https://miro.com/about/) — 2026-09-22] |
| Miro | ~4 M usuarios de pago, ~USD 600 M de ARR, 750+ clientes con más de USD 100k de ARR. Venta a Bending Spoons por USD 1.355 M (valor de empresa) | (P) comunicado de la operación | 10-sep-2026 | [verificado: [Business Wire](https://www.businesswire.com/news/home/20260910065427/en/Bending-Spoons-enters-into-a-definitive-agreement-to-acquire-Miro-for-$1.355-billion); [Bending Spoons](https://investors.bendingspoons.com/newsroom/bending-spoons-agrees-to-acquire-miro) — 2026-09-22] |
*Por qué aparece la operación de Miro:* es relevante para P3 porque el comunicado publica las únicas cifras de clientes de pago y de clientes enterprise de Miro. Su precio y su valoración **no** se usan como evidencia sobre la oportunidad de Teams. Una operación corporativa depende de muchos factores ajenos a la demanda de colaboración en reuniones.

| Herramienta | Cifra | Tipo | Fecha | Fuente |
|---|---|---|---|---|
| Mural | "Más del 50% del Fortune 100". No publica usuarios | (P) | sin fecha | [verificado: [mural.co/about-us](https://www.mural.co/about-us) — 2026-09-22] |
| Figma | Ingresos FY2025 USD 1.056 M (+41%); 1.405 clientes con más de USD 100k de ARR. **FigJam no aparece desglosado** (desconocido) | (P) resultados SEC | feb-2026 | [verificado: [SEC](https://www.sec.gov/Archives/edgar/data/1579878/000162828026009024/fy25pressrelease.htm) — 2026-09-22] |
| Lucid | "100M+ usuarios"; n.º 11 en el Fortune 500 según Okta 2026 | (P) citando a un tercero | may-2026 | [verificado: [comunicado Lucid](https://www.mykxlg.com/online_features/press_releases/lucid-software-continues-enterprise-momentum-ranking-among-top-apps-in-oktas-businesses-at-work-2026/article_b7f16cfd-294f-51ba-a14c-f709da4bd148.html) — 2026-09-22] |

**Expansión de SaaS y gasto fuera de TI (E, con sesgo de patrocinador)**

- **Zylo, SaaS Management Index 2026** (más de 40 M de licencias y 218 líderes de TI):
  - las unidades de negocio controlan el 81% del gasto SaaS;
  - el 36% de las licencias no se usa;
  - el gasto por reembolso de gastos creció un 267%.
  
  Zylo vende gestión de SaaS [verificado: [Zylo](https://zylo.com/news/2026-saas-management-index) — 2026-09-22].
- **BetterCloud 2026** (525 profesionales de TI): unas 118 apps por organización y "tras 2 años de consolidación, el stack vuelve a crecer". BetterCloud también es un vendedor interesado [verificado: [BetterCloud](https://www.bettercloud.com/resources/state-of-saas/) — 2026-09-22].
- **Gartner** (predicción de 2023, no medición): en 2027 el 75% de los empleados adquirirá o creará tecnología fuera de la visibilidad de TI [verificado: [Gartner](https://www.gartner.com/en/newsroom/press-releases/2023-03-28-gartner-unveils-top-8-cybersecurity-predictions-for-2023-2024) — 2026-09-22].

**Gobernanza (P)**

- **Loop:** está bajo Purview (retención, eDiscovery, etiquetas, DLP), con algunos huecos [verificado: [Learn — Loop](https://learn.microsoft.com/en-us/microsoft-365/loop/loop-compliance-summary?view=o365-worldwide) — 2026-09-22].
- **Whiteboard:** tiene cobertura parcial. En Azure "no soporta DLP, eDiscovery, políticas de retención". En OneDrive la cobertura es mayor, pero las etiquetas de sensibilidad siguen "planificadas" [verificado: [Learn — Whiteboard](https://learn.microsoft.com/en-us/microsoft-365/whiteboard/manage-data-organizations?view=o365-worldwide) — 2026-09-22].
- **Miro:** SCIM, residencia de datos y logs de auditoría están en Enterprise. Las claves de cifrado propias y Enterprise Guard son complementos aparte [verificado: [Miro Enterprise](https://help.miro.com/hc/en-us/articles/360017730433-Enterprise-Plan) — 2026-09-22].
- **Lectura:** hay un argumento de costo total a favor de la suite, pero la oferta de pizarra nativa todavía no está al nivel de gobernanza que la suite promete.

**Contraevidencia**

- **Las empresas usan herramientas que se solapan con Microsoft 365.** Según el Okta *Businesses at Work* 2025, citado por prensa, el 48% de los clientes de M365 usa Zoom y el 40% usa Slack (Pr) [verificado: [SC Media](https://www.scworld.com/resource/whos-using-what-results-from-the-2025-okta-businesses-at-work-report) — 2026-09-22]. Solo cubre clientes de Okta, sin tamaño de muestra publicado.
- **Miro alcanzó ~4 M de usuarios de pago y más de 750 clientes con más de USD 100k de ARR, aunque Whiteboard viene incluido en M365** (P, comunicado de la operación). Muestra que una parte del mercado paga una herramienta especializada que se solapa con la suite.
- **No encontré evidencia de que TI acepte un sobreprecio solo por consolidar.** Lo que la evidencia sí muestra es que la consolidación se usa para **eliminar herramientas duplicadas y negociar precio**.

---

## P4. Costo de la fragmentación y tendencia de la IA en reuniones

Los estudios son de **población general**, en su mayoría **patrocinados por proveedores** y basados en autorreporte. Ninguno mide el segmento del caso.

| Estudio | Patrocinador | Muestra | Fecha | Hallazgo | Limitación | Fuente |
|---|---|---|---|---|---|---|
| Work Trend Index 2023 | Microsoft (P/E) | 31.000 personas, 31 mercados, más telemetría | feb–mar 2023 | 55% tiene dificultad con los próximos pasos y 56% con resumir. **58% con el brainstorming virtual** | Autorreporte; el proveedor vende Copilot | [verificado: [WTI 2023](https://www.microsoft.com/en-us/worklab/work-trend-index/will-ai-fix-work) — 2026-09-22] |
| WTI "Infinite Workday" | Microsoft (P/E) | Telemetría del 20% más activo y encuesta | jun-2025 | ~275 interrupciones al día; 57% de reuniones ad hoc | Sesgo hacia usuarios intensivos | [verificado: [WTI 2025](https://www.microsoft.com/en-us/worklab/work-trend-index/breaking-down-infinite-workday) — 2026-09-22] |
| Experimento Copilot | Microsoft (P/E) | 60 empleados de Microsoft; una reunión guionizada de 35 min | nov-2023 | Resumir una reunión: 11 min con Copilot frente a **42 min sin él**; exhaustividad similar | Muestra interna y artificial | [verificado: [WorkLab](https://www.microsoft.com/en-us/worklab/work-trend-index/copilots-earliest-users-teach-us-about-generative-ai-at-work) — 2026-09-22] |
| HBR "Toggling" | Autores vinculados a un proveedor [conocimiento del modelo — verificar] | 137 usuarios, 3 empresas Fortune 500 | ago-2022 | ~1.200 cambios de app al día; ~4 h por semana en reorientarse | No aísla las reuniones | [verificado: [HBR](https://hbr.org/2022/08/how-much-time-and-energy-do-we-waste-toggling-between-applications) — 2026-09-22] |
| Asana Anatomy of Work 2023 | Asana (P/E) | 9.615 personas, 6 países | 2023 | 58% del tiempo en "trabajo sobre el trabajo"; 2,8 h por semana en reuniones innecesarias | Autorreporte; conflicto de interés | [verificado: [Asana IR](https://investors.asana.com/news-releases/news-release-details/asana-anatomy-work-global-index-2023-smart-collaboration-and) — 2026-09-22] |
| Otter.ai y S. Rogelberg | Otter (P/E) | 632 empleados | sep-2022 | 71% se saltaría una reunión si recibiera buenas notas | Conflicto de interés directo | [verificado: [Otter](https://otter.ai/blog/one-third-of-meetings-are-unnecessary-costing-companies-millions-and-no-one-is-happy-about-it) — 2026-09-22] |
| Asthana et al. (CSCW) | Microsoft Research (E, revisado por pares) | 7 usuarios | 2023, rev. 2025 | Al recap le falta el contexto de los artefactos compartidos | Muestra muy pequeña | [verificado: [arXiv](https://arxiv.org/abs/2307.15793) — 2026-09-22] |
| Piloto M365 Copilot, Gobierno del Reino Unido (DBT) | Gobierno (E) | 1.000 licencias; 300 personas analizadas | oct–dic 2024 | **Sin ganancia de productividad discernible.** Transcripción y resumen de reuniones, entre lo más valorado; 22% detectó alucinaciones | Sector público; piloto corto | (Pr) [verificado: [The Register](https://www.theregister.com/2025/09/04/m365_copilot_uk_government) — 2026-09-22] |

**No encontré** un estudio independiente que mida cuánto cuesta registrar las decisiones después de una reunión. La aproximación más cercana es el experimento interno de Microsoft.

**Tendencia: la IA captura la reunión**

- **Microsoft Facilitator** (P) genera notas en vivo co-editables, decisiones, acciones y agenda con temporizador. Requiere Copilot, funciona solo en reuniones programadas y deja fuera a los externos [verificado: [soporte Microsoft](https://support.microsoft.com/en-us/teams/copilot/facilitator-in-microsoft-teams-meetings) — 2026-09-22].
- **Zoom AI Companion** (P): resúmenes y próximos pasos sin costo adicional desde sep-2023 [verificado: [Zoom](https://news.zoom.com/zoom-ai-companion/) — 2026-09-22]. Según la prensa, los usuarios activos mensuales de pago crecieron un 184% interanual en may-2026 [verificado: [UC Today](https://www.uctoday.com/unified-communications/zoom-reports-1-24bn-q1-revenue-as-ai-companion-users-surge-184/) — 2026-09-22].
- **Google Meet** (P): "Take notes for me" captura *next steps* asignables desde feb-2025 [verificado: [Workspace Updates](https://workspaceupdates.googleblog.com/2025/02/google-meet-take-notes-for-me-next-steps.html) — 2026-09-22].
- **Toma de notas independiente** (P/Pr): Fireflies dice valer más de USD 1.000 M. Granola levantó USD 125 M en mar-2026 y se está moviendo de "notetaker" a "app empresarial" [verificado: [Fireflies](https://fireflies.ai/blog/fireflies-1-billion-valuation); [TechCrunch](https://techcrunch.com/2026/03/25/granola-raises-125m-hits-1-5b-valuation-as-it-expands-from-meeting-notetaker-to-enterprise-ai-app/) — 2026-09-22].
- **TI favorece la captura nativa:**
  - Hay demanda colectiva contra Otter por grabar sin consentimiento (ago-2025) [verificado: [NatLawReview](https://natlawreview.com/article/ai-notetaking-tools-under-fire-lessons-otterai-class-action-complaint) — 2026-09-22].
  - Universidades han bloqueado bots de terceros, y según la prensa Teams marca como "no verificados" los bots externos [verificado: [UW–Madison](https://it.wisc.edu/news/uw-madison-blocks-3rd-party-ai-services-for-enhanced-security); [UC Today](https://www.uctoday.com/security-compliance-risk/ai-meeting-bots-controls-microsoft-zoom-google/) — 2026-09-22].

**Durante frente a después**

- **El WTI 2023 separa las dos fricciones:** co-crear (58% tiene dificultad con el brainstorming virtual) y registrar (55–56% con próximos pasos y resúmenes).
- **La IA ataca sobre todo el "después".** No encontré evidencia independiente de que resuelva la co-creación en sí, es decir, priorizar o decidir en grupo.
- **Esta separación coincide con la pregunta abierta del brief:** qué sub-problema priorizar.

---

## Auditoría de evidencia (`pm-auditar-evidencia`)

**Trazar.** Cada afirmación tiene un enlace recuperable y fecha de consulta. Excepciones:

- La afiliación de los autores de HBR va marcada como conocimiento del modelo.
- El Message Center se consultó en un espejo de terceros.
- Los precios de FigJam y Lucidspark vienen de fuentes terciarias.
- Las páginas oficiales de precios de Google y Zoom no se pudieron leer, así que usé fuentes secundarias de 2026.

**Contar.**

- La mayoría de los estudios de P4 los patrocinan proveedores: Microsoft (3), Asana, Otter y Atlassian. Varios hallazgos "independientes" sobre SaaS vienen de dos vendedores de gestión de SaaS.
- La venta de Miro sí tiene fuentes independientes entre sí (comprador, prensa financiera y tecnológica), y la verifiqué directamente.

**Segmentar.**

- Ningún estudio cubre el segmento del caso (Business Premium, tecnología, ≥3 países, LATAM según las personas).
- Los precios son de lista en EE. UU. No reflejan acuerdos empresariales ni precios regionales.
- Los datos de Okta cubren solo clientes de Okta.

**Contradecir.**

- La creencia #1 (descubribilidad) tiene explicaciones rivales documentadas: funciones y externos.
- La #8 (pagar más) tiene una lectura rival: consolidar para ahorrar.
- La #7 tiene una lectura rival: que existan precios y complementos muestra modelos comerciales, no disposición a pagar.
- La operación de Miro no se usa como evidencia sobre la oportunidad de Teams.

**Des-solucionar.** "Pizarra", "Facilitator" y "votación" son soluciones. Las necesidades que aparecen en la evidencia son:

- facilitar la co-creación (timer, votación, foco común);
- incluir a externos;
- no transcribir a mano lo decidido.

**Calibrar.**

- **Respaldado:**
  - el mercado real empaqueta la IA de reunión como capa de pago o como motivo de subida de precio;
  - las alternativas externas tienen funciones de facilitación que Whiteboard no documenta;
  - la colaboración con externos es una limitación nativa documentada.
- **Plausible:** el "después" de la reunión se vuelve una función básica; TI valora la gobernanza nativa.
- **No inferible:**
  - que los clientes del segmento paguen el upgrade por esto;
  - que la descubribilidad sea o no la causa principal en *nuestros* Team Leads;
  - cuánto tiempo pierden.

---

## Impacto en creencias

*Veredictos sobre evidencia de mercado. No verifican creencias sobre nuestros usuarios, y este informe no modifica `overview.md`. Las creencias de la agenda secundaria del brief (#7, #8, #2) van primero.*

| Creencia (de overview.md) | Veredicto | Evidencia | Cómo validarla |
|---|---|---|---|
| **#7** [opportunity] [viability] La colaboración en reuniones es un motivo explícito de upgrade a Max | **No concluyente.** Los precios de las soluciones existentes muestran que hay modelos comerciales, pero no validan que los clientes hagan el upgrade a Max | Microsoft, Google, Zoom y Webex ponen la IA de reunión en una capa de pago o suben el precio al incluirla (P1, P). La adopción de Copilot es ~4% de los puestos (Pr). Con el Facilitator basta con la licencia del organizador, lo que abre una vía por puesto y no por cuenta. Que exista el precio **no prueba** disposición a pagar | **Datos internos:** codificar notas de CRM de renovaciones Max (ya en la agenda). **Entrevistas** con IT |
| **#8** [opportunity] [viability] IT considera que concentrar la colaboración en M365 justifica pagar más | **No concluyente.** El dolor de TI está documentado, pero la evidencia sobre consolidación y ahorro no permite saber si TI pagaría un sobreprecio por una solución que aporte valor | El gasto fuera de TI y las licencias sin uso están documentados (Zylo, BetterCloud; E con sesgo). La gobernanza de Loop está bajo Purview; la de Whiteboard es parcial (P). Las herramientas que se solapan con M365 persisten (Okta vía Pr). No hay evidencia de sobreprecio; la consolidación se usa para ahorrar | **Entrevistas** con 3–4 responsables de IT: ¿sustituir herramientas o pagar más? |
| **#2** [product] [value] El salto a herramientas externas es una fricción que quieren resolver, no un flujo que funciona | **No concluyente, con contraevidencia leve** | Miro, FigJam y Lucidspark tienen apps oficiales con panel lateral y Share to Stage (P): el flujo externo puede ocurrir *dentro* de Teams. Las opiniones elogian Miro (O, no representativas). Collab365 describe los tableros externos como espacios de larga vida (Pr). El WTI 2023 sí muestra fricción en el brainstorming virtual (58%, P/E, población general) | **Encuesta:** satisfacción con la alternativa actual. **Entrevistas:** priorizar a usuarios satisfechos con Miro |
| **#1** [product] [value] Sacan la colaboración de Teams porque no descubren las funciones nativas | **No concluyente.** Hay explicaciones alternativas documentadas, pero no se ha demostrado cuál predomina en el segmento | Whiteboard no documenta timer ni votación en reuniones; los externos tienen límites (P). Las quejas por falta de funciones son las más repetidas (O). La descubribilidad aparece ligada a configuración y licencia (O). Microsoft retira la app independiente de Whiteboard. No hay un estudio independiente de motivos | **Entrevistas:** separar descubribilidad, calidad, externos y "material ya externo". **Datos internos:** qué *tenants* tienen Whiteboard activado |
| **#6** [opportunity] [value] Pierden ≥1 h por semana entre salir de Teams y registrar lo decidido | **Apoya débilmente la dirección, no el umbral** | Resumir una reunión de 35 min sin IA llevó ~42 min en un experimento interno de Microsoft (P/E). 55–56% tiene dificultad con próximos pasos y resúmenes (P/E). ~4 h por semana en reorientarse entre apps (HBR, no específico de reuniones). Todo es población general. Y la IA ya comprime el "después" | **Encuesta:** tiempo declarado frente al umbral. **Datos internos:** duración con y sin enlace externo |
| **#4** [product] [viability] "El equipo ya usa otras herramientas" se refiere sobre todo a colaboración en reuniones | **No dice nada** (solo contexto) | El solapamiento existe tanto en chat (Slack 40%, Zoom 48% entre clientes de M365 en Okta, Pr) como en pizarras. No indica qué motiva las bajas | **Datos internos:** CRM de bajas |
| **#3** [product] [value] Quienes más sufren son quienes conducen | **No dice nada** | No hay evidencia secundaria por rol | **Datos internos:** comentarios por rol. **Encuesta** a quienes conducen y a quienes participan |
| **#5** [product] [viability] Colaborar dentro de Teams reduce las bajas | **No dice nada** | Sin evidencia de mercado sobre causalidad en la retención | **Datos internos:** cohortes de uso y renovación |

## Qué sigue necesitando investigación primaria

- **Datos internos** (antes del 6-oct):
  - #7 y #4: CRM de renovaciones y bajas;
  - #6 y #3: duración con y sin enlace externo, desglose de comentarios por rol;
  - #1: *tenants* con Whiteboard desactivado.
- **Encuesta** (`/design-survey`: cuántos, con qué frecuencia, cuánto):
  - #6: tiempo perdido durante y después;
  - #2: satisfacción con Miro/Mural/FigJam;
  - #3: fricción por rol;
  - añadir la frecuencia de **participantes externos** en las reuniones del segmento, porque es una variable nueva que surgió de esta investigación.
- **Entrevistas** (`/design-interview`: por qué, qué hacen hoy):
  - #1: descubribilidad frente a funciones, externos o material ya externo;
  - #2: priorizar a usuarios satisfechos con Miro (la persona faltante del brief);
  - #8 y #7: si IT ve la consolidación como sustitución con ahorro o como razón para pagar más.
- **Pregunta nueva para el brief (sin editarlo):** ¿el sub-problema a priorizar es el *durante* (co-crear, decidir) o el *después* (registrar)? En el mercado real, el segundo ya lo cubre la IA.

## Limitaciones generales

- Todas las fuentes se consultaron el 22-sep-2026. Precios, planes y fechas de retiro cambian rápido.
- Las páginas oficiales de precios de Google, Zoom, Figma y Lucid no se pudieron leer directamente.
- Varios datos recientes (SKUs de julio de 2026, venta de Miro, retiro de Whiteboard) son posteriores al conocimiento del modelo. Su única base son las fuentes citadas; verifiqué directamente la venta de Miro y el licenciamiento de Facilitator.
- Parte de la síntesis de páginas la hicieron subagentes. Antes de usar una cita en una decisión, conviene abrir el enlace.
- Esta investigación describe el **mercado real**. El caso AFPM es ficticio: no sabemos qué funciones tiene el "Teams" del ejercicio, y cualquier traslado debe hacerse de forma explícita.
