---
title: Flujo del correo (EOP)
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Para la mayoría de las organizaciones que usan Office 365, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Office 365 administra todos los buzones y el filtrado. En cambio, algunas organizaciones tienen una empresa que necesita mantener todos sus buzones de manera local. Exchange Online Protection (EOP) le permite hacer esto y proporciona un procesamiento contra correo no deseado y antivirus en la nube. Para obtener más información y para comprar EOP, vaya a Exchange Online Protection.
ms.openlocfilehash: c55d1d376d617b863a75ff609cbc3f064418746b
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341829"
---
# <a name="mail-floweop"></a>Flujo del correo (EOP)

Para la mayoría de las organizaciones que usan Office 365, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Office 365 administra todos los buzones y el filtrado. En cambio, algunas organizaciones tienen una empresa que necesita mantener todos sus buzones de manera local. Exchange Online Protection (EOP) le permite hacer esto y proporciona un procesamiento contra correo no deseado y antivirus en la nube. Para obtener más información y para comprar EOP, vaya a [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).
  
¿Busca información sobre la administración de dominios o el bloqueo perimetral basado en directorios (DBEB)? Vea [Administración de destinatarios, dominios e información de la compañía](recipient-domain-and-company-management.md). Para más información sobre todas las características de EOP, vea [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a>Enrutar correo electrónico entre Office 365 y sus servidores de correo electrónico propios
<a name="BKMK_outboundmailrouting"> </a>

Puede configurar un conector para habilitar el flujo de correo entre Office 365 (incluido Exchange Online o EOP) y un servidor de correo electrónico basado en SMTP como Exchange. Para obtener más información sobre esto, vea [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)?. y [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner
<a name="BKMK_securemessagingwithatrustedpartner"> </a>

Como cliente de EOP, puede configurar el flujo de correo seguro con un socio de confianza mediante conectores de Office 365. Office 365 permite la comunicación segura mediante Seguridad de la capa de transporte (TLS) y puede crear un conector para forzar el cifrado mediante TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) es un protocolo criptográfico que proporciona seguridad para las comunicaciones por Internet. Con los conectores, puede configurar TLS forzado tanto entrante como saliente mediante el uso de certificados autofirmados o validados por una entidad de certificación (CA). También puede aplicar otras restricciones de seguridad, como especificar nombres de dominio o intervalos de direcciones IP desde las que el socio de su organización envía correo. 
  
Para más información, vea [Configurar conectores para flujo de correo seguro con una organización asociada](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).
  
## <a name="safe-listing-a-partners-ip-address"></a>Incluir en una lista segura la dirección IP de un socio
<a name="BKMK_safelistingapartnersipaddress"> </a>

Puede agregar la dirección IP de un socio de confianza a una lista segura para garantizar que los mensajes procedentes de este socio no se someterán al filtrado contra correo no deseado. Para ello, use la lista de direcciones IP permitidas de filtro de conexión. Para obtener más información, vea [Configurar la directiva de filtro de conexión](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Enrutamiento de correo condicional
<a name="BKMK_conditionalmailrouting"> </a>

Puede configurar un conector con una regla de transporte que enrute el correo a un sitio concreto según ciertas condiciones. Para obtener más información, vea [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="hybrid-mail-routing"></a>Hybrid mail routing
<a name="BKMK_hybridmailrouting"> </a>

Híbrido significa que una parte de los buzones se hospeda de manera local y otra parte en la nube (Exchange Online). Puede pasar de una implementación independiente (local) a una híbrida.
  
Si tiene una implementación híbrida, puede proteger los buzones locales y los de la nube con EOP. Los buzones locales que se encuentran protegidos con EOP requieren licencias independientes. Para obtener más información sobre el enrutamiento de correo en una implementación híbrida, vea [Enrutamiento de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
El [Asistente para implementación de Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) también ofrece pautas detalladas para el aprovisionamiento de las implementaciones híbridas y el transporte de mensajes híbridos. 
  
## <a name="feature-availability"></a>Disponibilidad de características
<a name="BKMK_hybridmailrouting"> </a>

Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).
  

