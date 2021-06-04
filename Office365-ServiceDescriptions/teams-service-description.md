---
title: Descripción del servicio Microsoft Teams
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Normal
description: Obtenga información sobre Microsoft Teams disponibilidad de características y servicios en Microsoft 365 y Office 365 planes.
ms.openlocfilehash: 721c4bd99fd8f81e471ea79e6725c2d6c53d1791
ms.sourcegitcommit: c455501e86037b0f86e0afc9d6d6d04afdfd3442
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/28/2021
ms.locfileid: "52074491"
---
# <a name="microsoft-teams-service-description"></a>Descripción del servicio Microsoft Teams

Microsoft Teams es el centro del trabajo en equipo en Microsoft 365. El Teams permite la mensajería instantánea, las llamadas de audio y vídeo, las reuniones enriquecciones en línea, las experiencias móviles y las amplias capacidades de conferencia web. Además, Teams colaboración de archivos y datos y características de extensibilidad, e se integra con Microsoft 365 y otras aplicaciones de Microsoft y asociados.

Skype Empresarial Online se retira el 31 de julio de [](https://techcommunity.microsoft.com/t5/Microsoft-Teams-Blog/Skype-for-Business-Online-to-Be-Retired-in-2021/ba-p/777833) 2021, que se anunció el 30 de julio de 2019. Microsoft Teams es un servicio totalmente nuevo, creado para la nube desde cero al aprovechar Azure y otras innovaciones de servicio de Microsoft. Microsoft Teams se basa en grupos Microsoft 365, Microsoft Graph y con la misma seguridad, cumplimiento y capacidad de administración a nivel empresarial que el resto de Office 365. Teams aprovecha las identidades almacenadas en Azure Active Directory (Azure AD). Estos servicios se entregan desde centros de datos de Microsoft y son accesibles para los usuarios en una amplia variedad de dispositivos desde dentro de una red corporativa o a través de Internet. Para obtener más información, vea el Microsoft Teams [arquitectura de TI y los pósteres de](/microsoftteams/teams-architecture-solutions-posters)soluciones de telefonía.

Esta descripción del servicio detalla las diferencias clave entre los servicios proporcionados en las distintas instalaciones en la nube. Microsoft Teams funcionalidades principales no difieren entre las suscripciones. La disponibilidad de las capacidades de cumplimiento depende del nivel de suscripción. Para obtener más información Teams seguridad y cumplimiento normativo, vea [Seguridad y cumplimiento en Microsoft Teams](/microsoftteams/security-compliance-overview).

Si los usuarios se han migrado completamente en línea, deben tener licencias de teams y Skype Empresarial Online para la funcionalidad Teams completa, incluso si Skype Empresarial Online no se usará.

## <a name="available-plans"></a>Planes disponibles

Para obtener información detallada del plan sobre las suscripciones que permiten a los usuarios Teams, consulte [Find the right Microsoft Teams for your business](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options). Puede encontrar más detalles en la tabla de comparación [de soluciones de Microsoft](https://go.microsoft.com/fwlink/?linkid=2139145).

Los planes gubernamentales que admiten Teams incluyen Office 365 G1 a G5. Para obtener más información, [vea Office 365 Administración Pública planes](https://www.microsoft.com/microsoft-365/government/compare-office-365-government-plans).

Todos los planes de suscripción admitidos son aptos para acceder al Microsoft Teams web, los clientes de escritorio y las aplicaciones móviles.

Microsoft Teams no está disponible como servicio independiente.

## <a name="feature-availability"></a>Disponibilidad de características

En la tabla siguiente se enumeran las Teams principales disponibles en todos los planes. Se aplican ciertas advertencias. Vea las notas al pie para obtener más información. Esta tabla puede cambiar sin previo aviso.

Para obtener más información sobre Teams características de la plataforma del sistema operativo, vea [Teams por plataforma](https://aka.ms/teamsfeaturesbyplatform).

Para obtener la lista más actualizada y completa de características de Teams en los planes Microsoft 365 y Office 365, consulte [Find the right Microsoft Teams for your business](https://www.microsoft.com/microsoft-teams/compare-microsoft-teams-options).<br><br>

| Característica | Planes de pequeña empresa | Enterprise planes | GCC | GCC- High | DOD | Planes educativos |
|:-----|:-----|:-----|:-----|:-----|:-----|:-----|
|Chat  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Teams  <br/> |Sí <br/> |Sí <br/> |Sí <br/> |Sí<sup>1</sup>  <br/> |Sí<sup>1</sup>  <br/> |Sí  <br/> |
|Canales: estándar  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Canales: privado  <br/> |Sí  <br/> |Sí<sup>2</sup>  <br/> |Sí <br/> |No  <br/> |No <br/> |Sí  <br/> |
|Reuniones  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Pantalla compartida PowerPoint escritorio de audio y vídeo <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |
|Voz  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>3</sup>  <br/> |Sí<sup>3</sup>  <br/> |Sí  <br/> |
|Audioconferencia  <br/> |Sí  <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>3</sup>  <br/> |Sí<sup>3</sup>  <br/> |Sí  <br/> |
|Aplicaciones, Bots, & Connectors  <br/> |Sí  <br/> |Sí  <br/> |Sí<sup>4</sup>  <br/> |Sí<sup>4</sup>  <br/> |Sí<sup>4</sup>  <br/> |Sí  <br/> |
|Eventos en directo  <br/> |No  <br/> |Sí  <br/> |Sí  <br/> |No<sup>5</sup>  <br/> |No<sup>5</sup>  <br/> |Sí  <br/> |

<sup>1 Microsoft Teams</sup> en GCC-High y DOD admiten 2500 miembros en un equipo individual.<br/>
<sup>2</sup> Microsoft Planner no está disponible actualmente para acceder en canales privados.<br/>
<sup>3</sup> El enrutamiento directo debe configurarse para que Microsoft Teams voz y audioconferencia funcionen en GCCH y DoD.<br/>
<sup>4</sup> Las aplicaciones de terceros y la publicación de aplicaciones no están disponibles en estas nubes en este momento. Los conectores no se admiten en GCCH y DOD.<br/>
<sup>5</sup> Live Events no está disponible en GCC-High o DOD en este momento.<br/>

### <a name="cloud-voice-features"></a>Características de voz en la nube

Para las audioconferencias, la organización debe comprar y asignar una licencia de audioconferencia a cada usuario que configura reuniones de acceso telefónico local. Para Teams características que requieren planes de llamadas, cada usuario necesita un sistema telefónico y un plan de llamadas nacionales o nacionales e internacionales. Para obtener más información, [vea Microsoft Teams licencias de complementos](/microsoftteams/teams-add-on-licensing/microsoft-teams-add-on-licensing).

### <a name="live-events"></a>Eventos en directo

Esta oferta en Office 365 reemplaza a la difusión de reunión Skype retirada. Las funcionalidades de eventos en directo están disponibles para los planes de licencias, tal como se detalla en el servicio Stream. Para obtener más información, consulte la introducción a [las licencias de Microsoft Stream](/stream/license-overview). Se puede obtener acceso al servicio de eventos en directo a través de Stream, Yammer o Microsoft Teams. Para obtener más información acerca de las funcionalidades de eventos en directo, vea [Live events across Microsoft 365 in Yammer, Microsoft Teams y Microsoft Stream](/stream/live-event-m365). Para obtener más información sobre la planeación de eventos en directo, incluidos los requisitos de licencia, vea [Plan for live events in Microsoft Teams](/microsoftteams/teams-live-events/plan-for-teams-live-events).

## <a name="learn-more"></a>Más información

Para obtener más información Teams, consulte los siguientes recursos:
 
- [Documentación de administración de Microsoft Teams](/MicrosoftTeams)
- [Microsoft Teams de tecnología](https://techcommunity.microsoft.com/t5/microsoft-teams/ct-p/MicrosoftTeams)
- [Microsoft Teams blog](https://aka.ms/TeamsBlog)

### <a name="licensing-terms"></a>Términos de licencia

Para obtener términos y condiciones de licencia para productos y servicios comprados a través de los programas de licencias por volumen comerciales de Microsoft, consulte el [sitio términos del producto](https://www.microsoft.com/licensing/terms/). 

### <a name="messaging"></a>Mensajería 

Para mantenerse informado de los próximos cambios, incluidas las características nuevas y modificadas, el mantenimiento planeado u otros anuncios importantes, visite el Centro de mensajes. Para obtener más información, vea [Centro de mensajes](/microsoft-365/admin/manage/message-center).

### <a name="accessibility"></a>Accesibilidad

Microsoft sigue comprometido con la seguridad de sus datos y la accesibilidad de nuestros servicios. Para obtener más información, vea [el Centro](https://www.microsoft.com/trust-center) de confianza de Microsoft y el Centro Office [accesibilidad](https://support.office.com/article/ecab0fcf-d143-4fe8-a2ff-6cd596bddc6d).
