---
title: Flujo de correo [EOP]
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Para la mayoría de las organizaciones que usan Office 365, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Microsoft administra todos los buzones y el filtrado. En cambio, algunas organizaciones tienen una empresa que necesita mantener todos sus buzones de manera local. Exchange Online Protection (EOP) le permite hacer esto y proporciona procesamiento de correo electrónico no deseado y contra correo no deseado en la nube.
ms.openlocfilehash: 751551ef6b3ae710646b2fb63960eee5983d6c47
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132824"
---
# <a name="mail-floweop"></a>Flujo de correo [EOP]

Para la mayoría de las organizaciones que usan Microsoft, hospedamos sus buzones y se ocupan del flujo de correo. Es la configuración más sencilla y significa que Microsoft administra todos los buzones y el filtrado. En cambio, algunas organizaciones tienen una empresa que necesita mantener todos sus buzones de manera local. Exchange Online Protection (EOP) le permite hacer esto y proporciona procesamiento de correo electrónico no deseado y contra correo no deseado en la nube. Para obtener más información y para comprar EOP, vaya a [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
¿Busca información sobre la administración de dominios o el bloqueo perimetral basado en directorios (DBEB)? Consulte [Administración de destinatarios, dominios y compañías](recipient-domain-and-company-management.md). Para obtener más información sobre todas las características de EOP, vea la [Descripción del servicio de protección en línea de Exchange](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Enrutamiento de correo electrónico entre Microsoft y sus propios servidores de correo electrónico

Puede configurar un conector para habilitar el flujo de correo entre Microsoft (incluido Exchange online o EOP) y un servidor de correo electrónico basado en SMTP como Exchange. Para obtener más información sobre esto, vea [Do I need a connector](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)?. Y [configurar conectores para enrutar el correo entre Microsoft y sus propios servidores de correo electrónico](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente de EOP, puede configurar el flujo de correo seguro con un socio de confianza mediante los conectores de Microsoft. Microsoft admite la comunicación segura a través de la seguridad de la capa de transporte (TLS) y puede crear un conector para forzar el cifrado a través de TLS. [TLS](https://docs.microsoft.com/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) es un protocolo criptográfico que proporciona seguridad para las comunicaciones a través de Internet. Con los conectores, puede configurar TLS forzado tanto entrante como saliente mediante el uso de certificados autofirmados o validados por una entidad de certificación (CA). También puede aplicar otras restricciones de seguridad, como especificar nombres de dominio o intervalos de direcciones IP desde las que el socio de su organización envía correo. 
  
Para más información, vea [Configurar conectores para flujo de correo seguro con una organización asociada](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Incluir en una lista segura la dirección IP de un socio

You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).
  
## <a name="conditional-mail-routing"></a>Enrutamiento de correo condicional

You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Enrutamiento de correo híbrido

Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.
  
If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
El [Asistente para implementación de Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) también ofrece pautas detalladas para el aprovisionamiento de las implementaciones híbridas y el transporte de mensajes híbridos. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).
