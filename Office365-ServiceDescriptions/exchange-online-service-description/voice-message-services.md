---
title: Servicios de mensajes de voz
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: f1bf261e002eb7c8a637266c3b243ad728c63be3
ms.sourcegitcommit: 7a68dc894dde0d06fab014c56914a78aa8cda847
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/21/2020
ms.locfileid: "43640318"
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
    
- Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](https://go.microsoft.com/fwlink/p/?LinkId=286328)).
    
- Restablecimiento de PIN del correo de voz desde Outlook Web App y Outlook (vea [Restablecer un PIN del correo de voz](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Reglas de respuesta a llamada (vea [permitir a los usuarios de correo de voz reenviar llamadas](https://go.microsoft.com/fwlink/p/?LinkId=271795) para obtener más información).
    
- Correo de voz protegido en Exchange Online (consulte [proteger el correo de voz en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796) para obtener más información).
    
- Vista previa de correo de voz (vea [permitir a los usuarios ver una transcripción de correo de voz](https://go.microsoft.com/fwlink/p/?LinkId=271797) para obtener una lista de los idiomas admitidos).
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Acceso por voz a correo, correo de voz, calendario, contactos personales y grupos de contactos personales.
    
- Búsqueda de directorios con Outlook Voice Access o un operador automático.
    
Para obtener más información sobre las características de correo de voz, vea [correo de voz en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. 
>
> El cliente debe proporcionar una conexión telefónica desde la red telefónica conmutada pública (RTC) con una puerta de enlace VoIP y PBX, IP PBX o Skype empresarial Server 2015. 
>
> El cliente debe proporcionar los dispositivos de hardware SBC locales y garantizar que estén configurados correctamente para conectarse a los servicios de correo de voz en línea. Esto incluye configurar el nivel apropiado de seguridad mediante certificados, interfaces IP públicas y privadas, y la habilitación de los puertos TCP correctos a través de sus firewalls locales. 
>
> El correo de voz hospedado solo está disponible para suscriptores de Exchange Online plan 2 y Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidad del correo de voz de terceros

Interoperabilidad del correo de voz de terceros
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Integración con Skype Empresarial

Las organizaciones pueden comprar Skype Empresarial Online como servicio independiente o como parte de Microsoft Office 365. La implementación local de Skype empresarial 2015 también es compatible. Para obtener más información sobre Skype empresarial online, vea [Descripción del servicio Skype empresarial online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  

