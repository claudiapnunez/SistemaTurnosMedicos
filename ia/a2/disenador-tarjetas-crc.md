# Documentación de uso de Copilot Agent Mode - Diseñador de Tarjetas CRC

## Rol: Diseñador de Tarjetas CRC
## Integrante: Claudia P Nunez

## Prompt utilizado

> Lee el archivo anexos/introduccion.md como contexto del sistema de gestión de turnos médicos. Identificá las clases principales del sistema y generá tarjetas CRC para cada una siguiendo la plantilla proporcionada. Cada tarjeta debe incluir: nombre de la clase, superclase/subclase (si aplica), pensamiento del objeto en primera persona, responsabilidades principales con sus colaboraciones, y propiedades con sus tipos.

## Archivos de contexto referenciados

- `anexos/introduccion.md` — Descripción completa del sistema, actores, requerimientos funcionales y no funcionales, casos de uso y clases.

## Ajustes realizados al output de la IA

1. **Corrección de colaboraciones:** Se ajustaron las colaboraciones entre clases para que fueran bidireccionales y coherentes. Por ejemplo, Turno colabora con Agenda para validar disponibilidad, no al revés.
2. **Pensamiento del objeto:** Se reescribieron los pensamientos del objeto para que fueran más naturales y reflejaran mejor la identidad de cada clase.
3. **Propiedades:** Se agregaron tipos de datos específicos (Date, Time, List<>) donde la IA había dejado tipos genéricos.
4. **Clase ObraSocial:** Se agregó esta clase que la IA no había incluido inicialmente, considerando que es fundamental para la validación de cobertura.
5. **Formato:** Se ajustó el formato markdown para que coincidiera exactamente con la plantilla proporcionada por la cátedra.

## Resultado final

Se generaron 7 tarjetas CRC completas para las clases: Paciente, Medico, Turno, Agenda, Consultorio, Recepcionista y ObraSocial. Todas las tarjetas mantienen coherencia en las colaboraciones cruzadas y reflejan las responsabilidades definidas en los requerimientos funcionales del sistema.
