---
title: Flujo de correo
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: 'Para la mayoría de las organizaciones que usan Office 365, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Office 365 administra todos los buzones y el filtrado. En cambio, algunas organizaciones necesitan una configuración del flujo de correo más compleja para asegurarse de que cumplen con necesidades normativas o empresariales específicas. Puede obtener información sobre esas opciones aquí. '
ms.openlocfilehash: e5b56712a3c88c91b943d681f927cea480776839
ms.sourcegitcommit: 68eee0c2885fd112e37eea27370c3f8c1f0831cb
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/07/2019
ms.locfileid: "30467297"
---
# <a name="mail-flow"></a>Mail Flow

Para la mayoría de las organizaciones que usan Office 365, hospedamos sus buzones y nos ocupamos del flujo de correo. Es la configuración más sencilla y significa que Office 365 administra todos los buzones y el filtrado. En cambio, algunas organizaciones necesitan una configuración del flujo de correo más compleja para asegurarse de que cumplen con necesidades normativas o empresariales específicas. Puede obtener información sobre esas opciones aquí.  
  
## <a name="custom-routing-of-outbound-email"></a>Enrutamiento personalizado de correo saliente

Microsoft Exchange Online puede enrutar el flujo de correo de su organización con un servidor local o un servicio hospedado (a veces denominado "hospedaje inteligente"). Esto permite a su organización usar dispositivos de prevención de pérdida de datos (DLP), realizar un posprocesamiento personalizado del correo saliente y enviar correo a socios comerciales a través de redes privadas. Exchange Online también admite la reescritura de direcciones, que enruta el correo saliente a través de una puerta de enlace local que modifica las direcciones. Esta característica le permite ocultar subdominios, hacer que el correo de una organización con dominios múltiples aparezca como de dominio simple o hacer que el correo transmitido por socios aparezca como si hubiera sido enviado desde dentro de su organización. Los administradores configuran el enrutamiento de correo personalizado dentro del Centro de administración de Exchange (EAC).
  
Para obtener más información, vea [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).
  
> [!IMPORTANT]
> Exchange Online puede entregar el correo que fluye dentro y fuera de la organización. 
  
## <a name="secure-messaging-with-a-trusted-partner"></a>Mensajería segura con un partner de confianza

Como cliente de Exchange Online, puede configurar el flujo de correo seguro con un socio de confianza mediante conectores de Office 365. Office 365 permite la comunicación segura mediante Seguridad de la capa de transporte (TLS) y puede crear un conector para forzar el cifrado mediante TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) es un protocolo criptográfico que proporciona seguridad para las comunicaciones por Internet. Con los conectores, puede configurar TLS forzado tanto entrante como saliente mediante el uso de certificados autofirmados o validados por una entidad de certificación (CA). También puede aplicar otras restricciones de seguridad, como especificar nombres de dominio o intervalos de direcciones IP desde las que el socio de su organización envía correo. 
  
Para obtener más información, vea [Set up connectors for secure mail flow with a partner organization](http://technet.microsoft.com/library/1ce4d6a4-41ba-4d1e-9ca9-e826252c1041.aspx).
  
> [!IMPORTANT]
> Es posible que se requiera un certificado validado por la AC. 
  
## <a name="conditional-mail-routing"></a>Enrutamiento de correo condicional

Puede dirigir el correo a sitios específicos con conectores y reglas de transporte. Con el enrutamiento basado en criterios, puede elegir un conector según las condiciones específicas.
  
Para obtener más información, vea [Scenario: Conditional mail routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).
  
## <a name="incoming-mail-safe-list"></a>Lista segura de correo entrante

Puede agregar una dirección IP de un socio de confianza a una lista segura para garantizar que los mensajes que le envíe no pasen por el filtro de correo no deseado. Para ello, puede usar la lista de direcciones IP permitidas del filtro de conexión.
  
Para obtener más información, vea [Configure the connection filter policy](http://technet.microsoft.com/library/6ae78c12-7bbe-44fa-ab13-c3768387d0e3.aspx).
  
## <a name="hybrid-email-routing"></a>Enrutamiento de correo híbrido

Una implementación híbrida proporciona a las organizaciones la posibilidad de ampliar la experiencia variada y el control administrativo que tienen con la organización local existente de Microsoft Exchange a la nube. Con el transporte híbrido, los mensajes enviados entre destinatarios en cualquiera de las organizaciones se autentican, se cifran y se transfieren usando Seguridad de la capa de transporte (TLS), y aparecen como "internos" para los componentes de Exchange, como reglas de transporte, registros en diario y directivas contra correo no deseado. Puede configurar el transporte híbrido con el Asistente de configuración híbrida en Exchange Server.
  
Para obtener más información sobre el enrutamiento de correo en una implementación híbrida, vea [Enrutamiento de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).
  
El [Asistente para implementación de Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) también ofrece pautas detalladas para el aprovisionamiento de las implementaciones híbridas y el transporte de mensajes híbridos. 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a>Espacio de direcciones compartido con control de enrutamiento local (MX Points a local)

El Espacio de direcciones compartido con control de enrutamiento local (Puntos MX a local) es un escenario de enrutamiento de correo de implementación híbrida en el que los buzones son hospedados parcialmente en Exchange Online y parcialmente de manera local, y el flujo de correo entrante y saliente de Internet se enruta a través de Exchange en la organización local. Este escenario también se denomina transporte de correo centralizado. En este escenario, Exchange Online se aprovisiona con EOP y el correo entrante de Internet se enruta hacia su servidor de correo local antes de enrutarse hacia EOP y, finalmente, hacia los buzones hospedados en Exchange Online. Además, el correo que sale de los buzones de Exchange Online se enruta a través de la organización local de Exchange para los mensajes enviados a destinatarios externos. Con esta configuración, puede usar un espacio de nombre de dominio SMTP simple para todos los buzones de su organización de Exchange local y su organización de Exchange Online. 
  
Para obtener más información sobre las opciones de transporte en una implementación híbrida, vea [Opciones de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a>Espacio de direcciones compartido sin Control de enrutamiento local (MX Points a EOP)

El espacio de direcciones compartido sin Control de enrutamiento local (Puntos MX a EOP) es un escenario de enrutamiento de correo híbrido en el que los buzones están hospedados parcialmente en la nube con Exchange Online y parcialmente de manera local, y sus puntos de registros MX en EOP. Este escenario es adecuado cuando usa el servicio de Office 365 para hospedar algunos de los buzones de su organización, y quiere que EOP proteja los buzones de su organización y los de la nube. En este escenario, el correo enviado a los destinatarios de su organización se enruta a través de EOP, donde hay filtros de correo no deseado y filtrado de directivas, antes de llegar a los buzones locales y de la nube. 
  
Para obtener más información sobre las opciones de transporte en una implementación híbrida, vea [Opciones de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkID=271758).
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a>Solución de problemas de una implementación con el Asistente de configuración híbrida

Usar el Asistente de configuración híbrida para configurar una implementación híbrida en Microsoft Exchange Server minimiza en gran medida los problemas potenciales que podrían surgir durante la implementación híbrida. En cambio, existen áreas típicas fuera del alcance del asistente para la configuración híbrida que, si se configuran incorrectamente, pueden presentar problemas en una implementación híbrida. Estas incluyen una configuración de servidor de acceso de cliente adecuada y una instalación y configuración de certificado adecuadas.
  
Para obtener más información sobre cómo solucionar problemas en una implementación con el Asistente para la configuración híbrida, vea [Solucionar problemas de una implementación híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271040).
  
### <a name="managing-a-hybrid-configuration"></a>Administrar una configuración híbrida

Puede modificar una configuración híbrida existente cambiando la configuración del Asistente de configuración híbrida. Los escenarios incluyen desactivar el transporte centralizado o desactivar el transporte de correo seguro.
  
Para obtener más información sobre cómo administrar una configuración de implementación híbrida, vea [Administrar una implementación híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271044).
  
### <a name="hybrid-deployment-requirements"></a>Requisitos de implementación híbrida

Para obtener más información sobre los requisitos de implementación híbrida, vea [Requisitos previos de implementación híbrida](https://go.microsoft.com/fwlink/p/?LinkId=271759).
  
> [!IMPORTANT]
> En algunas configuraciones híbridas, es posible que deba comprar licencias de Exchange Online Protection para los buzones de su organización. 
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características en los planes de Office 365, las opciones independientes y las soluciones locales, vea [Descripción del servicio Exchange Online](exchange-online-service-description.md).
  

