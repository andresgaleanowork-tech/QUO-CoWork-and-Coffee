# QUO — Due Diligence de Traspaso de Cafetería (v1.0)

Plantilla maestra para **cualquier** target (incluida una futura reapertura de Il Crostino). Regla: ninguna respuesta en "No sabe / No aplica" autoriza a firmar. El vendedor que se niega a aportar un bloque entero pierde puntos según el peso del bloque.

## Bloque A — El alquiler (peso 30 %)
- [ ] Copia del contrato de arrendamiento completo (cláusulas, anexos, fianzas, garantías)
- [ ] Duración restante y prórrogas según LAU 2029/… (persona física vs jurídica); ¿el casero puede denegar la subrogación?
- [ ] Consentimiento **escrito del propietario** al traspaso y al cambio/explotación por nuevo titular
- [ ] Renta actual + último recibo + revisión de renta (¿IPCA topado 2026?)
- [ ] ¿Existe derecho de tanteo/retracto o opción de compra a favor de alguien?
- [ ] Fianza depositada en el organismo autonómico (IVASF) — justificante
- [ ] Acta de la última junta de propietarios: ¿derramas aprobadas/pendentes? ¿estatutos prohíben hostelería?

## Bloque B — Licencias y urbanismo (peso 20 %)
- [ ] Licencia de actividad/apertura original + última modificación; cotejo con actividad IAE proyectada (659.1 cafés vs mezcla con restauración)
- [ ] Informe urbanístico municipal (Ayto. Sagunto / Valencia): uso admisible, aforo legal, condiciones de terrazas
- [ ] **Licencia de terraza**: título, nº de mesas autorizadas, ocupación vía pública (tasa), vigencia tras cambio de titularidad
- [ ] Proyecto técnico / memoria de actividad + certificado de instalaciones eléctricas y de gas
- [ ] Registro Sanitario / APPCC al día; plan de autocontrol; control de plagas (contrato + últimos informes)
- [ ] Plan de evacuación/autoprotección, luces de emergencia, extintores revisados (si aplica por aforo)
- [ ] Expediente de sanciones: solicitar histórico en el ayuntamiento (disciplina urbanística y de consumo)
- [ ] Protección auditiva/medición de ruido si hay música o eventos

## Bloque C — Números del negocio (peso 25 %)
- [ ] Exportación del TPV o libro registro 24–36 meses (diario, no resumido) → tickets/día, ticket medio, por franja horaria
- [ ] **Conteo presencial propio**: 2 días laborables + 2 festivos + 2 en hora valle (10–13 y 16–19), contando comensales y tickets
- [ ] Liquidaciones IVA (303) y Resúmenes IRPF últimos 2 años → ingresos declarados vs caja del TPV (la diferencia es el margen de error del vendedor)
- [ ] Cuentas de resultados 3 años (modelo Pyme) con firma del asesor
- [ ] Comprobantes de los 12 últimos meses de: alquiler, luz, agua, gas, basura, asesoría, seguros, alquileres de máquina (cafetera, horno, frío), software TPV, música (SGAE si hay)
- [ ] Compras anuales por proveedor top-5 (café, leche, panadería, bebidas) → % COGS real
- [ ] Inventario valorado: ficha por activo (marca, año, estado, valor residual, último mantenimiento técnico de cafetera y horno)
- [ ] Deudas: certificado negativo AEAT + TGSS + vida laboral de empresas; IBI/vertidos si es propiedad; préstamos con garantía sobre activos
- [ ] Contratos de mantenimiento/asistencia técnica con condiciones (¡la cafetera sin servicio es un cierre de 3 días!)

## Bloque D — Personas y laboral (peso 15 %)
- [ ] Plantilla: contratos, convenio (Hostelería CV), categorías, antigüedad, salarios brutos reales con complementos
- [ ] Nóminas y TCs/RLC últimos 24 meses; horas extra y complementarias acumuladas; vacaciones disfrutadas/pendientes; festivos
- [ ] ¿Relevo generacional/parcial? Situación de contratos eventuales y "fijos discontinuos"
- [ ] Conflictos laborales, inspecciones de trabajo previas, sanciones
- [ ] ¿Alguno es familiar del vendedor con contrato ficticio? (auditar bases de cotización vs salario)
- [ ] Acuerdos de no competencia y de confidencialidad firmados con el vendedor (radio 1–2 km, ≥2 años)
- [ ] Formación PRL de la plantilla

## Bloque E — Cliente, marca y digital (peso 10 %)
- [ ] Reseñas Google/TripAdvisor: media, evolución, respuestas del dueño (un 4,3 con reseñas airadas = pasivo de marca a sanear)
- [ ] Cuotas/membresías de clientes privados (si el local las tuvo: gimnasios, empresas con factura mensual) → lista de contactos con consentimiento
- [ ] Cuentas de redes y web: ¿a nombre de quién? Transferir administradores por contrato
- [ ] Base de datos de clientes (RGPD: consentimiento verificable, o no vale)
- [ ] ¿Hay proveedores con condiciones atadas a la persona física del vendedor? (créditos, descuentos, máquina cedida)
- [ ] Nombre "Il Crostino": ¿registrado? ¿el traspaso incluye o excluye fondos de comercio/enseñas? (QUO será marca nueva: registrar en la OEPM/EUIPO antes de rotular)

## Bloque F — Cierre legal del deal
- [ ] Contrato privado de arras/traspaso con penalización cruzada (lote de 5k: doble devolución si retracta el vendedor)
- [ ] Inventario final anexo firmado con fotos y nº de serie
- [ ] Cláusulas de garantía de resultados + retención de la última cuota de la nota del vendedor a 6/12/18 (colateral del DD)
- [ ] Subrogación pactada de: fianza, licencia, contratos de suministros, seguros, TPV
- [ ] Alta censal, cambio de titularidad IAE, comunicación a la TGSS (contratos), notificación al ayuntamiento (titular de la licencia)
- [ ] Cuentas abiertas con firma del nuevo titular desde llaves (el dinero del traspaso, nunca por B sin factura)

---

## Ritual de los 12 supuestos (antes de la LOI)

Antes de escribir una cifra, responde por escrito (con datos, no con fe) los 12 supuestos del §12 del Plan. Formato por supuesto: `Dato → Fuente → Verificado por (iniciales) → Fecha`. El expediente completo va al Data Room del deal (`Deals/<nombre-local>/`), estructura mínima:

```
Deals/01-<local>/
  00_term-sheet-vX.md          # términos de §8.2 del plan
  01-alquiler/                 # bloque A escaneado
  02-licencias/                # bloque B
  03-numeros/                  # bloque C (CSV TPV + liquidaciones)
  04-personal/                 # bloque D
  05-marca-digital/            # bloque E
  06-actas-reunion/            # notas fechadas con vendedor/casero
  99-pacto-socios.md
```
