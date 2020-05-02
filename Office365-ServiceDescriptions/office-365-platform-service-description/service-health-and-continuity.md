---
title: Service health and continuity
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Los administradores de Microsoft pueden ver el estado de los servicios y saber cuándo está programado el mantenimiento. La información de estado del servicio está disponible en cualquier momento iniciando sesión.
ms.openlocfilehash: eb2368030148423301d21d7644561028b1fbcec2
ms.sourcegitcommit: f1322138cca22e4e1c640a31117f3b7999732b7a
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/01/2020
ms.locfileid: "44001956"
---
# <a name="service-health-and-continuity"></a>Service health and continuity

Los administradores de Microsoft pueden ver el estado de los servicios y saber cuándo está programado el mantenimiento. La información de estado del servicio está disponible en cualquier momento iniciando sesión.
  
> [!NOTE]
> Si usa Office 365 operado por 21Vianet, parte de la información siguiente podría no aplicarse. Consulte más información sobre el [contrato de nivel de servicio de 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Ver el estado de los servicios

La sección estado del servicio muestra el estado actual del servicio y los detalles sobre las interrupciones del servicio y las interrupciones. La información de mantenimiento planeado está disponible en el centro de mensajes. Para obtener más información, consulte [Ver el estado de los servicios](https://docs.microsoft.com/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidencias de servicio

Una incidencia de servicio es un evento que afecta al suministro de un servicio. Los incidentes de servicio pueden deberse a un error de hardware o software en el centro de datos de Microsoft, una conexión de red defectuosa entre el cliente y Microsoft, o un desafío importante del centro de datos, como incendios, inundaciones o catástrofes regionales. La mayoría de los incidentes de servicio se pueden resolver con la tecnología de Microsoft y las soluciones de procesos se solucionan en un período breve de tiempo. No obstante, algunos incidentes de servicio son más serios y pueden derivar en interrupciones de larga duración.
  
Hay dos tipos de notificaciones sobre las horas en las que los servicios pueden no estar disponibles:
  
- **Eventos de mantenimiento planeados:** El mantenimiento planeado es la actualización periódica del servicio Iniciado por Microsoft para las aplicaciones de infraestructura y software. Las notificaciones de mantenimiento planificadas informan a los clientes sobre el trabajo del servicio que puede afectar a la funcionalidad de un servicio de Microsoft. A los clientes se les notifica en un plazo de cinco días antes de todo el mantenimiento planeado a través del centro de mensajes en el centro de administración de Microsoft 365. Microsoft suele planear el mantenimiento de las horas en las que el uso del servicio se encuentra siempre a su nivel más bajo en función de las zonas horarias regionales. 
    
- **Tiempo de inactividad imprevisto:** Las incidencias de servicio no planificadas se producen cuando uno de los servicios no está disponible o no responde. 

### <a name="recent-worldwide-uptimes"></a>Recientes plazos de actividad en todo el mundo

El cambio a un servicio en la nube no debería significar la pérdida de la capacidad de saber lo que está ocurriendo. Con Office 365, no es así. Nuestro objetivo es ser transparente en nuestras operaciones para que pueda supervisar el estado de su servicio, realizar un seguimiento de los problemas y tener una vista histórica de la disponibilidad. En las siguientes tablas se muestran los datos recientes de actividad en todo el mundo.

<br/>

|**2020** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Trim** <br/> |**Q3** <br/> |**Tercer** <br/> |
| 99,98% <br/> | <br/> | <br/> |<br/> |

<br/>

|**2019** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Trim** <br/> |**Q3** <br/> |**Tercer** <br/> |
| 99,97% <br/> | 99,97% <br/> | 99,98% <br/> | 99,98% <br/> |

<br/>

|**2018** <br/>||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Trim** <br/> |**Q3** <br/> |**Tercer** <br/> |
| 99,99% <br/> | 99,98% <br/> | 99,97% <br/> | 99,98% <br/> |

<br/>

|**2017** <br/> ||||
|:-----|:-----|:-----|:-----|
| **Q1** <br/> | **Trim** <br/> |**Q3** <br/> |**Tercer** <br/> |
| 99,99% <br/> | 99,97% <br/> | 99,98% <br/> | 99,99% <br/> |

<br/>

## <a name="notification-policy"></a>Directiva de notificación

Cuando ocurre un incidente de servicio, Microsoft es consciente de que una comunicación precisa, destinada a las personas indicadas y a tiempo resulta fundamental para los clientes. Microsoft notifica a los administradores mediante la actualización del panel de estado del servicio específico del inquilino (publicación) en el centro de administración de Microsoft 365. Las actualizaciones de incidentes de servicio se proporcionan en una cadencia por horas o, si se requiere una cadencia distinta, se indicará en el registro de comunicación de publicación. 
  
## <a name="service-health-communication-channels"></a>Canales de comunicación de estado del servicio

### <a name="admin-app"></a>Aplicación de administración

La aplicación de administración para administradores de la organización le ofrece la posibilidad de conectarse al estado del servicio Microsoft de su organización en cualquier caso. Los administradores de Microsoft tendrán la posibilidad de ver la información de estado del servicio y las actualizaciones del estado del mantenimiento desde sus dispositivos móviles. Para obtener más información, visite la [Preguntas más frecuentes (FAQ) de la aplicación de administración](https://docs.microsoft.com/office365/admin/admin-overview/admin-mobile-app?view=o365-worldwide).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Módulo de administración de Office 365 para Microsoft System Center 2012 R2

Microsoft System Center es una plataforma de administración integrada que le ayuda a administrar el centro de datos, los dispositivos de cliente y los entornos híbridos de TI en la nube. Los administradores de Microsoft que usan System Center ahora tienen la opción de importar el módulo de administración de Office 365, que les permite ver todas las comunicaciones de servicio dentro de Operations Manager en System Center. Esta herramienta proporciona acceso al estado de los servicios suscritos, incidentes de servicio activos y resueltos, y las comunicaciones del Centro de mensajes. Para obtener más información, obtenga el [módulo de administración de Microsoft System Center para Office 365](https://www.microsoft.com/download/details.aspx?id=43708) en el centro de descarga de Microsoft. 
  
### <a name="office-365-service-communications-api"></a>API de comunicaciones de servicio de Office 365

La API de comunicaciones de servicio de Office 365 le permite tener acceso a las comunicaciones de servicio de la forma que desee. Con esta API, tiene la posibilidad de crear o conectar sus herramientas a las comunicaciones de servicio, lo que puede simplificar la forma en que supervisa el entorno. La API de comunicaciones de servicio le permite supervisar lo siguiente en su entorno:
  
- Estado del servicio en tiempo real
    
- Comunicaciones del Centro de mensajes
    
Para obtener más información, consulte la referencia de la [API de comunicaciones de servicio de Office 365](https://docs.microsoft.com/office/office-365-management-api/office-365-service-communications-api-reference). 
  
## <a name="post-incident-reviews"></a>Revisiones posteriores a la incidencia

El compromiso de Microsoft para una mejora continua conlleva el análisis de las incidencias de servicio no planificadas que afectan al cliente a fin de minimizar la recurrencia en el futuro. 
  
Las incidencias de servicio no planificadas se definen como interrupciones en el servicio multiinquilino que afectan al uso del servicio según los SLAs de los servicios y que se han declarado como tales en el panel de estado del servicio.
  
 Para los incidentes de servicio no planificados que influyen en el cliente en las que había un impacto amplio y perceptible en un gran número de organizaciones, se proporcionará una revisión preliminar posterior al incidente (PIR) a través de su panel de estado del servicio en 48 horas de resolución del incidente, seguida de una PIR final en cinco días hábiles. El informe detallado de PIR incluye: 
  
- Impacto en el cliente y experiencia del usuario
    
- Fecha y hora de inicio y fin del incidente
    
- Escala de tiempo detallada de las medidas de impacto y resolución
    
- Análisis de causas originarias y acciones emprendidas para la mejora continua
    
Para todos los demás incidentes de servicio, el panel de estado del servicio proporcionará un resumen del cierre del incidente, que incluye un resumen final del evento, la causa raíz preliminar, las horas de inicio y finalización y la información detallada de los pasos siguientes. Para esta categoría de incidente del servicio, no se generará un PIR. 
  
## <a name="service-continuity"></a>Continuidad del servicio

Las ofertas de Microsoft son ofrecidas por sistemas altamente resistentes que ayudan a mantener el máximo rendimiento del servicio. Las provisiones de continuidad del servicio forman parte del diseño del sistema. Estas disposiciones permiten que Microsoft se recupere rápidamente de eventos inesperados, como errores de hardware o de aplicaciones, daños en los datos u otros incidentes que afectan a los usuarios. Las soluciones de continuidad del servicio también se aplican durante las interrupciones catastróficas (por ejemplo, desastres naturales o un incidente en un centro de datos de Microsoft que lo deja completamente inoperativo).
  
Tenga en cuenta que, después de la recuperación de interrupciones graves, puede que transcurra cierto tiempo hasta que se restaure la redundancia completa del centro de datos para el servicio. Por ejemplo, si se produce un error en el centro de datos 1, los recursos restauran los servicios en el centro de datos 2. Pero puede que transcurra cierto tiempo hasta que los servicios del centro de datos 2 recuperen la continuidad del servicio en los recursos restaurados del centro de datos 1 o en los nuevos recursos del centro de datos 3. El [contrato de nivel de servicio](service-level-agreement.md) de Microsoft (SLA) se aplica durante este tiempo. Office 365 operado por 21Vianet tiene un contrato de nivel de servicio diferente. Vea el [sitio de 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/) para obtener más información. 
  
## <a name="ensuring-data-availability"></a>Garantizar la disponibilidad de los datos

Microsoft garantiza que los datos del cliente estén siempre disponibles cuando sea necesario, a través de las siguientes características:
  
- **Redundancia y almacenamiento de datos:** Los datos de los clientes se almacenan en un entorno redundante con sólidas capacidades de protección de datos para permitir la disponibilidad, la continuidad del negocio y una rápida recuperación. Se implementan varios niveles de redundancia de datos, desde discos redundantes para la protección frente a errores de disco locales hasta una replicación de datos continua y completa en un centro de datos disperso geográficamente. 
    
- **Supervisión de datos:** Los servicios de Microsoft mantienen altos niveles de rendimiento al: 
    
  - **Supervisión de las bases de datos:**
    
  - Procesos bloqueados
    
  - Pérdida de paquetes
    
  - Procesos en cola
    
  - Latencia de consulta
    
- **Realización de mantenimientos preventivos:** El mantenimiento preventivo incluye las comprobaciones de coherencia de bases de datos, la compresión periódica de los datos y las revisiones de registros de errores. 
    
## <a name="support"></a>Soporte técnico

Los equipos de operaciones y desarrollo de Microsoft se complementan con una organización de soporte dedicado, que desempeña un papel importante en proporcionar la continuidad del negocio a los clientes. El personal de soporte posee un amplio conocimiento del servicio y de las aplicaciones asociadas, así como la posibilidad de consultar directamente a expertos en arquitectura, desarrollo y pruebas de Microsoft.
  
La estructura de soporte se alinea estrechamente con las operaciones y desarrollo de productos, ofrece rápidos tiempos de solución de problemas y un canal para escuchar las opiniones de los clientes. Los comentarios de los clientes aportan información para la planificación, el desarrollo y los procesos operativos.
  
- **Seguimiento de incidentes en línea:** Los clientes necesitan saber que se está trabajando en sus incidentes y deben poder realizar un seguimiento de la solución de manera oportuna. El centro de padmin de Microsoft 365 Ortal proporciona una única interfaz basada en web para el soporte técnico. Los clientes pueden usar el portal para agregar o supervisar solicitudes de servicio y recibir comentarios de los equipos de soporte de Microsoft. 
    
- **Autoayuda, respaldado por el soporte de personal continuo:** Microsoft ofrece una amplia gama de recursos y herramientas de autoayuda que pueden ayudar a los clientes a resolver problemas relacionados con el servicio sin necesidad del soporte técnico de Microsoft. 
    
Antes de que los clientes notifiquen las solicitudes de servicio, pueden consultar los artículos de Knowledge Base y las Preguntas más frecuentes que ofrecen ayuda inmediata a los problemas más comunes. Estos recursos se actualizan de manera continua con la información más reciente, lo que permite evitar retrasos mediante la aportación de soluciones a los problemas conocidos. No obstante, cuando surge un incidente que precisa la ayuda de un profesional de soporte; los miembros del equipo están disponibles para ofrecer asistencia inmediata por teléfono o a través del portal de administración las 24 horas al día, 7 días a la semana.
  
Para obtener más información, vea el tema [Soporte técnico](support.md). 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, consulte la descripción del servicio de la [plataforma 365 de Office](office-365-platform-service-description.md).
  