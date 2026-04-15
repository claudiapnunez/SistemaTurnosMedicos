# Introducción al Sistema de Gestión de Turnos Médicos

## Descripción del Sistema

El Sistema de Gestión de Turnos Médicos es una aplicación diseñada para optimizar la administración de turnos en un consultorio médico. Permite a los pacientes solicitar turnos, a los médicos gestionar su agenda y a los recepcionistas coordinar la atención diaria. El sistema automatiza notificaciones, valida disponibilidad en tiempo real y mantiene un registro completo del historial de atención.

## Actores del Sistema

### Paciente
Persona que solicita atención médica. Puede solicitar, cancelar y reprogramar turnos, así como consultar su historial de atención.

### Médico
Profesional de la salud que atiende a los pacientes. Gestiona su agenda, consulta los turnos asignados y registra información en la historia clínica.

### Recepcionista
Personal administrativo que coordina la atención. Registra pacientes, gestiona turnos, verifica cobertura de obras sociales y atiende consultas presenciales y telefónicas.

### Sistema
Componente automatizado que envía notificaciones (recordatorios de turnos, confirmaciones, cancelaciones), valida reglas de negocio y gestiona la disponibilidad de la agenda.

## Requerimientos Funcionales

1. **RF01 - Solicitar Turno:** El sistema debe permitir solicitar un turno seleccionando médico, especialidad, fecha y hora disponible.
2. **RF02 - Cancelar Turno:** El sistema debe permitir cancelar un turno existente con al menos 24 horas de anticipación.
3. **RF03 - Consultar Agenda Médica:** El sistema debe mostrar la disponibilidad de cada médico por fecha y horario.
4. **RF04 - Registrar Paciente:** El sistema debe permitir el alta de nuevos pacientes con sus datos personales y obra social.
5. **RF05 - Gestionar Historia Clínica:** El sistema debe permitir al médico registrar diagnósticos, tratamientos y observaciones por consulta.
6. **RF06 - Confirmar Turno:** El sistema debe enviar una confirmación al paciente y registrar el estado del turno como confirmado.
7. **RF07 - Reprogramar Turno:** El sistema debe permitir cambiar la fecha u hora de un turno existente sin perder la información asociada.
8. **RF08 - Gestionar Obras Sociales:** El sistema debe validar la cobertura del paciente según su obra social y plan.
9. **RF09 - Enviar Notificaciones:** El sistema debe enviar recordatorios automáticos 24 horas antes del turno por email o SMS.
10. **RF10 - Generar Reportes:** El sistema debe generar reportes de turnos atendidos, cancelados y pendientes por período.
11. **RF11 - Gestionar Consultorios:** El sistema debe asignar consultorios disponibles según la especialidad del médico.
12. **RF12 - Autenticar Usuarios:** El sistema debe validar las credenciales de acceso según el rol del usuario.

## Requerimientos No Funcionales

1. **RNF01 - Usabilidad:** La interfaz debe ser intuitiva y accesible, permitiendo completar la solicitud de un turno en menos de 3 pasos.
2. **RNF02 - Disponibilidad:** El sistema debe estar disponible el 99.5% del tiempo durante el horario de atención (8:00 a 20:00).
3. **RNF03 - Seguridad:** Los datos de los pacientes deben estar protegidos según la Ley de Protección de Datos Personales (Ley 25.326).
4. **RNF04 - Rendimiento:** El sistema debe responder a cualquier consulta en menos de 2 segundos.
5. **RNF05 - Escalabilidad:** El sistema debe soportar al menos 100 usuarios concurrentes sin degradación del servicio.
6. **RNF06 - Compatibilidad:** El sistema debe ser accesible desde navegadores web modernos y dispositivos móviles.

## Casos de Uso Principales

1. **CU-001:** Solicitar Turno
2. **CU-002:** Cancelar Turno
3. **CU-003:** Consultar Agenda Médica
4. **CU-004:** Registrar Paciente
5. **CU-005:** Gestionar Historia Clínica
6. **CU-006:** Confirmar Turno
7. **CU-007:** Reprogramar Turno

## Clases Principales del Sistema

1. **Paciente:** Representa a la persona que solicita atención médica. Almacena datos personales, obra social e historial de turnos.
2. **Médico:** Representa al profesional de salud. Contiene especialidad, matrícula y horarios de atención.
3. **Turno:** Representa una cita médica programada. Registra fecha, hora, estado, paciente y médico asignado.
4. **Agenda:** Gestiona la disponibilidad horaria de un médico. Contiene los bloques de tiempo y turnos asignados.
5. **Consultorio:** Representa el espacio físico donde se realiza la atención. Tiene número, ubicación y equipamiento.
6. **Recepcionista:** Representa al personal administrativo. Gestiona turnos y atención al público.
7. **ObraSocial:** Representa la entidad de cobertura médica. Valida planes, coberturas y autorizaciones.
