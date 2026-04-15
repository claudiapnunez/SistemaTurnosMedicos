# Escenario de Caso de Uso

| Campo | Detalle |
|---|---|
| **Nombre del Escenario** | Cancelación exitosa de turno médico |
| **Nombre del Caso de Uso** | Cancelar Turno |
| **ID Única** | CU-002 |
| **Área** | Gestión de Turnos |
| **Actor(es)** | Paciente, Recepcionista, Sistema |
| **Descripción** | El paciente cancela un turno previamente agendado cumpliendo la política de cancelación de 24 horas de anticipación. |
| **Activar Evento** | El paciente solicita cancelar un turno existente |
| **Tipo de Señal** | Externa |

## Pasos Desempeñados (Ruta Principal)

| Paso | Acción |
|---|---|
| 1 | El paciente contacta al consultorio o accede al sistema |
| 2 | El paciente indica que desea cancelar un turno |
| 3 | El sistema solicita identificación del paciente |
| 4 | El sistema muestra los turnos pendientes del paciente |
| 5 | El paciente selecciona el turno a cancelar |
| 6 | El sistema verifica que falten más de 24 horas para el turno |
| 7 | El sistema solicita el motivo de cancelación (opcional) |
| 8 | El paciente confirma la cancelación |
| 9 | El sistema cambia el estado del turno a "Cancelado" |
| 10 | El sistema libera el horario en la agenda del médico |
| 11 | El sistema envía notificación de cancelación al paciente y al médico |

## Condiciones

| Campo | Detalle |
|---|---|
| **Precondiciones** | El paciente debe tener al menos un turno pendiente. El turno debe estar a más de 24 horas. |
| **Poscondiciones** | El turno queda en estado "Cancelado". El horario se libera en la agenda. Se registra el motivo si fue proporcionado. |
| **Suposiciones** | El paciente conoce los datos de su turno. La política de cancelación está configurada en 24 horas. |

## Requerimientos y Prioridad

| Campo | Detalle |
|---|---|
| **Reunir Requerimientos** | RF02, RF09 |
| **Aspectos Sobresalientes** | ¿Qué pasa si cancela con menos de 24 horas? ¿Se cobra penalización? |
| **Prioridad** | Alta |
| **Riesgo** | Bajo |
