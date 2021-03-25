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
ms.openlocfilehash: 21df7d4747ae0b92f21a9da56c0d4bc9ff96ccaf
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173325"
---
# <a name="interoperability-connectivity-and-compatibility"></a>Interoperabilidad, conectividad y compatibilidad

## <a name="interoperability-with-other-microsoft-products"></a>Interoperabilidad con otros productos de Microsoft

### <a name="skype-for-business-online"></a>Skype Empresarial Online

En el caso de clientes que hayan implementado Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 en el nivel local, Microsoft Office Communicator podrá conectarse a Microsoft Exchange Online a través de Exchange Web Services para tener acceso a los mensajes "fuera de la oficina" y a los datos de calendarios.
  
Lync Server 2010 y Lync Server 2013 local pueden interoperar con Exchange Online de dos formas adicionales:
  
- Interoperabilidad de mensajería instantánea e presencia en Outlook en la web
    
- Interoperabilidad de correo de voz
    
Para obtener más información sobre la configuración de Skype Empresarial Server 2015 con Exchange Online, vea [Configuración de la integración local de Skype Empresarial Server 2015 con Exchange Online](/skypeforbusiness/deploy/integrate-with-exchange-server/outlook-web-app). Para obtener más información sobre las opciones de configuración híbridas, vea [Configuraciones híbridas admitidas en Skype Empresarial Server 2015](/skypeforbusiness/skype-for-business-hybrid-solutions/integration-with-exchange-and-sharepoint).
  
### <a name="microsoft-sharepoint"></a>Microsoft SharePoint

Para los clientes que han implementado Microsoft SharePoint Server o SharePoint Online como parte de un plan de suscripción, SharePoint puede conectarse a Exchange Online para servicios integrados.
  
Para obtener más información sobre cómo conectar SharePoint a Exchange Online, vea [Usar SharePoint Online en un dominio personalizado con otros servicios](https://go.microsoft.com/fwlink/?LinkId=271805).
  
## <a name="features-for-external-connectivity"></a>Características de la conectividad externa

Exchange Online ofrece las siguientes características para la conexión con aplicaciones y dispositivos externos:
  
- **A través de protocolos de mensajería como MAPI sobre HTTP, SMTP, POP3, IMAP4 o los servicios Web Exchange** Las aplicaciones externas que se ejecutan en implementaciones locales, en Azure o en otros servicios hospedados, pueden obtener acceso a los datos que se han almacenado con Exchange Online usando protocolos de mensajería como MAPI sobre HTTP, SMTP, POP3 e IMAPv4. Se recomiendan Exchange Web Services o la API administrada de Exchange Web Services para el desarrollo de aplicaciones. 
    
- **Como servidor relé SMTP** Exchange Online se puede configurar como servicio de entrega SMTP para retransmitir los mensajes de correo electrónico enviados desde puertas de enlace de fax, hardware en red y aplicaciones personalizadas. 
    
### <a name="exchange-web-services"></a>Servicios web de Exchange

Exchange Web Services (EWS) es la API de desarrollo recomendada para Exchange Server y Exchange Online. Con EWS o su API administrada, los administradores pueden acceder a los datos almacenados con Exchange Online desde aplicaciones que se ejecutan localmente, desde Azure o desde otros servicios hospedados. EWS permite a los administradores realizar acciones especializadas, como consultar el contenido de un buzón, publicar un evento de calendario, crear una tarea o desencadenar una acción específica en función del contenido de un mensaje de correo electrónico. Exchange Online habilita la funcionalidad de EWS concediendo permisos de aplicaciones a las cuentas de clientes. Estos permisos permiten que la aplicación de cliente acceda al buzón de la aplicación y añada contenido. La suplantación de Exchange es uno de los métodos usados para conceder permisos de aplicación. Para obtener información detallada sobre cómo usar Exchange Web Services con Exchange Online, consulte los artículos técnicos en el Centro de desarrolladores de Exchange Online.
  
### <a name="smtp-relay"></a>Relé SMTP

Exchange Online se puede usar como servicio de entrega SMTP para transmitir los mensajes de correo electrónico desde puertas de enlace de fax, hardware en red y aplicaciones personalizadas. Por ejemplo, si una aplicación de línea de negocio envía alertas de correo electrónico a los usuarios, se podrá configurar para que utilice Exchange Online como sistema de entrega de correo. La aplicación o servicio deben autenticarse con el nombre de usuario y la contraseña de un buzón de correo válido y con licencia de Exchange Online y, seguidamente, conectarse mediante un TLS.
  
## <a name="feature-availability"></a>Disponibilidad de características

Para ver la disponibilidad de características entre planes, opciones independientes y soluciones locales, vea [Descripción del servicio de Exchange Online](exchange-online-service-description.md).
