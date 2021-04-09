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
# <a name="voice-message-services"></a><span data-ttu-id="b9462-102">Servicios de mensajes de voz</span><span class="sxs-lookup"><span data-stu-id="b9462-102">Voice message services</span></span>

## <a name="voice-mail"></a><span data-ttu-id="b9462-103">Correo de voz</span><span class="sxs-lookup"><span data-stu-id="b9462-103">Voice mail</span></span>

<span data-ttu-id="b9462-104">Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:</span><span class="sxs-lookup"><span data-stu-id="b9462-104">Microsoft Exchange Online offers hosted voice mail services, which provide:</span></span>
  
- <span data-ttu-id="b9462-105">Microsoft Exchange Online ofrece servicios de correo de voz hospedado, que brindan:</span><span class="sxs-lookup"><span data-stu-id="b9462-105">Call answering (voice mail)</span></span>
    
- <span data-ttu-id="b9462-106">Contestador automático (correo de voz)</span><span class="sxs-lookup"><span data-stu-id="b9462-106">Dial-in user interface to Exchange (Outlook Voice Access)</span></span>
    
- <span data-ttu-id="b9462-107">Interfaz de usuario de acceso telefónico a Exchange (Outlook Voice Access)</span><span class="sxs-lookup"><span data-stu-id="b9462-107">Dial-in interface for callers (auto attendant)</span></span>
    
<span data-ttu-id="b9462-p101">Interfaz de acceso telefónico para llamadores (operador automático)</span><span class="sxs-lookup"><span data-stu-id="b9462-p101">Hosted voice messaging services allow a company to connect its on-premises phone system to voice mail services provided by Exchange Online. Voice mail messages are recorded and stored in the Exchange Online infrastructure, allowing users to access their voice messages from Outlook, Outlook on the web, or mobile phones. All telephony connections to Exchange Online require voice-over-IP (VoIP) protocols. Administrators can connect on-premises IP PBXs or PBX phone systems using VoIP media gateways and session border controllers (SBCs) to Exchange Online. A VoIP media gateway is not required if the customer has deployed an IP PBX or if a PBX supports VoIP directly and is interoperable with Exchange voice messaging services. SBCs are deployed in the perimeter of the customer network to connect an on-premises telephony network and help secure the communications (and the customer network) against eavesdropping and intrusion. Interoperability with the voice capabilities of Microsoft Lync Server 2010 and 2013 is also supported.</span></span>
  
<span data-ttu-id="b9462-p102">Los servicios de mensajería de voz hospedados permiten a una empresa conectar su sistema telefónico local a los servicios de correo de voz que se proporcionan con Exchange Online. Los mensajes de correo de voz se graban y se almacenan en la infraestructura de Exchange Online, lo que permite a los usuarios tener acceso a sus mensajes de voz desde Outlook, desde Outlook Web Access o desde sus teléfonos móviles. Todas las conexiones telefónicas a Exchange Online requieren protocolos de voz sobre IP (VoIP). Los administradores pueden conectar los sistemas telefónicos IP PBX o PBX locales mediante puertas de enlace multimedia VoIP y controladores de bordes de sesión (SBC) para Exchange Online. No se requiere una puerta de enlace multimedia VoIP si el cliente implementó un IP PBX o si un PBX admite VoIP directamente y tiene interoperabilidad con los servicios de mensajería de voz de Exchange. Los SBC se implementan en el perímetro de la red del cliente para conectar una red de telefonía local y ayudar a proteger las comunicaciones (y la red del cliente) contra espías e intrusiones. También se admite la interoperabilidad con las capacidades de voz de Microsoft Lync Server 2010 y 2013.</span><span class="sxs-lookup"><span data-stu-id="b9462-p102">The voice messaging services features available in Exchange Online are similar to those offered in on-premises Exchange Server 2016. These include:</span></span>
  
- <span data-ttu-id="b9462-117">Las características de servicios de mensajería de voz disponibles en Exchange Online son parecidos a las que se ofrecen en Exchange Server 2013 local. Entre ellas se incluyen:</span><span class="sxs-lookup"><span data-stu-id="b9462-117">Play on phone from Outlook and Outlook on the web.</span></span>
    
- <span data-ttu-id="b9462-118">Reproducir en el teléfono desde Outlook y Outlook Web App.</span><span class="sxs-lookup"><span data-stu-id="b9462-118">Missed call notifications.</span></span>
    
- <span data-ttu-id="b9462-119">Notificaciones de llamadas perdidas.</span><span class="sxs-lookup"><span data-stu-id="b9462-119">Caller ID (using information in the Global Address List, users' personal contacts, custom Contacts folder, and contacts from external social networks).</span></span>
    
- <span data-ttu-id="b9462-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).</span><span class="sxs-lookup"><span data-stu-id="b9462-120">Voice mail PIN reset from Outlook on the web and Outlook (see [Reset a Voice Mail PIN](/exchange/voice-mail-unified-messaging/set-outlook-voice-access-pin-security/reset-a-voice-mail-pin)).</span></span>
    
- <span data-ttu-id="b9462-121">Restablecimiento de PIN del correo de voz desde Outlook Web App y Outlook (vea [Restablecer un PIN del correo de voz](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online)).</span><span class="sxs-lookup"><span data-stu-id="b9462-121">Message Waiting Indicator (see [MWI in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/mwi-in-exchange-online) for details).</span></span> 
    
- <span data-ttu-id="b9462-122">Reglas de contestación de llamadas (vea Permitir que los usuarios de correo de voz [reenván llamadas para](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) obtener más información).</span><span class="sxs-lookup"><span data-stu-id="b9462-122">Call answering rules (see [Allow voice mail users to forward calls](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-voice-mail-users-to-forward-calls) for details).</span></span>
    
- <span data-ttu-id="b9462-123">Correo de voz protegido en Exchange Online (vea [Proteger el correo de voz en Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) para obtener más información).</span><span class="sxs-lookup"><span data-stu-id="b9462-123">Protected voice mail in Exchange Online (see [Protect voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/protect-voice-mail) for details).</span></span>
    
- <span data-ttu-id="b9462-124">Vista previa del correo de voz (vea Permitir a los usuarios ver una transcripción [de correo](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) de voz para obtener una lista de idiomas compatibles).</span><span class="sxs-lookup"><span data-stu-id="b9462-124">Voice mail preview (see [Allow users to see a voice mail transcript](/exchange/voice-mail-unified-messaging/set-up-client-voice-mail-features/allow-users-to-see-a-voice-mail-transcript) for a list of supported languages).</span></span>
    
- <span data-ttu-id="b9462-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span><span class="sxs-lookup"><span data-stu-id="b9462-125">Speech access to email, voice mail, calendar, personal contacts, and personal contact groups.</span></span>
    
- <span data-ttu-id="b9462-126">Acceso por voz a correo, correo de voz, calendario, contactos personales y grupos de contactos personales.</span><span class="sxs-lookup"><span data-stu-id="b9462-126">Directory search through Outlook Voice Access or an auto attendant.</span></span>
    
- <span data-ttu-id="b9462-127">Búsqueda de directorios con Outlook Voice Access o un operador automático.</span><span class="sxs-lookup"><span data-stu-id="b9462-127">Administrators configure and manage voice messaging services interoperability by using the Exchange admin center (EAC).</span></span>
    
<span data-ttu-id="b9462-128">Para obtener más información acerca de las características de correo de voz, vea [Correo de voz en Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).</span><span class="sxs-lookup"><span data-stu-id="b9462-128">For more information about voice mail features, see [Voice mail in Exchange Online](/exchange/voice-mail-unified-messaging/voice-mail-unified-messaging).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="b9462-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span><span class="sxs-lookup"><span data-stu-id="b9462-129">The Automatic Speech Recognition (ASR) feature isn't available in menu navigation or directory search for Outlook Voice Access users or auto attendant callers using voice commands.</span></span> 
>
> <span data-ttu-id="b9462-130">El cliente debe proporcionar una conexión de telefonía desde la red telefónica conmutada (RTC) mediante una puerta de enlace VoIP y PBX, IP PBX o Skype Empresarial Server 2015.</span><span class="sxs-lookup"><span data-stu-id="b9462-130">The customer must provide a telephony connection from the public switched telephone network (PSTN) using a VoIP gateway and PBX, IP PBX, or Skype for Business Server 2015.</span></span> 
>
> <span data-ttu-id="b9462-p103">El cliente debe proporcionar los dispositivos de hardware SBC locales y garantizar que estén configurados correctamente para conectarse a los servicios de correo de voz en línea. Esto incluye configurar el nivel apropiado de seguridad mediante certificados, interfaces IP públicas y privadas, y la habilitación de los puertos TCP correctos a través de sus firewalls locales.</span><span class="sxs-lookup"><span data-stu-id="b9462-p103">The customer must provide the on-premises SBC hardware devices and ensure that the SBCs are correctly configured to connect to the online voice mail services. This includes configuring the appropriate level of security by using certificates and public and private IP interfaces and by enabling the correct TCP ports through their on-premises firewalls.</span></span> 
>
> <span data-ttu-id="b9462-133">El correo de voz hospedado solo está disponible para los suscriptores de Exchange Online Plan 2 y Office 365 Enterprise E3.</span><span class="sxs-lookup"><span data-stu-id="b9462-133">Hosted voice mail is available only to Exchange Online Plan 2 and Office 365 Enterprise E3 subscribers.</span></span> 
  
## <a name="third-party-voice-mail-interoperability"></a><span data-ttu-id="b9462-134">Interoperabilidad del correo de voz de terceros</span><span class="sxs-lookup"><span data-stu-id="b9462-134">Third-party voice mail interoperability</span></span>

<span data-ttu-id="b9462-p104">Interoperabilidad del correo de voz de terceros</span><span class="sxs-lookup"><span data-stu-id="b9462-p104">On-premises voice mail solutions from third-party providers can interoperate with Exchange Online if they can forward voice messages through SMTP or if they support Microsoft Exchange Web Services. If the voice mail system does not natively support forwarding voice messages through SMTP, an email server can be kept on-premises to receive messages from the voice mail system and then forward them to the cloud using SMTP. Because many third-party voice mail systems use MAPI/CDO to interoperate with Exchange Server for advanced UM features, the full capabilities of these systems may not be available when SMTP is used for interoperability with Exchange Online.</span></span>
  
> [!NOTE]
> <span data-ttu-id="b9462-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span><span class="sxs-lookup"><span data-stu-id="b9462-p105">Exchange Online UM support for third-party PBX systems via direct connections from customer operated SBCs will end in July 2018. Please see [Discontinuation of support for Session Border Controllers in Exchange Online Unified Messaging](https://techcommunity.microsoft.com/t5/Exchange-Team-Blog/Discontinuation-of-support-for-Session-Border-Controllers-in/ba-p/607117) for more information.</span></span> 
  
## <a name="skype-for-business-integration"></a><span data-ttu-id="b9462-140">Integración con Skype Empresarial</span><span class="sxs-lookup"><span data-stu-id="b9462-140">Skype for Business integration</span></span>

<span data-ttu-id="b9462-141">Las organizaciones pueden comprar Skype Empresarial Online como servicio independiente o como parte de Microsoft Office 365.</span><span class="sxs-lookup"><span data-stu-id="b9462-141">Organizations can purchase Skype for Business Online as a standalone service or as part of Microsoft Office 365.</span></span> <span data-ttu-id="b9462-142">También se admite Skype Empresarial 2015 local.</span><span class="sxs-lookup"><span data-stu-id="b9462-142">Skype for Business 2015 on-premises is also supported.</span></span> <span data-ttu-id="b9462-143">Para obtener más información sobre Skype Empresarial Online, vea Descripción del servicio [de Skype Empresarial Online](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="b9462-143">To learn more about Skype for Business Online, see [Skype for Business Online service description](../skype-for-business-online-service-description/skype-for-business-online-service-description.md).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="b9462-144">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="b9462-144">Feature availability</span></span>

<span data-ttu-id="b9462-145">Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea [Descripción del servicio de Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="b9462-145">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
