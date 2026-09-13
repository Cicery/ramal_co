# Deep Research — Validación y Crítica: Ramal

*Investigación realizada con AI (web search, fuentes 2025) como insumo para el Product Vision Board.*

---

## 1. Transcripción resumida — Validación

### Tamaño del mercado y contexto (Colombia)

- **~12.000 acueductos comunitarios** estimados en Colombia; solo **3.649 inscritos** en SINAS (Ministerio de Vivienda) y ~1.919 ante la SSPD. (Mongabay, entrevista a Adriana Baquero — ACER Agua Viva, oct. 2025)
- Atienden al **40% de la población rural**; más de **9 millones de personas** se abastecen de acueductos comunitarios.
- En América Latina: **+145.000 OCSAS** (Organizaciones Comunitarias de Sistemas de Agua y Saneamiento) que sirven a **+70 millones de personas** (CLOCSAS, 15 países).
- Caso Villavicencio: entre el 30% y 40% de una capital de departamento (>200.000 personas) se abastece de acueductos comunitarios; la Alcaldía reconoce 76, la SSPD solo tiene registrados 15, la red comunitaria censó 126 → **el Estado no sabe ni cuántos son**, hay espacio para herramientas que formalicen.

### El problema es administrativo y de confianza, no técnico

Estudios 2025 (Business Review / Dialnet / Dícere) documentan de forma consistente:

- **30-40% de los acueductos comunitarios rurales no funcionan o funcionan pobremente** (Lockwood, 2019).
- Operan **sin contabilidad estructurada, sin estudios tarifarios**, con baja cultura de pago y alta cartera (morosidad).
- Hallazgos del estudio de Zipacón (Cundinamarca): "ausencia de manuales de operación, falta de control y planeación financiera, cartera elevada que no permitía liquidez".
- **Desconfianza interna documentada**: "discrepancias en la toma de decisiones y desconfianza en el manejo de recursos… afectan la cohesión del colectivo y la continuidad del servicio".
- La literatura recomienda explícitamente: "involucrar a la comunidad validando que todos los procesos sean transparentes; presentación de informes periódicos de rendición de cuentas e incluyendo a las comunidades en la toma de decisiones" — **exactamente la tesis de Ramal**.
- **Círculo vicioso validado**: tarifas bajas + morosidad → sin liquidez → sin mantenimiento → mal servicio → usuarios no pagan. La transparencia rompe el eslabón de "no pago porque no confío".

### Marco regulatorio a favor (timing)

- **Decreto 0960 de 2025** (vigente desde sept. 2025): reglamenta la gestión comunitaria del agua, reconoce el agua como bien común, da enfoque diferencial a acueductos comunitarios (antes se les exigía igual que a empresas prestadoras) y les abre acceso a recursos estatales.
- Ley 142 de 1994 + Decreto 421 de 2000: las comunidades sin ánimo de lucro pueden prestar el servicio legalmente.
- Resoluciones CRA (844/2018, 571/2019, 943/2021) exigen reportes tarifarios y de calidad → necesidad de herramientas que los generen.
- Plan Nacional de Desarrollo (art. 274, Ley 2294 de 2023): numerales de fortalecimiento a acueductos comunitarios.
- **Implicación**: hay una ola de formalización inminente; miles de juntas van a necesitar llevar cuentas formales por primera vez.

### Usuario típico

- Líderes de junta voluntarios: **>70% no supera educación secundaria** (Gamboa, 2020) → el producto debe ser simple, con AI que redacte informes por ellos, no herramientas contables complejas.

---

## 2. Transcripción resumida — Crítica (debilidades y riesgos)

### Competencia existente (ninguna con transparencia al usuario como núcleo)

| Competidor | Qué hace | Débil frente a Ramal |
|---|---|---|
| **Software Integrin** (GPSI, gratuito del MVCT) | Suite completa: comercial, financiero, nómina, SUI. 25 años, +500 implementaciones (+300 rurales) | Es back-office del administrador; pesado; cero portal ciudadano |
| **HAPINET** | Plataforma cloud para acueductos veredales: facturación, medición, recaudo, laboratorio, SUI/CRA | Enfoque en la junta, no en el suscriptor-vigilante |
| **AquaProgrammer** | App móvil offline (lecturas, foto, GPS), facturación automática, portal de pagos; ~$978 COP/usuario/mes | Portal del administrador; el usuario final solo paga, no vigila |
| **Mi Vereda** | Facturación en sitio offline con impresora térmica, recaudo por Efecty/SuRed | Solo facturación/cobro |

### Riesgos identificados

1. **Adopción por la junta = veto interno.** El administrador/tesorero actual puede ver transparencia radical como amenaza a su discrecionalidad (o a sus negocios informales). Los primeros clientes serán juntas ya comprometidas con la transparencia — empezar por redes/gremios.
2. **Conectividad rural**: se requiere app offline-first en campo; la AI solo corre al sincronizar.
3. **Capacidad de pago**: organizaciones de bajos ingresos; pricing por tamaño y tier gratuito de transparencia como adquisición.
4. **Privacidad**: si todo es público, se pueden exponer deudas o datos de usuarios específicos → diseñar granularidad público/privado desde el día 1.
5. **Manipulación de registros**: una junta corrupta podría alterar datos antes de publicar → registro append-only con hash encadenado + evidencia fotográfica obligatoria de gastos.
6. **Alertas AI falsas**: acusar a un vecino erróneamente destruye confianza → alertas siempre "para revisión humana", nunca veredictos automáticos.
7. **Riesgo estatal**: Integrin es gratis y promovido por el MVCT; si agregan portal ciudadano y lo empujan por PDA, aplasta el pricing. Mitigación: integrarse con él (importar datos), no competir de frente.

### Conclusión

La validación es fuerte: problema masivo, documentado, con respaldo regulatorio nuevo y sin competidor centrado en el usuario-vigilante. La crítica exige: offline-first, granularidad de privacidad, integridad de registros (append-only), y distribución vía redes comunitarias antes que venta directa.

---

## Fuentes principales

- Mongabay (2025): [Acueductos comunitarios en Colombia — entrevista ACER Agua Viva](https://es.mongabay.com/2025/10/acueductos-comunitarios-colombia-agua-biodiversidad-entrevista/)
- International Business Review (2025): [Análisis situacional de la gestión administrativa de acueductos comunitarios rurales](https://doi.org/10.26668/businessreview/2025.v10i3.5323)
- Boletín Interamericano (2025): [Acueductos rurales basados en la comunidad — revisión de factores restrictivos](https://doi.org/10.62943/bij.v4n2.2025.314) ([PDF Dialnet](https://dialnet.unirioja.es/descarga/articulo/10550903.pdf))
- Dícere, Universidad Libre (2025): [El servicio de acueducto rural en el ordenamiento jurídico colombiano](https://doi.org/10.33324/dicere.v2i2.1003)
- MinVivienda: [SIASAR — Sistema de Información de Agua y Saneamiento Rural](https://www.minvivienda.gov.co/viceministerio-de-agua-y-saneamiento-basico-siasar-sistema-de-informacion-de-agua-y-saneamiento-rural)
- Competidores: [HAPINET](https://hapinet.com.co/), [AquaProgrammer](https://aquaprogrammer.com/), [Mi Vereda](https://mivereda.com/), [GPSI Integrin](https://gpsi.com.co/software-integrin-web)
