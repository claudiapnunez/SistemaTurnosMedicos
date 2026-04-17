# Documentación de uso de Copilot Agent Mode - Documentador y Coordinador

## Rol: Documentador y Coordinador
## Integrante: Claudia P Nunez (Matrícula: 131743)

---

## Prompt utilizado

> Actuando como Documentador y Coordinador del proyecto SistemaTurnosMedicos, generá la documentación general del proyecto. Esto incluye: 1) Un README.md profesional con descripción del proyecto, estructura del repositorio, integrantes, y enlaces a cada sección. 2) Un changelog.md con el registro de cambios organizados por rol y tipo de cambio (Added, Fixed, Changed). 3) Archivos índice (anexos.md, diagramasUML.md, herramientas_agile.md, escenarios_de_casos_de_uso.md, diagramas_de_casos_de_uso.md) que vinculen a los archivos generados por cada rol. 4) Verificá la coherencia entre todos los entregables de los distintos roles.

## Archivos de contexto referenciados

- `anexos/introduccion.md` — Documento base del sistema
- `herramientas-agile/tarjetas-crc/*.md` — Tarjetas CRC generadas por el Diseñador
- `diagramas/02-casos-de-uso/*.puml` — Diagramas de casos de uso del Modelador
- `diagramas/03-escenarios-casos-de-uso/*.md` — Escenarios del Especialista

## Archivos generados y coordinados

### Documentación principal

| Archivo | Descripción |
|---------|-------------|
| `README.md` | Página principal del proyecto con descripción, estructura, integrantes y enlaces |
| `changelog.md` | Registro de cambios por rol con convención Keep a Changelog |
| `anexos/anexos.md` | Índice de la sección de anexos |
| `diagramas/diagramasUML.md` | Índice general de diagramas UML |
| `herramientas-agile/herramientas_agile.md` | Índice de herramientas ágiles |

### Índices de subsecciones

| Archivo | Descripción |
|---------|-------------|
| `diagramas/02-casos-de-uso/diagramas_de_casos_de_uso.md` | Índice de diagramas de casos de uso |
| `diagramas/03-escenarios-casos-de-uso/escenarios_de_casos_de_uso.md` | Índice de escenarios de casos de uso |

### Templates de Pull Request

| Archivo | Descripción |
|---------|-------------|
| `.github/PULL_REQUEST_TEMPLATE/feature-template.md` | Template para PRs de feature branches |
| `.github/PULL_REQUEST_TEMPLATE/release-template.md` | Template para PRs de release branches |

## Ajustes realizados al output de la IA

1. **Estructura de carpetas**: Se organizó el repositorio siguiendo una convención clara y navegable, con índices en cada nivel de la jerarquía.
2. **Enlaces relativos**: Se verificaron y corrigieron todos los enlaces internos entre archivos para asegurar navegación correcta en GitHub.
3. **Coherencia entre roles**: Se validó que los nombres de archivos, actores y casos de uso fueran consistentes entre las tarjetas CRC, los diagramas y los escenarios.
4. **Changelog**: Se estructuró siguiendo la convención Keep a Changelog, agrupando los cambios por tipo (Added, Fixed) y por rol.
5. **README**: Se adaptó para incluir la información institucional requerida (materia, universidad, cuatrimestre, docente).

## Verificación de coherencia

Se realizaron las siguientes verificaciones cruzadas entre los entregables de todos los roles:

| Verificación | Estado |
|-------------|--------|
| Actores en CRC coinciden con actores en diagramas de caso de uso | ✅ Verificado |
| Casos de uso en diagramas coinciden con escenarios | ✅ Verificado |
| Responsabilidades en CRC son coherentes con flujos de escenarios | ✅ Verificado |
| Colaboraciones en CRC reflejan relaciones en diagramas | ✅ Verificado |
| Nomenclatura de archivos es consistente en todo el proyecto | ✅ Verificado |
| Enlaces internos en índices apuntan a archivos existentes | ✅ Verificado |

## Reflexión sobre el uso de IA

Como Documentador y Coordinador, la IA fue especialmente valiosa para:

- Generar la estructura base de archivos índice con formato consistente
- Crear el changelog con el nivel de detalle necesario
- Mantener la coherencia en nomenclatura y formato a través de múltiples archivos

La intervención manual fue necesaria para:

- Verificar que todos los enlaces relativos funcionaran correctamente en GitHub
- Asegurar que la información institucional fuera precisa
- Coordinar que los entregables de los 4 roles fueran consistentes entre sí
- Adaptar el README al formato esperado por la cátedra
