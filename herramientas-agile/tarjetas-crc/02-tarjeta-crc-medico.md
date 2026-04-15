# Tarjeta CRC - Medico

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | Medico |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy un médico del consultorio. Conozco mi especialidad, mi matrícula y mis horarios de atención. Gestiono mi agenda y atiendo a los pacientes en sus turnos." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Almacenar datos profesionales (nombre, matrícula, especialidad) | - |
| Gestionar horarios de atención | Agenda |
| Consultar turnos asignados | Turno, Agenda |
| Atender pacientes en el consultorio | Paciente, Consultorio |
| Registrar información en historia clínica | Paciente |

## Propiedad

| Propiedad | Tipo |
|---|---|
| nombre | String |
| apellido | String |
| matricula | String |
| especialidad | String |
| telefono | String |
| email | String |
| agenda | Agenda |
