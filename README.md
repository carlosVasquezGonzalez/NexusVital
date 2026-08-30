# NexusVital
Diseño de arquitectura de microservicios para NexusVital, plataforma de gestión de documentos médicos entre hospitales

## Sobre el proyecto

NexusVital es una plataforma de gestión de documentos médicos entre hospitales que permite a pacientes revisar sus exámenes e historial clínico, y a los médicos acceder al historial de los pacientes que atienden. La arquitectura se dividió en 5 microservicios con responsabilidad única (Gestión de Usuarios, Autenticación y Consentimiento, Historial Clínico, Documentos y Exámenes, y Búsqueda de Pacientes), cada uno con su propia base de datos, comunicados mediante REST a través de un API Gateway, priorizando la seguridad, escalabilidad y disponibilidad del sistema.

*Imagen del Draw.io*
<img width="1221" height="721" alt="image" src="https://github.com/user-attachments/assets/b58671aa-40f9-45da-9511-be198079d823" />
