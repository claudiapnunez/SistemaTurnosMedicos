# Documentación de uso de Copilot Agent Mode - Especialista en Escenarios de Casos de Uso

## Rol: Especialista en Escenarios de Casos de Uso
## Integrante: Claudia P Nunez (Matrícula: 131743)

---

## Prompt utilizado

> Actuando como Especialista en Escenarios de Casos de Uso para el sistema SistemaTurnosMedicos, leé el archivo anexos/introduccion.md como contexto. A partir de los 5 casos de uso principales definidos, generá un escenario exitoso detallado para cada uno. Cada escenario debe incluir: ID del escenario, título, caso de uso asociado, actor principal, actores secundarios, objetivo, precondiciones, flujo principal (paso a paso numerado), postcondiciones, prioridad y nivel de riesgo. Usá el formato Markdown con tablas para los campos y listas numeradas para los flujos.

## Archivos de contexto referenciados

- `anexos/introduccion.md` — Documento base con la descripción del sistema, actores, requisitos funcionales/no funcionales y casos de uso.
- `diagramas/02-casos-de-uso/*.puml` — Diagramas PlantUML de casos de uso como referencia para relaciones entre actores y casos.

## Ajustes realizados al output de la IA

1. **Precondiciones y postcondiciones**: Se refinaron para que sean verificables y específicas al contexto del sistema médico argentino (obras sociales, PAMI, etc.).
2. **Flujos principales**: Se ajustaron los pasos para mantener coherencia con los actores definidos en la introducción. Se eliminaron pasos redundantes y se agregaron validaciones implícitas del sistema.
3. **Prioridad y riesgo**: Se asignaron valores consistentes según la criticidad de cada caso de uso para el funcionamiento del sistema.
4. **Formato**: Se unificó el formato de todos los escenarios para mantener consistencia en la estructura de tablas y listas.
5. **Nomenclatura de archivos**: Se aplicó la convención de nombres establecida: `03-{nombre-caso-uso}-escenario-exitoso-{número}.md`.

## Resultado final

Se generaron 5 escenarios de casos de uso exitosos en formato Markdown:

| Archivo | Caso de Uso | Descripción |
|---------|-------------|-------------|
| `03-solicitar-turno-escenario-exitoso-01.md` | CU-001: Solicitar Turno | Paciente solicita y confirma un turno médico |
| `03-cancelar-turno-escenario-exitoso-02.md` | CU-002: Cancelar Turno | Paciente cancela un turno previamente agendado |
| `03-consultar-disponibilidad-escenario-exitoso-03.md` | CU-003: Consultar Disponibilidad | Recepcionista consulta agenda disponible |
| `03-registrar-paciente-escenario-exitoso-04.md` | CU-004: Registrar Paciente | Recepcionista registra un nuevo paciente |
| `03-gestionar-historia-clinica-escenario-exitoso-05.md` | CU-005: Gestionar Historia Clínica | Médico consulta y actualiza historia clínica |

## Reflexión sobre el uso de IA

La IA fue útil para generar una estructura base consistente para los 5 escenarios, asegurando que todos siguieran el mismo formato y nivel de detalle. Sin embargo, fue necesario intervenir manualmente para:

- Adaptar la terminología al contexto de salud argentino
- Asegurar coherencia entre los escenarios y los diagramas de casos de uso generados por el Modelador
- Verificar que los actores y sus responsabilidades coincidieran con las tarjetas CRC del Diseñador
- Ajustar los niveles de prioridad y riesgo según criterios del equipo
