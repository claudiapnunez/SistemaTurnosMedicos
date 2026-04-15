# Escenario de Caso de Uso

| Campo | Detalle |
|---|---|
| **Nombre del Escenario** | Solicitud exitosa de turno médico |
| **Nombre del Caso de Uso** | Solicitar Turno |
| **ID Única** | CU-001 |
| **Área** | Gestión de Turnos |
| **Actor(es)** | Paciente, Recepcionista, Sistema |
| **Descripción** | El paciente solicita un turno médico seleccionando especialidad, médico, fecha y hora. El sistema verifica disponibilidad y confirma el turno. |
| **Activar Evento** | El paciente solicita un turno por teléfono, presencialmente o vía web |
| **Tipo de Señal** | Externa |

## Pasos Desempeñados (Ruta Principal)

| Paso | Acción |
|---|---|
| 1 | El paciente contacta al consultorio o accede al sistema |
| 2 | La recepcionista solicita los datos del paciente |
| 3 | El sistema verifica que el paciente esté registrado |
| 4 | El paciente selecciona la especialidad médica deseada |
| 5 | El sistema muestra los médicos disponibles para esa especialidad |
| 6 | El paciente selecciona un médico |
| 7 | El sistema muestra las fechas y horarios disponibles |
| 8 | El paciente selecciona fecha y hora |
| 9 | El sistema verifica la disponibilidad del horario seleccionado |
| 10 | El sistema registra el turno con estado "Pendiente" |
| 11 | El sistema envía una notificación de confirmación al paciente |
| 12 | El sistema actualiza la agenda del médico |

## Condiciones

| Campo | Detalle |
|---|---|
| **Precondiciones** | El paciente debe estar registrado en el sistema. El médico debe tener horarios de atención configurados. |
| **Poscondiciones** | El turno queda registrado con estado "Pendiente". La agenda del médico se actualiza. El paciente recibe confirmación. |
| **Suposiciones** | El sistema está operativo. El médico tiene disponibilidad en la fecha solicitada. |

## Requerimientos y Prioridad

| Campo | Detalle |
|---|---|
| **Reunir Requerimientos** | RF01, RF03, RF06, RF09 |
| **Aspectos Sobresalientes** | ¿Qué sucede si el paciente no está registrado? ¿Se puede reservar más de un turno por día? |
| **Prioridad** | Alta |
| **Riesgo** | Medio |
