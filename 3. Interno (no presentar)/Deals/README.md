# Deals — expediente por oportunidad

> Un directorio por edificio/local en evaluación. El expediente NO sigue la vieja numeración de "traspaso de negocio" (bloques A–F de `Herramientas/DueDiligence_Traspaso_v1.0.md` siguen sirviendo para licencias y personal, pero el objeto central ahora es **el edificio y su propiedad**).

## Estructura estándar (ver `01-Muebles-Sagunto/` como modelo)

```
NN-<nombre>/
  00_expedificio.md              # qué hay que averiguar (registro, urbanismo, físico, familia)
  01_guion-pitch-propiedad.md    # cómo se abre la conversación
  02_mapa-de-aliados.md          # ecosistema con estado y pedidos
  03_lista-30-empresas.md        # panel de validación de la hipótesis
  04_guion-entrevista-empresas.md# metodología de las 30 conversaciones
  actas/                         # una por conversación, <24 h, con semáforo
  firmado/                       # NDA y cualquier papel firmado (fuera del repo si lleva cifras)
```

**Reglas:** estado del deal = señal del último acta. Nada se promete fuera de Fase 0 hasta el semáforo de `03`. Cifras y condiciones: solo en el Anexo Confidencial (fuera del repositorio, siempre).
