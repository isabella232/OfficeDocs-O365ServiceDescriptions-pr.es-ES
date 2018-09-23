---
title: Servicios de mensajes de voz
ms.author: pebaum
author: pebaum
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
ms.openlocfilehash: 98591e47ece7c59581824c6df375c41c66b7d2d1
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24037062"
---
# <a name="voice-message-services"></a>Servicios de mensajes de voz

## <a name="voice-mail"></a>Correo de voz

Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:
  
- Contestador automático (correo de voz)
    
- Interfaz de usuario de acceso telefónico a Exchange (Outlook Voice Access)
    
- Interfaz de usuario de acceso telefónico a Exchange (Outlook Voice Access)
    
Interfaz de acceso telefónico para llamadores (operador automático)
  
Los servicios de mensajería de voz hospedados permiten a una empresa conectar su sistema telefónico local a los servicios de correo de voz que se proporcionan con Exchange Online. Los mensajes de correo de voz se graban y se almacenan en la infraestructura de Exchange Online, lo que permite a los usuarios tener acceso a sus mensajes de voz desde Outlook, desde Outlook Web Access o desde sus teléfonos móviles. Todas las conexiones telefónicas a Exchange Online requieren protocolos de voz sobre IP (VoIP). Los administradores pueden conectar los sistemas telefónicos IP PBX o PBX locales mediante puertas de enlace multimedia VoIP y controladores de bordes de sesión (SBC) para Exchange Online. No se requiere una puerta de enlace multimedia VoIP si el cliente implementó un IP PBX o si un PBX admite VoIP directamente y tiene interoperabilidad con los servicios de mensajería de voz de Exchange. Los SBC se implementan en el perímetro de la red del cliente para conectar una red de telefonía local y ayudar a proteger las comunicaciones (y la red del cliente) contra espías e intrusiones. También se admite la interoperabilidad con las capacidades de voz de Microsoft Lync Server 2010 y 2013.
  
- Las características de servicios de mensajería de voz disponibles en Exchange Online son parecidos a las que se ofrecen en Exchange Server 2013 local. Entre ellas se incluyen:
    
- Reproducir en el teléfono desde Outlook y Outlook Web App.
    
- Notificaciones de llamadas perdidas.
    
- Restablecimiento de Outlook en el web y Outlook (consulte [Restablecer un PIN del correo de voz](https://go.microsoft.com/fwlink/p/?LinkId=286328)) del PIN del correo de voz.
    
- Restablecimiento de PIN del correo de voz desde Outlook Web App y Outlook (vea [Restablecer un PIN del correo de voz](https://go.microsoft.com/fwlink/p/?LinkId=271794)). 
    
- Reglas del contestador automático (para obtener más información, vea [Permitir a los usuarios de correo de voz reenviar llamadas](https://go.microsoft.com/fwlink/p/?LinkId=271795)). 
    
- Correo de voz protegido en Exchange Online (para obtener más información, vea [Proteger el correo de voz en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271796)). 
    
- Vista previa de correo de voz (vea la lista de idiomas admitidos en [Permitir a usuarios ver las transcripciones de correo de voz](https://go.microsoft.com/fwlink/p/?LinkId=271797)). 
    
- Acceso por voz a correo, correo de voz, calendario, contactos personales y grupos de contactos personales.
    
- Búsqueda de directorios con Outlook Voice Access o un operador automático.
    
- Los administradores configuran y administran la interoperabilidad de los servicios de mensajería de voz en el Centro de administración de Exchange (EAC).
    
Para obtener más información sobre las características del correo de voz, vea [Correo de voz en Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271798).
  
> [!IMPORTANT]
> La característica Reconocimiento de voz automático (ARS) no está disponible en la navegación de menús o la búsqueda de directorios para usuarios de Outlook Voice Access o llamadores de operador automático que utilizan comandos de voz. > El cliente debe proporcionar una conexión telefónica desde la red telefónica conmutada pública (PSTN) con una puerta de enlace VoIP y PBX, IP PBX o Skype Empresarial Server 2015. > El cliente debe proporcionar los dispositivos de hardware SBC locales y garantizar que estén configurados correctamente para conectarse a los servicios de correo de voz en línea. Esto incluye configurar el nivel apropiado de seguridad mediante certificados, interfaces IP públicas y privadas, y la habilitación de los puertos TCP correctos a través de sus firewalls locales. > El correo de voz hospedado está disponible solamente para suscriptores de Exchange Online Plan 2 y Office 365 Enterprise E3. 
  
## <a name="third-party-voice-mail-interoperability"></a>Interoperabilidad del correo de voz de terceros

Las soluciones de correo de voz locales de terceros pueden interoperar con Exchange Online si pueden reenviar mensajes de voz a través de SMTP o si admiten los servicios web de Microsoft Exchange. Si el sistema de correo de voz no admite de manera nativa el reenvío de mensajes de voz a través de SMTP, es posible tener un servidor en forma local para recibir mensajes del sistema de correo de voz y luego reenviarlos a la nube a través de SMTP. Debido a que muchos sistemas de correo de voz de terceros utilizan MAPI/CDO para interoperar con Exchange Server para características de mensajería unificada avanzadas, las capacidades completas de estos sistemas podrían no estar disponibles cuando SMTP se utiliza para la interoperabilidad con Exchange Online.
  
> [!NOTE]
> Exchange Online mensajería unificada compatibilidad con sistemas PBX de terceros a través de conexiones directas de cliente que se emplean SBCs finalizará en julio de 2018. Para obtener más información, consulte [fin de la asistencia para controladores de borde de sesión en Online mensajería unificada de Exchange](https://blogs.technet.microsoft.com/exchange/2017/07/18/discontinuation-of-support-for-session-border-controllers-in-exchange-online-unified-messaging/) . 
  
## <a name="skype-for-business-integration"></a>Integración con Skype Empresarial

Las organizaciones pueden comprar Skype Empresarial Online como servicio independiente o como parte de Microsoft Office 365. Para obtener más información sobre Skype Empresarial, consulte [Descripción del servicio Skype Empresarial Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

