# Tarjeta CRC - Agenda

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | Agenda |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy la agenda de un médico. Gestiono su disponibilidad horaria y los turnos asignados. Sé qué horarios están libres y cuáles ocupados." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Definir bloques horarios de atención | Medico |
| Verificar disponibilidad en fecha y hora | Turno |
| Asignar turno en horario libre | Turno |
| Liberar horario al cancelar turno | Turno |
| Listar turnos del día | Turno |
| Bloquear horarios por ausencia del médico | Medico |

## Propiedad

| Propiedad | Tipo |
|---|---|
| medico | Medico |
| bloquesHorarios | List<BloqueHorario> |
| turnosAsignados | List<Turno> |
| fechaInicio | Date |
| fechaFin | Date |
