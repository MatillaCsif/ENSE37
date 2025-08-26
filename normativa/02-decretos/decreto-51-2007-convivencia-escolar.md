---
id: <tipo-num-año-titulo-corto>           # p.ej., decreto-51-2007-convivencia-escolar
tipo: <Ley|Decreto|Orden|Instrucción|Circular>
numero: <número>                           # p.ej., 51
anio: <año>                                # p.ej., 2007
titulo: <título oficial>
jurisdiccion: Castilla y León              # ¡siempre CYL!
sector: Educación
estado: <vigente|derogado|parcial>
fecha_publicacion: YYYY-MM-DD
boe_bocyl: BOCYL
aplicabilidad:
  ambito_territorial: Castilla y León
  niveles: [infantil, primaria, secundaria, fp]   # ajusta según aplique
  centros: [públicos, concertados, privados]      # ajusta según aplique
vigencia:
  desde: YYYY-MM-DD
  hasta: null                                     # o fecha si está derogado
derogaciones:
  deroga: []                                      # ids de normas derogadas
  derogado_por: []                                # ids de normas que lo derogan
modificaciones:
  modificado_por: []                              # ids de normas que lo modifican
enlaces_oficiales:
  - https://...                                   # enlace(s) BOCYL
fuentes_pdf:
  - path: anexos/jurisprudencia/...               # si subes PDF propio o sentencia
tags: [tema1, tema2, tema3]
sinonimos_busqueda: [palabra1, palabra2]          # ayuda a la búsqueda
articulos_destacados:
  - art: 5
    tema: <tema del art.>
  - art: 12
    tema: <tema del art.>
ultima_revision: YYYY-MM-DD                       # cuándo revisaste este archivo
revisor: <tu nombre o equipo>
---

# Resumen ejecutivo
Explica en 8–12 líneas qué regula, a quién aplica, y por qué importa. Incluye
contexto de uso típico (p.ej., convivencia, permisos, licencias…).

# Texto/estructura de la norma (índice)
- Título I — Disposiciones generales
- Título II — Derechos y deberes…
- Cap. X — Procedimientos, plazos y órganos competentes
- Disposiciones adicionales/transitorias/finales

# Extractos clave (con referencias)
> **Art. 5** — Derechos del alumnado: …  
> **Art. 20** — Medidas correctoras y proporcionalidad: …

# Procedimientos y plazos
- **Quién**: órgano competente (dirección, inspección, etc.)
- **Plazos**: X días hábiles para Y
- **Recursos**: alzada/reposición, plazo, órgano
- **Documentación**: modelos, anexos, acreditaciones

# Ámbito y límites (check de aplicabilidad)
- ✅ Aplica en centros: públicos / concertados / privados (ajustar)
- ✅ Etapas: Infantil / Primaria / ESO / Bachillerato / FP (ajustar)
- ❗ No aplica cuando… (excepciones)
- 🔁 Relación con otras normas (remisiones, jerarquía)

# Interacciones y concordancias
- Complementa a: <id-otra-norma>
- Desarrolla: <id-ley-marco>
- Debe leerse junto con: <id-orden-relacionada>

# Cambios y versiones (historial)
- [YYYY-MM-DD] Revisado por <X>, notas: …
- [YYYY-MM-DD] Actualizado “modificado_por” con <id>

# Casos prácticos / ejemplos
- **Ejemplo 1**: Sanción por conducta Y → Art. X, plazos Z, recurso…
- **Ejemplo 2**: Permiso docente por … → requisitos, documentos, base legal.

# Preguntas frecuentes (FAQ)
- ¿Puedo …? → Sí/No. Base: Art. …
- ¿Qué plazo …? → X días. Base: Art. …

# Jurisprudencia o resoluciones relacionadas (si hay)
- STSJ CyL <fecha> — resumen 3–4 líneas — enlace/archivo
- Resolución DG <fecha> — criterio aplicado…

# Enlaces
- BOCYL: …
- Otros recursos: guía oficial, notas interpretativas…
