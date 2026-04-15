# Escenario de Caso de Uso

| Campo | Detalle |
|---|---|
| **Nombre del Escenario** | Consulta exitosa de agenda médica |
| **Nombre del Caso de Uso** | Consultar Agenda Médica |
| **ID Única** | CU-003 |
| **Área** | Gestión de Agenda |
| **Actor(es)** | Paciente, Recepcionista, Médico |
| **Descripción** | Un actor consulta la disponibilidad de horarios de un médico para una fecha determinada. |
| **Activar Evento** | El actor desea conocer los horarios disponibles de un médico |
| **Tipo de Señal** | Externa |

## Pasos Desempeñados (Ruta Principal)

| Paso | Acción |
|---|---|
| 1 | El actor accede a la función de consulta de agenda |
| 2 | El sistema muestra las especialidades disponibles |
| 3 | El actor selecciona una especialidad |
| 4 | El sistema muestra los médicos de esa especialidad |
| 5 | El actor selecciona un médico |
| 6 | El sistema muestra un calendario con las fechas disponibles |
| 7 | El actor selecciona una fecha |
| 8 | El sistema muestra los horarios disponibles y ocupados del médico para esa fecha |

## Condiciones

| Campo | Detalle |
|---|---|
| **Precondiciones** | El médico debe tener una agenda configurada con horarios de atención. |
| **Poscondiciones** | El actor visualiza la disponibilidad del médico. No se modifica ningún dato. |
| **Suposiciones** | El médico tiene horarios cargados. El sistema está operativo. |

## Requerimientos y Prioridad

| Campo | Detalle |
|---|---|
| **Reunir Requerimientos** | RF03 |
| **Aspectos Sobresalientes** | ¿Se muestra la agenda de varios días? ¿Se puede filtrar por obra social? |
| **Prioridad** | Alta |
| **Riesgo** | Bajo |
