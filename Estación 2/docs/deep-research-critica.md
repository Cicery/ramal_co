# Deep Research de Crítica — Ramal

> Contraparte adversarial del research de validación. Objetivo: encontrar la forma en que esto fracasa.
> Fecha: 14 de septiembre de 2026.

## 1. Riesgo existencial: el canal de venta es fricción pura

- **La investigación confirma la contradicción más peligrosa del proyecto:** quien decide comprar el software (la junta) es quien tiene interés en NO rendir cuentas más allá de lo obligatorio. Adicionalmente, aunque la competicia existe y el mercado es grande, ningún competidor hace portal de usuarios... y una posible explicación es que **no existe demanda del pagador (la junta) por esa feature**. Podría ser un producto para un comprador que no quiere comprarlo.
- **Contra-argumento (defensa):** la junta directiva honesta SÍ gana con la plataforma — blindaje contra acusaciones. El pitch a la junta es "protege tu reputación y tu libro de cuentas", no "te vas a vigilar". Validar en entrevistas si el pitch de blindaje mueve la adopción más que el pitch anti-corrupción.

## 2. ¿Le vendemos a un mercado que puede pagar? (Análisis de unit economics)

- Cifra honesta: 11.000 juntas "registradas" no significa 11.000 compradores. La gran mayoría son juntas de 30–300 usuarios, con directivas voluntarias que rotan cada año (cada cambio puede significar re-onboarding desde cero) y capacidades de pago frágiles.
- **TAM realista Colombia, solo tier Junta:** si en 3 años capturamos 400 juntas pagando $90.000 COP/mes promedio → $36M COP/mes ≈ **$9.000 USD MRR**. Es un negocio real pero *pequeño* por sí solo. el pitch "global" y "anti-corrupción" es la narrativa; el modelo de negocio del otro tier (Institucional B2G/B-ONG) es el que potencialmente lo escala. Sin el canal institucional, esto es risiblemente pequeño para ser una startup full-time.
- Los anuncios como ingreso secundario ayudarían marginalmente: con 400 juntas gratis y un promedio de $5.000 COP/mes de revenue publicitario por junta, los ingresos "integrados" serían unos USD $90/mes en la plataforma gratuita — es ruido, no margen.

## 3. Competencia: nos ganaron parte del terreno

- **AquaProgrammer ya implementó lo que creíamos era nuestro craft diferencial técnico**: app offline de lecturas con foto + GPS + firma del usuario, facturación masiva, macromedidores, +5.063 usuarios reales en producción desde 2021. Su "moat" (data histórica acumulada y clientes pagando) ya existe.
- Acuasoft ya ofrece contabilidad personalizada, flujo DIAN, WhatsApp, portal de pagos; Acueducto.co ya ofrece cumplimiento SSPD y plan gratuito — más económico que nuestro tier básico propuesto.
- **El único hueco no ocupado es el Transparency Ledger (portal de fiscalización pública de egresos + rendición de cuentas generada por AI).** Es la apuesta. Si ESE feature no logra marcas de conversión, Ramal es un clon débil de lo existente.

## 4. Riesgos de producto y operación en el entorno rural

- **Soporte como pesadilla:** juntas rurales de bajo alfabetismo digital generan soporte intensivo (llamadas por teléfono, visitas por WhatsApp). AquaProgrammer sobrevive porque "el desarrollador responde por WhatsApp" — eso no escala barato. El costo de soporte estimado podría comer el margen del 75%.
- **Rotación de la junta directiva:** se cambian cada 2 años en asamblea. Cada rotación = nueva capacitación, nueva cuenta, posible abandono. Retención incierta.
- **Sync offline con conflictos** (dos fontaneros sincronizando datos viejos) es quizás el bug más caro de manejar — y es el corazón del fontanero offline.
- **Fiscalización pública = exposición legal:** publicar egresos, estados de cuenta, cobros de afiliados en un portal pone privacidad (Ley 1581 de 2012, protección de datos personales colombiana) al medio. Un error de filtro (que el consumo individual del vecino sea público) puede matar el producto en una asamblea.

## 5. Riesgo del modelo de negocio "transparencia"

- **Conflicto de intereses estructural:** si la plataforma detecta irregularidades (AI de anomalías) y la junta es la quien paga... ¿qué pasa cuando la señal dice "tu tesorero está inflando gastos"? Presión de "páganos y somos neutrales" vs "reportamos". El trust moat exige un código de ética difícil de sostener comercialmente.
- **AI necesaria:** los tesoreros voluntarios rara vez creen el informe AI sin verificar. Si terminan editando casi todos los reportes, el costo de AI no retribuye — y si no los editan, hay riesgo de error que erosione confianza.

## 6. Hypótesis que el research NO valida (y que hay que entrevistar)

1. **Que las juntas pagarían $50.000–$120.000 COP/mes** — los competidores cobran más pero a escalas mayores; el piso de precios de micro-juntas (<300 usuarios) es desconocido. Entrevistar 5–10 tesoreros.
2. **Que los usuarios consultarán el portal**. Nada sugiere que la gente rural revisa app de su acueducto (dashboard de transparencia) espontáneamente, salvo en crisis. Intento de métrica en el piloto: % de usuarios que accede al portal ≥1 vez/mes.
3. **Que las ONGs/alcaldías pagarían licencias por portafolios de juntas** — hipótesis de canal puramente teórica hasta tener una carta de intento (LOI).
4. **Que el acueducto de mi vereda realmente sistematizará** — pending validación del propio piloto.

## 7. Simplifica o muere — Pivotes posibles si las hipótesis fallan

- **Pivot A (canal, no software):** estandarizar la venta vía la Red Nacional de Acueductos Comunitarios y federaciones departamentales — una venta que trae decenas de juntas.
- **Pivot B (producto convergente):** si los usuarios no consultan el portal, acercar la fiscalización al canal que SÍ usan: **WhatsApp Bot** — usuario escribe "cuánto se gastó en tubería este mes" y recibe respuesta multimedia con evidencia. Elimina el costo de retención de app.
- **Pivot C (primer comprador):** las ONGs y programas de agua que necesitan verificabilidad de sus obras financiadas — Ramal como plataforma de accountability para ellos, no para las juntas.

## 7b. Riesgos incorporados de la versión anterior (racol_copia)

- **Riesgo estatal — Integrin (GPSI):** suite **gratuita** del MVCT con 25 años, +500 implementaciones (+300 rurales): comercial, financiera, nómina y reportes SUI. Si el MVCT agrega un portal ciudadano y lo empuja por el canal de los PDA, aplasta cualquier pricing del segmento. Mitigación: integrarse (importar datos de Integrin), NO competir de frente; ganarlo en simplicidad y en el ángulo de vigilancia ciudadana. Este competidor no había sido detectado en nuestro research.
- **Integridad de registros:** una junta corrupta puede editar datos antes de publicarlos. Mitigación de diseño: registro **append-only con hash encadenado + evidencia fotográfica obligatoria de gastos** — cualquier alteración queda detectable.
- **Privacidad por diseño:** la granularidad público/privado con accesos por rol debe existir desde el día 1, no como parche post-incidente (conecta con el Riesgo 3 del vision board y la Ley 1581 de 2012 arriba).
- **Fatiga de alertas:** acusar erróneamente a un vecino destruye la confianza del producto. Las alertas de AI siempre se presentan "para revisión humana", nunca como veredictos automáticos.
- **Distribución vía redes/gremios:** la venta directa junta-a-junta es fricción pura (punto 1); la distribución viable es a través de redes (Red Nacional, ACER Agua Viva en el Meta, CLOCSAS en LATAM) y programas estatales (PDA, MVCT, Decreto 0960 de 2025). Una red que adopte Ramal como herramienta de rendición de cuentas trae decenas de juntas de golpe.
- **Morosidad como métrica de negocio:** el círculo vicioso (tarifas bajas + morosidad → sin liquidez → mal servicio → no pago) se rompe cuando el pago se vuelve socialmente exigible porque todos ven las cuentas. Medir **% de morosidad antes/después** en el piloto convierte la transparencia (ideal moral) en resultado de negocio (ahorro colectivo) — métrica #1 para la Estación 2.

## 8. Veredicto honesto para la Estación 2

La validación muestra un segmento doloroso, tamaño modesto pero real (con mercado LATAM articulado de 145.000 OCSAS), mercado ya educado por los competidores, un timing regulatorio favorable (Decreto 0960 de 2025) y un hueco (transparencia verificable) que nadie ocupa. La crítica muestra que ese hueco podría estar vacío porque nadie lo quiere, que el TAM solo-juntas es pequeño, que AquaProgrammer ya tiene la parte técnica y que el peligro estatal es Integrin. **El vision board se sostiene si:** (1) el piloto de mi vereda valida el uso real del portal (>30% de usuarios consultan ≥1 vez/mes) y baja la morosidad (>15 puntos); (2) se firma 1 LOI institucional en 6 meses; (3) el costo de soporte por junta se mantiene <20% del ARPU.
