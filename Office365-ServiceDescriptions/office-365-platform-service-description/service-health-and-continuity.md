---
title: Continuidad y estado del servicio
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-service-health
ms.service: o365-administration
ms.localizationpriority: medium
ms.custom: Adm_ServiceDesc
ms.assetid: 0483499d-8972-4a8f-97bd-b82f5b138991
description: Los administradores de Microsoft pueden ver el estado de los servicios y averiguar cuándo se programa el mantenimiento. La información de estado del servicio está disponible en cualquier momento iniciando sesión.
ms.openlocfilehash: 497568f54fc5a761278902eb26e92bc52789c9b5
ms.sourcegitcommit: c117bb958f5b94682fd384b4770a920c6114559b
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/24/2021
ms.locfileid: "59672971"
---
# <a name="service-health-and-continuity"></a>Continuidad y estado del servicio

Los administradores de Microsoft pueden ver el estado de los servicios y averiguar cuándo se programa el mantenimiento. La información de estado del servicio está disponible en cualquier momento iniciando sesión.
  
> [!NOTE]
> Si usa Office 365 operado por 21Vianet, parte de la información siguiente podría no aplicarse. Consulte más información sobre el [contrato de nivel de servicio de 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="view-status-of-services"></a>Ver el estado de los servicios

La sección Estado del servicio muestra el estado actual del servicio y detalles sobre las interrupciones y las interrupciones del servicio. La información de mantenimiento planeado está disponible en el Centro de mensajes. Para obtener más información, consulte [Ver el estado de los servicios](/office365/enterprise/view-service-health). 
  
## <a name="service-incidents"></a>Incidencias de servicio

Una incidencia de servicio es un evento que afecta al suministro de un servicio. Los incidentes de servicio pueden deberse a errores de hardware o software en el centro de datos de Microsoft, una conexión de red defectuosa entre el cliente y Microsoft o un desafío importante del centro de datos como el incendio, la inundación o la catástrofe regional. La mayoría de los incidentes de servicio se pueden resolver con la tecnología de Microsoft y las soluciones de procesos se solucionan en un período breve de tiempo. No obstante, algunos incidentes de servicio son más serios y pueden derivar en interrupciones de larga duración.
  
Hay dos tipos de notificaciones sobre las horas en las que es posible que los servicios no estén disponibles:
  
- **Eventos de mantenimiento planeados:** El mantenimiento planeado es actualizaciones regulares de servicio iniciadas por Microsoft en las aplicaciones de infraestructura y software. Las notificaciones de mantenimiento planeadas informan a los clientes sobre el trabajo de servicio que puede afectar a la funcionalidad de un servicio de Microsoft. Se notificará a los clientes con un mínimo de cinco días de antelación a todo el mantenimiento planeado a través del Centro de mensajes en el Centro de administración de Microsoft 365. Microsoft normalmente planea el mantenimiento para los momentos en los que el uso del servicio está históricamente en su nivel más bajo en función de las zonas horarias regionales. 

- **Tiempo de inactividad no planeado:** Los incidentes de servicio no planeados se producen cuando uno de los servicios no está disponible o no responde. 

### <a name="recent-worldwide-uptimes"></a>Tiempos de actividad recientes en todo el mundo

Mover a un servicio en la nube no debe significar perder la capacidad de saber lo que está sucediendo. Con Office 365, no lo hace. Nuestro objetivo es ser transparentes en nuestras operaciones para que pueda supervisar el estado del servicio, realizar un seguimiento de los problemas y tener una vista histórica de la disponibilidad. En las tablas siguientes se muestran los datos de tiempo de actividad recientes en todo el mundo.

**2021**

| P1 | P2 | P3 | P4 |
|:-----|:-----|:-----|:-----|
| 99.97%  | 99.98% | | |

<br>

**2020**

| P1 | P2 | P3 | P4 |
|:-----|:-----|:-----|:-----|
| 99.98% | 99,99% | 99.97% | 99.97% |

<br>

**2019**

| P1 | P2 | P3 | P4 |
|:-----|:-----|:-----|:-----|
| 99.97% | 99.97% | 99.98% | 99.98% |

<br>

**2018**

| P1 | P2 | P3 | P4 |
|:-----|:-----|:-----|:-----|
| 99,99% | 99.98% | 99.97% | 99.98% |

<br>

**2017**

| P1 | P2 | P3 | P4 |
|:-----|:-----|:-----|:-----|
| 99,99% | 99.97% | 99.98% | 99,99% |

## <a name="notification-policy"></a>Directiva de notificación

Cuando ocurre un incidente de servicio, Microsoft es consciente de que una comunicación precisa, destinada a las personas indicadas y a tiempo resulta fundamental para los clientes. Microsoft notifica a los administradores actualizando el Panel de mantenimiento de servicio (SHD) específico del espacio empresarial en el Centro de administración de Microsoft 365. Las actualizaciones de incidentes de servicio se proporcionan en una cadencia cada hora o, si se requiere una cadencia diferente, se indica en la publicación de comunicación shd. 
  
## <a name="service-health-communication-channels"></a>Canales de comunicación de estado del servicio

### <a name="admin-app"></a>Aplicación de administrador

La aplicación de administración para administradores de la organización te ofrece la posibilidad de conectarte con el estado de servicio de Microsoft de tu organización sobre la marcha. Los administradores de Microsoft tendrán la capacidad de ver la información de mantenimiento del servicio y las actualizaciones de estado de mantenimiento desde sus dispositivos móviles. Para obtener más información, visite la [Preguntas más frecuentes (FAQ) de la aplicación de administración](/office365/admin/admin-overview/admin-mobile-app).
  
### <a name="office-365-management-pack-for-microsoft-system-center-2012-r2"></a>Módulo de administración de Office 365 para Microsoft System Center 2012 R2

Microsoft System Center es una plataforma de administración integrada que le ayuda a administrar el centro de datos, los dispositivos de cliente y los entornos híbridos de TI en la nube. Los administradores de Microsoft que usan System Center ahora tienen la opción de importar el módulo de administración de Office 365, que les permite ver todas las comunicaciones de servicio dentro de Operations Manager en System Center. Esta herramienta proporciona acceso al estado de los servicios suscritos, incidentes de servicio activos y resueltos, y las comunicaciones del Centro de mensajes. Para obtener más información, obtenga [Microsoft System Center Management Pack para Office 365](https://www.microsoft.com/download/details.aspx?id=43708) en el Centro de descarga de Microsoft. 
  
### <a name="office-365-service-communications-api"></a>API de comunicaciones de servicio de Office 365

La OFFICE 365 de comunicaciones de servicio le permite acceder a las comunicaciones de servicio de la forma que desee. Con esta API, tiene la capacidad de crear o conectar las herramientas a las comunicaciones de servicio, lo que puede simplificar la forma en que supervisa el entorno. La API de comunicaciones de servicio le permite supervisar los siguientes elementos del entorno:
  
- Estado del servicio en tiempo real

- Comunicaciones del Centro de mensajes

Para obtener más información, vea la referencia Office 365 [API de comunicaciones de servicio .](/office/office-365-management-api/office-365-service-communications-api-reference) 
  
## <a name="post-incident-reviews"></a>Revisiones posteriores a la incidencia

El compromiso de Microsoft para una mejora continua conlleva el análisis de las incidencias de servicio no planificadas que afectan al cliente a fin de minimizar la recurrencia en el futuro. 
  
Los incidentes de servicio no planeados se definen como interrupciones del servicio multiinquilino que afectan al uso del servicio según lo definido por nuestros contratos de nivel de servicio (SLA) y se han declarado como tales en el Panel de mantenimiento del servicio.
  
 En el caso de incidentes de servicio no planeados que afectan al cliente en los que hubo un impacto amplio y notable en un gran número de organizaciones, se entregará una revisión preliminar posterior a los incidentes (PIR) a través del Panel de mantenimiento del servicio en un plazo de 48 horas después de la resolución de incidentes, seguida de una PIR final en un plazo de cinco días laborables. El informe pir detallado incluye: 
  
- Impacto en el cliente y experiencia del usuario

- Fecha y hora de inicio y fin del incidente

- Escala de tiempo detallada de medidas de impacto y resolución

- Análisis de causas originarias y acciones emprendidas para la mejora continua

Para el resto de incidentes de servicio, el Panel de mantenimiento del servicio proporcionará un resumen de cierre de incidentes, que incluye un resumen final del evento, la causa raíz preliminar, las horas de inicio y finalización, y la información que detalla los pasos siguientes. Para esta categoría de incidente del servicio, no se generará un PIR. 
  
## <a name="service-continuity"></a>Service continuity

Las ofertas de Microsoft se entregan mediante sistemas altamente resistentes que ayudan a mantener un rendimiento máximo del servicio. Las disposiciones de continuidad del servicio forman parte del diseño del sistema. Estas disposiciones permiten a Microsoft recuperarse rápidamente de eventos inesperados, como errores de hardware o aplicaciones, daños en los datos u otros incidentes que afectan a los usuarios. Las soluciones de continuidad del servicio también se aplican durante las interrupciones catastróficas (por ejemplo, desastres naturales o un incidente en un centro de datos de Microsoft que lo deja completamente inoperativo).
  
Tenga en cuenta que, después de la recuperación de interrupciones graves, puede que transcurra cierto tiempo hasta que se restaure la redundancia completa del centro de datos para el servicio. Por ejemplo, si se produce un error en el centro de datos 1, los recursos restauran los servicios en el centro de datos 2. Pero puede que transcurra cierto tiempo hasta que los servicios del centro de datos 2 recuperen la continuidad del servicio en los recursos restaurados del centro de datos 1 o en los nuevos recursos del centro de datos 3. El Contrato [de nivel de servicio](service-level-agreement.md) (SLA) de Microsoft se aplica durante este tiempo. Office 365 operado por 21Vianet tiene un contrato de nivel de servicio diferente. Para obtener más información, vea el [sitio de 21Vianet](https://www.21vbluecloud.com/office365/O365-SLA/). 
  
## <a name="ensuring-data-availability"></a>Garantizar la disponibilidad de los datos

Microsoft garantiza que los datos del cliente estén siempre disponibles cuando sea necesario, a través de las siguientes características:
  
- **Redundancia y almacenamiento de datos:** Los datos de los clientes se almacenan en un entorno redundante con sólidas capacidades de protección de datos para permitir la disponibilidad, la continuidad del negocio y una rápida recuperación. Se implementan varios niveles de redundancia de datos, desde discos redundantes para la protección frente a errores de disco locales hasta una replicación de datos continua y completa en un centro de datos disperso geográficamente. 

- **Supervisión de datos: servicios Microsoft** altos niveles de rendimiento mediante la supervisión: 

  - Databases

  - Procesos bloqueados

  - Pérdida de paquetes

  - Procesos en cola

  - Latencia de consulta

- **Realización de mantenimientos preventivos:** El mantenimiento preventivo incluye las comprobaciones de coherencia de bases de datos, la compresión periódica de los datos y las revisiones de registros de errores. 

## <a name="support"></a>Soporte técnico

Los equipos de desarrollo y operaciones de Microsoft se complementan con una organización de soporte técnico dedicada, que desempeña un papel importante en proporcionar a los clientes continuidad empresarial. El personal de soporte posee un amplio conocimiento del servicio y de las aplicaciones asociadas, así como la posibilidad de consultar directamente a expertos en arquitectura, desarrollo y pruebas de Microsoft.
  
La estructura de soporte se alinea estrechamente con las operaciones y desarrollo de productos, ofrece rápidos tiempos de solución de problemas y un canal para escuchar las opiniones de los clientes. Los comentarios de los clientes aportan información para la planificación, el desarrollo y los procesos operativos.
  
- **Seguimiento de incidentes en línea:** Los clientes necesitan saber que se está trabajando en sus incidentes y deben poder realizar un seguimiento de la solución de manera oportuna. El Centro de administración de Microsoft 365 proporciona una única interfaz basada en web para la compatibilidad. Los clientes pueden usar el portal para agregar o supervisar solicitudes de servicio y recibir comentarios de los equipos de soporte de Microsoft. 

- **Auto-ayuda, con el apoyo continuo del personal:** Microsoft ofrece una amplia variedad de recursos y herramientas de auto help que pueden ayudar a los clientes a resolver problemas relacionados con el servicio sin necesidad de soporte técnico de Microsoft. 

Antes de que los clientes notifiquen las solicitudes de servicio, pueden consultar los artículos de Knowledge Base y las Preguntas más frecuentes que ofrecen ayuda inmediata a los problemas más comunes. Estos recursos se actualizan de manera continua con la información más reciente, lo que permite evitar retrasos mediante la aportación de soluciones a los problemas conocidos. No obstante, cuando surge una incidencia que precisa la ayuda de un profesional de soporte; los miembros del equipo están disponibles para ofrecer asistencia inmediata por teléfono o a través del portal de administración las 24 horas al día, 7 días a la semana.
  
Para obtener más información acerca de la compatibilidad, consulte el [artículo soporte](support.md) técnico. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características en todos los planes, vea [Microsoft 365 y Office 365 descripción del servicio de la plataforma](office-365-platform-service-description.md).
