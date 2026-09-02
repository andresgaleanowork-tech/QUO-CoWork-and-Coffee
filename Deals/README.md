# Deals — data room por traspaso candidato

Un directorio por local evaluado. La estructura mínima y los bloques de documentación están definidos en
`../1. Plan de Negocio Unificado/DueDiligence_Traspaso_v1.0.md`.

```
NN-<nombre-local>/
  00_term-sheet-vX.md          # términos (modelo: §8.2 del plan maestro)
  01-alquiler/                 # bloque A
  02-licencias/                # bloque B
  03-numeros/                  # bloque C (CSV del TPV, liquidaciones, suministros)
  04-personal/                 # bloque D
  05-marca-digital/            # bloque E
  06-actas-reunion/            # notas fechadas con vendedor/casero
  99-notas.md                  # semáforo por bloque: verde/ámbar/rojo + fecha
```

**Regla de estado:** un deal solo pasa de `explorando` a `LOI` cuando los bloques A, B, C y D tienen evidencia
documental (no verbal). Un bloque rojo = deal muerto, no deal "a ver si mejora".
