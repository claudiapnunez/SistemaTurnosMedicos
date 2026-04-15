# Tarjeta CRC - ObraSocial

| Campo | Detalle |
|---|---|
| **Nombre de la Clase** | ObraSocial |
| **Superclase** | Ninguna |
| **Subclase** | Ninguna |
| **Pensamiento del Objeto** | "Yo soy una obra social. Conozco mis planes de cobertura y puedo validar si un paciente tiene autorización para una prestación médica." |

## Responsabilidades

| Responsabilidad | Colaboración |
|---|---|
| Almacenar datos de la obra social (nombre, código) | - |
| Gestionar planes de cobertura | - |
| Validar cobertura de un paciente | Paciente |
| Autorizar prestaciones médicas | Turno |
| Verificar vigencia del plan | Paciente |

## Propiedad

| Propiedad | Tipo |
|---|---|
| nombre | String |
| codigo | String |
| planes | List<Plan> |
| telefono | String |
| email | String |
