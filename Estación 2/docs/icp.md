# ICP — Ideal Customer Profile — Ramal

> Basado en: Product Vision Board, deep-research-validacion.md y deep-research-critica.md (14/sep/2026).
> Alcance: Colombia primero; extensión LATAM vía CLOCSAS (+145.000 OCSAS) cuando el canal institucional lo habilite.

---

## 1. Definición del ICP (segmento ideal)

**Organización:** Junta Administradora de Acueducto Comunitario o Rural (JAAP / JACA / asociación de usuarios) en Colombia.

**Filtros de calificación (criterios duros del ICP):**

| Criterio | Valor ideal |
|---|---|
| Número de afiliados | 100–800 (sweet spot ~150–500) |
| Presión regulatoria | Inscrita o en proceso de inscripción (SINAS/RUPS/SSPD); alcanzada por Decreto 0960 de 2025 |
| Contexto | Vereda/corregimiento con señal celular intermitente (offline-first obligatorio) |
| Actitud de la directiva | Junta **honest pero presionada** — quiere blindar su reputación, no ocultar cuentas |
| Gatillo activo | Asamblea reciente con quejas de cuentas, obra financiada por entidad externa (PDA/CAR/regalías), o proceso de formalización en curso |
| Disposición a pagar | Ya cobra tarifas de $10.000–$40.000 COP/usuario/mes → software de $80.000–$120.000 COP/mes es ~0,5–1% del recaudo |

**Anti-ICP (excluir del go-to-market inicial):**
- Juntas dirigidas de forma irregular u opacas — el comprador natural es quien más se resiste a transparentar (riesgo #1 de la crítica). No convencer: rodear (canal institucional, presión bottom-up).
- Micro-juntas <100 afiliados: precio mínimo ($25.000–40.000 COP/mes) puede no cubrir costo de soporte.
- ESP formales (>1.000 suscriptores, con planta administrativa): mejor servidas por Software GBS / Acuasoft.

---

## 2. Buyer Personas

### Persona 1 — El Tesorero (buyer principal y usuario diario)

| Campo | Detalle |
|---|---|
| Perfil | Líder voluntario, 35–65 años, >70% sin educación superior (Gamboa 2020), lleva las cuentas en cuaderno o Excel improvisado |
| Motivación | Que la asamblea no lo acuse; terminar el periodo con su reputación intacta; dejar el acueducto "en orden" |
| Dolor #1 | Reconciliar recaudo manual con gastos: plata que entra en efectivo, recibos sueltos, cuaderno que "no cuadra" |
| Dolor #2 | Preparar el informe de rendición de cuentas para la asamblea: le toma días y siempre queda alguien desconfiado |
| Dolor #3 | Morosidad alta: cobra puerta a puerta, enfrentamientos con vecinos, cartera que crece |
| Objeciones esperadas | "No sé usar computadores" · "¿Cuánto es al mes? Ya pagamos mucho en papel" · "¿Y si se daña y pierdo las cuentas?" · "La junta anterior no usaba nada de esto" |
| Gatillo de compra | Miedo a la próxima asamblea; un gasto grande reciente (tubería, bomba) que lo obligó a justificarse |
| Mensaje que mueve | **Blindaje:** "Tus cuentas claras, verificables y a prueba de acusaciones. El informe de asamblea se redacta solo." (el pitch anti-corrupción NO es el que compra; validar cuál pesa más) |
| Canal | WhatsApp (es su herramienta nativa), reuniones de red regional, voz-a-voz de presidentes de junta |

### Persona 2 — El Presidente de la Junta (decisor / controla el veto de confianza)

| Campo | Detalle |
|---|---|
| Perfil | Líder comunal reconocido, elegido en asamblea, rota cada 2 años; quien decide adoptar o no |
| Motivación | Legado: que su gestión se recuerde como la que "enderezó" el acueducto |
| Dolor #1 | Cada queja de usuario ("¿en qué se gasta la plata?") se convierte en un problema político personal |
| Dolor #2 | Que la junta anterior dejara cuentas desordenadas y él cargue con el desgaste |
| Objeciones esperadas | **"Transparentar me expone"** (la objeción central del proyecto) · "¿Qué pasa si el sistema dice que hay algo raro?" · "Otro software ya probamos y lo abandonamos" |
| Objeción latente | Si él es quien tiene algo que esconder → es anti-ICP; no perder tiempo, canalizar vía usuarios/entidad financiadora |
| Gatillo de compra | Asamblea conflictiva reciente; exigencia de la SSPD/alcaldía; obra financiada que exige rendición formal |
| Mensaje que mueve | "El sistema no te acusa: te defiende. Todo queda registrado con evidencia — ni tú ni tu tesorero podrán ser acusados de lo que no hicieron. Y las alertas siempre pasan por revisión humana, nunca son veredictos automáticos." |
| Canal | Red Nacional de Acueductos, ACER Agua Viva (Meta), asambleas de asociaciones, tutoría presencial del piloto |

### Persona 3 — El Fontanero / Operador (usuario diario, no comprador)

| Campo | Detalle |
|---|---|
| Perfil | A veces remunerado (bajo sueldo), a veces el mismo tesorero o un voluntario; maneja lecturas, fugas, cortes |
| Dolor #1 | Tomar y transcribir lecturas manuales en papel; olvidos y errores de transcripción |
| Dolor #2 | Registrar novedades (fugas, medidores dañados) sin forma de evidenciarlas después |
| Objeciones esperadas | "Otra app más en el celular" · "En la vereda no hay señal" |
| Requisito para él | App **offline-first** que funciona sin señal y sincroniza sola; foto + GPS como evidencia, flujo de 3 toques máximo |
| Rol en adopción | Si él no lo usa, no hay data → no hay portal → no hay producto. Es barrera de adopción tanto como el comprador |

### Persona 4 — El Usuario del Acueducto (beneficiario y fiscalizador; NO paga el software)

| Campo | Detalle |
|---|---|
| Perfil | Familia rural, paga $10.000–$40.000 COP/mes de tarifa, desconfía del manejo de recursos |
| Dolor | "Pago pero no sé en qué se usa mi plata" — el eslabón del círculo vicioso que rompe Ramal |
| Comportamiento hipotético (⚠ sin validar) | Consultaría el portal/WhatsApp bot para ver gastos con evidencia |
| Rol en el modelo | Su fiscalización convierte el pago en socialmente exigible → baja la morosidad (métrica #1: >15 puntos) |
| Riesgo documentado | Podría NO consultar espontáneamente (crítica, hipótesis 2). Mitigación: Pivot B — WhatsApp Bot ("¿cuánto se gastó en tubería este mes?") en el canal que ya usa |
| Riesgo de diseño | Privacidad: el consumo individual de un vecino NO puede ser público (Ley 1581 de 2012). Granularidad público/privado desde el día 1 |

### Persona 5 — El Financiador Institucional (canal B2G/B-ONG; el que escala el negocio)

| Campo | Detalle |
|---|---|
| Quién | PDA/MVCT, CARs, alcaldías, ONGs y programas de agua que financian obras rurales; redes gremiales (Red Nacional, CLOCSAS) |
| Dolor | Desembolsa recursos y no tiene forma verificable de saber si la junta los administró bien; los censos de acueductos están desordenados (caso Villavicencio: Alcaldía 76 vs censos 126 vs SSPD 15) |
| Objeciones esperadas | "¿Otra herramienta más que las juntas no usarán?" · "¿Tienen soporte para cientos de juntas?" · "¿Cumplen requisitos de seguridad de datos?" |
| Gatillo de compra | Obligación de rendición como condición de desembolso; Decreto 0960 de 2025 (ola de formalización con acceso a recursos) |
| Modelo | Licencia por portafolio de juntas, anual — **hipótesis puramente teórica hasta tener 1 LOI (meta: 6 meses)** |
| Rol estratégico | Sin este canal, el TAM solo-juntas es ~$9.000 USD MRR a 3 años: negocio real pero pequeño. Este tier es el que escala |

---

## 3. Mapa de objeciones y respuestas (battle card)

| # | Objeción | Respuesta / estrategia |
|---|---|---|
| 1 | "Transparentar me expone" (Presidente) | Reencuadre a blindaje: registro append-only con hash encadenado + evidencia fotográfica → las acusaciones falsas mueren. El pitch de blindaje es el primario; el anti-corrupción, secundario. |
| 2 | "No sé usar computadores" (Tesorero) | Paradigma Assistant: la AI redacta el informe por él; él revisa y aprueba. WhatsApp como canal de consulta. Onboarding presencial vía la red de acueductos. |
| 3 | "Es caro / no hay plata" | Anclar: ~0,5–1% del recaudo mensual; competidor (AquaProgrammer) cobra ~$978 COP/afiliado/mes a escala. Y el argumento de negocio: transparencia → baja morosidad >15 puntos → más recaudo que el costo del software. |
| 4 | "Ya probamos software y lo abandonamos" | Offline-first real, WhatsApp como soporte, plan de continuidad entre rotaciones de junta (la cuenta es de la junta, no del tesorero). Reconocer: la rotación bienal es un riesgo real que mitigamos con re-onboarding barato. |
| 5 | "¿Qué pasa si detecta algo raro?" | Las alertas de AI son siempre "para revisión humana", nunca veredictos automáticos. Fatiga de alertas = muerte por falsos positivos (<5% tolerado). |
| 6 | "Mi información de consumo no puede ser pública" | Correcto — y está diseñado: granularidad público/privado por rol desde el día 1, cumplimiento Ley 1581 de 2012. |
| 7 | "Integrin es gratis del Estado" | Integración, no competencia: importamos datos de GPSI. Ganamos en simplicidad (back-office pesado para voluntarios) y en el ángulo que Integrin no tiene: fiscalización ciudadana. |
| 8 | "¿Y si se daña y pierdo las cuentas?" | Registro append-only en la nube; el cuaderno físico sí se pierde, se moja y se quema. |

---

## 4. Mensajes por segmento (una línea cada uno)

- **Tesorero:** "Tus cuentas cuadran solas y el informe de asamblea se redacta solo."
- **Presidente:** "Blinda tu reputación: cada peso registrado con evidencia que nadie puede alterar."
- **Usuario final:** "Por fin sabes en qué se usa tu plata — directo en tu WhatsApp."
- **Institucional:** "Verificabilidad de cada peso desembolsado, junta por junta, sin auditorías manuales."
- **Redes/gremios:** "Una herramienta de rendición para todas sus juntas afiliadas, a precio de vereda."

---

## 5. Hipótesis del ICP que siguen sin validar (del deep research de crítica)

1. Que las juntas pagarían $50.000–$120.000 COP/mes — piso de precios de micro-juntas desconocido. Validar en piloto + entrevistas a 5–10 tesoreros.
2. Que los usuarios consultarán el portal ≥1 vez/mes (>30% target). Validar con métrica del piloto; plan B: WhatsApp Bot.
3. Que el pitch de blindaje mueve la adopción más que el pitch anti-corrupción.
4. Que instituciones firman LOIs por portafolios de juntas (meta: 1 LOI en 6 meses).
5. Que el costo de soporte por junta se mantiene <20% del ARPU (riesgo de soporte intensivo rural).

**Decisión documentada:** el desarrollo no espera estas validaciones; el piloto del acueducto de mi vereda (primer adoptante, ya con disposición a pagar) es el mecanismo de validación. Este ICP es revisable con cada aprendizaje del piloto.
