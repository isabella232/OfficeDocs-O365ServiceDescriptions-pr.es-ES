---
title: Interoperabilidad, conectividad y compatibilidad
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776801"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="a30eb-102">Interoperabilidad, conectividad y compatibilidad</span><span class="sxs-lookup"><span data-stu-id="a30eb-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="a30eb-103">Interoperabilidad con otros productos de Microsoft</span><span class="sxs-lookup"><span data-stu-id="a30eb-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="a30eb-104">Skype Empresarial Online</span><span class="sxs-lookup"><span data-stu-id="a30eb-104">Skype for Business Online</span></span>

<span data-ttu-id="a30eb-105">En el caso de clientes que hayan implementado Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 en el nivel local, Microsoft Office Communicator podrá conectarse a Microsoft Exchange Online a través de Exchange Web Services para tener acceso a los mensajes "fuera de la oficina" y a los datos de calendarios.</span><span class="sxs-lookup"><span data-stu-id="a30eb-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="a30eb-106">Lync Server 2010 y Lync Server 2013 local pueden interoperar con Exchange Online de dos formas adicionales:</span><span class="sxs-lookup"><span data-stu-id="a30eb-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="a30eb-107">MI y presencia de interoperabilidad en Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="a30eb-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="a30eb-108">Interoperabilidad de correo de voz</span><span class="sxs-lookup"><span data-stu-id="a30eb-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="a30eb-p101">Para obtener más información sobre la configuración de Skype Empresarial Server 2015 con Exchange Online, vea [Configuración de la integración local de Skype Empresarial Server 2015 con Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). Para obtener más información sobre las opciones de configuración híbridas, vea [Configuraciones híbridas admitidas en Skype Empresarial Server 2015](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="a30eb-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="a30eb-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="a30eb-111">Microsoft SharePoint</span></span>

<span data-ttu-id="a30eb-112">En el caso de clientes que hayan implementado Microsoft SharePoint Server o SharePoint Online como parte de un plan de suscripción a Office 365, SharePoint podrá conectarse a Exchange Online para los servicios integrados.</span><span class="sxs-lookup"><span data-stu-id="a30eb-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="a30eb-113">Para obtener más información sobre cómo conectar SharePoint a Exchange Online, vea [Usar SharePoint Online en un dominio personalizado con otros servicios](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="a30eb-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="a30eb-114">Características de la conectividad externa</span><span class="sxs-lookup"><span data-stu-id="a30eb-114">Features for external connectivity</span></span>

<span data-ttu-id="a30eb-115">Exchange Online ofrece las siguientes características para la conexión con aplicaciones y dispositivos externos:</span><span class="sxs-lookup"><span data-stu-id="a30eb-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="a30eb-p102">**A través de protocolos de mensajería como MAPI sobre HTTP, SMTP, POP3, IMAP4 o los servicios Web Exchange** Las aplicaciones externas que se ejecutan en implementaciones locales, en Azure o en otros servicios hospedados, pueden obtener acceso a los datos que se han almacenado con Exchange Online usando protocolos de mensajería como MAPI sobre HTTP, SMTP, POP3 e IMAPv4. Se recomiendan Exchange Web Services o la API administrada de Exchange Web Services para el desarrollo de aplicaciones.</span><span class="sxs-lookup"><span data-stu-id="a30eb-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="a30eb-118">**Como servidor relé SMTP** Exchange Online se puede configurar como servicio de entrega SMTP para retransmitir los mensajes de correo electrónico enviados desde puertas de enlace de fax, hardware en red y aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="a30eb-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="a30eb-119">Servicios web de Exchange</span><span class="sxs-lookup"><span data-stu-id="a30eb-119">Exchange Web Services</span></span>

<span data-ttu-id="a30eb-p103">Exchange Web Services (EWS) es la API de desarrollo recomendada para Exchange Server y Exchange Online. Con EWS o su API administrada, los administradores pueden acceder a los datos almacenados con Exchange Online desde aplicaciones que se ejecutan localmente, desde Azure o desde otros servicios hospedados. EWS permite que los administradores realicen acciones especializadas, como por ejemplo realizar consultas sobre el contenido de un buzón, colgar un evento en el calendario, crear una tarea o activar una acción específica en función del contenido de un mensaje de correo electrónico. Exchange Online habilita la funcionalidad de EWS concediendo permisos de aplicaciones a las cuentas de clientes. Estos permisos permiten que la aplicación de cliente acceda al buzón de la aplicación y añada contenido. La suplantación de Exchange es uno de los métodos usados para conceder permisos de aplicación. Para obtener información detallada sobre cómo usar Exchange Web Services con Exchange Online, consulte los artículos técnicos en el Centro de desarrolladores de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a30eb-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="a30eb-127">Relé SMTP</span><span class="sxs-lookup"><span data-stu-id="a30eb-127">SMTP relay</span></span>

<span data-ttu-id="a30eb-p104">Exchange Online se puede usar como servicio de entrega SMTP para transmitir los mensajes de correo electrónico desde puertas de enlace de fax, hardware en red y aplicaciones personalizadas. Por ejemplo, si una aplicación de línea de negocio envía alertas de correo electrónico a los usuarios, se podrá configurar para que utilice Exchange Online como sistema de entrega de correo. La aplicación o servicio deben autenticarse con el nombre de usuario y la contraseña de un buzón de correo válido y con licencia de Exchange Online y, seguidamente, conectarse mediante un TLS.</span><span class="sxs-lookup"><span data-stu-id="a30eb-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="a30eb-131">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="a30eb-131">Feature Availability</span></span>

<span data-ttu-id="a30eb-132">Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción del servicio Exchange Online](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="a30eb-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

