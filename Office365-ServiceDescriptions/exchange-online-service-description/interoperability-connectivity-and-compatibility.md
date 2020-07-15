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
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="483b8-102">Interoperabilidad, conectividad y compatibilidad</span><span class="sxs-lookup"><span data-stu-id="483b8-102">Interoperability, connectivity, and compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="483b8-103">Interoperabilidad con otros productos de Microsoft</span><span class="sxs-lookup"><span data-stu-id="483b8-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="483b8-104">Skype Empresarial Online</span><span class="sxs-lookup"><span data-stu-id="483b8-104">Skype for Business Online</span></span>

<span data-ttu-id="483b8-105">En el caso de clientes que hayan implementado Microsoft Lync Server 2010, Lync Server 2013 o Microsoft Office Communications Server 2007 R2 en el nivel local, Microsoft Office Communicator podrá conectarse a Microsoft Exchange Online a través de Exchange Web Services para tener acceso a los mensajes "fuera de la oficina" y a los datos de calendarios.</span><span class="sxs-lookup"><span data-stu-id="483b8-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="483b8-106">Lync Server 2010 y Lync Server 2013 local pueden interoperar con Exchange Online de dos formas adicionales:</span><span class="sxs-lookup"><span data-stu-id="483b8-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="483b8-107">Interoperabilidad de presencia y mensajería instantánea en Outlook en la web</span><span class="sxs-lookup"><span data-stu-id="483b8-107">IM and presence interoperability in Outlook on the web</span></span>
    
- <span data-ttu-id="483b8-108">Interoperabilidad de correo de voz</span><span class="sxs-lookup"><span data-stu-id="483b8-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="483b8-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span><span class="sxs-lookup"><span data-stu-id="483b8-109">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804).</span></span> <span data-ttu-id="483b8-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span><span class="sxs-lookup"><span data-stu-id="483b8-110">For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="483b8-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="483b8-111">Microsoft SharePoint</span></span>

<span data-ttu-id="483b8-112">Para los clientes que hayan implementado Microsoft SharePoint Server o SharePoint Online como parte de un plan de suscripción, SharePoint puede conectarse a Exchange Online para obtener servicios integrados.</span><span class="sxs-lookup"><span data-stu-id="483b8-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="483b8-113">Para obtener más información sobre cómo conectar SharePoint a Exchange Online, vea [Usar SharePoint Online en un dominio personalizado con otros servicios](https://go.microsoft.com/fwlink/?LinkId=271805).</span><span class="sxs-lookup"><span data-stu-id="483b8-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="483b8-114">Características de la conectividad externa</span><span class="sxs-lookup"><span data-stu-id="483b8-114">Features for external connectivity</span></span>

<span data-ttu-id="483b8-115">Exchange Online ofrece las siguientes características para la conexión con aplicaciones y dispositivos externos:</span><span class="sxs-lookup"><span data-stu-id="483b8-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="483b8-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span><span class="sxs-lookup"><span data-stu-id="483b8-116">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4.</span></span> <span data-ttu-id="483b8-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span><span class="sxs-lookup"><span data-stu-id="483b8-117">Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="483b8-118">**Como servidor relé SMTP** Exchange Online se puede configurar como servicio de entrega SMTP para retransmitir los mensajes de correo electrónico enviados desde puertas de enlace de fax, hardware en red y aplicaciones personalizadas.</span><span class="sxs-lookup"><span data-stu-id="483b8-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="483b8-119">Servicios web de Exchange</span><span class="sxs-lookup"><span data-stu-id="483b8-119">Exchange Web Services</span></span>

<span data-ttu-id="483b8-120">Exchange Web Services (EWS) es la API de desarrollo recomendada para Exchange Server y Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="483b8-120">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online.</span></span> <span data-ttu-id="483b8-121">Con EWS o su API administrada, los administradores pueden acceder a los datos almacenados con Exchange Online desde aplicaciones que se ejecutan localmente, desde Azure o desde otros servicios hospedados.</span><span class="sxs-lookup"><span data-stu-id="483b8-121">Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services.</span></span> <span data-ttu-id="483b8-122">EWS permite a los administradores realizar acciones especializadas, como consultar el contenido de un buzón, publicar un evento de calendario, crear una tarea o desencadenar una acción específica en función del contenido de un mensaje de correo electrónico.</span><span class="sxs-lookup"><span data-stu-id="483b8-122">EWS lets administrators perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message.</span></span> <span data-ttu-id="483b8-123">Exchange Online habilita la funcionalidad de EWS concediendo permisos de aplicaciones a las cuentas de clientes.</span><span class="sxs-lookup"><span data-stu-id="483b8-123">Exchange Online enables EWS functionality by granting application permissions to customer accounts.</span></span> <span data-ttu-id="483b8-124">Estos permisos permiten que la aplicación de cliente acceda al buzón de la aplicación y añada contenido.</span><span class="sxs-lookup"><span data-stu-id="483b8-124">These permissions allow the customer application to access the application mailbox and add content.</span></span> <span data-ttu-id="483b8-125">La suplantación de Exchange es uno de los métodos usados para conceder permisos de aplicación.</span><span class="sxs-lookup"><span data-stu-id="483b8-125">Exchange Impersonation is one method used to grant application permissions.</span></span> <span data-ttu-id="483b8-126">Para obtener información detallada sobre cómo usar Exchange Web Services con Exchange Online, consulte los artículos técnicos en el Centro de desarrolladores de Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="483b8-126">For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="483b8-127">Relé SMTP</span><span class="sxs-lookup"><span data-stu-id="483b8-127">SMTP relay</span></span>

<span data-ttu-id="483b8-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span><span class="sxs-lookup"><span data-stu-id="483b8-128">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> <span data-ttu-id="483b8-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span><span class="sxs-lookup"><span data-stu-id="483b8-129">For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system.</span></span> <span data-ttu-id="483b8-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span><span class="sxs-lookup"><span data-stu-id="483b8-130">The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="483b8-131">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="483b8-131">Feature availability</span></span>

<span data-ttu-id="483b8-132">Para ver la disponibilidad de características entre planes, las opciones independientes y las soluciones locales, consulte [Exchange Online Service Description](exchange-online-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="483b8-132">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online service description](exchange-online-service-description.md).</span></span>
  

