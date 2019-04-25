---
title: Servicios de mensajes de voz
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: 3879252927a26f47cd5d92f0fbcfbdecf4466c2a
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 04/25/2019
ms.locfileid: "33246476"
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
    
- Indicador de mensajes en espera (para obtener más información, vea [Indicador de mensajes en espera en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271795)). 
    
- Reglas del contestador automático (para obtener más información, vea [Permitir a los usuarios de correo de voz reenviar llamadas](https://go.microsoft.com/fwlink/p/?LinkId=271796)). 
    
- Correo de voz protegido en Exchange Online (para obtener más información, vea [Proteger el correo de voz en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271797)). 
    
- Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.
    
- Acceso por voz a correo, correo de voz, calendario, contactos personales y grupos de contactos personales.
    
- Búsqueda de directorios con Outlook Voice Access o un operador automático.
    
For more information about voice mail features, see [Voice Mail in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands. > The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015. > The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. > Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidad del correo de voz de terceros

Interoperabilidad del correo de voz de terceros
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) for more information. 
  
## <a name="skype-for-business-integration"></a>Integración con Skype Empresarial

Las organizaciones pueden comprar Skype Empresarial Online como servicio independiente o como parte de Microsoft Office 365. Para obtener más información sobre Skype Empresarial, consulte [Descripción del servicio Skype Empresarial Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

