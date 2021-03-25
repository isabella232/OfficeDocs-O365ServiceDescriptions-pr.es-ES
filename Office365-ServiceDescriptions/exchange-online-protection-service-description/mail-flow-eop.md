---
title: Flujo de correo en Exchange Online Protection
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
description: Lea este artículo para obtener información sobre el flujo de correo en Microsoft Exchange Online Protection (EOP).
ms.openlocfilehash: 1d8cbe7d3483ee0cfc73e8cea372e0d36dbc7b6d
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173795"
---
# <a name="mail-flow-in-exchange-online-protection"></a>Flujo de correo en Exchange Online Protection

Para la mayoría de las organizaciones que usan Microsoft, hospedamos sus buzones y nos encargamos del flujo de correo. Es la configuración más sencilla y significa que Microsoft administra todos los buzones y el filtrado. En cambio, algunas organizaciones tienen una empresa que necesita mantener todos sus buzones de manera local. Exchange Online Protection (EOP) le permite hacerlo y proporciona procesamiento de correo antivirus y contra correo no deseado en la nube. Para obtener más información y para comprar EOP, vaya a [Exchange Online Protection](https://products.office.com/exchange/exchange-email-security-spam-protection).
  
¿Busca información sobre la administración de dominios o el bloqueo perimetral basado en directorios (DBEB)? Consulte [Recipient, domain, and company management](recipient-domain-and-company-management.md). Para obtener más información sobre todas las características de EOP, vea la descripción del servicio [de Exchange Online Protection](exchange-online-protection-service-description.md).
  
## <a name="routing-email-between-microsoft-and-your-own-email-servers"></a>Enrutamiento de correo electrónico entre Microsoft y sus propios servidores de correo electrónico

Puede configurar un conector para habilitar el flujo de correo entre Microsoft (incluidos Exchange Online o EOP) y un servidor de correo electrónico basado en SMTP como Exchange. Para obtener más información sobre esto, vea [Do I need a connector](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/do-i-need-to-create-a-connector)?. Y [Configurar conectores para enrutar el correo entre Microsoft y sus propios servidores de correo electrónico.](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente de EOP, puede configurar el flujo de correo seguro con un socio de confianza mediante conectores de Microsoft. Microsoft admite la comunicación segura a través de La seguridad de la capa de transporte (TLS) y puede crear un conector para aplicar el cifrado a través de TLS. [TLS](/microsoft-365/compliance/exchange-online-uses-tls-to-secure-email-connections) es un protocolo criptográfico que proporciona seguridad para las comunicaciones a través de Internet. Con los conectores, puede configurar TLS forzado tanto entrante como saliente mediante el uso de certificados autofirmados o validados por una entidad de certificación (CA). También puede aplicar otras restricciones de seguridad, como especificar nombres de dominio o intervalos de direcciones IP desde las que el socio de su organización envía correo. 
  
Para más información, vea [Configurar conectores para flujo de correo seguro con una organización asociada](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
## <a name="safe-listing-a-partners-ip-address"></a>Incluir en una lista segura la dirección IP de un socio

Puede agregar la dirección IP de un socio de confianza a una lista segura para garantizar que los mensajes procedentes de este socio no se someterán al filtrado contra correo no deseado. Para ello, use la lista de direcciones IP permitidas de filtro de conexión. Para obtener más información, vea [Configurar la directiva de filtro de conexión](/microsoft-365/security/office-365-security/configure-the-connection-filter-policy).
  
## <a name="conditional-mail-routing"></a>Enrutamiento de correo condicional

Puede configurar un conector con una regla de transporte que enrute el correo a un sitio concreto según ciertas condiciones. Para obtener más información, vea [Scenario: Conditional email routing](/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="hybrid-mail-routing"></a>Enrutamiento de correo híbrido

Híbrido significa que una parte de los buzones se hospeda de manera local y otra parte en la nube (Exchange Online). Puede pasar de una implementación independiente (local) a una híbrida.
  
Si tiene una implementación híbrida, puede proteger los buzones locales y los de la nube con EOP. Los buzones locales que se encuentran protegidos con EOP requieren licencias independientes. Para obtener más información sobre el enrutamiento de correo en una implementación híbrida, vea [Enrutamiento de transporte en las implementaciones híbridas de Exchange](/exchange/transport-routing).
  
El [Asistente para implementación de Microsoft Exchange Server](/exchange/exchange-deployment-assistant) también ofrece pautas detalladas para el aprovisionamiento de las implementaciones híbridas y el transporte de mensajes híbridos. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea Descripción del servicio [de Exchange Online Protection](exchange-online-protection-service-description.md).