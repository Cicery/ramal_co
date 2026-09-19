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

**Nombre del producto:** Ramal ( Ramal Co )

**Descripción en una línea:** Plataforma de gestión y transparencia para acueductos rurales y comunitarios que digitaliza facturación, contabilidad y operación, y expone el manejo de recursos directamente a los usuarios del acueducto para reducir la corrupción.

---

## 1. PROBLEMA

**Problema que resuelvo:** En Colombia existen ~12.000 acueductos comunitarios — solo 3.649 inscritos en SINAS y ~1.919 ante la SSPD — que abastecen al 40% de la población rural (más de 9 millones de personas). Entre el 30% y 40% no funcionan o funcionan mal. La causa raíz documentada (Business Review 2025, Boletín Interamericano 2025, Dícere/Universidad Libre) es administrativa y de confianza, no técnica: operan sin contabilidad estructurada, sin estudios tarifarios, con alta carta/morosidad y con **desconfianza de los usuarios en el manejo de recursos** — dinero que se recauda y no se sabe en qué se gasta. Eso alimenta el círculo vicioso: tariffas bajas + morosidad → sin liquidez → sin mantenimiento → mal servicio → "si no sé en qué se usa mi plata, no pago". Los líderes de junta (>70% sin educación superior a secundaria; Gamboa 2020) no tienen herramientas para llevar cuentas claras ni rendir cuentas fácilmente. El Estado tampoco los conoce bien (en Villavicencio: Alcaldía cuenta 76, censos comunitarios 126, SSPD 15). Y el timing regulatorio lo vuelve urgente: el **Decreto 0960 de 2025** inaugura una ola de formalización con acceso a recursos estatales que obligará a miles de juntas a llevar cuentas formales por primera vez.

**¿Este problema sobrevive a las próximas 2-3 generaciones de modelos foundation (GPT-5, Claude 5)?**
[x] Sí, porque es un problema de WORKFLOW/INTEGRACIÓN, no de OUTPUT
[ ] No estoy seguro — necesito investigar más
[ ] No — mi problema es de generación/resumen que se commoditiza

**Durability Score (1-5):** 5 — la facturación, contabilidad, auditoría y rendición de cuentas de un servicio público son flujos regulatorios y operativos que ningún modelo de lenguaje reemplaza.

---

## 2. SEGMENTO TARGET

**¿Para quién es este producto?** Juntas Administradoras de Acueductos Comunitarios y Rurales (JAAP, JACAs, asociaciones de usuarios) en América Latina, empezando por Colombia: organizaciones de 100 a 5.000 afiliados, administradas por líderes voluntarios (presidente, tesorero, secretario) sin software, con presupuesto anual bajo y obligación legal de rendir cuentas a sus usuarios y a la Superintendencia de Servicios Públicos. **Beachhead:** el acueducto de mi vereda, que ya tiene disposición a sistematizarse — será el piloto y design partner del producto. El usuario final del producto es el tesorero/administrador y el fontanero de la junta; el beneficiario (y fiscalizador) es cada usuario del acueducto.

**¿Quién controla el veto de confianza?** La junta directiva de la acueducto (quien decide adoptar o no el software, y teme que "transparentar" lo exponga). Secundariamente: las entidades de control (Superintendencia de Servicios Públicos, alcaldías, Corporaciones Autónomas Regionales) y las ONGs/entidades financiadoras de obras, que pueden exigir o recomendar la plataforma como condición de desembolso.

---

## 3. MOAT PRIMARIO

**Moat primario:**
[ ] Data Moat — Generamos data única que competidores no pueden comprar ni copiar
[ ] Distribution Moat — Estamos embebidos en un canal/workflow difícil de replicar
[x] Trust Moat — Ofrecemos reliability/safety/compliance que otros no pueden igualar

**¿Qué data, distribución o trust única poseemos o podemos construir?** Trust: un "libro contable abierto" — cada ingreso, egreso y obra queda registrado con evidencia (recibos, fotos, geolocalización) en un registro **append-only con hash encadenado** (si alguien altera un dato antes de publicarlo, la alteración es detectable) y se publica automáticamente en un portal consultable por cualquier usuario del acueducto desde su celular. Ningún competidor ofrece capacidad de auditoría directa al usuario final (no al administrador). Distribución (moat secundario y vehículo del trust): las redes y gremios de acueductos comunitarios — Red Nacional de Acueductos Comunitarios, redes regionales (ACER Agua Viva en el Meta), CLOCSAS a nivel LATAM (145.000 OCSAS) y programas estatales (PDA, MVCT, Decreto 0960 de 2025) — una red que adopta Ramal como su herramienta de rendición trae decenas de juntas de golpe, y el legado documental inmutable de cada organización hace la migración posterior muy costosa. Data (tercer moat): histórico único de consumo, tarifas, fallas y costos de operación de acueductos rurales — data que no existe en ninguna base de datos pública ni privada y que permite benchmarks entre juntas.

---

## 4. ARENA COMPETITIVA

**¿En qué arena compites?**
[ ] Pioneer (AI-Native) — Estoy creando un mercado nuevo que no podría existir sin AI
[x] Disruptor (AI-Disrupted) — Estoy reimaginando un workflow existente haciéndolo 10x mejor
[ ] Enhancer (AI-Enhanced) — Estoy usando AI para fortalecer un producto/proceso existente

**¿Cómo sobrevives o complementas a los gigantes?** Investigación de competencia (14/sep/2026, ver docs/deep-research-validacion.md y el research de la versión anterior en racol_copia): el segmento ya tiene proveedores que validan disposición a pagar — **Acuasoft** (facturación, recaudo, DIAN, contabilidad; cotización por suscriptores), **AquaProgrammer** (app offline de lecturas con foto+GPS+firma; ~$978 COP/usuario/mes a escala; +5.063 usuarios en producción), **Software GBS** (ERP NIIF/NICSP para ESP pequeñas), **ASOCOMUNAL/Jacapp** (gestión general de JAC), **HAPINET** (cloud para acueductos veredales: facturación, medición, recaudo, SUI/CRA), **Mi Vereda** (facturación en sitio offline con impresora térmica, recaudo por Efecty/SuRed) y **Acueducto.co** (sitio institucional con cumplimiento SSPD y plan gratuito). El más peligroso es **Integrin (GPSI): es gratuito del MVCT**, con 25 años y +500 implementaciones (+300 rurales) — su amenaza es que agregue un portal ciudadano y lo empuje por el canal estatal (PDA); mitigación: integrarse con él (importar datos), no competir de frente — es back-office pesado y complejo para juntas voluntarias, y ahí gana Ramal en simplicidad y en el ángulo de vigilancia ciudadana. **Ninguno ofrece un portal de fiscalización para el usuario final del acueducto** — todos venden herramientas al administrador; nuestro diferenciador (libro contable abierto + reportes AI para usuarios) es el hueco que queda vacante. Los gigantes (SAP, SCADA, OpenAI/Google) no atienden juntas de 100–800 afiliados; la AI es capa de análisis, no ventaja — la ventaja es el workflow comunitario y la data acumulada.

---

## 5. UX PARADIGM

**¿Cómo interactúa el usuario con tu producto?**
[x] Assistant — El usuario está en control, AI sugiere (ej: Copilot)
[ ] Agent — AI ejecuta tareas autónomamente dentro de límites (ej: AI SDR)
[ ] Autonomous — AI corre sin supervisión humana (ej: fraud detection)
[ ] Embedded Intelligence — AI mejora el producto de forma invisible (ej: recomendaciones)

**¿Por qué este paradigma para tu caso de uso?** En un contexto de transparencia y confianza, la junta y los usuarios deben estar en control: la AI sugiere (detecta un gasto atípico, marca un consumo inconsistente con el histórico, redacta el borrador del informe mensual comunitario), pero nunca decide ni publica automáticamente sin revisión. La autonomía total erosionaría la confianza, que es justamente el producto. El producto es **offline-first**: el fontanero toma las lecturas de contadores y registra novedades (fugas, medidores dañados) en una app móvil que funciona sin señal y sincroniza cuando hay conectividad; el tesorero administra desde el móvil o el navegador.

---

## 6. AI DECISION TRIANGLE

**Optimizo primariamente para:**
[x] Cost — Lo más barato posible (ideal para tareas de alto volumen)
[ ] Capability — Lo más inteligente/preciso (ideal para decisiones de alto riesgo)
[ ] Speed — Lo más rápido posible (ideal para experiencias en tiempo real)

**Trade-offs que acepto:** Acepto menor sofisticación: detección de anomalías con reglas simples y modelos pequeños en lugar de LLMs costosos en cada operación; los LLMs se reservan para generación de reportes de bajo volumen (1 vez al mes por junta) y consultas de los usuarios. El producto funciona offline-first (sincronización cuando hay señal), aceptando datos menos "en tiempo real" a cambio de usabilidad rural real.

---

## 7. MODELO ECONÓMICO

**Modelo de pricing:**
[ ] Hybrid Tiered (tiers con límites crecientes)
[ ] Usage-Based / Per-Token (pago por uso)
[ ] Credit Pools (suscripción + créditos)
[ ] Outcome-Based (pago por resultado)
[ ] Seat-Based + AI Add-On (por usuario + AI premium)
[x] Freemium / Reverse Trial (gratis → conversión)

**¿El pricing escala si tienes 10x usuarios?**
[x] Sí   [ ] No   [ ] Necesita ajuste

**Pricing target en Colombia (anclado a benchmarks de competencia):**
- Ancla primaria: **AquaProgrammer ~$978 COP/afiliado/mes a escala** (1.800 afiliados ≈ $1,76M COP/mes). Ramal se fija igual o ~20–30% por debajo: el valórico diferencial (transparencia + AI) justifica precio similar, no menor.
- **Tier Vereda:** cuota mensual mínima fija de **$25.000–40.000 COP/mes** hasta ~150 afiliados (≈ $100–270 COP/afiliado), con límites en funciones AI y evidencias por encima. El comprador de mi vereda ya expresó disposición a pagar una cuota mensual — señal temprana de precio de anclaje.
- **Tier Junta:** proporcional al número de afiliados a ~$800–1.000 COP/afiliado/mes (tope ~$150.000 COP/mes). Sin límites. No usar gratis — la señal de compromiso de la junta que paga es parte del fit.
- **Tier Institucional (B2G/B-ONG):** cotización por portafolio de juntas, licencias anuales. Hipótesis de canal a validar con una LOI.
- Ingreso secundario: anuncios contextuales de proveedores del sector. Enfoque: bajar costos al usuario, no margen principal.
- Decisión: el desarrollo del producto NO espera la validación de precio; el MVP y las entrevistas de tesoreros corren en paralelo y el pricing es revisable hasta el lanzamiento. Los rangos listados son la hipótesis de partida y se ajustan con lo que se aprenda.

**Costo estimado por usuario/mes:** $300–900 COP de infraestructura por afiliado (compartida a nivel de junta)
**Revenue por usuario/mes:** $100–250 COP por afiliado (tier de pago) + ingresos por anuncios
**Gross margin proyectado:** 75%

---

## 8. MÉTRICAS DE ÉXITO

**Métricas de usuario:**
1. **% de morosidad del acueducto antes vs. 6 meses después de adoptar Ramal** (hipótesis: baja >15 puntos — el pago se vuelve socialmente exigible cuando todos ven las cuentas; es la métrica que convierte transparencia en resultado de negocio)
2. Número de juntas activas y % de juntas que publican su informe mensual comunitario (adopción real de transparencia, no solo registro)
3. % de usuarios del acueducto que consultan el portal de transparencia ≥1 vez al mes (target: >30% — fiscalización activa)

**Métricas específicas de AI:**
1. Precisión de detección de anomalías en gastos y consumos (target: >90%, con <5% falsos positivos para no desgastar la confianza)
2. % de informes de rendición de cuentas generados por AI aceptados sin edición por la junta (target: >70%)

---

## 9. RIESGOS CRÍTICOS

**1. ¿Qué pasa si el problema desaparece en 12 meses por commoditización?** El riesgo no es commoditización de AI sino que el problema "desaparezca" por falta de adopción: las juntas son voluntarias, con bajo alfabetismo digital, y quien administra de forma irregular es justamente quien más se resiste a transparentar. Punto a favor: la adopción inicial no depende de convencer a desconocidos — el piloto es el acueducto de mi vereda, que ya decidió sistematizarse, y allí se validan el flujo real y el costo de soporte. **Advertencia sobre timing:** la validación con usuarios reales (uso del portal por afiliados, flujo offline del fontanero, costo real de soporte) llegará tarde — después de construir, lanzar y lograr la adopción de la junta. Para compensar, en paralelo desde ya: (a) MVP mínimo (facturación + portal público) lanzable en semanas antes del producto completo, (b) validar con los usuarios de mi vereda si consultarían la plataforma vía el canal que ya usan (WhatsApp) aunque el software aún no exista, (c) el piloto real es el mecanismo de validación — sin entrevistas preliminares, decisión documentada en el checklist. Para escalar, la presión puede venir del propio entorno: en Colombia los usuarios de acueductos comunitarios están organizados y sensibilizados frente a la corrupción, por lo que la fiscalización puede ser una demanda *bottom-up* de los usuarios hacia su junta ("instalen la plataforma") más que un ofrecimiento de software. Se complementa con canal B2G/B-ONG (entidades financiadoras que exigen rendición de cuentas) y hay que verificar marco legal (Ley 142 de 1994, Superintendencia de Servicios Públicos).

**2. ¿Puede un competidor replicar tu producto con la misma API en menos de 6 semanas?** La app básica de facturación con AI sí se puede replicar en semanas. No se replica en 6 semanas: el trust moat (historial verificable, evidencias de obras, reputación ante entes de control y ONGs), la red de juntas instalada y la data de benchmarks rurales acumulada. Además, en transparencia, "quien fue primero y demostró integridad" gana el posicionamiento moral: un competidor que llegue después es sospechoso de lo mismo que las juntas quieren evitar.

**3. Si tienes éxito a escala, ¿cuál es la primera forma en que se rompe la confianza?** Que un administrador altere o borre un registro, o que se filtre/perda información sensible de los usuarios (consumo individual, morosidad) en el portal público. Mitigación: log inmutable y verificable de cambios (nada se borra, solo se corrige con rastro visible), controles de qué dato es público vs. interno, cifrado y política de privacidad clara, y auditoría de seguridad. Un solo escándalo de manipulación de datos mata el trust moat.

---

## Checklist de entrega

- [x] Producto seleccionado (idea propia: Ramal — gestión y transparencia para acueductos rurales)
- [x] Deep research de validación completado y estudiado (docs/deep-research-validacion.md)
- [x] Deep research de crítica completado y estudiado (docs/deep-research-critica.md)
- [x] Información documentada en archivos Markdown
- [x] Product Vision Board completado (este documento)
- [x] Listo para presentar en la Estación 2
- [ ] Validación en producción: piloto con el acueducto de mi vereda (primer adoptante) — sustituye a las entrevistas preliminares; se aprende con uso real: adopción del portal, flujo offline del fontanero, morosidad antes/después y costo real de soporte

**Nota de decisión:** no se realizarán entrevistas con tesoreros de otras juntas antes del MVP. El precio y las funcionalidades se definen por investigación (benchmarks de AquaProgrammer/Acuasoft/Integrin) y se ajustan con el piloto real de mi vereda, que ya expresó disposición a pagar una cuota mensual. Riesgo aceptado: las hipótesis de precio en micro-juntas (<150 afiliados) y de uso del portal por usuarios quedan sin validar hasta el piloto.
