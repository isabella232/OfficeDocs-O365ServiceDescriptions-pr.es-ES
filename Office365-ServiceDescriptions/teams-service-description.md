---
title: Descripción del servicio Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Microsoft Teams proporciona mensajería instantánea, colaboración de archivos y datos, llamadas de audio y vídeo, reuniones en línea enriquecciones, experiencias móviles y amplias capacidades de conferencia web.
ms.openlocfilehash: ba8642a3b1260767fe4884a68d79aac5a511f4c4
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51174045"
---
# <a name="microsoft-teams-service-description"></a>Descripción del servicio Microsoft Teams

Microsoft Teams es el centro del trabajo en equipo en Microsoft 365. El servicio de Teams permite la mensajería instantánea, las llamadas de audio y vídeo, las reuniones en línea enriquecciones, las experiencias móviles y las amplias capacidades de conferencia web. Además, Teams proporciona características de extensibilidad y colaboración de archivos y datos, e integra con Microsoft 365 y otras aplicaciones de Microsoft y asociados.

Skype Empresarial Online se retirará el 31 de julio de [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) 2021, que se anunció el 30 de julio de 2019. Microsoft Teams es un servicio totalmente nuevo, creado para la nube desde cero al aprovechar Azure y otras innovaciones de servicio de Microsoft. Microsoft Teams se basa en grupos de Microsoft 365, Microsoft Graph y con la misma seguridad, cumplimiento y facilidad de administración a nivel empresarial que el resto de Office 365. Teams aprovecha las identidades almacenadas en Azure Active Directory (Azure AD). Estos servicios se entregan desde centros de datos de Microsoft y son accesibles para los usuarios en una amplia variedad de dispositivos desde dentro de una red corporativa o a través de Internet. Para obtener más información, vea los pósteres de soluciones de telefonía y arquitectura de TI de [Microsoft Teams.](/microsoftteams/teams-architecture-solutions-posters)

Microsoft sigue comprometido con la seguridad de sus datos y la [accesibilidad](https://www.microsoft.com/trust-center/compliance/accessibility) de nuestros servicios. Para obtener más información, vea [El Centro de confianza de Microsoft](https://www.microsoft.com/trust-center) y el Centro de [accesibilidad de Office](https://support.office.com/article/Office-Accessibility-Center-Resources-for-people-with-disabilities-ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).

Para obtener información detallada del plan sobre las suscripciones que permiten a los usuarios de Microsoft Teams, consulte la tabla de comparación [de suscripciones completa.](https://go.microsoft.com/fwlink/?linkid=2139145) Para obtener información adicional sobre Office 365 en planes de gobierno, vea [Office 365 Government plans](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans). Office 365 G1 a G5 incluye acceso a las características de Teams.

Para obtener instrucciones detalladas de implementación de características de [producto,](/MicrosoftTeams)consulte la documentación de administración de Microsoft Teams . Esta descripción del servicio detalla las diferencias clave entre los servicios proporcionados en las distintas instalaciones en la nube. Las funcionalidades principales de Microsoft Teams no difieren entre las suscripciones. La disponibilidad de las capacidades de cumplimiento depende del nivel de suscripción. Para obtener más información, vea [Seguridad y cumplimiento en Microsoft Teams](/microsoftteams/security-compliance-overview). Para obtener una lista detallada de las características disponibles en cada suscripción, vea [Microsoft 365 and Office 365 platform service description](./office-365-platform-service-description/office-365-platform-service-description.md).

**Características de voz en** la nube: para las audioconferencias, la organización debe comprar y asignar una licencia de audioconferencia a cada usuario que configurará reuniones de acceso telefónico local. Para las características de Teams que requieren planes de llamadas, cada usuario necesita un sistema telefónico y un plan de llamadas nacionales o nacionales e internacionales. Para obtener más información, vea [Licencias de complementos de Microsoft Teams](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

**Eventos en directo:** esta oferta en Office 365 reemplaza a la difusión de reunión de Skype retirada. Las funcionalidades de eventos en directo están disponibles para los planes de licencias, tal como se detalla en el servicio Stream. Revise los detalles de [licencias de Microsoft Stream aquí](/stream/license-overview). Se puede acceder al servicio de eventos en directo a través de Stream, Yammer o Microsoft Teams. Para obtener más información sobre las capacidades de eventos en directo, vea [Live events across Microsoft 365 in Yammer, Microsoft Teams y Microsoft Stream](/stream/live-event-m365).

Todos los planes de suscripción compatibles son aptos para acceder al cliente web de Microsoft Teams, a los clientes de escritorio y a las aplicaciones móviles.

Microsoft Teams no está disponible como servicio independiente.

## <a name="feature-category-reference"></a>Referencia de categoría de características

En esta tabla se muestra la disponibilidad de características de Microsoft Teams en planes de licencias o instancias en la nube. Se aplican ciertas advertencias. Consulte las notas al pie para obtener más información. Esta tabla puede cambiar sin previo aviso. Consulte notificaciones del Centro de mensajes de Microsoft 365 para la mensajería de cambios de servicio principal y la documentación de referencia de términos de licencia [de Microsoft](https://www.microsoft.com/licensing/product-licensing/products).<br><br>

| Característica | Empresa pequeña | Planes de empresa | GCC | GCC- High | DOD | Educación |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Teams  <br/> |Sí <br/> |Sí <br/> |Sí <br/> |Sí<sup>1</sup>  <br/> |Sí<sup>1</sup>  <br/> |Sí  <br/> |
|Canales: estándar  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Canales: privado  <br/> |Sí  <br/> |Sí<sup>2</sup>  <br/> |Sí <br/> |No  <br/> |No <br/> |Sí  <br/> |
|Reuniones  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Escritorio de audio y vídeo de PowerPoint para compartir pantalla <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Voz  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>3</sup>  <br/> |Sí<sup>3</sup>  <br/> |Sí  <br/> |
|Audioconferencia  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>3</sup>  <br/> |Sí<sup>3</sup>  <br/> |Sí  <br/> |
|Aplicaciones, Bots, & Connectors  <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>5</sup>  <br/> |Sí<sup>5</sup>  <br/> |Sí<sup>4,5</sup>  <br/> |Sí  <br/> |
|Eventos en directo  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No<sup>6</sup>  <br/> |No<sup>6</sup>  <br/> |Sí  <br/> |

> <sup>1</sup>  Microsoft Teams en GCC-High y DOD admiten 2500 miembros en un equipo individual.<br/>
> <sup>2</sup> Microsoft Planner no está disponible actualmente para acceder en canales privados.<br/>
> <sup>3</sup> El enrutamiento directo debe configurarse para que la voz y la audioconferencia de Microsoft Teams funcionen en GCCH y DoD.<br/>
> <sup>4</sup> Microsoft OneNote no está disponible en las nubes de DOD.<br/>
> <sup>5</sup> Las aplicaciones de terceros y la publicación de aplicaciones no están disponibles en estas nubes en este momento.<br/>
> <sup>6</sup> Live Events no está disponible en GCC-High o DOD en este momento.<br/>

## <a name="next-steps"></a>Siguientes pasos

Comience a planear la implementación de Microsoft Teams visitando la [documentación técnica de Microsoft Teams](/MicrosoftTeams/). Manténgase al día sobre las características y capacidades de Teams [uniéndose a nuestra](https://aka.ms/TeamsBlog)comunidad y visitando nuestro blog de Microsoft Teams .

Para obtener más información acerca de las características de Teams por plataforma del sistema operativo, revise el artículo de soporte técnico de [características de Teams por plataforma](https://aka.ms/teamsfeaturesbyplatform).