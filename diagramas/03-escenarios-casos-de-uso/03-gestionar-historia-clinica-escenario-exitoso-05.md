# Escenario de Caso de Uso

| Campo | Detalle |
|---|---|
| **Nombre del Escenario** | Gestión exitosa de historia clínica |
| **Nombre del Caso de Uso** | Gestionar Historia Clínica |
| **ID Única** | CU-005 |
| **Área** | Gestión Clínica |
| **Actor(es)** | Médico, Sistema |
| **Descripción** | El médico accede a la historia clínica de un paciente durante la consulta para registrar diagnóstico y tratamiento. |
| **Activar Evento** | El médico inicia la atención de un paciente con turno confirmado |
| **Tipo de Señal** | Externa |

## Pasos Desempeñados (Ruta Principal)

| Paso | Acción |
|---|---|
| 1 | El médico accede al sistema con sus credenciales |
| 2 | El sistema muestra los turnos del día |
| 3 | El médico selecciona el turno del paciente a atender |
| 4 | El sistema muestra la historia clínica del paciente |
| 5 | El médico revisa antecedentes y consultas previas |
| 6 | El médico registra el motivo de consulta |
| 7 | El médico registra el diagnóstico |
| 8 | El médico registra el tratamiento indicado |
| 9 | El médico agrega observaciones adicionales (opcional) |
| 10 | El sistema guarda el registro en la historia clínica |
| 11 | El sistema actualiza el estado del turno a "Completado" |

## Condiciones

| Campo | Detalle |
|---|---|
| **Precondiciones** | El médico debe estar autenticado. El paciente debe tener un turno confirmado para el día. |
| **Poscondiciones** | La historia clínica queda actualizada. El turno pasa a estado "Completado". |
| **Suposiciones** | El médico tiene permisos para editar historias clínicas. El paciente asistió al turno. |

## Requerimientos y Prioridad

| Campo | Detalle |
|---|---|
| **Reunir Requerimientos** | RF05, RF12 |
| **Aspectos Sobresalientes** | ¿Se pueden adjuntar estudios o imágenes? ¿Hay registro de auditoría de cambios? |
| **Prioridad** | Alta |
| **Riesgo** | Alto |
