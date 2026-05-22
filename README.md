# SaludYa - Proyecto Completo

Proyecto base para SaludYa con:
- Backend: Node.js + Express + MongoDB
- Frontend: React + React Router
- Inicio de sesión con **username y password** para usuarios internos
- Título automático según nivel de acceso y sexo
- Pacientes sin login; consultan documentos por identificación

## Niveles de acceso internos
- Administrador -> Admin.
- Admisión -> Lic.
- Médico -> Dr. / Dra.
- Facturación -> Lic.

## Portal externo para pacientes
Los pacientes **no necesitan usuario ni contraseña**.
La consulta de documentos médicos se realiza desde un portal externo usando:
- tipo de identificación
- número de identificación

## Módulos internos
- Configuración
- Admisión
- Citas
- Historia Clínica
- Órdenes Médicas
- Facturación

##  Historias EYDER Arroyo
##HU1 – Configuración de usuarios
Como administrador
Quiero crear usuarios dentro del sistema
Para asignar accesos según el rol de cada funcionario.
Descripción
El sistema permite al administrador registrar usuarios con información básica, credenciales y roles específicos como administrador, médico, admisión y facturación.
Estado
Implementada.
 
##HU2 – Gestión de roles
Como administrador
Quiero asignar roles y permisos a los usuarios
Para controlar el acceso a los módulos del sistema.
Descripción
El módulo de configuración permite restringir el acceso a funcionalidades dependiendo del rol del usuario autenticado.
Estado
Implementada.

## Historias Cristian Bacca
##HU3 – Registro de pacientes
Como usuario de admisión
Quiero registrar pacientes en el sistema
Para almacenar y gestionar su información clínica.
Descripción
El módulo de admisión permite ingresar datos personales del paciente como identificación, nombres, dirección, teléfono y antecedentes básicos.
Estado
Implementada.
##HU4 – Búsqueda de pacientes
Como usuario de admisión
Quiero buscar pacientes por documento
Para evitar registros duplicados y consultar información rápidamente.
Descripción
El sistema permite consultar pacientes mediante tipo y número de identificación para reutilizar información existente.
Estado
Implementada.

## Historias  Andres Pardo 
HU5 – Agendamiento de citas médicas
Como usuario de admisión
Quiero agendar citas médicas
Para organizar la atención de los pacientes.
Descripción
El módulo de citas permite seleccionar fecha, médico, tipo de consulta y asignar citas a pacientes registrados previamente en admisión.
Estado
Implementada.
 
##HU6 – Gestión de estado de citas
Como usuario del sistema
Quiero confirmar, cancelar o reprogramar citas médicas
Para administrar adecuadamente la agenda médica.
Descripción
El sistema permite modificar el estado de las citas médicas y reprogramarlas según disponibilidad.
Estado
Implementada.

