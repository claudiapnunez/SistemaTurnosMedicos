# Tarjeta CRC - Turno

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | Turno |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy un turno médico. Conozco mi fecha, hora, estado y los participantes. Puedo ser solicitado, confirmado, cancelado o reprogramado." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Registrar fecha y hora del turno | - |
| Asociar paciente y médico | Paciente, Medico |
| Gestionar estado (pendiente, confirmado, cancelado, completado) | - |
| Validar disponibilidad antes de confirmar | Agenda |
| Enviar notificación de confirmación | Paciente |
| Registrar motivo de cancelación | - |
| Asignar consultorio | Consultorio |

## Propiedad

| Propiedad | Tipo |
|---|---|
| id | Integer |
| fecha | Date |
| hora | Time |
| estado | EstadoTurno |
| paciente | Paciente |
| medico | Medico |
| consultorio | Consultorio |
| motivoCancelacion | String |
