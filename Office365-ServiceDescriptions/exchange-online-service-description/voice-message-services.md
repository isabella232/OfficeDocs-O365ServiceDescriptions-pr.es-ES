---
title: Servicios de mensajes de voz
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- office-365-voice-message-services
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: a02af6e2-75c2-4e83-843e-77241072068e
ms.openlocfilehash: a6245acdeaeda173f1a675d1ce34d9086e3f077a
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132554"
---
# <a name="voice-message-services"></a>Servicios de mensajes de voz

## <a name="voice-mail"></a>Correo de voz

Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:
  
- Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:
    
- Contestador automático (correo de voz)
    
- Interfaz de usuario de acceso telefónico a Exchange (Outlook Voice Access)
    
Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.
  
The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:
  
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
> The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls. 
>
> El correo de voz hospedado solo está disponible para suscriptores de Exchange Online plan 2 y Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidad del correo de voz de terceros

On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.
  
> [!NOTE]
> Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information. 
  
## <a name="skype-for-business-integration"></a>Integración con Skype Empresarial

Las organizaciones pueden comprar Skype Empresarial Online como servicio independiente o como parte de Microsoft Office 365. La implementación local de Skype empresarial 2015 también es compatible. Para obtener más información sobre Skype empresarial online, vea [Descripción del servicio Skype empresarial online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  

