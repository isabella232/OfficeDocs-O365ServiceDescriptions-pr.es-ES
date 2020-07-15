---
title: Interoperabilidad, conectividad y compatibilidad
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 5308770ff7fc6ab6c44f27293ff89ebbffa6e72f
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/14/2020
ms.locfileid: "45132754"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilidad, conectividad y compatibilidad

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilidad con otros productos de Microsoft

### <a name="skype-for-business-online"></a>Skype Empresarial Online

En el caso de clientes que hayan implementado Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 en el nivel local, Microsoft Office Communicator podrá conectarse a Microsoft Exchange Online a través de Exchange Web Services para tener acceso a los mensajes "fuera de la oficina" y a los datos de calendarios.
  
Lync Server 2010 y Lync Server 2013 local pueden interoperar con Exchange Online de dos formas adicionales:
  
- Interoperabilidad de presencia y mensajería instantánea en Outlook en la web
    
- Interoperabilidad de correo de voz
    
For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Para los clientes que hayan implementado Microsoft SharePoint Server o SharePoint Online como parte de un plan de suscripción, SharePoint puede conectarse a Exchange Online para obtener servicios integrados.
  
Para obtener más información sobre cómo conectar SharePoint a Exchange Online, vea [Usar SharePoint Online en un dominio personalizado con otros servicios](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Características de la conectividad externa

Exchange Online ofrece las siguientes características para la conexión con aplicaciones y dispositivos externos:
  
- **Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development. 
    
- **Como servidor relé SMTP** Exchange Online se puede configurar como servicio de entrega SMTP para retransmitir los mensajes de correo electrónico enviados desde puertas de enlace de fax, hardware en red y aplicaciones personalizadas. 
    
### <a name="exchange-web-services"></a>Servicios web de Exchange

Exchange Web Services (EWS) es la API de desarrollo recomendada para Exchange Server y Exchange Online. Con EWS o su API administrada, los administradores pueden acceder a los datos almacenados con Exchange Online desde aplicaciones que se ejecutan localmente, desde Azure o desde otros servicios hospedados. EWS permite a los administradores realizar acciones especializadas, como consultar el contenido de un buzón, publicar un evento de calendario, crear una tarea o desencadenar una acción específica en función del contenido de un mensaje de correo electrónico. Exchange Online habilita la funcionalidad de EWS concediendo permisos de aplicaciones a las cuentas de clientes. Estos permisos permiten que la aplicación de cliente acceda al buzón de la aplicación y añada contenido. La suplantación de Exchange es uno de los métodos usados para conceder permisos de aplicación. Para obtener información detallada sobre cómo usar Exchange Web Services con Exchange Online, consulte los artículos técnicos en el Centro de desarrolladores de Exchange Online.
  
### <a name="smtp-relay"></a>Relé SMTP

Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).
  

