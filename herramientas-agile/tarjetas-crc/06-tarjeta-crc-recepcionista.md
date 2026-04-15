# Tarjeta CRC - Recepcionista

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | Recepcionista |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy la recepcionista del consultorio. Atiendo al público, gestiono los turnos de los pacientes y verifico la cobertura de obras sociales." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Registrar nuevos pacientes | Paciente |
| Solicitar turnos en nombre del paciente | Turno, Agenda |
| Cancelar y reprogramar turnos | Turno |
| Verificar cobertura de obra social | ObraSocial |
| Consultar agenda del médico | Agenda, Medico |
| Atender consultas presenciales y telefónicas | Paciente |

## Propiedad

| Propiedad | Tipo |
|---|---|
| nombre | String |
| apellido | String |
| legajo | String |
| turno_laboral | String |
| email | String |
