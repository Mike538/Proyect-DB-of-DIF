# Proyect-DB-of-DIF
-------------------------------------------
Entidades Agenda
-------------------------------------------

> [!IMPORTANT]
> Cita:

*clave id
* Fecha
* Hora
* Motivo de la Cita
* Codigo
* Recursos Especiales
* Recordatorio de Cita
* No. de expediente si son de primera vez o subsecuentes


> [!IMPORTANT]
> Paciente:

* Nombre
* Apellido
* Género
* Dirección
* Número de Teléfono
* Correo Electrónico
* Contacto de Emergencia
* Condiciones Médicas


> [!IMPORTANT]
> Psicologa:

* Nombre
* Apellido
* Especialización
* Número de Licencia
* Horario de Disponibilidad
* Datos de Contacto
* Tipo de Terapia


> [!IMPORTANT]
> Grupo de Edad:

* Nombre del Grupo (por ejemplo, "Niños", "Adolescentes", "Adultos")
* Edad Mínima
* Edad Máxima


> [!IMPORTANT]
> Estado de la Cita:

* Nombre del Estado (por ejemplo, "Programada", "Confirmada", "En Progreso", "Completada", "Cancelada")


> [!IMPORTANT]
> Recepción:

* Nombre
* Apellido
* Rol en la Recepción
* Horario de Trabajo
* Datos de Contacto


Estos son ejemplos de atributos que podrías considerar para cada entidad en tu sistema de gestión de citas psicológicas. Por supuesto, la elección de atributos dependerá de las necesidades específicas de tu clínica o centro de atención psicológica. Asegúrate de incluir todos los datos necesarios para el funcionamiento eficiente de tu sistema y el cumplimiento de las regulaciones de privacidad de datos aplicables en tu área. Además, ten en cuenta que algunos atributos pueden ser opcionales o requeridos según la situación y los requisitos legales y de seguridad de la información.

---------------------------------------------------------
Entidades:
---------------------------------------------------------

* Cita: Representa la entidad principal en tu base de datos. Esta entidad contendrá información sobre las citas programadas.

* Paciente: Representa la información relacionada con los pacientes que asisten a las citas.

* Psicologa: Contendrá información sobre los terapeutas que ofrecen servicios.

* Grupo de Edad: Puede ser una entidad que describe los grupos de edad, como "Niños", "Adolescentes" y "Adultos". Esta entidad puede tener atributos como "Edad Mínima" y "Edad Máxima" para definir los rangos de edad de cada grupo.

* Estado de la Cita: Una entidad para definir los posibles estados de una cita, como "Programada", "Confirmada", "En Progreso", "Completada", "Cancelada", etc.

---------------------------------------------------------------
Atributos:
----------------------------------------------------------------

> [!NOTE]
> La mayoría de los atributos mencionados anteriormente se pueden asignar a las entidades correspondientes en el diagrama E-R. Por ejemplo, la entidad "Cita" tendría atributos como Fecha, Hora, Duración, Motivo de la Cita, etc.
Relaciones:

> [!NOTE]
> Una cita está relacionada con un paciente. Esto se representa como una relación "Atendida por" entre las entidades "Cita" y "Paciente".

> [!NOTE]
> Una cita también está relacionada con un terapeuta, lo que se representa como una relación "Atendida por" entre las entidades "Cita" y "Terapeuta".

> [!NOTE]
> La entidad "Grupo de Edad" puede estar relacionada con la entidad "Paciente" para indicar el grupo de edad al que pertenece el paciente.

> [!NOTE]
> La entidad "Estado de la Cita" puede estar relacionada con la entidad "Cita" para indicar el estado de cada cita.

> [!NOTE]
> También puedes tener relaciones adicionales según sea necesario para representar la estructura de tu base de datos. Por ejemplo, si deseas rastrear los contactos de emergencia, podrías tener una relación entre la entidad "Paciente" y otra entidad llamada "Contacto de Emergencia".

> [!NOTE]
> Recuerda que en un diagrama E-R, las relaciones se representan mediante líneas que conectan las entidades y los rombos para indicar los atributos. Además, puedes especificar la cardinalidad de las relaciones (uno a uno, uno a muchos, muchos a muchos) según tus necesidades específicas.

> [!NOTE]
> Este es solo un ejemplo básico de cómo podrías estructurar un diagrama E-R para una agenda de atención psicológica. La estructura exacta dependerá de los detalles específicos de tu sistema y tus requisitos.

:shipit: :shipit: :shipit: :shipit: :shipit:
