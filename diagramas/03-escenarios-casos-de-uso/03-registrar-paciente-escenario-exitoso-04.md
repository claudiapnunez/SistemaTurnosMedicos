# Escenario de Caso de Uso

| Campo | Detalle |
|---|---|
| **Nombre del Escenario** | Registro exitoso de nuevo paciente |
| **Nombre del Caso de Uso** | Registrar Paciente |
| **ID Única** | CU-004 |
| **Área** | Gestión de Pacientes |
| **Actor(es)** | Recepcionista, Sistema |
| **Descripción** | La recepcionista registra un nuevo paciente con sus datos personales y obra social en el sistema. |
| **Activar Evento** | Un paciente nuevo se presenta en el consultorio |
| **Tipo de Señal** | Externa |

## Pasos Desempeñados (Ruta Principal)

| Paso | Acción |
|---|---|
| 1 | La recepcionista accede al módulo de registro de pacientes |
| 2 | El sistema muestra el formulario de registro |
| 3 | La recepcionista ingresa el DNI del paciente |
| 4 | El sistema verifica que el DNI no esté registrado |
| 5 | La recepcionista ingresa datos personales (nombre, apellido, teléfono, email, fecha de nacimiento) |
| 6 | La recepcionista selecciona la obra social del paciente |
| 7 | El sistema valida los datos ingresados |
| 8 | El sistema genera la ficha del paciente |
| 9 | El sistema confirma el registro exitoso |

## Condiciones

| Campo | Detalle |
|---|---|
| **Precondiciones** | El paciente no debe estar previamente registrado. La recepcionista debe estar autenticada. |
| **Poscondiciones** | El paciente queda registrado en el sistema con una ficha activa. |
| **Suposiciones** | El paciente proporciona datos válidos. La obra social está cargada en el sistema. |

## Requerimientos y Prioridad

| Campo | Detalle |
|---|---|
| **Reunir Requerimientos** | RF04, RF08 |
| **Aspectos Sobresalientes** | ¿Qué pasa si el DNI ya está registrado? ¿Se permite registrar sin obra social? |
| **Prioridad** | Alta |
| **Riesgo** | Bajo |
