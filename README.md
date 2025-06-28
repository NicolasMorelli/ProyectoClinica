**Gestión Web para Clínica Médica**
Este proyecto fue desarrollado como trabajo final para la facultad, y consistió en la implementación de un sistema completo de gestión médica para una clínica, accesible a través de una plataforma web.

El sistema fue desarrollado utilizando ASP.NET con C# para la lógica del servidor, combinando HTML y CSS para el diseño y la presentación visual. Para la persistencia de datos, se utilizó Microsoft SQL Server, diseñando e implementando 
una base de datos relacional adaptada a las necesidades de una clínica real.

**#######--- Funcionalidades principales ---########**
Gestión de turnos médicos:
Los usuarios pueden agendar turnos de manera sencilla, seleccionando especialidad, médico y fecha. El sistema valida la disponibilidad y registra el turno en la base de datos.

ABML de médicos y pacientes:
El sistema cuenta con un panel de administración que permite realizar altas, bajas, modificaciones y listados tanto de médicos como de pacientes. Se contemplan campos personales, especialidades médicas y estado del registro.

Hay dos tipos principales de usuarios:
Administrador: con acceso total a la gestión del sistema: administración de usuarios, turnos, pacientes, médicos e informes.
Médico: con acceso a su agenda personal de turnos y a los datos relevantes de los pacientes asignados.

Sección de informes:
Se desarrolló una sección dedicada a generar informes sobre turnos, cantidad de pacientes atendidos, historial de actividad por médico, entre otros datos relevantes, con el objetivo de facilitar la toma de decisiones en la clínica.


**#######--- Estructura del proyecto: ---########**
El sistema sigue una arquitectura basada en el patrón MVC (Modelo - Vista - Controlador), adaptada a un enfoque en capas:

Entidades: representan las clases de datos (como Paciente, Médico, etc.).
DAO (Data Access Object): capa de acceso a datos, que maneja las consultas y operaciones sobre la base de datos.
Negocio: contiene la lógica de negocio del sistema, funcionando como controlador entre los datos y la interfaz.
Vistas: comprende la capa visual e interfaz del usuario.

Esta estructura facilita la organización del código, la separación de responsabilidades y la escalabilidad del sistema.


**#######--- Consideraciones técnicas ---########**
Se aplicaron buenas prácticas de desarrollo, separando claramente la lógica del negocio de la presentación.

La base de datos fue modelada con claves foráneas, relaciones uno a muchos, validaciones y procedimientos almacenados.

Se contempló la escalabilidad del sistema y la seguridad de acceso mediante sesiones y validación de usuarios.

Este proyecto permitió consolidar conocimientos sobre el desarrollo de aplicaciones web completas con base de datos, aplicando lo aprendido en programación, diseño de interfaces, lógica empresarial y administración de bases de datos.
