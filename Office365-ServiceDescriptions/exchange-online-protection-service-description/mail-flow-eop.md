---
title: Flujo del correo (EOP)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Para la mayoría de las organizaciones que usan Office 365, se hospedan los buzones de correo y se encargan de flujo de correo. Es la configuración más sencilla y significa que Office 365 administra todos los buzones y el filtrado. Sin embargo, algunas organizaciones tienen una necesidad empresarial mantener todas sus buzones de correo local. Exchange Online Protection (EOP) permite hacer y proporciona correo antivirus y contra correo no deseado de procesamiento en la nube. Para obtener más información y elevación de privilegios de compra, vaya a protección en línea de Exchange.
ms.openlocfilehash: 6c43d308db3c4f62e4c6891cb87263560d9478a7
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: es-ES
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036952"
---
# <a name="mail-floweop"></a><span data-ttu-id="8cf47-107">Flujo del correo (EOP)</span><span class="sxs-lookup"><span data-stu-id="8cf47-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="8cf47-p102">Para la mayoría de las organizaciones que usan Office 365, se hospedan los buzones de correo y se encargan de flujo de correo. Es la configuración más sencilla y significa que Office 365 administra todos los buzones y el filtrado. Sin embargo, algunas organizaciones tienen una necesidad empresarial mantener todas sus buzones de correo local. Exchange Online Protection (EOP) permite hacer y proporciona correo antivirus y contra correo no deseado de procesamiento en la nube. Para obtener más información y elevación de privilegios de compra, vaya a [Protección en línea de Exchange](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span><span class="sxs-lookup"><span data-stu-id="8cf47-p102">For most organizations that use Office 365, we host your mailboxes and take care of mail flow. It's the simplest configuration and means that Office 365 manages all mailboxes and filtering. However, some organizations have a business need to keep all their mailboxes on premises. Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud. For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="8cf47-p103">¿Busca información sobre la administración de dominios o el bloqueo perimetral basado en directorios (DBEB)? Vea [Administración de destinatarios, dominios e información de la compañía](recipient-domain-and-company-management.md). Para más información sobre todas las características de EOP, vea [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="8cf47-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="8cf47-116">Enrutar correo electrónico entre Office 365 y sus servidores de correo electrónico propios</span><span class="sxs-lookup"><span data-stu-id="8cf47-116">Routing email between Office 365 and your own email servers</span></span>
<span data-ttu-id="8cf47-117"><a name="BKMK_outboundmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="8cf47-117"><a name="BKMK_outboundmailrouting"> </a></span></span>

<span data-ttu-id="8cf47-p104">Puede configurar un conector para habilitar el flujo de correo entre Office 365 (incluido Exchange Online o EOP) y un servidor de correo electrónico basado en SMTP como Exchange. Para obtener más información sobre esto, vea [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)?. y [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span><span class="sxs-lookup"><span data-stu-id="8cf47-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? And [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="8cf47-121">Mensajería segura con un socio de confianza</span><span class="sxs-lookup"><span data-stu-id="8cf47-121">Secure messaging with a trusted partner</span></span>
<span data-ttu-id="8cf47-122"><a name="BKMK_securemessagingwithatrustedpartner"> </a></span><span class="sxs-lookup"><span data-stu-id="8cf47-122"></span></span>

<span data-ttu-id="8cf47-p105">Como cliente de EOP, puede configurar el flujo de correo seguro con un socio de confianza mediante conectores de Office 365. Office 365 permite la comunicación segura mediante Seguridad de la capa de transporte (TLS) y puede crear un conector para forzar el cifrado mediante TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) es un protocolo criptográfico que proporciona seguridad para las comunicaciones por Internet. Con los conectores, puede configurar TLS forzado tanto entrante como saliente mediante el uso de certificados autofirmados o validados por una entidad de certificación (CA). También puede aplicar otras restricciones de seguridad, como especificar nombres de dominio o intervalos de direcciones IP desde las que el socio de su organización envía correo.</span><span class="sxs-lookup"><span data-stu-id="8cf47-p105">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="8cf47-128">Para más información, vea [Configurar conectores para flujo de correo seguro con una organización asociada](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span><span class="sxs-lookup"><span data-stu-id="8cf47-128">For more information, see [Set up connectors for secure mail flow with a partner organization](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="8cf47-129">Incluir en una lista segura la dirección IP de un socio</span><span class="sxs-lookup"><span data-stu-id="8cf47-129">Safe listing a partner's IP address</span></span>
<span data-ttu-id="8cf47-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span><span class="sxs-lookup"><span data-stu-id="8cf47-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span></span>

<span data-ttu-id="8cf47-p106">Puede agregar la dirección IP de un socio de confianza a una lista segura para garantizar que los mensajes procedentes de este socio no se someterán al filtrado contra correo no deseado. Para ello, use la lista de direcciones IP permitidas de filtro de conexión. Para obtener más información, vea [Configurar la directiva de filtro de conexión](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span><span class="sxs-lookup"><span data-stu-id="8cf47-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="8cf47-134">Enrutamiento de correo condicional</span><span class="sxs-lookup"><span data-stu-id="8cf47-134">Conditional mail routing</span></span>
<span data-ttu-id="8cf47-135"><a name="BKMK_conditionalmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="8cf47-135"></span></span>

<span data-ttu-id="8cf47-p107">Puede configurar un conector con una regla de transporte que enrute el correo a un sitio concreto según ciertas condiciones. Para obtener más información, vea [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span><span class="sxs-lookup"><span data-stu-id="8cf47-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="8cf47-138">Enrutamiento de correo híbrido</span><span class="sxs-lookup"><span data-stu-id="8cf47-138">Hybrid mail routing</span></span>
<span data-ttu-id="8cf47-139"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="8cf47-139"></span></span>

<span data-ttu-id="8cf47-p108">Híbrido significa que una parte de los buzones se hospeda de manera local y otra parte en la nube (Exchange Online). Puede pasar de una implementación independiente (local) a una híbrida.</span><span class="sxs-lookup"><span data-stu-id="8cf47-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="8cf47-p109">Si tiene una implementación híbrida, puede proteger los buzones locales y los de la nube con EOP. Los buzones locales que se encuentran protegidos con EOP requieren licencias independientes. Para obtener más información sobre el enrutamiento de correo en una implementación híbrida, vea [Enrutamiento de transporte en las implementaciones híbridas de Exchange](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span><span class="sxs-lookup"><span data-stu-id="8cf47-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="8cf47-145">El [Asistente para implementación de Microsoft Exchange Server](https://go.microsoft.com/fwlink/p/?LinkId=287036) también ofrece pautas detalladas para el aprovisionamiento de las implementaciones híbridas y el transporte de mensajes híbridos.</span><span class="sxs-lookup"><span data-stu-id="8cf47-145">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="8cf47-146">Disponibilidad de características</span><span class="sxs-lookup"><span data-stu-id="8cf47-146">Feature Availability</span></span>
<span data-ttu-id="8cf47-147"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="8cf47-147"></span></span>

<span data-ttu-id="8cf47-148">Para ver la disponibilidad de características entre planes de Office 365, las opciones independientes y las soluciones locales, consulte [Descripción de servicio Protección en línea de Exchange](exchange-online-protection-service-description.md).</span><span class="sxs-lookup"><span data-stu-id="8cf47-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

