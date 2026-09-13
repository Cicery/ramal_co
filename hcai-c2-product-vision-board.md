# Product Vision Board — Hardcore AI Cohorte 2

## Instrucciones

Este es tu primer artefacto de producto. Lo completas como tarea de la Estación 1 y lo traes listo a la Estación 2 (miércoles 13 de mayo).

### Pasos

1. **Selecciona tu producto:** Idea propia, proyecto de tu empresa o una opción del banco de productos.
2. **Genera un deep research de validación:** Usa AI para investigar si tu idea tiene fundamento real.
3. **Genera un deep research de crítica:** Usa AI para encontrar las debilidades y riesgos de tu idea. Estudia ambos.
4. **Documenta todo en Markdown:** Transcripciones, análisis, investigación, notas de entrevistas.
5. **Completa este Product Vision Board:** Llena cada sección con base en tu investigación.

### Reglas de llenado

- Sé específico. "Empresas" no es un segmento. "Equipos de legal en startups Series A-B con 2-5 abogados in-house" sí lo es.
- No escribas "queremos usar AI para X". Escribe el dolor específico que resuelves.
- Si no puedes responder una sección con confianza, eso es una señal de que necesitas más investigación.
- Trae tus dudas a la tutoría del martes 12 de mayo con José Alanya.

---

## PRODUCTO

**Nombre del producto:** Ramal

**Descripción en una línea:** Plataforma de gestión para acueductos comunitarios y rurales (adaptable a urbanos) que abre las finanzas y operaciones al escrutinio directo de los usuarios, reduciendo morosidad y corrupción mediante transparencia radical y vigilancia colectiva.

---

## 1. PROBLEMA

Define el problema que resuelves. Debe ser un dolor real, específico, y que persista incluso cuando los modelos de AI evolucionen.

**Problema que resuelvo:** En Colombia existen ~12.000 acueductos comunitarios (solo 3.649 inscritos en SINAS) que abastecen al 40% de la población rural. Entre el 30% y 40% funcionan mal o no funcionan. La causa raíz documentada es administrativa, no técnica: operan sin contabilidad estructurada, sin estudios tarifarios, con alta cartera/morosidad y con **desconfianza de los usuarios en el manejo de recursos** — dinero que se recauda y no se sabe en qué se gasta, juntas que rinden cuentas solo en asambleas anuales (si acaso). Esta desconfianza alimenta la baja cultura de pago ("si no sé en qué se usa mi plata, no pago"), que a su vez ahoga las finanzas del acueducto en un círculo vicioso. Los líderes de las juntas (70% sin educación superior a secundaria) no tienen herramientas para llevar cuentas claras ni para rendir cuentas fácilmente.

**¿Este problema sobrevive a las próximas 2-3 generaciones de modelos foundation (GPT-5, Claude 5)?**
[X] Sí, porque es un problema de WORKFLOW/INTEGRACIÓN, no de OUTPUT

**Durability Score (1-5):** 5 — El problema es de gobernanza, registro contable y confianza entre vecinos; ningún LLM lo elimina. La AI es un potenciador (detección de anomalías, reportes), no el producto.

---

## 2. SEGMENTO TARGET

**¿Para quién es este producto?** Juntas administradoras de acueductos comunitarios y veredales en Colombia (JAC, asociaciones de suscriptores, juntas administrativas), inicialmente las 1.900-3.600 organizadas e inscritas y las redes regionales (ej. ACER Agua Viva en el Meta, Red Nacional de Acueductos Comunitarios). Diseñado primero para organizaciones de 50-2.000 suscriptores con juntas voluntarias sin formación contable; escalable después a acueductos urbanos pequeños y OCSAS de América Latina (145.000 organizaciones, 70 millones de personas).

**¿Quién controla el veto de confianza?** El presidente y el tesorero de la junta (quienes firmarían adoptar el sistema), y las redes/gremios de acueductos comunitarios que recomiendan herramientas a sus afiliados. Segundo veto: el administrador/operario actual que ve en el software una amenaza a su discrecionalidad. Tercero: entes de asistencia técnica (PDA, alcaldías) que financian la adopción.

---

## 3. MOAT PRIMARIO

Solo puedes elegir UNO como primario. Es tu ventaja defensible principal.

**Moat primario:**
[ ] Data Moat — Generamos data única que competidores no pueden comprar ni copiar
[X] Distribution Moat — Estamos embebidos en un canal/workflow difícil de replicar
[ ] Trust Moat — Ofrecemos reliability/safety/compliance que otros no pueden igualar

**¿Qué data, distribución o trust única poseemos o podemos construir?** Distribución vía redes y gremios de acueductos comunitarios (Red Nacional, redes regionales como ACER, CLOCSAS a nivel LATAM) y programas estatales (PDA, MVCT, Decreto 0960 de 2025 que exige formalización y da acceso a recursos estatales): una vez una red adopta Ramal como su herramienta de rendición de cuentas, cambiar es muy costoso (histórico financiero completo de la organización vive ahí y los usuarios ya lo consultan). Además generamos un registro inmutable de ingresos/gastos/decisiones de junta que se vuelve el "legado documental" del acueducto — migrar significa perder la trazabilidad que los usuarios ya exigen.

---

## 4. ARENA COMPETITIVA

**¿En qué arena compites?**
[ ] Pioneer (AI-Native) — Estoy creando un mercado nuevo que no podría existir sin AI
[X] Disruptor (AI-Disrupted) — Estoy reimaginando un workflow existente haciéndolo 10x mejor
[ ] Enhancer (AI-Enhanced) — Estoy usando AI para fortalecer un producto/proceso existente

**¿Cómo sobrevives o complementas a los gigantes (Google, Microsoft, OpenAI)?** Los gigantes no atienden este nicho. Competidores locales: HAPINET, AquaProgrammer, Mi Vereda y Software Integrin (gratuito del MVCT) cubren facturación/lecturas/recaudo, pero son herramientas del **administrador** — el usuario común no ve nada. Ramal es el único cuyo núcleo es el **portal del usuario-suscriptor**: cada usuario ve ingresos, gastos, facturas pagadas por la junta, contratos y decisiones, y puede/alertar/questionar. Frente a Integrin (gratis, pesado, diseñado para cumplir SUI, complejo para juntas voluntarias), Ramal gana en simplicidad y en el ángulo de vigilancia ciudadana. AI (vía APIs de OpenAI/Anthropic) se usa como capa de análisis de anomalías y generación automática de informes legibles — commodity, no ventaja; la ventaja es el workflow comunitario y la data acumulada.

---

## 5. UX PARADIGM

**¿Cómo interactúa el usuario con tu producto?**
[X] Assistant — El usuario está en control, AI sugiere (ej: Copilot)
[ ] Agent — AI ejecuta tareas autónomamente dentro de límites (ej: AI SDR)
[ ] Autonomous — AI corre sin supervisión humana (ej: fraud detection)
[ ] Embedded Intelligence — AI mejora el producto de forma invisible (ej: recomendaciones)

**¿Por qué este paradigma para tu caso de uso?** La confianza es el producto: la AI no puede decidir nada ni operar en cajas negras. Ramal registra todo (gastos con foto de recibo, actas, lecturas), publica automáticamente un tablero público por acueducto, y la AI actúa como asistente: redacta el resumen mensual de cuentas en lenguaje sencillo ("gastamos $X, los 3 mayores gastos fueron…"), señala gastos inusuales para que la comunidad los revise, y ayuda a la junta a cumplir reportes SUI/CRA. Las decisiones (aprobar un gasto, contestar una alerta) siempre son humanas y quedan trazadas.

---

## 6. AI DECISION TRIANGLE

No puedes maximizar las tres. Elige la prioridad de tu producto.

**Optimizo primariamente para:**
[X] Cost — Lo más barato posible (ideal para tareas de alto volumen)
[ ] Capability — Lo más inteligente/preciso (ideal para decisiones de alto riesgo)
[ ] Speed — Lo más rápido posible (ideal para experiencias en tiempo real)

**Trade-offs que acepto:** Los acueductos son organizaciones de bajos recursos; el costo de inferencia debe ser céntimos por acueducto/mes. Acepto AI de menor capacidad para tareas rutinarias (resúmenes, clasificación de gastos con foto de recibo, alertas básicas) y reservo modelos más caros solo para detección de anomalías complejas. Sin internet en campo: la app de lecturas funciona offline y la AI solo corre al sincronizar.

---

## 7. MODELO ECONÓMICO

**Modelo de pricing:**
[X] Hybrid Tiered (tiers con límites crecientes)
[ ] Usage-Based / Per-Token (pago por uso)
[ ] Credit Pools (suscripción + créditos)
[ ] Outcome-Based (pago por resultado)
[ ] Seat-Based + AI Add-On (por usuario + AI premium)
[ ] Freemium / Reverse Trial (gratis → conversión)

**¿El pricing escala si tienes 10x usuarios?** Sí — el costo marginal es infraestructura cloud + inference, ambos decrecientes por usuario. El tier gratuito (portales de transparencia básicos) es el canal de adquisición; los tiers pagos agregan facturación, recaudo y reportes normativos.

**Costo estimado por usuario/mes:** ~$1.500-3.000 COP (~$0,40-0,80 USD) por acueducto (infra + AI; referencia: AquaProgrammer cobra ~$978 COP por usuario/mes a 1.800 suscriptores)
**Revenue por usuario/mes:** Tier por tamaño del acueducto: $50.000-300.000 COP/mes (~$12-75 USD) por organización; gratuito con transparencia básica para siembra
**Gross margin proyectado:** 70-80%

---

## 8. MÉTRICAS DE ÉXITO

**Métricas de usuario:**
1. % de morosidad del acueducto antes vs. 6 meses después de adoptar Ramal (hipótesis: baja >15 puntos porque el pago se vuelve socialmente exigible cuando todos ven las cuentas)
2. % de usuarios del acueducto que consultan el portal de transparencia al menos 1 vez/mes (objetivo: >30%)

**Métricas específicas de AI:**
1. % de gastos clasificados automáticamente de forma correcta a partir de foto de recibo (target: >90%)
2. Tasa de alertas de anomalías confirmadas como válidas por la comunidad (target: >60% — precision, para no generar "fatiga de alertas")

---

## 9. RIESGOS CRÍTICOS

**1. ¿Qué pasa si el problema desaparece en 12 meses por commoditización?** El problema (gobernanza y confianza comunitaria) no desaparece ni se commoditiza — es estructural y multidecenal. Riesgo real distinto: que Integrin (gratuito del MVCT) agregue un portal de usuario y lo empuje por canal estatal. Mitigación: aliarse con las redes comunitarias en vez de competir contra el Estado, y ser 10x más simple.

**2. ¿Puede un competidor replicar tu producto con la misma API en menos de 6 semanas?** La app en sí sí (facturación + tablero es replicable). Lo que no: la distribución por redes/gremios, el hábito instalado de que los usuarios consultan ahí las cuentas de su acueducto, y el histórico documental inmutable por organización. Además, Integrin tiene 25 años y 500 implementaciones pero cero cultura de portal ciudadano — su ADN es el back-office del administrador.

**3. Si tienes éxito a escala, ¿cuál es la primera forma en que se rompe la confianza?** Dos vías: (a) un dato financiero sensible filtrado o mal publicado (nómina de la junta, deudas de usuarios específicos visibles públicamente) → granularidad cuidadosa de qué es público y qué es privado, con controles de acceso por rol; (b) una junta corrupta manipula registros antes de publicarlos → registro append-only con hash encadenado y evidencia fotográfica obligatoria, de modo que cualquier alteración sea detectable. También: acusaciones falsas generadas por alertas de AI erróneas contra vecinos → las alertas siempre se presentan como "para revisión humana", nunca como veredictos.

---

## Checklist de entrega

- [X] Producto seleccionado (idea propia, proyecto de empresa o banco de productos)
- [X] Deep research de validación completado y estudiado
- [X] Deep research de crítica completado y estudiado
- [X] Información documentada en archivos Markdown
- [X] Product Vision Board completado (este documento)
- [ ] Listo para presentar en la Estación 2 (miércoles 13 de mayo)
