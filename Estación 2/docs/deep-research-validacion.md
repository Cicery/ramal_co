# Deep Research de Validación — Ramal

> Producto: Plataforma de gestión y transparencia para acueductos rurales y comunitarios.
> Fecha: 14 de septiembre de 2026. Fuentes consultadas en línea; todas referenciadas.

## 1. El problema es real y está documentado

### 1.1 Tamaño del segmento

- En Colombia hay **más de 11.000 acueductos comunitarios** que abastecen a millones de personas en veredas, corregimientos y cabeceras municipales sin empresa de acueducto formal. Son la principal —y en muchos casos la única— fuente de agua potable rural. (Fuente: colombiatramita.co/servicios-publicos/acueductos-comunitarios/, guía 2026, con base en Ley 142 de 1994 y Decreto 1898 de 2016)
- Existe una **Red Nacional de Acueductos Comunitarios de Colombia** (redacueductoscomunitarios.co) que articula asociaciones, redes y federaciones — existiendo un actor institucional de juntas a escala nacional (canal de distribución potencial y fuente de entrevistas).
- Regulación conocida y estable: Ley 142/1994 (art. 15 reconoce comunidades organizadas como prestadoras), Decreto 1898/2016 (esquemas diferenciales rurales), Resolución 0844/2018, registro en RUPS ante Superservicios. **La formalización es una política de Estado**, lo que empuja a las juntas a digitalizarse.

### 1.2 El dolor administrativo/financiero es estructural

- La gestión típica es papel y cuadernos: la tarifa se fija en asamblea, el recaudo es manual, el libro de cuentas es físico. (reddeagua.com/agua-rural-urbana)
- **El manejo irregular de recursos es un conflicto reconocido y frecuente**: la propia guía de trámites instruye a los usuarios "si sospecha malversación, solicite el libro de cuentas en asamblea. Si la junta lo niega, acuda a la Personaría para iniciar un proceso de control social". Es decir: el mecanismo de auditoría actual es una asamblea con un cuaderno — exactamente el dolor que Ramal digitaliza. (colombiatramita.co, sección "Problemas frecuentes")
- Los usuarios tienen canales formales de queja (Superservicios, Personería, alcaldías), lo que confirma que la fiscalización de usuarios es una demanda institucionalizada, no una invención nuestra.

### 1.3 El dolor técnico y operativo es estructural

- La calidad del agua se mide por IRCA/SIVICAP; muchos acueductos rurales están en riesgos medio-alto. Las juntas deben publicar resultados de laboratorio a los usuarios (obligación actual que hoy se cumple en papel o no se cumple).
- Cortes de servicio, fugas y toma de lecturas manuales son la operación diaria del fontanero — sin herramienta digital en la mayoría de casos.

### 1.4 La competencia confirma el mercado, no lo refuta

Los competidores ya validan que existen acueductos dispuestos a pagar por software:

| Competidor | Qué ofrece | Modelo de precio | Lo que NO ofrece |
|---|---|---|---|
| **Acuasoft** (Sotalia Labs S.A.S., acuasoft.com) | Facturación, recaudo, cartera, micromedición, DIAN, contabilidad | Cotización por suscriptores; mes a mes sin cláusulas | No hay portal de fiscalización para los usuarios finales; contabilidad es servicio aparte |
| **AquaProgrammer** (aquaprogrammer.com) | App offline de lecturas con foto+GPS+firma, billling masivo, macromedidores, +5.063 usuarios en producción | Por suscriptores; ejemplo: 1.800 suscriptores ≈ **$1.760.000 COP/mes (~$978 COP/usuario)** | No hay portal público de rendición de cuentas ni Transparency Ledger; facturación DIAN es add-on |
| **Software GBS** (softwaregbs.co) | ERP contable NIIF/NICSP para ESP pequeñas, reportes SUI | Vertical en ESP formalas | Enfocado a empresas, no a juntas voluntarias de 100–800 afiliados |
| **ASOCOMUNAL / Jacapp** (asocomunal.org, jacapp.online) | Gestión general de JAC: afiliados, actas, tesorería, inventarios | Suscripción | Contexto de JAC genérica, no operativa de acueducto (sin lecturas, sin consumo) |
| **Acueducto.co** | Sitio web institucional + cumplimiento SSPD + PQRS | Plan gratuito disponible | Es marketing institucional, no ERP ni transparencia financiera |

**Hallazgo clave:** nadie en el mercado ofrece el "libro contable abierto" consultado por el usuario final del acueducto. La competencia le da herramientas al tesorero; Ramal le da auditoría al pueblo. Ese es el hueco.

### 1.5 Willingness to pay — señales

- Los acueductos ya pagan tarifas a sus usuarios de **$10.000–$40.000 COP/mes** por usuario (fuente: colombiatramita.co). Un software de $80.000–$120.000 COP/mes para una junta de 300–500 usuarios es ~0,5–1% del recaudo mensual — un porcentaje estándar de inversión administrativa.
- AquaProgrammer cobra ~$978 COP/usuario/mes a escala (junta de 1.800 usuarios = $1,76M COP/mes) y tiene clientes pagando en producción — prueba de que hayoneksi PAY real en el segmento.

### 1.6 El canal bottom-up es plausible

- Los usuarios de acueductos comunitarios ya denuncian malversación ante la Personería y Superservicios; el control social está institucionalizado (guía oficial de reclamos lo documenta).
- Las entidades financiadoras (Programa Agua al Campo / MinVivienda, regalías, CARs, CONPES 3810 de 2014) obligan a juntas a mejorar gestión y rendir cuentas — punto de entrada institucional (B2G/B-ONG).
- Nuestro piloto: el acueducto de mi vereda ya decidió sistematizarse — primer caso de estudio con costos reales de soporte.

## 2. Hipótesis que este research refuerza

1. Segmento lo suficientemente grande (~12.000 juntas solo en Colombia) y desatendido digitalmente.
2. El diferenciador de transparencia está vacante: los competidores realmente no atacan la fiscalización por parte de usuarios.
3. Hay disposición a pagar verificada por competidores en producción.
4. El marco legal (Superservicios, RUPS, asambleas) creará más demanda de trazabilidad, no menos.

---

## 3. Complemento (fusión con la investigación anterior, versión racol_copia)

La investigación previa (transcripción íntegra preservada en `deep-research-validacion-critica-version-anterior.md`) aporta datos más duros que refuerzan las hipótesis anteriores:

### 3.1 Cifras del mercado (más precisas)

- ~12.000 acueductos comunitarios en Colombia; solo 3.649 inscritos en SINAS y ~1.919 ante la SSPD → el Estado no los conoce bien; hay espacio para herramientas que apoyen la formalización. (Mongabay, oct. 2025, entrevista a Adriana Baquero — ACER Agua Viva)
- Atienden al 40% de la población rural: **más de 9 millones de personas**.
- Caso Villavicencio: la Alcaldía reconoce 76 acueductos comunitarios, los censos comunitarios cuentan 126, la SSPD solo tiene 15 → desorden de información que la plataforma puede ayudar a resolver.
- América Latina: **+145.000 OCSAS** sirviendo a **+70 millones de personas** (CLOCSAS, 15 países) → el mercado "global" existe y ya está articulado institucionalmente (CLOCSAS es canal de distribución potencial).

### 3.2 La causa raíz es administrativa/de confianza (evidencia académica)

- Estudios 2025 (International Business Review, Boletín Interamericano, Dícere/Universidad Libre) documentan que el 30–40% de los acueductos comunitarios rurales **no funcionan o funcionan mal**; operan sin contabilidad estructurada ni estudios tarifarios, con alta cartera.
- La literatura recomienda explícitamente lo que Ramal hace: "involucrar a la comunidad validando que todos los procesos sean transparentes; presentación de informes periódicos de rendición de cuentas e incluyendo a las comunidades en la toma de decisiones".
- **Círculo vicioso documentado:** tarifas bajas + morosidad → sin liquidez → sin mantenimiento → mal servicio → usuarios no pagan. La transparencia rompe el eslabón "no pago porque no confío" — este es el argumento de negocio cuantificable central de Ramal.

### 3.3 Timing regulatorio (nuevo y favorable)

- **Decreto 0960 de 2025** (vigente desde sept. 2025) reglamenta la gestión comunitaria del agua, reconoce el agua como bien común, da enfoque diferencial y abre acceso a recursos estatales → ola de formalización inminente que obliga a miles de juntas a llevar cuentas formales por primera vez.
- Resoluciones CRA (844/2018, 571/2019, 943/2021) exigen reportes tarifarios y de calidad — reportes que la AI de Ramal puede generar automáticamente.
- Plan Nacional de Desarrollo (art. 274, Ley 2294 de 2023): numerales de fortalecimiento de acueductos comunitarios.

### 3.4 Diseño del usuario

- >70% de los líderes de junta no supera educación secundaria (Gamboa, 2020) → confirma el paradigma Assistant: el producto debe redactar los informes por ellos, no darles herramientas contables complejas.

### 3.5 Fuentes adicionales (de la versión anterior)

- Mongabay (2025): es.mongabay.com/2025/10/acueductos-comunitarios-colombia-agua-biodiversidad-entrevista/
- International Business Review (2025): doi.org/10.26668/businessreview/2025.v10i3.5323
- Boletín Interamericano (2025): doi.org/10.62943/bij.v4n2.2025.314 (PDF Dialnet: 10550903)
- Dícere, Universidad Libre (2025): doi.org/10.33324/dicere.v2i2.1003
- MinVivienda SIASAR: minvivienda.gov.co (Sistema de Información de Agua y Saneamiento Rural)
