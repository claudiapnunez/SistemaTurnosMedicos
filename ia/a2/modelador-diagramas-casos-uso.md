# Documentación de uso de Copilot Agent Mode - Modelador de Diagramas de Casos de Uso

## Rol: Modelador de Diagramas de Casos de Uso
## Integrante: Claudia P Nunez

## Prompt utilizado

> Lee el archivo anexos/introduccion.md como contexto. Generá código PlantUML para cada uno de los 5 casos de uso principales: Solicitar Turno, Cancelar Turno, Consultar Agenda Médica, Registrar Paciente y Gestionar Historia Clínica. Cada diagrama debe incluir actores principales, casos de uso con relaciones de asociación, inclusión y extensión según corresponda.

## Archivos de contexto referenciados

- `anexos/introduccion.md` — Actores, requerimientos y casos de uso del sistema.

## Ajustes realizados al output de la IA

1. **Relaciones:** Se corrigieron relaciones include/extend para que fueran semánticamente correctas según la definición UML.
2. **Actores:** Se verificó que cada diagrama incluyera solo los actores relevantes para ese caso de uso específico.
3. **Sintaxis PlantUML:** Se ajustó la sintaxis para que compilara correctamente con PlantUML.
4. **Nombres de archivos:** Se aplicó el naming convention definido por la cátedra.

## Resultado final

Se generaron 5 diagramas de casos de uso en formato .puml, almacenados en diagramas/02-casos-de-uso/.
