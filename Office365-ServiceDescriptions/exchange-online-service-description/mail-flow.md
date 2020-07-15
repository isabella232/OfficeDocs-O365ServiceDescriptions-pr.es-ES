---
title: Flujo de correo
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Para la mayoría de las organizaciones, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Microsoft administra todos los buzones y el filtrado. En cambio, algunas organizaciones necesitan una configuración del flujo de correo más compleja para asegurarse de que cumplen con necesidades normativas o empresariales específicas. Puede obtener información sobre esas opciones aquí.
ms.openlocfilehash: 1ada5a3199e6ae65c6aaa99873f13a4025366a8d
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132724"
---
# <a name="mail-flow"></a>Flujo de correo

Para la mayoría de las organizaciones, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Microsoft administra todos los buzones y el filtrado. En cambio, algunas organizaciones necesitan una configuración del flujo de correo más compleja para asegurarse de que cumplen con necesidades normativas o empresariales específicas. Puede obtener información sobre esas opciones aquí. 
  
## <a name="custom-routing-of-outbound-email"></a>Enrutamiento personalizado de correo saliente

Microsoft Exchange Online puede enrutar el flujo de correo de su organización con un servidor local o un servicio hospedado (a veces denominado "hospedaje inteligente"). Esto permite a su organización usar dispositivos de prevención de pérdida de datos (DLP), realizar un posterior procesamiento personalizado del correo electrónico saliente y entregar el correo electrónico a los socios comerciales a través de redes privadas. Exchange Online también admite la reescritura de direcciones, que enruta el correo saliente a través de una puerta de enlace local que modifica las direcciones. Esta característica le permite ocultar subdominios, hacer que el correo electrónico de una organización de varios dominios aparezca como un único dominio o hacer que el correo electrónico retransmitido por el asociado aparezca como si se hubiera enviado desde dentro de la organización. Los administradores configuran el enrutamiento de correo personalizado dentro del Centro de administración de Exchange (EAC).
  
Para obtener más información, vea [set up Connectors to redirigir el correo entre Microsoft y sus propios servidores de correo electrónico](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).
  
> [!IMPORTANT]
> Exchange Online puede entregar el correo que fluye dentro y fuera de la organización. Si el dominio del destinatario está hospedado en Exchange Online con registros MX de DNS que señalan a Exchange Online Protection, el flujo de correo desde su inquilino hasta el destinatario no se recorrerá a través de Internet.
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Secure messaging with a trusted partner

Como cliente de Exchange Online, puede configurar el flujo de correo seguro con un socio de confianza mediante los conectores de Microsoft. Microsoft admite la comunicación segura a través de la seguridad de la capa de transporte (TLS) y puede crear un conector para forzar el cifrado a través de TLS. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) es un protocolo criptográfico que proporciona seguridad para las comunicaciones a través de Internet. Con los conectores, puede configurar TLS forzado tanto entrante como saliente mediante el uso de certificados autofirmados o validados por una entidad de certificación (CA). También puede aplicar otras restricciones de seguridad, como especificar nombres de dominio o intervalos de direcciones IP desde las que el socio de su organización envía correo. 
  
Para obtener más información, vea [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).
  
> [!IMPORTANT]
> Es posible que se requiera un certificado validado por la AC. 
  
## <a name="conditional-mail-routing"></a>Enrutamiento de correo condicional

You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.
  
Para obtener más información, vea [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).
  
## <a name="incoming-mail-safe-list"></a>Lista segura de correo entrante

You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.
  
Para obtener más información, vea [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).
  
## <a name="hybrid-email-routing"></a>Enrutamiento de correo híbrido

A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.
  
Para obtener más información sobre el enrutamiento de correo en una implementación híbrida, vea [Enrutamiento de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
El [Asistente para implementación de Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) también ofrece pautas detalladas para el aprovisionamiento de las implementaciones híbridas y el transporte de mensajes híbridos. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espacio de direcciones compartido con control de enrutamiento local (MX Points a local)

Espacio de direcciones compartido con el control de enrutamiento local (MX Points to on-premises) es un escenario de enrutamiento de correo de implementación híbrida en el que los buzones se hospedan parcialmente en Exchange Online y parcialmente en local, y el flujo de correo entrante y saliente de Internet se enruta a través de la organización de Exchange local. Este escenario también se denomina transporte de correo centralizado. En este escenario, Exchange Online se aprovisiona con EOP y el correo de Internet entrante se enruta a su servidor de correo local antes de enrutarse a EOP y, finalmente, a los buzones hospedados en Exchange Online. Además, el correo que sale de los buzones de Exchange Online se enruta a través de la organización local de Exchange para los mensajes enviados a destinatarios externos. Con esta configuración, puede usar un espacio de nombre de dominio SMTP simple para todos los buzones de su organización de Exchange local y su organización de Exchange Online. 
  
Para obtener más información sobre las opciones de transporte en una implementación híbrida, vea [Opciones de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espacio de direcciones compartido sin Control de enrutamiento local (MX Points a EOP)

El espacio de direcciones compartido sin Control de enrutamiento local (Puntos MX a EOP) es un escenario de enrutamiento de correo híbrido en el que los buzones están hospedados parcialmente en la nube con Exchange Online y parcialmente de manera local, y sus puntos de registros MX en EOP. Este escenario es apropiado cuando usa Microsoft para hospedar algunos de los buzones de la organización y desea que EOP proteja tanto los buzones de correo locales como los de la nube. En este escenario, el correo enviado a los destinatarios de su organización se enruta a través de EOP, donde hay filtros de correo no deseado y filtrado de directivas, antes de llegar a los buzones locales y de la nube. 
  
Para obtener más información sobre las opciones de transporte en una implementación híbrida, vea [Opciones de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Solución de problemas de una implementación con el Asistente de configuración híbrida

Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.
  
Para obtener más información sobre cómo solucionar problemas en una implementación con el Asistente para la configuración híbrida, vea [Solucionar problemas de una implementación híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Administrar una configuración híbrida

You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.
  
Para obtener más información sobre cómo administrar una configuración de implementación híbrida, vea [Administrar una implementación híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Requisitos de implementación híbrida

Para obtener más información sobre los requisitos de implementación híbrida, vea [Requisitos previos de implementación híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> En algunas configuraciones híbridas, es posible que deba comprar licencias de Exchange Online Protection para los buzones de su organización. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, vea la [Descripción del servicio de Exchange Online](exchange-online-service-description.md).
  