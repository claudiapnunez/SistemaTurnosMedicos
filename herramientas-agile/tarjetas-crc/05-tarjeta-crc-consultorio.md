# Tarjeta CRC - Consultorio

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | Consultorio |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy un consultorio del centro médico. Conozco mi número, ubicación y equipamiento. Puedo ser asignado a turnos según la especialidad requerida." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Almacenar datos del consultorio (número, piso, ubicación) | - |
| Registrar equipamiento disponible | - |
| Verificar disponibilidad en fecha y hora | Turno |
| Asignarse a un turno | Turno |
| Asociarse a especialidades médicas | Medico |

## Propiedad

| Propiedad | Tipo |
|---|---|
| numero | Integer |
| piso | String |
| ubicacion | String |
| equipamiento | List<String> |
| especialidades | List<String> |
