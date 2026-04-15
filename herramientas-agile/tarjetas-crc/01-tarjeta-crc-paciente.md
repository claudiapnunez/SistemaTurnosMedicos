# Tarjeta CRC - Paciente

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | Paciente |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy un paciente del consultorio. Conozco mis datos personales, mi obra social y mi historial de turnos. Puedo solicitar, cancelar y consultar mis turnos médicos." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Almacenar datos personales (nombre, DNI, teléfono, email) | - |
| Registrar y validar obra social | ObraSocial |
| Solicitar un nuevo turno | Turno, Agenda |
| Cancelar un turno existente | Turno |
| Consultar historial de turnos | Turno |
| Recibir notificaciones de recordatorio | Turno |

## Propiedad

| Propiedad | Tipo |
|---|---|
| nombre | String |
| apellido | String |
| dni | String |
| telefono | String |
| email | String |
| fechaNacimiento | Date |
| obraSocial | ObraSocial |
| historialTurnos | List<Turno> |
