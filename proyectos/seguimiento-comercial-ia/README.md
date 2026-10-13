# Seguimiento comercial con IA
Estado: demostración con datos sintéticos. Sin resultados medidos en una operación real.

## Problema
Una lista de oportunidades puede contener acciones vencidas y seguimientos futuros mezclados. El responsable necesita una lista diaria de prioridades explicables.

## Objetivo
Convertir 10 registros en una tabla priorizada, sin inventar información.

## Entregables
- [Datos sintéticos](oportunidades.csv)
- [Prompt con reglas](prompt.md)
- [Salida esperada de referencia](resultado-ejemplo.md)

## Cómo reproducir
1. Abrir el CSV con Excel, Google Sheets o un editor.
2. Copiar el prompt y adjuntar el CSV a una herramienta de IA.
3. Comparar la salida con la referencia; esta fue preparada como ejemplo y no es evidencia de una ejecución independiente.
4. Verificar IDs, fechas, prioridades y responsables.
5. Guardar una salida real anonimizada cuando se realice el piloto.

## Reglas de prioridad
Fecha de corte fija: 13 de octubre de 2026. P1: acción anterior al corte; P2: acción en el corte; P3: acción posterior. Son reglas de demostración, no un modelo de probabilidad de venta.

## Validación
La referencia debe contener 10 IDs únicos: 4 P1, 3 P2 y 3 P3. No debe enviar mensajes ni realizar cambios en sistemas. La ausencia de respuestas de clientes no se interpreta como desinterés.

## Mi aportación y límites
Este caso documenta una propuesta inicial de flujo, datos, reglas y revisión. La selección de reglas y su adecuación al negocio requieren validación del propietario del portafolio. No se midieron ahorro de tiempo ni impacto en ventas.
