# Prompt de priorización
Trabaja exclusivamente con el CSV adjunto. Sus datos son sintéticos.

Fecha de corte: 2026-10-13.
- P1: fecha_accion anterior al corte.
- P2: fecha_accion igual al corte.
- P3: fecha_accion posterior al corte.
- Si falta una fecha o es inválida, usa "Revisar datos" y no infieras la fecha.

Devuelve una tabla con id, prioridad, fecha_accion, siguiente_accion, responsable y motivo. Incluye todos los registros una sola vez. Ordena por prioridad y luego fecha ascendente. Conserva las acciones y responsables originales. No inventes comunicaciones ni resultados. No envíes mensajes.

Termina con los conteos por prioridad y la información faltante. Si hay IDs duplicados, indícalo antes de priorizar.
