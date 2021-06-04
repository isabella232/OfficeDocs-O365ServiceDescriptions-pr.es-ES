---
title: Servicios de mensajes de voz
ms.author: office365servicedesc
author: pamelaar
manager: gailw
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 23cc82d51d1afcbd2662e86dd6bc2aeebfb22346
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/09/2021
ms.locfileid: "51652684"
---
# <a name="voice-message-services"></a>Servicios de mensajes de voz

## <a name="voice-mail"></a>Correo de voz

Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:
  
- Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:
    
- Contestador automático (correo de voz)
    
- Interfaz de usuario de acceso telefónico a Exchange (Outlook Voice Access)
    
Interfaz de acceso telefónico para llamadores (operador automático)
  
Los servicios de mensajería de voz hospedados permiten a una empresa conectar su sistema telefónico local a los servicios de correo de voz que se proporcionan con Exchange Online. Los mensajes de correo de voz se graban y se almacenan en la infraestructura de Exchange Online, lo que permite a los usuarios tener acceso a sus mensajes de voz desde Outlook, desde Outlook Web Access o desde sus teléfonos móviles. Todas las conexiones telefónicas a Exchange Online requieren protocolos de voz sobre IP (VoIP). Los administradores pueden conectar los sistemas telefónicos IP PBX o PBX locales mediante puertas de enlace multimedia VoIP y controladores de bordes de sesión (SBC) para Exchange Online. No se requiere una puerta de enlace multimedia VoIP si el cliente implementó un IP PBX o si un PBX admite VoIP directamente y tiene interoperabilidad con los servicios de mensajería de voz de Exchange. Los SBC se implementan en el perímetro de la red del cliente para conectar una red de telefonía local y ayudar a proteger las comunicaciones (y la red del cliente) contra espías e intrusiones. También se admite la interoperabilidad con las capacidades de voz de Microsoft Lync Server 2010 y 2013.
  
- Las características de servicios de mensajería de voz disponibles en Exchange Online son parecidos a las que se ofrecen en Exchange Server 2013 local. Entre ellas se incluyen:
    
- Reproducir en el teléfono desde Outlook y Outlook Web App.
    
- Notificaciones de llamadas perdidas.
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).
    
- Restablecimiento de PIN del correo de voz desde Outlook Web App y Outlook (vea [Restablecer un PIN del correo de voz](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)). 
    
- Reglas de contestación de llamadas (vea Permitir que los usuarios de correo de voz [reenván llamadas para](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) obtener más información).
    
- Correo de voz protegido en Exchange Online (consulte [Protect voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) para obtener más información).
    
- Vista previa del correo de voz (vea Permitir a los usuarios ver una transcripción [de correo](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) de voz para obtener una lista de idiomas compatibles).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Acceso por voz a correo, correo de voz, calendario, contactos personales y grupos de contactos personales.
    
- Búsqueda de directorios con Outlook Voice Access o un operador automático.
    
Para obtener más información acerca de las características de correo de voz, vea [Correo de voz en Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> El cliente debe proporcionar una conexión de telefonía desde la red telefónica conmutada (RTC) mediante una puerta de enlace VoIP y PBX, IP PBX o Skype Empresarial Server 2015. 
>
> El cliente debe proporcionar los dispositivos de hardware SBC locales y garantizar que estén configurados correctamente para conectarse a los servicios de correo de voz en línea. Esto incluye configurar el nivel apropiado de seguridad mediante certificados, interfaces IP públicas y privadas, y la habilitación de los puertos TCP correctos a través de sus firewalls locales. 
>
> El correo de voz hospedado solo está disponible para Exchange Online plan 2 y Office 365 Enterprise suscriptores de E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidad del correo de voz de terceros

Interoperabilidad del correo de voz de terceros
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Integración con Skype Empresarial

Las organizaciones pueden comprar Skype Empresarial Online como servicio independiente o como parte de Microsoft Office 365. Skype Empresarial 2015 local también es compatible. Para obtener más información sobre Skype Empresarial Online, [consulte Skype Empresarial Descripción del servicio en línea](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, [consulte Exchange Online descripción del servicio](exchange-online-service-description.md).
