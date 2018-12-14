---
title: Continuidad y estado del servicio
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Los administradores de Microsoft Office 365 pueden ver el estado de los servicios y saber cuándo se programa el mantenimiento. Información de estado de servicio está disponible en cualquier momento iniciando sesión en Office 365.
ms.openlocfilehash: 5744d0f0390aee046c63309c2395e2225c4d9342
ms.sourcegitcommit: ac81ba091876af9c42828faf9f5eb989a3a2cc58
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 12/13/2018
ms.locfileid: "27258742"
---
# <a name="service-health-and-continuity"></a>Continuidad y estado del servicio

Los administradores de Microsoft Office 365 pueden ver el estado de los servicios y saber cuándo se programa el mantenimiento. Información de estado de servicio está disponible en cualquier momento iniciando sesión en Office 365.
  
> [!NOTE]
> Si usa Office 365 operado por 21Vianet, parte de la información siguiente podría no aplicarse. Consulte más información sobre el [contrato de nivel de servicio de 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Ver el estado de los servicios

La sección de mantenimiento de servicio de Office 365 muestra el estado actual del servicio y obtener información detallada sobre las interrupciones y las interrupciones del servicio. Información de mantenimiento planeado está disponible en el centro de mensajes. Para obtener más información, consulte [Ver el estado de los servicios](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidentes de servicio

Un incidente de servicio es un evento que afecta a la entrega de un servicio. Incidentes de servicio pueden deberse a errores de hardware o software en el centro de datos de Microsoft, una conexión de red defectuoso entre el cliente y Microsoft o un desafío de centro de datos principales como incendios, "flood" del o catástrofe regional. La mayoría de los incidentes de servicio se pueden usar soluciones de tecnología y el proceso de Microsoft y se resuelven dentro de una hora corta. Sin embargo, algunos incidentes de servicio son más graves y pueden dar lugar a cortes de términos mayor.
  
Hay dos tipos de notificaciones sobre tiempos cuando servicios podrían no estar disponibles:
  
- **Planeado eventos de mantenimiento:** El mantenimiento planificado es actualizaciones regulares servicio iniciadas por Microsoft para las aplicaciones de software e infraestructura. Notificaciones de mantenimiento planeado informar a los clientes sobre el trabajo de servicio que puede afectar a la funcionalidad de un servicio de Office 365. Los clientes reciben una notificación a más tardar cinco días antes de todo el mantenimiento planeado mediante el centro de mensajes en el Portal de administración de Office 365. Microsoft normalmente planes de mantenimiento de horas al uso del servicio es históricamente mínima en función de zonas horarias regionales. 
    
- **Tiempo de inactividad no planificado:** Los incidentes de servicio no planificados ocurren cuando uno de los servicios en el conjunto de aplicaciones de Office 365 no está disponible o no responde. 
    
## <a name="notification-policy"></a>Directiva de notificación

Cuando se produce un incidente de servicio, Microsoft reconoce que son esenciales para los clientes communications oportunas, dirigidos y precisos. Microsoft notifica a los administradores de Office 365 actualizando el panel de estado de servicio específica de inquilinos (SHD) en el Portal de administración de Office 365. Actualizaciones de incidentes de servicio se proporcionan en una cadencia cada hora, o bien, si se requiere una cadencia diferente, se indicará en el registro de comunicación SHD. 
  
## <a name="service-health-communication-channels"></a>Canales de comunicación de estado del servicio

### <a name="office-365-admin-app"></a>Aplicación de administración de Office 365

El App Admin para los administradores de inquilinos de Office 365 proporciona capacidad para conectar con el estado de servicio de Office 365 de su organización sobre la marcha. Los administradores de Office 365 inquilino tendrán la capacidad de ver servicio mantenimiento información y mantenimiento de actualizaciones de estado de sus dispositivos móviles. Para obtener más información, visite las [Preguntas más frecuentes sobre aplicaciones de administración](https://docs.microsoft.com/en-us/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Módulo de administración de Office 365 para Microsoft System Center 2012 R2

Microsoft System Center es una plataforma de administración integrada que ayuda a administrar híbrida, los dispositivos de cliente y centro de datos en la nube entornos de TI. Los administradores de Office 365 que usar System Center ahora tienen la opción para importar el módulo de administración de Office 365, que les permite ver todas las comunicaciones de servicio dentro de Operations Manager en System Center. Uso de esta herramienta le proporciona acceso al estado de los servicios suscritos, los incidentes de servicio activos y resueltos y sus comunicaciones de centro de mensajes. Para obtener más información, visite la entrada de blog de [Herramientas de administración del nuevo Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/) . 
  
### <a name="office-365-service-communications-api"></a>API de comunicaciones de servicio de Office 365

La API de comunicaciones de servicio de Office 365 le permite tener acceso a las comunicaciones de servicio de Office 365 como desee. Con esta nueva herramienta de administración, ahora tiene la capacidad de crear o conectar las herramientas con las comunicaciones de servicio de Office 365, lo que potencialmente simplifica la forma de supervisar el entorno. La API de comunicaciones de servicio permite supervisar lo siguiente en su entorno:
  
- Estado del servicio en tiempo real
    
- Comunicaciones del Centro de mensajes
    
- Notificaciones de mantenimiento planeado
    
Para obtener más información, visite la entrada de blog sobre [nuevas herramientas de administración de Office 365](https://blogs.office.com/2014/07/29/new-office-365-admin-tools/). 
  
## <a name="post-incident-reviews"></a>Revisiones posteriores al incidente

El compromiso de Microsoft para una mejora continua conlleva el análisis de las incidencias de servicio no planificadas que afectan al cliente a fin de minimizar la recurrencia en el futuro. 
  
Incidentes de servicio no planeada se definen como las interrupciones del servicio de varios inquilinos que afectar al uso del servicio tal como se define por nuestros SLA de servicio y se han declarado como tal en el panel de estado de servicio.
  
 Para no planeada afecta al cliente incidentes de servicio en el que se ha producido una amplia y notable impacto a través de un gran número de las organizaciones, una revisión de incidente posteriores a la preliminar (PIR) se entregarán a través de su panel de estado de servicio dentro de 48 horas de incidente resolución, seguida de un PIR final dentro de cinco días laborables. El informe detallado de PIR incluye: 
  
- Impacto en el cliente y experiencia del usuario
    
- Fecha y hora de inicio y fin del incidente
    
- Escala de tiempo detallada de las medidas de impacto y resolución
    
- Análisis de causas originarias y acciones emprendidas para la mejora continua
    
Para todos los incidentes de servicio, el panel de estado de servicio proporciona un resumen de cierre de la incidencia incluido un resumen final del evento, causa raíz preliminar, inicio y finalización e información que incluye los pasos siguientes. Para esta categoría de incidentes de servicio, no se generará un PIR. 
  
## <a name="service-continuity"></a>Continuidad del servicio

Microsoft Office 365 entrega las ofertas mediante sistemas muy resistentes que ayudan a mantener el máximo rendimiento del servicio. Las provisiones de continuidad del servicio forman parte del diseño del sistema de Office 365. Estas provisiones permiten que Office 365 se recupere rápidamente de los eventos inesperados como errores de hardware o en aplicaciones, daños en los datos u otros incidentes que afecten a los usuarios. Las soluciones de continuidad del servicio también se aplican durante las interrupciones catastróficas (por ejemplo, desastres naturales o un incidente en un centro de datos de Microsoft que lo deja completamente inoperativo).
  
Tenga en cuenta que, después de la recuperación de interrupciones graves, puede que transcurra cierto tiempo hasta que se restaure la redundancia completa del centro de datos para el servicio. Por ejemplo, si se produce un error en el centro de datos 1, los recursos restauran los servicios en el centro de datos 2. Pero puede que transcurra cierto tiempo hasta que los servicios del centro de datos 2 recuperen la continuidad del servicio en los recursos restaurados del centro de datos 1 o en los nuevos recursos del centro de datos 3. Durante este tiempo, se aplica el [Contrato de nivel de servicio](https://technet.microsoft.com/en-us/library/office-365-service-level-agreement.aspx) de Office 365. Office 365 operado por 21Vianet tiene un contrato de nivel de servicio diferente. Vea el [sitio de 21Vianet](http://www.21vbluecloud.com/office365/O365-SLA/) para obtener más información. 
  
## <a name="ensuring-data-availability"></a>Garantizar la disponibilidad de los datos

Microsoft garantiza que los datos del cliente estén siempre disponibles cuando sea necesario, a través de las siguientes características:
  
- **Redundancia y almacenamiento de datos:** Los datos de los clientes se almacenan en un entorno redundante con sólidas capacidades de protección de datos para permitir la disponibilidad, la continuidad del negocio y una rápida recuperación. Se implementan varios niveles de redundancia de datos, desde discos redundantes para la protección frente a errores de disco locales hasta una replicación de datos continua y completa en un centro de datos disperso geográficamente. 
    
- **Supervisión de datos:** Los servicios de Office 365 mantienen altos niveles de rendimiento mediante: 
    
  - **Supervisión de las bases de datos:**
    
  - Procesos bloqueados
    
  - Pérdida de paquetes
    
  - Procesos en cola
    
  - Latencia de consulta
    
- **Realización de mantenimientos preventivos:** El mantenimiento preventivo incluye las comprobaciones de coherencia de bases de datos, la compresión periódica de los datos y las revisiones de registros de errores. 
    
## <a name="support"></a>Soporte técnico

Los equipos de operaciones y desarrollo de Office 365 se complementan con una estructura de soporte dedicado de Office 365, que juega un papel importe en el suministro de continuidad del negocio a los clientes. El personal de soporte posee un amplio conocimiento del servicio y de las aplicaciones asociadas, así como la posibilidad de consultar directamente a expertos en arquitectura, desarrollo y pruebas de Microsoft.
  
La estructura de soporte se alinea estrechamente con las operaciones y el desarrollo de productos, ofrece rápidos tiempos de solución de problemas y un canal para escuchar las opiniones de los clientes. Los comentarios de los clientes aportan información para la planificación, el desarrollo y los procesos operativos.
  
- **Seguimiento de incidentes en línea:** Los clientes necesitan saber que se está trabajando en sus incidentes y deben poder realizar un seguimiento de la solución de manera oportuna. El Portal de Office 365 ofrece una interfaz sencilla basada en web para el soporte. Los clientes pueden usar el portal para agregar o supervisar solicitudes de servicio y recibir comentarios de los equipos de soporte de Microsoft. 
    
- **Autoayuda, con la asistencia continua del equipo de soporte:** Office 365 ofrece una amplia gama de recursos y herramientas de autoayuda que permiten a los clientes solucionar incidentes relacionados con el servicio sin necesidad del soporte de Microsoft. 
    
Antes de que los clientes notifiquen las solicitudes de servicio, pueden consultar los artículos de Knowledge Base y las Preguntas más frecuentes que ofrecen ayuda inmediata a los problemas más comunes. Estos recursos se actualizan de manera continua con la información más reciente, lo que permite evitar retrasos mediante la aportación de soluciones a los problemas conocidos. No obstante, cuando surge un incidente que precisa la ayuda de un profesional de soporte; los miembros del equipo están disponibles para ofrecer asistencia inmediata por teléfono o a través del portal de administración las 24 horas al día, 7 días a la semana.
  
Para obtener más información, vea el tema [Soporte técnico](https://technet.microsoft.com/en-us/library/office-365-support.aspx). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, consulte [Descripción del servicio de la plataforma de Office 365](https://technet.microsoft.com/en-us/library/office-365-platform-service-description.aspx).
  

